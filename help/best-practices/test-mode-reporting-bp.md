---
title: Best Practice - Text mode reporting
description: Explore best practice recommendations from Adobe Workfront experts about setting up, managing, and using Workfront text mode reporting.
feature: Reports and Dashboards
role: Admin, Leader, User
level: Beginner
jira: KT-10928
exl-id: c624545c-ba42-4cc3-aafe-8be15baadb75
---
# Best Practice - Text mode reporting

## What is an Adobe Workfront “best practice”? 

Best practices are guidelines that represent an effective, efficient course of action; are easily adopted by you and the users at your company; and can be replicated successfully across your organization. 

As you review these recommendations, please keep in mind that some Workfront best practices are universal while others might be more specific to the topic. Use these best practices as a framework to help guide your Workfront system setups and use.

## Navigating this page 

As you scroll through this page, first you’ll find a high-level list of all the best practices for the topic. This allows you to review the recommendations without diving into the details of “why.” 

The “Why are these best practices?” area, found after the high-level list, provides greater detail into some of the best practices and why they're deemed as a process, tool, etc., you should consider implementing with your Workfront instance. 

</br>
</br>

## Text mode reporting best practices 

* Use text mode value expressions instead of calculated custom fields whenever possible in list report columns.  

* Put calculations used in a text mode calculation in the report’s description. 

</br>
</br>

## Why are these best practices? 

**Best practice**

Use text mode value expressions instead of calculated custom fields whenever possible in list report columns.  

  

**Here’s why**

Text mode value expressions are calculated at the time the report is run and are recalculated whenever the report is refreshed. This means you’ll always have up-to-minute data and accurate reports. 

 

Calculated custom fields (used on custom forms) do not update automatically when data is displayed in Workfront. Instead, they display the results of the most recent calculation stored in Workfront. This means those values might be “stale” or out of date at any given time. Calculated custom fields have to be refreshed manually, either by recalculating the expression or by editing and saving the object that contains the calculated field. This can be time consuming, as well as easy to forget to do. 


</br>
</br>

**Best practice**

Put calculations used in a text mode calculation in the report’s description. 



**Here’s why**

Including any text mode calculations in the report’s description helps others understand how the calculation was built and what kind of information it should be displaying. It also reminds system administrators how the report was built, in case updates are needed in the future.
