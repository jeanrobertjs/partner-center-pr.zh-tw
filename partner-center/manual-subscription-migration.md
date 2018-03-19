---
title: "將 Dynamics AX 訂閱遷移至 Dynamics 365 | 合作夥伴中心"
description: "Microsoft 引進新一代智慧型商業應用程式 Dynamics 365，它可讓您的組織成長、進化及轉型以滿足您客戶的需求，並掌握新的商機。"
ms.assetid: 79787bef-a6e9-4c11-8c3b-f0a77485c0a4
author: MaggiePucciEvans
ms.openlocfilehash: 39f254488dab4335a24a5a36fc593d2e281adbf8
ms.sourcegitcommit: 2c948321945d0e61153f7d766a1a669782df4a54
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 07/24/2017
---
# <a name="migrate-dynamics-ax-subscriptions-to-dynamics-365"></a>將 Dynamics AX 訂閱遷移至 Dynamics 365

**適用於**

-  合作夥伴中心

Microsoft 引進新一代智慧型商業應用程式 Dynamics 365，它可讓您的組織成長、進化及轉型以滿足您客戶的需求，並掌握新的商機。 Microsoft 在 2016 年 11 月 1 日為客戶引進了新的 Microsoft Dynamics 訂閱方案做為新產品的一部分，該方案與目前的方案類似，但不完全相同。

本文件中的指示說明間接提供者如何將客戶現有的 Microsoft Dynamics AX 訂閱及 Microsoft Dymanics CRM Online 訂閱切換至 Microsoft Dynamics 365。 此指示也適用於其他更新至新版本而需要提供者將客戶訂閱遷移至新 SKU 的 Microsoft 產品。

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


Microsoft 會持續提供新的產品及服務給經銷商和提供者。 在這些情況下，經銷商可能需要將客戶升級到新服務，或是從最後將會關閉的 SKU 移轉其訂閱。 將客戶從舊的 SKU 移轉到較新的 SKU 時需要依照以下順序執行：

-   [購買新訂閱](#manual-subscription-migration-purchasenewsubsc)；
-   [重新指派目前的使用者授權](#manual-subscription-migration-reassignlicenses)；
-   [取消舊訂閱](#manual-subscription-migration-cancelsubscriptions)。

在下列程序中，您會將客戶從 Microsoft Dynamics AX 或 CRM Online 移轉至 Dynamics 365。

在此範例中，經銷商需要將擁有現有 Dynamics AX Enterprise 訂閱的客戶移轉至 Dynamics 365 for Operations。 您的第一個步驟是購買 Dynamics 365 for Operations。  針對即將移轉至 Microsoft Dynamics 365 的 CRM Online 客戶重複下列步驟。

<a href="" id="purchasenewsubsc"></a>

**購買新訂閱**

1.  從 **\[儀表板\]** 功能表，選取 **\[客戶\]**，選取您要移動的客戶，然後選擇 **\[新增訂閱\]**。
2.  選取您要從型錄購買的訂閱 (在此案例中為 Dynamics 365 for Operations Enterprise Edition)，輸入授權數量，然後選擇 **\[送出\]**。

    您的客戶現在應該會同時有舊的和新的訂閱：在本範例中，舊的訂閱為 Dynamics AX Enterprise，新的「目標」訂閱為 Dynamics 365 for Operations Enterprise Edition。

<a href="" id="reassignlicenses"></a>下一步是將所有現有的使用者授權重新指派到新訂閱。

**重新指派使用者授權**

1.  從 **\[儀表板\]** 功能表，選取 **\[客戶\]**，選取您要移動的客戶，然後選擇 **\[使用者與授權\]**。 客戶的 \[使用者與授權\] 頁面隨即開啟。
2.  若要重新指派使用者授權，請選取要重新指派的使用者，然後選取 **\[管理授權\]**。
3.  在 **\[管理授權\]** 頁面上，清除 **\[Dynamics AX Enterprise\]** 授權核取方塊，並選取 **\[Dynamics 365 for Operations\]** 授權。
4.  選取 **\[送出\]**。 確認頁面會列出新的授權指派。
5.  針對需要重新指派授權的任何其他客戶使用者繼續執行相同步驟。

<a href="" id="cancelsubscriptions"></a>將使用者授權移至新服務後，您就可以放心地取消最上層 \[客戶\] 的舊訂閱。

**取消舊訂閱**

1.  從 **\[儀表板\]** 功能表，選取 **\[客戶\]**，選取您要移動的客戶，然後選取要取消的訂閱。
2.  在訂閱詳細資料頁面中，將訂閱的 **\[狀態\]** 設定為 **\[暫停\]**。
3.  選取 **\[送出\]**。

舊訂閱已暫停，而新訂閱為使用中。 暫停的訂閱將在 120 天後自動解除佈建。 客戶不會因為舊訂閱而產生額外費用。

## <a name="additional-considerations"></a>其他考量


如果您的客戶是從 Open Channel 移至雲端服務計畫以獲得進一步的訂閱佈建，您也必須移轉他們現有的訂閱：

-   如果客戶是透過 Open Channel 接收舊訂閱，則移至新 SKU 上的雲端解決方案提供者就會非常簡單。
-   如果客戶尚未建立為您的客戶，您可以邀請他們。 如需詳細資訊，請參閱[要求與客戶建立關係](https://msdn.microsoft.com/en-us/library/partnercenter/mt750320.aspx)說明主題。

客戶接受您成為其間接提供者之後，佈建步驟幾乎與上述步驟相同：您要購買新訂閱，然後指派使用者授權。 唯一的不同是取消舊訂閱。 新的提供者無法暫停/取消透過其他通路取得的訂閱。 如果客戶是在另一個銷售通路 (例如 Open Channel) 取得舊訂閱，客戶就必須透過該通路自行取消。

 

 



