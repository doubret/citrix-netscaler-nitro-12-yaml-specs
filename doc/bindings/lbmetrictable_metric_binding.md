# Binding lbmetrictable_metric_binding

- [Identifier](#identifier)
- [Operations](#operations)
- [Fields](#fields)

## Identifier

- metrictable
- metric

## Operations

| Name | Method | Url |
|----|----|----|
| List | GET | `http://<netscaler-ip-address>/nitro/v1/config/lbmetrictable_metric_binding` |
| Get | GET | `http://<netscaler-ip-address>/nitro/v1/config/lbmetrictable_metric_binding/<name>` |
| Delete | DELETE | `http://<netscaler-ip-address>/nitro/v1/config/lbmetrictable_metric_binding/<name>` |
| Add | POST | `http://<netscaler-ip-address>/nitro/v1/config/lbmetrictable_metric_binding` |

## Fields

| Name | Type |
|----|----|
| metric | string |
| metrictable | lbmetrictable.metrictable |
| snmpoid | string |

