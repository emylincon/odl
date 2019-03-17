# opendaylight build

run file as sudo

## To login to odl

http://'odl-ip':8181/index.html
  * username: admin
  * password: admin
  
## To connect ODL to the OVS
ovs-vsctl set-controller br0 tcp:'odl-ip':6633

```
sudo update-alternatives --config java  
#/usr/lib/jvm/java-8-openjdk-i386/jre/bin/java  
sudo nano /etc/environment  
# to in end of file  
JAVA_HOME="/usr/lib/jvm/java-8-openjdk-i386/jre/bin/java"  
source /etc/environment  
echo $JAVA_HOME  
```
