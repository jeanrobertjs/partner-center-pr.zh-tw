---
title: Migrate Dynamics AX subscriptions to Dynamics 365 | Partner Center
description: Microsoft introduces Dynamics 365, the next generation of intelligent business applications that enable your organization to grow, evolve and transform to meet the needs of your customers and capture new opportunities.
ms.assetid: 79787bef-a6e9-4c11-8c3b-f0a77485c0a4
author: MaggiePucciEvans
ms.openlocfilehash: 39f254488dab4335a24a5a36fc593d2e281adbf8
ms.sourcegitcommit: 2c948321945d0e61153f7d766a1a669782df4a54
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 07/24/2017
---
# <a name="migrate-dynamics-ax-subscriptions-to-dynamics-365"></a>Migrate Dynamics AX subscriptions to Dynamics 365

**Applies to**

-  Partner Center

Microsoft introduces Dynamics 365, the next generation of intelligent business applications that enable your organization to grow, evolve and transform to meet the needs of your customers and capture new opportunities. Microsoft 在 2016 年 11 月 1 日為客戶引進了新的 Microsoft Dynamics 訂閱方案做為新產品的一部分，該方案與目前的方案類似，但不完全相同。

本文件中的指示說明間接提供者如何將客戶現有的 Microsoft Dynamics AX 訂閱及 Microsoft Dymanics CRM Online 訂閱切換至 Microsoft Dynamics 365。 The instructions also apply to other Microsoft products that update to new versions, requiring providers to migrate customers’ subscriptions to a new SKU.

Microsoft Dynamics CRM Online 和 AX 計畫已淘汰。  自 2017 年 7 月 1 日生效，您已無法續約舊版計畫，現有的 E4 訂閱也不會在到期時自動續約。

當 CRM Online 和 AX 訂閱結束時，將會取消這些訂閱。 為了確保對客戶的持續服務，以下列出可將訂閱即將到期的客戶轉換至支援 SKU 選項的計畫。 我們建議在年度訂閱的結束日期之前將客戶移轉至新的訂閱，以避免發生任何客戶服務中斷。 

在訂閱的詳細資料頁面上，您會看到這些即將到期訂閱的訂閱狀態已從「在 [日期] 自動續約」變更為「在 [日期] 到期」。 

如果使用 API (CREST 或合作夥伴中心)，您可搭配 [自動續約] = False 屬性評估訂閱結束日期，以探索即將到期的訂閱。在 2017 年 7 月 1 日的訂閱已設定為 [自動續約] = False。 您可以隨時將客戶移轉至新的計畫。 

**Microsoft Dynamics AX 授權變更**

Microsoft Dynamics AX 產品線已於 2016 年 11 月 1 日淘汰。 若要深入了解 Dynamics 365 的新授權選項，請檢閱[授權指南](http://download.microsoft.com/documents/dynamics/pricing/Dynamics_365_Enterprise_edition_Licensing_Guide.pdf)。

 請參閱下表以了解授權對應的詳細資料：

|**淘汰的 SKU**   |**Dynamics 365 SKU**   |
|-------------------|:----------------------|
|Enterprise SKU|Microsoft Dynamics 365 for Unified Operations 或 Microsoft Dynamics 365 計畫 |
|工作|Microsoft Dynamics 365 for Activity
|工作/自助|Microsoft Dynamics 365 for Team Members|
|裝置|Microsoft Dynamics 365 for Operations Device|

## <a name="microsoft-dynamics-crm-online-licensing-changes"></a>Microsoft Dynamics CRM Online 授權變更 

**Microsoft Dynamics CRM Online**

目前的 Microsoft Dynamics CRM Online 方案已於 2016 年 11 月 1 日淘汰。 若要深入了解 Microsoft Dynamics 365 的新授權選項，請檢閱[授權指南](http://download.microsoft.com/documents/dynamics/pricing/Dynamics_365_Enterprise_edition_Licensing_Guide.pdf)。 請參閱 [給 CRM Online 客戶的重要資訊](https://go.microsoft.com/fwlink/?linkid=831667)以深入了解新的授權選項。

請參閱下表以了解授權對應的詳細資料：

|**淘汰的 SKU**   |**Dynamics 365 SKU**   |
|-------------------|:----------------------|
|Enterprise|Dynamics 365 Enterprise Customer Engagement Plan |
|Professional|Dynamics 365 Enterprise Customer Engagement Plan、Dynamics 365 for Sales 或 Dynamics 365 for Customer Service|
|Basic|Dynamics 365 for Team Members、Dynamics 365 for Sales、Dynamics 365 for Customer Service 或 Dynamics 365 Enterprise Customer Engagement Plan|
|Essential|Dynamics 365 for Team Members|
|現場服務附加元件|Dynamics 365 Enterprise Customer Engagement Plan 或 Dynamics 365 for Field Service|
|專案服務自動化附加元件|Dynamics 365 Customer Engagement Plan 或 Dynamics 365 for Project Service Automation|



## <a name="transition-customers-to-new-product-plans"></a>將客戶轉換到新產品計畫


Microsoft continuously offers new products and services to resellers and providers. In these cases, a reseller may need to upgrade customers to new services or migrate their subscriptions from SKUs that will eventually be shut down. Migrating customers from old SKUs to newer ones requires the following sequence:

-   [Purchase the new subscription](#manual-subscription-migration-purchasenewsubsc);
-   [Re-assign current user licenses](#manual-subscription-migration-reassignlicenses);
-   [取消舊訂閱](#manual-subscription-migration-cancelsubscriptions)。

在下列程序中，您會將客戶從 Microsoft Dynamics AX 或 CRM Online 移轉至 Dynamics 365。

在此範例中，經銷商需要將擁有現有 Dynamics AX Enterprise 訂閱的客戶移轉至 Dynamics 365 for Operations。 您的第一個步驟是購買 Dynamics 365 for Operations。  針對即將移轉至 Microsoft Dynamics 365 的 CRM Online 客戶重複下列步驟。

<a href="" id="purchasenewsubsc"></a>

**購買新訂閱**

1.  From the **Dashboard** menu, select **Customers**, select the customer you wish to move, and choose **Add Subscriptions**.
2.  Select the subscription you want to purchase from the catalog (in this case, Dynamics 365 for Operations, Enterprise Edition), enter the number of licenses, and choose **Submit**.

    Your customer should now have both old and new subscriptions: in this example, the old Dynamics AX Enterprise, and the new ‘target’ subscription, Dynamics 365 for Operations, Enterprise Edition.

<a href="" id="reassignlicenses"></a> The next step is to reassign all existing user licenses to the new subscription.

**Reassign user licenses**

1.  From the **Dashboard** menu, select **Customers**, select the customer you wish to move, and choose **Users and licenses**. The customer’s Users and Licenses page opens.
2.  To re-assign user licenses, select the user to reassign and then select **Manage licenses**.
3.  On the **Manage licenses** page, clear the **Dynamics AX Enterprise** license check box and select the **Dynamics 365 for Operations** license.
4.  Select **Submit**. A confirmation page lists the new license assignments.
5.  Continue the same steps with any other customer users that need license reassignment.

<a href="" id="cancelsubscriptions"></a> After moving the user licenses to the new service, you can safely cancel the old subscription at the top Customer level.

**Cancel the old subscription**

1.  From the **Dashboard** menu, select **Customers**, select the customer you wish to move, and select the subscription you want to cancel.
2.  In the subscription details page, set the subscription **Status** to **Suspended**.
3.  Select **Submit**.

The old subscription is suspended, and the new subscription is active. The suspended subscription will automatically be de-provisioned after 120 days. The customer incurs no additional costs for the old subscription.

## <a name="additional-considerations"></a>Additional considerations


If your customer is moving from the Open Channel to the Cloud Services Program for further subscription provisioning, you will also need to migrate their existing subscriptions:

-   If the customer received their old subscription through the Open Channel, moving to the CSP on the new SKU is straightforward.
-   If the customer is not yet established as your customer, you can invite them. For information, see the [Request a relationship with a customer](https://msdn.microsoft.com/en-us/library/partnercenter/mt750320.aspx) help topic.

After the customer accepts you as their indirect provider, the provisioning steps are mostly the same as described above: you purchase the new subscription, and then assign the user licenses. The only difference involves cancellation of old subscription(s). A new provider cannot cancel suspend/cancel subscriptions acquired via other channels. If the customer acquired prior subscriptions in another sales channel, such as the Open channel, the customer will need to cancel it themselves through that channel.

 

 



