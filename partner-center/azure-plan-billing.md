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
# <a name="new-commerce-experience-in-csp---azure-billing"></a><span data-ttu-id="90126-103">CSP 中的新商務體驗 - Azure 計費</span><span class="sxs-lookup"><span data-stu-id="90126-103">New commerce experience in CSP - Azure billing</span></span> 

<span data-ttu-id="90126-104">Azure 方案下的計費是藉由使用一致的單一計費日期和以行事曆月份為基礎的計費期間，簡化的計費體驗。</span><span class="sxs-lookup"><span data-stu-id="90126-104">Billing under the Azure plan is a simplified billing experience by using an aligned single billing date and calendar month-based billing period.</span></span> <span data-ttu-id="90126-105">如需計費平台的詳細資訊，請參閱[合作夥伴新式化商務營運指南](https://assetsprod.microsoft.com/mpn/Partner-Center-Modern-Commerce-Operating-Guide.docx)。</span><span class="sxs-lookup"><span data-stu-id="90126-105">For information on the billing platform, read  [Partner Center Modern Commerce Operating Guide](https://assetsprod.microsoft.com/mpn/Partner-Center-Modern-Commerce-Operating-Guide.docx).</span></span>

## <a name="summary-of-billing-essentials"></a><span data-ttu-id="90126-106">計費基本資訊摘要</span><span class="sxs-lookup"><span data-stu-id="90126-106">Summary of billing essentials</span></span>

- <span data-ttu-id="90126-107">**發票日期**：發票和對帳檔案在合作夥伴中心儀表板/API 中將於 8 日 (午夜 UTC) 提供。</span><span class="sxs-lookup"><span data-stu-id="90126-107">**Invoice date**: Invoice and reconciliation file will be available in the Partner Center dashboard/API by the 8th (midnight UTC).</span></span>

- <span data-ttu-id="90126-108">**發票計費期間**：發票計費期間會對應到行事曆月份，例如，10/1-10/31、11/1-11/30。</span><span class="sxs-lookup"><span data-stu-id="90126-108">**Invoice billing period**: The invoice billing period is aligned to the calendar month, for example,  10/1-10/31, 11/1-11/30.</span></span>

- <span data-ttu-id="90126-109">**收費服務期間**：收費將會與行事曆月份一致。</span><span class="sxs-lookup"><span data-stu-id="90126-109">**Charge service periods**: Charges will align to the calendar month.</span></span> <span data-ttu-id="90126-110">例如，如果計費合作夥伴在 10/15 透過 Azure 方案新增 Azure 服務，而客戶在 10/15 開始使用 Azure 服務，則計費合作夥伴會在 11/8 收到 10/15 - 10/31 服務期間客戶使用的發票/對帳檔案。</span><span class="sxs-lookup"><span data-stu-id="90126-110">For example, if billed partner adds Azure services through an Azure plan on 10/15 and the customer begins consumption of Azure services on 10/15, then billed partner will receive invoice/recon on 11/8 for customer consumption for the service period 10/15 - 10/31.</span></span> <span data-ttu-id="90126-111">下一個月份的發票會在 12/8 產生，其中包含 11/1- 11/31 服務期間的所有費用。</span><span class="sxs-lookup"><span data-stu-id="90126-111">The next month’s invoice that is going to be generated on 12/8 contains all the charges for the service period 11/1- 11/31.</span></span>

- <span data-ttu-id="90126-112">**發票付款期限**：淨 60 天。</span><span class="sxs-lookup"><span data-stu-id="90126-112">**Invoice payment term**: Net 60 days.</span></span>

- <span data-ttu-id="90126-113">**發票貨幣**：合作夥伴會繼續以客戶國家/地區的指派貨幣來計費。</span><span class="sxs-lookup"><span data-stu-id="90126-113">**Invoice currency**: Partners will continue to be billed in the customer's country's assigned currency.</span></span> <span data-ttu-id="90126-114">例如，如果計費合作夥伴是在愛爾蘭，而客戶是在英國、挪威和德國，則計費合作夥伴將會收到 GBP、NOK 和 EUR 發票/對帳檔案。</span><span class="sxs-lookup"><span data-stu-id="90126-114">For example, if the billed partner is in Ireland with customers in the UK, Norway, and Germany, then the billed partner will receive a GBP, NOK, and EUR invoice/recon.</span></span>

- <span data-ttu-id="90126-115">**合作夥伴獎勵**：從發票月份結束起算 45 天支付。</span><span class="sxs-lookup"><span data-stu-id="90126-115">**Partner incentives**: Paid 45 days from the end of the invoice month.</span></span>

##  <a name="access-your-invoices-and-recon-files"></a><span data-ttu-id="90126-116">存取您的發票和對帳檔案</span><span class="sxs-lookup"><span data-stu-id="90126-116">Access your invoices and recon files</span></span>

<span data-ttu-id="90126-117">貴公司的全域管理員或計費管理員將會在發票已準備好可供檢視時，收到電子郵件。</span><span class="sxs-lookup"><span data-stu-id="90126-117">The global admin or billing admin for your company will receive an email when an invoice is ready to view.</span></span> 

<span data-ttu-id="90126-118">**若要存取發票和對帳檔案**</span><span class="sxs-lookup"><span data-stu-id="90126-118">**To access the invoice and recon file**</span></span>

1. <span data-ttu-id="90126-119">登入合作夥伴中心。</span><span class="sxs-lookup"><span data-stu-id="90126-119">Sign in to Partner Center.</span></span>

2. <span data-ttu-id="90126-120">從 [合作夥伴中心] 功能表中，選取 [計費]  。</span><span class="sxs-lookup"><span data-stu-id="90126-120">From the Partner Center menu, select **Billing**.</span></span>

3. <span data-ttu-id="90126-121">選取您感興趣的**行事曆式**和貨幣的索引標籤。</span><span class="sxs-lookup"><span data-stu-id="90126-121">Select the tab for the **Calendar-based** and currency you are interested in.</span></span>

![計費](images/azure/billing1.png)

4. <span data-ttu-id="90126-123">選取 [發票和對帳檔案]  。</span><span class="sxs-lookup"><span data-stu-id="90126-123">Select **Invoice and Recon file**.</span></span>  

<span data-ttu-id="90126-124">若要檢視歷程記錄發票和對帳檔案，請展開下方的計費歷程記錄資料列。</span><span class="sxs-lookup"><span data-stu-id="90126-124">To view historical invoices and recon files expand the Billing history row below.</span></span>

## <a name="read-the-invoice"></a><span data-ttu-id="90126-125">讀取發票</span><span class="sxs-lookup"><span data-stu-id="90126-125">Read the invoice</span></span>

1. <span data-ttu-id="90126-126">發票在每個月的第 8 天之後才可取得。</span><span class="sxs-lookup"><span data-stu-id="90126-126">Invoice will be available no later than the 8th of each month.</span></span>

2. <span data-ttu-id="90126-127">合作夥伴有 60 天的時間匯款。</span><span class="sxs-lookup"><span data-stu-id="90126-127">Partners have 60 days to remit payment.</span></span>

3. <span data-ttu-id="90126-128">計費期間會涵蓋指定的行事曆月份，例如，10/1-10/31。</span><span class="sxs-lookup"><span data-stu-id="90126-128">The billing period will cover a given calendar month, for example, 10/1-10/31.</span></span>

4. <span data-ttu-id="90126-129">費用是調整淨額 (金額是「受控服務的合作夥伴所獲得信用點數」淨額)。</span><span class="sxs-lookup"><span data-stu-id="90126-129">Charges are net of adjustments (amount is net of “Partner earned credit for services managed”).</span></span>

5. <span data-ttu-id="90126-130">如需其他計費詳細資料，請參閱發票對帳檔案和每日評等使用量檔案。</span><span class="sxs-lookup"><span data-stu-id="90126-130">Review the invoice recon file and daily rated usage file for additional billing details.</span></span>

![發票](images/azure/invoice1.png)

## <a name="read-the-recon-file"></a><span data-ttu-id="90126-132">讀取對帳檔案</span><span class="sxs-lookup"><span data-stu-id="90126-132">Read the recon file</span></span>

1. <span data-ttu-id="90126-133">在對帳檔案中，每個 Azure 訂用帳戶計量最多可以有兩個計費行。</span><span class="sxs-lookup"><span data-stu-id="90126-133">Each Azure subscription meter may have up to two billing lines on the recon file.</span></span>

2. <span data-ttu-id="90126-134">如果計量符合整個行事曆月份任何類型折扣或信用點數的資格 (例如第 1 層折扣或受控服務的合作夥伴所獲得信用點數)，則對帳檔案只會包含一個計費行。</span><span class="sxs-lookup"><span data-stu-id="90126-134">If the meter qualified for any type of discount or credit (such as tier 1 discounts or the Partner earned credit for managed services) throughout the entire calendar month, then the recon file will only contain one billing line.</span></span> <span data-ttu-id="90126-135">資料行 **PriceAdjusmentDescription**  會參考折扣或所獲得信用點數；有效單位價格是零售價格減去合作夥伴所獲得信用點數或任何其他折扣。</span><span class="sxs-lookup"><span data-stu-id="90126-135">The column **PriceAdjusmentDescription** will reference the discount or earned credit; the effective unit price will be the retail price minus partner earned credit or any other discounts.</span></span>

3. <span data-ttu-id="90126-136">如果計量不符合整個行事曆月份受控服務的合作夥伴所獲得信用點數的資格，則對帳檔案只會包含一個計費行，而有效單價會是零售價格 (這就是單價)。</span><span class="sxs-lookup"><span data-stu-id="90126-136">If the meter didn’t qualify for the Partner earned credit for managed services throughout the entire calendar month, then the recon file will only contain one billing line and the effective unit price will be the retail price (which is the unit price).</span></span>

4. <span data-ttu-id="90126-137">如果計量符合部分月份**受控服務的合作夥伴所獲得信用點數**的資格，則對帳檔案會包含兩個計費行。</span><span class="sxs-lookup"><span data-stu-id="90126-137">If the meter qualified for **Partner earned credit for services managed** for a part of the month, the recon file will contain two billing lines.</span></span> <span data-ttu-id="90126-138">一行代表計量合格的天數，而第二行則代表計量不合格的天數。</span><span class="sxs-lookup"><span data-stu-id="90126-138">One line will represent the days the meter qualified and the second line will represent the days the meter did not qualify.</span></span> 

## <a name="read-the-daily-usage-file"></a><span data-ttu-id="90126-139">讀取每日使用量檔案</span><span class="sxs-lookup"><span data-stu-id="90126-139">Read the daily usage file</span></span>

- <span data-ttu-id="90126-140">Azure 方案下的訂用帳戶計量會進行分級，並以每天為基礎進行累計。</span><span class="sxs-lookup"><span data-stu-id="90126-140">Subscription meters under an Azure plan are rated, and are cumulated, on a daily basis.</span></span> 

- <span data-ttu-id="90126-141">**受控服務的合作夥伴所獲得信用點數**是以每天為基礎進行判斷和套用。</span><span class="sxs-lookup"><span data-stu-id="90126-141">**Partner earned credit for services managed** is determined and applied on a daily basis.</span></span>

- <span data-ttu-id="90126-142">每個訂用帳戶計量都會有一個資料列，用於月份中每天的使用量。</span><span class="sxs-lookup"><span data-stu-id="90126-142">Every subscription meter will have a row for every day of the month where there was consumption.</span></span>

- <span data-ttu-id="90126-143">在下列範例中：</span><span class="sxs-lookup"><span data-stu-id="90126-143">In the example below:</span></span>

  - <span data-ttu-id="90126-144">7/1 – 7/3 的計量符合**受控服務的合作夥伴所獲得信用點數**的資格 (請注意，有效單價是零售價減去合作夥伴所獲得信用點數)。</span><span class="sxs-lookup"><span data-stu-id="90126-144">Meter qualified for **Partner earned credit for services managed** from 7/1 – 7/3 (note the effective unit price is retail price less partner earned credit.</span></span>

   - <span data-ttu-id="90126-145">7/4 – 7/7 的計量不符合**受控服務的合作夥伴所獲得信用點數**的資格 (請注意，有效單價是零售價)。</span><span class="sxs-lookup"><span data-stu-id="90126-145">Meter didn’t qualify for **Partner earned credit for services managed** from 7/4 – 7/7 (note the effective unit price is retail price).</span></span>

    - <span data-ttu-id="90126-146">7/8 – 7/31 的計量符合**受控服務的合作夥伴所獲得信用點數**的資格 (請注意，有效單價是零售價)。</span><span class="sxs-lookup"><span data-stu-id="90126-146">Meter qualified for **Partner earned credit for services managed** from 7/8 – 7/31 (note the effective unit price is retail price less partner earned credit).</span></span>

![recon2](images/azure/billing2.png) 

## <a name="invoice-in-customer-currency"></a><span data-ttu-id="90126-148">以客戶貨幣表示的發票</span><span class="sxs-lookup"><span data-stu-id="90126-148">Invoice in customer currency</span></span> 

<span data-ttu-id="90126-149">透過 Azure 方案的 Azure 服務會以美元計價，並以客戶國家/地區指派貨幣來計費。</span><span class="sxs-lookup"><span data-stu-id="90126-149">Azure services through an Azure plan will be priced in USD and billed in the customer country assigned currency.</span></span> <span data-ttu-id="90126-150">如果計費貨幣不是美元，則使用的 FX 費率會顯示在發票的最後一頁。</span><span class="sxs-lookup"><span data-stu-id="90126-150">If the billing currency is non-USD, then the FX rate used will be shown on the last page of the invoice.</span></span> <span data-ttu-id="90126-151">FX 費率是每月決定，並套用至下列發票。</span><span class="sxs-lookup"><span data-stu-id="90126-151">FX rates are determined monthly and applied to the following invoice.</span></span> <span data-ttu-id="90126-152">如需國家/地區貨幣的完整清單，請參閱[新的商務供應項目國家/地區可用性和客戶貨幣對照表](https://query.prod.cms.rt.microsoft.com/cms/api/am/binary/RE3Qn1V)。</span><span class="sxs-lookup"><span data-stu-id="90126-152">For a full list of country currencies, please view the [New commerce offers country availability and customer currency matrix](https://query.prod.cms.rt.microsoft.com/cms/api/am/binary/RE3Qn1V).</span></span> 

<span data-ttu-id="90126-153">Microsoft 將使用 [Thompson Reuters](https://developers.thomsonreuters.com/content/wm-company)，判斷用來決定定價貨幣至發票貨幣轉換的 FX 費率。</span><span class="sxs-lookup"><span data-stu-id="90126-153">Microsoft will use [Thompson Reuters](https://developers.thomsonreuters.com/content/wm-company) to determine the FX rate used to determine pricing currency to invoice currency conversion.</span></span> <span data-ttu-id="90126-154">FX 費率會重新整理，並在其套用當月第一天的前一天可供使用。</span><span class="sxs-lookup"><span data-stu-id="90126-154">The FX rate will be refreshed and available on the day before the first of the month for which they apply.</span></span>

<span data-ttu-id="90126-155">**範例**：服務期間 8 月 1 日 – 8 月 31 日的使用費用，會使用在 8 月 1 日發佈的 FX 費率來計費。</span><span class="sxs-lookup"><span data-stu-id="90126-155">**Example**:  Usage charges for the service period August 1 – August 31 will be billed using the FX rate published on August 1.</span></span> <span data-ttu-id="90126-156">這些費用會出現在 9 月發票上，而 FX 費率會在發票的最後一頁上註明。</span><span class="sxs-lookup"><span data-stu-id="90126-156">These charges will appear on the September invoice and the FX rate will be noted on the last page of the invoice.</span></span> 

<span data-ttu-id="90126-157">合作夥伴租用戶使用者會繼續查看關於所有客戶和所有訂單的角色特定相關資訊，而不論計費貨幣為何。</span><span class="sxs-lookup"><span data-stu-id="90126-157">Partner tenant users will continue to see role-specific related information regarding all customers and all orders, regardless of the billing currency.</span></span> <span data-ttu-id="90126-158">此外，使用者能夠以所有貨幣來查看所有發票。</span><span class="sxs-lookup"><span data-stu-id="90126-158">Additionally, the user will be able to see all the invoices in all currencies.</span></span>  
 
## <a name="azure-reservations"></a><span data-ttu-id="90126-159">Azure Reservations</span><span class="sxs-lookup"><span data-stu-id="90126-159">Azure reservations</span></span> 

<span data-ttu-id="90126-160">如果透過 Azure 方案購買 [Azure Reservations](https://docs.microsoft.com/partner-center/azure-reservations)，一開始就只能在合作夥伴中心選擇一次性計費。</span><span class="sxs-lookup"><span data-stu-id="90126-160">If purchasing [Azure reservations](https://docs.microsoft.com/partner-center/azure-reservations) through an Azure plan, initially,  it will only be possible to choose one-time billing in Partner Center.</span></span> <span data-ttu-id="90126-161">在 Azure 入口網站上可以使用每月計費。</span><span class="sxs-lookup"><span data-stu-id="90126-161">Monthly billing is available on the Azure portal.</span></span> <span data-ttu-id="90126-162">合作夥伴中心將於日後提供每月計費。</span><span class="sxs-lookup"><span data-stu-id="90126-162">Monthly billing will be available in Partner Center at a later date.</span></span> 

## <a name="azure-cost-management"></a><span data-ttu-id="90126-163">Azure 成本管理</span><span class="sxs-lookup"><span data-stu-id="90126-163">Azure cost management</span></span> 

<span data-ttu-id="90126-164">Azure 成本管理工具將協助組織在 Microsoft Azure 之間視覺化、管理和最佳化成本。</span><span class="sxs-lookup"><span data-stu-id="90126-164">Azure Cost Management tools will help organizations visualize, manage and optimize costs across Microsoft Azure.</span></span> <span data-ttu-id="90126-165">這項功能將會在 Azure 入口網站中提供。</span><span class="sxs-lookup"><span data-stu-id="90126-165">This feature will be available in the Azure portal.</span></span> <span data-ttu-id="90126-166">合作夥伴將會擁有一個一律開啟、低延遲解決方案，並提供下列功能：</span><span class="sxs-lookup"><span data-stu-id="90126-166">Partners will have an always-on, low-latency solution with the following features available:</span></span> 

- <span data-ttu-id="90126-167">更豐富的分析和預算警示</span><span class="sxs-lookup"><span data-stu-id="90126-167">Richer analysis and budget alerting</span></span> 
- <span data-ttu-id="90126-168">API 和 Power BI 連接器</span><span class="sxs-lookup"><span data-stu-id="90126-168">APIs and Power BI connectors</span></span> 
- <span data-ttu-id="90126-169">多客戶檢視</span><span class="sxs-lookup"><span data-stu-id="90126-169">Multi-customer view</span></span> 
- <span data-ttu-id="90126-170">免費管理 Azure 成本</span><span class="sxs-lookup"><span data-stu-id="90126-170">Free to manage Azure costs</span></span> 
- <span data-ttu-id="90126-171">擴充角色/使用者</span><span class="sxs-lookup"><span data-stu-id="90126-171">Expansion of roles/users</span></span> 

<span data-ttu-id="90126-172">如需這個功能的詳細資訊，請參閱 [Azure 成本管理](https://azure.microsoft.com/services/cost-management)，這個功能會在 2019 年 2 月提供給 Enterprise 合約使用者。</span><span class="sxs-lookup"><span data-stu-id="90126-172">See [Azure cost management](https://azure.microsoft.com/services/cost-management) for more information on this feature, which became available for enterprise agreements in February, 2019.</span></span> <span data-ttu-id="90126-173">這僅適用於隨著 CSP 中這項新 Azure 商務體驗購買的 Azure 服務。</span><span class="sxs-lookup"><span data-stu-id="90126-173">This is available only with Azure services purchased as part of this new Azure commerce experience in CSP.</span></span> 
 
## <a name="azure-spending"></a><span data-ttu-id="90126-174">Azure 費用</span><span class="sxs-lookup"><span data-stu-id="90126-174">Azure spending</span></span> 

<span data-ttu-id="90126-175">Azure 費用工具將在合作夥伴中心，針對 CSP 中的新商務體驗提供。</span><span class="sxs-lookup"><span data-stu-id="90126-175">An Azure spending tool will be available in Partner Center for the new commerce experience in CSP.</span></span> <span data-ttu-id="90126-176">套用時，這項功能可讓合作夥伴看到：</span><span class="sxs-lookup"><span data-stu-id="90126-176">When applied, this capability will enable partners to see:</span></span>  

- <span data-ttu-id="90126-177">客戶的預算總計</span><span class="sxs-lookup"><span data-stu-id="90126-177">Total budget on a customer</span></span> 
- <span data-ttu-id="90126-178">現有 Azure 方案的預估費用總計</span><span class="sxs-lookup"><span data-stu-id="90126-178">Total estimated spending on an existing Azure plan</span></span> 
- <span data-ttu-id="90126-179">每個計費期間的客戶使用量百分比</span><span class="sxs-lookup"><span data-stu-id="90126-179">Percentage of customers usage in each billing period</span></span> 

<span data-ttu-id="90126-180">因為透過 Azure 方案的 Azure 服務計費模式是後付款使用方式，所以若要避免帳單超出預期，合作夥伴可以套用每月預算，並追蹤使用量的百分比。</span><span class="sxs-lookup"><span data-stu-id="90126-180">Because the billing model for Azure services through an Azure plan is post-pay consumption, to avoid a bigger bill than anticipated,partners can apply a monthly budget and track the percentage of usage.</span></span> <span data-ttu-id="90126-181">預算可以一次套用至一個客戶或多個客戶。</span><span class="sxs-lookup"><span data-stu-id="90126-181">A budget can be applied to one customer or multiple customers at one time.</span></span> 

![Azure 費用](images/azure/azurespend.png)

<span data-ttu-id="90126-183">**詳細資訊**</span><span class="sxs-lookup"><span data-stu-id="90126-183">**For more information**</span></span>

-  <span data-ttu-id="90126-184">合作夥伴所獲得信用點數 (PEC) 的計算方式，位於可透過合作夥伴中心儀表板取得的價目表。</span><span class="sxs-lookup"><span data-stu-id="90126-184">How the partner earned credit (PEC) is calculated is located on the price list available through your Partner Center dashboard.</span></span> 
   
-  [<span data-ttu-id="90126-185">購買 Azure 方案</span><span class="sxs-lookup"><span data-stu-id="90126-185">Purchase the Azure plan</span></span>](purchase-azure-plan.md)

-  [<span data-ttu-id="90126-186">CSP 中新商務體驗的價目表</span><span class="sxs-lookup"><span data-stu-id="90126-186">Price list for the new commerce experience in CSP </span></span>](azure-plan-price-list.md)
