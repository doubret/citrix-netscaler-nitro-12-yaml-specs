# Resource lbvserver

- [Identifier](#identifier)
- [Operations](#operations)
- [Fields](#fields)

## Identifier

Identifier : name

## Operations

| Name | Method | Url |
|----|----|----|
| List | GET | `http://<netscaler-ip-address>/nitro/v1/config/lbvserver` |
| Get | GET | `http://<netscaler-ip-address>/nitro/v1/config/lbvserver/<name>` |
| Delete | DELETE | `http://<netscaler-ip-address>/nitro/v1/config/lbvserver/<name>` |
| Update | PUT | `http://<netscaler-ip-address>/nitro/v1/config/lbvserver` |
| Add | POST | `http://<netscaler-ip-address>/nitro/v1/config/lbvserver` |
| Enable | POST | `http://<netscaler-ip-address>/nitro/v1/config/lbvserver?action=enable` |
| Disable | POST | `http://<netscaler-ip-address>/nitro/v1/config/lbvserver?action=disable` |
| Rename | POST | `http://<netscaler-ip-address>/nitro/v1/config/lbvserver?action=rename` |
| Unset | POST | `http://<netscaler-ip-address>/nitro/v1/config/lbvserver?action=unset` |

## Fields

| Name | Update | Type |
|----|----|----|
| name | No | string |
| state | No | ENABLED, DISABLED |
| servicetype | No | HTTP, FTP, TCP, UDP, SSL, SSL_BRIDGE, SSL_TCP, DTLS, NNTP, DNS, DHCPRA, ANY, SIP_UDP, SIP_TCP, SIP_SSL, DNS_TCP, RTSP, PUSH, SSL_PUSH, RADIUS, RDP, MYSQL, MSSQL, DIAMETER, SSL_DIAMETER, TFTP, ORACLE, SMPP, SYSLOGTCP, SYSLOGUDP, FIX, SSL_FIX, USER_TCP, USER_SSL_TCP |
| ipv46 | No | ip |
| ippattern | No | ip |
| ipmask | No | ip_mask |
| port | No | int |
| range | No | double |
| persistencetype | No | SOURCEIP, COOKIEINSERT, SSLSESSION, RULE, URLPASSIVE, CUSTOMSERVERID, DESTIP, SRCIPDESTIP, CALLID, RTSPSID, DIAMETER, FIXSESSION, USERSESSION, NONE |
| timeout | No | int |
| persistencebackup | No | SOURCEIP, NONE |
| backuppersistencetimeout | No | int |
| lbmethod | No | ROUNDROBIN, LEASTCONNECTION, LEASTRESPONSETIME, URLHASH, DOMAINHASH, DESTINATIONIPHASH, SOURCEIPHASH, SRCIPDESTIPHASH, LEASTBANDWIDTH, LEASTPACKETS, TOKEN, SRCIPSRCPORTHASH, LRTM, CALLIDHASH, CUSTOMLOAD, LEASTREQUEST, AUDITLOGHASH, STATICPROXIMITY, USER_TOKEN |
| hashlength | No | double |
| netmask | No | ip_mask |
| v6netmasklen | No | double |
| backuplbmethod | No | ROUNDROBIN, LEASTCONNECTION, LEASTRESPONSETIME, SOURCEIPHASH, LEASTBANDWIDTH, LEASTPACKETS, CUSTOMLOAD |
| cookiename | No | string |
| rule | No | string |
| listenpolicy | No | string |
| listenpriority | No | double |
| resrule | No | string |
| persistmask | No | string |
| v6persistmasklen | No | double |
| pq | No | ON, OFF |
| sc | No | ON, OFF |
| rtspnat | No | ON, OFF |
| m | No | IP, MAC, IPTUNNEL, TOS |
| tosid | No | double |
| datalength | No | double |
| dataoffset | No | double |
| sessionless | No | ENABLED, DISABLED |
| trofspersistence | No | ENABLED, DISABLED |
| connfailover | No | DISABLED, STATEFUL, STATELESS |
| redirurl | No | string |
| cacheable | No | YES, NO |
| clttimeout | No | double |
| somethod | No | CONNECTION, DYNAMICCONNECTION, BANDWIDTH, HEALTH, NONE |
| sopersistence | No | ENABLED, DISABLED |
| sopersistencetimeout | No | double |
| healththreshold | No | double |
| sothreshold | No | double |
| sobackupaction | No | DROP, ACCEPT, REDIRECT |
| redirectportrewrite | No | ENABLED, DISABLED |
| downstateflush | No | ENABLED, DISABLED |
| backupvserver | No | string |
| disableprimaryondown | No | ENABLED, DISABLED |
| insertvserveripport | No | OFF, VIPADDR, V6TOV4MAPPING |
| vipheader | No | string |
| authenticationhost | No | string |
| authentication | No | ON, OFF |
| authn401 | No | ON, OFF |
| authnvsname | No | string |
| push | No | ENABLED, DISABLED |
| pushvserver | No | string |
| pushlabel | No | string |
| pushmulticlients | No | YES, NO |
| tcpprofilename | No | nstcpprofile.name |
| httpprofilename | No | nshttpprofile.name |
| dbprofilename | No | nsdbprofile.name |
| comment | No | string |
| l2conn | No | ON, OFF |
| oracleserverversion | No | 10G, 11G |
| mssqlserverversion | No | 70, 2000, 2000SP1, 2005, 2008, 2008R2, 2012, 2014 |
| mysqlprotocolversion | No | double |
| mysqlserverversion | No | string |
| mysqlcharacterset | No | double |
| mysqlservercapabilities | No | double |
| appflowlog | No | ENABLED, DISABLED |
| netprofile | No | netprofile.name |
| icmpvsrresponse | No | PASSIVE, ACTIVE |
| rhistate | No | PASSIVE, ACTIVE |
| newservicerequest | No | double |
| newservicerequestunit | No | PER_SECOND, PERCENT |
| newservicerequestincrementinterval | No | double |
| minautoscalemembers | No | double |
| maxautoscalemembers | No | double |
| persistavpno | No | double[] |
| skippersistency | No | Bypass, ReLb, None |
| td | No | double |
| authnprofile | No | string |
| macmoderetainvlan | No | ENABLED, DISABLED |
| dbslb | No | ENABLED, DISABLED |
| dns64 | No | ENABLED, DISABLED |
| bypassaaaa | No | YES, NO |
| recursionavailable | No | YES, NO |
| processlocal | No | ENABLED, DISABLED |
| dnsprofilename | No | dnsprofile.dnsprofilename |
| lbprofilename | No | lbprofile.dnsprofilename |
| redirectfromport | No | int |
| httpsredirecturl | No | string |
| retainconnectionsoncluster | No | YES, NO |

