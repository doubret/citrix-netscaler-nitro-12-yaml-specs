# Binding servicegroup_servicegroupmember_binding

- [Identifier](#identifier)
- [Operations](#operations)
- [Fields](#fields)

## Identifier

- servicegroupname
- servername
- port

## Operations

| Name | Method | Url |
|----|----|----|
| List | GET | `http://<netscaler-ip-address>/nitro/v1/config/servicegroup_servicegroupmember_binding` |
| Get | GET | `http://<netscaler-ip-address>/nitro/v1/config/servicegroup_servicegroupmember_binding/<name>` |
| Delete | DELETE | `http://<netscaler-ip-address>/nitro/v1/config/servicegroup_servicegroupmember_binding/<name>` |
| Add | POST | `http://<netscaler-ip-address>/nitro/v1/config/servicegroup_servicegroupmember_binding` |

## Fields

| Name | Type |
|----|----|
| port | int |
| servername | string |
| servicegroupname | string |
| weight | double |

