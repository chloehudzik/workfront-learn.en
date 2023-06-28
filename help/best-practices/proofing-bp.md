---
title: Best Practice - Proofing
description: Explore best practice recommendations from Adobe Workfront experts about setting up, managing, and using proofing in Workfront.
feature: Workfront Proof
role: Admin, Leader, User
level: Beginner
jira: KT-10920
exl-id: 394485ee-bb8f-4248-86a9-4c86174dd37f
---
# Best Practice - Proofing

## What is an Adobe Workfront “best practice”? 

Best practices are guidelines that represent an effective, efficient course of action; are easily adopted by you and the users at your company; and can be replicated successfully across your organization. 

As you review these recommendations, please keep in mind that some Workfront best practices are universal while others might be more specific to the topic. Use these best practices as a framework to help guide your Workfront system setups and use.

## Navigating this page 

As you scroll through this page, first you’ll find a high-level list of all the best practices for the topic. This allows you to review the recommendations without diving into the details of “why.” 

The “Why are these best practices?” area, found after the high-level list, provides greater detail into some of the best practices and why they're deemed as a process, tool, etc., you should consider implementing with your Workfront instance. 

</br>
</br>

## Proofing in Workfront best practices 

* Take the time to create proofing workflow templates. 

* Disable the “Send emails from Workfront when a comment is made on a proof” setting in the Workfront setups. 

* Use only Read Only or Reviewer for the “Roles for non-recipients that open a document proof” setting in Workfront. 

* Adjust the proof back-end settings so users see deadlines in a 12-hour clock format. 

* Establish a default proof deadline as part of the system settings. 

* Hide the Not Relevant proof decision option. 

* Do not reorder the proof decision options in the proof settings. 

* Set user defaults for proof roles and email alerts. 

* Set the proof creator’s proof role to Reviewer. 

* Avoid using the Approver proof role. 

* Avoid the All Activity proof email alert option. 

</br>
</br>

## Why are these best practices? 

**Best practice**

Take the time to create proofing workflow templates.   

**Here’s why**

Not only do templates speed up and streamline the proof creation and assignment process, they provide consistency across proof workflows for similar types of assets. They also ensure each proof recipient is assigned the proper proof role and email alert, and that a deadline has been set. 

</br>
</br>

**Best practice**

Disable the “Send emails from Workfront when a comment is made on a proof” setting in the Workfront setups. 



**Here’s why**

When this setting is enabled (which it is by default), users have the potential to get multiple email notifications for each comment on a proof—one from the proofing functionality and one from Workfront itself. These duplicate notifications lead to email notification disruption and confusion, as well as a full email inbox, which may ultimately result in users ignoring proof notifications they receive. Which, in turn, could mean missed deadlines. 

 

**Note**: This setting is found in the Workfront Main Menu > Setup > Email > Review and Approval. 

</br>
</br>

**Best practice**
 
Use only Read Only or Reviewer for the “Roles for non-recipients that open a document proof” setting in Workfront.   



**Here’s why**

The other options for this setting all require a proof decision be made, which throws can derail your proofing workflow. Generally, people who are not added to the proof workflow just need to view the proof or make comments, not actually approve the proof, so the Read Only or Reviewer options are your best bet. 

 

**Note**: This setting is found in the Workfront Main Menu > Setup > Review and Approval. 

</br>
</br>

**Best practice**

Adjust the proof back-end settings so users see deadlines in a 12-hour clock format. 



**Here’s why**

Select the F j, Y, gi:a option in the proof settings for users who want to see proof deadlines/times in a AM/PM format. For areas that use a 12-hour clock, this helps with deadline clarity. 

 

**Note**: This setting is found by going to the Workfront Main Menu > Proofing > Account Settings > Users > and editing the Date format field for each user.  

</br>
</br>

**Best practice**

Establish a default proof deadline as part of the system settings.   



**Here’s why**

When a default proof deadline is set—the upload date + x number of business days—if the proof creator forgets to add a deadline, Workfront automatically applies this deadline to every proof uploaded. 

 

**Note**: This setting is found by going to the Workfront Main Menu > Proofing > Account Settings > Settings > Proof Defaults > Deadline (+ business days) field. 

</br>
</br>


**Best practice**

Hide the Not Relevant proof decision option. 



**Here’s why**
 
This decision option often causes confusion among approvers, as organizations often don't define when the Not Relevant option should be used. The Not Relevant option generally indicates the proof is not relevant to the proof recipient and they do not need to make an approved or rejected decision. By selecting Not Relevant, this allows the proof workflow to continue. 

 
The Not Relevant option is not needed in most proof workflows. 

**Note**: This setting is found by going to the Workfront Main Menu > Proofing > Account Settings > Decisions.   

</br>
</br>

**Best practice**

Do not reorder the proof decision options in the proof settings.   



**Here’s why**

Each proof decision setting holds a specific value/weight that, if re-ordered, can throw confusion into your proof configurations. The decision order and value/weight are used as proof stage activation triggers and in reporting. 

 

**Note**: This setting is found by going to the Workfront Main Menu > Proofing > Account Settings > Decisions. 

</br>
</br>

**Best practice**

Set user defaults for proof roles and email alerts. 



**Here’s why**

These settings populate automatically when assigning a proof workflow, speeding up the process, and contributing to consistency across proof workflows. 

 

**Note**: User default settings are found by going to the Workfront Main Menu > Proofing > Account Settings > Users > and selecting the user to set defaults for. 

</br>
</br>

**Best practice**

Set the proof creator’s proof role to Reviewer.   



**Here’s why**

The Reviewer proof role ensures the proof creator can make comments and access comments left by others. Most of the time, the proof creator isn’t required to make a decision on a proof they’ve uploaded. The Approver, Reviewer & Approver, Author, or Moderator proof roles all require a decision be made. If the proof creator is assigned one of these proof roles but never makes a decision, this can adversely affect proof deadlines. 

</br>
</br>

**Best practice**

Avoid using the Approver proof role. 



**Here’s why**

The Approver proof role does not allow the user to make comments on this proof. This could lead to a user rejecting the proof, without any explanation  because they could not make comments. Use the Reviewer & Approver proof role instead so the user can provide feedback. 

</br>
</br>

**Best practice**

Avoid the All Activity proof email alert option.   

**Here’s why**

This option sends a proof email notification any time something happens with a proof—a comment is made, a reply is posted, a decision is made, etc. The recipient is essentially seeing proof activity as it happens. 

For proof owners and creators, the Decisions email alert works best for multi-stage proof workflows and Final Decision works best for single-stage workflows. Generally, everyone else can be set to Disabled, unless they want to be notified of other people making comments or decisions (in which case, one of the summary email options might work best).
