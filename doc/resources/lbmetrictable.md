# Resource lbmetrictable

Spec for **lbmetrictable** resource - [citrix documentation page](https://developer-docs.citrix.com/projects/netscaler-nitro-api/en/12.0/configuration/load-balancing/lbmetrictable/lbmetrictable/)

- [Identifier](#identifier)
- [Operations](#operations)
- [Fields](#fields)

## Identifier

Identifier : metrictable

## Operations

| Name | Method | Url |
|----|----|----|
| List | GET | `http://<netscaler-ip-address>/nitro/v1/config/lbmetrictable` |
| Get | GET | `http://<netscaler-ip-address>/nitro/v1/config/lbmetrictable/<name>` |
| Delete | DELETE | `http://<netscaler-ip-address>/nitro/v1/config/lbmetrictable/<name>` |
| Update | PUT | `http://<netscaler-ip-address>/nitro/v1/config/lbmetrictable` |
| Add | POST | `http://<netscaler-ip-address>/nitro/v1/config/lbmetrictable` |
| Enable | POST | `http://<netscaler-ip-address>/nitro/v1/config/lbmetrictable?action=enable` |
| Disable | POST | `http://<netscaler-ip-address>/nitro/v1/config/lbmetrictable?action=disable` |
| Rename | POST | `http://<netscaler-ip-address>/nitro/v1/config/lbmetrictable?action=rename` |
| Unset | POST | `http://<netscaler-ip-address>/nitro/v1/config/lbmetrictable?action=unset` |

## Fields


