---
title: Azure 方案 - 計費 | 合作夥伴中心
ms.topic: article
ms.date: 10/04/2019
description: 描述發票和對帳檔案結構
author: LauraBrenner
ms.author: labrenne
Keywords: ''
robots: ''
ms.localizationpriority: High
ms.openlocfilehash: 28e670635ca7fcff60041fcb5c93b3ddd5e4069d
ms.sourcegitcommit: cd90a59ff0ea81197b603abcb7bf462c4fb1edbe
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 10/09/2019
ms.locfileid: "72171305"
---
# <a name="new-commerce-experience-in-csp---azure-billing"></a>CSP 中的新商務體驗 - Azure 計費 

Azure 方案下的計費是藉由使用一致的單一計費日期和以行事曆月份為基礎的計費期間，簡化的計費體驗。 如需計費平台的詳細資訊，請參閱[合作夥伴新式化商務營運指南](https://assetsprod.microsoft.com/mpn/Partner-Center-Modern-Commerce-Operating-Guide.docx)。

## <a name="summary-of-billing-essentials"></a>計費基本資訊摘要

- **發票日期**：發票和對帳檔案在合作夥伴中心儀表板/API 中將於 8 日 (午夜 UTC) 提供。

- **發票計費期間**：發票計費期間會對應到行事曆月份，例如，10/1-10/31、11/1-11/30。

- **收費服務期間**：收費將會與行事曆月份一致。 例如，如果計費合作夥伴在 10/15 透過 Azure 方案新增 Azure 服務，而客戶在 10/15 開始使用 Azure 服務，則計費合作夥伴會在 11/8 收到 10/15 - 10/31 服務期間客戶使用的發票/對帳檔案。 下一個月份的發票會在 12/8 產生，其中包含 11/1- 11/31 服務期間的所有費用。

- **發票付款期限**：淨 60 天。

- **發票貨幣**：合作夥伴會繼續以客戶國家/地區的指派貨幣來計費。 例如，如果計費合作夥伴是在愛爾蘭，而客戶是在英國、挪威和德國，則計費合作夥伴將會收到 GBP、NOK 和 EUR 發票/對帳檔案。

- **合作夥伴獎勵**：從發票月份結束起算 45 天支付。

##  <a name="access-your-invoices-and-recon-files"></a>存取您的發票和對帳檔案

貴公司的全域管理員或計費管理員將會在發票已準備好可供檢視時，收到電子郵件。 

**若要存取發票和對帳檔案**

1. 登入合作夥伴中心。

2. 從 [合作夥伴中心] 功能表中，選取 [計費]  。

3. 選取您感興趣的**行事曆式**和貨幣的索引標籤。

![計費](images/azure/billing1.png)

4. 選取 [發票和對帳檔案]  。  

若要檢視歷程記錄發票和對帳檔案，請展開下方的計費歷程記錄資料列。

## <a name="read-the-invoice"></a>讀取發票

1. 發票在每個月的第 8 天之後才可取得。

2. 合作夥伴有 60 天的時間匯款。

3. 計費期間會涵蓋指定的行事曆月份，例如，10/1-10/31。

4. 費用是調整淨額 (金額是「受控服務的合作夥伴所獲得信用點數」淨額)。

5. 如需其他計費詳細資料，請參閱發票對帳檔案和每日評等使用量檔案。

![發票](images/azure/invoice1.png)

## <a name="read-the-recon-file"></a>讀取對帳檔案

1. 在對帳檔案中，每個 Azure 訂用帳戶計量最多可以有兩個計費行。

2. 如果計量符合整個行事曆月份任何類型折扣或信用點數的資格 (例如第 1 層折扣或受控服務的合作夥伴所獲得信用點數)，則對帳檔案只會包含一個計費行。 資料行 **PriceAdjusmentDescription**  會參考折扣或所獲得信用點數；有效單位價格是零售價格減去合作夥伴所獲得信用點數或任何其他折扣。

3. 如果計量不符合整個行事曆月份受控服務的合作夥伴所獲得信用點數的資格，則對帳檔案只會包含一個計費行，而有效單價會是零售價格 (這就是單價)。

4. 如果計量符合部分月份**受控服務的合作夥伴所獲得信用點數**的資格，則對帳檔案會包含兩個計費行。 一行代表計量合格的天數，而第二行則代表計量不合格的天數。 

## <a name="read-the-daily-usage-file"></a>讀取每日使用量檔案

- Azure 方案下的訂用帳戶計量會進行分級，並以每天為基礎進行累計。 

- **受控服務的合作夥伴所獲得信用點數**是以每天為基礎進行判斷和套用。

- 每個訂用帳戶計量都會有一個資料列，用於月份中每天的使用量。

- 在下列範例中：

  - 7/1 – 7/3 的計量符合**受控服務的合作夥伴所獲得信用點數**的資格 (請注意，有效單價是零售價減去合作夥伴所獲得信用點數)。

   - 7/4 – 7/7 的計量不符合**受控服務的合作夥伴所獲得信用點數**的資格 (請注意，有效單價是零售價)。

    - 7/8 – 7/31 的計量符合**受控服務的合作夥伴所獲得信用點數**的資格 (請注意，有效單價是零售價)。

![recon2](images/azure/billing2.png) 

## <a name="invoice-in-customer-currency"></a>以客戶貨幣表示的發票 

透過 Azure 方案的 Azure 服務會以美元計價，並以客戶國家/地區指派貨幣來計費。 如果計費貨幣不是美元，則使用的 FX 費率會顯示在發票的最後一頁。 FX 費率是每月決定，並套用至下列發票。 如需國家/地區貨幣的完整清單，請參閱[新的商務供應項目國家/地區可用性和客戶貨幣對照表](https://query.prod.cms.rt.microsoft.com/cms/api/am/binary/RE3Qn1V)。 

Microsoft 將使用 [Thompson Reuters](https://developers.thomsonreuters.com/content/wm-company)，判斷用來決定定價貨幣至發票貨幣轉換的 FX 費率。 FX 費率會重新整理，並在其套用當月第一天的前一天可供使用。

**範例**：服務期間 8 月 1 日 – 8 月 31 日的使用費用，會使用在 8 月 1 日發佈的 FX 費率來計費。 這些費用會出現在 9 月發票上，而 FX 費率會在發票的最後一頁上註明。 

合作夥伴租用戶使用者會繼續查看關於所有客戶和所有訂單的角色特定相關資訊，而不論計費貨幣為何。 此外，使用者能夠以所有貨幣來查看所有發票。  
 
## <a name="azure-reservations"></a>Azure Reservations 

如果透過 Azure 方案購買 [Azure Reservations](https://docs.microsoft.com/partner-center/azure-reservations)，一開始就只能在合作夥伴中心選擇一次性計費。 在 Azure 入口網站上可以使用每月計費。 合作夥伴中心將於日後提供每月計費。 

## <a name="azure-cost-management"></a>Azure 成本管理 

Azure 成本管理工具將協助組織在 Microsoft Azure 之間視覺化、管理和最佳化成本。 這項功能將會在 Azure 入口網站中提供。 合作夥伴將會擁有一個一律開啟、低延遲解決方案，並提供下列功能： 

- 更豐富的分析和預算警示 
- API 和 Power BI 連接器 
- 多客戶檢視 
- 免費管理 Azure 成本 
- 擴充角色/使用者 

如需這個功能的詳細資訊，請參閱 [Azure 成本管理](https://azure.microsoft.com/services/cost-management)，這個功能會在 2019 年 2 月提供給 Enterprise 合約使用者。 這僅適用於隨著 CSP 中這項新 Azure 商務體驗購買的 Azure 服務。 
 
## <a name="azure-spending"></a>Azure 費用 

Azure 費用工具將在合作夥伴中心，針對 CSP 中的新商務體驗提供。 套用時，這項功能可讓合作夥伴看到：  

- 客戶的預算總計 
- 現有 Azure 方案的預估費用總計 
- 每個計費期間的客戶使用量百分比 

因為透過 Azure 方案的 Azure 服務計費模式是後付款使用方式，所以若要避免帳單超出預期，合作夥伴可以套用每月預算，並追蹤使用量的百分比。 預算可以一次套用至一個客戶或多個客戶。 

![Azure 費用](images/azure/azurespend.png)

**詳細資訊**

-  合作夥伴所獲得信用點數 (PEC) 的計算方式，位於可透過合作夥伴中心儀表板取得的價目表。 
   
-  [購買 Azure 方案](purchase-azure-plan.md)

-  [CSP 中新商務體驗的價目表](azure-plan-price-list.md)
