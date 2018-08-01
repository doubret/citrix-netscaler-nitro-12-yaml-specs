# Resource service

- [Identifier](#identifier)
- [Operations](#operations)
- [Fields](#fields)

## Identifier

Identifier : name

## Operations

| Name | Method | Url |
|----|----|----|
| List | GET | `http://<netscaler-ip-address>/nitro/v1/config/service` |
| Get | GET | `http://<netscaler-ip-address>/nitro/v1/config/service/<name>` |
| Delete | DELETE | `http://<netscaler-ip-address>/nitro/v1/config/service/<name>` |
| Update | PUT | `http://<netscaler-ip-address>/nitro/v1/config/service` |
| Add | POST | `http://<netscaler-ip-address>/nitro/v1/config/service` |
| Enable | POST | `http://<netscaler-ip-address>/nitro/v1/config/service?action=enable` |
| Disable | POST | `http://<netscaler-ip-address>/nitro/v1/config/service?action=disable` |
| Rename | POST | `http://<netscaler-ip-address>/nitro/v1/config/service?action=rename` |
| Unset | POST | `http://<netscaler-ip-address>/nitro/v1/config/service?action=unset` |

## Fields

| Name | Update | Type |
|----|----|----|
| name | No | string |
| ip | No | ip |
| servername | No | server.name |
| servicetype | No | HTTP, FTP, TCP, UDP, SSL, SSL_BRIDGE, SSL_TCP, DTLS, NNTP, RPCSVR, DNS, ADNS, SNMP, RTSP, DHCPRA, ANY, SIP_UDP, SIP_TCP, SIP_SSL, DNS_TCP, ADNS_TCP, MYSQL, MSSQL, ORACLE, RADIUS, RADIUSListener, RDP, DIAMETER, SSL_DIAMETER, TFTP, SMPP, PPTP, GRE, SYSLOGTCP, SYSLOGUDP, FIX, SSL_FIX, USER_TCP, USER_SSL_TCP |
| port | No | int |
| cleartextport | No | int |
| cachetype | No | TRANSPARENT, REVERSE, FORWARD |
| maxclient | No | double |
| healthmonitor | No | YES, NO |
| maxreq | No | double |
| cacheable | No | YES, NO |
| cip | No | ENABLED, DISABLED |
| cipheader | No | string |
| usip | No | YES, NO |
| pathmonitor | No | YES, NO |
| pathmonitorindv | No | YES, NO |
| useproxyport | No | YES, NO |
| sc | No | ON, OFF |
| sp | No | ON, OFF |
| rtspsessionidremap | No | ON, OFF |
| clttimeout | No | int |
| svrtimeout | No | int |
| customserverid | No | string |
| serverid | No | double |
| cka | No | YES, NO |
| tcpb | No | YES, NO |
| cmp | No | YES, NO |
| maxbandwidth | No | double |
| accessdown | No | YES, NO |
| monthreshold | No | double |
| downstateflush | No | ENABLED, DISABLED |
| tcpprofilename | No | nstcpprofile.name |
| httpprofilename | No | nshttpprofile.name |
| hashid | No | double |
| comment | No | string |
| appflowlog | No | ENABLED, DISABLED |
| netprofile | No | string |
| td | No | double |
| processlocal | No | ENABLED, DISABLED |
| dnsprofilename | No | dnsprofile.dnsprofilename |
| monconnectionclose | No | RESET, FIN |

