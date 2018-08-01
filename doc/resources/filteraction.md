# Resource filteraction

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
| qual | No | reset, add, corrupt, forward, errorcode, drop |
| value | No | string |
| respcode | No | double |
| page | No | string |
| servicename | No | service.name |

