```
$ sudo su
root# touch scscript
root# nano scscript
```

```nano
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

```
root# sh scscript
```
