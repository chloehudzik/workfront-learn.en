---
title: Proof roles and email alerts
description: Learn how to enable proper proof roles and email alerts so proof recipients have access to proofs and visibility into the work being done in [!DNL  Workfront].
activity: use
team: Technical Marketing
feature: Workfront Proof
type: Tutorial
role: User, Admin
level: Beginner
thumbnail: proof-roles-and-email-alerts.png
kt: 10177
exl-id: 15bfb18a-5392-4a91-a6a2-223f7ac30dc5
---
# Proof roles and email alerts

Proof roles and email alerts help drive the proof workflow, making sure recipients have the right access to proofs and have visibility into the work being done.

Let’s review some basic proof terminology:

* **Proof role —** Defines what a user can do with a proof (e.g., comment, markup, approve, etc.).
* **Email alert —** Emails sent to people in the proof workflow when there’s activity on the proof.

![An image of the [!UICONTROL New Proof] window with the [!UICONTROL Proof role] and [!UICONTROL Email alerts] columns highlighted.](assets/proof-roles-and-email-alerts.png)

Your proof system administrator can set default proof roles and email alerts for your organization’s proof users. In addition, this information can be built into proof workflow templates (also known as automated workflow templates).

There may be times, however, when you need to set this information manually while uploading a proof.

[!DNL Workfront] offers these general recommendations when assigning proof roles to proof recipients:

* **Reviewer & Approver —** These users can both make comments on proofs and make a decision (such as approved or rejected) on a proof. Use this proof role for the key internal and external stakeholders in the review process.
* **Reviewer —** Some people in your proof workflow only need to make comments, this role is ideal for them. The reviewer role can also be assigned to [!DNL Workfront] users who primarily upload proofs or serve as a proof owner but otherwise aren’t part of the proofing process.
* **Read Only —** Ideal for recipients who only need to see the proof. [!UICONTROL Read Only] gives view access and doesn’t allow for comments.

[!DNL Workfront] offers these general recommendations when assigning email alerts to proof recipients:

* **Final decision —** This sends an email when the last person makes a decision on the proof. Assign this to the person monitoring the proof workflow. This could be a proof manager, proof owner, proof creator, project manager, or other [!DNL Workfront] user. [!DNL Workfront] recommends this alert when using a basic workflow, so the person monitoring the proof knows that all decisions have been made.
* **Decisions —** This sends alerts as each proofing workflow stakeholder makes a decision on the proof. This option is best when using an automated workflow, with several decisions. Assign to the person monitoring the proof workflow. This could be a proof manager, proof owner, proof creator, project manager, or other [!DNL Workfront] user.
* **Disabled —** Use this for guest proof users to limit the number of emails they receive about the proof. Recipients are still notified about new proofs, new versions, and late proofs, plus [!DNL Workfront] users receive direct messages made in a proof comment using @username and guest recipients with @emailaddress.

## Your turn

1. Log in to Workfront and create users who will use proofing that you haven’t previously created. Set the proof permissions profile in their user settings according to the role the person will play in proof workflows.
1. For users who are already created, edit their settings to adjust the and proof permissions profile selection, if needed.
1. Access the proofing setups area and go to the Users tab. Check the personal settings for your users—language, time zone, date format, default proof role, and default email alert. This is important if these users were created before the global system defaults were established (these settings are discussed in Section 1 of this learning path).

<!--
Download the proof role and email alert guides to have on hand as you start uploading proofs and assigning proof recipients.
-->

<!--
## Learn more
* Notifications for proof comments and decisions
-->

<!--
## Guides
* Proof roles
* Email alerts
-->
