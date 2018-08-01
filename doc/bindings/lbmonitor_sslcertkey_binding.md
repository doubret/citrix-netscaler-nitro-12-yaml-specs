# Binding lbmonitor_sslcertkey_binding

- [Identifier](#identifier)
- [Operations](#operations)
- [Fields](#fields)

## Identifier

- monitorname
- certkeyname

## Operations

| Name | Method | Url |
|----|----|----|
| List | GET | `http://<netscaler-ip-address>/nitro/v1/config/lbmonitor_sslcertkey_binding` |
| Get | GET | `http://<netscaler-ip-address>/nitro/v1/config/lbmonitor_sslcertkey_binding/<name>` |
| Delete | DELETE | `http://<netscaler-ip-address>/nitro/v1/config/lbmonitor_sslcertkey_binding/<name>` |
| Add | POST | `http://<netscaler-ip-address>/nitro/v1/config/lbmonitor_sslcertkey_binding` |

## Fields

| Name | Type |
|----|----|
| ca | bool |
| certkeyname | string |
| crlcheck | string |
| monitorname | lbmonitor.monitorname |
| ocspcheck | string |

