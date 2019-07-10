---
title: 使用對帳檔案 | 合作夥伴中心
ms.topic: article
ms.date: 07/08/2019
description: 在計費週期中的每個收費詳細的明細項目檢視，請從合作夥伴中心下載的對帳檔案。
ms.assetid: FA6A6FCB-2597-44E7-93F8-8D1DD35D52EA
author: LauraBrenner
ms.author: labrenne
ms.localizationpriority: medium
ms.openlocfilehash: 83be47cd9963d7e5f14b6c670cd57a8ab1d54011
ms.sourcegitcommit: 66afdaa662cfad217e29ba1f9e3a9ffd4349112f
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 07/09/2019
ms.locfileid: "67694930"
---
# <a name="use-the-reconciliation-files"></a><span data-ttu-id="b6a8d-103">使用對帳檔案</span><span class="sxs-lookup"><span data-stu-id="b6a8d-103">Use the reconciliation files</span></span>

<span data-ttu-id="b6a8d-104">**適用於**</span><span class="sxs-lookup"><span data-stu-id="b6a8d-104">**Applies to**</span></span>

-  <span data-ttu-id="b6a8d-105">合作夥伴中心</span><span class="sxs-lookup"><span data-stu-id="b6a8d-105">Partner Center</span></span>
-  <span data-ttu-id="b6a8d-106">Microsoft Cloud for US Government 適用的合作夥伴中心</span><span class="sxs-lookup"><span data-stu-id="b6a8d-106">Partner Center for Microsoft Cloud for US Government</span></span>


<span data-ttu-id="b6a8d-107">在計費週期中的每個收費詳細的明細項目檢視，請從合作夥伴中心下載的對帳檔案。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-107">For a detailed line-item view of each charge in a billing cycle, download the reconciliation files from Partner Center.</span></span> <span data-ttu-id="b6a8d-108">詳細資料包括每個客戶的訂閱費用，以及詳細事件 (例如，期中增加訂閱基座)。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-108">The details include charges for each customer's subscriptions, and detailed events (such as a mid-term addition of seats to a subscription).</span></span>

## <a name="formatting-issues"></a><span data-ttu-id="b6a8d-109">格式化問題</span><span class="sxs-lookup"><span data-stu-id="b6a8d-109">Formatting issues</span></span>

<span data-ttu-id="b6a8d-110">有時候您偵查的檔案可能會有格式問題。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-110">Occasionally your recon file might have formatting issues.</span></span> <span data-ttu-id="b6a8d-111">（這種情形，例如，如果未使用 EN-US 地區設定。）請遵循下列步驟來修正這些問題。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-111">(This can happen, for example, if the EN-US locale is not used.) Follow the steps below to fix these issues.</span></span> 

<ol>
<li><span data-ttu-id="b6a8d-112">在 Excel 中開啟.csv 檔案，並選取第一個資料行。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-112">Open the .csv file in Excel, and select the first column.</span></span> <span data-ttu-id="b6a8d-113">在功能區中，選取<strong>資料</strong>，然後選取<strong>資料行的文字</strong>。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-113">On the ribbon, select <strong>Data</strong>, and then select <strong>Text to Columns</strong>.</span></span></li>

<li><span data-ttu-id="b6a8d-114">在 [文字轉換為資料行精靈，選取<strong>分隔的檔案類型</strong>，然後選取<strong>下一步]</strong>。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-114">In the Convert Text to Columns Wizard, select <strong>Delimited file type</strong>, and then select <strong>Next</strong>.</span></span></li> 

<li><span data-ttu-id="b6a8d-115">在 [分隔符號] 欄位中，選取<strong>逗號</strong>。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-115">In the Delimeters field, select <strong>Comma</strong>.</span></span> <span data-ttu-id="b6a8d-116">如果 <strong>索引標籤</strong>是已選取，您可以將它保留。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-116">If <strong>Tab</strong> is already selected, you can leave it.</span></span> <span data-ttu-id="b6a8d-117">選取 <strong>\[下一步\]</strong>。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-117">Select <strong>Next</strong>.</span></span></li>

<li><span data-ttu-id="b6a8d-118">在 資料行的資料格式 欄位中，選取<strong>日期：MDY</strong>，然後選取<strong>下一步</strong>。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-118">In the Column data format field, select <strong>Date: MDY</strong>, and then select <strong>Next</strong>.</span></span></li> 

<li><span data-ttu-id="b6a8d-119">在 [資料行的資料格式] 欄位中，選取<strong>文字</strong>的所有 amount 資料行，然後選取<strong>完成</strong>。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-119">In the Column data format field, select <strong>Text</strong> for all amount columns, and then select <strong>Finish</strong>.</span></span></li>
</ol>

## <a name="downloading-a-large-recon-file"></a><span data-ttu-id="b6a8d-120">下載大型的偵察檔案</span><span class="sxs-lookup"><span data-stu-id="b6a8d-120">Downloading a large recon file</span></span>

<span data-ttu-id="b6a8d-121">偵察檔案可以變得非常大，而且有時候很難進行下載。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-121">Recon files can grow very large and are sometimes difficult to download.</span></span> <span data-ttu-id="b6a8d-122">為了下載大型的偵察檔案的 PowerShell 指令碼，請參閱[取得發票明細項目](https://docs.microsoft.com/en-us/partner-center/develop/get-invoiceline-items)。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-122">For a PowerShell script to help download large recon files, see [Get invoice line items](https://docs.microsoft.com/en-us/partner-center/develop/get-invoiceline-items).</span></span>

## <a href="" id="itemizebypartner"></a><span data-ttu-id="b6a8d-123">由合作夥伴條列</span><span class="sxs-lookup"><span data-stu-id="b6a8d-123">Itemize by partner</span></span>


<span data-ttu-id="b6a8d-124">間接模型合作夥伴可以在授權型及用量型對帳檔案中使用這些額外欄位，以便依經銷商詳細列舉。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-124">Partners in the indirect model can use these additional fields in both license-based and usage-based reconciliation files to itemize by reseller.</span></span>

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th><span data-ttu-id="b6a8d-125">MPN 識別碼</span><span class="sxs-lookup"><span data-stu-id="b6a8d-125">MPN ID</span></span></th>
<th><span data-ttu-id="b6a8d-126">描述</span><span class="sxs-lookup"><span data-stu-id="b6a8d-126">Description</span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="b6a8d-127">MPN 識別碼</span><span class="sxs-lookup"><span data-stu-id="b6a8d-127">MPN ID</span></span></td>
<td><p><span data-ttu-id="b6a8d-128">CSP 合作夥伴 (直接或間接) 的 Microsoft 合作夥伴網路 (MPN) 識別碼。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-128">The Microsoft Partner Network (MPN) ID of the CSP partner (direct or indirect).</span></span></p></td>
</tr>
<tr class="even">
<td><span data-ttu-id="b6a8d-129">經銷商 MPN 識別碼</span><span class="sxs-lookup"><span data-stu-id="b6a8d-129">Reseller MPN ID</span></span></td>
<td><p><span data-ttu-id="b6a8d-130">只會出現在間接模型合作夥伴的對帳檔案上。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-130">Only appears on reconciliation files for partners in the indirect model.</span></span></p>
<p><span data-ttu-id="b6a8d-131">訂閱記錄中的經銷商 MPN 識別碼。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-131">The MPN ID of the reseller of record for the subscription.</span></span> <span data-ttu-id="b6a8d-132">這會對應到合作夥伴中心中針對特定訂閱列出的經銷商識別碼。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-132">This corresponds to the reseller ID listed for the specific subscription in Partner Center.</span></span></p>
<p><span data-ttu-id="b6a8d-133">干支檢視或更新的轉銷商，從合作夥伴中心 功能表中，選取<strong>客戶</strong>，然後從清單中選擇客戶。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-133">eTo view or update the reseller, from the Partner Center menu, select <strong>Customers</strong>, then choose the customer from the list.</span></span> <span data-ttu-id="b6a8d-134">在客戶功能表中，選取 \[訂閱\]，從清單中選擇訂閱。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-134">In the customer menu, select <strong>Subscriptions</strong>, choose the subscription from the list.</span></span> <span data-ttu-id="b6a8d-135">選取 \[更新\] 以變更 \[經銷商 (MPN 識別碼)\]。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-135">Select <strong>update</strong> to change the <strong>Reseller (MPN ID)</strong>.</span></span></p>
<p><span data-ttu-id="b6a8d-136">如果雲端解決方案提供者合作夥伴直接向客戶銷售訂閱，他們的 MPN 識別碼將會以 MPN 識別碼和經銷商 MPN 識別碼的形式列出兩次。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-136">If a CSP partner sold the subscription directly to the customer, their MPN ID is listed twice, as both the MPN ID and the Reseller MPN ID.</span></span></p>
<p><span data-ttu-id="b6a8d-137">如果雲端解決方案提供者合作夥伴具有沒有 MPN 識別碼的經銷商，這個值將會改成設為合作夥伴的 MPN 識別碼。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-137">If a CSP partner has a reseller with no MPN ID, this value is set to the partner’s MPN ID instead.</span></span></p>
<p><span data-ttu-id="b6a8d-138">如果雲端解決方案提供者合作夥伴移除經銷商識別碼，這個值將會設為 -1。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-138">If the CSP partner removes a reseller ID, this value will be set to -1.</span></span></p></td>
</tr>
</tbody>
</table>

 

## <a href="" id="licensebasedfiles"></a> <span data-ttu-id="b6a8d-139">以授權為基礎的檔案欄位</span><span class="sxs-lookup"><span data-stu-id="b6a8d-139">License-based file fields</span></span>


<span data-ttu-id="b6a8d-140">若要針對您對客戶訂單的費用來對帳，請比較對帳檔案中的 Syndication\_Partner\_Subscription\_Number 與合作夥伴中心的訂閱識別碼。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-140">To reconcile your charges against your customer's orders, compare the Syndication\_Partner\_Subscription\_Number from the reconciliation file against the Subscription ID from Partner Center.</span></span>

<table>
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<tbody>
<tr class="odd">
<td><span data-ttu-id="b6a8d-141"><strong>資料行</strong></span><span class="sxs-lookup"><span data-stu-id="b6a8d-141"><strong>Column</strong></span></span></td>
<td><span data-ttu-id="b6a8d-142"><strong>描述</strong></span><span class="sxs-lookup"><span data-stu-id="b6a8d-142"><strong>Description</strong></span></span></td>
<td><span data-ttu-id="b6a8d-143"><strong>範例值</strong></span><span class="sxs-lookup"><span data-stu-id="b6a8d-143"><strong>Sample Value</strong></span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="b6a8d-144">PartnerId</span><span class="sxs-lookup"><span data-stu-id="b6a8d-144">PartnerId</span></span></td>
<td><p><span data-ttu-id="b6a8d-145">特定帳單實體的唯一識別碼 (GUID 格式)。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-145">Unique identifier for a specific billing entity, in GUID format.</span></span> <span data-ttu-id="b6a8d-146">對帳時不需要，但可能是很有用的資訊。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-146">Not required for reconciliation, however may be useful information.</span></span> <span data-ttu-id="b6a8d-147">在所有資料列中都是如此。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-147">Same in all rows.</span></span></p></td>
<td><span data-ttu-id="b6a8d-148">8ddd03642-test-test-test-46b58d356b4e</span><span class="sxs-lookup"><span data-stu-id="b6a8d-148">8ddd03642-test-test-test-46b58d356b4e</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="b6a8d-149">CustomerID</span><span class="sxs-lookup"><span data-stu-id="b6a8d-149">CustomerID</span></span></td>
<td><p><span data-ttu-id="b6a8d-150">用來識別客戶的唯一 Microsoft ID（GUID 格式）。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-150">Unique Microsoft ID, in GUID format, used to identify the customer.</span></span></p></td>
<td><span data-ttu-id="b6a8d-151">12ABCD34-001A-BCD2-987C-3210ABCD5678</span><span class="sxs-lookup"><span data-stu-id="b6a8d-151">12ABCD34-001A-BCD2-987C-3210ABCD5678</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="b6a8d-152">OrderID</span><span class="sxs-lookup"><span data-stu-id="b6a8d-152">OrderID</span></span></td>
<td><p><span data-ttu-id="b6a8d-153">訂單在 Microsoft 帳單平台中的唯一識別碼。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-153">Unique identifier for an order in the Microsoft billing platform.</span></span> <span data-ttu-id="b6a8d-154">可在連絡支援時方便識別訂單，但不是用於對帳。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-154">May be useful to identify the order when contacting support but not for reconciliation.</span></span></p></td>
<td><span data-ttu-id="b6a8d-155">566890604832738111</span><span class="sxs-lookup"><span data-stu-id="b6a8d-155">566890604832738111</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="b6a8d-156">SubscriptionID</span><span class="sxs-lookup"><span data-stu-id="b6a8d-156">SubscriptionID</span></span></td>
<td><p><span data-ttu-id="b6a8d-157">訂閱在 Microsoft 帳單平台中的唯一識別碼。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-157">Unique identifier for a subscription in the Microsoft billing platform.</span></span> <span data-ttu-id="b6a8d-158">可在連絡支援時方便識別訂閱，但不是用於對帳。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-158">May be useful to identify the subscription when contacting support but not for reconciliation.</span></span></p>
<p><span data-ttu-id="b6a8d-159">這與合作夥伴管理主控台上的訂閱識別碼不一樣。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-159">This is not the same as the Subscription ID on the Partner Admin Console.</span></span> <span data-ttu-id="b6a8d-160">請參閱 Syndication_Partner_Subscription_Number。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-160">Please see Syndication_Partner_Subscription_Number.</span></span></p></td>
<td><span data-ttu-id="b6a8d-161">usCBMgAAAAAAAAIA</span><span class="sxs-lookup"><span data-stu-id="b6a8d-161">usCBMgAAAAAAAAIA</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="b6a8d-162">SyndicationPartnerSubscriptionNumber</span><span class="sxs-lookup"><span data-stu-id="b6a8d-162">SyndicationPartnerSubscriptionNumber</span></span></td>
<td><p><span data-ttu-id="b6a8d-163">訂閱的唯一識別碼。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-163">Unique identifier for subscriptions.</span></span> <span data-ttu-id="b6a8d-164">客戶可針對同一方案擁有多項訂閱，因此這對於對帳檔案分析而言很重要。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-164">A customer can have multiple subscriptions for the same plan, so this is important for reconciliation file analysis.</span></span></p>
<p><span data-ttu-id="b6a8d-165">這個欄位對應到合作夥伴管理主控台中的訂閱識別碼。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-165">This field maps to the Subscription ID in the Partner Admin Console.</span></span></p></td>
<td><span data-ttu-id="b6a8d-166">fb977ab5-test-test-test-24c8d9591708</span><span class="sxs-lookup"><span data-stu-id="b6a8d-166">fb977ab5-test-test-test-24c8d9591708</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="b6a8d-167">OfferID</span><span class="sxs-lookup"><span data-stu-id="b6a8d-167">OfferID</span></span></td>
<td><p><span data-ttu-id="b6a8d-168">唯一的優惠識別碼。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-168">Unique offer ID.</span></span> <span data-ttu-id="b6a8d-169">根據價目表的標準優惠識別碼。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-169">Standard offer ID as per price list.</span></span></p>
<p><span data-ttu-id="b6a8d-170"><b>注意</b>：此值不符合優惠識別碼從價格清單。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-170"><b>Note</b>: This value does not match Offer ID from the price list.</span></span> <span data-ttu-id="b6a8d-171">請參閱下方的 DurableOfferID。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-171">See DurableOfferID below.</span></span></p></td>
<td><span data-ttu-id="b6a8d-172">FE616D64-E9A8-40EF-843F-152E9BBEF3D1</span><span class="sxs-lookup"><span data-stu-id="b6a8d-172">FE616D64-E9A8-40EF-843F-152E9BBEF3D1</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="b6a8d-173">DurableOfferID</span><span class="sxs-lookup"><span data-stu-id="b6a8d-173">DurableOfferID</span></span></td>
<td><p><span data-ttu-id="b6a8d-174">唯一的持續性優惠識別碼，如價目表中所定義。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-174">Unique durable offer ID, as defined in the price list.</span></span></p>
<p><span data-ttu-id="b6a8d-175"><b>注意</b>：此值符合優惠識別碼從價格清單。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-175"><b>Note</b>: This value matches the Offer ID from the price list.</span></span></p></td>
<td><span data-ttu-id="b6a8d-176">1017D7F3-6D7F-4BFA-BDD8-79BC8F104E0C</span><span class="sxs-lookup"><span data-stu-id="b6a8d-176">1017D7F3-6D7F-4BFA-BDD8-79BC8F104E0C</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="b6a8d-177">OfferName</span><span class="sxs-lookup"><span data-stu-id="b6a8d-177">OfferName</span></span></td>
<td><p><span data-ttu-id="b6a8d-178">客戶購買的服務優惠名稱，如價目表中所定義。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-178">The name of the service offering purchased by the customer, as defined in the price list.</span></span></p></td>
<td><span data-ttu-id="b6a8d-179">Microsoft Office 365 (Plan E3)</span><span class="sxs-lookup"><span data-stu-id="b6a8d-179">Microsoft Office 365 (Plan E3)</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="b6a8d-180">SubscriptionStartDate</span><span class="sxs-lookup"><span data-stu-id="b6a8d-180">SubscriptionStartDate</span></span></td>
<td><p><span data-ttu-id="b6a8d-181">訂閱開始日期設定為送出訂單之後的隔日。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-181">The subscription start date, set to the day after the order is submitted.</span></span> <span data-ttu-id="b6a8d-182">藉由同時查看訂閱開始日期與結束日期，您就可以判斷客戶是否仍在第一年訂閱期內，或下一年的訂閱已續約。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-182">By looking at the subscription start date in conjunction with the end date, you can determine if the customer is still within the first year of the subscription or if the subscription has been renewed for the following year.</span></span></p>
<p><span data-ttu-id="b6a8d-183">時間一律是一天的開始時間 (0:00)。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-183">The time is always the beginning of the day, 0:00.</span></span></p></td>
<td><span data-ttu-id="b6a8d-184">2/1/2015 0:00</span><span class="sxs-lookup"><span data-stu-id="b6a8d-184">2/1/2015 0:00</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="b6a8d-185">SubscriptionEndDate</span><span class="sxs-lookup"><span data-stu-id="b6a8d-185">SubscriptionEndDate</span></span></td>
<td><p><span data-ttu-id="b6a8d-186">訂用帳戶結束日期：12 個月 + x 天後 （以配合計費日期的夥伴） 的開始日期或續約日期起的 12 個月。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-186">The subscription end date: 12 months + x days after start date (to align with partner billing date) or 12 months from renewal date.</span></span></p>
<p><span data-ttu-id="b6a8d-187">續約時，價格會更新至目前的價目表。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-187">At renewal, prices are updated to the current price list.</span></span> <span data-ttu-id="b6a8d-188">自動續約之前，可能需要與客戶連絡。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-188">Customer communication may be required in advance of automated renewal.</span></span></p>
<p><span data-ttu-id="b6a8d-189">時間一律是一天的開始時間 (0:00)。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-189">The time is always the beginning of the day, 0:00.</span></span></p></td>
<td><span data-ttu-id="b6a8d-190">2/1/2015 0:00</span><span class="sxs-lookup"><span data-stu-id="b6a8d-190">2/1/2015 0:00</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="b6a8d-191">ChargeStartDate</span><span class="sxs-lookup"><span data-stu-id="b6a8d-191">ChargeStartDate</span></span></td>
<td><p><span data-ttu-id="b6a8d-192">開始計算費用的日期。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-192">Start day of the charges.</span></span></p>
<p><span data-ttu-id="b6a8d-193">當客戶變更基座數目時，此數字用於計算每日 (按比例) 的費用。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-193">When a customer changes seat numbers, this number is used to calculate per-day (pro-rata) charges.</span></span></p>
<p><span data-ttu-id="b6a8d-194">時間一律是一天的開始時間 (0:00)。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-194">The time is always the beginning of the day, 0:00.</span></span></p></td>
<td><span data-ttu-id="b6a8d-195">2/1/2015 0:00</span><span class="sxs-lookup"><span data-stu-id="b6a8d-195">2/1/2015 0:00</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="b6a8d-196">ChargeEndDate</span><span class="sxs-lookup"><span data-stu-id="b6a8d-196">ChargeEndDate</span></span></td>
<td><p><span data-ttu-id="b6a8d-197">結束計算費用的日期。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-197">End day of the charges.</span></span></p>
<p><span data-ttu-id="b6a8d-198">當客戶變更基座數目時，此數字用於計算每日 (按比例) 的費用。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-198">When a customer changes seat numbers, this number is used to calculate per-day (pro-rata) charges.</span></span></p>
<p><span data-ttu-id="b6a8d-199">時間一律是一天的結束時間 (23:59)。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-199">The time is always the end of the day, 23:59.</span></span></p></td>
<td><span data-ttu-id="b6a8d-200">2/28/2015 23:59</span><span class="sxs-lookup"><span data-stu-id="b6a8d-200">2/28/2015 23:59</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="b6a8d-201">ChargeType</span><span class="sxs-lookup"><span data-stu-id="b6a8d-201">ChargeType</span></span></td>
<td><p><span data-ttu-id="b6a8d-202">費用或調整的類型。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-202">The type of charge or adjustment.</span></span> <span data-ttu-id="b6a8d-203">請參閱<a href="#charge_types">對應發票和對帳檔案之間的費用</a></span><span class="sxs-lookup"><span data-stu-id="b6a8d-203">See <a href="#charge_types">Mapping charges between an invoice and the reconciliation file</a></span></span></p></td>
<td><p><span data-ttu-id="b6a8d-204">請參閱<a href="#charge_types">對應發票和對帳檔案之間的費用</a></span><span class="sxs-lookup"><span data-stu-id="b6a8d-204">See <a href="#charge_types">Mapping charges between an invoice and the reconciliation file</a></span></span></p></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="b6a8d-205">UnitPrice</span><span class="sxs-lookup"><span data-stu-id="b6a8d-205">UnitPrice</span></span></td>
<td><p><span data-ttu-id="b6a8d-206">每一基座價格，即購買時價目表中所公佈的價格。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-206">Price per seat, as published in the pricelist at the time of purchase.</span></span> <span data-ttu-id="b6a8d-207">請確定這與對帳期間儲存在您帳單系統中的資訊相符。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-207">Ensure this matches the information stored in your billing system during reconciliation.</span></span></p></td>
<td><span data-ttu-id="b6a8d-208">6.82</span><span class="sxs-lookup"><span data-stu-id="b6a8d-208">6.82</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="b6a8d-209">數量</span><span class="sxs-lookup"><span data-stu-id="b6a8d-209">Quantity</span></span></td>
<td><p><span data-ttu-id="b6a8d-210">基座數目。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-210">Number of seats.</span></span> <span data-ttu-id="b6a8d-211">請確定這與對帳期間儲存在您帳單系統中的資訊相符。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-211">Ensure this matches the information stored in your billing system during reconciliation.</span></span></p></td>
<td><span data-ttu-id="b6a8d-212">2</span><span class="sxs-lookup"><span data-stu-id="b6a8d-212">2</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="b6a8d-213">數量</span><span class="sxs-lookup"><span data-stu-id="b6a8d-213">Amount</span></span></td>
<td><p><span data-ttu-id="b6a8d-214">數量總價。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-214">Total of price for quantity.</span></span> <span data-ttu-id="b6a8d-215">檢查計算金額與您用來為客戶計算此項目的方式是否相符時很有用。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-215">Useful to check that the amount calculation matches how you calculate this for your customers.</span></span></p></td>
<td><span data-ttu-id="b6a8d-216">13.32</span><span class="sxs-lookup"><span data-stu-id="b6a8d-216">13.32</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="b6a8d-217">TotalOtherDiscount</span><span class="sxs-lookup"><span data-stu-id="b6a8d-217">TotalOtherDiscount</span></span></td>
<td><p><span data-ttu-id="b6a8d-218">套用至這些費用的折扣金額。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-218">Amount of discount applied to these charges.</span></span> <span data-ttu-id="b6a8d-219">符合獎勵資格之 IUR 或新訂閱的訂單，也將於此欄中包含折扣金額。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-219">IUR or new subscriptions eligible for an incentive will also contain a discount amount in this column.</span></span></p></td>
<td><span data-ttu-id="b6a8d-220">2.32</span><span class="sxs-lookup"><span data-stu-id="b6a8d-220">2.32</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="b6a8d-221">小計</span><span class="sxs-lookup"><span data-stu-id="b6a8d-221">Subtotal</span></span></td>
<td><p><span data-ttu-id="b6a8d-222">稅前總計。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-222">Total before tax.</span></span> <span data-ttu-id="b6a8d-223">如果有折扣，可檢查小計是否和預期的總金額相符。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-223">Checks that your subtotal matches your expected total, in case of a discount.</span></span></p></td>
<td><span data-ttu-id="b6a8d-224">11</span><span class="sxs-lookup"><span data-stu-id="b6a8d-224">11</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="b6a8d-225">稅</span><span class="sxs-lookup"><span data-stu-id="b6a8d-225">Tax</span></span></td>
<td><p><span data-ttu-id="b6a8d-226">稅務量費用，費用，根據您的市場&#39;s 稅務規則與特定的情況。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-226">Tax amount charge, based on your market&#39;s tax rules and specific circumstances.</span></span></p></td>
<td><span data-ttu-id="b6a8d-227">0</span><span class="sxs-lookup"><span data-stu-id="b6a8d-227">0</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="b6a8d-228">TotalForCustomer</span><span class="sxs-lookup"><span data-stu-id="b6a8d-228">TotalForCustomer</span></span></td>
<td><p><span data-ttu-id="b6a8d-229">稅後總計。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-229">Total after tax.</span></span> <span data-ttu-id="b6a8d-230">檢查發票中是否向您收取稅金。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-230">Checks if you are charged tax in the invoice.</span></span></p></td>
<td><span data-ttu-id="b6a8d-231">11</span><span class="sxs-lookup"><span data-stu-id="b6a8d-231">11</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="b6a8d-232">Currency</span><span class="sxs-lookup"><span data-stu-id="b6a8d-232">Currency</span></span></td>
<td><p><span data-ttu-id="b6a8d-233">貨幣類型。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-233">Currency type.</span></span> <span data-ttu-id="b6a8d-234">每一帳單實體都只有一種貨幣。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-234">Each billing entity has only one currency.</span></span> <span data-ttu-id="b6a8d-235">檢查是否與您的第一張發票相符，然後在進行任何重大帳單平台更新之後檢查。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-235">Check that it matches your first invoice and then after any major billing platform update.</span></span></p></td>
<td><span data-ttu-id="b6a8d-236">EUR</span><span class="sxs-lookup"><span data-stu-id="b6a8d-236">EUR</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="b6a8d-237">CustomerName</span><span class="sxs-lookup"><span data-stu-id="b6a8d-237">CustomerName</span></span></td>
<td><p><span data-ttu-id="b6a8d-238">客戶&#39;合作夥伴中心中所報告的 s 的組織名稱。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-238">Customer&#39;s organization name as reported in Partner Center.</span></span> <span data-ttu-id="b6a8d-239">這在使用您的系統資訊對帳發票時非常重要。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-239">This is very important for reconciling the invoice with your system information.</span></span></p></td>
<td><span data-ttu-id="b6a8d-240">測試客戶 A</span><span class="sxs-lookup"><span data-stu-id="b6a8d-240">Test Customer A</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="b6a8d-241">MPNID</span><span class="sxs-lookup"><span data-stu-id="b6a8d-241">MPNID</span></span></td>
<td><p><span data-ttu-id="b6a8d-242">雲端解決方案提供者合作夥伴的 MPN 識別碼</span><span class="sxs-lookup"><span data-stu-id="b6a8d-242">MPN ID of the CSP partner</span></span></p></td>
<td><span data-ttu-id="b6a8d-243">4390934</span><span class="sxs-lookup"><span data-stu-id="b6a8d-243">4390934</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="b6a8d-244">ResellerMPNID</span><span class="sxs-lookup"><span data-stu-id="b6a8d-244">ResellerMPNID</span></span></td>
<td><p><span data-ttu-id="b6a8d-245">訂閱記錄中的經銷商 MPN 識別碼。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-245">MPN ID of the reseller of record for the subscription.</span></span> <span data-ttu-id="b6a8d-246">請參閱<a href="#itemizebypartner" data-raw-source="[Itemize by partner](#itemizebypartner)">依合作夥伴詳細列舉</a>。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-246">See <a href="#itemizebypartner" data-raw-source="[Itemize by partner](#itemizebypartner)">Itemize by partner</a>.</span></span></p></td>
<td><span data-ttu-id="b6a8d-247">4390934</span><span class="sxs-lookup"><span data-stu-id="b6a8d-247">4390934</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="b6a8d-248">DomainName</span><span class="sxs-lookup"><span data-stu-id="b6a8d-248">DomainName</span></span></td>
<td><p><span data-ttu-id="b6a8d-249">客戶&#39;用來協助識別客戶的 s 網域名稱。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-249">Customer&#39;s domain name, used to help identify the customer.</span></span> <span data-ttu-id="b6a8d-250">這不應該用來唯一識別客戶，客戶/合作夥伴可以更新透過 O365 入口網站的虛名/預設網域。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-250">This should not be used to uniquely identify the customer as the customer/partner can update the vanity/default domain via the O365 portal.</span></span> <span data-ttu-id="b6a8d-251">在下一個帳單週期之前，此欄位會是空白的。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-251">This field may appear blank until the second billing cycle.</span></span></p></td>
<td><span data-ttu-id="b6a8d-252">example.onmicrosoft.com</span><span class="sxs-lookup"><span data-stu-id="b6a8d-252">example.onmicrosoft.com</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="b6a8d-253">SubscriptionName</span><span class="sxs-lookup"><span data-stu-id="b6a8d-253">SubscriptionName</span></span></td>
<td><p><span data-ttu-id="b6a8d-254">訂閱暱稱。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-254">Subscription nickname.</span></span> <span data-ttu-id="b6a8d-255">如果未指定任何暱稱，合作夥伴中心會使用 OfferName。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-255">If no nickname is specified, Partner Center uses the OfferName.</span></span></p></td>
<td><span data-ttu-id="b6a8d-256">PROJECT ONLINE</span><span class="sxs-lookup"><span data-stu-id="b6a8d-256">PROJECT ONLINE</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="b6a8d-257">SubscriptionDescription</span><span class="sxs-lookup"><span data-stu-id="b6a8d-257">SubscriptionDescription</span></span></td>
<td><p><span data-ttu-id="b6a8d-258">客戶購買的服務優惠名稱，如價目表中所定義。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-258">The name of the service offering purchased by the customer, as defined in the price list.</span></span> <span data-ttu-id="b6a8d-259">（這是優惠名稱的相同欄位）。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-259">(This is an identical field to Offer name).</span></span></p></td>
<td><span data-ttu-id="b6a8d-260">PROJECT ONLINE PREMIUM WITHOUT PROJECT CLIENT</span><span class="sxs-lookup"><span data-stu-id="b6a8d-260">PROJECT ONLINE PREMIUM WITHOUT PROJECT CLIENT</span></span></td>
</tr>
</tbody>
</table>


## <a href="" id="usagebasedfiles"></a><span data-ttu-id="b6a8d-261">基於使用方式檔案欄位</span><span class="sxs-lookup"><span data-stu-id="b6a8d-261">Usage-based file fields</span></span>


<span data-ttu-id="b6a8d-262">若要針對您客戶使用量的費用來對帳，請比較對帳檔案中的 ResellerID/ResellerName/ResellerBillableAccount、客戶名稱，與合作夥伴中心的訂閱識別碼。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-262">To reconcile your charges against your customer's usage, compare the ResellerID/ResellerName/ResellerBillableAccount from the reconciliation file, the customer name, and the Subscription ID from Partner Center.</span></span>

<span data-ttu-id="b6a8d-263">下列欄位說明使用哪些服務及費率。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-263">The following fields explain which services were used and the rate.</span></span>

<table>
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<tbody>
<tr class="odd">
<td><span data-ttu-id="b6a8d-264"><strong>資料行</strong></span><span class="sxs-lookup"><span data-stu-id="b6a8d-264"><strong>Column</strong></span></span></td>
<td><span data-ttu-id="b6a8d-265"><strong>描述</strong></span><span class="sxs-lookup"><span data-stu-id="b6a8d-265"><strong>Description</strong></span></span></td>
<td><span data-ttu-id="b6a8d-266"><strong>範例值</strong></span><span class="sxs-lookup"><span data-stu-id="b6a8d-266"><strong>Sample value</strong></span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="b6a8d-267">PartnerID</span><span class="sxs-lookup"><span data-stu-id="b6a8d-267">PartnerID</span></span></td>
<td><p><span data-ttu-id="b6a8d-268">合作夥伴識別碼 (GUID 格式)。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-268">Partner ID, in GUID format.</span></span></p></td>
<td><span data-ttu-id="b6a8d-269">DA41BC5F-C52D-4464-8A8D-8C8DCC43503B</span><span class="sxs-lookup"><span data-stu-id="b6a8d-269">DA41BC5F-C52D-4464-8A8D-8C8DCC43503B</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="b6a8d-270">PartnerName</span><span class="sxs-lookup"><span data-stu-id="b6a8d-270">PartnerName</span></span></td>
<td><p><span data-ttu-id="b6a8d-271">合作夥伴名稱。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-271">Partner Name.</span></span></p></td>
<td><span data-ttu-id="b6a8d-272">Acme Incorporated</span><span class="sxs-lookup"><span data-stu-id="b6a8d-272">Acme Incorporated</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="b6a8d-273">PartnerBillableAccountID</span><span class="sxs-lookup"><span data-stu-id="b6a8d-273">PartnerBillableAccountID</span></span></td>
<td><p><span data-ttu-id="b6a8d-274">合作夥伴帳戶識別碼。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-274">Partner Account ID.</span></span></p></td>
<td><span data-ttu-id="b6a8d-275">1010578050</span><span class="sxs-lookup"><span data-stu-id="b6a8d-275">1010578050</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="b6a8d-276">CustomerName</span><span class="sxs-lookup"><span data-stu-id="b6a8d-276">CustomerName</span></span></td>
<td><p><span data-ttu-id="b6a8d-277">客戶&#39;合作夥伴中心中所報告的 s 的組織名稱。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-277">Customer&#39;s organization name as reported in Partner Center.</span></span> <span data-ttu-id="b6a8d-278">這在使用您的系統資訊對帳發票時非常重要。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-278">This is very important for reconciling the invoice with your system information.</span></span></p></td>
<td><span data-ttu-id="b6a8d-279">測試客戶 A</span><span class="sxs-lookup"><span data-stu-id="b6a8d-279">Test Customer A</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="b6a8d-280">MPNID</span><span class="sxs-lookup"><span data-stu-id="b6a8d-280">MPNID</span></span></td>
<td><p><span data-ttu-id="b6a8d-281">雲端解決方案提供者合作夥伴的 MPN 識別碼。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-281">MPN ID of the CSP partner.</span></span></p></td>
<td><span data-ttu-id="b6a8d-282">4390934</span><span class="sxs-lookup"><span data-stu-id="b6a8d-282">4390934</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="b6a8d-283">ResellerMPNID</span><span class="sxs-lookup"><span data-stu-id="b6a8d-283">ResellerMPNID</span></span></td>
<td><p><span data-ttu-id="b6a8d-284">訂閱記錄中的經銷商 MPN 識別碼。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-284">MPN ID of the reseller of record for the subscription.</span></span> <span data-ttu-id="b6a8d-285">請參閱<a href="#itemizebypartner" data-raw-source="[Itemize by partner](#itemizebypartner)">依合作夥伴詳細列舉</a>。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-285">See <a href="#itemizebypartner" data-raw-source="[Itemize by partner](#itemizebypartner)">Itemize by partner</a>.</span></span></p></td>
<td><span data-ttu-id="b6a8d-286">4390934</span><span class="sxs-lookup"><span data-stu-id="b6a8d-286">4390934</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="b6a8d-287">InvoiceNumber</span><span class="sxs-lookup"><span data-stu-id="b6a8d-287">InvoiceNumber</span></span></td>
<td><p><span data-ttu-id="b6a8d-288">交易的指定位置顯示的發票號碼。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-288">Invoice number where the specified transaction appears.</span></span></p></td>
<td><span data-ttu-id="b6a8d-289">D020001IVK</span><span class="sxs-lookup"><span data-stu-id="b6a8d-289">D020001IVK</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="b6a8d-290">ChargeStartDate</span><span class="sxs-lookup"><span data-stu-id="b6a8d-290">ChargeStartDate</span></span></td>
<td><p><span data-ttu-id="b6a8d-291">計費週期的開始日期，當顯示之前未收取潛在使用量資料費用的日期時除外 (從前一個計費週期開始)。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-291">Start date of billing cycle except when presenting dates of previously uncharged latent usage data (from previous bill cycle).</span></span></p>
<p><span data-ttu-id="b6a8d-292">時間一律是一天的開始時間 (0:00)。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-292">The time is always the beginning of the day, 0:00.</span></span></p></td>
<td><span data-ttu-id="b6a8d-293">2/1/2014 0:00</span><span class="sxs-lookup"><span data-stu-id="b6a8d-293">2/1/2014 0:00</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="b6a8d-294">ChargeEndDate</span><span class="sxs-lookup"><span data-stu-id="b6a8d-294">ChargeEndDate</span></span></td>
<td><p><span data-ttu-id="b6a8d-295">計費週期的結束日期，當顯示之前未收取潛在使用量資料費用的日期時除外 (從前一個計費週期開始)。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-295">End date of billing cycle except when presenting dates of previously uncharged latent usage data (from previous bill cycle).</span></span></p>
<p><span data-ttu-id="b6a8d-296">時間一律是一天的結束時間 (23:59)。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-296">The time is always the end of the day, 23:59.</span></span></p></td>
<td><span data-ttu-id="b6a8d-297">2/28/2014 23:59</span><span class="sxs-lookup"><span data-stu-id="b6a8d-297">2/28/2014 23:59</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="b6a8d-298">SubscriptionID</span><span class="sxs-lookup"><span data-stu-id="b6a8d-298">SubscriptionID</span></span></td>
<td><p><span data-ttu-id="b6a8d-299">訂閱在 Microsoft 帳單平台中的唯一識別碼。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-299">Unique identifier for a subscription in the Microsoft billing platform.</span></span> <span data-ttu-id="b6a8d-300">可在連絡支援時方便識別訂閱，但不是用於對帳。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-300">May be useful to identify the subscription when contacting support but not for reconciliation.</span></span></p>
<p><span data-ttu-id="b6a8d-301">這與合作夥伴管理主控台上的訂閱識別碼不一樣。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-301">This is not the same as the Subscription ID on the Partner Admin Console.</span></span></p></td>
<td><span data-ttu-id="b6a8d-302">usCBMgAAAAAAAAIA</span><span class="sxs-lookup"><span data-stu-id="b6a8d-302">usCBMgAAAAAAAAIA</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="b6a8d-303">SubscriptionName</span><span class="sxs-lookup"><span data-stu-id="b6a8d-303">SubscriptionName</span></span></td>
<td><p><span data-ttu-id="b6a8d-304">服務優惠的暱稱。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-304">Nickname of the service offering.</span></span></p></td>
<td><span data-ttu-id="b6a8d-305">Microsoft Azure</span><span class="sxs-lookup"><span data-stu-id="b6a8d-305">Microsoft Azure</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="b6a8d-306">SubscriptionDescription</span><span class="sxs-lookup"><span data-stu-id="b6a8d-306">SubscriptionDescription</span></span></td>
<td><p><span data-ttu-id="b6a8d-307">服務優惠的企業營運</span><span class="sxs-lookup"><span data-stu-id="b6a8d-307">Line of business of the service offering</span></span></p></td>
<td><span data-ttu-id="b6a8d-308">Microsoft Azure</span><span class="sxs-lookup"><span data-stu-id="b6a8d-308">Microsoft Azure</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="b6a8d-309">OrderID</span><span class="sxs-lookup"><span data-stu-id="b6a8d-309">OrderID</span></span></td>
<td><p><span data-ttu-id="b6a8d-310">訂單在 Microsoft 帳單平台中的唯一識別碼。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-310">Unique identifier for an order in the Microsoft billing platform.</span></span> <span data-ttu-id="b6a8d-311">可在連絡支援時方便識別訂閱，但不是用於對帳。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-311">May be useful to identify the subscription when contacting support but not for reconciliation.</span></span></p></td>
<td><span data-ttu-id="b6a8d-312">566890604832738111</span><span class="sxs-lookup"><span data-stu-id="b6a8d-312">566890604832738111</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="b6a8d-313">ServiceName</span><span class="sxs-lookup"><span data-stu-id="b6a8d-313">ServiceName</span></span></td>
<td><p><span data-ttu-id="b6a8d-314">要求的 Azure 服務名稱。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-314">The name of the Azure service in question.</span></span></p></td>
<td><span data-ttu-id="b6a8d-315">虛擬機器</span><span class="sxs-lookup"><span data-stu-id="b6a8d-315">VIRTUAL MACHINES</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="b6a8d-316">ServiceType</span><span class="sxs-lookup"><span data-stu-id="b6a8d-316">ServiceType</span></span></td>
<td><p><span data-ttu-id="b6a8d-317">Microsoft Azure 服務的特定類型。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-317">The specific type of Windows Azure service.</span></span></p></td>
<td><ul>
<li><span data-ttu-id="b6a8d-318">服務匯流排 – 個人或套件</span><span class="sxs-lookup"><span data-stu-id="b6a8d-318">Service Bus – Individual or Pack</span></span></li>
<li><span data-ttu-id="b6a8d-319">SQL Azure 資料庫 – Business 或 Web Edition</span><span class="sxs-lookup"><span data-stu-id="b6a8d-319">SQL Azure database – Business or Web Edition</span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="b6a8d-320">ResourceGUID</span><span class="sxs-lookup"><span data-stu-id="b6a8d-320">ResourceGUID</span></span></td>
<td><p><span data-ttu-id="b6a8d-321">所有服務資料與定價結構的特定唯一識別碼。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-321">Specific unique identifier for all the service data and pricing structure.</span></span></p></td>
<td><span data-ttu-id="b6a8d-322">DA41BC5F-C52D-4464-8A8D-8C8DCC43503B</span><span class="sxs-lookup"><span data-stu-id="b6a8d-322">DA41BC5F-C52D-4464-8A8D-8C8DCC43503B</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="b6a8d-323">Resource Name</span><span class="sxs-lookup"><span data-stu-id="b6a8d-323">Resource Name</span></span></td>
<td><p><span data-ttu-id="b6a8d-324">Azure 資源的名稱。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-324">The name of the Azure resource.</span></span></p></td>
<td><ul>
<li><span data-ttu-id="b6a8d-325">資料轉入 (GB)</span><span class="sxs-lookup"><span data-stu-id="b6a8d-325">Data Transfer In (GB)</span></span></li>
<li><span data-ttu-id="b6a8d-326">資料轉出 (GB)</span><span class="sxs-lookup"><span data-stu-id="b6a8d-326">Data Transfer Out (GB)</span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="b6a8d-327">地區</span><span class="sxs-lookup"><span data-stu-id="b6a8d-327">Region</span></span></td>
<td><p><span data-ttu-id="b6a8d-328">使用量適用的地區。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-328">The region the usage applies to.</span></span> <span data-ttu-id="b6a8d-329">主要用來指定資料傳輸速率，費率因地區而異。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-329">Primarily used to assign rates to data transfers, as rates vary by region.</span></span></p></td>
<td><span data-ttu-id="b6a8d-330">亞太地區、歐洲、拉丁美洲、北美洲</span><span class="sxs-lookup"><span data-stu-id="b6a8d-330">Asia Pacific, Europe, Latin America, North America</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="b6a8d-331">SKU</span><span class="sxs-lookup"><span data-stu-id="b6a8d-331">SKU</span></span></td>
<td><p><span data-ttu-id="b6a8d-332">優惠的 MSFT 唯一識別碼</span><span class="sxs-lookup"><span data-stu-id="b6a8d-332">MSFT unique identifier for offer</span></span></p></td>
<td><span data-ttu-id="b6a8d-333">7UD 00001</span><span class="sxs-lookup"><span data-stu-id="b6a8d-333">7UD-00001</span></span></td>
</tr>
<tr class="odd">
<td><p><span data-ttu-id="b6a8d-334">DetailLineItemId</span><span class="sxs-lookup"><span data-stu-id="b6a8d-334">DetailLineItemId</span></span></p></td>
<td><p><span data-ttu-id="b6a8d-335">用於詳細列出指定計費期間中，服務或資源不同費率的識別碼和數量。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-335">An ID and quantity for itemizing the different rates for a service or resource in a given billing period.</span></span> <span data-ttu-id="b6a8d-336">對於 Azure 分層評分，到某個數量的計費單位會有一個評分，之後則有不同評分。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-336">For Azure tiered rating, there may be one rate up to a certain quantity of billable units, then a different rate after that.</span></span></p></td>
<td><span data-ttu-id="b6a8d-337">1</span><span class="sxs-lookup"><span data-stu-id="b6a8d-337">1</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="b6a8d-338">ConsumedQuantity</span><span class="sxs-lookup"><span data-stu-id="b6a8d-338">ConsumedQuantity</span></span></td>
<td><p><span data-ttu-id="b6a8d-339">報表期間耗用的服務量 (小時、GB 等等)</span><span class="sxs-lookup"><span data-stu-id="b6a8d-339">The amount of service consumed (hours, GB, etc.) during the reporting period.</span></span></p>
<p><span data-ttu-id="b6a8d-340">同時包括先前報表期間任何未計費的使用量。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-340">Also includes any unbilled usage from previous reporting periods.</span></span></p></td>
<td><span data-ttu-id="b6a8d-341">11</span><span class="sxs-lookup"><span data-stu-id="b6a8d-341">11</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="b6a8d-342">IncludedQuantity</span><span class="sxs-lookup"><span data-stu-id="b6a8d-342">IncludedQuantity</span></span></td>
<td><p><span data-ttu-id="b6a8d-343">包含在優惠中的單位。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-343">Units included as part of the offer.</span></span> <span data-ttu-id="b6a8d-344">通常不會出現在雲端解決方案提供者中。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-344">Not typically present in CSP.</span></span></p></td>
<td><span data-ttu-id="b6a8d-345">0</span><span class="sxs-lookup"><span data-stu-id="b6a8d-345">0</span></span></td>
</tr>
<tr class="even">
<td><p><span data-ttu-id="b6a8d-346">OverageQuantity</span><span class="sxs-lookup"><span data-stu-id="b6a8d-346">OverageQuantity</span></span></p></td>
<td><p><span data-ttu-id="b6a8d-347">不包含在優惠中的單位，必須由合作夥伴支付。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-347">Units not included as part of the offer, that must be paid for by the partner.</span></span></p>
<p><span data-ttu-id="b6a8d-348">等同於 ConsumedQuantity - IncludedQuantity。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-348">Equal to the ConsumedQuantity - IncludedQuantity.</span></span></p></td>
<td><span data-ttu-id="b6a8d-349">11</span><span class="sxs-lookup"><span data-stu-id="b6a8d-349">11</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="b6a8d-350">ListPrice</span><span class="sxs-lookup"><span data-stu-id="b6a8d-350">ListPrice</span></span></td>
<td><p><span data-ttu-id="b6a8d-351">訂閱開始日期的生效優惠價格。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-351">Offer price in effect at subscription start date.</span></span></p></td>
<td><span data-ttu-id="b6a8d-352">$0.0808</span><span class="sxs-lookup"><span data-stu-id="b6a8d-352">$0.0808</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="b6a8d-353">PretaxCharges</span><span class="sxs-lookup"><span data-stu-id="b6a8d-353">PretaxCharges</span></span></td>
<td><p><span data-ttu-id="b6a8d-354">ListPrist 乘以 OverageQuantity，四捨五入至美分。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-354">ListPrist times OverageQuantity, rounded to the nearest cent.</span></span></p></td>
<td><span data-ttu-id="b6a8d-355">$0.085</span><span class="sxs-lookup"><span data-stu-id="b6a8d-355">$0.085</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="b6a8d-356">TaxAmount</span><span class="sxs-lookup"><span data-stu-id="b6a8d-356">TaxAmount</span></span></td>
<td><p><span data-ttu-id="b6a8d-357">稅務量費用，費用，根據您的市場&#39;s 稅務規則與特定的情況。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-357">Tax amount charge, based on your market&#39;s tax rules and specific circumstances.</span></span></p></td>
<td><span data-ttu-id="b6a8d-358">$0.08</span><span class="sxs-lookup"><span data-stu-id="b6a8d-358">$0.08</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="b6a8d-359">PostTaxTotal</span><span class="sxs-lookup"><span data-stu-id="b6a8d-359">PostTaxTotal</span></span></td>
<td><p><span data-ttu-id="b6a8d-360">稅後總計 (當適用稅金時)。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-360">Total after tax, when tax is applicable.</span></span></p></td>
<td><span data-ttu-id="b6a8d-361">$0.93</span><span class="sxs-lookup"><span data-stu-id="b6a8d-361">$0.93</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="b6a8d-362">Currency</span><span class="sxs-lookup"><span data-stu-id="b6a8d-362">Currency</span></span></td>
<td><p><span data-ttu-id="b6a8d-363">貨幣類型。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-363">Currency type.</span></span> <span data-ttu-id="b6a8d-364">每一帳單實體都只有一種貨幣。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-364">Each billing entity has only one currency.</span></span> <span data-ttu-id="b6a8d-365">檢查是否與您的第一張發票相符，然後在進行任何重大帳單平台更新之後檢查。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-365">Check that it matches your first invoice and then after any major billing platform update.</span></span></p></td>
<td><span data-ttu-id="b6a8d-366">EUR</span><span class="sxs-lookup"><span data-stu-id="b6a8d-366">EUR</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="b6a8d-367">PretaxEffectiveRate</span><span class="sxs-lookup"><span data-stu-id="b6a8d-367">PretaxEffectiveRate</span></span></td>
<td><p><span data-ttu-id="b6a8d-368">每個單位的稅前價格。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-368">Pretax price per unit.</span></span> <span data-ttu-id="b6a8d-369">等於 PretaxCharges / OverageQuantity, 四捨五入至美分。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-369">Equal to PretaxCharges / OverageQuantity, rounded to the nearest cent.</span></span></p></td>
<td><span data-ttu-id="b6a8d-370">$0.08</span><span class="sxs-lookup"><span data-stu-id="b6a8d-370">$0.08</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="b6a8d-371">PostTaxEffectiveRate</span><span class="sxs-lookup"><span data-stu-id="b6a8d-371">PostTaxEffectiveRate</span></span></td>
<td><p><span data-ttu-id="b6a8d-372">每個單位的稅後價格。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-372">Post tax price per unit.</span></span> <span data-ttu-id="b6a8d-373">等於 PostTaxTotal / OverageQuantity，或 PretaxEffectiveRate + 每單位數量稅率，四捨五入至美分。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-373">Equal to PostTaxTotal / OverageQuantity, or PretaxEffectiveRate + tax rate per unit amoun, rounded to the nearest cent.</span></span></p></td>
<td><span data-ttu-id="b6a8d-374">$0.08</span><span class="sxs-lookup"><span data-stu-id="b6a8d-374">$0.08</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="b6a8d-375">ChargeType</span><span class="sxs-lookup"><span data-stu-id="b6a8d-375">ChargeType</span></span></td>
<td><p><span data-ttu-id="b6a8d-376">費用或調整的類型。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-376">The type of charge or adjustment.</span></span> <span data-ttu-id="b6a8d-377">請參閱<a href="#charge_types">對應發票和對帳檔案之間的費用</a></span><span class="sxs-lookup"><span data-stu-id="b6a8d-377">See <a href="#charge_types">Mapping charges between an invoice and the reconciliation file</a></span></span></p></td>
<td><p><span data-ttu-id="b6a8d-378">請參閱<a href="#charge_types">對應發票和對帳檔案之間的費用</a></span><span class="sxs-lookup"><span data-stu-id="b6a8d-378">See <a href="#charge_types">Mapping charges between an invoice and the reconciliation file</a></span></span></p></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="b6a8d-379">CustomerBillableAccount</span><span class="sxs-lookup"><span data-stu-id="b6a8d-379">CustomerBillableAccount</span></span></td>
<td><p><span data-ttu-id="b6a8d-380">MSFT 帳單平台的唯一帳戶識別碼。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-380">Unique account ID in the MSFT billing platform.</span></span></p></td>
<td><span data-ttu-id="b6a8d-381">1280018095</span><span class="sxs-lookup"><span data-stu-id="b6a8d-381">1280018095</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="b6a8d-382">UsageDate</span><span class="sxs-lookup"><span data-stu-id="b6a8d-382">UsageDate</span></span></td>
<td><p><span data-ttu-id="b6a8d-383">服務部署的日期。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-383">Date of service deployment.</span></span></p></td>
<td><span data-ttu-id="b6a8d-384">2/1/2014 0:00</span><span class="sxs-lookup"><span data-stu-id="b6a8d-384">2/1/2014 0:00</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="b6a8d-385">MeteredRegion</span><span class="sxs-lookup"><span data-stu-id="b6a8d-385">MeteredRegion</span></span></td>
<td><p><span data-ttu-id="b6a8d-386">此欄可識別適用及填入此項目之服務地區內的資料中心的位置。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-386">This column identifies the location of a data center within the region for services where this is applicable and populated.</span></span></p></td>
<td><span data-ttu-id="b6a8d-387">東亞、東南亞、北歐、西歐、美國中北部、美國中南部</span><span class="sxs-lookup"><span data-stu-id="b6a8d-387">East Asia, South East Asia, North Europe, West Europe, North Central US, South Central US</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="b6a8d-388">MeteredService</span><span class="sxs-lookup"><span data-stu-id="b6a8d-388">MeteredService</span></span></td>
<td><p><span data-ttu-id="b6a8d-389">此欄是用來追蹤可能未在 \[服務名稱\] 欄中特別指出的個別 Microsoft Azure 服務。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-389">This column is utilized to track the individual Microsoft Azure service that may not be specifically identified in the Service Name column.</span></span> <span data-ttu-id="b6a8d-390">例如，在 \[服務名稱\] 欄中，資料傳輸是回報為 &quot;Microsoft Azure - 所有服務&quot;。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-390">For example, data transfers are reported as &quot;Microsoft Azure - All Services&quot; in the Service Name column.</span></span> <span data-ttu-id="b6a8d-391">此 MeteredService 欄會指出使用量與哪個特定服務有關。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-391">This MeteredService column will indicate to which specific service the usage pertains.</span></span></p></td>
<td><span data-ttu-id="b6a8d-392">AccessControl、CDN、Compute、Database、ServiceBus、Storage</span><span class="sxs-lookup"><span data-stu-id="b6a8d-392">AccessControl, CDN, Compute, Database, ServiceBus, Storage</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="b6a8d-393">MeteredServiceType</span><span class="sxs-lookup"><span data-stu-id="b6a8d-393">MeteredServiceType</span></span></td>
<td><p><span data-ttu-id="b6a8d-394">進一步釐清超出 MeteredService 欄位提供之層級的個別 Microsoft Azure 服務副標題。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-394">A subheading that further clarifies the individual Microsoft Azure service beyond the level provided by the MeteredService field.</span></span></p></td>
<td><span data-ttu-id="b6a8d-395">外部</span><span class="sxs-lookup"><span data-stu-id="b6a8d-395">EXTERNAL</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="b6a8d-396">Project</span><span class="sxs-lookup"><span data-stu-id="b6a8d-396">Project</span></span></td>
<td><p><span data-ttu-id="b6a8d-397">客戶為其服務執行個體定義的名稱</span><span class="sxs-lookup"><span data-stu-id="b6a8d-397">Customer-defined name for their service instance</span></span></p></td>
<td><span data-ttu-id="b6a8d-398">ORDDC52E52FDEF405786F0642DD0108BE4</span><span class="sxs-lookup"><span data-stu-id="b6a8d-398">ORDDC52E52FDEF405786F0642DD0108BE4</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="b6a8d-399">ServiceInfo</span><span class="sxs-lookup"><span data-stu-id="b6a8d-399">ServiceInfo</span></span></td>
<td><p><span data-ttu-id="b6a8d-400">於某一天佈建及使用的 ServiceBus 連線數目。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-400">The number of ServiceBus connections that were provisioned and utilized on a given day.</span></span></p></td>
<td><span data-ttu-id="b6a8d-401">例如：如果您在有 30 天的月份中有個別佈建的連線時，「服務資訊 1」的讀數會是「1.000000 連線 / 30 天」。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-401">For example: if you had an individually provisioned connection during a 30 day month, Service Info 1 would read “1.000000 Connections / 30 days”.</span></span> <span data-ttu-id="b6a8d-402">如果您有 25 的組件的佈建的服務匯流排連線，而且您必須在那一天使用 1，表示您那一天的每日使用量聲明 」 25 的連線 / 已使用的 30 天：1.000000”.</span><span class="sxs-lookup"><span data-stu-id="b6a8d-402">If you had a 25 pack of ServiceBus connections provisioned and you had utilized 1 during that day, your daily usage statement for that day would indicate “25 Connections / 30 Days – Used: 1.000000”.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="b6a8d-403">CustomerID</span><span class="sxs-lookup"><span data-stu-id="b6a8d-403">CustomerID</span></span></td>
<td><p><span data-ttu-id="b6a8d-404">用來識別客戶的唯一 Microsoft ID（GUID 格式）。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-404">Unique Microsoft ID, in GUID format, used to identify the customer.</span></span></p></td>
<td><span data-ttu-id="b6a8d-405">ORDDC52E52FDEF405786F0642DD0108BE4</span><span class="sxs-lookup"><span data-stu-id="b6a8d-405">ORDDC52E52FDEF405786F0642DD0108BE4</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="b6a8d-406">DomainName</span><span class="sxs-lookup"><span data-stu-id="b6a8d-406">DomainName</span></span></td>
<td><p><span data-ttu-id="b6a8d-407">客戶&#39;用來協助識別客戶的 s 網域名稱。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-407">Customer&#39;s domain name, used to help identify the customer.</span></span> <span data-ttu-id="b6a8d-408">在下一個帳單週期之前，此欄位會是空白的。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-408">This field may appear blank until the second billing cycle.</span></span></p></td>
<td><span data-ttu-id="b6a8d-409">example.onmicrosoft.com</span><span class="sxs-lookup"><span data-stu-id="b6a8d-409">example.onmicrosoft.com</span></span></td></tr>
</tr>
<tr class="even">
<td><span data-ttu-id="b6a8d-410">單位</span><span class="sxs-lookup"><span data-stu-id="b6a8d-410">Unit</span></span></td>
<td><p><span data-ttu-id="b6a8d-411">資源名稱的單位</span><span class="sxs-lookup"><span data-stu-id="b6a8d-411">The unit of the resource Name</span></span></p></td>
<td><span data-ttu-id="b6a8d-412">GB 或 HOURS</span><span class="sxs-lookup"><span data-stu-id="b6a8d-412">GB or HOURS</span></span></td>
</tr>
</tbody>
</table>

## <a href="" id="marketplacefilefields"></a><span data-ttu-id="b6a8d-413">單次和週期的檔案欄位</span><span class="sxs-lookup"><span data-stu-id="b6a8d-413">One-time and recurring file fields</span></span>

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th><span data-ttu-id="b6a8d-414">「資料行」</span><span class="sxs-lookup"><span data-stu-id="b6a8d-414">Column</span></span></th>
<th><span data-ttu-id="b6a8d-415">描述</span><span class="sxs-lookup"><span data-stu-id="b6a8d-415">Description</span></span></th>
</tr>
</thead>
<tbody>


<tr class="odd">
<td><span data-ttu-id="b6a8d-416">PartnerId</span><span class="sxs-lookup"><span data-stu-id="b6a8d-416">PartnerId</span></span></td>
<td><p><span data-ttu-id="b6a8d-417">唯一特定計費實體，則採用 GUID 格式的 Microsoft Azure Active Directory 租用戶識別碼。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-417">Unique Microsoft Azure Active Directory tenant identifier for a specific billing entity, in GUID format.</span></span> <span data-ttu-id="b6a8d-418">對帳時不需要，但可能是很有用的資訊。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-418">Not required for reconciliation, however may be useful information.</span></span> <span data-ttu-id="b6a8d-419">在所有資料列中都是如此。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-419">Same in all rows.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="b6a8d-420">客戶識別碼</span><span class="sxs-lookup"><span data-stu-id="b6a8d-420">Customer Id</span></span></td>
<td><p><span data-ttu-id="b6a8d-421">Microsoft Azure Active Directory 租用戶中唯一識別碼，用來識別客戶的 GUID 格式。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-421">Unique Microsoft Azure Active Directory tenant ID, in GUID format, used to identify the customer.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="b6a8d-422">[客戶名稱]</span><span class="sxs-lookup"><span data-stu-id="b6a8d-422">Customer Name</span></span></td>
<td><p><span data-ttu-id="b6a8d-423">合作夥伴中心中回報的客戶組織名稱。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-423">Customer's organization name as reported in Partner Center.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="b6a8d-424">CustomerDomainName</span><span class="sxs-lookup"><span data-stu-id="b6a8d-424">CustomerDomainName</span></span></td>
<td><p><span data-ttu-id="b6a8d-425">用來協助識別客戶的客戶網域名稱。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-425">Customer's domain name, used to help identify the customer.</span></span> <span data-ttu-id="b6a8d-426">這不應該用來唯一識別客戶，客戶/合作夥伴可以更新透過 O365 入口網站的虛名/預設網域。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-426">This should not be used to uniquely identify the customer as the customer/partner can update the vanity/default domain via the O365 portal.</span></span> <span data-ttu-id="b6a8d-427">在下一個帳單週期之前，此欄位會是空白的。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-427">This field may appear blank until the second billing cycle.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="b6a8d-428">客戶的國家/地區</span><span class="sxs-lookup"><span data-stu-id="b6a8d-428">Customer Country</span></span></td>
<td><p><span data-ttu-id="b6a8d-429">客戶所在的國家/地區。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-429">The country in which the customer is located.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="b6a8d-430">發票號碼</span><span class="sxs-lookup"><span data-stu-id="b6a8d-430">Invoice number</span></span></td>
<td><p><span data-ttu-id="b6a8d-431">交易的指定位置顯示的發票號碼。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-431">Invoice number where the specified transaction appears.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="b6a8d-432">MpnId</span><span class="sxs-lookup"><span data-stu-id="b6a8d-432">MpnId</span></span></td>
<td><p><span data-ttu-id="b6a8d-433">雲端解決方案提供者合作夥伴的 MPN 識別碼。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-433">MPN ID of the CSP partner.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="b6a8d-434">Reseller MpnId</span><span class="sxs-lookup"><span data-stu-id="b6a8d-434">Reseller MpnId</span></span></td>
<td><p><span data-ttu-id="b6a8d-435">訂閱記錄中的經銷商 MPN 識別碼。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-435">MPN ID of the reseller of record for the subscription.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="b6a8d-436">訂單識別碼</span><span class="sxs-lookup"><span data-stu-id="b6a8d-436">Order ID</span></span></td>
<td><p><span data-ttu-id="b6a8d-437">Microsoft commerce platform 中順序的唯一識別碼。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-437">Unique identifier for an order in the Microsoft commerce platform.</span></span> <span data-ttu-id="b6a8d-438">可在連絡支援時方便識別訂單，但不是用於對帳。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-438">May be useful to identify the order when contacting support but not for reconciliation.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="b6a8d-439">訂單日期</span><span class="sxs-lookup"><span data-stu-id="b6a8d-439">Order date</span></span></td>
<td><p><span data-ttu-id="b6a8d-440">下訂單的日期。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-440">The date the order was placed.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="b6a8d-441">ProductId</span><span class="sxs-lookup"><span data-stu-id="b6a8d-441">ProductId</span></span></td>
<td><p><span data-ttu-id="b6a8d-442">產品的識別碼。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-442">The ID for the product.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="b6a8d-443">SkuId</span><span class="sxs-lookup"><span data-stu-id="b6a8d-443">SkuId</span></span></td>
<td><p><span data-ttu-id="b6a8d-444">特定 SKU 的識別碼。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-444">The ID for a particular SKU.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="b6a8d-445">AvailabilityId</span><span class="sxs-lookup"><span data-stu-id="b6a8d-445">AvailabilityId</span></span></td>
<td><p><span data-ttu-id="b6a8d-446">特定可用性的識別碼。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-446">The ID for a particular Availability.</span></span> <span data-ttu-id="b6a8d-447">「可用性」是指特定 SKU 是否可供特定的國家/地區、貨幣、行業區段等等購買。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-447">“Availability” refers to whether or not a particular SKU is available for purchase for the given country, currency, industry segment, etc.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="b6a8d-448">SKU 名稱</span><span class="sxs-lookup"><span data-stu-id="b6a8d-448">SKU Name</span></span></td>
<td><p><span data-ttu-id="b6a8d-449">特定 SKU 的標題。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-449">The title for a particular SKU.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="b6a8d-450">產品名稱</span><span class="sxs-lookup"><span data-stu-id="b6a8d-450">Product name</span></span></td>
<td><p><span data-ttu-id="b6a8d-451">產品的名稱。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-451">The name of the product.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="b6a8d-452">PublisherName</span><span class="sxs-lookup"><span data-stu-id="b6a8d-452">PublisherName</span></span></td>
<td><p><span data-ttu-id="b6a8d-453">產品的 「 發行者 」 的名稱。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-453">The name of the product’s publisher.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="b6a8d-454">PublisherID</span><span class="sxs-lookup"><span data-stu-id="b6a8d-454">PublisherID</span></span></td>
<td><p><span data-ttu-id="b6a8d-455">這個 「 發行者 」 的唯一識別碼。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-455">Unique ID for this publisher.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="b6a8d-456">訂用帳戶描述</span><span class="sxs-lookup"><span data-stu-id="b6a8d-456">Subscription Description</span></span></td>
<td><p><span data-ttu-id="b6a8d-457">訂用帳戶的易記名稱。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-457">Friendly name of a subscription.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="b6a8d-458">訂閱識別碼</span><span class="sxs-lookup"><span data-stu-id="b6a8d-458">Subscription ID</span></span></td>
<td><p><span data-ttu-id="b6a8d-459">Microsoft 商務平台的訂用帳戶的唯一識別碼。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-459">Unique identifier for a subscription in the Microsoft commerce platform.</span></span> <span data-ttu-id="b6a8d-460">可在連絡支援時方便識別訂閱，但不是用於對帳。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-460">May be useful to identify the subscription when contacting support but not for reconciliation.</span></span> <span data-ttu-id="b6a8d-461">這與合作夥伴管理主控台上的訂閱識別碼不一樣。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-461">This is not the same as the Subscription ID on the Partner Admin Console.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="b6a8d-462">ChargeStartDate</span><span class="sxs-lookup"><span data-stu-id="b6a8d-462">ChargeStartDate</span></span></td>
<td><p><span data-ttu-id="b6a8d-463">開始計算費用的日期。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-463">Start day of the charges.</span></span> <span data-ttu-id="b6a8d-464">時間一律是一天的開始時間 (0:00)。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-464">The time is always the beginning of the day, 0:00.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="b6a8d-465">ChargeEndDate</span><span class="sxs-lookup"><span data-stu-id="b6a8d-465">ChargeEndDate</span></span></td>
<td><p><span data-ttu-id="b6a8d-466">結束計算費用的日期。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-466">End day of the charges.</span></span> <span data-ttu-id="b6a8d-467">時間一律是一天的結束時間 (23:59)。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-467">The time is always the end of the day, 23:59.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="b6a8d-468">詞彙和 Billingcycle</span><span class="sxs-lookup"><span data-stu-id="b6a8d-468">Term and Billingcycle</span></span></td>
<td><p><span data-ttu-id="b6a8d-469">約定期和購買計費週期。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-469">The term length and billing cycle for the purchase.</span></span> <span data-ttu-id="b6a8d-470">比方說，「 1 年，每個月。 」</span><span class="sxs-lookup"><span data-stu-id="b6a8d-470">For example, “1 Year, Monthly.”</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="b6a8d-471">收費類型</span><span class="sxs-lookup"><span data-stu-id="b6a8d-471">Charge Type</span></span></td>
<td><p><span data-ttu-id="b6a8d-472">費用或調整的類型。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-472">The type of charge or adjustment.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="b6a8d-473">單價</span><span class="sxs-lookup"><span data-stu-id="b6a8d-473">Unit Price</span></span></td>
<td><p><span data-ttu-id="b6a8d-474">價格為 pricelist 中發行當時的購買。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-474">The price as published in the pricelist at the time of purchase.</span></span> <span data-ttu-id="b6a8d-475">請確定這與對帳期間儲存在您帳單系統中的資訊相符。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-475">Ensure this matches the information stored in your billing system during reconciliation.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="b6a8d-476">有效的單位價格</span><span class="sxs-lookup"><span data-stu-id="b6a8d-476">Effective Unit Price</span></span></td>
<td><p><span data-ttu-id="b6a8d-477">單價後調整。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-477">The unit price after adjustments have been made.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="b6a8d-478">數量</span><span class="sxs-lookup"><span data-stu-id="b6a8d-478">Quantity</span></span></td>
<td><p><span data-ttu-id="b6a8d-479">單位數。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-479">Number of units.</span></span> <span data-ttu-id="b6a8d-480">請確定這與對帳期間儲存在您帳單系統中的資訊相符。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-480">Ensure this matches the information stored in your billing system during reconciliation.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="b6a8d-481">單位類型</span><span class="sxs-lookup"><span data-stu-id="b6a8d-481">Unit type</span></span></td>
<td><p><span data-ttu-id="b6a8d-482">正在購買的單位類型。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-482">The type of unit being purchased.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="b6a8d-483">DiscountDetails</span><span class="sxs-lookup"><span data-stu-id="b6a8d-483">DiscountDetails</span></span></td>
<td><p><span data-ttu-id="b6a8d-484">說明的任何適用的折扣。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-484">An explanation of any applicable discount.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="b6a8d-485">Sub Total</span><span class="sxs-lookup"><span data-stu-id="b6a8d-485">Sub Total</span></span></td>
<td><p><span data-ttu-id="b6a8d-486">稅前總計。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-486">Total before tax.</span></span> <span data-ttu-id="b6a8d-487">如果有折扣，可檢查小計是否和預期的總金額相符。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-487">Checks that your subtotal matches your expected total, in case of a discount.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="b6a8d-488">稅額總計</span><span class="sxs-lookup"><span data-stu-id="b6a8d-488">Tax Total</span></span></td>
<td><p><span data-ttu-id="b6a8d-489">稅金費用 (根據您所在市場的稅金規則與特定情況)。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-489">Tax amount charge, based on your market's tax rules and specific circumstances.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="b6a8d-490">總計</span><span class="sxs-lookup"><span data-stu-id="b6a8d-490">Total</span></span></td>
<td><p><span data-ttu-id="b6a8d-491">稅後總計。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-491">Total after tax.</span></span> <span data-ttu-id="b6a8d-492">檢查發票中是否向您收取稅金。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-492">Checks if you are charged tax in the invoice.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="b6a8d-493">Currency</span><span class="sxs-lookup"><span data-stu-id="b6a8d-493">Currency</span></span></td>
<td><p><span data-ttu-id="b6a8d-494">貨幣類型。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-494">Currency type.</span></span> <span data-ttu-id="b6a8d-495">每一帳單實體都只有一種貨幣。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-495">Each billing entity has only one currency.</span></span> <span data-ttu-id="b6a8d-496">檢查是否與您的第一張發票相符，然後在進行任何重大帳單平台更新之後檢查。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-496">Check that it matches your first invoice and then after any major billing platform update.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="b6a8d-497">AlternateID</span><span class="sxs-lookup"><span data-stu-id="b6a8d-497">AlternateID</span></span></td>
<td><p><span data-ttu-id="b6a8d-498">替代識別碼至單識別碼。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-498">An alternate identifier to an order ID.</span></span></p></td>
</tr>
</tbody>
</table>


## <a href="" id="dailyratedusagefields"></a><span data-ttu-id="b6a8d-499">每日按比例計算的使用方式檔案欄位</span><span class="sxs-lookup"><span data-stu-id="b6a8d-499">Daily-rated usage file fields</span></span>


<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th><span data-ttu-id="b6a8d-500">「資料行」</span><span class="sxs-lookup"><span data-stu-id="b6a8d-500">Column</span></span></th>
<th><span data-ttu-id="b6a8d-501">描述</span><span class="sxs-lookup"><span data-stu-id="b6a8d-501">Description</span></span></th>
</tr>
</thead>
<tbody>

<tr class="odd">
<td><span data-ttu-id="b6a8d-502">PartnerId</span><span class="sxs-lookup"><span data-stu-id="b6a8d-502">PartnerId</span></span></td>
<td><p><span data-ttu-id="b6a8d-503">合作夥伴識別碼 (GUID 格式)。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-503">Partner ID, in GUID format.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="b6a8d-504">PartnerName</span><span class="sxs-lookup"><span data-stu-id="b6a8d-504">PartnerName</span></span></td>
<td><p><span data-ttu-id="b6a8d-505">合作夥伴名稱。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-505">Partner Name.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="b6a8d-506">CustomerId</span><span class="sxs-lookup"><span data-stu-id="b6a8d-506">CustomerId</span></span></td>
<td><p><span data-ttu-id="b6a8d-507">用來識別客戶的唯一 Microsoft ID（GUID 格式）。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-507">Unique Microsoft ID, in GUID format, used to identify the customer.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="b6a8d-508">CustomerCompanyName</span><span class="sxs-lookup"><span data-stu-id="b6a8d-508">CustomerCompanyName</span></span></td>
<td><p><span data-ttu-id="b6a8d-509">合作夥伴中心中回報的客戶組織名稱。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-509">Customer's organization name as reported in Partner Center.</span></span> <span data-ttu-id="b6a8d-510">這在使用您的系統資訊對帳發票時非常重要。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-510">This is very important for reconciling the invoice with your system information.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="b6a8d-511">CustomerDomainName</span><span class="sxs-lookup"><span data-stu-id="b6a8d-511">CustomerDomainName</span></span></td>
<td><p><span data-ttu-id="b6a8d-512">客戶的網域名稱。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-512">The customer’s domain name.</span></span> <span data-ttu-id="b6a8d-513">不適用於目前的活動。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-513">Not available for current activity.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="b6a8d-514">客戶的國家/地區</span><span class="sxs-lookup"><span data-stu-id="b6a8d-514">Customer country</span></span></td>
<td><p><span data-ttu-id="b6a8d-515">客戶所在的國家/地區。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-515">The country in which the customer is located.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="b6a8d-516">MPNID</span><span class="sxs-lookup"><span data-stu-id="b6a8d-516">MPNID</span></span></td>
<td><p><span data-ttu-id="b6a8d-517">雲端解決方案提供者合作夥伴的 MPN 識別碼。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-517">MPN ID of the CSP partner.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="b6a8d-518">轉銷商 MPNID</span><span class="sxs-lookup"><span data-stu-id="b6a8d-518">Reseller MPNID</span></span></td>
<td><p><span data-ttu-id="b6a8d-519">訂閱記錄中的經銷商 MPN 識別碼。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-519">MPN ID of the reseller of record for the subscription.</span></span> <span data-ttu-id="b6a8d-520">不適用於目前的活動。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-520">Not available for current activity.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="b6a8d-521">InvoiceNumber</span><span class="sxs-lookup"><span data-stu-id="b6a8d-521">InvoiceNumber</span></span></td>
<td><p><span data-ttu-id="b6a8d-522">交易的指定位置顯示的發票號碼。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-522">Invoice number where the specified transaction appears.</span></span> <span data-ttu-id="b6a8d-523">不適用於目前的活動。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-523">Not available for current activity.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="b6a8d-524">ProductId</span><span class="sxs-lookup"><span data-stu-id="b6a8d-524">ProductId</span></span></td>
<td><p><span data-ttu-id="b6a8d-525">產品的識別碼。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-525">The ID for the product.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="b6a8d-526">SkuId</span><span class="sxs-lookup"><span data-stu-id="b6a8d-526">SkuId</span></span></td>
<td><p><span data-ttu-id="b6a8d-527">特定 SKU 的識別碼。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-527">The ID for a particular SKU.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="b6a8d-528">AvailabilityId</span><span class="sxs-lookup"><span data-stu-id="b6a8d-528">AvailabilityId</span></span></td>
<td><p><span data-ttu-id="b6a8d-529">特定可用性的識別碼。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-529">The ID for a particular Availability.</span></span> <span data-ttu-id="b6a8d-530">「可用性」是指特定 SKU 是否可供特定的國家/地區、貨幣、行業區段等等購買。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-530">“Availability” refers to whether or not a particular SKU is available for purchase for the given country, currency, industry segment, etc.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="b6a8d-531">SKU 名稱</span><span class="sxs-lookup"><span data-stu-id="b6a8d-531">SKU Name</span></span></td>
<td><p><span data-ttu-id="b6a8d-532">特定 SKU 的標題。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-532">The title for a particular SKU.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="b6a8d-533">PublisherName</span><span class="sxs-lookup"><span data-stu-id="b6a8d-533">PublisherName</span></span></td>
<td><p><span data-ttu-id="b6a8d-534">發行者的名稱。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-534">The name of the publisher.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="b6a8d-535">PublisherID</span><span class="sxs-lookup"><span data-stu-id="b6a8d-535">PublisherID</span></span></td>
<td><p><span data-ttu-id="b6a8d-536">「 發行者 」 的 GUID 格式的識別碼。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-536">The ID of the publisher, in GUID format.</span></span> <span data-ttu-id="b6a8d-537">不適用於目前的活動。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-537">Not available for current activity.</span></span></p></td>
</tr>

<tr class=”even">
<td><span data-ttu-id="b6a8d-538">訂用帳戶描述</span><span class="sxs-lookup"><span data-stu-id="b6a8d-538">Subscription Description</span></span></td>
<td><p><span data-ttu-id="b6a8d-539">客戶購買的服務優惠名稱，如價目表中所定義。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-539">The name of the service offering purchased by the customer, as defined in the price list.</span></span> <span data-ttu-id="b6a8d-540">（這是優惠名稱的相同欄位）。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-540">(This is an identical field to Offer name).</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="b6a8d-541">訂閱識別碼</span><span class="sxs-lookup"><span data-stu-id="b6a8d-541">Subscription ID</span></span></td>
<td><p><span data-ttu-id="b6a8d-542">訂閱在 Microsoft 帳單平台中的唯一識別碼。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-542">Unique identifier for a subscription in the Microsoft billing platform.</span></span> <span data-ttu-id="b6a8d-543">可在連絡支援時方便識別訂閱，但不是用於對帳。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-543">May be useful to identify the subscription when contacting support but not for reconciliation.</span></span> <span data-ttu-id="b6a8d-544">這與合作夥伴管理主控台上的訂閱識別碼不一樣。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-544">This is not the same as the Subscription ID on the Partner Admin Console.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="b6a8d-545">ChargeStartDate</span><span class="sxs-lookup"><span data-stu-id="b6a8d-545">ChargeStartDate</span></span></td>
<td><p><span data-ttu-id="b6a8d-546">計費週期的開始日期，當顯示之前未收取潛在使用量資料費用的日期時除外 (從前一個計費週期開始)。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-546">Start date of billing cycle except when presenting dates of previously uncharged latent usage data (from previous bill cycle).</span></span> <span data-ttu-id="b6a8d-547">時間一律是一天的開始時間 (0:00)。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-547">The time is always the beginning of the day, 0:00.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="b6a8d-548">ChargeEndDate</span><span class="sxs-lookup"><span data-stu-id="b6a8d-548">ChargeEndDate</span></span></td>
<td><p><span data-ttu-id="b6a8d-549">計費週期的結束日期，當顯示之前未收取潛在使用量資料費用的日期時除外 (從前一個計費週期開始)。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-549">End date of billing cycle except when presenting dates of previously uncharged latent usage data (from previous bill cycle).</span></span> <span data-ttu-id="b6a8d-550">時間一律是一天的結束時間 (23:59)。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-550">The time is always the end of the day, 23:59.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="b6a8d-551">使用日期</span><span class="sxs-lookup"><span data-stu-id="b6a8d-551">Usage Date</span></span></td>
<td><p><span data-ttu-id="b6a8d-552">服務使用量的日期。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-552">Date of service usage.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="b6a8d-553">計量類型</span><span class="sxs-lookup"><span data-stu-id="b6a8d-553">Meter Type</span></span></td>
<td><p><span data-ttu-id="b6a8d-554">計量類型。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-554">The type of meter.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="b6a8d-555">計量類別</span><span class="sxs-lookup"><span data-stu-id="b6a8d-555">Meter Category</span></span></td>
<td><p><span data-ttu-id="b6a8d-556">使用最上層服務。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-556">The top-level service for the usage.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="b6a8d-557">計量識別碼</span><span class="sxs-lookup"><span data-stu-id="b6a8d-557">Meter Id</span></span></td>
<td><p><span data-ttu-id="b6a8d-558">使用計量的識別碼。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-558">The ID for the meter being used.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="b6a8d-559">計量子類別</span><span class="sxs-lookup"><span data-stu-id="b6a8d-559">Meter Sub-category</span></span></td>
<td><p><span data-ttu-id="b6a8d-560">可能影響費率的 Azure 服務的型別。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-560">The type of Azure service that can affect the rate.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="b6a8d-561">計量名稱</span><span class="sxs-lookup"><span data-stu-id="b6a8d-561">Meter Name</span></span></td>
<td><p><span data-ttu-id="b6a8d-562">耗用計量的量值單位。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-562">The unit of measure for the meter being consumed.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="b6a8d-563">計量區域</span><span class="sxs-lookup"><span data-stu-id="b6a8d-563">Meter Region</span></span></td>
<td><p><span data-ttu-id="b6a8d-564">此欄可識別適用及填入此項目之服務地區內的資料中心的位置。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-564">This column identifies the location of a data center within the region for services where this is applicable and populated.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="b6a8d-565">單位</span><span class="sxs-lookup"><span data-stu-id="b6a8d-565">Unit</span></span></td>
<td><p><span data-ttu-id="b6a8d-566">資源名稱的單位。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-566">The unit of the resource Name.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="b6a8d-567">取用的數量</span><span class="sxs-lookup"><span data-stu-id="b6a8d-567">Consumed Quantity</span></span></td>
<td><p><span data-ttu-id="b6a8d-568">報表期間耗用的服務量 (小時、GB 等等)</span><span class="sxs-lookup"><span data-stu-id="b6a8d-568">The amount of service consumed (hours, GB, etc.) during the reporting period.</span></span> <span data-ttu-id="b6a8d-569">同時包括先前報表期間任何未計費的使用量。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-569">Also includes any unbilled usage from previous reporting periods.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="b6a8d-570">資源位置</span><span class="sxs-lookup"><span data-stu-id="b6a8d-570">Resource Location</span></span></td>
<td><p><span data-ttu-id="b6a8d-571">正在執行計量資料中心。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-571">The datacenter where the meter is running.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="b6a8d-572">已使用的服務</span><span class="sxs-lookup"><span data-stu-id="b6a8d-572">Consumed Service</span></span></td>
<td><p><span data-ttu-id="b6a8d-573">您所使用的 Azure 平台服務。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-573">The Azure platform service that you used.</span></span></p></td>
</tr>


<tr class="even">
<td><span data-ttu-id="b6a8d-574">資源 URI</span><span class="sxs-lookup"><span data-stu-id="b6a8d-574">Resource URI</span></span></td>
<td><p><span data-ttu-id="b6a8d-575">正在使用的資源 URI。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-575">The URI of the resource being used.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="b6a8d-576">收費類型</span><span class="sxs-lookup"><span data-stu-id="b6a8d-576">Charge type</span></span></td>
<td><p><span data-ttu-id="b6a8d-577">費用或調整的類型。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-577">The type of charge or adjustment.</span></span> <span data-ttu-id="b6a8d-578">不適用於目前的活動。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-578">Not available for current activity.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="b6a8d-579">單價</span><span class="sxs-lookup"><span data-stu-id="b6a8d-579">Unit price</span></span></td>
<td><p><span data-ttu-id="b6a8d-580">每份授權為 pricelist 中發行當時的購買價格。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-580">Price per license, as published in the pricelist at the time of purchase.</span></span> <span data-ttu-id="b6a8d-581">請確定這與對帳期間儲存在您帳單系統中的資訊相符。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-581">Ensure this matches the information stored in your billing system during reconciliation.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="b6a8d-582">數量</span><span class="sxs-lookup"><span data-stu-id="b6a8d-582">Quantity</span></span></td>
<td><p><span data-ttu-id="b6a8d-583">授權的數目。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-583">Number of licenses.</span></span> <span data-ttu-id="b6a8d-584">請確定這與對帳期間儲存在您帳單系統中的資訊相符。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-584">Ensure this matches the information stored in your billing system during reconciliation.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="b6a8d-585">單位類型</span><span class="sxs-lookup"><span data-stu-id="b6a8d-585">Unit type</span></span></td>
<td><p><span data-ttu-id="b6a8d-586">計量的計費的單位的類型。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-586">The type of unit the meter is charged in.</span></span> <span data-ttu-id="b6a8d-587">不適用於目前的活動。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-587">Not available for current activity.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="b6a8d-588">計費前稅額</span><span class="sxs-lookup"><span data-stu-id="b6a8d-588">Billing pre tax</span></span></td>
<td><p><span data-ttu-id="b6a8d-589">稅前的總金額。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-589">Total amount before taxes.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="b6a8d-590">帳單貨幣</span><span class="sxs-lookup"><span data-stu-id="b6a8d-590">Billing currency</span></span></td>
<td><p><span data-ttu-id="b6a8d-591">客戶的地理區域中的貨幣</span><span class="sxs-lookup"><span data-stu-id="b6a8d-591">The currency in the customer’s geographic region</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="b6a8d-592">定價 pretax 總計</span><span class="sxs-lookup"><span data-stu-id="b6a8d-592">Pricing pretax total</span></span></td>
<td><p><span data-ttu-id="b6a8d-593">定價加入稅金之前。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-593">The pricing before taxes are added.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="b6a8d-594">價格貨幣</span><span class="sxs-lookup"><span data-stu-id="b6a8d-594">Pricing currency</span></span></td>
<td><p><span data-ttu-id="b6a8d-595">在 pricelist 貨幣。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-595">The currency in the pricelist.</span></span></p></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="b6a8d-596">服務資訊 1</span><span class="sxs-lookup"><span data-stu-id="b6a8d-596">Service Info 1</span></span></td>
<td><p><span data-ttu-id="b6a8d-597">於某一天佈建及使用的 ServiceBus 連線數目。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-597">The number of ServiceBus connections that were provisioned and utilized on a given day.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="b6a8d-598">服務資訊 2</span><span class="sxs-lookup"><span data-stu-id="b6a8d-598">Service Info 2</span></span></td>
<td><p><span data-ttu-id="b6a8d-599">舊版欄位，可擷取選擇性服務特定中繼資料。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-599">A legacy field that captures optional service-specific metadata.</span></span></p></td>
</tr>

<tr class="even">
<td><span data-ttu-id="b6a8d-600">其他資訊</span><span class="sxs-lookup"><span data-stu-id="b6a8d-600">Additional Info</span></span></td>
<td><p><span data-ttu-id="b6a8d-601">未涵蓋在其他資料行中的任何其他資訊。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-601">Any additional information not covered in other columns.</span></span></p></td>
</tr>

</tbody>
</table>


## <a href="" id="charge_types"></a><span data-ttu-id="b6a8d-602">發票和對帳檔案之間的對應費用</span><span class="sxs-lookup"><span data-stu-id="b6a8d-602">Mapping charges between an invoice and the reconciliation file</span></span>

<span data-ttu-id="b6a8d-603">您的發票提供費用摘要，而對帳檔案則提供包括費用類型等明細項目交易的詳細細項。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-603">Your invoice provides a summary of charges, while your reconciliation file provides a detailed breakdown of line-item transactions, including charge types.</span></span>

<span data-ttu-id="b6a8d-604">若要交互參照發票和對帳檔案之間的費用金額，您可以使用 Microsoft Excel 篩選選項，在對帳檔案上依費用類型篩選，以便將發票費用對應到對帳檔案上的一組費用細項。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-604">To cross-reference charge amounts between the invoice and reconciliation file, you can use Microsoft Excel's filter options to filter by charge types on the reconciliation file to map the invoice charges to a set of charge breakdowns on reconciliation file.</span></span>

<span data-ttu-id="b6a8d-605">用量型和授權型訂閱的對帳檔案只會顯示交易和費用的相關使用量 (耗用單位和相關的費用)。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-605">Reconciliation files, both usage- and license-based, only show usage related transactions and charges (units consumed and related charges).</span></span> <span data-ttu-id="b6a8d-606">發票上顯示為「調整」的點數、折扣或退款不會出現在對帳檔案中。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-606">One off credits, discounts or refunds which appear on the invoice as “Adjustments” are not shown in the reconciliation file.</span></span>

<span data-ttu-id="b6a8d-607">下表顯示發票區段和對帳檔案上可能會顯示之相關費用類型之間的對應。</span><span class="sxs-lookup"><span data-stu-id="b6a8d-607">The table below shows the mappings between an invoice section and associated charge types that might show up on the reconciliation files.</span></span> 

<table>
<tbody>
<tr>
<td>
<p><span data-ttu-id="b6a8d-608"><strong>發票費用的描述</strong></span><span class="sxs-lookup"><span data-stu-id="b6a8d-608"><strong>Invoice charge description</strong></span></span></p>
</td>
<td>
<p><span data-ttu-id="b6a8d-609"><strong>對帳檔案費用描述 （ChargeType 資料行）</strong></span><span class="sxs-lookup"><span data-stu-id="b6a8d-609"><strong>Reconciliation file charge description (ChargeType column)</strong></span></span></p>
</td>
<td>
<p><span data-ttu-id="b6a8d-610"><strong>此費用是什麼？</strong></span><span class="sxs-lookup"><span data-stu-id="b6a8d-610"><strong>What is this charge?</strong></span></span></p>
</td>
<td>
<p><span data-ttu-id="b6a8d-611"><strong>如何將這些 ChargeTypes 對應到發票？</strong></span><span class="sxs-lookup"><span data-stu-id="b6a8d-611"><strong>How do I map these ChargeTypes to the invoice?</strong></span></span></p>
</td>
</tr>
<tr>
<td rowspan="10">
<p><span data-ttu-id="b6a8d-612"><strong>以授權為基礎的費用</strong></span><span class="sxs-lookup"><span data-stu-id="b6a8d-612"><strong>License-based charges</strong></span></span></p>
</td>
<td>
<p><span data-ttu-id="b6a8d-613">啟用費用</span><span class="sxs-lookup"><span data-stu-id="b6a8d-613">Activation fee</span></span></p>
</td>
<td>
<p><span data-ttu-id="b6a8d-614">當客戶購買後使用訂閱時，向客戶收取的金額</span><span class="sxs-lookup"><span data-stu-id="b6a8d-614">The amount charged to the customer when they use the subscription after purchasing it</span></span></p>
</td>
<td rowspan="10">
<p><span data-ttu-id="b6a8d-615">從授權型檔案，加總 <strong>Amount</strong> 欄</span><span class="sxs-lookup"><span data-stu-id="b6a8d-615">From license-based file, sum the <strong>Amount</strong> column</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="b6a8d-616">取消費用</span><span class="sxs-lookup"><span data-stu-id="b6a8d-616">Cancel fee</span></span></p>
</td>
<td>
<p><span data-ttu-id="b6a8d-617">當關聯的基座變更時，按比例計算退款給客戶的費用</span><span class="sxs-lookup"><span data-stu-id="b6a8d-617">Prorated charges refunded to the customer when associated seats are changed</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="b6a8d-618">循環費用</span><span class="sxs-lookup"><span data-stu-id="b6a8d-618">Cycle fee</span></span></p>
</td>
<td>
<p><span data-ttu-id="b6a8d-619">訂閱的定期費用</span><span class="sxs-lookup"><span data-stu-id="b6a8d-619">Periodic charges for a subscription</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="b6a8d-620">循環執行個體 (依比例計算)</span><span class="sxs-lookup"><span data-stu-id="b6a8d-620">Cycle instance prorate</span></span></p>
</td>
<td>
<p><span data-ttu-id="b6a8d-621">當關聯的基座變更時，按比例計算向客戶收取的費用</span><span class="sxs-lookup"><span data-stu-id="b6a8d-621">Prorated charges assessed from the customer when associated seats are changed</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="b6a8d-622">取消時按比例計算費用</span><span class="sxs-lookup"><span data-stu-id="b6a8d-622">Prorate fees when cancel</span></span></p>
</td>
<td>
<p><span data-ttu-id="b6a8d-623">取消時服務未使用部分之按比例計算的退款</span><span class="sxs-lookup"><span data-stu-id="b6a8d-623">Prorated refund for unused portion of service upon cancellation</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="b6a8d-624">購買時按比例計算費用</span><span class="sxs-lookup"><span data-stu-id="b6a8d-624">Prorate fees when purchase</span></span></p>
</td>
<td>
<p><span data-ttu-id="b6a8d-625">當使用年度計費訂用帳戶收費類型</span><span class="sxs-lookup"><span data-stu-id="b6a8d-625">The charge type for a subscription when using annual billing</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="b6a8d-626">購買費用</span><span class="sxs-lookup"><span data-stu-id="b6a8d-626">Purchase fee</span></span></p>
</td>
<td>
<p><span data-ttu-id="b6a8d-627">當使用每月計費訂用帳戶收費類型</span><span class="sxs-lookup"><span data-stu-id="b6a8d-627">The charge type for a subscription when using monthly billing</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="b6a8d-628">續約時按比例計算費用</span><span class="sxs-lookup"><span data-stu-id="b6a8d-628">Prorate fee when renew</span></span></p>
</td>
<td>
<p><span data-ttu-id="b6a8d-629">訂閱續約時按比例計算的費用</span><span class="sxs-lookup"><span data-stu-id="b6a8d-629">Prorated fees upon subscription renewal</span></span></p>
</td>
</tr>
<tr>

<td>
<p><span data-ttu-id="b6a8d-630">續約費用</span><span class="sxs-lookup"><span data-stu-id="b6a8d-630">Renew fee</span></span></p>
</td>
<td>
<p><span data-ttu-id="b6a8d-631">訂閱續約時的費用</span><span class="sxs-lookup"><span data-stu-id="b6a8d-631">Charge for renewing a subscription</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="b6a8d-632">啟用時按比例計算費用</span><span class="sxs-lookup"><span data-stu-id="b6a8d-632">Prorate fees when activate</span></span></p>
</td>
<td>
<p><span data-ttu-id="b6a8d-633">從啟用到計費期間結束時按比例計算的費用</span><span class="sxs-lookup"><span data-stu-id="b6a8d-633">Prorated fees from activation until end of billing period</span></span></p>
</td>
</tr>



<tr>
<td rowspan="5">
<p><span data-ttu-id="b6a8d-634"><strong>一次性費用</strong></span><span class="sxs-lookup"><span data-stu-id="b6a8d-634"><strong>One-time Charges</strong></span></span></p>

</td>
<td>
<p><span data-ttu-id="b6a8d-635">新的</span><span class="sxs-lookup"><span data-stu-id="b6a8d-635">New</span></span></p>
</td>
<td>
<p><span data-ttu-id="b6a8d-636">建立新的採購單時，使用</span><span class="sxs-lookup"><span data-stu-id="b6a8d-636">Used when a new purchase is created</span></span></p>
</td>

<p></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="b6a8d-637">addQuantity</span><span class="sxs-lookup"><span data-stu-id="b6a8d-637">addQuantity</span></span></p>
</td>
<td>
<p><span data-ttu-id="b6a8d-638">用於原始的購買和新的數量的退款之後增加</span><span class="sxs-lookup"><span data-stu-id="b6a8d-638">Used in both the refund of the original purchase and the new quantity after increase</span></span></p>
</td>
</tr>

</tr>
<tr>
<td>
<p><span data-ttu-id="b6a8d-639">removeQuantity</span><span class="sxs-lookup"><span data-stu-id="b6a8d-639">removeQuantity</span></span></p>
</td>
<td>
<p><span data-ttu-id="b6a8d-640">用於退還原始的購買和新的數量減少之後</span><span class="sxs-lookup"><span data-stu-id="b6a8d-640">Used in both the refund of the original purchase and the new quantity after decrease</span></span></p>
</td>
</tr>

</tr>
<tr>
<td>
<p><span data-ttu-id="b6a8d-641">取消</span><span class="sxs-lookup"><span data-stu-id="b6a8d-641">Cancel</span></span></p>
</td>
<td>
<p><span data-ttu-id="b6a8d-642">已取消訂用帳戶時使用</span><span class="sxs-lookup"><span data-stu-id="b6a8d-642">Used when a subscription is cancelled</span></span></p>
</td>
</tr>

</tr>
<tr>
<td>
<p><span data-ttu-id="b6a8d-643">轉換</span><span class="sxs-lookup"><span data-stu-id="b6a8d-643">Convert</span></span></p>
</td>
<td>
<p><span data-ttu-id="b6a8d-644">升級授權，但是的基座數目會維持不變時使用</span><span class="sxs-lookup"><span data-stu-id="b6a8d-644">Used when a license is upgraded but the number of seats remains unchanged</span></span></p>
</td>
</tr>

<tr>
<td rowspan="2">
<p><span data-ttu-id="b6a8d-645"><strong>使用量費用</strong></span><span class="sxs-lookup"><span data-stu-id="b6a8d-645"><strong>Usage Charges</strong></span></span></p>
</td>
<td>
<p><span data-ttu-id="b6a8d-646">取消時的存取用量費用</span><span class="sxs-lookup"><span data-stu-id="b6a8d-646">Assess usage fee when cancel</span></span></p>
</td>
<td>
<p><span data-ttu-id="b6a8d-647">在目前計費期間中取消時，未支付之使用量的存取用量費用</span><span class="sxs-lookup"><span data-stu-id="b6a8d-647">Access usage fee upon cancellation for unpaid usage during the current billing period</span></span></p>
</td>
<td rowspan="2">
<p><span data-ttu-id="b6a8d-648">從用量型檔案，加總 <strong>PretaxCharges</strong> 欄</span><span class="sxs-lookup"><span data-stu-id="b6a8d-648">From usage-based file, sum the <strong>PretaxCharges</strong> column</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="b6a8d-649">目前週期的存取用量費用</span><span class="sxs-lookup"><span data-stu-id="b6a8d-649">Assess usage fee for current cycle</span></span></p>
</td>
<td>
<p><span data-ttu-id="b6a8d-650">目前計費期間的存取用量費用</span><span class="sxs-lookup"><span data-stu-id="b6a8d-650">Access usage fee for the current billing period</span></span></p>
</td>
</tr>

<tr>
<td>
<p><span data-ttu-id="b6a8d-651"><strong>信用額度</strong></span><span class="sxs-lookup"><span data-stu-id="b6a8d-651"><strong>Credits</strong></span></span></p>
</td>
<td>
<p><span data-ttu-id="b6a8d-652">明細項目位移</span><span class="sxs-lookup"><span data-stu-id="b6a8d-652">Offset a line item</span></span></p>
</td>
<td>
<p><span data-ttu-id="b6a8d-653">明細項目的部分或完整退款 (含稅)</span><span class="sxs-lookup"><span data-stu-id="b6a8d-653">Partial or whole refund to a line item, including taxes</span></span></p>
</td>
<td>
<p><span data-ttu-id="b6a8d-654">從授權型檔案，加總 <strong>TotalForCustomer</strong> 欄</span><span class="sxs-lookup"><span data-stu-id="b6a8d-654">From license-based file, sum the <strong>TotalForCustomer</strong> column</span></span></p>
<p><span data-ttu-id="b6a8d-655">從用量型檔案，加總 <strong>PostTaxTotal</strong> 欄</span><span class="sxs-lookup"><span data-stu-id="b6a8d-655">From usage-based file, sum the <strong>PostTaxTotal</strong> column</span></span></p>
</td>
</tr>
<tr>
<td rowspan="4">
<p><span data-ttu-id="b6a8d-656"><strong>基於使用方式的折扣</strong></span><span class="sxs-lookup"><span data-stu-id="b6a8d-656"><strong>Usage-based discounts</strong></span></span></p>
</td>
<td>
<p><span data-ttu-id="b6a8d-657">啟用折扣</span><span class="sxs-lookup"><span data-stu-id="b6a8d-657">Activation discount</span></span></p>
</td>
<td>
<p><span data-ttu-id="b6a8d-658">啟用訂閱時套用的折扣</span><span class="sxs-lookup"><span data-stu-id="b6a8d-658">Discount applied when subscription activated</span></span></p>
</td>

<td rowspan="4">
<p><span data-ttu-id="b6a8d-659">從用量型檔案，加總 <strong>PretaxCharges</strong> 欄</span><span class="sxs-lookup"><span data-stu-id="b6a8d-659">From usage-based file, sum the <strong>PretaxCharges</strong> column</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="b6a8d-660">循環折扣</span><span class="sxs-lookup"><span data-stu-id="b6a8d-660">Cycle discount</span></span></p>
</td>
<td>
<p><span data-ttu-id="b6a8d-661">套用至定期費用的折扣</span><span class="sxs-lookup"><span data-stu-id="b6a8d-661">Discount applied on periodic charges</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="b6a8d-662">續約折扣</span><span class="sxs-lookup"><span data-stu-id="b6a8d-662">Renew discount</span></span></p>
</td>
<td>
<p><span data-ttu-id="b6a8d-663">訂閱續約時套用的折扣</span><span class="sxs-lookup"><span data-stu-id="b6a8d-663">Discount applied when subscription renewed</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="b6a8d-664">取消折扣</span><span class="sxs-lookup"><span data-stu-id="b6a8d-664">Cancel discount</span></span></p>
</td>
<td>
<p><span data-ttu-id="b6a8d-665">折扣取消時收取的費用</span><span class="sxs-lookup"><span data-stu-id="b6a8d-665">Charges applied when discounts cancelled</span></span></p>
</td>
</tr>


<tr>
<td>
<p><span data-ttu-id="b6a8d-666"><strong>以授權為基礎的折扣</strong></span><span class="sxs-lookup"><span data-stu-id="b6a8d-666"><strong>License-based discounts</strong></span></span></p>
</td>
<td>
<p><span data-ttu-id="b6a8d-667"><em>可套用至多個收費類型</em></span><span class="sxs-lookup"><span data-stu-id="b6a8d-667"><em>May be applied to multiple charge types</em></span></span></p>
</td>
<td>
<p></p>
</td>
<td>
<p><span data-ttu-id="b6a8d-668">從授權型檔案，加總 <strong>TotalOtherDiscount</strong> 欄</span><span class="sxs-lookup"><span data-stu-id="b6a8d-668">From license-based file, sum the <strong>TotalOtherDiscount</strong> column</span></span></p>
</td>
</tr>
<tr>
<td>
<p><span data-ttu-id="b6a8d-669"><strong>稅金</strong>&nbsp;或&nbsp;<strong>加值稅</strong></span><span class="sxs-lookup"><span data-stu-id="b6a8d-669"><strong>Taxes</strong>&nbsp;or&nbsp;<strong>VAT</strong></span></span></p>
</td>
<td>
<p><span data-ttu-id="b6a8d-670"><em>可套用至多個收費類型</em></span><span class="sxs-lookup"><span data-stu-id="b6a8d-670"><em>May be applied to multiple charge types</em></span></span></p>
<p><span data-ttu-id="b6a8d-671"><em>例外狀況：&quot;位移明細項目&quot;已經包含稅金。請參閱上面的信用額度。</em></span><span class="sxs-lookup"><span data-stu-id="b6a8d-671"><em>Exception: &quot;Offset a line item&quot; already includes taxes. See Credits, above.</em></span></span></p>
</td>
<td>
<p><span data-ttu-id="b6a8d-672">稅金或加值稅 (VAT)</span><span class="sxs-lookup"><span data-stu-id="b6a8d-672">Taxes or value-added taxes (VAT)</span></span></p>
</td>
<td>
<p><span data-ttu-id="b6a8d-673">從授權型檔案，加總 <strong>Tax</strong> 欄</span><span class="sxs-lookup"><span data-stu-id="b6a8d-673">From license-based file, sum the <strong>Tax</strong> column</span></span></p>
<p><span data-ttu-id="b6a8d-674">從用量型檔案，加總 <strong>TaxAmount</strong> 欄</span><span class="sxs-lookup"><span data-stu-id="b6a8d-674">From usage-based file, sum the <strong>TaxAmount</strong> column</span></span></p>
</td>
</tr>
</tbody>
</table>
<p>&nbsp;</p>
