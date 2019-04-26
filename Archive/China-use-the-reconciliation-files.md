---
title: 使用的對帳檔案 （由 21Vianet 運作的合作夥伴中心）
ms.topic: article
ms.date: 10/29/2018
description: 如需計費週期中每項費用的詳細明細項目檢視，請從合作夥伴中心儀表板下載對帳檔案。
ms.assetid: FA6A6FCB-2597-44E7-93F8-8D1DD35D52EA
author: KPacquer
ms.author: kenpacq
ms.openlocfilehash: 30e3b7a7933678c4af079bb86aa1439559387f2b
ms.sourcegitcommit: b1ab80345b4e4af649fb8cc51d96d798e0791ade
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 04/23/2019
ms.locfileid: "62132078"
---
# <a name="use-the-reconciliation-files"></a><span data-ttu-id="8844c-103">使用對帳檔案</span><span class="sxs-lookup"><span data-stu-id="8844c-103">Use the reconciliation files</span></span>

<span data-ttu-id="8844c-104">**適用於**</span><span class="sxs-lookup"><span data-stu-id="8844c-104">**Applies to**</span></span>

-   <span data-ttu-id="8844c-105">由 21Vianet 營運的合作夥伴中心</span><span class="sxs-lookup"><span data-stu-id="8844c-105">Partner Center operated by 21Vianet</span></span>


<span data-ttu-id="8844c-106">如需計費週期中每項費用的詳細明細項目檢視，請從合作夥伴中心儀表板下載對帳檔案。</span><span class="sxs-lookup"><span data-stu-id="8844c-106">For a detailed line-item view of each charge in a billing cycle, download the reconciliation files from the Partner Center dashboard.</span></span> <span data-ttu-id="8844c-107">詳細資料包括每個客戶的訂閱費用，以及詳細事件 (例如，期中增加訂閱基座)。</span><span class="sxs-lookup"><span data-stu-id="8844c-107">The details include charges for each customer's subscriptions, and detailed events (such as a mid-term addition of seats to a subscription).</span></span>

## <a href="" id="itemizebypartner"></a><span data-ttu-id="8844c-108">由合作夥伴條列</span><span class="sxs-lookup"><span data-stu-id="8844c-108">Itemize by partner</span></span>


<span data-ttu-id="8844c-109">間接模型合作夥伴可以在授權型及用量型對帳檔案中使用這些額外欄位，以便依經銷商詳細列舉。</span><span class="sxs-lookup"><span data-stu-id="8844c-109">Partners in the indirect model can use these additional fields in both license-based and usage-based reconciliation files to itemize by reseller.</span></span>

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th><span data-ttu-id="8844c-110">MPN 識別碼</span><span class="sxs-lookup"><span data-stu-id="8844c-110">MPN ID</span></span></th>
<th><span data-ttu-id="8844c-111">描述</span><span class="sxs-lookup"><span data-stu-id="8844c-111">Description</span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="8844c-112">MPN 識別碼</span><span class="sxs-lookup"><span data-stu-id="8844c-112">MPN ID</span></span></td>
<td><p><span data-ttu-id="8844c-113">CSP 合作夥伴 (直接或間接) 的 Microsoft 合作夥伴網路 (MPN) 識別碼。</span><span class="sxs-lookup"><span data-stu-id="8844c-113">The Microsoft Partner Network (MPN) ID of the CSP partner (direct or indirect).</span></span></p></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8844c-114">經銷商 MPN 識別碼</span><span class="sxs-lookup"><span data-stu-id="8844c-114">Reseller MPN ID</span></span></td>
<td><p><span data-ttu-id="8844c-115">只會出現在間接模型合作夥伴的對帳檔案上。</span><span class="sxs-lookup"><span data-stu-id="8844c-115">Only appears on reconciliation files for partners in the indirect model.</span></span></p>
<p><span data-ttu-id="8844c-116">訂閱記錄中的經銷商 MPN 識別碼。</span><span class="sxs-lookup"><span data-stu-id="8844c-116">The MPN ID of the reseller of record for the subscription.</span></span> <span data-ttu-id="8844c-117">這會對應到合作夥伴中心中針對特定訂閱列出的經銷商識別碼。</span><span class="sxs-lookup"><span data-stu-id="8844c-117">This corresponds to the reseller ID listed for the specific subscription in Partner Center.</span></span></p>
<p><span data-ttu-id="8844c-118">若要檢視或更新經銷商，請在合作夥伴中心功能表中選取 \[客戶\]，然後從清單中選擇客戶。</span><span class="sxs-lookup"><span data-stu-id="8844c-118">eTo view or update the reseller, in the Partner Center menu, select <strong>Customers</strong>, then choose the customer from the list.</span></span> <span data-ttu-id="8844c-119">在客戶功能表中，選取 \[訂閱\]，從清單中選擇訂閱。</span><span class="sxs-lookup"><span data-stu-id="8844c-119">In the customer menu, select <strong>Subscriptions</strong>, choose the subscription from the list.</span></span> <span data-ttu-id="8844c-120">選取 \[更新\] 以變更 \[經銷商 (MPN 識別碼)\]。</span><span class="sxs-lookup"><span data-stu-id="8844c-120">Select <strong>update</strong> to change the <strong>Reseller (MPN ID)</strong>.</span></span></p>
<p><span data-ttu-id="8844c-121">如果雲端解決方案提供者合作夥伴直接向客戶銷售訂閱，他們的 MPN 識別碼將會以 MPN 識別碼和經銷商 MPN 識別碼的形式列出兩次。</span><span class="sxs-lookup"><span data-stu-id="8844c-121">If a CSP partner sold the subscription directly to the customer, their MPN ID is listed twice, as both the MPN ID and the Reseller MPN ID.</span></span></p>
<p><span data-ttu-id="8844c-122">如果雲端解決方案提供者合作夥伴具有沒有 MPN 識別碼的經銷商，這個值將會改成設為合作夥伴的 MPN 識別碼。</span><span class="sxs-lookup"><span data-stu-id="8844c-122">If a CSP partner has a reseller with no MPN ID, this value is set to the partner’s MPN ID instead.</span></span></p>
<p><span data-ttu-id="8844c-123">如果雲端解決方案提供者合作夥伴移除經銷商識別碼，這個值將會設為 -1。</span><span class="sxs-lookup"><span data-stu-id="8844c-123">If the CSP partner removes a reseller ID, this value will be set to -1.</span></span></p></td>
</tr>
</tbody>
</table>

 

## <a href="" id="licensebasedfiles"></a> <span data-ttu-id="8844c-124">以授權為基礎的檔案欄位</span><span class="sxs-lookup"><span data-stu-id="8844c-124">License-based file fields</span></span>


<span data-ttu-id="8844c-125">若要針對您對客戶訂單的費用來對帳，請比較對帳檔案中的 Syndication\_Partner\_Subscription\_Number 與合作夥伴中心的訂閱識別碼。</span><span class="sxs-lookup"><span data-stu-id="8844c-125">To reconcile your charges against your customer's orders, compare the Syndication\_Partner\_Subscription\_Number from the reconciliation file against the Subscription ID from Partner Center.</span></span>

<table>
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<tbody>
<tr class="odd">
<td><span data-ttu-id="8844c-126"><strong>資料行</strong></span><span class="sxs-lookup"><span data-stu-id="8844c-126"><strong>Column</strong></span></span></td>
<td><span data-ttu-id="8844c-127"><strong>描述</strong></span><span class="sxs-lookup"><span data-stu-id="8844c-127"><strong>Description</strong></span></span></td>
<td><span data-ttu-id="8844c-128"><strong>範例值</strong></span><span class="sxs-lookup"><span data-stu-id="8844c-128"><strong>Sample Value</strong></span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8844c-129">PartnerId</span><span class="sxs-lookup"><span data-stu-id="8844c-129">PartnerId</span></span></td>
<td><p><span data-ttu-id="8844c-130">特定帳單實體的唯一識別碼 (GUID 格式)。</span><span class="sxs-lookup"><span data-stu-id="8844c-130">Unique identifier for a specific billing entity, in GUID format.</span></span> <span data-ttu-id="8844c-131">對帳時不需要，但可能是很有用的資訊。</span><span class="sxs-lookup"><span data-stu-id="8844c-131">Not required for reconciliation, however may be useful information.</span></span> <span data-ttu-id="8844c-132">在所有資料列中都是如此。</span><span class="sxs-lookup"><span data-stu-id="8844c-132">Same in all rows.</span></span></p></td>
<td><span data-ttu-id="8844c-133">8ddd03642-test-test-test-46b58d356b4e</span><span class="sxs-lookup"><span data-stu-id="8844c-133">8ddd03642-test-test-test-46b58d356b4e</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8844c-134">CustomerID</span><span class="sxs-lookup"><span data-stu-id="8844c-134">CustomerID</span></span></td>
<td><p><span data-ttu-id="8844c-135">用來識別客戶的唯一 Microsoft ID（GUID 格式）。</span><span class="sxs-lookup"><span data-stu-id="8844c-135">Unique Microsoft ID, in GUID format, used to identify the customer.</span></span></p></td>
<td><span data-ttu-id="8844c-136">12ABCD34-001A-BCD2-987C-3210ABCD5678</span><span class="sxs-lookup"><span data-stu-id="8844c-136">12ABCD34-001A-BCD2-987C-3210ABCD5678</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8844c-137">OrderID</span><span class="sxs-lookup"><span data-stu-id="8844c-137">OrderID</span></span></td>
<td><p><span data-ttu-id="8844c-138">訂單在 Microsoft 帳單平台中的唯一識別碼。</span><span class="sxs-lookup"><span data-stu-id="8844c-138">Unique identifier for an order in the Microsoft billing platform.</span></span> <span data-ttu-id="8844c-139">可在連絡支援時方便識別訂單，但不是用於對帳。</span><span class="sxs-lookup"><span data-stu-id="8844c-139">May be useful to identify the order when contacting support but not for reconciliation.</span></span></p></td>
<td><span data-ttu-id="8844c-140">566890604832738111</span><span class="sxs-lookup"><span data-stu-id="8844c-140">566890604832738111</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8844c-141">SubscriptionID</span><span class="sxs-lookup"><span data-stu-id="8844c-141">SubscriptionID</span></span></td>
<td><p><span data-ttu-id="8844c-142">訂閱在 Microsoft 帳單平台中的唯一識別碼。</span><span class="sxs-lookup"><span data-stu-id="8844c-142">Unique identifier for a subscription in the Microsoft billing platform.</span></span> <span data-ttu-id="8844c-143">可在連絡支援時方便識別訂閱，但不是用於對帳。</span><span class="sxs-lookup"><span data-stu-id="8844c-143">May be useful to identify the subscription when contacting support but not for reconciliation.</span></span></p>
<p><span data-ttu-id="8844c-144">這與合作夥伴管理主控台上的訂閱識別碼不一樣。</span><span class="sxs-lookup"><span data-stu-id="8844c-144">This is not the same as the Subscription ID on the Partner Admin Console.</span></span> <span data-ttu-id="8844c-145">請參閱 Syndication_Partner_Subscription_Number。</span><span class="sxs-lookup"><span data-stu-id="8844c-145">Please see Syndication_Partner_Subscription_Number.</span></span></p></td>
<td><span data-ttu-id="8844c-146">usCBMgAAAAAAAAIA</span><span class="sxs-lookup"><span data-stu-id="8844c-146">usCBMgAAAAAAAAIA</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8844c-147">SyndicationPartnerSubscriptionNumber</span><span class="sxs-lookup"><span data-stu-id="8844c-147">SyndicationPartnerSubscriptionNumber</span></span></td>
<td><p><span data-ttu-id="8844c-148">訂閱的唯一識別碼。</span><span class="sxs-lookup"><span data-stu-id="8844c-148">Unique identifier for subscriptions.</span></span> <span data-ttu-id="8844c-149">客戶可針對同一方案擁有多項訂閱，因此這對於對帳檔案分析而言很重要。</span><span class="sxs-lookup"><span data-stu-id="8844c-149">A customer can have multiple subscriptions for the same plan, so this is important for reconciliation file analysis.</span></span></p>
<p><span data-ttu-id="8844c-150">這個欄位對應到合作夥伴管理主控台中的訂閱識別碼。</span><span class="sxs-lookup"><span data-stu-id="8844c-150">This field maps to the Subscription ID in the Partner Admin Console.</span></span></p></td>
<td><span data-ttu-id="8844c-151">fb977ab5-test-test-test-24c8d9591708</span><span class="sxs-lookup"><span data-stu-id="8844c-151">fb977ab5-test-test-test-24c8d9591708</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8844c-152">OfferID</span><span class="sxs-lookup"><span data-stu-id="8844c-152">OfferID</span></span></td>
<td><p><span data-ttu-id="8844c-153">唯一的優惠識別碼。</span><span class="sxs-lookup"><span data-stu-id="8844c-153">Unique offer ID.</span></span> <span data-ttu-id="8844c-154">根據價目表的標準優惠識別碼。</span><span class="sxs-lookup"><span data-stu-id="8844c-154">Standard offer ID as per price list.</span></span></p>
<p><span data-ttu-id="8844c-155"><b>注意</b>：此值不符合優惠識別碼從價格清單。</span><span class="sxs-lookup"><span data-stu-id="8844c-155"><b>Note</b>: This value does not match Offer ID from the price list.</span></span> <span data-ttu-id="8844c-156">請參閱下方的 DurableOfferID。</span><span class="sxs-lookup"><span data-stu-id="8844c-156">See DurableOfferID below.</span></span></p></td>
<td><span data-ttu-id="8844c-157">FE616D64-E9A8-40EF-843F-152E9BBEF3D1</span><span class="sxs-lookup"><span data-stu-id="8844c-157">FE616D64-E9A8-40EF-843F-152E9BBEF3D1</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8844c-158">DurableOfferID</span><span class="sxs-lookup"><span data-stu-id="8844c-158">DurableOfferID</span></span></td>
<td><p><span data-ttu-id="8844c-159">唯一的持續性優惠識別碼，如價目表中所定義。</span><span class="sxs-lookup"><span data-stu-id="8844c-159">Unique durable offer ID, as defined in the price list.</span></span></p>
<p><span data-ttu-id="8844c-160"><b>注意</b>：此值符合優惠識別碼從價格清單。</span><span class="sxs-lookup"><span data-stu-id="8844c-160"><b>Note</b>: This value matches the Offer ID from the price list.</span></span></p></td>
<td><span data-ttu-id="8844c-161">1017D7F3-6D7F-4BFA-BDD8-79BC8F104E0C</span><span class="sxs-lookup"><span data-stu-id="8844c-161">1017D7F3-6D7F-4BFA-BDD8-79BC8F104E0C</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8844c-162">OfferName</span><span class="sxs-lookup"><span data-stu-id="8844c-162">OfferName</span></span></td>
<td><p><span data-ttu-id="8844c-163">客戶購買的服務優惠名稱，如價目表中所定義。</span><span class="sxs-lookup"><span data-stu-id="8844c-163">The name of the service offering purchased by the customer, as defined in the price list.</span></span></p></td>
<td><span data-ttu-id="8844c-164">Microsoft Office 365 (Plan E3)</span><span class="sxs-lookup"><span data-stu-id="8844c-164">Microsoft Office 365 (Plan E3)</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8844c-165">SubscriptionStartDate</span><span class="sxs-lookup"><span data-stu-id="8844c-165">SubscriptionStartDate</span></span></td>
<td><p><span data-ttu-id="8844c-166">訂閱開始日期設定為送出訂單之後的隔日。</span><span class="sxs-lookup"><span data-stu-id="8844c-166">The subscription start date, set to the day after the order is submitted.</span></span> <span data-ttu-id="8844c-167">藉由同時查看訂閱開始日期與結束日期，您就可以判斷客戶是否仍在第一年訂閱期內，或下一年的訂閱已續約。</span><span class="sxs-lookup"><span data-stu-id="8844c-167">By looking at the subscription start date in conjunction with the end date, you can determine if the customer is still within the first year of the subscription or if the subscription has been renewed for the following year.</span></span></p>
<p><span data-ttu-id="8844c-168">時間一律是一天的開始時間 (0:00)。</span><span class="sxs-lookup"><span data-stu-id="8844c-168">The time is always the beginning of the day, 0:00.</span></span></p></td>
<td><span data-ttu-id="8844c-169">2/1/2015 0:00</span><span class="sxs-lookup"><span data-stu-id="8844c-169">2/1/2015 0:00</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8844c-170">SubscriptionEndDate</span><span class="sxs-lookup"><span data-stu-id="8844c-170">SubscriptionEndDate</span></span></td>
<td><p><span data-ttu-id="8844c-171">訂用帳戶結束日期：12 個月 + x 天後 （以配合計費日期的夥伴） 的開始日期或續約日期起的 12 個月。</span><span class="sxs-lookup"><span data-stu-id="8844c-171">The subscription end date: 12 months + x days after start date (to align with partner billing date) or 12 months from renewal date.</span></span></p>
<p><span data-ttu-id="8844c-172">續約時，價格會更新至目前的價目表。</span><span class="sxs-lookup"><span data-stu-id="8844c-172">At renewal, prices are updated to the current price list.</span></span> <span data-ttu-id="8844c-173">自動續約之前，可能需要與客戶連絡。</span><span class="sxs-lookup"><span data-stu-id="8844c-173">Customer communication may be required in advance of automated renewal.</span></span></p>
<p><span data-ttu-id="8844c-174">時間一律是一天的開始時間 (0:00)。</span><span class="sxs-lookup"><span data-stu-id="8844c-174">The time is always the beginning of the day, 0:00.</span></span></p></td>
<td><span data-ttu-id="8844c-175">2/1/2015 0:00</span><span class="sxs-lookup"><span data-stu-id="8844c-175">2/1/2015 0:00</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8844c-176">ChargeStartDate</span><span class="sxs-lookup"><span data-stu-id="8844c-176">ChargeStartDate</span></span></td>
<td><p><span data-ttu-id="8844c-177">開始計算費用的日期。</span><span class="sxs-lookup"><span data-stu-id="8844c-177">Start day of the charges.</span></span></p>
<p><span data-ttu-id="8844c-178">當客戶變更基座數目時，此數字用於計算每日 (按比例) 的費用。</span><span class="sxs-lookup"><span data-stu-id="8844c-178">When a customer changes seat numbers, this number is used to calculate per-day (pro-rata) charges.</span></span></p>
<p><span data-ttu-id="8844c-179">時間一律是一天的開始時間 (0:00)。</span><span class="sxs-lookup"><span data-stu-id="8844c-179">The time is always the beginning of the day, 0:00.</span></span></p></td>
<td><span data-ttu-id="8844c-180">2/1/2015 0:00</span><span class="sxs-lookup"><span data-stu-id="8844c-180">2/1/2015 0:00</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8844c-181">ChargeEndDate</span><span class="sxs-lookup"><span data-stu-id="8844c-181">ChargeEndDate</span></span></td>
<td><p><span data-ttu-id="8844c-182">結束計算費用的日期。</span><span class="sxs-lookup"><span data-stu-id="8844c-182">End day of the charges.</span></span></p>
<p><span data-ttu-id="8844c-183">當客戶變更基座數目時，此數字用於計算每日 (按比例) 的費用。</span><span class="sxs-lookup"><span data-stu-id="8844c-183">When a customer changes seat numbers, this number is used to calculate per-day (pro-rata) charges.</span></span></p>
<p><span data-ttu-id="8844c-184">時間一律是一天的結束時間 (23:59)。</span><span class="sxs-lookup"><span data-stu-id="8844c-184">The time is always the end of the day, 23:59.</span></span></p></td>
<td><span data-ttu-id="8844c-185">2/28/2015 23:59</span><span class="sxs-lookup"><span data-stu-id="8844c-185">2/28/2015 23:59</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8844c-186">ChargeType</span><span class="sxs-lookup"><span data-stu-id="8844c-186">ChargeType</span></span></td>
<td><p><span data-ttu-id="8844c-187">費用或調整的類型。</span><span class="sxs-lookup"><span data-stu-id="8844c-187">The type of charge or adjustment.</span></span> <span data-ttu-id="8844c-188">請參閱<a href="#charge_types">對應發票和對帳檔案之間的費用</a></span><span class="sxs-lookup"><span data-stu-id="8844c-188">See <a href="#charge_types">Mapping charges between an invoice and the reconciliation file</a></span></span></p></td>
<td><p><span data-ttu-id="8844c-189">請參閱<a href="#charge_types">對應發票和對帳檔案之間的費用</a></span><span class="sxs-lookup"><span data-stu-id="8844c-189">See <a href="#charge_types">Mapping charges between an invoice and the reconciliation file</a></span></span></p></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8844c-190">UnitPrice</span><span class="sxs-lookup"><span data-stu-id="8844c-190">UnitPrice</span></span></td>
<td><p><span data-ttu-id="8844c-191">每一基座價格。</span><span class="sxs-lookup"><span data-stu-id="8844c-191">Price per seat.</span></span> <span data-ttu-id="8844c-192">請確定這與對帳期間儲存在您帳單系統中的資訊相符。</span><span class="sxs-lookup"><span data-stu-id="8844c-192">Ensure this matches the information stored in your billing system during reconciliation.</span></span></p></td>
<td><span data-ttu-id="8844c-193">6.82</span><span class="sxs-lookup"><span data-stu-id="8844c-193">6.82</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8844c-194">數量</span><span class="sxs-lookup"><span data-stu-id="8844c-194">Quantity</span></span></td>
<td><p><span data-ttu-id="8844c-195">基座數目。</span><span class="sxs-lookup"><span data-stu-id="8844c-195">Number of seats.</span></span> <span data-ttu-id="8844c-196">請確定這與對帳期間儲存在您帳單系統中的資訊相符。</span><span class="sxs-lookup"><span data-stu-id="8844c-196">Ensure this matches the information stored in your billing system during reconciliation.</span></span></p></td>
<td><span data-ttu-id="8844c-197">2</span><span class="sxs-lookup"><span data-stu-id="8844c-197">2</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8844c-198">數量</span><span class="sxs-lookup"><span data-stu-id="8844c-198">Amount</span></span></td>
<td><p><span data-ttu-id="8844c-199">數量總價。</span><span class="sxs-lookup"><span data-stu-id="8844c-199">Total of price for quantity.</span></span> <span data-ttu-id="8844c-200">檢查計算金額與您用來為客戶計算此項目的方式是否相符時很有用。</span><span class="sxs-lookup"><span data-stu-id="8844c-200">Useful to check that the amount calculation matches how you calculate this for your customers.</span></span></p></td>
<td><span data-ttu-id="8844c-201">13.32</span><span class="sxs-lookup"><span data-stu-id="8844c-201">13.32</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8844c-202">TotalOtherDiscount</span><span class="sxs-lookup"><span data-stu-id="8844c-202">TotalOtherDiscount</span></span></td>
<td><p><span data-ttu-id="8844c-203">套用至這些費用的折扣金額。</span><span class="sxs-lookup"><span data-stu-id="8844c-203">Amount of discount applied to these charges.</span></span> <span data-ttu-id="8844c-204">符合獎勵資格之 IUR 或新訂閱的訂單，也將於此欄中包含折扣金額。</span><span class="sxs-lookup"><span data-stu-id="8844c-204">IUR or new subscriptions eligible for an incentive will also contain a discount amount in this column.</span></span></p></td>
<td><span data-ttu-id="8844c-205">2.32</span><span class="sxs-lookup"><span data-stu-id="8844c-205">2.32</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8844c-206">小計</span><span class="sxs-lookup"><span data-stu-id="8844c-206">Subtotal</span></span></td>
<td><p><span data-ttu-id="8844c-207">稅前總計。</span><span class="sxs-lookup"><span data-stu-id="8844c-207">Total before tax.</span></span> <span data-ttu-id="8844c-208">如果有折扣，可檢查小計是否和預期的總金額相符。</span><span class="sxs-lookup"><span data-stu-id="8844c-208">Checks that your subtotal matches your expected total, in case of a discount.</span></span></p></td>
<td><span data-ttu-id="8844c-209">11</span><span class="sxs-lookup"><span data-stu-id="8844c-209">11</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8844c-210">稅</span><span class="sxs-lookup"><span data-stu-id="8844c-210">Tax</span></span></td>
<td><p><span data-ttu-id="8844c-211">稅金費用 (根據您所在市場的稅金規則與特定情況)。</span><span class="sxs-lookup"><span data-stu-id="8844c-211">Tax amount charge, based on your market's tax rules and specific circumstances.</span></span></p></td>
<td><span data-ttu-id="8844c-212">0</span><span class="sxs-lookup"><span data-stu-id="8844c-212">0</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8844c-213">TotalForCustomer</span><span class="sxs-lookup"><span data-stu-id="8844c-213">TotalForCustomer</span></span></td>
<td><p><span data-ttu-id="8844c-214">稅後總計。</span><span class="sxs-lookup"><span data-stu-id="8844c-214">Total after tax.</span></span> <span data-ttu-id="8844c-215">檢查發票中是否向您收取稅金。</span><span class="sxs-lookup"><span data-stu-id="8844c-215">Checks if you are charged tax in the invoice.</span></span></p></td>
<td><span data-ttu-id="8844c-216">11</span><span class="sxs-lookup"><span data-stu-id="8844c-216">11</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8844c-217">貨幣</span><span class="sxs-lookup"><span data-stu-id="8844c-217">Currency</span></span></td>
<td><p><span data-ttu-id="8844c-218">貨幣類型。</span><span class="sxs-lookup"><span data-stu-id="8844c-218">Currency type.</span></span> <span data-ttu-id="8844c-219">每一帳單實體都只有一種貨幣。</span><span class="sxs-lookup"><span data-stu-id="8844c-219">Each billing entity has only one currency.</span></span> <span data-ttu-id="8844c-220">檢查是否與您的第一張發票相符，然後在進行任何重大帳單平台更新之後檢查。</span><span class="sxs-lookup"><span data-stu-id="8844c-220">Check that it matches your first invoice and then after any major billing platform update.</span></span></p></td>
<td><span data-ttu-id="8844c-221">CNY</span><span class="sxs-lookup"><span data-stu-id="8844c-221">CNY</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8844c-222">CustomerName</span><span class="sxs-lookup"><span data-stu-id="8844c-222">CustomerName</span></span></td>
<td><p><span data-ttu-id="8844c-223">合作夥伴中心中回報的客戶組織名稱。</span><span class="sxs-lookup"><span data-stu-id="8844c-223">Customer's organization name as reported in Partner Center.</span></span> <span data-ttu-id="8844c-224">這在使用您的系統資訊對帳發票時非常重要。</span><span class="sxs-lookup"><span data-stu-id="8844c-224">This is very important for reconciling the invoice with your system information.</span></span></p></td>
<td><span data-ttu-id="8844c-225">測試客戶 A</span><span class="sxs-lookup"><span data-stu-id="8844c-225">Test Customer A</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8844c-226">MPNID</span><span class="sxs-lookup"><span data-stu-id="8844c-226">MPNID</span></span></td>
<td><p><span data-ttu-id="8844c-227">雲端解決方案提供者合作夥伴的 MPN 識別碼</span><span class="sxs-lookup"><span data-stu-id="8844c-227">MPN ID of the CSP partner</span></span></p></td>
<td><span data-ttu-id="8844c-228">4390934</span><span class="sxs-lookup"><span data-stu-id="8844c-228">4390934</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8844c-229">ResellerMPNID</span><span class="sxs-lookup"><span data-stu-id="8844c-229">ResellerMPNID</span></span></td>
<td><p><span data-ttu-id="8844c-230">訂閱記錄中的經銷商 MPN 識別碼。</span><span class="sxs-lookup"><span data-stu-id="8844c-230">MPN ID of the reseller of record for the subscription.</span></span> <span data-ttu-id="8844c-231">請參閱[依合作夥伴詳細列舉](#itemizebypartner)。</span><span class="sxs-lookup"><span data-stu-id="8844c-231">See [Itemize by partner](#itemizebypartner).</span></span></p></td>
<td><span data-ttu-id="8844c-232">4390934</span><span class="sxs-lookup"><span data-stu-id="8844c-232">4390934</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8844c-233">DomainName</span><span class="sxs-lookup"><span data-stu-id="8844c-233">DomainName</span></span></td>
<td><p><span data-ttu-id="8844c-234">用來協助識別客戶的客戶網域名稱。</span><span class="sxs-lookup"><span data-stu-id="8844c-234">Customer's domain name, used to help identify the customer.</span></span></p></td>
<td><span data-ttu-id="8844c-235">example.onmicrosoft.com</span><span class="sxs-lookup"><span data-stu-id="8844c-235">example.onmicrosoft.com</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8844c-236">SubscriptionName</span><span class="sxs-lookup"><span data-stu-id="8844c-236">SubscriptionName</span></span></td>
<td><p><span data-ttu-id="8844c-237">訂閱暱稱。</span><span class="sxs-lookup"><span data-stu-id="8844c-237">Subscription nickname.</span></span> <span data-ttu-id="8844c-238">如果未指定任何暱稱，合作夥伴中心會使用 OfferName。</span><span class="sxs-lookup"><span data-stu-id="8844c-238">If no nickname is specified, Partner Center uses the OfferName.</span></span></p></td>
<td><span data-ttu-id="8844c-239">PROJECT ONLINE</span><span class="sxs-lookup"><span data-stu-id="8844c-239">PROJECT ONLINE</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8844c-240">SubscriptionDescription</span><span class="sxs-lookup"><span data-stu-id="8844c-240">SubscriptionDescription</span></span></td>
<td><p><span data-ttu-id="8844c-241">客戶購買的服務優惠名稱，如價目表中所定義。</span><span class="sxs-lookup"><span data-stu-id="8844c-241">The name of the service offering purchased by the customer, as defined in the price list.</span></span> <span data-ttu-id="8844c-242">（這是優惠名稱的相同欄位）。</span><span class="sxs-lookup"><span data-stu-id="8844c-242">(This is an identical field to Offer name).</span></span></p></td>
<td><span data-ttu-id="8844c-243">PROJECT ONLINE PREMIUM WITHOUT PROJECT CLIENT</span><span class="sxs-lookup"><span data-stu-id="8844c-243">PROJECT ONLINE PREMIUM WITHOUT PROJECT CLIENT</span></span></td>
</tr>
</tbody>
</table>


## <a href="" id="usagebasedfiles"></a><span data-ttu-id="8844c-244">基於使用方式檔案欄位</span><span class="sxs-lookup"><span data-stu-id="8844c-244">Usage-based file fields</span></span>


<span data-ttu-id="8844c-245">若要針對您客戶使用量的費用來對帳，請比較對帳檔案中的 ResellerID/ResellerName/ResellerBillableAccount、客戶名稱，與合作夥伴中心的訂閱識別碼。</span><span class="sxs-lookup"><span data-stu-id="8844c-245">To reconcile your charges against your customer's usage, compare the ResellerID/ResellerName/ResellerBillableAccount from the reconciliation file, the customer name, and the Subscription ID from Partner Center.</span></span>

<span data-ttu-id="8844c-246">下列欄位說明使用哪些服務及費率。</span><span class="sxs-lookup"><span data-stu-id="8844c-246">The following fields explain which services were used and the rate.</span></span>

<table>
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<tbody>
<tr class="odd">
<td><span data-ttu-id="8844c-247"><strong>資料行</strong></span><span class="sxs-lookup"><span data-stu-id="8844c-247"><strong>Column</strong></span></span></td>
<td><span data-ttu-id="8844c-248"><strong>描述</strong></span><span class="sxs-lookup"><span data-stu-id="8844c-248"><strong>Description</strong></span></span></td>
<td><span data-ttu-id="8844c-249"><strong>範例值</strong></span><span class="sxs-lookup"><span data-stu-id="8844c-249"><strong>Sample value</strong></span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8844c-250">PartnerID</span><span class="sxs-lookup"><span data-stu-id="8844c-250">PartnerID</span></span></td>
<td><p><span data-ttu-id="8844c-251">合作夥伴識別碼 (GUID 格式)。</span><span class="sxs-lookup"><span data-stu-id="8844c-251">Partner ID, in GUID format.</span></span></p></td>
<td><span data-ttu-id="8844c-252">DA41BC5F-C52D-4464-8A8D-8C8DCC43503B</span><span class="sxs-lookup"><span data-stu-id="8844c-252">DA41BC5F-C52D-4464-8A8D-8C8DCC43503B</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8844c-253">PartnerName</span><span class="sxs-lookup"><span data-stu-id="8844c-253">PartnerName</span></span></td>
<td><p><span data-ttu-id="8844c-254">合作夥伴名稱。</span><span class="sxs-lookup"><span data-stu-id="8844c-254">Partner Name.</span></span></p></td>
<td><span data-ttu-id="8844c-255">Acme Incorporated</span><span class="sxs-lookup"><span data-stu-id="8844c-255">Acme Incorporated</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8844c-256">PartnerBillableAccountID</span><span class="sxs-lookup"><span data-stu-id="8844c-256">PartnerBillableAccountID</span></span></td>
<td><p><span data-ttu-id="8844c-257">合作夥伴帳戶識別碼。</span><span class="sxs-lookup"><span data-stu-id="8844c-257">Partner Account ID.</span></span></p></td>
<td><span data-ttu-id="8844c-258">1010578050</span><span class="sxs-lookup"><span data-stu-id="8844c-258">1010578050</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8844c-259">CustomerName</span><span class="sxs-lookup"><span data-stu-id="8844c-259">CustomerName</span></span></td>
<td><p><span data-ttu-id="8844c-260">合作夥伴中心中回報的客戶組織名稱。</span><span class="sxs-lookup"><span data-stu-id="8844c-260">Customer's organization name as reported in Partner Center.</span></span> <span data-ttu-id="8844c-261">這在使用您的系統資訊對帳發票時非常重要。</span><span class="sxs-lookup"><span data-stu-id="8844c-261">This is very important for reconciling the invoice with your system information.</span></span></p></td>
<td><span data-ttu-id="8844c-262">測試客戶 A</span><span class="sxs-lookup"><span data-stu-id="8844c-262">Test Customer A</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8844c-263">MPNID</span><span class="sxs-lookup"><span data-stu-id="8844c-263">MPNID</span></span></td>
<td><p><span data-ttu-id="8844c-264">雲端解決方案提供者合作夥伴的 MPN 識別碼。</span><span class="sxs-lookup"><span data-stu-id="8844c-264">MPN ID of the CSP partner.</span></span></p></td>
<td><span data-ttu-id="8844c-265">4390934</span><span class="sxs-lookup"><span data-stu-id="8844c-265">4390934</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8844c-266">ResellerMPNID</span><span class="sxs-lookup"><span data-stu-id="8844c-266">ResellerMPNID</span></span></td>
<td><p><span data-ttu-id="8844c-267">訂閱記錄中的經銷商 MPN 識別碼。</span><span class="sxs-lookup"><span data-stu-id="8844c-267">MPN ID of the reseller of record for the subscription.</span></span> <span data-ttu-id="8844c-268">請參閱[依合作夥伴詳細列舉](#itemizebypartner)。</span><span class="sxs-lookup"><span data-stu-id="8844c-268">See [Itemize by partner](#itemizebypartner).</span></span></p></td>
<td><span data-ttu-id="8844c-269">4390934</span><span class="sxs-lookup"><span data-stu-id="8844c-269">4390934</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8844c-270">InvoiceNumber</span><span class="sxs-lookup"><span data-stu-id="8844c-270">InvoiceNumber</span></span></td>
<td><p><span data-ttu-id="8844c-271">交易的指定位置顯示的發票號碼。</span><span class="sxs-lookup"><span data-stu-id="8844c-271">Invoice number where the specified transaction appears.</span></span></p></td>
<td><span data-ttu-id="8844c-272">D020001IVK</span><span class="sxs-lookup"><span data-stu-id="8844c-272">D020001IVK</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8844c-273">ChargeStartDate</span><span class="sxs-lookup"><span data-stu-id="8844c-273">ChargeStartDate</span></span></td>
<td><p><span data-ttu-id="8844c-274">計費週期的開始日期，當顯示之前未收取潛在使用量資料費用的日期時除外 (從前一個計費週期開始)。</span><span class="sxs-lookup"><span data-stu-id="8844c-274">Start date of billing cycle except when presenting dates of previously uncharged latent usage data (from previous bill cycle).</span></span></p>
<p><span data-ttu-id="8844c-275">時間一律是一天的開始時間 (0:00)。</span><span class="sxs-lookup"><span data-stu-id="8844c-275">The time is always the beginning of the day, 0:00.</span></span></p></td>
<td><span data-ttu-id="8844c-276">2/1/2014 0:00</span><span class="sxs-lookup"><span data-stu-id="8844c-276">2/1/2014 0:00</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8844c-277">ChargeEndDate</span><span class="sxs-lookup"><span data-stu-id="8844c-277">ChargeEndDate</span></span></td>
<td><p><span data-ttu-id="8844c-278">計費週期的結束日期，當顯示之前未收取潛在使用量資料費用的日期時除外 (從前一個計費週期開始)。</span><span class="sxs-lookup"><span data-stu-id="8844c-278">End date of billing cycle except when presenting dates of previously uncharged latent usage data (from previous bill cycle).</span></span></p>
<p><span data-ttu-id="8844c-279">時間一律是一天的結束時間 (23:59)。</span><span class="sxs-lookup"><span data-stu-id="8844c-279">The time is always the end of the day, 23:59.</span></span></p></td>
<td><span data-ttu-id="8844c-280">2/28/2014 23:59</span><span class="sxs-lookup"><span data-stu-id="8844c-280">2/28/2014 23:59</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8844c-281">SubscriptionID</span><span class="sxs-lookup"><span data-stu-id="8844c-281">SubscriptionID</span></span></td>
<td><p><span data-ttu-id="8844c-282">訂閱在 Microsoft 帳單平台中的唯一識別碼。</span><span class="sxs-lookup"><span data-stu-id="8844c-282">Unique identifier for a subscription in the Microsoft billing platform.</span></span> <span data-ttu-id="8844c-283">可在連絡支援時方便識別訂閱，但不是用於對帳。</span><span class="sxs-lookup"><span data-stu-id="8844c-283">May be useful to identify the subscription when contacting support but not for reconciliation.</span></span></p>
<p><span data-ttu-id="8844c-284">這與合作夥伴管理主控台上的訂閱識別碼不一樣。</span><span class="sxs-lookup"><span data-stu-id="8844c-284">This is not the same as the Subscription ID on the Partner Admin Console.</span></span></p></td>
<td><span data-ttu-id="8844c-285">usCBMgAAAAAAAAIA</span><span class="sxs-lookup"><span data-stu-id="8844c-285">usCBMgAAAAAAAAIA</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8844c-286">SubscriptionName</span><span class="sxs-lookup"><span data-stu-id="8844c-286">SubscriptionName</span></span></td>
<td><p><span data-ttu-id="8844c-287">服務優惠的暱稱。</span><span class="sxs-lookup"><span data-stu-id="8844c-287">Nickname of the service offering.</span></span></p></td>
<td><span data-ttu-id="8844c-288">Microsoft Azure</span><span class="sxs-lookup"><span data-stu-id="8844c-288">Microsoft Azure</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8844c-289">SubscriptionDescription</span><span class="sxs-lookup"><span data-stu-id="8844c-289">SubscriptionDescription</span></span></td>
<td><p><span data-ttu-id="8844c-290">服務優惠的企業營運</span><span class="sxs-lookup"><span data-stu-id="8844c-290">Line of business of the service offering</span></span></p></td>
<td><span data-ttu-id="8844c-291">Microsoft Azure</span><span class="sxs-lookup"><span data-stu-id="8844c-291">Microsoft Azure</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8844c-292">OrderID</span><span class="sxs-lookup"><span data-stu-id="8844c-292">OrderID</span></span></td>
<td><p><span data-ttu-id="8844c-293">訂單在 Microsoft 帳單平台中的唯一識別碼。</span><span class="sxs-lookup"><span data-stu-id="8844c-293">Unique identifier for an order in the Microsoft billing platform.</span></span> <span data-ttu-id="8844c-294">可在連絡支援時方便識別訂閱，但不是用於對帳。</span><span class="sxs-lookup"><span data-stu-id="8844c-294">May be useful to identify the subscription when contacting support but not for reconciliation.</span></span></p></td>
<td><span data-ttu-id="8844c-295">566890604832738111</span><span class="sxs-lookup"><span data-stu-id="8844c-295">566890604832738111</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8844c-296">ServiceName</span><span class="sxs-lookup"><span data-stu-id="8844c-296">ServiceName</span></span></td>
<td><p><span data-ttu-id="8844c-297">要求的 Azure 服務名稱。</span><span class="sxs-lookup"><span data-stu-id="8844c-297">The name of the Azure service in question.</span></span></p></td>
<td><span data-ttu-id="8844c-298">虛擬機器</span><span class="sxs-lookup"><span data-stu-id="8844c-298">VIRTUAL MACHINES</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8844c-299">ServiceType</span><span class="sxs-lookup"><span data-stu-id="8844c-299">ServiceType</span></span></td>
<td><p><span data-ttu-id="8844c-300">Microsoft Azure 服務的特定類型。</span><span class="sxs-lookup"><span data-stu-id="8844c-300">The specific type of Windows Azure service.</span></span></p></td>
<td><ul>
<li><span data-ttu-id="8844c-301">服務匯流排 – 個人或套件</span><span class="sxs-lookup"><span data-stu-id="8844c-301">Service Bus – Individual or Pack</span></span></li>
<li><span data-ttu-id="8844c-302">SQL Azure 資料庫 – Business 或 Web Edition</span><span class="sxs-lookup"><span data-stu-id="8844c-302">SQL Azure database – Business or Web Edition</span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8844c-303">ResourceGUID</span><span class="sxs-lookup"><span data-stu-id="8844c-303">ResourceGUID</span></span></td>
<td><p><span data-ttu-id="8844c-304">所有服務資料與定價結構的特定唯一識別碼。</span><span class="sxs-lookup"><span data-stu-id="8844c-304">Specific unique identifier for all the service data and pricing structure.</span></span></p></td>
<td><span data-ttu-id="8844c-305">DA41BC5F-C52D-4464-8A8D-8C8DCC43503B</span><span class="sxs-lookup"><span data-stu-id="8844c-305">DA41BC5F-C52D-4464-8A8D-8C8DCC43503B</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8844c-306">Resource Name</span><span class="sxs-lookup"><span data-stu-id="8844c-306">Resource Name</span></span></td>
<td><p><span data-ttu-id="8844c-307">Azure 資源的名稱。</span><span class="sxs-lookup"><span data-stu-id="8844c-307">The name of the Azure resource.</span></span></p></td>
<td><ul>
<li><span data-ttu-id="8844c-308">資料轉入 (GB)</span><span class="sxs-lookup"><span data-stu-id="8844c-308">Data Transfer In (GB)</span></span></li>
<li><span data-ttu-id="8844c-309">資料轉出 (GB)</span><span class="sxs-lookup"><span data-stu-id="8844c-309">Data Transfer Out (GB)</span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8844c-310">地區</span><span class="sxs-lookup"><span data-stu-id="8844c-310">Region</span></span></td>
<td><p><span data-ttu-id="8844c-311">使用量適用的地區。</span><span class="sxs-lookup"><span data-stu-id="8844c-311">The region the usage applies to.</span></span> <span data-ttu-id="8844c-312">主要用來指定資料傳輸速率，費率因地區而異。</span><span class="sxs-lookup"><span data-stu-id="8844c-312">Primarily used to assign rates to data transfers, as rates vary by region.</span></span></p></td>
<td><span data-ttu-id="8844c-313">亞太地區、歐洲、拉丁美洲、北美洲</span><span class="sxs-lookup"><span data-stu-id="8844c-313">Asia Pacific, Europe, Latin America, North America</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8844c-314">SKU</span><span class="sxs-lookup"><span data-stu-id="8844c-314">SKU</span></span></td>
<td><p><span data-ttu-id="8844c-315">優惠的 MSFT 唯一識別碼</span><span class="sxs-lookup"><span data-stu-id="8844c-315">MSFT unique identifier for offer</span></span></p></td>
<td><span data-ttu-id="8844c-316">7UD 00001</span><span class="sxs-lookup"><span data-stu-id="8844c-316">7UD-00001</span></span></td>
</tr>
<tr class="odd">
<td><p><span data-ttu-id="8844c-317">DetailLineItemId</span><span class="sxs-lookup"><span data-stu-id="8844c-317">DetailLineItemId</span></span></p></td>
<td><p><span data-ttu-id="8844c-318">用於詳細列出指定計費期間中，服務或資源不同費率的識別碼和數量。</span><span class="sxs-lookup"><span data-stu-id="8844c-318">An ID and quantity for itemizing the different rates for a service or resource in a given billing period.</span></span> <span data-ttu-id="8844c-319">對於 Azure 分層評分，到某個數量的計費單位會有一個評分，之後則有不同評分。</span><span class="sxs-lookup"><span data-stu-id="8844c-319">For Azure tiered rating, there may be one rate up to a certain quantity of billable units, then a different rate after that.</span></span></p></td>
<td><span data-ttu-id="8844c-320">1</span><span class="sxs-lookup"><span data-stu-id="8844c-320">1</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8844c-321">ConsumedQuantity</span><span class="sxs-lookup"><span data-stu-id="8844c-321">ConsumedQuantity</span></span></td>
<td><p><span data-ttu-id="8844c-322">報表期間耗用的服務量 (小時、GB 等等)</span><span class="sxs-lookup"><span data-stu-id="8844c-322">The amount of service consumed (hours, GB, etc.) during the reporting period.</span></span></p>
<p><span data-ttu-id="8844c-323">同時包括先前報表期間任何未計費的使用量。</span><span class="sxs-lookup"><span data-stu-id="8844c-323">Also includes any unbilled usage from previous reporting periods.</span></span></p></td>
<td><span data-ttu-id="8844c-324">11</span><span class="sxs-lookup"><span data-stu-id="8844c-324">11</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8844c-325">IncludedQuantity</span><span class="sxs-lookup"><span data-stu-id="8844c-325">IncludedQuantity</span></span></td>
<td><p><span data-ttu-id="8844c-326">包含在優惠中的單位。</span><span class="sxs-lookup"><span data-stu-id="8844c-326">Units included as part of the offer.</span></span> <span data-ttu-id="8844c-327">通常不會出現在雲端解決方案提供者中。</span><span class="sxs-lookup"><span data-stu-id="8844c-327">Not typically present in CSP.</span></span></p></td>
<td><span data-ttu-id="8844c-328">0</span><span class="sxs-lookup"><span data-stu-id="8844c-328">0</span></span></td>
</tr>
<tr class="even">
<td><p><span data-ttu-id="8844c-329">OverageQuantity</span><span class="sxs-lookup"><span data-stu-id="8844c-329">OverageQuantity</span></span></p></td>
<td><p><span data-ttu-id="8844c-330">不包含在優惠中的單位，必須由合作夥伴支付。</span><span class="sxs-lookup"><span data-stu-id="8844c-330">Units not included as part of the offer, that must be paid for by the partner.</span></span></p>
<p><span data-ttu-id="8844c-331">等同於 ConsumedQuantity - IncludedQuantity。</span><span class="sxs-lookup"><span data-stu-id="8844c-331">Equal to the ConsumedQuantity - IncludedQuantity.</span></span></p></td>
<td><span data-ttu-id="8844c-332">11</span><span class="sxs-lookup"><span data-stu-id="8844c-332">11</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8844c-333">ListPrice</span><span class="sxs-lookup"><span data-stu-id="8844c-333">ListPrice</span></span></td>
<td><p><span data-ttu-id="8844c-334">訂閱開始日期的生效優惠價格。</span><span class="sxs-lookup"><span data-stu-id="8844c-334">Offer price in effect at subscription start date.</span></span></p></td>
<td><span data-ttu-id="8844c-335">$0.0808</span><span class="sxs-lookup"><span data-stu-id="8844c-335">$0.0808</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8844c-336">PretaxCharges</span><span class="sxs-lookup"><span data-stu-id="8844c-336">PretaxCharges</span></span></td>
<td><p><span data-ttu-id="8844c-337">ListPrist 乘以 OverageQuantity，四捨五入至美分。</span><span class="sxs-lookup"><span data-stu-id="8844c-337">ListPrist times OverageQuantity, rounded to the nearest cent.</span></span></p></td>
<td><span data-ttu-id="8844c-338">$0.085</span><span class="sxs-lookup"><span data-stu-id="8844c-338">$0.085</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8844c-339">TaxAmount</span><span class="sxs-lookup"><span data-stu-id="8844c-339">TaxAmount</span></span></td>
<td><p><span data-ttu-id="8844c-340">稅金費用 (根據您所在市場的稅金規則與特定情況)。</span><span class="sxs-lookup"><span data-stu-id="8844c-340">Tax amount charge, based on your market's tax rules and specific circumstances.</span></span></p></td>
<td><span data-ttu-id="8844c-341">$0.08</span><span class="sxs-lookup"><span data-stu-id="8844c-341">$0.08</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8844c-342">PostTaxTotal</span><span class="sxs-lookup"><span data-stu-id="8844c-342">PostTaxTotal</span></span></td>
<td><p><span data-ttu-id="8844c-343">稅後總計 (當適用稅金時)。</span><span class="sxs-lookup"><span data-stu-id="8844c-343">Total after tax, when tax is applicable.</span></span></p></td>
<td><span data-ttu-id="8844c-344">$0.93</span><span class="sxs-lookup"><span data-stu-id="8844c-344">$0.93</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8844c-345">貨幣</span><span class="sxs-lookup"><span data-stu-id="8844c-345">Currency</span></span></td>
<td><p><span data-ttu-id="8844c-346">貨幣類型。</span><span class="sxs-lookup"><span data-stu-id="8844c-346">Currency type.</span></span> <span data-ttu-id="8844c-347">每一帳單實體都只有一種貨幣。</span><span class="sxs-lookup"><span data-stu-id="8844c-347">Each billing entity has only one currency.</span></span> <span data-ttu-id="8844c-348">檢查是否與您的第一張發票相符，然後在進行任何重大帳單平台更新之後檢查。</span><span class="sxs-lookup"><span data-stu-id="8844c-348">Check that it matches your first invoice and then after any major billing platform update.</span></span></p></td>
<td><span data-ttu-id="8844c-349">CNY</span><span class="sxs-lookup"><span data-stu-id="8844c-349">CNY</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8844c-350">PretaxEffectiveRate</span><span class="sxs-lookup"><span data-stu-id="8844c-350">PretaxEffectiveRate</span></span></td>
<td><p><span data-ttu-id="8844c-351">每個單位的稅前價格。</span><span class="sxs-lookup"><span data-stu-id="8844c-351">Pretax price per unit.</span></span> <span data-ttu-id="8844c-352">等於 PretaxCharges / OverageQuantity, 四捨五入至美分。</span><span class="sxs-lookup"><span data-stu-id="8844c-352">Equal to PretaxCharges / OverageQuantity, rounded to the nearest cent.</span></span></p></td>
<td><span data-ttu-id="8844c-353">$0.08</span><span class="sxs-lookup"><span data-stu-id="8844c-353">$0.08</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8844c-354">PostTaxEffectiveRate</span><span class="sxs-lookup"><span data-stu-id="8844c-354">PostTaxEffectiveRate</span></span></td>
<td><p><span data-ttu-id="8844c-355">每個單位的稅後價格。</span><span class="sxs-lookup"><span data-stu-id="8844c-355">Post tax price per unit.</span></span> <span data-ttu-id="8844c-356">等於 PostTaxTotal / OverageQuantity，或 PretaxEffectiveRate + 每單位數量稅率，四捨五入至美分。</span><span class="sxs-lookup"><span data-stu-id="8844c-356">Equal to PostTaxTotal / OverageQuantity, or PretaxEffectiveRate + tax rate per unit amoun, rounded to the nearest cent.</span></span></p></td>
<td><span data-ttu-id="8844c-357">$0.08</span><span class="sxs-lookup"><span data-stu-id="8844c-357">$0.08</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8844c-358">ChargeType</span><span class="sxs-lookup"><span data-stu-id="8844c-358">ChargeType</span></span></td>
<td><p><span data-ttu-id="8844c-359">費用或調整的類型。</span><span class="sxs-lookup"><span data-stu-id="8844c-359">The type of charge or adjustment.</span></span> <span data-ttu-id="8844c-360">請參閱<a href="#charge_types">對應發票和對帳檔案之間的費用</a></span><span class="sxs-lookup"><span data-stu-id="8844c-360">See <a href="#charge_types">Mapping charges between an invoice and the reconciliation file</a></span></span></p></td>
<td><p><span data-ttu-id="8844c-361">請參閱<a href="#charge_types">對應發票和對帳檔案之間的費用</a></span><span class="sxs-lookup"><span data-stu-id="8844c-361">See <a href="#charge_types">Mapping charges between an invoice and the reconciliation file</a></span></span></p></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8844c-362">CustomerBillableAccount</span><span class="sxs-lookup"><span data-stu-id="8844c-362">CustomerBillableAccount</span></span></td>
<td><p><span data-ttu-id="8844c-363">MSFT 帳單平台的唯一帳戶識別碼。</span><span class="sxs-lookup"><span data-stu-id="8844c-363">Unique account ID in the MSFT billing platform.</span></span></p></td>
<td><span data-ttu-id="8844c-364">1280018095</span><span class="sxs-lookup"><span data-stu-id="8844c-364">1280018095</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8844c-365">UsageDate</span><span class="sxs-lookup"><span data-stu-id="8844c-365">UsageDate</span></span></td>
<td><p><span data-ttu-id="8844c-366">服務部署的日期。</span><span class="sxs-lookup"><span data-stu-id="8844c-366">Date of service deployment.</span></span></p></td>
<td><span data-ttu-id="8844c-367">2/1/2014 0:00</span><span class="sxs-lookup"><span data-stu-id="8844c-367">2/1/2014 0:00</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8844c-368">MeteredRegion</span><span class="sxs-lookup"><span data-stu-id="8844c-368">MeteredRegion</span></span></td>
<td><p><span data-ttu-id="8844c-369">此欄可識別適用及填入此項目之服務地區內的資料中心的位置。</span><span class="sxs-lookup"><span data-stu-id="8844c-369">This column identifies the location of a data center within the region for services where this is applicable and populated.</span></span></p></td>
<td><span data-ttu-id="8844c-370">東亞、東南亞、北歐、西歐、美國中北部、美國中南部</span><span class="sxs-lookup"><span data-stu-id="8844c-370">East Asia, South East Asia, North Europe, West Europe, North Central US, South Central US</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8844c-371">MeteredService</span><span class="sxs-lookup"><span data-stu-id="8844c-371">MeteredService</span></span></td>
<td><p><span data-ttu-id="8844c-372">此欄是用來追蹤可能未在 \[服務名稱\] 欄中特別指出的個別 Microsoft Azure 服務。</span><span class="sxs-lookup"><span data-stu-id="8844c-372">This column is utilized to track the individual Microsoft Azure service that may not be specifically identified in the Service Name column.</span></span> <span data-ttu-id="8844c-373">例如，在 \[服務名稱\] 欄中，資料傳輸是回報為 &quot;Microsoft Azure - 所有服務&quot;。</span><span class="sxs-lookup"><span data-stu-id="8844c-373">For example, data transfers are reported as &quot;Microsoft Azure - All Services&quot; in the Service Name column.</span></span> <span data-ttu-id="8844c-374">此 MeteredService 欄會指出使用量與哪個特定服務有關。</span><span class="sxs-lookup"><span data-stu-id="8844c-374">This MeteredService column will indicate to which specific service the usage pertains.</span></span></p></td>
<td><span data-ttu-id="8844c-375">AccessControl、CDN、Compute、Database、ServiceBus、Storage</span><span class="sxs-lookup"><span data-stu-id="8844c-375">AccessControl, CDN, Compute, Database, ServiceBus, Storage</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8844c-376">MeteredServiceType</span><span class="sxs-lookup"><span data-stu-id="8844c-376">MeteredServiceType</span></span></td>
<td><p><span data-ttu-id="8844c-377">進一步釐清超出 MeteredService 欄位提供之層級的個別 Microsoft Azure 服務副標題。</span><span class="sxs-lookup"><span data-stu-id="8844c-377">A subheading that further clarifies the individual Microsoft Azure service beyond the level provided by the MeteredService field.</span></span></p></td>
<td><span data-ttu-id="8844c-378">外部</span><span class="sxs-lookup"><span data-stu-id="8844c-378">EXTERNAL</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8844c-379">Project</span><span class="sxs-lookup"><span data-stu-id="8844c-379">Project</span></span></td>
<td><p><span data-ttu-id="8844c-380">客戶為其服務執行個體定義的名稱</span><span class="sxs-lookup"><span data-stu-id="8844c-380">Customer-defined name for their service instance</span></span></p></td>
<td><span data-ttu-id="8844c-381">ORDDC52E52FDEF405786F0642DD0108BE4</span><span class="sxs-lookup"><span data-stu-id="8844c-381">ORDDC52E52FDEF405786F0642DD0108BE4</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8844c-382">ServiceInfo</span><span class="sxs-lookup"><span data-stu-id="8844c-382">ServiceInfo</span></span></td>
<td><p><span data-ttu-id="8844c-383">於某一天佈建及使用的 ServiceBus 連線數目。</span><span class="sxs-lookup"><span data-stu-id="8844c-383">The number of ServiceBus connections that were provisioned and utilized on a given day.</span></span></p></td>
<td><span data-ttu-id="8844c-384">例如：如果您在有 30 天的月份中有個別佈建的連線時，「服務資訊 1」的讀數會是「1.000000 連線 / 30 天」。</span><span class="sxs-lookup"><span data-stu-id="8844c-384">For example: if you had an individually provisioned connection during a 30 day month, Service Info 1 would read “1.000000 Connections / 30 days”.</span></span> <span data-ttu-id="8844c-385">如果您有 25 的組件的佈建的服務匯流排連線，而且您必須在那一天使用 1，表示您那一天的每日使用量聲明 」 25 的連線 / 已使用的 30 天：1.000000”.</span><span class="sxs-lookup"><span data-stu-id="8844c-385">If you had a 25 pack of ServiceBus connections provisioned and you had utilized 1 during that day, your daily usage statement for that day would indicate “25 Connections / 30 Days – Used: 1.000000”.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8844c-386">CustomerID</span><span class="sxs-lookup"><span data-stu-id="8844c-386">CustomerID</span></span></td>
<td><p><span data-ttu-id="8844c-387">用來識別客戶的唯一 Microsoft ID（GUID 格式）。</span><span class="sxs-lookup"><span data-stu-id="8844c-387">Unique Microsoft ID, in GUID format, used to identify the customer.</span></span></p></td>
<td><span data-ttu-id="8844c-388">ORDDC52E52FDEF405786F0642DD0108BE4</span><span class="sxs-lookup"><span data-stu-id="8844c-388">ORDDC52E52FDEF405786F0642DD0108BE4</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8844c-389">DomainName</span><span class="sxs-lookup"><span data-stu-id="8844c-389">DomainName</span></span></td>
<td><p><span data-ttu-id="8844c-390">用來協助識別客戶的客戶網域名稱。</span><span class="sxs-lookup"><span data-stu-id="8844c-390">Customer's domain name, used to help identify the customer.</span></span></p></td>
<td><span data-ttu-id="8844c-391">example.onmicrosoft.com</span><span class="sxs-lookup"><span data-stu-id="8844c-391">example.onmicrosoft.com</span></span></td></tr>
</tbody>
</table>



## <a href="" id="charge_types"></a><span data-ttu-id="8844c-392">發票和對帳檔案之間的對應費用</span><span class="sxs-lookup"><span data-stu-id="8844c-392">Mapping charges between an invoice and the reconciliation file</span></span>

<span data-ttu-id="8844c-393">您的發票提供費用摘要，而對帳檔案則提供包括費用類型等明細項目交易的詳細細項。</span><span class="sxs-lookup"><span data-stu-id="8844c-393">Your invoice provides a summary of charges, while your reconciliation file provides a detailed breakdown of line-item transactions, including charge types.</span></span>

<span data-ttu-id="8844c-394">若要交互參照發票和對帳檔案之間的費用金額，您可以使用 Microsoft Excel 篩選選項，在對帳檔案上依費用類型篩選，以便將發票費用對應到對帳檔案上的一組費用細項。</span><span class="sxs-lookup"><span data-stu-id="8844c-394">To cross-reference charge amounts between the invoice and reconciliation file, you can use Microsoft Excel's filter options to filter by charge types on the reconciliation file to map the invoice charges to a set of charge breakdowns on reconciliation file.</span></span>

<span data-ttu-id="8844c-395">下表顯示發票區段和對帳檔案上可能會顯示之相關費用類型之間的對應。</span><span class="sxs-lookup"><span data-stu-id="8844c-395">The table below shows the mappings between an invoice section and associated charge types that might show up on the reconciliation files.</span></span> 

<table>
<tbody>
<tr>
<td>
<p><span data-ttu-id="8844c-396"><strong>發票費用的描述</strong></span><span class="sxs-lookup"><span data-stu-id="8844c-396"><strong>Invoice charge description</strong></span></span></p>
</td>
<td>
<p><span data-ttu-id="8844c-397"><strong>對帳檔案費用描述 （ChargeType 資料行）</strong></span><span class="sxs-lookup"><span data-stu-id="8844c-397"><strong>Reconciliation file charge description (ChargeType column)</strong></span></span></p>
</td>
<td>
<p><span data-ttu-id="8844c-398"><strong>此費用是什麼？</strong></span><span class="sxs-lookup"><span data-stu-id="8844c-398"><strong>What is this charge?</strong></span></span></p>
</td>
<td>
<p><span data-ttu-id="8844c-399"><strong>如何將這些 ChargeTypes 對應到發票？</strong></span><span class="sxs-lookup"><span data-stu-id="8844c-399"><strong>How do I map these ChargeTypes to the invoice?</strong></span></span></p>
</td>
</tr>
<tr>
<td rowspan="8">
<p><span data-ttu-id="8844c-400"><strong>週期性費用</strong></span><span class="sxs-lookup"><span data-stu-id="8844c-400"><strong>Recurring Charges</strong></span></span></p>
</td>
<td>
<p><span data-ttu-id="8844c-401">取消執行個體按比例計算</span><span class="sxs-lookup"><span data-stu-id="8844c-401">Cancel instance prorate</span></span></p>
</td>
<td>
<p><span data-ttu-id="8844c-402">當關聯的基座變更時，按比例計算退款給客戶的費用</span><span class="sxs-lookup"><span data-stu-id="8844c-402">Prorated charges refunded to the customer when associated seats are changed</span></span></p>
</td>
<td rowspan="8">
<p><span data-ttu-id="8844c-403">從授權型檔案，加總 <strong>Amount</strong> 欄</span><span class="sxs-lookup"><span data-stu-id="8844c-403">From license-based file, sum the <strong>Amount</strong> column</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="8844c-404">循環費用</span><span class="sxs-lookup"><span data-stu-id="8844c-404">Cycle fee</span></span></p>
</td>
<td>
<p><span data-ttu-id="8844c-405">訂閱的定期費用</span><span class="sxs-lookup"><span data-stu-id="8844c-405">Periodic charges for a subscription</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="8844c-406">循環執行個體 (依比例計算)</span><span class="sxs-lookup"><span data-stu-id="8844c-406">Cycle instance prorate</span></span></p>
</td>
<td>
<p><span data-ttu-id="8844c-407">當關聯的基座變更時，按比例計算向客戶收取的費用</span><span class="sxs-lookup"><span data-stu-id="8844c-407">Prorated charges assessed from the customer when associated seats are changed</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="8844c-408">取消時按比例計算費用</span><span class="sxs-lookup"><span data-stu-id="8844c-408">Prorate fees when cancel</span></span></p>
</td>
<td>
<p><span data-ttu-id="8844c-409">取消時服務未使用部分之按比例計算的退款</span><span class="sxs-lookup"><span data-stu-id="8844c-409">Prorated refund for unused portion of service upon cancellation</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="8844c-410">購買時按比例計算費用</span><span class="sxs-lookup"><span data-stu-id="8844c-410">Prorate fees when purchase</span></span></p>
</td>
<td>
<p><span data-ttu-id="8844c-411">在購買時按比例計算的費用</span><span class="sxs-lookup"><span data-stu-id="8844c-411">Prorated fees upon purchase</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="8844c-412">購買費用</span><span class="sxs-lookup"><span data-stu-id="8844c-412">Purchase fee</span></span></p>
</td>
<td>
<p><span data-ttu-id="8844c-413">訂閱的初始費用</span><span class="sxs-lookup"><span data-stu-id="8844c-413">Initial charge for a subscription</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="8844c-414">續約時按比例計算費用</span><span class="sxs-lookup"><span data-stu-id="8844c-414">Prorate fee when renew</span></span></p>
</td>
<td>
<p><span data-ttu-id="8844c-415">訂閱續約時按比例計算的費用</span><span class="sxs-lookup"><span data-stu-id="8844c-415">Prorated fees upon subscription renewal</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="8844c-416">續約費用</span><span class="sxs-lookup"><span data-stu-id="8844c-416">Renew fee</span></span></p>
</td>
<td>
<p><span data-ttu-id="8844c-417">訂閱續約時的費用</span><span class="sxs-lookup"><span data-stu-id="8844c-417">Charge for renewing a subscription</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="8844c-418"><strong>其他產品和服務</strong></span><span class="sxs-lookup"><span data-stu-id="8844c-418"><strong>Other Products and Services</strong></span></span></p>
</td>
<td>
<p><span data-ttu-id="8844c-419">啟用時按比例計算費用</span><span class="sxs-lookup"><span data-stu-id="8844c-419">Prorate fees when activate</span></span></p>
</td>
<td>
<p><span data-ttu-id="8844c-420">從啟用到計費期間結束時按比例計算的費用</span><span class="sxs-lookup"><span data-stu-id="8844c-420">Prorated fees from activation until end of billing period</span></span></p>
</td>
<td>
<p><span data-ttu-id="8844c-421">從授權型檔案，加總 <strong>Amount</strong> 欄</span><span class="sxs-lookup"><span data-stu-id="8844c-421">From license-based file, sum the <strong>Amount</strong> column</span></span></p>
</td>
</tr>
<tr>
<td rowspan="2">
<p><span data-ttu-id="8844c-422"><strong>使用量費用</strong></span><span class="sxs-lookup"><span data-stu-id="8844c-422"><strong>Usage Charges</strong></span></span></p>
</td>
<td>
<p><span data-ttu-id="8844c-423">取消時的存取用量費用</span><span class="sxs-lookup"><span data-stu-id="8844c-423">Assess usage fee when cancel</span></span></p>
</td>
<td>
<p><span data-ttu-id="8844c-424">在目前計費期間中取消時，未支付之使用量的存取用量費用</span><span class="sxs-lookup"><span data-stu-id="8844c-424">Access usage fee upon cancellation for unpaid usage during the current billing period</span></span></p>
</td>
<td rowspan="2">
<p><span data-ttu-id="8844c-425">從用量型檔案，加總 <strong>PretaxCharges</strong> 欄</span><span class="sxs-lookup"><span data-stu-id="8844c-425">From usage-based file, sum the <strong>PretaxCharges</strong> column</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="8844c-426">目前週期的存取用量費用</span><span class="sxs-lookup"><span data-stu-id="8844c-426">Assess usage fee for current cycle</span></span></p>
</td>
<td>
<p><span data-ttu-id="8844c-427">目前計費期間的存取用量費用</span><span class="sxs-lookup"><span data-stu-id="8844c-427">Access usage fee for the current billing period</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="8844c-428"><strong>信用額度&amp;調整</strong></span><span class="sxs-lookup"><span data-stu-id="8844c-428"><strong>Credits &amp; Adjustments</strong></span></span></p>
</td>
<td>
<p><span data-ttu-id="8844c-429">明細項目位移</span><span class="sxs-lookup"><span data-stu-id="8844c-429">Offset a line item</span></span></p>
</td>
<td>
<p><span data-ttu-id="8844c-430">明細項目的部分或完整退款 (含稅)</span><span class="sxs-lookup"><span data-stu-id="8844c-430">Partial or whole refund to a line item, including taxes</span></span></p>
</td>
<td>
<p><span data-ttu-id="8844c-431">從授權型檔案，加總 <strong>TotalForCustomer</strong> 欄</span><span class="sxs-lookup"><span data-stu-id="8844c-431">From license-based file, sum the <strong>TotalForCustomer</strong> column</span></span></p>
<p><span data-ttu-id="8844c-432">從用量型檔案，加總 <strong>PostTaxTotal</strong> 欄</span><span class="sxs-lookup"><span data-stu-id="8844c-432">From usage-based file, sum the <strong>PostTaxTotal</strong> column</span></span></p>
</td>
</tr>


<tr>
<td rowspan="4">
<p><span data-ttu-id="8844c-433"><strong>其他折扣</strong></span><span class="sxs-lookup"><span data-stu-id="8844c-433"><strong>Other Discounts</strong></span></span></br><span data-ttu-id="8844c-434">
<em>(usage-based)</em></span><span class="sxs-lookup"><span data-stu-id="8844c-434">
<em>(usage-based)</em></span></span></p>
</td>
<td>
<p><span data-ttu-id="8844c-435">啟用折扣</span><span class="sxs-lookup"><span data-stu-id="8844c-435">Activation discount</span></span></p>
</td>
<td>
<p><span data-ttu-id="8844c-436">啟用訂閱時套用的折扣</span><span class="sxs-lookup"><span data-stu-id="8844c-436">Discount applied when subscription activated</span></span></p>
</td>
<td rowspan="4">
<p><span data-ttu-id="8844c-437">從用量型檔案，加總 <strong>PretaxCharges</strong> 欄</span><span class="sxs-lookup"><span data-stu-id="8844c-437">From usage-based file, sum the <strong>PretaxCharges</strong> column</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="8844c-438">循環折扣</span><span class="sxs-lookup"><span data-stu-id="8844c-438">Cycle discount</span></span></p>
</td>
<td>
<p><span data-ttu-id="8844c-439">套用至定期費用的折扣</span><span class="sxs-lookup"><span data-stu-id="8844c-439">Discount applied on periodic charges</span></span></p>
</td>
</tr><tr>
<td>
<p><span data-ttu-id="8844c-440">續約折扣</span><span class="sxs-lookup"><span data-stu-id="8844c-440">Renew discount</span></span></p>
</td>
<td>
<p><span data-ttu-id="8844c-441">訂閱續約時套用的折扣</span><span class="sxs-lookup"><span data-stu-id="8844c-441">Discount applied when subscription renewed</span></span></p>
</td>
</tr><tr>
<td>
<p><span data-ttu-id="8844c-442">取消折扣</span><span class="sxs-lookup"><span data-stu-id="8844c-442">Cancel discount</span></span></p>
</td>
<td>
<p><span data-ttu-id="8844c-443">折扣取消時收取的費用</span><span class="sxs-lookup"><span data-stu-id="8844c-443">Charges applied when discounts cancelled</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="8844c-444"><strong>其他折扣</strong></span><span class="sxs-lookup"><span data-stu-id="8844c-444"><strong>Other Discounts</strong></span></span></br><span data-ttu-id="8844c-445">
<em>（以授權為基礎）</em></span><span class="sxs-lookup"><span data-stu-id="8844c-445">
<em>(license-based)</em></span></span></p>
</td>
<td>
<p><span data-ttu-id="8844c-446"><em>可套用至多個收費類型</em></span><span class="sxs-lookup"><span data-stu-id="8844c-446"><em>May be applied to multiple charge types</em></span></span></p>
</td>
<td>
<p>&nbsp;</p>
</td>
<td>
<p><span data-ttu-id="8844c-447">從授權型檔案，加總 <strong>TotalOtherDiscount</strong> 欄</span><span class="sxs-lookup"><span data-stu-id="8844c-447">From license-based file, sum the <strong>TotalOtherDiscount</strong> column</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="8844c-448"><strong>稅金</strong>&nbsp;或&nbsp;<strong>加值稅</strong></span><span class="sxs-lookup"><span data-stu-id="8844c-448"><strong>Taxes</strong>&nbsp;or&nbsp;<strong>VAT</strong></span></span></p>
</td>
<td>
<p><span data-ttu-id="8844c-449"><em>可套用至多個收費類型</em></span><span class="sxs-lookup"><span data-stu-id="8844c-449"><em>May be applied to multiple charge types</em></span></span></p>
<p><span data-ttu-id="8844c-450"><em>例外狀況：「 位移明細項目 」 已經包含稅金。請參閱信用額度&amp;調整上面。</em></span><span class="sxs-lookup"><span data-stu-id="8844c-450"><em>Exception: "Offset a line item" already includes taxes. See Credits &amp; Adjustments, above.</em></span></span></p>
</td>
<td>
<p><span data-ttu-id="8844c-451">稅金或加值稅 (VAT)</span><span class="sxs-lookup"><span data-stu-id="8844c-451">Taxes or value-added taxes (VAT)</span></span></p>
</td>
<td>
<p><span data-ttu-id="8844c-452">從授權型檔案，加總 <strong>Tax</strong> 欄</span><span class="sxs-lookup"><span data-stu-id="8844c-452">From license-based file, sum the <strong>Tax</strong> column</span></span></p>
<p><span data-ttu-id="8844c-453">從用量型檔案，加總 <strong>TaxAmount</strong> 欄</span><span class="sxs-lookup"><span data-stu-id="8844c-453">From usage-based file, sum the <strong>TaxAmount</strong> column</span></span></p>
</td>
</tr>
</tbody>
</table>
<p>&nbsp;</p>
