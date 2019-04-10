---
title: 使用對帳檔案 | 合作夥伴中心
ms.topic: article
ms.date: 10/29/2018
description: 在計費週期中的每個收費詳細的明細項目檢視，請從合作夥伴中心下載的對帳檔案。
ms.assetid: FA6A6FCB-2597-44E7-93F8-8D1DD35D52EA
author: LauraBrenner
ms.author: labrenne
ms.localizationpriority: medium
ms.openlocfilehash: 0d986ca81e77578ecbb79b909d8f2a8afc4777e4
ms.sourcegitcommit: 275d3eee5613d52f0ac7b8c78f7a7ddd74f56c9e
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 04/10/2019
ms.locfileid: "59430197"
---
# <a name="use-the-reconciliation-files"></a><span data-ttu-id="8bab0-103">使用對帳檔案</span><span class="sxs-lookup"><span data-stu-id="8bab0-103">Use the reconciliation files</span></span>

**<span data-ttu-id="8bab0-104">適用於</span><span class="sxs-lookup"><span data-stu-id="8bab0-104">Applies to</span></span>**

-  <span data-ttu-id="8bab0-105">合作夥伴中心</span><span class="sxs-lookup"><span data-stu-id="8bab0-105">Partner Center</span></span>
-  <span data-ttu-id="8bab0-106">Microsoft Cloud for US Government 適用的合作夥伴中心</span><span class="sxs-lookup"><span data-stu-id="8bab0-106">Partner Center for Microsoft Cloud for US Government</span></span>


<span data-ttu-id="8bab0-107">在計費週期中的每個收費詳細的明細項目檢視，請從合作夥伴中心下載的對帳檔案。</span><span class="sxs-lookup"><span data-stu-id="8bab0-107">For a detailed line-item view of each charge in a billing cycle, download the reconciliation files from Partner Center.</span></span> <span data-ttu-id="8bab0-108">詳細資料包括每個客戶的訂閱費用，以及詳細事件 (例如，期中增加訂閱基座)。</span><span class="sxs-lookup"><span data-stu-id="8bab0-108">The details include charges for each customer's subscriptions, and detailed events (such as a mid-term addition of seats to a subscription).</span></span>

## <a name="formatting-issues"></a><span data-ttu-id="8bab0-109">格式化問題</span><span class="sxs-lookup"><span data-stu-id="8bab0-109">Formatting issues</span></span>

<span data-ttu-id="8bab0-110">有時候您偵查的檔案可能會有格式問題。</span><span class="sxs-lookup"><span data-stu-id="8bab0-110">Occasionally your recon file might have formatting issues.</span></span> <span data-ttu-id="8bab0-111">（這種情形，例如，如果未使用 EN-US 地區設定。）請遵循下列步驟來修正這些問題。</span><span class="sxs-lookup"><span data-stu-id="8bab0-111">(This can happen, for example, if the EN-US locale is not used.) Follow the steps below to fix these issues.</span></span> 

<ol>
<li><span data-ttu-id="8bab0-112">在 Excel 中開啟.csv 檔案，並選取第一個資料行。</span><span class="sxs-lookup"><span data-stu-id="8bab0-112">Open the .csv file in Excel, and select the first column.</span></span> <span data-ttu-id="8bab0-113">在功能區中，選取<strong>資料</strong>，然後選取<strong>資料行的文字</strong>。</span><span class="sxs-lookup"><span data-stu-id="8bab0-113">On the ribbon, select <strong>Data</strong>, and then select <strong>Text to Columns</strong>.</span></span></li>

<li><span data-ttu-id="8bab0-114">在 [文字轉換為資料行精靈，選取<strong>分隔的檔案類型</strong>，然後選取<strong>下一步]</strong>。</span><span class="sxs-lookup"><span data-stu-id="8bab0-114">In the Convert Text to Columns Wizard, select <strong>Delimited file type</strong>, and then select <strong>Next</strong>.</span></span></li> 

<li><span data-ttu-id="8bab0-115">在 [分隔符號] 欄位中，選取<strong>逗號</strong>。</span><span class="sxs-lookup"><span data-stu-id="8bab0-115">In the Delimeters field, select <strong>Comma</strong>.</span></span> <span data-ttu-id="8bab0-116">如果<strong> 索引標籤</strong>是已選取，您可以將它保留。</span><span class="sxs-lookup"><span data-stu-id="8bab0-116">If <strong>Tab</strong> is already selected, you can leave it.</span></span> <span data-ttu-id="8bab0-117">選取 <strong>\[下一步\]</strong>。</span><span class="sxs-lookup"><span data-stu-id="8bab0-117">Select <strong>Next</strong>.</span></span></li>

<li><span data-ttu-id="8bab0-118">在 資料行的資料格式 欄位中，選取<strong>日期：MDY</strong>，然後選取<strong>下一步</strong>。</span><span class="sxs-lookup"><span data-stu-id="8bab0-118">In the Column data format field, select <strong>Date: MDY</strong>, and then select <strong>Next</strong>.</span></span></li> 

<li><span data-ttu-id="8bab0-119">在 [資料行的資料格式] 欄位中，選取<strong>文字</strong>的所有 amount 資料行，然後選取<strong>完成</strong>。</span><span class="sxs-lookup"><span data-stu-id="8bab0-119">In the Column data format field, select <strong>Text</strong> for all amount columns, and then select <strong>Finish</strong>.</span></span></li>
</ol>

## <a href="" id="itemizebypartner"></a><span data-ttu-id="8bab0-120">由合作夥伴條列</span><span class="sxs-lookup"><span data-stu-id="8bab0-120">Itemize by partner</span></span>


<span data-ttu-id="8bab0-121">間接模型合作夥伴可以在授權型及用量型對帳檔案中使用這些額外欄位，以便依經銷商詳細列舉。</span><span class="sxs-lookup"><span data-stu-id="8bab0-121">Partners in the indirect model can use these additional fields in both license-based and usage-based reconciliation files to itemize by reseller.</span></span>

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th><span data-ttu-id="8bab0-122">MPN 識別碼</span><span class="sxs-lookup"><span data-stu-id="8bab0-122">MPN ID</span></span></th>
<th><span data-ttu-id="8bab0-123">描述</span><span class="sxs-lookup"><span data-stu-id="8bab0-123">Description</span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="8bab0-124">MPN 識別碼</span><span class="sxs-lookup"><span data-stu-id="8bab0-124">MPN ID</span></span></td>
<td><p><span data-ttu-id="8bab0-125">CSP 合作夥伴 (直接或間接) 的 Microsoft 合作夥伴網路 (MPN) 識別碼。</span><span class="sxs-lookup"><span data-stu-id="8bab0-125">The Microsoft Partner Network (MPN) ID of the CSP partner (direct or indirect).</span></span></p></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8bab0-126">經銷商 MPN 識別碼</span><span class="sxs-lookup"><span data-stu-id="8bab0-126">Reseller MPN ID</span></span></td>
<td><p><span data-ttu-id="8bab0-127">只會出現在間接模型合作夥伴的對帳檔案上。</span><span class="sxs-lookup"><span data-stu-id="8bab0-127">Only appears on reconciliation files for partners in the indirect model.</span></span></p>
<p><span data-ttu-id="8bab0-128">訂閱記錄中的經銷商 MPN 識別碼。</span><span class="sxs-lookup"><span data-stu-id="8bab0-128">The MPN ID of the reseller of record for the subscription.</span></span> <span data-ttu-id="8bab0-129">這會對應到合作夥伴中心中針對特定訂閱列出的經銷商識別碼。</span><span class="sxs-lookup"><span data-stu-id="8bab0-129">This corresponds to the reseller ID listed for the specific subscription in Partner Center.</span></span></p>
<p><span data-ttu-id="8bab0-130">干支檢視或更新的轉銷商，從合作夥伴中心 功能表中，選取<strong>客戶</strong>，然後從清單中選擇客戶。</span><span class="sxs-lookup"><span data-stu-id="8bab0-130">eTo view or update the reseller, from the Partner Center menu, select <strong>Customers</strong>, then choose the customer from the list.</span></span> <span data-ttu-id="8bab0-131">在客戶功能表中，選取 \[訂閱\]，從清單中選擇訂閱。</span><span class="sxs-lookup"><span data-stu-id="8bab0-131">In the customer menu, select <strong>Subscriptions</strong>, choose the subscription from the list.</span></span> <span data-ttu-id="8bab0-132">選取 \[更新\] 以變更 \[經銷商 (MPN 識別碼)\]。</span><span class="sxs-lookup"><span data-stu-id="8bab0-132">Select <strong>update</strong> to change the <strong>Reseller (MPN ID)</strong>.</span></span></p>
<p><span data-ttu-id="8bab0-133">如果雲端解決方案提供者合作夥伴直接向客戶銷售訂閱，他們的 MPN 識別碼將會以 MPN 識別碼和經銷商 MPN 識別碼的形式列出兩次。</span><span class="sxs-lookup"><span data-stu-id="8bab0-133">If a CSP partner sold the subscription directly to the customer, their MPN ID is listed twice, as both the MPN ID and the Reseller MPN ID.</span></span></p>
<p><span data-ttu-id="8bab0-134">如果雲端解決方案提供者合作夥伴具有沒有 MPN 識別碼的經銷商，這個值將會改成設為合作夥伴的 MPN 識別碼。</span><span class="sxs-lookup"><span data-stu-id="8bab0-134">If a CSP partner has a reseller with no MPN ID, this value is set to the partner’s MPN ID instead.</span></span></p>
<p><span data-ttu-id="8bab0-135">如果雲端解決方案提供者合作夥伴移除經銷商識別碼，這個值將會設為 -1。</span><span class="sxs-lookup"><span data-stu-id="8bab0-135">If the CSP partner removes a reseller ID, this value will be set to -1.</span></span></p></td>
</tr>
</tbody>
</table>

 

## <a href="" id="licensebasedfiles"></a> <span data-ttu-id="8bab0-136">以授權為基礎的檔案欄位</span><span class="sxs-lookup"><span data-stu-id="8bab0-136">License-based file fields</span></span>


<span data-ttu-id="8bab0-137">若要針對您對客戶訂單的費用來對帳，請比較對帳檔案中的 Syndication\_Partner\_Subscription\_Number 與合作夥伴中心的訂閱識別碼。</span><span class="sxs-lookup"><span data-stu-id="8bab0-137">To reconcile your charges against your customer's orders, compare the Syndication\_Partner\_Subscription\_Number from the reconciliation file against the Subscription ID from Partner Center.</span></span>

<table>
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<tbody>
<tr class="odd">
<td><strong><span data-ttu-id="8bab0-138">Column</span><span class="sxs-lookup"><span data-stu-id="8bab0-138">Column</span></span></strong></td>
<td><strong><span data-ttu-id="8bab0-139">描述</span><span class="sxs-lookup"><span data-stu-id="8bab0-139">Description</span></span></strong></td>
<td><strong><span data-ttu-id="8bab0-140">範例值</span><span class="sxs-lookup"><span data-stu-id="8bab0-140">Sample Value</span></span></strong></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8bab0-141">PartnerId</span><span class="sxs-lookup"><span data-stu-id="8bab0-141">PartnerId</span></span></td>
<td><p><span data-ttu-id="8bab0-142">特定帳單實體的唯一識別碼 (GUID 格式)。</span><span class="sxs-lookup"><span data-stu-id="8bab0-142">Unique identifier for a specific billing entity, in GUID format.</span></span> <span data-ttu-id="8bab0-143">對帳時不需要，但可能是很有用的資訊。</span><span class="sxs-lookup"><span data-stu-id="8bab0-143">Not required for reconciliation, however may be useful information.</span></span> <span data-ttu-id="8bab0-144">在所有資料列中都是如此。</span><span class="sxs-lookup"><span data-stu-id="8bab0-144">Same in all rows.</span></span></p></td>
<td><span data-ttu-id="8bab0-145">8ddd03642-test-test-test-46b58d356b4e</span><span class="sxs-lookup"><span data-stu-id="8bab0-145">8ddd03642-test-test-test-46b58d356b4e</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8bab0-146">CustomerID</span><span class="sxs-lookup"><span data-stu-id="8bab0-146">CustomerID</span></span></td>
<td><p><span data-ttu-id="8bab0-147">用來識別客戶的唯一 Microsoft ID（GUID 格式）。</span><span class="sxs-lookup"><span data-stu-id="8bab0-147">Unique Microsoft ID, in GUID format, used to identify the customer.</span></span></p></td>
<td><span data-ttu-id="8bab0-148">12ABCD34-001A-BCD2-987C-3210ABCD5678</span><span class="sxs-lookup"><span data-stu-id="8bab0-148">12ABCD34-001A-BCD2-987C-3210ABCD5678</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8bab0-149">OrderID</span><span class="sxs-lookup"><span data-stu-id="8bab0-149">OrderID</span></span></td>
<td><p><span data-ttu-id="8bab0-150">訂單在 Microsoft 帳單平台中的唯一識別碼。</span><span class="sxs-lookup"><span data-stu-id="8bab0-150">Unique identifier for an order in the Microsoft billing platform.</span></span> <span data-ttu-id="8bab0-151">可在連絡支援時方便識別訂單，但不是用於對帳。</span><span class="sxs-lookup"><span data-stu-id="8bab0-151">May be useful to identify the order when contacting support but not for reconciliation.</span></span></p></td>
<td><span data-ttu-id="8bab0-152">566890604832738111</span><span class="sxs-lookup"><span data-stu-id="8bab0-152">566890604832738111</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8bab0-153">SubscriptionID</span><span class="sxs-lookup"><span data-stu-id="8bab0-153">SubscriptionID</span></span></td>
<td><p><span data-ttu-id="8bab0-154">訂閱在 Microsoft 帳單平台中的唯一識別碼。</span><span class="sxs-lookup"><span data-stu-id="8bab0-154">Unique identifier for a subscription in the Microsoft billing platform.</span></span> <span data-ttu-id="8bab0-155">可在連絡支援時方便識別訂閱，但不是用於對帳。</span><span class="sxs-lookup"><span data-stu-id="8bab0-155">May be useful to identify the subscription when contacting support but not for reconciliation.</span></span></p>
<p><span data-ttu-id="8bab0-156">這與合作夥伴管理主控台上的訂閱識別碼不一樣。</span><span class="sxs-lookup"><span data-stu-id="8bab0-156">This is not the same as the Subscription ID on the Partner Admin Console.</span></span> <span data-ttu-id="8bab0-157">請參閱 Syndication_Partner_Subscription_Number。</span><span class="sxs-lookup"><span data-stu-id="8bab0-157">Please see Syndication_Partner_Subscription_Number.</span></span></p></td>
<td><span data-ttu-id="8bab0-158">usCBMgAAAAAAAAIA</span><span class="sxs-lookup"><span data-stu-id="8bab0-158">usCBMgAAAAAAAAIA</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8bab0-159">SyndicationPartnerSubscriptionNumber</span><span class="sxs-lookup"><span data-stu-id="8bab0-159">SyndicationPartnerSubscriptionNumber</span></span></td>
<td><p><span data-ttu-id="8bab0-160">訂閱的唯一識別碼。</span><span class="sxs-lookup"><span data-stu-id="8bab0-160">Unique identifier for subscriptions.</span></span> <span data-ttu-id="8bab0-161">客戶可針對同一方案擁有多項訂閱，因此這對於對帳檔案分析而言很重要。</span><span class="sxs-lookup"><span data-stu-id="8bab0-161">A customer can have multiple subscriptions for the same plan, so this is important for reconciliation file analysis.</span></span></p>
<p><span data-ttu-id="8bab0-162">這個欄位對應到合作夥伴管理主控台中的訂閱識別碼。</span><span class="sxs-lookup"><span data-stu-id="8bab0-162">This field maps to the Subscription ID in the Partner Admin Console.</span></span></p></td>
<td><span data-ttu-id="8bab0-163">fb977ab5-test-test-test-24c8d9591708</span><span class="sxs-lookup"><span data-stu-id="8bab0-163">fb977ab5-test-test-test-24c8d9591708</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8bab0-164">OfferID</span><span class="sxs-lookup"><span data-stu-id="8bab0-164">OfferID</span></span></td>
<td><p><span data-ttu-id="8bab0-165">唯一的優惠識別碼。</span><span class="sxs-lookup"><span data-stu-id="8bab0-165">Unique offer ID.</span></span> <span data-ttu-id="8bab0-166">根據價目表的標準優惠識別碼。</span><span class="sxs-lookup"><span data-stu-id="8bab0-166">Standard offer ID as per price list.</span></span></p>
<p><span data-ttu-id="8bab0-167"><b>注意</b>：此值不符合優惠識別碼從價格清單。</span><span class="sxs-lookup"><span data-stu-id="8bab0-167"><b>Note</b>: This value does not match Offer ID from the price list.</span></span> <span data-ttu-id="8bab0-168">請參閱下方的 DurableOfferID。</span><span class="sxs-lookup"><span data-stu-id="8bab0-168">See DurableOfferID below.</span></span></p></td>
<td><span data-ttu-id="8bab0-169">FE616D64-E9A8-40EF-843F-152E9BBEF3D1</span><span class="sxs-lookup"><span data-stu-id="8bab0-169">FE616D64-E9A8-40EF-843F-152E9BBEF3D1</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8bab0-170">DurableOfferID</span><span class="sxs-lookup"><span data-stu-id="8bab0-170">DurableOfferID</span></span></td>
<td><p><span data-ttu-id="8bab0-171">唯一的持續性優惠識別碼，如價目表中所定義。</span><span class="sxs-lookup"><span data-stu-id="8bab0-171">Unique durable offer ID, as defined in the price list.</span></span></p>
<p><span data-ttu-id="8bab0-172"><b>注意</b>：此值符合優惠識別碼從價格清單。</span><span class="sxs-lookup"><span data-stu-id="8bab0-172"><b>Note</b>: This value matches the Offer ID from the price list.</span></span></p></td>
<td><span data-ttu-id="8bab0-173">1017D7F3-6D7F-4BFA-BDD8-79BC8F104E0C</span><span class="sxs-lookup"><span data-stu-id="8bab0-173">1017D7F3-6D7F-4BFA-BDD8-79BC8F104E0C</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8bab0-174">OfferName</span><span class="sxs-lookup"><span data-stu-id="8bab0-174">OfferName</span></span></td>
<td><p><span data-ttu-id="8bab0-175">客戶購買的服務優惠名稱，如價目表中所定義。</span><span class="sxs-lookup"><span data-stu-id="8bab0-175">The name of the service offering purchased by the customer, as defined in the price list.</span></span></p></td>
<td><span data-ttu-id="8bab0-176">Microsoft Office 365 (Plan E3)</span><span class="sxs-lookup"><span data-stu-id="8bab0-176">Microsoft Office 365 (Plan E3)</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8bab0-177">SubscriptionStartDate</span><span class="sxs-lookup"><span data-stu-id="8bab0-177">SubscriptionStartDate</span></span></td>
<td><p><span data-ttu-id="8bab0-178">訂閱開始日期設定為送出訂單之後的隔日。</span><span class="sxs-lookup"><span data-stu-id="8bab0-178">The subscription start date, set to the day after the order is submitted.</span></span> <span data-ttu-id="8bab0-179">藉由同時查看訂閱開始日期與結束日期，您就可以判斷客戶是否仍在第一年訂閱期內，或下一年的訂閱已續約。</span><span class="sxs-lookup"><span data-stu-id="8bab0-179">By looking at the subscription start date in conjunction with the end date, you can determine if the customer is still within the first year of the subscription or if the subscription has been renewed for the following year.</span></span></p>
<p><span data-ttu-id="8bab0-180">時間一律是一天的開始時間 (0:00)。</span><span class="sxs-lookup"><span data-stu-id="8bab0-180">The time is always the beginning of the day, 0:00.</span></span></p></td>
<td><span data-ttu-id="8bab0-181">2/1/2015 0:00</span><span class="sxs-lookup"><span data-stu-id="8bab0-181">2/1/2015 0:00</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8bab0-182">SubscriptionEndDate</span><span class="sxs-lookup"><span data-stu-id="8bab0-182">SubscriptionEndDate</span></span></td>
<td><p><span data-ttu-id="8bab0-183">訂用帳戶結束日期：12 個月 + x 天後 （以配合計費日期的夥伴） 的開始日期或續約日期起的 12 個月。</span><span class="sxs-lookup"><span data-stu-id="8bab0-183">The subscription end date: 12 months + x days after start date (to align with partner billing date) or 12 months from renewal date.</span></span></p>
<p><span data-ttu-id="8bab0-184">續約時，價格會更新至目前的價目表。</span><span class="sxs-lookup"><span data-stu-id="8bab0-184">At renewal, prices are updated to the current price list.</span></span> <span data-ttu-id="8bab0-185">自動續約之前，可能需要與客戶連絡。</span><span class="sxs-lookup"><span data-stu-id="8bab0-185">Customer communication may be required in advance of automated renewal.</span></span></p>
<p><span data-ttu-id="8bab0-186">時間一律是一天的開始時間 (0:00)。</span><span class="sxs-lookup"><span data-stu-id="8bab0-186">The time is always the beginning of the day, 0:00.</span></span></p></td>
<td><span data-ttu-id="8bab0-187">2/1/2015 0:00</span><span class="sxs-lookup"><span data-stu-id="8bab0-187">2/1/2015 0:00</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8bab0-188">ChargeStartDate</span><span class="sxs-lookup"><span data-stu-id="8bab0-188">ChargeStartDate</span></span></td>
<td><p><span data-ttu-id="8bab0-189">開始計算費用的日期。</span><span class="sxs-lookup"><span data-stu-id="8bab0-189">Start day of the charges.</span></span></p>
<p><span data-ttu-id="8bab0-190">當客戶變更基座數目時，此數字用於計算每日 (按比例) 的費用。</span><span class="sxs-lookup"><span data-stu-id="8bab0-190">When a customer changes seat numbers, this number is used to calculate per-day (pro-rata) charges.</span></span></p>
<p><span data-ttu-id="8bab0-191">時間一律是一天的開始時間 (0:00)。</span><span class="sxs-lookup"><span data-stu-id="8bab0-191">The time is always the beginning of the day, 0:00.</span></span></p></td>
<td><span data-ttu-id="8bab0-192">2/1/2015 0:00</span><span class="sxs-lookup"><span data-stu-id="8bab0-192">2/1/2015 0:00</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8bab0-193">ChargeEndDate</span><span class="sxs-lookup"><span data-stu-id="8bab0-193">ChargeEndDate</span></span></td>
<td><p><span data-ttu-id="8bab0-194">結束計算費用的日期。</span><span class="sxs-lookup"><span data-stu-id="8bab0-194">End day of the charges.</span></span></p>
<p><span data-ttu-id="8bab0-195">當客戶變更基座數目時，此數字用於計算每日 (按比例) 的費用。</span><span class="sxs-lookup"><span data-stu-id="8bab0-195">When a customer changes seat numbers, this number is used to calculate per-day (pro-rata) charges.</span></span></p>
<p><span data-ttu-id="8bab0-196">時間一律是一天的結束時間 (23:59)。</span><span class="sxs-lookup"><span data-stu-id="8bab0-196">The time is always the end of the day, 23:59.</span></span></p></td>
<td><span data-ttu-id="8bab0-197">2/28/2015 23:59</span><span class="sxs-lookup"><span data-stu-id="8bab0-197">2/28/2015 23:59</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8bab0-198">ChargeType</span><span class="sxs-lookup"><span data-stu-id="8bab0-198">ChargeType</span></span></td>
<td><p><span data-ttu-id="8bab0-199">費用或調整的類型。</span><span class="sxs-lookup"><span data-stu-id="8bab0-199">The type of charge or adjustment.</span></span> <span data-ttu-id="8bab0-200">請參閱<a href="#charge_types">對應發票和對帳檔案之間的費用</a></span><span class="sxs-lookup"><span data-stu-id="8bab0-200">See <a href="#charge_types">Mapping charges between an invoice and the reconciliation file</a></span></span></p></td>
<td><p><span data-ttu-id="8bab0-201">請參閱<a href="#charge_types">對應發票和對帳檔案之間的費用</a></span><span class="sxs-lookup"><span data-stu-id="8bab0-201">See <a href="#charge_types">Mapping charges between an invoice and the reconciliation file</a></span></span></p></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8bab0-202">UnitPrice</span><span class="sxs-lookup"><span data-stu-id="8bab0-202">UnitPrice</span></span></td>
<td><p><span data-ttu-id="8bab0-203">每一基座價格，即購買時價目表中所公佈的價格。</span><span class="sxs-lookup"><span data-stu-id="8bab0-203">Price per seat, as published in the pricelist at the time of purchase.</span></span> <span data-ttu-id="8bab0-204">請確定這與對帳期間儲存在您帳單系統中的資訊相符。</span><span class="sxs-lookup"><span data-stu-id="8bab0-204">Ensure this matches the information stored in your billing system during reconciliation.</span></span></p></td>
<td><span data-ttu-id="8bab0-205">6.82</span><span class="sxs-lookup"><span data-stu-id="8bab0-205">6.82</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8bab0-206">數量</span><span class="sxs-lookup"><span data-stu-id="8bab0-206">Quantity</span></span></td>
<td><p><span data-ttu-id="8bab0-207">基座數目。</span><span class="sxs-lookup"><span data-stu-id="8bab0-207">Number of seats.</span></span> <span data-ttu-id="8bab0-208">請確定這與對帳期間儲存在您帳單系統中的資訊相符。</span><span class="sxs-lookup"><span data-stu-id="8bab0-208">Ensure this matches the information stored in your billing system during reconciliation.</span></span></p></td>
<td><span data-ttu-id="8bab0-209">2</span><span class="sxs-lookup"><span data-stu-id="8bab0-209">2</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8bab0-210">數量</span><span class="sxs-lookup"><span data-stu-id="8bab0-210">Amount</span></span></td>
<td><p><span data-ttu-id="8bab0-211">數量總價。</span><span class="sxs-lookup"><span data-stu-id="8bab0-211">Total of price for quantity.</span></span> <span data-ttu-id="8bab0-212">檢查計算金額與您用來為客戶計算此項目的方式是否相符時很有用。</span><span class="sxs-lookup"><span data-stu-id="8bab0-212">Useful to check that the amount calculation matches how you calculate this for your customers.</span></span></p></td>
<td><span data-ttu-id="8bab0-213">13.32</span><span class="sxs-lookup"><span data-stu-id="8bab0-213">13.32</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8bab0-214">TotalOtherDiscount</span><span class="sxs-lookup"><span data-stu-id="8bab0-214">TotalOtherDiscount</span></span></td>
<td><p><span data-ttu-id="8bab0-215">套用至這些費用的折扣金額。</span><span class="sxs-lookup"><span data-stu-id="8bab0-215">Amount of discount applied to these charges.</span></span> <span data-ttu-id="8bab0-216">符合獎勵資格之 IUR 或新訂閱的訂單，也將於此欄中包含折扣金額。</span><span class="sxs-lookup"><span data-stu-id="8bab0-216">IUR or new subscriptions eligible for an incentive will also contain a discount amount in this column.</span></span></p></td>
<td><span data-ttu-id="8bab0-217">2.32</span><span class="sxs-lookup"><span data-stu-id="8bab0-217">2.32</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8bab0-218">小計</span><span class="sxs-lookup"><span data-stu-id="8bab0-218">Subtotal</span></span></td>
<td><p><span data-ttu-id="8bab0-219">稅前總計。</span><span class="sxs-lookup"><span data-stu-id="8bab0-219">Total before tax.</span></span> <span data-ttu-id="8bab0-220">如果有折扣，可檢查小計是否和預期的總金額相符。</span><span class="sxs-lookup"><span data-stu-id="8bab0-220">Checks that your subtotal matches your expected total, in case of a discount.</span></span></p></td>
<td><span data-ttu-id="8bab0-221">11</span><span class="sxs-lookup"><span data-stu-id="8bab0-221">11</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8bab0-222">稅</span><span class="sxs-lookup"><span data-stu-id="8bab0-222">Tax</span></span></td>
<td><p><span data-ttu-id="8bab0-223">稅務量費用，費用，根據您的市場&#39;s 稅務規則與特定的情況。</span><span class="sxs-lookup"><span data-stu-id="8bab0-223">Tax amount charge, based on your market&#39;s tax rules and specific circumstances.</span></span></p></td>
<td><span data-ttu-id="8bab0-224">0</span><span class="sxs-lookup"><span data-stu-id="8bab0-224">0</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8bab0-225">TotalForCustomer</span><span class="sxs-lookup"><span data-stu-id="8bab0-225">TotalForCustomer</span></span></td>
<td><p><span data-ttu-id="8bab0-226">稅後總計。</span><span class="sxs-lookup"><span data-stu-id="8bab0-226">Total after tax.</span></span> <span data-ttu-id="8bab0-227">檢查發票中是否向您收取稅金。</span><span class="sxs-lookup"><span data-stu-id="8bab0-227">Checks if you are charged tax in the invoice.</span></span></p></td>
<td><span data-ttu-id="8bab0-228">11</span><span class="sxs-lookup"><span data-stu-id="8bab0-228">11</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8bab0-229">貨幣</span><span class="sxs-lookup"><span data-stu-id="8bab0-229">Currency</span></span></td>
<td><p><span data-ttu-id="8bab0-230">貨幣類型。</span><span class="sxs-lookup"><span data-stu-id="8bab0-230">Currency type.</span></span> <span data-ttu-id="8bab0-231">每一帳單實體都只有一種貨幣。</span><span class="sxs-lookup"><span data-stu-id="8bab0-231">Each billing entity has only one currency.</span></span> <span data-ttu-id="8bab0-232">檢查是否與您的第一張發票相符，然後在進行任何重大帳單平台更新之後檢查。</span><span class="sxs-lookup"><span data-stu-id="8bab0-232">Check that it matches your first invoice and then after any major billing platform update.</span></span></p></td>
<td><span data-ttu-id="8bab0-233">EUR</span><span class="sxs-lookup"><span data-stu-id="8bab0-233">EUR</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8bab0-234">CustomerName</span><span class="sxs-lookup"><span data-stu-id="8bab0-234">CustomerName</span></span></td>
<td><p><span data-ttu-id="8bab0-235">客戶&#39;合作夥伴中心中所報告的 s 的組織名稱。</span><span class="sxs-lookup"><span data-stu-id="8bab0-235">Customer&#39;s organization name as reported in Partner Center.</span></span> <span data-ttu-id="8bab0-236">這在使用您的系統資訊對帳發票時非常重要。</span><span class="sxs-lookup"><span data-stu-id="8bab0-236">This is very important for reconciling the invoice with your system information.</span></span></p></td>
<td><span data-ttu-id="8bab0-237">測試客戶 A</span><span class="sxs-lookup"><span data-stu-id="8bab0-237">Test Customer A</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8bab0-238">MPNID</span><span class="sxs-lookup"><span data-stu-id="8bab0-238">MPNID</span></span></td>
<td><p><span data-ttu-id="8bab0-239">雲端解決方案提供者合作夥伴的 MPN 識別碼</span><span class="sxs-lookup"><span data-stu-id="8bab0-239">MPN ID of the CSP partner</span></span></p></td>
<td><span data-ttu-id="8bab0-240">4390934</span><span class="sxs-lookup"><span data-stu-id="8bab0-240">4390934</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8bab0-241">ResellerMPNID</span><span class="sxs-lookup"><span data-stu-id="8bab0-241">ResellerMPNID</span></span></td>
<td><p><span data-ttu-id="8bab0-242">訂閱記錄中的經銷商 MPN 識別碼。</span><span class="sxs-lookup"><span data-stu-id="8bab0-242">MPN ID of the reseller of record for the subscription.</span></span> <span data-ttu-id="8bab0-243">請參閱<a href="#itemizebypartner" data-raw-source="[Itemize by partner](#itemizebypartner)">依合作夥伴詳細列舉</a>。</span><span class="sxs-lookup"><span data-stu-id="8bab0-243">See <a href="#itemizebypartner" data-raw-source="[Itemize by partner](#itemizebypartner)">Itemize by partner</a>.</span></span></p></td>
<td><span data-ttu-id="8bab0-244">4390934</span><span class="sxs-lookup"><span data-stu-id="8bab0-244">4390934</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8bab0-245">DomainName</span><span class="sxs-lookup"><span data-stu-id="8bab0-245">DomainName</span></span></td>
<td><p><span data-ttu-id="8bab0-246">客戶&#39;用來協助識別客戶的 s 網域名稱。</span><span class="sxs-lookup"><span data-stu-id="8bab0-246">Customer&#39;s domain name, used to help identify the customer.</span></span> <span data-ttu-id="8bab0-247">這不應該用來唯一識別客戶，客戶/合作夥伴可以更新透過 O365 入口網站的虛名/預設網域。</span><span class="sxs-lookup"><span data-stu-id="8bab0-247">This should not be used to uniquely identify the customer as the customer/partner can update the vanity/default domain via the O365 portal.</span></span> <span data-ttu-id="8bab0-248">在下一個帳單週期之前，此欄位會是空白的。</span><span class="sxs-lookup"><span data-stu-id="8bab0-248">This field may appear blank until the second billing cycle.</span></span></p></td>
<td><span data-ttu-id="8bab0-249">example.onmicrosoft.com</span><span class="sxs-lookup"><span data-stu-id="8bab0-249">example.onmicrosoft.com</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8bab0-250">SubscriptionName</span><span class="sxs-lookup"><span data-stu-id="8bab0-250">SubscriptionName</span></span></td>
<td><p><span data-ttu-id="8bab0-251">訂閱暱稱。</span><span class="sxs-lookup"><span data-stu-id="8bab0-251">Subscription nickname.</span></span> <span data-ttu-id="8bab0-252">如果未指定任何暱稱，合作夥伴中心會使用 OfferName。</span><span class="sxs-lookup"><span data-stu-id="8bab0-252">If no nickname is specified, Partner Center uses the OfferName.</span></span></p></td>
<td><span data-ttu-id="8bab0-253">PROJECT ONLINE</span><span class="sxs-lookup"><span data-stu-id="8bab0-253">PROJECT ONLINE</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8bab0-254">SubscriptionDescription</span><span class="sxs-lookup"><span data-stu-id="8bab0-254">SubscriptionDescription</span></span></td>
<td><p><span data-ttu-id="8bab0-255">客戶購買的服務優惠名稱，如價目表中所定義。</span><span class="sxs-lookup"><span data-stu-id="8bab0-255">The name of the service offering purchased by the customer, as defined in the price list.</span></span> <span data-ttu-id="8bab0-256">（這是優惠名稱的相同欄位）。</span><span class="sxs-lookup"><span data-stu-id="8bab0-256">(This is an identical field to Offer name).</span></span></p></td>
<td><span data-ttu-id="8bab0-257">PROJECT ONLINE PREMIUM WITHOUT PROJECT CLIENT</span><span class="sxs-lookup"><span data-stu-id="8bab0-257">PROJECT ONLINE PREMIUM WITHOUT PROJECT CLIENT</span></span></td>
</tr>
</tbody>
</table>


## <a href="" id="usagebasedfiles"></a><span data-ttu-id="8bab0-258">基於使用方式檔案欄位</span><span class="sxs-lookup"><span data-stu-id="8bab0-258">Usage-based file fields</span></span>


<span data-ttu-id="8bab0-259">若要針對您客戶使用量的費用來對帳，請比較對帳檔案中的 ResellerID/ResellerName/ResellerBillableAccount、客戶名稱，與合作夥伴中心的訂閱識別碼。</span><span class="sxs-lookup"><span data-stu-id="8bab0-259">To reconcile your charges against your customer's usage, compare the ResellerID/ResellerName/ResellerBillableAccount from the reconciliation file, the customer name, and the Subscription ID from Partner Center.</span></span>

<span data-ttu-id="8bab0-260">下列欄位說明使用哪些服務及費率。</span><span class="sxs-lookup"><span data-stu-id="8bab0-260">The following fields explain which services were used and the rate.</span></span>

<table>
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<tbody>
<tr class="odd">
<td><strong><span data-ttu-id="8bab0-261">Column</span><span class="sxs-lookup"><span data-stu-id="8bab0-261">Column</span></span></strong></td>
<td><strong><span data-ttu-id="8bab0-262">描述</span><span class="sxs-lookup"><span data-stu-id="8bab0-262">Description</span></span></strong></td>
<td><strong><span data-ttu-id="8bab0-263">範例值</span><span class="sxs-lookup"><span data-stu-id="8bab0-263">Sample value</span></span></strong></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8bab0-264">PartnerID</span><span class="sxs-lookup"><span data-stu-id="8bab0-264">PartnerID</span></span></td>
<td><p><span data-ttu-id="8bab0-265">合作夥伴識別碼 (GUID 格式)。</span><span class="sxs-lookup"><span data-stu-id="8bab0-265">Partner ID, in GUID format.</span></span></p></td>
<td><span data-ttu-id="8bab0-266">DA41BC5F-C52D-4464-8A8D-8C8DCC43503B</span><span class="sxs-lookup"><span data-stu-id="8bab0-266">DA41BC5F-C52D-4464-8A8D-8C8DCC43503B</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8bab0-267">PartnerName</span><span class="sxs-lookup"><span data-stu-id="8bab0-267">PartnerName</span></span></td>
<td><p><span data-ttu-id="8bab0-268">合作夥伴名稱。</span><span class="sxs-lookup"><span data-stu-id="8bab0-268">Partner Name.</span></span></p></td>
<td><span data-ttu-id="8bab0-269">Acme Incorporated</span><span class="sxs-lookup"><span data-stu-id="8bab0-269">Acme Incorporated</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8bab0-270">PartnerBillableAccountID</span><span class="sxs-lookup"><span data-stu-id="8bab0-270">PartnerBillableAccountID</span></span></td>
<td><p><span data-ttu-id="8bab0-271">合作夥伴帳戶識別碼。</span><span class="sxs-lookup"><span data-stu-id="8bab0-271">Partner Account ID.</span></span></p></td>
<td><span data-ttu-id="8bab0-272">1010578050</span><span class="sxs-lookup"><span data-stu-id="8bab0-272">1010578050</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8bab0-273">CustomerName</span><span class="sxs-lookup"><span data-stu-id="8bab0-273">CustomerName</span></span></td>
<td><p><span data-ttu-id="8bab0-274">客戶&#39;合作夥伴中心中所報告的 s 的組織名稱。</span><span class="sxs-lookup"><span data-stu-id="8bab0-274">Customer&#39;s organization name as reported in Partner Center.</span></span> <span data-ttu-id="8bab0-275">這在使用您的系統資訊對帳發票時非常重要。</span><span class="sxs-lookup"><span data-stu-id="8bab0-275">This is very important for reconciling the invoice with your system information.</span></span></p></td>
<td><span data-ttu-id="8bab0-276">測試客戶 A</span><span class="sxs-lookup"><span data-stu-id="8bab0-276">Test Customer A</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8bab0-277">MPNID</span><span class="sxs-lookup"><span data-stu-id="8bab0-277">MPNID</span></span></td>
<td><p><span data-ttu-id="8bab0-278">雲端解決方案提供者合作夥伴的 MPN 識別碼。</span><span class="sxs-lookup"><span data-stu-id="8bab0-278">MPN ID of the CSP partner.</span></span></p></td>
<td><span data-ttu-id="8bab0-279">4390934</span><span class="sxs-lookup"><span data-stu-id="8bab0-279">4390934</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8bab0-280">ResellerMPNID</span><span class="sxs-lookup"><span data-stu-id="8bab0-280">ResellerMPNID</span></span></td>
<td><p><span data-ttu-id="8bab0-281">訂閱記錄中的經銷商 MPN 識別碼。</span><span class="sxs-lookup"><span data-stu-id="8bab0-281">MPN ID of the reseller of record for the subscription.</span></span> <span data-ttu-id="8bab0-282">請參閱<a href="#itemizebypartner" data-raw-source="[Itemize by partner](#itemizebypartner)">依合作夥伴詳細列舉</a>。</span><span class="sxs-lookup"><span data-stu-id="8bab0-282">See <a href="#itemizebypartner" data-raw-source="[Itemize by partner](#itemizebypartner)">Itemize by partner</a>.</span></span></p></td>
<td><span data-ttu-id="8bab0-283">4390934</span><span class="sxs-lookup"><span data-stu-id="8bab0-283">4390934</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8bab0-284">InvoiceNumber</span><span class="sxs-lookup"><span data-stu-id="8bab0-284">InvoiceNumber</span></span></td>
<td><p><span data-ttu-id="8bab0-285">交易的指定位置顯示的發票號碼。</span><span class="sxs-lookup"><span data-stu-id="8bab0-285">Invoice number where the specified transaction appears.</span></span></p></td>
<td><span data-ttu-id="8bab0-286">D020001IVK</span><span class="sxs-lookup"><span data-stu-id="8bab0-286">D020001IVK</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8bab0-287">ChargeStartDate</span><span class="sxs-lookup"><span data-stu-id="8bab0-287">ChargeStartDate</span></span></td>
<td><p><span data-ttu-id="8bab0-288">計費週期的開始日期，當顯示之前未收取潛在使用量資料費用的日期時除外 (從前一個計費週期開始)。</span><span class="sxs-lookup"><span data-stu-id="8bab0-288">Start date of billing cycle except when presenting dates of previously uncharged latent usage data (from previous bill cycle).</span></span></p>
<p><span data-ttu-id="8bab0-289">時間一律是一天的開始時間 (0:00)。</span><span class="sxs-lookup"><span data-stu-id="8bab0-289">The time is always the beginning of the day, 0:00.</span></span></p></td>
<td><span data-ttu-id="8bab0-290">2/1/2014 0:00</span><span class="sxs-lookup"><span data-stu-id="8bab0-290">2/1/2014 0:00</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8bab0-291">ChargeEndDate</span><span class="sxs-lookup"><span data-stu-id="8bab0-291">ChargeEndDate</span></span></td>
<td><p><span data-ttu-id="8bab0-292">計費週期的結束日期，當顯示之前未收取潛在使用量資料費用的日期時除外 (從前一個計費週期開始)。</span><span class="sxs-lookup"><span data-stu-id="8bab0-292">End date of billing cycle except when presenting dates of previously uncharged latent usage data (from previous bill cycle).</span></span></p>
<p><span data-ttu-id="8bab0-293">時間一律是一天的結束時間 (23:59)。</span><span class="sxs-lookup"><span data-stu-id="8bab0-293">The time is always the end of the day, 23:59.</span></span></p></td>
<td><span data-ttu-id="8bab0-294">2/28/2014 23:59</span><span class="sxs-lookup"><span data-stu-id="8bab0-294">2/28/2014 23:59</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8bab0-295">SubscriptionID</span><span class="sxs-lookup"><span data-stu-id="8bab0-295">SubscriptionID</span></span></td>
<td><p><span data-ttu-id="8bab0-296">訂閱在 Microsoft 帳單平台中的唯一識別碼。</span><span class="sxs-lookup"><span data-stu-id="8bab0-296">Unique identifier for a subscription in the Microsoft billing platform.</span></span> <span data-ttu-id="8bab0-297">可在連絡支援時方便識別訂閱，但不是用於對帳。</span><span class="sxs-lookup"><span data-stu-id="8bab0-297">May be useful to identify the subscription when contacting support but not for reconciliation.</span></span></p>
<p><span data-ttu-id="8bab0-298">這與合作夥伴管理主控台上的訂閱識別碼不一樣。</span><span class="sxs-lookup"><span data-stu-id="8bab0-298">This is not the same as the Subscription ID on the Partner Admin Console.</span></span></p></td>
<td><span data-ttu-id="8bab0-299">usCBMgAAAAAAAAIA</span><span class="sxs-lookup"><span data-stu-id="8bab0-299">usCBMgAAAAAAAAIA</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8bab0-300">SubscriptionName</span><span class="sxs-lookup"><span data-stu-id="8bab0-300">SubscriptionName</span></span></td>
<td><p><span data-ttu-id="8bab0-301">服務優惠的暱稱。</span><span class="sxs-lookup"><span data-stu-id="8bab0-301">Nickname of the service offering.</span></span></p></td>
<td><span data-ttu-id="8bab0-302">Microsoft Azure</span><span class="sxs-lookup"><span data-stu-id="8bab0-302">Microsoft Azure</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8bab0-303">SubscriptionDescription</span><span class="sxs-lookup"><span data-stu-id="8bab0-303">SubscriptionDescription</span></span></td>
<td><p><span data-ttu-id="8bab0-304">服務優惠的企業營運</span><span class="sxs-lookup"><span data-stu-id="8bab0-304">Line of business of the service offering</span></span></p></td>
<td><span data-ttu-id="8bab0-305">Microsoft Azure</span><span class="sxs-lookup"><span data-stu-id="8bab0-305">Microsoft Azure</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8bab0-306">OrderID</span><span class="sxs-lookup"><span data-stu-id="8bab0-306">OrderID</span></span></td>
<td><p><span data-ttu-id="8bab0-307">訂單在 Microsoft 帳單平台中的唯一識別碼。</span><span class="sxs-lookup"><span data-stu-id="8bab0-307">Unique identifier for an order in the Microsoft billing platform.</span></span> <span data-ttu-id="8bab0-308">可在連絡支援時方便識別訂閱，但不是用於對帳。</span><span class="sxs-lookup"><span data-stu-id="8bab0-308">May be useful to identify the subscription when contacting support but not for reconciliation.</span></span></p></td>
<td><span data-ttu-id="8bab0-309">566890604832738111</span><span class="sxs-lookup"><span data-stu-id="8bab0-309">566890604832738111</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8bab0-310">ServiceName</span><span class="sxs-lookup"><span data-stu-id="8bab0-310">ServiceName</span></span></td>
<td><p><span data-ttu-id="8bab0-311">要求的 Azure 服務名稱。</span><span class="sxs-lookup"><span data-stu-id="8bab0-311">The name of the Azure service in question.</span></span></p></td>
<td><span data-ttu-id="8bab0-312">虛擬機器</span><span class="sxs-lookup"><span data-stu-id="8bab0-312">VIRTUAL MACHINES</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8bab0-313">ServiceType</span><span class="sxs-lookup"><span data-stu-id="8bab0-313">ServiceType</span></span></td>
<td><p><span data-ttu-id="8bab0-314">Microsoft Azure 服務的特定類型。</span><span class="sxs-lookup"><span data-stu-id="8bab0-314">The specific type of Windows Azure service.</span></span></p></td>
<td><ul>
<li><span data-ttu-id="8bab0-315">服務匯流排 – 個人或套件</span><span class="sxs-lookup"><span data-stu-id="8bab0-315">Service Bus – Individual or Pack</span></span></li>
<li><span data-ttu-id="8bab0-316">SQL Azure 資料庫 – Business 或 Web Edition</span><span class="sxs-lookup"><span data-stu-id="8bab0-316">SQL Azure database – Business or Web Edition</span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8bab0-317">ResourceGUID</span><span class="sxs-lookup"><span data-stu-id="8bab0-317">ResourceGUID</span></span></td>
<td><p><span data-ttu-id="8bab0-318">所有服務資料與定價結構的特定唯一識別碼。</span><span class="sxs-lookup"><span data-stu-id="8bab0-318">Specific unique identifier for all the service data and pricing structure.</span></span></p></td>
<td><span data-ttu-id="8bab0-319">DA41BC5F-C52D-4464-8A8D-8C8DCC43503B</span><span class="sxs-lookup"><span data-stu-id="8bab0-319">DA41BC5F-C52D-4464-8A8D-8C8DCC43503B</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8bab0-320">Resource Name</span><span class="sxs-lookup"><span data-stu-id="8bab0-320">Resource Name</span></span></td>
<td><p><span data-ttu-id="8bab0-321">Azure 資源的名稱。</span><span class="sxs-lookup"><span data-stu-id="8bab0-321">The name of the Azure resource.</span></span></p></td>
<td><ul>
<li><span data-ttu-id="8bab0-322">資料轉入 (GB)</span><span class="sxs-lookup"><span data-stu-id="8bab0-322">Data Transfer In (GB)</span></span></li>
<li><span data-ttu-id="8bab0-323">資料轉出 (GB)</span><span class="sxs-lookup"><span data-stu-id="8bab0-323">Data Transfer Out (GB)</span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8bab0-324">地區</span><span class="sxs-lookup"><span data-stu-id="8bab0-324">Region</span></span></td>
<td><p><span data-ttu-id="8bab0-325">使用量適用的地區。</span><span class="sxs-lookup"><span data-stu-id="8bab0-325">The region the usage applies to.</span></span> <span data-ttu-id="8bab0-326">主要用來指定資料傳輸速率，費率因地區而異。</span><span class="sxs-lookup"><span data-stu-id="8bab0-326">Primarily used to assign rates to data transfers, as rates vary by region.</span></span></p></td>
<td><span data-ttu-id="8bab0-327">亞太地區、歐洲、拉丁美洲、北美洲</span><span class="sxs-lookup"><span data-stu-id="8bab0-327">Asia Pacific, Europe, Latin America, North America</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8bab0-328">SKU</span><span class="sxs-lookup"><span data-stu-id="8bab0-328">SKU</span></span></td>
<td><p><span data-ttu-id="8bab0-329">優惠的 MSFT 唯一識別碼</span><span class="sxs-lookup"><span data-stu-id="8bab0-329">MSFT unique identifier for offer</span></span></p></td>
<td><span data-ttu-id="8bab0-330">7UD 00001</span><span class="sxs-lookup"><span data-stu-id="8bab0-330">7UD-00001</span></span></td>
</tr>
<tr class="odd">
<td><p><span data-ttu-id="8bab0-331">DetailLineItemId</span><span class="sxs-lookup"><span data-stu-id="8bab0-331">DetailLineItemId</span></span></p></td>
<td><p><span data-ttu-id="8bab0-332">用於詳細列出指定計費期間中，服務或資源不同費率的識別碼和數量。</span><span class="sxs-lookup"><span data-stu-id="8bab0-332">An ID and quantity for itemizing the different rates for a service or resource in a given billing period.</span></span> <span data-ttu-id="8bab0-333">對於 Azure 分層評分，到某個數量的計費單位會有一個評分，之後則有不同評分。</span><span class="sxs-lookup"><span data-stu-id="8bab0-333">For Azure tiered rating, there may be one rate up to a certain quantity of billable units, then a different rate after that.</span></span></p></td>
<td><span data-ttu-id="8bab0-334">1</span><span class="sxs-lookup"><span data-stu-id="8bab0-334">1</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8bab0-335">ConsumedQuantity</span><span class="sxs-lookup"><span data-stu-id="8bab0-335">ConsumedQuantity</span></span></td>
<td><p><span data-ttu-id="8bab0-336">報表期間耗用的服務量 (小時、GB 等等)</span><span class="sxs-lookup"><span data-stu-id="8bab0-336">The amount of service consumed (hours, GB, etc.) during the reporting period.</span></span></p>
<p><span data-ttu-id="8bab0-337">同時包括先前報表期間任何未計費的使用量。</span><span class="sxs-lookup"><span data-stu-id="8bab0-337">Also includes any unbilled usage from previous reporting periods.</span></span></p></td>
<td><span data-ttu-id="8bab0-338">11</span><span class="sxs-lookup"><span data-stu-id="8bab0-338">11</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8bab0-339">IncludedQuantity</span><span class="sxs-lookup"><span data-stu-id="8bab0-339">IncludedQuantity</span></span></td>
<td><p><span data-ttu-id="8bab0-340">包含在優惠中的單位。</span><span class="sxs-lookup"><span data-stu-id="8bab0-340">Units included as part of the offer.</span></span> <span data-ttu-id="8bab0-341">通常不會出現在雲端解決方案提供者中。</span><span class="sxs-lookup"><span data-stu-id="8bab0-341">Not typically present in CSP.</span></span></p></td>
<td><span data-ttu-id="8bab0-342">0</span><span class="sxs-lookup"><span data-stu-id="8bab0-342">0</span></span></td>
</tr>
<tr class="even">
<td><p><span data-ttu-id="8bab0-343">OverageQuantity</span><span class="sxs-lookup"><span data-stu-id="8bab0-343">OverageQuantity</span></span></p></td>
<td><p><span data-ttu-id="8bab0-344">不包含在優惠中的單位，必須由合作夥伴支付。</span><span class="sxs-lookup"><span data-stu-id="8bab0-344">Units not included as part of the offer, that must be paid for by the partner.</span></span></p>
<p><span data-ttu-id="8bab0-345">等同於 ConsumedQuantity - IncludedQuantity。</span><span class="sxs-lookup"><span data-stu-id="8bab0-345">Equal to the ConsumedQuantity - IncludedQuantity.</span></span></p></td>
<td><span data-ttu-id="8bab0-346">11</span><span class="sxs-lookup"><span data-stu-id="8bab0-346">11</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8bab0-347">ListPrice</span><span class="sxs-lookup"><span data-stu-id="8bab0-347">ListPrice</span></span></td>
<td><p><span data-ttu-id="8bab0-348">訂閱開始日期的生效優惠價格。</span><span class="sxs-lookup"><span data-stu-id="8bab0-348">Offer price in effect at subscription start date.</span></span></p></td>
<td><span data-ttu-id="8bab0-349">$0.0808</span><span class="sxs-lookup"><span data-stu-id="8bab0-349">$0.0808</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8bab0-350">PretaxCharges</span><span class="sxs-lookup"><span data-stu-id="8bab0-350">PretaxCharges</span></span></td>
<td><p><span data-ttu-id="8bab0-351">ListPrist 乘以 OverageQuantity，四捨五入至美分。</span><span class="sxs-lookup"><span data-stu-id="8bab0-351">ListPrist times OverageQuantity, rounded to the nearest cent.</span></span></p></td>
<td><span data-ttu-id="8bab0-352">$0.085</span><span class="sxs-lookup"><span data-stu-id="8bab0-352">$0.085</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8bab0-353">TaxAmount</span><span class="sxs-lookup"><span data-stu-id="8bab0-353">TaxAmount</span></span></td>
<td><p><span data-ttu-id="8bab0-354">稅務量費用，費用，根據您的市場&#39;s 稅務規則與特定的情況。</span><span class="sxs-lookup"><span data-stu-id="8bab0-354">Tax amount charge, based on your market&#39;s tax rules and specific circumstances.</span></span></p></td>
<td><span data-ttu-id="8bab0-355">$0.08</span><span class="sxs-lookup"><span data-stu-id="8bab0-355">$0.08</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8bab0-356">PostTaxTotal</span><span class="sxs-lookup"><span data-stu-id="8bab0-356">PostTaxTotal</span></span></td>
<td><p><span data-ttu-id="8bab0-357">稅後總計 (當適用稅金時)。</span><span class="sxs-lookup"><span data-stu-id="8bab0-357">Total after tax, when tax is applicable.</span></span></p></td>
<td><span data-ttu-id="8bab0-358">$0.93</span><span class="sxs-lookup"><span data-stu-id="8bab0-358">$0.93</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8bab0-359">貨幣</span><span class="sxs-lookup"><span data-stu-id="8bab0-359">Currency</span></span></td>
<td><p><span data-ttu-id="8bab0-360">貨幣類型。</span><span class="sxs-lookup"><span data-stu-id="8bab0-360">Currency type.</span></span> <span data-ttu-id="8bab0-361">每一帳單實體都只有一種貨幣。</span><span class="sxs-lookup"><span data-stu-id="8bab0-361">Each billing entity has only one currency.</span></span> <span data-ttu-id="8bab0-362">檢查是否與您的第一張發票相符，然後在進行任何重大帳單平台更新之後檢查。</span><span class="sxs-lookup"><span data-stu-id="8bab0-362">Check that it matches your first invoice and then after any major billing platform update.</span></span></p></td>
<td><span data-ttu-id="8bab0-363">EUR</span><span class="sxs-lookup"><span data-stu-id="8bab0-363">EUR</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8bab0-364">PretaxEffectiveRate</span><span class="sxs-lookup"><span data-stu-id="8bab0-364">PretaxEffectiveRate</span></span></td>
<td><p><span data-ttu-id="8bab0-365">每個單位的稅前價格。</span><span class="sxs-lookup"><span data-stu-id="8bab0-365">Pretax price per unit.</span></span> <span data-ttu-id="8bab0-366">等於 PretaxCharges / OverageQuantity, 四捨五入至美分。</span><span class="sxs-lookup"><span data-stu-id="8bab0-366">Equal to PretaxCharges / OverageQuantity, rounded to the nearest cent.</span></span></p></td>
<td><span data-ttu-id="8bab0-367">$0.08</span><span class="sxs-lookup"><span data-stu-id="8bab0-367">$0.08</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8bab0-368">PostTaxEffectiveRate</span><span class="sxs-lookup"><span data-stu-id="8bab0-368">PostTaxEffectiveRate</span></span></td>
<td><p><span data-ttu-id="8bab0-369">每個單位的稅後價格。</span><span class="sxs-lookup"><span data-stu-id="8bab0-369">Post tax price per unit.</span></span> <span data-ttu-id="8bab0-370">等於 PostTaxTotal / OverageQuantity，或 PretaxEffectiveRate + 每單位數量稅率，四捨五入至美分。</span><span class="sxs-lookup"><span data-stu-id="8bab0-370">Equal to PostTaxTotal / OverageQuantity, or PretaxEffectiveRate + tax rate per unit amoun, rounded to the nearest cent.</span></span></p></td>
<td><span data-ttu-id="8bab0-371">$0.08</span><span class="sxs-lookup"><span data-stu-id="8bab0-371">$0.08</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8bab0-372">ChargeType</span><span class="sxs-lookup"><span data-stu-id="8bab0-372">ChargeType</span></span></td>
<td><p><span data-ttu-id="8bab0-373">費用或調整的類型。</span><span class="sxs-lookup"><span data-stu-id="8bab0-373">The type of charge or adjustment.</span></span> <span data-ttu-id="8bab0-374">請參閱<a href="#charge_types">對應發票和對帳檔案之間的費用</a></span><span class="sxs-lookup"><span data-stu-id="8bab0-374">See <a href="#charge_types">Mapping charges between an invoice and the reconciliation file</a></span></span></p></td>
<td><p><span data-ttu-id="8bab0-375">請參閱<a href="#charge_types">對應發票和對帳檔案之間的費用</a></span><span class="sxs-lookup"><span data-stu-id="8bab0-375">See <a href="#charge_types">Mapping charges between an invoice and the reconciliation file</a></span></span></p></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8bab0-376">CustomerBillableAccount</span><span class="sxs-lookup"><span data-stu-id="8bab0-376">CustomerBillableAccount</span></span></td>
<td><p><span data-ttu-id="8bab0-377">MSFT 帳單平台的唯一帳戶識別碼。</span><span class="sxs-lookup"><span data-stu-id="8bab0-377">Unique account ID in the MSFT billing platform.</span></span></p></td>
<td><span data-ttu-id="8bab0-378">1280018095</span><span class="sxs-lookup"><span data-stu-id="8bab0-378">1280018095</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8bab0-379">UsageDate</span><span class="sxs-lookup"><span data-stu-id="8bab0-379">UsageDate</span></span></td>
<td><p><span data-ttu-id="8bab0-380">服務部署的日期。</span><span class="sxs-lookup"><span data-stu-id="8bab0-380">Date of service deployment.</span></span></p></td>
<td><span data-ttu-id="8bab0-381">2/1/2014 0:00</span><span class="sxs-lookup"><span data-stu-id="8bab0-381">2/1/2014 0:00</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8bab0-382">MeteredRegion</span><span class="sxs-lookup"><span data-stu-id="8bab0-382">MeteredRegion</span></span></td>
<td><p><span data-ttu-id="8bab0-383">此欄可識別適用及填入此項目之服務地區內的資料中心的位置。</span><span class="sxs-lookup"><span data-stu-id="8bab0-383">This column identifies the location of a data center within the region for services where this is applicable and populated.</span></span></p></td>
<td><span data-ttu-id="8bab0-384">東亞、東南亞、北歐、西歐、美國中北部、美國中南部</span><span class="sxs-lookup"><span data-stu-id="8bab0-384">East Asia, South East Asia, North Europe, West Europe, North Central US, South Central US</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8bab0-385">MeteredService</span><span class="sxs-lookup"><span data-stu-id="8bab0-385">MeteredService</span></span></td>
<td><p><span data-ttu-id="8bab0-386">此欄是用來追蹤可能未在 \[服務名稱\] 欄中特別指出的個別 Microsoft Azure 服務。</span><span class="sxs-lookup"><span data-stu-id="8bab0-386">This column is utilized to track the individual Microsoft Azure service that may not be specifically identified in the Service Name column.</span></span> <span data-ttu-id="8bab0-387">例如，在 \[服務名稱\] 欄中，資料傳輸是回報為 &quot;Microsoft Azure - 所有服務&quot;。</span><span class="sxs-lookup"><span data-stu-id="8bab0-387">For example, data transfers are reported as &quot;Microsoft Azure - All Services&quot; in the Service Name column.</span></span> <span data-ttu-id="8bab0-388">此 MeteredService 欄會指出使用量與哪個特定服務有關。</span><span class="sxs-lookup"><span data-stu-id="8bab0-388">This MeteredService column will indicate to which specific service the usage pertains.</span></span></p></td>
<td><span data-ttu-id="8bab0-389">AccessControl、CDN、Compute、Database、ServiceBus、Storage</span><span class="sxs-lookup"><span data-stu-id="8bab0-389">AccessControl, CDN, Compute, Database, ServiceBus, Storage</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8bab0-390">MeteredServiceType</span><span class="sxs-lookup"><span data-stu-id="8bab0-390">MeteredServiceType</span></span></td>
<td><p><span data-ttu-id="8bab0-391">進一步釐清超出 MeteredService 欄位提供之層級的個別 Microsoft Azure 服務副標題。</span><span class="sxs-lookup"><span data-stu-id="8bab0-391">A subheading that further clarifies the individual Microsoft Azure service beyond the level provided by the MeteredService field.</span></span></p></td>
<td><span data-ttu-id="8bab0-392">外部</span><span class="sxs-lookup"><span data-stu-id="8bab0-392">EXTERNAL</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8bab0-393">Project</span><span class="sxs-lookup"><span data-stu-id="8bab0-393">Project</span></span></td>
<td><p><span data-ttu-id="8bab0-394">客戶為其服務執行個體定義的名稱</span><span class="sxs-lookup"><span data-stu-id="8bab0-394">Customer-defined name for their service instance</span></span></p></td>
<td><span data-ttu-id="8bab0-395">ORDDC52E52FDEF405786F0642DD0108BE4</span><span class="sxs-lookup"><span data-stu-id="8bab0-395">ORDDC52E52FDEF405786F0642DD0108BE4</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8bab0-396">ServiceInfo</span><span class="sxs-lookup"><span data-stu-id="8bab0-396">ServiceInfo</span></span></td>
<td><p><span data-ttu-id="8bab0-397">於某一天佈建及使用的 ServiceBus 連線數目。</span><span class="sxs-lookup"><span data-stu-id="8bab0-397">The number of ServiceBus connections that were provisioned and utilized on a given day.</span></span></p></td>
<td><span data-ttu-id="8bab0-398">例如：如果您在有 30 天的月份中有個別佈建的連線時，「服務資訊 1」的讀數會是「1.000000 連線 / 30 天」。</span><span class="sxs-lookup"><span data-stu-id="8bab0-398">For example: if you had an individually provisioned connection during a 30 day month, Service Info 1 would read “1.000000 Connections / 30 days”.</span></span> <span data-ttu-id="8bab0-399">如果您有 25 的組件的佈建的服務匯流排連線，而且您必須在那一天使用 1，表示您那一天的每日使用量聲明 」 25 的連線 / 已使用的 30 天：1.000000”.</span><span class="sxs-lookup"><span data-stu-id="8bab0-399">If you had a 25 pack of ServiceBus connections provisioned and you had utilized 1 during that day, your daily usage statement for that day would indicate “25 Connections / 30 Days – Used: 1.000000”.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8bab0-400">CustomerID</span><span class="sxs-lookup"><span data-stu-id="8bab0-400">CustomerID</span></span></td>
<td><p><span data-ttu-id="8bab0-401">用來識別客戶的唯一 Microsoft ID（GUID 格式）。</span><span class="sxs-lookup"><span data-stu-id="8bab0-401">Unique Microsoft ID, in GUID format, used to identify the customer.</span></span></p></td>
<td><span data-ttu-id="8bab0-402">ORDDC52E52FDEF405786F0642DD0108BE4</span><span class="sxs-lookup"><span data-stu-id="8bab0-402">ORDDC52E52FDEF405786F0642DD0108BE4</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8bab0-403">DomainName</span><span class="sxs-lookup"><span data-stu-id="8bab0-403">DomainName</span></span></td>
<td><p><span data-ttu-id="8bab0-404">客戶&#39;用來協助識別客戶的 s 網域名稱。</span><span class="sxs-lookup"><span data-stu-id="8bab0-404">Customer&#39;s domain name, used to help identify the customer.</span></span> <span data-ttu-id="8bab0-405">在下一個帳單週期之前，此欄位會是空白的。</span><span class="sxs-lookup"><span data-stu-id="8bab0-405">This field may appear blank until the second billing cycle.</span></span></p></td>
<td><span data-ttu-id="8bab0-406">example.onmicrosoft.com</span><span class="sxs-lookup"><span data-stu-id="8bab0-406">example.onmicrosoft.com</span></span></td></tr>
</tr>
<tr class="even">
<td><span data-ttu-id="8bab0-407">單位</span><span class="sxs-lookup"><span data-stu-id="8bab0-407">Unit</span></span></td>
<td><p><span data-ttu-id="8bab0-408">資源名稱的單位</span><span class="sxs-lookup"><span data-stu-id="8bab0-408">The unit of the resource Name</span></span></p></td>
<td><span data-ttu-id="8bab0-409">GB 或 HOURS</span><span class="sxs-lookup"><span data-stu-id="8bab0-409">GB or HOURS</span></span></td>
</tr>
</tbody>
</table>

## <a href="" id="marketplacefilefields"></a><span data-ttu-id="8bab0-410">單次和週期的檔案欄位</span><span class="sxs-lookup"><span data-stu-id="8bab0-410">One-time and recurring file fields</span></span>

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th><span data-ttu-id="8bab0-411">Column</span><span class="sxs-lookup"><span data-stu-id="8bab0-411">Column</span></span></th>
<th><span data-ttu-id="8bab0-412">描述</span><span class="sxs-lookup"><span data-stu-id="8bab0-412">Description</span></span></th>
</tr>
</thead>
<tbody>


<tr class="odd">
<td><span data-ttu-id="8bab0-413">PartnerId</span><span class="sxs-lookup"><span data-stu-id="8bab0-413">PartnerId</span></span></td>
<td><p><span data-ttu-id="8bab0-414">唯一特定計費實體，則採用 GUID 格式的 Microsoft Azure Active Directory 租用戶識別碼。</span><span class="sxs-lookup"><span data-stu-id="8bab0-414">Unique Microsoft Azure Active Directory tenant identifier for a specific billing entity, in GUID format.</span></span> <span data-ttu-id="8bab0-415">對帳時不需要，但可能是很有用的資訊。</span><span class="sxs-lookup"><span data-stu-id="8bab0-415">Not required for reconciliation, however may be useful information.</span></span> <span data-ttu-id="8bab0-416">在所有資料列中都是如此。</span><span class="sxs-lookup"><span data-stu-id="8bab0-416">Same in all rows.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="8bab0-417">客戶識別碼</span><span class="sxs-lookup"><span data-stu-id="8bab0-417">Customer Id</span></span></td>
<td><p><span data-ttu-id="8bab0-418">Microsoft Azure Active Directory 租用戶中唯一識別碼，用來識別客戶的 GUID 格式。</span><span class="sxs-lookup"><span data-stu-id="8bab0-418">Unique Microsoft Azure Active Directory tenant ID, in GUID format, used to identify the customer.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="8bab0-419">[客戶名稱]</span><span class="sxs-lookup"><span data-stu-id="8bab0-419">Customer Name</span></span></td>
<td><p><span data-ttu-id="8bab0-420">合作夥伴中心中回報的客戶組織名稱。</span><span class="sxs-lookup"><span data-stu-id="8bab0-420">Customer's organization name as reported in Partner Center.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="8bab0-421">CustomerDomainName</span><span class="sxs-lookup"><span data-stu-id="8bab0-421">CustomerDomainName</span></span></td>
<td><p><span data-ttu-id="8bab0-422">用來協助識別客戶的客戶網域名稱。</span><span class="sxs-lookup"><span data-stu-id="8bab0-422">Customer's domain name, used to help identify the customer.</span></span> <span data-ttu-id="8bab0-423">這不應該用來唯一識別客戶，客戶/合作夥伴可以更新透過 O365 入口網站的虛名/預設網域。</span><span class="sxs-lookup"><span data-stu-id="8bab0-423">This should not be used to uniquely identify the customer as the customer/partner can update the vanity/default domain via the O365 portal.</span></span> <span data-ttu-id="8bab0-424">在下一個帳單週期之前，此欄位會是空白的。</span><span class="sxs-lookup"><span data-stu-id="8bab0-424">This field may appear blank until the second billing cycle.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="8bab0-425">客戶的國家/地區</span><span class="sxs-lookup"><span data-stu-id="8bab0-425">Customer Country</span></span></td>
<td><p><span data-ttu-id="8bab0-426">客戶所在的國家/地區。</span><span class="sxs-lookup"><span data-stu-id="8bab0-426">The country in which the customer is located.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="8bab0-427">發票號碼</span><span class="sxs-lookup"><span data-stu-id="8bab0-427">Invoice number</span></span></td>
<td><p><span data-ttu-id="8bab0-428">交易的指定位置顯示的發票號碼。</span><span class="sxs-lookup"><span data-stu-id="8bab0-428">Invoice number where the specified transaction appears.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="8bab0-429">MpnId</span><span class="sxs-lookup"><span data-stu-id="8bab0-429">MpnId</span></span></td>
<td><p><span data-ttu-id="8bab0-430">雲端解決方案提供者合作夥伴的 MPN 識別碼。</span><span class="sxs-lookup"><span data-stu-id="8bab0-430">MPN ID of the CSP partner.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="8bab0-431">Reseller MpnId</span><span class="sxs-lookup"><span data-stu-id="8bab0-431">Reseller MpnId</span></span></td>
<td><p><span data-ttu-id="8bab0-432">訂閱記錄中的經銷商 MPN 識別碼。</span><span class="sxs-lookup"><span data-stu-id="8bab0-432">MPN ID of the reseller of record for the subscription.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="8bab0-433">訂單識別碼</span><span class="sxs-lookup"><span data-stu-id="8bab0-433">Order ID</span></span></td>
<td><p><span data-ttu-id="8bab0-434">Microsoft commerce platform 中順序的唯一識別碼。</span><span class="sxs-lookup"><span data-stu-id="8bab0-434">Unique identifier for an order in the Microsoft commerce platform.</span></span> <span data-ttu-id="8bab0-435">可在連絡支援時方便識別訂單，但不是用於對帳。</span><span class="sxs-lookup"><span data-stu-id="8bab0-435">May be useful to identify the order when contacting support but not for reconciliation.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="8bab0-436">訂單日期</span><span class="sxs-lookup"><span data-stu-id="8bab0-436">Order date</span></span></td>
<td><p><span data-ttu-id="8bab0-437">下訂單的日期。</span><span class="sxs-lookup"><span data-stu-id="8bab0-437">The date the order was placed.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="8bab0-438">ProductId</span><span class="sxs-lookup"><span data-stu-id="8bab0-438">ProductId</span></span></td>
<td><p><span data-ttu-id="8bab0-439">產品的識別碼。</span><span class="sxs-lookup"><span data-stu-id="8bab0-439">The ID for the product.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="8bab0-440">SkuId</span><span class="sxs-lookup"><span data-stu-id="8bab0-440">SkuId</span></span></td>
<td><p><span data-ttu-id="8bab0-441">特定 SKU 的識別碼。</span><span class="sxs-lookup"><span data-stu-id="8bab0-441">The ID for a particular SKU.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="8bab0-442">AvailabilityId</span><span class="sxs-lookup"><span data-stu-id="8bab0-442">AvailabilityId</span></span></td>
<td><p><span data-ttu-id="8bab0-443">特定可用性的識別碼。</span><span class="sxs-lookup"><span data-stu-id="8bab0-443">The ID for a particular Availability.</span></span> <span data-ttu-id="8bab0-444">「可用性」是指特定 SKU 是否可供特定的國家/地區、貨幣、行業區段等等購買。</span><span class="sxs-lookup"><span data-stu-id="8bab0-444">“Availability” refers to whether or not a particular SKU is available for purchase for the given country, currency, industry segment, etc.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="8bab0-445">SKU 名稱</span><span class="sxs-lookup"><span data-stu-id="8bab0-445">SKU Name</span></span></td>
<td><p><span data-ttu-id="8bab0-446">特定 SKU 的標題。</span><span class="sxs-lookup"><span data-stu-id="8bab0-446">The title for a particular SKU.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="8bab0-447">產品名稱</span><span class="sxs-lookup"><span data-stu-id="8bab0-447">Product name</span></span></td>
<td><p><span data-ttu-id="8bab0-448">產品的名稱。</span><span class="sxs-lookup"><span data-stu-id="8bab0-448">The name of the product.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="8bab0-449">PublisherName</span><span class="sxs-lookup"><span data-stu-id="8bab0-449">PublisherName</span></span></td>
<td><p><span data-ttu-id="8bab0-450">產品的 「 發行者 」 的名稱。</span><span class="sxs-lookup"><span data-stu-id="8bab0-450">The name of the product’s publisher.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="8bab0-451">PublisherID</span><span class="sxs-lookup"><span data-stu-id="8bab0-451">PublisherID</span></span></td>
<td><p><span data-ttu-id="8bab0-452">這個 「 發行者 」 的唯一識別碼。</span><span class="sxs-lookup"><span data-stu-id="8bab0-452">Unique ID for this publisher.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="8bab0-453">訂用帳戶描述</span><span class="sxs-lookup"><span data-stu-id="8bab0-453">Subscription Description</span></span></td>
<td><p><span data-ttu-id="8bab0-454">訂用帳戶的易記名稱。</span><span class="sxs-lookup"><span data-stu-id="8bab0-454">Friendly name of a subscription.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="8bab0-455">訂閱識別碼</span><span class="sxs-lookup"><span data-stu-id="8bab0-455">Subscription ID</span></span></td>
<td><p><span data-ttu-id="8bab0-456">Microsoft 商務平台的訂用帳戶的唯一識別碼。</span><span class="sxs-lookup"><span data-stu-id="8bab0-456">Unique identifier for a subscription in the Microsoft commerce platform.</span></span> <span data-ttu-id="8bab0-457">可在連絡支援時方便識別訂閱，但不是用於對帳。</span><span class="sxs-lookup"><span data-stu-id="8bab0-457">May be useful to identify the subscription when contacting support but not for reconciliation.</span></span> <span data-ttu-id="8bab0-458">這與合作夥伴管理主控台上的訂閱識別碼不一樣。</span><span class="sxs-lookup"><span data-stu-id="8bab0-458">This is not the same as the Subscription ID on the Partner Admin Console.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="8bab0-459">ChargeStartDate</span><span class="sxs-lookup"><span data-stu-id="8bab0-459">ChargeStartDate</span></span></td>
<td><p><span data-ttu-id="8bab0-460">開始計算費用的日期。</span><span class="sxs-lookup"><span data-stu-id="8bab0-460">Start day of the charges.</span></span> <span data-ttu-id="8bab0-461">時間一律是一天的開始時間 (0:00)。</span><span class="sxs-lookup"><span data-stu-id="8bab0-461">The time is always the beginning of the day, 0:00.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="8bab0-462">ChargeEndDate</span><span class="sxs-lookup"><span data-stu-id="8bab0-462">ChargeEndDate</span></span></td>
<td><p><span data-ttu-id="8bab0-463">結束計算費用的日期。</span><span class="sxs-lookup"><span data-stu-id="8bab0-463">End day of the charges.</span></span> <span data-ttu-id="8bab0-464">時間一律是一天的結束時間 (23:59)。</span><span class="sxs-lookup"><span data-stu-id="8bab0-464">The time is always the end of the day, 23:59.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="8bab0-465">詞彙和 Billingcycle</span><span class="sxs-lookup"><span data-stu-id="8bab0-465">Term and Billingcycle</span></span></td>
<td><p><span data-ttu-id="8bab0-466">約定期和購買計費週期。</span><span class="sxs-lookup"><span data-stu-id="8bab0-466">The term length and billing cycle for the purchase.</span></span> <span data-ttu-id="8bab0-467">比方說，「 1 年，每個月。 」</span><span class="sxs-lookup"><span data-stu-id="8bab0-467">For example, “1 Year, Monthly.”</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="8bab0-468">收費類型</span><span class="sxs-lookup"><span data-stu-id="8bab0-468">Charge Type</span></span></td>
<td><p><span data-ttu-id="8bab0-469">費用或調整的類型。</span><span class="sxs-lookup"><span data-stu-id="8bab0-469">The type of charge or adjustment.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="8bab0-470">單價</span><span class="sxs-lookup"><span data-stu-id="8bab0-470">Unit Price</span></span></td>
<td><p><span data-ttu-id="8bab0-471">價格為 pricelist 中發行當時的購買。</span><span class="sxs-lookup"><span data-stu-id="8bab0-471">The price as published in the pricelist at the time of purchase.</span></span> <span data-ttu-id="8bab0-472">請確定這與對帳期間儲存在您帳單系統中的資訊相符。</span><span class="sxs-lookup"><span data-stu-id="8bab0-472">Ensure this matches the information stored in your billing system during reconciliation.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="8bab0-473">有效的單位價格</span><span class="sxs-lookup"><span data-stu-id="8bab0-473">Effective Unit Price</span></span></td>
<td><p><span data-ttu-id="8bab0-474">單價後調整。</span><span class="sxs-lookup"><span data-stu-id="8bab0-474">The unit price after adjustments have been made.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="8bab0-475">數量</span><span class="sxs-lookup"><span data-stu-id="8bab0-475">Quantity</span></span></td>
<td><p><span data-ttu-id="8bab0-476">單位數。</span><span class="sxs-lookup"><span data-stu-id="8bab0-476">Number of units.</span></span> <span data-ttu-id="8bab0-477">請確定這與對帳期間儲存在您帳單系統中的資訊相符。</span><span class="sxs-lookup"><span data-stu-id="8bab0-477">Ensure this matches the information stored in your billing system during reconciliation.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="8bab0-478">單位類型</span><span class="sxs-lookup"><span data-stu-id="8bab0-478">Unit type</span></span></td>
<td><p><span data-ttu-id="8bab0-479">正在購買的單位類型。</span><span class="sxs-lookup"><span data-stu-id="8bab0-479">The type of unit being purchased.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="8bab0-480">DiscountDetails</span><span class="sxs-lookup"><span data-stu-id="8bab0-480">DiscountDetails</span></span></td>
<td><p><span data-ttu-id="8bab0-481">說明的任何適用的折扣。</span><span class="sxs-lookup"><span data-stu-id="8bab0-481">An explanation of any applicable discount.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="8bab0-482">Sub Total</span><span class="sxs-lookup"><span data-stu-id="8bab0-482">Sub Total</span></span></td>
<td><p><span data-ttu-id="8bab0-483">稅前總計。</span><span class="sxs-lookup"><span data-stu-id="8bab0-483">Total before tax.</span></span> <span data-ttu-id="8bab0-484">如果有折扣，可檢查小計是否和預期的總金額相符。</span><span class="sxs-lookup"><span data-stu-id="8bab0-484">Checks that your subtotal matches your expected total, in case of a discount.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="8bab0-485">稅額總計</span><span class="sxs-lookup"><span data-stu-id="8bab0-485">Tax Total</span></span></td>
<td><p><span data-ttu-id="8bab0-486">稅金費用 (根據您所在市場的稅金規則與特定情況)。</span><span class="sxs-lookup"><span data-stu-id="8bab0-486">Tax amount charge, based on your market's tax rules and specific circumstances.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="8bab0-487">總計</span><span class="sxs-lookup"><span data-stu-id="8bab0-487">Total</span></span></td>
<td><p><span data-ttu-id="8bab0-488">稅後總計。</span><span class="sxs-lookup"><span data-stu-id="8bab0-488">Total after tax.</span></span> <span data-ttu-id="8bab0-489">檢查發票中是否向您收取稅金。</span><span class="sxs-lookup"><span data-stu-id="8bab0-489">Checks if you are charged tax in the invoice.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="8bab0-490">貨幣</span><span class="sxs-lookup"><span data-stu-id="8bab0-490">Currency</span></span></td>
<td><p><span data-ttu-id="8bab0-491">貨幣類型。</span><span class="sxs-lookup"><span data-stu-id="8bab0-491">Currency type.</span></span> <span data-ttu-id="8bab0-492">每一帳單實體都只有一種貨幣。</span><span class="sxs-lookup"><span data-stu-id="8bab0-492">Each billing entity has only one currency.</span></span> <span data-ttu-id="8bab0-493">檢查是否與您的第一張發票相符，然後在進行任何重大帳單平台更新之後檢查。</span><span class="sxs-lookup"><span data-stu-id="8bab0-493">Check that it matches your first invoice and then after any major billing platform update.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="8bab0-494">AlternateID</span><span class="sxs-lookup"><span data-stu-id="8bab0-494">AlternateID</span></span></td>
<td><p><span data-ttu-id="8bab0-495">替代識別碼至單識別碼。</span><span class="sxs-lookup"><span data-stu-id="8bab0-495">An alternate identifier to an order ID.</span></span></p></td>
</tr>
</tbody>
</table>


## <a href="" id="dailyratedusagefields"></a><span data-ttu-id="8bab0-496">每日按比例計算的使用方式檔案欄位</span><span class="sxs-lookup"><span data-stu-id="8bab0-496">Daily-rated usage file fields</span></span>


<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th><span data-ttu-id="8bab0-497">Column</span><span class="sxs-lookup"><span data-stu-id="8bab0-497">Column</span></span></th>
<th><span data-ttu-id="8bab0-498">描述</span><span class="sxs-lookup"><span data-stu-id="8bab0-498">Description</span></span></th>
</tr>
</thead>
<tbody>

<tr class="odd">
<td><span data-ttu-id="8bab0-499">PartnerId</span><span class="sxs-lookup"><span data-stu-id="8bab0-499">PartnerId</span></span></td>
<td><p><span data-ttu-id="8bab0-500">合作夥伴識別碼 (GUID 格式)。</span><span class="sxs-lookup"><span data-stu-id="8bab0-500">Partner ID, in GUID format.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="8bab0-501">PartnerName</span><span class="sxs-lookup"><span data-stu-id="8bab0-501">PartnerName</span></span></td>
<td><p><span data-ttu-id="8bab0-502">合作夥伴名稱。</span><span class="sxs-lookup"><span data-stu-id="8bab0-502">Partner Name.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="8bab0-503">CustomerId</span><span class="sxs-lookup"><span data-stu-id="8bab0-503">CustomerId</span></span></td>
<td><p><span data-ttu-id="8bab0-504">用來識別客戶的唯一 Microsoft ID（GUID 格式）。</span><span class="sxs-lookup"><span data-stu-id="8bab0-504">Unique Microsoft ID, in GUID format, used to identify the customer.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="8bab0-505">CustomerCompanyName</span><span class="sxs-lookup"><span data-stu-id="8bab0-505">CustomerCompanyName</span></span></td>
<td><p><span data-ttu-id="8bab0-506">合作夥伴中心中回報的客戶組織名稱。</span><span class="sxs-lookup"><span data-stu-id="8bab0-506">Customer's organization name as reported in Partner Center.</span></span> <span data-ttu-id="8bab0-507">這在使用您的系統資訊對帳發票時非常重要。</span><span class="sxs-lookup"><span data-stu-id="8bab0-507">This is very important for reconciling the invoice with your system information.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="8bab0-508">CustomerDomainName</span><span class="sxs-lookup"><span data-stu-id="8bab0-508">CustomerDomainName</span></span></td>
<td><p><span data-ttu-id="8bab0-509">客戶的網域名稱。</span><span class="sxs-lookup"><span data-stu-id="8bab0-509">The customer’s domain name.</span></span> <span data-ttu-id="8bab0-510">不適用於目前的活動。</span><span class="sxs-lookup"><span data-stu-id="8bab0-510">Not available for current activity.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="8bab0-511">客戶的國家/地區</span><span class="sxs-lookup"><span data-stu-id="8bab0-511">Customer country</span></span></td>
<td><p><span data-ttu-id="8bab0-512">客戶所在的國家/地區。</span><span class="sxs-lookup"><span data-stu-id="8bab0-512">The country in which the customer is located.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="8bab0-513">MPNID</span><span class="sxs-lookup"><span data-stu-id="8bab0-513">MPNID</span></span></td>
<td><p><span data-ttu-id="8bab0-514">雲端解決方案提供者合作夥伴的 MPN 識別碼。</span><span class="sxs-lookup"><span data-stu-id="8bab0-514">MPN ID of the CSP partner.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="8bab0-515">轉銷商 MPNID</span><span class="sxs-lookup"><span data-stu-id="8bab0-515">Reseller MPNID</span></span></td>
<td><p><span data-ttu-id="8bab0-516">訂閱記錄中的經銷商 MPN 識別碼。</span><span class="sxs-lookup"><span data-stu-id="8bab0-516">MPN ID of the reseller of record for the subscription.</span></span> <span data-ttu-id="8bab0-517">不適用於目前的活動。</span><span class="sxs-lookup"><span data-stu-id="8bab0-517">Not available for current activity.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="8bab0-518">InvoiceNumber</span><span class="sxs-lookup"><span data-stu-id="8bab0-518">InvoiceNumber</span></span></td>
<td><p><span data-ttu-id="8bab0-519">交易的指定位置顯示的發票號碼。</span><span class="sxs-lookup"><span data-stu-id="8bab0-519">Invoice number where the specified transaction appears.</span></span> <span data-ttu-id="8bab0-520">不適用於目前的活動。</span><span class="sxs-lookup"><span data-stu-id="8bab0-520">Not available for current activity.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="8bab0-521">ProductId</span><span class="sxs-lookup"><span data-stu-id="8bab0-521">ProductId</span></span></td>
<td><p><span data-ttu-id="8bab0-522">產品的識別碼。</span><span class="sxs-lookup"><span data-stu-id="8bab0-522">The ID for the product.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="8bab0-523">SkuId</span><span class="sxs-lookup"><span data-stu-id="8bab0-523">SkuId</span></span></td>
<td><p><span data-ttu-id="8bab0-524">特定 SKU 的識別碼。</span><span class="sxs-lookup"><span data-stu-id="8bab0-524">The ID for a particular SKU.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="8bab0-525">AvailabilityId</span><span class="sxs-lookup"><span data-stu-id="8bab0-525">AvailabilityId</span></span></td>
<td><p><span data-ttu-id="8bab0-526">特定可用性的識別碼。</span><span class="sxs-lookup"><span data-stu-id="8bab0-526">The ID for a particular Availability.</span></span> <span data-ttu-id="8bab0-527">「可用性」是指特定 SKU 是否可供特定的國家/地區、貨幣、行業區段等等購買。</span><span class="sxs-lookup"><span data-stu-id="8bab0-527">“Availability” refers to whether or not a particular SKU is available for purchase for the given country, currency, industry segment, etc.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="8bab0-528">SKU 名稱</span><span class="sxs-lookup"><span data-stu-id="8bab0-528">SKU Name</span></span></td>
<td><p><span data-ttu-id="8bab0-529">特定 SKU 的標題。</span><span class="sxs-lookup"><span data-stu-id="8bab0-529">The title for a particular SKU.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="8bab0-530">PublisherName</span><span class="sxs-lookup"><span data-stu-id="8bab0-530">PublisherName</span></span></td>
<td><p><span data-ttu-id="8bab0-531">發行者的名稱。</span><span class="sxs-lookup"><span data-stu-id="8bab0-531">The name of the publisher.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="8bab0-532">PublisherID</span><span class="sxs-lookup"><span data-stu-id="8bab0-532">PublisherID</span></span></td>
<td><p><span data-ttu-id="8bab0-533">「 發行者 」 的 GUID 格式的識別碼。</span><span class="sxs-lookup"><span data-stu-id="8bab0-533">The ID of the publisher, in GUID format.</span></span> <span data-ttu-id="8bab0-534">不適用於目前的活動。</span><span class="sxs-lookup"><span data-stu-id="8bab0-534">Not available for current activity.</span></span></p></td>
</tr>

<tr class=”even">
<td><span data-ttu-id="8bab0-535">訂用帳戶描述</span><span class="sxs-lookup"><span data-stu-id="8bab0-535">Subscription Description</span></span></td>
<td><p><span data-ttu-id="8bab0-536">客戶購買的服務優惠名稱，如價目表中所定義。</span><span class="sxs-lookup"><span data-stu-id="8bab0-536">The name of the service offering purchased by the customer, as defined in the price list.</span></span> <span data-ttu-id="8bab0-537">（這是優惠名稱的相同欄位）。</span><span class="sxs-lookup"><span data-stu-id="8bab0-537">(This is an identical field to Offer name).</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="8bab0-538">訂閱識別碼</span><span class="sxs-lookup"><span data-stu-id="8bab0-538">Subscription ID</span></span></td>
<td><p><span data-ttu-id="8bab0-539">訂閱在 Microsoft 帳單平台中的唯一識別碼。</span><span class="sxs-lookup"><span data-stu-id="8bab0-539">Unique identifier for a subscription in the Microsoft billing platform.</span></span> <span data-ttu-id="8bab0-540">可在連絡支援時方便識別訂閱，但不是用於對帳。</span><span class="sxs-lookup"><span data-stu-id="8bab0-540">May be useful to identify the subscription when contacting support but not for reconciliation.</span></span> <span data-ttu-id="8bab0-541">這與合作夥伴管理主控台上的訂閱識別碼不一樣。</span><span class="sxs-lookup"><span data-stu-id="8bab0-541">This is not the same as the Subscription ID on the Partner Admin Console.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="8bab0-542">ChargeStartDate</span><span class="sxs-lookup"><span data-stu-id="8bab0-542">ChargeStartDate</span></span></td>
<td><p><span data-ttu-id="8bab0-543">計費週期的開始日期，當顯示之前未收取潛在使用量資料費用的日期時除外 (從前一個計費週期開始)。</span><span class="sxs-lookup"><span data-stu-id="8bab0-543">Start date of billing cycle except when presenting dates of previously uncharged latent usage data (from previous bill cycle).</span></span> <span data-ttu-id="8bab0-544">時間一律是一天的開始時間 (0:00)。</span><span class="sxs-lookup"><span data-stu-id="8bab0-544">The time is always the beginning of the day, 0:00.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="8bab0-545">ChargeEndDate</span><span class="sxs-lookup"><span data-stu-id="8bab0-545">ChargeEndDate</span></span></td>
<td><p><span data-ttu-id="8bab0-546">計費週期的結束日期，當顯示之前未收取潛在使用量資料費用的日期時除外 (從前一個計費週期開始)。</span><span class="sxs-lookup"><span data-stu-id="8bab0-546">End date of billing cycle except when presenting dates of previously uncharged latent usage data (from previous bill cycle).</span></span> <span data-ttu-id="8bab0-547">時間一律是一天的結束時間 (23:59)。</span><span class="sxs-lookup"><span data-stu-id="8bab0-547">The time is always the end of the day, 23:59.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="8bab0-548">使用日期</span><span class="sxs-lookup"><span data-stu-id="8bab0-548">Usage Date</span></span></td>
<td><p><span data-ttu-id="8bab0-549">服務使用量的日期。</span><span class="sxs-lookup"><span data-stu-id="8bab0-549">Date of service usage.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="8bab0-550">計量類型</span><span class="sxs-lookup"><span data-stu-id="8bab0-550">Meter Type</span></span></td>
<td><p><span data-ttu-id="8bab0-551">計量類型。</span><span class="sxs-lookup"><span data-stu-id="8bab0-551">The type of meter.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="8bab0-552">計量類別</span><span class="sxs-lookup"><span data-stu-id="8bab0-552">Meter Category</span></span></td>
<td><p><span data-ttu-id="8bab0-553">使用最上層服務。</span><span class="sxs-lookup"><span data-stu-id="8bab0-553">The top-level service for the usage.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="8bab0-554">計量識別碼</span><span class="sxs-lookup"><span data-stu-id="8bab0-554">Meter Id</span></span></td>
<td><p><span data-ttu-id="8bab0-555">使用計量的識別碼。</span><span class="sxs-lookup"><span data-stu-id="8bab0-555">The ID for the meter being used.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="8bab0-556">計量子類別</span><span class="sxs-lookup"><span data-stu-id="8bab0-556">Meter Sub-category</span></span></td>
<td><p><span data-ttu-id="8bab0-557">可能影響費率的 Azure 服務的型別。</span><span class="sxs-lookup"><span data-stu-id="8bab0-557">The type of Azure service that can affect the rate.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="8bab0-558">計量名稱</span><span class="sxs-lookup"><span data-stu-id="8bab0-558">Meter Name</span></span></td>
<td><p><span data-ttu-id="8bab0-559">耗用計量的量值單位。</span><span class="sxs-lookup"><span data-stu-id="8bab0-559">The unit of measure for the meter being consumed.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="8bab0-560">計量區域</span><span class="sxs-lookup"><span data-stu-id="8bab0-560">Meter Region</span></span></td>
<td><p><span data-ttu-id="8bab0-561">此欄可識別適用及填入此項目之服務地區內的資料中心的位置。</span><span class="sxs-lookup"><span data-stu-id="8bab0-561">This column identifies the location of a data center within the region for services where this is applicable and populated.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="8bab0-562">單位</span><span class="sxs-lookup"><span data-stu-id="8bab0-562">Unit</span></span></td>
<td><p><span data-ttu-id="8bab0-563">資源名稱的單位。</span><span class="sxs-lookup"><span data-stu-id="8bab0-563">The unit of the resource Name.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="8bab0-564">取用的數量</span><span class="sxs-lookup"><span data-stu-id="8bab0-564">Consumed Quantity</span></span></td>
<td><p><span data-ttu-id="8bab0-565">報表期間耗用的服務量 (小時、GB 等等)</span><span class="sxs-lookup"><span data-stu-id="8bab0-565">The amount of service consumed (hours, GB, etc.) during the reporting period.</span></span> <span data-ttu-id="8bab0-566">同時包括先前報表期間任何未計費的使用量。</span><span class="sxs-lookup"><span data-stu-id="8bab0-566">Also includes any unbilled usage from previous reporting periods.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="8bab0-567">資源位置</span><span class="sxs-lookup"><span data-stu-id="8bab0-567">Resource Location</span></span></td>
<td><p><span data-ttu-id="8bab0-568">正在執行計量資料中心。</span><span class="sxs-lookup"><span data-stu-id="8bab0-568">The datacenter where the meter is running.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="8bab0-569">已使用的服務</span><span class="sxs-lookup"><span data-stu-id="8bab0-569">Consumed Service</span></span></td>
<td><p><span data-ttu-id="8bab0-570">您所使用的 Azure 平台服務。</span><span class="sxs-lookup"><span data-stu-id="8bab0-570">The Azure platform service that you used.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="8bab0-571">資源群組</span><span class="sxs-lookup"><span data-stu-id="8bab0-571">Resource Group</span></span></td>
<td><p><span data-ttu-id="8bab0-572">已部署的計量執行所在的資源群組。</span><span class="sxs-lookup"><span data-stu-id="8bab0-572">The resource group in which the deployed meter is running.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="8bab0-573">資源 URI</span><span class="sxs-lookup"><span data-stu-id="8bab0-573">Resource URI</span></span></td>
<td><p><span data-ttu-id="8bab0-574">正在使用的資源 URI。</span><span class="sxs-lookup"><span data-stu-id="8bab0-574">The URI of the resource being used.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="8bab0-575">收費類型</span><span class="sxs-lookup"><span data-stu-id="8bab0-575">Charge type</span></span></td>
<td><p><span data-ttu-id="8bab0-576">費用或調整的類型。</span><span class="sxs-lookup"><span data-stu-id="8bab0-576">The type of charge or adjustment.</span></span> <span data-ttu-id="8bab0-577">不適用於目前的活動。</span><span class="sxs-lookup"><span data-stu-id="8bab0-577">Not available for current activity.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="8bab0-578">單價</span><span class="sxs-lookup"><span data-stu-id="8bab0-578">Unit price</span></span></td>
<td><p><span data-ttu-id="8bab0-579">每份授權為 pricelist 中發行當時的購買價格。</span><span class="sxs-lookup"><span data-stu-id="8bab0-579">Price per license, as published in the pricelist at the time of purchase.</span></span> <span data-ttu-id="8bab0-580">請確定這與對帳期間儲存在您帳單系統中的資訊相符。</span><span class="sxs-lookup"><span data-stu-id="8bab0-580">Ensure this matches the information stored in your billing system during reconciliation.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="8bab0-581">數量</span><span class="sxs-lookup"><span data-stu-id="8bab0-581">Quantity</span></span></td>
<td><p><span data-ttu-id="8bab0-582">授權的數目。</span><span class="sxs-lookup"><span data-stu-id="8bab0-582">Number of licenses.</span></span> <span data-ttu-id="8bab0-583">請確定這與對帳期間儲存在您帳單系統中的資訊相符。</span><span class="sxs-lookup"><span data-stu-id="8bab0-583">Ensure this matches the information stored in your billing system during reconciliation.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="8bab0-584">單位類型</span><span class="sxs-lookup"><span data-stu-id="8bab0-584">Unit type</span></span></td>
<td><p><span data-ttu-id="8bab0-585">計量的計費的單位的類型。</span><span class="sxs-lookup"><span data-stu-id="8bab0-585">The type of unit the meter is charged in.</span></span> <span data-ttu-id="8bab0-586">不適用於目前的活動。</span><span class="sxs-lookup"><span data-stu-id="8bab0-586">Not available for current activity.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="8bab0-587">計費前稅額</span><span class="sxs-lookup"><span data-stu-id="8bab0-587">Billing pre tax</span></span></td>
<td><p><span data-ttu-id="8bab0-588">稅前的總金額。</span><span class="sxs-lookup"><span data-stu-id="8bab0-588">Total amount before taxes.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="8bab0-589">帳單貨幣</span><span class="sxs-lookup"><span data-stu-id="8bab0-589">Billing currency</span></span></td>
<td><p><span data-ttu-id="8bab0-590">客戶的地理區域中的貨幣</span><span class="sxs-lookup"><span data-stu-id="8bab0-590">The currency in the customer’s geographic region</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="8bab0-591">定價 pretax 總計</span><span class="sxs-lookup"><span data-stu-id="8bab0-591">Pricing pretax total</span></span></td>
<td><p><span data-ttu-id="8bab0-592">定價加入稅金之前。</span><span class="sxs-lookup"><span data-stu-id="8bab0-592">The pricing before taxes are added.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="8bab0-593">價格貨幣</span><span class="sxs-lookup"><span data-stu-id="8bab0-593">Pricing currency</span></span></td>
<td><p><span data-ttu-id="8bab0-594">在 pricelist 貨幣。</span><span class="sxs-lookup"><span data-stu-id="8bab0-594">The currency in the pricelist.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="8bab0-595">服務資訊 1</span><span class="sxs-lookup"><span data-stu-id="8bab0-595">Service Info 1</span></span></td>
<td><p><span data-ttu-id="8bab0-596">於某一天佈建及使用的 ServiceBus 連線數目。</span><span class="sxs-lookup"><span data-stu-id="8bab0-596">The number of ServiceBus connections that were provisioned and utilized on a given day.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="8bab0-597">服務資訊 2</span><span class="sxs-lookup"><span data-stu-id="8bab0-597">Service Info 2</span></span></td>
<td><p><span data-ttu-id="8bab0-598">舊版欄位，可擷取選擇性服務特定中繼資料。</span><span class="sxs-lookup"><span data-stu-id="8bab0-598">A legacy field that captures optional service-specific metadata.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="8bab0-599">Tags</span><span class="sxs-lookup"><span data-stu-id="8bab0-599">Tags</span></span></td>
<td><p><span data-ttu-id="8bab0-600">您指派給以順序為帳單記錄分組計量的標籤。</span><span class="sxs-lookup"><span data-stu-id="8bab0-600">Tags you assign to the meter in order to group billing records.</span></span> <span data-ttu-id="8bab0-601">例如，您可以使用標記根據使用計量的部門散發成本。</span><span class="sxs-lookup"><span data-stu-id="8bab0-601">For example, you can use tags to distribute costs by the department that uses the meter.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="8bab0-602">其他資訊</span><span class="sxs-lookup"><span data-stu-id="8bab0-602">Additional Info</span></span></td>
<td><p><span data-ttu-id="8bab0-603">未涵蓋在其他資料行中的任何其他資訊。</span><span class="sxs-lookup"><span data-stu-id="8bab0-603">Any additional information not covered in other columns.</span></span></p></td>
</tr>

</tbody>
</table>


## <a href="" id="charge_types"></a><span data-ttu-id="8bab0-604">發票和對帳檔案之間的對應費用</span><span class="sxs-lookup"><span data-stu-id="8bab0-604">Mapping charges between an invoice and the reconciliation file</span></span>

<span data-ttu-id="8bab0-605">您的發票提供費用摘要，而對帳檔案則提供包括費用類型等明細項目交易的詳細細項。</span><span class="sxs-lookup"><span data-stu-id="8bab0-605">Your invoice provides a summary of charges, while your reconciliation file provides a detailed breakdown of line-item transactions, including charge types.</span></span>

<span data-ttu-id="8bab0-606">若要交互參照發票和對帳檔案之間的費用金額，您可以使用 Microsoft Excel 篩選選項，在對帳檔案上依費用類型篩選，以便將發票費用對應到對帳檔案上的一組費用細項。</span><span class="sxs-lookup"><span data-stu-id="8bab0-606">To cross-reference charge amounts between the invoice and reconciliation file, you can use Microsoft Excel's filter options to filter by charge types on the reconciliation file to map the invoice charges to a set of charge breakdowns on reconciliation file.</span></span>

<span data-ttu-id="8bab0-607">用量型和授權型訂閱的對帳檔案只會顯示交易和費用的相關使用量 (耗用單位和相關的費用)。</span><span class="sxs-lookup"><span data-stu-id="8bab0-607">Reconciliation files, both usage- and license-based, only show usage related transactions and charges (units consumed and related charges).</span></span> <span data-ttu-id="8bab0-608">發票上顯示為「調整」的點數、折扣或退款不會出現在對帳檔案中。</span><span class="sxs-lookup"><span data-stu-id="8bab0-608">One off credits, discounts or refunds which appear on the invoice as “Adjustments” are not shown in the reconciliation file.</span></span>

<span data-ttu-id="8bab0-609">下表顯示發票區段和對帳檔案上可能會顯示之相關費用類型之間的對應。</span><span class="sxs-lookup"><span data-stu-id="8bab0-609">The table below shows the mappings between an invoice section and associated charge types that might show up on the reconciliation files.</span></span> 

<table>
<tbody>
<tr>
<td>
<p><strong><span data-ttu-id="8bab0-610">發票費用描述</span><span class="sxs-lookup"><span data-stu-id="8bab0-610">Invoice charge description</span></span></strong></p>
</td>
<td>
<p><strong><span data-ttu-id="8bab0-611">對帳檔案費用描述（ChargeType 欄）</span><span class="sxs-lookup"><span data-stu-id="8bab0-611">Reconciliation file charge description (ChargeType column)</span></span></strong></p>
</td>
<td>
<p><strong><span data-ttu-id="8bab0-612">這項費用是什麼？</span><span class="sxs-lookup"><span data-stu-id="8bab0-612">What is this charge?</span></span></strong></p>
</td>
<td>
<p><strong><span data-ttu-id="8bab0-613">如何將這些 ChargeTypes 對應到發票？</span><span class="sxs-lookup"><span data-stu-id="8bab0-613">How do I map these ChargeTypes to the invoice?</span></span></strong></p>
</td>
</tr>
<tr>
<td rowspan="10">
<p><strong><span data-ttu-id="8bab0-614">授權型費用</span><span class="sxs-lookup"><span data-stu-id="8bab0-614">License-based charges</span></span></strong></p>
</td>
<td>
<p><span data-ttu-id="8bab0-615">啟用費用</span><span class="sxs-lookup"><span data-stu-id="8bab0-615">Activation fee</span></span></p>
</td>
<td>
<p><span data-ttu-id="8bab0-616">當客戶購買後使用訂閱時，向客戶收取的金額</span><span class="sxs-lookup"><span data-stu-id="8bab0-616">The amount charged to the customer when they use the subscription after purchasing it</span></span></p>
</td>
<td rowspan="10">
<p><span data-ttu-id="8bab0-617">從授權型檔案，加總 <strong>Amount</strong> 欄</span><span class="sxs-lookup"><span data-stu-id="8bab0-617">From license-based file, sum the <strong>Amount</strong> column</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="8bab0-618">取消費用</span><span class="sxs-lookup"><span data-stu-id="8bab0-618">Cancel fee</span></span></p>
</td>
<td>
<p><span data-ttu-id="8bab0-619">當關聯的基座變更時，按比例計算退款給客戶的費用</span><span class="sxs-lookup"><span data-stu-id="8bab0-619">Prorated charges refunded to the customer when associated seats are changed</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="8bab0-620">循環費用</span><span class="sxs-lookup"><span data-stu-id="8bab0-620">Cycle fee</span></span></p>
</td>
<td>
<p><span data-ttu-id="8bab0-621">訂閱的定期費用</span><span class="sxs-lookup"><span data-stu-id="8bab0-621">Periodic charges for a subscription</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="8bab0-622">循環執行個體 (依比例計算)</span><span class="sxs-lookup"><span data-stu-id="8bab0-622">Cycle instance prorate</span></span></p>
</td>
<td>
<p><span data-ttu-id="8bab0-623">當關聯的基座變更時，按比例計算向客戶收取的費用</span><span class="sxs-lookup"><span data-stu-id="8bab0-623">Prorated charges assessed from the customer when associated seats are changed</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="8bab0-624">取消時按比例計算費用</span><span class="sxs-lookup"><span data-stu-id="8bab0-624">Prorate fees when cancel</span></span></p>
</td>
<td>
<p><span data-ttu-id="8bab0-625">取消時服務未使用部分之按比例計算的退款</span><span class="sxs-lookup"><span data-stu-id="8bab0-625">Prorated refund for unused portion of service upon cancellation</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="8bab0-626">購買時按比例計算費用</span><span class="sxs-lookup"><span data-stu-id="8bab0-626">Prorate fees when purchase</span></span></p>
</td>
<td>
<p><span data-ttu-id="8bab0-627">當使用年度計費訂用帳戶收費類型</span><span class="sxs-lookup"><span data-stu-id="8bab0-627">The charge type for a subscription when using annual billing</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="8bab0-628">購買費用</span><span class="sxs-lookup"><span data-stu-id="8bab0-628">Purchase fee</span></span></p>
</td>
<td>
<p><span data-ttu-id="8bab0-629">當使用每月計費訂用帳戶收費類型</span><span class="sxs-lookup"><span data-stu-id="8bab0-629">The charge type for a subscription when using monthly billing</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="8bab0-630">續約時按比例計算費用</span><span class="sxs-lookup"><span data-stu-id="8bab0-630">Prorate fee when renew</span></span></p>
</td>
<td>
<p><span data-ttu-id="8bab0-631">訂閱續約時按比例計算的費用</span><span class="sxs-lookup"><span data-stu-id="8bab0-631">Prorated fees upon subscription renewal</span></span></p>
</td>
</tr>
<tr>

<td>
<p><span data-ttu-id="8bab0-632">續約費用</span><span class="sxs-lookup"><span data-stu-id="8bab0-632">Renew fee</span></span></p>
</td>
<td>
<p><span data-ttu-id="8bab0-633">訂閱續約時的費用</span><span class="sxs-lookup"><span data-stu-id="8bab0-633">Charge for renewing a subscription</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="8bab0-634">啟用時按比例計算費用</span><span class="sxs-lookup"><span data-stu-id="8bab0-634">Prorate fees when activate</span></span></p>
</td>
<td>
<p><span data-ttu-id="8bab0-635">從啟用到計費期間結束時按比例計算的費用</span><span class="sxs-lookup"><span data-stu-id="8bab0-635">Prorated fees from activation until end of billing period</span></span></p>
</td>
</tr>
<tr>
<td rowspan="2">
<p><strong><span data-ttu-id="8bab0-636">使用量費用</span><span class="sxs-lookup"><span data-stu-id="8bab0-636">Usage Charges</span></span></strong></p>
</td>
<td>
<p><span data-ttu-id="8bab0-637">取消時的存取用量費用</span><span class="sxs-lookup"><span data-stu-id="8bab0-637">Assess usage fee when cancel</span></span></p>
</td>
<td>
<p><span data-ttu-id="8bab0-638">在目前計費期間中取消時，未支付之使用量的存取用量費用</span><span class="sxs-lookup"><span data-stu-id="8bab0-638">Access usage fee upon cancellation for unpaid usage during the current billing period</span></span></p>
</td>
<td rowspan="2">
<p><span data-ttu-id="8bab0-639">從用量型檔案，加總 <strong>PretaxCharges</strong> 欄</span><span class="sxs-lookup"><span data-stu-id="8bab0-639">From usage-based file, sum the <strong>PretaxCharges</strong> column</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="8bab0-640">目前週期的存取用量費用</span><span class="sxs-lookup"><span data-stu-id="8bab0-640">Assess usage fee for current cycle</span></span></p>
</td>
<td>
<p><span data-ttu-id="8bab0-641">目前計費期間的存取用量費用</span><span class="sxs-lookup"><span data-stu-id="8bab0-641">Access usage fee for the current billing period</span></span></p>
</td>
</tr>
<tr>
<td>
<p><strong><span data-ttu-id="8bab0-642">點數</span><span class="sxs-lookup"><span data-stu-id="8bab0-642">Credits</span></span></strong></p>
</td>
<td>
<p><span data-ttu-id="8bab0-643">明細項目位移</span><span class="sxs-lookup"><span data-stu-id="8bab0-643">Offset a line item</span></span></p>
</td>
<td>
<p><span data-ttu-id="8bab0-644">明細項目的部分或完整退款 (含稅)</span><span class="sxs-lookup"><span data-stu-id="8bab0-644">Partial or whole refund to a line item, including taxes</span></span></p>
</td>
<td>
<p><span data-ttu-id="8bab0-645">從授權型檔案，加總 <strong>TotalForCustomer</strong> 欄</span><span class="sxs-lookup"><span data-stu-id="8bab0-645">From license-based file, sum the <strong>TotalForCustomer</strong> column</span></span></p>
<p><span data-ttu-id="8bab0-646">從用量型檔案，加總 <strong>PostTaxTotal</strong> 欄</span><span class="sxs-lookup"><span data-stu-id="8bab0-646">From usage-based file, sum the <strong>PostTaxTotal</strong> column</span></span></p>
</td>
</tr>
<tr>
<td rowspan="4">
<p><strong><span data-ttu-id="8bab0-647">用量型折扣</span><span class="sxs-lookup"><span data-stu-id="8bab0-647">Usage-based discounts</span></span></strong></p>
</td>
<td>
<p><span data-ttu-id="8bab0-648">啟用折扣</span><span class="sxs-lookup"><span data-stu-id="8bab0-648">Activation discount</span></span></p>
</td>
<td>
<p><span data-ttu-id="8bab0-649">啟用訂閱時套用的折扣</span><span class="sxs-lookup"><span data-stu-id="8bab0-649">Discount applied when subscription activated</span></span></p>
</td>

<td rowspan="4">
<p><span data-ttu-id="8bab0-650">從用量型檔案，加總 <strong>PretaxCharges</strong> 欄</span><span class="sxs-lookup"><span data-stu-id="8bab0-650">From usage-based file, sum the <strong>PretaxCharges</strong> column</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="8bab0-651">循環折扣</span><span class="sxs-lookup"><span data-stu-id="8bab0-651">Cycle discount</span></span></p>
</td>
<td>
<p><span data-ttu-id="8bab0-652">套用至定期費用的折扣</span><span class="sxs-lookup"><span data-stu-id="8bab0-652">Discount applied on periodic charges</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="8bab0-653">續約折扣</span><span class="sxs-lookup"><span data-stu-id="8bab0-653">Renew discount</span></span></p>
</td>
<td>
<p><span data-ttu-id="8bab0-654">訂閱續約時套用的折扣</span><span class="sxs-lookup"><span data-stu-id="8bab0-654">Discount applied when subscription renewed</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="8bab0-655">取消折扣</span><span class="sxs-lookup"><span data-stu-id="8bab0-655">Cancel discount</span></span></p>
</td>
<td>
<p><span data-ttu-id="8bab0-656">折扣取消時收取的費用</span><span class="sxs-lookup"><span data-stu-id="8bab0-656">Charges applied when discounts cancelled</span></span></p>
</td>
</tr>


<tr>
<td>
<p><strong><span data-ttu-id="8bab0-657">授權型折扣</span><span class="sxs-lookup"><span data-stu-id="8bab0-657">License-based discounts</span></span></strong></p>
</td>
<td>
<p><em><span data-ttu-id="8bab0-658">可套用至多個費用類型</span><span class="sxs-lookup"><span data-stu-id="8bab0-658">May be applied to multiple charge types</span></span></em></p>
</td>
<td>
<p></p>
</td>
<td>
<p><span data-ttu-id="8bab0-659">從授權型檔案，加總 <strong>TotalOtherDiscount</strong> 欄</span><span class="sxs-lookup"><span data-stu-id="8bab0-659">From license-based file, sum the <strong>TotalOtherDiscount</strong> column</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="8bab0-660"><strong>稅金</strong>&nbsp;或&nbsp;<strong>加值稅</strong></span><span class="sxs-lookup"><span data-stu-id="8bab0-660"><strong>Taxes</strong>&nbsp;or&nbsp;<strong>VAT</strong></span></span></p>
</td>
<td>
<p><em><span data-ttu-id="8bab0-661">可套用至多個費用類型</span><span class="sxs-lookup"><span data-stu-id="8bab0-661">May be applied to multiple charge types</span></span></em></p>
<p><em><span data-ttu-id="8bab0-662">例外狀況：&quot;位移明細項目&quot;已經包含稅金。</span><span class="sxs-lookup"><span data-stu-id="8bab0-662">Exception: &quot;Offset a line item&quot; already includes taxes.</span></span> <span data-ttu-id="8bab0-663">請參閱上面的「點數」。</span><span class="sxs-lookup"><span data-stu-id="8bab0-663">See Credits, above.</span></span></em></p>
</td>
<td>
<p><span data-ttu-id="8bab0-664">稅金或加值稅 (VAT)</span><span class="sxs-lookup"><span data-stu-id="8bab0-664">Taxes or value-added taxes (VAT)</span></span></p>
</td>
<td>
<p><span data-ttu-id="8bab0-665">從授權型檔案，加總 <strong>Tax</strong> 欄</span><span class="sxs-lookup"><span data-stu-id="8bab0-665">From license-based file, sum the <strong>Tax</strong> column</span></span></p>
<p><span data-ttu-id="8bab0-666">從用量型檔案，加總 <strong>TaxAmount</strong> 欄</span><span class="sxs-lookup"><span data-stu-id="8bab0-666">From usage-based file, sum the <strong>TaxAmount</strong> column</span></span></p>
</td>
</tr>
</tbody>
</table>
<p>&nbsp;</p>
