#Instructions:

##1- Clone repo
 
  git clone https://github.com/qcrivera/openstack-neutron-lab.git
  
##2- Create networking

```
virsh net-define os-vanila-management-net.xml
virsh net-start os-vanila-management-net.xml
virsh net-autostart os-vanila-management-net.xml

virsh net-define os-vanilla-external-net.xml
virsh net-start os-vanilla-external-net.xml
virsh net-autostart os-vanilla-external-net.xml

```

##3- Create your vms
  
###Download the VMs for the LAB

#### Neutron with Linux bridge:
Compute: https://objects-east.cloud.ca/v1/5ef827605f884961b94881e928e7a250/crivera/newton-compute-lx-br.tgz
Controller: https://objects-east.cloud.ca/v1/5ef827605f884961b94881e928e7a250/crivera/newton-controller-lx-br.tgz

#### Neutron with OVS+DVR:



Presentation Openstack Days Canada 2016
https://objects-east.cloud.ca/v1/5ef827605f884961b94881e928e7a250/crivera/AYCE%20Neutron.pdf




