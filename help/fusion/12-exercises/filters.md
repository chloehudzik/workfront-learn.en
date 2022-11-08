---
title: Filters
description: Learn how to use the filter between modules to allow only certain types of bundles through.
feature: Workfront Fusion
role: User
level: Beginner
kt: 11040
thumbnail: KT1101.png
exl-id: d2cec1ea-7ff9-48ae-8bfb-0c767d346079
---
# Filters

Learn how to use the filter between modules to allow only certain types of bundles through.

## Exercise overview

Add a filter between the two modules in the Beyond basic mapping scenario to only create projects that have a "Red" project color in the CSV file.

   ![Filters Image 1](../12-exercises/assets/filters-walkthrough-1.png)

## Steps to follow

1. Create a clone of the "Beyond basic mapping" scenario and name it "Using the mighty filter."

    **Add a filter before the Create Workfront projects module to only allow red projects to be created.**

   ![Filters Image 2](../12-exercises/assets/filters-walkthrough-2.png)

1. Add a filter by clicking the dotted line connecting the modules or clicking the wrench and selecting Set up a filter.
1. Use the Label field to name the filter "Only Red Projects."
1. In the Condition field, map the Project Color field (Column 3 in the CSV file). Select the Equal to (case insensitive) operator, and then type in "red."
1. Click OK.

   ![Filters Image 3](../12-exercises/assets/filters-walkthrough-3.png)

    **Test the filter and verify the results.**

1. Click Save to save the scenario and then Run once.
1. Click the execution inspector for the filter to see how each bundle was examined by the filter and either passed or failed to move on to the Create Workfront projects module.

   ![Filters Image 4](../12-exercises/assets/filters-walkthrough-4.png)

1. Find the projects created in your Workfront instance.
