---
title: Best Practice - Request queues
description: Explore best practice recommendations from Adobe Workfront experts about setting up, managing, and using Workfront request queues.
feature: Resource Management
role: Admin, Leader, User
level: Beginner
jira: KT-10921
exl-id: dbb961f9-c207-49f1-9545-ec127f983c15
---
# Best Practice - Request queues

## What is an Adobe Workfront “best practice”? 

Best practices are guidelines that represent an effective, efficient course of action; are easily adopted by you and the users at your company; and can be replicated successfully across your organization. 

As you review these recommendations, please keep in mind that some Workfront best practices are universal while others might be more specific to the topic. Use these best practices as a framework to help guide your Workfront system setups and use.

## Navigating this page 

As you scroll through this page, first you’ll find a high-level list of all the best practices for the topic. This allows you to review the recommendations without diving into the details of “why.” 

The “Why are these best practices?” area, found after the high-level list, provides greater detail into some of the best practices and why they're deemed as a process, tool, etc., you should consider implementing with your Workfront instance. 

</br>
</br>

## Request queue best practices 

* Include a description for each element of a request queue—the request queue project, topic groups, queue topics, and routing rules. 

* Create a project status called “Request Queue” or “Operational” that equates with “Current” to distinguish request queue projects from other projects.  

* If you plan to use issue approvals with requests submitted through a queue, create an issue status called Rejected. 

* Assign "universal" custom forms to request queues to capture as much enterprise-wide consistent data as possible. 

* Avoid sharing request queues with "everyone." Set up the queue details settings so users only see the queues relevant to their needs.  

* Build and assign a dashboard containing request queue reports so traffic managers, system administrators, or assigned users can work on issues directly. 

* Use layout templates to remove the request queue setup options from the left panel menu of projects for users who do not need to create queues. 

* Create a system administrator request queue for users to ask Workfront-related questions, make requests regarding system setups, schedule new user training, etc. 

* Audit request queues on a regular basis to identify and unshare queues that aren't being used. 

* Use topic groups to organize more than 10 queue topics in a request queue to create shorter, easier to manage lists. 

* Control the total number of request queues available to users by breaking down a request queue using topic groups and queue topics, rather than creating multiple queues. 

* Set up routing rules for each queue topic. At minimum, set up a default routing rule. 

* Leverage topic groups and queue topics when selective routing is needed. 

* Route requests to a team, rather than an individual. 


</br>
</br>


## Why are these best practices? 
 

**Best practice**

Include a description for each element of a request queue—the request queue project, topic groups, queue topics, and routing rules. 

**Here’s why**

Descriptions let group administrators, future system administrators, or others who maintain request queues know exactly what each piece of the request queue does. 

The description information also appears when you hover over the information icon on the field in the new request window. 

The description doesn’t have to be long, just a brief comment about the purpose or use of the element. 

</br>
</br>

**Best practice**

Create a project status called “Request Queue” or “Operational” that equates with “Current” to distinguish request queue projects from other projects. 

**Here’s why**

A request queue “lives” in a project and must be in a status equal to Current for the queue to be active. 

In order to distinguish a request from actual work projects with a “Current” status, create a status to be used only on request queues called “Request Queue” or “Operational.” You can then use this status to help exclude or include request queue projects while writing reports. 
 
</br>
</br>

**Best practice**

Create an issue status called “Rejected” when using issue approvals and set the If Rejected option to the “Rejected” status. 

**Here’s why**

By using a “Rejected” status, this makes it clear the request was reviewed and rejected. 

</br>
</br>

**Best practice**

Assign "universal" custom forms to request queues to capture as much enterprise-wide consistent data as possible. 

**Here’s why**

A “universal” custom form gathers standard information needed for the request, regardless of the type of request being submitted. 

Having a “universal” custom form helps cut down on the number of custom forms you need to create and maintain. It also ensures that all requests are collecting the same information in the same way, which leads to consistent reporting and data analysis. 

</br>
</br>

**Best practice**

Avoid sharing request queues with "everyone."  Set up the queue details settings so users only see the queues relevant to their needs. 

**Here’s why**

In most cases, a request queue only needs to be shared with a certain set of people like a team, a vendor, customers, etc. When requestors see only what they need in the request queue list, it makes things easy to find and navigate. 

</br>
</br>


**Best practice**

Build and assign a dashboard containing request queue reports so traffic managers, system administrators, or assigned users can work on issues directly. 

**Here’s why**

Giving users quick and easy access to incoming requests means work doesn't get lost in the shuffle. 

</br>
</br>

**Best practice**

Use layout templates to remove the request queue setup options from the left panel menu of projects for users who do not need to create queues. 


**Here’s why**

This ensures all request queues go through the proper process for creation (such as being reviewed by a governance committee) and are set up correctly by either a system or group administrator. 

In addition, this helps keep the queue list organized and focused on the types of requests your organization needs. 

</br>
</br>

**Best practice**

Create a system administrator request queue for users to ask Workfront-related questions, make requests regarding system setups, schedule new user training, etc.  

**Here’s why**

This provides a centralized location for users to submit questions and for admins to gather, monitor and respond to Workfront-related issues. 

In addition, this information can be used to show leadership the time, effort, and value of the system administrator role and as a justification for an additional system administrator.  

</br>
</br>


**Best practice**
 
Audit request queues on a regular basis to identify and unshare queues that aren't being used. 

**Here’s why**

A regular audit of the setups and items in your Adobe Workfront system helps keep it uncluttered and free of unneeded items. If a queue is no longer being used or monitored, make sure users can no longer access it so work requests don’t fall into a void. 

</br>
</br>


**Best practice**

Use topic groups to organize more than 10 queue topics in a request queue to create shorter, easier to manage lists. 

**Here’s why**

Topic groups increase user adoption and create less confusion by decreasing the initial list of  options to select from. This allows users to easily find what they’re looking for without overwhelming them when trying to submit a request. 

In addition, it allows system administrators and/or request queue managers an opportunity to create a smooth navigational path for users and a better way so organizing and reporting on the types of requests being submitted. 

</br>
</br>

**Best practice**

Control the total number of request queues available to users by breaking down a request queue using topic groups and queue topics, rather than creating multiple queues. 

**Here’s why**

Too many request queues makes it hard for users to find what they need. 

Fewer queues also help traffic coordinators, system administrators, or others managing the queues, allowing them to find the information they need more quickly, without having to navigate to multiple request queue projects. 

Create multiple request queues if different access is needed for different request queues or if consolidating queues would be confusing to users. 

</br>
</br>

**Best practice**

Set up routing rules for each queue topic. At minimum, set up a default routing rule. 

**Here’s why**

Routing rules ensure someone will always be assigned the incoming request so work doesn't fall through the cracks. 

</br>
</br>

**Best practice**

Leverage topic groups and queue topics when selective routing is needed. 

**Here’s why**
 
Routing rules cannot be applied to fields of a custom form. So if different types of requests need to be routed to different teams/individuals, then make each type of request its own topic group/queue topic so the work can be routed properly. 

</br>
</br>

**Best practice**

Route requests to a team, rather than an individual. 

**Here’s why**

When requests are sent to the team, it gives the whole team visibility into the requests being made and what upcoming work might entail. Everyone can watch the Team page for new items or keep track of what’s new with a report on a dashboard. 

It also ensures that when the traffic manager or other person in charge of reviewing or assigning the incoming requests is unavailable, that a back-up is automatically available and has access to the request information.
