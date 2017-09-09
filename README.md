# Zabbix checks that can be used as they are

## Installation:
### zabbix
put refernce into into agentd.conf.d/ if you want to use it with zabbix
### cron
put into crontab or /etc/cron.d ...

## Riot (Vector) check/automation
This is meant to either help monitor, autodownload to prepar, or even fully upgrade a [Riot (Vector)](https://github.com/vector-im/riot-web/) installation that is running on nginx.

### requirements
* Having a symlink in the HTDOCS folder to the newest running installation (and have nginx configured to use this).
* installed (in PATH): wget or curl, head, grep, which, nginx
* currently service is required

### parameters
1. Atom url (mandatory)
normally: https://github.com/vector-im/riot-web/releases.atom
2. HTDOCS path (mandatory)
for example: /var/www/my-riot.local/
3. What to do (optional)
choose: (CHECK),DOWNLOAD,INSTALL

### TODOs
* Implement solution (maybe introduce config file) for proper check and restart handling for systemctl and other systems.

