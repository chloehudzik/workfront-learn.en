---
title: Create OR statements in filters
description: Learn how to use an OR statement to tell Workfront that you want to see either this OR that in your report.
activity: use
team: Technical Marketing
feature: Reports and Dashboards
thumbnail: create-or-statements-in-filters.png
type: Tutorial
role: User
level: Intermediate
kt: 9987
exl-id: 1a56f2f6-12df-43a5-943c-986a85661efa
---
# Create OR statements in filters

When you build a filter with multiple lines of criteria, by default Workfront puts an AND between each line. This means each result in the list when you use this filter meets all the filter rules. 

In this example, we have three criteria, or rules, for a project filter: 

1. The project must have a planned completion date that falls in the current month. 
1. The project must be in the Events Marketing portfolio. 
1. The project must be an active project, meaning it must have a status of Current. 

![An image of creating a filter with AND statements in [!DNL Workfront]](assets/or-statement-1.png)

The projects in the results list meet all three of those criteria, helping you narrow down the search results so you can see the exact information you need. 

![An image of a filtered list in [!DNL Workfront]](assets/or-statement-2.png)

However, there may be times you want the filter results to meet various criteria, and that's when OR statements can help. With an OR statement, you're telling the filter that you want to see things that match ANY of your OR statements as opposed to ALL of your AND statements.  

## Using OR statements 

OR statements expand or increase the amount of information the filter finds because to show up in the results list, an item has to meet only one of the filter rules, not all of them. 

Let's look at a simple OR statement—projects you're the project manager (owner) for OR projects that were created by you. 

![An image of creating a filter with OR statements in [!DNL Workfront]](assets/or-statement-3.png)

After setting up both filter rules, click the AND between them and switch it to OR. 

![An image of creating a filter with OR statements in [!DNL Workfront]](assets/or-statement-4.png)

The OR between the two filter rules expands your search criteria, telling Workfront to find projects that meet one or the other of those options—your name is in the project owner field or you're the person who created the project. 

## Multiple filter rules with OR statements 

Now let's look at an OR statement that contains multiple filter rules on each side of the OR. This uses the same two rules as before but adds a rule—projects also must have a Current status. 

![An image of creating a filter with OR statements in [!DNL Workfront]](assets/or-statement-5.png)

Notice that Workfront "grouped" the filter rules on each side of the OR (there's a gray box around them). This tells Workfront to run the rules on each side of the OR together, finding projects that meet both of those criteria because they're joined with AND. 

In this example, Workfront looks for: 

* Projects that have your name in the project owner field that also have a status of Current. 
* **PLUS (OR)** 
* Projects that you created that also have a status of Current. 

Putting the "project status equals Current" rule on each side of the OR ensures that rule works in conjunction with each of the other rules. This common rule is sometimes referred to as the "constant." 

>[!NOTE]
>
>You're not limited to one repeated filter rule on each side of the OR. Depending on your needs, you may have multiple. Workfront recommends keeping these repeated rules to a minimum, to ensure the filter provides the results you need. 

## What happens without the common filter rule?

Without the common filter rule(s), you may not get the search results you anticipated. 

For example, if you put the "project status equals Current" rule only on one side of the OR, it only works with the other filter rules in that section. In the image below, you see the "project status equals Current" rule is in the top section only. 

![An image of creating a filter with OR statements in [!DNL Workfront]](assets/or-statement-6.png)

This means Workfront will look for: 

* Projects that have your name in the project owner field and have a status of Current. 
* **PLUS (OR)** 
* All projects you created. 

As you can see, this filter setup gives you slightly different results than the filter with the repeated filter rule. That's why making sure the filter is set up properly is important to ensuring you're getting the results you want and need. 

You may not use OR statements frequently when creating filters. But doing so might help you reduce the number of filters you need to create. Just make sure that your filters don't return too many results—a long list can make finding the exact information needed more difficult for users. 

## OR filter activity

You want to find incomplete tasks that are assigned to you or that aren't assigned to anyone. You set up a filter to look like the one below. Will this filter give you the results you want? Why or why not? 

![An image of an improperly created OR statement in [!DNL Workfront]](assets/or-statement-your-turn-1.png)

### Answers 

No, this filter will not provide the results you're hoping for—tasks that aren't finished that are either assigned to you or assigned to no one—because the filter rule for the task status is only on one side of the OR. 

Instead, this filter will generate a list that shows: 

* Tasks assigned to you that have a status of In Progress or New. 
* **PLUS (OR)** 
* All unassigned tasks, no matter what the status is. 

The filter should look like the one below. Notice this filter has the filter rule for task status on both sides of the OR. 

![An image of a properly created OR statement in [!DNL Workfront]](assets/or-statement-your-turn-2.png)
