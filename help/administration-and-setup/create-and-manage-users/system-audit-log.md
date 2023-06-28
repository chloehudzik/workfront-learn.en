---
title: Understand the System Audit Log
description: Learn how to use the system audit log to review when changes were made and when to items.
feature: System Setup and Administration
activity: deploy
type: Tutorial
team: Technical Marketing
role: Admin
level: Beginner, Intermediate
thumbnail: 10040.jpeg
jira: KT-10040
exl-id: 9de6fd40-10fb-47a6-b186-3a38c411f1ac
---
# Understand the system audit log

The system audit log is the system administrator’s best way to keep an eye on what’s going on in [!DNL Workfront]. Think of the log as your source of truth for who made what changes and when.

Access the audit log by going to the [!UICONTROL Preferences] section in the [!UICONTROL Setup] area. By default, you see data from the last seven days. Change the filter criteria to see data from different date ranges. 

When a user performs certain actions, [!UICONTROL Workfront] records them in the [!UICONTROL Audit Logs] section of the [!UICONTROL Setup] area.

![[!UICONTROL Log Type] drop-down menu on the [!UICONTROL Audit Logs] page in [!UICONTROL Setup]](assets/admin-fund-audit-log-1.png)

Each action recorded, or logged, shows:

* The date and time of the change
* The log type
* The name of the user who completed the action
* The object
* Any details associated with the action 
* The IP address

![[!UICONTROL Audit Log] list](assets/admin-fund-audit-log-2.JPG)

## Export the audit log

Exporting the audit log data allows system administrators to share the information with internal/external auditors or security specialists. Some organizations require certain logs be retained for compliance with cybersecurity regulations. Others need the information imported into a security system for analysis.

Audit logs can be exported in a CSV (comma-separated value) file, which can be opened into a spreadsheet application or plain text editor. The export is limited to 50,000 rows at one time, so use the filters to narrow down the list if the total exceeds 50,000.

![[!UICONTROL Export] button on [!UICONTROL Audit Logs] page](assets/admin-fund-audit-log-3.png)

<!---
learn more URLs
Audit logs
Managing audit logs
--->
