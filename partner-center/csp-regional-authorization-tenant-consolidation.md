---
title: CSP regional authorization tenant consolidation | Partner Center
description: Use these instructions to consolidate tenants for different country/regions.
ms.assetid: 749B4C6A-26BE-4942-BDA8-F08C40DF048A
author: MaggiePucciEvans
ms.openlocfilehash: 06709900a4f98c44ef0ae8505928d7c901ee8473
ms.sourcegitcommit: c47f8e765def420017abe290f2f7327eab2cbba7
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 07/07/2017
---
# <a name="csp-regional-authorization-tenant-consolidation"></a><span data-ttu-id="1f1a1-103">CSP regional authorization tenant consolidation</span><span class="sxs-lookup"><span data-stu-id="1f1a1-103">CSP regional authorization tenant consolidation</span></span>

**<span data-ttu-id="1f1a1-104">Applies to</span><span class="sxs-lookup"><span data-stu-id="1f1a1-104">Applies to</span></span>**

-  <span data-ttu-id="1f1a1-105">Partner Center</span><span class="sxs-lookup"><span data-stu-id="1f1a1-105">Partner Center</span></span>
-  <span data-ttu-id="1f1a1-106">Partner Center for Microsoft Cloud for US Government</span><span class="sxs-lookup"><span data-stu-id="1f1a1-106">Partner Center for Microsoft Cloud for US Government</span></span>
-  <span data-ttu-id="1f1a1-107">Partner Center for Microsoft Cloud Germany</span><span class="sxs-lookup"><span data-stu-id="1f1a1-107">Partner Center for Microsoft Cloud Germany</span></span>

<span data-ttu-id="1f1a1-108">\[Some information relates to pre-released product which may be substantially modified before it's commercially released.</span><span class="sxs-lookup"><span data-stu-id="1f1a1-108">\[Some information relates to pre-released product which may be substantially modified before it's commercially released.</span></span> <span data-ttu-id="1f1a1-109">Microsoft makes no warranties, express or implied, with respect to the information provided here.\]</span><span class="sxs-lookup"><span data-stu-id="1f1a1-109">Microsoft makes no warranties, express or implied, with respect to the information provided here.\]</span></span>

<span data-ttu-id="1f1a1-110">Use these instructions to consolidate tenants for different country/regions.</span><span class="sxs-lookup"><span data-stu-id="1f1a1-110">Use these instructions to consolidate tenants for different country/regions.</span></span>

<span data-ttu-id="1f1a1-111">**注意**：您必須知道您從轉換帳戶佈建之客戶的所有訂閱和基座數目。</span><span class="sxs-lookup"><span data-stu-id="1f1a1-111">**Note**  You must be aware of all of the subscriptions and seat counts for your customers provisioned from the transition accounts.</span></span> <span data-ttu-id="1f1a1-112">Partners will be re-provisioning those same exact subscriptions with the same seat counts under the new Central CSP account as part of the migration process.</span><span class="sxs-lookup"><span data-stu-id="1f1a1-112">Partners will be re-provisioning those same exact subscriptions with the same seat counts under the new Central CSP account as part of the migration process.</span></span> <span data-ttu-id="1f1a1-113">Use the export list feature to help create a list of customers to move over to the centralized tenant.</span><span class="sxs-lookup"><span data-stu-id="1f1a1-113">Use the export list feature to help create a list of customers to move over to the centralized tenant.</span></span> <span data-ttu-id="1f1a1-114">Partners choose to consolidate their tenants.</span><span class="sxs-lookup"><span data-stu-id="1f1a1-114">Partners choose to consolidate their tenants.</span></span> <span data-ttu-id="1f1a1-115">Once consolidation is complete, Partners cannot revert to their previous state.</span><span class="sxs-lookup"><span data-stu-id="1f1a1-115">Once consolidation is complete, Partners cannot revert to their previous state.</span></span> <span data-ttu-id="1f1a1-116">Note that customer action is also be required.</span><span class="sxs-lookup"><span data-stu-id="1f1a1-116">Note that customer action is also be required.</span></span>

 

## <a name="prepare-for-migration"></a><span data-ttu-id="1f1a1-117">Prepare for migration</span><span class="sxs-lookup"><span data-stu-id="1f1a1-117">Prepare for migration</span></span>


-   <span data-ttu-id="1f1a1-118">Log on to <https://partnercenter.microsoft.com> with the Transitioning (existing) account and take note of all customers and all of the services provisioned for those customers.</span><span class="sxs-lookup"><span data-stu-id="1f1a1-118">Log on to <https://partnercenter.microsoft.com> with the Transitioning (existing) account and take note of all customers and all of the services provisioned for those customers.</span></span>

![regional customer list](images/regionalcustomer1.png)

## <a name="migrate-customer-accounts"></a><span data-ttu-id="1f1a1-120">Migrate customer accounts</span><span class="sxs-lookup"><span data-stu-id="1f1a1-120">Migrate customer accounts</span></span>


1.  <span data-ttu-id="1f1a1-121">使用轉換 (新) 帳戶登入 <https://partnercenter.microsoft.com>，並從合作夥伴中心儀表板瀏覽至客戶清單。</span><span class="sxs-lookup"><span data-stu-id="1f1a1-121">Log on to <https://partnercenter.microsoft.com> with the Transitioning (new) account and navigate to the Customers list from the Partner Center dashboard.</span></span>

2.  <span data-ttu-id="1f1a1-122">Select Customer.</span><span class="sxs-lookup"><span data-stu-id="1f1a1-122">Select Customer.</span></span>

3.  <span data-ttu-id="1f1a1-123">按一下 **\[要求建立經銷商關係\]**。</span><span class="sxs-lookup"><span data-stu-id="1f1a1-123">Click **Request a reseller relationship**.</span></span> <span data-ttu-id="1f1a1-124">You are presented with a default email message to present to your customers.</span><span class="sxs-lookup"><span data-stu-id="1f1a1-124">You are presented with a default email message to present to your customers.</span></span> <span data-ttu-id="1f1a1-125">This message contains a URL with the org ID unique to your new Partner Center account.</span><span class="sxs-lookup"><span data-stu-id="1f1a1-125">This message contains a URL with the org ID unique to your new Partner Center account.</span></span>

4.  <span data-ttu-id="1f1a1-126">**客戶動作：**確保您要移轉的每個作用中客戶都會造訪此 URL。</span><span class="sxs-lookup"><span data-stu-id="1f1a1-126">**Customer Action:** Ensure that each of the active customers you want to migrate visits this URL.</span></span> <span data-ttu-id="1f1a1-127">When opening the URL, the customer is prompted to sign in to the Office 365 portal.</span><span class="sxs-lookup"><span data-stu-id="1f1a1-127">When opening the URL, the customer is prompted to sign in to the Office 365 portal.</span></span> <span data-ttu-id="1f1a1-128">The customer signs in using the same Org ID that they use to access the Azure and Office 365 admin portals.</span><span class="sxs-lookup"><span data-stu-id="1f1a1-128">The customer signs in using the same Org ID that they use to access the Azure and Office 365 admin portals.</span></span>

5.  <span data-ttu-id="1f1a1-129">After signing in, the Global Admin for the customer account is prompted to submit an agreement to give delegated admin privileges to the new CSP account.</span><span class="sxs-lookup"><span data-stu-id="1f1a1-129">After signing in, the Global Admin for the customer account is prompted to submit an agreement to give delegated admin privileges to the new CSP account.</span></span> <span data-ttu-id="1f1a1-130">If they agree, the customer selects the checkbox and agrees to authorize the relationship.</span><span class="sxs-lookup"><span data-stu-id="1f1a1-130">If they agree, the customer selects the checkbox and agrees to authorize the relationship.</span></span>

<span data-ttu-id="1f1a1-131">The customers will appear in the partner’s customer list after they have submitted the agreement, one by one.</span><span class="sxs-lookup"><span data-stu-id="1f1a1-131">The customers will appear in the partner’s customer list after they have submitted the agreement, one by one.</span></span>

## <a name="migrating-office-365-and-non-azure-usage-based-subscriptions"></a><span data-ttu-id="1f1a1-132">Migrating Office 365 and non-Azure usage-based subscriptions</span><span class="sxs-lookup"><span data-stu-id="1f1a1-132">Migrating Office 365 and non-Azure usage-based subscriptions</span></span>


1.  <span data-ttu-id="1f1a1-133">Once your customer has signed the agreement, you can recreate their subscriptions under your Centralized Partner Tenant.</span><span class="sxs-lookup"><span data-stu-id="1f1a1-133">Once your customer has signed the agreement, you can recreate their subscriptions under your Centralized Partner Tenant.</span></span>

2.  <span data-ttu-id="1f1a1-134">在合作夥伴中心儀表板上，按一下左邊瀏覽中的 **\[客戶\]**</span><span class="sxs-lookup"><span data-stu-id="1f1a1-134">On the Partner Center Dashboard click on **Customers** in the left navigation</span></span>

3.  <span data-ttu-id="1f1a1-135">Open the company name for the customer you want to migrate.</span><span class="sxs-lookup"><span data-stu-id="1f1a1-135">Open the company name for the customer you want to migrate.</span></span>

4.  <span data-ttu-id="1f1a1-136">按一下 **\[新增訂閱\]**。</span><span class="sxs-lookup"><span data-stu-id="1f1a1-136">Click **Add subscription**.</span></span>

5.  <span data-ttu-id="1f1a1-137">Add the correct subscriptions and seat counts from the catalog.</span><span class="sxs-lookup"><span data-stu-id="1f1a1-137">Add the correct subscriptions and seat counts from the catalog.</span></span> <span data-ttu-id="1f1a1-138">檢視 **\[轉換來源\]** 合作夥伴帳戶中提供的資訊。</span><span class="sxs-lookup"><span data-stu-id="1f1a1-138">Verify with the information provided in the **Transitioning From** partner accounts.</span></span>

    ![screenshot of customer list](images/regionalcustomer2.png)

6.  <span data-ttu-id="1f1a1-140">按一下 **\[送出\]**。</span><span class="sxs-lookup"><span data-stu-id="1f1a1-140">Click **Submit.**</span></span>

<span data-ttu-id="1f1a1-141">服務現在就會提供給來自 **\[轉換至\]** 合作夥伴帳戶的客戶。</span><span class="sxs-lookup"><span data-stu-id="1f1a1-141">The services are now provided to the customer from the **Transitioning To** partner account.</span></span>

<span data-ttu-id="1f1a1-142">Repeat these steps to migrate subscriptions for all additional customers.</span><span class="sxs-lookup"><span data-stu-id="1f1a1-142">Repeat these steps to migrate subscriptions for all additional customers.</span></span>

<span data-ttu-id="1f1a1-143">Before proceeding to the next section, ensure all customer subscriptions existing under the **Transitioning From** partner accounts are re-provisioned under the **Transitioning To** partner account.</span><span class="sxs-lookup"><span data-stu-id="1f1a1-143">Before proceeding to the next section, ensure all customer subscriptions existing under the **Transitioning From** partner accounts are re-provisioned under the **Transitioning To** partner account.</span></span>

<span data-ttu-id="1f1a1-144">**Note**  Partners must suspend subscriptions on the **Transitioning From** Partner Tenant account in Partner Center the same day that those subscriptions are transitioned and set up under the **Transitioning To** Partner Tenant account in the Partner Center to ensure double billing does not occur.</span><span class="sxs-lookup"><span data-stu-id="1f1a1-144">**Note**  Partners must suspend subscriptions on the **Transitioning From** Partner Tenant account in Partner Center the same day that those subscriptions are transitioned and set up under the **Transitioning To** Partner Tenant account in the Partner Center to ensure double billing does not occur.</span></span> <span data-ttu-id="1f1a1-145">Support requests will be denied for credits due to any overlap in billing that occurs from not correctly setting the **Transitioning From** subscriptions to disabled.</span><span class="sxs-lookup"><span data-stu-id="1f1a1-145">Support requests will be denied for credits due to any overlap in billing that occurs from not correctly setting the **Transitioning From** subscriptions to disabled.</span></span>

 

## <a name="disabling-the-office-365-subscriptions-under-the-transitioning-from-partner-account"></a><span data-ttu-id="1f1a1-146">Disabling the Office 365 subscriptions under the Transitioning From partner account</span><span class="sxs-lookup"><span data-stu-id="1f1a1-146">Disabling the Office 365 subscriptions under the Transitioning From partner account</span></span>


<span data-ttu-id="1f1a1-147">停用 **\[轉換來源\]** 合作夥伴帳戶底下的雲端解決方案提供者訂閱會停止產生任何未來的帳單。</span><span class="sxs-lookup"><span data-stu-id="1f1a1-147">Disabling the CSP subscription under the **Transitioning From** partner accounts stops any future billing.</span></span> <span data-ttu-id="1f1a1-148">You do not have to manually disable Azure subscriptions, because Azure subscriptions are automatically disabled during the migration process.</span><span class="sxs-lookup"><span data-stu-id="1f1a1-148">You do not have to manually disable Azure subscriptions, because Azure subscriptions are automatically disabled during the migration process.</span></span>

1.  <span data-ttu-id="1f1a1-149">使用 **\[轉換來源\]** 雲端解決方案提供者帳戶登入 <https://partnercenter.microsoft.com>，並瀏覽至客戶清單。</span><span class="sxs-lookup"><span data-stu-id="1f1a1-149">Log on to <https://partnercenter.microsoft.com> with the **Transitioning From** CSP account and navigate to the customer list.</span></span>

2.  <span data-ttu-id="1f1a1-150">Open the customer with subscriptions to disable, and then select the first offer to disable.</span><span class="sxs-lookup"><span data-stu-id="1f1a1-150">Open the customer with subscriptions to disable, and then select the first offer to disable.</span></span>
3.  <span data-ttu-id="1f1a1-151">將訂閱設定為 **\[暫停\]**，然後按一下 **\[送出\]**。</span><span class="sxs-lookup"><span data-stu-id="1f1a1-151">Set the subscription to **suspended**, and then click **submit**.</span></span>

    <span data-ttu-id="1f1a1-152">**注意**：暫停訂閱可確保不會發生重複收費。</span><span class="sxs-lookup"><span data-stu-id="1f1a1-152">**Note**  Suspending the subscription ensures double billing does not occur.</span></span>

     

    <span data-ttu-id="1f1a1-153">訂閱清單上的訂閱會顯示 **\[暫停\]**。</span><span class="sxs-lookup"><span data-stu-id="1f1a1-153">The Subscription shows **suspended** on the subscriptions list.</span></span>

4.  <span data-ttu-id="1f1a1-154">Repeat these steps for all subscriptions under the customer.</span><span class="sxs-lookup"><span data-stu-id="1f1a1-154">Repeat these steps for all subscriptions under the customer.</span></span> <span data-ttu-id="1f1a1-155">確認全部顯示 **\[暫停\]**。</span><span class="sxs-lookup"><span data-stu-id="1f1a1-155">Verify all show **suspended.**</span></span>

5.  <span data-ttu-id="1f1a1-156">Select the next customer on the list and repeat the process of disabling all subscriptions.</span><span class="sxs-lookup"><span data-stu-id="1f1a1-156">Select the next customer on the list and repeat the process of disabling all subscriptions.</span></span>

## <a name="migrating-azure-usage-based-subscriptions"></a><span data-ttu-id="1f1a1-157">Migrating Azure usage-based subscriptions</span><span class="sxs-lookup"><span data-stu-id="1f1a1-157">Migrating Azure usage-based subscriptions</span></span>


<span data-ttu-id="1f1a1-158">Note that Azure usage-based CSP subscriptions do not need to be migrated manually as in the case with Office 365 CSP subscriptions.</span><span class="sxs-lookup"><span data-stu-id="1f1a1-158">Note that Azure usage-based CSP subscriptions do not need to be migrated manually as in the case with Office 365 CSP subscriptions.</span></span> <span data-ttu-id="1f1a1-159">Microsoft Azure Support can migrate the Azure subscriptions as well as all deployed services or resources from the **Transitioning From** CSP reseller accounts to the **Transitioning To** CSP reseller account.</span><span class="sxs-lookup"><span data-stu-id="1f1a1-159">Microsoft Azure Support can migrate the Azure subscriptions as well as all deployed services or resources from the **Transitioning From** CSP reseller accounts to the **Transitioning To** CSP reseller account.</span></span> <span data-ttu-id="1f1a1-160">There will be no disruption of service to the customer during this transition.</span><span class="sxs-lookup"><span data-stu-id="1f1a1-160">There will be no disruption of service to the customer during this transition.</span></span>

1.  <span data-ttu-id="1f1a1-161">Ensure that the customer accounts that need Azure subscriptions migrated have accepted the agreement to be associated with the new **Transitioning To** CSP account.</span><span class="sxs-lookup"><span data-stu-id="1f1a1-161">Ensure that the customer accounts that need Azure subscriptions migrated have accepted the agreement to be associated with the new **Transitioning To** CSP account.</span></span>
2.  <span data-ttu-id="1f1a1-162">Partners notify Microsoft which customer accounts that have Azure subscriptions are ready to migrate, and provides those customer’s company names.</span><span class="sxs-lookup"><span data-stu-id="1f1a1-162">Partners notify Microsoft which customer accounts that have Azure subscriptions are ready to migrate, and provides those customer’s company names.</span></span>
3.  <span data-ttu-id="1f1a1-163">Microsoft migrates the Azure usage-based subscriptions and notifies the partner when the migration is complete.</span><span class="sxs-lookup"><span data-stu-id="1f1a1-163">Microsoft migrates the Azure usage-based subscriptions and notifies the partner when the migration is complete.</span></span>
4.  <span data-ttu-id="1f1a1-164">The partner confirms that the Azure subscription under the **Transitioning From** CSP reseller accounts now shows suspended in the Partner Center under the customer subscriptions section.</span><span class="sxs-lookup"><span data-stu-id="1f1a1-164">The partner confirms that the Azure subscription under the **Transitioning From** CSP reseller accounts now shows suspended in the Partner Center under the customer subscriptions section.</span></span>
5.  <span data-ttu-id="1f1a1-165">The partner confirms that the Azure subscription under the **Transitioning To** CSP reseller account now shows a status of **active** in the Partner Center under the customer subscriptions section.</span><span class="sxs-lookup"><span data-stu-id="1f1a1-165">The partner confirms that the Azure subscription under the **Transitioning To** CSP reseller account now shows a status of **active** in the Partner Center under the customer subscriptions section.</span></span>

    <span data-ttu-id="1f1a1-166">**注意**：停用客戶底下的訂閱並不會改變客戶在客戶清單中的外觀。</span><span class="sxs-lookup"><span data-stu-id="1f1a1-166">**Note**  Disabling the subscriptions under the customer does not change the appearance of the customer in the Customers list.</span></span> <span data-ttu-id="1f1a1-167">There is currently no option to remove customers from the list.</span><span class="sxs-lookup"><span data-stu-id="1f1a1-167">There is currently no option to remove customers from the list.</span></span> <span data-ttu-id="1f1a1-168">合作夥伴未來應避免從客戶的 **\[轉換來源\]** 帳戶將訂閱加回給這些客戶。</span><span class="sxs-lookup"><span data-stu-id="1f1a1-168">Partners should avoid adding subscriptions back to these customers from their **Transitioning From** account in the future.</span></span>

     

6.  <span data-ttu-id="1f1a1-169">請針對您所有客戶底下的所有訂閱重複這些步驟，以停止未來在 **\[轉換來源\]** 帳戶上收費。</span><span class="sxs-lookup"><span data-stu-id="1f1a1-169">Repeat these steps for all subscriptions under all of your customers to stop future charges on the **Transitioning From** account(s).</span></span> <span data-ttu-id="1f1a1-170">The partner will receive one final invoice with a credit for the number of unused days between the day of cancellation and the last day of the billing period.</span><span class="sxs-lookup"><span data-stu-id="1f1a1-170">The partner will receive one final invoice with a credit for the number of unused days between the day of cancellation and the last day of the billing period.</span></span> <span data-ttu-id="1f1a1-171">No future invoices will generate after that final billing period.</span><span class="sxs-lookup"><span data-stu-id="1f1a1-171">No future invoices will generate after that final billing period.</span></span>

### <a name="notes"></a><span data-ttu-id="1f1a1-172">Notes</span><span class="sxs-lookup"><span data-stu-id="1f1a1-172">Notes</span></span>

-   <span data-ttu-id="1f1a1-173">Disabling the subscription from the **Transitioning From** CSP account does not impact end customer’s service provided the service was provisioned from the **Transitioning To** CSP account prior to the disable.</span><span class="sxs-lookup"><span data-stu-id="1f1a1-173">Disabling the subscription from the **Transitioning From** CSP account does not impact end customer’s service provided the service was provisioned from the **Transitioning To** CSP account prior to the disable.</span></span>

-   <span data-ttu-id="1f1a1-174">Subscriptions cannot be used by the customer and do not generate charges when suspended or cancelled.</span><span class="sxs-lookup"><span data-stu-id="1f1a1-174">Subscriptions cannot be used by the customer and do not generate charges when suspended or cancelled.</span></span>

-   <span data-ttu-id="1f1a1-175">There is currently no way to remove a customer from the Customers list completely.</span><span class="sxs-lookup"><span data-stu-id="1f1a1-175">There is currently no way to remove a customer from the Customers list completely.</span></span>

-   <span data-ttu-id="1f1a1-176">**Note**  Partners must suspend subscriptions on the **Transitioning From** Partner Tenant account in Partner Center the same day that those subscriptions are transitioned to and set up under the **Transitioning To** Partner Tenant account in the Partner Center to ensure double billing does not occur.</span><span class="sxs-lookup"><span data-stu-id="1f1a1-176">**Note**  Partners must suspend subscriptions on the **Transitioning From** Partner Tenant account in Partner Center the same day that those subscriptions are transitioned to and set up under the **Transitioning To** Partner Tenant account in the Partner Center to ensure double billing does not occur.</span></span> <span data-ttu-id="1f1a1-177">Microsoft will not support requests for credits due to any overlap in billing which occurs from not correctly setting the **Transitioning From** subscriptions to suspended.</span><span class="sxs-lookup"><span data-stu-id="1f1a1-177">Microsoft will not support requests for credits due to any overlap in billing which occurs from not correctly setting the **Transitioning From** subscriptions to suspended.</span></span>

     

### <a name="simplify-migration-using-export"></a><span data-ttu-id="1f1a1-178">Simplify migration using Export</span><span class="sxs-lookup"><span data-stu-id="1f1a1-178">Simplify migration using Export</span></span>

<span data-ttu-id="1f1a1-179">使用 **\[匯出功能\]**，您就可以擷取您需要在新的合併結構中使用的訂閱：</span><span class="sxs-lookup"><span data-stu-id="1f1a1-179">Using the **Export Function**, you can capture the subscriptions you need to use in your new consolidated structure:</span></span>

1.  <span data-ttu-id="1f1a1-180">按一下您儀表板上的 **\[客戶\]**，來查看您現有結構中客戶的清單。</span><span class="sxs-lookup"><span data-stu-id="1f1a1-180">Click **Customers** on your Dashboard to see the list of customers in your existing structure.</span></span>

2.  <span data-ttu-id="1f1a1-181">Open the desired customer name.</span><span class="sxs-lookup"><span data-stu-id="1f1a1-181">Open the desired customer name.</span></span>

3.  <span data-ttu-id="1f1a1-182">在 **\[訂閱\]** 頁面上，按一下 **\[匯出訂閱\]** 來將訂閱的詳細資料匯出到 Excel 檔案。</span><span class="sxs-lookup"><span data-stu-id="1f1a1-182">On the **Subscriptions** page, click **Export Subscriptions** to export details of subscriptions to an Excel file.</span></span>

4.  <span data-ttu-id="1f1a1-183">Use this list to recreate the subscriptions in your new consolidated tenant.</span><span class="sxs-lookup"><span data-stu-id="1f1a1-183">Use this list to recreate the subscriptions in your new consolidated tenant.</span></span>

### <a name="api-registration"></a><span data-ttu-id="1f1a1-184">API registration</span><span class="sxs-lookup"><span data-stu-id="1f1a1-184">API registration</span></span>

<span data-ttu-id="1f1a1-185">如需 API 註冊的詳細資訊，請[參閱此頁面](https://go.microsoft.com/fwlink/?linkid=847990)。</span><span class="sxs-lookup"><span data-stu-id="1f1a1-185">For more information about API registration, [see this page](https://go.microsoft.com/fwlink/?linkid=847990).</span></span>

## <a name="partner-center-activity-log"></a><span data-ttu-id="1f1a1-186">Partner Center Activity log</span><span class="sxs-lookup"><span data-stu-id="1f1a1-186">Partner Center Activity log</span></span>


<span data-ttu-id="1f1a1-187">With the Activity log, partners can view a record of all customer-affecting changes made on their tenant.</span><span class="sxs-lookup"><span data-stu-id="1f1a1-187">With the Activity log, partners can view a record of all customer-affecting changes made on their tenant.</span></span> <span data-ttu-id="1f1a1-188">This helps partners track changes on a customer tenant.</span><span class="sxs-lookup"><span data-stu-id="1f1a1-188">This helps partners track changes on a customer tenant.</span></span>

**<span data-ttu-id="1f1a1-189">View the Activity log</span><span class="sxs-lookup"><span data-stu-id="1f1a1-189">View the Activity log</span></span>**

1.  <span data-ttu-id="1f1a1-190">從合作夥伴中心儀表板，按一下 **\[活動記錄\]** 連結。</span><span class="sxs-lookup"><span data-stu-id="1f1a1-190">From the Partner Center Dashboard, click the **Activity Log** link.</span></span>
2.  <span data-ttu-id="1f1a1-191">在 **\[活動記錄\]** 頁面上，檢視對客戶帳戶所做的變更。</span><span class="sxs-lookup"><span data-stu-id="1f1a1-191">On the **Activity Log** page, view the changes made to customer accounts.</span></span> <span data-ttu-id="1f1a1-192">若要依照日期篩選活動記錄，請選擇 **\[從\]** 和 **\[到\]** 日期，來減少記錄中選取的記錄數目。</span><span class="sxs-lookup"><span data-stu-id="1f1a1-192">To filter the Activity log by date, pick **from** and **to** dates to narrow the selected records in the log.</span></span> <span data-ttu-id="1f1a1-193">若要在 **\[活動記錄\]** 中依照客戶篩選，請使用搜尋方塊。</span><span class="sxs-lookup"><span data-stu-id="1f1a1-193">To filter by customer in the **Activity log**, use the search box.</span></span>

**<span data-ttu-id="1f1a1-194">Export the Activity log</span><span class="sxs-lookup"><span data-stu-id="1f1a1-194">Export the Activity log</span></span>**

-   <span data-ttu-id="1f1a1-195">按一下 **\[匯出記錄\]** 來將您的活動記錄資料匯出到 CSV 檔案。</span><span class="sxs-lookup"><span data-stu-id="1f1a1-195">Click **Export log** to export your Activity log data to a CSV file.</span></span>

    <span data-ttu-id="1f1a1-196">You can also export the customer list and the subscription list of a single customer (from the customer’s subscription page).</span><span class="sxs-lookup"><span data-stu-id="1f1a1-196">You can also export the customer list and the subscription list of a single customer (from the customer’s subscription page).</span></span>

 

 



