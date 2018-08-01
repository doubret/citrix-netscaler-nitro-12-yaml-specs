# Resource cmpaction

- [Identifier](#identifier)
- [Operations](#operations)
- [Fields](#fields)

## Identifier

Identifier : name

## Operations

| Name | Method | Url |
|----|----|----|
| List | GET | `http://<netscaler-ip-address>/nitro/v1/config/cmpaction` |
| Get | GET | `http://<netscaler-ip-address>/nitro/v1/config/cmpaction/<name>` |
| Delete | DELETE | `http://<netscaler-ip-address>/nitro/v1/config/cmpaction/<name>` |
| Update | PUT | `http://<netscaler-ip-address>/nitro/v1/config/cmpaction` |
| Add | POST | `http://<netscaler-ip-address>/nitro/v1/config/cmpaction` |
| Enable | POST | `http://<netscaler-ip-address>/nitro/v1/config/cmpaction?action=enable` |
| Disable | POST | `http://<netscaler-ip-address>/nitro/v1/config/cmpaction?action=disable` |
| Rename | POST | `http://<netscaler-ip-address>/nitro/v1/config/cmpaction?action=rename` |
| Unset | POST | `http://<netscaler-ip-address>/nitro/v1/config/cmpaction?action=unset` |

## Fields

| Name | Update | Type |
|----|----|----|
| name | No | string |
| varyheadervalue | No | string |
| addvaryheader | No | GLOBAL, DISABLED, ENABLED |
| cmptype | No | compress, gzip, deflate, nocompress |
| deltatype | No | PERURL, PERPOLICY |
