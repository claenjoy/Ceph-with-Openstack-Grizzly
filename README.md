Ceph-with-Openstack-Grizzly
===========================

Ceph with Openstack Grizzly





Guide-temp

multi-node Openstack grizzly , ubuntu 12.04 64bit

if you have single disk , recommend to separate OS from the data .
 
example from:

                  |sda1 /boot
    VG-machine--->|sda2 / LV-root 500gb ext4
        
to 

                  |sda1 /boot
    VG-machine--->|sda2 LV-root 30gb ext4
                  |sdb /data 470gb xfs

