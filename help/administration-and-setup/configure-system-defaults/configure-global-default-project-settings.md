---
title: Configure Global Default Project Settings
description: Learn how to change a custom status, set global project preferences, and create schedules that are global default settings.
feature: System Setup and Administration
role: Admin
level: Intermediate
activity: deploy
type: Tutorial
team: Technical Marketing
thumbnail: 335065.png
kt: 8753
exl-id: b961ba8c-9597-4ed4-a6d7-79689c8e290d
doc-type: video
---
# Configure global default project settings

<!---
21.4 updates have been made
--->

In this video, you will learn how to:

* Change a custom status
* Set global project preferences
* Create and use schedules

>[!VIDEO](https://video.tv.adobe.com/v/335065/?quality=12&learn=on)

## Global and group project, task, and issue settings

When you open the [!UICONTROL Projects] settings in [!DNL Workfront], you’ll notice it says “[!UICONTROL System Project Preferences]” in the search bar at the top of the window. This lets you know these settings affect everyone in your [!DNL Workfront] system — it's a global configuration.

![[!UICONTROL Project Preferences] page in [!UICONTROL Setup]](assets/admin-fund-system-project-preferences-1.png)

You’ll see something similar when you open the [!UICONTROL Tasks & Issues] settings.

![[!UICONTROL Task & Issue Preferences] in [!UICONTROL Setup]](assets/admin-fund-task-issue-preferences-2.png)

However, it’s possible that not every group in [!DNL Workfront] needs the same project, task, and issue preferences. For example, the marketing group wants a new project’s status to be Planning while the project manager group prefers the Request status.

[!DNL Workfront] allows group administrators to adjust certain project, task, and issue preferences for their groups. Which preferences can be adjusted are determined by the [!DNL Workfront] system administrator using the lock/unlock toggles.

Start by navigating to the [!UICONTROL Setup] area:

1. Select **[!UICONTROL Setup]** in the **[!UICONTROL Main Menu]**.
1. Expand **[!UICONTROL Project Preferences]** in the left menu.
1. Select **[!UICONTROL Projects]** or **[!UICONTROL Tasks & Issues]**, depending on which settings you want to modify.
 
Lock a preference to prevent group administrators from adjusting that setting for their group.

![Locked preference message](assets/admin-fund-preferences-locked-3.png)

Unlock the preference to make it available for group admins to customize.

![Unlocked preference message](assets/admin-fund-preferences-unlocked-4.png)

Some settings cannot be unlocked and remain global system settings.

![Locked preference message](assets/admin-fund-preferences-always-locked-5.png)

### Set group and subgroup preferences

For any settings unlocked by the system administrator, the group administrators can make adjustments for the group(s) they manage and any subgroups nested under those groups. In addition, group administrators can control which settings their subgroup administrators can modify. 

1. Select **[!UICONTROL Setup]** in the **[!UICONTROL Main Menu]**.
1. Click **[!DNL Groups]** in the left menu.
1. Click the group or subgroup name to open it.
1. Select **[!UICONTROL Project Preferences]** or **[!UICONTROL Tasks & Issues Preferences]** in the left menu.
1. Make the changes needed for each of the preferences that has been unlocked.
1. Select **[!UICONTROL Save]**.

![[!UICONTROL Project Status] section on [!UICONTROL Group] page](assets/admin-fund-group-preferences.png)

If your organization isn’t using group administrators, the system administrator can manage the preference settings for the different groups. 

<!---
learn more URLs and guides
Create or edit a group status 
Group administrators 
Configure system-wide project preferences 
Configure project preferences for a group 
Configure task and issue preferences for a group 
Create and modify a group’s schedule 
--->
