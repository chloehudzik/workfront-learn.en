---
title: Get started with calculated fields and expressions
description: Learn how to create expressions in calculated fields to gather unique custom data about the work being done for your organization.
feature: System Setup and Administration
type: Tutorial
role: Admin, Leader, User
level: Experienced
activity: use
team: Technical Marketing
thumbnail: gs-calc-fields-expressions.png
exl-id: fbd17f01-9e97-4ead-9a56-7ce4f81255ec
---
# Get started with calculated fields and expressions

<!-- **Note**: The expression examples shown are simple and some may be mitigated by fields already supplied by  . However, the examples are used to illustrate the foundational knowledge needed in order to build expressions in Workfront.-->

Workfront provides a variety of fields that are common across multiple areas of business and are regularly used for work management. Fields like planned completion date, project budget, task assignee name, etc.

Yet, each organization has data specific to its industry and company that needs to be gathered in order to understand if company objectives are being met. For instance, your organization wants to keep track of:

* What line of business a project will contribute to.
* If funding is coming from suppliers, internal, or both.
* What resolution is needed for images used.

Although those fields are not inherently built into [!DNL Workfront], you can create custom data entry fields and pre-populated, multi-select answer fields through a custom form.

This learning path focuses on the calculated field. You will learn what a calculated field is, the different types of information you can pull into the calculated field through data expressions, and how to build those calculated fields to enhance your data collection and reporting.

![Resource management setups one pager](assets/GS01.png)

## What is a calculated field?

A calculated field houses custom data created by using data expressions and existing Workfront fields. 

![Workload balancer with utilization report](assets/GS02.png)

For instance, your organization has a specific project numbering, or work number, system that includes the:

* Year the project was created,
* Initials of the project owner, and
* The [!DNL Workfront] project reference number.


Using expressions in a calculated field, you can take each piece of information already stored in [!DNL Workfront] and create that unique project ID, or work number, which can then be added to a report like this:

![Workload balancer with utilization report](assets/GS03.png)

Depending on the specific data needed, calculated fields can be simple, using one or two expressions, or more complicated, using several embedded expressions. Just keep in mind that Workfront can only use data already stored or pulled into the system for calculated fields.

## Text expressions

Text expressions search, dissect, and combine information found in [!DNL Workfront] to create more meaningful data or gain greater insight into the work being done for your organization. 

For example, text expressions can be used to:

* Show "Over $5,000" when project expenses are more than $5,000, or “Under $5,000” when expenses are below that, in a column of a project view.

* Give each project a unique number that includes the year the project was created, the project's  [!DNL Workfront] reference number, the project name, and the project owner's initials.

* Build a report that lists every project that isn't assigned to a portfolio and/or program so you can use this in your manager meetings.

Text expressions can be used in a custom field to do these types of searches and combinations in Workfront.

When looking at the possible text expressions, you’ll find several options.

![Resource management setups one pager](assets/TE01.png)

There are six text expressions that are used most often:

* CONCAT
* LEFT / RIGHT
* CONTAINS
* IF
* ISBLANK