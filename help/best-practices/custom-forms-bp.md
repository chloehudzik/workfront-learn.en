---
title: Best Practice - Custom forms
description: Explore best practice recommendations from Adobe Workfront experts about setting up and managing Workfront custom forms.
feature: Digital Content and Documents
role: Admin, Leader, User
level: Beginner
jira: KT-10907
exl-id: 0c0fca34-2be0-4208-95d0-241d2e032ce7
---
# Best Practice - Custom forms

## What is an Adobe Workfront “best practice”? 

Best practices are guidelines that represent an effective, efficient course of action; are easily adopted by you and the users at your company; and can be replicated successfully across your organization. 

As you review these recommendations, please keep in mind that some Workfront best practices are universal while others might be more specific to the topic. Use these best practices as a framework to help guide your Workfront system setups and use.

## Navigating this page 

As you scroll through this page, first you’ll find a high-level list of all the best practices for the topic. This allows you to review the recommendations without diving into the details of “why.” 

The “Why are these best practices?” area, found after the high-level list, provides greater detail into some of the best practices and why they're deemed as a process, tool, etc., you should consider implementing with your Workfront instance. 

</br>
</br>

## Custom form best practices 

* Diagram a custom form—on a whiteboard or piece of paper—before creating it in Adobe Workfront. 

* Attach custom forms to a project template if the projects made with that template always need certain custom forms attached. You can even fill in the fields that rarely change or that require specific information. 

* Create a custom form to track information about external customers or vendors that you have added to your Workfront system as a company. 

* Create a single "general" or "universal" custom form that contains common fields and calculated fields, rather than tacking the individual fields on to multiple forms. This helps you collect enterprise-wide information in a consistent manner. 

* Add section breaks to a custom form to keep it organized and easy to understand. 

* Keep custom forms shorter to ensure the form is completely filled out and you get all the information you need. 

* Use predefined custom field options—such as radio buttons and drop-down menus—to limit the answer options by requiring users to select from specific options. 

* Make sure field labels are clearly worded and descriptive. 

* Add information in the Instructions field on custom fields to indicate what information the person filling out the field must enter. 

* Use display logic to show needed fields when another field is filled in a specific way. Use skip logic in custom forms to hide fields not related to the type of request. 

* Cut down on the number of calculations required on a custom form by pulling the calculated information from another form. 

* Check the field library before creating new fields for a custom form to see if the field already exists. 

* Use required fields to ensure information critical to your process or organization is captured.

* Exercise caution when changing field names on a custom form, as this can affect calculated fields that are calling to that field. 

* Review custom forms and fields on a regular basis—such as once a quarter—as part of your regular Workfront system maintenance. 

* Deactivate unneeded custom forms instead of deleting them. 

* Hide custom fields that are no longer needed on a custom form under a section break. Then make that section visible only to system administrators. 

* Limit who can create custom forms in your Workfront instance. 

</br>
</br>

## Why are these best practices?

**Best practice**

Diagram a custom form—on a whiteboard or piece of paper—before creating it in Adobe Workfront. 

**Here’s why**

Make sure you have fields for all the required information and that the fields are organized in a way that will make it easy for users to fill out the form. Diagraming the form also can help you determine if some fields can be hidden/shown using display logic. 

</br>
</br>

**Best practice**
 
Attach custom forms to a project template if the projects made with that template always need certain custom forms attached. You can even fill in the fields that rarely change or that require specific information. 

**Here’s why**

This way, the form is already attached and some of the information is already filled out, which helps speed up project creation and ensures those custom fields are filled out correctly and completely across all applicable projects. 

</br>
</br>

**Best practice**
 
Create a custom form to track information about external customers or vendors that you have added to your Workfront system as a company. 

**Here’s why**

Use the custom form to track address, name of the primary contact, etc., so it’s easily accessible inside Workfront. You’ll also be able to pull this custom form information into reports. 

</br>
</br>

**Best practice**
 
Create a single "general" or "universal" custom form that contains common fields and calculated fields, rather than tacking the individual fields on to multiple forms. This helps you collect enterprise-wide information in a consistent manner. 

**Here’s why**

A “general” form makes maintaining these fields easier, because they all live in one place. You'll be able to update a single form, rather than having these individual fields living on several different forms, which you would then have to update individually. 

</br>
</br>

**Best practice**
 
Add section breaks to a custom form to keep it organized and easy to understand. 

**Here’s why**

Grouping related information into sections helps users navigate the form. 

</br>
</br>

**Best practice**
  
Keep custom forms shorter to ensure the form is completely filled out and you get all the information you need. 

**Here’s why**

Long forms can be intimidating to users and often lead to the form not being filled out completely. This, in turn, results in incomplete assignment information and inaccurate data for reporting. 

If a custom form has a lot of fields, place related fields side-by-side, where possible, so there is less scrolling for the user. You can also use skip logic to hide fields that don’t need to be filled out or display logic to show specific fields. 

</br>
</br>

**Best practice**
 
Use predefined custom field options—such as radio buttons and drop-down menus—to limit the answer options by requiring users to select from specific options. 

**Here's why**

With a predefined field, users will just click a box or select from a menu, ensuring that all answers to that question are identical. 

Consistent, accurate data is vital to accurate reporting. Inconsistent data results in inaccurate reports, which can affect decisions from the individual level on up. In addition, this consistent data allows you to add charts to reports for a visual representation of your data. Open-ended text fields cannot be used in charts. 

</br>
</br>

**Best practice**
 
Make sure field labels are clearly worded and descriptive. 

**Here's why**

This way the person filling out the custom form understands what information is being asked for. 

</br>
</br>

**Best practice**
 
Add information in the Instructions field on custom fields to indicate what information the person filling out the field must enter. 

**Here's why**

This information appears as a pop-up when you hover over the ? Icon next to a field on a custom form. Include what data should be entered in the field, included any required formatting for text fields. 

Providing more detail for the user helps lessen additional conversations, back-and-forth emails, or confusion. When information is incomplete or missing, that can delay the work being done. 

</br>
</br>

**Best practice**

Use display logic to show needed fields when another field is filled in a specific way. Use skip logic in custom forms to hide fields not related to the type of request. 

**Here's why**

Displaying only the fields that are needed, or hiding ones that aren’t, creates a cleaner custom form and less confusion for users as they are filling out custom forms. This also contributes to an overall shorter form, which is less intimidating users and promotes a higher response rate. 

Using display logic also can help you cut down on the number of custom forms you need to create and maintain. 

</br>
</br>

**Best practice**
 
Cut down on the number of calculations required on a custom form by pulling the calculated information from another form. 

**Here's why**

For example, you have a calculated field called "Number of Assets" on an issue form that calculates the number of assets attached to the item. This is used on a request queue. You need this information to carry over to the project when the request is converted. Make a copy of the issue form and save it as a project form. Then add the name of the issue calculated field to the project form's calculation box. In this example, in the project form’s calculated field called "Number of Assets," literally enter "Number of Assets." This prevents Workfront from trying to re-run this calculation on the project and instead uses the value from the issue custom form. 

</br>
</br>

**Best practice**
 
Use existing fields from the field library that serve the same purpose, when applicable. 

**Here's why**

Two fields in Workfront cannot have the same name. If the field has a common name, there's a chance the field already exists. Check the field library before creating new fields to see if the field already exists. 

When using fields that you didn't create, remember that modifications to this field affect ALL custom forms the field is a part of. If you need to change a calculation or change the type of field (text to radio buttons, for example), then you need to create a new field and give it a different name than the original. (Keep in mind that multiple fields with similar names can be confusing to users.) 

</br>
</br>

**Best practice**
 
Use required fields to ensure information critical to your process or organization is captured. 

**Here's why**

Incomplete data on a custom form can delay work and affect reporting. The required field indicator (a red * next to the field name) reminds users that specific information is required before editing and then saving that custom form or officially submitting a request. 

However, required fields should be used sparingly and carefully. Having every field required can deter users from filling in the fields with useful and complete information. Also when editing a custom form in an object’s Details area, an incomplete required field prevents a custom form from being saved.  

</br>
</br>

**Best practice**
 
Exercise caution when changing field names on a custom form, as this can affect calculated fields that are calling to that field. 

**Here's why**

When you change the name of a field, the name needs to be updated where it's used in either a calculated custom field on a custom form or in a calculation built into text mode. Changing a field name can break calculations and result in inaccurate information. 

</br>
</br>

**Best practice**
 
Review custom forms and fields on a regular basis—such as once a quarter—as part of your regular Workfront system maintenance. 

**Here’s why**

Custom forms and fields aren’t useful if they’re not collecting the data your organization needs to get work done.  

When making updates, be mindful of how these changes affect other aspects of Workfront. For example, changing a field name can break a calculation that uses that field. Or changing the label or name of a form may cause a report not to display needed information or an integration with another system not to run. 

In addition to updating custom forms, identify forms that have low usage or aren’t being used at all. Can forms that aren’t used frequently be combined with another form? Or maybe it’s time for that form to be deprecated, because your teams no longer need the information that form is collecting. 

Before you take any actions with these unnecessary forms, read about deactivating vs. deleting custom forms and custom fields. 

</br>
</br>

**Best practice**
 
Deactivate unneeded custom forms instead of deleting them. 

**Here’s why**
 
When you delete a custom form, you delete all custom data that was entered via that custom form. 
Deactivating a custom form retains all associated historical data. This means you can continue to report on this information. 

Deactivating also prevents the form from showing up in drop-down menus where users select a custom form. However, the form still displays on any object it’s already attached to. 

</br>
</br>

**Best practice**

Hide custom fields that are no longer needed on a custom form under a section break. Then make that section visible only to system administrators. 

**Here’s why**
 
Deleting an existing custom field not only removes it from a custom form, it deletes all the data contained in that field wherever that custom field is used. This means that historical data, which might be needed for reports, is deleted. 

To prevent data loss, hide the unneeded field in the custom form itself. Section breaks in custom forms allow you to hide or expose the fields that are part of that section based on whether the user has access to view, contribute to, or manage the Workfront object it’s attached to. Or a section can be set to Admin Only, so only users with a system administrator access level can see that whole section of the form. 

</br>
</br>

**Best practice**

Limit who can create custom forms in your Workfront instance. 


**Here’s why**

Having a select group of people who can create custom forms helps control the number of custom forms created in your Workfront instance.  

In addition, allowing others to create forms can alleviate work from the system administrator and gives each group control over updates to the custom forms they use on a regular basis.
