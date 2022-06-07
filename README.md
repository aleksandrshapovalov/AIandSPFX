# AIandSPFX


This sample project enables Graph API data to be pulled in Dataverse


## Applies to

*   [Microsoft Power Automate](https://docs.microsoft.com/power-automate/)
*   [Microsoft Power BI](https://docs.microsoft.com/en-us/power-bi/)

## Compatibility

![Premium License](https://img.shields.io/badge/Premium%20Power%20Automate-Required-orange)

![On-Premises Connectors](https://img.shields.io/badge/On--Premises%20Connectors-No-green.svg)

![Custom Connectors](https://img.shields.io/badge/Custom%20Connectors-%20Required-orange.svg)

## Features

This sample demonstrates the following concepts:

*   Use of Power BI Report / Power BI Data Flows to trigger Power Automate
*   Development of a Custom Connector to connect to Microsoft Graph API
*   Graph API Paging
*   Returning Data to Power BI Report / Power BI Dataflow

## Minimal Path to Awesome
*   [Configure Azure Application and Import Custom Connector](customconnector.md "Configure Azure Application and Import Custom Connector")
*   [Download](solution/GetOrganizationUsers.zip) the `GetOrganizationUsers.zip` from the `solution` folder
*   [Import](https://flow.microsoft.com/en-us/blog/import-export-bap-packages/) the `GetOrganizationUsers.zip` file using **My Flows** > **Import** > **Upload** within Microsoft Flow.

### Import Get Organization Users Solution
Select the **Microsoft Graph API Demo Connection**, under **Related Resources** > **Select during import** and select the Custom Connector Connection previously created.
  
Once complete, select **Import**.

### Configure Get Organization Users Automation

Once the solution is imported, edit it
Select the **Get Organization Users** action and edit ***$Filter*** properties that are appropriate.
Save your flow.
Select the **When a HTTP request is recieved** trigger and copy the ***HTTP Post URL***.

### Alternative Uses
Replace the **When a HTTP request is recieved** trigger to a **PowerApps Trigger**


