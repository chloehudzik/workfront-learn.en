---
title: Understand groups and users in [!UICONTROL Workfront DAM]
description: Learn how to create folders, groups, and users in [!UICONTROL Workfront DAM]. Understand the user role types and grant permissions to folders.
activity: use
feature: Digital Content and Documents
type: Tutorial
role: Admin
level: Intermediate
team: Technical Marketing
jira: KT-8967
exl-id: 4ebf675c-b72d-447e-b131-a89acb449e15
doc-type: video
---
# System setup: groups and users

In this video, you will learn how to:

* Understand how group setups affect access to assets
* Create folders, groups, and users in a specific order
* Understand the user role types
* Grant permissions to folders
* Create and edit groups
* Add and edit users

>[!VIDEO](https://video.tv.adobe.com/v/335230/?quality=12&learn=on)

## Groups and users review

As you configure your [!UICONTROL Workfront DAM] system, it’s important to consider the roles that users and groups play in the big picture.

Groups control access to asset folders in [!UICONTROL Workfront DAM]. Group settings also control what users can do with the assets (view, download, edit, etc.) they have permission to access.

When creating groups, it’s vital to keep in mind what asset folders the members of that group will need access to in [!UICONTROL Workfront DAM].

Users are the individuals who have logins to [!UICONTROL Workfront DAM]. A user cannot access anything in [!UICONTROL Workfront DAM] unless they are assigned to a group. Users can belong to more than one group, depending on their needs.

## Default groups

There are two default groups that come with [!UICONTROL Workfront DAM]. All users belong to these groups automatically, based on whether they have [!UICONTROL Workfront DAM] login credentials. You cannot add or remove users from these groups:

* **Guest group**—Used to control access for an anonymous user. This could be someone without login credentials or a user who is not currently logged in.
* **Logged**-In group—All users who are logged in belong to this group.

The Admin group and its settings also exist by default. You can add users to this group but you cannot adjust the settings.

## Role types

As groups are created, they are assigned a role type. The role type determines what part of the [!UICONTROL Workfront DAM] system users get when they log in — [!UICONTROL Workfront DAM] itself or [!UICONTROL Brand Connect].

There are three role types available with [!UICONTROL Workfront DAM] licenses:

* **[!UICONTROL Brand Portal]**—These users have access only to [!UICONTROL Brand Connect], which is where they can view and download approved assets.
* **[!UICONTROL Contributor]**—These users can access [!UICONTROL Workfront DAM] and [!UICONTROL Brand Connect]. They have full access rights to assets and folders—view, download, upload, edit, move, and delete.
* **[!UICONTROL Administrator]**—System administrators have access to everything in [!UICONTROL Brand Connect] and [!UICONTROL Workfront DAM], plus the ability to establish the global system settings for each. They also can access assets that have expired or been set as inactive.

<!-- 
Learn more graphic & documentation article link, below
* Understanding the difference between Workfront licenses and Workfront DAM role types
* -->
