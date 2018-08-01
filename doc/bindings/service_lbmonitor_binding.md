# Binding service_lbmonitor_binding

- [Identifier](#identifier)
- [Operations](#operations)
- [Fields](#fields)

## Identifier

- name

## Operations

| Name | Method | Url |
|----|----|----|
| List | GET | `http://<netscaler-ip-address>/nitro/v1/config/service_lbmonitor_binding` |
| Get | GET | `http://<netscaler-ip-address>/nitro/v1/config/service_lbmonitor_binding/<name>` |
| Delete | DELETE | `http://<netscaler-ip-address>/nitro/v1/config/service_lbmonitor_binding/<name>` |
| Add | POST | `http://<netscaler-ip-address>/nitro/v1/config/service_lbmonitor_binding` |

## Fields

| Name | Type |
|----|----|
| monitor_name | lbmonitor.monitorname |
| monstate | string |
| name | service.name |
| passive | bool |
| weight | double |

