---
title: Best Practice - Licenses and access levels
description: Explore best practice recommendations from Adobe Workfront experts about setting up, managing, and using Workfront licenses and access levels.
feature: System Setup and Administration
role: Admin, Leader, User
level: Beginner
jira: KT-10914
exl-id: 6be3fab9-16a1-4ab9-89ce-8c53f8358e62
---
# Best Practice - Licenses and access levels

## What is an Adobe Workfront “best practice”? 

Best practices are guidelines that represent an effective, efficient course of action; are easily adopted by you and the users at your company; and can be replicated successfully across your organization. 

As you review these recommendations, please keep in mind that some Workfront best practices are universal while others might be more specific to the topic. Use these best practices as a framework to help guide your Workfront system setups and use.

## Navigating this page 

As you scroll through this page, first you’ll find a high-level list of all the best practices for the topic. This allows you to review the recommendations without diving into the details of “why.” 

The “Why are these best practices?” area, found after the high-level list, provides greater detail into some of the best practices and why they're deemed as a process, tool, etc., you should consider implementing with your Workfront instance. 

</br>
</br>

## Licenses and access levels best practices 

* Start with less access for users when setting up access levels. 

* When assigning Review and Request licenses, typically default to Review because it provides the user with more permissions in Adobe Workfront. 

* Uncheck the "Share System-wide" checkbox on each object in all your access levels unless you specifically want those users to be able to do it.   

* Consider activating the “Never allow users to delete comments” setting under Set additional restrictions in an access level. 

* Limit the number of system administrators in favor of group administrators. 

* Copy an existing access level and make modifications, rather than creating a new access level from scratch. 

* Document what each access level can do in the Description box. 

* Limit yourself to only the access levels that are necessary to accomplish your work goals, ideally four or five that capture the needs of most users in the system. 

* Assign at least two users the global system administrator access level.   

* Restrict what users can do with Workfront items through sharing, rather than removing a capability in an access level. 

</br>
</br>


## Why are these best practices? 

**Best practice**

Start with less access for users when setting up access levels. 

 

**Here’s why**

Start users with the minimum access they’ll need to do their work. If they can’t do their jobs due to insufficient access rights, they’ll usually request additional access. Granting users too much access right away could lead to security issues. Plus, it’s always better to give users more access than to take access away. 

</br>
</br>

 

**Best practice**

When assigning Review and Request licenses, typically default to Review because it provides the user with more permissions in Adobe Workfront. 

 

**Here’s why**

Although both Review and Request licenses can be assigned to an unlimited number of users in Workfront, the Request licenses are limited to pretty much just making and updating requests. A Review license has more access to projects and tasks than a Request license, as well as possibility of viewing portfolios and programs, editing documents, and accessing resource management tools.  

</br>
</br>

**Best practice**

Uncheck the "Share System-wide" checkbox on each object in all your access levels, unless there’s a specific reason users need to be able to share system-wide.  

 

**Here’s why**

Sharing an object system-wide is often used as a crutch to allow certain users to see items in Workfront. This happens when the Workfront group structure is lacking or when sharing permissions aren’t fully understood. When items are shared system-wide, it means everyone can see the item that is shared. Depending on the type of information being kept in the system, this could lead to privacy issues.  

 

For instance, you may be working with several vendors inside Workfront to check progress, provide approvals, etc. If the “Share System-wide" checkbox is an option, that could be selected or set as a default, making information available to all vendors. 

 

By unchecking the option altogether, you make it so a user, with the permission to share, must determine the specific person or people -- either through a company, group or team – they want to share the object with. 

 </br>
</br>

**Best practice**

Consider activating the “Never allow users to delete comments” setting under Set additional restrictions in an access level.  

 

**Here’s why**

Activating this option ensures past communications are not removed from Workfront. Some organizations require the full comment history be retained for auditing purposes. 

</br>
</br>

**Best practice**

Limit the number of system administrators in favor of group administrators. 

 

**Here’s why**

System administrators have access to everything in Workfront, including global system settings. The settings group administrators can access are controlled by the system administrator and apply only to that specific group. 

 

Having group administrators allows the system administrators to delegate many responsibilities, allowing them to focus on bigger picture items, rather than the day-to-day maintenance of Workfront. Group administrators can more easily keep in touch with the needs of their groups, which provides better service for users. 

 </br>
</br>
 

**Best practice**

Copy an existing access level and make modifications, rather than creating a new access level from scratch. 

 

**Here’s why**

Copying an existing access level provides a consistent base for new access levels, ensuring the initial settings are identical. This is also a time-saver, as system administrators won’t have to set up an access level entirely from scratch. 

 </br>
</br>

**Best practice**

Document what each access level can do in the Description box. 

 

**Here’s why**
 
Be detailed with the description, listing what the settings are for each object type. This helps system administrators—present and future—know exactly what each access level does without having to dive into the access level itself to review the settings. 

 

This can also make comparing access levels easier when looking at them in a report. The description field can quickly be added to the view to quickly see how they differ and, possibly, why a different access level was created. 

</br>
</br>

**Best practice**

Limit yourself to only the access levels that are necessary to accomplish your work goals, ideally four or five that capture the needs of most users in the system. 


**Here’s why**

The access level ensures that when a Workfront object is shared with a user, the user has the rights they need to edit it, delete it, etc. You can make access levels more general because sharing on individual items can be configured to be more specific.  


In addition, having fewer access levels can make it easier to maintain a clutter-free system and implement a strategy, which can also lead to quicker onboarding when people join the company or switch departments.  

</br>
</br>

**Best practice**

Assign at least two users the global system administrator access level.  

**Here’s why**

More than one person should understand why the Workfront was configured the way that it was, how to manage/maintain it, and how to support users. If one person is out of office, leaves the organization, is busy, etc., this ensures there is another person who has the information and knowledge to successfully manage the system. 

</br>
</br>

**Best practice**

Restrict what users can do with Workfront items through sharing, rather than removing a capability in an access level. 


**Here’s why**

Access levels control what users can do with specific items on a global level. The sharing permissions on each project, task, portfolio, document, etc., control what an individual user can do with that specific item. Rather than removing a capability for everyone with a specific access level, fine-tune the sharing permissions on specific items so users have limited controls.
