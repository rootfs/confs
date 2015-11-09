# confs
multiple confs

# [ganesha](./ganesha): sample nfs-ganesha conf using VFS FASL;
On Fedora 21, 

```console
yum install -y nfs-ganesah
git clone https://github.com/rootfs/confs
cd confs/ganesha
cp ganesha.nfsd.conf /etc/
systemctl enable nfs-ganesha && systemctl start rpcbind && systemctl start nfs-ganesha
```
