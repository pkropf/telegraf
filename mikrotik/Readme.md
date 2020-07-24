Capture the network traffic data from a Mikrotik Lora device and add
it to an influx database via telegraf.

The lora.conf file goes into your /etc/telegraf/telegraf.d/
directory. Change the LORA_DEVICE to the network name or IP address of
the Lora device. Change COMMUNITY to the SNMP community name as
configured on the Lora device. If you didn't change it use public, the
default.