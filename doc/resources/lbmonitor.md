# Resource lbmonitor

- [Identifier](#identifier)
- [Operations](#operations)
- [Fields](#fields)

## Identifier

Identifier : monitorname
Additionnal fields :
- type

## Operations

| Name | Method | Url |
|----|----|----|
| List | GET | `http://<netscaler-ip-address>/nitro/v1/config/lbmonitor` |
| Get | GET | `http://<netscaler-ip-address>/nitro/v1/config/lbmonitor/<name>` |
| Delete | DELETE | `http://<netscaler-ip-address>/nitro/v1/config/lbmonitor/<name>` |
| Update | PUT | `http://<netscaler-ip-address>/nitro/v1/config/lbmonitor` |
| Add | POST | `http://<netscaler-ip-address>/nitro/v1/config/lbmonitor` |
| Enable | POST | `http://<netscaler-ip-address>/nitro/v1/config/lbmonitor?action=enable` |
| Disable | POST | `http://<netscaler-ip-address>/nitro/v1/config/lbmonitor?action=disable` |
| Rename | POST | `http://<netscaler-ip-address>/nitro/v1/config/lbmonitor?action=rename` |
| Unset | POST | `http://<netscaler-ip-address>/nitro/v1/config/lbmonitor?action=unset` |

## Fields

| Name | Update | Type |
|----|----|----|
| monitorname | No | string |
| state | No | ENABLED, DISABLED |
| type | No | PING, TCP, HTTP, TCP-ECV, HTTP-ECV, UDP-ECV, DNS, FTP, LDNS-PING, LDNS-TCP, LDNS-DNS, RADIUS, USER, HTTP-INLINE, SIP-UDP, SIP-TCP, LOAD, FTP-EXTENDED, SMTP, SNMP, NNTP, MYSQL, MYSQL-ECV, MSSQL-ECV, ORACLE-ECV, LDAP, POP3, CITRIX-XML-SERVICE, CITRIX-WEB-INTERFACE, DNS-TCP, RTSP, ARP, CITRIX-AG, CITRIX-AAC-LOGINPAGE, CITRIX-AAC-LAS, CITRIX-XD-DDC, ND6, CITRIX-WI-EXTENDED, DIAMETER, RADIUS_ACCOUNTING, STOREFRONT, APPC, SMPP, CITRIX-XNC-ECV, CITRIX-XDM, CITRIX-STA-SERVICE, CITRIX-STA-SERVICE-NHOP |
| action | No | NONE, LOG, DOWN |
| httprequest | No | string |
| rtsprequest | No | string |
| customheaders | No | string |
| maxforwards | No | double |
| sipmethod | No | string |
| sipuri | No | string |
| sipreguri | No | string |
| send | No | string |
| recv | No | string |
| query | No | string |
| querytype | No | string |
| scriptname | No | string |
| scriptargs | No | string |
| dispatcherip | No | ip |
| dispatcherport | No | int |
| username | No | string |
| password | No | string |
| secondarypassword | No | string |
| logonpointname | No | string |
| lasversion | No | string |
| radkey | No | string |
| radnasid | No | string |
| radnasip | No | ip |
| radaccounttype | No | double |
| radframedip | No | ip |
| radapn | No | string |
| radmsisdn | No | string |
| radaccountsession | No | string |
| lrtm | No | string |
| deviation | No | double |
| units1 | No | string |
| interval | No | int |
| units3 | No | string |
| resptimeout | No | int |
| units4 | No | string |
| resptimeoutthresh | No | double |
| retries | No | int |
| failureretries | No | int |
| alertretries | No | int |
| successretries | No | int |
| downtime | No | int |
| units2 | No | string |
| destip | No | ip |
| destport | No | int |
| reverse | No | string |
| transparent | No | string |
| iptunnel | No | string |
| tos | No | string |
| tosid | No | double |
| secure | No | string |
| validatecred | No | string |
| domain | No | string |
| group | No | string |
| filename | No | string |
| basedn | No | string |
| binddn | No | string |
| filter | No | string |
| attribute | No | string |
| database | No | string |
| oraclesid | No | string |
| sqlquery | No | string |
| evalrule | No | string |
| mssqlprotocolversion | No | string |
| snmpoid | No | string |
| snmpcommunity | No | string |
| snmpthreshold | No | string |
| snmpversion | No | string |
| metrictable | No | string |
| application | No | string |
| sitepath | No | string |
| storename | No | string |
| storefrontacctservice | No | string |
| hostname | No | string |
| netprofile | No | string |
| originhost | No | string |
| originrealm | No | string |
| hostipaddress | No | string |
| vendorid | No | double |
| productname | No | string |
| firmwarerevision | No | double |
| inbandsecurityid | No | string |
| vendorspecificvendorid | No | double |
| kcdaccount | No | string |
| storedb | No | string |
| storefrontcheckbackendservices | No | string |
| trofscode | No | double |
| trofsstring | No | string |
| sslprofile | No | string |

