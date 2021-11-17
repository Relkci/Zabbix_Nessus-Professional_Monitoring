# Zabbix_Nessus-Professional_Monitoring
Zabbix Nessus Professional Monitor (API)

## Background 
This template is used to monitor and alert on a Nessus Professional Installation.

## Installation
- Import Zabbix_Nessus_Professional_API.yaml
- Create new Host
- Assign Template "Nessus Professional Monitor" to Host
- Set Macro {$NESSUS_ACCESSKEY} to your Nessus API Access Key (Can be created within Nessus web GUI)
- Set Macro {$NESSUS_SECRETKEY} to your Nessus API Secret Key (Can be created within Nessus web GUI)
- Set Macro {$NESSUS_HOST} to your Nessus Host URL  Key
- Add an agent host (can be left blank, only necessary to allow HTTP Agent to operate).  The data is collected by the Zabbix Serer or Proxy.

## Methodology
- Pulls Data from Nessus Professional API

## Features
- Monitors and stuff

## Details
- 58 Items
- 9 Triggers
- 10 Graphs
- 2 Dashboard
- 9 macros


## Triggers
- Active Hosts scanned > threshold
- Active scans > threshold
- Active TCP Sessions > threshold
- License Expires in xx days
- Server Status not ready

# Screenshots

Dashboard - Active Scans and Active Scan Hosts (7 days)
![](images/screenshot1.png)

Dashboard - Network Traffic (7 days)
![](images/screenshot2.png)

Dashboard - TCP Sessions (7 days)
![](images/sceenshot3.png)

Dashboard - Folder Count (7 days)
![](images/screenshot4.png)

Dashboard - Nessus Process CPU Util (7 days)
![](images/screenshot5.png)

Dashboard - Nessus Versioning 
![](images/screenshot6.png)

Dashboard - Nessus DNS Stats
![](images/screenshot7.png)

Dashboard - Active Health Alerts 
![](images/screenshot8.png)

Dashboard - Nessus License Expiry Approach
![](images/screenshot9.png)

Dashboard - Nessus Professional License Information
![](images/screenshot10.png)

Triggers 
![](images/screenshot11.png)

Graphs

![](images/screenshot12.png)

## Known Limitations & Issues
- 


## Contact
@Krelkci (twitter)   @ Relkci (Github)

## License
Apache 2

## Thanks
Black Hills Information Security https://www.blackhillsinfosec.com
