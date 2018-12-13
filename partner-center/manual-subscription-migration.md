---
title: 將 Dynamics 365 和 Customer Engagement Plan 從基本 （合格的供應項目） 移轉至較新版本 |合作夥伴中心
ms.topic: article
ms.date: 12/12/2018
description: Dynamics 365 for Sales / Customer Engagement Plan （合格提供） 的基本訂閱從可以不再更新。
ms.assetid: 79787bef-a6e9-4c11-8c3b-f0a77485c0a4
author: labrenne
ms.author: labrenne
ms.localizationpriority: medium
ms.custom: seodec18
Keywords: Dynamics 365 offers, renew offers, new Dynamics 365 SKUs
ms.openlocfilehash: b4b25dd80a684c9060b28461a9e6f594651ae224
ms.sourcegitcommit: 23adf424dd43ed0281473f97d535d73c59c92b01
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 12/13/2018
ms.locfileid: "8968268"
---
# <a name="migrate-dynamics-365-and-customer-engagement-plan-from-basic-qualified-offers-to-newer-versions"></a><span data-ttu-id="3859d-103">將 Dynamics 365 和 Customer Engagement Plan 從基本 （合格的供應項目） 移轉至較新版本</span><span class="sxs-lookup"><span data-stu-id="3859d-103">Migrate Dynamics 365 and Customer Engagement Plan from Basic (qualified offers) to newer versions</span></span>

**<span data-ttu-id="3859d-104">適用於</span><span class="sxs-lookup"><span data-stu-id="3859d-104">Applies to</span></span>**

-  <span data-ttu-id="3859d-105">合作夥伴中心</span><span class="sxs-lookup"><span data-stu-id="3859d-105">Partner Center</span></span>

<span data-ttu-id="3859d-106">有效 2019 年 1 月 1 日，客戶使用 Dynamics 365 for Sales / Customer Engagement Plan 從 （合格提供） 的基本訂閱無法續這些舊版供應項目;現有訂閱在到期時，將不會自動的續約。</span><span class="sxs-lookup"><span data-stu-id="3859d-106">Effective January 1, 2019, customers with Dynamics 365 for Sales/ Customer Engagement Plan from Basic (Qualified Offers) subscriptions can no longer renew these legacy offers; existing subscriptions will not renew automatically when they expire.</span></span> <span data-ttu-id="3859d-107">訂閱的詳細資料頁面上，訂閱狀態將會從 「 自動續約於 [日期] 」 變更為 「 到期日 [日期] 」。</span><span class="sxs-lookup"><span data-stu-id="3859d-107">On the subscription’s detail page, the subscription status will change to "Expires on [date]" from "Auto renews on [date]".</span></span> 


<span data-ttu-id="3859d-108">若要確保客戶持續的您應該將具有即將到期的訂閱至支援的選項，如下所列的那些轉換。</span><span class="sxs-lookup"><span data-stu-id="3859d-108">To ensure continuity for customers, you should transition those with expiring subscriptions to a supported option, listed below.</span></span> <span data-ttu-id="3859d-109">我們建議在年度訂閱的結束日期之前將客戶移轉至新的訂閱，以避免發生任何客戶服務中斷。</span><span class="sxs-lookup"><span data-stu-id="3859d-109">We recommend moving customers to new subscriptions before the subscription’s yearly end date to avoid any service outages for customers.</span></span>

<span data-ttu-id="3859d-110">如果您使用 API （CREST 或合作夥伴中心），您可以尋找即將到期的訂閱評估的結束日期搭配自動訂閱續約 = False 屬性。</span><span class="sxs-lookup"><span data-stu-id="3859d-110">If you use the API (either CREST or Partner Center), you can find expiring subscriptions by evaluating the end date of the subscription along with the auto renew = False property.</span></span> <span data-ttu-id="3859d-111">有問題的訂閱將會設定為自動續約 = False 在 2019 年 1 月 1 日。</span><span class="sxs-lookup"><span data-stu-id="3859d-111">The subscriptions in question will be set to auto renew=False on Jan 1, 2019.</span></span> <span data-ttu-id="3859d-112">您可以隨時將客戶移轉至新的方案。</span><span class="sxs-lookup"><span data-stu-id="3859d-112">You can move customers to a new plan at any time.</span></span> 

### <a name="the-dynamics-365-offers-being-retired"></a><span data-ttu-id="3859d-113">Dynamics 365 優惠被淘汰</span><span class="sxs-lookup"><span data-stu-id="3859d-113">The Dynamics 365 offers being retired</span></span>

- <span data-ttu-id="3859d-114">Dynamics 365 銷售 Enterprise Edition CRMOL 基本 （合格的供應項目）</span><span class="sxs-lookup"><span data-stu-id="3859d-114">Dynamics 365 for Sales Enterprise Edition CRMOL Basic (Qualified Offer)</span></span>
- <span data-ttu-id="3859d-115">Dynamics 365 銷售 Enterprise Edition CRMOL 基本適用於教職員 （合格的供應項目）</span><span class="sxs-lookup"><span data-stu-id="3859d-115">Dynamics 365 for Sales Enterprise Edition CRMOL Basic (Qualified Offer) for Faculty</span></span>
- <span data-ttu-id="3859d-116">Dynamics 365 銷售 Enterprise Edition CRMOL 基本適用於學生 （合格的供應項目）</span><span class="sxs-lookup"><span data-stu-id="3859d-116">Dynamics 365 for Sales Enterprise Edition CRMOL Basic (Qualified Offer) for Students</span></span>
- <span data-ttu-id="3859d-117">Dynamics 365 銷售的企業版 （政府定價） CRMOL 基本 （合格的供應項目）</span><span class="sxs-lookup"><span data-stu-id="3859d-117">Dynamics 365 for Sales Enterprise Edition (Government Pricing) CRMOL Basic (Qualified Offer)</span></span>
- <span data-ttu-id="3859d-118">Dynamics 365 適用於銷售的企業版從 SA CRM 基本 （合格的供應項目）</span><span class="sxs-lookup"><span data-stu-id="3859d-118">Dynamics 365 for Sales Enterprise Edition From SA for CRM Basic (Qualified Offer)</span></span>
- <span data-ttu-id="3859d-119">Dynamics 365 適用於銷售的企業版 SA CRM 基本 （合格的供應項目） 適用於教職員從</span><span class="sxs-lookup"><span data-stu-id="3859d-119">Dynamics 365 for Sales Enterprise Edition From SA for CRM Basic (Qualified Offer) for Faculty</span></span>
- <span data-ttu-id="3859d-120">Dynamics 365 適用於銷售的企業版 SA CRM 基本 （合格的供應項目） 的學生從</span><span class="sxs-lookup"><span data-stu-id="3859d-120">Dynamics 365 for Sales Enterprise Edition From SA for CRM Basic (Qualified Offer) for Students</span></span>
- <span data-ttu-id="3859d-121">Dynamics 365 適用於銷售的企業版 （政府定價） 從 SA CRM 基本 （合格的供應項目）</span><span class="sxs-lookup"><span data-stu-id="3859d-121">Dynamics 365 for Sales Enterprise Edition (Government Pricing) From SA for CRM Basic (Qualified Offer)</span></span>
- <span data-ttu-id="3859d-122">Dynamics 365 銷售的企業版的附加元件 CRM 基本 （合格的供應項目）</span><span class="sxs-lookup"><span data-stu-id="3859d-122">Dynamics 365 for Sales Enterprise Edition Add-On for CRM Basic (Qualified Offer)</span></span>
- <span data-ttu-id="3859d-123">Dynamics 365 銷售的企業版的附加元件適用於教職員的 CRM 基本 （合格的供應項目）</span><span class="sxs-lookup"><span data-stu-id="3859d-123">Dynamics 365 for Sales Enterprise Edition Add-On for CRM Basic (Qualified Offer) for Faculty</span></span>
- <span data-ttu-id="3859d-124">Dynamics 365 銷售的企業版的附加元件的學生的 CRM 基本 （合格的供應項目）</span><span class="sxs-lookup"><span data-stu-id="3859d-124">Dynamics 365 for Sales Enterprise Edition Add-On for CRM Basic (Qualified Offer) for Students</span></span>
- <span data-ttu-id="3859d-125">Dynamics 365 銷售的企業版 （政府定價） 附加元件的 CRM 基本 （合格的供應項目）</span><span class="sxs-lookup"><span data-stu-id="3859d-125">Dynamics 365 for Sales Enterprise Edition (Government Pricing) Add-On for CRM Basic (Qualified Offer)</span></span>
- <span data-ttu-id="3859d-126">Dynamics 365 客戶參與計劃 Enterprise Edition CRMOL Basic （合格的供應項目）</span><span class="sxs-lookup"><span data-stu-id="3859d-126">Dynamics 365 Customer Engagement Plan Enterprise Edition CRMOL Basic (Qualified Offer)</span></span>
- <span data-ttu-id="3859d-127">Dynamics 365 客戶參與計劃 Enterprise Edition （政府定價） CRMOL Basic （合格的供應項目）</span><span class="sxs-lookup"><span data-stu-id="3859d-127">Dynamics 365 Customer Engagement Plan Enterprise Edition (Government Pricing) CRMOL Basic (Qualified Offer)</span></span>
- <span data-ttu-id="3859d-128">Dynamics 365 客戶參與計劃 Enterprise Edition CRMOL Basic （合格的供應項目） 為學生</span><span class="sxs-lookup"><span data-stu-id="3859d-128">Dynamics 365 Customer Engagement Plan Enterprise Edition CRMOL Basic (Qualified Offer) for Students</span></span>
- <span data-ttu-id="3859d-129">Dynamics 365 客戶參與計劃 Enterprise Edition CRMOL Basic （合格的供應項目） 適用於教職員</span><span class="sxs-lookup"><span data-stu-id="3859d-129">Dynamics 365 Customer Engagement Plan Enterprise Edition CRMOL Basic (Qualified Offer) for Faculty</span></span>
- <span data-ttu-id="3859d-130">Dynamics 365 客戶業務開發計劃企業版從 SA CRM 基本 （合格的供應項目）</span><span class="sxs-lookup"><span data-stu-id="3859d-130">Dynamics 365 Customer Engagement Plan Enterprise Edition From SA for CRM Basic (Qualified Offer)</span></span>
- <span data-ttu-id="3859d-131">Dynamics 365 客戶業務開發計劃企業版 （政府定價） 從 SA CRM 基本 （合格的供應項目）</span><span class="sxs-lookup"><span data-stu-id="3859d-131">Dynamics 365 Customer Engagement Plan Enterprise Edition (Government Pricing) From SA for CRM Basic (Qualified Offer)</span></span>
- <span data-ttu-id="3859d-132">Dynamics 365 客戶業務開發計劃企業版 SA CRM 基本 （合格的供應項目） 的學生從</span><span class="sxs-lookup"><span data-stu-id="3859d-132">Dynamics 365 Customer Engagement Plan Enterprise Edition From SA for CRM Basic (Qualified Offer) for Students</span></span>
- <span data-ttu-id="3859d-133">Dynamics 365 客戶業務開發計劃企業版 SA CRM 基本 （合格的供應項目） 適用於教職員從</span><span class="sxs-lookup"><span data-stu-id="3859d-133">Dynamics 365 Customer Engagement Plan Enterprise Edition From SA for CRM Basic (Qualified Offer) for Faculty</span></span>
- <span data-ttu-id="3859d-134">Dynamics 365 客戶參與計劃企業版的附加元件 CRM Basic （合格的供應項目）</span><span class="sxs-lookup"><span data-stu-id="3859d-134">Dynamics 365 Customer Engagement Plan Enterprise Edition Add-On for CRM Basic (Qualified Offer)</span></span>
- <span data-ttu-id="3859d-135">Dynamics 365 客戶參與計劃 Enterprise Edition （政府定價） 附加元件 CRM 基本 （合格的供應項目）</span><span class="sxs-lookup"><span data-stu-id="3859d-135">Dynamics 365 Customer Engagement Plan Enterprise Edition (Government Pricing) Add-On for CRM Basic (Qualified Offer)</span></span>
- <span data-ttu-id="3859d-136">Dynamics 365 客戶參與計劃企業版附加元件的學生的 CRM Basic （合格的供應項目）</span><span class="sxs-lookup"><span data-stu-id="3859d-136">Dynamics 365 Customer Engagement Plan Enterprise Edition Add-On for CRM Basic (Qualified Offer) for Students</span></span>
- <span data-ttu-id="3859d-137">Dynamics 365 客戶參與計劃 Enterprise Edition 附加元件適用於教職員的 CRM 基本 （合格的供應項目）</span><span class="sxs-lookup"><span data-stu-id="3859d-137">Dynamics 365 Customer Engagement Plan Enterprise Edition Add-On for CRM Basic (Qualified Offer) for Faculty</span></span>



## <a name="dynamics-365-for-sales-customer-engagement-plan-from-basic-qualified-offers-replacement-plans"></a><span data-ttu-id="3859d-138">Dynamics 365 for Sales / Customer Engagement Plan 從基本 （合格提供） 取代方案</span><span class="sxs-lookup"><span data-stu-id="3859d-138">Dynamics 365 for Sales/ Customer Engagement Plan from Basic (Qualified Offers) replacement plans</span></span>

**<span data-ttu-id="3859d-139">已淘汰的供應項目</span><span class="sxs-lookup"><span data-stu-id="3859d-139">Retired offers</span></span>**   

- <span data-ttu-id="3859d-140">Dynamics 365 for Sales 從 CRM 基本或 CRMOL Basic （合格的供應項目）</span><span class="sxs-lookup"><span data-stu-id="3859d-140">Dynamics 365 for Sales from CRM Basic or CRMOL Basic (Qualified Offer)</span></span>
- <span data-ttu-id="3859d-141">Dynamics 365 Customer Engagement Plan 從 CRM 基本或 CRMOL Basic （合格的供應項目）</span><span class="sxs-lookup"><span data-stu-id="3859d-141">Dynamics 365 Customer Engagement Plan from CRM Basic or CRMOL Basic (Qualified Offer)</span></span>

**<span data-ttu-id="3859d-142">取代選項</span><span class="sxs-lookup"><span data-stu-id="3859d-142">Replacement options</span></span>**
- <span data-ttu-id="3859d-143">適用於銷售 （新） 專業人員的 Dynamics 365</span><span class="sxs-lookup"><span data-stu-id="3859d-143">Dynamics 365 for Sales Professional (NEW)</span></span>
- <span data-ttu-id="3859d-144">適用於銷售 （新） 專業人員的 Dynamics 365</span><span class="sxs-lookup"><span data-stu-id="3859d-144">Dynamics 365 for Sales Professional (NEW)</span></span>
- <span data-ttu-id="3859d-145">Dynamics 365 for Customer Service</span><span class="sxs-lookup"><span data-stu-id="3859d-145">Dynamics 365 for Customer Service</span></span>
- <span data-ttu-id="3859d-146">Dynamics 365 Customer Engagement Plan 或</span><span class="sxs-lookup"><span data-stu-id="3859d-146">Dynamics 365 Customer Engagement Plan or</span></span>
- <span data-ttu-id="3859d-147">Dynamics 365 Team Members</span><span class="sxs-lookup"><span data-stu-id="3859d-147">Dynamics 365 Team Members</span></span>



## <a name="transition-customers-to-new-product-plans"></a><span data-ttu-id="3859d-148">將客戶轉換到新產品方案</span><span class="sxs-lookup"><span data-stu-id="3859d-148">Transition customers to new product plans</span></span>

<span data-ttu-id="3859d-149">將客戶從淘汰的 Sku 移轉到較新的需要此訂單中的下列步驟：</span><span class="sxs-lookup"><span data-stu-id="3859d-149">Moving customers from retired SKUs to newer ones requires the following steps in this order:</span></span>

- <span data-ttu-id="3859d-150">購買新訂閱</span><span class="sxs-lookup"><span data-stu-id="3859d-150">Purchase the new subscription</span></span>
- <span data-ttu-id="3859d-151">重新指派目前的使用者授權</span><span class="sxs-lookup"><span data-stu-id="3859d-151">Reassign current user licenses</span></span>
- <span data-ttu-id="3859d-152">取消舊訂閱</span><span class="sxs-lookup"><span data-stu-id="3859d-152">Cancel old subscription</span></span>

## <a name="purchase-the-new-plan-for-your-customer"></a><span data-ttu-id="3859d-153">為您的客戶購買新的計劃</span><span class="sxs-lookup"><span data-stu-id="3859d-153">Purchase the new plan for your customer</span></span>

1. <span data-ttu-id="3859d-154">選取**客戶**從左瀏覽，然後選取您想要移到新訂閱的客戶。</span><span class="sxs-lookup"><span data-stu-id="3859d-154">Select **Customers** from the left nav and then select the customer you want to move to the new subscription.</span></span>
2. <span data-ttu-id="3859d-155">選取 [**新增訂閱**。</span><span class="sxs-lookup"><span data-stu-id="3859d-155">Select **Add Subscription**.</span></span>
3. <span data-ttu-id="3859d-156">選取您要從型錄購買的訂閱 (在此案例中為以上其中一個選項)，輸入授權數量，然後選取 **\[提交\]**。</span><span class="sxs-lookup"><span data-stu-id="3859d-156">Select the subscription you want to purchase from the catalog (in this case, one of the options above), enter the number of licenses, and then select **Submit**.</span></span> 

<span data-ttu-id="3859d-157">您的客戶現在將會有舊訂閱和新的網站。</span><span class="sxs-lookup"><span data-stu-id="3859d-157">Your customer will now have both the old subscription and the new one.</span></span> <span data-ttu-id="3859d-158">您的下一個步驟是要重新指派授權給客戶的使用者。</span><span class="sxs-lookup"><span data-stu-id="3859d-158">Your next step is to reassign licenses to the customer's users.</span></span>

1. <span data-ttu-id="3859d-159">從左瀏覽中選取**客戶**，然後選取您要移動的客戶。</span><span class="sxs-lookup"><span data-stu-id="3859d-159">Select **Customers** from the left nav and then select the customer you are moving.</span></span>
2. <span data-ttu-id="3859d-160">選取 **\[使用者和授權\]**。</span><span class="sxs-lookup"><span data-stu-id="3859d-160">Select **Users and licenses**.</span></span>
3. <span data-ttu-id="3859d-161">若要重新指派授權給使用者，選取使用者，然後選取 [**管理授權**。</span><span class="sxs-lookup"><span data-stu-id="3859d-161">To reassign a license to a user, select the user and then select **Manage licenses**.</span></span> 
4. <span data-ttu-id="3859d-162">**管理授權**\] 頁面，清除 Dynamics 365 for Sales/Customer Engagement Plan 從基本 （合格提供） 授權核取方塊，然後選取客戶移動到的訂閱新服務方案。</span><span class="sxs-lookup"><span data-stu-id="3859d-162">On the **Manage licenses** page, clear the Dynamics 365 for Sales/ Customer Engagement Plan from Basic (Qualified Offer) license check box and select a new service plan for the subscription the customer is moving to.</span></span> 
5. <span data-ttu-id="3859d-163">選取 **\[提交\]**。</span><span class="sxs-lookup"><span data-stu-id="3859d-163">Select **Submit**.</span></span> <span data-ttu-id="3859d-164">針對每個使用者需要新的授權，您將會執行此動作。</span><span class="sxs-lookup"><span data-stu-id="3859d-164">You will do this for each user who needs the new license.</span></span> 

<span data-ttu-id="3859d-165">一旦您已移至授權到新訂閱，您可以取消舊訂閱。</span><span class="sxs-lookup"><span data-stu-id="3859d-165">Once you've moved the licenses over to the new subscription you can cancel the old subscription.</span></span> 

1. <span data-ttu-id="3859d-166">從左瀏覽中選取**客戶**，然後選取您要移動的客戶。</span><span class="sxs-lookup"><span data-stu-id="3859d-166">Select **Customers** from the left nav and then select the customer you are moving.</span></span>
2. <span data-ttu-id="3859d-167">訂閱詳細資料頁面上，將舊訂閱設定為**已暫停**，並選取 [**送出**。</span><span class="sxs-lookup"><span data-stu-id="3859d-167">On the subscription detail page, set the old subscription to **Suspended** and select **Submit**.</span></span>

<span data-ttu-id="3859d-168">舊訂閱現在暫停，而新訂閱為使用中。</span><span class="sxs-lookup"><span data-stu-id="3859d-168">The old subscription is now suspended, and the new subscription is active.</span></span> <span data-ttu-id="3859d-169">暫停的訂閱將在 120 天後自動解除佈建。</span><span class="sxs-lookup"><span data-stu-id="3859d-169">The suspended subscription will be de-provisioned automatically after 120 days.</span></span> <span data-ttu-id="3859d-170">您的客戶將會產生舊訂閱沒有額外成本。</span><span class="sxs-lookup"><span data-stu-id="3859d-170">Your customer will incur no additional costs for the old subscription.</span></span>
 

 



