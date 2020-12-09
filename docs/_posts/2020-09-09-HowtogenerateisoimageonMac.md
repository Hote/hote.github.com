# How to generate iso image on Mac

1. Use disk utilty to generate cdr file format
2. disk format: select DVD/CD master

![](media/15996390758332/15996392748122.jpg)

1. It will geneate a file extension .cdr
2. hdiutil makehybrid -iso -joliet -o destination.iso source.cdr

3. hdiutil convert source.cdr -format UDTO -o destination.iso