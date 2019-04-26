---
title: 從 Basic （完整的供應項目） 的 Dynamics 365 和客戶參與計劃移轉至較新版本 |合作夥伴中心
ms.topic: article
ms.date: 12/12/2018
description: Dynamics 365 for Sales / 客戶參與計劃從 Basic （限定提供） 的訂用帳戶可以不會再更新。
ms.assetid: 79787bef-a6e9-4c11-8c3b-f0a77485c0a4
author: LauraBrenner
ms.author: labrenne
ms.localizationpriority: medium
ms.custom: seodec18
Keywords: Dynamics 365 供應項目，更新供應項目，新的 Dynamics 365 Sku
ms.openlocfilehash: e5128abe71cfab4e2cdabb0cafcd5fd7df56b116
ms.sourcegitcommit: b1ab80345b4e4af649fb8cc51d96d798e0791ade
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 04/23/2019
ms.locfileid: "62134398"
---
# <a name="migrate-dynamics-365-and-customer-engagement-plan-from-basic-qualified-offers-to-newer-versions"></a>將 Dynamics 365 和 Customer Engagement Plan 從基本 （合格的供應項目） 移轉至較新版本

**適用於**

-  合作夥伴中心

有效 2019 年 1 月 1 日，客戶與銷售的 Dynamics 365 Customer Engagement 計劃從 Basic （限定提供） 的訂用帳戶可以不再更新這些舊版的供應項目; /過期時，現有的訂用帳戶將不會自動續訂。 在訂用帳戶的詳細資料頁面上，訂閱狀態會變更為 「 [date] 到期 」 從 「 自動更新於 [date]"。 


若要確保持續性的客戶，您應該先即將過期的訂用帳戶支援的選項下, 面所列的轉換。 我們建議在年度訂閱的結束日期之前將客戶移至新的訂閱，以避免提供客戶的服務中斷。

如果您使用 API （CREST 或合作夥伴中心），您可以找到 即將過期的訂用帳戶，藉由評估結束日期的訂用帳戶，以及自動續訂 = False 的屬性。 有問題的訂用帳戶將會設定為自動續約於 2019 年 1 月 1 日 = False。 您可以隨時將客戶移轉至新的方案。 

### <a name="the-dynamics-365-offers-being-retired"></a>Dynamics 365 提供即將淘汰

- Dynamics 365 for Sales 企業版 CRMOL Basic （完整的供應項目）
- Dynamics 365 for Sales 企業版 CRMOL Basic 教職員版 （完整的供應項目）
- Dynamics 365 for Sales 企業版 CRMOL Basic 學生版 （完整的供應項目）
- Dynamics 365 for Sales 企業版 （政府定價） CRMOL Basic （完整的供應項目）
- Dynamics 365 for Sales 企業版來自 SA 的 CRM Basic （完整的供應項目）
- Dynamics 365 for Sales 企業版來自 SA 的 CRM Basic 教職員版 （完整的供應項目）
- Dynamics 365 for Sales 企業版來自 CRM basic （完整的供應項目） 適用於學生的 SA
- Dynamics 365 for Sales 企業版 （政府定價） 來自 SA 的 CRM Basic （完整的供應項目）
- Dynamics 365 for Sales 企業版的附加元件 CRM basic （完整的供應項目）
- Dynamics 365 for Sales 企業版的附加元件 CRM basic 教職員版 （完整的供應項目）
- Dynamics 365 for Sales 企業版的附加元件適用於學生的 CRM basic （完整的供應項目）
- Dynamics 365 for Sales 企業版 （政府定價） 附加元件 CRM basic （完整的供應項目）
- Dynamics 365 Customer Engagement 計劃 Enterprise Edition CRMOL Basic （完整的供應項目）
- Dynamics 365 Customer Engagement 計劃 Enterprise Edition （政府定價） CRMOL Basic （完整的供應項目）
- Dynamics 365 Customer Engagement 計劃企業版本 CRMOL Basic （完整的供應項目） 適用於學生
- Dynamics 365 Customer Engagement 計劃 Enterprise Edition CRMOL Basic （完整的供應項目） 教職員版
- Dynamics 365 Customer Engagement Plan 企業版來自 SA 的 CRM Basic （完整的供應項目）
- Dynamics 365 Customer Engagement Plan 企業版 （政府定價） 來自 SA 的 CRM Basic （完整的供應項目）
- Dynamics 365 Customer Engagement Plan 企業版來自 CRM basic （完整的供應項目） 適用於學生的 SA
- Dynamics 365 Customer Engagement Plan 企業版來自 SA 的 CRM Basic 教職員版 （完整的供應項目）
- Dynamics 365 Customer Engagement 計劃 Enterprise Edition 的附加元件 CRM Basic （完整的供應項目）
- Dynamics 365 Customer Engagement 計劃 Enterprise 版 （政府定價） 的附加元件 CRM Basic （完整的供應項目）
- Dynamics 365 Customer Engagement 計劃 Enterprise Edition 的附加元件適用於學生的 CRM Basic （完整的供應項目）
- Dynamics 365 Customer Engagement 計劃 Enterprise Edition 的附加元件 CRM Basic 教職員版 （完整的供應項目）



## <a name="dynamics-365-for-sales-customer-engagement-plan-from-basic-qualified-offers-replacement-plans"></a>Dynamics 365 for Sales / Basic （限定提供） 取代從計劃的客戶參與的計劃

**已停用的供應項目**   

- Dynamics 365 銷售從 CRM Basic 或 CRMOL Basic （完整的供應項目）
- Dynamics 365 客戶業務開發計劃從 CRM Basic 或 CRMOL Basic （完整的供應項目）

**取代選項**
- Dynamics 365 for Sales 專業 （新）
- Dynamics 365 for Sales 專業 （新）
- Dynamics 365 for Customer Service
- Dynamics 365 Customer Engagement 方案或
- Dynamics 365 小組成員



## <a name="transition-customers-to-new-product-plans"></a>將客戶轉換到新產品方案

將客戶從已停用的 Sku 移到較新的需要下列步驟順序如下：

- 購買新訂閱
- 重新指派目前的使用者授權
- 取消舊訂閱

## <a name="purchase-the-new-plan-for-your-customer"></a>為您的客戶購買新的計劃

1. 選取 **客戶**從左側的導覽中，然後選取您想要移動到新的訂用帳戶的客戶。
2. 選取 **新增訂用帳戶**。
3. 選取您要從型錄購買的訂閱 (在此案例中為以上其中一個選項)，輸入授權數量，然後選取 **\[提交\]**。 

舊訂用帳戶和新的現在會有您的客戶。 下一步是要重新指派授權給客戶的使用者。

1. 選取 **客戶**從左側的導覽中，然後選取客戶是移動。
2. 選取 \[使用者和授權\]。
3. 若要重新指派授權給使用者時，選取的使用者，然後按**管理授權**。 
4. 在 **管理授權** 頁面上，清除 Dynamics 365 for Sales / 客戶業務開發計劃 （限定優惠） 的 basic 授權核取方塊，然後選取 訂用帳戶客戶移至新的服務方案。 
5. 選取 **送出**。 您將會針對每個需要新授權的使用者來這麼做。 

授權移動到新的訂用帳戶之後，您可以取消舊訂用帳戶。 

1. 選取 **客戶**從左側的導覽中，然後選取客戶是移動。
2. 在訂用帳戶詳細資料頁面上，設定為舊的訂用帳戶**Suspended** ，然後選取**送出**。

舊訂用帳戶現在已暫停，並且新的訂用帳戶作用中。 暫停的訂閱將在 120 天後自動解除佈建。 您的客戶將會產生任何額外的費用，舊的訂用帳戶。
 

 



