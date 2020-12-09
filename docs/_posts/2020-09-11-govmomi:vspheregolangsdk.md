# govmomi : vsphere golang sdk
＃安裝
```
go get -u github.com/vmware/govmomi
```

# 裡面除了有SDK外，還有三個額外的command line tools: 
    #govc
    #vcsim
    #toolbox
    
#登錄：主要有兩種方式，
    
1.一個是透過environment varaible
    * GOVMOMI_URL: vshpere ip
    * GOVMOMI_USERNAME: 登入名稱
    * GOVMOMI_PASSWORD: 登入密碼
    * GOVMOMI_INSECURE: 是用驗證certificate
2.
    *透過connection string方式
    https://user:password@IP/sdk
    
# 工具介紹： govc
編譯govc
```
go build github.com/vmware/govmomi/govc/
```
    