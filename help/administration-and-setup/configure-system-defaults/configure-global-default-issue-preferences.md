---
title: Configure Global Default Issue Preferences
description: Learn how to set issue preferences for converted issues, actual dates, and issue access.
feature: System Setup and Administration
activity: deploy
type: Tutorial
team: Technical Marketing
role: Admin
level: Intermediate, Experienced
jira: KT-10018
exl-id: 9924e479-c300-47b4-8e40-241ebb2435cf
---
# Configure global default issue preferences

Several system-wide settings establish defaults for how issues behave in certain circumstances in [!DNL Workfront].

Best practice is to leave the global defaults as they are and allow project managers to make adjustments they need at the project level or in project templates.

The global issue preferences can be adjusted, but it’s recommended that you and your [!DNL Workfront] consultant discuss what settings are needed for your organization’s workflows, processes, and reporting needs. Your consultant also can help you understand what will happen if certain settings are changed.

Issue preferences allow system administrators to control the options when issues are converted to tasks or projects, how actual dates are calculated, and who gets project access when issues are assigned. Let’s take a look at where those settings are in [!DNL Workfront].

## Converted issue preferences

These settings control what happens to an issue when it’s converted to a task or a project in [!DNL Workfront].

![[!UICONTROL Tasks & Issues] preferences window with [!UICONTROL Issues] section highlighted](assets/admin-fund-issue-prefs-converting.png)

1. Click **[!UICONTROL Setup]** in the **[!UICONTROL Main Menu]**.
1. Expand the **[!UICONTROL Project Preferences]** section in the left menu panel.
1. Select **[!UICONTROL Tasks & Issues]**.
1. Scroll to the **[!UICONTROL Issues]** section.
1. Click the desired options.
1. Save when you’re done.

Let’s take a look at the options in this section, so you can choose the appropriate options for your organization.

* **[!UICONTROL Automatically update Resolvable Issue status when the status of the Resolving Object Changes]**

  This setting lets you correlate the resolution of the original issue to the resolution of the new object (task or project).

  With this setting enabled (checked), you can create custom issue statuses that have the same status key as a task or project status. When the task or project (the resolvable object) is set to the custom status, the change also shows up on the issue status.

  When disabled, the resolving object status is set automatically to the default status, instead of custom ones.

  In order for this setting to have any effect, the “[!UICONTROL Keep the original issue and tie its resolution to the task]” option must be selected.

* **[!UICONTROL Keep the original issue and tie is resolution to the task/project]**

  When the issue is converted, this tells [!DNL Workfront] to keep the original issues. The status of the issue changes as the status of the task or project is changed. Once the task or project is marked as complete, the issue is marked as resolved.

  If this option is not checked, the original issue is deleted and only the converted task or project remains.

  This setting affects reporting on issues originally logged on a project or that come through a [!DNL Workfront] request queue.

* **[!UICONTROL Allow Primary Contact to have access to the task/project]**

  This gives the person who created the original issue access to the task or project created during the conversion. They can review the work, make updates, and stay informed of its progress.

* **[!UICONTROL Allow these settings to be changed during conversion]**

  When selected, this option means the default settings for “[!UICONTROL Keep original issue]” and “[!UICONTROL Allow Primary Contact]” can be changed by the user converting the issue. If you want the defaults to remain unchanged, deselect this option.

<!---
learn more URLs
Configure system-wide task and issue preferences
Issue statuses
Create and customize system-wide statuses
--->

## Actual dates preferences

There are multiple types of dates used throughout [!DNL Workfront]. Actual dates are a “timestamp” that [!DNL Workfront] generates when certain status changes occur.

The [!UICONTROL Actual Start Date] timestamp is created when the issue status changes from New to another status. The [!UICONTROL Actual Completion Date] timestamp is when the issue status changes to a status that indicates it is closed.

It’s important to note that this preference controls the actual date settings for both tasks and issues.

![[!UICONTROL Tasks & Issues] preferences window with [!UICONTROL Actual Dates] section highlighted](assets/admin-fund-issue-prefs-actual-dates.png)

1. Click **[!UICONTROL Setup]** in the **[!UICONTROL Main Menu]**.
1. Expand the **[!UICONTROL Project Preferences]** section in the left menu panel.
1. Select **[!UICONTROL Tasks & Issues]**.
1. Scroll to the **[!UICONTROL Actual Dates]** section.
1. Select the desired option for the **[!UICONTROL Actual Start Date]** — [!UICONTROL Now] (the current date and time) or [!UICONTROL The Planned Start Date] (the [!UICONTROL Actual Start Date] matches the start date set in the issue details).
1. Now select the option for the **[!UICONTROL Actual Completion Date]** — [!UICONTROL Now] (the current date and time) or [!UICONTROL The Planned Completion Date] (the [!UICONTROL Actual Start Date] matches the date set in the issue details).
1. Save when you’re done.


<!---
learn more URLs
Definitions for the project, task, and issue dates within Workfront
Configure system-wide task and issue preferences
--->

## Issue access

The [!UICONTROL Access] settings for issues control what access a user is granted when they’re assigned an issue in Workfront. These settings control access to the issue itself, in addition to access to the project the issue is associated with.

Before changing these settings, discuss any workflow or process needs with your [!DNL Workfront] consultants and your internal governance team.

![[!UICONTROL Tasks & Issues] preferences window with [!UICONTROL When someone is assigned to an ISSUE] section highlighted](assets/admin-fund-issue-prefs-access-1.png)

1. Click **[!UICONTROL Setup]** in the **[!UICONTROL Main Menu]**.
1. Expand the **[!UICONTROL Project Preferences]** section in the left menu panel.
1. Select **[!UICONTROL Tasks & Issues]**.
1. Scroll to the **[!UICONTROL Access]** section and find the “[!UICONTROL When someone is assigned to an ISSUE]” option.
1. Set the sharing access for the issue itself — [!UICONTROL View], [!UICONTROL Contribute], or [!UICONTROL Manage]. [!DNL Workfront] recommends leaving the advanced options as-is.
1. Check the box if the issue assignee should also have access to the project
1. Then select the sharing access for the project — [!UICONTROL View], [!UICONTROL Contribute], or [!UICONTROL Manage]. As you set the [!UICONTROL Advanced Options], keep in mind your organization’s workflows and access needs.
1. Save when you’re done.

![[!UICONTROL Access] window showing [!UICONTROL Contribute] options](assets/admin-fund-issue-prefs-access-2.png)

<!---
learn more URLs
Configure system-wide task and issue preferences
Grant access to issues
--->
