Capture the network traffic data from a Ubiquiti EdgeRouter device and
add it to an influx database via telegraf.

The edgerouter.conf file goes into your /etc/telegraf/telegraf.d/
directory. Change the EDGEROUTER_DEVICE to the network name or IP
address of the EdgeRouter device. Change COMMUNITY to the SNMP
community name as configured on the EdgeRouter. If you didn't change
it use public, the default.