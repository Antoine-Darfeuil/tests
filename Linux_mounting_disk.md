






## MOUNTING A DISK

### Find/list all hard drive partitions

Use `lsblk - list block devices`
> $ sudo lsblk 

> $ sudo lsblk -o NAME,FSTYPE,SIZE,MOUNTPOINT,LABEL

*REM: Can also use *`fdisk - manipulate disk partition table`* to see hard drive*

>**Links :** [askubutu : how-do-i-view-all-available-hdds-partitions](https://askubuntu.com/questions/182446/how-do-i-view-all-available-hdds-partitions)


### Access Disk from inside liveCD

> $ sudo mkdir /media/odlhd

> $ sudo mount /dev/sda1 /media/oldhd

*You know have access to your hard drive from liveCD*


When finished :

> $ sudo umount /media/oldhd


## PARTITIONING DISK - DUAL BOOT UBUNTU14/UBUNTU16

**Etape 1 :** Free some space
Use GParted from liveCD
* Right-click on *swap* partition & do *swap off*
* Right-click on hard drive : *Resize/Move* -> resize partition to unallocate disk space. 
* Free space following (MiB)

>* link : [HowtoGeek : resize Ubuntu Partition](https://www.howtogeek.com/114503/how-to-resize-your-ubuntu-partitions/)

**Etape 2:** Install Ubuntu
Use Ubuntu 16 Installer
-> install Ubuntu 16 alongside Ubuntu 14 selected






## Other Linux Command
> $ id - print real and effective user and group IDs

>* link : [askubuntu : external-hard-disk-read-only](https://askubuntu.com/questions/333287/external-hard-disk-read-only)
