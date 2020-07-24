Capture the network traffic data from Ubiquiti EdgeRouter and
EdgeSwitch devices and add it to an influx database via telegraf.

The edgerouter.conf or edgeswitch.conf file goes into your
/etc/telegraf/telegraf.d/ directory. Change the NAME_OR_IP to the
network name or IP address of the device. Change COMMUNITY to the SNMP
community name as configured on the device. If you didn't change it
use public, the default.

If there are multiple EdgeSwitch or EdgeRouters devices that are to be
monitored, create a .conf file for each of the devices.