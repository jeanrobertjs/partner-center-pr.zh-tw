---
title: 從 Basic （完整的供應項目） 的 Dynamics 365 和客戶參與計劃移轉至較新版本 |合作夥伴中心
ms.topic: article
ms.date: 12/12/2018
description: Dynamics 365 for Sales / 客戶參與計劃從 Basic （限定提供） 的訂用帳戶可以不會再更新。
ms.assetid: 79787bef-a6e9-4c11-8c3b-f0a77485c0a4
author: LauraBrenner
ms.author: labrenne
ms.localizationpriority: medium
ms.custom: seodec18
Keywords: Dynamics 365 供應項目，更新供應項目，新的 Dynamics 365 Sku
ms.openlocfilehash: e5128abe71cfab4e2cdabb0cafcd5fd7df56b116
ms.sourcegitcommit: 4c34d6fcaf020bcc53eaa5f0379011a56149a14f
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 03/05/2019
ms.locfileid: "57586941"
---
# <a name="migrate-dynamics-365-and-customer-engagement-plan-from-basic-qualified-offers-to-newer-versions"></a><span data-ttu-id="329b0-104">將 Dynamics 365 和 Customer Engagement Plan 從基本 （合格的供應項目） 移轉至較新版本</span><span class="sxs-lookup"><span data-stu-id="329b0-104">Migrate Dynamics 365 and Customer Engagement Plan from Basic (qualified offers) to newer versions</span></span>

<span data-ttu-id="329b0-105">**適用於**</span><span class="sxs-lookup"><span data-stu-id="329b0-105">**Applies to**</span></span>

-  <span data-ttu-id="329b0-106">合作夥伴中心</span><span class="sxs-lookup"><span data-stu-id="329b0-106">Partner Center</span></span>

<span data-ttu-id="329b0-107">有效 2019 年 1 月 1 日，客戶與銷售的 Dynamics 365 Customer Engagement 計劃從 Basic （限定提供） 的訂用帳戶可以不再更新這些舊版的供應項目; /過期時，現有的訂用帳戶將不會自動續訂。</span><span class="sxs-lookup"><span data-stu-id="329b0-107">Effective January 1, 2019, customers with Dynamics 365 for Sales/ Customer Engagement Plan from Basic (Qualified Offers) subscriptions can no longer renew these legacy offers; existing subscriptions will not renew automatically when they expire.</span></span> <span data-ttu-id="329b0-108">在訂用帳戶的詳細資料頁面上，訂閱狀態會變更為 「 [date] 到期 」 從 「 自動更新於 [date]"。</span><span class="sxs-lookup"><span data-stu-id="329b0-108">On the subscription’s detail page, the subscription status will change to "Expires on [date]" from "Auto renews on [date]".</span></span> 


<span data-ttu-id="329b0-109">若要確保持續性的客戶，您應該先即將過期的訂用帳戶支援的選項下, 面所列的轉換。</span><span class="sxs-lookup"><span data-stu-id="329b0-109">To ensure continuity for customers, you should transition those with expiring subscriptions to a supported option, listed below.</span></span> <span data-ttu-id="329b0-110">我們建議在年度訂閱的結束日期之前將客戶移至新的訂閱，以避免提供客戶的服務中斷。</span><span class="sxs-lookup"><span data-stu-id="329b0-110">We recommend moving customers to new subscriptions before the subscription’s yearly end date to avoid any service outages for customers.</span></span>

<span data-ttu-id="329b0-111">如果您使用 API （CREST 或合作夥伴中心），您可以找到 即將過期的訂用帳戶，藉由評估結束日期的訂用帳戶，以及自動續訂 = False 的屬性。</span><span class="sxs-lookup"><span data-stu-id="329b0-111">If you use the API (either CREST or Partner Center), you can find expiring subscriptions by evaluating the end date of the subscription along with the auto renew = False property.</span></span> <span data-ttu-id="329b0-112">有問題的訂用帳戶將會設定為自動續約於 2019 年 1 月 1 日 = False。</span><span class="sxs-lookup"><span data-stu-id="329b0-112">The subscriptions in question will be set to auto renew=False on Jan 1, 2019.</span></span> <span data-ttu-id="329b0-113">您可以隨時將客戶移轉至新的方案。</span><span class="sxs-lookup"><span data-stu-id="329b0-113">You can move customers to a new plan at any time.</span></span> 

### <a name="the-dynamics-365-offers-being-retired"></a><span data-ttu-id="329b0-114">Dynamics 365 提供即將淘汰</span><span class="sxs-lookup"><span data-stu-id="329b0-114">The Dynamics 365 offers being retired</span></span>

- <span data-ttu-id="329b0-115">Dynamics 365 for Sales 企業版 CRMOL Basic （完整的供應項目）</span><span class="sxs-lookup"><span data-stu-id="329b0-115">Dynamics 365 for Sales Enterprise Edition CRMOL Basic (Qualified Offer)</span></span>
- <span data-ttu-id="329b0-116">Dynamics 365 for Sales 企業版 CRMOL Basic 教職員版 （完整的供應項目）</span><span class="sxs-lookup"><span data-stu-id="329b0-116">Dynamics 365 for Sales Enterprise Edition CRMOL Basic (Qualified Offer) for Faculty</span></span>
- <span data-ttu-id="329b0-117">Dynamics 365 for Sales 企業版 CRMOL Basic 學生版 （完整的供應項目）</span><span class="sxs-lookup"><span data-stu-id="329b0-117">Dynamics 365 for Sales Enterprise Edition CRMOL Basic (Qualified Offer) for Students</span></span>
- <span data-ttu-id="329b0-118">Dynamics 365 for Sales 企業版 （政府定價） CRMOL Basic （完整的供應項目）</span><span class="sxs-lookup"><span data-stu-id="329b0-118">Dynamics 365 for Sales Enterprise Edition (Government Pricing) CRMOL Basic (Qualified Offer)</span></span>
- <span data-ttu-id="329b0-119">Dynamics 365 for Sales 企業版來自 SA 的 CRM Basic （完整的供應項目）</span><span class="sxs-lookup"><span data-stu-id="329b0-119">Dynamics 365 for Sales Enterprise Edition From SA for CRM Basic (Qualified Offer)</span></span>
- <span data-ttu-id="329b0-120">Dynamics 365 for Sales 企業版來自 SA 的 CRM Basic 教職員版 （完整的供應項目）</span><span class="sxs-lookup"><span data-stu-id="329b0-120">Dynamics 365 for Sales Enterprise Edition From SA for CRM Basic (Qualified Offer) for Faculty</span></span>
- <span data-ttu-id="329b0-121">Dynamics 365 for Sales 企業版來自 CRM basic （完整的供應項目） 適用於學生的 SA</span><span class="sxs-lookup"><span data-stu-id="329b0-121">Dynamics 365 for Sales Enterprise Edition From SA for CRM Basic (Qualified Offer) for Students</span></span>
- <span data-ttu-id="329b0-122">Dynamics 365 for Sales 企業版 （政府定價） 來自 SA 的 CRM Basic （完整的供應項目）</span><span class="sxs-lookup"><span data-stu-id="329b0-122">Dynamics 365 for Sales Enterprise Edition (Government Pricing) From SA for CRM Basic (Qualified Offer)</span></span>
- <span data-ttu-id="329b0-123">Dynamics 365 for Sales 企業版的附加元件 CRM basic （完整的供應項目）</span><span class="sxs-lookup"><span data-stu-id="329b0-123">Dynamics 365 for Sales Enterprise Edition Add-On for CRM Basic (Qualified Offer)</span></span>
- <span data-ttu-id="329b0-124">Dynamics 365 for Sales 企業版的附加元件 CRM basic 教職員版 （完整的供應項目）</span><span class="sxs-lookup"><span data-stu-id="329b0-124">Dynamics 365 for Sales Enterprise Edition Add-On for CRM Basic (Qualified Offer) for Faculty</span></span>
- <span data-ttu-id="329b0-125">Dynamics 365 for Sales 企業版的附加元件適用於學生的 CRM basic （完整的供應項目）</span><span class="sxs-lookup"><span data-stu-id="329b0-125">Dynamics 365 for Sales Enterprise Edition Add-On for CRM Basic (Qualified Offer) for Students</span></span>
- <span data-ttu-id="329b0-126">Dynamics 365 for Sales 企業版 （政府定價） 附加元件 CRM basic （完整的供應項目）</span><span class="sxs-lookup"><span data-stu-id="329b0-126">Dynamics 365 for Sales Enterprise Edition (Government Pricing) Add-On for CRM Basic (Qualified Offer)</span></span>
- <span data-ttu-id="329b0-127">Dynamics 365 Customer Engagement 計劃 Enterprise Edition CRMOL Basic （完整的供應項目）</span><span class="sxs-lookup"><span data-stu-id="329b0-127">Dynamics 365 Customer Engagement Plan Enterprise Edition CRMOL Basic (Qualified Offer)</span></span>
- <span data-ttu-id="329b0-128">Dynamics 365 Customer Engagement 計劃 Enterprise Edition （政府定價） CRMOL Basic （完整的供應項目）</span><span class="sxs-lookup"><span data-stu-id="329b0-128">Dynamics 365 Customer Engagement Plan Enterprise Edition (Government Pricing) CRMOL Basic (Qualified Offer)</span></span>
- <span data-ttu-id="329b0-129">Dynamics 365 Customer Engagement 計劃企業版本 CRMOL Basic （完整的供應項目） 適用於學生</span><span class="sxs-lookup"><span data-stu-id="329b0-129">Dynamics 365 Customer Engagement Plan Enterprise Edition CRMOL Basic (Qualified Offer) for Students</span></span>
- <span data-ttu-id="329b0-130">Dynamics 365 Customer Engagement 計劃 Enterprise Edition CRMOL Basic （完整的供應項目） 教職員版</span><span class="sxs-lookup"><span data-stu-id="329b0-130">Dynamics 365 Customer Engagement Plan Enterprise Edition CRMOL Basic (Qualified Offer) for Faculty</span></span>
- <span data-ttu-id="329b0-131">Dynamics 365 Customer Engagement Plan 企業版來自 SA 的 CRM Basic （完整的供應項目）</span><span class="sxs-lookup"><span data-stu-id="329b0-131">Dynamics 365 Customer Engagement Plan Enterprise Edition From SA for CRM Basic (Qualified Offer)</span></span>
- <span data-ttu-id="329b0-132">Dynamics 365 Customer Engagement Plan 企業版 （政府定價） 來自 SA 的 CRM Basic （完整的供應項目）</span><span class="sxs-lookup"><span data-stu-id="329b0-132">Dynamics 365 Customer Engagement Plan Enterprise Edition (Government Pricing) From SA for CRM Basic (Qualified Offer)</span></span>
- <span data-ttu-id="329b0-133">Dynamics 365 Customer Engagement Plan 企業版來自 CRM basic （完整的供應項目） 適用於學生的 SA</span><span class="sxs-lookup"><span data-stu-id="329b0-133">Dynamics 365 Customer Engagement Plan Enterprise Edition From SA for CRM Basic (Qualified Offer) for Students</span></span>
- <span data-ttu-id="329b0-134">Dynamics 365 Customer Engagement Plan 企業版來自 SA 的 CRM Basic 教職員版 （完整的供應項目）</span><span class="sxs-lookup"><span data-stu-id="329b0-134">Dynamics 365 Customer Engagement Plan Enterprise Edition From SA for CRM Basic (Qualified Offer) for Faculty</span></span>
- <span data-ttu-id="329b0-135">Dynamics 365 Customer Engagement 計劃 Enterprise Edition 的附加元件 CRM Basic （完整的供應項目）</span><span class="sxs-lookup"><span data-stu-id="329b0-135">Dynamics 365 Customer Engagement Plan Enterprise Edition Add-On for CRM Basic (Qualified Offer)</span></span>
- <span data-ttu-id="329b0-136">Dynamics 365 Customer Engagement 計劃 Enterprise 版 （政府定價） 的附加元件 CRM Basic （完整的供應項目）</span><span class="sxs-lookup"><span data-stu-id="329b0-136">Dynamics 365 Customer Engagement Plan Enterprise Edition (Government Pricing) Add-On for CRM Basic (Qualified Offer)</span></span>
- <span data-ttu-id="329b0-137">Dynamics 365 Customer Engagement 計劃 Enterprise Edition 的附加元件適用於學生的 CRM Basic （完整的供應項目）</span><span class="sxs-lookup"><span data-stu-id="329b0-137">Dynamics 365 Customer Engagement Plan Enterprise Edition Add-On for CRM Basic (Qualified Offer) for Students</span></span>
- <span data-ttu-id="329b0-138">Dynamics 365 Customer Engagement 計劃 Enterprise Edition 的附加元件 CRM Basic 教職員版 （完整的供應項目）</span><span class="sxs-lookup"><span data-stu-id="329b0-138">Dynamics 365 Customer Engagement Plan Enterprise Edition Add-On for CRM Basic (Qualified Offer) for Faculty</span></span>



## <a name="dynamics-365-for-sales-customer-engagement-plan-from-basic-qualified-offers-replacement-plans"></a><span data-ttu-id="329b0-139">Dynamics 365 for Sales / Basic （限定提供） 取代從計劃的客戶參與的計劃</span><span class="sxs-lookup"><span data-stu-id="329b0-139">Dynamics 365 for Sales/ Customer Engagement Plan from Basic (Qualified Offers) replacement plans</span></span>

<span data-ttu-id="329b0-140">**已停用的供應項目**</span><span class="sxs-lookup"><span data-stu-id="329b0-140">**Retired offers**</span></span>   

- <span data-ttu-id="329b0-141">Dynamics 365 銷售從 CRM Basic 或 CRMOL Basic （完整的供應項目）</span><span class="sxs-lookup"><span data-stu-id="329b0-141">Dynamics 365 for Sales from CRM Basic or CRMOL Basic (Qualified Offer)</span></span>
- <span data-ttu-id="329b0-142">Dynamics 365 客戶業務開發計劃從 CRM Basic 或 CRMOL Basic （完整的供應項目）</span><span class="sxs-lookup"><span data-stu-id="329b0-142">Dynamics 365 Customer Engagement Plan from CRM Basic or CRMOL Basic (Qualified Offer)</span></span>

<span data-ttu-id="329b0-143">**取代選項**</span><span class="sxs-lookup"><span data-stu-id="329b0-143">**Replacement options**</span></span>
- <span data-ttu-id="329b0-144">Dynamics 365 for Sales 專業 （新）</span><span class="sxs-lookup"><span data-stu-id="329b0-144">Dynamics 365 for Sales Professional (NEW)</span></span>
- <span data-ttu-id="329b0-145">Dynamics 365 for Sales 專業 （新）</span><span class="sxs-lookup"><span data-stu-id="329b0-145">Dynamics 365 for Sales Professional (NEW)</span></span>
- <span data-ttu-id="329b0-146">Dynamics 365 for Customer Service</span><span class="sxs-lookup"><span data-stu-id="329b0-146">Dynamics 365 for Customer Service</span></span>
- <span data-ttu-id="329b0-147">Dynamics 365 Customer Engagement 方案或</span><span class="sxs-lookup"><span data-stu-id="329b0-147">Dynamics 365 Customer Engagement Plan or</span></span>
- <span data-ttu-id="329b0-148">Dynamics 365 小組成員</span><span class="sxs-lookup"><span data-stu-id="329b0-148">Dynamics 365 Team Members</span></span>



## <a name="transition-customers-to-new-product-plans"></a><span data-ttu-id="329b0-149">將客戶轉換到新產品方案</span><span class="sxs-lookup"><span data-stu-id="329b0-149">Transition customers to new product plans</span></span>

<span data-ttu-id="329b0-150">將客戶從已停用的 Sku 移到較新的需要下列步驟順序如下：</span><span class="sxs-lookup"><span data-stu-id="329b0-150">Moving customers from retired SKUs to newer ones requires the following steps in this order:</span></span>

- <span data-ttu-id="329b0-151">購買新訂閱</span><span class="sxs-lookup"><span data-stu-id="329b0-151">Purchase the new subscription</span></span>
- <span data-ttu-id="329b0-152">重新指派目前的使用者授權</span><span class="sxs-lookup"><span data-stu-id="329b0-152">Reassign current user licenses</span></span>
- <span data-ttu-id="329b0-153">取消舊訂閱</span><span class="sxs-lookup"><span data-stu-id="329b0-153">Cancel old subscription</span></span>

## <a name="purchase-the-new-plan-for-your-customer"></a><span data-ttu-id="329b0-154">為您的客戶購買新的計劃</span><span class="sxs-lookup"><span data-stu-id="329b0-154">Purchase the new plan for your customer</span></span>

1. <span data-ttu-id="329b0-155">選取 **客戶**從左側的導覽中，然後選取您想要移動到新的訂用帳戶的客戶。</span><span class="sxs-lookup"><span data-stu-id="329b0-155">Select **Customers** from the left nav and then select the customer you want to move to the new subscription.</span></span>
2. <span data-ttu-id="329b0-156">選取 **新增訂用帳戶**。</span><span class="sxs-lookup"><span data-stu-id="329b0-156">Select **Add Subscription**.</span></span>
3. <span data-ttu-id="329b0-157">選取您要從型錄購買的訂閱 (在此案例中為以上其中一個選項)，輸入授權數量，然後選取 **\[提交\]**。</span><span class="sxs-lookup"><span data-stu-id="329b0-157">Select the subscription you want to purchase from the catalog (in this case, one of the options above), enter the number of licenses, and then select **Submit**.</span></span> 

<span data-ttu-id="329b0-158">舊訂用帳戶和新的現在會有您的客戶。</span><span class="sxs-lookup"><span data-stu-id="329b0-158">Your customer will now have both the old subscription and the new one.</span></span> <span data-ttu-id="329b0-159">下一步是要重新指派授權給客戶的使用者。</span><span class="sxs-lookup"><span data-stu-id="329b0-159">Your next step is to reassign licenses to the customer's users.</span></span>

1. <span data-ttu-id="329b0-160">選取 **客戶**從左側的導覽中，然後選取客戶是移動。</span><span class="sxs-lookup"><span data-stu-id="329b0-160">Select **Customers** from the left nav and then select the customer you are moving.</span></span>
2. <span data-ttu-id="329b0-161">選取 \[使用者和授權\]。</span><span class="sxs-lookup"><span data-stu-id="329b0-161">Select **Users and licenses**.</span></span>
3. <span data-ttu-id="329b0-162">若要重新指派授權給使用者時，選取的使用者，然後按**管理授權**。</span><span class="sxs-lookup"><span data-stu-id="329b0-162">To reassign a license to a user, select the user and then select **Manage licenses**.</span></span> 
4. <span data-ttu-id="329b0-163">在 **管理授權** 頁面上，清除 Dynamics 365 for Sales / 客戶業務開發計劃 （限定優惠） 的 basic 授權核取方塊，然後選取 訂用帳戶客戶移至新的服務方案。</span><span class="sxs-lookup"><span data-stu-id="329b0-163">On the **Manage licenses** page, clear the Dynamics 365 for Sales/ Customer Engagement Plan from Basic (Qualified Offer) license check box and select a new service plan for the subscription the customer is moving to.</span></span> 
5. <span data-ttu-id="329b0-164">選取 \[送出\]。</span><span class="sxs-lookup"><span data-stu-id="329b0-164">Select **Submit**.</span></span> <span data-ttu-id="329b0-165">您將會針對每個需要新授權的使用者來這麼做。</span><span class="sxs-lookup"><span data-stu-id="329b0-165">You will do this for each user who needs the new license.</span></span> 

<span data-ttu-id="329b0-166">授權移動到新的訂用帳戶之後，您可以取消舊訂用帳戶。</span><span class="sxs-lookup"><span data-stu-id="329b0-166">Once you've moved the licenses over to the new subscription you can cancel the old subscription.</span></span> 

1. <span data-ttu-id="329b0-167">選取 **客戶**從左側的導覽中，然後選取客戶是移動。</span><span class="sxs-lookup"><span data-stu-id="329b0-167">Select **Customers** from the left nav and then select the customer you are moving.</span></span>
2. <span data-ttu-id="329b0-168">在訂用帳戶詳細資料頁面上，設定為舊的訂用帳戶**Suspended** ，然後選取**送出**。</span><span class="sxs-lookup"><span data-stu-id="329b0-168">On the subscription detail page, set the old subscription to **Suspended** and select **Submit**.</span></span>

<span data-ttu-id="329b0-169">舊訂用帳戶現在已暫停，並且新的訂用帳戶作用中。</span><span class="sxs-lookup"><span data-stu-id="329b0-169">The old subscription is now suspended, and the new subscription is active.</span></span> <span data-ttu-id="329b0-170">暫停的訂閱將在 120 天後自動解除佈建。</span><span class="sxs-lookup"><span data-stu-id="329b0-170">The suspended subscription will be de-provisioned automatically after 120 days.</span></span> <span data-ttu-id="329b0-171">您的客戶將會產生任何額外的費用，舊的訂用帳戶。</span><span class="sxs-lookup"><span data-stu-id="329b0-171">Your customer will incur no additional costs for the old subscription.</span></span>
 

 



