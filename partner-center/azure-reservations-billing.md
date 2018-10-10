---
title: Azure Reservations 帳單 | 合作夥伴中心
Description: Information about billing for Azure reservations.
author: v-petand
keywords: Azure RI, azure 保留的執行個體, 保留區, vm, 管理, 帳單, 購買
robots: noindex, nofollow
ms.localizationpriority: medium
ms.openlocfilehash: 846f2863e9c4dc9967b8c337bcab40f153b99eb6
ms.sourcegitcommit: 123a7f53d633c27eb5f982926d856de47afb1042
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 10/09/2018
ms.locfileid: "4489434"
---
# <a name="microsoft-azure-reserved-vm-instances-billing"></a>Microsoft Azure 保留的 VM 執行個體帳單

**適用對象：**

-  合作夥伴中心
-  Microsoft Azure 入口網站
-  雲端解決方案提供者中的合作夥伴

雲端解決方案提供者 (CSP) 中的合作夥伴可提供 Microsoft Azure 虛擬機器上的保留執行個體給客戶。 客戶可事先保留虛擬機器 – 使用一年或三年期限 – 並體驗 Azure 使用率的大幅度節省。   

您的客戶需事先支付 Azure 保留的 VM 執行個體。 當您代表客戶購買 Azure 保留的 VM 執行個體時，您會收到這些一次性費用的發票和對帳檔案。 

>[!IMPORTANT]
>如果您在所用貨幣與您不同的市場中為客戶購買 Azure 保留的 VM 執行個體，預設帳單貨幣會以客戶的市場為準，而不是您的所在位置。 如果您在多個市場擁有客戶，您會針對需要付費客戶的每種貨幣收到不同的發票和對帳檔案，讓您可用適當的貨幣向客戶開立發票。 

若要存取一次收費發票和對帳檔案中，選取**帳單**從合作夥伴中心，然後選取**一次**。 

如需雲端解決方案提供者計畫中的帳單一般資訊，請參閱[帳單基本知識](billing-basics.md)。

## <a name="azure-reserved-vm-instance-invoice-file-definitions"></a>Azure 保留的 VM 執行個體發票檔案定義

**一般帳單資訊**

|**欄位** |**定義**|
|:----------------|:-----------------------------|
|美國 FEIN |您的聯邦稅務識別碼。 |
|帳單地址 |用於報稅的合法公司地址。 若要變更此地址，請移至 \[帳戶設定\] > \[合作夥伴帳單設定檔\]。 |
|費用 |目前所有費用。 |
|點數 |自首次購買以來退款活動的點數。 |
|折扣 |適用於 Azure Reservations 或客戶訂單中其他項目的折扣。 |
|稅金 |在發票第 2 頁開始位置的詳細資料區段中加總的目前費用的總稅金。 |
|目前總費用 |付款期限到期時，以您使用的帳單貨幣計算的帳單期間應付金額。 |
|付款指示 |描述何時及如何支付發票 (根據您的地區)。 付款時，一律包含您的發票號碼。 |
|發票號碼 |發票的號碼。 |
|發票日期 |產生發票的日期。 |
|付款期限 |對於一次性購買，這一律是 60 天。 |
|付款截止日期 |必須在此日期前收到您的付款。 |


**一次性費用的分項清單**

|**欄位** |**定義**|
|:----------------|:-----------------------------|
|日期 |購買日期。 |
|描述 |產品名稱。 |
|數量 |購買的產品 (例如保留區) 數目。 |
|單價 |產品 (例如保留區) 的單價。 |
|折扣 |適用的任何折扣。 |
|稅前金額 |稅前購買小計。 |
|營業稅 |稅額。 |
|總計 |至今應付總額。 |


## <a name="azure-reserved-vm-instance-reconciliation-file-descriptions"></a>Azure 保留的 VM 執行個體對帳檔案描述

|**欄位** |**定義**|
|:----------------|:-----------------------------|
|PartnerId |合作夥伴識別碼 (GUID 格式)。 |
|CustomerId |用來識別客戶的唯一 Microsoft ID（GUID 格式）。 |
|CustomerName |合作夥伴中心中回報的客戶組織名稱。 這在使用您的系統資訊對帳發票時非常重要。 |
|CustomerDomainName |客戶的網域名稱。 |
|CustomerCountry |客戶所在的國家/地區。 |
|InvoiceNumber |交易的指定位置顯示的發票號碼。 |
|MpnId |雲端解決方案提供者合作夥伴的 MPN 識別碼 (直接或間接)。 |
|經銷商 MPN 識別碼 |只會出現在間接模型合作夥伴的對帳檔案上。 保留區記錄中的經銷商 MPN 識別碼。 這會對應到合作夥伴中心中針對特定保留區列出的經銷商識別碼。 如果雲端解決方案提供者合作夥伴直接向客戶銷售保留區，他們的 MPN 識別碼將會以 MPN 識別碼和經銷商 MPN 識別碼的形式列出兩次。 如果雲端解決方案提供者合作夥伴具有沒有 MPN 識別碼的經銷商，這個值將會改成設為合作夥伴的 MPN 識別碼。 如果雲端解決方案提供者合作夥伴移除經銷商識別碼，這個值將會設為 -1。 |
|OrderId |訂單在 Microsoft 帳單平台中的唯一識別碼。 可在連絡支援時方便識別 Azure Reservations，但不是用於對帳。 |
|OrderDate |下訂單的日期。 |
|ProductId |產品的識別碼。 |
|SkuId  |特定 SKU 的識別碼。 |
|AvailabilityId |特定可用性的識別碼。 「可用性」是指特定 SKU 是否可供特定的國家/地區、貨幣、行業區段等等購買。 |
|SkuName  |特定 SKU 的標題。 |
|ProductName |產品的名稱。 |
|ChargeType |費用或調整的類型。 |
|UnitPrice |訂購的每件產品價格。 |
|Quantity |訂購的產品數目。 |
|Subtotal |稅前總計。 如果有折扣，可檢查小計是否和預期的總金額相符。 |
|TaxTotal |所有適用稅額的總計。 |
|Total |此次購買的總金額。 |
|Currency |貨幣類型。 每一帳單實體都只有一種貨幣。 檢查是否與您的第一張發票相符，然後在進行任何重大帳單平台更新之後檢查。 |
|DiscountDetails |任何相關折扣的詳細清單。 |


## <a name="manage-your-billing"></a>管理您的帳單

### <a name="view-your-current-billing-status-invoices-and-recon-files"></a>檢視您目前的帳單狀態、發票，以及對帳檔案

1.  在合作夥伴中心，選取**帳單**，然後**一次**，檢視您的帳單狀態。 
2.  選取發票或對帳檔案來檢視更多詳細資訊。 

### <a name="view-a-customers-order-history"></a>檢視客戶的訂購記錄

1.  從合作夥伴中心功能表中選取**客戶**。
2.  在 **\[客戶\]** 頁面上，尋找您要檢視其訂購記錄的客戶，然後選取向下箭號來展開客戶的記錄。 
3.  選取 **\[檢視訂單\]** 來顯示訂購記錄。

### <a name="create-a-credit-or-void-note"></a>建立信貸或無效票據

有些時候，您可能需要作廢發票，再核發新發票。 例如，客戶可能變更其企業名稱，然後收到舊名稱的發票。 

若要作廢發票再核發新的，請從帳單頁面的調整下方下載表格。

## <a name="azure-reservations-resources"></a>Azure Reservations 資源
|**如需以下相關資訊**   |**請閱讀本文**    |
|:-----------------------------|:-----------------|
|雲端解決方案提供者中的 Azure Reservations 概觀  | [銷售 Microsoft Azure 保留的 VM 執行個體](azure-reservations.md)
|為您在合作夥伴中心的客戶購買 Azure reservations   |[購買 Azure Reservations](azure-reservations-buying.md)
| 在合作夥伴中心管理 Azure reservations | [在合作夥伴中心管理 Azure reservations](azure-reservations-manage.md)
|在 Azure 入口網站中購買 Azure Reservations | Azure 說明中的[預付具有 Azure 保留的 VM 執行個體的虛擬機器](https://docs.microsoft.com/azure/virtual-machines/windows/prepay-reserved-vm-instances) |
|在 Azure 入口網站中管理 Azure Reservations   |Azure 說明中的[管理保留的 VM 執行個體](https://docs.microsoft.com/azure/billing/billing-manage-reserved-vm-instance)  |
|使用合作夥伴中心 API 購買 Azure Reservations | 合作夥伴中心開發人員文件中的[購買 Azure 保留的 VM 執行個體](https://docs.microsoft.com/partner-center/develop/purchase-azure-reservations)

 
