---
title: Understand basic text mode for filters
description: Learn what text mode is, what camel case is, and some basic “plug and play” text mode you can use in your report filters in Workfront.
activity: use
feature: Reports and Dashboards
thumbnail: 336820.png
type: Tutorial
role: User
level: Intermediate
team: Technical Marketing
kt: 9086
exl-id: b3f16468-b720-468d-887a-b313fc32bd89
---
# Understand basic text mode for filters

>[!IMPORTANT]
>
>Prerequisites:
>
>* Understand reporting elements
>* Understand reporting components
>* Create a basic filter

>[!TIP]
>
>* To gain a more in depth understanding of text mode we recommend watching the recorded webinar event [Ask the Expert - Introduction to Text Mode Reporting](https://experienceleague.adobe.com/docs/workfront-events/events/reporting-and-dashboards/introduction-to-text-mode-reporting.html?lang=en), which is one hour in length.
>* To learn even more about text mode we recommend watching the [Advanced reporting](https://experienceleague.adobe.com/docs/workfront-learn/tutorials-workfront/reporting/advanced-reporting/welcome-to-advanced-reporting.html?lang=en) tutorials, which together are five and a half hours in length.


In this video, you will learn:

* What text mode is 
* What camel case is 
* Some basic “plug and play” text mode you can use in your report filters 

>[!VIDEO](https://video.tv.adobe.com/v/336820/?quality=12)


## Task - Filter out tasks where I've marked "Done with my part"

The following text mode will exclude tasks where a user has marked "Done with My Part." All you have to do is create a task filter, add any filter rules you want, then switch to text mode and paste the code below after any text mode you see in the filter.

```
EXISTS:1:$$OBJCODE=ASSGN  
EXISTS:1:taskID=FIELD:ID  
EXISTS:1:status=DN  
EXISTS:1:status_Mod=notin  
EXISTS:1:assignedToID=$$USER.ID 
```

## Task - Show me all tasks awaiting my approval

```
approvalProcessID_Mod=notblank
currentUserApproversMM:ID=$$USER.ID
currentUserApproversMM:ID_Mod=in
currentUserApproversMM_Join=allowingnull
```

## Task - Show me all tasks I have approved

Create a task report with whatever filters you want, then go to the Filter tab and click on Switch to Text Mode. Add this code to whatever is already there:

```
approvalProcessID_Mod=notblank
approverStatuses:approvedByID=$$USER.ID
approverStatuses:approvedByID_Mod=in
```

## Task - Show me all tasks that have at least one cross project predecessor

```
predecessorsMM:ID_Mod=notblank
predecessorsMM:projectID=FIELD:projectID
predecessorsMM:projectID_Mod=ne
```

## Task - Show me all tasks I assigned to others

Create a task report with whatever filters you want, then go to the Filter tab and click on Switch to Text Mode. Add this code to whatever is already there:

```
EXISTS:1:$$OBJCODE=ASSGN
EXISTS:1:taskID=FIELD:ID
EXISTS:1:assignedByID=$$USER.ID
```

This will show you all tasks where the logged in user assigned at least one of the current assignees. If assignees were assigned by multiple people only the name of the first person who assigned someone will appear as "Requested By" on the task landing page.

## Task - Show me all tasks that are Complete - Pending Approval

```
status=CPL:A
status_Mod=in
```


## Issue - Show me all issues that are Complete - Pending Approval

```
status=CPL:A
status_Mod=in
```


## Project - Show me all projects that are Complete - Pending Approval

```
status=CPL:A
status_Mod=in
```


## Note - Show me all comments I’m tagged in

```
tags:userID=$$USER.ID
tags:userID_Mod=in
```


## Parameter/Custom Field Report - Show me custom fields that are not attached to a custom form (very useful in cleanup efforts)

```
EXISTS:A:$$EXISTSMOD=NOTEXISTS
EXISTS:A:$$OBJCODE=CTGYPA
EXISTS:A:parameterID=FIELD:ID
```
