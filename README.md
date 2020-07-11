# Zabbix-Template-Radio-Ceragon-IP10
Template Zabbix - Radio Ceragon IP10-R3

Inclui arquivo MIB

Itens coletados: MRMC-RX-ACM adaptive profile / MRMC-RX-Bitrate (Mbps) / MRMC-RX-QAM / MRMC-TX-ACM adaptive profile / MRMC-TX-Bitrate (Mbps) / MRMC-TX-QAM / MSE / OperationalStatus / RFU Rx frequency (MHz) Configued / RFU Rx level (dBm) / RFU Temperature / RFU Tx frequency (MHz) Configured / RFU Tx level (dBm)

Para realizar a coleta é necessário criar um host para cada SLOT disponivel, e alterar a community SNMP da seguinte forma:

SLOT 1 -> community = public_1

SLOT 2 -> community = public_2

SLOT 3 -> community = public_3

SLOT 4 -> community = public_4

SLOT 5 -> community = public_5

SLOT 6 -> community = public_6
