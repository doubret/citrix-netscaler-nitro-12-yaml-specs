# Binding lbmonitor_metric_binding

- [Identifier](#identifier)
- [Operations](#operations)
- [Fields](#fields)

## Identifier

- monitorname
- metric

## Operations

| Name | Method | Url |
|----|----|----|
| List | GET | `http://<netscaler-ip-address>/nitro/v1/config/lbmonitor_metric_binding` |
| Get | GET | `http://<netscaler-ip-address>/nitro/v1/config/lbmonitor_metric_binding/<name>` |
| Delete | DELETE | `http://<netscaler-ip-address>/nitro/v1/config/lbmonitor_metric_binding/<name>` |
| Add | POST | `http://<netscaler-ip-address>/nitro/v1/config/lbmonitor_metric_binding` |

## Fields

| Name | Type |
|----|----|
| metric | string |
| metricthreshold | double |
| metricweight | double |
| monitorname | lbmonitor.monitorname |

