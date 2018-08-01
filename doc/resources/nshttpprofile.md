# Resource nshttpprofile

- [Identifier](#identifier)
- [Operations](#operations)
- [Fields](#fields)

## Identifier

Identifier : name

## Operations

| Name | Method | Url |
|----|----|----|
| List | GET | `http://<netscaler-ip-address>/nitro/v1/config/nshttpprofile` |
| Get | GET | `http://<netscaler-ip-address>/nitro/v1/config/nshttpprofile/<name>` |
| Delete | DELETE | `http://<netscaler-ip-address>/nitro/v1/config/nshttpprofile/<name>` |
| Update | PUT | `http://<netscaler-ip-address>/nitro/v1/config/nshttpprofile` |
| Add | POST | `http://<netscaler-ip-address>/nitro/v1/config/nshttpprofile` |
| Enable | POST | `http://<netscaler-ip-address>/nitro/v1/config/nshttpprofile?action=enable` |
| Disable | POST | `http://<netscaler-ip-address>/nitro/v1/config/nshttpprofile?action=disable` |
| Rename | POST | `http://<netscaler-ip-address>/nitro/v1/config/nshttpprofile?action=rename` |
| Unset | POST | `http://<netscaler-ip-address>/nitro/v1/config/nshttpprofile?action=unset` |

## Fields

| Name | Update | Type |
|----|----|----|
| name | No | string |
| reusepooltimeout | No | double |
| maxheaderlen | No | double |
| minreusepool | No | double |
| http2maxheaderlistsize | No | double |
| http2maxframesize | No | double |
| http2maxconcurrentstreams | No | double |
| http2initialwindowsize | No | double |
| http2headertablesize | No | double |
| http2minseverconn | No | double |
| apdexcltresptimethreshold | No | double |
| maxreusepool | No | double |
| incomphdrdelay | No | double |
| reqtimeout | No | double |
| reqtimeoutaction | No | string |
| clientiphdrexpr | No | string |
| maxreq | No | double |
| dropinvalreqs | No | ENABLED, DISABLED |
| markhttp09inval | No | ENABLED, DISABLED |
| markconnreqinval | No | ENABLED, DISABLED |
| cmponpush | No | ENABLED, DISABLED |
| conmultiplex | No | ENABLED, DISABLED |
| dropextracrlf | No | ENABLED, DISABLED |
| websocket | No | ENABLED, DISABLED |
| rtsptunnel | No | ENABLED, DISABLED |
| adpttimeout | No | ENABLED, DISABLED |
| dropextradata | No | ENABLED, DISABLED |
| weblog | No | ENABLED, DISABLED |
| persistentetag | No | ENABLED, DISABLED |
| spdy | No | DISABLED, ENABLED, V2, V3 |
| http2 | No | ENABLED, DISABLED |
| http2direct | No | ENABLED, DISABLED |
| altsvc | No | ENABLED, DISABLED |

