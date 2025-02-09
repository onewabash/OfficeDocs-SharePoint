---
title: "Limit access"
ms.author: v-bshilpa
author: Benny-54
manager: serdars
audience: Admin
f1.keywords:
- CSH
ms.topic: article
ms.service: one-drive
ms.localizationpriority: medium
ms.collection: 
- Strat_OD_admin
- M365-collaboration
search.appverid:
ms.assetid: 
ms.custom: admindeeplinkSPO
description: "In this article, you'll learn how to all only users in specified security groups to access OneDrive."
---

# Limit OneDrive access by security group

Use this setting if you want to allow only users in specified security groups to access OneDrive. Even if other users outside of these security groups are licensed for OneDrive, they won’t have access to their own OneDrive or any shared OneDrive content.

## Requirements

To enable this feature, you need a subscription to one of the following plans:

- Office 365 E5

- Office 365 A5

- Microsoft 365 E5

- Microsoft 365 E5 Compliance

- Microsoft 365 E5 Information Protection and Governance

- Microsoft 365 A5

## Enablement

To enable this feature:

1. Go to <a href="https://go.microsoft.com/fwlink/?linkid=2185071" target="_blank">Access control in the SharePoint admin center</a>, and sign in with an account that has [admin permissions](/sharepoint/sharepoint-admin-role) for your organization.

2. Select **Limit OneDrive access**.

3. Select **Limit OneDrive access to only users in specified security groups**.

   ![Limit access on the Access control page in the SharePoint admin center](media/limit-access.png)

4. Add the security groups you want to be able to use OneDrive.

5. Select **Save**.

> [!NOTE]
> Users who aren't included in the security groups you added will lose access to their own OneDrive and any shared OneDrive content.
