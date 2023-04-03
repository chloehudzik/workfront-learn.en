---
title: Create custom prompts
description: Learn what a custom prompt is, how to create a custom prompt using text mode, and some examples that you can use in reporting in Workfront.
activity: use
feature: Reports and Dashboards
thumbnail: 336822.png
type: Tutorial
role: User
level: Intermediate
team: Technical Marketing
kt: 9087
exl-id: 1bb0832e-e888-4154-b78d-24c6d69f629f
doc-type: video
---
# Create custom prompts

In this video, you will learn:

* What a custom prompt is  
* How to create a custom prompt using text mode  
* Some examples that you can use in your reporting 

>[!VIDEO](https://video.tv.adobe.com/v/336822/?quality=12&learn=on)

## Activity: Create custom prompts

1. Create a custom prompt that shows the following project statuses in the prompt drop-down menu:
   * Planning 
   * Current 
   * Completed 
   * Dead 
1. Modify the prompt to show current projects that are due this month. 
 
## Answers 

1. Your custom prompts should look similar to this and have the following text mode: 

   ![An image of the screen to create a new filter in text mode](assets/cp-01.png)

   Once you save the custom prompt, the prompt drop-down menu should look like this: 

1.  The text mode in your custom prompt should look like this: 

   ![An image of the screen to create a new filter in text mode](assets/cp-02.png)

```
   status=CUR&plannedCompletionDate=$$TODAYbm&plannedCompletionDate_Mod=between&plannedCompletionDate_Range=$$TODAYem 
```

   And the drop-down label for active prompts should be updated to reflect the change in the code like this: 

   ![An image of the screen to create a new filter in text mode](assets/cp-02a.png)
