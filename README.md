# zabbix-server

Extremely fast Zabbix server installation based on docker and docker-compose  
Note: only for dev and testing issues

## Prerequisites

1. git
1. systemd
1. docker
1. docker-compose
1. [Optionally] nginx

## Installation

```bash
# mkdir /var/zabbix && cd /var/zabbix
# git clone https://github.com/glushkovds/zabbix-server
# cp zabbix-server.service /etc/systemd/system
# systemctl enable zabbix-server
# systemctl start zabbix-server
```

That's all. Zabbix server latest version  [5.0 at writing time]

Now you can access it on http://localhost:8001

