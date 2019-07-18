---
title: 銷售 Azure Marketplace 產品的訂閱 |合作夥伴中心
ms.topic: article
ms.date: 07/12/2019
description: 您可以使用合作夥伴中心, 向獨立軟體廠商 (Isv) 發佈到 Azure Marketplace 的軟體即服務 (SaaS) 產品銷售您的客戶訂用帳戶。
author: JnHs
ms.author: jenhayes
keywords: 訂用帳戶, Marketplace, 協力廠商, ISV
ms.localizationpriority: medium
ms.openlocfilehash: 4dda776e7ebdece3a8a15c3576b64d93d3e4158c
ms.sourcegitcommit: dd961f85bc790e56c70479a5926177454dd8e855
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 07/12/2019
ms.locfileid: "67854508"
---
# <a name="sell-subscriptions-to-azure-marketplace-products"></a>銷售 Azure Marketplace 產品的訂閱

**適用於**

- 合作夥伴中心

您可以使用合作夥伴中心, 向獨立軟體廠商 (Isv) 發佈到[Azure Marketplace](https://azuremarketplace.microsoft.com/marketplace)的軟體即服務 (SaaS) 產品銷售您的客戶訂用帳戶。 這有助於區分您的業務, 並為客戶提供滿足其特定業務需求的軟體配套。 您可以管理這些 Azure Marketplace SaaS 產品的授權和訂用帳戶, 就像 Microsoft 產品一樣。

如需 Azure Marketplace 的詳細資訊, 請參閱[Azure Marketplace 常見問題](https://docs.microsoft.com/azure/marketplace/marketplace-faq-publisher-guide)。

## <a name="view-marketplace-offers-and-pricing"></a>觀看 Marketplace 供應專案和定價

若要查看所有可用的供應專案, 請從左側導覽功能表中選取 [ **Marketplace** ]。 根據預設, 您會看到所有類型和類別目錄的產品。 您可以依 [類型] 和/或 [類別] 篩選, 或使用 [搜尋] 方塊來搜尋特定關鍵字。 選取產品以查看發行者和可用 Sku 的相關資訊, 包括是否提供免費試用期間。

> [!NOTE]
> Azure Marketplace 中提供的某些產品可能不會顯示在這裡。 Isv 可以決定是否要在合作夥伴中心將其產品提供給雲端解決方案提供者 (CSP) 合作夥伴。 如果您在 Azure Marketplace 中看到您想要透過合作夥伴中心提供給客戶的產品, 請在 Azure Marketplace 中尋找發行者的連絡人資訊, 並讓他們知道您有興趣。

Azure Marketplace 產品的價格可能會經常變更。 若要取得所有 Marketplace 產品的目前定價資訊, 請選取 [ **marketplace** ] 頁面右上角的 [**匯出價格清單**]。 這會產生包含所有定價資料的試算表。 定價資訊每天都會更新, 因此您可以依您想要取得目前價格的頻率來進行檢查。

> [!TIP]
> 如果這份清單中的產品提供免費試用版, 試算表會包含該產品的兩個數據列。 一個資料列會顯示零的價格, 表示有可用的免費試用。 另一個資料列將包含試用期結束後將套用的價格和期限。

## <a name="purchase-marketplace-products-for-your-customers"></a>為您的客戶購買 Marketplace 產品

購買 Azure Marketplace SaaS 產品的訂閱, 與購買 Microsoft 產品訂閱的程式相同。 為客戶新增訂用帳戶時, 您可以選擇 [**發行者]** 篩選器中的 [**合作夥伴**], 以選擇僅查看 Isv 提供的 Marketplace 供應專案。 如需詳細資訊, 請參閱[建立新的訂用](create-a-new-subscription.md)帳戶。

> [!IMPORTANT]
> 您只能在合作夥伴中心購買軟體即服務 (SaaS) 產品訂用帳戶。 其他供應專案類型 (例如 Azure 應用程式、容器或 Vm) 則是透過 Azure 入口網站進行管理, 並根據耗用量計費。 需要現有的 Azure 訂用帳戶, 才能透過 Azure 入口網站啟用隨用隨付解決方案。

請注意, 您在**Marketplace**頁面中看到的某些供應專案可能無法供特定客戶使用。 可用性可能會受到一些因素的影響, 包括 ISV 是否支援客戶的帳單國家/地區。

> [!TIP]
> 您也可以使用[合作夥伴中心 api](https://docs.microsoft.com/partner-center/develop/)來為您的客戶建立 Azure Marketplace 訂用帳戶。 如需詳細資訊, 請參閱[建立 Azure Marketplace 產品的訂用](https://docs.microsoft.com/partner-center/develop/create-subscription-azure-marketplace-products)帳戶。

有了 Azure Marketplace 產品的訂閱, 您可以選擇[取消訂](https://docs.microsoft.com/partner-center/create-a-new-subscription#cancel-a-subscription)用帳戶 (每月訂閱24小時, 年度訂閱為14天)。 您也可以[選擇是否要自動更新訂](https://docs.microsoft.com/partner-center/create-a-new-subscription#choose-whether-to-automatically-renew-an-azure-marketplace-subscription)用帳戶。

## <a name="license-activation-for-marketplace-products"></a>Marketplace 產品的授權啟用

對於軟體即服務 (SaaS) 供應專案類型, 授權指派和啟用是透過發行產品的獨立軟體廠商 (ISV) 來管理。 若要完成此程式, 您必須造訪發行者的網站, 搭配授權碼使用個人化連結, 讓發行者能夠識別您的特定購買。 您可以在購買 SaaS 供應專案之後出現的 [確認] 頁面上找到此連結, 然後  在 [訂用帳戶] 頁面上 (在該供應專案的資料列中)。 您也可以[使用合作夥伴中心 api 來抓取此連結](https://docs.microsoft.com/partner-center/develop/get-activation-link-by-order-line-item)。

當您使用此連結流覽發行者的網站時, 您會看到布建和指派授權或完成安裝程式所需的其他資訊或動作。 所需的步驟可能會根據發行者和供應專案而有所不同。 貴使用者必須負責提交任何必要的資訊 (或將 URL 傳送給您的客戶, 以直接提供此資訊)。 一旦提供必要的資訊, 發行者就會布建並指派適當的授權。 只有在成功指派授權之後, 訂用帳戶才會開始計費。

## <a name="access-billing-info-for-marketplace-products"></a>存取 Marketplace 產品的帳單資訊

若為 Marketplace 產品, 計費期間會從日曆月份的第一天開始, 並在日曆月份的最後一天結束。 我們會讓您的發票在下個月的第8天提供。 您可以在合作夥伴中心或使用合作夥伴中心 Api 來存取這些發票。

如需詳細資訊, 請參閱[瞭解合作夥伴中心的帳單類型](https://docs.microsoft.com/partner-center/billing-different-types#billing-for-one-time-and-select-recurring-charges)。

## <a name="provide-support-for-customers-using-marketplace-products"></a>為使用 Marketplace 產品的客戶提供支援

就像 Microsoft 產品一樣, 您應該是客戶的第一個聯繫點, 以取得帳單和訂用帳戶管理的相關問題。 如需技術支援, 您必須聯繫「發行者」。 Microsoft 不提供 Marketplace 產品的支援, 但會將發行者的支援連絡人資訊提供給您。

如需詳細資訊, 請參閱[支援 Azure Marketplace 產品](https://docs.microsoft.com/partner-center/report-problems-on-behalf-of-a-customer#support-for-azure-marketplace-products)和[為您的客戶提供支援](https://docs.microsoft.com/partner-center/customer-support)。

## <a name="manage-subscriptions-using-partner-center-apis"></a>使用合作夥伴中心 Api 管理訂用帳戶

您可以使用合作夥伴中心 Api 來建立 Azure Marketplace 產品的訂用帳戶, 方法是取得市場供應專案的清單、建立和提交 Azure Marketplace 訂用帳戶的訂單, 然後抓取啟用連結。 您也可以使用合作夥伴中心 Api 來執行生命週期管理, 並管理這些訂用帳戶的發票。

如需詳細資訊, 請參閱[建立 Azure Marketplace 產品的訂用](https://docs.microsoft.com/partner-center/develop/create-subscription-azure-marketplace-products)帳戶。