# Resource transformaction

- [Identifier](#identifier)
- [Operations](#operations)
- [Fields](#fields)

## Identifier

Identifier : name

## Operations

| Name | Method | Url |
|----|----|----|
| List | GET | `http://<netscaler-ip-address>/nitro/v1/config/transformaction` |
| Get | GET | `http://<netscaler-ip-address>/nitro/v1/config/transformaction/<name>` |
| Delete | DELETE | `http://<netscaler-ip-address>/nitro/v1/config/transformaction/<name>` |
| Update | PUT | `http://<netscaler-ip-address>/nitro/v1/config/transformaction` |
| Add | POST | `http://<netscaler-ip-address>/nitro/v1/config/transformaction` |
| Enable | POST | `http://<netscaler-ip-address>/nitro/v1/config/transformaction?action=enable` |
| Disable | POST | `http://<netscaler-ip-address>/nitro/v1/config/transformaction?action=disable` |
| Rename | POST | `http://<netscaler-ip-address>/nitro/v1/config/transformaction?action=rename` |
| Unset | POST | `http://<netscaler-ip-address>/nitro/v1/config/transformaction?action=unset` |

## Fields

| Name | Update | Type |
|----|----|----|
| name | No | string |
| profilename | No | transformprofile.name |
| priority | No | double |
| state | No | ENABLED, DISABLED |
| requrlfrom | No | string |
| requrlinto | No | string |
| resurlfrom | No | string |
| resurlinto | No | string |
| cookiedomainfrom | No | string |
| cookiedomaininto | No | string |
| comment | No | string |

