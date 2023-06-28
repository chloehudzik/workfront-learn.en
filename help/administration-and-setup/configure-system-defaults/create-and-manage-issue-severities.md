---
title: Create and Manage Issue Severities
description: Learn how to set up and manage issue severities.
feature: System Setup and Administration
activity: deploy
type: Tutorial
team: Technical Marketing
role: Admin
level: Intermediate, Experienced
jira: KT-10020
exl-id: a5a9280b-0d48-413d-92de-f6a949e6b210
---
# Create and manage issue severities

## Introduction to issue severities

A severity can be used to indicate how severe an issue is or how it might impact the work being done.

![[!UICONTROL Severity] menu in the [!UICONTROL Issue Details] window](assets/admin-fund-severity-issue-details.png)

The [!UICONTROL Severity] field can be accessed in the [!UICONTROL Issue Details]. It can also be included in column views on lists and in custom reports.

[!DNL Workfront] has five default severities:

* [!UICONTROL Cosmetic]
* [!UICONTROL Causes Confusion]
* [!UICONTROL Bug with workaround]
* [!UICONTROL Bug with no workaround]
* [!UICONTROL Fatal error]

System administrators can rename these default severities or create new ones, if needed.

Severities are available only for issues in [!DNL Workfront].

## Create and manage issue severities

As the system administrator, you can create new severities, if needed, to complete the workflow of the issue.

![[!UICONTROL Severities] page in [!UICONTROL Setup]](assets/admin-fund-severity-section.png)

1. Click **[!UICONTROL Setup]** in the **[!UICONTROL Main Menu]**.
1. Expand the **[!UICONTROL Project Preferences]** section in the left menu panel.
1. Select **[!UICONTROL Severities]**.
1. Click **[!UICONTROL Add a New Severity]**.
1. Give the severity a name that matches its intended use.
1. The **[!UICONTROL Importance]** number matches the seriousness of the issue. The highest number corresponds with the highest severity. The [!UICONTROL Importance] number must be unique.
1. Select a color for your priority. This is used in chart reports and other places in [!DNL Workfront].
1. Designate one of the severity options as the **[!UICONTROL Default Severity]**. This is applied automatically to all new issues in Workfront.
1. Include a description of the severity, such as how it will be used.
1. Click outside of the fields to save.

![[!UICONTROL Severities] list](assets/admin-fund-severity-new.png)

### Modifying severities

If a severity no longer becomes relevant to your issue workflows, it can be renamed, hidden, or deleted.

If a severity is no longer needed, [!DNL Workfront] recommends you hide the severity (click the [!UICONTROL Hide] box next to it in the setup area). This removes the severity option from the drop-down menu on the issue, but it retains the severity on historical data so it’s still available for reporting purposes.

![[!UICONTROL Hide] column highlighted on [!UICONTROL Severities] page in [!UICONTROL Setup]](assets/admin-fund-severity-hide.png)

[!DNL Workfront] recommends that you **do not** delete a severity that has been used on past issues. When you delete a severity, it asks you to substitute another severity. This can change historical data and affect reporting.

![Delete severity window](assets/admin-fund-severity-delete.png)

<!---
learn more URLs
Create and customize issue severities
Update issue severity
--->
