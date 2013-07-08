This repository contains all files needed to build a Gentoo initramfs image that will handle image resizing. This is useful in KVM-based cloud environments where the image is not automatically resized to account for the disk space of the chosen flavor.

To build the image, do something like:

```bash
$ genkernel --initramfs-overlay=/root/initramfs/overlay --linuxrc=/root/initramfs/linuxrc --install initramfs"
```
