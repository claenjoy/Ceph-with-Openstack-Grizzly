Ceph-with-Openstack-Grizzly
===========================

Ceph with Openstack Grizzly





Guide-temp

multi-node Openstack grizzly , ubuntu 12.04 64bit

if you have single disk , reccomend to separate OS from the data so use the LVM tool to separate single LV-root ,

                          |---LV-swap 16 gb
example : from VG-machine |---LV-root 500gb ext4

              |---LV-swap 16gb
to VG-machine |---LV-root 30gb ext4
              |---LV-data 470gb xfs
