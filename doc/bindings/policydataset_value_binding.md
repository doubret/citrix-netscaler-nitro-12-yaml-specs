# Binding policydataset_value_binding

- [Identifier](#identifier)
- [Operations](#operations)
- [Fields](#fields)

## Identifier

- name
- value

## Operations

| Name | Method | Url |
|----|----|----|
| List | GET | `http://<netscaler-ip-address>/nitro/v1/config/policydataset_value_binding` |
| Get | GET | `http://<netscaler-ip-address>/nitro/v1/config/policydataset_value_binding/<name>` |
| Delete | DELETE | `http://<netscaler-ip-address>/nitro/v1/config/policydataset_value_binding/<name>` |
| Add | POST | `http://<netscaler-ip-address>/nitro/v1/config/policydataset_value_binding` |

## Fields

| Name | Type |
|----|----|
| index | double |
| name | policydataset.name |
| value | string |

