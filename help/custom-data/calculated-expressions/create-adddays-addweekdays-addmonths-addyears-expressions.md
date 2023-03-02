---
title: Create ADDDAYS, ADDWEEKDAY, ADDMONTHS, ADDYEARS expressions
description: Learn how to use and create the ADD expressions in a calculated field in Adobe [!DNL Workfront].
feature: System Setup and Administration
type: Tutorial
role: Admin, Leader, User
level: Experienced
activity: use
team: Technical Marketing
thumbnail: 335175.png
kt: 8912
exl-id: f194fbc8-99b3-4fed-9fc5-a2f5fa4593d2
doc-type: video
---
# Create ADDDAYS, ADDWEEKDAY, ADDMONTHS, ADDYEARS expressions

In this video, you will learn:

* What the ADDDAYS/ADDWEEKDAY/ADDMONTHS/ADDYEAR expressions calculate
* How to create an ADDWEEKDAYS data expression in a calculated field

>[!VIDEO](https://video.tv.adobe.com/v/335175/?quality=12)

## Additional examples

Below are a few additional ADDDAYS/ADDWEEKDAY/ADDMONTHS/ADDYEAR expressions Adobe Workfront customers have created.

**Should have been done by**

The customer wanted to know when the task should have been completed based on the Actual Start Date and the Planned Duration. The Projected Completion Date won’t work in this case because it can move if the task is late, and the Planned Completion Date doesn't help if there are delays in prior tasks. 

The expression created was ADDDAYS({actualStartDate},{durationMinutes}/480)

Time in the Duration field is stored in minutes. So in this expression, the Duration field cannot stand alone if the time is to be reflected in days. For that to happen, the Duration has to be divided by 480 minutes (480 minutes = 8 hours = 1 Day)

This is why the second value slot contains (Duration/480).


**Invoice completion date**

This example includes not only uses the ADDDAYS expression but a custom field previsouly created and saved in the custom form.

The customer is capturing the date an invoice is submitted through a custom date field titled “Invoice Submission Date”. 

Once submitted, the invoice must be completed and filed within 30 days. To automatically produce that completion and filing date, an ADDDAYS calculated field is used along with the "Invoice Submisison Date" custom field. The expression looks like this:

ADDDAYS({DE:Invoice Submission Date},30)
