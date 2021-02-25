```bash
$ sudo su
root# touch scscript
root# nano scscript
```

```bash
echo "WELCOME ALL TO STORAGE SCRIPT CREATION AND TESTING"
sleep 2
echo "FILEDISK LISTING"
fdisk -l
sleep 3
echo "FILE DISK operations:::"
fdisk /dev/sda
sleep 3
echo "ElASTIC BLOCK LISTING"
lsblk
```

> Ctrl+x , press Enter

```bash
root# sh scscript
```

## aws ebs

```bash
# ls
# mount /dev/xvdf joy/
# df
# lsblk
# df
# lsblk
# df
# history
# mkfs
# lsblk
# mkfs -t ext3 /dev/xvdg
# df-kh
# df -kh
# mkdir joy1
# mount /dev/xvdg/joy1
# mount /dev/xvdg/ joy1
# mount /dev/xvdg joy1/
# df
# df -kh
# history
# 1 apt update
# umount joy1/
# df
# umount joy/
# df
# lsblk
# fdisk -l
# history
# umkdir joy
# history
```
