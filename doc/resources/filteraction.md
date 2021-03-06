# Resource filteraction

Spec for **filteraction** resource - [citrix documentation page](https://developer-docs.citrix.com/projects/netscaler-nitro-api/en/12.0/configuration/filter/filteraction/filteraction/)

- [Identifier](#identifier)
- [Operations](#operations)
- [Fields](#fields)

## Identifier

Identifier : name

## Operations

| Name | Method | Url |
|----|----|----|
| List | GET | `http://<netscaler-ip-address>/nitro/v1/config/filteraction` |
| Get | GET | `http://<netscaler-ip-address>/nitro/v1/config/filteraction/<name>` |
| Delete | DELETE | `http://<netscaler-ip-address>/nitro/v1/config/filteraction/<name>` |
| Update | PUT | `http://<netscaler-ip-address>/nitro/v1/config/filteraction` |
| Add | POST | `http://<netscaler-ip-address>/nitro/v1/config/filteraction` |
| Enable | POST | `http://<netscaler-ip-address>/nitro/v1/config/filteraction?action=enable` |
| Disable | POST | `http://<netscaler-ip-address>/nitro/v1/config/filteraction?action=disable` |
| Rename | POST | `http://<netscaler-ip-address>/nitro/v1/config/filteraction?action=rename` |
| Unset | POST | `http://<netscaler-ip-address>/nitro/v1/config/filteraction?action=unset` |

## Fields

| Name | Update | Type |
|----|----|----|
| name | No | string |
| page | No | string |
| qual | No | reset, add, corrupt, forward, errorcode, drop |
| respcode | No | double |
| servicename | No | service.name |
| value | No | string |

