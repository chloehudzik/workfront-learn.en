---
title: Best Practice - Filters, Views, and Groupings
description: Explore best practice recommendations from Adobe Workfront experts about setting up, managing, and using Workfront filters, views, and groupings.
feature: Reports and Dashboards
role: Admin, Leader, User
level: Beginner
jira: KT-10911
exl-id: 845aa0b4-3fe9-4bc1-9dde-2f22c537e758
---
# Best Practice - Filters, Views, and Groupings

## What is an Adobe Workfront “best practice”? 

Best practices are guidelines that represent an effective, efficient course of action; are easily adopted by you and the users at your company; and can be replicated successfully across your organization. 

As you review these recommendations, please keep in mind that some Workfront best practices are universal while others might be more specific to the topic. Use these best practices as a framework to help guide your Workfront system setups and use.

## Navigating this page 

As you scroll through this page, first you’ll find a high-level list of all the best practices for the topic. This allows you to review the recommendations without diving into the details of “why.” 

The “Why are these best practices?” area, found after the high-level list, provides greater detail into some of the best practices and why they're deemed as a process, tool, etc., you should consider implementing with your Workfront instance. 

</br>
</br>

## Filters, views, and groupings best practices 

* Cut down on the number of custom reports you create by leveraging filters, views, and groupings on an object list to get the data you need. 

* Use the list controls in layout templates to hide unneeded filters, views, and groupings for commonly used objects (projects, tasks, programs, etc.). 

* Share custom filters, views, and groupings relevant to your organization’s workflows and processes through the list controls on layout templates. 

* When creating filters for project status, task status, or issue status, use the (object)>>Status Equates With field source/field name with the Equal modifier, rather than the Project>>Status field source/field name. 

</br>
</br>

## Why are these best practices? 

**Best practice**

Cut down on the number of custom reports you create by leveraging filters, views, and groupings on an object list to get the data you need. 

**Here’s why**

Creating one-time use reports for each segment of data you want to see is time-consuming and clutters up the Workfront system. 

</br>
</br>

**Best practice**

Use the list controls in layout templates to hide unneeded filters, views, and groupings for commonly used objects (projects, tasks, programs, etc.). 

**Here’s why**

Less is more. Hiding filter, view, and grouping list options that aren’t relevant to your users’ daily workflows narrows down the lists, which makes it easier for users to find what they need faster. 

</br>
</br>

**Best practice**

Share custom filters, views, and groupings relevant to your organization’s workflows and processes through the list controls on layout templates. 

**Here’s why**

If you’ve created filters, views, and groupings that display information specific to users’ daily processes, it’s easy to share these through the layout templates. This ensures everyone assigned that layout template has filter, view, and grouping options relevant to their workflows. 

Customizing the information that you want visible to your users through the layout templates is also a time-saver for system and group administrators because they won't have to share each filter, view, or grouping option individually. 

</br>
</br>

**Best practice**

When creating filters for project status, task status, or issue status, use the (object)>>Status Equates With field source/field name with the Equal modifier, rather than the Project>>Status field source/field name. 

**Here’s why**

By using (object)>>Equates With, you’re including all custom statuses that have that specific status assigned in the Equates With field in the status setups. Whereas setting up the filter as (object)>>Status > Equal requires that you select specific statutes for the filter. This could present a maintenance challenge if you need to account for those new statuses in various filters. Each filter would need to be opened and updated with the new status. 

For example, if you want to see all current projects, you could set up your filter to read Project>>Status > Equal > Current. But if someone adds a custom status named Active and equates it to Current, that filter won’t find projects with the Active status. However, if you use the Project>>Status Equates With > Equal > Current, then the filter finds objects with either the Current or Active status because they both have Current in the Equates With field.
