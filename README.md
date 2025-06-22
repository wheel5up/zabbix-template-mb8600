# zabbix-template-mb8600

Template and installation instructions for mb8600 cable modem monitor in Zabbix

# installation

Decide where you will be installing the script. The script requires node 18 or later.
These instructions assume you are installing on the Zabbix server

1. Install node
   `sudo apt install nodejs`

2. Download the script and place it in /usr/lib/externalscripts/

3. Confirm the script is executable by Zabbix
   `sudo -u zabbix /usr/lib/zabbix/externalscripts/mb8600 -down
❌ Argument error: Both -u (username) and -p (password) are required.`

# Acknowledgements

https://gist.github.com/josedaniel/951664
