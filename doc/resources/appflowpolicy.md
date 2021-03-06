# Resource appflowpolicy

Spec for **appflowpolicy** resource - [citrix documentation page](https://developer-docs.citrix.com/projects/netscaler-nitro-api/en/12.0/configuration/appflow/appflowpolicy/appflowpolicy/)

- [Identifier](#identifier)
- [Operations](#operations)
- [Fields](#fields)

## Identifier

Identifier : name

## Operations

| Name | Method | Url |
|----|----|----|
| List | GET | `http://<netscaler-ip-address>/nitro/v1/config/appflowpolicy` |
| Get | GET | `http://<netscaler-ip-address>/nitro/v1/config/appflowpolicy/<name>` |
| Delete | DELETE | `http://<netscaler-ip-address>/nitro/v1/config/appflowpolicy/<name>` |
| Update | PUT | `http://<netscaler-ip-address>/nitro/v1/config/appflowpolicy` |
| Add | POST | `http://<netscaler-ip-address>/nitro/v1/config/appflowpolicy` |
| Enable | POST | `http://<netscaler-ip-address>/nitro/v1/config/appflowpolicy?action=enable` |
| Disable | POST | `http://<netscaler-ip-address>/nitro/v1/config/appflowpolicy?action=disable` |
| Rename | POST | `http://<netscaler-ip-address>/nitro/v1/config/appflowpolicy?action=rename` |
| Unset | POST | `http://<netscaler-ip-address>/nitro/v1/config/appflowpolicy?action=unset` |

## Fields

| Name | Update | Type |
|----|----|----|
| name | No | string |
| action | No | appflowaction.name |
| comment | No | string |
| rule | No | string |
| undefaction | No | appflowaction.name |

