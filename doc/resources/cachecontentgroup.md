# Resource cachecontentgroup

- [Identifier](#identifier)
- [Operations](#operations)
- [Fields](#fields)

## Identifier

Identifier : name

## Operations

| Name | Method | Url |
|----|----|----|
| List | GET | `http://<netscaler-ip-address>/nitro/v1/config/cachecontentgroup` |
| Get | GET | `http://<netscaler-ip-address>/nitro/v1/config/cachecontentgroup/<name>` |
| Delete | DELETE | `http://<netscaler-ip-address>/nitro/v1/config/cachecontentgroup/<name>` |
| Update | PUT | `http://<netscaler-ip-address>/nitro/v1/config/cachecontentgroup` |
| Add | POST | `http://<netscaler-ip-address>/nitro/v1/config/cachecontentgroup` |
| Enable | POST | `http://<netscaler-ip-address>/nitro/v1/config/cachecontentgroup?action=enable` |
| Disable | POST | `http://<netscaler-ip-address>/nitro/v1/config/cachecontentgroup?action=disable` |
| Rename | POST | `http://<netscaler-ip-address>/nitro/v1/config/cachecontentgroup?action=rename` |
| Unset | POST | `http://<netscaler-ip-address>/nitro/v1/config/cachecontentgroup?action=unset` |

## Fields

| Name | Update | Type |
|----|----|----|
| name | No | string |
| weakposrelexpiry | No | double |
| heurexpiryparam | No | double |
| relexpiry | No | double |
| relexpirymillisec | No | double |
| absexpiry | No | string[] |
| absexpirygmt | No | string[] |
| weaknegrelexpiry | No | double |
| hitparams | No | string[] |
| invalparams | No | string[] |
| ignoreparamvaluecase | No | YES, NO |
| matchcookies | No | YES, NO |
| invalrestrictedtohost | No | YES, NO |
| polleverytime | No | YES, NO |
| ignorereloadreq | No | YES, NO |
| removecookies | No | YES, NO |
| prefetch | No | YES, NO |
| prefetchperiod | No | double |
| prefetchperiodmillisec | No | double |
| prefetchmaxpending | No | double |
| flashcache | No | YES, NO |
| expireatlastbyte | No | YES, NO |
| insertvia | No | YES, NO |
| insertage | No | YES, NO |
| insertetag | No | YES, NO |
| cachecontrol | No | string |
| quickabortsize | No | double |
| minressize | No | double |
| maxressize | No | double |
| memlimit | No | double |
| ignorereqcachinghdrs | No | YES, NO |
| minhits | No | int |
| alwaysevalpolicies | No | YES, NO |
| persistha | No | YES, NO |
| pinned | No | YES, NO |
| lazydnsresolve | No | YES, NO |
| hitselector | No | string |
| invalselector | No | string |
| type | No | HTTP, MYSQL, MSSQL |

