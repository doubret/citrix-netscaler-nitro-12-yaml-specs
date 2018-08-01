# Binding service_scpolicy_binding

- [Identifier](#identifier)
- [Operations](#operations)
- [Fields](#fields)

## Identifier

- name
- policyname

## Operations

| Name | Method | Url |
|----|----|----|
| List | GET | `http://<netscaler-ip-address>/nitro/v1/config/service_scpolicy_binding` |
| Get | GET | `http://<netscaler-ip-address>/nitro/v1/config/service_scpolicy_binding/<name>` |
| Delete | DELETE | `http://<netscaler-ip-address>/nitro/v1/config/service_scpolicy_binding/<name>` |
| Add | POST | `http://<netscaler-ip-address>/nitro/v1/config/service_scpolicy_binding` |

## Fields

| Name | Type |
|----|----|
| name | service.name |
| policyname | scpolicy.name |

