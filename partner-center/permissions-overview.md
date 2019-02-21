---
title: 指派使用者角色和權限 |合作夥伴中心
ms.topic: article
ms.date: 10/29/2018
description: 若要在合作夥伴中心中工作需要每個員工必須有指派的角色。
author: labrenne
ms.author: labrenne
keywords: 角色、 權限，系統管理員、 代理程式
ms.localizationpriority: medium
ms.openlocfilehash: d811cb76b03b1784eaf926052e6a00151b2fc347
ms.sourcegitcommit: bfbb5b5edb381e219134be5a3e4a97bfe232288f
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 02/21/2019
ms.locfileid: "9086726"
---
# <a name="assign-users-roles-and-permissions"></a><span data-ttu-id="4c605-104">指派使用者角色和權限</span><span class="sxs-lookup"><span data-stu-id="4c605-104">Assign users roles and permissions</span></span>


<span data-ttu-id="4c605-105">您已經設定您的合作夥伴設定檔，包括合法的名稱和地址、 支援詳細資料、 回報免稅、 銀行資訊，以及為您的公司主要連絡人。</span><span class="sxs-lookup"><span data-stu-id="4c605-105">You've set up your partner profile including legal name and address, support details, file tax exemptions, bank info, and the primary contact for your company.</span></span> <span data-ttu-id="4c605-106">下一步： 讓您設定密碼與角色，他們就可以開始使用合作夥伴中心中您的使用者。</span><span class="sxs-lookup"><span data-stu-id="4c605-106">Next step: get your users set up with passwords and roles so they can begin working in Partner Center with you.</span></span>

## <a name="set-up-your-employees-to-work-in-partner-center"></a><span data-ttu-id="4c605-107">將您的員工設定為使用合作夥伴中心</span><span class="sxs-lookup"><span data-stu-id="4c605-107">Set up your employees to work in Partner Center</span></span>

<span data-ttu-id="4c605-108">您判斷您的使用者擁有的角色和權限給他們的合作夥伴中心的存取權的類型。</span><span class="sxs-lookup"><span data-stu-id="4c605-108">You determine the types of access your users have to Partner Center by the roles and permissions you give them.</span></span> <span data-ttu-id="4c605-109">角色與有關您的業務涉及的程式。</span><span class="sxs-lookup"><span data-stu-id="4c605-109">Roles are related to the program(s) your business is involved in.</span></span> <span data-ttu-id="4c605-110">例如，如果您的企業雲端解決方案提供者 (CSP) 的商務版，您不只會標準的 Azure AD 租用戶的全域系統管理員，例如管理角色，但將需要專屬於雲端解決方案提供者計畫的角色。</span><span class="sxs-lookup"><span data-stu-id="4c605-110">For example,if your business is a Cloud Solution Provider (CSP) business, you will not only have the standard Azure AD tenant management roles such as global admin, but will need roles specific to the CSP program.</span></span> <span data-ttu-id="4c605-111">每個程式都有它的特定的角色。</span><span class="sxs-lookup"><span data-stu-id="4c605-111">Each program has roles specific to it.</span></span>

>[!Note]
> <span data-ttu-id="4c605-112">Azure Active Directory (AAD) 租用戶角色包含全域系統管理員、 使用者系統管理員，以及雲端解決方案提供者角色。</span><span class="sxs-lookup"><span data-stu-id="4c605-112">Azure Active Directory (AAD) tenant roles include global admin, user admin, and CSP roles.</span></span> <span data-ttu-id="4c605-113">非 AAD 角色包括 MPN 系統管理員、 商務設定檔系統管理員、 推薦系統管理員、 獎勵系統管理員，以及獎勵使用者。</span><span class="sxs-lookup"><span data-stu-id="4c605-113">Non-AAD roles include MPN admin, business profile admin, referral admin, incentive admin, and incentive user.</span></span> 

### <a name="manage-commercial-transactions-in-partner-center-azure-ad-and-csp-roles"></a><span data-ttu-id="4c605-114">管理合作夥伴中心中的商業交易 (Azure AD 與雲端解決方案提供者角色)</span><span class="sxs-lookup"><span data-stu-id="4c605-114">Manage commercial transactions in Partner Center (Azure AD and CSP roles)</span></span>

|**<span data-ttu-id="4c605-115">角色</span><span class="sxs-lookup"><span data-stu-id="4c605-115">Role</span></span>**|**<span data-ttu-id="4c605-116">可執行</span><span class="sxs-lookup"><span data-stu-id="4c605-116">What they can do</span></span>**|
|----------------------------------|:---------------------------------|
|<span data-ttu-id="4c605-117">全域系統管理員</span><span class="sxs-lookup"><span data-stu-id="4c605-117">Global admin</span></span>|<span data-ttu-id="4c605-118">• 可以存取所有 Microsoft 帳戶/服務的完整權限</span><span class="sxs-lookup"><span data-stu-id="4c605-118">• Can access all Microsoft account/services with full privileges</span></span>
|      |<span data-ttu-id="4c605-119">• 建立合作夥伴中心的支援票證</span><span class="sxs-lookup"><span data-stu-id="4c605-119">•   Create support tickets for the Partner Center</span></span>
||<span data-ttu-id="4c605-120">• 檢視合約、 價目表和優惠</span><span class="sxs-lookup"><span data-stu-id="4c605-120">• View agreements, price lists, and offers</span></span>
||<span data-ttu-id="4c605-121">• 檢視中，建立和管理合作夥伴使用者</span><span class="sxs-lookup"><span data-stu-id="4c605-121">• View, create, and manage partner users</span></span>|
|<span data-ttu-id="4c605-122">使用者系統管理員</span><span class="sxs-lookup"><span data-stu-id="4c605-122">User Admin</span></span>   | <span data-ttu-id="4c605-123">• 檢視中，建立和管理使用者</span><span class="sxs-lookup"><span data-stu-id="4c605-123">•   View, create, and manage users</span></span>
||<span data-ttu-id="4c605-124">• 檢視所有合作夥伴設定檔</span><span class="sxs-lookup"><span data-stu-id="4c605-124">• View all partner profiles</span></span>
||<span data-ttu-id="4c605-125">• 檢視中，建立和管理合作夥伴使用者</span><span class="sxs-lookup"><span data-stu-id="4c605-125">• View, create, and manage partner users</span></span>  |
|<span data-ttu-id="4c605-126">預設使用者</span><span class="sxs-lookup"><span data-stu-id="4c605-126">Default user</span></span>|  <span data-ttu-id="4c605-127">檢視我的設定檔</span><span class="sxs-lookup"><span data-stu-id="4c605-127">View My profile</span></span>   |
|<span data-ttu-id="4c605-128">系統管理代理人</span><span class="sxs-lookup"><span data-stu-id="4c605-128">Admin agent</span></span> | <span data-ttu-id="4c605-129">• 客戶管理</span><span class="sxs-lookup"><span data-stu-id="4c605-129">•    Customer management</span></span>
||<span data-ttu-id="4c605-130">• 將裝置清單新增至合作夥伴 Center<</span><span class="sxs-lookup"><span data-stu-id="4c605-130">• Add device list to the Partner Center<</span></span>
||<span data-ttu-id="4c605-131">• 建立和套用設定檔至裝置</span><span class="sxs-lookup"><span data-stu-id="4c605-131">• Create and apply profiles to devices</span></span>
||<span data-ttu-id="4c605-132">• 訂用帳戶管理</span><span class="sxs-lookup"><span data-stu-id="4c605-132">• Subscription management</span></span>
||<span data-ttu-id="4c605-133">• 服務健康狀況和服務要求的客戶</span><span class="sxs-lookup"><span data-stu-id="4c605-133">• Service health and service requests for customers</span></span>
||<span data-ttu-id="4c605-134">• 要求委派的系統管理員權限</span><span class="sxs-lookup"><span data-stu-id="4c605-134">• Request delegated administrator privileges</span></span>
||<span data-ttu-id="4c605-135">• 檢視定價與方案</span><span class="sxs-lookup"><span data-stu-id="4c605-135">• View pricing and offers</span></span>
||<span data-ttu-id="4c605-136">• 帳單</span><span class="sxs-lookup"><span data-stu-id="4c605-136">• Billing</span></span>
||<span data-ttu-id="4c605-137">•，則代表客戶進行管理</span><span class="sxs-lookup"><span data-stu-id="4c605-137">• Administer on behalf of a customer</span></span>
||<span data-ttu-id="4c605-138">• 暫存器值加值型經銷商</span><span class="sxs-lookup"><span data-stu-id="4c605-138">• Register a value added reseller</span></span>|
|<span data-ttu-id="4c605-139">銷售代理人</span><span class="sxs-lookup"><span data-stu-id="4c605-139">Sales agent</span></span> | <span data-ttu-id="4c605-140">• 客戶管理</span><span class="sxs-lookup"><span data-stu-id="4c605-140">•    Customer management</span></span>
||<span data-ttu-id="4c605-141">• 將裝置清單新增至合作夥伴中心</span><span class="sxs-lookup"><span data-stu-id="4c605-141">• Add device list to the Partner Center</span></span>
||<span data-ttu-id="4c605-142">• 訂用帳戶管理</span><span class="sxs-lookup"><span data-stu-id="4c605-142">• Subscription management</span></span>
||<span data-ttu-id="4c605-143">• 檢視支援票證</span><span class="sxs-lookup"><span data-stu-id="4c605-143">• View support tickets</span></span>
||<span data-ttu-id="4c605-144">• 要求與客戶建立關係</span><span class="sxs-lookup"><span data-stu-id="4c605-144">• Request a relationship with a customer</span></span>
||<span data-ttu-id="4c605-145">• 管理潛在客戶</span><span class="sxs-lookup"><span data-stu-id="4c605-145">• Manage customer leads</span></span>
||<span data-ttu-id="4c605-146">• 檢視客戶合約</span><span class="sxs-lookup"><span data-stu-id="4c605-146">• View the customer agreement</span></span>
||<span data-ttu-id="4c605-147">• 註冊加值型經銷商</span><span class="sxs-lookup"><span data-stu-id="4c605-147">• Register a value-added reseller</span></span>|
|<span data-ttu-id="4c605-148">技術服務代理人</span><span class="sxs-lookup"><span data-stu-id="4c605-148">Helpdesk agent</span></span>| <span data-ttu-id="4c605-149">• 搜尋並檢視客戶</span><span class="sxs-lookup"><span data-stu-id="4c605-149">•  Search for and view a customer</span></span>
||<span data-ttu-id="4c605-150">• 編輯客戶詳細資料</span><span class="sxs-lookup"><span data-stu-id="4c605-150">• Edit customer details</span></span>
||<span data-ttu-id="4c605-151">• 協助解決客戶的帳單及訂閱管理問題</span><span class="sxs-lookup"><span data-stu-id="4c605-151">• Help resolve customer issues with billing or subscription management</span></span>
||<span data-ttu-id="4c605-152">代表客戶 • 要求支援 (注意： 您必須是系統管理代理人，才能完成 Office 365 訂閱的這項工作)</span><span class="sxs-lookup"><span data-stu-id="4c605-152">• Request support on behalf of customers (Note: You must be an admin agent to complete this task for Office 365 subscriptions)</span></span>
||<span data-ttu-id="4c605-153">• 管理訂閱及帳單問題代表客戶 (注意： 您必須是系統管理代理人，才能完成 Office 365 訂閱的這項工作)</span><span class="sxs-lookup"><span data-stu-id="4c605-153">• Manage subscriptions and billing issues on behalf of customers (Note: You must be an admin agent to complete this task for Office 365 subscriptions)</span></span>|
|
### <a name="control-panel-vendor-cpv-csp-role-and-non-aad-role"></a><span data-ttu-id="4c605-154">控制台廠商 (CPV)。</span><span class="sxs-lookup"><span data-stu-id="4c605-154">Control Panel Vendor (CPV).</span></span> <span data-ttu-id="4c605-155">（雲端解決方案提供者角色和非 AAD 角色）</span><span class="sxs-lookup"><span data-stu-id="4c605-155">(CSP role and non-AAD role)</span></span>
<span data-ttu-id="4c605-156">CPVs 開發雲端解決方案提供者 (CSP) 的合作夥伴，以便讓廠商與合作夥伴中心 Api 整合其系統所使用的應用程式。</span><span class="sxs-lookup"><span data-stu-id="4c605-156">CPVs develop apps for use by Cloud Solution Provider (CSP) partners to enable them to integrate their systems with Partner Center APIs.</span></span> 

|**<span data-ttu-id="4c605-157">角色</span><span class="sxs-lookup"><span data-stu-id="4c605-157">Role</span></span>**   |**<span data-ttu-id="4c605-158">您可以執行的動作</span><span class="sxs-lookup"><span data-stu-id="4c605-158">What you can do</span></span>**|
|------------------------------|:----------------------------|
|<span data-ttu-id="4c605-159">全域系統管理員</span><span class="sxs-lookup"><span data-stu-id="4c605-159">Global admin</span></span>| <span data-ttu-id="4c605-160">檢視和管理您的 CPV 設定檔</span><span class="sxs-lookup"><span data-stu-id="4c605-160">View and manage your CPV profile</span></span>|
||<span data-ttu-id="4c605-161">檢視和管理的任何使用者需要存取 CPV 功能</span><span class="sxs-lookup"><span data-stu-id="4c605-161">View and manage any of your users who need access to CPV capabilities</span></span>|

## <a name="manage-mpn-membership-and-your-company-non-aad-roles"></a><span data-ttu-id="4c605-162">管理 MPN 會員資格和您的公司 （非 AAD 角色）</span><span class="sxs-lookup"><span data-stu-id="4c605-162">Manage MPN membership and your company (non-AAD roles)</span></span>

|**<span data-ttu-id="4c605-163">角色</span><span class="sxs-lookup"><span data-stu-id="4c605-163">Role</span></span>** | **<span data-ttu-id="4c605-164">您可以執行的動作</span><span class="sxs-lookup"><span data-stu-id="4c605-164">What you can do</span></span>**|
|----------------------------|:----------------------------|
|<span data-ttu-id="4c605-165">MPN 系統管理員</span><span class="sxs-lookup"><span data-stu-id="4c605-165">MPN admin</span></span>|<span data-ttu-id="4c605-166">•Can 新增非租用戶使用者</span><span class="sxs-lookup"><span data-stu-id="4c605-166">•Can add non-tenant users</span></span>
||<span data-ttu-id="4c605-167">• 檢視中，建立和管理合作夥伴服務要求</span><span class="sxs-lookup"><span data-stu-id="4c605-167">• View, create, and manage partner service requests</span></span>
||<span data-ttu-id="4c605-168">• 檢視法律、 組織、 商務及 MPN 設定檔</span><span class="sxs-lookup"><span data-stu-id="4c605-168">• View legal, organization, business, and MPN profiles</span></span>
||<span data-ttu-id="4c605-169">• 檢視使用者詳細資料及資料及其技能資料</span><span class="sxs-lookup"><span data-stu-id="4c605-169">• View user details and their skills data</span></span>
||<span data-ttu-id="4c605-170">• 檢視專長認證</span><span class="sxs-lookup"><span data-stu-id="4c605-170">• View competencies</span></span>
||<span data-ttu-id="4c605-171">• 檢視及管理權益</span><span class="sxs-lookup"><span data-stu-id="4c605-171">• View and manage benefits</span></span>
||<span data-ttu-id="4c605-172">• 檢視及購買 MPN 優惠</span><span class="sxs-lookup"><span data-stu-id="4c605-172">• View and purchase MPN offers</span></span>
||<span data-ttu-id="4c605-173">• 檢視 MPN 優惠訂購記錄和發票</span><span class="sxs-lookup"><span data-stu-id="4c605-173">• View MPN offers order history and invoices</span></span>
||<span data-ttu-id="4c605-174">• 可以檢視合作夥伴貢獻資料</span><span class="sxs-lookup"><span data-stu-id="4c605-174">• Can view partner contribution data</span></span>
||<span data-ttu-id="4c605-175">• 可以使用憑證驗證工具</span><span class="sxs-lookup"><span data-stu-id="4c605-175">• Can work in the Voucher Validation tool</span></span>|
|<span data-ttu-id="4c605-176">帳戶管理</span><span class="sxs-lookup"><span data-stu-id="4c605-176">Account admin</span></span>| <span data-ttu-id="4c605-177">• 可以新增非租用戶使用者</span><span class="sxs-lookup"><span data-stu-id="4c605-177">•   Can add non-tenant users</span></span>
||<span data-ttu-id="4c605-178">• 新增或刪除位置</span><span class="sxs-lookup"><span data-stu-id="4c605-178">• Add or delete locations</span></span>
||<span data-ttu-id="4c605-179">-管理是系統管理員帳戶的相關的設定檔</span><span class="sxs-lookup"><span data-stu-id="4c605-179">- Manage profiles related to the accounts you are admin for</span></span> 
||<span data-ttu-id="4c605-180">• 將角色指派給非 AAD 角色的租用戶中的使用者</span><span class="sxs-lookup"><span data-stu-id="4c605-180">• Assign roles for users in tenant to non AAD roles</span></span> 
||<span data-ttu-id="4c605-181">• 註冊到計畫的位置</span><span class="sxs-lookup"><span data-stu-id="4c605-181">• Enroll locations into programs</span></span>

## <a name="manage-referrals-non-aad-roles"></a><span data-ttu-id="4c605-182">管理推薦 （非 AAD 角色）</span><span class="sxs-lookup"><span data-stu-id="4c605-182">Manage referrals (non-AAD roles)</span></span>

|**<span data-ttu-id="4c605-183">角色</span><span class="sxs-lookup"><span data-stu-id="4c605-183">Role</span></span>**|**<span data-ttu-id="4c605-184">您可以執行的動作</span><span class="sxs-lookup"><span data-stu-id="4c605-184">What you can do</span></span>**|
|-----------------------------|:------------------------|
|<span data-ttu-id="4c605-185">推薦系統管理員</span><span class="sxs-lookup"><span data-stu-id="4c605-185">Referrals admin</span></span>       |<span data-ttu-id="4c605-186">• 檢視中，建立和管理商務設定檔</span><span class="sxs-lookup"><span data-stu-id="4c605-186">•   View, create, and manage business profiles</span></span>
||<span data-ttu-id="4c605-187">• 接收及管理推薦</span><span class="sxs-lookup"><span data-stu-id="4c605-187">• Receive and manage referrals</span></span>
||<span data-ttu-id="4c605-188">• 檢視中，建立和管理合作夥伴服務要求</span><span class="sxs-lookup"><span data-stu-id="4c605-188">• View, create, and manage partner service requests</span></span>|
|<span data-ttu-id="4c605-189">商務設定檔系統管理員</span><span class="sxs-lookup"><span data-stu-id="4c605-189">Business profile admin</span></span>   |<span data-ttu-id="4c605-190">•View，建立和管理商務設定檔</span><span class="sxs-lookup"><span data-stu-id="4c605-190">•View, create, and manage business profile</span></span> 
||<span data-ttu-id="4c605-191">• 檢視中，建立和管理合作夥伴服務要求</span><span class="sxs-lookup"><span data-stu-id="4c605-191">• View, create, and manage partner service requests</span></span>|

## <a name="manage-incentives--non-aad-roles"></a><span data-ttu-id="4c605-192">管理獎勵 （非 AAD 角色）</span><span class="sxs-lookup"><span data-stu-id="4c605-192">Manage Incentives  (non-AAD roles)</span></span>

|**<span data-ttu-id="4c605-193">角色</span><span class="sxs-lookup"><span data-stu-id="4c605-193">Role</span></span>** | **<span data-ttu-id="4c605-194">您可以執行的動作</span><span class="sxs-lookup"><span data-stu-id="4c605-194">What you can do</span></span>**|
|------------------------------|:-------------------------|
|<span data-ttu-id="4c605-195">獎勵系統管理員</span><span class="sxs-lookup"><span data-stu-id="4c605-195">Incentives admin</span></span>|<span data-ttu-id="4c605-196">• 起始及管理獎勵</span><span class="sxs-lookup"><span data-stu-id="4c605-196">• Initiates and manages incentives</span></span> 
||<span data-ttu-id="4c605-197">• 可檢視和編輯獎勵計畫的各個層面</span><span class="sxs-lookup"><span data-stu-id="4c605-197">• Can view and edit all aspects of incentives programs</span></span>
||<span data-ttu-id="4c605-198">• 可檢視和編輯銀行和稅務詳細資料</span><span class="sxs-lookup"><span data-stu-id="4c605-198">• Can view and edit bank and tax details</span></span>
||<span data-ttu-id="4c605-199">• 檢視回贈和合作收益</span><span class="sxs-lookup"><span data-stu-id="4c605-199">• View rebate and co-op earnings</span></span>
||<span data-ttu-id="4c605-200">• 存取支援</span><span class="sxs-lookup"><span data-stu-id="4c605-200">• Access support</span></span>
||<span data-ttu-id="4c605-201">• 爭議獎勵付款</span><span class="sxs-lookup"><span data-stu-id="4c605-201">• Dispute incentives payments</span></span>|
|<span data-ttu-id="4c605-202">獎勵使用者</span><span class="sxs-lookup"><span data-stu-id="4c605-202">Incentives user</span></span>|<span data-ttu-id="4c605-203">• 可以檢視獎勵計畫</span><span class="sxs-lookup"><span data-stu-id="4c605-203">•  Can view incentives programs</span></span>
||<span data-ttu-id="4c605-204">• 可檢視和起始獎勵宣告</span><span class="sxs-lookup"><span data-stu-id="4c605-204">• Can view and initiate incentives claims</span></span>
||<span data-ttu-id="4c605-205">• 檢視回贈和合作收益</span><span class="sxs-lookup"><span data-stu-id="4c605-205">• View rebate and co-op earnings</span></span>
||<span data-ttu-id="4c605-206">• 檢視回贈和合作收益</span><span class="sxs-lookup"><span data-stu-id="4c605-206">• View rebate and co-op earnings</span></span>
||<span data-ttu-id="4c605-207">• 存取支援</span><span class="sxs-lookup"><span data-stu-id="4c605-207">• Access support</span></span>












