---
title: Fill in the project details
description: Learn which 12 project details fields [!DNL  Workfront] recommends you fill in when creating a project.
activity: use
team: Technical Marketing
feature: Work Management
thumbnail: fill-in-the-project-details.jpeg
type: Tutorial
role: User
level: Intermediate
jira: KT-10140
exl-id: a62b9421-627a-4f23-ab66-da1f29114225
---
# Fill in the project details

Don't worry … you don't have to fill out every field and checkbox in the project details with each project you create in [!DNL  Workfront]. Use templates to pre-fill information, then turn your attention to the 12 most important project details fields listed below. 

1. **Name**
   
   A descriptive project name helps everyone identify the purpose of the project. Be sure to follow your organization's project naming convention, which may require certain information be included in the project name (such as a reference number, department name, or category indicator).
   

1. **Description**

   When multiple people work on a project, you—as the project manager—have to ensure everyone is up to speed on the purpose and expectations of the project. 

   Do this with a project description that provides basic information, answers questions, and allows the project team to move forward with their work. For example, "A campaign aimed to increase revenue generating work by 50%" or "New system upgrade to improve efficiencies throughout the department."

   Some Workfront customers include a sample of what a project description should look like in their project templates.

1. **Status**

   Status is used in Workfront to indicate where, or at what stage, in the workflow a project is. Status is used in many Workfront reports to track how work is progressing.

   Workfront recommends the status be set to Planning while you're fleshing out and finalizing the project plan. The key thing with the Planning status is that Workfront notifications don't go out to task assignees about the project while it's in this status.

   Then once the project is ready to go live, change the status to Current. This allows Workfront to send notifications to people about new tasks they're assigned to, but it won't send notifications to users for the tasks they were assigned while the project was in a Planning status.

   >[!TIP]
   >
   >  When making changes to the project—such as changing due dates—you can roll the status back to Planning or turn off the Autosave feature to prevent notifications from going out until changes are complete.

   The Planning status can be set as the global Workfront default for new projects by your system administrator.

1. **Schedule Mode**

   Workfront projects can be scheduled from a start date or a completion date. That important selection determines how the planned dates of each task are calculated.

   The Start Date option takes the start date for the project—entered by you—and each task's duration and predecessors to calculate when the project will finish. Workfront recommends using this option, as it's the most common and makes planning project dates easier.

   However, you can use a completion date. Workfront looks at the end date (entered by you) and the work to be done (based on durations and predecessors), then works backward to calculate the project's start date. Workfront recommends waiting to use completion date after a certain level of proficiency in Workfront has been established.

   Whichever option you choose, don't forget to select a date from the pop-up calendar.

   The Schedule Mode option can be set in the template.

1. **Group**

   A group is a Workfront organizational unit that often aligns with a department. This field can be set on the project template. If it's not, the field is automatically set to the Home Group of the person creating the project. You can change the group as needed.

   Generally, most of the people working on the project come from this group. But this doesn't restrict people from other groups being assigned work in the project.

   The Group on the project also determines which project, task, and issue preferences the project will use. These preferences, such as a custom status for a specific group, are set by the system administrator or a group administrator.

   The group setting is a convenient way, through reporting, to show all projects a department is working on.

1. **Project Owner**

   The Project Owner is Workfront's term for project manager. This is the person responsible for the planning and/or management of the project.

   In order for the Project Owner to have full manage permissions to the project, they must have a Plan license.

   Normally this field is left blank in the template and fills in automatically with the name of the person who creates the project. If a name is entered in the template, that is the default owner of the project.

1. **Project Sponsor**

   The Project Sponsor is not required, but when used this is generally the person who requested the project. This is often an internal stakeholder, such as a manager or executive, with overall accountability for the project.

   The sponsor is automatically given view permissions to the project and must be a Workfront licensed user.

   The Project Sponsor can be set in the template.

1. **Resource Manager**

   The Workfront users listed in this field can use the resource planning and management tools in Workfront for the specific project(s) they're listed on. Up to 30 names can be listed in the Resource Manager field, and each must have a Plan license.

   The Resource Manager field can be set in the template.

1. **Custom Forms**

   Workfront provides native fields for things like project name and start date. But there's additional information you need as a project manager, or that the project team will need. Your unique data is equally important and is easily storeable in these forms. Details like publication dates, print asset sizes, delivery channels, etc.

   Custom forms can capture this information and can be included in lists and reports in Workfront, making the information easy to view and edit.

   Custom forms can be attached to your templates ahead of time.

1. **Schedule**

   Work happens around the clock, as many companies have employees across the globe.

   Workfront allows you to apply a common schedule to projects. These are created by your system administrator. Schedules reflect the work days and hours of your teams, plus days when employees won't be working (such as holidays).

   As a planner, make sure you're applying the right schedule to the right project. The schedule settings affect timeline calculations, taking time off and time zones into account.

   The schedule assigned to the project should be the one that applies to the majority of the task assignees. If there is no schedule specified for the project, the schedule marked as Default will be used.

   The schedule can be set in the template.

1. **Resource Pools**

   Resource pools are collections of Workfront users who are needed at the same time for the completion of projects at your organization. A resource pool can be assigned to multiple projects, which means you have projects competing for resources.

   Having resource pools assigned to a project is a prerequisite for using the Resource Planner and other resource management tools in Workfront.

   A default resource pool can be set in the template.

1. **Access to the Project for Viewers and Contributors**

   When someone is given access to a project through Share, there are three levels of permissions they can be given—View, Contribute, and Manage. Each permission level allows the user to see and do certain things with the project.

   For example, there are people who might have access to the project but shouldn't see the financial information. So you can turn off the View Finance option for them.

   The access settings can be set in the template.
