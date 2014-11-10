# How start a vm with rbd disk via libvirt
# reference: http://ceph.com/docs/master/rbd/libvirt/
* 0.configure ceph repo and install ceph.

* 1.create ceph user and configure certain read/write access to the pools by ceph auth.

* 2.configure libvirt for cephx authorization

* 3.start vm with virsh create start.xml

* 4.add an extra rbd disk through virsh device-attach <domain> datadisk.xml
