# DashboardTemplates
Dynatrace Dashboards that are generic enough to use as a starting point with any customer.<br />  
They are not limited to specific entities and work well with Management Zones.<br />

If you would like to view these dashboards, I can give you readonly access to my personal tenant.<br />

Screenshots:
![Overview](images/Overview.png)
![Applications](images/Applications.png)
![Synthetics](images/Synthetics.png)
![Services](images/Services.png)
![Databases](images/Databases.png)
![Hosts](images/Hosts.png)
![Processes](images/Processes.png)
![Java](images/Java.png)
![.NET](images/.NET.png)
![Tomcat](images/Tomcat.png)

The following list will help you identify dashboards by ID:<br />
00000000-dddd-bbbb-ffff-000000000001 TEMPLATE: Overview<br />
00000000-dddd-bbbb-ffff-000000000002 TEMPLATE: Applications<br />
00000000-dddd-bbbb-ffff-000000000003 TEMPLATE: Synthetics<br />
00000000-dddd-bbbb-ffff-000000000004 TEMPLATE: Services<br />
00000000-dddd-bbbb-ffff-000000000005 TEMPLATE: Databases<br />
00000000-dddd-bbbb-ffff-000000000006 TEMPLATE: Hosts<br />
00000000-dddd-bbbb-ffff-000000000007 TEMPLATE: Processes<br />
00000000-dddd-bbbb-ffff-000000000008 TEMPLATE: Java Monitoring<br />
00000000-dddd-bbbb-ffff-000000000009 TEMPLATE: .NET Monitoring<br />
00000000-dddd-bbbb-ffff-000000000010 TEMPLATE: Tomcat Monitoring<br />

Notes: <br />
The Overview dashboard provides drilldowns to child dashboards via markdown tiles.<br />
You might want to modify the owner to your email address or a customer email address.<br />
Version differences can be an issue, so select the most recent version equal or prior to the version of the cluster/tenant you are importing into. <br />
Always use PUT rather than POST as the IDs are designed to remain static and PUT allows that. <br />
