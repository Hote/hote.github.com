# uber go : automaxprocs
今天早上看到同事分享說採用automaxprocs,RPS提升了20%，然後google了一下，automaxprocs主要就是正確的幫忙調適docker內可用的cpu數量

例如
```
#kubectl get pod testpod -n default -o=jsonpath='{.spec.containers[0].resources}'
#map[limits:map[cpu:500m memory:128Mi] requests:map[cpu:100m memory:128Mi]]%
```
一般在container go routine會遇到的問題就在於container 中會拿到host node上面的cpu 核心數, 這就會導致golang 服務預設會拿host node上面的cpu核心數來調適 runtime.GOMAXPROCS(), 導致Ｐ數量元(註一）大於可用的CPU核心數，所以效能就會受影響
automaxprocs 能夠辯視真正的核心數，合理的設置go processor避免這個問題

lscpu |head -n 10

```
[ec2-user@ip-10-102-140-123 ~]$ lscpu |head -n 10
Architecture:        x86_64
CPU op-mode(s):      32-bit, 64-bit
Byte Order:          Little Endian
CPU(s):              4
On-line CPU(s) list: 0-3
Thread(s) per core:  2
Core(s) per socket:  2
Socket(s):           1
NUMA node(s):        1
Vendor ID:           GenuineIntel
```


仔細觀看automaxprocs 的source code就可以發現
automaxprocs/automaxprocs.go
核心函數就是maxprocs.Set() 他會正確的從cgroup種獲取設置的cpu quota然後轉換合適的GOMAXPROCS , iruntime.CPUQuotaToGOMAXPROCS()
parse 的位置 /proc/$pid/cgroup
```
package automaxprocs // import "go.uber.org/automaxprocs"

import (
	"log"

	"go.uber.org/automaxprocs/maxprocs"
)

func init() {
	maxprocs.Set(maxprocs.Logger(log.Printf))
}
```

註一：
GO scheduler中
    * Ｇ：goroutine
    * P : Processor(Logical)
    * M : machine
