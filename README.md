**Zabbix Network Monitoring Scripts**
Monitoring toolkit for Cisco switches, Cisco IE Industrial Ethernet, NCS routers, Microsemi, APC UPS, Fortinet firewalls, and more — built for Zabbix 6.0+.

📌 Overview
This repository contains a collection of Zabbix discovery rules, item prototypes, triggers, and YAML templates designed for multi‑vendor network monitoring.

The scripts are optimized for:

Cisco Catalyst switches
Cisco IE Industrial Ethernet platforms
Cisco NCS routers
Microsemi devices
APC UPS systems
Fortinet firewalls
SNMP‑based monitoring environments
All templates follow Zabbix 6.0 LLD (Low‑Level Discovery) standards.


🚀 Features
✔️ SNMPv2/v3 support
✔️ Auto‑discovery of interfaces, modules, power supplies, fans
✔️ Industrial Ethernet (IE) platform monitoring
✔️ NCS router health & interface monitoring
✔️ APC UPS battery, load, runtime metrics
✔️ Fortinet firewall CPU, memory, session count
✔️ YAML‑based Zabbix templates for easy import
✔️ Clean trigger logic to reduce false positives

**🛠 Requirements**
Zabbix Server 6.0 or later
SNMP enabled on target devices
Correct SNMP community or SNMPv3 credentials
Import permissions on Zabbix frontend
