NFS server deb packages
============
These files are required for serving NFS volumes on the Ubuntu Xenial Stemcell.

relies on the `nfs-debs` package for basic NFS dependencies that are no longer in the
root stemcell as they were in Trusty,  and adds `nfs-kernel-server`.

They can be downloaded from the following locations:

| Filename | Download URL |
| -------- | ------------ |
| nfs-kernel-server_1.2.8-9ubuntu12.1_amd64.deb | http://mirrors.edge.kernel.org/ubuntu/pool/main/n/nfs-utils/nfs-kernel-server_1.2.8-9ubuntu12.1_amd64.deb |

