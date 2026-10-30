# Enterprise-SOC-SIEM-Lab-Wazuh
Project overview
This project demonstrates the deployment and initial configuration of security information and event Management (SIEM) lab using Wazuh Ubuntu Server.
This lab design designed to develop practical Blue Team and SOC Analyst skills.
## Technologies Used
- Wazuh SIEM
- Ubuntu server 24.04 LTS
- Oracle VirtualBox
- Linux CLI
- Window 11 Host
## Lab architecture
- Window 11:Host machine
- Ubuntu server: Wazuh SIEM deployment
- VirtualBox host-Only Network: Lab communication
- Kali Linux: Planned endpoint integration
## Completed Activities
- created an ubuntu server
- installed and configured Wazuh SIEM
- accessed the wazuh Dashboard
- reviewed initial securities alerts
- configured Host-only networking
- verified network connectivity between ubuntu and kali linux
## Future improvements
. install and register the wazuh agent
. collect endpoint security logs
. investigate security alerts
. develop SOC incident investigation scenarios
## Skills Demonstrate 
SIEM Deployment | linux administration | virtualization | network configuration | security monitoring | SOC fundamentals.
## Disclaimer 
This project is intended for educational purpose in an isolated virtual lab.
## Wazuh Dashboard screenshot
![Wazuh SIEM Dashboard]
(wazuh-dashboard.png)
## Lab Arcitecture
```text
windows 11 host
virtualBox host-only networks
Ubuntu 24.04 Wazuh SIEM Server
IP: 192.168.56.10
Network connecttivity verified(ping)
kali linux: VM
wazuh agent: not installed
```
## Network configuration 
- Virtualization: Oracle VirtualBox
- Wazuh server: Ubuntu 24.04
- Host-Only network:192.168.56.0/24
- Wazuh server IP: 192.168.56.10
- Kali Linux: Network connectivity verified
- Agent-based monitoring: pending
