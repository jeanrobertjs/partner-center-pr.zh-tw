---
title: 指派使用者角色和權限 | 合作夥伴中心
ms.topic: article
ms.date: 3/5/2019
description: 需要在合作夥伴中心工作的每個員工都必須獲派角色。
author: LauraBrenner
ms.author: labrenne
keywords: 角色, 權限, 系統管理員, 代理人
ms.localizationpriority: medium
ms.openlocfilehash: 744ce84c47d3adaf21d8f7b790001737d6489cdb
ms.sourcegitcommit: 9d01fb30eafc523784ecc3568c05da9bbe9a1e8c
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 08/01/2019
ms.locfileid: "68708862"
---
# <a name="assign-users-roles-and-permissions"></a><span data-ttu-id="6188a-104">指派使用者角色和權限</span><span class="sxs-lookup"><span data-stu-id="6188a-104">Assign users roles and permissions</span></span>


<span data-ttu-id="6188a-105">您已設定您的夥伴設定檔, 包括合法的名稱和位址、支援詳細資料、檔案稅務豁免、銀行資訊, 以及貴公司的主要連絡人。</span><span class="sxs-lookup"><span data-stu-id="6188a-105">You've set up your partner profile including legal name and address, support details, file tax exemptions, bank info, and the primary contact for your company.</span></span> <span data-ttu-id="6188a-106">下一步: 讓您的使用者使用密碼和角色來設定, 讓他們可以開始在合作夥伴中心與您合作。</span><span class="sxs-lookup"><span data-stu-id="6188a-106">Next step: get your users set up with passwords and roles so they can begin working in Partner Center with you.</span></span>

## <a name="set-up-your-employees-to-work-in-partner-center"></a><span data-ttu-id="6188a-107">設定您的員工以在合作夥伴中心工作</span><span class="sxs-lookup"><span data-stu-id="6188a-107">Set up your employees to work in Partner Center</span></span>

<span data-ttu-id="6188a-108">您可以依據您提供的角色和許可權來決定您的使用者對合作夥伴中心所擁有的存取類型。</span><span class="sxs-lookup"><span data-stu-id="6188a-108">You determine the types of access your users have to Partner Center by the roles and permissions you give them.</span></span> <span data-ttu-id="6188a-109">角色與您的企業所牽涉的程式相關。</span><span class="sxs-lookup"><span data-stu-id="6188a-109">Roles are related to the program(s) your business is involved in.</span></span> <span data-ttu-id="6188a-110">例如, 如果您的企業是雲端解決方案提供者 (CSP) 企業, 您不僅可以使用標準的 Azure AD 租使用者管理角色 (例如全域管理員), 還需要 CSP 方案專屬的角色。</span><span class="sxs-lookup"><span data-stu-id="6188a-110">For example,if your business is a Cloud Solution Provider (CSP) business, you will not only have the standard Azure AD tenant management roles such as global admin, but will need roles specific to the CSP program.</span></span> <span data-ttu-id="6188a-111">每個程式都有其特有的角色。</span><span class="sxs-lookup"><span data-stu-id="6188a-111">Each program has roles specific to it.</span></span>

>[!Note]
> <span data-ttu-id="6188a-112">Azure Active Directory (AAD) 租使用者角色包含全域管理員、使用者管理員和 CSP 角色。</span><span class="sxs-lookup"><span data-stu-id="6188a-112">Azure Active Directory (AAD) tenant roles include global admin, user admin, and CSP roles.</span></span> <span data-ttu-id="6188a-113">非 AAD 角色是指不管理租使用者的角色, 包括 MPN 管理員、商務設定檔管理員、參考管理員、獎勵管理員和獎勵使用者。</span><span class="sxs-lookup"><span data-stu-id="6188a-113">Non-AAD roles are those roles that do not manage the tenant, and they include MPN admin, business profile admin, referral admin, incentive admin, and incentive user.</span></span> 

### <a name="manage-commercial-transactions-in-partner-center-azure-ad-and-csp-roles"></a><span data-ttu-id="6188a-114">在合作夥伴中心管理商業交易 (Azure AD 和 CSP 角色)</span><span class="sxs-lookup"><span data-stu-id="6188a-114">Manage commercial transactions in Partner Center (Azure AD and CSP roles)</span></span>

|<span data-ttu-id="6188a-115">**角色**</span><span class="sxs-lookup"><span data-stu-id="6188a-115">**Role**</span></span>|<span data-ttu-id="6188a-116">**可以執行的動作**</span><span class="sxs-lookup"><span data-stu-id="6188a-116">**What they can do**</span></span>|
|----------------------------------|:---------------------------------|
|<span data-ttu-id="6188a-117">全域系統管理員</span><span class="sxs-lookup"><span data-stu-id="6188a-117">Global admin</span></span>|<span data-ttu-id="6188a-118">•可以存取所有具有完整許可權的 Microsoft 帳戶/服務</span><span class="sxs-lookup"><span data-stu-id="6188a-118">• Can access all Microsoft account/services with full privileges</span></span>
|      |<span data-ttu-id="6188a-119">•建立合作夥伴中心的支援票證</span><span class="sxs-lookup"><span data-stu-id="6188a-119">•   Create support tickets for the Partner Center</span></span>
||<span data-ttu-id="6188a-120">•查看合約、價格清單和供應專案</span><span class="sxs-lookup"><span data-stu-id="6188a-120">• View agreements, price lists, and offers</span></span>
||<span data-ttu-id="6188a-121">•查看、建立和管理合作夥伴使用者</span><span class="sxs-lookup"><span data-stu-id="6188a-121">• View, create, and manage partner users</span></span>|
||  <span data-ttu-id="6188a-122">查看、建立和管理帳單、發票和偵察檔案</span><span class="sxs-lookup"><span data-stu-id="6188a-122">View, create, and manage billing, invoices, and recon files</span></span>
|<span data-ttu-id="6188a-123">使用者管理系統管理員</span><span class="sxs-lookup"><span data-stu-id="6188a-123">User management admin</span></span>   | <span data-ttu-id="6188a-124">•查看、建立及管理使用者</span><span class="sxs-lookup"><span data-stu-id="6188a-124">•    View, create, and manage users</span></span>
||<span data-ttu-id="6188a-125">•查看所有夥伴設定檔</span><span class="sxs-lookup"><span data-stu-id="6188a-125">• View all partner profiles</span></span>
||<span data-ttu-id="6188a-126">•查看、建立和管理合作夥伴使用者</span><span class="sxs-lookup"><span data-stu-id="6188a-126">• View, create, and manage partner users</span></span>  |
|<span data-ttu-id="6188a-127">帳單管理</span><span class="sxs-lookup"><span data-stu-id="6188a-127">Billing admin</span></span> | <span data-ttu-id="6188a-128">-查看、建立及管理帳單、發票和偵察檔案</span><span class="sxs-lookup"><span data-stu-id="6188a-128">- View, create, and manage billing, invoices, and recon files</span></span>|
|<span data-ttu-id="6188a-129">預設使用者</span><span class="sxs-lookup"><span data-stu-id="6188a-129">Default user</span></span>|  <span data-ttu-id="6188a-130">View 我的設定檔</span><span class="sxs-lookup"><span data-stu-id="6188a-130">View My profile</span></span>   |
|<span data-ttu-id="6188a-131">系統管理代理人</span><span class="sxs-lookup"><span data-stu-id="6188a-131">Admin agent</span></span> | <span data-ttu-id="6188a-132">•客戶管理</span><span class="sxs-lookup"><span data-stu-id="6188a-132">•    Customer management</span></span>
||<span data-ttu-id="6188a-133">•將裝置清單新增至合作夥伴中心</span><span class="sxs-lookup"><span data-stu-id="6188a-133">• Add device list to the Partner Center</span></span>
||<span data-ttu-id="6188a-134">•建立設定檔並將其套用至裝置</span><span class="sxs-lookup"><span data-stu-id="6188a-134">• Create and apply profiles to devices</span></span>
||<span data-ttu-id="6188a-135">•訂用帳戶管理</span><span class="sxs-lookup"><span data-stu-id="6188a-135">• Subscription management</span></span>
||<span data-ttu-id="6188a-136">•客戶的服務健康狀態和服務要求</span><span class="sxs-lookup"><span data-stu-id="6188a-136">• Service health and service requests for customers</span></span>
||<span data-ttu-id="6188a-137">•要求委派的系統管理員許可權</span><span class="sxs-lookup"><span data-stu-id="6188a-137">• Request delegated administrator privileges</span></span>
||<span data-ttu-id="6188a-138">•查看定價和優惠</span><span class="sxs-lookup"><span data-stu-id="6188a-138">• View pricing and offers</span></span>
||<span data-ttu-id="6188a-139">•計費</span><span class="sxs-lookup"><span data-stu-id="6188a-139">• Billing</span></span>
||<span data-ttu-id="6188a-140">•代表客戶進行管理</span><span class="sxs-lookup"><span data-stu-id="6188a-140">• Administer on behalf of a customer</span></span>
||<span data-ttu-id="6188a-141">•註冊增值轉銷商</span><span class="sxs-lookup"><span data-stu-id="6188a-141">• Register a value added reseller</span></span>|
|<span data-ttu-id="6188a-142">銷售代理人</span><span class="sxs-lookup"><span data-stu-id="6188a-142">Sales agent</span></span> | <span data-ttu-id="6188a-143">•客戶管理</span><span class="sxs-lookup"><span data-stu-id="6188a-143">•    Customer management</span></span>
||<span data-ttu-id="6188a-144">•將裝置清單新增至合作夥伴中心</span><span class="sxs-lookup"><span data-stu-id="6188a-144">• Add device list to the Partner Center</span></span>
||<span data-ttu-id="6188a-145">•訂用帳戶管理</span><span class="sxs-lookup"><span data-stu-id="6188a-145">• Subscription management</span></span>
||<span data-ttu-id="6188a-146">•查看價格清單和供應專案</span><span class="sxs-lookup"><span data-stu-id="6188a-146">• View price lists and offers</span></span>
||<span data-ttu-id="6188a-147">•查看支援票證</span><span class="sxs-lookup"><span data-stu-id="6188a-147">• View support tickets</span></span>
||<span data-ttu-id="6188a-148">•要求與客戶的關係</span><span class="sxs-lookup"><span data-stu-id="6188a-148">• Request a relationship with a customer</span></span>
||<span data-ttu-id="6188a-149">•管理潛在客戶</span><span class="sxs-lookup"><span data-stu-id="6188a-149">• Manage customer leads</span></span>
||<span data-ttu-id="6188a-150">•查看客戶合約</span><span class="sxs-lookup"><span data-stu-id="6188a-150">• View the customer agreement</span></span>
||<span data-ttu-id="6188a-151">•註冊增值轉銷商</span><span class="sxs-lookup"><span data-stu-id="6188a-151">• Register a value-added reseller</span></span>|
|<span data-ttu-id="6188a-152">技術服務代理人</span><span class="sxs-lookup"><span data-stu-id="6188a-152">Helpdesk agent</span></span>| <span data-ttu-id="6188a-153">•搜尋並查看客戶</span><span class="sxs-lookup"><span data-stu-id="6188a-153">•  Search for and view a customer</span></span>
||<span data-ttu-id="6188a-154">•編輯客戶詳細資料</span><span class="sxs-lookup"><span data-stu-id="6188a-154">• Edit customer details</span></span>
||<span data-ttu-id="6188a-155">•協助解決客戶在帳單或訂用帳戶管理方面的問題</span><span class="sxs-lookup"><span data-stu-id="6188a-155">• Help resolve customer issues with billing or subscription management</span></span>
||<span data-ttu-id="6188a-156">•代表客戶要求支援 (注意:您必須是系統管理員代理程式, 才能完成 Office 365 訂閱的這項工作)</span><span class="sxs-lookup"><span data-stu-id="6188a-156">• Request support on behalf of customers (Note: You must be an admin agent to complete this task for Office 365 subscriptions)</span></span>
||<span data-ttu-id="6188a-157">•代表客戶管理訂閱和帳單問題 (注意:您必須是系統管理員代理程式, 才能完成 Office 365 訂閱的這項工作)</span><span class="sxs-lookup"><span data-stu-id="6188a-157">• Manage subscriptions and billing issues on behalf of customers (Note: You must be an admin agent to complete this task for Office 365 subscriptions)</span></span>|

### <a name="control-panel-vendor-cpv-csp-role-and-non-aad-role"></a><span data-ttu-id="6188a-158">控制台廠商 (CPV)。</span><span class="sxs-lookup"><span data-stu-id="6188a-158">Control Panel Vendor (CPV).</span></span> <span data-ttu-id="6188a-159">(CSP 角色和非 AAD 角色)</span><span class="sxs-lookup"><span data-stu-id="6188a-159">(CSP role and non-AAD role)</span></span>
<span data-ttu-id="6188a-160">CPVs 開發可供雲端解決方案提供者 (CSP) 合作夥伴使用的應用程式, 讓他們能夠整合其系統與合作夥伴中心 Api。</span><span class="sxs-lookup"><span data-stu-id="6188a-160">CPVs develop apps for use by Cloud Solution Provider (CSP) partners to enable them to integrate their systems with Partner Center APIs.</span></span> 

|<span data-ttu-id="6188a-161">**角色**</span><span class="sxs-lookup"><span data-stu-id="6188a-161">**Role**</span></span>   |<span data-ttu-id="6188a-162">**您可以執行的動作**</span><span class="sxs-lookup"><span data-stu-id="6188a-162">**What you can do**</span></span>|
|------------------------------|:----------------------------|
|<span data-ttu-id="6188a-163">全域系統管理員</span><span class="sxs-lookup"><span data-stu-id="6188a-163">Global admin</span></span>| <span data-ttu-id="6188a-164">查看及管理您的 CPV 設定檔</span><span class="sxs-lookup"><span data-stu-id="6188a-164">View and manage your CPV profile</span></span>|
||<span data-ttu-id="6188a-165">查看和管理任何需要存取 CPV 功能的使用者</span><span class="sxs-lookup"><span data-stu-id="6188a-165">View and manage any of your users who need access to CPV capabilities</span></span>|

### <a name="guest-user-must-be-added-to-the-aad-tenant"></a><span data-ttu-id="6188a-166">來賓使用者 (必須新增至 AAD 租使用者)</span><span class="sxs-lookup"><span data-stu-id="6188a-166">Guest user (must be added to the AAD tenant)</span></span>

|<span data-ttu-id="6188a-167">**來賓使用者**</span><span class="sxs-lookup"><span data-stu-id="6188a-167">**Guest user**</span></span>   | <span data-ttu-id="6188a-168">**角色**</span><span class="sxs-lookup"><span data-stu-id="6188a-168">**Roles**</span></span>|
|---------------------------|:--------------------|
||<span data-ttu-id="6188a-169">MPN 合作夥伴系統管理員</span><span class="sxs-lookup"><span data-stu-id="6188a-169">MPN partner admin</span></span>|
||<span data-ttu-id="6188a-170">帳戶管理員</span><span class="sxs-lookup"><span data-stu-id="6188a-170">Accounts admin</span></span>|
||<span data-ttu-id="6188a-171">獎勵系統管理員</span><span class="sxs-lookup"><span data-stu-id="6188a-171">Incentives admin</span></span>|
||<span data-ttu-id="6188a-172">商務設定檔系統管理員</span><span class="sxs-lookup"><span data-stu-id="6188a-172">Business profile admin</span></span>|
||<span data-ttu-id="6188a-173">參考系統管理員</span><span class="sxs-lookup"><span data-stu-id="6188a-173">Referrals admin</span></span>|


## <a name="manage-mpn-membership-and-your-company-non-aad-roles-these-roles-manage-the-company-business-rather-than-the-tenant"></a><span data-ttu-id="6188a-174">管理 MPN 成員資格和您的公司 (非 AAD 角色: 這些角色會管理公司業務, 而不是租使用者)</span><span class="sxs-lookup"><span data-stu-id="6188a-174">Manage MPN membership and your company (non-AAD roles: these roles manage the company business rather than the tenant)</span></span>

|<span data-ttu-id="6188a-175">**角色**</span><span class="sxs-lookup"><span data-stu-id="6188a-175">**Role**</span></span> | <span data-ttu-id="6188a-176">**您可以執行的動作**</span><span class="sxs-lookup"><span data-stu-id="6188a-176">**What you can do**</span></span>|
|----------------------------|:----------------------------|
|<span data-ttu-id="6188a-177">MPN 合作夥伴系統管理員</span><span class="sxs-lookup"><span data-stu-id="6188a-177">MPN partner admin</span></span>|<span data-ttu-id="6188a-178">•查看、建立和管理夥伴服務要求</span><span class="sxs-lookup"><span data-stu-id="6188a-178">•    View, create, and manage partner service requests</span></span>||
||<span data-ttu-id="6188a-179">•查看法律、公司、商務和 MPN 設定檔</span><span class="sxs-lookup"><span data-stu-id="6188a-179">• View legal, company, business, and MPN profiles</span></span>
||<span data-ttu-id="6188a-180">•查看使用者詳細資料及其技能資料</span><span class="sxs-lookup"><span data-stu-id="6188a-180">• View user details and their skills data</span></span>
||<span data-ttu-id="6188a-181">•查看專長認證</span><span class="sxs-lookup"><span data-stu-id="6188a-181">• View competencies</span></span>
||<span data-ttu-id="6188a-182">•查看和管理權益</span><span class="sxs-lookup"><span data-stu-id="6188a-182">• View and manage benefits</span></span>
||<span data-ttu-id="6188a-183">•觀看並購買 MPN 優惠</span><span class="sxs-lookup"><span data-stu-id="6188a-183">• View and purchase MPN offers</span></span>
||<span data-ttu-id="6188a-184">• View MPN 提供訂單歷程記錄和發票</span><span class="sxs-lookup"><span data-stu-id="6188a-184">• View MPN offers order history and invoices</span></span>
||<span data-ttu-id="6188a-185">•觀看合作夥伴的貢獻指標資料</span><span class="sxs-lookup"><span data-stu-id="6188a-185">• View partner contribution indicator data</span></span>
||<span data-ttu-id="6188a-186">•可在「憑證驗證」工具中工作</span><span class="sxs-lookup"><span data-stu-id="6188a-186">• Can work in the Voucher Validation tool</span></span>|
||<span data-ttu-id="6188a-187">-查看客戶資料分析</span><span class="sxs-lookup"><span data-stu-id="6188a-187">- View customer data analytics</span></span>
|| <span data-ttu-id="6188a-188">查看公司內的其他使用者角色, 但無法指派角色</span><span class="sxs-lookup"><span data-stu-id="6188a-188">View other user roles within company, but can't assign roles</span></span>
|<span data-ttu-id="6188a-189">帳戶系統管理員</span><span class="sxs-lookup"><span data-stu-id="6188a-189">Account admin</span></span>| <span data-ttu-id="6188a-190">新增位置</span><span class="sxs-lookup"><span data-stu-id="6188a-190">Add locations</span></span>
|| <span data-ttu-id="6188a-191">管理與您的系統管理員帳戶相關的設定檔</span><span class="sxs-lookup"><span data-stu-id="6188a-191">Manage profiles related to the accounts you are admin for</span></span> 
||<span data-ttu-id="6188a-192">•將租使用者中使用者的角色指派給非 AAD 角色</span><span class="sxs-lookup"><span data-stu-id="6188a-192">• Assign roles for users in tenant to non AAD roles</span></span> 
||<span data-ttu-id="6188a-193">•在程式中註冊位置</span><span class="sxs-lookup"><span data-stu-id="6188a-193">• Enroll locations into programs</span></span>


## <a name="manage-referrals"></a><span data-ttu-id="6188a-194">管理參考</span><span class="sxs-lookup"><span data-stu-id="6188a-194">Manage referrals</span></span> 

|<span data-ttu-id="6188a-195">**角色**</span><span class="sxs-lookup"><span data-stu-id="6188a-195">**Role**</span></span>|<span data-ttu-id="6188a-196">**您可以執行的動作**</span><span class="sxs-lookup"><span data-stu-id="6188a-196">**What you can do**</span></span>|
|-----------------------------|:------------------------|
|<span data-ttu-id="6188a-197">參考系統管理員</span><span class="sxs-lookup"><span data-stu-id="6188a-197">Referrals admin</span></span>       |<span data-ttu-id="6188a-198">•查看、建立及管理商務設定檔</span><span class="sxs-lookup"><span data-stu-id="6188a-198">•   View, create, and manage business profiles</span></span>
||<span data-ttu-id="6188a-199">•接收和管理參考</span><span class="sxs-lookup"><span data-stu-id="6188a-199">• Receive and manage referrals</span></span>
||<span data-ttu-id="6188a-200">•查看、建立和管理共同銷售的參考</span><span class="sxs-lookup"><span data-stu-id="6188a-200">• View, create, and manage co-sell referrals</span></span>|
||<span data-ttu-id="6188a-201">•查看、建立和管理夥伴服務要求</span><span class="sxs-lookup"><span data-stu-id="6188a-201">• View, create, and manage partner service requests</span></span>
|<span data-ttu-id="6188a-202">商務設定檔系統管理員</span><span class="sxs-lookup"><span data-stu-id="6188a-202">Business profile admin</span></span>   |<span data-ttu-id="6188a-203">•查看、建立及管理商務設定檔</span><span class="sxs-lookup"><span data-stu-id="6188a-203">• View, create, and manage business profile</span></span> 
||<span data-ttu-id="6188a-204">•查看、建立和管理夥伴服務要求</span><span class="sxs-lookup"><span data-stu-id="6188a-204">• View, create, and manage partner service requests</span></span>|

## <a name="manage-incentives"></a><span data-ttu-id="6188a-205">管理獎勵</span><span class="sxs-lookup"><span data-stu-id="6188a-205">Manage incentives</span></span> 

|<span data-ttu-id="6188a-206">**角色**</span><span class="sxs-lookup"><span data-stu-id="6188a-206">**Role**</span></span> | <span data-ttu-id="6188a-207">**您可以執行的動作**</span><span class="sxs-lookup"><span data-stu-id="6188a-207">**What you can do**</span></span>|
|------------------------------|:-------------------------|
|<span data-ttu-id="6188a-208">獎勵系統管理員</span><span class="sxs-lookup"><span data-stu-id="6188a-208">Incentives admin</span></span>|<span data-ttu-id="6188a-209">•起始和管理獎勵</span><span class="sxs-lookup"><span data-stu-id="6188a-209">• Initiates and manages incentives</span></span> 
||<span data-ttu-id="6188a-210">•可以查看和編輯獎勵計畫的所有層面</span><span class="sxs-lookup"><span data-stu-id="6188a-210">• Can view and edit all aspects of incentives programs</span></span>
||<span data-ttu-id="6188a-211">•可以查看和編輯銀行和稅務詳細資料</span><span class="sxs-lookup"><span data-stu-id="6188a-211">• Can view and edit bank and tax details</span></span>
||<span data-ttu-id="6188a-212">•觀看退款和共同作業收益</span><span class="sxs-lookup"><span data-stu-id="6188a-212">• View rebate and co-op earnings</span></span>
||<span data-ttu-id="6188a-213">•存取支援</span><span class="sxs-lookup"><span data-stu-id="6188a-213">• Access support</span></span>
||<span data-ttu-id="6188a-214">•爭議獎勵付款</span><span class="sxs-lookup"><span data-stu-id="6188a-214">• Dispute incentives payments</span></span>|
|<span data-ttu-id="6188a-215">獎勵使用者</span><span class="sxs-lookup"><span data-stu-id="6188a-215">Incentives user</span></span>|<span data-ttu-id="6188a-216">•可以查看獎勵計畫</span><span class="sxs-lookup"><span data-stu-id="6188a-216">•  Can view incentives programs</span></span>
||<span data-ttu-id="6188a-217">•可以查看並起始獎勵宣告</span><span class="sxs-lookup"><span data-stu-id="6188a-217">• Can view and initiate incentives claims</span></span>
||<span data-ttu-id="6188a-218">•觀看退款和共同作業收益</span><span class="sxs-lookup"><span data-stu-id="6188a-218">• View rebate and co-op earnings</span></span>
||<span data-ttu-id="6188a-219">•存取支援</span><span class="sxs-lookup"><span data-stu-id="6188a-219">• Access support</span></span>












