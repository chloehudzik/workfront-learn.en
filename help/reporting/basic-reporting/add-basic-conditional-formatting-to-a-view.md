---
title: Add basic conditional formatting
description: Learn how to use column rules to change text color, formatting and background colors in a report or view, based on criteria you set.
activity: use
feature: Reports and Dashboards
thumbnail: 335149.jpeg
type: Tutorial
role: User
level: Beginner
team: Technical Marketing
kt: 8855
exl-id: bf9a4cf4-b073-4f7e-8516-e7843f4dc20f
doc-type: video
---
# Add basic conditional formatting to a view

Conditional formatting is done by creating column rules. Column rules allow you to format a column in a specific way based on criteria you set.

In this video, you will learn:

* What conditional formatting is in a view
* How to create and modify conditional formatting

>[!VIDEO](https://video.tv.adobe.com/v/335149/?quality=12&learn=on)

## Summary

To create conditional formatting:

1. Choose the column where you want the formatting to appear
1. Decide on what conditions you want the formatting to change
1. Decide what kind of formatting change will work best

    * background color
    * text color
    * replacement text
    * show an icon

## Activity: Add conditional formatting to a view

Create a task view named "Standard + Progress" by using the existing Standard view and adding this conditional formatting on the [!UICONTROL Name] column.

1. Add a column rule that will turn the field background red when the progress status of the task is Late.
1. Add a column rule that will turn the field background yellow when the progress status is Behind or At Risk.

This will help you spot troubled tasks without including the column for progress status as part of your view.

## Answer

![An image of the screen to create a new column rule](assets/conditional-formatting-exercise.png)

1. In a task list report, go to the **[!UICONTROL View]** drop-down menu and select **[!UICONTROL New View]**.
1. Name your view "Standard + Progress."
1. Use the default columns provided.
1. Select the [!UICONTROL Task Name] column. This is the column you want to apply the conditional formatting to, so it appears red or yellow if the progress status of the task is not On Time.
1. Click **[!UICONTROL Advanced Options]** at the top-right corner of the report builder window.
1. Click **[!UICONTROL Add a Rule for this Column]**.
1. Start the column rule by changing [!UICONTROL Task] > [!UICONTROL Name] at the top of the window to [!UICONTROL Task] > [!UICONTROL Progress Status]. Just click the **[!UICONTROL X]** icon next to [!UICONTROL Task] > [!UICONTROL Name] to delete it from the field.
1. Type "progress" in the field, then select [!UICONTROL Progress Status] under the [!UICONTROL Task] field source.
1. Select **[!UICONTROL Late]** in the field to the right of the [!UICONTROL Equal] qualifier.
1. Choose a background of red in the [!UICONTROL Text Color] row.
1. Click **[!UICONTROL Add Rule]** to save the column rule.
1. Now click **[!UICONTROL Add Column Rule]** again to add another rule.
1. Just like before, delete [!UICONTROL Task] > [!UICONTROL Name] from the criteria field. Replace it with [!UICONTROL Progress Status] under the [!UICONTROL Task] field source.
1. Select both [!UICONTROL At Risk] and [!UICONTROL Behind] in the field to the right of the Equal qualifier.
1. Choose a background of yellow in the [!UICONTROL Text Color] row.
1. Click **[!UICONTROL Add Rule]** to save the column rule.
1. Click **[!UICONTROL Save View]** to save the view.
