---
title: Introduction to universal connectors
description: Expand your understanding of working with REST universal connectors and working with the data returned.
feature: Workfront Fusion
role: User
level: Beginner
kt: 11042
thumbnail: KT11042.png
exl-id: eb442c3e-26f3-44b7-9937-ed4eeba39fb1
---
# Introduction to universal connectors

Expand your understanding of working with REST universal connectors and working with the data returned.

## Exercise overview

Using a Pokemon character in a spreadsheet, call the Poke API through an HTTP connector to gather and post more information on that character.

   ![Introduction to universal connectors Image 1](../12-exercises/assets/introduction-to-universal-connectors-walkthrough-1.png)

## Steps to follow

   **Download the CSV file from Workfront.**

1. In the Workfront "Fusion Exercise Files" folder, select "_Fusion2020_Shipping Manifest.csv" and click Document Details.
1. Copy the first ID number from the URL address.
1. Create a new scenario in Workfront Fusion. Name it "Using universal connectors."
1. Start with the Download Document module from the Workfront app.
1. Set up your Workfront connection and include the Document ID you copied from the Workfront URL.
1. Rename this module "Download shipping manifest."

   ![Introduction to universal connectors Image 9](../12-exercises/assets/introduction-to-universal-connectors-walkthrough-9.png)

   **Parse the shipping manifest data.**

1. Add another module, selecting Parse CSV.
1. Set up Parse CSV for 11 columns. Check the CSV contains headers box. Choose the Comma delimiterType, and put Data from the Download Document module in the CSV field.

   ![Introduction to universal connectors Image 2](../12-exercises/assets/introduction-to-universal-connectors-walkthrough-2.png)

1. Rename this module "Parse shipping manifest."
1. Save the scenario and click Run once so you can see data from the CSV file in the next steps.

   **Get the Pokemon data using the universal connector.**

1. Add an HTTP Make a Request module.
1. In the URL field use https://pokeapi.co/api/v2/pokemon/[Character], where [Character] is mapped to Column 3 from the Parse CSV module.
1. Select the Parse response check box.
1. Select Show advanced settings and then check the box next to "Evaluate all states as errors."
1. Click OK and rename the module "Get Pokemon info."

   **Your mapping panel should look like this:**

   ![Introduction to universal connectors Image 3](../12-exercises/assets/introduction-to-universal-connectors-walkthrough-3.png)

   **In this part of the exercise, you only want to process row 1 in the CSV file.**

1. Add a filter before your Get Pokemon info module. Name it "Only row 1."
1. Set the condition to only allow ID number 1 to pass. ID number 1 is in row 1, and the ID field is in Column 1 in the CSV file.

   ![Introduction to universal connectors Image 4](../12-exercises/assets/introduction-to-universal-connectors-walkthrough-4.png)

1. Save the scenario.
1. Click Run Once and observe the error message you receive in the HTTP Make a request module.

   >[!IMPORTANT]
   >
   >Notice in the input data URL field the character name is capitalized. This won't work for making that API call because character names need to be lowercase.

   ![Introduction to universal connectors Image 5](../12-exercises/assets/introduction-to-universal-connectors-walkthrough-5.png)

1. Use the mapping panel in the HTTP Make a request URL field to make the [Character] field all lowercase letters using the **lower** function.

   ![Introduction to universal connectors Image 6](../12-exercises/assets/introduction-to-universal-connectors-walkthrough-6.png)

   **Map information back from the API using the Set multiple variables module.**

1. Add the Set multiple variables module after Get Pokemon info. Map name, height, weight, and abilities.
1. Since the Abilities field is an array, remember to use the map function to access the name of each ability in the array.

   ![Introduction to universal connectors Image 7](../12-exercises/assets/introduction-to-universal-connectors-walkthrough-7.png)

   **Run the scenario without the filter to uncover another error.**

1. To process all the rows in the CSV file, delete the filter named Only row 1:
 
   + Click the filter icon to edit it.
   + Delete the filter label.
   + Delete the Condition.
   + Click OK.

1. Save the scenario and click Run once.
1. An error occurs in the Get Pokemon info module. You see a superhero character has been passed to the Pokemon API.

   >[!NOTE]
   >
   >In the Routers walkthrough, you'll see how to resolve this error by creating a separate path to process superheroes.

   ![Introduction to universal connectors Image 8](../12-exercises/assets/introduction-to-universal-connectors-walkthrough-8.png)
