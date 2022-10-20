---
title: Understand basic text mode for filters
description: Learn what text mode is, what camel case is, and some basic “plug and play” text mode you can use in your report filters in [!DNL  Workfront].
activity: use
feature: Reports and Dashboards
thumbnail: 336820.png
type: Tutorial
role: User
level: Intermediate
team: Technical Marketing
kt: 9086
last-substantial-update tag: 2022-09-29
exl-id: b3f16468-b720-468d-887a-b313fc32bd89
---
# Understand basic text mode for filters

In this video, you will learn:

* What text mode is 
* What camel case is 
* Some basic “plug and play” text mode you can use in your report filters 

>[!VIDEO](https://video.tv.adobe.com/v/336820/?quality=12)

The following text mode will exclude tasks where a user has marked "Done with My Part." All you have to do is create a task filter, add any filter rules you want, then switch to text mode and paste the code below after any text mode you see in the filter.

```
EXISTS:1:$$OBJCODE=ASSGN  
EXISTS:1:taskID=FIELD:ID  
EXISTS:1:status=DN  
EXISTS:1:status_Mod=notin  
EXISTS:1:assignedToID=$$USER.ID 
```

## Activity: Text mode questions

1. How would you write the camel case for the field titled “Entered By ID”? 
1. In an Issue report, create a filter to show issues that have been marked as closed but are pending approval. 

## Answers 

1. The camel case for the field “Entered By ID” should be written like this—enteredByID 
1. The text mode should look like this in the issue report filter: 

   ![An image of the screen to create a new filter in text mode](assets/btm-answer.png)
