# Resource feoaction

- [Identifier](#identifier)
- [Operations](#operations)
- [Fields](#fields)

## Identifier

Identifier : name

## Operations

| Name | Method | Url |
|----|----|----|
| List | GET | `http://<netscaler-ip-address>/nitro/v1/config/feoaction` |
| Get | GET | `http://<netscaler-ip-address>/nitro/v1/config/feoaction/<name>` |
| Delete | DELETE | `http://<netscaler-ip-address>/nitro/v1/config/feoaction/<name>` |
| Update | PUT | `http://<netscaler-ip-address>/nitro/v1/config/feoaction` |
| Add | POST | `http://<netscaler-ip-address>/nitro/v1/config/feoaction` |
| Enable | POST | `http://<netscaler-ip-address>/nitro/v1/config/feoaction?action=enable` |
| Disable | POST | `http://<netscaler-ip-address>/nitro/v1/config/feoaction?action=disable` |
| Rename | POST | `http://<netscaler-ip-address>/nitro/v1/config/feoaction?action=rename` |
| Unset | POST | `http://<netscaler-ip-address>/nitro/v1/config/feoaction?action=unset` |

## Fields

| Name | Update | Type |
|----|----|----|
| name | No | string |
| pageextendcache | No | bool |
| cachemaxage | No | double |
| imgshrinktoattrib | No | bool |
| imggiftopng | No | bool |
| imgtowebp | No | bool |
| imgtojpegxr | No | bool |
| imginline | No | bool |
| cssimginline | No | bool |
| jpgoptimize | No | bool |
| imglazyload | No | bool |
| cssminify | No | bool |
| cssinline | No | bool |
| csscombine | No | bool |
| convertimporttolink | No | bool |
| jsminify | No | bool |
| jsinline | No | bool |
| htmlminify | No | bool |
| cssmovetohead | No | bool |
| jsmovetoend | No | bool |
| domainsharding | No | string |
| dnsshards | No | string[] |
| clientsidemeasurements | No | bool |

