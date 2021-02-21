---
layout: post
title: Linux zfs configuarion
---
![My helpful screenshot](/public/assets/file_Fabien_Barral.jpg)
For each pool you want automatically mounted by the zfs daemon execute:
```console
$zpool set cachefile=/etc/zfs/zpool.cache <poolname>
```
Enable the service so it is automatically started at boot time:
```console
$systemctl enable zfs.target
```
To manually start the daemon:
```console
$systemctl start zfs.target
```
Note: If zfs-mount.service fails on boot due to running before the kernel module is loaded, you may have to manually enable the zfs-import-cache.service.
```console
$systemctl enable zfs-import-cache.service
```