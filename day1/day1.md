## Slides

https://docs.google.com/presentation/d/12iQDnrxCDVuqIEtOvDN2d4XZM_08dz7mDZxddd8ieA4/edit#slide=id.g25c49b3e5b8_1_152


## Commands learned


Print system information

```$ uname -a
kernel-name nodename kernel-release kernel-version machine processor hardware-platform operating-system

Linux myhost.example.org 5.9.16-200.fc33.x86_64 #1 SMP Mon Dec 21 14:08:22 UTC 2020 x86_64 x86_64 x86_64 GNU/Linux
```

List drivers used by Kernel
```
$ lsmod

```

Info on Drivers
```
$ modinfo <drivername>
$ modinfo ena # Example
```


Watch system calls of process
```
$ strace <process>
$ strace ls -l # Example
```

List CPU

```
$ lscpu
$ cat /proc/cpuinfo

```

Memory Information

```
$ free -m # MB Notation
$ free -g # GB Notation
$ cat /proc/meminfo
```

List Disks
```
$ fdisk -l 
```
Show summary information of hardware
```
$ inxi -Fxz  
$ hwinfo --short 
$ lshw -short
$ lspci -vvv
```

