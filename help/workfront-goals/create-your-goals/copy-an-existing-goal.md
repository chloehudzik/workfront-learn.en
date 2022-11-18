---
title: Copy an Existing Goal
description: Learn how to copy an existing goal in [!DNL Workfront Goals].
activity: use
team: Technical Marketing
feature: Workfront Goals
type: Tutorial
role: User
level: Beginner
kt: 10121
exl-id: bf9ac10a-8419-458b-b4e8-bedb0ad3b98f
---
# Copy an Existing Goal

Let's say it's the end of a quarter and you want to recreate an existing goal for the next period. Or maybe you didn't complete the goal and need to extend into the next time period. What is the best option to create that goal? You'll want to copy and modify an existing goal.

Copying an existing goal also is useful if multiple team members have similar goals and you need to create one goal for each of them.

<!--
Pro-tips graphic
-->

Here are a few things to consider before copying goals:

* All of the information from the original goal will be copied, with the exception of the goal period (because it is in the past).
* You can copy results of an existing goal and they will transfer to the new goal.
* Copied results are assigned to the same owner, by default.
* You cannot copy progress of the existing goal to a new goal.
* You cannot copy the activities of a goal when you copy a goal.

## How to copy a goal

1. Click a goal name to open the **[!UICONTROL Goal Details]** panel.
1. Click the 3-dot icon, then select **[!UICONTROL Copy]**.
1. Update any of the following information for the copied goal:
    * **New Goal**—This is the name of the new goal. The default is the name of the original goal.
    * **Period**—The time period during which you want to achieve the goal. Select a time period from the drop-down menu or click Define custom dates to indicate a custom time period. The default period is always the current quarter.
    * **Owner**—The owner of the goal. This can be a user, team, group, or company. The default is the owner of the original goal.
    * **Description**—Additional information about the goal.

1. Check the **[!UICONTROL Copy results]** box if the original goal had results added to it and you want to copy them to the new goal. The results of the copied goal have the same owner, names, and measured values as the results of the original goal.

1. Click **[!UICONTROL Save]**. The copied goal is saved with a status of Draft.

    ![An image of the [!UICONTROL Goal Details] panel in [!DNL Workfront Goals] with the [!UICONTROL Copy] option](assets/03-workfront-goals-copy-a-goal.png)

1. Click **[!UICONTROL Activate]**, which updates the goal status to Active. The goal must have an associated activity or result in order to "activate."

1. Click the **X** in the upper-right of the [!UICONTROL Goal Details] panel to close it.

If you copied a goal that was not completed in a previous time period and want to continue working on it in the following time period, do the following:

1. Go to the original goal in the **[!UICONTROL Goal List]**, **[!UICONTROL Check-in]** section, or **[!UICONTROL Pulse]** section.
1. Comment on the goal to indicate it was copied and a more current goal was created.
1. Close the original goal to preserve the progress made during its original time period. Click the 3-dot icon in the **[!UICONTROL Goal Details]** panel and select **[!UICONTROL Close]** from the menu.
1. Update the [!UICONTROL Initial] value of the new result to match the **[!UICONTROL Target]** value of the previous result, so your new goal progress starts calculating from the point achieved in the previous period.
