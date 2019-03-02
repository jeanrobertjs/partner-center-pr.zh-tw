---
title: 使用對帳檔案 | 合作夥伴中心
ms.topic: article
ms.date: 10/29/2018
description: 如計費週期中每項費用的詳細的明細項目檢視，請從合作夥伴中心下載對帳檔案。
ms.assetid: FA6A6FCB-2597-44E7-93F8-8D1DD35D52EA
author: labrenne
ms.author: labrenne
ms.localizationpriority: medium
ms.openlocfilehash: 081afc547a0ff86010e06fcb5224a615a0075e34
ms.sourcegitcommit: 8bfd1358a0ef86e46bee2a1097d86de3c9e969e8
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 03/02/2019
ms.locfileid: "9122275"
---
# <a name="use-the-reconciliation-files"></a><span data-ttu-id="0c172-103">使用對帳檔案</span><span class="sxs-lookup"><span data-stu-id="0c172-103">Use the reconciliation files</span></span>

**<span data-ttu-id="0c172-104">適用於</span><span class="sxs-lookup"><span data-stu-id="0c172-104">Applies to</span></span>**

-  <span data-ttu-id="0c172-105">合作夥伴中心</span><span class="sxs-lookup"><span data-stu-id="0c172-105">Partner Center</span></span>
-  <span data-ttu-id="0c172-106">美國政府適用的 Microsoft Cloud 合作夥伴中心</span><span class="sxs-lookup"><span data-stu-id="0c172-106">Partner Center for Microsoft Cloud for US Government</span></span>


<span data-ttu-id="0c172-107">如計費週期中每項費用的詳細的明細項目檢視，請從合作夥伴中心下載對帳檔案。</span><span class="sxs-lookup"><span data-stu-id="0c172-107">For a detailed line-item view of each charge in a billing cycle, download the reconciliation files from Partner Center.</span></span> <span data-ttu-id="0c172-108">詳細資料包括每個客戶的訂閱費用，以及詳細事件 (例如，期中增加訂閱基座)。</span><span class="sxs-lookup"><span data-stu-id="0c172-108">The details include charges for each customer's subscriptions, and detailed events (such as a mid-term addition of seats to a subscription).</span></span>

## <a href="" id="itemizebypartner"></a><span data-ttu-id="0c172-109">依合作夥伴詳細列舉</span><span class="sxs-lookup"><span data-stu-id="0c172-109">Itemize by partner</span></span>


<span data-ttu-id="0c172-110">間接模型合作夥伴可以在授權型及用量型對帳檔案中使用這些額外欄位，以便依經銷商詳細列舉。</span><span class="sxs-lookup"><span data-stu-id="0c172-110">Partners in the indirect model can use these additional fields in both license-based and usage-based reconciliation files to itemize by reseller.</span></span>

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th><span data-ttu-id="0c172-111">MPN 識別碼</span><span class="sxs-lookup"><span data-stu-id="0c172-111">MPN ID</span></span></th>
<th><span data-ttu-id="0c172-112">描述</span><span class="sxs-lookup"><span data-stu-id="0c172-112">Description</span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="0c172-113">MPN 識別碼</span><span class="sxs-lookup"><span data-stu-id="0c172-113">MPN ID</span></span></td>
<td><p><span data-ttu-id="0c172-114">CSP 合作夥伴 (直接或間接) 的 Microsoft 合作夥伴網路 (MPN) 識別碼。</span><span class="sxs-lookup"><span data-stu-id="0c172-114">The Microsoft Partner Network (MPN) ID of the CSP partner (direct or indirect).</span></span></p></td>
</tr>
<tr class="even">
<td><span data-ttu-id="0c172-115">經銷商 MPN 識別碼</span><span class="sxs-lookup"><span data-stu-id="0c172-115">Reseller MPN ID</span></span></td>
<td><p><span data-ttu-id="0c172-116">只會出現在間接模型合作夥伴的對帳檔案上。</span><span class="sxs-lookup"><span data-stu-id="0c172-116">Only appears on reconciliation files for partners in the indirect model.</span></span></p>
<p><span data-ttu-id="0c172-117">訂閱記錄中的經銷商 MPN 識別碼。</span><span class="sxs-lookup"><span data-stu-id="0c172-117">The MPN ID of the reseller of record for the subscription.</span></span> <span data-ttu-id="0c172-118">這會對應到合作夥伴中心中針對特定訂閱列出的經銷商識別碼。</span><span class="sxs-lookup"><span data-stu-id="0c172-118">This corresponds to the reseller ID listed for the specific subscription in Partner Center.</span></span></p>
<p><span data-ttu-id="0c172-119">若要檢視或更新經銷商，請從合作夥伴中心功能表中，選取<strong>客戶</strong>，然後從清單中選擇客戶。</span><span class="sxs-lookup"><span data-stu-id="0c172-119">eTo view or update the reseller, from the Partner Center menu, select <strong>Customers</strong>, then choose the customer from the list.</span></span> <span data-ttu-id="0c172-120">在客戶功能表中，選取 \[訂閱\]<strong></strong>，從清單中選擇訂閱。</span><span class="sxs-lookup"><span data-stu-id="0c172-120">In the customer menu, select <strong>Subscriptions</strong>, choose the subscription from the list.</span></span> <span data-ttu-id="0c172-121">選取 \[更新\]<strong></strong> 以變更 \[經銷商 (MPN 識別碼)\]<strong></strong>。</span><span class="sxs-lookup"><span data-stu-id="0c172-121">Select <strong>update</strong> to change the <strong>Reseller (MPN ID)</strong>.</span></span></p>
<p><span data-ttu-id="0c172-122">如果雲端解決方案提供者合作夥伴直接向客戶銷售訂閱，他們的 MPN 識別碼將會以 MPN 識別碼和經銷商 MPN 識別碼的形式列出兩次。</span><span class="sxs-lookup"><span data-stu-id="0c172-122">If a CSP partner sold the subscription directly to the customer, their MPN ID is listed twice, as both the MPN ID and the Reseller MPN ID.</span></span></p>
<p><span data-ttu-id="0c172-123">如果雲端解決方案提供者合作夥伴具有沒有 MPN 識別碼的經銷商，這個值將會改成設為合作夥伴的 MPN 識別碼。</span><span class="sxs-lookup"><span data-stu-id="0c172-123">If a CSP partner has a reseller with no MPN ID, this value is set to the partner’s MPN ID instead.</span></span></p>
<p><span data-ttu-id="0c172-124">如果雲端解決方案提供者合作夥伴移除經銷商識別碼，這個值將會設為 -1。</span><span class="sxs-lookup"><span data-stu-id="0c172-124">If the CSP partner removes a reseller ID, this value will be set to -1.</span></span></p></td>
</tr>
</tbody>
</table>

 

## <a href="" id="licensebasedfiles"></a><span data-ttu-id="0c172-125">授權型檔案欄位</span><span class="sxs-lookup"><span data-stu-id="0c172-125">License-based file fields</span></span>


<span data-ttu-id="0c172-126">若要針對您對客戶訂單的費用來對帳，請比較對帳檔案中的 Syndication\_Partner\_Subscription\_Number 與合作夥伴中心的訂閱識別碼。</span><span class="sxs-lookup"><span data-stu-id="0c172-126">To reconcile your charges against your customer's orders, compare the Syndication\_Partner\_Subscription\_Number from the reconciliation file against the Subscription ID from Partner Center.</span></span>

<table>
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<tbody>
<tr class="odd">
<td><strong><span data-ttu-id="0c172-127">欄</span><span class="sxs-lookup"><span data-stu-id="0c172-127">Column</span></span></strong></td>
<td><strong><span data-ttu-id="0c172-128">描述</span><span class="sxs-lookup"><span data-stu-id="0c172-128">Description</span></span></strong></td>
<td><strong><span data-ttu-id="0c172-129">範例值</span><span class="sxs-lookup"><span data-stu-id="0c172-129">Sample Value</span></span></strong></td>
</tr>
<tr class="even">
<td><span data-ttu-id="0c172-130">PartnerId</span><span class="sxs-lookup"><span data-stu-id="0c172-130">PartnerId</span></span></td>
<td><p><span data-ttu-id="0c172-131">特定帳單實體的唯一識別碼 (GUID 格式)。</span><span class="sxs-lookup"><span data-stu-id="0c172-131">Unique identifier for a specific billing entity, in GUID format.</span></span> <span data-ttu-id="0c172-132">對帳時不需要，但可能是很有用的資訊。</span><span class="sxs-lookup"><span data-stu-id="0c172-132">Not required for reconciliation, however may be useful information.</span></span> <span data-ttu-id="0c172-133">在所有資料列中都是如此。</span><span class="sxs-lookup"><span data-stu-id="0c172-133">Same in all rows.</span></span></p></td>
<td><span data-ttu-id="0c172-134">8ddd03642-test-test-test-46b58d356b4e</span><span class="sxs-lookup"><span data-stu-id="0c172-134">8ddd03642-test-test-test-46b58d356b4e</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="0c172-135">CustomerID</span><span class="sxs-lookup"><span data-stu-id="0c172-135">CustomerID</span></span></td>
<td><p><span data-ttu-id="0c172-136">用來識別客戶的唯一 Microsoft ID（GUID 格式）。</span><span class="sxs-lookup"><span data-stu-id="0c172-136">Unique Microsoft ID, in GUID format, used to identify the customer.</span></span></p></td>
<td><span data-ttu-id="0c172-137">12ABCD34-001A-BCD2-987C-3210ABCD5678</span><span class="sxs-lookup"><span data-stu-id="0c172-137">12ABCD34-001A-BCD2-987C-3210ABCD5678</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="0c172-138">OrderID</span><span class="sxs-lookup"><span data-stu-id="0c172-138">OrderID</span></span></td>
<td><p><span data-ttu-id="0c172-139">訂單在 Microsoft 帳單平台中的唯一識別碼。</span><span class="sxs-lookup"><span data-stu-id="0c172-139">Unique identifier for an order in the Microsoft billing platform.</span></span> <span data-ttu-id="0c172-140">可在連絡支援時方便識別訂單，但不是用於對帳。</span><span class="sxs-lookup"><span data-stu-id="0c172-140">May be useful to identify the order when contacting support but not for reconciliation.</span></span></p></td>
<td><span data-ttu-id="0c172-141">566890604832738111</span><span class="sxs-lookup"><span data-stu-id="0c172-141">566890604832738111</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="0c172-142">SubscriptionID</span><span class="sxs-lookup"><span data-stu-id="0c172-142">SubscriptionID</span></span></td>
<td><p><span data-ttu-id="0c172-143">訂閱在 Microsoft 帳單平台中的唯一識別碼。</span><span class="sxs-lookup"><span data-stu-id="0c172-143">Unique identifier for a subscription in the Microsoft billing platform.</span></span> <span data-ttu-id="0c172-144">可在連絡支援時方便識別訂閱，但不是用於對帳。</span><span class="sxs-lookup"><span data-stu-id="0c172-144">May be useful to identify the subscription when contacting support but not for reconciliation.</span></span></p>
<p><span data-ttu-id="0c172-145">這與合作夥伴管理主控台上的訂閱識別碼不一樣。</span><span class="sxs-lookup"><span data-stu-id="0c172-145">This is not the same as the Subscription ID on the Partner Admin Console.</span></span> <span data-ttu-id="0c172-146">請參閱 Syndication_Partner_Subscription_Number。</span><span class="sxs-lookup"><span data-stu-id="0c172-146">Please see Syndication_Partner_Subscription_Number.</span></span></p></td>
<td><span data-ttu-id="0c172-147">usCBMgAAAAAAAAIA</span><span class="sxs-lookup"><span data-stu-id="0c172-147">usCBMgAAAAAAAAIA</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="0c172-148">SyndicationPartnerSubscriptionNumber</span><span class="sxs-lookup"><span data-stu-id="0c172-148">SyndicationPartnerSubscriptionNumber</span></span></td>
<td><p><span data-ttu-id="0c172-149">訂閱的唯一識別碼。</span><span class="sxs-lookup"><span data-stu-id="0c172-149">Unique identifier for subscriptions.</span></span> <span data-ttu-id="0c172-150">客戶可針對同一方案擁有多項訂閱，因此這對於對帳檔案分析而言很重要。</span><span class="sxs-lookup"><span data-stu-id="0c172-150">A customer can have multiple subscriptions for the same plan, so this is important for reconciliation file analysis.</span></span></p>
<p><span data-ttu-id="0c172-151">這個欄位對應到合作夥伴管理主控台中的訂閱識別碼。</span><span class="sxs-lookup"><span data-stu-id="0c172-151">This field maps to the Subscription ID in the Partner Admin Console.</span></span></p></td>
<td><span data-ttu-id="0c172-152">fb977ab5-test-test-test-24c8d9591708</span><span class="sxs-lookup"><span data-stu-id="0c172-152">fb977ab5-test-test-test-24c8d9591708</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="0c172-153">OfferID</span><span class="sxs-lookup"><span data-stu-id="0c172-153">OfferID</span></span></td>
<td><p><span data-ttu-id="0c172-154">唯一的優惠識別碼。</span><span class="sxs-lookup"><span data-stu-id="0c172-154">Unique offer ID.</span></span> <span data-ttu-id="0c172-155">根據價目表的標準優惠識別碼。</span><span class="sxs-lookup"><span data-stu-id="0c172-155">Standard offer ID as per price list.</span></span></p>
<p><span data-ttu-id="0c172-156"><b>注意</b>：這個值不符合價目表上的優惠識別碼。</span><span class="sxs-lookup"><span data-stu-id="0c172-156"><b>Note</b>: This value does not match Offer ID from the price list.</span></span> <span data-ttu-id="0c172-157">請參閱下方的 DurableOfferID。</span><span class="sxs-lookup"><span data-stu-id="0c172-157">See DurableOfferID below.</span></span></p></td>
<td><span data-ttu-id="0c172-158">FE616D64-E9A8-40EF-843F-152E9BBEF3D1</span><span class="sxs-lookup"><span data-stu-id="0c172-158">FE616D64-E9A8-40EF-843F-152E9BBEF3D1</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="0c172-159">DurableOfferID</span><span class="sxs-lookup"><span data-stu-id="0c172-159">DurableOfferID</span></span></td>
<td><p><span data-ttu-id="0c172-160">唯一的持續性優惠識別碼，如價目表中所定義。</span><span class="sxs-lookup"><span data-stu-id="0c172-160">Unique durable offer ID, as defined in the price list.</span></span></p>
<p><span data-ttu-id="0c172-161"><b>注意</b>：這個值符合價目表上的優惠識別碼。</span><span class="sxs-lookup"><span data-stu-id="0c172-161"><b>Note</b>: This value matches the Offer ID from the price list.</span></span></p></td>
<td><span data-ttu-id="0c172-162">1017D7F3-6D7F-4BFA-BDD8-79BC8F104E0C</span><span class="sxs-lookup"><span data-stu-id="0c172-162">1017D7F3-6D7F-4BFA-BDD8-79BC8F104E0C</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="0c172-163">OfferName</span><span class="sxs-lookup"><span data-stu-id="0c172-163">OfferName</span></span></td>
<td><p><span data-ttu-id="0c172-164">客戶購買的服務優惠名稱，如價目表中所定義。</span><span class="sxs-lookup"><span data-stu-id="0c172-164">The name of the service offering purchased by the customer, as defined in the price list.</span></span></p></td>
<td><span data-ttu-id="0c172-165">Microsoft Office 365 (Plan E3)</span><span class="sxs-lookup"><span data-stu-id="0c172-165">Microsoft Office 365 (Plan E3)</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="0c172-166">SubscriptionStartDate</span><span class="sxs-lookup"><span data-stu-id="0c172-166">SubscriptionStartDate</span></span></td>
<td><p><span data-ttu-id="0c172-167">訂閱開始日期設定為送出訂單之後的隔日。</span><span class="sxs-lookup"><span data-stu-id="0c172-167">The subscription start date, set to the day after the order is submitted.</span></span> <span data-ttu-id="0c172-168">藉由同時查看訂閱開始日期與結束日期，您就可以判斷客戶是否仍在第一年訂閱期內，或下一年的訂閱已續約。</span><span class="sxs-lookup"><span data-stu-id="0c172-168">By looking at the subscription start date in conjunction with the end date, you can determine if the customer is still within the first year of the subscription or if the subscription has been renewed for the following year.</span></span></p>
<p><span data-ttu-id="0c172-169">時間一律是一天的開始時間 (0:00)。</span><span class="sxs-lookup"><span data-stu-id="0c172-169">The time is always the beginning of the day, 0:00.</span></span></p></td>
<td><span data-ttu-id="0c172-170">2/1/2015 0:00</span><span class="sxs-lookup"><span data-stu-id="0c172-170">2/1/2015 0:00</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="0c172-171">SubscriptionEndDate</span><span class="sxs-lookup"><span data-stu-id="0c172-171">SubscriptionEndDate</span></span></td>
<td><p><span data-ttu-id="0c172-172">訂閱結束日期：開始日期之後的 12 個月 + x 天 (與合作夥伴帳單日期配合) 或自續約日期起 12 個月。</span><span class="sxs-lookup"><span data-stu-id="0c172-172">The subscription end date: 12 months + x days after start date (to align with partner billing date) or 12 months from renewal date.</span></span></p>
<p><span data-ttu-id="0c172-173">續約時，價格會更新至目前的價目表。</span><span class="sxs-lookup"><span data-stu-id="0c172-173">At renewal, prices are updated to the current price list.</span></span> <span data-ttu-id="0c172-174">自動續約之前，可能需要與客戶連絡。</span><span class="sxs-lookup"><span data-stu-id="0c172-174">Customer communication may be required in advance of automated renewal.</span></span></p>
<p><span data-ttu-id="0c172-175">時間一律是一天的開始時間 (0:00)。</span><span class="sxs-lookup"><span data-stu-id="0c172-175">The time is always the beginning of the day, 0:00.</span></span></p></td>
<td><span data-ttu-id="0c172-176">2/1/2015 0:00</span><span class="sxs-lookup"><span data-stu-id="0c172-176">2/1/2015 0:00</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="0c172-177">ChargeStartDate</span><span class="sxs-lookup"><span data-stu-id="0c172-177">ChargeStartDate</span></span></td>
<td><p><span data-ttu-id="0c172-178">開始計算費用的日期。</span><span class="sxs-lookup"><span data-stu-id="0c172-178">Start day of the charges.</span></span></p>
<p><span data-ttu-id="0c172-179">當客戶變更基座數目時，此數字用於計算每日 (按比例) 的費用。</span><span class="sxs-lookup"><span data-stu-id="0c172-179">When a customer changes seat numbers, this number is used to calculate per-day (pro-rata) charges.</span></span></p>
<p><span data-ttu-id="0c172-180">時間一律是一天的開始時間 (0:00)。</span><span class="sxs-lookup"><span data-stu-id="0c172-180">The time is always the beginning of the day, 0:00.</span></span></p></td>
<td><span data-ttu-id="0c172-181">2/1/2015 0:00</span><span class="sxs-lookup"><span data-stu-id="0c172-181">2/1/2015 0:00</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="0c172-182">ChargeEndDate</span><span class="sxs-lookup"><span data-stu-id="0c172-182">ChargeEndDate</span></span></td>
<td><p><span data-ttu-id="0c172-183">結束計算費用的日期。</span><span class="sxs-lookup"><span data-stu-id="0c172-183">End day of the charges.</span></span></p>
<p><span data-ttu-id="0c172-184">當客戶變更基座數目時，此數字用於計算每日 (按比例) 的費用。</span><span class="sxs-lookup"><span data-stu-id="0c172-184">When a customer changes seat numbers, this number is used to calculate per-day (pro-rata) charges.</span></span></p>
<p><span data-ttu-id="0c172-185">時間一律是一天的結束時間 (23:59)。</span><span class="sxs-lookup"><span data-stu-id="0c172-185">The time is always the end of the day, 23:59.</span></span></p></td>
<td><span data-ttu-id="0c172-186">2/28/2015 23:59</span><span class="sxs-lookup"><span data-stu-id="0c172-186">2/28/2015 23:59</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="0c172-187">ChargeType</span><span class="sxs-lookup"><span data-stu-id="0c172-187">ChargeType</span></span></td>
<td><p><span data-ttu-id="0c172-188">費用或調整的類型。</span><span class="sxs-lookup"><span data-stu-id="0c172-188">The type of charge or adjustment.</span></span> <span data-ttu-id="0c172-189">請參閱<a href="#charge_types">對應發票和對帳檔案之間的費用</a></span><span class="sxs-lookup"><span data-stu-id="0c172-189">See <a href="#charge_types">Mapping charges between an invoice and the reconciliation file</a></span></span></p></td>
<td><p><span data-ttu-id="0c172-190">請參閱<a href="#charge_types">對應發票和對帳檔案之間的費用</a></span><span class="sxs-lookup"><span data-stu-id="0c172-190">See <a href="#charge_types">Mapping charges between an invoice and the reconciliation file</a></span></span></p></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="0c172-191">UnitPrice</span><span class="sxs-lookup"><span data-stu-id="0c172-191">UnitPrice</span></span></td>
<td><p><span data-ttu-id="0c172-192">每一基座價格，即購買時價目表中所公佈的價格。</span><span class="sxs-lookup"><span data-stu-id="0c172-192">Price per seat, as published in the pricelist at the time of purchase.</span></span> <span data-ttu-id="0c172-193">請確定這與對帳期間儲存在您帳單系統中的資訊相符。</span><span class="sxs-lookup"><span data-stu-id="0c172-193">Ensure this matches the information stored in your billing system during reconciliation.</span></span></p></td>
<td><span data-ttu-id="0c172-194">6.82</span><span class="sxs-lookup"><span data-stu-id="0c172-194">6.82</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="0c172-195">Quantity</span><span class="sxs-lookup"><span data-stu-id="0c172-195">Quantity</span></span></td>
<td><p><span data-ttu-id="0c172-196">基座數目。</span><span class="sxs-lookup"><span data-stu-id="0c172-196">Number of seats.</span></span> <span data-ttu-id="0c172-197">請確定這與對帳期間儲存在您帳單系統中的資訊相符。</span><span class="sxs-lookup"><span data-stu-id="0c172-197">Ensure this matches the information stored in your billing system during reconciliation.</span></span></p></td>
<td><span data-ttu-id="0c172-198">2</span><span class="sxs-lookup"><span data-stu-id="0c172-198">2</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="0c172-199">Amount</span><span class="sxs-lookup"><span data-stu-id="0c172-199">Amount</span></span></td>
<td><p><span data-ttu-id="0c172-200">數量總價。</span><span class="sxs-lookup"><span data-stu-id="0c172-200">Total of price for quantity.</span></span> <span data-ttu-id="0c172-201">檢查計算金額與您用來為客戶計算此項目的方式是否相符時很有用。</span><span class="sxs-lookup"><span data-stu-id="0c172-201">Useful to check that the amount calculation matches how you calculate this for your customers.</span></span></p></td>
<td><span data-ttu-id="0c172-202">13.32</span><span class="sxs-lookup"><span data-stu-id="0c172-202">13.32</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="0c172-203">TotalOtherDiscount</span><span class="sxs-lookup"><span data-stu-id="0c172-203">TotalOtherDiscount</span></span></td>
<td><p><span data-ttu-id="0c172-204">套用至這些費用的折扣金額。</span><span class="sxs-lookup"><span data-stu-id="0c172-204">Amount of discount applied to these charges.</span></span> <span data-ttu-id="0c172-205">符合獎勵資格之 IUR 或新訂閱的訂單，也將於此欄中包含折扣金額。</span><span class="sxs-lookup"><span data-stu-id="0c172-205">IUR or new subscriptions eligible for an incentive will also contain a discount amount in this column.</span></span></p></td>
<td><span data-ttu-id="0c172-206">2.32</span><span class="sxs-lookup"><span data-stu-id="0c172-206">2.32</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="0c172-207">Subtotal</span><span class="sxs-lookup"><span data-stu-id="0c172-207">Subtotal</span></span></td>
<td><p><span data-ttu-id="0c172-208">稅前總計。</span><span class="sxs-lookup"><span data-stu-id="0c172-208">Total before tax.</span></span> <span data-ttu-id="0c172-209">如果有折扣，可檢查小計是否和預期的總金額相符。</span><span class="sxs-lookup"><span data-stu-id="0c172-209">Checks that your subtotal matches your expected total, in case of a discount.</span></span></p></td>
<td><span data-ttu-id="0c172-210">11</span><span class="sxs-lookup"><span data-stu-id="0c172-210">11</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="0c172-211">Tax</span><span class="sxs-lookup"><span data-stu-id="0c172-211">Tax</span></span></td>
<td><p><span data-ttu-id="0c172-212">稅金費用，根據您 market& #39; s 稅金規則與特定情況。</span><span class="sxs-lookup"><span data-stu-id="0c172-212">Tax amount charge, based on your market&#39;s tax rules and specific circumstances.</span></span></p></td>
<td><span data-ttu-id="0c172-213">0</span><span class="sxs-lookup"><span data-stu-id="0c172-213">0</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="0c172-214">TotalForCustomer</span><span class="sxs-lookup"><span data-stu-id="0c172-214">TotalForCustomer</span></span></td>
<td><p><span data-ttu-id="0c172-215">稅後總計。</span><span class="sxs-lookup"><span data-stu-id="0c172-215">Total after tax.</span></span> <span data-ttu-id="0c172-216">檢查發票中是否向您收取稅金。</span><span class="sxs-lookup"><span data-stu-id="0c172-216">Checks if you are charged tax in the invoice.</span></span></p></td>
<td><span data-ttu-id="0c172-217">11</span><span class="sxs-lookup"><span data-stu-id="0c172-217">11</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="0c172-218">Currency</span><span class="sxs-lookup"><span data-stu-id="0c172-218">Currency</span></span></td>
<td><p><span data-ttu-id="0c172-219">貨幣類型。</span><span class="sxs-lookup"><span data-stu-id="0c172-219">Currency type.</span></span> <span data-ttu-id="0c172-220">每一帳單實體都只有一種貨幣。</span><span class="sxs-lookup"><span data-stu-id="0c172-220">Each billing entity has only one currency.</span></span> <span data-ttu-id="0c172-221">檢查是否與您的第一張發票相符，然後在進行任何重大帳單平台更新之後檢查。</span><span class="sxs-lookup"><span data-stu-id="0c172-221">Check that it matches your first invoice and then after any major billing platform update.</span></span></p></td>
<td><span data-ttu-id="0c172-222">EUR</span><span class="sxs-lookup"><span data-stu-id="0c172-222">EUR</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="0c172-223">CustomerName</span><span class="sxs-lookup"><span data-stu-id="0c172-223">CustomerName</span></span></td>
<td><p><span data-ttu-id="0c172-224">Customer& #39; 合作夥伴中心中回報 s 組織名稱。</span><span class="sxs-lookup"><span data-stu-id="0c172-224">Customer&#39;s organization name as reported in Partner Center.</span></span> <span data-ttu-id="0c172-225">這在使用您的系統資訊對帳發票時非常重要。</span><span class="sxs-lookup"><span data-stu-id="0c172-225">This is very important for reconciling the invoice with your system information.</span></span></p></td>
<td><span data-ttu-id="0c172-226">測試客戶 A</span><span class="sxs-lookup"><span data-stu-id="0c172-226">Test Customer A</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="0c172-227">MPNID</span><span class="sxs-lookup"><span data-stu-id="0c172-227">MPNID</span></span></td>
<td><p><span data-ttu-id="0c172-228">雲端解決方案提供者合作夥伴的 MPN 識別碼</span><span class="sxs-lookup"><span data-stu-id="0c172-228">MPN ID of the CSP partner</span></span></p></td>
<td><span data-ttu-id="0c172-229">4390934</span><span class="sxs-lookup"><span data-stu-id="0c172-229">4390934</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="0c172-230">ResellerMPNID</span><span class="sxs-lookup"><span data-stu-id="0c172-230">ResellerMPNID</span></span></td>
<td><p><span data-ttu-id="0c172-231">訂閱記錄中的經銷商 MPN 識別碼。</span><span class="sxs-lookup"><span data-stu-id="0c172-231">MPN ID of the reseller of record for the subscription.</span></span> <span data-ttu-id="0c172-232">請參閱<a href="#itemizebypartner" data-raw-source="[Itemize by partner](#itemizebypartner)">依合作夥伴詳細列舉</a>。</span><span class="sxs-lookup"><span data-stu-id="0c172-232">See <a href="#itemizebypartner" data-raw-source="[Itemize by partner](#itemizebypartner)">Itemize by partner</a>.</span></span></p></td>
<td><span data-ttu-id="0c172-233">4390934</span><span class="sxs-lookup"><span data-stu-id="0c172-233">4390934</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="0c172-234">DomainName</span><span class="sxs-lookup"><span data-stu-id="0c172-234">DomainName</span></span></td>
<td><p><span data-ttu-id="0c172-235">Customer& #39; s 網域名稱，用來協助識別客戶。</span><span class="sxs-lookup"><span data-stu-id="0c172-235">Customer&#39;s domain name, used to help identify the customer.</span></span> <span data-ttu-id="0c172-236">這不應該用來唯一識別客戶，因為客戶/合作夥伴可以更新透過 O365 入口網站的預設虛名/網域。</span><span class="sxs-lookup"><span data-stu-id="0c172-236">This should not be used to uniquely identify the customer as the customer/partner can update the vanity/default domain via the O365 portal.</span></span> <span data-ttu-id="0c172-237">在下一個帳單週期之前，此欄位會是空白的。</span><span class="sxs-lookup"><span data-stu-id="0c172-237">This field may appear blank until the second billing cycle.</span></span></p></td>
<td><span data-ttu-id="0c172-238">example.onmicrosoft.com</span><span class="sxs-lookup"><span data-stu-id="0c172-238">example.onmicrosoft.com</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="0c172-239">SubscriptionName</span><span class="sxs-lookup"><span data-stu-id="0c172-239">SubscriptionName</span></span></td>
<td><p><span data-ttu-id="0c172-240">訂閱暱稱。</span><span class="sxs-lookup"><span data-stu-id="0c172-240">Subscription nickname.</span></span> <span data-ttu-id="0c172-241">如果未指定任何暱稱，合作夥伴中心會使用 OfferName。</span><span class="sxs-lookup"><span data-stu-id="0c172-241">If no nickname is specified, Partner Center uses the OfferName.</span></span></p></td>
<td><span data-ttu-id="0c172-242">PROJECT ONLINE</span><span class="sxs-lookup"><span data-stu-id="0c172-242">PROJECT ONLINE</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="0c172-243">SubscriptionDescription</span><span class="sxs-lookup"><span data-stu-id="0c172-243">SubscriptionDescription</span></span></td>
<td><p><span data-ttu-id="0c172-244">客戶購買的服務優惠名稱，如價目表中所定義。</span><span class="sxs-lookup"><span data-stu-id="0c172-244">The name of the service offering purchased by the customer, as defined in the price list.</span></span> <span data-ttu-id="0c172-245">（這是優惠名稱的相同欄位）。</span><span class="sxs-lookup"><span data-stu-id="0c172-245">(This is an identical field to Offer name).</span></span></p></td>
<td><span data-ttu-id="0c172-246">PROJECT ONLINE PREMIUM WITHOUT PROJECT CLIENT</span><span class="sxs-lookup"><span data-stu-id="0c172-246">PROJECT ONLINE PREMIUM WITHOUT PROJECT CLIENT</span></span></td>
</tr>
</tbody>
</table>


## <a href="" id="usagebasedfiles"></a><span data-ttu-id="0c172-247">用量型檔案欄位</span><span class="sxs-lookup"><span data-stu-id="0c172-247">Usage-based file fields</span></span>


<span data-ttu-id="0c172-248">若要針對您客戶使用量的費用來對帳，請比較對帳檔案中的 ResellerID/ResellerName/ResellerBillableAccount、客戶名稱，與合作夥伴中心的訂閱識別碼。</span><span class="sxs-lookup"><span data-stu-id="0c172-248">To reconcile your charges against your customer's usage, compare the ResellerID/ResellerName/ResellerBillableAccount from the reconciliation file, the customer name, and the Subscription ID from Partner Center.</span></span>

<span data-ttu-id="0c172-249">下列欄位說明使用哪些服務及費率。</span><span class="sxs-lookup"><span data-stu-id="0c172-249">The following fields explain which services were used and the rate.</span></span>

<table>
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<tbody>
<tr class="odd">
<td><strong><span data-ttu-id="0c172-250">欄位</span><span class="sxs-lookup"><span data-stu-id="0c172-250">Column</span></span></strong></td>
<td><strong><span data-ttu-id="0c172-251">描述</span><span class="sxs-lookup"><span data-stu-id="0c172-251">Description</span></span></strong></td>
<td><strong><span data-ttu-id="0c172-252">範例值</span><span class="sxs-lookup"><span data-stu-id="0c172-252">Sample value</span></span></strong></td>
</tr>
<tr class="even">
<td><span data-ttu-id="0c172-253">PartnerID</span><span class="sxs-lookup"><span data-stu-id="0c172-253">PartnerID</span></span></td>
<td><p><span data-ttu-id="0c172-254">合作夥伴識別碼 (GUID 格式)。</span><span class="sxs-lookup"><span data-stu-id="0c172-254">Partner ID, in GUID format.</span></span></p></td>
<td><span data-ttu-id="0c172-255">DA41BC5F-C52D-4464-8A8D-8C8DCC43503B</span><span class="sxs-lookup"><span data-stu-id="0c172-255">DA41BC5F-C52D-4464-8A8D-8C8DCC43503B</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="0c172-256">PartnerName</span><span class="sxs-lookup"><span data-stu-id="0c172-256">PartnerName</span></span></td>
<td><p><span data-ttu-id="0c172-257">合作夥伴名稱。</span><span class="sxs-lookup"><span data-stu-id="0c172-257">Partner Name.</span></span></p></td>
<td><span data-ttu-id="0c172-258">Acme Incorporated</span><span class="sxs-lookup"><span data-stu-id="0c172-258">Acme Incorporated</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="0c172-259">PartnerBillableAccountID</span><span class="sxs-lookup"><span data-stu-id="0c172-259">PartnerBillableAccountID</span></span></td>
<td><p><span data-ttu-id="0c172-260">合作夥伴帳戶識別碼。</span><span class="sxs-lookup"><span data-stu-id="0c172-260">Partner Account ID.</span></span></p></td>
<td><span data-ttu-id="0c172-261">1010578050</span><span class="sxs-lookup"><span data-stu-id="0c172-261">1010578050</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="0c172-262">CustomerName</span><span class="sxs-lookup"><span data-stu-id="0c172-262">CustomerName</span></span></td>
<td><p><span data-ttu-id="0c172-263">Customer& #39; 合作夥伴中心中回報 s 組織名稱。</span><span class="sxs-lookup"><span data-stu-id="0c172-263">Customer&#39;s organization name as reported in Partner Center.</span></span> <span data-ttu-id="0c172-264">這在使用您的系統資訊對帳發票時非常重要。</span><span class="sxs-lookup"><span data-stu-id="0c172-264">This is very important for reconciling the invoice with your system information.</span></span></p></td>
<td><span data-ttu-id="0c172-265">測試客戶 A</span><span class="sxs-lookup"><span data-stu-id="0c172-265">Test Customer A</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="0c172-266">MPNID</span><span class="sxs-lookup"><span data-stu-id="0c172-266">MPNID</span></span></td>
<td><p><span data-ttu-id="0c172-267">雲端解決方案提供者合作夥伴的 MPN 識別碼。</span><span class="sxs-lookup"><span data-stu-id="0c172-267">MPN ID of the CSP partner.</span></span></p></td>
<td><span data-ttu-id="0c172-268">4390934</span><span class="sxs-lookup"><span data-stu-id="0c172-268">4390934</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="0c172-269">ResellerMPNID</span><span class="sxs-lookup"><span data-stu-id="0c172-269">ResellerMPNID</span></span></td>
<td><p><span data-ttu-id="0c172-270">訂閱記錄中的經銷商 MPN 識別碼。</span><span class="sxs-lookup"><span data-stu-id="0c172-270">MPN ID of the reseller of record for the subscription.</span></span> <span data-ttu-id="0c172-271">請參閱<a href="#itemizebypartner" data-raw-source="[Itemize by partner](#itemizebypartner)">依合作夥伴詳細列舉</a>。</span><span class="sxs-lookup"><span data-stu-id="0c172-271">See <a href="#itemizebypartner" data-raw-source="[Itemize by partner](#itemizebypartner)">Itemize by partner</a>.</span></span></p></td>
<td><span data-ttu-id="0c172-272">4390934</span><span class="sxs-lookup"><span data-stu-id="0c172-272">4390934</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="0c172-273">InvoiceNumber</span><span class="sxs-lookup"><span data-stu-id="0c172-273">InvoiceNumber</span></span></td>
<td><p><span data-ttu-id="0c172-274">交易的指定位置顯示的發票號碼。</span><span class="sxs-lookup"><span data-stu-id="0c172-274">Invoice number where the specified transaction appears.</span></span></p></td>
<td><span data-ttu-id="0c172-275">D020001IVK</span><span class="sxs-lookup"><span data-stu-id="0c172-275">D020001IVK</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="0c172-276">ChargeStartDate</span><span class="sxs-lookup"><span data-stu-id="0c172-276">ChargeStartDate</span></span></td>
<td><p><span data-ttu-id="0c172-277">計費週期的開始日期，當顯示之前未收取潛在使用量資料費用的日期時除外 (從前一個計費週期開始)。</span><span class="sxs-lookup"><span data-stu-id="0c172-277">Start date of billing cycle except when presenting dates of previously uncharged latent usage data (from previous bill cycle).</span></span></p>
<p><span data-ttu-id="0c172-278">時間一律是一天的開始時間 (0:00)。</span><span class="sxs-lookup"><span data-stu-id="0c172-278">The time is always the beginning of the day, 0:00.</span></span></p></td>
<td><span data-ttu-id="0c172-279">2/1/2014 0:00</span><span class="sxs-lookup"><span data-stu-id="0c172-279">2/1/2014 0:00</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="0c172-280">ChargeEndDate</span><span class="sxs-lookup"><span data-stu-id="0c172-280">ChargeEndDate</span></span></td>
<td><p><span data-ttu-id="0c172-281">計費週期的結束日期，當顯示之前未收取潛在使用量資料費用的日期時除外 (從前一個計費週期開始)。</span><span class="sxs-lookup"><span data-stu-id="0c172-281">End date of billing cycle except when presenting dates of previously uncharged latent usage data (from previous bill cycle).</span></span></p>
<p><span data-ttu-id="0c172-282">時間一律是一天的結束時間 (23:59)。</span><span class="sxs-lookup"><span data-stu-id="0c172-282">The time is always the end of the day, 23:59.</span></span></p></td>
<td><span data-ttu-id="0c172-283">2/28/2014 23:59</span><span class="sxs-lookup"><span data-stu-id="0c172-283">2/28/2014 23:59</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="0c172-284">SubscriptionID</span><span class="sxs-lookup"><span data-stu-id="0c172-284">SubscriptionID</span></span></td>
<td><p><span data-ttu-id="0c172-285">訂閱在 Microsoft 帳單平台中的唯一識別碼。</span><span class="sxs-lookup"><span data-stu-id="0c172-285">Unique identifier for a subscription in the Microsoft billing platform.</span></span> <span data-ttu-id="0c172-286">可在連絡支援時方便識別訂閱，但不是用於對帳。</span><span class="sxs-lookup"><span data-stu-id="0c172-286">May be useful to identify the subscription when contacting support but not for reconciliation.</span></span></p>
<p><span data-ttu-id="0c172-287">這與合作夥伴管理主控台上的訂閱識別碼不一樣。</span><span class="sxs-lookup"><span data-stu-id="0c172-287">This is not the same as the Subscription ID on the Partner Admin Console.</span></span></p></td>
<td><span data-ttu-id="0c172-288">usCBMgAAAAAAAAIA</span><span class="sxs-lookup"><span data-stu-id="0c172-288">usCBMgAAAAAAAAIA</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="0c172-289">SubscriptionName</span><span class="sxs-lookup"><span data-stu-id="0c172-289">SubscriptionName</span></span></td>
<td><p><span data-ttu-id="0c172-290">服務優惠的暱稱。</span><span class="sxs-lookup"><span data-stu-id="0c172-290">Nickname of the service offering.</span></span></p></td>
<td><span data-ttu-id="0c172-291">Microsoft Azure</span><span class="sxs-lookup"><span data-stu-id="0c172-291">Microsoft Azure</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="0c172-292">SubscriptionDescription</span><span class="sxs-lookup"><span data-stu-id="0c172-292">SubscriptionDescription</span></span></td>
<td><p><span data-ttu-id="0c172-293">服務優惠的企業營運</span><span class="sxs-lookup"><span data-stu-id="0c172-293">Line of business of the service offering</span></span></p></td>
<td><span data-ttu-id="0c172-294">Microsoft Azure</span><span class="sxs-lookup"><span data-stu-id="0c172-294">Microsoft Azure</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="0c172-295">OrderID</span><span class="sxs-lookup"><span data-stu-id="0c172-295">OrderID</span></span></td>
<td><p><span data-ttu-id="0c172-296">訂單在 Microsoft 帳單平台中的唯一識別碼。</span><span class="sxs-lookup"><span data-stu-id="0c172-296">Unique identifier for an order in the Microsoft billing platform.</span></span> <span data-ttu-id="0c172-297">可在連絡支援時方便識別訂閱，但不是用於對帳。</span><span class="sxs-lookup"><span data-stu-id="0c172-297">May be useful to identify the subscription when contacting support but not for reconciliation.</span></span></p></td>
<td><span data-ttu-id="0c172-298">566890604832738111</span><span class="sxs-lookup"><span data-stu-id="0c172-298">566890604832738111</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="0c172-299">ServiceName</span><span class="sxs-lookup"><span data-stu-id="0c172-299">ServiceName</span></span></td>
<td><p><span data-ttu-id="0c172-300">要求的 Azure 服務名稱。</span><span class="sxs-lookup"><span data-stu-id="0c172-300">The name of the Azure service in question.</span></span></p></td>
<td><span data-ttu-id="0c172-301">虛擬機器</span><span class="sxs-lookup"><span data-stu-id="0c172-301">VIRTUAL MACHINES</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="0c172-302">ServiceType</span><span class="sxs-lookup"><span data-stu-id="0c172-302">ServiceType</span></span></td>
<td><p><span data-ttu-id="0c172-303">Microsoft Azure 服務的特定類型。</span><span class="sxs-lookup"><span data-stu-id="0c172-303">The specific type of Windows Azure service.</span></span></p></td>
<td><ul>
<li><span data-ttu-id="0c172-304">服務匯流排 – 個人或套件</span><span class="sxs-lookup"><span data-stu-id="0c172-304">Service Bus – Individual or Pack</span></span></li>
<li><span data-ttu-id="0c172-305">SQL Azure 資料庫 – Business 或 Web Edition</span><span class="sxs-lookup"><span data-stu-id="0c172-305">SQL Azure database – Business or Web Edition</span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="0c172-306">ResourceGUID</span><span class="sxs-lookup"><span data-stu-id="0c172-306">ResourceGUID</span></span></td>
<td><p><span data-ttu-id="0c172-307">所有服務資料與定價結構的特定唯一識別碼。</span><span class="sxs-lookup"><span data-stu-id="0c172-307">Specific unique identifier for all the service data and pricing structure.</span></span></p></td>
<td><span data-ttu-id="0c172-308">DA41BC5F-C52D-4464-8A8D-8C8DCC43503B</span><span class="sxs-lookup"><span data-stu-id="0c172-308">DA41BC5F-C52D-4464-8A8D-8C8DCC43503B</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="0c172-309">Resource Name</span><span class="sxs-lookup"><span data-stu-id="0c172-309">Resource Name</span></span></td>
<td><p><span data-ttu-id="0c172-310">Azure 資源的名稱。</span><span class="sxs-lookup"><span data-stu-id="0c172-310">The name of the Azure resource.</span></span></p></td>
<td><ul>
<li><span data-ttu-id="0c172-311">資料轉入 (GB)</span><span class="sxs-lookup"><span data-stu-id="0c172-311">Data Transfer In (GB)</span></span></li>
<li><span data-ttu-id="0c172-312">資料轉出 (GB)</span><span class="sxs-lookup"><span data-stu-id="0c172-312">Data Transfer Out (GB)</span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="0c172-313">地區</span><span class="sxs-lookup"><span data-stu-id="0c172-313">Region</span></span></td>
<td><p><span data-ttu-id="0c172-314">使用量適用的地區。</span><span class="sxs-lookup"><span data-stu-id="0c172-314">The region the usage applies to.</span></span> <span data-ttu-id="0c172-315">主要用來指定資料傳輸速率，費率因地區而異。</span><span class="sxs-lookup"><span data-stu-id="0c172-315">Primarily used to assign rates to data transfers, as rates vary by region.</span></span></p></td>
<td><span data-ttu-id="0c172-316">亞太地區、歐洲、拉丁美洲、北美洲</span><span class="sxs-lookup"><span data-stu-id="0c172-316">Asia Pacific, Europe, Latin America, North America</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="0c172-317">SKU</span><span class="sxs-lookup"><span data-stu-id="0c172-317">SKU</span></span></td>
<td><p><span data-ttu-id="0c172-318">優惠的 MSFT 唯一識別碼</span><span class="sxs-lookup"><span data-stu-id="0c172-318">MSFT unique identifier for offer</span></span></p></td>
<td><span data-ttu-id="0c172-319">7UD 00001</span><span class="sxs-lookup"><span data-stu-id="0c172-319">7UD-00001</span></span></td>
</tr>
<tr class="odd">
<td><p><span data-ttu-id="0c172-320">DetailLineItemId</span><span class="sxs-lookup"><span data-stu-id="0c172-320">DetailLineItemId</span></span></p></td>
<td><p><span data-ttu-id="0c172-321">用於詳細列出指定計費期間中，服務或資源不同費率的識別碼和數量。</span><span class="sxs-lookup"><span data-stu-id="0c172-321">An ID and quantity for itemizing the different rates for a service or resource in a given billing period.</span></span> <span data-ttu-id="0c172-322">對於 Azure 分層評分，到某個數量的計費單位會有一個評分，之後則有不同評分。</span><span class="sxs-lookup"><span data-stu-id="0c172-322">For Azure tiered rating, there may be one rate up to a certain quantity of billable units, then a different rate after that.</span></span></p></td>
<td><span data-ttu-id="0c172-323">1</span><span class="sxs-lookup"><span data-stu-id="0c172-323">1</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="0c172-324">ConsumedQuantity</span><span class="sxs-lookup"><span data-stu-id="0c172-324">ConsumedQuantity</span></span></td>
<td><p><span data-ttu-id="0c172-325">報表期間耗用的服務量 (小時、GB 等等)</span><span class="sxs-lookup"><span data-stu-id="0c172-325">The amount of service consumed (hours, GB, etc.) during the reporting period.</span></span></p>
<p><span data-ttu-id="0c172-326">同時包括先前報表期間任何未計費的使用量。</span><span class="sxs-lookup"><span data-stu-id="0c172-326">Also includes any unbilled usage from previous reporting periods.</span></span></p></td>
<td><span data-ttu-id="0c172-327">11</span><span class="sxs-lookup"><span data-stu-id="0c172-327">11</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="0c172-328">IncludedQuantity</span><span class="sxs-lookup"><span data-stu-id="0c172-328">IncludedQuantity</span></span></td>
<td><p><span data-ttu-id="0c172-329">包含在優惠中的單位。</span><span class="sxs-lookup"><span data-stu-id="0c172-329">Units included as part of the offer.</span></span> <span data-ttu-id="0c172-330">通常不會出現在雲端解決方案提供者中。</span><span class="sxs-lookup"><span data-stu-id="0c172-330">Not typically present in CSP.</span></span></p></td>
<td><span data-ttu-id="0c172-331">0</span><span class="sxs-lookup"><span data-stu-id="0c172-331">0</span></span></td>
</tr>
<tr class="even">
<td><p><span data-ttu-id="0c172-332">OverageQuantity</span><span class="sxs-lookup"><span data-stu-id="0c172-332">OverageQuantity</span></span></p></td>
<td><p><span data-ttu-id="0c172-333">不包含在優惠中的單位，必須由合作夥伴支付。</span><span class="sxs-lookup"><span data-stu-id="0c172-333">Units not included as part of the offer, that must be paid for by the partner.</span></span></p>
<p><span data-ttu-id="0c172-334">等同於 ConsumedQuantity - IncludedQuantity。</span><span class="sxs-lookup"><span data-stu-id="0c172-334">Equal to the ConsumedQuantity - IncludedQuantity.</span></span></p></td>
<td><span data-ttu-id="0c172-335">11</span><span class="sxs-lookup"><span data-stu-id="0c172-335">11</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="0c172-336">ListPrice</span><span class="sxs-lookup"><span data-stu-id="0c172-336">ListPrice</span></span></td>
<td><p><span data-ttu-id="0c172-337">訂閱開始日期的生效優惠價格。</span><span class="sxs-lookup"><span data-stu-id="0c172-337">Offer price in effect at subscription start date.</span></span></p></td>
<td><span data-ttu-id="0c172-338">$0.0808</span><span class="sxs-lookup"><span data-stu-id="0c172-338">$0.0808</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="0c172-339">PretaxCharges</span><span class="sxs-lookup"><span data-stu-id="0c172-339">PretaxCharges</span></span></td>
<td><p><span data-ttu-id="0c172-340">ListPrist 乘以 OverageQuantity，四捨五入至美分。</span><span class="sxs-lookup"><span data-stu-id="0c172-340">ListPrist times OverageQuantity, rounded to the nearest cent.</span></span></p></td>
<td><span data-ttu-id="0c172-341">$0.085</span><span class="sxs-lookup"><span data-stu-id="0c172-341">$0.085</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="0c172-342">TaxAmount</span><span class="sxs-lookup"><span data-stu-id="0c172-342">TaxAmount</span></span></td>
<td><p><span data-ttu-id="0c172-343">稅金費用，根據您 market& #39; s 稅金規則與特定情況。</span><span class="sxs-lookup"><span data-stu-id="0c172-343">Tax amount charge, based on your market&#39;s tax rules and specific circumstances.</span></span></p></td>
<td><span data-ttu-id="0c172-344">$0.08</span><span class="sxs-lookup"><span data-stu-id="0c172-344">$0.08</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="0c172-345">PostTaxTotal</span><span class="sxs-lookup"><span data-stu-id="0c172-345">PostTaxTotal</span></span></td>
<td><p><span data-ttu-id="0c172-346">稅後總計 (當適用稅金時)。</span><span class="sxs-lookup"><span data-stu-id="0c172-346">Total after tax, when tax is applicable.</span></span></p></td>
<td><span data-ttu-id="0c172-347">$0.93</span><span class="sxs-lookup"><span data-stu-id="0c172-347">$0.93</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="0c172-348">Currency</span><span class="sxs-lookup"><span data-stu-id="0c172-348">Currency</span></span></td>
<td><p><span data-ttu-id="0c172-349">貨幣類型。</span><span class="sxs-lookup"><span data-stu-id="0c172-349">Currency type.</span></span> <span data-ttu-id="0c172-350">每一帳單實體都只有一種貨幣。</span><span class="sxs-lookup"><span data-stu-id="0c172-350">Each billing entity has only one currency.</span></span> <span data-ttu-id="0c172-351">檢查是否與您的第一張發票相符，然後在進行任何重大帳單平台更新之後檢查。</span><span class="sxs-lookup"><span data-stu-id="0c172-351">Check that it matches your first invoice and then after any major billing platform update.</span></span></p></td>
<td><span data-ttu-id="0c172-352">EUR</span><span class="sxs-lookup"><span data-stu-id="0c172-352">EUR</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="0c172-353">PretaxEffectiveRate</span><span class="sxs-lookup"><span data-stu-id="0c172-353">PretaxEffectiveRate</span></span></td>
<td><p><span data-ttu-id="0c172-354">每個單位的稅前價格。</span><span class="sxs-lookup"><span data-stu-id="0c172-354">Pretax price per unit.</span></span> <span data-ttu-id="0c172-355">等於 PretaxCharges / OverageQuantity, 四捨五入至美分。</span><span class="sxs-lookup"><span data-stu-id="0c172-355">Equal to PretaxCharges / OverageQuantity, rounded to the nearest cent.</span></span></p></td>
<td><span data-ttu-id="0c172-356">$0.08</span><span class="sxs-lookup"><span data-stu-id="0c172-356">$0.08</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="0c172-357">PostTaxEffectiveRate</span><span class="sxs-lookup"><span data-stu-id="0c172-357">PostTaxEffectiveRate</span></span></td>
<td><p><span data-ttu-id="0c172-358">每個單位的稅後價格。</span><span class="sxs-lookup"><span data-stu-id="0c172-358">Post tax price per unit.</span></span> <span data-ttu-id="0c172-359">等於 PostTaxTotal / OverageQuantity，或 PretaxEffectiveRate + 每單位數量稅率，四捨五入至美分。</span><span class="sxs-lookup"><span data-stu-id="0c172-359">Equal to PostTaxTotal / OverageQuantity, or PretaxEffectiveRate + tax rate per unit amoun, rounded to the nearest cent.</span></span></p></td>
<td><span data-ttu-id="0c172-360">$0.08</span><span class="sxs-lookup"><span data-stu-id="0c172-360">$0.08</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="0c172-361">ChargeType</span><span class="sxs-lookup"><span data-stu-id="0c172-361">ChargeType</span></span></td>
<td><p><span data-ttu-id="0c172-362">費用或調整的類型。</span><span class="sxs-lookup"><span data-stu-id="0c172-362">The type of charge or adjustment.</span></span> <span data-ttu-id="0c172-363">請參閱<a href="#charge_types">對應發票和對帳檔案之間的費用</a></span><span class="sxs-lookup"><span data-stu-id="0c172-363">See <a href="#charge_types">Mapping charges between an invoice and the reconciliation file</a></span></span></p></td>
<td><p><span data-ttu-id="0c172-364">請參閱<a href="#charge_types">對應發票和對帳檔案之間的費用</a></span><span class="sxs-lookup"><span data-stu-id="0c172-364">See <a href="#charge_types">Mapping charges between an invoice and the reconciliation file</a></span></span></p></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="0c172-365">CustomerBillableAccount</span><span class="sxs-lookup"><span data-stu-id="0c172-365">CustomerBillableAccount</span></span></td>
<td><p><span data-ttu-id="0c172-366">MSFT 帳單平台的唯一帳戶識別碼。</span><span class="sxs-lookup"><span data-stu-id="0c172-366">Unique account ID in the MSFT billing platform.</span></span></p></td>
<td><span data-ttu-id="0c172-367">1280018095</span><span class="sxs-lookup"><span data-stu-id="0c172-367">1280018095</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="0c172-368">UsageDate</span><span class="sxs-lookup"><span data-stu-id="0c172-368">UsageDate</span></span></td>
<td><p><span data-ttu-id="0c172-369">服務部署的日期。</span><span class="sxs-lookup"><span data-stu-id="0c172-369">Date of service deployment.</span></span></p></td>
<td><span data-ttu-id="0c172-370">2/1/2014 0:00</span><span class="sxs-lookup"><span data-stu-id="0c172-370">2/1/2014 0:00</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="0c172-371">MeteredRegion</span><span class="sxs-lookup"><span data-stu-id="0c172-371">MeteredRegion</span></span></td>
<td><p><span data-ttu-id="0c172-372">此欄可識別適用及填入此項目之服務地區內的資料中心的位置。</span><span class="sxs-lookup"><span data-stu-id="0c172-372">This column identifies the location of a data center within the region for services where this is applicable and populated.</span></span></p></td>
<td><span data-ttu-id="0c172-373">東亞、東南亞、北歐、西歐、美國中北部、美國中南部</span><span class="sxs-lookup"><span data-stu-id="0c172-373">East Asia, South East Asia, North Europe, West Europe, North Central US, South Central US</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="0c172-374">MeteredService</span><span class="sxs-lookup"><span data-stu-id="0c172-374">MeteredService</span></span></td>
<td><p><span data-ttu-id="0c172-375">此欄是用來追蹤可能未在 \[服務名稱\] 欄中特別指出的個別 Microsoft Azure 服務。</span><span class="sxs-lookup"><span data-stu-id="0c172-375">This column is utilized to track the individual Microsoft Azure service that may not be specifically identified in the Service Name column.</span></span> <span data-ttu-id="0c172-376">例如，在 \[服務名稱\] 欄中，資料傳輸是回報為 &quot;Microsoft Azure - 所有服務&quot;。</span><span class="sxs-lookup"><span data-stu-id="0c172-376">For example, data transfers are reported as &quot;Microsoft Azure - All Services&quot; in the Service Name column.</span></span> <span data-ttu-id="0c172-377">此 MeteredService 欄會指出使用量與哪個特定服務有關。</span><span class="sxs-lookup"><span data-stu-id="0c172-377">This MeteredService column will indicate to which specific service the usage pertains.</span></span></p></td>
<td><span data-ttu-id="0c172-378">AccessControl、CDN、Compute、Database、ServiceBus、Storage</span><span class="sxs-lookup"><span data-stu-id="0c172-378">AccessControl, CDN, Compute, Database, ServiceBus, Storage</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="0c172-379">MeteredServiceType</span><span class="sxs-lookup"><span data-stu-id="0c172-379">MeteredServiceType</span></span></td>
<td><p><span data-ttu-id="0c172-380">進一步釐清超出 MeteredService 欄位提供之層級的個別 Microsoft Azure 服務副標題。</span><span class="sxs-lookup"><span data-stu-id="0c172-380">A subheading that further clarifies the individual Microsoft Azure service beyond the level provided by the MeteredService field.</span></span></p></td>
<td><span data-ttu-id="0c172-381">外部</span><span class="sxs-lookup"><span data-stu-id="0c172-381">EXTERNAL</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="0c172-382">Project</span><span class="sxs-lookup"><span data-stu-id="0c172-382">Project</span></span></td>
<td><p><span data-ttu-id="0c172-383">客戶為其服務執行個體定義的名稱</span><span class="sxs-lookup"><span data-stu-id="0c172-383">Customer-defined name for their service instance</span></span></p></td>
<td><span data-ttu-id="0c172-384">ORDDC52E52FDEF405786F0642DD0108BE4</span><span class="sxs-lookup"><span data-stu-id="0c172-384">ORDDC52E52FDEF405786F0642DD0108BE4</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="0c172-385">ServiceInfo</span><span class="sxs-lookup"><span data-stu-id="0c172-385">ServiceInfo</span></span></td>
<td><p><span data-ttu-id="0c172-386">於某一天佈建及使用的 ServiceBus 連線數目。</span><span class="sxs-lookup"><span data-stu-id="0c172-386">The number of ServiceBus connections that were provisioned and utilized on a given day.</span></span></p></td>
<td><span data-ttu-id="0c172-387">例如：如果您在有 30 天的月份中有個別佈建的連線時，「服務資訊 1」的讀數會是「1.000000 連線 / 30 天」。</span><span class="sxs-lookup"><span data-stu-id="0c172-387">For example: if you had an individually provisioned connection during a 30 day month, Service Info 1 would read “1.000000 Connections / 30 days”.</span></span> <span data-ttu-id="0c172-388">如果您佈建 25 組 ServiceBus 連線並在那天使用其中一組，那一天的每日使用量就會指示「25 組連線 / 30 天 - 已使用：1.000000」。</span><span class="sxs-lookup"><span data-stu-id="0c172-388">If you had a 25 pack of ServiceBus connections provisioned and you had utilized 1 during that day, your daily usage statement for that day would indicate “25 Connections / 30 Days – Used: 1.000000”.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="0c172-389">CustomerID</span><span class="sxs-lookup"><span data-stu-id="0c172-389">CustomerID</span></span></td>
<td><p><span data-ttu-id="0c172-390">用來識別客戶的唯一 Microsoft ID（GUID 格式）。</span><span class="sxs-lookup"><span data-stu-id="0c172-390">Unique Microsoft ID, in GUID format, used to identify the customer.</span></span></p></td>
<td><span data-ttu-id="0c172-391">ORDDC52E52FDEF405786F0642DD0108BE4</span><span class="sxs-lookup"><span data-stu-id="0c172-391">ORDDC52E52FDEF405786F0642DD0108BE4</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="0c172-392">DomainName</span><span class="sxs-lookup"><span data-stu-id="0c172-392">DomainName</span></span></td>
<td><p><span data-ttu-id="0c172-393">Customer& #39; s 網域名稱，用來協助識別客戶。</span><span class="sxs-lookup"><span data-stu-id="0c172-393">Customer&#39;s domain name, used to help identify the customer.</span></span> <span data-ttu-id="0c172-394">在下一個帳單週期之前，此欄位會是空白的。</span><span class="sxs-lookup"><span data-stu-id="0c172-394">This field may appear blank until the second billing cycle.</span></span></p></td>
<td><span data-ttu-id="0c172-395">example.onmicrosoft.com</span><span class="sxs-lookup"><span data-stu-id="0c172-395">example.onmicrosoft.com</span></span></td></tr>
</tr>
<tr class="even">
<td><span data-ttu-id="0c172-396">Unit</span><span class="sxs-lookup"><span data-stu-id="0c172-396">Unit</span></span></td>
<td><p><span data-ttu-id="0c172-397">資源名稱的單位</span><span class="sxs-lookup"><span data-stu-id="0c172-397">The unit of the resource Name</span></span></p></td>
<td><span data-ttu-id="0c172-398">GB 或 HOURS</span><span class="sxs-lookup"><span data-stu-id="0c172-398">GB or HOURS</span></span></td>
</tr>
</tbody>
</table>

## <a href="" id="marketplacefilefields"></a><span data-ttu-id="0c172-399">一次性和週期性檔案欄位</span><span class="sxs-lookup"><span data-stu-id="0c172-399">One-time and recurring file fields</span></span>

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th><span data-ttu-id="0c172-400">欄位</span><span class="sxs-lookup"><span data-stu-id="0c172-400">Column</span></span></th>
<th><span data-ttu-id="0c172-401">描述</span><span class="sxs-lookup"><span data-stu-id="0c172-401">Description</span></span></th>
</tr>
</thead>
<tbody>


<tr class="odd">
<td><span data-ttu-id="0c172-402">PartnerId</span><span class="sxs-lookup"><span data-stu-id="0c172-402">PartnerId</span></span></td>
<td><p><span data-ttu-id="0c172-403">特定帳單實體，GUID 格式的唯一 Microsoft Azure Active Directory 租用戶識別碼。</span><span class="sxs-lookup"><span data-stu-id="0c172-403">Unique Microsoft Azure Active Directory tenant identifier for a specific billing entity, in GUID format.</span></span> <span data-ttu-id="0c172-404">對帳時不需要，但可能是很有用的資訊。</span><span class="sxs-lookup"><span data-stu-id="0c172-404">Not required for reconciliation, however may be useful information.</span></span> <span data-ttu-id="0c172-405">在所有資料列中都是如此。</span><span class="sxs-lookup"><span data-stu-id="0c172-405">Same in all rows.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="0c172-406">客戶識別碼</span><span class="sxs-lookup"><span data-stu-id="0c172-406">Customer Id</span></span></td>
<td><p><span data-ttu-id="0c172-407">唯一 Microsoft Azure Active Directory 租用戶識別碼，用來識別客戶的 GUID 格式中。</span><span class="sxs-lookup"><span data-stu-id="0c172-407">Unique Microsoft Azure Active Directory tenant ID, in GUID format, used to identify the customer.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="0c172-408">[客戶名稱]</span><span class="sxs-lookup"><span data-stu-id="0c172-408">Customer Name</span></span></td>
<td><p><span data-ttu-id="0c172-409">合作夥伴中心中回報的客戶組織名稱。</span><span class="sxs-lookup"><span data-stu-id="0c172-409">Customer's organization name as reported in Partner Center.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="0c172-410">CustomerDomainName</span><span class="sxs-lookup"><span data-stu-id="0c172-410">CustomerDomainName</span></span></td>
<td><p><span data-ttu-id="0c172-411">用來協助識別客戶的客戶網域名稱。</span><span class="sxs-lookup"><span data-stu-id="0c172-411">Customer's domain name, used to help identify the customer.</span></span> <span data-ttu-id="0c172-412">這不應該用來唯一識別客戶，因為客戶/合作夥伴可以更新透過 O365 入口網站的預設虛名/網域。</span><span class="sxs-lookup"><span data-stu-id="0c172-412">This should not be used to uniquely identify the customer as the customer/partner can update the vanity/default domain via the O365 portal.</span></span> <span data-ttu-id="0c172-413">在下一個帳單週期之前，此欄位會是空白的。</span><span class="sxs-lookup"><span data-stu-id="0c172-413">This field may appear blank until the second billing cycle.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="0c172-414">客戶的國家/地區</span><span class="sxs-lookup"><span data-stu-id="0c172-414">Customer Country</span></span></td>
<td><p><span data-ttu-id="0c172-415">客戶所在的國家/地區。</span><span class="sxs-lookup"><span data-stu-id="0c172-415">The country in which the customer is located.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="0c172-416">發票號碼</span><span class="sxs-lookup"><span data-stu-id="0c172-416">Invoice number</span></span></td>
<td><p><span data-ttu-id="0c172-417">交易的指定位置顯示的發票號碼。</span><span class="sxs-lookup"><span data-stu-id="0c172-417">Invoice number where the specified transaction appears.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="0c172-418">MpnId</span><span class="sxs-lookup"><span data-stu-id="0c172-418">MpnId</span></span></td>
<td><p><span data-ttu-id="0c172-419">雲端解決方案提供者合作夥伴的 MPN 識別碼。</span><span class="sxs-lookup"><span data-stu-id="0c172-419">MPN ID of the CSP partner.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="0c172-420">經銷商 MpnId</span><span class="sxs-lookup"><span data-stu-id="0c172-420">Reseller MpnId</span></span></td>
<td><p><span data-ttu-id="0c172-421">訂閱記錄中的經銷商 MPN 識別碼。</span><span class="sxs-lookup"><span data-stu-id="0c172-421">MPN ID of the reseller of record for the subscription.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="0c172-422">訂單識別碼</span><span class="sxs-lookup"><span data-stu-id="0c172-422">Order ID</span></span></td>
<td><p><span data-ttu-id="0c172-423">在 Microsoft 交易平台的訂單的唯一識別碼。</span><span class="sxs-lookup"><span data-stu-id="0c172-423">Unique identifier for an order in the Microsoft commerce platform.</span></span> <span data-ttu-id="0c172-424">可在連絡支援時方便識別訂單，但不是用於對帳。</span><span class="sxs-lookup"><span data-stu-id="0c172-424">May be useful to identify the order when contacting support but not for reconciliation.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="0c172-425">訂單日期</span><span class="sxs-lookup"><span data-stu-id="0c172-425">Order date</span></span></td>
<td><p><span data-ttu-id="0c172-426">下訂單的日期。</span><span class="sxs-lookup"><span data-stu-id="0c172-426">The date the order was placed.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="0c172-427">ProductId</span><span class="sxs-lookup"><span data-stu-id="0c172-427">ProductId</span></span></td>
<td><p><span data-ttu-id="0c172-428">產品的識別碼。</span><span class="sxs-lookup"><span data-stu-id="0c172-428">The ID for the product.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="0c172-429">SkuId</span><span class="sxs-lookup"><span data-stu-id="0c172-429">SkuId</span></span></td>
<td><p><span data-ttu-id="0c172-430">特定 SKU 的識別碼。</span><span class="sxs-lookup"><span data-stu-id="0c172-430">The ID for a particular SKU.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="0c172-431">AvailabilityId</span><span class="sxs-lookup"><span data-stu-id="0c172-431">AvailabilityId</span></span></td>
<td><p><span data-ttu-id="0c172-432">特定可用性的識別碼。</span><span class="sxs-lookup"><span data-stu-id="0c172-432">The ID for a particular Availability.</span></span> <span data-ttu-id="0c172-433">「可用性」是指特定 SKU 是否可供特定的國家/地區、貨幣、行業區段等等購買。</span><span class="sxs-lookup"><span data-stu-id="0c172-433">“Availability” refers to whether or not a particular SKU is available for purchase for the given country, currency, industry segment, etc.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="0c172-434">SKU 的名稱</span><span class="sxs-lookup"><span data-stu-id="0c172-434">SKU Name</span></span></td>
<td><p><span data-ttu-id="0c172-435">特定 SKU 的標題。</span><span class="sxs-lookup"><span data-stu-id="0c172-435">The title for a particular SKU.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="0c172-436">產品名稱</span><span class="sxs-lookup"><span data-stu-id="0c172-436">Product name</span></span></td>
<td><p><span data-ttu-id="0c172-437">產品的名稱。</span><span class="sxs-lookup"><span data-stu-id="0c172-437">The name of the product.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="0c172-438">PublisherName</span><span class="sxs-lookup"><span data-stu-id="0c172-438">PublisherName</span></span></td>
<td><p><span data-ttu-id="0c172-439">產品發行者的名稱。</span><span class="sxs-lookup"><span data-stu-id="0c172-439">The name of the product’s publisher.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="0c172-440">PublisherID</span><span class="sxs-lookup"><span data-stu-id="0c172-440">PublisherID</span></span></td>
<td><p><span data-ttu-id="0c172-441">針對此發行者的唯一識別碼。</span><span class="sxs-lookup"><span data-stu-id="0c172-441">Unique ID for this publisher.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="0c172-442">訂閱描述</span><span class="sxs-lookup"><span data-stu-id="0c172-442">Subscription Description</span></span></td>
<td><p><span data-ttu-id="0c172-443">訂閱的易記名稱。</span><span class="sxs-lookup"><span data-stu-id="0c172-443">Friendly name of a subscription.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="0c172-444">訂閱識別碼</span><span class="sxs-lookup"><span data-stu-id="0c172-444">Subscription ID</span></span></td>
<td><p><span data-ttu-id="0c172-445">訂閱在 Microsoft 交易平台的唯一識別碼。</span><span class="sxs-lookup"><span data-stu-id="0c172-445">Unique identifier for a subscription in the Microsoft commerce platform.</span></span> <span data-ttu-id="0c172-446">可在連絡支援時方便識別訂閱，但不是用於對帳。</span><span class="sxs-lookup"><span data-stu-id="0c172-446">May be useful to identify the subscription when contacting support but not for reconciliation.</span></span> <span data-ttu-id="0c172-447">這與合作夥伴管理主控台上的訂閱識別碼不一樣。</span><span class="sxs-lookup"><span data-stu-id="0c172-447">This is not the same as the Subscription ID on the Partner Admin Console.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="0c172-448">ChargeStartDate</span><span class="sxs-lookup"><span data-stu-id="0c172-448">ChargeStartDate</span></span></td>
<td><p><span data-ttu-id="0c172-449">開始計算費用的日期。</span><span class="sxs-lookup"><span data-stu-id="0c172-449">Start day of the charges.</span></span> <span data-ttu-id="0c172-450">時間一律是一天的開始時間 (0:00)。</span><span class="sxs-lookup"><span data-stu-id="0c172-450">The time is always the beginning of the day, 0:00.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="0c172-451">ChargeEndDate</span><span class="sxs-lookup"><span data-stu-id="0c172-451">ChargeEndDate</span></span></td>
<td><p><span data-ttu-id="0c172-452">結束計算費用的日期。</span><span class="sxs-lookup"><span data-stu-id="0c172-452">End day of the charges.</span></span> <span data-ttu-id="0c172-453">時間一律是一天的結束時間 (23:59)。</span><span class="sxs-lookup"><span data-stu-id="0c172-453">The time is always the end of the day, 23:59.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="0c172-454">詞彙和 Billingcycle</span><span class="sxs-lookup"><span data-stu-id="0c172-454">Term and Billingcycle</span></span></td>
<td><p><span data-ttu-id="0c172-455">詞彙的長度和帳單週期購買。</span><span class="sxs-lookup"><span data-stu-id="0c172-455">The term length and billing cycle for the purchase.</span></span> <span data-ttu-id="0c172-456">例如，「 1 年，每個月。 」</span><span class="sxs-lookup"><span data-stu-id="0c172-456">For example, “1 Year, Monthly.”</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="0c172-457">收費類型</span><span class="sxs-lookup"><span data-stu-id="0c172-457">Charge Type</span></span></td>
<td><p><span data-ttu-id="0c172-458">費用或調整的類型。</span><span class="sxs-lookup"><span data-stu-id="0c172-458">The type of charge or adjustment.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="0c172-459">單價</span><span class="sxs-lookup"><span data-stu-id="0c172-459">Unit Price</span></span></td>
<td><p><span data-ttu-id="0c172-460">價格如公佈的價格表中的購買。</span><span class="sxs-lookup"><span data-stu-id="0c172-460">The price as published in the pricelist at the time of purchase.</span></span> <span data-ttu-id="0c172-461">請確定這與對帳期間儲存在您帳單系統中的資訊相符。</span><span class="sxs-lookup"><span data-stu-id="0c172-461">Ensure this matches the information stored in your billing system during reconciliation.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="0c172-462">有效的單價</span><span class="sxs-lookup"><span data-stu-id="0c172-462">Effective Unit Price</span></span></td>
<td><p><span data-ttu-id="0c172-463">單價之後所做調整。</span><span class="sxs-lookup"><span data-stu-id="0c172-463">The unit price after adjustments have been made.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="0c172-464">數量</span><span class="sxs-lookup"><span data-stu-id="0c172-464">Quantity</span></span></td>
<td><p><span data-ttu-id="0c172-465">單位數。</span><span class="sxs-lookup"><span data-stu-id="0c172-465">Number of units.</span></span> <span data-ttu-id="0c172-466">請確定這與對帳期間儲存在您帳單系統中的資訊相符。</span><span class="sxs-lookup"><span data-stu-id="0c172-466">Ensure this matches the information stored in your billing system during reconciliation.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="0c172-467">單位類型</span><span class="sxs-lookup"><span data-stu-id="0c172-467">Unit type</span></span></td>
<td><p><span data-ttu-id="0c172-468">單位所購買的類型。</span><span class="sxs-lookup"><span data-stu-id="0c172-468">The type of unit being purchased.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="0c172-469">DiscountDetails</span><span class="sxs-lookup"><span data-stu-id="0c172-469">DiscountDetails</span></span></td>
<td><p><span data-ttu-id="0c172-470">任何適用的折扣的說明。</span><span class="sxs-lookup"><span data-stu-id="0c172-470">An explanation of any applicable discount.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="0c172-471">子總計</span><span class="sxs-lookup"><span data-stu-id="0c172-471">Sub Total</span></span></td>
<td><p><span data-ttu-id="0c172-472">稅前總計。</span><span class="sxs-lookup"><span data-stu-id="0c172-472">Total before tax.</span></span> <span data-ttu-id="0c172-473">如果有折扣，可檢查小計是否和預期的總金額相符。</span><span class="sxs-lookup"><span data-stu-id="0c172-473">Checks that your subtotal matches your expected total, in case of a discount.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="0c172-474">稅金總計</span><span class="sxs-lookup"><span data-stu-id="0c172-474">Tax Total</span></span></td>
<td><p><span data-ttu-id="0c172-475">稅金費用 (根據您所在市場的稅金規則與特定情況)。</span><span class="sxs-lookup"><span data-stu-id="0c172-475">Tax amount charge, based on your market's tax rules and specific circumstances.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="0c172-476">Total</span><span class="sxs-lookup"><span data-stu-id="0c172-476">Total</span></span></td>
<td><p><span data-ttu-id="0c172-477">稅後總計。</span><span class="sxs-lookup"><span data-stu-id="0c172-477">Total after tax.</span></span> <span data-ttu-id="0c172-478">檢查發票中是否向您收取稅金。</span><span class="sxs-lookup"><span data-stu-id="0c172-478">Checks if you are charged tax in the invoice.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="0c172-479">Currency</span><span class="sxs-lookup"><span data-stu-id="0c172-479">Currency</span></span></td>
<td><p><span data-ttu-id="0c172-480">貨幣類型。</span><span class="sxs-lookup"><span data-stu-id="0c172-480">Currency type.</span></span> <span data-ttu-id="0c172-481">每一帳單實體都只有一種貨幣。</span><span class="sxs-lookup"><span data-stu-id="0c172-481">Each billing entity has only one currency.</span></span> <span data-ttu-id="0c172-482">檢查是否與您的第一張發票相符，然後在進行任何重大帳單平台更新之後檢查。</span><span class="sxs-lookup"><span data-stu-id="0c172-482">Check that it matches your first invoice and then after any major billing platform update.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="0c172-483">AlternateID</span><span class="sxs-lookup"><span data-stu-id="0c172-483">AlternateID</span></span></td>
<td><p><span data-ttu-id="0c172-484">替代識別碼的識別碼。</span><span class="sxs-lookup"><span data-stu-id="0c172-484">An alternate identifier to an ID.</span></span></p></td>
</tr>
</tbody>
</table>


## <a href="" id="dailyratedusagefields"></a><span data-ttu-id="0c172-485">每日分級使用量檔案欄位</span><span class="sxs-lookup"><span data-stu-id="0c172-485">Daily-rated usage file fields</span></span>


<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th><span data-ttu-id="0c172-486">欄位</span><span class="sxs-lookup"><span data-stu-id="0c172-486">Column</span></span></th>
<th><span data-ttu-id="0c172-487">描述</span><span class="sxs-lookup"><span data-stu-id="0c172-487">Description</span></span></th>
</tr>
</thead>
<tbody>

<tr class="odd">
<td><span data-ttu-id="0c172-488">PartnerId</span><span class="sxs-lookup"><span data-stu-id="0c172-488">PartnerId</span></span></td>
<td><p><span data-ttu-id="0c172-489">合作夥伴識別碼 (GUID 格式)。</span><span class="sxs-lookup"><span data-stu-id="0c172-489">Partner ID, in GUID format.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="0c172-490">PartnerName</span><span class="sxs-lookup"><span data-stu-id="0c172-490">PartnerName</span></span></td>
<td><p><span data-ttu-id="0c172-491">合作夥伴名稱。</span><span class="sxs-lookup"><span data-stu-id="0c172-491">Partner Name.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="0c172-492">CustomerId</span><span class="sxs-lookup"><span data-stu-id="0c172-492">CustomerId</span></span></td>
<td><p><span data-ttu-id="0c172-493">用來識別客戶的唯一 Microsoft ID（GUID 格式）。</span><span class="sxs-lookup"><span data-stu-id="0c172-493">Unique Microsoft ID, in GUID format, used to identify the customer.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="0c172-494">CustomerCompanyName</span><span class="sxs-lookup"><span data-stu-id="0c172-494">CustomerCompanyName</span></span></td>
<td><p><span data-ttu-id="0c172-495">合作夥伴中心中回報的客戶組織名稱。</span><span class="sxs-lookup"><span data-stu-id="0c172-495">Customer's organization name as reported in Partner Center.</span></span> <span data-ttu-id="0c172-496">這在使用您的系統資訊對帳發票時非常重要。</span><span class="sxs-lookup"><span data-stu-id="0c172-496">This is very important for reconciling the invoice with your system information.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="0c172-497">CustomerDomainName</span><span class="sxs-lookup"><span data-stu-id="0c172-497">CustomerDomainName</span></span></td>
<td><p><span data-ttu-id="0c172-498">客戶的網域名稱。</span><span class="sxs-lookup"><span data-stu-id="0c172-498">The customer’s domain name.</span></span> <span data-ttu-id="0c172-499">沒有適用於目前的活動。</span><span class="sxs-lookup"><span data-stu-id="0c172-499">Not available for current activity.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="0c172-500">客戶的國家/地區</span><span class="sxs-lookup"><span data-stu-id="0c172-500">Customer country</span></span></td>
<td><p><span data-ttu-id="0c172-501">客戶所在的國家/地區。</span><span class="sxs-lookup"><span data-stu-id="0c172-501">The country in which the customer is located.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="0c172-502">MPNID</span><span class="sxs-lookup"><span data-stu-id="0c172-502">MPNID</span></span></td>
<td><p><span data-ttu-id="0c172-503">雲端解決方案提供者合作夥伴的 MPN 識別碼。</span><span class="sxs-lookup"><span data-stu-id="0c172-503">MPN ID of the CSP partner.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="0c172-504">MPNID 經銷商</span><span class="sxs-lookup"><span data-stu-id="0c172-504">Reseller MPNID</span></span></td>
<td><p><span data-ttu-id="0c172-505">訂閱記錄中的經銷商 MPN 識別碼。</span><span class="sxs-lookup"><span data-stu-id="0c172-505">MPN ID of the reseller of record for the subscription.</span></span> <span data-ttu-id="0c172-506">沒有適用於目前的活動。</span><span class="sxs-lookup"><span data-stu-id="0c172-506">Not available for current activity.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="0c172-507">InvoiceNumber</span><span class="sxs-lookup"><span data-stu-id="0c172-507">InvoiceNumber</span></span></td>
<td><p><span data-ttu-id="0c172-508">交易的指定位置顯示的發票號碼。</span><span class="sxs-lookup"><span data-stu-id="0c172-508">Invoice number where the specified transaction appears.</span></span> <span data-ttu-id="0c172-509">沒有適用於目前的活動。</span><span class="sxs-lookup"><span data-stu-id="0c172-509">Not available for current activity.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="0c172-510">ProductId</span><span class="sxs-lookup"><span data-stu-id="0c172-510">ProductId</span></span></td>
<td><p><span data-ttu-id="0c172-511">產品的識別碼。</span><span class="sxs-lookup"><span data-stu-id="0c172-511">The ID for the product.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="0c172-512">SkuId</span><span class="sxs-lookup"><span data-stu-id="0c172-512">SkuId</span></span></td>
<td><p><span data-ttu-id="0c172-513">特定 SKU 的識別碼。</span><span class="sxs-lookup"><span data-stu-id="0c172-513">The ID for a particular SKU.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="0c172-514">AvailabilityId</span><span class="sxs-lookup"><span data-stu-id="0c172-514">AvailabilityId</span></span></td>
<td><p><span data-ttu-id="0c172-515">特定可用性的識別碼。</span><span class="sxs-lookup"><span data-stu-id="0c172-515">The ID for a particular Availability.</span></span> <span data-ttu-id="0c172-516">「可用性」是指特定 SKU 是否可供特定的國家/地區、貨幣、行業區段等等購買。</span><span class="sxs-lookup"><span data-stu-id="0c172-516">“Availability” refers to whether or not a particular SKU is available for purchase for the given country, currency, industry segment, etc.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="0c172-517">SKU 的名稱</span><span class="sxs-lookup"><span data-stu-id="0c172-517">SKU Name</span></span></td>
<td><p><span data-ttu-id="0c172-518">特定 SKU 的標題。</span><span class="sxs-lookup"><span data-stu-id="0c172-518">The title for a particular SKU.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="0c172-519">PublisherName</span><span class="sxs-lookup"><span data-stu-id="0c172-519">PublisherName</span></span></td>
<td><p><span data-ttu-id="0c172-520">發行者的名稱。</span><span class="sxs-lookup"><span data-stu-id="0c172-520">The name of the publisher.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="0c172-521">PublisherID</span><span class="sxs-lookup"><span data-stu-id="0c172-521">PublisherID</span></span></td>
<td><p><span data-ttu-id="0c172-522">GUID 格式的發行者識別碼。</span><span class="sxs-lookup"><span data-stu-id="0c172-522">The ID of the publisher, in GUID format.</span></span> <span data-ttu-id="0c172-523">沒有適用於目前的活動。</span><span class="sxs-lookup"><span data-stu-id="0c172-523">Not available for current activity.</span></span></p></td>
</tr>

<tr class=”even">
<td><span data-ttu-id="0c172-524">訂閱描述</span><span class="sxs-lookup"><span data-stu-id="0c172-524">Subscription Description</span></span></td>
<td><p><span data-ttu-id="0c172-525">客戶購買的服務優惠名稱，如價目表中所定義。</span><span class="sxs-lookup"><span data-stu-id="0c172-525">The name of the service offering purchased by the customer, as defined in the price list.</span></span> <span data-ttu-id="0c172-526">（這是優惠名稱的相同欄位）。</span><span class="sxs-lookup"><span data-stu-id="0c172-526">(This is an identical field to Offer name).</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="0c172-527">訂閱識別碼</span><span class="sxs-lookup"><span data-stu-id="0c172-527">Subscription ID</span></span></td>
<td><p><span data-ttu-id="0c172-528">訂閱在 Microsoft 帳單平台中的唯一識別碼。</span><span class="sxs-lookup"><span data-stu-id="0c172-528">Unique identifier for a subscription in the Microsoft billing platform.</span></span> <span data-ttu-id="0c172-529">可在連絡支援時方便識別訂閱，但不是用於對帳。</span><span class="sxs-lookup"><span data-stu-id="0c172-529">May be useful to identify the subscription when contacting support but not for reconciliation.</span></span> <span data-ttu-id="0c172-530">這與合作夥伴管理主控台上的訂閱識別碼不一樣。</span><span class="sxs-lookup"><span data-stu-id="0c172-530">This is not the same as the Subscription ID on the Partner Admin Console.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="0c172-531">ChargeStartDate</span><span class="sxs-lookup"><span data-stu-id="0c172-531">ChargeStartDate</span></span></td>
<td><p><span data-ttu-id="0c172-532">計費週期的開始日期，當顯示之前未收取潛在使用量資料費用的日期時除外 (從前一個計費週期開始)。</span><span class="sxs-lookup"><span data-stu-id="0c172-532">Start date of billing cycle except when presenting dates of previously uncharged latent usage data (from previous bill cycle).</span></span> <span data-ttu-id="0c172-533">時間一律是一天的開始時間 (0:00)。</span><span class="sxs-lookup"><span data-stu-id="0c172-533">The time is always the beginning of the day, 0:00.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="0c172-534">ChargeEndDate</span><span class="sxs-lookup"><span data-stu-id="0c172-534">ChargeEndDate</span></span></td>
<td><p><span data-ttu-id="0c172-535">計費週期的結束日期，當顯示之前未收取潛在使用量資料費用的日期時除外 (從前一個計費週期開始)。</span><span class="sxs-lookup"><span data-stu-id="0c172-535">End date of billing cycle except when presenting dates of previously uncharged latent usage data (from previous bill cycle).</span></span> <span data-ttu-id="0c172-536">時間一律是一天的結束時間 (23:59)。</span><span class="sxs-lookup"><span data-stu-id="0c172-536">The time is always the end of the day, 23:59.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="0c172-537">使用量日期</span><span class="sxs-lookup"><span data-stu-id="0c172-537">Usage Date</span></span></td>
<td><p><span data-ttu-id="0c172-538">服務使用方式的日期。</span><span class="sxs-lookup"><span data-stu-id="0c172-538">Date of service usage.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="0c172-539">計量表類型</span><span class="sxs-lookup"><span data-stu-id="0c172-539">Meter Type</span></span></td>
<td><p><span data-ttu-id="0c172-540">公尺的類型。</span><span class="sxs-lookup"><span data-stu-id="0c172-540">The type of meter.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="0c172-541">計量表類別</span><span class="sxs-lookup"><span data-stu-id="0c172-541">Meter Category</span></span></td>
<td><p><span data-ttu-id="0c172-542">使用方式的最上層的服務。</span><span class="sxs-lookup"><span data-stu-id="0c172-542">The top-level service for the usage.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="0c172-543">計量表識別碼</span><span class="sxs-lookup"><span data-stu-id="0c172-543">Meter Id</span></span></td>
<td><p><span data-ttu-id="0c172-544">計量表所使用的識別碼。</span><span class="sxs-lookup"><span data-stu-id="0c172-544">The ID for the meter being used.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="0c172-545">計量表子類別</span><span class="sxs-lookup"><span data-stu-id="0c172-545">Meter Sub-category</span></span></td>
<td><p><span data-ttu-id="0c172-546">可能會影響速率的 Azure 服務的類型。</span><span class="sxs-lookup"><span data-stu-id="0c172-546">The type of Azure service that can affect the rate.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="0c172-547">計量表名稱</span><span class="sxs-lookup"><span data-stu-id="0c172-547">Meter Name</span></span></td>
<td><p><span data-ttu-id="0c172-548">針對取用所計量表度量單位。</span><span class="sxs-lookup"><span data-stu-id="0c172-548">The unit of measure for the meter being consumed.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="0c172-549">計量表地區</span><span class="sxs-lookup"><span data-stu-id="0c172-549">Meter Region</span></span></td>
<td><p><span data-ttu-id="0c172-550">此欄可識別適用及填入此項目之服務地區內的資料中心的位置。</span><span class="sxs-lookup"><span data-stu-id="0c172-550">This column identifies the location of a data center within the region for services where this is applicable and populated.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="0c172-551">單位</span><span class="sxs-lookup"><span data-stu-id="0c172-551">Unit</span></span></td>
<td><p><span data-ttu-id="0c172-552">資源名稱的單位。</span><span class="sxs-lookup"><span data-stu-id="0c172-552">The unit of the resource Name.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="0c172-553">享用的數量</span><span class="sxs-lookup"><span data-stu-id="0c172-553">Consumed Quantity</span></span></td>
<td><p><span data-ttu-id="0c172-554">報表期間耗用的服務量 (小時、GB 等等)</span><span class="sxs-lookup"><span data-stu-id="0c172-554">The amount of service consumed (hours, GB, etc.) during the reporting period.</span></span> <span data-ttu-id="0c172-555">同時包括先前報表期間任何未計費的使用量。</span><span class="sxs-lookup"><span data-stu-id="0c172-555">Also includes any unbilled usage from previous reporting periods.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="0c172-556">資源位置</span><span class="sxs-lookup"><span data-stu-id="0c172-556">Resource Location</span></span></td>
<td><p><span data-ttu-id="0c172-557">資料中心計量表在何處執行。</span><span class="sxs-lookup"><span data-stu-id="0c172-557">The datacenter where the meter is running.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="0c172-558">享用的服務</span><span class="sxs-lookup"><span data-stu-id="0c172-558">Consumed Service</span></span></td>
<td><p><span data-ttu-id="0c172-559">您使用 Azure 平台服務。</span><span class="sxs-lookup"><span data-stu-id="0c172-559">The Azure platform service that you used.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="0c172-560">資源群組</span><span class="sxs-lookup"><span data-stu-id="0c172-560">Resource Group</span></span></td>
<td><p><span data-ttu-id="0c172-561">資源群組已部署的計量表正在執行。</span><span class="sxs-lookup"><span data-stu-id="0c172-561">The resource group in which the deployed meter is running.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="0c172-562">資源 URI</span><span class="sxs-lookup"><span data-stu-id="0c172-562">Resource URI</span></span></td>
<td><p><span data-ttu-id="0c172-563">正在使用之資源的 URI。</span><span class="sxs-lookup"><span data-stu-id="0c172-563">The URI of the resource being used.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="0c172-564">收費類型</span><span class="sxs-lookup"><span data-stu-id="0c172-564">Charge type</span></span></td>
<td><p><span data-ttu-id="0c172-565">費用或調整的類型。</span><span class="sxs-lookup"><span data-stu-id="0c172-565">The type of charge or adjustment.</span></span> <span data-ttu-id="0c172-566">沒有適用於目前的活動。</span><span class="sxs-lookup"><span data-stu-id="0c172-566">Not available for current activity.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="0c172-567">單價</span><span class="sxs-lookup"><span data-stu-id="0c172-567">Unit price</span></span></td>
<td><p><span data-ttu-id="0c172-568">每一授權，因為在購買時，價格表中發佈的價格。</span><span class="sxs-lookup"><span data-stu-id="0c172-568">Price per license, as published in the pricelist at the time of purchase.</span></span> <span data-ttu-id="0c172-569">請確定這與對帳期間儲存在您帳單系統中的資訊相符。</span><span class="sxs-lookup"><span data-stu-id="0c172-569">Ensure this matches the information stored in your billing system during reconciliation.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="0c172-570">數量</span><span class="sxs-lookup"><span data-stu-id="0c172-570">Quantity</span></span></td>
<td><p><span data-ttu-id="0c172-571">授權數目。</span><span class="sxs-lookup"><span data-stu-id="0c172-571">Number of licenses.</span></span> <span data-ttu-id="0c172-572">請確定這與對帳期間儲存在您帳單系統中的資訊相符。</span><span class="sxs-lookup"><span data-stu-id="0c172-572">Ensure this matches the information stored in your billing system during reconciliation.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="0c172-573">單位類型</span><span class="sxs-lookup"><span data-stu-id="0c172-573">Unit type</span></span></td>
<td><p><span data-ttu-id="0c172-574">在負責的計量表單元類型。</span><span class="sxs-lookup"><span data-stu-id="0c172-574">The type of unit the meter is charged in.</span></span> <span data-ttu-id="0c172-575">沒有適用於目前的活動。</span><span class="sxs-lookup"><span data-stu-id="0c172-575">Not available for current activity.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="0c172-576">帳單 pre 稅</span><span class="sxs-lookup"><span data-stu-id="0c172-576">Billing pre tax</span></span></td>
<td><p><span data-ttu-id="0c172-577">稅前的總金額。</span><span class="sxs-lookup"><span data-stu-id="0c172-577">Total amount before taxes.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="0c172-578">帳單貨幣</span><span class="sxs-lookup"><span data-stu-id="0c172-578">Billing currency</span></span></td>
<td><p><span data-ttu-id="0c172-579">在客戶的地理區域貨幣</span><span class="sxs-lookup"><span data-stu-id="0c172-579">The currency in the customer’s geographic region</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="0c172-580">定價稅前總計</span><span class="sxs-lookup"><span data-stu-id="0c172-580">Pricing pretax total</span></span></td>
<td><p><span data-ttu-id="0c172-581">定價之前內含稅金。</span><span class="sxs-lookup"><span data-stu-id="0c172-581">The pricing before taxes are added.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="0c172-582">定價貨幣</span><span class="sxs-lookup"><span data-stu-id="0c172-582">Pricing currency</span></span></td>
<td><p><span data-ttu-id="0c172-583">價格表中的貨幣。</span><span class="sxs-lookup"><span data-stu-id="0c172-583">The currency in the pricelist.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="0c172-584">服務資訊 1</span><span class="sxs-lookup"><span data-stu-id="0c172-584">Service Info 1</span></span></td>
<td><p><span data-ttu-id="0c172-585">於某一天佈建及使用的 ServiceBus 連線數目。</span><span class="sxs-lookup"><span data-stu-id="0c172-585">The number of ServiceBus connections that were provisioned and utilized on a given day.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="0c172-586">服務資訊 2</span><span class="sxs-lookup"><span data-stu-id="0c172-586">Service Info 2</span></span></td>
<td><p><span data-ttu-id="0c172-587">舊版的欄位，擷取選用服務特定的中繼資料。</span><span class="sxs-lookup"><span data-stu-id="0c172-587">A legacy field that captures optional service-specific metadata.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="0c172-588">標記</span><span class="sxs-lookup"><span data-stu-id="0c172-588">Tags</span></span></td>
<td><p><span data-ttu-id="0c172-589">您指派給群組的帳單記錄的順序中的計量表標記。</span><span class="sxs-lookup"><span data-stu-id="0c172-589">Tags you assign to the meter in order to group billing records.</span></span> <span data-ttu-id="0c172-590">例如，您可以使用標記來散發使用計量表部門的成本。</span><span class="sxs-lookup"><span data-stu-id="0c172-590">For example, you can use tags to distribute costs by the department that uses the meter.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="0c172-591">其他資訊</span><span class="sxs-lookup"><span data-stu-id="0c172-591">Additional Info</span></span></td>
<td><p><span data-ttu-id="0c172-592">未涵蓋其他欄中的任何其他資訊。</span><span class="sxs-lookup"><span data-stu-id="0c172-592">Any additional information not covered in other columns.</span></span></p></td>
</tr>

</tbody>
</table>


## <a href="" id="charge_types"></a><span data-ttu-id="0c172-593">對應發票和對帳檔案之間的費用</span><span class="sxs-lookup"><span data-stu-id="0c172-593">Mapping charges between an invoice and the reconciliation file</span></span>

<span data-ttu-id="0c172-594">您的發票提供費用摘要，而對帳檔案則提供包括費用類型等明細項目交易的詳細細項。</span><span class="sxs-lookup"><span data-stu-id="0c172-594">Your invoice provides a summary of charges, while your reconciliation file provides a detailed breakdown of line-item transactions, including charge types.</span></span>

<span data-ttu-id="0c172-595">若要交互參照發票和對帳檔案之間的費用金額，您可以使用 Microsoft Excel 篩選選項，在對帳檔案上依費用類型篩選，以便將發票費用對應到對帳檔案上的一組費用細項。</span><span class="sxs-lookup"><span data-stu-id="0c172-595">To cross-reference charge amounts between the invoice and reconciliation file, you can use Microsoft Excel's filter options to filter by charge types on the reconciliation file to map the invoice charges to a set of charge breakdowns on reconciliation file.</span></span>

<span data-ttu-id="0c172-596">用量型和授權型訂閱的對帳檔案只會顯示交易和費用的相關使用量 (耗用單位和相關的費用)。</span><span class="sxs-lookup"><span data-stu-id="0c172-596">Reconciliation files, both usage- and license-based, only show usage related transactions and charges (units consumed and related charges).</span></span> <span data-ttu-id="0c172-597">發票上顯示為「調整」的點數、折扣或退款不會出現在對帳檔案中。</span><span class="sxs-lookup"><span data-stu-id="0c172-597">One off credits, discounts or refunds which appear on the invoice as “Adjustments” are not shown in the reconciliation file.</span></span>

<span data-ttu-id="0c172-598">下表顯示發票區段和對帳檔案上可能會顯示之相關費用類型之間的對應。</span><span class="sxs-lookup"><span data-stu-id="0c172-598">The table below shows the mappings between an invoice section and associated charge types that might show up on the reconciliation files.</span></span> 

<table>
<tbody>
<tr>
<td>
<p><strong><span data-ttu-id="0c172-599">發票費用描述</span><span class="sxs-lookup"><span data-stu-id="0c172-599">Invoice charge description</span></span></strong></p>
</td>
<td>
<p><strong><span data-ttu-id="0c172-600">對帳檔案費用描述（ChargeType 欄）</span><span class="sxs-lookup"><span data-stu-id="0c172-600">Reconciliation file charge description (ChargeType column)</span></span></strong></p>
</td>
<td>
<p><strong><span data-ttu-id="0c172-601">這項費用是什麼？</span><span class="sxs-lookup"><span data-stu-id="0c172-601">What is this charge?</span></span></strong></p>
</td>
<td>
<p><strong><span data-ttu-id="0c172-602">如何將這些 ChargeTypes 對應到發票？</span><span class="sxs-lookup"><span data-stu-id="0c172-602">How do I map these ChargeTypes to the invoice?</span></span></strong></p>
</td>
</tr>
<tr>
<td rowspan="10">
<p><strong><span data-ttu-id="0c172-603">授權型的費用</span><span class="sxs-lookup"><span data-stu-id="0c172-603">License-based charges</span></span></strong></p>
</td>
<td>
<p><span data-ttu-id="0c172-604">啟用費用</span><span class="sxs-lookup"><span data-stu-id="0c172-604">Activation fee</span></span></p>
</td>
<td>
<p><span data-ttu-id="0c172-605">當客戶購買後使用訂閱時，向客戶收取的金額</span><span class="sxs-lookup"><span data-stu-id="0c172-605">The amount charged to the customer when they use the subscription after purchasing it</span></span></p>
</td>
<td rowspan="10">
<p><span data-ttu-id="0c172-606">從授權型檔案，加總 <strong>Amount</strong> 欄</span><span class="sxs-lookup"><span data-stu-id="0c172-606">From license-based file, sum the <strong>Amount</strong> column</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="0c172-607">取消費用</span><span class="sxs-lookup"><span data-stu-id="0c172-607">Cancel fee</span></span></p>
</td>
<td>
<p><span data-ttu-id="0c172-608">當關聯的基座變更時，按比例計算退款給客戶的費用</span><span class="sxs-lookup"><span data-stu-id="0c172-608">Prorated charges refunded to the customer when associated seats are changed</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="0c172-609">循環費用</span><span class="sxs-lookup"><span data-stu-id="0c172-609">Cycle fee</span></span></p>
</td>
<td>
<p><span data-ttu-id="0c172-610">訂閱的定期費用</span><span class="sxs-lookup"><span data-stu-id="0c172-610">Periodic charges for a subscription</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="0c172-611">循環執行個體按比例計算</span><span class="sxs-lookup"><span data-stu-id="0c172-611">Cycle instance prorate</span></span></p>
</td>
<td>
<p><span data-ttu-id="0c172-612">當關聯的基座變更時，按比例計算向客戶收取的費用</span><span class="sxs-lookup"><span data-stu-id="0c172-612">Prorated charges assessed from the customer when associated seats are changed</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="0c172-613">取消時按比例計算費用</span><span class="sxs-lookup"><span data-stu-id="0c172-613">Prorate fees when cancel</span></span></p>
</td>
<td>
<p><span data-ttu-id="0c172-614">取消時服務未使用部分之按比例計算的退款</span><span class="sxs-lookup"><span data-stu-id="0c172-614">Prorated refund for unused portion of service upon cancellation</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="0c172-615">購買時按比例計算費用</span><span class="sxs-lookup"><span data-stu-id="0c172-615">Prorate fees when purchase</span></span></p>
</td>
<td>
<p><span data-ttu-id="0c172-616">當使用年度計費訂閱的費用類型</span><span class="sxs-lookup"><span data-stu-id="0c172-616">The charge type for a subscription when using annual billing</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="0c172-617">購買費用</span><span class="sxs-lookup"><span data-stu-id="0c172-617">Purchase fee</span></span></p>
</td>
<td>
<p><span data-ttu-id="0c172-618">當使用每月計費的訂閱費用類型</span><span class="sxs-lookup"><span data-stu-id="0c172-618">The charge type for a subscription when using monthly billing</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="0c172-619">續約時按比例計算費用</span><span class="sxs-lookup"><span data-stu-id="0c172-619">Prorate fee when renew</span></span></p>
</td>
<td>
<p><span data-ttu-id="0c172-620">訂閱續約時按比例計算的費用</span><span class="sxs-lookup"><span data-stu-id="0c172-620">Prorated fees upon subscription renewal</span></span></p>
</td>
</tr>
<tr>

<td>
<p><span data-ttu-id="0c172-621">續約費用</span><span class="sxs-lookup"><span data-stu-id="0c172-621">Renew fee</span></span></p>
</td>
<td>
<p><span data-ttu-id="0c172-622">訂閱續約時的費用</span><span class="sxs-lookup"><span data-stu-id="0c172-622">Charge for renewing a subscription</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="0c172-623">啟用時按比例計算費用</span><span class="sxs-lookup"><span data-stu-id="0c172-623">Prorate fees when activate</span></span></p>
</td>
<td>
<p><span data-ttu-id="0c172-624">從啟用到計費期間結束時按比例計算的費用</span><span class="sxs-lookup"><span data-stu-id="0c172-624">Prorated fees from activation until end of billing period</span></span></p>
</td>
</tr>
<tr>
<td rowspan="2">
<p><strong><span data-ttu-id="0c172-625">使用量費用</span><span class="sxs-lookup"><span data-stu-id="0c172-625">Usage Charges</span></span></strong></p>
</td>
<td>
<p><span data-ttu-id="0c172-626">取消時的存取用量費用</span><span class="sxs-lookup"><span data-stu-id="0c172-626">Assess usage fee when cancel</span></span></p>
</td>
<td>
<p><span data-ttu-id="0c172-627">在目前計費期間中取消時，未支付之使用量的存取用量費用</span><span class="sxs-lookup"><span data-stu-id="0c172-627">Access usage fee upon cancellation for unpaid usage during the current billing period</span></span></p>
</td>
<td rowspan="2">
<p><span data-ttu-id="0c172-628">從用量型檔案，加總 <strong>PretaxCharges</strong> 欄</span><span class="sxs-lookup"><span data-stu-id="0c172-628">From usage-based file, sum the <strong>PretaxCharges</strong> column</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="0c172-629">目前週期的存取用量費用</span><span class="sxs-lookup"><span data-stu-id="0c172-629">Assess usage fee for current cycle</span></span></p>
</td>
<td>
<p><span data-ttu-id="0c172-630">目前計費期間的存取用量費用</span><span class="sxs-lookup"><span data-stu-id="0c172-630">Access usage fee for the current billing period</span></span></p>
</td>
</tr>
<tr>
<td>
<p><strong><span data-ttu-id="0c172-631">點數</span><span class="sxs-lookup"><span data-stu-id="0c172-631">Credits</span></span></strong></p>
</td>
<td>
<p><span data-ttu-id="0c172-632">明細項目位移</span><span class="sxs-lookup"><span data-stu-id="0c172-632">Offset a line item</span></span></p>
</td>
<td>
<p><span data-ttu-id="0c172-633">明細項目的部分或完整退款 (含稅)</span><span class="sxs-lookup"><span data-stu-id="0c172-633">Partial or whole refund to a line item, including taxes</span></span></p>
</td>
<td>
<p><span data-ttu-id="0c172-634">從授權型檔案，加總 <strong>TotalForCustomer</strong> 欄</span><span class="sxs-lookup"><span data-stu-id="0c172-634">From license-based file, sum the <strong>TotalForCustomer</strong> column</span></span></p>
<p><span data-ttu-id="0c172-635">從用量型檔案，加總 <strong>PostTaxTotal</strong> 欄</span><span class="sxs-lookup"><span data-stu-id="0c172-635">From usage-based file, sum the <strong>PostTaxTotal</strong> column</span></span></p>
</td>
</tr>
<tr>
<td rowspan="4">
<p><strong><span data-ttu-id="0c172-636">用量型折扣</span><span class="sxs-lookup"><span data-stu-id="0c172-636">Usage-based discounts</span></span></strong></p>
</td>
<td>
<p><span data-ttu-id="0c172-637">啟用折扣</span><span class="sxs-lookup"><span data-stu-id="0c172-637">Activation discount</span></span></p>
</td>
<td>
<p><span data-ttu-id="0c172-638">啟用訂閱時套用的折扣</span><span class="sxs-lookup"><span data-stu-id="0c172-638">Discount applied when subscription activated</span></span></p>
</td>

<td rowspan="4">
<p><span data-ttu-id="0c172-639">從用量型檔案，加總 <strong>PretaxCharges</strong> 欄</span><span class="sxs-lookup"><span data-stu-id="0c172-639">From usage-based file, sum the <strong>PretaxCharges</strong> column</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="0c172-640">循環折扣</span><span class="sxs-lookup"><span data-stu-id="0c172-640">Cycle discount</span></span></p>
</td>
<td>
<p><span data-ttu-id="0c172-641">套用至定期費用的折扣</span><span class="sxs-lookup"><span data-stu-id="0c172-641">Discount applied on periodic charges</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="0c172-642">續約折扣</span><span class="sxs-lookup"><span data-stu-id="0c172-642">Renew discount</span></span></p>
</td>
<td>
<p><span data-ttu-id="0c172-643">訂閱續約時套用的折扣</span><span class="sxs-lookup"><span data-stu-id="0c172-643">Discount applied when subscription renewed</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="0c172-644">取消折扣</span><span class="sxs-lookup"><span data-stu-id="0c172-644">Cancel discount</span></span></p>
</td>
<td>
<p><span data-ttu-id="0c172-645">折扣取消時收取的費用</span><span class="sxs-lookup"><span data-stu-id="0c172-645">Charges applied when discounts cancelled</span></span></p>
</td>
</tr>


<tr>
<td>
<p><strong><span data-ttu-id="0c172-646">授權型折扣</span><span class="sxs-lookup"><span data-stu-id="0c172-646">License-based discounts</span></span></strong></p>
</td>
<td>
<p><em><span data-ttu-id="0c172-647">可套用至多個費用類型</span><span class="sxs-lookup"><span data-stu-id="0c172-647">May be applied to multiple charge types</span></span></em></p>
</td>
<td>
<p></p>
</td>
<td>
<p><span data-ttu-id="0c172-648">從授權型檔案，加總 <strong>TotalOtherDiscount</strong> 欄</span><span class="sxs-lookup"><span data-stu-id="0c172-648">From license-based file, sum the <strong>TotalOtherDiscount</strong> column</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="0c172-649"><strong>稅金</strong>&nbsp;或&nbsp;<strong>加值稅</strong></span><span class="sxs-lookup"><span data-stu-id="0c172-649"><strong>Taxes</strong>&nbsp;or&nbsp;<strong>VAT</strong></span></span></p>
</td>
<td>
<p><em><span data-ttu-id="0c172-650">可套用至多個費用類型</span><span class="sxs-lookup"><span data-stu-id="0c172-650">May be applied to multiple charge types</span></span></em></p>
<p><em><span data-ttu-id="0c172-651">例外： &quot;Offset 明細項目&quot;已含稅。</span><span class="sxs-lookup"><span data-stu-id="0c172-651">Exception: &quot;Offset a line item&quot; already includes taxes.</span></span> <span data-ttu-id="0c172-652">請參閱上面的點數。</span><span class="sxs-lookup"><span data-stu-id="0c172-652">See Credits, above.</span></span></em></p>
</td>
<td>
<p><span data-ttu-id="0c172-653">稅金或加值稅 (VAT)</span><span class="sxs-lookup"><span data-stu-id="0c172-653">Taxes or value-added taxes (VAT)</span></span></p>
</td>
<td>
<p><span data-ttu-id="0c172-654">從授權型檔案，加總 <strong>Tax</strong> 欄</span><span class="sxs-lookup"><span data-stu-id="0c172-654">From license-based file, sum the <strong>Tax</strong> column</span></span></p>
<p><span data-ttu-id="0c172-655">從用量型檔案，加總 <strong>TaxAmount</strong> 欄</span><span class="sxs-lookup"><span data-stu-id="0c172-655">From usage-based file, sum the <strong>TaxAmount</strong> column</span></span></p>
</td>
</tr>
</tbody>
</table>
<p>&nbsp;</p>
