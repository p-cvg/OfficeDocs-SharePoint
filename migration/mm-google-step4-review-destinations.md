---
ms.date: 01/22/2021
title: "Review the destination paths for your Google migration with Migration Manager"
ms.reviewer: 
ms.author: jhendr
author: JoanneHendrickson
manager: serdars
audience: ITPro
f1.keywords:
- NOCSH
ms.topic: article
ms.service: sharepoint-online
ms.subservice: sharepoint-migration
ms.localizationpriority: high
ms.collection: 
- m365solutions-migratefileshares
- m365solution-migratetom365
- m365solution-scenario
- M365-collaboration
- SPMigration
- highpri
search.appverid: MET150
description: Review your destination paths for your Google migration while using Migration Manager.
---
# Step 4: Review destination paths in Migration Manager Google

In this step, review the destination paths of the accounts you have moved to the migrations list, making sure they are correct. An account cannot be migrated without a destination indicated. Once you start migrating content to a destination, it cannot be modified.

## Single destination edit
If a destination is missing, highlight the row. A panel will appear to the right. Under **Destination**, select **Edit**.  In this step, review the destination paths of the accounts you have moved to the migrations list, making sure they are correct. An account cannot be migrated without a destination indicated. Once you start migrating content to a destination, it cannot be modified.

1. Highlight the row. Under **Destination**, select **Edit.**
2. You have the choice of selecting a OneDrive, SharePoint, or Teams path as a destination. Depending on your selection:

    - For OneDrive, enter the OneDrive URL or email address and the location/folder name
    - For SharePoint, enter site URL and location
    - For Teams, select the team and the channel

3. Select **Save path**.


## Upload destinations using a CSV file

If you have many destinations to edit, you can choose to upload a bulk destinations CSV file.  Download the *MigrationDestinations.csv* file template to your computer and enter your destinations. Save your file as a .csv file using any name you wish. 


![upload destinations for Google accounts bulk](media/mm-box-bulk-upload-destination-panel.png)

1. From the Migrations tab, select **Upload destinations** from the menu bar.
2. Select the file to upload with your destinations.
4. Select **Save**.  


>[!Important]
>Review your destination CSV file before you upload it to make sure you have entered the values in correctly.  The destination file is not validated, and once you have migrated to these destinations it cannot be undone.


## Go to [**Step 5: Map identities**](mm-google-step5-map-identities.md)


>[!NOTE]
>Migration Manager Google Workspace isn't available for users of Office 365 operated by 21Vianet in China.
>
> This feature is also not supported for users of the Government Cloud, including GCC, Consumer, GCC High, or DoD.

