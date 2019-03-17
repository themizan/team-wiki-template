__Title__: Postmortem Template

__Date__: 1/1/1970

__Authors__: 

__Status__: (draft, complete)

__Summary__: 
A brief, high level description of the outage.

__Impact__: Impacted user(s) & systems.

__Root Causes__:

A detailed analysis of the root casuses.

__Trigger__:

What event triggered the outage.

__Detection Time__: 1/1/1970 12:01pm EST 

__Resolution Time__: 1/1/1970 12:11pm EST 

__Timeline__:

| Timestamp (include timezone) | Event  |
| ---------------------------- | -------|
| 1/1/1970 12:01pm EST         | Outage detected. |

__Resolution__

A thorough explanation of the actions taken to resolve/mitigate the issue. More involved updates can be tracked as action items below.

__Action Items__:
|Action Item | Type | Owner | Bug |
|------------|------|-------|-----|
| Delete excess log files | mitigate | jschmo | [#123456](https://tickets.localhost/ticket/123456) |
| Configure log rotation | prevent  | jschmo | [#654321](https://tickets.localhost/ticket/654321) |
| Add logfile rotation to lifecycle considerations | process | jschmo | [#456123](https://tickets.localhost/ticket/456123) |

## Lessons Learned

### What went well
Outage occurred on the weekend

### What went wrong

Logs from 14 years back filled the harddrive and caused the webserver to stop responding.


