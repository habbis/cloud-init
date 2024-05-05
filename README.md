# cloud-init
cloud-init for multiple os.


## Generate cloud-init iso

First install  genisoimage.

To generate.

```
genisoimage -output cloud-init.iso -V cidata -r -J meta-data user-data network-config
```


