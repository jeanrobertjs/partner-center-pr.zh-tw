---
title: 合作夥伴安全性需求常見問題 |合作夥伴中心
ms.topic: article
ms.date: 07/18/2019
description: 關於合作夥伴安全性需求的常見問題
author: isaiahwilliams
ms.author: iswillia
keywords: Azure Active Directory, 雲端解決方案提供者, 雲端解決方案提供者方案, CSP, 控制台廠商, CPV, 多重要素驗證, MFA, 安全應用程式模型, 安全應用程式模型, 安全性
ms.localizationpriority: medium
ms.openlocfilehash: 1a178dc71f8042e6b39a316c6c889b619aaed12c
ms.sourcegitcommit: 5c8ac1b6d29d183d85582d6eb32e37b91dd8c6c1
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 07/18/2019
ms.locfileid: "68315547"
---
# <a name="frequently-asked-questions-about-the-partner-security-requirements"></a><span data-ttu-id="62fed-104">關於合作夥伴安全性需求的常見問題</span><span class="sxs-lookup"><span data-stu-id="62fed-104">Frequently asked questions about the partner security requirements</span></span>

<span data-ttu-id="62fed-105">本文包含[合作夥伴安全性需求](partner-security-requirements.md)的一些常見問題。</span><span class="sxs-lookup"><span data-stu-id="62fed-105">This article contains some frequently asked questions for the [partner security requirements](partner-security-requirements.md).</span></span> <span data-ttu-id="62fed-106">您可以在[這裡](http://assetsprod.microsoft.com/security-requirements-faq.pdf)找到完整的常見問題清單。</span><span class="sxs-lookup"><span data-stu-id="62fed-106">You can find a comprehensive list of frequently asked questions [here](http://assetsprod.microsoft.com/security-requirements-faq.pdf).</span></span>

## <a name="conditional-access"></a><span data-ttu-id="62fed-107">條件式存取</span><span class="sxs-lookup"><span data-stu-id="62fed-107">Conditional Access</span></span>

### <a name="can-conditional-access-be-used"></a><span data-ttu-id="62fed-108">是否可以使用條件式存取？</span><span class="sxs-lookup"><span data-stu-id="62fed-108">Can conditional access be used?</span></span>

<span data-ttu-id="62fed-109">是, 您可以使用條件式存取, 為您的夥伴租使用者中的每個使用者 (包括服務帳戶) 強制執行 MFA。</span><span class="sxs-lookup"><span data-stu-id="62fed-109">Yes, you can use conditional access to enforce MFA for each user, including service accounts, in your partner tenant.</span></span> <span data-ttu-id="62fed-110">不過, 由於身為合作夥伴的高度特殊許可權, 我們必須確保每個使用者都有每個單一驗證的 MFA 挑戰。</span><span class="sxs-lookup"><span data-stu-id="62fed-110">However, given the highly privileged nature of being a partner we need to ensure that each user has an MFA challenge for every single authentication.</span></span> <span data-ttu-id="62fed-111">這表示您將無法利用避開 MFA 需求的條件式存取功能。</span><span class="sxs-lookup"><span data-stu-id="62fed-111">This means you will not be able to leverage feature of conditional access that circumvent the requirement for MFA.</span></span>

## <a name="multi-factor-authentication"></a><span data-ttu-id="62fed-112">多重要素驗證</span><span class="sxs-lookup"><span data-stu-id="62fed-112">Multi-Factor Authentication</span></span>

### <a name="are-my-customers-subject-to-the-partner-security-requirements"></a><span data-ttu-id="62fed-113">我的客戶是否遵守合作夥伴的安全性需求？</span><span class="sxs-lookup"><span data-stu-id="62fed-113">Are my customers subject to the partner security requirements?</span></span>

<span data-ttu-id="62fed-114">否, 您不需要對客戶的 Azure AD 租使用者中的每位使用者強制執行 MFA。</span><span class="sxs-lookup"><span data-stu-id="62fed-114">No, it is not required that you enforce MFA for each user in your customer's Azure AD tenants.</span></span> <span data-ttu-id="62fed-115">不過, 建議您與每個客戶合作, 以判斷保護其使用者的最佳方式。</span><span class="sxs-lookup"><span data-stu-id="62fed-115">However, it is recommended that you work with each customer to determine how best to protect their users.</span></span>

### <a name="can-app-passwords-be-used-with-the-baseline-protection-policies"></a><span data-ttu-id="62fed-116">應用程式密碼可以搭配基準保護原則使用嗎？</span><span class="sxs-lookup"><span data-stu-id="62fed-116">Can app passwords be used with the baseline protection policies?</span></span>

<span data-ttu-id="62fed-117">是, 可以使用[應用程式密碼](https://docs.microsoft.com/azure/active-directory/authentication/howto-mfa-mfasettings#app-passwords)。</span><span class="sxs-lookup"><span data-stu-id="62fed-117">Yes, [app passwords](https://docs.microsoft.com/azure/active-directory/authentication/howto-mfa-mfasettings#app-passwords) can be used.</span></span> <span data-ttu-id="62fed-118">您應該參閱使用[此處](https://docs.microsoft.com/azure/active-directory/authentication/howto-mfa-mfasettings#considerations-about-app-passwords)記載的應用程式密碼的考慮, 以判斷是否支援您的需求。</span><span class="sxs-lookup"><span data-stu-id="62fed-118">You should review the considerations for using app passwords documented [here](https://docs.microsoft.com/azure/active-directory/authentication/howto-mfa-mfasettings#considerations-about-app-passwords) to determine if they are supported for your need.</span></span>

### <a name="can-any-user-be-excluded-from-this-requirement"></a><span data-ttu-id="62fed-119">是否可以將任何使用者排除在此需求之外？</span><span class="sxs-lookup"><span data-stu-id="62fed-119">Can any user be excluded from this requirement?</span></span> 

<span data-ttu-id="62fed-120">否, 您的合作夥伴租使用者中包含服務帳戶的每個使用者都需要使用 MFA 進行驗證。</span><span class="sxs-lookup"><span data-stu-id="62fed-120">No, each user, including service accounts, in your partner tenant will be required to authenticate using MFA.</span></span>

### <a name="do-the-partner-security-requirements-apply-to-the-integration-sandbox"></a><span data-ttu-id="62fed-121">合作夥伴安全性需求適用于整合沙箱嗎？</span><span class="sxs-lookup"><span data-stu-id="62fed-121">Do the partner security requirements apply to the integration sandbox?</span></span>

<span data-ttu-id="62fed-122">是, 合作夥伴安全性需求適用于整合沙箱。</span><span class="sxs-lookup"><span data-stu-id="62fed-122">Yes, the partner security requirements apply to the integration sandbox.</span></span> <span data-ttu-id="62fed-123">這表示您必須為整合沙箱租使用者中的使用者執行適當的 MFA 解決方案。</span><span class="sxs-lookup"><span data-stu-id="62fed-123">This means you will need to implement the appropriate MFA solution for users in the integration sandbox tenant.</span></span> <span data-ttu-id="62fed-124">建議您執行基準保護原則來提供 MFA。</span><span class="sxs-lookup"><span data-stu-id="62fed-124">It is recommended that you implement the baseline protection policies to provide MFA.</span></span>

### <a name="how-do-i-configure-an-emergency-access-break-glass-account"></a><span data-ttu-id="62fed-125">如何? 設定緊急存取 (中斷玻璃) 帳戶嗎？</span><span class="sxs-lookup"><span data-stu-id="62fed-125">How do I configure an emergency access (break glass) account?</span></span>

<span data-ttu-id="62fed-126">考慮到建立一或兩個緊急存取帳戶的最佳作法, 以避免不小心鎖定 Azure AD 的租使用者。</span><span class="sxs-lookup"><span data-stu-id="62fed-126">It considered best practice to create one or two emergency access accounts to prevent being inadvertently locked out of your Azure AD tenant.</span></span> <span data-ttu-id="62fed-127">關於合作夥伴的安全性需求, 每個使用者都必須使用 MFA 進行驗證。</span><span class="sxs-lookup"><span data-stu-id="62fed-127">With respect to the partner security requirements, it is required that each user authenticate using MFA.</span></span> <span data-ttu-id="62fed-128">因此, 這表示您將需要修改緊急存取帳戶的定義。</span><span class="sxs-lookup"><span data-stu-id="62fed-128">So, this means you will need to modify the definition of an emergency access account.</span></span> <span data-ttu-id="62fed-129">這可能是利用協力廠商解決方案進行 MFA 的帳戶。</span><span class="sxs-lookup"><span data-stu-id="62fed-129">It could be an account that is leveraging a third-party solution for MFA.</span></span>

### <a name="how-will-guest-users-be-impacted-by-the-partner-security-requirements"></a><span data-ttu-id="62fed-130">來賓使用者會如何受到合作夥伴安全性需求的影響？</span><span class="sxs-lookup"><span data-stu-id="62fed-130">How will guest users be impacted by the partner security requirements?</span></span>

<span data-ttu-id="62fed-131">當您存取合作夥伴租使用者中的資源時, 來賓使用者將需要使用 MFA 進行驗證。</span><span class="sxs-lookup"><span data-stu-id="62fed-131">Guest users will be required to authenticate using MFA, when accessing resources in your partner tenant.</span></span> <span data-ttu-id="62fed-132">合作夥伴的安全性需求不會對來賓使用者存取自己租使用者中資源的影響。</span><span class="sxs-lookup"><span data-stu-id="62fed-132">The partner security requirements will have no impact on the guest user will accessing resources in their own tenant.</span></span>

### <a name="if-i-am-using-a-third-party-solution-is-active-directory-federation-service-adfs-required"></a><span data-ttu-id="62fed-133">如果我使用協力廠商解決方案, 需要 Active Directory 同盟服務 (ADFS) 嗎？</span><span class="sxs-lookup"><span data-stu-id="62fed-133">If I am using a third-party solution is Active Directory Federation Service (ADFS) required?</span></span> 

<span data-ttu-id="62fed-134">否, 如果您使用協力廠商解決方案, 則不需要有 Active Directory 同盟服務 (ADFS)。</span><span class="sxs-lookup"><span data-stu-id="62fed-134">No, it is not required to have Active Directory Federation Service (ADFS) if you are using a third-party solution.</span></span> <span data-ttu-id="62fed-135">建議您與解決方案的廠商共同決定其解決方案的需求。</span><span class="sxs-lookup"><span data-stu-id="62fed-135">It is recommended that you work with the vendor of the solution determine what the requirements for their solution are.</span></span>

### <a name="is-it-a-requirement-to-enable-the-baseline-protection-policies"></a><span data-ttu-id="62fed-136">是否需要啟用基準保護原則？</span><span class="sxs-lookup"><span data-stu-id="62fed-136">Is it a requirement to enable the baseline protection policies?</span></span>

<span data-ttu-id="62fed-137">否, 您不需要啟用基準保護原則。</span><span class="sxs-lookup"><span data-stu-id="62fed-137">No, it is not required that you enable the baseline protection policies.</span></span> <span data-ttu-id="62fed-138">唯一的需求是您在合作夥伴租使用者中對每個使用者 (包括服務帳戶) 強制執行 MFA。</span><span class="sxs-lookup"><span data-stu-id="62fed-138">The only requirement is that you enforce MFA for each user, including service accounts, in your partner tenant.</span></span>

### <a name="what-verification-options-are-provided-through-the-implementation-of-the-baseline-protection-policies"></a><span data-ttu-id="62fed-139">哪些驗證選項是透過基準保護原則的執行而提供？</span><span class="sxs-lookup"><span data-stu-id="62fed-139">What verification options are provided through the implementation of the baseline protection policies?</span></span> 

<span data-ttu-id="62fed-140">關於可透過執行基準保護原則來取得的 MFA 版本, 唯一可用的驗證選項是驗證器應用程式。</span><span class="sxs-lookup"><span data-stu-id="62fed-140">With respect to the version of MFA that is available through the implementation of the baseline protection polices, the only verification option available is an authenticator app.</span></span> <span data-ttu-id="62fed-141">使用通話和文字訊息訊息會被視為較不安全。</span><span class="sxs-lookup"><span data-stu-id="62fed-141">The use of a phone call and text message message is considered less secure.</span></span> <span data-ttu-id="62fed-142">因此, 這些選項無法透過此版本的 MFA 使用。</span><span class="sxs-lookup"><span data-stu-id="62fed-142">So, these options are not available through this version of MFA.</span></span>

### <a name="will-the-service-account-used-by-azure-ad-connect-be-impacted-by-the-partner-security-requirements"></a><span data-ttu-id="62fed-143">Azure AD Connect 所使用的服務帳戶是否會受到合作夥伴安全性需求的影響？</span><span class="sxs-lookup"><span data-stu-id="62fed-143">Will the service account used by Azure AD Connect be impacted by the partner security requirements?</span></span>

<span data-ttu-id="62fed-144">否, Azure AD Connect 所使用的服務帳戶不會受到合作夥伴安全性需求的影響。</span><span class="sxs-lookup"><span data-stu-id="62fed-144">No, the service account used by Azure AD Connect will not be impacted by the partner security requirements.</span></span> <span data-ttu-id="62fed-145">如果您在強制執行 MFA 時遇到 Azure AD Connect 的問題, 請向 Microsoft 支援服務開啟技術支援要求。</span><span class="sxs-lookup"><span data-stu-id="62fed-145">If you experience an issue with Azure AD Connect as result of enforcing MFA, then open a technical support request with Microsoft support.</span></span>
