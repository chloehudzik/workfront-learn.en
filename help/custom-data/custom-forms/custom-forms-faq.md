---
title: Answers to Questions about Custom Forms
description: Get answers to common questions about custom forms.
feature: System Setup and Administration
type: Tutorial
role: Admin, Leader, User
level: Beginner, Intermediate
activity: use
team: Technical Marketing
jira: KT-10058
---
# Common questions about custom forms

**Can I switch the display type of a field after I’ve created it? For example, can I change from a drop-down menu to check boxes?**

Yes. The display type can be switched to another, similar display type—text to paragraph, drop-down to checkboxes or radio buttons, etc. For more information on changing the display type, see the Create a Custom Form article.


**Can I use the same custom form for multiple objects? For example, a form I created for a task to a project?**

No. Custom forms have a one-to-one relationship with an object. However, you can copy the custom form and change the object to the one that is needed.


**Can a custom form be attached to a project template?**

Yes. This way any project created from that template will have the custom form attached to it already.


**Is there a limit to the number of fields I can have on a custom form?**

You can add up to 500 fields on a single custom form. However, performance degradation can occur when more than 100 fields exist on a form, depending on the complexity of your custom form. Examples of complex forms include forms with cascading parameters, calculated custom data fields, and multiple value options in a given field.


**Is there a limit to the number of custom forms I can attach to a project?**

Yes. You can attach up to 10 custom forms on an object. For more information, refer to this article, Apply Custom Forms to Objects.


**Can I deactivate a custom form?**

Yes. In the Form Settings tab in the custom form, uncheck the Is Active box. This removes the custom form from any drop-down menus throughout Workfront. However, if the custom form is already attached to a project, the form remains and keeps any data already entered.