---
title: 指派使用者角色和權限 | 合作夥伴中心
ms.topic: article
ms.date: 3/5/19
description: 每一位員工需要能夠在合作夥伴中心內的使用者必須指派一個角色。
author: LauraBrenner
ms.author: labrenne
keywords: 角色, 權限, 系統管理員, 代理人
ms.localizationpriority: medium
ms.openlocfilehash: 66923c8a5d4912d178ef483a883f08f40ed8378b
ms.sourcegitcommit: 9a2bda49446030e60251c9c913259472ff2eed9a
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 03/08/2019
ms.locfileid: "57682486"
---
# <a name="assign-users-roles-and-permissions"></a><span data-ttu-id="7b74f-104">指派使用者角色和權限</span><span class="sxs-lookup"><span data-stu-id="7b74f-104">Assign users roles and permissions</span></span>


<span data-ttu-id="7b74f-105">您已設定您的夥伴設定檔，包括合法的名稱和地址、 支援詳細資料、 檔案稅務豁免、 銀行資訊和您公司的主要連絡人。</span><span class="sxs-lookup"><span data-stu-id="7b74f-105">You've set up your partner profile including legal name and address, support details, file tax exemptions, bank info, and the primary contact for your company.</span></span> <span data-ttu-id="7b74f-106">下一步： 讓您設定密碼和角色讓他們可以開始在合作夥伴中心與您的使用者。</span><span class="sxs-lookup"><span data-stu-id="7b74f-106">Next step: get your users set up with passwords and roles so they can begin working in Partner Center with you.</span></span>

## <a name="set-up-your-employees-to-work-in-partner-center"></a><span data-ttu-id="7b74f-107">設定您的員工，以在合作夥伴中心</span><span class="sxs-lookup"><span data-stu-id="7b74f-107">Set up your employees to work in Partner Center</span></span>

<span data-ttu-id="7b74f-108">您決定您的使用者需要合作夥伴中心的角色和權限給他們的存取類型。</span><span class="sxs-lookup"><span data-stu-id="7b74f-108">You determine the types of access your users have to Partner Center by the roles and permissions you give them.</span></span> <span data-ttu-id="7b74f-109">開始參與您的業務相關的角色。</span><span class="sxs-lookup"><span data-stu-id="7b74f-109">Roles are related to the program(s) your business is involved in.</span></span> <span data-ttu-id="7b74f-110">例如，如果您的企業雲端解決方案提供者 (CSP) 的企業，您將不只有標準的 Azure AD 租用戶全域管理員，例如管理角色，但需要角色專屬 CSP 計劃。</span><span class="sxs-lookup"><span data-stu-id="7b74f-110">For example,if your business is a Cloud Solution Provider (CSP) business, you will not only have the standard Azure AD tenant management roles such as global admin, but will need roles specific to the CSP program.</span></span> <span data-ttu-id="7b74f-111">每個程式都有特定的角色。</span><span class="sxs-lookup"><span data-stu-id="7b74f-111">Each program has roles specific to it.</span></span>

>[!Note]
> <span data-ttu-id="7b74f-112">Azure Active Directory (AAD) 租用戶角色包含全域管理員、 使用者管理員和 CSP 的角色。</span><span class="sxs-lookup"><span data-stu-id="7b74f-112">Azure Active Directory (AAD) tenant roles include global admin, user admin, and CSP roles.</span></span> <span data-ttu-id="7b74f-113">非 AAD 角色包括 MPN 管理、 商務設定檔管理員、 轉介系統管理員、 獎勵的系統管理員，以及獎勵的使用者。</span><span class="sxs-lookup"><span data-stu-id="7b74f-113">Non-AAD roles include MPN admin, business profile admin, referral admin, incentive admin, and incentive user.</span></span> 

### <a name="manage-commercial-transactions-in-partner-center-azure-ad-and-csp-roles"></a><span data-ttu-id="7b74f-114">管理在合作夥伴中心內的商業交易 (Azure AD 和 CSP 角色)</span><span class="sxs-lookup"><span data-stu-id="7b74f-114">Manage commercial transactions in Partner Center (Azure AD and CSP roles)</span></span>

|<span data-ttu-id="7b74f-115">**角色**</span><span class="sxs-lookup"><span data-stu-id="7b74f-115">**Role**</span></span>|<span data-ttu-id="7b74f-116">**他們可以做什麼**</span><span class="sxs-lookup"><span data-stu-id="7b74f-116">**What they can do**</span></span>|
|----------------------------------|:---------------------------------|
|<span data-ttu-id="7b74f-117">全域系統管理員</span><span class="sxs-lookup"><span data-stu-id="7b74f-117">Global admin</span></span>|<span data-ttu-id="7b74f-118">• 可以存取所有 Microsoft 帳戶/服務，以完整權限</span><span class="sxs-lookup"><span data-stu-id="7b74f-118">• Can access all Microsoft account/services with full privileges</span></span>
|      |<span data-ttu-id="7b74f-119">• 建立支援票證，如合作夥伴中心</span><span class="sxs-lookup"><span data-stu-id="7b74f-119">•   Create support tickets for the Partner Center</span></span>
||<span data-ttu-id="7b74f-120">• 檢視協議、 價格清單和供應項目</span><span class="sxs-lookup"><span data-stu-id="7b74f-120">• View agreements, price lists, and offers</span></span>
||<span data-ttu-id="7b74f-121">• 檢視中，建立和管理合作夥伴使用者</span><span class="sxs-lookup"><span data-stu-id="7b74f-121">• View, create, and manage partner users</span></span>|
|<span data-ttu-id="7b74f-122">使用者管理員</span><span class="sxs-lookup"><span data-stu-id="7b74f-122">User Admin</span></span>   | <span data-ttu-id="7b74f-123">• 檢視中，建立和管理使用者</span><span class="sxs-lookup"><span data-stu-id="7b74f-123">•   View, create, and manage users</span></span>
||<span data-ttu-id="7b74f-124">• 檢視所有夥伴設定檔</span><span class="sxs-lookup"><span data-stu-id="7b74f-124">• View all partner profiles</span></span>
||<span data-ttu-id="7b74f-125">• 檢視中，建立和管理合作夥伴使用者</span><span class="sxs-lookup"><span data-stu-id="7b74f-125">• View, create, and manage partner users</span></span>  |
|<span data-ttu-id="7b74f-126">帳單管理</span><span class="sxs-lookup"><span data-stu-id="7b74f-126">Billing admin</span></span> | <span data-ttu-id="7b74f-127">-檢視、 建立和管理計費、 發票和偵察檔案</span><span class="sxs-lookup"><span data-stu-id="7b74f-127">- View, create, and manage billing, invoices, and recon files</span></span>|
|<span data-ttu-id="7b74f-128">預設的使用者</span><span class="sxs-lookup"><span data-stu-id="7b74f-128">Default user</span></span>|  <span data-ttu-id="7b74f-129">檢視我的設定檔</span><span class="sxs-lookup"><span data-stu-id="7b74f-129">View My profile</span></span>   |
|<span data-ttu-id="7b74f-130">系統管理代理人</span><span class="sxs-lookup"><span data-stu-id="7b74f-130">Admin agent</span></span> | <span data-ttu-id="7b74f-131">• 客戶管理</span><span class="sxs-lookup"><span data-stu-id="7b74f-131">•    Customer management</span></span>
||<span data-ttu-id="7b74f-132">• 加入合作夥伴中心的裝置清單 <</span><span class="sxs-lookup"><span data-stu-id="7b74f-132">• Add device list to the Partner Center<</span></span>
||<span data-ttu-id="7b74f-133">• 建立和設定檔套用至裝置</span><span class="sxs-lookup"><span data-stu-id="7b74f-133">• Create and apply profiles to devices</span></span>
||<span data-ttu-id="7b74f-134">• 訂用帳戶管理</span><span class="sxs-lookup"><span data-stu-id="7b74f-134">• Subscription management</span></span>
||<span data-ttu-id="7b74f-135">• 服務健康情況和服務要求的客戶</span><span class="sxs-lookup"><span data-stu-id="7b74f-135">• Service health and service requests for customers</span></span>
||<span data-ttu-id="7b74f-136">• 要求委派的系統管理員權限</span><span class="sxs-lookup"><span data-stu-id="7b74f-136">• Request delegated administrator privileges</span></span>
||<span data-ttu-id="7b74f-137">• 檢視定價與優惠</span><span class="sxs-lookup"><span data-stu-id="7b74f-137">• View pricing and offers</span></span>
||<span data-ttu-id="7b74f-138">• 計費</span><span class="sxs-lookup"><span data-stu-id="7b74f-138">• Billing</span></span>
||<span data-ttu-id="7b74f-139">• 管理代表客戶</span><span class="sxs-lookup"><span data-stu-id="7b74f-139">• Administer on behalf of a customer</span></span>
||<span data-ttu-id="7b74f-140">• 暫存器值加入轉銷商</span><span class="sxs-lookup"><span data-stu-id="7b74f-140">• Register a value added reseller</span></span>|
|<span data-ttu-id="7b74f-141">銷售代理人</span><span class="sxs-lookup"><span data-stu-id="7b74f-141">Sales agent</span></span> | <span data-ttu-id="7b74f-142">• 客戶管理</span><span class="sxs-lookup"><span data-stu-id="7b74f-142">•    Customer management</span></span>
||<span data-ttu-id="7b74f-143">• 加入合作夥伴中心的裝置清單</span><span class="sxs-lookup"><span data-stu-id="7b74f-143">• Add device list to the Partner Center</span></span>
||<span data-ttu-id="7b74f-144">• 訂用帳戶管理</span><span class="sxs-lookup"><span data-stu-id="7b74f-144">• Subscription management</span></span>
||<span data-ttu-id="7b74f-145">• 檢視支援票證</span><span class="sxs-lookup"><span data-stu-id="7b74f-145">• View support tickets</span></span>
||<span data-ttu-id="7b74f-146">• 要求與客戶之間的關係</span><span class="sxs-lookup"><span data-stu-id="7b74f-146">• Request a relationship with a customer</span></span>
||<span data-ttu-id="7b74f-147">• 管理潛在客戶</span><span class="sxs-lookup"><span data-stu-id="7b74f-147">• Manage customer leads</span></span>
||<span data-ttu-id="7b74f-148">• 檢視客戶合約</span><span class="sxs-lookup"><span data-stu-id="7b74f-148">• View the customer agreement</span></span>
||<span data-ttu-id="7b74f-149">• 暫存器的附加價值的轉銷商</span><span class="sxs-lookup"><span data-stu-id="7b74f-149">• Register a value-added reseller</span></span>|
|<span data-ttu-id="7b74f-150">技術服務代理人</span><span class="sxs-lookup"><span data-stu-id="7b74f-150">Helpdesk agent</span></span>| <span data-ttu-id="7b74f-151">• 搜尋並檢視客戶</span><span class="sxs-lookup"><span data-stu-id="7b74f-151">•  Search for and view a customer</span></span>
||<span data-ttu-id="7b74f-152">• 編輯客戶詳細資料</span><span class="sxs-lookup"><span data-stu-id="7b74f-152">• Edit customer details</span></span>
||<span data-ttu-id="7b74f-153">• 協助解決客戶問題與帳務或訂用帳戶管理</span><span class="sxs-lookup"><span data-stu-id="7b74f-153">• Help resolve customer issues with billing or subscription management</span></span>
||<span data-ttu-id="7b74f-154">• 要求支援代表客戶 (注意：您必須是系統管理員代理程式，以完成這項工作如 Office 365 訂用帳戶）</span><span class="sxs-lookup"><span data-stu-id="7b74f-154">• Request support on behalf of customers (Note: You must be an admin agent to complete this task for Office 365 subscriptions)</span></span>
||<span data-ttu-id="7b74f-155">• 管理訂用帳戶和計費代表客戶的問題 (請注意：您必須是系統管理員代理程式，以完成這項工作如 Office 365 訂用帳戶）</span><span class="sxs-lookup"><span data-stu-id="7b74f-155">• Manage subscriptions and billing issues on behalf of customers (Note: You must be an admin agent to complete this task for Office 365 subscriptions)</span></span>|

### <a name="control-panel-vendor-cpv-csp-role-and-non-aad-role"></a><span data-ttu-id="7b74f-156">控制面板供應商 (CPV)。</span><span class="sxs-lookup"><span data-stu-id="7b74f-156">Control Panel Vendor (CPV).</span></span> <span data-ttu-id="7b74f-157">（CSP 角色和非 AAD 角色）</span><span class="sxs-lookup"><span data-stu-id="7b74f-157">(CSP role and non-AAD role)</span></span>
<span data-ttu-id="7b74f-158">CPVs 開發以供雲端解決方案提供者 (CSP) 合作夥伴，使其能夠將其系統與合作夥伴中心 Api 整合的應用程式。</span><span class="sxs-lookup"><span data-stu-id="7b74f-158">CPVs develop apps for use by Cloud Solution Provider (CSP) partners to enable them to integrate their systems with Partner Center APIs.</span></span> 

|<span data-ttu-id="7b74f-159">**角色**</span><span class="sxs-lookup"><span data-stu-id="7b74f-159">**Role**</span></span>   |<span data-ttu-id="7b74f-160">**您可以執行**</span><span class="sxs-lookup"><span data-stu-id="7b74f-160">**What you can do**</span></span>|
|------------------------------|:----------------------------|
|<span data-ttu-id="7b74f-161">全域系統管理員</span><span class="sxs-lookup"><span data-stu-id="7b74f-161">Global admin</span></span>| <span data-ttu-id="7b74f-162">檢視及管理您的 CPV 設定檔</span><span class="sxs-lookup"><span data-stu-id="7b74f-162">View and manage your CPV profile</span></span>|
||<span data-ttu-id="7b74f-163">檢視及管理任何您需要 CPV 功能的存取權的使用者</span><span class="sxs-lookup"><span data-stu-id="7b74f-163">View and manage any of your users who need access to CPV capabilities</span></span>|

## <a name="manage-mpn-membership-and-your-company-non-aad-roles"></a><span data-ttu-id="7b74f-164">管理 MPN 成員資格和您的公司 （非 AAD 角色）</span><span class="sxs-lookup"><span data-stu-id="7b74f-164">Manage MPN membership and your company (non-AAD roles)</span></span>

|<span data-ttu-id="7b74f-165">**角色**</span><span class="sxs-lookup"><span data-stu-id="7b74f-165">**Role**</span></span> | <span data-ttu-id="7b74f-166">**您可以執行**</span><span class="sxs-lookup"><span data-stu-id="7b74f-166">**What you can do**</span></span>|
|----------------------------|:----------------------------|
|<span data-ttu-id="7b74f-167">MPN 合作夥伴系統管理員</span><span class="sxs-lookup"><span data-stu-id="7b74f-167">MPN partner admin</span></span>|<span data-ttu-id="7b74f-168">•Can 新增非租用戶使用者</span><span class="sxs-lookup"><span data-stu-id="7b74f-168">•Can add non-tenant users</span></span>
||<span data-ttu-id="7b74f-169">• 檢視中，建立和管理協力廠商服務要求</span><span class="sxs-lookup"><span data-stu-id="7b74f-169">• View, create, and manage partner service requests</span></span>
||<span data-ttu-id="7b74f-170">• 合法的檢視、 組織、 商務和 MPN 設定檔</span><span class="sxs-lookup"><span data-stu-id="7b74f-170">• View legal, organization, business, and MPN profiles</span></span>
||<span data-ttu-id="7b74f-171">• 檢視使用者詳細資料和他們的技能的資料</span><span class="sxs-lookup"><span data-stu-id="7b74f-171">• View user details and their skills data</span></span>
||<span data-ttu-id="7b74f-172">• 檢視專長認證</span><span class="sxs-lookup"><span data-stu-id="7b74f-172">• View competencies</span></span>
||<span data-ttu-id="7b74f-173">• 檢視及管理優點</span><span class="sxs-lookup"><span data-stu-id="7b74f-173">• View and manage benefits</span></span>
||<span data-ttu-id="7b74f-174">• 檢視及購買 MPN 提供</span><span class="sxs-lookup"><span data-stu-id="7b74f-174">• View and purchase MPN offers</span></span>
||<span data-ttu-id="7b74f-175">• 檢視 MPN 提供訂單歷程記錄和發票</span><span class="sxs-lookup"><span data-stu-id="7b74f-175">• View MPN offers order history and invoices</span></span>
||<span data-ttu-id="7b74f-176">• 檢視夥伴參與的資料</span><span class="sxs-lookup"><span data-stu-id="7b74f-176">• View partner contribution data</span></span>
||<span data-ttu-id="7b74f-177">• 可以用於憑證驗證工具</span><span class="sxs-lookup"><span data-stu-id="7b74f-177">• Can work in the Voucher Validation tool</span></span>|
||<span data-ttu-id="7b74f-178">-檢視客戶資料分析</span><span class="sxs-lookup"><span data-stu-id="7b74f-178">- View customer data analytics</span></span>
|<span data-ttu-id="7b74f-179">帳戶系統管理員</span><span class="sxs-lookup"><span data-stu-id="7b74f-179">Account admin</span></span>| <span data-ttu-id="7b74f-180">• 可以新增非租用戶使用者</span><span class="sxs-lookup"><span data-stu-id="7b74f-180">•   Can add non-tenant users</span></span>
||<span data-ttu-id="7b74f-181">• 加入或刪除位置</span><span class="sxs-lookup"><span data-stu-id="7b74f-181">• Add or delete locations</span></span>
||<span data-ttu-id="7b74f-182">-管理您是系統管理員帳戶相關的設定檔</span><span class="sxs-lookup"><span data-stu-id="7b74f-182">- Manage profiles related to the accounts you are admin for</span></span> 
||<span data-ttu-id="7b74f-183">• 指派角色給非 AAD 角色的租用戶中使用者</span><span class="sxs-lookup"><span data-stu-id="7b74f-183">• Assign roles for users in tenant to non AAD roles</span></span> 
||<span data-ttu-id="7b74f-184">• 註冊到程式的位置</span><span class="sxs-lookup"><span data-stu-id="7b74f-184">• Enroll locations into programs</span></span>

## <a name="guest-user-must-be-added-to-the-aad-tenant"></a><span data-ttu-id="7b74f-185">（必須新增至 AAD 租用戶） 的來賓使用者</span><span class="sxs-lookup"><span data-stu-id="7b74f-185">Guest user (must be added to the AAD tenant)</span></span>

|<span data-ttu-id="7b74f-186">**來賓使用者**</span><span class="sxs-lookup"><span data-stu-id="7b74f-186">**Guest user**</span></span>   | <span data-ttu-id="7b74f-187">**角色**</span><span class="sxs-lookup"><span data-stu-id="7b74f-187">**Roles**</span></span>|
|---------------------------|:--------------------|
||<span data-ttu-id="7b74f-188">MPN 合作夥伴系統管理員</span><span class="sxs-lookup"><span data-stu-id="7b74f-188">MPN partner admin</span></span>|
||<span data-ttu-id="7b74f-189">帳戶系統管理員</span><span class="sxs-lookup"><span data-stu-id="7b74f-189">Accounts admin</span></span>|
||<span data-ttu-id="7b74f-190">獎勵系統管理員</span><span class="sxs-lookup"><span data-stu-id="7b74f-190">Incentives admin</span></span>|
||<span data-ttu-id="7b74f-191">商務設定檔系統管理員</span><span class="sxs-lookup"><span data-stu-id="7b74f-191">Business profile admin</span></span>|
||<span data-ttu-id="7b74f-192">轉介系統管理員</span><span class="sxs-lookup"><span data-stu-id="7b74f-192">Referrals admin</span></span>|


## <a name="manage-referrals-non-aad-roles"></a><span data-ttu-id="7b74f-193">管理轉介 （非 AAD 角色）</span><span class="sxs-lookup"><span data-stu-id="7b74f-193">Manage referrals (non-AAD roles)</span></span>

|<span data-ttu-id="7b74f-194">**角色**</span><span class="sxs-lookup"><span data-stu-id="7b74f-194">**Role**</span></span>|<span data-ttu-id="7b74f-195">**您可以執行**</span><span class="sxs-lookup"><span data-stu-id="7b74f-195">**What you can do**</span></span>|
|-----------------------------|:------------------------|
|<span data-ttu-id="7b74f-196">轉介系統管理員</span><span class="sxs-lookup"><span data-stu-id="7b74f-196">Referrals admin</span></span>       |<span data-ttu-id="7b74f-197">• 檢視中，建立和管理商務設定檔</span><span class="sxs-lookup"><span data-stu-id="7b74f-197">•   View, create, and manage business profiles</span></span>
||<span data-ttu-id="7b74f-198">• 接收及管理轉介</span><span class="sxs-lookup"><span data-stu-id="7b74f-198">• Receive and manage referrals</span></span>
||<span data-ttu-id="7b74f-199">• 檢視中，建立和管理協力廠商服務要求</span><span class="sxs-lookup"><span data-stu-id="7b74f-199">• View, create, and manage partner service requests</span></span>|
|<span data-ttu-id="7b74f-200">商務設定檔系統管理員</span><span class="sxs-lookup"><span data-stu-id="7b74f-200">Business profile admin</span></span>   |<span data-ttu-id="7b74f-201">•View，建立和管理商務設定檔</span><span class="sxs-lookup"><span data-stu-id="7b74f-201">•View, create, and manage business profile</span></span> 
||<span data-ttu-id="7b74f-202">• 檢視中，建立和管理協力廠商服務要求</span><span class="sxs-lookup"><span data-stu-id="7b74f-202">• View, create, and manage partner service requests</span></span>|

## <a name="manage-incentives--non-aad-roles"></a><span data-ttu-id="7b74f-203">管理獎勵 （非 AAD 角色）</span><span class="sxs-lookup"><span data-stu-id="7b74f-203">Manage Incentives  (non-AAD roles)</span></span>

|<span data-ttu-id="7b74f-204">**角色**</span><span class="sxs-lookup"><span data-stu-id="7b74f-204">**Role**</span></span> | <span data-ttu-id="7b74f-205">**您可以執行**</span><span class="sxs-lookup"><span data-stu-id="7b74f-205">**What you can do**</span></span>|
|------------------------------|:-------------------------|
|<span data-ttu-id="7b74f-206">獎勵系統管理員</span><span class="sxs-lookup"><span data-stu-id="7b74f-206">Incentives admin</span></span>|<span data-ttu-id="7b74f-207">• 起始並管理獎勵</span><span class="sxs-lookup"><span data-stu-id="7b74f-207">• Initiates and manages incentives</span></span> 
||<span data-ttu-id="7b74f-208">• 可以檢視和編輯獎勵程式的所有層面</span><span class="sxs-lookup"><span data-stu-id="7b74f-208">• Can view and edit all aspects of incentives programs</span></span>
||<span data-ttu-id="7b74f-209">• 可以檢視和編輯銀行和稅務詳細資料</span><span class="sxs-lookup"><span data-stu-id="7b74f-209">• Can view and edit bank and tax details</span></span>
||<span data-ttu-id="7b74f-210">• 檢視 rebate 和聯合盈餘</span><span class="sxs-lookup"><span data-stu-id="7b74f-210">• View rebate and co-op earnings</span></span>
||<span data-ttu-id="7b74f-211">• 存取支援</span><span class="sxs-lookup"><span data-stu-id="7b74f-211">• Access support</span></span>
||<span data-ttu-id="7b74f-212">• 爭議獎勵付款</span><span class="sxs-lookup"><span data-stu-id="7b74f-212">• Dispute incentives payments</span></span>|
|<span data-ttu-id="7b74f-213">獎勵使用者</span><span class="sxs-lookup"><span data-stu-id="7b74f-213">Incentives user</span></span>|<span data-ttu-id="7b74f-214">• 可以檢視獎勵的程式</span><span class="sxs-lookup"><span data-stu-id="7b74f-214">•  Can view incentives programs</span></span>
||<span data-ttu-id="7b74f-215">• 可以檢視並起始獎勵宣告</span><span class="sxs-lookup"><span data-stu-id="7b74f-215">• Can view and initiate incentives claims</span></span>
||<span data-ttu-id="7b74f-216">• 檢視 rebate 和聯合盈餘</span><span class="sxs-lookup"><span data-stu-id="7b74f-216">• View rebate and co-op earnings</span></span>
||<span data-ttu-id="7b74f-217">• 檢視 rebate 和聯合盈餘</span><span class="sxs-lookup"><span data-stu-id="7b74f-217">• View rebate and co-op earnings</span></span>
||<span data-ttu-id="7b74f-218">• 存取支援</span><span class="sxs-lookup"><span data-stu-id="7b74f-218">• Access support</span></span>












