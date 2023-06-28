---
title: Best Practice - Statuses
description: Explore best practice recommendations from Adobe Workfront experts about setting up, managing, and using Workfront statuses.
feature: System Setup and Administration
role: Admin, Leader, User
level: Beginner
jira: KT-10926
exl-id: c3a4fe42-339c-4063-ad67-045868bbc6b1
---
# Best Practice - Statuses

## What is an Adobe Workfront “best practice”? 

Best practices are guidelines that represent an effective, efficient course of action; are easily adopted by you and the users at your company; and can be replicated successfully across your organization. 

As you review these recommendations, please keep in mind that some Workfront best practices are universal while others might be more specific to the topic. Use these best practices as a framework to help guide your Workfront system setups and use.

## Navigating this page 

As you scroll through this page, first you’ll find a high-level list of all the best practices for the topic. This allows you to review the recommendations without diving into the details of “why.” 

The “Why are these best practices?” area, found after the high-level list, provides greater detail into some of the best practices and why they're deemed as a process, tool, etc., you should consider implementing with your Workfront instance. 

</br>
</br>

## Statuses best practices 

* When renaming Workfront's default statuses, keep the original purpose of the status the same. 

* If you create a custom project status for Cancelled, equate the status with Dead. 

* Keep global custom statuses to a minimum. 

* Do not use project statuses in place of tasks to indicate progression of a project. 


</br>
</br>



## Why are these best practices? 

**Best practice**

When renaming Workfront's default statuses, keep the original purpose of the status the same.

  

**Here’s why**

Some actions in Workfront are triggered by system default statuses. Changing the intent of a status can impact how Workfront behaves in certain situations, affect reporting, etc. 

 

For example, the default task status of Complete tells Workfront to change the percent complete of a task to 100%. The Complete status also lets Workfront know that work on dependent tasks can begin. If you changed the name of the status to Waiting, to indicate a work on a task is paused, then Workfront is going to think the task is done and kick off the next steps in the project. 

</br>
</br>



**Best practice**

If you create a custom project status for Cancelled, equate the status with Dead. 



**Here’s why**

If you equate Cancelled with Complete, you can’t use the status to cancel a project unless all tasks are marked complete and all the issues are closed. But if you equate Cancelled with Dead, you can cancel the project without changing anything in the historical record. 


</br>
</br>

**Best practice**

Keep global custom statuses to a minimum.  

  

**Here’s why**
 
Less is more. In addition to creating unnecessary maintenance, too many custom statuses creates confusion, especially when working on cross-functional projects. Instead, make custom statuses group specific. This keeps your Workfront environment cleaner and better positioned for expansion to other groups in the future. Work with your governance/oversight committee and stakeholders to identify the statuses your organization's groups needs to use. 


</br>
</br>

**Best practice**

Do not use project statuses in place of tasks to indicate progression of a project. 



**Here’s why**

Keep project statuses simple to indicate high-level phases of progression, like Planning, Current, Complete, etc. Let the tasks, task statuses, and the task percent complete tell you how work is progressing overall on the project. These task-level indicators roll up into the project percent complete, the project condition, and the project progress status, all of which are better and more accurate indicators of project progression than a project status. In addition, this task-level information provides better project reporting.
