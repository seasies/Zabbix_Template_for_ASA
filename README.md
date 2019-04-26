# Zabbix_Template_for_ASA
Данный шаблон используется у меня для мониторинга Cisco ASA 5525. Помимо созданных и выложенных здесь шаблонов он также использует некоторые шаблоны Zabbix, установленные по умолчанию:
* Template Module Cisco Inventory SNMPv2
* Template Module EtherLike-MIB SNMPv2
* Template Module Generic SNMPv2
* Template Module Interfaces SNMPv2

Поэтому перед установкой убедитесь в их наличии.

## Установка: ##
1. Импортируйте шаблоны на сервер Zabbix в следующей последовательности:
* Template Module Cisco CISCO-MEMORY-POOL-MIB SNMPv2 for firewalls ASA
* Template Module Cisco CISCO-PROCESS-MIB SNMPv2 for firewalls ASA
* Template Module Cisco Inventory ASA SNMPv2
* Template Module Generic ASA SNMPv2
* Template for ASA
2. Добавьте узел сети в котором, в качестве шаблона укажите Template for ASA.
