Pull json data for a PurpleAir device and put into telegraf.

The purpleair.conf file goes into you /etc/telegraf/telegraf.d/
directory. The DEVICEID and APIKEY need to be replaced with the id of
the device for which data is to be pulled and the API key for your
account.

The purpleair_json.py script needs to go into the /usr/local/bin
directory. It requires Python 3 and the requests package.
