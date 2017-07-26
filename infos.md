






## M O U N T I N G A   D I S K

**Find/list all hard drive partitions**

Use `lsblk - list block devices`
> $ sudo lsblk 

> $ sudo lsblk -o NAME,FSTYPE,SIZE,MOUNTPOINT,LABEL

*REM: Can also use *`fdisk - manipulate disk partition table`* to see hard drive*


Links :
* [askubutu : how-do-i-view-all-available-hdds-partitions](https://askubuntu.com/questions/182446/how-do-i-view-all-available-hdds-partitions)


**Access Disk from inside liveCD**)

> $ sudo mkdir /media/odlhd

> $ sudo mount /dev/sda1 /media/oldhd

*You know have access to your hard drive from liveCD*


When finished :

> $ sudo umount /media/oldhd


## PARTITIONING DISK - DUAL BOOT UBUNTU14/UBUNTU16

*Usefull links :*

[Dual boot Ubuntu 14.04 + 16.04 setup?](Dual boot Ubuntu 14.04 + 16.04 setup?)

**Etape 1 : **
Resize partition to unallocate disk space : use GParted from liveCD. 

REM: 
Free space 104.6GB
USED space 47.4GB

### Other Linux Command
> $ id - print real and effective user and group IDs

[askubuntu : external-hard-disk-read-only](https://askubuntu.com/questions/333287/external-hard-disk-read-only)
