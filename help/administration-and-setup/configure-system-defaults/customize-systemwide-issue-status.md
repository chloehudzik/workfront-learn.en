---
title: Customize System-Wide Issue Statuses
description: Learn how to change issue status names, control the issue types a status is used for, and lock/unlock statuses for group-level customization.
feature: System Setup and Administration
activity: deploy
type: Tutorial
team: Technical Marketing
role: Admin
level: Intermediate, Experienced
jira: KT-10030
exl-id: c8f5677f-8d9d-4d1a-a1e3-d1a438878213
---
# Customize system-wide statuses

[!DNL Workfront] provides a variety of default statues to accommodate your organization’s issue management workflows. These statuses can be renamed to match your organization’s terminology. And statuses can be assigned to specific issue types. 

Additional statuses can be created, if needed. Only system administrators can create system-wide statuses. In addition, system administrators control which statuses can be edited by group administrators.

![[!UICONTROL Issues] tab on [!UICONTROL Statues] page in [!UICONTROL Setup]](assets/admin-fund-all-issue-statuses.png)

## Modify existing statuses

[!DNL Workfront] recommends a minimum number of statuses. This makes choosing the right status easier for users and results in a shorter list of statuses to maintain.

You can edit an existing status to change the name, what issue types it is assigned to, the related color, etc.

![Issue status list with [!UICONTROL Edit] option highlighted](assets/admin-fund-edit-issue-status.png)

1. Click **[!UICONTROL Setup]** in the **[!UICONTROL Main Menu]**.
1. Expand the **[!UICONTROL Project Preferences]** section in the left menu panel.
1. Select **[!UICONTROL Statuses]**.
1. Select the **[!UICONTROL Issues]** tab and make sure [!UICONTROL System Statuses] shows in the upper-right corner.
1. Select **[!UICONTROL Master List]** to see the statuses for all issue types. This is where you create or modify an issue status.
1. Hover over the right side of the status you’d like to rename and click **[!UICONTROL Edit]**.
1. Give the status a new name or change any of the other information, as desired.
1. Lock the status if these settings should apply to all users in your [!DNL Workfront] instance.
1. Unlock the status to allow group administrators to edit the status only for their groups.
1. Check the boxes for the issue type the status should apply to.
1. Click **[!UICONTROL Save]**.

![Window for creating a new status](assets/admin-fund-edit-issue-status-2.png)

### Status assignments

Not all statuses may be assigned to all issue types. The [!UICONTROL Statuses] page has columns showing which issue type each status can be used for.

![Change Order highlighted on Issues tab of Statuses page](assets/admin-fund-issue-type-statuses.png)


To see just the statuses assigned to a specific issue type, just click the issue type name at the top of the window.

![[!UICONTROL Issue] tab of [!UICONTROL Status] page with columns highlighted](assets/admin-fund-statuses-issue-type.png)

From here, you can drag and drop the issues into the order you want them to appear in the [!UICONTROL Status] drop-down menu.

To edit the statuses, you’ll need to go back to the [!UICONTROL Master List].
