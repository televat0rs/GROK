# GROK Patterns
  
`Extraction of log message fields from NETGEAR XSM/GSM and SonicWall NSA devices.`

  &nbsp;
### NETGEAR Extractors - ###
>NETGEAR_CMDLOGGER: Extracts cli commands and executing user: traputil, count, source_if, source_ip, user, msg  
>NETGEAR_LINKSTATE: Extracts linkstate changes and interface information: traputil, count, msg, interface  
>NETGEAR_LLDP: Extracts LLDP alert information: traputil, count, msg, ChassisIDSubtype, ChassisID, DeviceClass, interface  
>NETGEAR_STP: Extracts STP alert inform.ation: traputil, count, msg, interface  

&nbsp;
### Sonicwall Extractors - ###
>SONICWALL_SRC: Extracts source information: src_ip, src_port, src_if, src_vlan, src_hostname  
>SONICWALL_DST: Extracts destination information: dst_ip, dst_port, dst_if, dst_vlan, dst_hostname  
>SONICWALL_PROTO: Extracts protocol information: proto, proto_type  


&nbsp;



# License

#### Apache 2.0 ####
