# Resource scpolicy

Spec for **scpolicy** resource - [citrix documentation page](https://developer-docs.citrix.com/projects/netscaler-nitro-api/en/12.0/configuration/sure-connect/scpolicy/scpolicy/)

- [Identifier](#identifier)
- [Operations](#operations)
- [Fields](#fields)

## Identifier

Identifier : name

## Operations

| Name | Method | Url |
|----|----|----|
| List | GET | `http://<netscaler-ip-address>/nitro/v1/config/scpolicy` |
| Get | GET | `http://<netscaler-ip-address>/nitro/v1/config/scpolicy/<name>` |
| Delete | DELETE | `http://<netscaler-ip-address>/nitro/v1/config/scpolicy/<name>` |
| Update | PUT | `http://<netscaler-ip-address>/nitro/v1/config/scpolicy` |
| Add | POST | `http://<netscaler-ip-address>/nitro/v1/config/scpolicy` |
| Enable | POST | `http://<netscaler-ip-address>/nitro/v1/config/scpolicy?action=enable` |
| Disable | POST | `http://<netscaler-ip-address>/nitro/v1/config/scpolicy?action=disable` |
| Rename | POST | `http://<netscaler-ip-address>/nitro/v1/config/scpolicy?action=rename` |
| Unset | POST | `http://<netscaler-ip-address>/nitro/v1/config/scpolicy?action=unset` |

## Fields

| Name | Update | Type |
|----|----|----|
| name | No | string |
| action | No | string |
| altcontentpath | No | ACS, NS, NOACTION |
| altcontentsvcname | No | string |
| delay | No | double |
| maxconn | No | double |
| rule | No | string |
| url | No | string |

