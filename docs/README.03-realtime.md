# Real-Time Linux
NVIDIA L4T for Jetson TX2 release contains Linux 4.4.48 kernel  
[patch-4.4.38-rt49.patch.gz](https://www.kernel.org/pub/linux/kernel/projects/rt/4.4/older/) from 13-Dec-2016 is an exact version match  

```shell
$ cd $HOME/nvidia/kernel/kernel-4.4
$ for i in rt-patches/*.patch; do echo $i; done
$ for i in rt-patches/*.patch; do patch -p1 < $i; done
```