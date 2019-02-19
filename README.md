# opendaylight build

run file as sudo

## To login to odl

http://'odl-ip':8181/index.html
  * username: admin
  * password: admin
  
## To connect ODL to the OVS
ovs-vsctl set-controller br0 tcp:'odl-ip':6633
