---
title: "使用對帳檔案 | 合作夥伴中心"
description: "如需計費週期中每項費用的詳細明細項目檢視，請從合作夥伴中心儀表板下載對帳檔案。"
ms.assetid: FA6A6FCB-2597-44E7-93F8-8D1DD35D52EA
author: KPacquer
ms.openlocfilehash: bcb5677d2b1309df0e33e093a3908d55e5792580
ms.sourcegitcommit: ac370f5d2d5b74e1e4752eaeec6fde73e5328225
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 12/15/2017
---
# <a name="use-the-reconciliation-files"></a><span data-ttu-id="32470-103">使用對帳檔案</span><span class="sxs-lookup"><span data-stu-id="32470-103">Use the reconciliation files</span></span>

**<span data-ttu-id="32470-104">適用於</span><span class="sxs-lookup"><span data-stu-id="32470-104">Applies to</span></span>**

-  <span data-ttu-id="32470-105">合作夥伴中心</span><span class="sxs-lookup"><span data-stu-id="32470-105">Partner Center</span></span>
-  <span data-ttu-id="32470-106">美國政府適用的 Microsoft Cloud 合作夥伴中心</span><span class="sxs-lookup"><span data-stu-id="32470-106">Partner Center for Microsoft Cloud for US Government</span></span>
-  <span data-ttu-id="32470-107">Microsoft Cloud 德國合作夥伴中心</span><span class="sxs-lookup"><span data-stu-id="32470-107">Partner Center for Microsoft Cloud Germany</span></span>

<span data-ttu-id="32470-108">如需計費週期中每項費用的詳細明細項目檢視，請從合作夥伴中心儀表板下載對帳檔案。</span><span class="sxs-lookup"><span data-stu-id="32470-108">For a detailed line-item view of each charge in a billing cycle, download the reconciliation files from the Partner Center dashboard.</span></span> <span data-ttu-id="32470-109">詳細資料包括每個客戶的訂閱費用，以及詳細事件 (例如，期中增加訂閱基座)。</span><span class="sxs-lookup"><span data-stu-id="32470-109">The details include charges for each customer's subscriptions, and detailed events (such as a mid-term addition of seats to a subscription).</span></span>

## <a href="" id="itemizebypartner"></a><span data-ttu-id="32470-110">依合作夥伴詳細列舉</span><span class="sxs-lookup"><span data-stu-id="32470-110">Itemize by partner</span></span>


<span data-ttu-id="32470-111">間接模型合作夥伴可以在授權型及用量型對帳檔案中使用這些額外欄位，以便依經銷商詳細列舉。</span><span class="sxs-lookup"><span data-stu-id="32470-111">Partners in the indirect model can use these additional fields in both license-based and usage-based reconciliation files to itemize by reseller.</span></span>

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th><span data-ttu-id="32470-112">MPN 識別碼</span><span class="sxs-lookup"><span data-stu-id="32470-112">MPN ID</span></span></th>
<th><span data-ttu-id="32470-113">描述</span><span class="sxs-lookup"><span data-stu-id="32470-113">Description</span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="32470-114">MPN 識別碼</span><span class="sxs-lookup"><span data-stu-id="32470-114">MPN ID</span></span></td>
<td><p><span data-ttu-id="32470-115">CSP 合作夥伴 (直接或間接) 的 Microsoft 合作夥伴網路 (MPN) 識別碼。</span><span class="sxs-lookup"><span data-stu-id="32470-115">The Microsoft Partner Network (MPN) ID of the CSP partner (direct or indirect).</span></span></p></td>
</tr>
<tr class="even">
<td><span data-ttu-id="32470-116">經銷商 MPN 識別碼</span><span class="sxs-lookup"><span data-stu-id="32470-116">Reseller MPN ID</span></span></td>
<td><p><span data-ttu-id="32470-117">只會出現在間接模型合作夥伴的對帳檔案上。</span><span class="sxs-lookup"><span data-stu-id="32470-117">Only appears on reconciliation files for partners in the indirect model.</span></span></p>
<p><span data-ttu-id="32470-118">訂閱記錄中的經銷商 MPN 識別碼。</span><span class="sxs-lookup"><span data-stu-id="32470-118">The MPN ID of the reseller of record for the subscription.</span></span> <span data-ttu-id="32470-119">這會對應到合作夥伴中心中針對特定訂閱列出的經銷商識別碼。</span><span class="sxs-lookup"><span data-stu-id="32470-119">This corresponds to the reseller ID listed for the specific subscription in Partner Center.</span></span></p>
<p><span data-ttu-id="32470-120">若要檢視或更新經銷商，請在合作夥伴中心功能表中選取 \[客戶\]<strong></strong>，然後從清單中選擇客戶。</span><span class="sxs-lookup"><span data-stu-id="32470-120">eTo view or update the reseller, in the Partner Center menu, select <strong>Customers</strong>, then choose the customer from the list.</span></span> <span data-ttu-id="32470-121">在客戶功能表中，選取 \[訂閱\]<strong></strong>，從清單中選擇訂閱。</span><span class="sxs-lookup"><span data-stu-id="32470-121">In the customer menu, select <strong>Subscriptions</strong>, choose the subscription from the list.</span></span> <span data-ttu-id="32470-122">選取 \[更新\]<strong></strong> 以變更 \[經銷商 (MPN 識別碼)\]<strong></strong>。</span><span class="sxs-lookup"><span data-stu-id="32470-122">Select <strong>update</strong> to change the <strong>Reseller (MPN ID)</strong>.</span></span></p>
<p><span data-ttu-id="32470-123">如果雲端解決方案提供者合作夥伴直接向客戶銷售訂閱，他們的 MPN 識別碼將會以 MPN 識別碼和經銷商 MPN 識別碼的形式列出兩次。</span><span class="sxs-lookup"><span data-stu-id="32470-123">If a CSP partner sold the subscription directly to the customer, their MPN ID is listed twice, as both the MPN ID and the Reseller MPN ID.</span></span></p>
<p><span data-ttu-id="32470-124">如果雲端解決方案提供者合作夥伴具有沒有 MPN 識別碼的經銷商，這個值將會改成設為合作夥伴的 MPN 識別碼。</span><span class="sxs-lookup"><span data-stu-id="32470-124">If a CSP partner has a reseller with no MPN ID, this value is set to the partner’s MPN ID instead.</span></span></p>
<p><span data-ttu-id="32470-125">如果雲端解決方案提供者合作夥伴移除經銷商識別碼，這個值將會設為 -1。</span><span class="sxs-lookup"><span data-stu-id="32470-125">If the CSP partner removes a reseller ID, this value will be set to -1.</span></span></p></td>
</tr>
</tbody>
</table>

 

## <a href="" id="licensebasedfiles"></a><span data-ttu-id="32470-126">授權型檔案欄位</span><span class="sxs-lookup"><span data-stu-id="32470-126">License-based file fields</span></span>


<span data-ttu-id="32470-127">若要針對您對客戶訂單的費用來對帳，請比較對帳檔案中的 Syndication\_Partner\_Subscription\_Number 與合作夥伴中心的訂閱識別碼。</span><span class="sxs-lookup"><span data-stu-id="32470-127">To reconcile your charges against your customer's orders, compare the Syndication\_Partner\_Subscription\_Number from the reconciliation file against the Subscription ID from Partner Center.</span></span>

<table>
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<tbody>
<tr class="odd">
<td><strong><span data-ttu-id="32470-128">欄</span><span class="sxs-lookup"><span data-stu-id="32470-128">Column</span></span></strong></td>
<td><strong><span data-ttu-id="32470-129">描述</span><span class="sxs-lookup"><span data-stu-id="32470-129">Description</span></span></strong></td>
<td><strong><span data-ttu-id="32470-130">範例值</span><span class="sxs-lookup"><span data-stu-id="32470-130">Sample Value</span></span></strong></td>
</tr>
<tr class="even">
<td><span data-ttu-id="32470-131">PartnerId</span><span class="sxs-lookup"><span data-stu-id="32470-131">PartnerId</span></span></td>
<td><p><span data-ttu-id="32470-132">特定帳單實體的唯一識別碼 (GUID 格式)。</span><span class="sxs-lookup"><span data-stu-id="32470-132">Unique identifier for a specific billing entity, in GUID format.</span></span> <span data-ttu-id="32470-133">對帳時不需要，但可能是很有用的資訊。</span><span class="sxs-lookup"><span data-stu-id="32470-133">Not required for reconciliation, however may be useful information.</span></span> <span data-ttu-id="32470-134">在所有資料列中都是如此。</span><span class="sxs-lookup"><span data-stu-id="32470-134">Same in all rows.</span></span></p></td>
<td><span data-ttu-id="32470-135">8ddd03642-test-test-test-46b58d356b4e</span><span class="sxs-lookup"><span data-stu-id="32470-135">8ddd03642-test-test-test-46b58d356b4e</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="32470-136">CustomerID</span><span class="sxs-lookup"><span data-stu-id="32470-136">CustomerID</span></span></td>
<td><p><span data-ttu-id="32470-137">用來識別客戶的唯一 Microsoft ID（GUID 格式）。</span><span class="sxs-lookup"><span data-stu-id="32470-137">Unique Microsoft ID, in GUID format, used to identify the customer.</span></span></p></td>
<td><span data-ttu-id="32470-138">12ABCD34-001A-BCD2-987C-3210ABCD5678</span><span class="sxs-lookup"><span data-stu-id="32470-138">12ABCD34-001A-BCD2-987C-3210ABCD5678</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="32470-139">OrderID</span><span class="sxs-lookup"><span data-stu-id="32470-139">OrderID</span></span></td>
<td><p><span data-ttu-id="32470-140">訂單在 Microsoft 帳單平台中的唯一識別碼。</span><span class="sxs-lookup"><span data-stu-id="32470-140">Unique identifier for an order in the Microsoft billing platform.</span></span> <span data-ttu-id="32470-141">可在連絡支援時方便識別訂單，但不是用於對帳。</span><span class="sxs-lookup"><span data-stu-id="32470-141">May be useful to identify the order when contacting support but not for reconciliation.</span></span></p></td>
<td><span data-ttu-id="32470-142">566890604832738111</span><span class="sxs-lookup"><span data-stu-id="32470-142">566890604832738111</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="32470-143">SubscriptionID</span><span class="sxs-lookup"><span data-stu-id="32470-143">SubscriptionID</span></span></td>
<td><p><span data-ttu-id="32470-144">訂閱在 Microsoft 帳單平台中的唯一識別碼。</span><span class="sxs-lookup"><span data-stu-id="32470-144">Unique identifier for a subscription in the Microsoft billing platform.</span></span> <span data-ttu-id="32470-145">可在連絡支援時方便識別訂閱，但不是用於對帳。</span><span class="sxs-lookup"><span data-stu-id="32470-145">May be useful to identify the subscription when contacting support but not for reconciliation.</span></span></p>
<p><span data-ttu-id="32470-146">這與合作夥伴管理主控台上的訂閱識別碼不一樣。</span><span class="sxs-lookup"><span data-stu-id="32470-146">This is not the same as the Subscription ID on the Partner Admin Console.</span></span> <span data-ttu-id="32470-147">請參閱 Syndication_Partner_Subscription_Number。</span><span class="sxs-lookup"><span data-stu-id="32470-147">Please see Syndication_Partner_Subscription_Number.</span></span></p></td>
<td><span data-ttu-id="32470-148">usCBMgAAAAAAAAIA</span><span class="sxs-lookup"><span data-stu-id="32470-148">usCBMgAAAAAAAAIA</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="32470-149">SyndicationPartnerSubscriptionNumber</span><span class="sxs-lookup"><span data-stu-id="32470-149">SyndicationPartnerSubscriptionNumber</span></span></td>
<td><p><span data-ttu-id="32470-150">訂閱的唯一識別碼。</span><span class="sxs-lookup"><span data-stu-id="32470-150">Unique identifier for subscriptions.</span></span> <span data-ttu-id="32470-151">客戶可針對同一方案擁有多項訂閱，因此這對於對帳檔案分析而言很重要。</span><span class="sxs-lookup"><span data-stu-id="32470-151">A customer can have multiple subscriptions for the same plan, so this is important for reconciliation file analysis.</span></span></p>
<p><span data-ttu-id="32470-152">這個欄位對應到合作夥伴管理主控台中的訂閱識別碼。</span><span class="sxs-lookup"><span data-stu-id="32470-152">This field maps to the Subscription ID in the Partner Admin Console.</span></span></p></td>
<td><span data-ttu-id="32470-153">fb977ab5-test-test-test-24c8d9591708</span><span class="sxs-lookup"><span data-stu-id="32470-153">fb977ab5-test-test-test-24c8d9591708</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="32470-154">OfferID</span><span class="sxs-lookup"><span data-stu-id="32470-154">OfferID</span></span></td>
<td><p><span data-ttu-id="32470-155">唯一的優惠識別碼。</span><span class="sxs-lookup"><span data-stu-id="32470-155">Unique offer ID.</span></span> <span data-ttu-id="32470-156">根據價目表的標準優惠識別碼。</span><span class="sxs-lookup"><span data-stu-id="32470-156">Standard offer ID as per price list.</span></span></p>
<p><span data-ttu-id="32470-157"><b>注意</b>：這個值不符合價目表上的優惠識別碼。</span><span class="sxs-lookup"><span data-stu-id="32470-157"><b>Note</b>: This value does not match Offer ID from the price list.</span></span> <span data-ttu-id="32470-158">請參閱下方的 DurableOfferID。</span><span class="sxs-lookup"><span data-stu-id="32470-158">See DurableOfferID below.</span></span></p></td>
<td><span data-ttu-id="32470-159">FE616D64-E9A8-40EF-843F-152E9BBEF3D1</span><span class="sxs-lookup"><span data-stu-id="32470-159">FE616D64-E9A8-40EF-843F-152E9BBEF3D1</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="32470-160">DurableOfferID</span><span class="sxs-lookup"><span data-stu-id="32470-160">DurableOfferID</span></span></td>
<td><p><span data-ttu-id="32470-161">唯一的持續性優惠識別碼，如價目表中所定義。</span><span class="sxs-lookup"><span data-stu-id="32470-161">Unique durable offer ID, as defined in the price list.</span></span></p>
<p><span data-ttu-id="32470-162"><b>注意</b>：這個值符合價目表上的優惠識別碼。</span><span class="sxs-lookup"><span data-stu-id="32470-162"><b>Note</b>: This value matches the Offer ID from the price list.</span></span></p></td>
<td><span data-ttu-id="32470-163">1017D7F3-6D7F-4BFA-BDD8-79BC8F104E0C</span><span class="sxs-lookup"><span data-stu-id="32470-163">1017D7F3-6D7F-4BFA-BDD8-79BC8F104E0C</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="32470-164">OfferName</span><span class="sxs-lookup"><span data-stu-id="32470-164">OfferName</span></span></td>
<td><p><span data-ttu-id="32470-165">客戶購買的服務優惠名稱，如價目表中所定義。</span><span class="sxs-lookup"><span data-stu-id="32470-165">The name of the service offering purchased by the customer, as defined in the price list.</span></span></p></td>
<td><span data-ttu-id="32470-166">Microsoft Office 365 (Plan E3)</span><span class="sxs-lookup"><span data-stu-id="32470-166">Microsoft Office 365 (Plan E3)</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="32470-167">SubscriptionStartDate</span><span class="sxs-lookup"><span data-stu-id="32470-167">SubscriptionStartDate</span></span></td>
<td><p><span data-ttu-id="32470-168">訂閱開始日期設定為送出訂單之後的隔日。</span><span class="sxs-lookup"><span data-stu-id="32470-168">The subscription start date, set to the day after the order is submitted.</span></span> <span data-ttu-id="32470-169">藉由同時查看訂閱開始日期與結束日期，您就可以判斷客戶是否仍在第一年訂閱期內，或下一年的訂閱已續約。</span><span class="sxs-lookup"><span data-stu-id="32470-169">By looking at the subscription start date in conjunction with the end date, you can determine if the customer is still within the first year of the subscription or if the subscription has been renewed for the following year.</span></span></p>
<p><span data-ttu-id="32470-170">時間一律是一天的開始時間 (0:00)。</span><span class="sxs-lookup"><span data-stu-id="32470-170">The time is always the beginning of the day, 0:00.</span></span></p></td>
<td><span data-ttu-id="32470-171">2/1/2015 0:00</span><span class="sxs-lookup"><span data-stu-id="32470-171">2/1/2015 0:00</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="32470-172">SubscriptionEndDate</span><span class="sxs-lookup"><span data-stu-id="32470-172">SubscriptionEndDate</span></span></td>
<td><p><span data-ttu-id="32470-173">訂閱結束日期：開始日期之後的 12 個月 + x 天 (與合作夥伴帳單日期配合) 或自續約日期起 12 個月。</span><span class="sxs-lookup"><span data-stu-id="32470-173">The subscription end date: 12 months + x days after start date (to align with partner billing date) or 12 months from renewal date.</span></span></p>
<p><span data-ttu-id="32470-174">續約時，價格會更新至目前的價目表。</span><span class="sxs-lookup"><span data-stu-id="32470-174">At renewal, prices are updated to the current price list.</span></span> <span data-ttu-id="32470-175">自動續約之前，可能需要與客戶連絡。</span><span class="sxs-lookup"><span data-stu-id="32470-175">Customer communication may be required in advance of automated renewal.</span></span></p>
<p><span data-ttu-id="32470-176">時間一律是一天的開始時間 (0:00)。</span><span class="sxs-lookup"><span data-stu-id="32470-176">The time is always the beginning of the day, 0:00.</span></span></p></td>
<td><span data-ttu-id="32470-177">2/1/2015 0:00</span><span class="sxs-lookup"><span data-stu-id="32470-177">2/1/2015 0:00</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="32470-178">ChargeStartDate</span><span class="sxs-lookup"><span data-stu-id="32470-178">ChargeStartDate</span></span></td>
<td><p><span data-ttu-id="32470-179">開始計算費用的日期。</span><span class="sxs-lookup"><span data-stu-id="32470-179">Start day of the charges.</span></span></p>
<p><span data-ttu-id="32470-180">當客戶變更基座數目時，此數字用於計算每日 (按比例) 的費用。</span><span class="sxs-lookup"><span data-stu-id="32470-180">When a customer changes seat numbers, this number is used to calculate per-day (pro-rata) charges.</span></span></p>
<p><span data-ttu-id="32470-181">時間一律是一天的開始時間 (0:00)。</span><span class="sxs-lookup"><span data-stu-id="32470-181">The time is always the beginning of the day, 0:00.</span></span></p></td>
<td><span data-ttu-id="32470-182">2/1/2015 0:00</span><span class="sxs-lookup"><span data-stu-id="32470-182">2/1/2015 0:00</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="32470-183">ChargeEndDate</span><span class="sxs-lookup"><span data-stu-id="32470-183">ChargeEndDate</span></span></td>
<td><p><span data-ttu-id="32470-184">結束計算費用的日期。</span><span class="sxs-lookup"><span data-stu-id="32470-184">End day of the charges.</span></span></p>
<p><span data-ttu-id="32470-185">當客戶變更基座數目時，此數字用於計算每日 (按比例) 的費用。</span><span class="sxs-lookup"><span data-stu-id="32470-185">When a customer changes seat numbers, this number is used to calculate per-day (pro-rata) charges.</span></span></p>
<p><span data-ttu-id="32470-186">時間一律是一天的結束時間 (23:59)。</span><span class="sxs-lookup"><span data-stu-id="32470-186">The time is always the end of the day, 23:59.</span></span></p></td>
<td><span data-ttu-id="32470-187">2/28/2015 23:59</span><span class="sxs-lookup"><span data-stu-id="32470-187">2/28/2015 23:59</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="32470-188">ChargeType</span><span class="sxs-lookup"><span data-stu-id="32470-188">ChargeType</span></span></td>
<td><p><span data-ttu-id="32470-189">費用或調整的類型。</span><span class="sxs-lookup"><span data-stu-id="32470-189">The type of charge or adjustment.</span></span> <span data-ttu-id="32470-190">請參閱<a href="#charge_types">對應發票和對帳檔案之間的費用</a></span><span class="sxs-lookup"><span data-stu-id="32470-190">See <a href="#charge_types">Mapping charges between an invoice and the reconciliation file</a></span></span></p></td>
<td><p><span data-ttu-id="32470-191">請參閱<a href="#charge_types">對應發票和對帳檔案之間的費用</a></span><span class="sxs-lookup"><span data-stu-id="32470-191">See <a href="#charge_types">Mapping charges between an invoice and the reconciliation file</a></span></span></p></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="32470-192">UnitPrice</span><span class="sxs-lookup"><span data-stu-id="32470-192">UnitPrice</span></span></td>
<td><p><span data-ttu-id="32470-193">每一基座價格，即購買時價目表中所公佈的價格。</span><span class="sxs-lookup"><span data-stu-id="32470-193">Price per seat, as published in the pricelist at the time of purchase.</span></span> <span data-ttu-id="32470-194">請確定這與對帳期間儲存在您帳單系統中的資訊相符。</span><span class="sxs-lookup"><span data-stu-id="32470-194">Ensure this matches the information stored in your billing system during reconciliation.</span></span></p></td>
<td><span data-ttu-id="32470-195">6.82</span><span class="sxs-lookup"><span data-stu-id="32470-195">6.82</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="32470-196">Quantity</span><span class="sxs-lookup"><span data-stu-id="32470-196">Quantity</span></span></td>
<td><p><span data-ttu-id="32470-197">基座數目。</span><span class="sxs-lookup"><span data-stu-id="32470-197">Number of seats.</span></span> <span data-ttu-id="32470-198">請確定這與對帳期間儲存在您帳單系統中的資訊相符。</span><span class="sxs-lookup"><span data-stu-id="32470-198">Ensure this matches the information stored in your billing system during reconciliation.</span></span></p></td>
<td><span data-ttu-id="32470-199">2</span><span class="sxs-lookup"><span data-stu-id="32470-199">2</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="32470-200">Amount</span><span class="sxs-lookup"><span data-stu-id="32470-200">Amount</span></span></td>
<td><p><span data-ttu-id="32470-201">數量總價。</span><span class="sxs-lookup"><span data-stu-id="32470-201">Total of price for quantity.</span></span> <span data-ttu-id="32470-202">檢查計算金額與您用來為客戶計算此項目的方式是否相符時很有用。</span><span class="sxs-lookup"><span data-stu-id="32470-202">Useful to check that the amount calculation matches how you calculate this for your customers.</span></span></p></td>
<td><span data-ttu-id="32470-203">13.32</span><span class="sxs-lookup"><span data-stu-id="32470-203">13.32</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="32470-204">TotalOtherDiscount</span><span class="sxs-lookup"><span data-stu-id="32470-204">TotalOtherDiscount</span></span></td>
<td><p><span data-ttu-id="32470-205">套用至這些費用的折扣金額。</span><span class="sxs-lookup"><span data-stu-id="32470-205">Amount of discount applied to these charges.</span></span> <span data-ttu-id="32470-206">符合獎勵資格之 IUR 或新訂閱的訂單，也將於此欄中包含折扣金額。</span><span class="sxs-lookup"><span data-stu-id="32470-206">IUR or new subscriptions eligible for an incentive will also contain a discount amount in this column.</span></span></p></td>
<td><span data-ttu-id="32470-207">2.32</span><span class="sxs-lookup"><span data-stu-id="32470-207">2.32</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="32470-208">Subtotal</span><span class="sxs-lookup"><span data-stu-id="32470-208">Subtotal</span></span></td>
<td><p><span data-ttu-id="32470-209">稅前總計。</span><span class="sxs-lookup"><span data-stu-id="32470-209">Total before tax.</span></span> <span data-ttu-id="32470-210">如果有折扣，可檢查小計是否和預期的總金額相符。</span><span class="sxs-lookup"><span data-stu-id="32470-210">Checks that your subtotal matches your expected total, in case of a discount.</span></span></p></td>
<td><span data-ttu-id="32470-211">11</span><span class="sxs-lookup"><span data-stu-id="32470-211">11</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="32470-212">Tax</span><span class="sxs-lookup"><span data-stu-id="32470-212">Tax</span></span></td>
<td><p><span data-ttu-id="32470-213">稅金費用 (根據您所在市場的稅金規則與特定情況)。</span><span class="sxs-lookup"><span data-stu-id="32470-213">Tax amount charge, based on your market's tax rules and specific circumstances.</span></span></p></td>
<td><span data-ttu-id="32470-214">0</span><span class="sxs-lookup"><span data-stu-id="32470-214">0</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="32470-215">TotalForCustomer</span><span class="sxs-lookup"><span data-stu-id="32470-215">TotalForCustomer</span></span></td>
<td><p><span data-ttu-id="32470-216">稅後總計。</span><span class="sxs-lookup"><span data-stu-id="32470-216">Total after tax.</span></span> <span data-ttu-id="32470-217">檢查發票中是否向您收取稅金。</span><span class="sxs-lookup"><span data-stu-id="32470-217">Checks if you are charged tax in the invoice.</span></span></p></td>
<td><span data-ttu-id="32470-218">11</span><span class="sxs-lookup"><span data-stu-id="32470-218">11</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="32470-219">Currency</span><span class="sxs-lookup"><span data-stu-id="32470-219">Currency</span></span></td>
<td><p><span data-ttu-id="32470-220">貨幣類型。</span><span class="sxs-lookup"><span data-stu-id="32470-220">Currency type.</span></span> <span data-ttu-id="32470-221">每一帳單實體都只有一種貨幣。</span><span class="sxs-lookup"><span data-stu-id="32470-221">Each billing entity has only one currency.</span></span> <span data-ttu-id="32470-222">檢查是否與您的第一張發票相符，然後在進行任何重大帳單平台更新之後檢查。</span><span class="sxs-lookup"><span data-stu-id="32470-222">Check that it matches your first invoice and then after any major billing platform update.</span></span></p></td>
<td><span data-ttu-id="32470-223">EUR</span><span class="sxs-lookup"><span data-stu-id="32470-223">EUR</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="32470-224">CustomerName</span><span class="sxs-lookup"><span data-stu-id="32470-224">CustomerName</span></span></td>
<td><p><span data-ttu-id="32470-225">合作夥伴中心中回報的客戶組織名稱。</span><span class="sxs-lookup"><span data-stu-id="32470-225">Customer's organization name as reported in Partner Center.</span></span> <span data-ttu-id="32470-226">這在使用您的系統資訊對帳發票時非常重要。</span><span class="sxs-lookup"><span data-stu-id="32470-226">This is very important for reconciling the invoice with your system information.</span></span></p></td>
<td><span data-ttu-id="32470-227">測試客戶 A</span><span class="sxs-lookup"><span data-stu-id="32470-227">Test Customer A</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="32470-228">MPNID</span><span class="sxs-lookup"><span data-stu-id="32470-228">MPNID</span></span></td>
<td><p><span data-ttu-id="32470-229">雲端解決方案提供者合作夥伴的 MPN 識別碼</span><span class="sxs-lookup"><span data-stu-id="32470-229">MPN ID of the CSP partner</span></span></p></td>
<td><span data-ttu-id="32470-230">4390934</span><span class="sxs-lookup"><span data-stu-id="32470-230">4390934</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="32470-231">ResellerMPNID</span><span class="sxs-lookup"><span data-stu-id="32470-231">ResellerMPNID</span></span></td>
<td><p><span data-ttu-id="32470-232">訂閱記錄中的經銷商 MPN 識別碼。</span><span class="sxs-lookup"><span data-stu-id="32470-232">MPN ID of the reseller of record for the subscription.</span></span> <span data-ttu-id="32470-233">請參閱[依合作夥伴詳細列舉](#itemizebypartner)。</span><span class="sxs-lookup"><span data-stu-id="32470-233">See [Itemize by partner](#itemizebypartner).</span></span></p></td>
<td><span data-ttu-id="32470-234">4390934</span><span class="sxs-lookup"><span data-stu-id="32470-234">4390934</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="32470-235">DomainName</span><span class="sxs-lookup"><span data-stu-id="32470-235">DomainName</span></span></td>
<td><p><span data-ttu-id="32470-236">用來協助識別客戶的客戶網域名稱。</span><span class="sxs-lookup"><span data-stu-id="32470-236">Customer's domain name, used to help identify the customer.</span></span></p></td>
<td><span data-ttu-id="32470-237">example.onmicrosoft.com</span><span class="sxs-lookup"><span data-stu-id="32470-237">example.onmicrosoft.com</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="32470-238">SubscriptionName</span><span class="sxs-lookup"><span data-stu-id="32470-238">SubscriptionName</span></span></td>
<td><p><span data-ttu-id="32470-239">訂閱暱稱。</span><span class="sxs-lookup"><span data-stu-id="32470-239">Subscription nickname.</span></span> <span data-ttu-id="32470-240">如果未指定任何暱稱，合作夥伴中心會使用 OfferName。</span><span class="sxs-lookup"><span data-stu-id="32470-240">If no nickname is specified, Partner Center uses the OfferName.</span></span></p></td>
<td><span data-ttu-id="32470-241">PROJECT ONLINE</span><span class="sxs-lookup"><span data-stu-id="32470-241">PROJECT ONLINE</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="32470-242">SubscriptionDescription</span><span class="sxs-lookup"><span data-stu-id="32470-242">SubscriptionDescription</span></span></td>
<td><p><span data-ttu-id="32470-243">客戶購買的服務優惠名稱，如價目表中所定義。</span><span class="sxs-lookup"><span data-stu-id="32470-243">The name of the service offering purchased by the customer, as defined in the price list.</span></span> <span data-ttu-id="32470-244">（這是優惠名稱的相同欄位）。</span><span class="sxs-lookup"><span data-stu-id="32470-244">(This is an identical field to Offer name).</span></span></p></td>
<td><span data-ttu-id="32470-245">PROJECT ONLINE PREMIUM WITHOUT PROJECT CLIENT</span><span class="sxs-lookup"><span data-stu-id="32470-245">PROJECT ONLINE PREMIUM WITHOUT PROJECT CLIENT</span></span></td>
</tr>
</tbody>
</table>


## <a href="" id="usagebasedfiles"></a><span data-ttu-id="32470-246">用量型檔案欄位</span><span class="sxs-lookup"><span data-stu-id="32470-246">Usage-based file fields</span></span>


<span data-ttu-id="32470-247">若要針對您客戶使用量的費用來對帳，請比較對帳檔案中的 ResellerID/ResellerName/ResellerBillableAccount、客戶名稱，與合作夥伴中心的訂閱識別碼。</span><span class="sxs-lookup"><span data-stu-id="32470-247">To reconcile your charges against your customer's usage, compare the ResellerID/ResellerName/ResellerBillableAccount from the reconciliation file, the customer name, and the Subscription ID from Partner Center.</span></span>

<span data-ttu-id="32470-248">下列欄位說明使用哪些服務及費率。</span><span class="sxs-lookup"><span data-stu-id="32470-248">The following fields explain which services were used and the rate.</span></span>

<table>
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<tbody>
<tr class="odd">
<td><strong><span data-ttu-id="32470-249">欄位</span><span class="sxs-lookup"><span data-stu-id="32470-249">Column</span></span></strong></td>
<td><strong><span data-ttu-id="32470-250">描述</span><span class="sxs-lookup"><span data-stu-id="32470-250">Description</span></span></strong></td>
<td><strong><span data-ttu-id="32470-251">範例值</span><span class="sxs-lookup"><span data-stu-id="32470-251">Sample value</span></span></strong></td>
</tr>
<tr class="even">
<td><span data-ttu-id="32470-252">PartnerID</span><span class="sxs-lookup"><span data-stu-id="32470-252">PartnerID</span></span></td>
<td><p><span data-ttu-id="32470-253">合作夥伴識別碼 (GUID 格式)。</span><span class="sxs-lookup"><span data-stu-id="32470-253">Partner ID, in GUID format.</span></span></p></td>
<td><span data-ttu-id="32470-254">DA41BC5F-C52D-4464-8A8D-8C8DCC43503B</span><span class="sxs-lookup"><span data-stu-id="32470-254">DA41BC5F-C52D-4464-8A8D-8C8DCC43503B</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="32470-255">PartnerName</span><span class="sxs-lookup"><span data-stu-id="32470-255">PartnerName</span></span></td>
<td><p><span data-ttu-id="32470-256">合作夥伴名稱。</span><span class="sxs-lookup"><span data-stu-id="32470-256">Partner Name.</span></span></p></td>
<td><span data-ttu-id="32470-257">Acme Incorporated</span><span class="sxs-lookup"><span data-stu-id="32470-257">Acme Incorporated</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="32470-258">PartnerBillableAccountID</span><span class="sxs-lookup"><span data-stu-id="32470-258">PartnerBillableAccountID</span></span></td>
<td><p><span data-ttu-id="32470-259">合作夥伴帳戶識別碼。</span><span class="sxs-lookup"><span data-stu-id="32470-259">Partner Account ID.</span></span></p></td>
<td><span data-ttu-id="32470-260">1010578050</span><span class="sxs-lookup"><span data-stu-id="32470-260">1010578050</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="32470-261">CustomerName</span><span class="sxs-lookup"><span data-stu-id="32470-261">CustomerName</span></span></td>
<td><p><span data-ttu-id="32470-262">合作夥伴中心中回報的客戶組織名稱。</span><span class="sxs-lookup"><span data-stu-id="32470-262">Customer's organization name as reported in Partner Center.</span></span> <span data-ttu-id="32470-263">這在使用您的系統資訊對帳發票時非常重要。</span><span class="sxs-lookup"><span data-stu-id="32470-263">This is very important for reconciling the invoice with your system information.</span></span></p></td>
<td><span data-ttu-id="32470-264">測試客戶 A</span><span class="sxs-lookup"><span data-stu-id="32470-264">Test Customer A</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="32470-265">MPNID</span><span class="sxs-lookup"><span data-stu-id="32470-265">MPNID</span></span></td>
<td><p><span data-ttu-id="32470-266">雲端解決方案提供者合作夥伴的 MPN 識別碼。</span><span class="sxs-lookup"><span data-stu-id="32470-266">MPN ID of the CSP partner.</span></span></p></td>
<td><span data-ttu-id="32470-267">4390934</span><span class="sxs-lookup"><span data-stu-id="32470-267">4390934</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="32470-268">ResellerMPNID</span><span class="sxs-lookup"><span data-stu-id="32470-268">ResellerMPNID</span></span></td>
<td><p><span data-ttu-id="32470-269">訂閱記錄中的經銷商 MPN 識別碼。</span><span class="sxs-lookup"><span data-stu-id="32470-269">MPN ID of the reseller of record for the subscription.</span></span> <span data-ttu-id="32470-270">請參閱[依合作夥伴詳細列舉](#itemizebypartner)。</span><span class="sxs-lookup"><span data-stu-id="32470-270">See [Itemize by partner](#itemizebypartner).</span></span></p></td>
<td><span data-ttu-id="32470-271">4390934</span><span class="sxs-lookup"><span data-stu-id="32470-271">4390934</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="32470-272">InvoiceNumber</span><span class="sxs-lookup"><span data-stu-id="32470-272">InvoiceNumber</span></span></td>
<td><p><span data-ttu-id="32470-273">交易的指定位置顯示的發票號碼。</span><span class="sxs-lookup"><span data-stu-id="32470-273">Invoice number where the specified transaction appears.</span></span></p></td>
<td><span data-ttu-id="32470-274">D020001IVK</span><span class="sxs-lookup"><span data-stu-id="32470-274">D020001IVK</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="32470-275">ChargeStartDate</span><span class="sxs-lookup"><span data-stu-id="32470-275">ChargeStartDate</span></span></td>
<td><p><span data-ttu-id="32470-276">計費週期的開始日期，當顯示之前未收取潛在使用量資料費用的日期時除外 (從前一個計費週期開始)。</span><span class="sxs-lookup"><span data-stu-id="32470-276">Start date of billing cycle except when presenting dates of previously uncharged latent usage data (from previous bill cycle).</span></span></p>
<p><span data-ttu-id="32470-277">時間一律是一天的開始時間 (0:00)。</span><span class="sxs-lookup"><span data-stu-id="32470-277">The time is always the beginning of the day, 0:00.</span></span></p></td>
<td><span data-ttu-id="32470-278">2/1/2014 0:00</span><span class="sxs-lookup"><span data-stu-id="32470-278">2/1/2014 0:00</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="32470-279">ChargeEndDate</span><span class="sxs-lookup"><span data-stu-id="32470-279">ChargeEndDate</span></span></td>
<td><p><span data-ttu-id="32470-280">計費週期的結束日期，當顯示之前未收取潛在使用量資料費用的日期時除外 (從前一個計費週期開始)。</span><span class="sxs-lookup"><span data-stu-id="32470-280">End date of billing cycle except when presenting dates of previously uncharged latent usage data (from previous bill cycle).</span></span></p>
<p><span data-ttu-id="32470-281">時間一律是一天的結束時間 (23:59)。</span><span class="sxs-lookup"><span data-stu-id="32470-281">The time is always the end of the day, 23:59.</span></span></p></td>
<td><span data-ttu-id="32470-282">2/28/2014 23:59</span><span class="sxs-lookup"><span data-stu-id="32470-282">2/28/2014 23:59</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="32470-283">SubscriptionID</span><span class="sxs-lookup"><span data-stu-id="32470-283">SubscriptionID</span></span></td>
<td><p><span data-ttu-id="32470-284">訂閱在 Microsoft 帳單平台中的唯一識別碼。</span><span class="sxs-lookup"><span data-stu-id="32470-284">Unique identifier for a subscription in the Microsoft billing platform.</span></span> <span data-ttu-id="32470-285">可在連絡支援時方便識別訂閱，但不是用於對帳。</span><span class="sxs-lookup"><span data-stu-id="32470-285">May be useful to identify the subscription when contacting support but not for reconciliation.</span></span></p>
<p><span data-ttu-id="32470-286">這與合作夥伴管理主控台上的訂閱識別碼不一樣。</span><span class="sxs-lookup"><span data-stu-id="32470-286">This is not the same as the Subscription ID on the Partner Admin Console.</span></span></p></td>
<td><span data-ttu-id="32470-287">usCBMgAAAAAAAAIA</span><span class="sxs-lookup"><span data-stu-id="32470-287">usCBMgAAAAAAAAIA</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="32470-288">SubscriptionName</span><span class="sxs-lookup"><span data-stu-id="32470-288">SubscriptionName</span></span></td>
<td><p><span data-ttu-id="32470-289">服務優惠的暱稱。</span><span class="sxs-lookup"><span data-stu-id="32470-289">Nickname of the service offering.</span></span></p></td>
<td><span data-ttu-id="32470-290">Microsoft Azure</span><span class="sxs-lookup"><span data-stu-id="32470-290">Microsoft Azure</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="32470-291">SubscriptionDescription</span><span class="sxs-lookup"><span data-stu-id="32470-291">SubscriptionDescription</span></span></td>
<td><p><span data-ttu-id="32470-292">服務優惠的企業營運</span><span class="sxs-lookup"><span data-stu-id="32470-292">Line of business of the service offering</span></span></p></td>
<td><span data-ttu-id="32470-293">Microsoft Azure</span><span class="sxs-lookup"><span data-stu-id="32470-293">Microsoft Azure</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="32470-294">OrderID</span><span class="sxs-lookup"><span data-stu-id="32470-294">OrderID</span></span></td>
<td><p><span data-ttu-id="32470-295">訂單在 Microsoft 帳單平台中的唯一識別碼。</span><span class="sxs-lookup"><span data-stu-id="32470-295">Unique identifier for an order in the Microsoft billing platform.</span></span> <span data-ttu-id="32470-296">可在連絡支援時方便識別訂閱，但不是用於對帳。</span><span class="sxs-lookup"><span data-stu-id="32470-296">May be useful to identify the subscription when contacting support but not for reconciliation.</span></span></p></td>
<td><span data-ttu-id="32470-297">566890604832738111</span><span class="sxs-lookup"><span data-stu-id="32470-297">566890604832738111</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="32470-298">ServiceName</span><span class="sxs-lookup"><span data-stu-id="32470-298">ServiceName</span></span></td>
<td><p><span data-ttu-id="32470-299">要求的 Azure 服務名稱。</span><span class="sxs-lookup"><span data-stu-id="32470-299">The name of the Azure service in question.</span></span></p></td>
<td><span data-ttu-id="32470-300">虛擬機器</span><span class="sxs-lookup"><span data-stu-id="32470-300">VIRTUAL MACHINES</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="32470-301">ServiceType</span><span class="sxs-lookup"><span data-stu-id="32470-301">ServiceType</span></span></td>
<td><p><span data-ttu-id="32470-302">Microsoft Azure 服務的特定類型。</span><span class="sxs-lookup"><span data-stu-id="32470-302">The specific type of Windows Azure service.</span></span></p></td>
<td><ul>
<li><span data-ttu-id="32470-303">服務匯流排 – 個人或套件</span><span class="sxs-lookup"><span data-stu-id="32470-303">Service Bus – Individual or Pack</span></span></li>
<li><span data-ttu-id="32470-304">SQL Azure 資料庫 – Business 或 Web Edition</span><span class="sxs-lookup"><span data-stu-id="32470-304">SQL Azure database – Business or Web Edition</span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="32470-305">ResourceGUID</span><span class="sxs-lookup"><span data-stu-id="32470-305">ResourceGUID</span></span></td>
<td><p><span data-ttu-id="32470-306">所有服務資料與定價結構的特定唯一識別碼。</span><span class="sxs-lookup"><span data-stu-id="32470-306">Specific unique identifier for all the service data and pricing structure.</span></span></p></td>
<td><span data-ttu-id="32470-307">DA41BC5F-C52D-4464-8A8D-8C8DCC43503B</span><span class="sxs-lookup"><span data-stu-id="32470-307">DA41BC5F-C52D-4464-8A8D-8C8DCC43503B</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="32470-308">Resource Name</span><span class="sxs-lookup"><span data-stu-id="32470-308">Resource Name</span></span></td>
<td><p><span data-ttu-id="32470-309">Azure 資源的名稱。</span><span class="sxs-lookup"><span data-stu-id="32470-309">The name of the Azure resource.</span></span></p></td>
<td><ul>
<li><span data-ttu-id="32470-310">資料轉入 (GB)</span><span class="sxs-lookup"><span data-stu-id="32470-310">Data Transfer In (GB)</span></span></li>
<li><span data-ttu-id="32470-311">資料轉出 (GB)</span><span class="sxs-lookup"><span data-stu-id="32470-311">Data Transfer Out (GB)</span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="32470-312">地區</span><span class="sxs-lookup"><span data-stu-id="32470-312">Region</span></span></td>
<td><p><span data-ttu-id="32470-313">使用量適用的地區。</span><span class="sxs-lookup"><span data-stu-id="32470-313">The region the usage applies to.</span></span> <span data-ttu-id="32470-314">主要用來指定資料傳輸速率，費率因地區而異。</span><span class="sxs-lookup"><span data-stu-id="32470-314">Primarily used to assign rates to data transfers, as rates vary by region.</span></span></p></td>
<td><span data-ttu-id="32470-315">亞太地區、歐洲、拉丁美洲、北美洲</span><span class="sxs-lookup"><span data-stu-id="32470-315">Asia Pacific, Europe, Latin America, North America</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="32470-316">SKU</span><span class="sxs-lookup"><span data-stu-id="32470-316">SKU</span></span></td>
<td><p><span data-ttu-id="32470-317">優惠的 MSFT 唯一識別碼</span><span class="sxs-lookup"><span data-stu-id="32470-317">MSFT unique identifier for offer</span></span></p></td>
<td><span data-ttu-id="32470-318">7UD 00001</span><span class="sxs-lookup"><span data-stu-id="32470-318">7UD-00001</span></span></td>
</tr>
<tr class="odd">
<td><p><span data-ttu-id="32470-319">DetailLineItemId</span><span class="sxs-lookup"><span data-stu-id="32470-319">DetailLineItemId</span></span></p></td>
<td><p><span data-ttu-id="32470-320">用於詳細列出指定計費期間中，服務或資源不同費率的識別碼和數量。</span><span class="sxs-lookup"><span data-stu-id="32470-320">An ID and quantity for itemizing the different rates for a service or resource in a given billing period.</span></span> <span data-ttu-id="32470-321">對於 Azure 分層評分，到某個數量的計費單位會有一個評分，之後則有不同評分。</span><span class="sxs-lookup"><span data-stu-id="32470-321">For Azure tiered rating, there may be one rate up to a certain quantity of billable units, then a different rate after that.</span></span></p></td>
<td><span data-ttu-id="32470-322">1</span><span class="sxs-lookup"><span data-stu-id="32470-322">1</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="32470-323">ConsumedQuantity</span><span class="sxs-lookup"><span data-stu-id="32470-323">ConsumedQuantity</span></span></td>
<td><p><span data-ttu-id="32470-324">報表期間耗用的服務量 (小時、GB 等等)</span><span class="sxs-lookup"><span data-stu-id="32470-324">The amount of service consumed (hours, GB, etc.) during the reporting period.</span></span></p>
<p><span data-ttu-id="32470-325">同時包括先前報表期間任何未計費的使用量。</span><span class="sxs-lookup"><span data-stu-id="32470-325">Also includes any unbilled usage from previous reporting periods.</span></span></p></td>
<td><span data-ttu-id="32470-326">11</span><span class="sxs-lookup"><span data-stu-id="32470-326">11</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="32470-327">IncludedQuantity</span><span class="sxs-lookup"><span data-stu-id="32470-327">IncludedQuantity</span></span></td>
<td><p><span data-ttu-id="32470-328">包含在優惠中的單位。</span><span class="sxs-lookup"><span data-stu-id="32470-328">Units included as part of the offer.</span></span> <span data-ttu-id="32470-329">通常不會出現在雲端解決方案提供者中。</span><span class="sxs-lookup"><span data-stu-id="32470-329">Not typically present in CSP.</span></span></p></td>
<td><span data-ttu-id="32470-330">0</span><span class="sxs-lookup"><span data-stu-id="32470-330">0</span></span></td>
</tr>
<tr class="even">
<td><p><span data-ttu-id="32470-331">OverageQuantity</span><span class="sxs-lookup"><span data-stu-id="32470-331">OverageQuantity</span></span></p></td>
<td><p><span data-ttu-id="32470-332">不包含在優惠中的單位，必須由合作夥伴支付。</span><span class="sxs-lookup"><span data-stu-id="32470-332">Units not included as part of the offer, that must be paid for by the partner.</span></span></p>
<p><span data-ttu-id="32470-333">等同於 ConsumedQuantity - IncludedQuantity。</span><span class="sxs-lookup"><span data-stu-id="32470-333">Equal to the ConsumedQuantity - IncludedQuantity.</span></span></p></td>
<td><span data-ttu-id="32470-334">11</span><span class="sxs-lookup"><span data-stu-id="32470-334">11</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="32470-335">ListPrice</span><span class="sxs-lookup"><span data-stu-id="32470-335">ListPrice</span></span></td>
<td><p><span data-ttu-id="32470-336">訂閱開始日期的生效優惠價格。</span><span class="sxs-lookup"><span data-stu-id="32470-336">Offer price in effect at subscription start date.</span></span></p></td>
<td><span data-ttu-id="32470-337">$0.0808</span><span class="sxs-lookup"><span data-stu-id="32470-337">$0.0808</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="32470-338">PretaxCharges</span><span class="sxs-lookup"><span data-stu-id="32470-338">PretaxCharges</span></span></td>
<td><p><span data-ttu-id="32470-339">ListPrist 乘以 OverageQuantity，四捨五入至美分。</span><span class="sxs-lookup"><span data-stu-id="32470-339">ListPrist times OverageQuantity, rounded to the nearest cent.</span></span></p></td>
<td><span data-ttu-id="32470-340">$0.085</span><span class="sxs-lookup"><span data-stu-id="32470-340">$0.085</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="32470-341">TaxAmount</span><span class="sxs-lookup"><span data-stu-id="32470-341">TaxAmount</span></span></td>
<td><p><span data-ttu-id="32470-342">稅金費用 (根據您所在市場的稅金規則與特定情況)。</span><span class="sxs-lookup"><span data-stu-id="32470-342">Tax amount charge, based on your market's tax rules and specific circumstances.</span></span></p></td>
<td><span data-ttu-id="32470-343">$0.08</span><span class="sxs-lookup"><span data-stu-id="32470-343">$0.08</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="32470-344">PostTaxTotal</span><span class="sxs-lookup"><span data-stu-id="32470-344">PostTaxTotal</span></span></td>
<td><p><span data-ttu-id="32470-345">稅後總計 (當適用稅金時)。</span><span class="sxs-lookup"><span data-stu-id="32470-345">Total after tax, when tax is applicable.</span></span></p></td>
<td><span data-ttu-id="32470-346">$0.93</span><span class="sxs-lookup"><span data-stu-id="32470-346">$0.93</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="32470-347">Currency</span><span class="sxs-lookup"><span data-stu-id="32470-347">Currency</span></span></td>
<td><p><span data-ttu-id="32470-348">貨幣類型。</span><span class="sxs-lookup"><span data-stu-id="32470-348">Currency type.</span></span> <span data-ttu-id="32470-349">每一帳單實體都只有一種貨幣。</span><span class="sxs-lookup"><span data-stu-id="32470-349">Each billing entity has only one currency.</span></span> <span data-ttu-id="32470-350">檢查是否與您的第一張發票相符，然後在進行任何重大帳單平台更新之後檢查。</span><span class="sxs-lookup"><span data-stu-id="32470-350">Check that it matches your first invoice and then after any major billing platform update.</span></span></p></td>
<td><span data-ttu-id="32470-351">EUR</span><span class="sxs-lookup"><span data-stu-id="32470-351">EUR</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="32470-352">PretaxEffectiveRate</span><span class="sxs-lookup"><span data-stu-id="32470-352">PretaxEffectiveRate</span></span></td>
<td><p><span data-ttu-id="32470-353">每個單位的稅前價格。</span><span class="sxs-lookup"><span data-stu-id="32470-353">Pretax price per unit.</span></span> <span data-ttu-id="32470-354">等於 PretaxCharges / OverageQuantity, 四捨五入至美分。</span><span class="sxs-lookup"><span data-stu-id="32470-354">Equal to PretaxCharges / OverageQuantity, rounded to the nearest cent.</span></span></p></td>
<td><span data-ttu-id="32470-355">$0.08</span><span class="sxs-lookup"><span data-stu-id="32470-355">$0.08</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="32470-356">PostTaxEffectiveRate</span><span class="sxs-lookup"><span data-stu-id="32470-356">PostTaxEffectiveRate</span></span></td>
<td><p><span data-ttu-id="32470-357">每個單位的稅後價格。</span><span class="sxs-lookup"><span data-stu-id="32470-357">Post tax price per unit.</span></span> <span data-ttu-id="32470-358">等於 PostTaxTotal / OverageQuantity，或 PretaxEffectiveRate + 每單位數量稅率，四捨五入至美分。</span><span class="sxs-lookup"><span data-stu-id="32470-358">Equal to PostTaxTotal / OverageQuantity, or PretaxEffectiveRate + tax rate per unit amoun, rounded to the nearest cent.</span></span></p></td>
<td><span data-ttu-id="32470-359">$0.08</span><span class="sxs-lookup"><span data-stu-id="32470-359">$0.08</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="32470-360">ChargeType</span><span class="sxs-lookup"><span data-stu-id="32470-360">ChargeType</span></span></td>
<td><p><span data-ttu-id="32470-361">費用或調整的類型。</span><span class="sxs-lookup"><span data-stu-id="32470-361">The type of charge or adjustment.</span></span> <span data-ttu-id="32470-362">請參閱<a href="#charge_types">對應發票和對帳檔案之間的費用</a></span><span class="sxs-lookup"><span data-stu-id="32470-362">See <a href="#charge_types">Mapping charges between an invoice and the reconciliation file</a></span></span></p></td>
<td><p><span data-ttu-id="32470-363">請參閱<a href="#charge_types">對應發票和對帳檔案之間的費用</a></span><span class="sxs-lookup"><span data-stu-id="32470-363">See <a href="#charge_types">Mapping charges between an invoice and the reconciliation file</a></span></span></p></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="32470-364">CustomerBillableAccount</span><span class="sxs-lookup"><span data-stu-id="32470-364">CustomerBillableAccount</span></span></td>
<td><p><span data-ttu-id="32470-365">MSFT 帳單平台的唯一帳戶識別碼。</span><span class="sxs-lookup"><span data-stu-id="32470-365">Unique account ID in the MSFT billing platform.</span></span></p></td>
<td><span data-ttu-id="32470-366">1280018095</span><span class="sxs-lookup"><span data-stu-id="32470-366">1280018095</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="32470-367">UsageDate</span><span class="sxs-lookup"><span data-stu-id="32470-367">UsageDate</span></span></td>
<td><p><span data-ttu-id="32470-368">服務部署的日期。</span><span class="sxs-lookup"><span data-stu-id="32470-368">Date of service deployment.</span></span></p></td>
<td><span data-ttu-id="32470-369">2/1/2014 0:00</span><span class="sxs-lookup"><span data-stu-id="32470-369">2/1/2014 0:00</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="32470-370">MeteredRegion</span><span class="sxs-lookup"><span data-stu-id="32470-370">MeteredRegion</span></span></td>
<td><p><span data-ttu-id="32470-371">此欄可識別適用及填入此項目之服務地區內的資料中心的位置。</span><span class="sxs-lookup"><span data-stu-id="32470-371">This column identifies the location of a data center within the region for services where this is applicable and populated.</span></span></p></td>
<td><span data-ttu-id="32470-372">東亞、東南亞、北歐、西歐、美國中北部、美國中南部</span><span class="sxs-lookup"><span data-stu-id="32470-372">East Asia, South East Asia, North Europe, West Europe, North Central US, South Central US</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="32470-373">MeteredService</span><span class="sxs-lookup"><span data-stu-id="32470-373">MeteredService</span></span></td>
<td><p><span data-ttu-id="32470-374">此欄是用來追蹤可能未在 \[服務名稱\] 欄中特別指出的個別 Microsoft Azure 服務。</span><span class="sxs-lookup"><span data-stu-id="32470-374">This column is utilized to track the individual Microsoft Azure service that may not be specifically identified in the Service Name column.</span></span> <span data-ttu-id="32470-375">例如，在 \[服務名稱\] 欄中，資料傳輸是回報為 &quot;Microsoft Azure - 所有服務&quot;。</span><span class="sxs-lookup"><span data-stu-id="32470-375">For example, data transfers are reported as &quot;Microsoft Azure - All Services&quot; in the Service Name column.</span></span> <span data-ttu-id="32470-376">此 MeteredService 欄會指出使用量與哪個特定服務有關。</span><span class="sxs-lookup"><span data-stu-id="32470-376">This MeteredService column will indicate to which specific service the usage pertains.</span></span></p></td>
<td><span data-ttu-id="32470-377">AccessControl、CDN、Compute、Database、ServiceBus、Storage</span><span class="sxs-lookup"><span data-stu-id="32470-377">AccessControl, CDN, Compute, Database, ServiceBus, Storage</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="32470-378">MeteredServiceType</span><span class="sxs-lookup"><span data-stu-id="32470-378">MeteredServiceType</span></span></td>
<td><p><span data-ttu-id="32470-379">進一步釐清超出 MeteredService 欄位提供之層級的個別 Microsoft Azure 服務副標題。</span><span class="sxs-lookup"><span data-stu-id="32470-379">A subheading that further clarifies the individual Microsoft Azure service beyond the level provided by the MeteredService field.</span></span></p></td>
<td><span data-ttu-id="32470-380">外部</span><span class="sxs-lookup"><span data-stu-id="32470-380">EXTERNAL</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="32470-381">Project</span><span class="sxs-lookup"><span data-stu-id="32470-381">Project</span></span></td>
<td><p><span data-ttu-id="32470-382">客戶為其服務執行個體定義的名稱</span><span class="sxs-lookup"><span data-stu-id="32470-382">Customer-defined name for their service instance</span></span></p></td>
<td><span data-ttu-id="32470-383">ORDDC52E52FDEF405786F0642DD0108BE4</span><span class="sxs-lookup"><span data-stu-id="32470-383">ORDDC52E52FDEF405786F0642DD0108BE4</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="32470-384">ServiceInfo</span><span class="sxs-lookup"><span data-stu-id="32470-384">ServiceInfo</span></span></td>
<td><p><span data-ttu-id="32470-385">於某一天佈建及使用的 ServiceBus 連線數目。</span><span class="sxs-lookup"><span data-stu-id="32470-385">The number of ServiceBus connections that were provisioned and utilized on a given day.</span></span></p></td>
<td><span data-ttu-id="32470-386">例如：如果您在有 30 天的月份中有個別佈建的連線時，「服務資訊 1」的讀數會是「1.000000 連線 / 30 天」。</span><span class="sxs-lookup"><span data-stu-id="32470-386">For example: if you had an individually provisioned connection during a 30 day month, Service Info 1 would read “1.000000 Connections / 30 days”.</span></span> <span data-ttu-id="32470-387">如果您佈建 25 組 ServiceBus 連線並在那天使用其中一組，那一天的每日使用量就會指示「25 組連線 / 30 天 - 已使用：1.000000」。</span><span class="sxs-lookup"><span data-stu-id="32470-387">If you had a 25 pack of ServiceBus connections provisioned and you had utilized 1 during that day, your daily usage statement for that day would indicate “25 Connections / 30 Days – Used: 1.000000”.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="32470-388">CustomerID</span><span class="sxs-lookup"><span data-stu-id="32470-388">CustomerID</span></span></td>
<td><p><span data-ttu-id="32470-389">用來識別客戶的唯一 Microsoft ID（GUID 格式）。</span><span class="sxs-lookup"><span data-stu-id="32470-389">Unique Microsoft ID, in GUID format, used to identify the customer.</span></span></p></td>
<td><span data-ttu-id="32470-390">ORDDC52E52FDEF405786F0642DD0108BE4</span><span class="sxs-lookup"><span data-stu-id="32470-390">ORDDC52E52FDEF405786F0642DD0108BE4</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="32470-391">DomainName</span><span class="sxs-lookup"><span data-stu-id="32470-391">DomainName</span></span></td>
<td><p><span data-ttu-id="32470-392">用來協助識別客戶的客戶網域名稱。</span><span class="sxs-lookup"><span data-stu-id="32470-392">Customer's domain name, used to help identify the customer.</span></span></p></td>
<td><span data-ttu-id="32470-393">example.onmicrosoft.com</span><span class="sxs-lookup"><span data-stu-id="32470-393">example.onmicrosoft.com</span></span></td></tr>
</tr>
<tr class="even">
<td><span data-ttu-id="32470-394">Unit</span><span class="sxs-lookup"><span data-stu-id="32470-394">Unit</span></span></td>
<td><p><span data-ttu-id="32470-395">資源名稱的單位</span><span class="sxs-lookup"><span data-stu-id="32470-395">The unit of the resource Name</span></span></p></td>
<td><span data-ttu-id="32470-396">GB 或 HOURS</span><span class="sxs-lookup"><span data-stu-id="32470-396">GB or HOURS</span></span></td>
</tr>
</tbody>
</table>



## <a href="" id="charge_types"></a><span data-ttu-id="32470-397">對應發票和對帳檔案之間的費用</span><span class="sxs-lookup"><span data-stu-id="32470-397">Mapping charges between an invoice and the reconciliation file</span></span>

<span data-ttu-id="32470-398">您的發票提供費用摘要，而對帳檔案則提供包括費用類型等明細項目交易的詳細細項。</span><span class="sxs-lookup"><span data-stu-id="32470-398">Your invoice provides a summary of charges, while your reconciliation file provides a detailed breakdown of line-item transactions, including charge types.</span></span>

<span data-ttu-id="32470-399">若要交互參照發票和對帳檔案之間的費用金額，您可以使用 Microsoft Excel 篩選選項，在對帳檔案上依費用類型篩選，以便將發票費用對應到對帳檔案上的一組費用細項。</span><span class="sxs-lookup"><span data-stu-id="32470-399">To cross-reference charge amounts between the invoice and reconciliation file, you can use Microsoft Excel's filter options to filter by charge types on the reconciliation file to map the invoice charges to a set of charge breakdowns on reconciliation file.</span></span>

<span data-ttu-id="32470-400">用量型和授權型訂閱的對帳檔案只會顯示交易和費用的相關使用量 (耗用單位和相關的費用)。</span><span class="sxs-lookup"><span data-stu-id="32470-400">Reconciliation files, both usage- and license-based, only show usage related transactions and charges (units consumed and related charges).</span></span> <span data-ttu-id="32470-401">發票上顯示為「調整」的點數、折扣或退款不會出現在對帳檔案中。</span><span class="sxs-lookup"><span data-stu-id="32470-401">One off credits, discounts or refunds which appear on the invoice as “Adjustments” are not shown in the reconciliation file.</span></span>

<span data-ttu-id="32470-402">下表顯示發票區段和對帳檔案上可能會顯示之相關費用類型之間的對應。</span><span class="sxs-lookup"><span data-stu-id="32470-402">The table below shows the mappings between an invoice section and associated charge types that might show up on the reconciliation files.</span></span> 

<table>
<tbody>
<tr>
<td>
<p><strong><span data-ttu-id="32470-403">發票費用描述</span><span class="sxs-lookup"><span data-stu-id="32470-403">Invoice charge description</span></span></strong></p>
</td>
<td>
<p><strong><span data-ttu-id="32470-404">對帳檔案費用描述（ChargeType 欄）</span><span class="sxs-lookup"><span data-stu-id="32470-404">Reconciliation file charge description (ChargeType column)</span></span></strong></p>
</td>
<td>
<p><strong><span data-ttu-id="32470-405">這項費用是什麼？</span><span class="sxs-lookup"><span data-stu-id="32470-405">What is this charge?</span></span></strong></p>
</td>
<td>
<p><strong><span data-ttu-id="32470-406">如何將這些 ChargeTypes 對應到發票？</span><span class="sxs-lookup"><span data-stu-id="32470-406">How do I map these ChargeTypes to the invoice?</span></span></strong></p>
</td>
</tr>
<tr>
<td rowspan="8">
<p><strong><span data-ttu-id="32470-407">週期性費用</span><span class="sxs-lookup"><span data-stu-id="32470-407">Recurring Charges</span></span></strong></p>
</td>
<td>
<p><span data-ttu-id="32470-408">啟用費用</span><span class="sxs-lookup"><span data-stu-id="32470-408">Activation fee</span></span></p>
</td>
<td>
<p><span data-ttu-id="32470-409">當客戶購買後使用訂閱時，向客戶收取的金額</span><span class="sxs-lookup"><span data-stu-id="32470-409">The amount charged to the customer when they use the subscription after purchasing it</span></span></p>
</td>
<td rowspan="8">
<p><span data-ttu-id="32470-410">從授權型檔案，加總 <strong>Amount</strong> 欄</span><span class="sxs-lookup"><span data-stu-id="32470-410">From license-based file, sum the <strong>Amount</strong> column</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="32470-411">取消執行個體按比例計算</span><span class="sxs-lookup"><span data-stu-id="32470-411">Cancel instance prorate</span></span></p>
</td>
<td>
<p><span data-ttu-id="32470-412">當關聯的基座變更時，按比例計算退款給客戶的費用</span><span class="sxs-lookup"><span data-stu-id="32470-412">Prorated charges refunded to the customer when associated seats are changed</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="32470-413">循環費用</span><span class="sxs-lookup"><span data-stu-id="32470-413">Cycle fee</span></span></p>
</td>
<td>
<p><span data-ttu-id="32470-414">訂閱的定期費用</span><span class="sxs-lookup"><span data-stu-id="32470-414">Periodic charges for a subscription</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="32470-415">循環執行個體按比例計算</span><span class="sxs-lookup"><span data-stu-id="32470-415">Cycle instance prorate</span></span></p>
</td>
<td>
<p><span data-ttu-id="32470-416">當關聯的基座變更時，按比例計算向客戶收取的費用</span><span class="sxs-lookup"><span data-stu-id="32470-416">Prorated charges assessed from the customer when associated seats are changed</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="32470-417">取消時按比例計算費用</span><span class="sxs-lookup"><span data-stu-id="32470-417">Prorate fees when cancel</span></span></p>
</td>
<td>
<p><span data-ttu-id="32470-418">取消時服務未使用部分之按比例計算的退款</span><span class="sxs-lookup"><span data-stu-id="32470-418">Prorated refund for unused portion of service upon cancellation</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="32470-419">購買時按比例計算費用</span><span class="sxs-lookup"><span data-stu-id="32470-419">Prorate fees when purchase</span></span></p>
</td>
<td>
<p><span data-ttu-id="32470-420">在購買時按比例計算的費用</span><span class="sxs-lookup"><span data-stu-id="32470-420">Prorated fees upon purchase</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="32470-421">購買費用</span><span class="sxs-lookup"><span data-stu-id="32470-421">Purchase fee</span></span></p>
</td>
<td>
<p><span data-ttu-id="32470-422">訂閱的初始費用</span><span class="sxs-lookup"><span data-stu-id="32470-422">Initial charge for a subscription</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="32470-423">續約時按比例計算費用</span><span class="sxs-lookup"><span data-stu-id="32470-423">Prorate fee when renew</span></span></p>
</td>
<td>
<p><span data-ttu-id="32470-424">訂閱續約時按比例計算的費用</span><span class="sxs-lookup"><span data-stu-id="32470-424">Prorated fees upon subscription renewal</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="32470-425">續約費用</span><span class="sxs-lookup"><span data-stu-id="32470-425">Renew fee</span></span></p>
</td>
<td>
<p><span data-ttu-id="32470-426">訂閱續約時的費用</span><span class="sxs-lookup"><span data-stu-id="32470-426">Charge for renewing a subscription</span></span></p>
</td>
</tr>
<tr>
<td>
<p><strong><span data-ttu-id="32470-427">其他產品與服務</span><span class="sxs-lookup"><span data-stu-id="32470-427">Other Products and Services</span></span></strong></p>
</td>
<td>
<p><span data-ttu-id="32470-428">啟用時按比例計算費用</span><span class="sxs-lookup"><span data-stu-id="32470-428">Prorate fees when activate</span></span></p>
</td>
<td>
<p><span data-ttu-id="32470-429">從啟用到計費期間結束時按比例計算的費用</span><span class="sxs-lookup"><span data-stu-id="32470-429">Prorated fees from activation until end of billing period</span></span></p>
</td>
<td>
<p><span data-ttu-id="32470-430">從授權型檔案，加總 <strong>Amount</strong> 欄</span><span class="sxs-lookup"><span data-stu-id="32470-430">From license-based file, sum the <strong>Amount</strong> column</span></span></p>
</td>
</tr>
<tr>
<td rowspan="2">
<p><strong><span data-ttu-id="32470-431">使用量費用</span><span class="sxs-lookup"><span data-stu-id="32470-431">Usage Charges</span></span></strong></p>
</td>
<td>
<p><span data-ttu-id="32470-432">取消時的存取用量費用</span><span class="sxs-lookup"><span data-stu-id="32470-432">Assess usage fee when cancel</span></span></p>
</td>
<td>
<p><span data-ttu-id="32470-433">在目前計費期間中取消時，未支付之使用量的存取用量費用</span><span class="sxs-lookup"><span data-stu-id="32470-433">Access usage fee upon cancellation for unpaid usage during the current billing period</span></span></p>
</td>
<td rowspan="2">
<p><span data-ttu-id="32470-434">從用量型檔案，加總 <strong>PretaxCharges</strong> 欄</span><span class="sxs-lookup"><span data-stu-id="32470-434">From usage-based file, sum the <strong>PretaxCharges</strong> column</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="32470-435">目前週期的存取用量費用</span><span class="sxs-lookup"><span data-stu-id="32470-435">Assess usage fee for current cycle</span></span></p>
</td>
<td>
<p><span data-ttu-id="32470-436">目前計費期間的存取用量費用</span><span class="sxs-lookup"><span data-stu-id="32470-436">Access usage fee for the current billing period</span></span></p>
</td>
</tr>
<tr>
<td>
<p><strong><span data-ttu-id="32470-437">信用 &amp; 調整</span><span class="sxs-lookup"><span data-stu-id="32470-437">Credits &amp; Adjustments</span></span></strong></p>
</td>
<td>
<p><span data-ttu-id="32470-438">明細項目位移</span><span class="sxs-lookup"><span data-stu-id="32470-438">Offset a line item</span></span></p>
</td>
<td>
<p><span data-ttu-id="32470-439">明細項目的部分或完整退款 (含稅)</span><span class="sxs-lookup"><span data-stu-id="32470-439">Partial or whole refund to a line item, including taxes</span></span></p>
</td>
<td>
<p><span data-ttu-id="32470-440">從授權型檔案，加總 <strong>TotalForCustomer</strong> 欄</span><span class="sxs-lookup"><span data-stu-id="32470-440">From license-based file, sum the <strong>TotalForCustomer</strong> column</span></span></p>
<p><span data-ttu-id="32470-441">從用量型檔案，加總 <strong>PostTaxTotal</strong> 欄</span><span class="sxs-lookup"><span data-stu-id="32470-441">From usage-based file, sum the <strong>PostTaxTotal</strong> column</span></span></p>
</td>
</tr>


<tr>
<td rowspan="4">
<p><strong><span data-ttu-id="32470-442">其他折扣</span><span class="sxs-lookup"><span data-stu-id="32470-442">Other Discounts</span></span></strong></br>
<em><span data-ttu-id="32470-443">（用量型）</span><span class="sxs-lookup"><span data-stu-id="32470-443">(usage-based)</span></span></em></p>
</td>
<td>
<p><span data-ttu-id="32470-444">啟用折扣</span><span class="sxs-lookup"><span data-stu-id="32470-444">Activation discount</span></span></p>
</td>
<td>
<p><span data-ttu-id="32470-445">啟用訂閱時套用的折扣</span><span class="sxs-lookup"><span data-stu-id="32470-445">Discount applied when subscription activated</span></span></p>
</td>
<td rowspan="4">
<p><span data-ttu-id="32470-446">從用量型檔案，加總 <strong>PretaxCharges</strong> 欄</span><span class="sxs-lookup"><span data-stu-id="32470-446">From usage-based file, sum the <strong>PretaxCharges</strong> column</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="32470-447">循環折扣</span><span class="sxs-lookup"><span data-stu-id="32470-447">Cycle discount</span></span></p>
</td>
<td>
<p><span data-ttu-id="32470-448">套用至定期費用的折扣</span><span class="sxs-lookup"><span data-stu-id="32470-448">Discount applied on periodic charges</span></span></p>
</td>
</tr><tr>
<td>
<p><span data-ttu-id="32470-449">續約折扣</span><span class="sxs-lookup"><span data-stu-id="32470-449">Renew discount</span></span></p>
</td>
<td>
<p><span data-ttu-id="32470-450">訂閱續約時套用的折扣</span><span class="sxs-lookup"><span data-stu-id="32470-450">Discount applied when subscription renewed</span></span></p>
</td>
</tr><tr>
<td>
<p><span data-ttu-id="32470-451">取消折扣</span><span class="sxs-lookup"><span data-stu-id="32470-451">Cancel discount</span></span></p>
</td>
<td>
<p><span data-ttu-id="32470-452">折扣取消時收取的費用</span><span class="sxs-lookup"><span data-stu-id="32470-452">Charges applied when discounts cancelled</span></span></p>
</td>
</tr>
<tr>
<td>
<p><strong><span data-ttu-id="32470-453">其他折扣</span><span class="sxs-lookup"><span data-stu-id="32470-453">Other Discounts</span></span></strong></br>
<em><span data-ttu-id="32470-454">（授權型）</span><span class="sxs-lookup"><span data-stu-id="32470-454">(license-based)</span></span></em></p>
</td>
<td>
<p><em><span data-ttu-id="32470-455">可套用至多個費用類型</span><span class="sxs-lookup"><span data-stu-id="32470-455">May be applied to multiple charge types</span></span></em></p>
</td>
<td>
<p>&nbsp;</p>
</td>
<td>
<p><span data-ttu-id="32470-456">從授權型檔案，加總 <strong>TotalOtherDiscount</strong> 欄</span><span class="sxs-lookup"><span data-stu-id="32470-456">From license-based file, sum the <strong>TotalOtherDiscount</strong> column</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="32470-457"><strong>稅金</strong>&nbsp;或&nbsp;<strong>加值稅</strong></span><span class="sxs-lookup"><span data-stu-id="32470-457"><strong>Taxes</strong>&nbsp;or&nbsp;<strong>VAT</strong></span></span></p>
</td>
<td>
<p><em><span data-ttu-id="32470-458">可套用至多個費用類型</span><span class="sxs-lookup"><span data-stu-id="32470-458">May be applied to multiple charge types</span></span></em></p>
<p><em><span data-ttu-id="32470-459">例外：「明細項目位移」已含稅。</span><span class="sxs-lookup"><span data-stu-id="32470-459">Exception: "Offset a line item" already includes taxes.</span></span> <span data-ttu-id="32470-460">請參閱上方的＜信用 &amp; 調整＞。</span><span class="sxs-lookup"><span data-stu-id="32470-460">See Credits &amp; Adjustments, above.</span></span></em></p>
</td>
<td>
<p><span data-ttu-id="32470-461">稅金或加值稅 (VAT)</span><span class="sxs-lookup"><span data-stu-id="32470-461">Taxes or value-added taxes (VAT)</span></span></p>
</td>
<td>
<p><span data-ttu-id="32470-462">從授權型檔案，加總 <strong>Tax</strong> 欄</span><span class="sxs-lookup"><span data-stu-id="32470-462">From license-based file, sum the <strong>Tax</strong> column</span></span></p>
<p><span data-ttu-id="32470-463">從用量型檔案，加總 <strong>TaxAmount</strong> 欄</span><span class="sxs-lookup"><span data-stu-id="32470-463">From usage-based file, sum the <strong>TaxAmount</strong> column</span></span></p>
</td>
</tr>
</tbody>
</table>
<p>&nbsp;</p>
