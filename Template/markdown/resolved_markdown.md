# &#9989; ZABBIX ALERT RESOLVED &#9989;

## HOST INFORMATION

| &#127991;&#65039; Name: | {HOST.NAME} |
| --- | --- |
| &#128256; Proxy:        | {PROXY.NAME} |
| &#128187; IP:           | {HOST.CONN} |
| &#128221; Description:  | {HOST.DESCRIPTION} |


## EVENT DETAILS

| &#128279; Event:          | [{EVENT.NAME}]({$ZABBIX.URL}/tr_events.php?triggerid={TRIGGER.ID}&eventid={EVENT.ID}) |
| --- | --- |
| &#128680; Details:        | {TRIGGER.DESCRIPTION} |
| &#128680; Event ID:       | {EVENT.ID} |
| &#9888;&#65039; Severity: | {TRIGGER.SEVERITY} |
| &#128347; Start:          | {EVENT.TIME} from {EVENT.DATE} |
| &#128350; End:            | {EVENT.RECOVERY.TIME} from {EVENT.RECOVERY.DATE} |
| &#8987; Duration:         | {EVENT.DURATION} |
| &#128178; Event Data:     | {EVENT.OPDATA} |

> &#9203; Zabbix Alert - {{TIME}.fmttime(%Y-%m-%d %H:%M:%S)}