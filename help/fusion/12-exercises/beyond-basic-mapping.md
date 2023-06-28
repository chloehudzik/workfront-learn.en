---
title: Beyond basic mapping
description: Learn how to use the mapping panel formulas to manipulate or convert field(s) sent to a module.
activity: use
team: Technical Marketing
type: Tutorial
feature: Workfront Fusion
role: User
level: Beginner
jira: KT-11039
thumbnail: KT11039.png
exl-id: 979d794d-b936-402e-b07c-71e999f40780
---
# Beyond basic mapping

Learn how to use the mapping panel formulas to manipulate or convert field(s) sent to a module.

## Exercise overview

Change the project name, planned start date, and priority from the Beyond Basic Mapping walkthrough exercises using the mapping panel formulas.

   ![Beyond Basic Mapping Image 1](../12-exercises/assets/beyond-basic-mapping-walkthrough-1.png)

## Steps to follow

   **Make a clone of your Initial scenario design scenario.**

1. Select the Clone option to the right of the Initial scenario design in the scenario section, as shown below. Name it "Beyond basic mapping."

   ![Beyond Basic Mapping Image 2](../12-exercises/assets/beyond-basic-mapping-walkthrough-2.png)

   **Now we're going to use the mapping panel in the Create Workfront projects module to configure the project name, planned start date, and priority fields.**

1. Click the Create Workfront projects module to edit the settings. Using the mapping panel, change the Name field to be "[My Project Name] by [Sponsor]."

   + The [My Project Name] is column 1 from the Parse CSV module and [Sponsor] is column 6. The word "by" is just typed between the two.

1. Next go to the Planned Start Date and use the addDays formula to add 15 days to the field, as described in the Beyond basic mapping walkthrough video.
1. Find the Priority field and toggle the Map button at the top right of the field. The picklist menu changes to a number. Create an if statement to label a project as High(4) priority if the CSV file confidence rating is less than 100, otherwise it can be Normal(2).

   + The confidence rating is in Column 4.

   **At this point, your mapping panel should look like this:**

   ![Beyond Basic Mapping Image 3](../12-exercises/assets/beyond-basic-mapping-walkthrough-3.png)

1. Click OK and then click Run once.
1. Find the project in your Workfront instance to make sure everything was mapped correctly.
1. Save your scenario.
