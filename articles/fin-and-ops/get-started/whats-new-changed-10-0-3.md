---
# required metadata

title: Preview features in Finance and Operations version 10.0.3 (June 2019)
description: This topic describes features that are either new or changed in Dynamics 365 for Finance and Operations version 10.0.3. This version will be released in June.
author: tonyafehr
manager: AnnBe
ms.date: 05/07/2019
ms.topic: article
ms.prod: 
ms.service: dynamics-ax-platform
ms.technology: 

# optional metadata

# ms.search.form: 
# ROBOTS: 
audience: Developer, IT Pro
# ms.devlang: 
ms.reviewer: tfehr
ms.search.scope:  Operations
# ms.tgt_pltfrm: 
ms.custom: 
ms.assetid: a362a31d-44df-45c5-b698-64c5264c592e
ms.search.region: Global
# ms.search.industry: 
ms.author: tfehr
ms.search.validFrom:  
ms.dyn365.ops.version: Release 10.0.3

---
# Preview features in Finance and Operations version 10.0.3 (June 2019)

[!include [banner](../includes/banner.md)]

[!include [banner](../includes/preview-banner.md)]

This topic describes features that are either new or changed in Microsoft Dynamics 365 for Finance and Operations version 10.0.3. This version will be released in June and has a build number of 10.0.107. For more information about version 10.0.3, see [Additional resources](whats-new-changed-10-0-3.md#additional-resources).


## Feature management

The **Feature management** experience provides a workspace where you can view a list of features that have been delivered in each release. By default, new features are turned off. You can use the workspace to turn them on and view the documentation for them.

For more information, see [Feature management](https://go.microsoft.com/fwlink/?linkid=2080380).

## Enable Bank foreign currency revaluation without a parameter
Bank foreign currency revaluation was released in version 10.0.2 and it included a parameter in Cash and Bank parameters to enable it. You can now enable bank foreign currency revaluation for all legal entities where it is available using feature management. 

For more information, see [Bank foreign currency revaluation](https://go.microsoft.com/fwlink/?linkid=2079802).

## Set up interest distribution for cash accounts
Your agency can allocate (distribute) the interest on a bank account to specific General ledger accounts, based on the average daily balance in cash accounts. You can use this process to generate an advanced ledger entry for the interest amounts. Alternatively, you can generate the interest amounts for review, without posting them.

For more information, see [Interest distribution for cash accounts](https://go.microsoft.com/fwlink/?linkid=2088607).

## Expense reports re-imagined
Expense report entry has been redesigned to simplify and decrease the time to complete your expense report. You can enable this functionality in feature management to add a new setup form to configure expense fields visibility to determine what data is required, optional, or not enabled for entering expense reports. A new expense workspace is enabled with this feature, replacing the previous expense workspace and is the landing page for the improved entry experience. 

For more information, see [Expense reports re-imagined](https://go.microsoft.com/fwlink/?linkid=2087165).

## Additional resources

### Bug fixes
For information about the bug fixes included in each of the updates that are part of Finance and Operations version 10.0.3, sign in to Lifecycle Services (LCS) and view the [KB article](https://fix.lcs.dynamics.com/Issue/Details?bugId=320385&dbType=3&qc=d5539716f56ccea45e2187c269570772af20e1f10a78371811220da6315a3c34).

### Platform update 27
Microsoft Dynamics 365 for Finance and Operations version 10.0.3 includes Platform update 27. To learn more about Platform update 27, see [Preview features in Finance and Operations platform update 27 (June 2019)](whats-new-platform-update-27.md).

### Dynamics 365 April '19 release notes
Wondering about upcoming and recently released capabilities in any of our business apps or platform?

[Check out the April '19 release notes](https://docs.microsoft.com/en-us/business-applications-release-notes/April19/index). We've captured all the details, end to end, top to bottom, in a single document that you can use for planning.

### Removed and deprecated features
The [Removed or deprecated features](../../dev-itpro/migration-upgrade/deprecated-features.md) topic describes features that have been removed or deprecated for Dynamics 365 for Finance and Operations.

- A *removed* feature is no longer available in the product.
- A *deprecated* feature is not in active development and may be removed in a future update.

Before any feature is removed from the product, the deprecation notice will be announced in the [Removed or deprecated features](../../dev-itpro/migration-upgrade/deprecated-features.md) topic 12 months prior to the removal.

For breaking changes that only affect compilation time, but are binary compatible with sandbox and production environments, the deprecation time will be less than 12 months. Typically, these are functional updates that need to be made to the compiler.
