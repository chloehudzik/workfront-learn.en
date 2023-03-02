---
title: Understand incomplete executions
description: Learn what incomplete executions are and how to handle an error that results in an incomplete execution in [!DNL Adobe Workfront Fusion].
activity: use
team: Technical Marketing
type: Tutorial
feature: Workfront Fusion
role: User
level: Beginner
kt: 9066
exl-id: 3b7bf669-4736-4ba5-bcec-0d3fe0b2ce74
doc-type: video
---
# Understand incomplete executions

Incomplete executions can be stored in Workfront Fusion where they can later be reviewed and resolved. Learn how to take advantage of this amazing feature.

In this video, you will learn:

* What incomplete executions are
* How to handle an error that results in an incomplete execution

>[!VIDEO](https://video.tv.adobe.com/v/335307/?quality=12)

## Errors resulting in incomplete executions

There are several categories of errors that result in the storing of incomplete executions.

Different error types received will depend on the APIs you're connecting to. The error could be a validation errors arising from incomplete or erroneous data, mostly because of a missing item that is expected in order to successfully process all data going through a module. Or the errors could occur from the final destination's unavailability because of temporary or long-term connection failure (e.g. during connection to email or remote FTP server).

If an error occurs on the first module in the scenario, the execution stops immediately and no incomplete execution is stored.

If an error occurs on any other module and there is no error handler route attached, then:

* If the error type is ConnectionError, RateLimitError, OutOfSpaceError or ModuleTimeoutError, an incomplete execution record WITH auto-retry is stored.
* If the error type is DataError, InvalidConfigurationError, InvalidAccessTokenError, UnexpectedError, MaxFileSizeExceededError or MaxResultsExceededError, an incomplete execution record WITHOUT auto-retry is stored.
* If the error type is anything other than the above, the execution fails.

## Want to learn more? We recommend the following:

[Workfront Fusion documentation](https://experienceleague.adobe.com/docs/workfront/using/adobe-workfront-fusion/workfront-fusion-2.html?lang=en)
