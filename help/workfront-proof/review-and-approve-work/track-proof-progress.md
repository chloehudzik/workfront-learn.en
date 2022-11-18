---
title: Track proof progress
description: Learn how to use [!UICONTROL SOCD] indicators, proof progress, and reports to track the progress of a proof in [!DNL  Workfront].
activity: use
team: Technical Marketing
feature: Workfront Proof
type: Tutorial
role: User
level: Beginner
thumbnail: track-proof-progress.png
kt: 10111
exl-id: 343483fe-487a-4a23-914d-2807a00630f9
---
# Track proof progress

As a project manager, proof manager, or other stakeholder in the review and approval process, you’ll want to track the progress of your proofs. You can do this with [!DNL Workfront’s] built-in **proof progress indicators** on the [!UICONTROL Documents] page or by writing custom reports.

To view proof progress in [!DNL Workfront], you must have a Plan, Work, or Review license and be a proofing user. If you’re not sure your [!DNL Workfront] profile meets these requirements, check with the proofing system administrator at your organization.

## Track proof progress with [!UICONTROL SOCD] indicators and proof status

Get a high-level view of how the proof is progressing through the review and approval process using the [!UICONTROL SOCD] icons in the [!UICONTROL Documents] list. These icons indicate specific actions taken on the proof.

![An image of the [!UICONTROL Documents] list in an [!DNL  Workfront] project with the [!UICONTROL SOCD] icons highlighted.](assets/manage-proofs-socd.png)

The icons indicate the work done on a proof from the time you send the proof to recipients to the time they make a decision on the proof.

* **S —** The proof has been sent to recipients.
* **O —** The proof has been opened.
* **C —** Comments have been made on the proof.
* **D —** A decision has been made on the proof (approved, rejected, etc.).

The colors indicate if the action is complete or not.

* **White —** The step hasn’t happened yet.
* **Green —** The step has been completed.
* **Orange —** The proof deadline is within 24 hours and the step hasn’t happened.
* **Red —** The proof deadline has passed and the step hasn’t happened.

The [!UICONTROL SOCD] on the [!UICONTROL Documents] list, in the summary panel, or in the [!UICONTROL Document Details], is a high-level summary of the proof’s progress. [!DNL Workfront] configures this based on the recipient who is the “most behind” in the proofing process.

For example, if there are three reviewers/approvers and only two of them have looked at the proof and made comments, then the [!UICONTROL SOCD] icons will show the proof has been sent ([!UICONTROL S]) and opened ([!UICONTROL O]) but not that comments have been made ([!UICONTROL C]).

If you want to know how each individual proof recipient is doing, open the proofing workflow. The overall proof progress is at the top of the window. Each stage has its own progress indicator in the gray bar.  And next to each user is that individual’s progress.

![An image of the [!UICONTROL Proofing Workflow] section of a document.](assets/manage-proofs-socd-in-proofing-workflow-window.png)

## Proof status

The proof status is based on the status of the stage’s proof recipients. The overall proof status is visible on the [!UICONTROL Documents] page, to the right of the [!UICONTROL SOCD] indicators, so you can easily tell if you have a decision on the proof.

![An image of the [!UICONTROL Documents] list in an [!DNL  Workfront] project with the overall proof status highlighted.](assets/manage-proofs-overall-status.png)

This proof status indicates the overall status of the proof. For example, if two recipients approved the proof, their individual statuses show [!UICONTROL Approved]. However, the third recipient hasn’t made a decision yet, so that person’s status is [!UICONTROL Pending]. Therefore, the overall status shows as [!UICONTROL Pending].

If custom statuses were configured for your organization, those statuses will be used. Otherwise, you’ll see the standard status options of:

* [!UICONTROL Pending]
* [!UICONTROL Approved]
* [!UICONTROL Approved with Changes]
* [!UICONTROL Changes required]
* [!UICONTROL Not relevant]

Open the proofing workflow window to see a proof status for recipients assigned the [!UICONTROL Reviewer & Approver] or [!UICONTROL Approver ]proof roles.

## Reports in [!DNL Workfront]

You also can leverage [!DNL Workfront’s] reporting capabilities to track proofs as they move through the review and approval process.

A proof approval report helps you track outstanding approvals to make sure deadlines are met.

![An image of a proof approval report in [!DNL  Workfront].](assets/proof-approval-report.png)

A document version report allows you to manage and track proof versions.

![An image of a document version report in [!DNL  Workfront].](assets/document-version-report.png)

We recommend working with your [!DNL Workfront] consultant to create reports that meet your organization’s requirements. Some of the reports require familiarity with [!DNL Workfront’s] text mode reporting.

## Your turn

Talk with your team or proofing system administrator to find out what kind of reporting you’ll use in Workfront to keep proof workflows running smoothly.

<!--
### Learn more
* Learn to create reports in [!DNL Workfront] with the Basic Report Creation course.
* View progress and status of a proof
* View activity on a proof within [!DNL Workfront]
-->
