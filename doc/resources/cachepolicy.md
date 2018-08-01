# Resource cachepolicy

- [Identifier](#identifier)
- [Operations](#operations)
- [Fields](#fields)

## Identifier

Identifier : policyname

## Operations

| Name | Method | Url |
|----|----|----|
| List | GET | `http://<netscaler-ip-address>/nitro/v1/config/cachepolicy` |
| Get | GET | `http://<netscaler-ip-address>/nitro/v1/config/cachepolicy/<name>` |
| Delete | DELETE | `http://<netscaler-ip-address>/nitro/v1/config/cachepolicy/<name>` |
| Update | PUT | `http://<netscaler-ip-address>/nitro/v1/config/cachepolicy` |
| Add | POST | `http://<netscaler-ip-address>/nitro/v1/config/cachepolicy` |
| Enable | POST | `http://<netscaler-ip-address>/nitro/v1/config/cachepolicy?action=enable` |
| Disable | POST | `http://<netscaler-ip-address>/nitro/v1/config/cachepolicy?action=disable` |
| Rename | POST | `http://<netscaler-ip-address>/nitro/v1/config/cachepolicy?action=rename` |
| Unset | POST | `http://<netscaler-ip-address>/nitro/v1/config/cachepolicy?action=unset` |

## Fields

| Name | Update | Type |
|----|----|----|
| policyname | No | string |
| rule | No | string |
| storeingroup | No | cachecontentgroup.name |
| invalgroups | No | cachecontentgroup.name[] |
| invalobjects | No | cachecontentgroup.name[] |
| action | No | CACHE, NOCACHE, MAY_CACHE, MAY_NOCACHE, INVAL |
| undefaction | No | NOCACHE, RESET |

