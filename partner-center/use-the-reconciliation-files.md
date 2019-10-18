---
title: 使用對帳檔案 | 合作夥伴中心
ms.topic: article
ms.date: 07/08/2019
description: 如需計費週期中每個費用的詳細明細專案查看，請從合作夥伴中心下載對帳檔案。
ms.assetid: FA6A6FCB-2597-44E7-93F8-8D1DD35D52EA
author: LauraBrenner
ms.author: labrenne
ms.localizationpriority: medium
ms.openlocfilehash: cbc982fa5bf6848cb77a2de2dcdaa7660c422888
ms.sourcegitcommit: 30f946b3c5c2c30a5ee3276037385ea97e644781
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 10/03/2019
ms.locfileid: "71931572"
---
# <a name="use-the-reconciliation-files"></a><span data-ttu-id="6635a-103">使用對帳檔案</span><span class="sxs-lookup"><span data-stu-id="6635a-103">Use the reconciliation files</span></span>

<span data-ttu-id="6635a-104">**適用於**</span><span class="sxs-lookup"><span data-stu-id="6635a-104">**Applies to**</span></span>

-  <span data-ttu-id="6635a-105">合作夥伴中心</span><span class="sxs-lookup"><span data-stu-id="6635a-105">Partner Center</span></span>
-  <span data-ttu-id="6635a-106">Microsoft Cloud for US Government 適用的合作夥伴中心</span><span class="sxs-lookup"><span data-stu-id="6635a-106">Partner Center for Microsoft Cloud for US Government</span></span>


<span data-ttu-id="6635a-107">如需計費週期中每個費用的詳細明細專案查看，請從合作夥伴中心下載對帳檔案。</span><span class="sxs-lookup"><span data-stu-id="6635a-107">For a detailed line-item view of each charge in a billing cycle, download the reconciliation files from Partner Center.</span></span> <span data-ttu-id="6635a-108">詳細資料包括每個客戶的訂閱費用，以及詳細事件 (例如，期中增加訂閱基座)。</span><span class="sxs-lookup"><span data-stu-id="6635a-108">The details include charges for each customer's subscriptions, and detailed events (such as a mid-term addition of seats to a subscription).</span></span>

## <a name="formatting-issues"></a><span data-ttu-id="6635a-109">格式化問題</span><span class="sxs-lookup"><span data-stu-id="6635a-109">Formatting issues</span></span>

<span data-ttu-id="6635a-110">有時候，您的偵察檔案可能會有格式問題。</span><span class="sxs-lookup"><span data-stu-id="6635a-110">Occasionally your recon file might have formatting issues.</span></span> <span data-ttu-id="6635a-111">（例如，如果未使用 EN-US 地區設定，就會發生這種情況）。請遵循下列步驟來修正這些問題。</span><span class="sxs-lookup"><span data-stu-id="6635a-111">(This can happen, for example, if the EN-US locale is not used.) Follow the steps below to fix these issues.</span></span> 

<ol>
<li><span data-ttu-id="6635a-112">在 Excel 中開啟 .csv 檔案，然後選取第一個資料行。</span><span class="sxs-lookup"><span data-stu-id="6635a-112">Open the .csv file in Excel, and select the first column.</span></span> <span data-ttu-id="6635a-113">在功能區上，選取 [<strong>資料</strong>]，然後選取 [<strong>文字到資料行</strong>]。</span><span class="sxs-lookup"><span data-stu-id="6635a-113">On the ribbon, select <strong>Data</strong>, and then select <strong>Text to Columns</strong>.</span></span></li>

<li><span data-ttu-id="6635a-114">在 [將文字轉換成資料行] Wizard 中，選取 [<strong>分隔檔案類型</strong>]，然後選取<strong>[下一步]</strong>。</span><span class="sxs-lookup"><span data-stu-id="6635a-114">In the Convert Text to Columns Wizard, select <strong>Delimited file type</strong>, and then select <strong>Next</strong>.</span></span></li> 

<li><span data-ttu-id="6635a-115">在 [Delimeters] 欄位中，選取 [<strong>逗號</strong>]。</span><span class="sxs-lookup"><span data-stu-id="6635a-115">In the Delimeters field, select <strong>Comma</strong>.</span></span> <span data-ttu-id="6635a-116">如果已選取 [ <strong>]</strong>索引標籤，您可以將它保留。</span><span class="sxs-lookup"><span data-stu-id="6635a-116">If <strong>Tab</strong> is already selected, you can leave it.</span></span> <span data-ttu-id="6635a-117">選取 <strong>\[下一步\]</strong>。</span><span class="sxs-lookup"><span data-stu-id="6635a-117">Select <strong>Next</strong>.</span></span></li>

<li><span data-ttu-id="6635a-118">在 [資料行資料格式] 欄位中，選取 [<strong>日期： MDY</strong>]，然後選取<strong>[下一步]</strong>。</span><span class="sxs-lookup"><span data-stu-id="6635a-118">In the Column data format field, select <strong>Date: MDY</strong>, and then select <strong>Next</strong>.</span></span></li> 

<li><span data-ttu-id="6635a-119">在 [資料行資料格式] 欄位中，針對 [所有數量] 資料行選取 [<strong>文字</strong>]，然後選取<strong>[完成]</strong>。</span><span class="sxs-lookup"><span data-stu-id="6635a-119">In the Column data format field, select <strong>Text</strong> for all amount columns, and then select <strong>Finish</strong>.</span></span></li>
</ol>

## <a name="downloading-a-large-recon-file"></a><span data-ttu-id="6635a-120">下載大型偵察檔案</span><span class="sxs-lookup"><span data-stu-id="6635a-120">Downloading a large recon file</span></span>

<span data-ttu-id="6635a-121">偵察檔案可能會變得非常大，有時很難以下載。</span><span class="sxs-lookup"><span data-stu-id="6635a-121">Recon files can grow very large and are sometimes difficult to download.</span></span> <span data-ttu-id="6635a-122">如需可協助下載大型偵察檔案的 PowerShell 腳本，請參閱[取得發票明細專案](https://docs.microsoft.com/partner-center/develop/get-invoiceline-items)。</span><span class="sxs-lookup"><span data-stu-id="6635a-122">For a PowerShell script to help download large recon files, see [Get invoice line items](https://docs.microsoft.com/partner-center/develop/get-invoiceline-items).</span></span>

## <a href="" id="itemizebypartner"></a><span data-ttu-id="6635a-123">依合作夥伴的列舉</span><span class="sxs-lookup"><span data-stu-id="6635a-123">Itemize by partner</span></span>


<span data-ttu-id="6635a-124">間接模型合作夥伴可以在授權型及用量型對帳檔案中使用這些額外欄位，以便依經銷商詳細列舉。</span><span class="sxs-lookup"><span data-stu-id="6635a-124">Partners in the indirect model can use these additional fields in both license-based and usage-based reconciliation files to itemize by reseller.</span></span>

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th><span data-ttu-id="6635a-125">MPN 識別碼</span><span class="sxs-lookup"><span data-stu-id="6635a-125">MPN ID</span></span></th>
<th><span data-ttu-id="6635a-126">說明</span><span class="sxs-lookup"><span data-stu-id="6635a-126">Description</span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="6635a-127">MPN 識別碼</span><span class="sxs-lookup"><span data-stu-id="6635a-127">MPN ID</span></span></td>
<td><p><span data-ttu-id="6635a-128">CSP 合作夥伴 (直接或間接) 的 Microsoft 合作夥伴網路 (MPN) 識別碼。</span><span class="sxs-lookup"><span data-stu-id="6635a-128">The Microsoft Partner Network (MPN) ID of the CSP partner (direct or indirect).</span></span></p></td>
</tr>
<tr class="even">
<td><span data-ttu-id="6635a-129">經銷商 MPN 識別碼</span><span class="sxs-lookup"><span data-stu-id="6635a-129">Reseller MPN ID</span></span></td>
<td><p><span data-ttu-id="6635a-130">只會出現在間接模型合作夥伴的對帳檔案上。</span><span class="sxs-lookup"><span data-stu-id="6635a-130">Only appears on reconciliation files for partners in the indirect model.</span></span></p>
<p><span data-ttu-id="6635a-131">訂閱記錄中的經銷商 MPN 識別碼。</span><span class="sxs-lookup"><span data-stu-id="6635a-131">The MPN ID of the reseller of record for the subscription.</span></span> <span data-ttu-id="6635a-132">這會對應到合作夥伴中心中針對特定訂閱列出的經銷商識別碼。</span><span class="sxs-lookup"><span data-stu-id="6635a-132">This corresponds to the reseller ID listed for the specific subscription in Partner Center.</span></span></p>
<p><span data-ttu-id="6635a-133">eTo 觀看或更新轉銷商，從 [合作夥伴中心] 功能表選取 [<strong>客戶</strong>]，然後從清單中選擇客戶。</span><span class="sxs-lookup"><span data-stu-id="6635a-133">eTo view or update the reseller, from the Partner Center menu, select <strong>Customers</strong>, then choose the customer from the list.</span></span> <span data-ttu-id="6635a-134">在客戶功能表中，選取 \[訂閱\]，從清單中選擇訂閱。</span><span class="sxs-lookup"><span data-stu-id="6635a-134">In the customer menu, select <strong>Subscriptions</strong>, choose the subscription from the list.</span></span> <span data-ttu-id="6635a-135">選取 \[更新\] 以變更 \[經銷商 (MPN 識別碼)\]。</span><span class="sxs-lookup"><span data-stu-id="6635a-135">Select <strong>update</strong> to change the <strong>Reseller (MPN ID)</strong>.</span></span></p>
<p><span data-ttu-id="6635a-136">如果雲端解決方案提供者合作夥伴直接向客戶銷售訂閱，他們的 MPN 識別碼將會以 MPN 識別碼和經銷商 MPN 識別碼的形式列出兩次。</span><span class="sxs-lookup"><span data-stu-id="6635a-136">If a CSP partner sold the subscription directly to the customer, their MPN ID is listed twice, as both the MPN ID and the Reseller MPN ID.</span></span></p>
<p><span data-ttu-id="6635a-137">如果雲端解決方案提供者合作夥伴具有沒有 MPN 識別碼的經銷商，這個值將會改成設為合作夥伴的 MPN 識別碼。</span><span class="sxs-lookup"><span data-stu-id="6635a-137">If a CSP partner has a reseller with no MPN ID, this value is set to the partner’s MPN ID instead.</span></span></p>
<p><span data-ttu-id="6635a-138">如果雲端解決方案提供者合作夥伴移除經銷商識別碼，這個值將會設為 -1。</span><span class="sxs-lookup"><span data-stu-id="6635a-138">If the CSP partner removes a reseller ID, this value will be set to -1.</span></span></p></td>
</tr>
</tbody>
</table>

 

## <a href="" id="licensebasedfiles"></a><span data-ttu-id="6635a-139">以授權為基礎的檔案欄位</span><span class="sxs-lookup"><span data-stu-id="6635a-139">License-based file fields</span></span>


<span data-ttu-id="6635a-140">若要針對您對客戶訂單的費用來對帳，請比較對帳檔案中的 Syndication\_Partner\_Subscription\_Number 與合作夥伴中心的訂閱識別碼。</span><span class="sxs-lookup"><span data-stu-id="6635a-140">To reconcile your charges against your customer's orders, compare the Syndication\_Partner\_Subscription\_Number from the reconciliation file against the Subscription ID from Partner Center.</span></span>

<table>
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<tbody>
<tr class="odd">
<td><span data-ttu-id="6635a-141"><strong>排</strong></span><span class="sxs-lookup"><span data-stu-id="6635a-141"><strong>Column</strong></span></span></td>
<td><span data-ttu-id="6635a-142"><strong>描述</strong></span><span class="sxs-lookup"><span data-stu-id="6635a-142"><strong>Description</strong></span></span></td>
<td><span data-ttu-id="6635a-143"><strong>範例值</strong></span><span class="sxs-lookup"><span data-stu-id="6635a-143"><strong>Sample Value</strong></span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="6635a-144">PartnerId</span><span class="sxs-lookup"><span data-stu-id="6635a-144">PartnerId</span></span></td>
<td><p><span data-ttu-id="6635a-145">特定帳單實體的唯一識別碼 (GUID 格式)。</span><span class="sxs-lookup"><span data-stu-id="6635a-145">Unique identifier for a specific billing entity, in GUID format.</span></span> <span data-ttu-id="6635a-146">對帳時不需要，但可能是很有用的資訊。</span><span class="sxs-lookup"><span data-stu-id="6635a-146">Not required for reconciliation, however may be useful information.</span></span> <span data-ttu-id="6635a-147">在所有資料列中都是如此。</span><span class="sxs-lookup"><span data-stu-id="6635a-147">Same in all rows.</span></span></p></td>
<td><span data-ttu-id="6635a-148">8ddd03642-test-test-test-46b58d356b4e</span><span class="sxs-lookup"><span data-stu-id="6635a-148">8ddd03642-test-test-test-46b58d356b4e</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="6635a-149">CustomerID</span><span class="sxs-lookup"><span data-stu-id="6635a-149">CustomerID</span></span></td>
<td><p><span data-ttu-id="6635a-150">用來識別客戶的唯一 Microsoft ID（GUID 格式）。</span><span class="sxs-lookup"><span data-stu-id="6635a-150">Unique Microsoft ID, in GUID format, used to identify the customer.</span></span></p></td>
<td><span data-ttu-id="6635a-151">12ABCD34-001A-BCD2-987C-3210ABCD5678</span><span class="sxs-lookup"><span data-stu-id="6635a-151">12ABCD34-001A-BCD2-987C-3210ABCD5678</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="6635a-152">OrderID</span><span class="sxs-lookup"><span data-stu-id="6635a-152">OrderID</span></span></td>
<td><p><span data-ttu-id="6635a-153">訂單在 Microsoft 帳單平台中的唯一識別碼。</span><span class="sxs-lookup"><span data-stu-id="6635a-153">Unique identifier for an order in the Microsoft billing platform.</span></span> <span data-ttu-id="6635a-154">可在連絡支援時方便識別訂單，但不是用於對帳。</span><span class="sxs-lookup"><span data-stu-id="6635a-154">May be useful to identify the order when contacting support but not for reconciliation.</span></span></p></td>
<td><span data-ttu-id="6635a-155">566890604832738111</span><span class="sxs-lookup"><span data-stu-id="6635a-155">566890604832738111</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="6635a-156">SubscriptionID</span><span class="sxs-lookup"><span data-stu-id="6635a-156">SubscriptionID</span></span></td>
<td><p><span data-ttu-id="6635a-157">訂閱在 Microsoft 帳單平台中的唯一識別碼。</span><span class="sxs-lookup"><span data-stu-id="6635a-157">Unique identifier for a subscription in the Microsoft billing platform.</span></span> <span data-ttu-id="6635a-158">可在連絡支援時方便識別訂閱，但不是用於對帳。</span><span class="sxs-lookup"><span data-stu-id="6635a-158">May be useful to identify the subscription when contacting support but not for reconciliation.</span></span></p>
<p><span data-ttu-id="6635a-159">這與合作夥伴管理主控台上的訂閱識別碼不一樣。</span><span class="sxs-lookup"><span data-stu-id="6635a-159">This is not the same as the Subscription ID on the Partner Admin Console.</span></span> <span data-ttu-id="6635a-160">請參閱 Syndication_Partner_Subscription_Number。</span><span class="sxs-lookup"><span data-stu-id="6635a-160">Please see Syndication_Partner_Subscription_Number.</span></span></p></td>
<td><span data-ttu-id="6635a-161">usCBMgAAAAAAAAIA</span><span class="sxs-lookup"><span data-stu-id="6635a-161">usCBMgAAAAAAAAIA</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="6635a-162">SyndicationPartnerSubscriptionNumber</span><span class="sxs-lookup"><span data-stu-id="6635a-162">SyndicationPartnerSubscriptionNumber</span></span></td>
<td><p><span data-ttu-id="6635a-163">訂閱的唯一識別碼。</span><span class="sxs-lookup"><span data-stu-id="6635a-163">Unique identifier for subscriptions.</span></span> <span data-ttu-id="6635a-164">客戶可針對同一方案擁有多項訂閱，因此這對於對帳檔案分析而言很重要。</span><span class="sxs-lookup"><span data-stu-id="6635a-164">A customer can have multiple subscriptions for the same plan, so this is important for reconciliation file analysis.</span></span></p>
<p><span data-ttu-id="6635a-165">這個欄位對應到合作夥伴管理主控台中的訂閱識別碼。</span><span class="sxs-lookup"><span data-stu-id="6635a-165">This field maps to the Subscription ID in the Partner Admin Console.</span></span></p></td>
<td><span data-ttu-id="6635a-166">fb977ab5-test-test-test-24c8d9591708</span><span class="sxs-lookup"><span data-stu-id="6635a-166">fb977ab5-test-test-test-24c8d9591708</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="6635a-167">OfferID</span><span class="sxs-lookup"><span data-stu-id="6635a-167">OfferID</span></span></td>
<td><p><span data-ttu-id="6635a-168">唯一的優惠識別碼。</span><span class="sxs-lookup"><span data-stu-id="6635a-168">Unique offer ID.</span></span> <span data-ttu-id="6635a-169">根據價目表的標準優惠識別碼。</span><span class="sxs-lookup"><span data-stu-id="6635a-169">Standard offer ID as per price list.</span></span></p>
<p><span data-ttu-id="6635a-170"><b>注意</b>：這個值不符合價目表上的優惠識別碼。</span><span class="sxs-lookup"><span data-stu-id="6635a-170"><b>Note</b>: This value does not match Offer ID from the price list.</span></span> <span data-ttu-id="6635a-171">請參閱下方的 DurableOfferID。</span><span class="sxs-lookup"><span data-stu-id="6635a-171">See DurableOfferID below.</span></span></p></td>
<td><span data-ttu-id="6635a-172">FE616D64-E9A8-40EF-843F-152E9BBEF3D1</span><span class="sxs-lookup"><span data-stu-id="6635a-172">FE616D64-E9A8-40EF-843F-152E9BBEF3D1</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="6635a-173">DurableOfferID</span><span class="sxs-lookup"><span data-stu-id="6635a-173">DurableOfferID</span></span></td>
<td><p><span data-ttu-id="6635a-174">唯一的持續性優惠識別碼，如價目表中所定義。</span><span class="sxs-lookup"><span data-stu-id="6635a-174">Unique durable offer ID, as defined in the price list.</span></span></p>
<p><span data-ttu-id="6635a-175"><b>注意</b>：這個值符合價目表上的優惠識別碼。</span><span class="sxs-lookup"><span data-stu-id="6635a-175"><b>Note</b>: This value matches the Offer ID from the price list.</span></span></p></td>
<td><span data-ttu-id="6635a-176">1017D7F3-6D7F-4BFA-BDD8-79BC8F104E0C</span><span class="sxs-lookup"><span data-stu-id="6635a-176">1017D7F3-6D7F-4BFA-BDD8-79BC8F104E0C</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="6635a-177">OfferName</span><span class="sxs-lookup"><span data-stu-id="6635a-177">OfferName</span></span></td>
<td><p><span data-ttu-id="6635a-178">客戶購買的服務優惠名稱，如價目表中所定義。</span><span class="sxs-lookup"><span data-stu-id="6635a-178">The name of the service offering purchased by the customer, as defined in the price list.</span></span></p></td>
<td><span data-ttu-id="6635a-179">Microsoft Office 365 (Plan E3)</span><span class="sxs-lookup"><span data-stu-id="6635a-179">Microsoft Office 365 (Plan E3)</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="6635a-180">SubscriptionStartDate</span><span class="sxs-lookup"><span data-stu-id="6635a-180">SubscriptionStartDate</span></span></td>
<td><p><span data-ttu-id="6635a-181">訂閱開始日期設定為送出訂單之後的隔日。</span><span class="sxs-lookup"><span data-stu-id="6635a-181">The subscription start date, set to the day after the order is submitted.</span></span> <span data-ttu-id="6635a-182">藉由同時查看訂閱開始日期與結束日期，您就可以判斷客戶是否仍在第一年訂閱期內，或下一年的訂閱已續約。</span><span class="sxs-lookup"><span data-stu-id="6635a-182">By looking at the subscription start date in conjunction with the end date, you can determine if the customer is still within the first year of the subscription or if the subscription has been renewed for the following year.</span></span></p>
<p><span data-ttu-id="6635a-183">時間一律是一天的開始時間 (0:00)。</span><span class="sxs-lookup"><span data-stu-id="6635a-183">The time is always the beginning of the day, 0:00.</span></span></p></td>
<td><span data-ttu-id="6635a-184">2/1/2015 0:00</span><span class="sxs-lookup"><span data-stu-id="6635a-184">2/1/2015 0:00</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="6635a-185">SubscriptionEndDate</span><span class="sxs-lookup"><span data-stu-id="6635a-185">SubscriptionEndDate</span></span></td>
<td><p><span data-ttu-id="6635a-186">訂閱結束日期：開始日期之後的 12 個月 + x 天 (與合作夥伴帳單日期配合) 或自續約日期起 12 個月。</span><span class="sxs-lookup"><span data-stu-id="6635a-186">The subscription end date: 12 months + x days after start date (to align with partner billing date) or 12 months from renewal date.</span></span></p>
<p><span data-ttu-id="6635a-187">續約時，價格會更新至目前的價目表。</span><span class="sxs-lookup"><span data-stu-id="6635a-187">At renewal, prices are updated to the current price list.</span></span> <span data-ttu-id="6635a-188">自動續約之前，可能需要與客戶連絡。</span><span class="sxs-lookup"><span data-stu-id="6635a-188">Customer communication may be required in advance of automated renewal.</span></span></p>
<p><span data-ttu-id="6635a-189">時間一律是一天的開始時間 (0:00)。</span><span class="sxs-lookup"><span data-stu-id="6635a-189">The time is always the beginning of the day, 0:00.</span></span></p></td>
<td><span data-ttu-id="6635a-190">2/1/2015 0:00</span><span class="sxs-lookup"><span data-stu-id="6635a-190">2/1/2015 0:00</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="6635a-191">ChargeStartDate</span><span class="sxs-lookup"><span data-stu-id="6635a-191">ChargeStartDate</span></span></td>
<td><p><span data-ttu-id="6635a-192">開始計算費用的日期。</span><span class="sxs-lookup"><span data-stu-id="6635a-192">Start day of the charges.</span></span></p>
<p><span data-ttu-id="6635a-193">當客戶變更基座數目時，此數字用於計算每日 (按比例) 的費用。</span><span class="sxs-lookup"><span data-stu-id="6635a-193">When a customer changes seat numbers, this number is used to calculate per-day (pro-rata) charges.</span></span></p>
<p><span data-ttu-id="6635a-194">時間一律是一天的開始時間 (0:00)。</span><span class="sxs-lookup"><span data-stu-id="6635a-194">The time is always the beginning of the day, 0:00.</span></span></p></td>
<td><span data-ttu-id="6635a-195">2/1/2015 0:00</span><span class="sxs-lookup"><span data-stu-id="6635a-195">2/1/2015 0:00</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="6635a-196">ChargeEndDate</span><span class="sxs-lookup"><span data-stu-id="6635a-196">ChargeEndDate</span></span></td>
<td><p><span data-ttu-id="6635a-197">結束計算費用的日期。</span><span class="sxs-lookup"><span data-stu-id="6635a-197">End day of the charges.</span></span></p>
<p><span data-ttu-id="6635a-198">當客戶變更基座數目時，此數字用於計算每日 (按比例) 的費用。</span><span class="sxs-lookup"><span data-stu-id="6635a-198">When a customer changes seat numbers, this number is used to calculate per-day (pro-rata) charges.</span></span></p>
<p><span data-ttu-id="6635a-199">時間一律是一天的結束時間 (23:59)。</span><span class="sxs-lookup"><span data-stu-id="6635a-199">The time is always the end of the day, 23:59.</span></span></p></td>
<td><span data-ttu-id="6635a-200">2/28/2015 23:59</span><span class="sxs-lookup"><span data-stu-id="6635a-200">2/28/2015 23:59</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="6635a-201">ChargeType</span><span class="sxs-lookup"><span data-stu-id="6635a-201">ChargeType</span></span></td>
<td><p><span data-ttu-id="6635a-202">費用或調整的類型。</span><span class="sxs-lookup"><span data-stu-id="6635a-202">The type of charge or adjustment.</span></span> <span data-ttu-id="6635a-203">請參閱<a href="#charge_types">對應發票和對帳檔案之間的費用</a></span><span class="sxs-lookup"><span data-stu-id="6635a-203">See <a href="#charge_types">Mapping charges between an invoice and the reconciliation file</a></span></span></p></td>
<td><p><span data-ttu-id="6635a-204">請參閱<a href="#charge_types">對應發票和對帳檔案之間的費用</a></span><span class="sxs-lookup"><span data-stu-id="6635a-204">See <a href="#charge_types">Mapping charges between an invoice and the reconciliation file</a></span></span></p></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="6635a-205">UnitPrice</span><span class="sxs-lookup"><span data-stu-id="6635a-205">UnitPrice</span></span></td>
<td><p><span data-ttu-id="6635a-206">每一基座價格，即購買時價目表中所公佈的價格。</span><span class="sxs-lookup"><span data-stu-id="6635a-206">Price per seat, as published in the pricelist at the time of purchase.</span></span> <span data-ttu-id="6635a-207">請確定這與對帳期間儲存在您帳單系統中的資訊相符。</span><span class="sxs-lookup"><span data-stu-id="6635a-207">Ensure this matches the information stored in your billing system during reconciliation.</span></span></p></td>
<td><span data-ttu-id="6635a-208">6.82</span><span class="sxs-lookup"><span data-stu-id="6635a-208">6.82</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="6635a-209">數量</span><span class="sxs-lookup"><span data-stu-id="6635a-209">Quantity</span></span></td>
<td><p><span data-ttu-id="6635a-210">基座數目。</span><span class="sxs-lookup"><span data-stu-id="6635a-210">Number of seats.</span></span> <span data-ttu-id="6635a-211">請確定這與對帳期間儲存在您帳單系統中的資訊相符。</span><span class="sxs-lookup"><span data-stu-id="6635a-211">Ensure this matches the information stored in your billing system during reconciliation.</span></span></p></td>
<td><span data-ttu-id="6635a-212">2</span><span class="sxs-lookup"><span data-stu-id="6635a-212">2</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="6635a-213">金額</span><span class="sxs-lookup"><span data-stu-id="6635a-213">Amount</span></span></td>
<td><p><span data-ttu-id="6635a-214">數量總價。</span><span class="sxs-lookup"><span data-stu-id="6635a-214">Total of price for quantity.</span></span> <span data-ttu-id="6635a-215">檢查計算金額與您用來為客戶計算此項目的方式是否相符時很有用。</span><span class="sxs-lookup"><span data-stu-id="6635a-215">Useful to check that the amount calculation matches how you calculate this for your customers.</span></span></p></td>
<td><span data-ttu-id="6635a-216">13.32</span><span class="sxs-lookup"><span data-stu-id="6635a-216">13.32</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="6635a-217">TotalOtherDiscount</span><span class="sxs-lookup"><span data-stu-id="6635a-217">TotalOtherDiscount</span></span></td>
<td><p><span data-ttu-id="6635a-218">套用至這些費用的折扣金額。</span><span class="sxs-lookup"><span data-stu-id="6635a-218">Amount of discount applied to these charges.</span></span> <span data-ttu-id="6635a-219">專長認證或對應或符合獎勵資格的新訂用帳戶所含的產品授權也會在本專欄中包含折扣金額。</span><span class="sxs-lookup"><span data-stu-id="6635a-219">Product Licenses included with a competency or MAPS or new subscriptions eligible for an incentive will also contain a discount amount in this column.</span></span></p></td>
<td><span data-ttu-id="6635a-220">2.32</span><span class="sxs-lookup"><span data-stu-id="6635a-220">2.32</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="6635a-221">小計</span><span class="sxs-lookup"><span data-stu-id="6635a-221">Subtotal</span></span></td>
<td><p><span data-ttu-id="6635a-222">稅前總計。</span><span class="sxs-lookup"><span data-stu-id="6635a-222">Total before tax.</span></span> <span data-ttu-id="6635a-223">如果有折扣，可檢查小計是否和預期的總金額相符。</span><span class="sxs-lookup"><span data-stu-id="6635a-223">Checks that your subtotal matches your expected total, in case of a discount.</span></span></p></td>
<td><span data-ttu-id="6635a-224">11</span><span class="sxs-lookup"><span data-stu-id="6635a-224">11</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="6635a-225">稅</span><span class="sxs-lookup"><span data-stu-id="6635a-225">Tax</span></span></td>
<td><p><span data-ttu-id="6635a-226">稅金金額費用，以您的市場&#39;稅務規則和特定情況為基礎。</span><span class="sxs-lookup"><span data-stu-id="6635a-226">Tax amount charge, based on your market&#39;s tax rules and specific circumstances.</span></span></p></td>
<td><span data-ttu-id="6635a-227">0</span><span class="sxs-lookup"><span data-stu-id="6635a-227">0</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="6635a-228">TotalForCustomer</span><span class="sxs-lookup"><span data-stu-id="6635a-228">TotalForCustomer</span></span></td>
<td><p><span data-ttu-id="6635a-229">稅後總計。</span><span class="sxs-lookup"><span data-stu-id="6635a-229">Total after tax.</span></span> <span data-ttu-id="6635a-230">檢查發票中是否向您收取稅金。</span><span class="sxs-lookup"><span data-stu-id="6635a-230">Checks if you are charged tax in the invoice.</span></span></p></td>
<td><span data-ttu-id="6635a-231">11</span><span class="sxs-lookup"><span data-stu-id="6635a-231">11</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="6635a-232">Currency</span><span class="sxs-lookup"><span data-stu-id="6635a-232">Currency</span></span></td>
<td><p><span data-ttu-id="6635a-233">貨幣類型。</span><span class="sxs-lookup"><span data-stu-id="6635a-233">Currency type.</span></span> <span data-ttu-id="6635a-234">每一帳單實體都只有一種貨幣。</span><span class="sxs-lookup"><span data-stu-id="6635a-234">Each billing entity has only one currency.</span></span> <span data-ttu-id="6635a-235">檢查是否與您的第一張發票相符，然後在進行任何重大帳單平台更新之後檢查。</span><span class="sxs-lookup"><span data-stu-id="6635a-235">Check that it matches your first invoice and then after any major billing platform update.</span></span></p></td>
<td><span data-ttu-id="6635a-236">EUR</span><span class="sxs-lookup"><span data-stu-id="6635a-236">EUR</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="6635a-237">CustomerName</span><span class="sxs-lookup"><span data-stu-id="6635a-237">CustomerName</span></span></td>
<td><p><span data-ttu-id="6635a-238">合作夥伴&#39;中心所回報的客戶組織名稱。</span><span class="sxs-lookup"><span data-stu-id="6635a-238">Customer&#39;s organization name as reported in Partner Center.</span></span> <span data-ttu-id="6635a-239">這在使用您的系統資訊對帳發票時非常重要。</span><span class="sxs-lookup"><span data-stu-id="6635a-239">This is very important for reconciling the invoice with your system information.</span></span></p></td>
<td><span data-ttu-id="6635a-240">測試客戶 A</span><span class="sxs-lookup"><span data-stu-id="6635a-240">Test Customer A</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="6635a-241">MPNID</span><span class="sxs-lookup"><span data-stu-id="6635a-241">MPNID</span></span></td>
<td><p><span data-ttu-id="6635a-242">雲端解決方案提供者合作夥伴的 MPN 識別碼</span><span class="sxs-lookup"><span data-stu-id="6635a-242">MPN ID of the CSP partner</span></span></p></td>
<td><span data-ttu-id="6635a-243">4390934</span><span class="sxs-lookup"><span data-stu-id="6635a-243">4390934</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="6635a-244">ResellerMPNID</span><span class="sxs-lookup"><span data-stu-id="6635a-244">ResellerMPNID</span></span></td>
<td><p><span data-ttu-id="6635a-245">訂閱記錄中的經銷商 MPN 識別碼。</span><span class="sxs-lookup"><span data-stu-id="6635a-245">MPN ID of the reseller of record for the subscription.</span></span> <span data-ttu-id="6635a-246">請參閱<a href="#itemizebypartner" data-raw-source="[Itemize by partner](#itemizebypartner)">依合作夥伴詳細列舉</a>。</span><span class="sxs-lookup"><span data-stu-id="6635a-246">See <a href="#itemizebypartner" data-raw-source="[Itemize by partner](#itemizebypartner)">Itemize by partner</a>.</span></span></p></td>
<td><span data-ttu-id="6635a-247">4390934</span><span class="sxs-lookup"><span data-stu-id="6635a-247">4390934</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="6635a-248">DomainName</span><span class="sxs-lookup"><span data-stu-id="6635a-248">DomainName</span></span></td>
<td><p><span data-ttu-id="6635a-249">客戶&#39;的功能變數名稱，用來協助識別客戶。</span><span class="sxs-lookup"><span data-stu-id="6635a-249">Customer&#39;s domain name, used to help identify the customer.</span></span> <span data-ttu-id="6635a-250">這不應該用來唯一識別客戶，因為客戶/合作夥伴可以透過 O365 入口網站更新虛名/預設網域。</span><span class="sxs-lookup"><span data-stu-id="6635a-250">This should not be used to uniquely identify the customer as the customer/partner can update the vanity/default domain via the O365 portal.</span></span> <span data-ttu-id="6635a-251">在下一個帳單週期之前，此欄位會是空白的。</span><span class="sxs-lookup"><span data-stu-id="6635a-251">This field may appear blank until the second billing cycle.</span></span></p></td>
<td><span data-ttu-id="6635a-252">example.onmicrosoft.com</span><span class="sxs-lookup"><span data-stu-id="6635a-252">example.onmicrosoft.com</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="6635a-253">SubscriptionName</span><span class="sxs-lookup"><span data-stu-id="6635a-253">SubscriptionName</span></span></td>
<td><p><span data-ttu-id="6635a-254">訂閱暱稱。</span><span class="sxs-lookup"><span data-stu-id="6635a-254">Subscription nickname.</span></span> <span data-ttu-id="6635a-255">如果未指定任何暱稱，合作夥伴中心會使用 OfferName。</span><span class="sxs-lookup"><span data-stu-id="6635a-255">If no nickname is specified, Partner Center uses the OfferName.</span></span></p></td>
<td><span data-ttu-id="6635a-256">PROJECT ONLINE</span><span class="sxs-lookup"><span data-stu-id="6635a-256">PROJECT ONLINE</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="6635a-257">SubscriptionDescription</span><span class="sxs-lookup"><span data-stu-id="6635a-257">SubscriptionDescription</span></span></td>
<td><p><span data-ttu-id="6635a-258">客戶購買的服務優惠名稱，如價目表中所定義。</span><span class="sxs-lookup"><span data-stu-id="6635a-258">The name of the service offering purchased by the customer, as defined in the price list.</span></span> <span data-ttu-id="6635a-259">（這是優惠名稱的相同欄位）。</span><span class="sxs-lookup"><span data-stu-id="6635a-259">(This is an identical field to Offer name).</span></span></p></td>
<td><span data-ttu-id="6635a-260">PROJECT ONLINE PREMIUM WITHOUT PROJECT CLIENT</span><span class="sxs-lookup"><span data-stu-id="6635a-260">PROJECT ONLINE PREMIUM WITHOUT PROJECT CLIENT</span></span></td>
</tr>
</tbody>
</table>


## <a href="" id="usagebasedfiles"></a><span data-ttu-id="6635a-261">以使用方式為基礎的檔案欄位</span><span class="sxs-lookup"><span data-stu-id="6635a-261">Usage-based file fields</span></span>


<span data-ttu-id="6635a-262">若要針對您客戶使用量的費用來對帳，請比較對帳檔案中的 ResellerID/ResellerName/ResellerBillableAccount、客戶名稱，與合作夥伴中心的訂閱識別碼。</span><span class="sxs-lookup"><span data-stu-id="6635a-262">To reconcile your charges against your customer's usage, compare the ResellerID/ResellerName/ResellerBillableAccount from the reconciliation file, the customer name, and the Subscription ID from Partner Center.</span></span>

<span data-ttu-id="6635a-263">下列欄位說明使用哪些服務及費率。</span><span class="sxs-lookup"><span data-stu-id="6635a-263">The following fields explain which services were used and the rate.</span></span>

<table>
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<tbody>
<tr class="odd">
<td><span data-ttu-id="6635a-264"><strong>排</strong></span><span class="sxs-lookup"><span data-stu-id="6635a-264"><strong>Column</strong></span></span></td>
<td><span data-ttu-id="6635a-265"><strong>描述</strong></span><span class="sxs-lookup"><span data-stu-id="6635a-265"><strong>Description</strong></span></span></td>
<td><span data-ttu-id="6635a-266"><strong>範例值</strong></span><span class="sxs-lookup"><span data-stu-id="6635a-266"><strong>Sample value</strong></span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="6635a-267">PartnerID</span><span class="sxs-lookup"><span data-stu-id="6635a-267">PartnerID</span></span></td>
<td><p><span data-ttu-id="6635a-268">合作夥伴識別碼 (GUID 格式)。</span><span class="sxs-lookup"><span data-stu-id="6635a-268">Partner ID, in GUID format.</span></span></p></td>
<td><span data-ttu-id="6635a-269">DA41BC5F-C52D-4464-8A8D-8C8DCC43503B</span><span class="sxs-lookup"><span data-stu-id="6635a-269">DA41BC5F-C52D-4464-8A8D-8C8DCC43503B</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="6635a-270">PartnerName</span><span class="sxs-lookup"><span data-stu-id="6635a-270">PartnerName</span></span></td>
<td><p><span data-ttu-id="6635a-271">合作夥伴名稱。</span><span class="sxs-lookup"><span data-stu-id="6635a-271">Partner Name.</span></span></p></td>
<td><span data-ttu-id="6635a-272">Acme Incorporated</span><span class="sxs-lookup"><span data-stu-id="6635a-272">Acme Incorporated</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="6635a-273">PartnerBillableAccountID</span><span class="sxs-lookup"><span data-stu-id="6635a-273">PartnerBillableAccountID</span></span></td>
<td><p><span data-ttu-id="6635a-274">合作夥伴帳戶識別碼。</span><span class="sxs-lookup"><span data-stu-id="6635a-274">Partner Account ID.</span></span></p></td>
<td><span data-ttu-id="6635a-275">1010578050</span><span class="sxs-lookup"><span data-stu-id="6635a-275">1010578050</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="6635a-276">CustomerName</span><span class="sxs-lookup"><span data-stu-id="6635a-276">CustomerName</span></span></td>
<td><p><span data-ttu-id="6635a-277">合作夥伴&#39;中心所回報的客戶組織名稱。</span><span class="sxs-lookup"><span data-stu-id="6635a-277">Customer&#39;s organization name as reported in Partner Center.</span></span> <span data-ttu-id="6635a-278">這在使用您的系統資訊對帳發票時非常重要。</span><span class="sxs-lookup"><span data-stu-id="6635a-278">This is very important for reconciling the invoice with your system information.</span></span></p></td>
<td><span data-ttu-id="6635a-279">測試客戶 A</span><span class="sxs-lookup"><span data-stu-id="6635a-279">Test Customer A</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="6635a-280">MPNID</span><span class="sxs-lookup"><span data-stu-id="6635a-280">MPNID</span></span></td>
<td><p><span data-ttu-id="6635a-281">雲端解決方案提供者合作夥伴的 MPN 識別碼。</span><span class="sxs-lookup"><span data-stu-id="6635a-281">MPN ID of the CSP partner.</span></span></p></td>
<td><span data-ttu-id="6635a-282">4390934</span><span class="sxs-lookup"><span data-stu-id="6635a-282">4390934</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="6635a-283">ResellerMPNID</span><span class="sxs-lookup"><span data-stu-id="6635a-283">ResellerMPNID</span></span></td>
<td><p><span data-ttu-id="6635a-284">訂閱記錄中的經銷商 MPN 識別碼。</span><span class="sxs-lookup"><span data-stu-id="6635a-284">MPN ID of the reseller of record for the subscription.</span></span> <span data-ttu-id="6635a-285">請參閱<a href="#itemizebypartner" data-raw-source="[Itemize by partner](#itemizebypartner)">依合作夥伴詳細列舉</a>。</span><span class="sxs-lookup"><span data-stu-id="6635a-285">See <a href="#itemizebypartner" data-raw-source="[Itemize by partner](#itemizebypartner)">Itemize by partner</a>.</span></span></p></td>
<td><span data-ttu-id="6635a-286">4390934</span><span class="sxs-lookup"><span data-stu-id="6635a-286">4390934</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="6635a-287">InvoiceNumber</span><span class="sxs-lookup"><span data-stu-id="6635a-287">InvoiceNumber</span></span></td>
<td><p><span data-ttu-id="6635a-288">交易的指定位置顯示的發票號碼。</span><span class="sxs-lookup"><span data-stu-id="6635a-288">Invoice number where the specified transaction appears.</span></span></p></td>
<td><span data-ttu-id="6635a-289">D020001IVK</span><span class="sxs-lookup"><span data-stu-id="6635a-289">D020001IVK</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="6635a-290">ChargeStartDate</span><span class="sxs-lookup"><span data-stu-id="6635a-290">ChargeStartDate</span></span></td>
<td><p><span data-ttu-id="6635a-291">計費週期的開始日期，當顯示之前未收取潛在使用量資料費用的日期時除外 (從前一個計費週期開始)。</span><span class="sxs-lookup"><span data-stu-id="6635a-291">Start date of billing cycle except when presenting dates of previously uncharged latent usage data (from previous bill cycle).</span></span></p>
<p><span data-ttu-id="6635a-292">時間一律是一天的開始時間 (0:00)。</span><span class="sxs-lookup"><span data-stu-id="6635a-292">The time is always the beginning of the day, 0:00.</span></span></p></td>
<td><span data-ttu-id="6635a-293">2/1/2014 0:00</span><span class="sxs-lookup"><span data-stu-id="6635a-293">2/1/2014 0:00</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="6635a-294">ChargeEndDate</span><span class="sxs-lookup"><span data-stu-id="6635a-294">ChargeEndDate</span></span></td>
<td><p><span data-ttu-id="6635a-295">計費週期的結束日期，當顯示之前未收取潛在使用量資料費用的日期時除外 (從前一個計費週期開始)。</span><span class="sxs-lookup"><span data-stu-id="6635a-295">End date of billing cycle except when presenting dates of previously uncharged latent usage data (from previous bill cycle).</span></span></p>
<p><span data-ttu-id="6635a-296">時間一律是一天的結束時間 (23:59)。</span><span class="sxs-lookup"><span data-stu-id="6635a-296">The time is always the end of the day, 23:59.</span></span></p></td>
<td><span data-ttu-id="6635a-297">2/28/2014 23:59</span><span class="sxs-lookup"><span data-stu-id="6635a-297">2/28/2014 23:59</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="6635a-298">SubscriptionID</span><span class="sxs-lookup"><span data-stu-id="6635a-298">SubscriptionID</span></span></td>
<td><p><span data-ttu-id="6635a-299">訂閱在 Microsoft 帳單平台中的唯一識別碼。</span><span class="sxs-lookup"><span data-stu-id="6635a-299">Unique identifier for a subscription in the Microsoft billing platform.</span></span> <span data-ttu-id="6635a-300">可在連絡支援時方便識別訂閱，但不是用於對帳。</span><span class="sxs-lookup"><span data-stu-id="6635a-300">May be useful to identify the subscription when contacting support but not for reconciliation.</span></span></p>
<p><span data-ttu-id="6635a-301">這與合作夥伴管理主控台上的訂閱識別碼不一樣。</span><span class="sxs-lookup"><span data-stu-id="6635a-301">This is not the same as the Subscription ID on the Partner Admin Console.</span></span></p></td>
<td><span data-ttu-id="6635a-302">usCBMgAAAAAAAAIA</span><span class="sxs-lookup"><span data-stu-id="6635a-302">usCBMgAAAAAAAAIA</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="6635a-303">SubscriptionName</span><span class="sxs-lookup"><span data-stu-id="6635a-303">SubscriptionName</span></span></td>
<td><p><span data-ttu-id="6635a-304">服務優惠的暱稱。</span><span class="sxs-lookup"><span data-stu-id="6635a-304">Nickname of the service offering.</span></span></p></td>
<td><span data-ttu-id="6635a-305">Microsoft Azure</span><span class="sxs-lookup"><span data-stu-id="6635a-305">Microsoft Azure</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="6635a-306">SubscriptionDescription</span><span class="sxs-lookup"><span data-stu-id="6635a-306">SubscriptionDescription</span></span></td>
<td><p><span data-ttu-id="6635a-307">服務優惠的企業營運</span><span class="sxs-lookup"><span data-stu-id="6635a-307">Line of business of the service offering</span></span></p></td>
<td><span data-ttu-id="6635a-308">Microsoft Azure</span><span class="sxs-lookup"><span data-stu-id="6635a-308">Microsoft Azure</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="6635a-309">OrderID</span><span class="sxs-lookup"><span data-stu-id="6635a-309">OrderID</span></span></td>
<td><p><span data-ttu-id="6635a-310">訂單在 Microsoft 帳單平台中的唯一識別碼。</span><span class="sxs-lookup"><span data-stu-id="6635a-310">Unique identifier for an order in the Microsoft billing platform.</span></span> <span data-ttu-id="6635a-311">可在連絡支援時方便識別訂閱，但不是用於對帳。</span><span class="sxs-lookup"><span data-stu-id="6635a-311">May be useful to identify the subscription when contacting support but not for reconciliation.</span></span></p></td>
<td><span data-ttu-id="6635a-312">566890604832738111</span><span class="sxs-lookup"><span data-stu-id="6635a-312">566890604832738111</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="6635a-313">ServiceName</span><span class="sxs-lookup"><span data-stu-id="6635a-313">ServiceName</span></span></td>
<td><p><span data-ttu-id="6635a-314">要求的 Azure 服務名稱。</span><span class="sxs-lookup"><span data-stu-id="6635a-314">The name of the Azure service in question.</span></span></p></td>
<td><span data-ttu-id="6635a-315">虛擬機器</span><span class="sxs-lookup"><span data-stu-id="6635a-315">VIRTUAL MACHINES</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="6635a-316">ServiceType</span><span class="sxs-lookup"><span data-stu-id="6635a-316">ServiceType</span></span></td>
<td><p><span data-ttu-id="6635a-317">Microsoft Azure 服務的特定類型。</span><span class="sxs-lookup"><span data-stu-id="6635a-317">The specific type of Windows Azure service.</span></span></p></td>
<td><ul>
<li><span data-ttu-id="6635a-318">服務匯流排 – 個人或套件</span><span class="sxs-lookup"><span data-stu-id="6635a-318">Service Bus – Individual or Pack</span></span></li>
<li><span data-ttu-id="6635a-319">SQL Azure 資料庫 – Business 或 Web Edition</span><span class="sxs-lookup"><span data-stu-id="6635a-319">SQL Azure database – Business or Web Edition</span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="6635a-320">ResourceGUID</span><span class="sxs-lookup"><span data-stu-id="6635a-320">ResourceGUID</span></span></td>
<td><p><span data-ttu-id="6635a-321">所有服務資料與定價結構的特定唯一識別碼。</span><span class="sxs-lookup"><span data-stu-id="6635a-321">Specific unique identifier for all the service data and pricing structure.</span></span></p></td>
<td><span data-ttu-id="6635a-322">DA41BC5F-C52D-4464-8A8D-8C8DCC43503B</span><span class="sxs-lookup"><span data-stu-id="6635a-322">DA41BC5F-C52D-4464-8A8D-8C8DCC43503B</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="6635a-323">Resource Name</span><span class="sxs-lookup"><span data-stu-id="6635a-323">Resource Name</span></span></td>
<td><p><span data-ttu-id="6635a-324">Azure 資源的名稱。</span><span class="sxs-lookup"><span data-stu-id="6635a-324">The name of the Azure resource.</span></span></p></td>
<td><ul>
<li><span data-ttu-id="6635a-325">資料轉入 (GB)</span><span class="sxs-lookup"><span data-stu-id="6635a-325">Data Transfer In (GB)</span></span></li>
<li><span data-ttu-id="6635a-326">資料轉出 (GB)</span><span class="sxs-lookup"><span data-stu-id="6635a-326">Data Transfer Out (GB)</span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="6635a-327">地區</span><span class="sxs-lookup"><span data-stu-id="6635a-327">Region</span></span></td>
<td><p><span data-ttu-id="6635a-328">使用量適用的地區。</span><span class="sxs-lookup"><span data-stu-id="6635a-328">The region the usage applies to.</span></span> <span data-ttu-id="6635a-329">主要用來指定資料傳輸速率，費率因地區而異。</span><span class="sxs-lookup"><span data-stu-id="6635a-329">Primarily used to assign rates to data transfers, as rates vary by region.</span></span></p></td>
<td><span data-ttu-id="6635a-330">亞太地區、歐洲、拉丁美洲、北美洲</span><span class="sxs-lookup"><span data-stu-id="6635a-330">Asia Pacific, Europe, Latin America, North America</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="6635a-331">SKU</span><span class="sxs-lookup"><span data-stu-id="6635a-331">SKU</span></span></td>
<td><p><span data-ttu-id="6635a-332">優惠的 MSFT 唯一識別碼</span><span class="sxs-lookup"><span data-stu-id="6635a-332">MSFT unique identifier for offer</span></span></p></td>
<td><span data-ttu-id="6635a-333">7UD 00001</span><span class="sxs-lookup"><span data-stu-id="6635a-333">7UD-00001</span></span></td>
</tr>
<tr class="odd">
<td><p><span data-ttu-id="6635a-334">DetailLineItemId</span><span class="sxs-lookup"><span data-stu-id="6635a-334">DetailLineItemId</span></span></p></td>
<td><p><span data-ttu-id="6635a-335">用於詳細列出指定計費期間中，服務或資源不同費率的識別碼和數量。</span><span class="sxs-lookup"><span data-stu-id="6635a-335">An ID and quantity for itemizing the different rates for a service or resource in a given billing period.</span></span> <span data-ttu-id="6635a-336">對於 Azure 分層評分，到某個數量的計費單位會有一個評分，之後則有不同評分。</span><span class="sxs-lookup"><span data-stu-id="6635a-336">For Azure tiered rating, there may be one rate up to a certain quantity of billable units, then a different rate after that.</span></span></p></td>
<td><span data-ttu-id="6635a-337">1</span><span class="sxs-lookup"><span data-stu-id="6635a-337">1</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="6635a-338">ConsumedQuantity</span><span class="sxs-lookup"><span data-stu-id="6635a-338">ConsumedQuantity</span></span></td>
<td><p><span data-ttu-id="6635a-339">報表期間耗用的服務量 (小時、GB 等等)</span><span class="sxs-lookup"><span data-stu-id="6635a-339">The amount of service consumed (hours, GB, etc.) during the reporting period.</span></span></p>
<p><span data-ttu-id="6635a-340">同時包括先前報表期間任何未計費的使用量。</span><span class="sxs-lookup"><span data-stu-id="6635a-340">Also includes any unbilled usage from previous reporting periods.</span></span></p></td>
<td><span data-ttu-id="6635a-341">11</span><span class="sxs-lookup"><span data-stu-id="6635a-341">11</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="6635a-342">IncludedQuantity</span><span class="sxs-lookup"><span data-stu-id="6635a-342">IncludedQuantity</span></span></td>
<td><p><span data-ttu-id="6635a-343">包含在優惠中的單位。</span><span class="sxs-lookup"><span data-stu-id="6635a-343">Units included as part of the offer.</span></span> <span data-ttu-id="6635a-344">通常不會出現在雲端解決方案提供者中。</span><span class="sxs-lookup"><span data-stu-id="6635a-344">Not typically present in CSP.</span></span></p></td>
<td><span data-ttu-id="6635a-345">0</span><span class="sxs-lookup"><span data-stu-id="6635a-345">0</span></span></td>
</tr>
<tr class="even">
<td><p><span data-ttu-id="6635a-346">OverageQuantity</span><span class="sxs-lookup"><span data-stu-id="6635a-346">OverageQuantity</span></span></p></td>
<td><p><span data-ttu-id="6635a-347">不包含在優惠中的單位，必須由合作夥伴支付。</span><span class="sxs-lookup"><span data-stu-id="6635a-347">Units not included as part of the offer, that must be paid for by the partner.</span></span></p>
<p><span data-ttu-id="6635a-348">等同於 ConsumedQuantity - IncludedQuantity。</span><span class="sxs-lookup"><span data-stu-id="6635a-348">Equal to the ConsumedQuantity - IncludedQuantity.</span></span></p></td>
<td><span data-ttu-id="6635a-349">11</span><span class="sxs-lookup"><span data-stu-id="6635a-349">11</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="6635a-350">ListPrice</span><span class="sxs-lookup"><span data-stu-id="6635a-350">ListPrice</span></span></td>
<td><p><span data-ttu-id="6635a-351">訂閱開始日期的生效優惠價格。</span><span class="sxs-lookup"><span data-stu-id="6635a-351">Offer price in effect at subscription start date.</span></span></p></td>
<td><span data-ttu-id="6635a-352">$0.0808</span><span class="sxs-lookup"><span data-stu-id="6635a-352">$0.0808</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="6635a-353">PretaxCharges</span><span class="sxs-lookup"><span data-stu-id="6635a-353">PretaxCharges</span></span></td>
<td><p><span data-ttu-id="6635a-354">ListPrist 乘以 OverageQuantity，四捨五入至美分。</span><span class="sxs-lookup"><span data-stu-id="6635a-354">ListPrist times OverageQuantity, rounded to the nearest cent.</span></span></p></td>
<td><span data-ttu-id="6635a-355">$0.085</span><span class="sxs-lookup"><span data-stu-id="6635a-355">$0.085</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="6635a-356">TaxAmount</span><span class="sxs-lookup"><span data-stu-id="6635a-356">TaxAmount</span></span></td>
<td><p><span data-ttu-id="6635a-357">稅金金額費用，以您的市場&#39;稅務規則和特定情況為基礎。</span><span class="sxs-lookup"><span data-stu-id="6635a-357">Tax amount charge, based on your market&#39;s tax rules and specific circumstances.</span></span></p></td>
<td><span data-ttu-id="6635a-358">$0.08</span><span class="sxs-lookup"><span data-stu-id="6635a-358">$0.08</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="6635a-359">PostTaxTotal</span><span class="sxs-lookup"><span data-stu-id="6635a-359">PostTaxTotal</span></span></td>
<td><p><span data-ttu-id="6635a-360">稅後總計 (當適用稅金時)。</span><span class="sxs-lookup"><span data-stu-id="6635a-360">Total after tax, when tax is applicable.</span></span></p></td>
<td><span data-ttu-id="6635a-361">$0.93</span><span class="sxs-lookup"><span data-stu-id="6635a-361">$0.93</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="6635a-362">Currency</span><span class="sxs-lookup"><span data-stu-id="6635a-362">Currency</span></span></td>
<td><p><span data-ttu-id="6635a-363">貨幣類型。</span><span class="sxs-lookup"><span data-stu-id="6635a-363">Currency type.</span></span> <span data-ttu-id="6635a-364">每一帳單實體都只有一種貨幣。</span><span class="sxs-lookup"><span data-stu-id="6635a-364">Each billing entity has only one currency.</span></span> <span data-ttu-id="6635a-365">檢查是否與您的第一張發票相符，然後在進行任何重大帳單平台更新之後檢查。</span><span class="sxs-lookup"><span data-stu-id="6635a-365">Check that it matches your first invoice and then after any major billing platform update.</span></span></p></td>
<td><span data-ttu-id="6635a-366">EUR</span><span class="sxs-lookup"><span data-stu-id="6635a-366">EUR</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="6635a-367">PretaxEffectiveRate</span><span class="sxs-lookup"><span data-stu-id="6635a-367">PretaxEffectiveRate</span></span></td>
<td><p><span data-ttu-id="6635a-368">每個單位的稅前價格。</span><span class="sxs-lookup"><span data-stu-id="6635a-368">Pretax price per unit.</span></span> <span data-ttu-id="6635a-369">等於 PretaxCharges / OverageQuantity, 四捨五入至美分。</span><span class="sxs-lookup"><span data-stu-id="6635a-369">Equal to PretaxCharges / OverageQuantity, rounded to the nearest cent.</span></span></p></td>
<td><span data-ttu-id="6635a-370">$0.08</span><span class="sxs-lookup"><span data-stu-id="6635a-370">$0.08</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="6635a-371">PostTaxEffectiveRate</span><span class="sxs-lookup"><span data-stu-id="6635a-371">PostTaxEffectiveRate</span></span></td>
<td><p><span data-ttu-id="6635a-372">每個單位的稅後價格。</span><span class="sxs-lookup"><span data-stu-id="6635a-372">Post tax price per unit.</span></span> <span data-ttu-id="6635a-373">等於 PostTaxTotal / OverageQuantity，或 PretaxEffectiveRate + 每單位數量稅率，四捨五入至美分。</span><span class="sxs-lookup"><span data-stu-id="6635a-373">Equal to PostTaxTotal / OverageQuantity, or PretaxEffectiveRate + tax rate per unit amoun, rounded to the nearest cent.</span></span></p></td>
<td><span data-ttu-id="6635a-374">$0.08</span><span class="sxs-lookup"><span data-stu-id="6635a-374">$0.08</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="6635a-375">ChargeType</span><span class="sxs-lookup"><span data-stu-id="6635a-375">ChargeType</span></span></td>
<td><p><span data-ttu-id="6635a-376">費用或調整的類型。</span><span class="sxs-lookup"><span data-stu-id="6635a-376">The type of charge or adjustment.</span></span> <span data-ttu-id="6635a-377">請參閱<a href="#charge_types">對應發票和對帳檔案之間的費用</a></span><span class="sxs-lookup"><span data-stu-id="6635a-377">See <a href="#charge_types">Mapping charges between an invoice and the reconciliation file</a></span></span></p></td>
<td><p><span data-ttu-id="6635a-378">請參閱<a href="#charge_types">對應發票和對帳檔案之間的費用</a></span><span class="sxs-lookup"><span data-stu-id="6635a-378">See <a href="#charge_types">Mapping charges between an invoice and the reconciliation file</a></span></span></p></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="6635a-379">CustomerBillableAccount</span><span class="sxs-lookup"><span data-stu-id="6635a-379">CustomerBillableAccount</span></span></td>
<td><p><span data-ttu-id="6635a-380">MSFT 帳單平台的唯一帳戶識別碼。</span><span class="sxs-lookup"><span data-stu-id="6635a-380">Unique account ID in the MSFT billing platform.</span></span></p></td>
<td><span data-ttu-id="6635a-381">1280018095</span><span class="sxs-lookup"><span data-stu-id="6635a-381">1280018095</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="6635a-382">UsageDate</span><span class="sxs-lookup"><span data-stu-id="6635a-382">UsageDate</span></span></td>
<td><p><span data-ttu-id="6635a-383">服務部署的日期。</span><span class="sxs-lookup"><span data-stu-id="6635a-383">Date of service deployment.</span></span></p></td>
<td><span data-ttu-id="6635a-384">2/1/2014 0:00</span><span class="sxs-lookup"><span data-stu-id="6635a-384">2/1/2014 0:00</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="6635a-385">MeteredRegion</span><span class="sxs-lookup"><span data-stu-id="6635a-385">MeteredRegion</span></span></td>
<td><p><span data-ttu-id="6635a-386">此欄可識別適用及填入此項目之服務地區內的資料中心的位置。</span><span class="sxs-lookup"><span data-stu-id="6635a-386">This column identifies the location of a data center within the region for services where this is applicable and populated.</span></span></p></td>
<td><span data-ttu-id="6635a-387">東亞、東南亞、北歐、西歐、美國中北部、美國中南部</span><span class="sxs-lookup"><span data-stu-id="6635a-387">East Asia, South East Asia, North Europe, West Europe, North Central US, South Central US</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="6635a-388">MeteredService</span><span class="sxs-lookup"><span data-stu-id="6635a-388">MeteredService</span></span></td>
<td><p><span data-ttu-id="6635a-389">此欄是用來追蹤可能未在 \[服務名稱\] 欄中特別指出的個別 Microsoft Azure 服務。</span><span class="sxs-lookup"><span data-stu-id="6635a-389">This column is utilized to track the individual Microsoft Azure service that may not be specifically identified in the Service Name column.</span></span> <span data-ttu-id="6635a-390">例如，在 \[服務名稱\] 欄中，資料傳輸是回報為 &quot;Microsoft Azure - 所有服務&quot;。</span><span class="sxs-lookup"><span data-stu-id="6635a-390">For example, data transfers are reported as &quot;Microsoft Azure - All Services&quot; in the Service Name column.</span></span> <span data-ttu-id="6635a-391">此 MeteredService 欄會指出使用量與哪個特定服務有關。</span><span class="sxs-lookup"><span data-stu-id="6635a-391">This MeteredService column will indicate to which specific service the usage pertains.</span></span></p></td>
<td><span data-ttu-id="6635a-392">AccessControl、CDN、Compute、Database、ServiceBus、Storage</span><span class="sxs-lookup"><span data-stu-id="6635a-392">AccessControl, CDN, Compute, Database, ServiceBus, Storage</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="6635a-393">MeteredServiceType</span><span class="sxs-lookup"><span data-stu-id="6635a-393">MeteredServiceType</span></span></td>
<td><p><span data-ttu-id="6635a-394">進一步釐清超出 MeteredService 欄位提供之層級的個別 Microsoft Azure 服務副標題。</span><span class="sxs-lookup"><span data-stu-id="6635a-394">A subheading that further clarifies the individual Microsoft Azure service beyond the level provided by the MeteredService field.</span></span></p></td>
<td><span data-ttu-id="6635a-395">外部</span><span class="sxs-lookup"><span data-stu-id="6635a-395">EXTERNAL</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="6635a-396">投影</span><span class="sxs-lookup"><span data-stu-id="6635a-396">Project</span></span></td>
<td><p><span data-ttu-id="6635a-397">客戶為其服務執行個體定義的名稱</span><span class="sxs-lookup"><span data-stu-id="6635a-397">Customer-defined name for their service instance</span></span></p></td>
<td><span data-ttu-id="6635a-398">ORDDC52E52FDEF405786F0642DD0108BE4</span><span class="sxs-lookup"><span data-stu-id="6635a-398">ORDDC52E52FDEF405786F0642DD0108BE4</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="6635a-399">ServiceInfo</span><span class="sxs-lookup"><span data-stu-id="6635a-399">ServiceInfo</span></span></td>
<td><p><span data-ttu-id="6635a-400">於某一天佈建及使用的 ServiceBus 連線數目。</span><span class="sxs-lookup"><span data-stu-id="6635a-400">The number of ServiceBus connections that were provisioned and utilized on a given day.</span></span></p></td>
<td><span data-ttu-id="6635a-401">例如：如果您在有 30 天的月份中有個別佈建的連線時，「服務資訊 1」的讀數會是「1.000000 連線 / 30 天」。</span><span class="sxs-lookup"><span data-stu-id="6635a-401">For example: if you had an individually provisioned connection during a 30 day month, Service Info 1 would read “1.000000 Connections / 30 days”.</span></span> <span data-ttu-id="6635a-402">如果您佈建 25 組 ServiceBus 連線並在那天使用其中一組，那一天的每日使用量就會指示「25 組連線 / 30 天 - 已使用：1.000000」。</span><span class="sxs-lookup"><span data-stu-id="6635a-402">If you had a 25 pack of ServiceBus connections provisioned and you had utilized 1 during that day, your daily usage statement for that day would indicate “25 Connections / 30 Days – Used: 1.000000”.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="6635a-403">CustomerID</span><span class="sxs-lookup"><span data-stu-id="6635a-403">CustomerID</span></span></td>
<td><p><span data-ttu-id="6635a-404">用來識別客戶的唯一 Microsoft ID（GUID 格式）。</span><span class="sxs-lookup"><span data-stu-id="6635a-404">Unique Microsoft ID, in GUID format, used to identify the customer.</span></span></p></td>
<td><span data-ttu-id="6635a-405">ORDDC52E52FDEF405786F0642DD0108BE4</span><span class="sxs-lookup"><span data-stu-id="6635a-405">ORDDC52E52FDEF405786F0642DD0108BE4</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="6635a-406">DomainName</span><span class="sxs-lookup"><span data-stu-id="6635a-406">DomainName</span></span></td>
<td><p><span data-ttu-id="6635a-407">客戶&#39;的功能變數名稱，用來協助識別客戶。</span><span class="sxs-lookup"><span data-stu-id="6635a-407">Customer&#39;s domain name, used to help identify the customer.</span></span> <span data-ttu-id="6635a-408">在下一個帳單週期之前，此欄位會是空白的。</span><span class="sxs-lookup"><span data-stu-id="6635a-408">This field may appear blank until the second billing cycle.</span></span></p></td>
<td><span data-ttu-id="6635a-409">example.onmicrosoft.com</span><span class="sxs-lookup"><span data-stu-id="6635a-409">example.onmicrosoft.com</span></span></td></tr>
</tr>
<tr class="even">
<td><span data-ttu-id="6635a-410">單位</span><span class="sxs-lookup"><span data-stu-id="6635a-410">Unit</span></span></td>
<td><p><span data-ttu-id="6635a-411">資源名稱的單位</span><span class="sxs-lookup"><span data-stu-id="6635a-411">The unit of the resource Name</span></span></p></td>
<td><span data-ttu-id="6635a-412">GB 或 HOURS</span><span class="sxs-lookup"><span data-stu-id="6635a-412">GB or HOURS</span></span></td>
</tr>
</tbody>
</table>

## <a href="" id="marketplacefilefields"></a><span data-ttu-id="6635a-413">一次性和週期性的檔案欄位</span><span class="sxs-lookup"><span data-stu-id="6635a-413">One-time and recurring file fields</span></span>

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th><span data-ttu-id="6635a-414">Column</span><span class="sxs-lookup"><span data-stu-id="6635a-414">Column</span></span></th>
<th><span data-ttu-id="6635a-415">說明</span><span class="sxs-lookup"><span data-stu-id="6635a-415">Description</span></span></th>
</tr>
</thead>
<tbody>

<tr class="odd">
<td><span data-ttu-id="6635a-416">PartnerId</span><span class="sxs-lookup"><span data-stu-id="6635a-416">PartnerId</span></span></td>
<td><p><span data-ttu-id="6635a-417">特定計費實體的唯一 Microsoft Azure Active Directory 租使用者識別碼（GUID 格式）。</span><span class="sxs-lookup"><span data-stu-id="6635a-417">Unique Microsoft Azure Active Directory tenant identifier for a specific billing entity, in GUID format.</span></span> <span data-ttu-id="6635a-418">對帳時不需要，但可能是很有用的資訊。</span><span class="sxs-lookup"><span data-stu-id="6635a-418">Not required for reconciliation, however may be useful information.</span></span> <span data-ttu-id="6635a-419">在所有資料列中都是如此。</span><span class="sxs-lookup"><span data-stu-id="6635a-419">Same in all rows.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="6635a-420">客戶識別碼</span><span class="sxs-lookup"><span data-stu-id="6635a-420">Customer Id</span></span></td>
<td><p><span data-ttu-id="6635a-421">用來識別客戶的唯一 Microsoft Azure Active Directory 租使用者識別碼（GUID 格式）。</span><span class="sxs-lookup"><span data-stu-id="6635a-421">Unique Microsoft Azure Active Directory tenant ID, in GUID format, used to identify the customer.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="6635a-422">[客戶名稱]</span><span class="sxs-lookup"><span data-stu-id="6635a-422">Customer Name</span></span></td>
<td><p><span data-ttu-id="6635a-423">合作夥伴中心中回報的客戶組織名稱。</span><span class="sxs-lookup"><span data-stu-id="6635a-423">Customer's organization name as reported in Partner Center.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="6635a-424">CustomerDomainName</span><span class="sxs-lookup"><span data-stu-id="6635a-424">CustomerDomainName</span></span></td>
<td><p><span data-ttu-id="6635a-425">用來協助識別客戶的客戶網域名稱。</span><span class="sxs-lookup"><span data-stu-id="6635a-425">Customer's domain name, used to help identify the customer.</span></span> <span data-ttu-id="6635a-426">這不應該用來唯一識別客戶，因為客戶/合作夥伴可以透過 O365 入口網站更新虛名/預設網域。</span><span class="sxs-lookup"><span data-stu-id="6635a-426">This should not be used to uniquely identify the customer as the customer/partner can update the vanity/default domain via the O365 portal.</span></span> <span data-ttu-id="6635a-427">在下一個帳單週期之前，此欄位會是空白的。</span><span class="sxs-lookup"><span data-stu-id="6635a-427">This field may appear blank until the second billing cycle.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="6635a-428">客戶國家/地區</span><span class="sxs-lookup"><span data-stu-id="6635a-428">Customer Country</span></span></td>
<td><p><span data-ttu-id="6635a-429">客戶所在的國家/地區。</span><span class="sxs-lookup"><span data-stu-id="6635a-429">The country in which the customer is located.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="6635a-430">發票號碼</span><span class="sxs-lookup"><span data-stu-id="6635a-430">Invoice number</span></span></td>
<td><p><span data-ttu-id="6635a-431">交易的指定位置顯示的發票號碼。</span><span class="sxs-lookup"><span data-stu-id="6635a-431">Invoice number where the specified transaction appears.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="6635a-432">MpnId</span><span class="sxs-lookup"><span data-stu-id="6635a-432">MpnId</span></span></td>
<td><p><span data-ttu-id="6635a-433">雲端解決方案提供者合作夥伴的 MPN 識別碼。</span><span class="sxs-lookup"><span data-stu-id="6635a-433">MPN ID of the CSP partner.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="6635a-434">轉售商 MpnId</span><span class="sxs-lookup"><span data-stu-id="6635a-434">Reseller MpnId</span></span></td>
<td><p><span data-ttu-id="6635a-435">訂閱記錄中的經銷商 MPN 識別碼。</span><span class="sxs-lookup"><span data-stu-id="6635a-435">MPN ID of the reseller of record for the subscription.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="6635a-436">訂單識別碼</span><span class="sxs-lookup"><span data-stu-id="6635a-436">Order ID</span></span></td>
<td><p><span data-ttu-id="6635a-437">Microsoft 商務平臺中訂單的唯一識別碼。</span><span class="sxs-lookup"><span data-stu-id="6635a-437">Unique identifier for an order in the Microsoft commerce platform.</span></span> <span data-ttu-id="6635a-438">可在連絡支援時方便識別訂單，但不是用於對帳。</span><span class="sxs-lookup"><span data-stu-id="6635a-438">May be useful to identify the order when contacting support but not for reconciliation.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="6635a-439">訂單日期</span><span class="sxs-lookup"><span data-stu-id="6635a-439">Order date</span></span></td>
<td><p><span data-ttu-id="6635a-440">下訂單的日期。</span><span class="sxs-lookup"><span data-stu-id="6635a-440">The date the order was placed.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="6635a-441">ProductId</span><span class="sxs-lookup"><span data-stu-id="6635a-441">ProductId</span></span></td>
<td><p><span data-ttu-id="6635a-442">產品的識別碼。</span><span class="sxs-lookup"><span data-stu-id="6635a-442">The ID for the product.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="6635a-443">SkuId</span><span class="sxs-lookup"><span data-stu-id="6635a-443">SkuId</span></span></td>
<td><p><span data-ttu-id="6635a-444">特定 SKU 的識別碼。</span><span class="sxs-lookup"><span data-stu-id="6635a-444">The ID for a particular SKU.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="6635a-445">AvailabilityId</span><span class="sxs-lookup"><span data-stu-id="6635a-445">AvailabilityId</span></span></td>
<td><p><span data-ttu-id="6635a-446">特定可用性的識別碼。</span><span class="sxs-lookup"><span data-stu-id="6635a-446">The ID for a particular Availability.</span></span> <span data-ttu-id="6635a-447">「可用性」是指特定 SKU 是否可供特定的國家/地區、貨幣、行業區段等等購買。</span><span class="sxs-lookup"><span data-stu-id="6635a-447">“Availability” refers to whether or not a particular SKU is available for purchase for the given country, currency, industry segment, etc.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="6635a-448">SKU 名稱</span><span class="sxs-lookup"><span data-stu-id="6635a-448">SKU Name</span></span></td>
<td><p><span data-ttu-id="6635a-449">特定 SKU 的標題。</span><span class="sxs-lookup"><span data-stu-id="6635a-449">The title for a particular SKU.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="6635a-450">[產品名稱]</span><span class="sxs-lookup"><span data-stu-id="6635a-450">Product name</span></span></td>
<td><p><span data-ttu-id="6635a-451">產品的名稱。</span><span class="sxs-lookup"><span data-stu-id="6635a-451">The name of the product.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="6635a-452">PublisherName</span><span class="sxs-lookup"><span data-stu-id="6635a-452">PublisherName</span></span></td>
<td><p><span data-ttu-id="6635a-453">產品發行者的名稱。</span><span class="sxs-lookup"><span data-stu-id="6635a-453">The name of the product’s publisher.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="6635a-454">PublisherID</span><span class="sxs-lookup"><span data-stu-id="6635a-454">PublisherID</span></span></td>
<td><p><span data-ttu-id="6635a-455">此發行者的唯一識別碼。</span><span class="sxs-lookup"><span data-stu-id="6635a-455">Unique ID for this publisher.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="6635a-456">訂用帳戶描述</span><span class="sxs-lookup"><span data-stu-id="6635a-456">Subscription Description</span></span></td>
<td><p><span data-ttu-id="6635a-457">訂用帳戶的易記名稱。</span><span class="sxs-lookup"><span data-stu-id="6635a-457">Friendly name of a subscription.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="6635a-458">[訂閱識別碼]</span><span class="sxs-lookup"><span data-stu-id="6635a-458">Subscription ID</span></span></td>
<td><p><span data-ttu-id="6635a-459">Microsoft commerce 平臺中訂用帳戶的唯一識別碼。</span><span class="sxs-lookup"><span data-stu-id="6635a-459">Unique identifier for a subscription in the Microsoft commerce platform.</span></span> <span data-ttu-id="6635a-460">可在連絡支援時方便識別訂閱，但不是用於對帳。</span><span class="sxs-lookup"><span data-stu-id="6635a-460">May be useful to identify the subscription when contacting support but not for reconciliation.</span></span> <span data-ttu-id="6635a-461">這與合作夥伴管理主控台上的訂閱識別碼不一樣。</span><span class="sxs-lookup"><span data-stu-id="6635a-461">This is not the same as the Subscription ID on the Partner Admin Console.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="6635a-462">ChargeStartDate</span><span class="sxs-lookup"><span data-stu-id="6635a-462">ChargeStartDate</span></span></td>
<td><p><span data-ttu-id="6635a-463">開始計算費用的日期。</span><span class="sxs-lookup"><span data-stu-id="6635a-463">Start day of the charges.</span></span> <span data-ttu-id="6635a-464">時間一律是一天的開始時間 (0:00)。</span><span class="sxs-lookup"><span data-stu-id="6635a-464">The time is always the beginning of the day, 0:00.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="6635a-465">ChargeEndDate</span><span class="sxs-lookup"><span data-stu-id="6635a-465">ChargeEndDate</span></span></td>
<td><p><span data-ttu-id="6635a-466">結束計算費用的日期。</span><span class="sxs-lookup"><span data-stu-id="6635a-466">End day of the charges.</span></span> <span data-ttu-id="6635a-467">時間一律是一天的結束時間 (23:59)。</span><span class="sxs-lookup"><span data-stu-id="6635a-467">The time is always the end of the day, 23:59.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="6635a-468">詞彙和 Billingcycle</span><span class="sxs-lookup"><span data-stu-id="6635a-468">Term and Billingcycle</span></span></td>
<td><p><span data-ttu-id="6635a-469">購買的詞彙長度和計費週期。</span><span class="sxs-lookup"><span data-stu-id="6635a-469">The term length and billing cycle for the purchase.</span></span> <span data-ttu-id="6635a-470">例如，「1年、每月」。</span><span class="sxs-lookup"><span data-stu-id="6635a-470">For example, “1 Year, Monthly.”</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="6635a-471">收費類型</span><span class="sxs-lookup"><span data-stu-id="6635a-471">Charge Type</span></span></td>
<td><p><span data-ttu-id="6635a-472">費用或調整的類型。</span><span class="sxs-lookup"><span data-stu-id="6635a-472">The type of charge or adjustment.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="6635a-473">單價</span><span class="sxs-lookup"><span data-stu-id="6635a-473">Unit Price</span></span></td>
<td><p><span data-ttu-id="6635a-474">購買時，在價目表中發佈的價格。</span><span class="sxs-lookup"><span data-stu-id="6635a-474">The price as published in the pricelist at the time of purchase.</span></span> <span data-ttu-id="6635a-475">請確定這與對帳期間儲存在您帳單系統中的資訊相符。</span><span class="sxs-lookup"><span data-stu-id="6635a-475">Ensure this matches the information stored in your billing system during reconciliation.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="6635a-476">有效單位價格</span><span class="sxs-lookup"><span data-stu-id="6635a-476">Effective Unit Price</span></span></td>
<td><p><span data-ttu-id="6635a-477">進行調整後的單位價格。</span><span class="sxs-lookup"><span data-stu-id="6635a-477">The unit price after adjustments have been made.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="6635a-478">數量</span><span class="sxs-lookup"><span data-stu-id="6635a-478">Quantity</span></span></td>
<td><p><span data-ttu-id="6635a-479">單位數。</span><span class="sxs-lookup"><span data-stu-id="6635a-479">Number of units.</span></span> <span data-ttu-id="6635a-480">請確定這與對帳期間儲存在您帳單系統中的資訊相符。</span><span class="sxs-lookup"><span data-stu-id="6635a-480">Ensure this matches the information stored in your billing system during reconciliation.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="6635a-481">單位類型</span><span class="sxs-lookup"><span data-stu-id="6635a-481">Unit type</span></span></td>
<td><p><span data-ttu-id="6635a-482">所購買的單位類型。</span><span class="sxs-lookup"><span data-stu-id="6635a-482">The type of unit being purchased.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="6635a-483">DiscountDetails</span><span class="sxs-lookup"><span data-stu-id="6635a-483">DiscountDetails</span></span></td>
<td><p><span data-ttu-id="6635a-484">任何適用折扣的說明。</span><span class="sxs-lookup"><span data-stu-id="6635a-484">An explanation of any applicable discount.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="6635a-485">子總計</span><span class="sxs-lookup"><span data-stu-id="6635a-485">Sub Total</span></span></td>
<td><p><span data-ttu-id="6635a-486">稅前總計。</span><span class="sxs-lookup"><span data-stu-id="6635a-486">Total before tax.</span></span> <span data-ttu-id="6635a-487">如果有折扣，可檢查小計是否和預期的總金額相符。</span><span class="sxs-lookup"><span data-stu-id="6635a-487">Checks that your subtotal matches your expected total, in case of a discount.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="6635a-488">稅金總計</span><span class="sxs-lookup"><span data-stu-id="6635a-488">Tax Total</span></span></td>
<td><p><span data-ttu-id="6635a-489">稅金費用 (根據您所在市場的稅金規則與特定情況)。</span><span class="sxs-lookup"><span data-stu-id="6635a-489">Tax amount charge, based on your market's tax rules and specific circumstances.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="6635a-490">總計</span><span class="sxs-lookup"><span data-stu-id="6635a-490">Total</span></span></td>
<td><p><span data-ttu-id="6635a-491">稅後總計。</span><span class="sxs-lookup"><span data-stu-id="6635a-491">Total after tax.</span></span> <span data-ttu-id="6635a-492">檢查發票中是否向您收取稅金。</span><span class="sxs-lookup"><span data-stu-id="6635a-492">Checks if you are charged tax in the invoice.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="6635a-493">Currency</span><span class="sxs-lookup"><span data-stu-id="6635a-493">Currency</span></span></td>
<td><p><span data-ttu-id="6635a-494">貨幣類型。</span><span class="sxs-lookup"><span data-stu-id="6635a-494">Currency type.</span></span> <span data-ttu-id="6635a-495">每一帳單實體都只有一種貨幣。</span><span class="sxs-lookup"><span data-stu-id="6635a-495">Each billing entity has only one currency.</span></span> <span data-ttu-id="6635a-496">檢查是否與您的第一張發票相符，然後在進行任何重大帳單平台更新之後檢查。</span><span class="sxs-lookup"><span data-stu-id="6635a-496">Check that it matches your first invoice and then after any major billing platform update.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="6635a-497">替代識別碼</span><span class="sxs-lookup"><span data-stu-id="6635a-497">AlternateID</span></span></td>
<td><p><span data-ttu-id="6635a-498">訂單識別碼的替代識別碼。</span><span class="sxs-lookup"><span data-stu-id="6635a-498">An alternate identifier to an order ID.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="6635a-499">BillingFrequency</span><span class="sxs-lookup"><span data-stu-id="6635a-499">BillingFrequency</span></span></td>
<td><p> <span data-ttu-id="6635a-500">當每月計費啟用時，會顯示每月。</span><span class="sxs-lookup"><span data-stu-id="6635a-500">Displays monthly when monthly billing is enabled.</span></span> <span data-ttu-id="6635a-501">否則為空白。</span><span class="sxs-lookup"><span data-stu-id="6635a-501">Otherwise blank.</span></span> </p></td>
</tr>

</tbody>
</table>


## <a href="" id="dailyratedusagefields"></a><span data-ttu-id="6635a-502">每日評分的使用量檔案欄位</span><span class="sxs-lookup"><span data-stu-id="6635a-502">Daily-rated usage file fields</span></span>


<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th><span data-ttu-id="6635a-503">Column</span><span class="sxs-lookup"><span data-stu-id="6635a-503">Column</span></span></th>
<th><span data-ttu-id="6635a-504">說明</span><span class="sxs-lookup"><span data-stu-id="6635a-504">Description</span></span></th>
</tr>
</thead>
<tbody>

<tr class="odd">
<td><span data-ttu-id="6635a-505">PartnerId</span><span class="sxs-lookup"><span data-stu-id="6635a-505">PartnerId</span></span></td>
<td><p><span data-ttu-id="6635a-506">合作夥伴識別碼 (GUID 格式)。</span><span class="sxs-lookup"><span data-stu-id="6635a-506">Partner ID, in GUID format.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="6635a-507">PartnerName</span><span class="sxs-lookup"><span data-stu-id="6635a-507">PartnerName</span></span></td>
<td><p><span data-ttu-id="6635a-508">合作夥伴名稱。</span><span class="sxs-lookup"><span data-stu-id="6635a-508">Partner Name.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="6635a-509">CustomerId</span><span class="sxs-lookup"><span data-stu-id="6635a-509">CustomerId</span></span></td>
<td><p><span data-ttu-id="6635a-510">用來識別客戶的唯一 Microsoft ID（GUID 格式）。</span><span class="sxs-lookup"><span data-stu-id="6635a-510">Unique Microsoft ID, in GUID format, used to identify the customer.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="6635a-511">CustomerCompanyName</span><span class="sxs-lookup"><span data-stu-id="6635a-511">CustomerCompanyName</span></span></td>
<td><p><span data-ttu-id="6635a-512">合作夥伴中心中回報的客戶組織名稱。</span><span class="sxs-lookup"><span data-stu-id="6635a-512">Customer's organization name as reported in Partner Center.</span></span> <span data-ttu-id="6635a-513">這在使用您的系統資訊對帳發票時非常重要。</span><span class="sxs-lookup"><span data-stu-id="6635a-513">This is very important for reconciling the invoice with your system information.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="6635a-514">CustomerDomainName</span><span class="sxs-lookup"><span data-stu-id="6635a-514">CustomerDomainName</span></span></td>
<td><p><span data-ttu-id="6635a-515">客戶的網域名稱。</span><span class="sxs-lookup"><span data-stu-id="6635a-515">The customer’s domain name.</span></span> <span data-ttu-id="6635a-516">目前的活動無法使用。</span><span class="sxs-lookup"><span data-stu-id="6635a-516">Not available for current activity.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="6635a-517">客戶國家/地區</span><span class="sxs-lookup"><span data-stu-id="6635a-517">Customer country</span></span></td>
<td><p><span data-ttu-id="6635a-518">客戶所在的國家/地區。</span><span class="sxs-lookup"><span data-stu-id="6635a-518">The country in which the customer is located.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="6635a-519">MPNID</span><span class="sxs-lookup"><span data-stu-id="6635a-519">MPNID</span></span></td>
<td><p><span data-ttu-id="6635a-520">雲端解決方案提供者合作夥伴的 MPN 識別碼。</span><span class="sxs-lookup"><span data-stu-id="6635a-520">MPN ID of the CSP partner.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="6635a-521">轉售商 MPNID</span><span class="sxs-lookup"><span data-stu-id="6635a-521">Reseller MPNID</span></span></td>
<td><p><span data-ttu-id="6635a-522">訂閱記錄中的經銷商 MPN 識別碼。</span><span class="sxs-lookup"><span data-stu-id="6635a-522">MPN ID of the reseller of record for the subscription.</span></span> <span data-ttu-id="6635a-523">目前的活動無法使用。</span><span class="sxs-lookup"><span data-stu-id="6635a-523">Not available for current activity.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="6635a-524">InvoiceNumber</span><span class="sxs-lookup"><span data-stu-id="6635a-524">InvoiceNumber</span></span></td>
<td><p><span data-ttu-id="6635a-525">交易的指定位置顯示的發票號碼。</span><span class="sxs-lookup"><span data-stu-id="6635a-525">Invoice number where the specified transaction appears.</span></span> <span data-ttu-id="6635a-526">目前的活動無法使用。</span><span class="sxs-lookup"><span data-stu-id="6635a-526">Not available for current activity.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="6635a-527">ProductId</span><span class="sxs-lookup"><span data-stu-id="6635a-527">ProductId</span></span></td>
<td><p><span data-ttu-id="6635a-528">產品的識別碼。</span><span class="sxs-lookup"><span data-stu-id="6635a-528">The ID for the product.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="6635a-529">SkuId</span><span class="sxs-lookup"><span data-stu-id="6635a-529">SkuId</span></span></td>
<td><p><span data-ttu-id="6635a-530">特定 SKU 的識別碼。</span><span class="sxs-lookup"><span data-stu-id="6635a-530">The ID for a particular SKU.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="6635a-531">AvailabilityId</span><span class="sxs-lookup"><span data-stu-id="6635a-531">AvailabilityId</span></span></td>
<td><p><span data-ttu-id="6635a-532">特定可用性的識別碼。</span><span class="sxs-lookup"><span data-stu-id="6635a-532">The ID for a particular Availability.</span></span> <span data-ttu-id="6635a-533">「可用性」是指特定 SKU 是否可供特定的國家/地區、貨幣、行業區段等等購買。</span><span class="sxs-lookup"><span data-stu-id="6635a-533">“Availability” refers to whether or not a particular SKU is available for purchase for the given country, currency, industry segment, etc.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="6635a-534">SKU 名稱</span><span class="sxs-lookup"><span data-stu-id="6635a-534">SKU Name</span></span></td>
<td><p><span data-ttu-id="6635a-535">特定 SKU 的標題。</span><span class="sxs-lookup"><span data-stu-id="6635a-535">The title for a particular SKU.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="6635a-536">PublisherName</span><span class="sxs-lookup"><span data-stu-id="6635a-536">PublisherName</span></span></td>
<td><p><span data-ttu-id="6635a-537">發行者的名稱。</span><span class="sxs-lookup"><span data-stu-id="6635a-537">The name of the publisher.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="6635a-538">PublisherID</span><span class="sxs-lookup"><span data-stu-id="6635a-538">PublisherID</span></span></td>
<td><p><span data-ttu-id="6635a-539">發行者的識別碼（以 GUID 格式）。</span><span class="sxs-lookup"><span data-stu-id="6635a-539">The ID of the publisher, in GUID format.</span></span> <span data-ttu-id="6635a-540">目前的活動無法使用。</span><span class="sxs-lookup"><span data-stu-id="6635a-540">Not available for current activity.</span></span></p></td>
</tr>

<tr class=”even">
<td><span data-ttu-id="6635a-541">訂用帳戶描述</span><span class="sxs-lookup"><span data-stu-id="6635a-541">Subscription Description</span></span></td>
<td><p><span data-ttu-id="6635a-542">客戶購買的服務優惠名稱，如價目表中所定義。</span><span class="sxs-lookup"><span data-stu-id="6635a-542">The name of the service offering purchased by the customer, as defined in the price list.</span></span> <span data-ttu-id="6635a-543">（這是優惠名稱的相同欄位）。</span><span class="sxs-lookup"><span data-stu-id="6635a-543">(This is an identical field to Offer name).</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="6635a-544">[訂閱識別碼]</span><span class="sxs-lookup"><span data-stu-id="6635a-544">Subscription ID</span></span></td>
<td><p><span data-ttu-id="6635a-545">訂閱在 Microsoft 帳單平台中的唯一識別碼。</span><span class="sxs-lookup"><span data-stu-id="6635a-545">Unique identifier for a subscription in the Microsoft billing platform.</span></span> <span data-ttu-id="6635a-546">可在連絡支援時方便識別訂閱，但不是用於對帳。</span><span class="sxs-lookup"><span data-stu-id="6635a-546">May be useful to identify the subscription when contacting support but not for reconciliation.</span></span> <span data-ttu-id="6635a-547">這與合作夥伴管理主控台上的訂閱識別碼不一樣。</span><span class="sxs-lookup"><span data-stu-id="6635a-547">This is not the same as the Subscription ID on the Partner Admin Console.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="6635a-548">ChargeStartDate</span><span class="sxs-lookup"><span data-stu-id="6635a-548">ChargeStartDate</span></span></td>
<td><p><span data-ttu-id="6635a-549">計費週期的開始日期，當顯示之前未收取潛在使用量資料費用的日期時除外 (從前一個計費週期開始)。</span><span class="sxs-lookup"><span data-stu-id="6635a-549">Start date of billing cycle except when presenting dates of previously uncharged latent usage data (from previous bill cycle).</span></span> <span data-ttu-id="6635a-550">時間一律是一天的開始時間 (0:00)。</span><span class="sxs-lookup"><span data-stu-id="6635a-550">The time is always the beginning of the day, 0:00.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="6635a-551">ChargeEndDate</span><span class="sxs-lookup"><span data-stu-id="6635a-551">ChargeEndDate</span></span></td>
<td><p><span data-ttu-id="6635a-552">計費週期的結束日期，當顯示之前未收取潛在使用量資料費用的日期時除外 (從前一個計費週期開始)。</span><span class="sxs-lookup"><span data-stu-id="6635a-552">End date of billing cycle except when presenting dates of previously uncharged latent usage data (from previous bill cycle).</span></span> <span data-ttu-id="6635a-553">時間一律是一天的結束時間 (23:59)。</span><span class="sxs-lookup"><span data-stu-id="6635a-553">The time is always the end of the day, 23:59.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="6635a-554">使用日期</span><span class="sxs-lookup"><span data-stu-id="6635a-554">Usage Date</span></span></td>
<td><p><span data-ttu-id="6635a-555">服務使用量的日期。</span><span class="sxs-lookup"><span data-stu-id="6635a-555">Date of service usage.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="6635a-556">計量類型</span><span class="sxs-lookup"><span data-stu-id="6635a-556">Meter Type</span></span></td>
<td><p><span data-ttu-id="6635a-557">計量的類型。</span><span class="sxs-lookup"><span data-stu-id="6635a-557">The type of meter.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="6635a-558">計量類別</span><span class="sxs-lookup"><span data-stu-id="6635a-558">Meter Category</span></span></td>
<td><p><span data-ttu-id="6635a-559">使用的最上層服務。</span><span class="sxs-lookup"><span data-stu-id="6635a-559">The top-level service for the usage.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="6635a-560">計量識別碼</span><span class="sxs-lookup"><span data-stu-id="6635a-560">Meter Id</span></span></td>
<td><p><span data-ttu-id="6635a-561">所使用之計量的識別碼。</span><span class="sxs-lookup"><span data-stu-id="6635a-561">The ID for the meter being used.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="6635a-562">計量子類別</span><span class="sxs-lookup"><span data-stu-id="6635a-562">Meter Sub-category</span></span></td>
<td><p><span data-ttu-id="6635a-563">可能會影響費率的 Azure 服務類型。</span><span class="sxs-lookup"><span data-stu-id="6635a-563">The type of Azure service that can affect the rate.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="6635a-564">計量名稱</span><span class="sxs-lookup"><span data-stu-id="6635a-564">Meter Name</span></span></td>
<td><p><span data-ttu-id="6635a-565">所耗用計量的測量單位。</span><span class="sxs-lookup"><span data-stu-id="6635a-565">The unit of measure for the meter being consumed.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="6635a-566">計量區域</span><span class="sxs-lookup"><span data-stu-id="6635a-566">Meter Region</span></span></td>
<td><p><span data-ttu-id="6635a-567">此欄可識別適用及填入此項目之服務地區內的資料中心的位置。</span><span class="sxs-lookup"><span data-stu-id="6635a-567">This column identifies the location of a data center within the region for services where this is applicable and populated.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="6635a-568">單位</span><span class="sxs-lookup"><span data-stu-id="6635a-568">Unit</span></span></td>
<td><p><span data-ttu-id="6635a-569">資源名稱的單位。</span><span class="sxs-lookup"><span data-stu-id="6635a-569">The unit of the resource Name.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="6635a-570">已耗用數量</span><span class="sxs-lookup"><span data-stu-id="6635a-570">Consumed Quantity</span></span></td>
<td><p><span data-ttu-id="6635a-571">報表期間耗用的服務量 (小時、GB 等等)</span><span class="sxs-lookup"><span data-stu-id="6635a-571">The amount of service consumed (hours, GB, etc.) during the reporting period.</span></span> <span data-ttu-id="6635a-572">同時包括先前報表期間任何未計費的使用量。</span><span class="sxs-lookup"><span data-stu-id="6635a-572">Also includes any unbilled usage from previous reporting periods.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="6635a-573">資源位置</span><span class="sxs-lookup"><span data-stu-id="6635a-573">Resource Location</span></span></td>
<td><p><span data-ttu-id="6635a-574">正在執行計量的資料中心。</span><span class="sxs-lookup"><span data-stu-id="6635a-574">The datacenter where the meter is running.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="6635a-575">已使用服務</span><span class="sxs-lookup"><span data-stu-id="6635a-575">Consumed Service</span></span></td>
<td><p><span data-ttu-id="6635a-576">您所使用的 Azure 平臺服務。</span><span class="sxs-lookup"><span data-stu-id="6635a-576">The Azure platform service that you used.</span></span></p></td>
</tr>


<tr class="even">
<td><span data-ttu-id="6635a-577">資源 URI</span><span class="sxs-lookup"><span data-stu-id="6635a-577">Resource URI</span></span></td>
<td><p><span data-ttu-id="6635a-578">所使用資源的 URI。</span><span class="sxs-lookup"><span data-stu-id="6635a-578">The URI of the resource being used.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="6635a-579">收費類型</span><span class="sxs-lookup"><span data-stu-id="6635a-579">Charge type</span></span></td>
<td><p><span data-ttu-id="6635a-580">費用或調整的類型。</span><span class="sxs-lookup"><span data-stu-id="6635a-580">The type of charge or adjustment.</span></span> <span data-ttu-id="6635a-581">目前的活動無法使用。</span><span class="sxs-lookup"><span data-stu-id="6635a-581">Not available for current activity.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="6635a-582">單價</span><span class="sxs-lookup"><span data-stu-id="6635a-582">Unit price</span></span></td>
<td><p><span data-ttu-id="6635a-583">每份授權的價格，在購買時于價目表中發行。</span><span class="sxs-lookup"><span data-stu-id="6635a-583">Price per license, as published in the pricelist at the time of purchase.</span></span> <span data-ttu-id="6635a-584">請確定這與對帳期間儲存在您帳單系統中的資訊相符。</span><span class="sxs-lookup"><span data-stu-id="6635a-584">Ensure this matches the information stored in your billing system during reconciliation.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="6635a-585">數量</span><span class="sxs-lookup"><span data-stu-id="6635a-585">Quantity</span></span></td>
<td><p><span data-ttu-id="6635a-586">授權數目。</span><span class="sxs-lookup"><span data-stu-id="6635a-586">Number of licenses.</span></span> <span data-ttu-id="6635a-587">請確定這與對帳期間儲存在您帳單系統中的資訊相符。</span><span class="sxs-lookup"><span data-stu-id="6635a-587">Ensure this matches the information stored in your billing system during reconciliation.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="6635a-588">單位類型</span><span class="sxs-lookup"><span data-stu-id="6635a-588">Unit type</span></span></td>
<td><p><span data-ttu-id="6635a-589">計量計費的單位類型。</span><span class="sxs-lookup"><span data-stu-id="6635a-589">The type of unit the meter is charged in.</span></span> <span data-ttu-id="6635a-590">目前的活動無法使用。</span><span class="sxs-lookup"><span data-stu-id="6635a-590">Not available for current activity.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="6635a-591">計費預付稅</span><span class="sxs-lookup"><span data-stu-id="6635a-591">Billing pre tax</span></span></td>
<td><p><span data-ttu-id="6635a-592">稅金之前的總金額。</span><span class="sxs-lookup"><span data-stu-id="6635a-592">Total amount before taxes.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="6635a-593">計費貨幣</span><span class="sxs-lookup"><span data-stu-id="6635a-593">Billing currency</span></span></td>
<td><p><span data-ttu-id="6635a-594">客戶地理區域中的貨幣</span><span class="sxs-lookup"><span data-stu-id="6635a-594">The currency in the customer’s geographic region</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="6635a-595">定價稅前總計</span><span class="sxs-lookup"><span data-stu-id="6635a-595">Pricing pretax total</span></span></td>
<td><p><span data-ttu-id="6635a-596">新增稅額前的價格。</span><span class="sxs-lookup"><span data-stu-id="6635a-596">The pricing before taxes are added.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="6635a-597">定價貨幣</span><span class="sxs-lookup"><span data-stu-id="6635a-597">Pricing currency</span></span></td>
<td><p><span data-ttu-id="6635a-598">價目表中的貨幣。</span><span class="sxs-lookup"><span data-stu-id="6635a-598">The currency in the pricelist.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="6635a-599">服務資訊1</span><span class="sxs-lookup"><span data-stu-id="6635a-599">Service Info 1</span></span></td>
<td><p><span data-ttu-id="6635a-600">於某一天佈建及使用的 ServiceBus 連線數目。</span><span class="sxs-lookup"><span data-stu-id="6635a-600">The number of ServiceBus connections that were provisioned and utilized on a given day.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="6635a-601">服務資訊2</span><span class="sxs-lookup"><span data-stu-id="6635a-601">Service Info 2</span></span></td>
<td><p><span data-ttu-id="6635a-602">舊版欄位，可捕捉選擇性的服務特定中繼資料。</span><span class="sxs-lookup"><span data-stu-id="6635a-602">A legacy field that captures optional service-specific metadata.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="6635a-603">其他資訊</span><span class="sxs-lookup"><span data-stu-id="6635a-603">Additional Info</span></span></td>
<td><p><span data-ttu-id="6635a-604">其他資料行中未涵蓋的任何其他資訊。</span><span class="sxs-lookup"><span data-stu-id="6635a-604">Any additional information not covered in other columns.</span></span></p></td>
</tr>

</tbody>
</table>


## <a href="" id="charge_types"></a><span data-ttu-id="6635a-605">發票與對帳檔案之間的對應費用</span><span class="sxs-lookup"><span data-stu-id="6635a-605">Mapping charges between an invoice and the reconciliation file</span></span>

<span data-ttu-id="6635a-606">您的發票提供費用摘要，而對帳檔案則提供包括費用類型等明細項目交易的詳細細項。</span><span class="sxs-lookup"><span data-stu-id="6635a-606">Your invoice provides a summary of charges, while your reconciliation file provides a detailed breakdown of line-item transactions, including charge types.</span></span>

<span data-ttu-id="6635a-607">若要交互參照發票和對帳檔案之間的費用金額，您可以使用 Microsoft Excel 篩選選項，在對帳檔案上依費用類型篩選，以便將發票費用對應到對帳檔案上的一組費用細項。</span><span class="sxs-lookup"><span data-stu-id="6635a-607">To cross-reference charge amounts between the invoice and reconciliation file, you can use Microsoft Excel's filter options to filter by charge types on the reconciliation file to map the invoice charges to a set of charge breakdowns on reconciliation file.</span></span>

<span data-ttu-id="6635a-608">用量型和授權型訂閱的對帳檔案只會顯示交易和費用的相關使用量 (耗用單位和相關的費用)。</span><span class="sxs-lookup"><span data-stu-id="6635a-608">Reconciliation files, both usage- and license-based, only show usage related transactions and charges (units consumed and related charges).</span></span> <span data-ttu-id="6635a-609">發票上顯示為「調整」的點數、折扣或退款不會出現在對帳檔案中。</span><span class="sxs-lookup"><span data-stu-id="6635a-609">One off credits, discounts or refunds which appear on the invoice as “Adjustments” are not shown in the reconciliation file.</span></span>

<span data-ttu-id="6635a-610">下表顯示發票區段和對帳檔案上可能會顯示之相關費用類型之間的對應。</span><span class="sxs-lookup"><span data-stu-id="6635a-610">The table below shows the mappings between an invoice section and associated charge types that might show up on the reconciliation files.</span></span> 

<table>
<tbody>
<tr>
<td>
<p><span data-ttu-id="6635a-611"><strong>發票費用描述</strong></span><span class="sxs-lookup"><span data-stu-id="6635a-611"><strong>Invoice charge description</strong></span></span></p>
</td>
<td>
<p><span data-ttu-id="6635a-612"><strong>對帳檔案費用描述（ChargeType 資料行）</strong></span><span class="sxs-lookup"><span data-stu-id="6635a-612"><strong>Reconciliation file charge description (ChargeType column)</strong></span></span></p>
</td>
<td>
<p><span data-ttu-id="6635a-613"><strong>這會產生什麼費用？</strong></span><span class="sxs-lookup"><span data-stu-id="6635a-613"><strong>What is this charge?</strong></span></span></p>
</td>
<td>
<p><span data-ttu-id="6635a-614"><strong>如何? 將這些 ChargeTypes 對應至發票？</strong></span><span class="sxs-lookup"><span data-stu-id="6635a-614"><strong>How do I map these ChargeTypes to the invoice?</strong></span></span></p>
</td>
</tr>
<tr>
<td rowspan="10">
<p><span data-ttu-id="6635a-615"><strong>以授權為基礎的費用</strong></span><span class="sxs-lookup"><span data-stu-id="6635a-615"><strong>License-based charges</strong></span></span></p>
</td>
<td>
<p><span data-ttu-id="6635a-616">啟用費用</span><span class="sxs-lookup"><span data-stu-id="6635a-616">Activation fee</span></span></p>
</td>
<td>
<p><span data-ttu-id="6635a-617">當客戶購買後使用訂閱時，向客戶收取的金額</span><span class="sxs-lookup"><span data-stu-id="6635a-617">The amount charged to the customer when they use the subscription after purchasing it</span></span></p>
</td>
<td rowspan="10">
<p><span data-ttu-id="6635a-618">從授權型檔案，加總 <strong>Amount</strong> 欄</span><span class="sxs-lookup"><span data-stu-id="6635a-618">From license-based file, sum the <strong>Amount</strong> column</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="6635a-619">取消費用</span><span class="sxs-lookup"><span data-stu-id="6635a-619">Cancel fee</span></span></p>
</td>
<td>
<p><span data-ttu-id="6635a-620">當關聯的基座變更時，按比例計算退款給客戶的費用</span><span class="sxs-lookup"><span data-stu-id="6635a-620">Prorated charges refunded to the customer when associated seats are changed</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="6635a-621">循環費用</span><span class="sxs-lookup"><span data-stu-id="6635a-621">Cycle fee</span></span></p>
</td>
<td>
<p><span data-ttu-id="6635a-622">訂閱的定期費用</span><span class="sxs-lookup"><span data-stu-id="6635a-622">Periodic charges for a subscription</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="6635a-623">循環執行個體 (依比例計算)</span><span class="sxs-lookup"><span data-stu-id="6635a-623">Cycle instance prorate</span></span></p>
</td>
<td>
<p><span data-ttu-id="6635a-624">當關聯的基座變更時，按比例計算向客戶收取的費用</span><span class="sxs-lookup"><span data-stu-id="6635a-624">Prorated charges assessed from the customer when associated seats are changed</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="6635a-625">取消時按比例計算費用</span><span class="sxs-lookup"><span data-stu-id="6635a-625">Prorate fees when cancel</span></span></p>
</td>
<td>
<p><span data-ttu-id="6635a-626">取消時服務未使用部分之按比例計算的退款</span><span class="sxs-lookup"><span data-stu-id="6635a-626">Prorated refund for unused portion of service upon cancellation</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="6635a-627">購買時按比例計算費用</span><span class="sxs-lookup"><span data-stu-id="6635a-627">Prorate fees when purchase</span></span></p>
</td>
<td>
<p><span data-ttu-id="6635a-628">使用年度計費時的訂用帳戶費用類型</span><span class="sxs-lookup"><span data-stu-id="6635a-628">The charge type for a subscription when using annual billing</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="6635a-629">購買費用</span><span class="sxs-lookup"><span data-stu-id="6635a-629">Purchase fee</span></span></p>
</td>
<td>
<p><span data-ttu-id="6635a-630">使用每月計費時的訂用帳戶費用類型</span><span class="sxs-lookup"><span data-stu-id="6635a-630">The charge type for a subscription when using monthly billing</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="6635a-631">續約時按比例計算費用</span><span class="sxs-lookup"><span data-stu-id="6635a-631">Prorate fee when renew</span></span></p>
</td>
<td>
<p><span data-ttu-id="6635a-632">訂閱續約時按比例計算的費用</span><span class="sxs-lookup"><span data-stu-id="6635a-632">Prorated fees upon subscription renewal</span></span></p>
</td>
</tr>
<tr>

<td>
<p><span data-ttu-id="6635a-633">續約費用</span><span class="sxs-lookup"><span data-stu-id="6635a-633">Renew fee</span></span></p>
</td>
<td>
<p><span data-ttu-id="6635a-634">訂閱續約時的費用</span><span class="sxs-lookup"><span data-stu-id="6635a-634">Charge for renewing a subscription</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="6635a-635">啟用時按比例計算費用</span><span class="sxs-lookup"><span data-stu-id="6635a-635">Prorate fees when activate</span></span></p>
</td>
<td>
<p><span data-ttu-id="6635a-636">從啟用到計費期間結束時按比例計算的費用</span><span class="sxs-lookup"><span data-stu-id="6635a-636">Prorated fees from activation until end of billing period</span></span></p>
</td>
</tr>



<tr>
<td rowspan="5">
<p><span data-ttu-id="6635a-637"><strong>一次性費用</strong></span><span class="sxs-lookup"><span data-stu-id="6635a-637"><strong>One-time Charges</strong></span></span></p>

</td>
<td>
<p><span data-ttu-id="6635a-638">新的</span><span class="sxs-lookup"><span data-stu-id="6635a-638">New</span></span></p>
</td>
<td>
<p><span data-ttu-id="6635a-639">在建立新購買時使用</span><span class="sxs-lookup"><span data-stu-id="6635a-639">Used when a new purchase is created</span></span></p>
</td>

<p></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="6635a-640">addQuantity</span><span class="sxs-lookup"><span data-stu-id="6635a-640">addQuantity</span></span></p>
</td>
<td>
<p><span data-ttu-id="6635a-641">用於原始購買的退款和增加後的新數量</span><span class="sxs-lookup"><span data-stu-id="6635a-641">Used in both the refund of the original purchase and the new quantity after increase</span></span></p>
</td>
</tr>

</tr>
<tr>
<td>
<p><span data-ttu-id="6635a-642">removeQuantity</span><span class="sxs-lookup"><span data-stu-id="6635a-642">removeQuantity</span></span></p>
</td>
<td>
<p><span data-ttu-id="6635a-643">用於原始購買的退款和減少後的新數量</span><span class="sxs-lookup"><span data-stu-id="6635a-643">Used in both the refund of the original purchase and the new quantity after decrease</span></span></p>
</td>
</tr>

</tr>
<tr>
<td>
<p><span data-ttu-id="6635a-644">[取消]</span><span class="sxs-lookup"><span data-stu-id="6635a-644">Cancel</span></span></p>
</td>
<td>
<p><span data-ttu-id="6635a-645">在取消訂用帳戶時使用</span><span class="sxs-lookup"><span data-stu-id="6635a-645">Used when a subscription is cancelled</span></span></p>
</td>
</tr>

</tr>
<tr>
<td>
<p><span data-ttu-id="6635a-646">轉換</span><span class="sxs-lookup"><span data-stu-id="6635a-646">Convert</span></span></p>
</td>
<td>
<p><span data-ttu-id="6635a-647">當授權已升級，但基座數目維持不變時使用</span><span class="sxs-lookup"><span data-stu-id="6635a-647">Used when a license is upgraded but the number of seats remains unchanged</span></span></p>
</td>
</tr>

<tr>
<td rowspan="2">
<p><span data-ttu-id="6635a-648"><strong>使用費用</strong></span><span class="sxs-lookup"><span data-stu-id="6635a-648"><strong>Usage Charges</strong></span></span></p>
</td>
<td>
<p><span data-ttu-id="6635a-649">取消時的存取用量費用</span><span class="sxs-lookup"><span data-stu-id="6635a-649">Assess usage fee when cancel</span></span></p>
</td>
<td>
<p><span data-ttu-id="6635a-650">在目前計費期間中取消時，未支付之使用量的存取用量費用</span><span class="sxs-lookup"><span data-stu-id="6635a-650">Access usage fee upon cancellation for unpaid usage during the current billing period</span></span></p>
</td>
<td rowspan="2">
<p><span data-ttu-id="6635a-651">從用量型檔案，加總 <strong>PretaxCharges</strong> 欄</span><span class="sxs-lookup"><span data-stu-id="6635a-651">From usage-based file, sum the <strong>PretaxCharges</strong> column</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="6635a-652">目前週期的存取用量費用</span><span class="sxs-lookup"><span data-stu-id="6635a-652">Assess usage fee for current cycle</span></span></p>
</td>
<td>
<p><span data-ttu-id="6635a-653">目前計費期間的存取用量費用</span><span class="sxs-lookup"><span data-stu-id="6635a-653">Access usage fee for the current billing period</span></span></p>
</td>
</tr>

<tr>
<td>
<p><span data-ttu-id="6635a-654"><strong>信用</strong></span><span class="sxs-lookup"><span data-stu-id="6635a-654"><strong>Credits</strong></span></span></p>
</td>
<td>
<p><span data-ttu-id="6635a-655">明細項目位移</span><span class="sxs-lookup"><span data-stu-id="6635a-655">Offset a line item</span></span></p>
</td>
<td>
<p><span data-ttu-id="6635a-656">明細項目的部分或完整退款 (含稅)</span><span class="sxs-lookup"><span data-stu-id="6635a-656">Partial or whole refund to a line item, including taxes</span></span></p>
</td>
<td>
<p><span data-ttu-id="6635a-657">從授權型檔案，加總 <strong>TotalForCustomer</strong> 欄</span><span class="sxs-lookup"><span data-stu-id="6635a-657">From license-based file, sum the <strong>TotalForCustomer</strong> column</span></span></p>
<p><span data-ttu-id="6635a-658">從用量型檔案，加總 <strong>PostTaxTotal</strong> 欄</span><span class="sxs-lookup"><span data-stu-id="6635a-658">From usage-based file, sum the <strong>PostTaxTotal</strong> column</span></span></p>
</td>
</tr>
<tr>
<td rowspan="4">
<p><span data-ttu-id="6635a-659"><strong>以使用量為基礎的折扣</strong></span><span class="sxs-lookup"><span data-stu-id="6635a-659"><strong>Usage-based discounts</strong></span></span></p>
</td>
<td>
<p><span data-ttu-id="6635a-660">啟用折扣</span><span class="sxs-lookup"><span data-stu-id="6635a-660">Activation discount</span></span></p>
</td>
<td>
<p><span data-ttu-id="6635a-661">啟用訂閱時套用的折扣</span><span class="sxs-lookup"><span data-stu-id="6635a-661">Discount applied when subscription activated</span></span></p>
</td>

<td rowspan="4">
<p><span data-ttu-id="6635a-662">從用量型檔案，加總 <strong>PretaxCharges</strong> 欄</span><span class="sxs-lookup"><span data-stu-id="6635a-662">From usage-based file, sum the <strong>PretaxCharges</strong> column</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="6635a-663">循環折扣</span><span class="sxs-lookup"><span data-stu-id="6635a-663">Cycle discount</span></span></p>
</td>
<td>
<p><span data-ttu-id="6635a-664">套用至定期費用的折扣</span><span class="sxs-lookup"><span data-stu-id="6635a-664">Discount applied on periodic charges</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="6635a-665">續約折扣</span><span class="sxs-lookup"><span data-stu-id="6635a-665">Renew discount</span></span></p>
</td>
<td>
<p><span data-ttu-id="6635a-666">訂閱續約時套用的折扣</span><span class="sxs-lookup"><span data-stu-id="6635a-666">Discount applied when subscription renewed</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="6635a-667">取消折扣</span><span class="sxs-lookup"><span data-stu-id="6635a-667">Cancel discount</span></span></p>
</td>
<td>
<p><span data-ttu-id="6635a-668">折扣取消時收取的費用</span><span class="sxs-lookup"><span data-stu-id="6635a-668">Charges applied when discounts cancelled</span></span></p>
</td>
</tr>


<tr>
<td>
<p><span data-ttu-id="6635a-669"><strong>以授權為基礎的折扣</strong></span><span class="sxs-lookup"><span data-stu-id="6635a-669"><strong>License-based discounts</strong></span></span></p>
</td>
<td>
<p><span data-ttu-id="6635a-670"><em>可套用至多個費用類型</em></span><span class="sxs-lookup"><span data-stu-id="6635a-670"><em>May be applied to multiple charge types</em></span></span></p>
</td>
<td>
<p></p>
</td>
<td>
<p><span data-ttu-id="6635a-671">從授權型檔案，加總 <strong>TotalOtherDiscount</strong> 欄</span><span class="sxs-lookup"><span data-stu-id="6635a-671">From license-based file, sum the <strong>TotalOtherDiscount</strong> column</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="6635a-672"><strong>稅金</strong>&nbsp;或&nbsp;<strong>加值稅</strong></span><span class="sxs-lookup"><span data-stu-id="6635a-672"><strong>Taxes</strong>&nbsp;or&nbsp;<strong>VAT</strong></span></span></p>
</td>
<td>
<p><span data-ttu-id="6635a-673"><em>可套用至多個費用類型</em></span><span class="sxs-lookup"><span data-stu-id="6635a-673"><em>May be applied to multiple charge types</em></span></span></p>
<p><span data-ttu-id="6635a-674"><em>例外狀況： &quot;Offset &quot; 已包含稅金的明細專案。請參閱上方的信用額度。</em></span><span class="sxs-lookup"><span data-stu-id="6635a-674"><em>Exception: &quot;Offset a line item&quot; already includes taxes. See Credits, above.</em></span></span></p>
</td>
<td>
<p><span data-ttu-id="6635a-675">稅金或加值稅 (VAT)</span><span class="sxs-lookup"><span data-stu-id="6635a-675">Taxes or value-added taxes (VAT)</span></span></p>
</td>
<td>
<p><span data-ttu-id="6635a-676">從授權型檔案，加總 <strong>Tax</strong> 欄</span><span class="sxs-lookup"><span data-stu-id="6635a-676">From license-based file, sum the <strong>Tax</strong> column</span></span></p>
<p><span data-ttu-id="6635a-677">從用量型檔案，加總 <strong>TaxAmount</strong> 欄</span><span class="sxs-lookup"><span data-stu-id="6635a-677">From usage-based file, sum the <strong>TaxAmount</strong> column</span></span></p>
</td>
</tr>
</tbody>
</table>
<p>&nbsp;</p>
