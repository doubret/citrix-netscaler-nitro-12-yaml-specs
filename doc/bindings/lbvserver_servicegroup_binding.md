# Binding lbvserver_servicegroup_binding

- [Identifier](#identifier)
- [Operations](#operations)
- [Fields](#fields)

## Identifier

- name
- servicegroupname

## Operations

| Name | Method | Url |
|----|----|----|
| List | GET | `http://<netscaler-ip-address>/nitro/v1/config/lbvserver_servicegroup_binding` |
| Get | GET | `http://<netscaler-ip-address>/nitro/v1/config/lbvserver_servicegroup_binding/<name>` |
| Delete | DELETE | `http://<netscaler-ip-address>/nitro/v1/config/lbvserver_servicegroup_binding/<name>` |
| Add | POST | `http://<netscaler-ip-address>/nitro/v1/config/lbvserver_servicegroup_binding` |

## Fields

| Name | Type |
|----|----|
| name | lbvserver.name |
| servicegroupname | servicegroup.servicegroupname |
| weight | double |

