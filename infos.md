M O U N T I N G   A   D I S K

**Find/list all hard drive partitions**

Use `lsblk - list block devices`
> $ sudo lsblk 

> $ sudo lsblk -o NAME,FSTYPE,SIZE,MOUNTPOINT,LABEL


*REM: Can also use `fdisk - manipulate disk partition table` to see hard drive*




**Access Disk from inside liveCD**

> $ sudo mkdir /media/odlhd

> $ sudo mount /dev/sda1 /media/oldhd

*You know have access to your hard drive from liveCD*
