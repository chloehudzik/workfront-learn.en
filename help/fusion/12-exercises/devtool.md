---
title: Dev tool
description: Enhance your abilities to troubleshoot a scenario and ease complex configurations using the DevTool.
feature: Workfront Fusion
role: User
level: Beginner
kt: 11057
thumbnail: KT11057.png
exl-id: 13080212-26cf-4e5f-8f0b-fc59a6f66eb1
---
# Dev tool

Enhance your abilities to troubleshoot a scenario and ease complex configurations using the Dev tool.

## Exercise overview

Install and use the different areas in the Workfront Dev tool to take a deeper dive into requests/responses made and advanced scenario design tricks.

>[!NOTE]
>
>The Workfront Fusion Dev tool is only available in the Chrome browser when using the [Chrome developer tool](https://developer.chrome.com/docs/devtools/).

   ![Devtool Image 1](../12-exercises/assets/devtool-walkthrough-1.png)

## Steps to follow

**Install the Dev tool.**

1. Download the "workfront-fusion-devtool.zip" document found in the Fusion Exercise Files folder in the test drive.
1. Extract the Zip files to a folder.
1. Open a tab in Chrome and enter **chrome://extensions**.
1. Toggle on Developer mode using the switch at the top right, then click the "Load unpacked" button that appears at the top left. Select the folder containing the Dev tool (this is where you unzipped it).

   ![Devtool Image 2](../12-exercises/assets/devtool-walkthrough-2.png)

1. Once unpacked, the Dev tool appears among your other extensions.

   ![Devtool Image 3](../12-exercises/assets/devtool-walkthrough-3.png)

    **Use the Live Stream.**

1. Start by opening the "Using Data Stores to sync data" scenario.
1. Open the Dev tool by typing F12 or function F12. Or you can click the three-dot menu in the Chrome address bar and navigate to Developer Tools.

   ![Devtool Image 4](../12-exercises/assets/navigate-to-devtools.png)

1. Click the Workfront Fusion tab, then select Live Stream from the list on the left.
1. Click Run once to see events as they occur.
1. Click on an event to see tabs on the right for Request Headers, Request Body, Response Headers, and Response Body.

   ![Devtool Image 4](../12-exercises/assets/devtool-walkthrough-4.png)

    **Use the Scenario Debugger**

1. Select Scenario Debugger and click a module to see information about the operations of that module.

   ![Devtool Image 5](../12-exercises/assets/devtool-walkthrough-5.png)

1. Navigate to the History tab. Click Details on an execution to examine module operation details for a specific execution.

   ![Devtool Image 6](../12-exercises/assets/devtool-walkthrough-6.png)

    **Use the Tools**

1. Go back to the scenario designer and select Tools in the Dev tool. This displays the tools available.

   ![Devtool Image 7](../12-exercises/assets/devtool-walkthrough-7.png)

+ Focus a Module - Find and open a module quickly by using the module ID.
+ Find Module(s) by Mapping - Search a scenario using a keyword to find mapped values and/or keys in modules.
+ Get App Metadata - See the metadata for the selected app a scenario.
+ Copy Mapping - Copies mapping from one module to another. You also can clone the module in the designer.
+ Copy Filter - Copies a filter. The filter is always assigned to the module on it's right.
+ Swap Connection - The tool takes the connection from the selected module and sets the same connection to all modules of the same app in the scenario. This is helpful if you have to change the connection throughout a completed scenario. Avoid losing all mapping and save time by using this tool.
+ Swap Variable - Finds all occurrences of the given variable across the whole scenario, or in one module, and replaces them with the new one. Wildcards are not supported. If you've accidentally mapped a value throughout the entire scenario, this can help you easily swap for the correct value.
+ Swap App - Swaps the given app for another one.
+ Base 64 - Encode the entered data to Base64 or decode Base64. Useful when you want to search for particular data in the encoded request.
+ Copy Module Name - Copies the selected module name to the clipboard.
+ Remap Source - Change the mapping source from one module to another. You need to first add the module to use as a source module to the route in a scenario.
+ Migrate OS - Made specifically to upgrade Google Sheets (legacy) modules to the latest Google Sheets version. It adds a new version of the module just after the legacy version of the module in the scenario route.
