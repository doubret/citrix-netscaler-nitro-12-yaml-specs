# Resource netprofile

- [Identifier](#identifier)
- [Operations](#operations)
- [Fields](#fields)

## Identifier

Identifier : name

## Operations

| Name | Method | Url |
|----|----|----|
| List | GET | `http://<netscaler-ip-address>/nitro/v1/config/netprofile` |
| Get | GET | `http://<netscaler-ip-address>/nitro/v1/config/netprofile/<name>` |
| Delete | DELETE | `http://<netscaler-ip-address>/nitro/v1/config/netprofile/<name>` |
| Update | PUT | `http://<netscaler-ip-address>/nitro/v1/config/netprofile` |
| Add | POST | `http://<netscaler-ip-address>/nitro/v1/config/netprofile` |
| Enable | POST | `http://<netscaler-ip-address>/nitro/v1/config/netprofile?action=enable` |
| Disable | POST | `http://<netscaler-ip-address>/nitro/v1/config/netprofile?action=disable` |
| Rename | POST | `http://<netscaler-ip-address>/nitro/v1/config/netprofile?action=rename` |
| Unset | POST | `http://<netscaler-ip-address>/nitro/v1/config/netprofile?action=unset` |

## Fields

| Name | Update | Type |
|----|----|----|
| name | No | string |
| td | No | double |
| srcip | No | ip |
| srcippersistency | No | ENABLED, DISABLED |
| overridelsn | No | ENABLED, DISABLED |

