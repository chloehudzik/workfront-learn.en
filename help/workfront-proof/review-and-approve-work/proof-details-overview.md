---
title: Understand proof details
description: Dig deeper into the details behind a proof in [!DNL  Workfront] through the summary panel and [!UICONTROL Document Details] page.
activity: use
team: Technical Marketing
feature: Workfront Proof
type: Tutorial
role: User, Admin
level: Beginner
thumbnail: understand-proof-details.png
kt: 10110
exl-id: 196f9318-eced-4825-b0fd-8592b6cb3403
---
# Understand proof details

## View proof details

As a proof manager or owner, you can dig deeper into the details behind a proof through the summary panel and the [!UICONTROL Document Details] page. Start by finding your proof in the [!UICONTROL Documents] section of a project, task, or issue.

### Summary panel

The summary panel provides a high-level overview of the proof’s basic details. Use the icon to expand the panel when you need it and collapse it when you don’t. You can even hover over the thumbnail of the proof to open or download it.

![An image of the [!UICONTROL Documents] section of a project with a proof selected and the summary panel expanded. Both the summary panel icon and summary panel are highlighted.](assets/document-summary.png)

Note: The [!UICONTROL Approvals] section in the summary panel is for **document** approvals and **is not** tied to the proof review and approval process you’ve been learning about in this course. The two processes are separate in [!DNL Workfront].

### [!UICONTROL Document Details]

If you need more information about the proof, the [!UICONTROL Document Details] link takes you to the proof’s “page” in [!DNL Workfront].

![An image of the proof's page in [!DNL  Workfront].](assets/document-details.png)

It’s important to note that the ability to see information related to the proofing process depends on your proofing permissions in [!DNL Workfront].

From the proof’s page, you can access these sections from the left panel menu:

* **Updates —** Comments made in the proof viewer show up here, with a “proof comment” tag. You can also make comments on the file, just like you make comments on a task or project (these comments do not appear in the proof viewer).
* **Approvals —** This section is for document approvals, not proofing approvals. The two types of approvals are separate processes in [!DNL Workfront] and do not link together. If you’re using proof workflows for your reviews and approvals, you won’t use this section.
* **All Versions —** Track and manage the version history of the proof. You may find it easier to access this information in the summary panel on the [!UICONTROL Documents] list.
* **Custom Forms —** Custom forms are used on proofs to capture organization-specific information. This information can be passed with the file to integrated document storage systems, such as [!DNL Workfront] DAM or [!DNL Adobe’s] AEM. Custom forms are set up by your [!DNL Workfront] system administrator or group administrator. Talk with your team or your administrators to learn if you will be using custom forms on proofs.
* **Proofing Workflow —** Manage or modify the workflow assigned to the proof. You can open this window using the [!UICONTROL Proofing Workflow] link on the proof in the [!UICONTROL Documents] list, too. Learn how to make changes to the workflow with the Edit a proof workflow video.

Let’s take a closer look at two of the sections: [!UICONTROL Proofing Viewer Settings] and [!UICONTROL Proofing Activity]. 

### [!UICONTROL Proofing Viewer Settings]

These settings help you control access to the proof itself.

![An image of the [!UICONTROL Proofing Viewer Settings] from the proof's page with the [!UICONTROL Proofing Viewer Settings] option highlighted in the left panel menu.](assets/proofing-settings-on-details-page.png)

* **[!UICONTROL Require login. This proof cannot be shared with guest users] —** The proof can be shared only with people who have a [!DNL Workfront] proofing license.
* **[!UICONTROL Require decisions to be electronically signed] —** When sharing a proof, this requires that the recipient have proofing permissions in [!DNL Workfront] and makes them “electronically sign” the proof by entering their proofing password when they make a proof decision. (Note: The proofing password is different from your [!DNL Workfront] password. The proofing password is not easily accessible, so most recipients will not know this password.) [!DNL Workfront] recommends talking with your [!DNL Workfront] consultant before using this feature.
* **[!UICONTROL Lock proof when all required decisions are made ]—** This locks the proof to any further comments, replies, decisions, etc., once every decision on the proof has been made. This locks the whole proof version, not just a specific stage of the proofing workflow.
* **[!UICONTROL Allow downloading the original file] —** Proof recipients are able to download the original source file of the proof from the proofing viewer (the option is in the right panel menu).
* **[!UICONTROL Allow sharing proof via public URL or embed code] —** Proof recipients can share a publicly accessible proof link with anyone.
* **[!UICONTROL Allow subscribing to proof via public URL or embed code] —** Anyone who is sent the public URL can add themselves to the proof with their email address and name (if not a proof users) or their email address and proofing password (if a proofing user). (Note: The proofing password is not the same as a [!DNL Workfront] password.)

These same settings can be set when the proof is uploaded in the [!UICONTROL Proof settings] section, at the bottom of the upload window.

![An image of the [!UICONTROL Proof settings] section at the bottom of the upload window.](assets/proof-settings-on-upload-page.png)

### [!UICONTROL Proofing Activity]

This page tracks all of the activity that’s happened on the proof, plus the email messages that were sent regarding this proof.

![An image of the [!UICONTROL Proofing Activity] section of the proof's page with the [!UICONTROL Proofing Activity] option highlighted in the left panel menu.](assets/proofing-activity-in-details.png)

The [!UICONTROL Activity] section timestamps when comments and decisions were made, plus who made them. It also tracks when proofing workflow stages started, when a recipient first opened a proof, and other information a proof manager or owner will want to know. These details can be helpful when you’re trying to figure out things like, why a proofing workflow stage never kicked off, for example.

The [!UICONTROL Messages] section timestamps when email alerts and messages were sent to recipients, who sent them, and the content of the message. This can be useful when troubleshooting if someone says they didn’t receive an email about a proof. You can check if and when an email was sent.

[!DNL Workfront] recommends the proof manager and proof owner become familiar with the information in these two sections. When you combine this information with understanding how to read the [!UICONTROL SOCD] progress bar, you can truly understand and manage your proofs, no matter where they are in the proofing workflow.

Once you’re done working in the [!UICONTROL Document Details] section, use the breadcrumb trail to get back to the [!UICONTROL Documents] section of the project, task, or issue the proof is attached to.

![An image of the breadcrumb trail in the header.](assets/proof-breadcrumb.png)

<!--
#### Learn more
* [!UICONTROL Document details] overview
* Add a custom form to a document
* Request document approvals
* Summary for documents overview
* View activity on a proof within [!DNL Workfront]
-->
