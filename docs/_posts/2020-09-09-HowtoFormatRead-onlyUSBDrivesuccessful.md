# How to Format Read-only USB Drive successful

Use "Diskpart" command

on windows dos prompt
#DiskPpart
    ## list disk
Diskpart > list disk
    ## select disk in
Diskpart > select disk. [1,2..]
    ## attributes disk
Diskpart > attribute disk
    ## modify Read-only state from yes to "no
Diskpart > attributes disk clear readonly
