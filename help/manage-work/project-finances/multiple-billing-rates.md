---
title: Understand multiple billing rates
description: Learn how to override system billing rates within a project.
activity: use
team: Technical Marketing
feature: Work Management
thumbnail: understand-multiple-billing-rates.png
type: Tutorial
role: User
level: Intermediate
kt: 10048
exl-id: bda562b9-f8da-49c9-bea7-0440fdc4c24c
---
# Understand multiple billing rates

Within [!DNL Workfront], a project manager has the ability to override system billing rates within a specific project. Previously, when the new billing rate was applied to the project, it not only affected future hours but hours already logged on the project.

With [!DNL Workfront]’s new multiple billing rate capability, the project manager is able to decide what period of time a billing rate should be applied. This way, if a rate has been negotiated or changed, the project manager can determine when that rate should take effect.

## Change the billing rate

1. Go to the project’s landing page. Select **[!UICONTROL Billing Rates]** from the left panel.

   ![An image of selecting [!UICONTROL Billing Rates] in [!DNL Workfront]](assets/project-finances-1.png)

1. From the **[!UICONTROL Billing Rates]** tab, click the **[!UICONTROL Add Billing Rate]** button. Select **[!UICONTROL New Billing Rate]** from the dropdown.

   ![An image of selecting [!UICONTROL New Billing Rate] in [!DNL Workfront]](assets/project-finances-2.png)

1. The [!UICONTROL New Billing Rate] dialogue box appears. From the **[!UICONTROL Job Role]** dropdown, select the job role to which the new billing rate will be applied.

   ![An image of selecting job roles in a new billing rate in [!DNL Workfront]](assets/project-finances-3.png)

1. Once the job role is selected, the [!UICONTROL Default Billing Rate] and the [!UICONTROL Billing Rate 1] field appear. Enter the new billing rate in the [!UICONTROL Billing Rate 1] field. If that billing rate applies to the whole project (past, present, and future hours logged), click the **[!UICONTROL Save]** button.

   ![An image of saving a new billing rate that applies to the whole project in [!DNL Workfront]](assets/project-finances-5.png)

1. If the new billing rate only applies for a certain period of time, click the **[!UICONTROL Add Rate]** button. The [!UICONTROL Billing Rate 1 End Date] and the [!UICONTROL Billing Rate 2] fields appear. Enter the End Date for [!UICONTROL Billing Rate 1]. You cannot enter a Start Date for [!UICONTROL Billing Rate 1] because the system assumes it started at the beginning of the project.

   ![An image of creating a new billing rate that applies to a certain period of time, starting at the beginning of the project in [!DNL Workfront]](assets/project-finances-6.png)

1. If this is not the case:

   * Enter the default billing rate for [!UICONTROL Billing Rate 1].
   * Select the End Date for [!UICONTROL Billing Rate 1] ([!UICONTROL Default Billing Rate]).
   * The Start Date for [!UICONTROL Billing Rate 2] will automatically be set to the day after [!UICONTROL Billing Rate 1] ends.
   * Enter the desired billing rate in the [!UICONTROL Billing Rate 2] section.
   * Continue to add billing rates, as needed, by clicking the **[!UICONTROL Add Rate]** button.
   * When done, click **[!UICONTROL Save]**.
   * All Billing Rates will show in the [!UICONTROL Billing Rates] tab on the project.

   ![An image of creating new billing rates that apply to the different time periods in [!DNL Workfront]](assets/project-finances-7.png)
