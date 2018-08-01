# Resource policypatset

- [Identifier](#identifier)
- [Operations](#operations)
- [Fields](#fields)

## Identifier

Identifier : name

## Operations

| Name | Method | Url |
|----|----|----|
| List | GET | `http://<netscaler-ip-address>/nitro/v1/config/policypatset` |
| Get | GET | `http://<netscaler-ip-address>/nitro/v1/config/policypatset/<name>` |
| Delete | DELETE | `http://<netscaler-ip-address>/nitro/v1/config/policypatset/<name>` |
| Update | PUT | `http://<netscaler-ip-address>/nitro/v1/config/policypatset` |
| Add | POST | `http://<netscaler-ip-address>/nitro/v1/config/policypatset` |
| Enable | POST | `http://<netscaler-ip-address>/nitro/v1/config/policypatset?action=enable` |
| Disable | POST | `http://<netscaler-ip-address>/nitro/v1/config/policypatset?action=disable` |
| Rename | POST | `http://<netscaler-ip-address>/nitro/v1/config/policypatset?action=rename` |
| Unset | POST | `http://<netscaler-ip-address>/nitro/v1/config/policypatset?action=unset` |

## Fields

| Name | Update | Type |
|----|----|----|
| name | No | string |
| indextype | No | Auto-generated, User-defined |
| comment | No | string |

