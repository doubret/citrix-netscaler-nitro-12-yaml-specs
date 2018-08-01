# Resource lbgroup

- [Identifier](#identifier)
- [Operations](#operations)
- [Fields](#fields)

## Identifier

Identifier : name

## Operations

| Name | Method | Url |
|----|----|----|
| List | GET | `http://<netscaler-ip-address>/nitro/v1/config/lbgroup` |
| Get | GET | `http://<netscaler-ip-address>/nitro/v1/config/lbgroup/<name>` |
| Delete | DELETE | `http://<netscaler-ip-address>/nitro/v1/config/lbgroup/<name>` |
| Update | PUT | `http://<netscaler-ip-address>/nitro/v1/config/lbgroup` |
| Add | POST | `http://<netscaler-ip-address>/nitro/v1/config/lbgroup` |
| Enable | POST | `http://<netscaler-ip-address>/nitro/v1/config/lbgroup?action=enable` |
| Disable | POST | `http://<netscaler-ip-address>/nitro/v1/config/lbgroup?action=disable` |
| Rename | POST | `http://<netscaler-ip-address>/nitro/v1/config/lbgroup?action=rename` |
| Unset | POST | `http://<netscaler-ip-address>/nitro/v1/config/lbgroup?action=unset` |

## Fields

| Name | Update | Type |
|----|----|----|
| name | No | string |
| backuppersistencetimeout | No | double |
| persistmask | No | string |
| cookiename | No | string |
| v6persistmasklen | No | double |
| cookiedomain | No | string |
| timeout | No | double |
| rule | No | string |
| persistencetype | No | SOURCEIP, COOKIEINSERT, RULE, NONE |
| persistencebackup | No | SOURCEIP, NONE |
| usevserverpersistency | No | ENABLED, DISABLED |

