```
systemctl start nfs
edit /etc/exports
/dir 192.168.122.0/24(rw)
exportfs -r
showmount -e ip
mount ip:/sharedir z:
```
