# AIandSPFX
This sample project enables Graph API data to be pulled in Dataverse


## Applies to

*   [Microsoft Power Automate](https://docs.microsoft.com/power-automate/)
*   [Microsoft Dataverse](https://docs.microsoft.com/en-us/power-apps/maker/data-platform/data-platform-intro)

## Compatibility
![Custom Connectors](https://img.shields.io/badge/Custom%20Connectors-%20Required-orange.svg)
![On-Premises Connectors](https://img.shields.io/badge/On--Premises%20Connectors-No-green.svg)

## Features

This sample demonstrates the following concepts:

*   Use of DataVerse Tables to trigger Power Automate
*   Development of a Custom Connector to connect to Microsoft Graph API
*   Graph API Paging
*   Returning Data to DataFlow

### Import  Solution
In Dataverse,  **Select during import** and select the Custom Connector Connection previously created.
Once complete, select **Import**.

### Configure Users Automation

Once the solution is imported into the environment, click Settings
Select the **Get Organization Users** action and edit ***$Filter*** properties that are appropriate.
Save your flow.
Select the **When a HTTP request is recieved** trigger and copy the ***HTTP Post URL***.

### Alternative Uses
Replace the **When a HTTP request is recieved** trigger to a **PowerApps Trigger**


