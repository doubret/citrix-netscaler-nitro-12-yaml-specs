# Resource servicegroup

- [Identifier](#identifier)
- [Operations](#operations)
- [Fields](#fields)

## Identifier

Identifier : servicegroupname

## Operations

| Name | Method | Url |
|----|----|----|
| List | GET | `http://<netscaler-ip-address>/nitro/v1/config/servicegroup` |
| Get | GET | `http://<netscaler-ip-address>/nitro/v1/config/servicegroup/<name>` |
| Delete | DELETE | `http://<netscaler-ip-address>/nitro/v1/config/servicegroup/<name>` |
| Update | PUT | `http://<netscaler-ip-address>/nitro/v1/config/servicegroup` |
| Add | POST | `http://<netscaler-ip-address>/nitro/v1/config/servicegroup` |
| Enable | POST | `http://<netscaler-ip-address>/nitro/v1/config/servicegroup?action=enable` |
| Disable | POST | `http://<netscaler-ip-address>/nitro/v1/config/servicegroup?action=disable` |
| Rename | POST | `http://<netscaler-ip-address>/nitro/v1/config/servicegroup?action=rename` |
| Unset | POST | `http://<netscaler-ip-address>/nitro/v1/config/servicegroup?action=unset` |

## Fields

| Name | Update | Type |
|----|----|----|
| servicegroupname | No | string |
| servicetype | No | HTTP, FTP, TCP, UDP, SSL, SSL_BRIDGE, SSL_TCP, DTLS, NNTP, RPCSVR, DNS, ADNS, SNMP, RTSP, DHCPRA, ANY, SIP_UDP, SIP_TCP, SIP_SSL, DNS_TCP, ADNS_TCP, MYSQL, MSSQL, ORACLE, RADIUS, RADIUSListener, RDP, DIAMETER, SSL_DIAMETER, TFTP, SMPP, PPTP, GRE, SYSLOGTCP, SYSLOGUDP, FIX, SSL_FIX, USER_TCP, USER_SSL_TCP |
| cachetype | No | TRANSPARENT, REVERSE, FORWARD |
| td | No | double |
| maxclient | No | double |
| maxreq | No | double |
| cacheable | No | YES, NO |
| cip | No | ENABLED, DISABLED |
| cipheader | No | string |
| usip | No | YES, NO |
| pathmonitor | No | YES, NO |
| pathmonitorindv | No | YES, NO |
| useproxyport | No | YES, NO |
| healthmonitor | No | YES, NO |
| sc | No | ON, OFF |
| sp | No | ON, OFF |
| rtspsessionidremap | No | ON, OFF |
| clttimeout | No | int |
| svrtimeout | No | int |
| cka | No | YES, NO |
| tcpb | No | YES, NO |
| cmp | No | YES, NO |
| maxbandwidth | No | double |
| monthreshold | No | double |
| state | No | ENABLED, DISABLED |
| downstateflush | No | ENABLED, DISABLED |
| tcpprofilename | No | nstcpprofile.name |
| httpprofilename | No | nshttpprofile.name |
| comment | No | string |
| appflowlog | No | ENABLED, DISABLED |
| netprofile | No | netprofile.name |
| autoscale | No | DISABLED, DNS, POLICY |
| memberport | No | int |
| monconnectionclose | No | RESET, FIN |

