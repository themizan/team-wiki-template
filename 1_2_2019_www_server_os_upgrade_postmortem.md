__Title__: www server os upgrade

__Date__: 1/2/2019

__Authors__: jschmo 

__Status__: complete

__Summary__: 
The existing webserver is IIS running on Windows Me. The content is to be migrated to a CentOS 7 server running nginx.

__Impact__: All users of public facing www site.

__Root Causes__:

N/A

__Trigger__:

Windows Me has been EOL for over a decade.

__Detection Time__: 

__Resolution Time__: 1/2/2019 12:11pm EST 

__Timeline__:

| Timestamp (include timezone) | Event  |
| ---------------------------- | -------|
| 12/31/2003       | EOL of Windows Me platform. |
| 12/3/2018                    | Decision made to upgrade platform. |
| 12/21/2018       | Migration plan approved. |
| 1/1/2019 12:01pm EST         | Migration begins. |
| 1/2/2019 12:01pm EST         | Migration successful. |


__Resolution__

A thorough explanation of the actions taken to resolve/mitigate the issue. More involved updates can be tracked as action items below.

__Action Items__:
|Action Item | Type | Owner | Bug |
|------------|------|-------|-----|
| Migrate www server | prevent | jschmo | [#123456](https://tickets.localhost/ticket/123456) |


## Lessons Learned

### What went well
Migration plan went smoothly.

### What went wrong

We had a webserver running on Windows Me.


