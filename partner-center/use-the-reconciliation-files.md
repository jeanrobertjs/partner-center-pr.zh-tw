---
title: 使用對帳檔案 | 合作夥伴中心
ms.topic: article
ms.date: 10/29/2018
description: 在計費週期中的每個收費詳細的明細項目檢視，請從合作夥伴中心下載的對帳檔案。
ms.assetid: FA6A6FCB-2597-44E7-93F8-8D1DD35D52EA
author: LauraBrenner
ms.author: labrenne
ms.localizationpriority: medium
ms.openlocfilehash: 9997b01c76dacb736baa33f458def0b820753f1d
ms.sourcegitcommit: 9a2bda49446030e60251c9c913259472ff2eed9a
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 03/08/2019
ms.locfileid: "57682506"
---
# <a name="use-the-reconciliation-files"></a><span data-ttu-id="27213-103">使用對帳檔案</span><span class="sxs-lookup"><span data-stu-id="27213-103">Use the reconciliation files</span></span>

<span data-ttu-id="27213-104">**適用於**</span><span class="sxs-lookup"><span data-stu-id="27213-104">**Applies to**</span></span>

-  <span data-ttu-id="27213-105">合作夥伴中心</span><span class="sxs-lookup"><span data-stu-id="27213-105">Partner Center</span></span>
-  <span data-ttu-id="27213-106">Microsoft Cloud for US Government 適用的合作夥伴中心</span><span class="sxs-lookup"><span data-stu-id="27213-106">Partner Center for Microsoft Cloud for US Government</span></span>


<span data-ttu-id="27213-107">在計費週期中的每個收費詳細的明細項目檢視，請從合作夥伴中心下載的對帳檔案。</span><span class="sxs-lookup"><span data-stu-id="27213-107">For a detailed line-item view of each charge in a billing cycle, download the reconciliation files from Partner Center.</span></span> <span data-ttu-id="27213-108">詳細資料包括每個客戶的訂閱費用，以及詳細事件 (例如，期中增加訂閱基座)。</span><span class="sxs-lookup"><span data-stu-id="27213-108">The details include charges for each customer's subscriptions, and detailed events (such as a mid-term addition of seats to a subscription).</span></span>

## <a href="" id="itemizebypartner"></a><span data-ttu-id="27213-109">由合作夥伴條列</span><span class="sxs-lookup"><span data-stu-id="27213-109">Itemize by partner</span></span>


<span data-ttu-id="27213-110">間接模型合作夥伴可以在授權型及用量型對帳檔案中使用這些額外欄位，以便依經銷商詳細列舉。</span><span class="sxs-lookup"><span data-stu-id="27213-110">Partners in the indirect model can use these additional fields in both license-based and usage-based reconciliation files to itemize by reseller.</span></span>

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th><span data-ttu-id="27213-111">MPN 識別碼</span><span class="sxs-lookup"><span data-stu-id="27213-111">MPN ID</span></span></th>
<th><span data-ttu-id="27213-112">描述</span><span class="sxs-lookup"><span data-stu-id="27213-112">Description</span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="27213-113">MPN 識別碼</span><span class="sxs-lookup"><span data-stu-id="27213-113">MPN ID</span></span></td>
<td><p><span data-ttu-id="27213-114">CSP 合作夥伴 (直接或間接) 的 Microsoft 合作夥伴網路 (MPN) 識別碼。</span><span class="sxs-lookup"><span data-stu-id="27213-114">The Microsoft Partner Network (MPN) ID of the CSP partner (direct or indirect).</span></span></p></td>
</tr>
<tr class="even">
<td><span data-ttu-id="27213-115">經銷商 MPN 識別碼</span><span class="sxs-lookup"><span data-stu-id="27213-115">Reseller MPN ID</span></span></td>
<td><p><span data-ttu-id="27213-116">只會出現在間接模型合作夥伴的對帳檔案上。</span><span class="sxs-lookup"><span data-stu-id="27213-116">Only appears on reconciliation files for partners in the indirect model.</span></span></p>
<p><span data-ttu-id="27213-117">訂閱記錄中的經銷商 MPN 識別碼。</span><span class="sxs-lookup"><span data-stu-id="27213-117">The MPN ID of the reseller of record for the subscription.</span></span> <span data-ttu-id="27213-118">這會對應到合作夥伴中心中針對特定訂閱列出的經銷商識別碼。</span><span class="sxs-lookup"><span data-stu-id="27213-118">This corresponds to the reseller ID listed for the specific subscription in Partner Center.</span></span></p>
<p><span data-ttu-id="27213-119">干支檢視或更新的轉銷商，從合作夥伴中心 功能表中，選取<strong>客戶</strong>，然後從清單中選擇客戶。</span><span class="sxs-lookup"><span data-stu-id="27213-119">eTo view or update the reseller, from the Partner Center menu, select <strong>Customers</strong>, then choose the customer from the list.</span></span> <span data-ttu-id="27213-120">在客戶功能表中，選取 \[訂閱\]，從清單中選擇訂閱。</span><span class="sxs-lookup"><span data-stu-id="27213-120">In the customer menu, select <strong>Subscriptions</strong>, choose the subscription from the list.</span></span> <span data-ttu-id="27213-121">選取 \[更新\] 以變更 \[經銷商 (MPN 識別碼)\]。</span><span class="sxs-lookup"><span data-stu-id="27213-121">Select <strong>update</strong> to change the <strong>Reseller (MPN ID)</strong>.</span></span></p>
<p><span data-ttu-id="27213-122">如果雲端解決方案提供者合作夥伴直接向客戶銷售訂閱，他們的 MPN 識別碼將會以 MPN 識別碼和經銷商 MPN 識別碼的形式列出兩次。</span><span class="sxs-lookup"><span data-stu-id="27213-122">If a CSP partner sold the subscription directly to the customer, their MPN ID is listed twice, as both the MPN ID and the Reseller MPN ID.</span></span></p>
<p><span data-ttu-id="27213-123">如果雲端解決方案提供者合作夥伴具有沒有 MPN 識別碼的經銷商，這個值將會改成設為合作夥伴的 MPN 識別碼。</span><span class="sxs-lookup"><span data-stu-id="27213-123">If a CSP partner has a reseller with no MPN ID, this value is set to the partner’s MPN ID instead.</span></span></p>
<p><span data-ttu-id="27213-124">如果雲端解決方案提供者合作夥伴移除經銷商識別碼，這個值將會設為 -1。</span><span class="sxs-lookup"><span data-stu-id="27213-124">If the CSP partner removes a reseller ID, this value will be set to -1.</span></span></p></td>
</tr>
</tbody>
</table>

 

## <a href="" id="licensebasedfiles"></a> <span data-ttu-id="27213-125">以授權為基礎的檔案欄位</span><span class="sxs-lookup"><span data-stu-id="27213-125">License-based file fields</span></span>


<span data-ttu-id="27213-126">若要針對您對客戶訂單的費用來對帳，請比較對帳檔案中的 Syndication\_Partner\_Subscription\_Number 與合作夥伴中心的訂閱識別碼。</span><span class="sxs-lookup"><span data-stu-id="27213-126">To reconcile your charges against your customer's orders, compare the Syndication\_Partner\_Subscription\_Number from the reconciliation file against the Subscription ID from Partner Center.</span></span>

<table>
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<tbody>
<tr class="odd">
<td><span data-ttu-id="27213-127"><strong>資料行</strong></span><span class="sxs-lookup"><span data-stu-id="27213-127"><strong>Column</strong></span></span></td>
<td><span data-ttu-id="27213-128"><strong>描述</strong></span><span class="sxs-lookup"><span data-stu-id="27213-128"><strong>Description</strong></span></span></td>
<td><span data-ttu-id="27213-129"><strong>範例值</strong></span><span class="sxs-lookup"><span data-stu-id="27213-129"><strong>Sample Value</strong></span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="27213-130">PartnerId</span><span class="sxs-lookup"><span data-stu-id="27213-130">PartnerId</span></span></td>
<td><p><span data-ttu-id="27213-131">特定帳單實體的唯一識別碼 (GUID 格式)。</span><span class="sxs-lookup"><span data-stu-id="27213-131">Unique identifier for a specific billing entity, in GUID format.</span></span> <span data-ttu-id="27213-132">對帳時不需要，但可能是很有用的資訊。</span><span class="sxs-lookup"><span data-stu-id="27213-132">Not required for reconciliation, however may be useful information.</span></span> <span data-ttu-id="27213-133">在所有資料列中都是如此。</span><span class="sxs-lookup"><span data-stu-id="27213-133">Same in all rows.</span></span></p></td>
<td><span data-ttu-id="27213-134">8ddd03642-test-test-test-46b58d356b4e</span><span class="sxs-lookup"><span data-stu-id="27213-134">8ddd03642-test-test-test-46b58d356b4e</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="27213-135">CustomerID</span><span class="sxs-lookup"><span data-stu-id="27213-135">CustomerID</span></span></td>
<td><p><span data-ttu-id="27213-136">用來識別客戶的唯一 Microsoft ID（GUID 格式）。</span><span class="sxs-lookup"><span data-stu-id="27213-136">Unique Microsoft ID, in GUID format, used to identify the customer.</span></span></p></td>
<td><span data-ttu-id="27213-137">12ABCD34-001A-BCD2-987C-3210ABCD5678</span><span class="sxs-lookup"><span data-stu-id="27213-137">12ABCD34-001A-BCD2-987C-3210ABCD5678</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="27213-138">OrderID</span><span class="sxs-lookup"><span data-stu-id="27213-138">OrderID</span></span></td>
<td><p><span data-ttu-id="27213-139">訂單在 Microsoft 帳單平台中的唯一識別碼。</span><span class="sxs-lookup"><span data-stu-id="27213-139">Unique identifier for an order in the Microsoft billing platform.</span></span> <span data-ttu-id="27213-140">可在連絡支援時方便識別訂單，但不是用於對帳。</span><span class="sxs-lookup"><span data-stu-id="27213-140">May be useful to identify the order when contacting support but not for reconciliation.</span></span></p></td>
<td><span data-ttu-id="27213-141">566890604832738111</span><span class="sxs-lookup"><span data-stu-id="27213-141">566890604832738111</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="27213-142">SubscriptionID</span><span class="sxs-lookup"><span data-stu-id="27213-142">SubscriptionID</span></span></td>
<td><p><span data-ttu-id="27213-143">訂閱在 Microsoft 帳單平台中的唯一識別碼。</span><span class="sxs-lookup"><span data-stu-id="27213-143">Unique identifier for a subscription in the Microsoft billing platform.</span></span> <span data-ttu-id="27213-144">可在連絡支援時方便識別訂閱，但不是用於對帳。</span><span class="sxs-lookup"><span data-stu-id="27213-144">May be useful to identify the subscription when contacting support but not for reconciliation.</span></span></p>
<p><span data-ttu-id="27213-145">這與合作夥伴管理主控台上的訂閱識別碼不一樣。</span><span class="sxs-lookup"><span data-stu-id="27213-145">This is not the same as the Subscription ID on the Partner Admin Console.</span></span> <span data-ttu-id="27213-146">請參閱 Syndication_Partner_Subscription_Number。</span><span class="sxs-lookup"><span data-stu-id="27213-146">Please see Syndication_Partner_Subscription_Number.</span></span></p></td>
<td><span data-ttu-id="27213-147">usCBMgAAAAAAAAIA</span><span class="sxs-lookup"><span data-stu-id="27213-147">usCBMgAAAAAAAAIA</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="27213-148">SyndicationPartnerSubscriptionNumber</span><span class="sxs-lookup"><span data-stu-id="27213-148">SyndicationPartnerSubscriptionNumber</span></span></td>
<td><p><span data-ttu-id="27213-149">訂閱的唯一識別碼。</span><span class="sxs-lookup"><span data-stu-id="27213-149">Unique identifier for subscriptions.</span></span> <span data-ttu-id="27213-150">客戶可針對同一方案擁有多項訂閱，因此這對於對帳檔案分析而言很重要。</span><span class="sxs-lookup"><span data-stu-id="27213-150">A customer can have multiple subscriptions for the same plan, so this is important for reconciliation file analysis.</span></span></p>
<p><span data-ttu-id="27213-151">這個欄位對應到合作夥伴管理主控台中的訂閱識別碼。</span><span class="sxs-lookup"><span data-stu-id="27213-151">This field maps to the Subscription ID in the Partner Admin Console.</span></span></p></td>
<td><span data-ttu-id="27213-152">fb977ab5-test-test-test-24c8d9591708</span><span class="sxs-lookup"><span data-stu-id="27213-152">fb977ab5-test-test-test-24c8d9591708</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="27213-153">OfferID</span><span class="sxs-lookup"><span data-stu-id="27213-153">OfferID</span></span></td>
<td><p><span data-ttu-id="27213-154">唯一的優惠識別碼。</span><span class="sxs-lookup"><span data-stu-id="27213-154">Unique offer ID.</span></span> <span data-ttu-id="27213-155">根據價目表的標準優惠識別碼。</span><span class="sxs-lookup"><span data-stu-id="27213-155">Standard offer ID as per price list.</span></span></p>
<p><span data-ttu-id="27213-156"><b>注意</b>：此值不符合優惠識別碼從價格清單。</span><span class="sxs-lookup"><span data-stu-id="27213-156"><b>Note</b>: This value does not match Offer ID from the price list.</span></span> <span data-ttu-id="27213-157">請參閱下方的 DurableOfferID。</span><span class="sxs-lookup"><span data-stu-id="27213-157">See DurableOfferID below.</span></span></p></td>
<td><span data-ttu-id="27213-158">FE616D64-E9A8-40EF-843F-152E9BBEF3D1</span><span class="sxs-lookup"><span data-stu-id="27213-158">FE616D64-E9A8-40EF-843F-152E9BBEF3D1</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="27213-159">DurableOfferID</span><span class="sxs-lookup"><span data-stu-id="27213-159">DurableOfferID</span></span></td>
<td><p><span data-ttu-id="27213-160">唯一的持續性優惠識別碼，如價目表中所定義。</span><span class="sxs-lookup"><span data-stu-id="27213-160">Unique durable offer ID, as defined in the price list.</span></span></p>
<p><span data-ttu-id="27213-161"><b>注意</b>：此值符合優惠識別碼從價格清單。</span><span class="sxs-lookup"><span data-stu-id="27213-161"><b>Note</b>: This value matches the Offer ID from the price list.</span></span></p></td>
<td><span data-ttu-id="27213-162">1017D7F3-6D7F-4BFA-BDD8-79BC8F104E0C</span><span class="sxs-lookup"><span data-stu-id="27213-162">1017D7F3-6D7F-4BFA-BDD8-79BC8F104E0C</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="27213-163">OfferName</span><span class="sxs-lookup"><span data-stu-id="27213-163">OfferName</span></span></td>
<td><p><span data-ttu-id="27213-164">客戶購買的服務優惠名稱，如價目表中所定義。</span><span class="sxs-lookup"><span data-stu-id="27213-164">The name of the service offering purchased by the customer, as defined in the price list.</span></span></p></td>
<td><span data-ttu-id="27213-165">Microsoft Office 365 (Plan E3)</span><span class="sxs-lookup"><span data-stu-id="27213-165">Microsoft Office 365 (Plan E3)</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="27213-166">SubscriptionStartDate</span><span class="sxs-lookup"><span data-stu-id="27213-166">SubscriptionStartDate</span></span></td>
<td><p><span data-ttu-id="27213-167">訂閱開始日期設定為送出訂單之後的隔日。</span><span class="sxs-lookup"><span data-stu-id="27213-167">The subscription start date, set to the day after the order is submitted.</span></span> <span data-ttu-id="27213-168">藉由同時查看訂閱開始日期與結束日期，您就可以判斷客戶是否仍在第一年訂閱期內，或下一年的訂閱已續約。</span><span class="sxs-lookup"><span data-stu-id="27213-168">By looking at the subscription start date in conjunction with the end date, you can determine if the customer is still within the first year of the subscription or if the subscription has been renewed for the following year.</span></span></p>
<p><span data-ttu-id="27213-169">時間一律是一天的開始時間 (0:00)。</span><span class="sxs-lookup"><span data-stu-id="27213-169">The time is always the beginning of the day, 0:00.</span></span></p></td>
<td><span data-ttu-id="27213-170">2/1/2015 0:00</span><span class="sxs-lookup"><span data-stu-id="27213-170">2/1/2015 0:00</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="27213-171">SubscriptionEndDate</span><span class="sxs-lookup"><span data-stu-id="27213-171">SubscriptionEndDate</span></span></td>
<td><p><span data-ttu-id="27213-172">訂用帳戶結束日期：12 個月 + x 天後 （以配合計費日期的夥伴） 的開始日期或續約日期起的 12 個月。</span><span class="sxs-lookup"><span data-stu-id="27213-172">The subscription end date: 12 months + x days after start date (to align with partner billing date) or 12 months from renewal date.</span></span></p>
<p><span data-ttu-id="27213-173">續約時，價格會更新至目前的價目表。</span><span class="sxs-lookup"><span data-stu-id="27213-173">At renewal, prices are updated to the current price list.</span></span> <span data-ttu-id="27213-174">自動續約之前，可能需要與客戶連絡。</span><span class="sxs-lookup"><span data-stu-id="27213-174">Customer communication may be required in advance of automated renewal.</span></span></p>
<p><span data-ttu-id="27213-175">時間一律是一天的開始時間 (0:00)。</span><span class="sxs-lookup"><span data-stu-id="27213-175">The time is always the beginning of the day, 0:00.</span></span></p></td>
<td><span data-ttu-id="27213-176">2/1/2015 0:00</span><span class="sxs-lookup"><span data-stu-id="27213-176">2/1/2015 0:00</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="27213-177">ChargeStartDate</span><span class="sxs-lookup"><span data-stu-id="27213-177">ChargeStartDate</span></span></td>
<td><p><span data-ttu-id="27213-178">開始計算費用的日期。</span><span class="sxs-lookup"><span data-stu-id="27213-178">Start day of the charges.</span></span></p>
<p><span data-ttu-id="27213-179">當客戶變更基座數目時，此數字用於計算每日 (按比例) 的費用。</span><span class="sxs-lookup"><span data-stu-id="27213-179">When a customer changes seat numbers, this number is used to calculate per-day (pro-rata) charges.</span></span></p>
<p><span data-ttu-id="27213-180">時間一律是一天的開始時間 (0:00)。</span><span class="sxs-lookup"><span data-stu-id="27213-180">The time is always the beginning of the day, 0:00.</span></span></p></td>
<td><span data-ttu-id="27213-181">2/1/2015 0:00</span><span class="sxs-lookup"><span data-stu-id="27213-181">2/1/2015 0:00</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="27213-182">ChargeEndDate</span><span class="sxs-lookup"><span data-stu-id="27213-182">ChargeEndDate</span></span></td>
<td><p><span data-ttu-id="27213-183">結束計算費用的日期。</span><span class="sxs-lookup"><span data-stu-id="27213-183">End day of the charges.</span></span></p>
<p><span data-ttu-id="27213-184">當客戶變更基座數目時，此數字用於計算每日 (按比例) 的費用。</span><span class="sxs-lookup"><span data-stu-id="27213-184">When a customer changes seat numbers, this number is used to calculate per-day (pro-rata) charges.</span></span></p>
<p><span data-ttu-id="27213-185">時間一律是一天的結束時間 (23:59)。</span><span class="sxs-lookup"><span data-stu-id="27213-185">The time is always the end of the day, 23:59.</span></span></p></td>
<td><span data-ttu-id="27213-186">2/28/2015 23:59</span><span class="sxs-lookup"><span data-stu-id="27213-186">2/28/2015 23:59</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="27213-187">ChargeType</span><span class="sxs-lookup"><span data-stu-id="27213-187">ChargeType</span></span></td>
<td><p><span data-ttu-id="27213-188">費用或調整的類型。</span><span class="sxs-lookup"><span data-stu-id="27213-188">The type of charge or adjustment.</span></span> <span data-ttu-id="27213-189">請參閱<a href="#charge_types">對應發票和對帳檔案之間的費用</a></span><span class="sxs-lookup"><span data-stu-id="27213-189">See <a href="#charge_types">Mapping charges between an invoice and the reconciliation file</a></span></span></p></td>
<td><p><span data-ttu-id="27213-190">請參閱<a href="#charge_types">對應發票和對帳檔案之間的費用</a></span><span class="sxs-lookup"><span data-stu-id="27213-190">See <a href="#charge_types">Mapping charges between an invoice and the reconciliation file</a></span></span></p></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="27213-191">UnitPrice</span><span class="sxs-lookup"><span data-stu-id="27213-191">UnitPrice</span></span></td>
<td><p><span data-ttu-id="27213-192">每一基座價格，即購買時價目表中所公佈的價格。</span><span class="sxs-lookup"><span data-stu-id="27213-192">Price per seat, as published in the pricelist at the time of purchase.</span></span> <span data-ttu-id="27213-193">請確定這與對帳期間儲存在您帳單系統中的資訊相符。</span><span class="sxs-lookup"><span data-stu-id="27213-193">Ensure this matches the information stored in your billing system during reconciliation.</span></span></p></td>
<td><span data-ttu-id="27213-194">6.82</span><span class="sxs-lookup"><span data-stu-id="27213-194">6.82</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="27213-195">數量</span><span class="sxs-lookup"><span data-stu-id="27213-195">Quantity</span></span></td>
<td><p><span data-ttu-id="27213-196">基座數目。</span><span class="sxs-lookup"><span data-stu-id="27213-196">Number of seats.</span></span> <span data-ttu-id="27213-197">請確定這與對帳期間儲存在您帳單系統中的資訊相符。</span><span class="sxs-lookup"><span data-stu-id="27213-197">Ensure this matches the information stored in your billing system during reconciliation.</span></span></p></td>
<td><span data-ttu-id="27213-198">2</span><span class="sxs-lookup"><span data-stu-id="27213-198">2</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="27213-199">數量</span><span class="sxs-lookup"><span data-stu-id="27213-199">Amount</span></span></td>
<td><p><span data-ttu-id="27213-200">數量總價。</span><span class="sxs-lookup"><span data-stu-id="27213-200">Total of price for quantity.</span></span> <span data-ttu-id="27213-201">檢查計算金額與您用來為客戶計算此項目的方式是否相符時很有用。</span><span class="sxs-lookup"><span data-stu-id="27213-201">Useful to check that the amount calculation matches how you calculate this for your customers.</span></span></p></td>
<td><span data-ttu-id="27213-202">13.32</span><span class="sxs-lookup"><span data-stu-id="27213-202">13.32</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="27213-203">TotalOtherDiscount</span><span class="sxs-lookup"><span data-stu-id="27213-203">TotalOtherDiscount</span></span></td>
<td><p><span data-ttu-id="27213-204">套用至這些費用的折扣金額。</span><span class="sxs-lookup"><span data-stu-id="27213-204">Amount of discount applied to these charges.</span></span> <span data-ttu-id="27213-205">符合獎勵資格之 IUR 或新訂閱的訂單，也將於此欄中包含折扣金額。</span><span class="sxs-lookup"><span data-stu-id="27213-205">IUR or new subscriptions eligible for an incentive will also contain a discount amount in this column.</span></span></p></td>
<td><span data-ttu-id="27213-206">2.32</span><span class="sxs-lookup"><span data-stu-id="27213-206">2.32</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="27213-207">小計</span><span class="sxs-lookup"><span data-stu-id="27213-207">Subtotal</span></span></td>
<td><p><span data-ttu-id="27213-208">稅前總計。</span><span class="sxs-lookup"><span data-stu-id="27213-208">Total before tax.</span></span> <span data-ttu-id="27213-209">如果有折扣，可檢查小計是否和預期的總金額相符。</span><span class="sxs-lookup"><span data-stu-id="27213-209">Checks that your subtotal matches your expected total, in case of a discount.</span></span></p></td>
<td><span data-ttu-id="27213-210">11</span><span class="sxs-lookup"><span data-stu-id="27213-210">11</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="27213-211">稅</span><span class="sxs-lookup"><span data-stu-id="27213-211">Tax</span></span></td>
<td><p><span data-ttu-id="27213-212">稅務量費用，費用，根據您的市場&#39;s 稅務規則與特定的情況。</span><span class="sxs-lookup"><span data-stu-id="27213-212">Tax amount charge, based on your market&#39;s tax rules and specific circumstances.</span></span></p></td>
<td><span data-ttu-id="27213-213">0</span><span class="sxs-lookup"><span data-stu-id="27213-213">0</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="27213-214">TotalForCustomer</span><span class="sxs-lookup"><span data-stu-id="27213-214">TotalForCustomer</span></span></td>
<td><p><span data-ttu-id="27213-215">稅後總計。</span><span class="sxs-lookup"><span data-stu-id="27213-215">Total after tax.</span></span> <span data-ttu-id="27213-216">檢查發票中是否向您收取稅金。</span><span class="sxs-lookup"><span data-stu-id="27213-216">Checks if you are charged tax in the invoice.</span></span></p></td>
<td><span data-ttu-id="27213-217">11</span><span class="sxs-lookup"><span data-stu-id="27213-217">11</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="27213-218">貨幣</span><span class="sxs-lookup"><span data-stu-id="27213-218">Currency</span></span></td>
<td><p><span data-ttu-id="27213-219">貨幣類型。</span><span class="sxs-lookup"><span data-stu-id="27213-219">Currency type.</span></span> <span data-ttu-id="27213-220">每一帳單實體都只有一種貨幣。</span><span class="sxs-lookup"><span data-stu-id="27213-220">Each billing entity has only one currency.</span></span> <span data-ttu-id="27213-221">檢查是否與您的第一張發票相符，然後在進行任何重大帳單平台更新之後檢查。</span><span class="sxs-lookup"><span data-stu-id="27213-221">Check that it matches your first invoice and then after any major billing platform update.</span></span></p></td>
<td><span data-ttu-id="27213-222">EUR</span><span class="sxs-lookup"><span data-stu-id="27213-222">EUR</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="27213-223">CustomerName</span><span class="sxs-lookup"><span data-stu-id="27213-223">CustomerName</span></span></td>
<td><p><span data-ttu-id="27213-224">客戶&#39;合作夥伴中心中所報告的 s 的組織名稱。</span><span class="sxs-lookup"><span data-stu-id="27213-224">Customer&#39;s organization name as reported in Partner Center.</span></span> <span data-ttu-id="27213-225">這在使用您的系統資訊對帳發票時非常重要。</span><span class="sxs-lookup"><span data-stu-id="27213-225">This is very important for reconciling the invoice with your system information.</span></span></p></td>
<td><span data-ttu-id="27213-226">測試客戶 A</span><span class="sxs-lookup"><span data-stu-id="27213-226">Test Customer A</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="27213-227">MPNID</span><span class="sxs-lookup"><span data-stu-id="27213-227">MPNID</span></span></td>
<td><p><span data-ttu-id="27213-228">雲端解決方案提供者合作夥伴的 MPN 識別碼</span><span class="sxs-lookup"><span data-stu-id="27213-228">MPN ID of the CSP partner</span></span></p></td>
<td><span data-ttu-id="27213-229">4390934</span><span class="sxs-lookup"><span data-stu-id="27213-229">4390934</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="27213-230">ResellerMPNID</span><span class="sxs-lookup"><span data-stu-id="27213-230">ResellerMPNID</span></span></td>
<td><p><span data-ttu-id="27213-231">訂閱記錄中的經銷商 MPN 識別碼。</span><span class="sxs-lookup"><span data-stu-id="27213-231">MPN ID of the reseller of record for the subscription.</span></span> <span data-ttu-id="27213-232">請參閱<a href="#itemizebypartner" data-raw-source="[Itemize by partner](#itemizebypartner)">依合作夥伴詳細列舉</a>。</span><span class="sxs-lookup"><span data-stu-id="27213-232">See <a href="#itemizebypartner" data-raw-source="[Itemize by partner](#itemizebypartner)">Itemize by partner</a>.</span></span></p></td>
<td><span data-ttu-id="27213-233">4390934</span><span class="sxs-lookup"><span data-stu-id="27213-233">4390934</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="27213-234">DomainName</span><span class="sxs-lookup"><span data-stu-id="27213-234">DomainName</span></span></td>
<td><p><span data-ttu-id="27213-235">客戶&#39;用來協助識別客戶的 s 網域名稱。</span><span class="sxs-lookup"><span data-stu-id="27213-235">Customer&#39;s domain name, used to help identify the customer.</span></span> <span data-ttu-id="27213-236">這不應該用來唯一識別客戶，客戶/合作夥伴可以更新透過 O365 入口網站的虛名/預設網域。</span><span class="sxs-lookup"><span data-stu-id="27213-236">This should not be used to uniquely identify the customer as the customer/partner can update the vanity/default domain via the O365 portal.</span></span> <span data-ttu-id="27213-237">在下一個帳單週期之前，此欄位會是空白的。</span><span class="sxs-lookup"><span data-stu-id="27213-237">This field may appear blank until the second billing cycle.</span></span></p></td>
<td><span data-ttu-id="27213-238">example.onmicrosoft.com</span><span class="sxs-lookup"><span data-stu-id="27213-238">example.onmicrosoft.com</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="27213-239">SubscriptionName</span><span class="sxs-lookup"><span data-stu-id="27213-239">SubscriptionName</span></span></td>
<td><p><span data-ttu-id="27213-240">訂閱暱稱。</span><span class="sxs-lookup"><span data-stu-id="27213-240">Subscription nickname.</span></span> <span data-ttu-id="27213-241">如果未指定任何暱稱，合作夥伴中心會使用 OfferName。</span><span class="sxs-lookup"><span data-stu-id="27213-241">If no nickname is specified, Partner Center uses the OfferName.</span></span></p></td>
<td><span data-ttu-id="27213-242">PROJECT ONLINE</span><span class="sxs-lookup"><span data-stu-id="27213-242">PROJECT ONLINE</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="27213-243">SubscriptionDescription</span><span class="sxs-lookup"><span data-stu-id="27213-243">SubscriptionDescription</span></span></td>
<td><p><span data-ttu-id="27213-244">客戶購買的服務優惠名稱，如價目表中所定義。</span><span class="sxs-lookup"><span data-stu-id="27213-244">The name of the service offering purchased by the customer, as defined in the price list.</span></span> <span data-ttu-id="27213-245">（這是優惠名稱的相同欄位）。</span><span class="sxs-lookup"><span data-stu-id="27213-245">(This is an identical field to Offer name).</span></span></p></td>
<td><span data-ttu-id="27213-246">PROJECT ONLINE PREMIUM WITHOUT PROJECT CLIENT</span><span class="sxs-lookup"><span data-stu-id="27213-246">PROJECT ONLINE PREMIUM WITHOUT PROJECT CLIENT</span></span></td>
</tr>
</tbody>
</table>


## <a href="" id="usagebasedfiles"></a><span data-ttu-id="27213-247">基於使用方式檔案欄位</span><span class="sxs-lookup"><span data-stu-id="27213-247">Usage-based file fields</span></span>


<span data-ttu-id="27213-248">若要針對您客戶使用量的費用來對帳，請比較對帳檔案中的 ResellerID/ResellerName/ResellerBillableAccount、客戶名稱，與合作夥伴中心的訂閱識別碼。</span><span class="sxs-lookup"><span data-stu-id="27213-248">To reconcile your charges against your customer's usage, compare the ResellerID/ResellerName/ResellerBillableAccount from the reconciliation file, the customer name, and the Subscription ID from Partner Center.</span></span>

<span data-ttu-id="27213-249">下列欄位說明使用哪些服務及費率。</span><span class="sxs-lookup"><span data-stu-id="27213-249">The following fields explain which services were used and the rate.</span></span>

<table>
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<tbody>
<tr class="odd">
<td><span data-ttu-id="27213-250"><strong>資料行</strong></span><span class="sxs-lookup"><span data-stu-id="27213-250"><strong>Column</strong></span></span></td>
<td><span data-ttu-id="27213-251"><strong>描述</strong></span><span class="sxs-lookup"><span data-stu-id="27213-251"><strong>Description</strong></span></span></td>
<td><span data-ttu-id="27213-252"><strong>範例值</strong></span><span class="sxs-lookup"><span data-stu-id="27213-252"><strong>Sample value</strong></span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="27213-253">PartnerID</span><span class="sxs-lookup"><span data-stu-id="27213-253">PartnerID</span></span></td>
<td><p><span data-ttu-id="27213-254">合作夥伴識別碼 (GUID 格式)。</span><span class="sxs-lookup"><span data-stu-id="27213-254">Partner ID, in GUID format.</span></span></p></td>
<td><span data-ttu-id="27213-255">DA41BC5F-C52D-4464-8A8D-8C8DCC43503B</span><span class="sxs-lookup"><span data-stu-id="27213-255">DA41BC5F-C52D-4464-8A8D-8C8DCC43503B</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="27213-256">PartnerName</span><span class="sxs-lookup"><span data-stu-id="27213-256">PartnerName</span></span></td>
<td><p><span data-ttu-id="27213-257">合作夥伴名稱。</span><span class="sxs-lookup"><span data-stu-id="27213-257">Partner Name.</span></span></p></td>
<td><span data-ttu-id="27213-258">Acme Incorporated</span><span class="sxs-lookup"><span data-stu-id="27213-258">Acme Incorporated</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="27213-259">PartnerBillableAccountID</span><span class="sxs-lookup"><span data-stu-id="27213-259">PartnerBillableAccountID</span></span></td>
<td><p><span data-ttu-id="27213-260">合作夥伴帳戶識別碼。</span><span class="sxs-lookup"><span data-stu-id="27213-260">Partner Account ID.</span></span></p></td>
<td><span data-ttu-id="27213-261">1010578050</span><span class="sxs-lookup"><span data-stu-id="27213-261">1010578050</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="27213-262">CustomerName</span><span class="sxs-lookup"><span data-stu-id="27213-262">CustomerName</span></span></td>
<td><p><span data-ttu-id="27213-263">客戶&#39;合作夥伴中心中所報告的 s 的組織名稱。</span><span class="sxs-lookup"><span data-stu-id="27213-263">Customer&#39;s organization name as reported in Partner Center.</span></span> <span data-ttu-id="27213-264">這在使用您的系統資訊對帳發票時非常重要。</span><span class="sxs-lookup"><span data-stu-id="27213-264">This is very important for reconciling the invoice with your system information.</span></span></p></td>
<td><span data-ttu-id="27213-265">測試客戶 A</span><span class="sxs-lookup"><span data-stu-id="27213-265">Test Customer A</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="27213-266">MPNID</span><span class="sxs-lookup"><span data-stu-id="27213-266">MPNID</span></span></td>
<td><p><span data-ttu-id="27213-267">雲端解決方案提供者合作夥伴的 MPN 識別碼。</span><span class="sxs-lookup"><span data-stu-id="27213-267">MPN ID of the CSP partner.</span></span></p></td>
<td><span data-ttu-id="27213-268">4390934</span><span class="sxs-lookup"><span data-stu-id="27213-268">4390934</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="27213-269">ResellerMPNID</span><span class="sxs-lookup"><span data-stu-id="27213-269">ResellerMPNID</span></span></td>
<td><p><span data-ttu-id="27213-270">訂閱記錄中的經銷商 MPN 識別碼。</span><span class="sxs-lookup"><span data-stu-id="27213-270">MPN ID of the reseller of record for the subscription.</span></span> <span data-ttu-id="27213-271">請參閱<a href="#itemizebypartner" data-raw-source="[Itemize by partner](#itemizebypartner)">依合作夥伴詳細列舉</a>。</span><span class="sxs-lookup"><span data-stu-id="27213-271">See <a href="#itemizebypartner" data-raw-source="[Itemize by partner](#itemizebypartner)">Itemize by partner</a>.</span></span></p></td>
<td><span data-ttu-id="27213-272">4390934</span><span class="sxs-lookup"><span data-stu-id="27213-272">4390934</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="27213-273">InvoiceNumber</span><span class="sxs-lookup"><span data-stu-id="27213-273">InvoiceNumber</span></span></td>
<td><p><span data-ttu-id="27213-274">交易的指定位置顯示的發票號碼。</span><span class="sxs-lookup"><span data-stu-id="27213-274">Invoice number where the specified transaction appears.</span></span></p></td>
<td><span data-ttu-id="27213-275">D020001IVK</span><span class="sxs-lookup"><span data-stu-id="27213-275">D020001IVK</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="27213-276">ChargeStartDate</span><span class="sxs-lookup"><span data-stu-id="27213-276">ChargeStartDate</span></span></td>
<td><p><span data-ttu-id="27213-277">計費週期的開始日期，當顯示之前未收取潛在使用量資料費用的日期時除外 (從前一個計費週期開始)。</span><span class="sxs-lookup"><span data-stu-id="27213-277">Start date of billing cycle except when presenting dates of previously uncharged latent usage data (from previous bill cycle).</span></span></p>
<p><span data-ttu-id="27213-278">時間一律是一天的開始時間 (0:00)。</span><span class="sxs-lookup"><span data-stu-id="27213-278">The time is always the beginning of the day, 0:00.</span></span></p></td>
<td><span data-ttu-id="27213-279">2/1/2014 0:00</span><span class="sxs-lookup"><span data-stu-id="27213-279">2/1/2014 0:00</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="27213-280">ChargeEndDate</span><span class="sxs-lookup"><span data-stu-id="27213-280">ChargeEndDate</span></span></td>
<td><p><span data-ttu-id="27213-281">計費週期的結束日期，當顯示之前未收取潛在使用量資料費用的日期時除外 (從前一個計費週期開始)。</span><span class="sxs-lookup"><span data-stu-id="27213-281">End date of billing cycle except when presenting dates of previously uncharged latent usage data (from previous bill cycle).</span></span></p>
<p><span data-ttu-id="27213-282">時間一律是一天的結束時間 (23:59)。</span><span class="sxs-lookup"><span data-stu-id="27213-282">The time is always the end of the day, 23:59.</span></span></p></td>
<td><span data-ttu-id="27213-283">2/28/2014 23:59</span><span class="sxs-lookup"><span data-stu-id="27213-283">2/28/2014 23:59</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="27213-284">SubscriptionID</span><span class="sxs-lookup"><span data-stu-id="27213-284">SubscriptionID</span></span></td>
<td><p><span data-ttu-id="27213-285">訂閱在 Microsoft 帳單平台中的唯一識別碼。</span><span class="sxs-lookup"><span data-stu-id="27213-285">Unique identifier for a subscription in the Microsoft billing platform.</span></span> <span data-ttu-id="27213-286">可在連絡支援時方便識別訂閱，但不是用於對帳。</span><span class="sxs-lookup"><span data-stu-id="27213-286">May be useful to identify the subscription when contacting support but not for reconciliation.</span></span></p>
<p><span data-ttu-id="27213-287">這與合作夥伴管理主控台上的訂閱識別碼不一樣。</span><span class="sxs-lookup"><span data-stu-id="27213-287">This is not the same as the Subscription ID on the Partner Admin Console.</span></span></p></td>
<td><span data-ttu-id="27213-288">usCBMgAAAAAAAAIA</span><span class="sxs-lookup"><span data-stu-id="27213-288">usCBMgAAAAAAAAIA</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="27213-289">SubscriptionName</span><span class="sxs-lookup"><span data-stu-id="27213-289">SubscriptionName</span></span></td>
<td><p><span data-ttu-id="27213-290">服務優惠的暱稱。</span><span class="sxs-lookup"><span data-stu-id="27213-290">Nickname of the service offering.</span></span></p></td>
<td><span data-ttu-id="27213-291">Microsoft Azure</span><span class="sxs-lookup"><span data-stu-id="27213-291">Microsoft Azure</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="27213-292">SubscriptionDescription</span><span class="sxs-lookup"><span data-stu-id="27213-292">SubscriptionDescription</span></span></td>
<td><p><span data-ttu-id="27213-293">服務優惠的企業營運</span><span class="sxs-lookup"><span data-stu-id="27213-293">Line of business of the service offering</span></span></p></td>
<td><span data-ttu-id="27213-294">Microsoft Azure</span><span class="sxs-lookup"><span data-stu-id="27213-294">Microsoft Azure</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="27213-295">OrderID</span><span class="sxs-lookup"><span data-stu-id="27213-295">OrderID</span></span></td>
<td><p><span data-ttu-id="27213-296">訂單在 Microsoft 帳單平台中的唯一識別碼。</span><span class="sxs-lookup"><span data-stu-id="27213-296">Unique identifier for an order in the Microsoft billing platform.</span></span> <span data-ttu-id="27213-297">可在連絡支援時方便識別訂閱，但不是用於對帳。</span><span class="sxs-lookup"><span data-stu-id="27213-297">May be useful to identify the subscription when contacting support but not for reconciliation.</span></span></p></td>
<td><span data-ttu-id="27213-298">566890604832738111</span><span class="sxs-lookup"><span data-stu-id="27213-298">566890604832738111</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="27213-299">ServiceName</span><span class="sxs-lookup"><span data-stu-id="27213-299">ServiceName</span></span></td>
<td><p><span data-ttu-id="27213-300">要求的 Azure 服務名稱。</span><span class="sxs-lookup"><span data-stu-id="27213-300">The name of the Azure service in question.</span></span></p></td>
<td><span data-ttu-id="27213-301">虛擬機器</span><span class="sxs-lookup"><span data-stu-id="27213-301">VIRTUAL MACHINES</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="27213-302">ServiceType</span><span class="sxs-lookup"><span data-stu-id="27213-302">ServiceType</span></span></td>
<td><p><span data-ttu-id="27213-303">Microsoft Azure 服務的特定類型。</span><span class="sxs-lookup"><span data-stu-id="27213-303">The specific type of Windows Azure service.</span></span></p></td>
<td><ul>
<li><span data-ttu-id="27213-304">服務匯流排 – 個人或套件</span><span class="sxs-lookup"><span data-stu-id="27213-304">Service Bus – Individual or Pack</span></span></li>
<li><span data-ttu-id="27213-305">SQL Azure 資料庫 – Business 或 Web Edition</span><span class="sxs-lookup"><span data-stu-id="27213-305">SQL Azure database – Business or Web Edition</span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="27213-306">ResourceGUID</span><span class="sxs-lookup"><span data-stu-id="27213-306">ResourceGUID</span></span></td>
<td><p><span data-ttu-id="27213-307">所有服務資料與定價結構的特定唯一識別碼。</span><span class="sxs-lookup"><span data-stu-id="27213-307">Specific unique identifier for all the service data and pricing structure.</span></span></p></td>
<td><span data-ttu-id="27213-308">DA41BC5F-C52D-4464-8A8D-8C8DCC43503B</span><span class="sxs-lookup"><span data-stu-id="27213-308">DA41BC5F-C52D-4464-8A8D-8C8DCC43503B</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="27213-309">Resource Name</span><span class="sxs-lookup"><span data-stu-id="27213-309">Resource Name</span></span></td>
<td><p><span data-ttu-id="27213-310">Azure 資源的名稱。</span><span class="sxs-lookup"><span data-stu-id="27213-310">The name of the Azure resource.</span></span></p></td>
<td><ul>
<li><span data-ttu-id="27213-311">資料轉入 (GB)</span><span class="sxs-lookup"><span data-stu-id="27213-311">Data Transfer In (GB)</span></span></li>
<li><span data-ttu-id="27213-312">資料轉出 (GB)</span><span class="sxs-lookup"><span data-stu-id="27213-312">Data Transfer Out (GB)</span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="27213-313">地區</span><span class="sxs-lookup"><span data-stu-id="27213-313">Region</span></span></td>
<td><p><span data-ttu-id="27213-314">使用量適用的地區。</span><span class="sxs-lookup"><span data-stu-id="27213-314">The region the usage applies to.</span></span> <span data-ttu-id="27213-315">主要用來指定資料傳輸速率，費率因地區而異。</span><span class="sxs-lookup"><span data-stu-id="27213-315">Primarily used to assign rates to data transfers, as rates vary by region.</span></span></p></td>
<td><span data-ttu-id="27213-316">亞太地區、歐洲、拉丁美洲、北美洲</span><span class="sxs-lookup"><span data-stu-id="27213-316">Asia Pacific, Europe, Latin America, North America</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="27213-317">SKU</span><span class="sxs-lookup"><span data-stu-id="27213-317">SKU</span></span></td>
<td><p><span data-ttu-id="27213-318">優惠的 MSFT 唯一識別碼</span><span class="sxs-lookup"><span data-stu-id="27213-318">MSFT unique identifier for offer</span></span></p></td>
<td><span data-ttu-id="27213-319">7UD 00001</span><span class="sxs-lookup"><span data-stu-id="27213-319">7UD-00001</span></span></td>
</tr>
<tr class="odd">
<td><p><span data-ttu-id="27213-320">DetailLineItemId</span><span class="sxs-lookup"><span data-stu-id="27213-320">DetailLineItemId</span></span></p></td>
<td><p><span data-ttu-id="27213-321">用於詳細列出指定計費期間中，服務或資源不同費率的識別碼和數量。</span><span class="sxs-lookup"><span data-stu-id="27213-321">An ID and quantity for itemizing the different rates for a service or resource in a given billing period.</span></span> <span data-ttu-id="27213-322">對於 Azure 分層評分，到某個數量的計費單位會有一個評分，之後則有不同評分。</span><span class="sxs-lookup"><span data-stu-id="27213-322">For Azure tiered rating, there may be one rate up to a certain quantity of billable units, then a different rate after that.</span></span></p></td>
<td><span data-ttu-id="27213-323">1</span><span class="sxs-lookup"><span data-stu-id="27213-323">1</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="27213-324">ConsumedQuantity</span><span class="sxs-lookup"><span data-stu-id="27213-324">ConsumedQuantity</span></span></td>
<td><p><span data-ttu-id="27213-325">報表期間耗用的服務量 (小時、GB 等等)</span><span class="sxs-lookup"><span data-stu-id="27213-325">The amount of service consumed (hours, GB, etc.) during the reporting period.</span></span></p>
<p><span data-ttu-id="27213-326">同時包括先前報表期間任何未計費的使用量。</span><span class="sxs-lookup"><span data-stu-id="27213-326">Also includes any unbilled usage from previous reporting periods.</span></span></p></td>
<td><span data-ttu-id="27213-327">11</span><span class="sxs-lookup"><span data-stu-id="27213-327">11</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="27213-328">IncludedQuantity</span><span class="sxs-lookup"><span data-stu-id="27213-328">IncludedQuantity</span></span></td>
<td><p><span data-ttu-id="27213-329">包含在優惠中的單位。</span><span class="sxs-lookup"><span data-stu-id="27213-329">Units included as part of the offer.</span></span> <span data-ttu-id="27213-330">通常不會出現在雲端解決方案提供者中。</span><span class="sxs-lookup"><span data-stu-id="27213-330">Not typically present in CSP.</span></span></p></td>
<td><span data-ttu-id="27213-331">0</span><span class="sxs-lookup"><span data-stu-id="27213-331">0</span></span></td>
</tr>
<tr class="even">
<td><p><span data-ttu-id="27213-332">OverageQuantity</span><span class="sxs-lookup"><span data-stu-id="27213-332">OverageQuantity</span></span></p></td>
<td><p><span data-ttu-id="27213-333">不包含在優惠中的單位，必須由合作夥伴支付。</span><span class="sxs-lookup"><span data-stu-id="27213-333">Units not included as part of the offer, that must be paid for by the partner.</span></span></p>
<p><span data-ttu-id="27213-334">等同於 ConsumedQuantity - IncludedQuantity。</span><span class="sxs-lookup"><span data-stu-id="27213-334">Equal to the ConsumedQuantity - IncludedQuantity.</span></span></p></td>
<td><span data-ttu-id="27213-335">11</span><span class="sxs-lookup"><span data-stu-id="27213-335">11</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="27213-336">ListPrice</span><span class="sxs-lookup"><span data-stu-id="27213-336">ListPrice</span></span></td>
<td><p><span data-ttu-id="27213-337">訂閱開始日期的生效優惠價格。</span><span class="sxs-lookup"><span data-stu-id="27213-337">Offer price in effect at subscription start date.</span></span></p></td>
<td><span data-ttu-id="27213-338">$0.0808</span><span class="sxs-lookup"><span data-stu-id="27213-338">$0.0808</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="27213-339">PretaxCharges</span><span class="sxs-lookup"><span data-stu-id="27213-339">PretaxCharges</span></span></td>
<td><p><span data-ttu-id="27213-340">ListPrist 乘以 OverageQuantity，四捨五入至美分。</span><span class="sxs-lookup"><span data-stu-id="27213-340">ListPrist times OverageQuantity, rounded to the nearest cent.</span></span></p></td>
<td><span data-ttu-id="27213-341">$0.085</span><span class="sxs-lookup"><span data-stu-id="27213-341">$0.085</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="27213-342">TaxAmount</span><span class="sxs-lookup"><span data-stu-id="27213-342">TaxAmount</span></span></td>
<td><p><span data-ttu-id="27213-343">稅務量費用，費用，根據您的市場&#39;s 稅務規則與特定的情況。</span><span class="sxs-lookup"><span data-stu-id="27213-343">Tax amount charge, based on your market&#39;s tax rules and specific circumstances.</span></span></p></td>
<td><span data-ttu-id="27213-344">$0.08</span><span class="sxs-lookup"><span data-stu-id="27213-344">$0.08</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="27213-345">PostTaxTotal</span><span class="sxs-lookup"><span data-stu-id="27213-345">PostTaxTotal</span></span></td>
<td><p><span data-ttu-id="27213-346">稅後總計 (當適用稅金時)。</span><span class="sxs-lookup"><span data-stu-id="27213-346">Total after tax, when tax is applicable.</span></span></p></td>
<td><span data-ttu-id="27213-347">$0.93</span><span class="sxs-lookup"><span data-stu-id="27213-347">$0.93</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="27213-348">貨幣</span><span class="sxs-lookup"><span data-stu-id="27213-348">Currency</span></span></td>
<td><p><span data-ttu-id="27213-349">貨幣類型。</span><span class="sxs-lookup"><span data-stu-id="27213-349">Currency type.</span></span> <span data-ttu-id="27213-350">每一帳單實體都只有一種貨幣。</span><span class="sxs-lookup"><span data-stu-id="27213-350">Each billing entity has only one currency.</span></span> <span data-ttu-id="27213-351">檢查是否與您的第一張發票相符，然後在進行任何重大帳單平台更新之後檢查。</span><span class="sxs-lookup"><span data-stu-id="27213-351">Check that it matches your first invoice and then after any major billing platform update.</span></span></p></td>
<td><span data-ttu-id="27213-352">EUR</span><span class="sxs-lookup"><span data-stu-id="27213-352">EUR</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="27213-353">PretaxEffectiveRate</span><span class="sxs-lookup"><span data-stu-id="27213-353">PretaxEffectiveRate</span></span></td>
<td><p><span data-ttu-id="27213-354">每個單位的稅前價格。</span><span class="sxs-lookup"><span data-stu-id="27213-354">Pretax price per unit.</span></span> <span data-ttu-id="27213-355">等於 PretaxCharges / OverageQuantity, 四捨五入至美分。</span><span class="sxs-lookup"><span data-stu-id="27213-355">Equal to PretaxCharges / OverageQuantity, rounded to the nearest cent.</span></span></p></td>
<td><span data-ttu-id="27213-356">$0.08</span><span class="sxs-lookup"><span data-stu-id="27213-356">$0.08</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="27213-357">PostTaxEffectiveRate</span><span class="sxs-lookup"><span data-stu-id="27213-357">PostTaxEffectiveRate</span></span></td>
<td><p><span data-ttu-id="27213-358">每個單位的稅後價格。</span><span class="sxs-lookup"><span data-stu-id="27213-358">Post tax price per unit.</span></span> <span data-ttu-id="27213-359">等於 PostTaxTotal / OverageQuantity，或 PretaxEffectiveRate + 每單位數量稅率，四捨五入至美分。</span><span class="sxs-lookup"><span data-stu-id="27213-359">Equal to PostTaxTotal / OverageQuantity, or PretaxEffectiveRate + tax rate per unit amoun, rounded to the nearest cent.</span></span></p></td>
<td><span data-ttu-id="27213-360">$0.08</span><span class="sxs-lookup"><span data-stu-id="27213-360">$0.08</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="27213-361">ChargeType</span><span class="sxs-lookup"><span data-stu-id="27213-361">ChargeType</span></span></td>
<td><p><span data-ttu-id="27213-362">費用或調整的類型。</span><span class="sxs-lookup"><span data-stu-id="27213-362">The type of charge or adjustment.</span></span> <span data-ttu-id="27213-363">請參閱<a href="#charge_types">對應發票和對帳檔案之間的費用</a></span><span class="sxs-lookup"><span data-stu-id="27213-363">See <a href="#charge_types">Mapping charges between an invoice and the reconciliation file</a></span></span></p></td>
<td><p><span data-ttu-id="27213-364">請參閱<a href="#charge_types">對應發票和對帳檔案之間的費用</a></span><span class="sxs-lookup"><span data-stu-id="27213-364">See <a href="#charge_types">Mapping charges between an invoice and the reconciliation file</a></span></span></p></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="27213-365">CustomerBillableAccount</span><span class="sxs-lookup"><span data-stu-id="27213-365">CustomerBillableAccount</span></span></td>
<td><p><span data-ttu-id="27213-366">MSFT 帳單平台的唯一帳戶識別碼。</span><span class="sxs-lookup"><span data-stu-id="27213-366">Unique account ID in the MSFT billing platform.</span></span></p></td>
<td><span data-ttu-id="27213-367">1280018095</span><span class="sxs-lookup"><span data-stu-id="27213-367">1280018095</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="27213-368">UsageDate</span><span class="sxs-lookup"><span data-stu-id="27213-368">UsageDate</span></span></td>
<td><p><span data-ttu-id="27213-369">服務部署的日期。</span><span class="sxs-lookup"><span data-stu-id="27213-369">Date of service deployment.</span></span></p></td>
<td><span data-ttu-id="27213-370">2/1/2014 0:00</span><span class="sxs-lookup"><span data-stu-id="27213-370">2/1/2014 0:00</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="27213-371">MeteredRegion</span><span class="sxs-lookup"><span data-stu-id="27213-371">MeteredRegion</span></span></td>
<td><p><span data-ttu-id="27213-372">此欄可識別適用及填入此項目之服務地區內的資料中心的位置。</span><span class="sxs-lookup"><span data-stu-id="27213-372">This column identifies the location of a data center within the region for services where this is applicable and populated.</span></span></p></td>
<td><span data-ttu-id="27213-373">東亞、東南亞、北歐、西歐、美國中北部、美國中南部</span><span class="sxs-lookup"><span data-stu-id="27213-373">East Asia, South East Asia, North Europe, West Europe, North Central US, South Central US</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="27213-374">MeteredService</span><span class="sxs-lookup"><span data-stu-id="27213-374">MeteredService</span></span></td>
<td><p><span data-ttu-id="27213-375">此欄是用來追蹤可能未在 \[服務名稱\] 欄中特別指出的個別 Microsoft Azure 服務。</span><span class="sxs-lookup"><span data-stu-id="27213-375">This column is utilized to track the individual Microsoft Azure service that may not be specifically identified in the Service Name column.</span></span> <span data-ttu-id="27213-376">例如，在 \[服務名稱\] 欄中，資料傳輸是回報為 &quot;Microsoft Azure - 所有服務&quot;。</span><span class="sxs-lookup"><span data-stu-id="27213-376">For example, data transfers are reported as &quot;Microsoft Azure - All Services&quot; in the Service Name column.</span></span> <span data-ttu-id="27213-377">此 MeteredService 欄會指出使用量與哪個特定服務有關。</span><span class="sxs-lookup"><span data-stu-id="27213-377">This MeteredService column will indicate to which specific service the usage pertains.</span></span></p></td>
<td><span data-ttu-id="27213-378">AccessControl、CDN、Compute、Database、ServiceBus、Storage</span><span class="sxs-lookup"><span data-stu-id="27213-378">AccessControl, CDN, Compute, Database, ServiceBus, Storage</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="27213-379">MeteredServiceType</span><span class="sxs-lookup"><span data-stu-id="27213-379">MeteredServiceType</span></span></td>
<td><p><span data-ttu-id="27213-380">進一步釐清超出 MeteredService 欄位提供之層級的個別 Microsoft Azure 服務副標題。</span><span class="sxs-lookup"><span data-stu-id="27213-380">A subheading that further clarifies the individual Microsoft Azure service beyond the level provided by the MeteredService field.</span></span></p></td>
<td><span data-ttu-id="27213-381">外部</span><span class="sxs-lookup"><span data-stu-id="27213-381">EXTERNAL</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="27213-382">Project</span><span class="sxs-lookup"><span data-stu-id="27213-382">Project</span></span></td>
<td><p><span data-ttu-id="27213-383">客戶為其服務執行個體定義的名稱</span><span class="sxs-lookup"><span data-stu-id="27213-383">Customer-defined name for their service instance</span></span></p></td>
<td><span data-ttu-id="27213-384">ORDDC52E52FDEF405786F0642DD0108BE4</span><span class="sxs-lookup"><span data-stu-id="27213-384">ORDDC52E52FDEF405786F0642DD0108BE4</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="27213-385">ServiceInfo</span><span class="sxs-lookup"><span data-stu-id="27213-385">ServiceInfo</span></span></td>
<td><p><span data-ttu-id="27213-386">於某一天佈建及使用的 ServiceBus 連線數目。</span><span class="sxs-lookup"><span data-stu-id="27213-386">The number of ServiceBus connections that were provisioned and utilized on a given day.</span></span></p></td>
<td><span data-ttu-id="27213-387">例如：如果您在有 30 天的月份中有個別佈建的連線時，「服務資訊 1」的讀數會是「1.000000 連線 / 30 天」。</span><span class="sxs-lookup"><span data-stu-id="27213-387">For example: if you had an individually provisioned connection during a 30 day month, Service Info 1 would read “1.000000 Connections / 30 days”.</span></span> <span data-ttu-id="27213-388">如果您有 25 的組件的佈建的服務匯流排連線，而且您必須在那一天使用 1，表示您那一天的每日使用量聲明 」 25 的連線 / 已使用的 30 天：1.000000”.</span><span class="sxs-lookup"><span data-stu-id="27213-388">If you had a 25 pack of ServiceBus connections provisioned and you had utilized 1 during that day, your daily usage statement for that day would indicate “25 Connections / 30 Days – Used: 1.000000”.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="27213-389">CustomerID</span><span class="sxs-lookup"><span data-stu-id="27213-389">CustomerID</span></span></td>
<td><p><span data-ttu-id="27213-390">用來識別客戶的唯一 Microsoft ID（GUID 格式）。</span><span class="sxs-lookup"><span data-stu-id="27213-390">Unique Microsoft ID, in GUID format, used to identify the customer.</span></span></p></td>
<td><span data-ttu-id="27213-391">ORDDC52E52FDEF405786F0642DD0108BE4</span><span class="sxs-lookup"><span data-stu-id="27213-391">ORDDC52E52FDEF405786F0642DD0108BE4</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="27213-392">DomainName</span><span class="sxs-lookup"><span data-stu-id="27213-392">DomainName</span></span></td>
<td><p><span data-ttu-id="27213-393">客戶&#39;用來協助識別客戶的 s 網域名稱。</span><span class="sxs-lookup"><span data-stu-id="27213-393">Customer&#39;s domain name, used to help identify the customer.</span></span> <span data-ttu-id="27213-394">在下一個帳單週期之前，此欄位會是空白的。</span><span class="sxs-lookup"><span data-stu-id="27213-394">This field may appear blank until the second billing cycle.</span></span></p></td>
<td><span data-ttu-id="27213-395">example.onmicrosoft.com</span><span class="sxs-lookup"><span data-stu-id="27213-395">example.onmicrosoft.com</span></span></td></tr>
</tr>
<tr class="even">
<td><span data-ttu-id="27213-396">單位</span><span class="sxs-lookup"><span data-stu-id="27213-396">Unit</span></span></td>
<td><p><span data-ttu-id="27213-397">資源名稱的單位</span><span class="sxs-lookup"><span data-stu-id="27213-397">The unit of the resource Name</span></span></p></td>
<td><span data-ttu-id="27213-398">GB 或 HOURS</span><span class="sxs-lookup"><span data-stu-id="27213-398">GB or HOURS</span></span></td>
</tr>
</tbody>
</table>

## <a href="" id="marketplacefilefields"></a><span data-ttu-id="27213-399">單次和週期的檔案欄位</span><span class="sxs-lookup"><span data-stu-id="27213-399">One-time and recurring file fields</span></span>

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th><span data-ttu-id="27213-400">Column</span><span class="sxs-lookup"><span data-stu-id="27213-400">Column</span></span></th>
<th><span data-ttu-id="27213-401">描述</span><span class="sxs-lookup"><span data-stu-id="27213-401">Description</span></span></th>
</tr>
</thead>
<tbody>


<tr class="odd">
<td><span data-ttu-id="27213-402">PartnerId</span><span class="sxs-lookup"><span data-stu-id="27213-402">PartnerId</span></span></td>
<td><p><span data-ttu-id="27213-403">唯一特定計費實體，則採用 GUID 格式的 Microsoft Azure Active Directory 租用戶識別碼。</span><span class="sxs-lookup"><span data-stu-id="27213-403">Unique Microsoft Azure Active Directory tenant identifier for a specific billing entity, in GUID format.</span></span> <span data-ttu-id="27213-404">對帳時不需要，但可能是很有用的資訊。</span><span class="sxs-lookup"><span data-stu-id="27213-404">Not required for reconciliation, however may be useful information.</span></span> <span data-ttu-id="27213-405">在所有資料列中都是如此。</span><span class="sxs-lookup"><span data-stu-id="27213-405">Same in all rows.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="27213-406">客戶識別碼</span><span class="sxs-lookup"><span data-stu-id="27213-406">Customer Id</span></span></td>
<td><p><span data-ttu-id="27213-407">Microsoft Azure Active Directory 租用戶中唯一識別碼，用來識別客戶的 GUID 格式。</span><span class="sxs-lookup"><span data-stu-id="27213-407">Unique Microsoft Azure Active Directory tenant ID, in GUID format, used to identify the customer.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="27213-408">[客戶名稱]</span><span class="sxs-lookup"><span data-stu-id="27213-408">Customer Name</span></span></td>
<td><p><span data-ttu-id="27213-409">合作夥伴中心中回報的客戶組織名稱。</span><span class="sxs-lookup"><span data-stu-id="27213-409">Customer's organization name as reported in Partner Center.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="27213-410">CustomerDomainName</span><span class="sxs-lookup"><span data-stu-id="27213-410">CustomerDomainName</span></span></td>
<td><p><span data-ttu-id="27213-411">用來協助識別客戶的客戶網域名稱。</span><span class="sxs-lookup"><span data-stu-id="27213-411">Customer's domain name, used to help identify the customer.</span></span> <span data-ttu-id="27213-412">這不應該用來唯一識別客戶，客戶/合作夥伴可以更新透過 O365 入口網站的虛名/預設網域。</span><span class="sxs-lookup"><span data-stu-id="27213-412">This should not be used to uniquely identify the customer as the customer/partner can update the vanity/default domain via the O365 portal.</span></span> <span data-ttu-id="27213-413">在下一個帳單週期之前，此欄位會是空白的。</span><span class="sxs-lookup"><span data-stu-id="27213-413">This field may appear blank until the second billing cycle.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="27213-414">客戶的國家/地區</span><span class="sxs-lookup"><span data-stu-id="27213-414">Customer Country</span></span></td>
<td><p><span data-ttu-id="27213-415">客戶所在的國家/地區。</span><span class="sxs-lookup"><span data-stu-id="27213-415">The country in which the customer is located.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="27213-416">發票號碼</span><span class="sxs-lookup"><span data-stu-id="27213-416">Invoice number</span></span></td>
<td><p><span data-ttu-id="27213-417">交易的指定位置顯示的發票號碼。</span><span class="sxs-lookup"><span data-stu-id="27213-417">Invoice number where the specified transaction appears.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="27213-418">MpnId</span><span class="sxs-lookup"><span data-stu-id="27213-418">MpnId</span></span></td>
<td><p><span data-ttu-id="27213-419">雲端解決方案提供者合作夥伴的 MPN 識別碼。</span><span class="sxs-lookup"><span data-stu-id="27213-419">MPN ID of the CSP partner.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="27213-420">Reseller MpnId</span><span class="sxs-lookup"><span data-stu-id="27213-420">Reseller MpnId</span></span></td>
<td><p><span data-ttu-id="27213-421">訂閱記錄中的經銷商 MPN 識別碼。</span><span class="sxs-lookup"><span data-stu-id="27213-421">MPN ID of the reseller of record for the subscription.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="27213-422">訂單識別碼</span><span class="sxs-lookup"><span data-stu-id="27213-422">Order ID</span></span></td>
<td><p><span data-ttu-id="27213-423">Microsoft commerce platform 中順序的唯一識別碼。</span><span class="sxs-lookup"><span data-stu-id="27213-423">Unique identifier for an order in the Microsoft commerce platform.</span></span> <span data-ttu-id="27213-424">可在連絡支援時方便識別訂單，但不是用於對帳。</span><span class="sxs-lookup"><span data-stu-id="27213-424">May be useful to identify the order when contacting support but not for reconciliation.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="27213-425">訂單日期</span><span class="sxs-lookup"><span data-stu-id="27213-425">Order date</span></span></td>
<td><p><span data-ttu-id="27213-426">下訂單的日期。</span><span class="sxs-lookup"><span data-stu-id="27213-426">The date the order was placed.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="27213-427">ProductId</span><span class="sxs-lookup"><span data-stu-id="27213-427">ProductId</span></span></td>
<td><p><span data-ttu-id="27213-428">產品的識別碼。</span><span class="sxs-lookup"><span data-stu-id="27213-428">The ID for the product.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="27213-429">SkuId</span><span class="sxs-lookup"><span data-stu-id="27213-429">SkuId</span></span></td>
<td><p><span data-ttu-id="27213-430">特定 SKU 的識別碼。</span><span class="sxs-lookup"><span data-stu-id="27213-430">The ID for a particular SKU.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="27213-431">AvailabilityId</span><span class="sxs-lookup"><span data-stu-id="27213-431">AvailabilityId</span></span></td>
<td><p><span data-ttu-id="27213-432">特定可用性的識別碼。</span><span class="sxs-lookup"><span data-stu-id="27213-432">The ID for a particular Availability.</span></span> <span data-ttu-id="27213-433">「可用性」是指特定 SKU 是否可供特定的國家/地區、貨幣、行業區段等等購買。</span><span class="sxs-lookup"><span data-stu-id="27213-433">“Availability” refers to whether or not a particular SKU is available for purchase for the given country, currency, industry segment, etc.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="27213-434">SKU 名稱</span><span class="sxs-lookup"><span data-stu-id="27213-434">SKU Name</span></span></td>
<td><p><span data-ttu-id="27213-435">特定 SKU 的標題。</span><span class="sxs-lookup"><span data-stu-id="27213-435">The title for a particular SKU.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="27213-436">產品名稱</span><span class="sxs-lookup"><span data-stu-id="27213-436">Product name</span></span></td>
<td><p><span data-ttu-id="27213-437">產品的名稱。</span><span class="sxs-lookup"><span data-stu-id="27213-437">The name of the product.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="27213-438">PublisherName</span><span class="sxs-lookup"><span data-stu-id="27213-438">PublisherName</span></span></td>
<td><p><span data-ttu-id="27213-439">產品的 「 發行者 」 的名稱。</span><span class="sxs-lookup"><span data-stu-id="27213-439">The name of the product’s publisher.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="27213-440">PublisherID</span><span class="sxs-lookup"><span data-stu-id="27213-440">PublisherID</span></span></td>
<td><p><span data-ttu-id="27213-441">這個 「 發行者 」 的唯一識別碼。</span><span class="sxs-lookup"><span data-stu-id="27213-441">Unique ID for this publisher.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="27213-442">訂用帳戶描述</span><span class="sxs-lookup"><span data-stu-id="27213-442">Subscription Description</span></span></td>
<td><p><span data-ttu-id="27213-443">訂用帳戶的易記名稱。</span><span class="sxs-lookup"><span data-stu-id="27213-443">Friendly name of a subscription.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="27213-444">訂閱識別碼</span><span class="sxs-lookup"><span data-stu-id="27213-444">Subscription ID</span></span></td>
<td><p><span data-ttu-id="27213-445">Microsoft 商務平台的訂用帳戶的唯一識別碼。</span><span class="sxs-lookup"><span data-stu-id="27213-445">Unique identifier for a subscription in the Microsoft commerce platform.</span></span> <span data-ttu-id="27213-446">可在連絡支援時方便識別訂閱，但不是用於對帳。</span><span class="sxs-lookup"><span data-stu-id="27213-446">May be useful to identify the subscription when contacting support but not for reconciliation.</span></span> <span data-ttu-id="27213-447">這與合作夥伴管理主控台上的訂閱識別碼不一樣。</span><span class="sxs-lookup"><span data-stu-id="27213-447">This is not the same as the Subscription ID on the Partner Admin Console.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="27213-448">ChargeStartDate</span><span class="sxs-lookup"><span data-stu-id="27213-448">ChargeStartDate</span></span></td>
<td><p><span data-ttu-id="27213-449">開始計算費用的日期。</span><span class="sxs-lookup"><span data-stu-id="27213-449">Start day of the charges.</span></span> <span data-ttu-id="27213-450">時間一律是一天的開始時間 (0:00)。</span><span class="sxs-lookup"><span data-stu-id="27213-450">The time is always the beginning of the day, 0:00.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="27213-451">ChargeEndDate</span><span class="sxs-lookup"><span data-stu-id="27213-451">ChargeEndDate</span></span></td>
<td><p><span data-ttu-id="27213-452">結束計算費用的日期。</span><span class="sxs-lookup"><span data-stu-id="27213-452">End day of the charges.</span></span> <span data-ttu-id="27213-453">時間一律是一天的結束時間 (23:59)。</span><span class="sxs-lookup"><span data-stu-id="27213-453">The time is always the end of the day, 23:59.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="27213-454">詞彙和 Billingcycle</span><span class="sxs-lookup"><span data-stu-id="27213-454">Term and Billingcycle</span></span></td>
<td><p><span data-ttu-id="27213-455">約定期和購買計費週期。</span><span class="sxs-lookup"><span data-stu-id="27213-455">The term length and billing cycle for the purchase.</span></span> <span data-ttu-id="27213-456">比方說，「 1 年，每個月。 」</span><span class="sxs-lookup"><span data-stu-id="27213-456">For example, “1 Year, Monthly.”</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="27213-457">收費類型</span><span class="sxs-lookup"><span data-stu-id="27213-457">Charge Type</span></span></td>
<td><p><span data-ttu-id="27213-458">費用或調整的類型。</span><span class="sxs-lookup"><span data-stu-id="27213-458">The type of charge or adjustment.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="27213-459">單價</span><span class="sxs-lookup"><span data-stu-id="27213-459">Unit Price</span></span></td>
<td><p><span data-ttu-id="27213-460">價格為 pricelist 中發行當時的購買。</span><span class="sxs-lookup"><span data-stu-id="27213-460">The price as published in the pricelist at the time of purchase.</span></span> <span data-ttu-id="27213-461">請確定這與對帳期間儲存在您帳單系統中的資訊相符。</span><span class="sxs-lookup"><span data-stu-id="27213-461">Ensure this matches the information stored in your billing system during reconciliation.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="27213-462">有效的單位價格</span><span class="sxs-lookup"><span data-stu-id="27213-462">Effective Unit Price</span></span></td>
<td><p><span data-ttu-id="27213-463">單價後調整。</span><span class="sxs-lookup"><span data-stu-id="27213-463">The unit price after adjustments have been made.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="27213-464">數量</span><span class="sxs-lookup"><span data-stu-id="27213-464">Quantity</span></span></td>
<td><p><span data-ttu-id="27213-465">單位數。</span><span class="sxs-lookup"><span data-stu-id="27213-465">Number of units.</span></span> <span data-ttu-id="27213-466">請確定這與對帳期間儲存在您帳單系統中的資訊相符。</span><span class="sxs-lookup"><span data-stu-id="27213-466">Ensure this matches the information stored in your billing system during reconciliation.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="27213-467">單位類型</span><span class="sxs-lookup"><span data-stu-id="27213-467">Unit type</span></span></td>
<td><p><span data-ttu-id="27213-468">正在購買的單位類型。</span><span class="sxs-lookup"><span data-stu-id="27213-468">The type of unit being purchased.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="27213-469">DiscountDetails</span><span class="sxs-lookup"><span data-stu-id="27213-469">DiscountDetails</span></span></td>
<td><p><span data-ttu-id="27213-470">說明的任何適用的折扣。</span><span class="sxs-lookup"><span data-stu-id="27213-470">An explanation of any applicable discount.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="27213-471">Sub Total</span><span class="sxs-lookup"><span data-stu-id="27213-471">Sub Total</span></span></td>
<td><p><span data-ttu-id="27213-472">稅前總計。</span><span class="sxs-lookup"><span data-stu-id="27213-472">Total before tax.</span></span> <span data-ttu-id="27213-473">如果有折扣，可檢查小計是否和預期的總金額相符。</span><span class="sxs-lookup"><span data-stu-id="27213-473">Checks that your subtotal matches your expected total, in case of a discount.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="27213-474">稅額總計</span><span class="sxs-lookup"><span data-stu-id="27213-474">Tax Total</span></span></td>
<td><p><span data-ttu-id="27213-475">稅金費用 (根據您所在市場的稅金規則與特定情況)。</span><span class="sxs-lookup"><span data-stu-id="27213-475">Tax amount charge, based on your market's tax rules and specific circumstances.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="27213-476">總計</span><span class="sxs-lookup"><span data-stu-id="27213-476">Total</span></span></td>
<td><p><span data-ttu-id="27213-477">稅後總計。</span><span class="sxs-lookup"><span data-stu-id="27213-477">Total after tax.</span></span> <span data-ttu-id="27213-478">檢查發票中是否向您收取稅金。</span><span class="sxs-lookup"><span data-stu-id="27213-478">Checks if you are charged tax in the invoice.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="27213-479">貨幣</span><span class="sxs-lookup"><span data-stu-id="27213-479">Currency</span></span></td>
<td><p><span data-ttu-id="27213-480">貨幣類型。</span><span class="sxs-lookup"><span data-stu-id="27213-480">Currency type.</span></span> <span data-ttu-id="27213-481">每一帳單實體都只有一種貨幣。</span><span class="sxs-lookup"><span data-stu-id="27213-481">Each billing entity has only one currency.</span></span> <span data-ttu-id="27213-482">檢查是否與您的第一張發票相符，然後在進行任何重大帳單平台更新之後檢查。</span><span class="sxs-lookup"><span data-stu-id="27213-482">Check that it matches your first invoice and then after any major billing platform update.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="27213-483">AlternateID</span><span class="sxs-lookup"><span data-stu-id="27213-483">AlternateID</span></span></td>
<td><p><span data-ttu-id="27213-484">替代識別碼至單識別碼。</span><span class="sxs-lookup"><span data-stu-id="27213-484">An alternate identifier to an order ID.</span></span></p></td>
</tr>
</tbody>
</table>


## <a href="" id="dailyratedusagefields"></a><span data-ttu-id="27213-485">每日按比例計算的使用方式檔案欄位</span><span class="sxs-lookup"><span data-stu-id="27213-485">Daily-rated usage file fields</span></span>


<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th><span data-ttu-id="27213-486">Column</span><span class="sxs-lookup"><span data-stu-id="27213-486">Column</span></span></th>
<th><span data-ttu-id="27213-487">描述</span><span class="sxs-lookup"><span data-stu-id="27213-487">Description</span></span></th>
</tr>
</thead>
<tbody>

<tr class="odd">
<td><span data-ttu-id="27213-488">PartnerId</span><span class="sxs-lookup"><span data-stu-id="27213-488">PartnerId</span></span></td>
<td><p><span data-ttu-id="27213-489">合作夥伴識別碼 (GUID 格式)。</span><span class="sxs-lookup"><span data-stu-id="27213-489">Partner ID, in GUID format.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="27213-490">PartnerName</span><span class="sxs-lookup"><span data-stu-id="27213-490">PartnerName</span></span></td>
<td><p><span data-ttu-id="27213-491">合作夥伴名稱。</span><span class="sxs-lookup"><span data-stu-id="27213-491">Partner Name.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="27213-492">CustomerId</span><span class="sxs-lookup"><span data-stu-id="27213-492">CustomerId</span></span></td>
<td><p><span data-ttu-id="27213-493">用來識別客戶的唯一 Microsoft ID（GUID 格式）。</span><span class="sxs-lookup"><span data-stu-id="27213-493">Unique Microsoft ID, in GUID format, used to identify the customer.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="27213-494">CustomerCompanyName</span><span class="sxs-lookup"><span data-stu-id="27213-494">CustomerCompanyName</span></span></td>
<td><p><span data-ttu-id="27213-495">合作夥伴中心中回報的客戶組織名稱。</span><span class="sxs-lookup"><span data-stu-id="27213-495">Customer's organization name as reported in Partner Center.</span></span> <span data-ttu-id="27213-496">這在使用您的系統資訊對帳發票時非常重要。</span><span class="sxs-lookup"><span data-stu-id="27213-496">This is very important for reconciling the invoice with your system information.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="27213-497">CustomerDomainName</span><span class="sxs-lookup"><span data-stu-id="27213-497">CustomerDomainName</span></span></td>
<td><p><span data-ttu-id="27213-498">客戶的網域名稱。</span><span class="sxs-lookup"><span data-stu-id="27213-498">The customer’s domain name.</span></span> <span data-ttu-id="27213-499">不適用於目前的活動。</span><span class="sxs-lookup"><span data-stu-id="27213-499">Not available for current activity.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="27213-500">客戶的國家/地區</span><span class="sxs-lookup"><span data-stu-id="27213-500">Customer country</span></span></td>
<td><p><span data-ttu-id="27213-501">客戶所在的國家/地區。</span><span class="sxs-lookup"><span data-stu-id="27213-501">The country in which the customer is located.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="27213-502">MPNID</span><span class="sxs-lookup"><span data-stu-id="27213-502">MPNID</span></span></td>
<td><p><span data-ttu-id="27213-503">雲端解決方案提供者合作夥伴的 MPN 識別碼。</span><span class="sxs-lookup"><span data-stu-id="27213-503">MPN ID of the CSP partner.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="27213-504">轉銷商 MPNID</span><span class="sxs-lookup"><span data-stu-id="27213-504">Reseller MPNID</span></span></td>
<td><p><span data-ttu-id="27213-505">訂閱記錄中的經銷商 MPN 識別碼。</span><span class="sxs-lookup"><span data-stu-id="27213-505">MPN ID of the reseller of record for the subscription.</span></span> <span data-ttu-id="27213-506">不適用於目前的活動。</span><span class="sxs-lookup"><span data-stu-id="27213-506">Not available for current activity.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="27213-507">InvoiceNumber</span><span class="sxs-lookup"><span data-stu-id="27213-507">InvoiceNumber</span></span></td>
<td><p><span data-ttu-id="27213-508">交易的指定位置顯示的發票號碼。</span><span class="sxs-lookup"><span data-stu-id="27213-508">Invoice number where the specified transaction appears.</span></span> <span data-ttu-id="27213-509">不適用於目前的活動。</span><span class="sxs-lookup"><span data-stu-id="27213-509">Not available for current activity.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="27213-510">ProductId</span><span class="sxs-lookup"><span data-stu-id="27213-510">ProductId</span></span></td>
<td><p><span data-ttu-id="27213-511">產品的識別碼。</span><span class="sxs-lookup"><span data-stu-id="27213-511">The ID for the product.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="27213-512">SkuId</span><span class="sxs-lookup"><span data-stu-id="27213-512">SkuId</span></span></td>
<td><p><span data-ttu-id="27213-513">特定 SKU 的識別碼。</span><span class="sxs-lookup"><span data-stu-id="27213-513">The ID for a particular SKU.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="27213-514">AvailabilityId</span><span class="sxs-lookup"><span data-stu-id="27213-514">AvailabilityId</span></span></td>
<td><p><span data-ttu-id="27213-515">特定可用性的識別碼。</span><span class="sxs-lookup"><span data-stu-id="27213-515">The ID for a particular Availability.</span></span> <span data-ttu-id="27213-516">「可用性」是指特定 SKU 是否可供特定的國家/地區、貨幣、行業區段等等購買。</span><span class="sxs-lookup"><span data-stu-id="27213-516">“Availability” refers to whether or not a particular SKU is available for purchase for the given country, currency, industry segment, etc.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="27213-517">SKU 名稱</span><span class="sxs-lookup"><span data-stu-id="27213-517">SKU Name</span></span></td>
<td><p><span data-ttu-id="27213-518">特定 SKU 的標題。</span><span class="sxs-lookup"><span data-stu-id="27213-518">The title for a particular SKU.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="27213-519">PublisherName</span><span class="sxs-lookup"><span data-stu-id="27213-519">PublisherName</span></span></td>
<td><p><span data-ttu-id="27213-520">發行者的名稱。</span><span class="sxs-lookup"><span data-stu-id="27213-520">The name of the publisher.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="27213-521">PublisherID</span><span class="sxs-lookup"><span data-stu-id="27213-521">PublisherID</span></span></td>
<td><p><span data-ttu-id="27213-522">「 發行者 」 的 GUID 格式的識別碼。</span><span class="sxs-lookup"><span data-stu-id="27213-522">The ID of the publisher, in GUID format.</span></span> <span data-ttu-id="27213-523">不適用於目前的活動。</span><span class="sxs-lookup"><span data-stu-id="27213-523">Not available for current activity.</span></span></p></td>
</tr>

<tr class=”even">
<td><span data-ttu-id="27213-524">訂用帳戶描述</span><span class="sxs-lookup"><span data-stu-id="27213-524">Subscription Description</span></span></td>
<td><p><span data-ttu-id="27213-525">客戶購買的服務優惠名稱，如價目表中所定義。</span><span class="sxs-lookup"><span data-stu-id="27213-525">The name of the service offering purchased by the customer, as defined in the price list.</span></span> <span data-ttu-id="27213-526">（這是優惠名稱的相同欄位）。</span><span class="sxs-lookup"><span data-stu-id="27213-526">(This is an identical field to Offer name).</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="27213-527">訂閱識別碼</span><span class="sxs-lookup"><span data-stu-id="27213-527">Subscription ID</span></span></td>
<td><p><span data-ttu-id="27213-528">訂閱在 Microsoft 帳單平台中的唯一識別碼。</span><span class="sxs-lookup"><span data-stu-id="27213-528">Unique identifier for a subscription in the Microsoft billing platform.</span></span> <span data-ttu-id="27213-529">可在連絡支援時方便識別訂閱，但不是用於對帳。</span><span class="sxs-lookup"><span data-stu-id="27213-529">May be useful to identify the subscription when contacting support but not for reconciliation.</span></span> <span data-ttu-id="27213-530">這與合作夥伴管理主控台上的訂閱識別碼不一樣。</span><span class="sxs-lookup"><span data-stu-id="27213-530">This is not the same as the Subscription ID on the Partner Admin Console.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="27213-531">ChargeStartDate</span><span class="sxs-lookup"><span data-stu-id="27213-531">ChargeStartDate</span></span></td>
<td><p><span data-ttu-id="27213-532">計費週期的開始日期，當顯示之前未收取潛在使用量資料費用的日期時除外 (從前一個計費週期開始)。</span><span class="sxs-lookup"><span data-stu-id="27213-532">Start date of billing cycle except when presenting dates of previously uncharged latent usage data (from previous bill cycle).</span></span> <span data-ttu-id="27213-533">時間一律是一天的開始時間 (0:00)。</span><span class="sxs-lookup"><span data-stu-id="27213-533">The time is always the beginning of the day, 0:00.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="27213-534">ChargeEndDate</span><span class="sxs-lookup"><span data-stu-id="27213-534">ChargeEndDate</span></span></td>
<td><p><span data-ttu-id="27213-535">計費週期的結束日期，當顯示之前未收取潛在使用量資料費用的日期時除外 (從前一個計費週期開始)。</span><span class="sxs-lookup"><span data-stu-id="27213-535">End date of billing cycle except when presenting dates of previously uncharged latent usage data (from previous bill cycle).</span></span> <span data-ttu-id="27213-536">時間一律是一天的結束時間 (23:59)。</span><span class="sxs-lookup"><span data-stu-id="27213-536">The time is always the end of the day, 23:59.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="27213-537">使用日期</span><span class="sxs-lookup"><span data-stu-id="27213-537">Usage Date</span></span></td>
<td><p><span data-ttu-id="27213-538">服務使用量的日期。</span><span class="sxs-lookup"><span data-stu-id="27213-538">Date of service usage.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="27213-539">計量類型</span><span class="sxs-lookup"><span data-stu-id="27213-539">Meter Type</span></span></td>
<td><p><span data-ttu-id="27213-540">計量類型。</span><span class="sxs-lookup"><span data-stu-id="27213-540">The type of meter.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="27213-541">計量類別</span><span class="sxs-lookup"><span data-stu-id="27213-541">Meter Category</span></span></td>
<td><p><span data-ttu-id="27213-542">使用最上層服務。</span><span class="sxs-lookup"><span data-stu-id="27213-542">The top-level service for the usage.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="27213-543">計量識別碼</span><span class="sxs-lookup"><span data-stu-id="27213-543">Meter Id</span></span></td>
<td><p><span data-ttu-id="27213-544">使用計量的識別碼。</span><span class="sxs-lookup"><span data-stu-id="27213-544">The ID for the meter being used.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="27213-545">計量子類別</span><span class="sxs-lookup"><span data-stu-id="27213-545">Meter Sub-category</span></span></td>
<td><p><span data-ttu-id="27213-546">可能影響費率的 Azure 服務的型別。</span><span class="sxs-lookup"><span data-stu-id="27213-546">The type of Azure service that can affect the rate.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="27213-547">計量名稱</span><span class="sxs-lookup"><span data-stu-id="27213-547">Meter Name</span></span></td>
<td><p><span data-ttu-id="27213-548">耗用計量的量值單位。</span><span class="sxs-lookup"><span data-stu-id="27213-548">The unit of measure for the meter being consumed.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="27213-549">計量區域</span><span class="sxs-lookup"><span data-stu-id="27213-549">Meter Region</span></span></td>
<td><p><span data-ttu-id="27213-550">此欄可識別適用及填入此項目之服務地區內的資料中心的位置。</span><span class="sxs-lookup"><span data-stu-id="27213-550">This column identifies the location of a data center within the region for services where this is applicable and populated.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="27213-551">單位</span><span class="sxs-lookup"><span data-stu-id="27213-551">Unit</span></span></td>
<td><p><span data-ttu-id="27213-552">資源名稱的單位。</span><span class="sxs-lookup"><span data-stu-id="27213-552">The unit of the resource Name.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="27213-553">取用的數量</span><span class="sxs-lookup"><span data-stu-id="27213-553">Consumed Quantity</span></span></td>
<td><p><span data-ttu-id="27213-554">報表期間耗用的服務量 (小時、GB 等等)</span><span class="sxs-lookup"><span data-stu-id="27213-554">The amount of service consumed (hours, GB, etc.) during the reporting period.</span></span> <span data-ttu-id="27213-555">同時包括先前報表期間任何未計費的使用量。</span><span class="sxs-lookup"><span data-stu-id="27213-555">Also includes any unbilled usage from previous reporting periods.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="27213-556">資源位置</span><span class="sxs-lookup"><span data-stu-id="27213-556">Resource Location</span></span></td>
<td><p><span data-ttu-id="27213-557">正在執行計量資料中心。</span><span class="sxs-lookup"><span data-stu-id="27213-557">The datacenter where the meter is running.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="27213-558">已使用的服務</span><span class="sxs-lookup"><span data-stu-id="27213-558">Consumed Service</span></span></td>
<td><p><span data-ttu-id="27213-559">您所使用的 Azure 平台服務。</span><span class="sxs-lookup"><span data-stu-id="27213-559">The Azure platform service that you used.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="27213-560">資源群組</span><span class="sxs-lookup"><span data-stu-id="27213-560">Resource Group</span></span></td>
<td><p><span data-ttu-id="27213-561">已部署的計量執行所在的資源群組。</span><span class="sxs-lookup"><span data-stu-id="27213-561">The resource group in which the deployed meter is running.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="27213-562">資源 URI</span><span class="sxs-lookup"><span data-stu-id="27213-562">Resource URI</span></span></td>
<td><p><span data-ttu-id="27213-563">正在使用的資源 URI。</span><span class="sxs-lookup"><span data-stu-id="27213-563">The URI of the resource being used.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="27213-564">收費類型</span><span class="sxs-lookup"><span data-stu-id="27213-564">Charge type</span></span></td>
<td><p><span data-ttu-id="27213-565">費用或調整的類型。</span><span class="sxs-lookup"><span data-stu-id="27213-565">The type of charge or adjustment.</span></span> <span data-ttu-id="27213-566">不適用於目前的活動。</span><span class="sxs-lookup"><span data-stu-id="27213-566">Not available for current activity.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="27213-567">單價</span><span class="sxs-lookup"><span data-stu-id="27213-567">Unit price</span></span></td>
<td><p><span data-ttu-id="27213-568">每份授權為 pricelist 中發行當時的購買價格。</span><span class="sxs-lookup"><span data-stu-id="27213-568">Price per license, as published in the pricelist at the time of purchase.</span></span> <span data-ttu-id="27213-569">請確定這與對帳期間儲存在您帳單系統中的資訊相符。</span><span class="sxs-lookup"><span data-stu-id="27213-569">Ensure this matches the information stored in your billing system during reconciliation.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="27213-570">數量</span><span class="sxs-lookup"><span data-stu-id="27213-570">Quantity</span></span></td>
<td><p><span data-ttu-id="27213-571">授權的數目。</span><span class="sxs-lookup"><span data-stu-id="27213-571">Number of licenses.</span></span> <span data-ttu-id="27213-572">請確定這與對帳期間儲存在您帳單系統中的資訊相符。</span><span class="sxs-lookup"><span data-stu-id="27213-572">Ensure this matches the information stored in your billing system during reconciliation.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="27213-573">單位類型</span><span class="sxs-lookup"><span data-stu-id="27213-573">Unit type</span></span></td>
<td><p><span data-ttu-id="27213-574">計量的計費的單位的類型。</span><span class="sxs-lookup"><span data-stu-id="27213-574">The type of unit the meter is charged in.</span></span> <span data-ttu-id="27213-575">不適用於目前的活動。</span><span class="sxs-lookup"><span data-stu-id="27213-575">Not available for current activity.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="27213-576">計費前稅額</span><span class="sxs-lookup"><span data-stu-id="27213-576">Billing pre tax</span></span></td>
<td><p><span data-ttu-id="27213-577">稅前的總金額。</span><span class="sxs-lookup"><span data-stu-id="27213-577">Total amount before taxes.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="27213-578">帳單貨幣</span><span class="sxs-lookup"><span data-stu-id="27213-578">Billing currency</span></span></td>
<td><p><span data-ttu-id="27213-579">客戶的地理區域中的貨幣</span><span class="sxs-lookup"><span data-stu-id="27213-579">The currency in the customer’s geographic region</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="27213-580">定價 pretax 總計</span><span class="sxs-lookup"><span data-stu-id="27213-580">Pricing pretax total</span></span></td>
<td><p><span data-ttu-id="27213-581">定價加入稅金之前。</span><span class="sxs-lookup"><span data-stu-id="27213-581">The pricing before taxes are added.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="27213-582">價格貨幣</span><span class="sxs-lookup"><span data-stu-id="27213-582">Pricing currency</span></span></td>
<td><p><span data-ttu-id="27213-583">在 pricelist 貨幣。</span><span class="sxs-lookup"><span data-stu-id="27213-583">The currency in the pricelist.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="27213-584">服務資訊 1</span><span class="sxs-lookup"><span data-stu-id="27213-584">Service Info 1</span></span></td>
<td><p><span data-ttu-id="27213-585">於某一天佈建及使用的 ServiceBus 連線數目。</span><span class="sxs-lookup"><span data-stu-id="27213-585">The number of ServiceBus connections that were provisioned and utilized on a given day.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="27213-586">服務資訊 2</span><span class="sxs-lookup"><span data-stu-id="27213-586">Service Info 2</span></span></td>
<td><p><span data-ttu-id="27213-587">舊版欄位，可擷取選擇性服務特定中繼資料。</span><span class="sxs-lookup"><span data-stu-id="27213-587">A legacy field that captures optional service-specific metadata.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="27213-588">Tags</span><span class="sxs-lookup"><span data-stu-id="27213-588">Tags</span></span></td>
<td><p><span data-ttu-id="27213-589">您指派給以順序為帳單記錄分組計量的標籤。</span><span class="sxs-lookup"><span data-stu-id="27213-589">Tags you assign to the meter in order to group billing records.</span></span> <span data-ttu-id="27213-590">例如，您可以使用標記根據使用計量的部門散發成本。</span><span class="sxs-lookup"><span data-stu-id="27213-590">For example, you can use tags to distribute costs by the department that uses the meter.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="27213-591">其他資訊</span><span class="sxs-lookup"><span data-stu-id="27213-591">Additional Info</span></span></td>
<td><p><span data-ttu-id="27213-592">未涵蓋在其他資料行中的任何其他資訊。</span><span class="sxs-lookup"><span data-stu-id="27213-592">Any additional information not covered in other columns.</span></span></p></td>
</tr>

</tbody>
</table>


## <a href="" id="charge_types"></a><span data-ttu-id="27213-593">發票和對帳檔案之間的對應費用</span><span class="sxs-lookup"><span data-stu-id="27213-593">Mapping charges between an invoice and the reconciliation file</span></span>

<span data-ttu-id="27213-594">您的發票提供費用摘要，而對帳檔案則提供包括費用類型等明細項目交易的詳細細項。</span><span class="sxs-lookup"><span data-stu-id="27213-594">Your invoice provides a summary of charges, while your reconciliation file provides a detailed breakdown of line-item transactions, including charge types.</span></span>

<span data-ttu-id="27213-595">若要交互參照發票和對帳檔案之間的費用金額，您可以使用 Microsoft Excel 篩選選項，在對帳檔案上依費用類型篩選，以便將發票費用對應到對帳檔案上的一組費用細項。</span><span class="sxs-lookup"><span data-stu-id="27213-595">To cross-reference charge amounts between the invoice and reconciliation file, you can use Microsoft Excel's filter options to filter by charge types on the reconciliation file to map the invoice charges to a set of charge breakdowns on reconciliation file.</span></span>

<span data-ttu-id="27213-596">用量型和授權型訂閱的對帳檔案只會顯示交易和費用的相關使用量 (耗用單位和相關的費用)。</span><span class="sxs-lookup"><span data-stu-id="27213-596">Reconciliation files, both usage- and license-based, only show usage related transactions and charges (units consumed and related charges).</span></span> <span data-ttu-id="27213-597">發票上顯示為「調整」的點數、折扣或退款不會出現在對帳檔案中。</span><span class="sxs-lookup"><span data-stu-id="27213-597">One off credits, discounts or refunds which appear on the invoice as “Adjustments” are not shown in the reconciliation file.</span></span>

<span data-ttu-id="27213-598">下表顯示發票區段和對帳檔案上可能會顯示之相關費用類型之間的對應。</span><span class="sxs-lookup"><span data-stu-id="27213-598">The table below shows the mappings between an invoice section and associated charge types that might show up on the reconciliation files.</span></span> 

<table>
<tbody>
<tr>
<td>
<p><span data-ttu-id="27213-599"><strong>發票費用的描述</strong></span><span class="sxs-lookup"><span data-stu-id="27213-599"><strong>Invoice charge description</strong></span></span></p>
</td>
<td>
<p><span data-ttu-id="27213-600"><strong>對帳檔案費用描述 （ChargeType 資料行）</strong></span><span class="sxs-lookup"><span data-stu-id="27213-600"><strong>Reconciliation file charge description (ChargeType column)</strong></span></span></p>
</td>
<td>
<p><span data-ttu-id="27213-601"><strong>此費用是什麼？</strong></span><span class="sxs-lookup"><span data-stu-id="27213-601"><strong>What is this charge?</strong></span></span></p>
</td>
<td>
<p><span data-ttu-id="27213-602"><strong>如何將這些 ChargeTypes 對應到發票？</strong></span><span class="sxs-lookup"><span data-stu-id="27213-602"><strong>How do I map these ChargeTypes to the invoice?</strong></span></span></p>
</td>
</tr>
<tr>
<td rowspan="10">
<p><span data-ttu-id="27213-603"><strong>以授權為基礎的費用</strong></span><span class="sxs-lookup"><span data-stu-id="27213-603"><strong>License-based charges</strong></span></span></p>
</td>
<td>
<p><span data-ttu-id="27213-604">啟用費用</span><span class="sxs-lookup"><span data-stu-id="27213-604">Activation fee</span></span></p>
</td>
<td>
<p><span data-ttu-id="27213-605">當客戶購買後使用訂閱時，向客戶收取的金額</span><span class="sxs-lookup"><span data-stu-id="27213-605">The amount charged to the customer when they use the subscription after purchasing it</span></span></p>
</td>
<td rowspan="10">
<p><span data-ttu-id="27213-606">從授權型檔案，加總 <strong>Amount</strong> 欄</span><span class="sxs-lookup"><span data-stu-id="27213-606">From license-based file, sum the <strong>Amount</strong> column</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="27213-607">取消費用</span><span class="sxs-lookup"><span data-stu-id="27213-607">Cancel fee</span></span></p>
</td>
<td>
<p><span data-ttu-id="27213-608">當關聯的基座變更時，按比例計算退款給客戶的費用</span><span class="sxs-lookup"><span data-stu-id="27213-608">Prorated charges refunded to the customer when associated seats are changed</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="27213-609">循環費用</span><span class="sxs-lookup"><span data-stu-id="27213-609">Cycle fee</span></span></p>
</td>
<td>
<p><span data-ttu-id="27213-610">訂閱的定期費用</span><span class="sxs-lookup"><span data-stu-id="27213-610">Periodic charges for a subscription</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="27213-611">循環執行個體 (依比例計算)</span><span class="sxs-lookup"><span data-stu-id="27213-611">Cycle instance prorate</span></span></p>
</td>
<td>
<p><span data-ttu-id="27213-612">當關聯的基座變更時，按比例計算向客戶收取的費用</span><span class="sxs-lookup"><span data-stu-id="27213-612">Prorated charges assessed from the customer when associated seats are changed</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="27213-613">取消時按比例計算費用</span><span class="sxs-lookup"><span data-stu-id="27213-613">Prorate fees when cancel</span></span></p>
</td>
<td>
<p><span data-ttu-id="27213-614">取消時服務未使用部分之按比例計算的退款</span><span class="sxs-lookup"><span data-stu-id="27213-614">Prorated refund for unused portion of service upon cancellation</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="27213-615">購買時按比例計算費用</span><span class="sxs-lookup"><span data-stu-id="27213-615">Prorate fees when purchase</span></span></p>
</td>
<td>
<p><span data-ttu-id="27213-616">當使用年度計費訂用帳戶收費類型</span><span class="sxs-lookup"><span data-stu-id="27213-616">The charge type for a subscription when using annual billing</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="27213-617">購買費用</span><span class="sxs-lookup"><span data-stu-id="27213-617">Purchase fee</span></span></p>
</td>
<td>
<p><span data-ttu-id="27213-618">當使用每月計費訂用帳戶收費類型</span><span class="sxs-lookup"><span data-stu-id="27213-618">The charge type for a subscription when using monthly billing</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="27213-619">續約時按比例計算費用</span><span class="sxs-lookup"><span data-stu-id="27213-619">Prorate fee when renew</span></span></p>
</td>
<td>
<p><span data-ttu-id="27213-620">訂閱續約時按比例計算的費用</span><span class="sxs-lookup"><span data-stu-id="27213-620">Prorated fees upon subscription renewal</span></span></p>
</td>
</tr>
<tr>

<td>
<p><span data-ttu-id="27213-621">續約費用</span><span class="sxs-lookup"><span data-stu-id="27213-621">Renew fee</span></span></p>
</td>
<td>
<p><span data-ttu-id="27213-622">訂閱續約時的費用</span><span class="sxs-lookup"><span data-stu-id="27213-622">Charge for renewing a subscription</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="27213-623">啟用時按比例計算費用</span><span class="sxs-lookup"><span data-stu-id="27213-623">Prorate fees when activate</span></span></p>
</td>
<td>
<p><span data-ttu-id="27213-624">從啟用到計費期間結束時按比例計算的費用</span><span class="sxs-lookup"><span data-stu-id="27213-624">Prorated fees from activation until end of billing period</span></span></p>
</td>
</tr>
<tr>
<td rowspan="2">
<p><span data-ttu-id="27213-625"><strong>使用量費用</strong></span><span class="sxs-lookup"><span data-stu-id="27213-625"><strong>Usage Charges</strong></span></span></p>
</td>
<td>
<p><span data-ttu-id="27213-626">取消時的存取用量費用</span><span class="sxs-lookup"><span data-stu-id="27213-626">Assess usage fee when cancel</span></span></p>
</td>
<td>
<p><span data-ttu-id="27213-627">在目前計費期間中取消時，未支付之使用量的存取用量費用</span><span class="sxs-lookup"><span data-stu-id="27213-627">Access usage fee upon cancellation for unpaid usage during the current billing period</span></span></p>
</td>
<td rowspan="2">
<p><span data-ttu-id="27213-628">從用量型檔案，加總 <strong>PretaxCharges</strong> 欄</span><span class="sxs-lookup"><span data-stu-id="27213-628">From usage-based file, sum the <strong>PretaxCharges</strong> column</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="27213-629">目前週期的存取用量費用</span><span class="sxs-lookup"><span data-stu-id="27213-629">Assess usage fee for current cycle</span></span></p>
</td>
<td>
<p><span data-ttu-id="27213-630">目前計費期間的存取用量費用</span><span class="sxs-lookup"><span data-stu-id="27213-630">Access usage fee for the current billing period</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="27213-631"><strong>信用額度</strong></span><span class="sxs-lookup"><span data-stu-id="27213-631"><strong>Credits</strong></span></span></p>
</td>
<td>
<p><span data-ttu-id="27213-632">明細項目位移</span><span class="sxs-lookup"><span data-stu-id="27213-632">Offset a line item</span></span></p>
</td>
<td>
<p><span data-ttu-id="27213-633">明細項目的部分或完整退款 (含稅)</span><span class="sxs-lookup"><span data-stu-id="27213-633">Partial or whole refund to a line item, including taxes</span></span></p>
</td>
<td>
<p><span data-ttu-id="27213-634">從授權型檔案，加總 <strong>TotalForCustomer</strong> 欄</span><span class="sxs-lookup"><span data-stu-id="27213-634">From license-based file, sum the <strong>TotalForCustomer</strong> column</span></span></p>
<p><span data-ttu-id="27213-635">從用量型檔案，加總 <strong>PostTaxTotal</strong> 欄</span><span class="sxs-lookup"><span data-stu-id="27213-635">From usage-based file, sum the <strong>PostTaxTotal</strong> column</span></span></p>
</td>
</tr>
<tr>
<td rowspan="4">
<p><span data-ttu-id="27213-636"><strong>基於使用方式的折扣</strong></span><span class="sxs-lookup"><span data-stu-id="27213-636"><strong>Usage-based discounts</strong></span></span></p>
</td>
<td>
<p><span data-ttu-id="27213-637">啟用折扣</span><span class="sxs-lookup"><span data-stu-id="27213-637">Activation discount</span></span></p>
</td>
<td>
<p><span data-ttu-id="27213-638">啟用訂閱時套用的折扣</span><span class="sxs-lookup"><span data-stu-id="27213-638">Discount applied when subscription activated</span></span></p>
</td>

<td rowspan="4">
<p><span data-ttu-id="27213-639">從用量型檔案，加總 <strong>PretaxCharges</strong> 欄</span><span class="sxs-lookup"><span data-stu-id="27213-639">From usage-based file, sum the <strong>PretaxCharges</strong> column</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="27213-640">循環折扣</span><span class="sxs-lookup"><span data-stu-id="27213-640">Cycle discount</span></span></p>
</td>
<td>
<p><span data-ttu-id="27213-641">套用至定期費用的折扣</span><span class="sxs-lookup"><span data-stu-id="27213-641">Discount applied on periodic charges</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="27213-642">續約折扣</span><span class="sxs-lookup"><span data-stu-id="27213-642">Renew discount</span></span></p>
</td>
<td>
<p><span data-ttu-id="27213-643">訂閱續約時套用的折扣</span><span class="sxs-lookup"><span data-stu-id="27213-643">Discount applied when subscription renewed</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="27213-644">取消折扣</span><span class="sxs-lookup"><span data-stu-id="27213-644">Cancel discount</span></span></p>
</td>
<td>
<p><span data-ttu-id="27213-645">折扣取消時收取的費用</span><span class="sxs-lookup"><span data-stu-id="27213-645">Charges applied when discounts cancelled</span></span></p>
</td>
</tr>


<tr>
<td>
<p><span data-ttu-id="27213-646"><strong>以授權為基礎的折扣</strong></span><span class="sxs-lookup"><span data-stu-id="27213-646"><strong>License-based discounts</strong></span></span></p>
</td>
<td>
<p><span data-ttu-id="27213-647"><em>可套用至多個收費類型</em></span><span class="sxs-lookup"><span data-stu-id="27213-647"><em>May be applied to multiple charge types</em></span></span></p>
</td>
<td>
<p></p>
</td>
<td>
<p><span data-ttu-id="27213-648">從授權型檔案，加總 <strong>TotalOtherDiscount</strong> 欄</span><span class="sxs-lookup"><span data-stu-id="27213-648">From license-based file, sum the <strong>TotalOtherDiscount</strong> column</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="27213-649"><strong>稅金</strong>&nbsp;或&nbsp;<strong>加值稅</strong></span><span class="sxs-lookup"><span data-stu-id="27213-649"><strong>Taxes</strong>&nbsp;or&nbsp;<strong>VAT</strong></span></span></p>
</td>
<td>
<p><span data-ttu-id="27213-650"><em>可套用至多個收費類型</em></span><span class="sxs-lookup"><span data-stu-id="27213-650"><em>May be applied to multiple charge types</em></span></span></p>
<p><span data-ttu-id="27213-651"><em>例外狀況：&quot;位移明細項目&quot;已經包含稅金。請參閱上面的信用額度。</em></span><span class="sxs-lookup"><span data-stu-id="27213-651"><em>Exception: &quot;Offset a line item&quot; already includes taxes. See Credits, above.</em></span></span></p>
</td>
<td>
<p><span data-ttu-id="27213-652">稅金或加值稅 (VAT)</span><span class="sxs-lookup"><span data-stu-id="27213-652">Taxes or value-added taxes (VAT)</span></span></p>
</td>
<td>
<p><span data-ttu-id="27213-653">從授權型檔案，加總 <strong>Tax</strong> 欄</span><span class="sxs-lookup"><span data-stu-id="27213-653">From license-based file, sum the <strong>Tax</strong> column</span></span></p>
<p><span data-ttu-id="27213-654">從用量型檔案，加總 <strong>TaxAmount</strong> 欄</span><span class="sxs-lookup"><span data-stu-id="27213-654">From usage-based file, sum the <strong>TaxAmount</strong> column</span></span></p>
</td>
</tr>
</tbody>
</table>
<p>&nbsp;</p>
