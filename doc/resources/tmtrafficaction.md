# Resource tmtrafficaction

- [Identifier](#identifier)
- [Operations](#operations)
- [Fields](#fields)

## Identifier

Identifier : name

## Operations

| Name | Method | Url |
|----|----|----|
| List | GET | `http://<netscaler-ip-address>/nitro/v1/config/tmtrafficaction` |
| Get | GET | `http://<netscaler-ip-address>/nitro/v1/config/tmtrafficaction/<name>` |
| Delete | DELETE | `http://<netscaler-ip-address>/nitro/v1/config/tmtrafficaction/<name>` |
| Update | PUT | `http://<netscaler-ip-address>/nitro/v1/config/tmtrafficaction` |
| Add | POST | `http://<netscaler-ip-address>/nitro/v1/config/tmtrafficaction` |
| Enable | POST | `http://<netscaler-ip-address>/nitro/v1/config/tmtrafficaction?action=enable` |
| Disable | POST | `http://<netscaler-ip-address>/nitro/v1/config/tmtrafficaction?action=disable` |
| Rename | POST | `http://<netscaler-ip-address>/nitro/v1/config/tmtrafficaction?action=rename` |
| Unset | POST | `http://<netscaler-ip-address>/nitro/v1/config/tmtrafficaction?action=unset` |

## Fields

| Name | Update | Type |
|----|----|----|
| name | No | string |
| apptimeout | No | double |
| sso | No | ON, OFF |
| formssoaction | No | string |
| persistentcookie | No | ON, OFF |
| initiatelogout | No | ON, OFF |
| kcdaccount | No | string |
| samlssoprofile | No | string |
| forcedtimeout | No | START, STOP, RESET |
| forcedtimeoutval | No | double |
| userexpression | No | string |
| passwdexpression | No | string |

