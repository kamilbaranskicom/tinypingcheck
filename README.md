# tinypingcheck
Pings devices to check if they exist on network; outputs HTML

## Usage:
* copy deviceList.sample.php to deviceList.php
* edit deviceList.php
* upload to the webserver
* voila.

## Problems?
* chmod u+s /bin/ping
* chmod u+s /usr/sbin/arp
* check if shell_exec isn't blocked on the server