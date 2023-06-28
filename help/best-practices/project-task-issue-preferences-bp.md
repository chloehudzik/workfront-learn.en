---
title: Best Practice - Project, task, and issue preferences
description: Explore best practice recommendations from Adobe Workfront experts about setting up, managing, and using Workfront project, task, and issue preferences.
feature: System Setup and Administration
role: Admin, Leader, User
level: Beginner
jira: KT-10918
exl-id: 321af897-3791-4b06-a9dd-241b5246b2a0
---
# Best Practice - Project, task, and issue preferences

## What is an Adobe Workfront “best practice”? 

Best practices are guidelines that represent an effective, efficient course of action; are easily adopted by you and the users at your company; and can be replicated successfully across your organization. 

As you review these recommendations, please keep in mind that some Workfront best practices are universal while others might be more specific to the topic. Use these best practices as a framework to help guide your Workfront system setups and use.

## Navigating this page 

As you scroll through this page, first you’ll find a high-level list of all the best practices for the topic. This allows you to review the recommendations without diving into the details of “why.” 

The “Why are these best practices?” area, found after the high-level list, provides greater detail into some of the best practices and why they're deemed as a process, tool, etc., you should consider implementing with your Workfront instance. 

</br>
</br>

## Project, task, and issue preferences best practices 

* Set the default task duration type to Simple. 

* Set the preference for a new project’s status to Planning or Idea, not Current. 

* Enable Create Baselines Automatically in the global project preferences. 

* Check all the options in the Business Cases section of the system project preferences. 

* In the issues preferences, check the option for Automatically update Resolvable Issue status when the status of the Resolving Object changes. 

</br>
</br>


## Why are these best practices? 

**Best practice**

Set the default task duration type to Simple. 

**Here’s why**

Duration types define the relationship between the task duration, planned hours, and the number of people assigned to the task.  

With Simple as the global system default, all tasks created manually have this duration type. Planned hours are divided evenly among the task assignees across the length of the duration. The Simple duration type can simplify project planning, as it allows you to make changes to the task assignees and planned hours without affecting the task’s duration, planned start date, or planned completion date. 

</br>
</br>

**Best practice**

Set the preference for a new project’s status to Planning or Idea, not Current. 

**Here’s why**

A Current status indicates a project is live and work is actively being done. It’s rare that a project would need to be in this status upon creation. Even if you use a project template, there’s some “planning” involved in getting task assignments made, adjusting the project’s planned completion date, etc. The Planning status also suppresses notifications to task assignees and project team members. Receiving notifications before the project is live can be confusing for those involved. 

</br>
</br>

**Best practice**

Enable Create Baselines Automatically in the global project preferences.  

**Here’s why**

Every time you change a project status to Current, Workfront automatically records a project baseline. This “snapshot” of the project provides historical information about how the project’s plan changed over time. For example, you can compare the original project plan with the current plan when showing leadership how shifting priorities or scope creep affected the project's deadlines. 

</br>
</br>

**Best practice**

Check all the options in the Business Cases section of the system project preferences. 

**Here’s why**

Enable all five options to allow project managers, planners, and others to include any of those sections in the business case on a project. If the options aren’t enabled, then they do not appear in the business case window. Users can leave any of the fields blank if it’s not needed for that particular project, but they can’t enable a field at the project level. These options can only be enabled globally in Setup. 

</br>
</br>

**Best practice**

In the issues preferences, check the option for Automatically update Resolvable Issue status when the status of the Resolving Object changes. 

**Here’s why**

When an issue is converted to a project, this preference setting “links” the statuses of the two items. Updating the status of the project (the resolving object) will automatically update the issue status. This means the requester can see progress being made on their request, even if they don’t have permissions to see the entire project in Workfront.
