# Resource appflowaction

- [Identifier](#identifier)
- [Operations](#operations)
- [Fields](#fields)

## Identifier

Identifier : name

## Operations

| Name | Method | Url |
|----|----|----|
| List | GET | `http://<netscaler-ip-address>/nitro/v1/config/appflowaction` |
| Get | GET | `http://<netscaler-ip-address>/nitro/v1/config/appflowaction/<name>` |
| Delete | DELETE | `http://<netscaler-ip-address>/nitro/v1/config/appflowaction/<name>` |
| Update | PUT | `http://<netscaler-ip-address>/nitro/v1/config/appflowaction` |
| Add | POST | `http://<netscaler-ip-address>/nitro/v1/config/appflowaction` |
| Enable | POST | `http://<netscaler-ip-address>/nitro/v1/config/appflowaction?action=enable` |
| Disable | POST | `http://<netscaler-ip-address>/nitro/v1/config/appflowaction?action=disable` |
| Rename | POST | `http://<netscaler-ip-address>/nitro/v1/config/appflowaction?action=rename` |
| Unset | POST | `http://<netscaler-ip-address>/nitro/v1/config/appflowaction?action=unset` |

## Fields

| Name | Update | Type |
|----|----|----|
| name | No | string |
| metricslog | No | bool |
| comment | No | string |
| clientsidemeasurements | No | ENABLED, DISABLED |
| pagetracking | No | ENABLED, DISABLED |
| webinsight | No | ENABLED, DISABLED |
| securityinsight | No | ENABLED, DISABLED |
| videoanalytics | No | ENABLED, DISABLED |
| distributionalgorithm | No | ENABLED, DISABLED |
| transactionlog | No | ANOMALOUS, NONE, ALL |
| collectors | No | appflowcollector.name[] |

