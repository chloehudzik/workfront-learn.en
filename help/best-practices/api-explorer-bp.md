---
title: Best Practice - API Explorer
description: Explore best practice recommendations from Adobe Workfront experts about setting up, managing, and using Workfront's API Explorer.
feature: Workfront API
role: Admin, Leader, User
level: Beginner
jira: KT-10902
exl-id: 0f3fc5ba-d01a-4337-829f-def0830ddf81
---
# Best Practice - API Explorer

## What is an Adobe Workfront “best practice”? 

Best practices are guidelines that represent an effective, efficient course of action; are easily adopted by you and the users at your company; and can be replicated successfully across your organization. 

As you review these recommendations, please keep in mind that some Workfront best practices are universal while others might be more specific to the topic. Use these best practices as a framework to help guide your Workfront system setups and use.

## Navigating this page 

As you scroll through this page, first you’ll find a high-level list of all the best practices for the topic. This allows you to review the recommendations without diving into the details of “why.” 

The “Why are these best practices?” area, found after the high-level list, provides greater detail into some of the best practices and why they're deemed as a process, tool, etc., you should consider implementing with your Workfront instance. 

</br>
</br>

## API Explorer best practices 

* Establish a naming convention for custom fields used with integrations from third-party systems.

* Track all custom fields used in integrations using a Workfront project.

* Add the object ID field to reports used by the system administrator. 

</br>
</br>

## Why are these best practices? 

**Best practice**

Establish a naming convention for custom fields used with integrations from third-party systems. 

**Here’s why**

Make sure everyone creating custom forms knows about the naming convention, so they don’t accidentally use a field reserved for an integration. Depending on your integrations and workflows, using the same field in multiple ways could result in data being modified or overwritten, and could result in incorrect data in reports. 

</br>
</br>


**Best practice**

Track all custom fields used in integrations using a Workfront project. 

**Here’s why**

A project makes the perfect place to log custom field names, what integration they’re used with, etc. This will help you avoid creating redundant custom fields or from using the same custom field with multiple integrations. 

</br>
</br>


**Best practice**

Add the object ID field to reports used by the system administrator. 

**Here’s why**

System administrators often need to refer to objects in Workfront by their ID numbers when using APIs or other integrations. Include the ID field in views for the objects you work on (projects, tasks, issues, templates, custom forms, etc.) to make it easy to access and copy.
