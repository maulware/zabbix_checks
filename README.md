# Zabbix Riot (Vector) check/automation
This is meant to either help monitor, autodownload to prepar, or even fully upgrade a {Riot (Vector)}(https://github.com/vector-im/riot-web/) installation that is running on nginx.

## Installation:
### zabbix
put refernce into into agentd.conf.d/ if you want to use it with zabbix
### cron
put into crontab or /etc/cron.d ...

## parameters
### 1. atom url
normally: https://github.com/vector-im/riot-web/releases.atom
### 2. HTDOCS path
for example: /var/www/my-riot.local/
### 3. what to do (optional)
choose: (CHECK),DOWNLOAD,INSTALL

