# Resource pqpolicy

- [Identifier](#identifier)
- [Operations](#operations)
- [Fields](#fields)

## Identifier

Identifier : policyname

## Operations

| Name | Method | Url |
|----|----|----|
| List | GET | `http://<netscaler-ip-address>/nitro/v1/config/pqpolicy` |
| Get | GET | `http://<netscaler-ip-address>/nitro/v1/config/pqpolicy/<name>` |
| Delete | DELETE | `http://<netscaler-ip-address>/nitro/v1/config/pqpolicy/<name>` |
| Update | PUT | `http://<netscaler-ip-address>/nitro/v1/config/pqpolicy` |
| Add | POST | `http://<netscaler-ip-address>/nitro/v1/config/pqpolicy` |
| Enable | POST | `http://<netscaler-ip-address>/nitro/v1/config/pqpolicy?action=enable` |
| Disable | POST | `http://<netscaler-ip-address>/nitro/v1/config/pqpolicy?action=disable` |
| Rename | POST | `http://<netscaler-ip-address>/nitro/v1/config/pqpolicy?action=rename` |
| Unset | POST | `http://<netscaler-ip-address>/nitro/v1/config/pqpolicy?action=unset` |

## Fields

| Name | Update | Type |
|----|----|----|
| policyname | No | string |
| rule | No | string |
| priority | No | double |
| weight | No | double |
| qdepth | No | double |
| polqdepth | No | double |
