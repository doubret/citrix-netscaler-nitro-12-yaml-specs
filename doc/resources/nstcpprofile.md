# Resource nstcpprofile

- [Identifier](#identifier)
- [Operations](#operations)
- [Fields](#fields)

## Identifier

Identifier : name

## Operations

| Name | Method | Url |
|----|----|----|
| List | GET | `http://<netscaler-ip-address>/nitro/v1/config/nstcpprofile` |
| Get | GET | `http://<netscaler-ip-address>/nitro/v1/config/nstcpprofile/<name>` |
| Delete | DELETE | `http://<netscaler-ip-address>/nitro/v1/config/nstcpprofile/<name>` |
| Update | PUT | `http://<netscaler-ip-address>/nitro/v1/config/nstcpprofile` |
| Add | POST | `http://<netscaler-ip-address>/nitro/v1/config/nstcpprofile` |
| Enable | POST | `http://<netscaler-ip-address>/nitro/v1/config/nstcpprofile?action=enable` |
| Disable | POST | `http://<netscaler-ip-address>/nitro/v1/config/nstcpprofile?action=disable` |
| Rename | POST | `http://<netscaler-ip-address>/nitro/v1/config/nstcpprofile?action=rename` |
| Unset | POST | `http://<netscaler-ip-address>/nitro/v1/config/nstcpprofile?action=unset` |

## Fields

| Name | Update | Type |
|----|----|----|
| name | No | string |
| ws | No | ENABLED, DISABLED |
| sack | No | ENABLED, DISABLED |
| wsval | No | double |
| nagle | No | ENABLED, DISABLED |
| ackonpush | No | ENABLED, DISABLED |
| mss | No | double |
| maxburst | No | double |
| initialcwnd | No | double |
| delayedack | No | double |
| oooqsize | No | double |
| maxpktpermss | No | double |
| pktperretx | No | double |
| minrto | No | double |
| slowstartincr | No | double |
| buffersize | No | double |
| syncookie | No | ENABLED, DISABLED |
| kaprobeupdatelastactivity | No | ENABLED, DISABLED |
| flavor | No | Default, Westwood, BIC, CUBIC, Nile |
| dynamicreceivebuffering | No | ENABLED, DISABLED |
| ka | No | ENABLED, DISABLED |
| kaconnidletime | No | double |
| kamaxprobes | No | double |
| kaprobeinterval | No | double |
| sendbuffsize | No | double |
| mptcp | No | ENABLED, DISABLED |
| establishclientconn | No | AUTOMATIC, CONN_ESTABLISHED, ON_FIRST_DATA |
| tcpsegoffload | No | AUTOMATIC, DISABLED |
| rstwindowattenuate | No | ENABLED, DISABLED |
| rstmaxack | No | ENABLED, DISABLED |
| spoofsyndrop | No | ENABLED, DISABLED |
| ecn | No | ENABLED, DISABLED |
| mptcpdropdataonpreestsf | No | ENABLED, DISABLED |
| mptcpfastopen | No | ENABLED, DISABLED |
| mptcpsessiontimeout | No | double |
| timestamp | No | ENABLED, DISABLED |
| dsack | No | ENABLED, DISABLED |
| ackaggregation | No | ENABLED, DISABLED |
| frto | No | ENABLED, DISABLED |
| maxcwnd | No | double |
| fack | No | ENABLED, DISABLED |
| tcpmode | No | TRANSPARENT, ENDPOINT |
| tcpfastopen | No | ENABLED, DISABLED |
| hystart | No | ENABLED, DISABLED |
| dupackthresh | No | double |
| burstratecontrol | No | DISABLED, FIXED, DYNAMIC |
| tcprate | No | double |
| rateqmax | No | double |
| drophalfclosedconnontimeout | No | ENABLED, DISABLED |
| dropestconnontimeout | No | ENABLED, DISABLED |

