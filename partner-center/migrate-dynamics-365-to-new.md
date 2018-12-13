---
title: 將 Dynamics 365 商務版提供移轉至較新版本 |合作夥伴中心
ms.topic: article
ms.date: 12/12/2018
description: Dynamics 365 商務版訂閱可以不再續約。
ms.assetid: 79787bef-a6e9-4c11-8c3b-f0a77485c0a4
author: labrenne
ms.author: labrenne
ms.localizationpriority: medium
ms.custom: seodec18
Keywords: Dynamics 365 offers, renew offers, new Dynamics 365 SKUs
ms.openlocfilehash: 11f0d9262856d28adb4d67871503d86f2d4945ac
ms.sourcegitcommit: 23adf424dd43ed0281473f97d535d73c59c92b01
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 12/13/2018
ms.locfileid: "8968279"
---
# <a name="migrate-dynamics-365-business-edition-offers-to-newer-versions"></a>將 Dynamics 365 商務版提供移轉至較新版本 

**適用於**

- 合作夥伴中心

Dynamics 365 商務版訂閱與有效 2019 年 1 月 1 日，客戶可以無法續約這些舊版供應項目;現有訂閱在到期時，將不會自動的續約。 訂閱的詳細資料頁面上，訂閱狀態將會從 「 自動續約於 [日期] 」 變更為 「 到期日 [日期] 」。

若要確保客戶持續的您應該將具有即將到期的訂閱至支援的選項，如下所列的那些轉換。 我們建議在年度訂閱的結束日期之前將客戶移轉至新的訂閱，以避免發生任何客戶服務中斷。

如果您使用 API （CREST 或合作夥伴中心），您可以尋找即將到期的訂閱評估的結束日期搭配自動訂閱續約 = False 屬性。 有問題的訂閱將會設定為自動續約 = False 在 2019 年 1 月 1 日。 您可以隨時將客戶移轉至新的方案。 

## <a name="the-dynamics-365-business-editions-being-retired"></a>正在淘汰的 Dynamics 365 企業版

- Dynamics 365 Finance and Operations 企業版的
- Dynamics 365 for Team Members，商務版

## <a name="dynamics-business-central---the-dynamics-365-business-edition-new-offers"></a>Dynamics 商務中央 Dynamics 365 商務版的新供應項目

使用新的中央 Dynamics 商務用供應項目，您的客戶可以連線 financials、 銷售、 服務及作業來簡化商務處理程序、 改善客戶互動，並做出更好。 Dynamics 365 商務版中央是雲端為基礎且可透過僅限雲端解決方案提供者 (CSP) 計畫的合作夥伴。
Dynamics 365 商務版客戶有資格折扣的轉換定價為新的商務中心提供 2020 年 6 月 30 日，直到。

## <a name="transition-customers-to-new-product-plans"></a>將客戶轉換到新產品方案

 將客戶從淘汰的 Sku 移轉到較新的需要此訂單中的下列步驟：

- 購買新訂閱
- 重新指派目前的使用者授權
- 取消舊訂閱

## <a name="purchase-the-new-plan-for-your-customer"></a>為您的客戶購買新的計劃

1. 選取**客戶**從左瀏覽，然後選取您想要移到新訂閱的客戶。
2. 選取 [**新增訂閱**。
3. 選取您要從型錄購買的訂閱 (在此案例中為以上其中一個選項)，輸入授權數量，然後選取 **\[提交\]**。 

您的客戶現在將會有舊訂閱和新的網站。 您的下一個步驟是要重新指派授權給客戶的使用者。

1. 從左瀏覽中選取**客戶**，然後選取您要移動的客戶。
2. 選取 **\[使用者和授權\]**。
3. 若要重新指派授權給使用者，選取使用者，然後選取 [**管理授權**。 
4. **管理授權**\] 頁面，清除 Dynamics 365 for Sales/Customer Engagement Plan 從基本 （合格提供） 授權核取方塊，然後選取客戶移動到的訂閱新服務方案。 
5. 選取 **\[提交\]**。 針對每個使用者需要新的授權，您將會執行此動作。 

一旦您已移至授權到新訂閱，您可以取消舊訂閱。 

1. 從左瀏覽中選取**客戶**，然後選取您要移動的客戶。
2. 訂閱詳細資料頁面上，將舊訂閱設定為**已暫停**，並選取 [**送出**。

舊訂閱現在暫停，而新訂閱為使用中。 暫停的訂閱將在 120 天後自動解除佈建。 您的客戶將會產生舊訂閱沒有額外成本。