Capture data from running speedtest and add it to an influx database
via telegraf.

The speedtest.conf file goes into your /etc/telegraf/telegraf.d/
directory.

The speedtest_json.py script needs to go into the /usr/local/bin
directory. It requires the speedtest-cli package.
