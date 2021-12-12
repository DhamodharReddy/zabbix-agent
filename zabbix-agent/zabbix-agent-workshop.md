## **Prerequisites**
_Virtual machine with Ubuntu 18.04 installed on it._

_Make sure user have sudo or root previlages._

## **Install Zabbix Agent**
```
git clone https://github.com/DhamodharReddy/zabbix-agent.git && cd /zabbix-agent/zabbix-agent-install.sh
```
```
sudo chmod 755 zabbix-agent-install.sh && sudo ./zabbix-agent-install.sh
```
## **Replace <_server-IP_> & <_hostname_>**
In the below file locate the Server and hostname and replace details as below
```
sudo nano /etc/zabbix/zabbix_agentd.conf
```
**Server**=<_IP-of-zabbix-server_>

**hostname**=<_hostname-of-your-machine_>

## **Restart the Zabbix-agent & allow 10050/tcp**
```
sudo chmod 755 zabbix-agent2.sh && sudo ./zabbix-agent2.sh
```
