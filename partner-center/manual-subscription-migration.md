---
title: 將 Dynamics AX 訂閱遷移至 Dynamics 365 | 合作夥伴中心
description: Microsoft 引進新一代智慧型商業應用程式 Dynamics 365，它可讓您的組織成長、進化及轉型以滿足您客戶的需求，並掌握新的商機。
ms.assetid: 79787bef-a6e9-4c11-8c3b-f0a77485c0a4
author: MaggiePucciEvans
ms.localizationpriority: medium
ms.openlocfilehash: f5e03825226171b8002b260e1b00a59a5eb53ebb
ms.sourcegitcommit: 123a7f53d633c27eb5f982926d856de47afb1042
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 10/09/2018
ms.locfileid: "4489784"
---
# <a name="migrate-dynamics-ax-subscriptions-to-dynamics-365"></a><span data-ttu-id="47db0-103">將 Dynamics AX 訂閱遷移至 Dynamics 365</span><span class="sxs-lookup"><span data-stu-id="47db0-103">Migrate Dynamics AX subscriptions to Dynamics 365</span></span>

**<span data-ttu-id="47db0-104">適用於</span><span class="sxs-lookup"><span data-stu-id="47db0-104">Applies to</span></span>**

-  <span data-ttu-id="47db0-105">合作夥伴中心</span><span class="sxs-lookup"><span data-stu-id="47db0-105">Partner Center</span></span>

<span data-ttu-id="47db0-106">Microsoft 引進新一代智慧型商業應用程式 Dynamics 365，它可讓您的組織成長、進化及轉型以滿足您客戶的需求，並掌握新的商機。</span><span class="sxs-lookup"><span data-stu-id="47db0-106">Microsoft introduces Dynamics 365, the next generation of intelligent business applications that enable your organization to grow, evolve and transform to meet the needs of your customers and capture new opportunities.</span></span> <span data-ttu-id="47db0-107">Microsoft 在 2016 年 11 月 1 日為客戶引進了新的 Microsoft Dynamics 訂閱方案做為新產品的一部分，該方案與目前的方案類似，但不完全相同。</span><span class="sxs-lookup"><span data-stu-id="47db0-107">As part of the new product, Microsoft introduced new Microsoft Dynamics subscription plans for customers on November 1st, 2016, that are similar but not identical to your current plans.</span></span>

<span data-ttu-id="47db0-108">本文件中的指示說明間接提供者如何將客戶現有的 Microsoft Dynamics AX 訂閱及 Microsoft Dymanics CRM Online 訂閱切換至 Microsoft Dynamics 365。</span><span class="sxs-lookup"><span data-stu-id="47db0-108">The instructions in this document describe how indirect providers can switch customers’ existing Microsoft Dynamics AX subscriptions and Microsoft Dymanics CRM Online subscriptions to Microsoft Dynamics 365.</span></span> <span data-ttu-id="47db0-109">此指示也適用於其他更新至新版本而需要提供者將客戶訂閱遷移至新 SKU 的 Microsoft 產品。</span><span class="sxs-lookup"><span data-stu-id="47db0-109">The instructions also apply to other Microsoft products that update to new versions, requiring providers to migrate customers’ subscriptions to a new SKU.</span></span>

<span data-ttu-id="47db0-110">Microsoft Dynamics CRM Online 和 AX 計畫已淘汰。</span><span class="sxs-lookup"><span data-stu-id="47db0-110">The Microsoft Dynamics CRM Online and AX plans are retired.</span></span>  <span data-ttu-id="47db0-111">自 2017 年 7 月 1 日生效，您已無法續約舊版計畫，現有的 E4 訂閱也不會在到期時自動續約。</span><span class="sxs-lookup"><span data-stu-id="47db0-111">Effective July 1, 2017, you can no longer renew into the legacy plans, also existing E4 subscriptions will not renew automatically when they expire.</span></span>

<span data-ttu-id="47db0-112">當 CRM Online 和 AX 訂閱結束時，將會取消這些訂閱。</span><span class="sxs-lookup"><span data-stu-id="47db0-112">When CRM Online and AX subscriptions end, they will be canceled.</span></span> <span data-ttu-id="47db0-113">為了確保對客戶的持續服務，以下列出可將訂閱即將到期的客戶轉換至支援 SKU 選項的計畫。</span><span class="sxs-lookup"><span data-stu-id="47db0-113">To ensure continuity for customers, plan to transition customers with expiring subscriptions to a supported SKU option, listed below.</span></span> <span data-ttu-id="47db0-114">我們建議在年度訂閱的結束日期之前將客戶移轉至新的訂閱，以避免發生任何客戶服務中斷。</span><span class="sxs-lookup"><span data-stu-id="47db0-114">We recommend moving customers to new subscriptions before the subscription’s yearly end date to avoid any service outages for customers.</span></span> 

<span data-ttu-id="47db0-115">在訂閱的詳細資料頁面上，您會看到這些即將到期訂閱的訂閱狀態已從「在 [日期] 自動續約」變更為「在 [日期] 到期」。</span><span class="sxs-lookup"><span data-stu-id="47db0-115">On the subscription's detail page, you will see that for these expiring subscriptions, the subscription status has changed to "Expires on [date]" from "Auto renews on [date]".</span></span> 

<span data-ttu-id="47db0-116">如果使用 API (CREST 或合作夥伴中心)，您可搭配 [自動續約] = False 屬性評估訂閱結束日期，以探索即將到期的訂閱。在 2017 年 7 月 1 日的訂閱已設定為 [自動續約] = False。</span><span class="sxs-lookup"><span data-stu-id="47db0-116">If you use the API (either CREST or Partner Center), you can discover expiring subscriptions by evaluating the end date of the subscription along with the auto renew = False property.The subscriptions were set to auto renew=False on July 1, 2017.</span></span> <span data-ttu-id="47db0-117">您可以隨時將客戶移轉至新的計畫。</span><span class="sxs-lookup"><span data-stu-id="47db0-117">You can move customers to a new plan at any time.</span></span> 

**<span data-ttu-id="47db0-118">Microsoft Dynamics AX 授權變更</span><span class="sxs-lookup"><span data-stu-id="47db0-118">Microsoft Dynamics AX licensing changes</span></span>**

<span data-ttu-id="47db0-119">Microsoft Dynamics AX 產品線已於 2016 年 11 月 1 日淘汰。</span><span class="sxs-lookup"><span data-stu-id="47db0-119">The Microsoft Dynamics AX product line was retired, effective November 1st, 2016.</span></span> <span data-ttu-id="47db0-120">若要深入了解 Dynamics 365 的新授權選項，請檢閱[授權指南](http://download.microsoft.com/documents/dynamics/pricing/Dynamics_365_Enterprise_edition_Licensing_Guide.pdf)。</span><span class="sxs-lookup"><span data-stu-id="47db0-120">To learn more about the new licensing options for Dynamics 365, review the [Licensing Guide](http://download.microsoft.com/documents/dynamics/pricing/Dynamics_365_Enterprise_edition_Licensing_Guide.pdf).</span></span>

 <span data-ttu-id="47db0-121">請參閱下表以了解授權對應的詳細資料：</span><span class="sxs-lookup"><span data-stu-id="47db0-121">Refer to the following table for details on license mapping:</span></span>

|**<span data-ttu-id="47db0-122">淘汰的 SKU</span><span class="sxs-lookup"><span data-stu-id="47db0-122">Retired SKU</span></span>**   |**<span data-ttu-id="47db0-123">Dynamics 365 SKU</span><span class="sxs-lookup"><span data-stu-id="47db0-123">Dynamics 365 SKU</span></span>**   |
|-------------------|:----------------------|
|<span data-ttu-id="47db0-124">Enterprise SKU</span><span class="sxs-lookup"><span data-stu-id="47db0-124">Enterprise SKU</span></span>|<span data-ttu-id="47db0-125">Microsoft Dynamics 365 for Unified Operations 或 Microsoft Dynamics 365 計畫</span><span class="sxs-lookup"><span data-stu-id="47db0-125">Microsoft Dynamics 365 for Unified Operations or Microsoft Dynamics 365 Plan</span></span> |
|<span data-ttu-id="47db0-126">工作</span><span class="sxs-lookup"><span data-stu-id="47db0-126">Task</span></span>|<span data-ttu-id="47db0-127">Microsoft Dynamics 365 for Activity</span><span class="sxs-lookup"><span data-stu-id="47db0-127">Microsoft Dynamics 365 for Activity</span></span>
|<span data-ttu-id="47db0-128">工作/自助</span><span class="sxs-lookup"><span data-stu-id="47db0-128">Task/self service</span></span>|<span data-ttu-id="47db0-129">Microsoft Dynamics 365 for Team Members</span><span class="sxs-lookup"><span data-stu-id="47db0-129">Microsoft Dynamics 365 for Team Members</span></span>|
|<span data-ttu-id="47db0-130">裝置</span><span class="sxs-lookup"><span data-stu-id="47db0-130">Device</span></span>|<span data-ttu-id="47db0-131">Microsoft Dynamics 365 for Operations Device</span><span class="sxs-lookup"><span data-stu-id="47db0-131">Microsoft Dynamics 365 for Operations Device</span></span>|

## <a name="microsoft-dynamics-crm-online-licensing-changes"></a><span data-ttu-id="47db0-132">Microsoft Dynamics CRM Online 授權變更</span><span class="sxs-lookup"><span data-stu-id="47db0-132">Microsoft Dynamics CRM Online licensing changes</span></span> 

**<span data-ttu-id="47db0-133">Microsoft Dynamics CRM Online</span><span class="sxs-lookup"><span data-stu-id="47db0-133">Microsoft Dynamics CRM Online</span></span>**

<span data-ttu-id="47db0-134">目前的 Microsoft Dynamics CRM Online 方案已於 2016 年 11 月 1 日淘汰。</span><span class="sxs-lookup"><span data-stu-id="47db0-134">The current Microsoft Dynamics CRM Online plan was retired effective November 1, 2016.</span></span> <span data-ttu-id="47db0-135">若要深入了解 Microsoft Dynamics 365 的新授權選項，請檢閱[授權指南](http://download.microsoft.com/documents/dynamics/pricing/Dynamics_365_Enterprise_edition_Licensing_Guide.pdf)。</span><span class="sxs-lookup"><span data-stu-id="47db0-135">To learn more about the new licensing options for microsoft Dynaics 365, review the [licensing guide](http://download.microsoft.com/documents/dynamics/pricing/Dynamics_365_Enterprise_edition_Licensing_Guide.pdf).</span></span> <span data-ttu-id="47db0-136">請參閱 [給 CRM Online 客戶的重要資訊](https://go.microsoft.com/fwlink/?linkid=831667)以深入了解新的授權選項。</span><span class="sxs-lookup"><span data-stu-id="47db0-136">See [Important information for CRM Online customers](https://go.microsoft.com/fwlink/?linkid=831667) to find out more about new licensing options.</span></span>

<span data-ttu-id="47db0-137">請參閱下表以了解授權對應的詳細資料：</span><span class="sxs-lookup"><span data-stu-id="47db0-137">Refer to the following table for details on license mapping:</span></span>

|**<span data-ttu-id="47db0-138">淘汰的 SKU</span><span class="sxs-lookup"><span data-stu-id="47db0-138">Retired SKU</span></span>**   |**<span data-ttu-id="47db0-139">Dynamics 365 SKU</span><span class="sxs-lookup"><span data-stu-id="47db0-139">Dynamics 365 SKU</span></span>**   |
|-------------------|:----------------------|
|<span data-ttu-id="47db0-140">Enterprise</span><span class="sxs-lookup"><span data-stu-id="47db0-140">Enterprise</span></span>|<span data-ttu-id="47db0-141">Dynamics 365 Enterprise Customer Engagement Plan</span><span class="sxs-lookup"><span data-stu-id="47db0-141">Dynamics 365 Enterprise Customer Engagement Plan</span></span> |
|<span data-ttu-id="47db0-142">Professional</span><span class="sxs-lookup"><span data-stu-id="47db0-142">Professional</span></span>|<span data-ttu-id="47db0-143">Dynamics 365 Enterprise Customer Engagement Plan、Dynamics 365 for Sales 或 Dynamics 365 for Customer Service</span><span class="sxs-lookup"><span data-stu-id="47db0-143">Dynamics 365 Enterprise Customer Engagement Plan, Dynamics 365 for Sales, or Dynamics 365 for Customer Service</span></span>|
|<span data-ttu-id="47db0-144">Basic</span><span class="sxs-lookup"><span data-stu-id="47db0-144">Basic</span></span>|<span data-ttu-id="47db0-145">Dynamics 365 for Team Members、Dynamics 365 for Sales、Dynamics 365 for Customer Service 或 Dynamics 365 Enterprise Customer Engagement Plan</span><span class="sxs-lookup"><span data-stu-id="47db0-145">Dynamics 365 for Team Members, Dynamics 365 for Sales, Dynamics 365 for Customer Service, or Dynamics 365 Enterprise Customer Engagement Plan</span></span>|
|<span data-ttu-id="47db0-146">Essential</span><span class="sxs-lookup"><span data-stu-id="47db0-146">Essential</span></span>|<span data-ttu-id="47db0-147">Dynamics 365 for Team Members</span><span class="sxs-lookup"><span data-stu-id="47db0-147">Dynamics 365 for Team Members</span></span>|
|<span data-ttu-id="47db0-148">現場服務附加元件</span><span class="sxs-lookup"><span data-stu-id="47db0-148">Field service add-on</span></span>|<span data-ttu-id="47db0-149">Dynamics 365 Enterprise Customer Engagement Plan 或 Dynamics 365 for Field Service</span><span class="sxs-lookup"><span data-stu-id="47db0-149">Dynamics 365 Enterprise Customer Engagement Plan or Dynamics 365 for Field Service</span></span>|
|<span data-ttu-id="47db0-150">專案服務自動化附加元件</span><span class="sxs-lookup"><span data-stu-id="47db0-150">Project Service Authomation Add-on</span></span>|<span data-ttu-id="47db0-151">Dynamics 365 Customer Engagement Plan 或 Dynamics 365 for Project Service Automation</span><span class="sxs-lookup"><span data-stu-id="47db0-151">Dynamics 365 Customer Engagement Plan or Dynamics 365 for Project Service Automation</span></span>|



## <a name="transition-customers-to-new-product-plans"></a><span data-ttu-id="47db0-152">將客戶轉換到新產品計畫</span><span class="sxs-lookup"><span data-stu-id="47db0-152">Transition customers to new product plans</span></span>


<span data-ttu-id="47db0-153">Microsoft 會持續提供新的產品及服務給經銷商和提供者。</span><span class="sxs-lookup"><span data-stu-id="47db0-153">Microsoft continuously offers new products and services to resellers and providers.</span></span> <span data-ttu-id="47db0-154">在這些情況下，經銷商可能需要將客戶升級到新服務，或是從最後將會關閉的 SKU 移轉其訂閱。</span><span class="sxs-lookup"><span data-stu-id="47db0-154">In these cases, a reseller may need to upgrade customers to new services or migrate their subscriptions from SKUs that will eventually be shut down.</span></span> <span data-ttu-id="47db0-155">將客戶從舊的 SKU 移轉到較新的 SKU 時需要依照以下順序執行：</span><span class="sxs-lookup"><span data-stu-id="47db0-155">Migrating customers from old SKUs to newer ones requires the following sequence:</span></span>

-   <span data-ttu-id="47db0-156">[購買新訂閱](#manual-subscription-migration-purchasenewsubsc)；</span><span class="sxs-lookup"><span data-stu-id="47db0-156">[Purchase the new subscription](#manual-subscription-migration-purchasenewsubsc);</span></span>
-   <span data-ttu-id="47db0-157">[重新指派目前的使用者授權](#manual-subscription-migration-reassignlicenses)；</span><span class="sxs-lookup"><span data-stu-id="47db0-157">[Re-assign current user licenses](#manual-subscription-migration-reassignlicenses);</span></span>
-   <span data-ttu-id="47db0-158">[取消舊訂閱](#manual-subscription-migration-cancelsubscriptions)。</span><span class="sxs-lookup"><span data-stu-id="47db0-158">[Cancel the old subscription](#manual-subscription-migration-cancelsubscriptions).</span></span>

<span data-ttu-id="47db0-159">在下列程序中，您會將客戶從 Microsoft Dynamics AX 或 CRM Online 移轉至 Dynamics 365。</span><span class="sxs-lookup"><span data-stu-id="47db0-159">In the following procedures, you move a customer from Microsoft Dynamics AX or CRM Online to Dynamics 365.</span></span>

<span data-ttu-id="47db0-160">在此範例中，經銷商需要將擁有現有 Dynamics AX Enterprise 訂閱的客戶移轉至 Dynamics 365 for Operations。</span><span class="sxs-lookup"><span data-stu-id="47db0-160">In this example, the reseller needs to move a customer with an existing subscription for Dynamics AX Enterprise to Dynamics 365 for Operations.</span></span> <span data-ttu-id="47db0-161">您的第一個步驟是購買 Dynamics 365 for Operations。</span><span class="sxs-lookup"><span data-stu-id="47db0-161">Your first step is to purchase Dynamics 365 for Operations.</span></span>  <span data-ttu-id="47db0-162">針對即將移轉至 Microsoft Dynamics 365 的 CRM Online 客戶重複下列步驟。</span><span class="sxs-lookup"><span data-stu-id="47db0-162">Repeat these steps for a CRM Online customer moving to Microsoft Dynamics 365.</span></span>

<a href="" id="purchasenewsubsc"></a>

**<span data-ttu-id="47db0-163">購買新訂閱</span><span class="sxs-lookup"><span data-stu-id="47db0-163">Purchase the new subscription</span></span>**

1.  <span data-ttu-id="47db0-164">在**合作夥伴中心**功能表中，選取**客戶**，選取您想要移動的客戶，選擇 [**新增訂閱**。</span><span class="sxs-lookup"><span data-stu-id="47db0-164">From the **Partner Center** menu, select **Customers**, select the customer you wish to move, and choose **Add Subscriptions**.</span></span>
2.  <span data-ttu-id="47db0-165">選取您要從型錄購買的訂閱 (在此案例中為 Dynamics 365 for Operations Enterprise Edition)，輸入授權數量，然後選擇 **\[送出\]**。</span><span class="sxs-lookup"><span data-stu-id="47db0-165">Select the subscription you want to purchase from the catalog (in this case, Dynamics 365 for Operations, Enterprise Edition), enter the number of licenses, and choose **Submit**.</span></span>

    <span data-ttu-id="47db0-166">您的客戶現在應該會同時有舊的和新的訂閱：在本範例中，舊的訂閱為 Dynamics AX Enterprise，新的「目標」訂閱為 Dynamics 365 for Operations Enterprise Edition。</span><span class="sxs-lookup"><span data-stu-id="47db0-166">Your customer should now have both old and new subscriptions: in this example, the old Dynamics AX Enterprise, and the new ‘target’ subscription, Dynamics 365 for Operations, Enterprise Edition.</span></span>

<a href="" id="reassignlicenses"></a><span data-ttu-id="47db0-167">下一步是將所有現有的使用者授權重新指派到新訂閱。</span><span class="sxs-lookup"><span data-stu-id="47db0-167">The next step is to reassign all existing user licenses to the new subscription.</span></span>

**<span data-ttu-id="47db0-168">重新指派使用者授權</span><span class="sxs-lookup"><span data-stu-id="47db0-168">Reassign user licenses</span></span>**

1.  <span data-ttu-id="47db0-169">在**合作夥伴中心**功能表中，選取**客戶**，選取您想要移動的客戶，選擇**使用者和授權**。</span><span class="sxs-lookup"><span data-stu-id="47db0-169">From the **Partner Center** menu, select **Customers**, select the customer you wish to move, and choose **Users and licenses**.</span></span> <span data-ttu-id="47db0-170">客戶的 \[使用者與授權\] 頁面隨即開啟。</span><span class="sxs-lookup"><span data-stu-id="47db0-170">The customer’s Users and Licenses page opens.</span></span>
2.  <span data-ttu-id="47db0-171">若要重新指派使用者授權，請選取要重新指派的使用者，然後選取 **\[管理授權\]**。</span><span class="sxs-lookup"><span data-stu-id="47db0-171">To re-assign user licenses, select the user to reassign and then select **Manage licenses**.</span></span>
3.  <span data-ttu-id="47db0-172">在 **\[管理授權\]** 頁面上，清除 **\[Dynamics AX Enterprise\]** 授權核取方塊，並選取 **\[Dynamics 365 for Operations\]** 授權。</span><span class="sxs-lookup"><span data-stu-id="47db0-172">On the **Manage licenses** page, clear the **Dynamics AX Enterprise** license check box and select the **Dynamics 365 for Operations** license.</span></span>
4.  <span data-ttu-id="47db0-173">選取 **\[送出\]**。</span><span class="sxs-lookup"><span data-stu-id="47db0-173">Select **Submit**.</span></span> <span data-ttu-id="47db0-174">確認頁面會列出新的授權指派。</span><span class="sxs-lookup"><span data-stu-id="47db0-174">A confirmation page lists the new license assignments.</span></span>
5.  <span data-ttu-id="47db0-175">針對需要重新指派授權的任何其他客戶使用者繼續執行相同步驟。</span><span class="sxs-lookup"><span data-stu-id="47db0-175">Continue the same steps with any other customer users that need license reassignment.</span></span>

<a href="" id="cancelsubscriptions"></a><span data-ttu-id="47db0-176">將使用者授權移至新服務後，您就可以放心地取消最上層 \[客戶\] 的舊訂閱。</span><span class="sxs-lookup"><span data-stu-id="47db0-176">After moving the user licenses to the new service, you can safely cancel the old subscription at the top Customer level.</span></span>

**<span data-ttu-id="47db0-177">取消舊訂閱</span><span class="sxs-lookup"><span data-stu-id="47db0-177">Cancel the old subscription</span></span>**

1.  <span data-ttu-id="47db0-178">在**合作夥伴中心**功能表中，選取**客戶**，選取您想要移動的客戶，並選取您想要取消的訂閱。</span><span class="sxs-lookup"><span data-stu-id="47db0-178">From the **Partner Center** menu, select **Customers**, select the customer you wish to move, and select the subscription you want to cancel.</span></span>
2.  <span data-ttu-id="47db0-179">在訂閱詳細資料頁面中，將訂閱的 **\[狀態\]** 設定為 **\[暫停\]**。</span><span class="sxs-lookup"><span data-stu-id="47db0-179">In the subscription details page, set the subscription **Status** to **Suspended**.</span></span>
3.  <span data-ttu-id="47db0-180">選取 **\[送出\]**。</span><span class="sxs-lookup"><span data-stu-id="47db0-180">Select **Submit**.</span></span>

<span data-ttu-id="47db0-181">舊訂閱已暫停，而新訂閱為使用中。</span><span class="sxs-lookup"><span data-stu-id="47db0-181">The old subscription is suspended, and the new subscription is active.</span></span> <span data-ttu-id="47db0-182">暫停的訂閱將在 120 天後自動解除佈建。</span><span class="sxs-lookup"><span data-stu-id="47db0-182">The suspended subscription will automatically be de-provisioned after 120 days.</span></span> <span data-ttu-id="47db0-183">客戶不會因為舊訂閱而產生額外費用。</span><span class="sxs-lookup"><span data-stu-id="47db0-183">The customer incurs no additional costs for the old subscription.</span></span>

## <a name="additional-considerations"></a><span data-ttu-id="47db0-184">其他考量</span><span class="sxs-lookup"><span data-stu-id="47db0-184">Additional considerations</span></span>


<span data-ttu-id="47db0-185">如果您的客戶是從 Open Channel 移至雲端服務計畫以獲得進一步的訂閱佈建，您也必須移轉他們現有的訂閱：</span><span class="sxs-lookup"><span data-stu-id="47db0-185">If your customer is moving from the Open Channel to the Cloud Services Program for further subscription provisioning, you will also need to migrate their existing subscriptions:</span></span>

-   <span data-ttu-id="47db0-186">如果客戶是透過 Open Channel 接收舊訂閱，則移至新 SKU 上的雲端解決方案提供者就會非常簡單。</span><span class="sxs-lookup"><span data-stu-id="47db0-186">If the customer received their old subscription through the Open Channel, moving to the CSP on the new SKU is straightforward.</span></span>
-   <span data-ttu-id="47db0-187">如果客戶尚未建立為您的客戶，您可以邀請他們。</span><span class="sxs-lookup"><span data-stu-id="47db0-187">If the customer is not yet established as your customer, you can invite them.</span></span> <span data-ttu-id="47db0-188">如需詳細資訊，請參閱[要求與客戶建立關係](https://msdn.microsoft.com/en-us/library/partnercenter/mt750320.aspx)說明主題。</span><span class="sxs-lookup"><span data-stu-id="47db0-188">For information, see the [Request a relationship with a customer](https://msdn.microsoft.com/en-us/library/partnercenter/mt750320.aspx) help topic.</span></span>

<span data-ttu-id="47db0-189">客戶接受您成為其間接提供者之後，佈建步驟幾乎與上述步驟相同：您要購買新訂閱，然後指派使用者授權。</span><span class="sxs-lookup"><span data-stu-id="47db0-189">After the customer accepts you as their indirect provider, the provisioning steps are mostly the same as described above: you purchase the new subscription, and then assign the user licenses.</span></span> <span data-ttu-id="47db0-190">唯一的不同是取消舊訂閱。</span><span class="sxs-lookup"><span data-stu-id="47db0-190">The only difference involves cancellation of old subscription(s).</span></span> <span data-ttu-id="47db0-191">新的提供者無法暫停/取消透過其他通路取得的訂閱。</span><span class="sxs-lookup"><span data-stu-id="47db0-191">A new provider cannot cancel suspend/cancel subscriptions acquired via other channels.</span></span> <span data-ttu-id="47db0-192">如果客戶是在另一個銷售通路 (例如 Open Channel) 取得舊訂閱，客戶就必須透過該通路自行取消。</span><span class="sxs-lookup"><span data-stu-id="47db0-192">If the customer acquired prior subscriptions in another sales channel, such as the Open channel, the customer will need to cancel it themselves through that channel.</span></span>

 

 



