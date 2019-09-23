# Zabbix_Template_for_ASA
Данный шаблон используется у меня для мониторинга Cisco ASA 5525. Помимо созданных и выложенных здесь шаблонов он также использует некоторые шаблоны Zabbix, установленные по умолчанию:

# Translation:
I use this template for monitoring the Cisco ASA 5525. In addition to the templates created and posted here, it also uses some default Zabbix templates.

* Template Module Cisco Inventory SNMPv2
* Template Module EtherLike-MIB SNMPv2
* Template Module Generic SNMPv2
* Template Module Interfaces SNMPv2

Поэтому перед установкой убедитесь в их наличии.
# Translation:
Therefore, before installation, make sure that they are

## Installation: ##
1. Import the templates to the Zabbix server in the following sequence:
* Template Module Cisco CISCO-MEMORY-POOL-MIB SNMPv2 for firewalls ASA
* Template Module Cisco CISCO-PROCESS-MIB SNMPv2 for firewalls ASA
* Template Module Cisco Inventory ASA SNMPv2
* Template Module Generic ASA SNMPv2
* Template for ASA
2. Add a host in which, as a template, specify Template for ASA.
