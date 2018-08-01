# Resource policyexpression

- [Identifier](#identifier)
- [Operations](#operations)
- [Fields](#fields)

## Identifier

Identifier : name

## Operations

| Name | Method | Url |
|----|----|----|
| List | GET | `http://<netscaler-ip-address>/nitro/v1/config/policyexpression` |
| Get | GET | `http://<netscaler-ip-address>/nitro/v1/config/policyexpression/<name>` |
| Delete | DELETE | `http://<netscaler-ip-address>/nitro/v1/config/policyexpression/<name>` |
| Update | PUT | `http://<netscaler-ip-address>/nitro/v1/config/policyexpression` |
| Add | POST | `http://<netscaler-ip-address>/nitro/v1/config/policyexpression` |
| Enable | POST | `http://<netscaler-ip-address>/nitro/v1/config/policyexpression?action=enable` |
| Disable | POST | `http://<netscaler-ip-address>/nitro/v1/config/policyexpression?action=disable` |
| Rename | POST | `http://<netscaler-ip-address>/nitro/v1/config/policyexpression?action=rename` |
| Unset | POST | `http://<netscaler-ip-address>/nitro/v1/config/policyexpression?action=unset` |

## Fields

| Name | Update | Type |
|----|----|----|
| name | No | string |
| clientsecuritymessage | No | string |
| comment | No | string |
| description | No | string |
| value | No | string |

