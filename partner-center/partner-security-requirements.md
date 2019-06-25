---
title: 合作夥伴的安全性需求 |合作夥伴中心
ms.topic: article
ms.date: 06/25/2019
description: 深入了解的法律顧問及合作夥伴參與雲端解決方案提供者方案的安全性需求。
author: isaiahwilliams
ms.author: iswillia
keywords: Azure Active Directory、 雲端解決方案提供者、 雲端解決方案提供者進行程式設計，CSP、 控制項面板廠商、 CPV、 多重要素驗證、 MFA，保護應用程式模型、 安全的應用程式模型、 安全性
ms.localizationpriority: medium
ms.openlocfilehash: de1452ce14c8343e2e05dcc65a7a6c05259576c5
ms.sourcegitcommit: ca7f000a58575fa9a089693256c095120dde3c5d
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 06/24/2019
ms.locfileid: "67346997"
---
# <a name="partner-security-requirements"></a><span data-ttu-id="6d3f2-104">合作夥伴的安全性需求</span><span class="sxs-lookup"><span data-stu-id="6d3f2-104">Partner Security Requirements</span></span>

<span data-ttu-id="6d3f2-105">**適用於**</span><span class="sxs-lookup"><span data-stu-id="6d3f2-105">**Applies to**</span></span>

- <span data-ttu-id="6d3f2-106">在雲端解決方案提供者程式中的所有夥伴</span><span class="sxs-lookup"><span data-stu-id="6d3f2-106">All partners in the Cloud Solution Provider program</span></span>
  - <span data-ttu-id="6d3f2-107">直接的帳單</span><span class="sxs-lookup"><span data-stu-id="6d3f2-107">Direct bill</span></span>
  - <span data-ttu-id="6d3f2-108">間接提供者</span><span class="sxs-lookup"><span data-stu-id="6d3f2-108">Indirect provider</span></span>
  - <span data-ttu-id="6d3f2-109">間接轉銷商</span><span class="sxs-lookup"><span data-stu-id="6d3f2-109">Indirect reseller</span></span>
- <span data-ttu-id="6d3f2-110">所有的控制面板廠商</span><span class="sxs-lookup"><span data-stu-id="6d3f2-110">All Control Panel Vendors</span></span>
- <span data-ttu-id="6d3f2-111">所有的建議程式</span><span class="sxs-lookup"><span data-stu-id="6d3f2-111">All Advisors</span></span>

<span data-ttu-id="6d3f2-112">安全性和客戶與合作夥伴的隱私權是 microsoft 的最高優先順序。</span><span class="sxs-lookup"><span data-stu-id="6d3f2-112">Security and privacy of customers and partners are top priorities for Microsoft.</span></span> <span data-ttu-id="6d3f2-113">我們持續看到越來越多的更複雜的安全性攻擊，主要是遭入侵的身分識別相關的變更。</span><span class="sxs-lookup"><span data-stu-id="6d3f2-113">We continue to see an increasing number of more sophisticated security attacks, primarily related to compromised identities.</span></span> <span data-ttu-id="6d3f2-114">為預防性的控制項來防堵安全性攻擊整體的防禦策略中扮演關鍵角色，我們將開始強制執行一組必要的安全性需求，以協助保護合作夥伴與客戶。</span><span class="sxs-lookup"><span data-stu-id="6d3f2-114">As preventive controls play a key role in an overall defense strategy to thwart security attacks, we will start enforcing a set of mandatory security requirements to help protect partners and their customers.</span></span>

> [!NOTE]
> <span data-ttu-id="6d3f2-115">我們強烈建議透過主權雲端 (21Vianet，美國政府和德國) 交易的所有交易夥伴採取行動，並立即採用這些新的安全性需求。</span><span class="sxs-lookup"><span data-stu-id="6d3f2-115">We strongly recommend that all partners transacting through a sovereign cloud (21Vianet, US Government, and Germany) act and adopt these new security requirements immediately.</span></span> <span data-ttu-id="6d3f2-116">不過，這些合作夥伴不需要符合年 7 月 1 日生效的新安全性需求。</span><span class="sxs-lookup"><span data-stu-id="6d3f2-116">However, these partners are not required to meet the new security requirements effective July 1st.</span></span> <span data-ttu-id="6d3f2-117">Microsoft 會提供有關在未來的主權雲端的安全性需求強制執行的其他詳細資料。</span><span class="sxs-lookup"><span data-stu-id="6d3f2-117">Microsoft will provide additional details regarding the enforcement of these security requirements for sovereign clouds in the future.</span></span>

## <a name="overview-of-the-requirements"></a><span data-ttu-id="6d3f2-118">需求概觀</span><span class="sxs-lookup"><span data-stu-id="6d3f2-118">Overview of the requirements</span></span>

<span data-ttu-id="6d3f2-119">所有合作夥伴參與雲端解決方案提供者方案、 控制面板廠商和 Advisor 夥伴，都才能針對其合作夥伴租用戶中的每個使用者強制執行 Multi-factor Authentication (MFA)。</span><span class="sxs-lookup"><span data-stu-id="6d3f2-119">All partners who are participating in the Cloud Solution Provider program, Control Panel Vendors, and Advisor partners are required to enforce Multi-Factor Authentication (MFA) for each user in their partner tenant.</span></span> <span data-ttu-id="6d3f2-120">這可以藉由啟用兩個[Azure Active Directory 基準原則](https://docs.microsoft.com/azure/active-directory/conditional-access/concept-baseline-protection)。</span><span class="sxs-lookup"><span data-stu-id="6d3f2-120">This can be done by enabling two [Azure Active Directory baseline policies](https://docs.microsoft.com/azure/active-directory/conditional-access/concept-baseline-protection).</span></span> <span data-ttu-id="6d3f2-121">基準原則是一組預先定義的原則，協助您保護組織針對許多常見的攻擊。</span><span class="sxs-lookup"><span data-stu-id="6d3f2-121">Baseline policies are a set of predefined policies that help protect organizations against many common attacks.</span></span> <span data-ttu-id="6d3f2-122">密碼噴灑、 重新執行和網路釣魚，可以包含這些常見的攻擊。</span><span class="sxs-lookup"><span data-stu-id="6d3f2-122">These common attacks can include password spray, replay, and phishing.</span></span> <span data-ttu-id="6d3f2-123">基準原則可用於所有版本的 Azure Active Directory。</span><span class="sxs-lookup"><span data-stu-id="6d3f2-123">Baseline policies are available in all editions of Azure Active Directory.</span></span> <span data-ttu-id="6d3f2-124">Microsoft 將這些基準保護原則提供給所有人因為過去幾年來的已識別為基礎的攻擊。</span><span class="sxs-lookup"><span data-stu-id="6d3f2-124">Microsoft is making these baseline protection policies available to everyone because identity-based attacks have been on the rise over the last few years.</span></span>

<span data-ttu-id="6d3f2-125">下表描述應該啟用的兩個基準原則。</span><span class="sxs-lookup"><span data-stu-id="6d3f2-125">The two baseline policies that should be enabled are described in the table below.</span></span>

|<span data-ttu-id="6d3f2-126">**原則**</span><span class="sxs-lookup"><span data-stu-id="6d3f2-126">**Policy**</span></span>| |
|-----|-----|
|<span data-ttu-id="6d3f2-127">**適用於系統管理員需要 MFA**</span><span class="sxs-lookup"><span data-stu-id="6d3f2-127">**Require MFA for admins**</span></span>|<span data-ttu-id="6d3f2-128">啟用系統管理員原則需要 MFA，必須在系統管理員角色的使用者註冊使用驗證器應用程式的 MFA。</span><span class="sxs-lookup"><span data-stu-id="6d3f2-128">Enabling the Require MFA for admins policy, will require users in the administrator roles  to register for MFA using the Authenticator App.</span></span> <span data-ttu-id="6d3f2-129">MFA 註冊完成之後，系統管理員必須執行 MFA，每次登入。</span><span class="sxs-lookup"><span data-stu-id="6d3f2-129">Once MFA registration is complete, administrators will need to perform MFA every time they sign-in.</span></span>|
|<span data-ttu-id="6d3f2-130">**終端使用者的保護**</span><span class="sxs-lookup"><span data-stu-id="6d3f2-130">**End user protection**</span></span>|<span data-ttu-id="6d3f2-131">終端使用者保護是風險型 MFA 基準原則所保護的目錄中的所有使用者。</span><span class="sxs-lookup"><span data-stu-id="6d3f2-131">End user protection is a risk-based MFA baseline policy that protects all users in a directory.</span></span> <span data-ttu-id="6d3f2-132">啟用此原則要求所有使用者註冊使用驗證器應用程式的 MFA。</span><span class="sxs-lookup"><span data-stu-id="6d3f2-132">Enabling this policy requires all users to register for MFA using the Authenticator App.</span></span> <span data-ttu-id="6d3f2-133">使用者可以忽略 MFA 註冊提示 14 天之後，他們即將遭到封鎖無法登入，直到在註冊 MFA。</span><span class="sxs-lookup"><span data-stu-id="6d3f2-133">Users can ignore the MFA registration prompt for 14 days, after which they will be blocked from signing in until they register for MFA.</span></span> <span data-ttu-id="6d3f2-134">一旦註冊過 MFA，將 mfa 提示使用者，只在有風險的登入嘗試。</span><span class="sxs-lookup"><span data-stu-id="6d3f2-134">Once registered for MFA, users will be prompted for MFA only during risky sign-in attempts.</span></span> <span data-ttu-id="6d3f2-135">遭盜用的使用者帳戶會遭到封鎖，直到重設其密碼，並有已關閉風險事件。</span><span class="sxs-lookup"><span data-stu-id="6d3f2-135">Compromised user accounts are blocked until their password is reset and risk events have been dismissed.</span></span>|

<span data-ttu-id="6d3f2-136">這些原則啟用時，每位使用者將能夠利用 Azure MFA，完全免費。</span><span class="sxs-lookup"><span data-stu-id="6d3f2-136">When these policies are enabled, each user will be able to utilize Azure MFA at no additional cost.</span></span> <span data-ttu-id="6d3f2-137">如果您使用第三方解決方案，您會需要對每個使用者強制執行 MFA，存取 Microsoft 商業雲端服務時。</span><span class="sxs-lookup"><span data-stu-id="6d3f2-137">If you are using a third-party solution, then you are required to enforce MFA for each user when accessing Microsoft Commercial cloud services.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="6d3f2-138">在合作夥伴目錄中的每個使用者都會強制執行 MFA，因為會有影響的任何自動化或利用使用者認證的整合。</span><span class="sxs-lookup"><span data-stu-id="6d3f2-138">Since MFA will be enforced for every user in the partner directory, there will be an impact to any automation or integration that utilizes user credentials.</span></span> <span data-ttu-id="6d3f2-139">若要解決這種影響您要修改的方式您的自動化或整合會連接到 Microsoft 商業雲端服務。</span><span class="sxs-lookup"><span data-stu-id="6d3f2-139">To address this impact you will need to modify the way your automation or integration connects to Microsoft commercial cloud services.</span></span> <span data-ttu-id="6d3f2-140">如果您要連接到此服務支援權杖型的驗證，則建議您實作[保護的應用程式模型架構](https://docs.microsoft.com/partner-center/develop/enable-secure-app-model)。</span><span class="sxs-lookup"><span data-stu-id="6d3f2-140">If the service you are connecting to supports token based authentication, then it is recommended that you implement the [Secure Application Model framework](https://docs.microsoft.com/partner-center/develop/enable-secure-app-model).</span></span>

## <a name="what-actions-do-i-need-to-take"></a><span data-ttu-id="6d3f2-141">我需要採取哪些動作？</span><span class="sxs-lookup"><span data-stu-id="6d3f2-141">What actions do I need to take?</span></span> 

<span data-ttu-id="6d3f2-142">若要確保受保護的每個夥伴中的使用者，您必須啟用[需要系統管理員的 MFA](https://docs.microsoft.com/azure/active-directory/conditional-access/howto-baseline-protect-administrators)並[終端使用者保護](https://docs.microsoft.com/azure/active-directory/conditional-access/howto-baseline-protect-end-users)基準原則。</span><span class="sxs-lookup"><span data-stu-id="6d3f2-142">To ensure each user in the partner is protected, you are required to enable the [Require MFA for admins](https://docs.microsoft.com/azure/active-directory/conditional-access/howto-baseline-protect-administrators) and [End user protection](https://docs.microsoft.com/azure/active-directory/conditional-access/howto-baseline-protect-end-users) baseline policies.</span></span> <span data-ttu-id="6d3f2-143">再啟用這些原則，請務必了解它們的功用，以及它們如何會影響任何自動化或整合和您的使用者。</span><span class="sxs-lookup"><span data-stu-id="6d3f2-143">Prior to enabling these policies, it is important to understand what they do and how they will impact any automation or integration and your users.</span></span>

### <a name="considerations"></a><span data-ttu-id="6d3f2-144">考量</span><span class="sxs-lookup"><span data-stu-id="6d3f2-144">Considerations</span></span>

<span data-ttu-id="6d3f2-145">因為安全性需求會套用至合作夥伴目錄中的所有使用者，數個考量必須對確保順利部署。</span><span class="sxs-lookup"><span data-stu-id="6d3f2-145">Because the security requirements apply to all users in a partner directory, several considerations need to be made to ensure a smooth deployment.</span></span> <span data-ttu-id="6d3f2-146">這些考量包括識別無法或不應該執行 MFA，以及應用程式與您組織所使用的用戶端不支援新式驗證的 Azure Active Directory 中的使用者。</span><span class="sxs-lookup"><span data-stu-id="6d3f2-146">These considerations include identifying users in Azure Active Directory that cannot or should not perform MFA, as well as applications and clients used by your organization that do not support modern authentication.</span></span>

#### <a name="legacy-protocols"></a><span data-ttu-id="6d3f2-147">舊版通訊協定</span><span class="sxs-lookup"><span data-stu-id="6d3f2-147">Legacy protocols</span></span>

<span data-ttu-id="6d3f2-148">郵件用戶端會使用舊版驗證通訊協定 （IMAP、 SMTP、 POP3 等） 提出驗證要求。</span><span class="sxs-lookup"><span data-stu-id="6d3f2-148">Legacy authentication protocols (IMAP, SMTP, POP3, etc.) are used by mail clients to make authentication requests.</span></span> <span data-ttu-id="6d3f2-149">這些通訊協定不支援 MFA。</span><span class="sxs-lookup"><span data-stu-id="6d3f2-149">These protocols do not support MFA.</span></span> <span data-ttu-id="6d3f2-150">大部分看過 microsoft 帳戶入侵的不良執行者執行嘗試略過 MFA 的舊版通訊協定攻擊所造成。</span><span class="sxs-lookup"><span data-stu-id="6d3f2-150">Most of the account compromises seen by Microsoft are caused by bad actors performing attacks against legacy protocols attempting to bypass MFA.</span></span> <span data-ttu-id="6d3f2-151">若要確保登入合作夥伴目錄中的帳戶時，會需要 MFA，和不良執行者不能略過 MFA，這些安全性需求會封鎖舊版通訊協定的所有驗證要求。</span><span class="sxs-lookup"><span data-stu-id="6d3f2-151">To ensure that MFA is required when logging into an account in a partner directory and bad actors are not able to bypass MFA, these security requirements will block all authentication requests from legacy protocols.</span></span>

### <a name="enabling-the-baseline-policies"></a><span data-ttu-id="6d3f2-152">啟用基準原則</span><span class="sxs-lookup"><span data-stu-id="6d3f2-152">Enabling the baseline policies</span></span>

<span data-ttu-id="6d3f2-153">請參閱[實作合作夥伴的安全性需求的教學課程](tutorials/partner-security-requirements.yml)有關的基準原則實作的引導式體驗。</span><span class="sxs-lookup"><span data-stu-id="6d3f2-153">See the [Implementing the partner security requirements tutorial](tutorials/partner-security-requirements.yml) for a guided experience regarding the implementation of the baseline policies.</span></span>  

#### <a name="require-mfa-for-admins"></a><span data-ttu-id="6d3f2-154">適用於系統管理員需要 MFA</span><span class="sxs-lookup"><span data-stu-id="6d3f2-154">Require MFA for admins</span></span>

<span data-ttu-id="6d3f2-155">*需要系統管理員的 MFA*基準原則要求使用 MFA 進行以下的目錄角色，被視為最特殊權限的 Azure Active Directory 角色：</span><span class="sxs-lookup"><span data-stu-id="6d3f2-155">The *Require MFA for admin* baseline policy requires MFA for the following directory roles, considered to be the most privileged Azure Active Directory roles:</span></span>

- <span data-ttu-id="6d3f2-156">全域管理員</span><span class="sxs-lookup"><span data-stu-id="6d3f2-156">Global administrator</span></span>
- <span data-ttu-id="6d3f2-157">SharePoint 系統管理員</span><span class="sxs-lookup"><span data-stu-id="6d3f2-157">SharePoint administrator</span></span>
- <span data-ttu-id="6d3f2-158">Exchange 系統管理員</span><span class="sxs-lookup"><span data-stu-id="6d3f2-158">Exchange administrator</span></span>
- <span data-ttu-id="6d3f2-159">條件式存取系統管理員</span><span class="sxs-lookup"><span data-stu-id="6d3f2-159">Conditional access administrator</span></span>
- <span data-ttu-id="6d3f2-160">安全性系統管理員</span><span class="sxs-lookup"><span data-stu-id="6d3f2-160">Security administrator</span></span>
- <span data-ttu-id="6d3f2-161">技術支援中心管理員 / 密碼管理員</span><span class="sxs-lookup"><span data-stu-id="6d3f2-161">Helpdesk administrator / Password administrator</span></span>
- <span data-ttu-id="6d3f2-162">計費管理員</span><span class="sxs-lookup"><span data-stu-id="6d3f2-162">Billing administrator</span></span>
- <span data-ttu-id="6d3f2-163">使用者管理員</span><span class="sxs-lookup"><span data-stu-id="6d3f2-163">User administrator</span></span>

<span data-ttu-id="6d3f2-164">在啟用系統管理員原則需要 MFA，上述的九個的系統管理員角色必須註冊 MFA 使用驗證器應用程式。</span><span class="sxs-lookup"><span data-stu-id="6d3f2-164">Upon enabling the Require MFA for admins policy, the above nine administrator roles will be required to register for MFA using the Authenticator App.</span></span> <span data-ttu-id="6d3f2-165">MFA 註冊完成之後，系統管理員必須執行 MFA 每次登入。</span><span class="sxs-lookup"><span data-stu-id="6d3f2-165">Once MFA registration is complete, administrators will need to perform MFA every single time they sign-in.</span></span>

<span data-ttu-id="6d3f2-166">如果貴組織擁有這些帳戶在指令碼或程式碼中使用，請考慮更換它們 [受管理身分識別](https://docs.microsoft.com/azure/active-directory/managed-identities-azure-resources/overview)。</span><span class="sxs-lookup"><span data-stu-id="6d3f2-166">If your organization has these accounts in use in scripts or code, consider replacing them with [managed identities](https://docs.microsoft.com/azure/active-directory/managed-identities-azure-resources/overview).</span></span>

<span data-ttu-id="6d3f2-167">若要啟用此原則，並保護您的系統管理員：</span><span class="sxs-lookup"><span data-stu-id="6d3f2-167">To enable this policy and protect your administrators:</span></span>

1. <span data-ttu-id="6d3f2-168">登入 **Azure 入口網站** 為全域管理員、 安全性系統管理員或條件式存取 」 系統管理員。</span><span class="sxs-lookup"><span data-stu-id="6d3f2-168">Sign in to the **Azure portal** as a Global Administrator, Security Administrator, or Conditional Access Administrator.</span></span>
2. <span data-ttu-id="6d3f2-169">瀏覽至**Azure Active Directory** > **條件式存取**。</span><span class="sxs-lookup"><span data-stu-id="6d3f2-169">Browse to **Azure Active Directory** > **Conditional Access**.</span></span>
3. <span data-ttu-id="6d3f2-170">在原則清單中，選取 **基準原則：適用於系統管理員要求 MFA**。</span><span class="sxs-lookup"><span data-stu-id="6d3f2-170">In the list of policies, select **Baseline policy: Require MFA for admins**.</span></span>
4. <span data-ttu-id="6d3f2-171">設定**啟用原則**要**立即使用原則**。</span><span class="sxs-lookup"><span data-stu-id="6d3f2-171">Set **Enable policy** to **Use policy immediately**.</span></span>
5. <span data-ttu-id="6d3f2-172">按一下  **儲存**。</span><span class="sxs-lookup"><span data-stu-id="6d3f2-172">Click **Save**.</span></span>

    ![適用於系統管理員需要 MFA](images/security/baseline-policy-require-mfa-for-admins.png)

> [!WARNING]
> <span data-ttu-id="6d3f2-174">啟用此原則之前，請確定您的使用者沒有使用舊版驗證通訊協定。</span><span class="sxs-lookup"><span data-stu-id="6d3f2-174">Before you enable this policy, make sure your users are not using legacy authentication protocols.</span></span> <span data-ttu-id="6d3f2-175">請參閱文章[How to:區塊使用條件式存取的 Azure Active directory 的舊版驗證](https://docs.microsoft.com/azure/active-directory/conditional-access/howto-baseline-protect-legacy-auth#identify-legacy-authentication-use)如需詳細資訊。</span><span class="sxs-lookup"><span data-stu-id="6d3f2-175">See the article [How to: Block legacy authentication to Azure Active Directory with Conditional Access](https://docs.microsoft.com/azure/active-directory/conditional-access/howto-baseline-protect-legacy-auth#identify-legacy-authentication-use) for more information.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="6d3f2-176">沒有已知的問題，會影響您連線到 Exchange Online 的 PowerShell，使用委派的系統管理權限的能力。</span><span class="sxs-lookup"><span data-stu-id="6d3f2-176">There is a known issue, that impacts your ability to connect to Exchange Online PowerShell using delegated administrative privileges.</span></span> <span data-ttu-id="6d3f2-177">請參閱[Exchange Online PowerShell](#exchange-online-powershell)已知問題，然後才啟用此原則，如果您使用此 PowerShell 模組。</span><span class="sxs-lookup"><span data-stu-id="6d3f2-177">See the [Exchange Online PowerShell](#exchange-online-powershell) known issue prior to enabling this policy if you using this PowerShell module.</span></span>

#### <a name="end-user-protection"></a><span data-ttu-id="6d3f2-178">終端使用者的保護</span><span class="sxs-lookup"><span data-stu-id="6d3f2-178">End user protection</span></span>

<span data-ttu-id="6d3f2-179">終端使用者保護基準原則保護的目錄中的所有使用者。</span><span class="sxs-lookup"><span data-stu-id="6d3f2-179">The End user protection baseline policy protects all users in a directory.</span></span> <span data-ttu-id="6d3f2-180">啟用此原則需要 14 天內註冊 Azure MFA 的所有使用者。</span><span class="sxs-lookup"><span data-stu-id="6d3f2-180">Enabling this policy requires all users to register for Azure MFA within 14 days.</span></span> <span data-ttu-id="6d3f2-181">註冊之後，將 mfa 提示使用者，只在有風險的登入嘗試。</span><span class="sxs-lookup"><span data-stu-id="6d3f2-181">Once registered, users will be prompted for MFA only during risky sign-in attempts.</span></span> <span data-ttu-id="6d3f2-182">遭盜用的使用者帳戶會遭到封鎖，直到重設密碼，以及風險 dismissal。</span><span class="sxs-lookup"><span data-stu-id="6d3f2-182">Compromised user accounts are blocked until password reset and risk dismissal.</span></span>

<span data-ttu-id="6d3f2-183">原則**基準原則：終端使用者保護**隨附預先設定，然後會出現在頂端當您瀏覽至 Azure 入口網站中的 [條件式存取] 刀鋒視窗。</span><span class="sxs-lookup"><span data-stu-id="6d3f2-183">The policy **Baseline policy: End user protection** comes pre-configured and will show up at the top when you navigate to the Conditional Access blade in Azure portal.</span></span>

<span data-ttu-id="6d3f2-184">若要啟用此原則，並保護您的使用者：</span><span class="sxs-lookup"><span data-stu-id="6d3f2-184">To enable this policy and protect your users:</span></span>

1. <span data-ttu-id="6d3f2-185">登入 **Azure 入口網站** 為全域管理員、 安全性系統管理員或條件式存取 」 系統管理員。</span><span class="sxs-lookup"><span data-stu-id="6d3f2-185">Sign in to the **Azure portal** as a Global Administrator, Security Administrator, or Conditional Access Administrator.</span></span>
2. <span data-ttu-id="6d3f2-186">瀏覽至**Azure Active Directory** > **條件式存取**。</span><span class="sxs-lookup"><span data-stu-id="6d3f2-186">Browse to **Azure Active Directory** > **Conditional Access**.</span></span>
3. <span data-ttu-id="6d3f2-187">在原則清單中，選取 **基準原則：終端使用者 protection （預覽）** 。</span><span class="sxs-lookup"><span data-stu-id="6d3f2-187">In the list of policies, select **Baseline policy: End user protection (preview)**.</span></span>
4. <span data-ttu-id="6d3f2-188">設定**啟用原則**要**立即使用原則**。</span><span class="sxs-lookup"><span data-stu-id="6d3f2-188">Set **Enable policy** to **Use policy immediately**.</span></span>
5. <span data-ttu-id="6d3f2-189">按一下  **儲存**。</span><span class="sxs-lookup"><span data-stu-id="6d3f2-189">Click **Save**.</span></span>

    ![終端使用者的保護](images/security/baseline-policy-end-user-protection.png)

> [!WARNING]
> <span data-ttu-id="6d3f2-191">啟用此原則之前，請確定您的使用者沒有使用舊版驗證通訊協定。</span><span class="sxs-lookup"><span data-stu-id="6d3f2-191">Before you enable this policy, make sure your users are not using legacy authentication protocols.</span></span> <span data-ttu-id="6d3f2-192">請參閱文章[How to:區塊使用條件式存取的 Azure Active directory 的舊版驗證](https://docs.microsoft.com/azure/active-directory/conditional-access/howto-baseline-protect-legacy-auth#identify-legacy-authentication-use)如需詳細資訊。</span><span class="sxs-lookup"><span data-stu-id="6d3f2-192">See the article [How to: Block legacy authentication to Azure Active Directory with Conditional Access](https://docs.microsoft.com/azure/active-directory/conditional-access/howto-baseline-protect-legacy-auth#identify-legacy-authentication-use) for more information.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="6d3f2-193">沒有已知的問題，會影響您連線到 Exchange Online 的 PowerShell，使用委派的系統管理權限的能力。</span><span class="sxs-lookup"><span data-stu-id="6d3f2-193">There is a known issues, that impacts your ability to connect to Exchange Online PowerShell using delegated administrative privileges.</span></span> <span data-ttu-id="6d3f2-194">請參閱[Exchange Online PowerShell](#exchange-online-powershell)已知問題，然後才啟用此原則，如果您使用此 PowerShell 模組。</span><span class="sxs-lookup"><span data-stu-id="6d3f2-194">See the [Exchange Online PowerShell](#exchange-online-powershell) known issue prior to enabling this policy if you using this PowerShell module.</span></span>

## <a name="common-issues"></a><span data-ttu-id="6d3f2-195">常見問題</span><span class="sxs-lookup"><span data-stu-id="6d3f2-195">Common issues</span></span>

### <a name="azure-active-directory"></a><span data-ttu-id="6d3f2-196">Azure Active Directory</span><span class="sxs-lookup"><span data-stu-id="6d3f2-196">Azure Active Directory</span></span>

#### <a name="aadsts50076"></a><span data-ttu-id="6d3f2-197">AADSTS50076</span><span class="sxs-lookup"><span data-stu-id="6d3f2-197">AADSTS50076</span></span>

<span data-ttu-id="6d3f2-198">啟用後的基準原則，您可能會發現您的自動化或整合會遇到類似下面的例外狀況</span><span class="sxs-lookup"><span data-stu-id="6d3f2-198">After enabling the baseline policies, you might find that your automation or integration is encountering an exception similar to the following</span></span>

    AADSTS50076: Due to a configuration change made by your administrator, or because you moved to a new location, you must use multi-factor authentication to access 'MyApp'.

<span data-ttu-id="6d3f2-199">這個例外狀況的原因是，您會使用使用者認證來進行驗證，以及 MFA 現在是必要。</span><span class="sxs-lookup"><span data-stu-id="6d3f2-199">The reason for this exception is that you are authenticating using user credentials and MFA is now required.</span></span> <span data-ttu-id="6d3f2-200">若要解決這個例外狀況，您必須使用存取權杖進行驗證。</span><span class="sxs-lookup"><span data-stu-id="6d3f2-200">To address this exception, you will need to utilize an access token for authentication.</span></span> <span data-ttu-id="6d3f2-201">請參閱[保護的應用程式模型指南](http://assetsprod.microsoft.com/secure-application-model-guide.pdf)如需詳細資訊。</span><span class="sxs-lookup"><span data-stu-id="6d3f2-201">See the [Secure Application Model guide](http://assetsprod.microsoft.com/secure-application-model-guide.pdf) for more information.</span></span>

>[!IMPORTANT]
><span data-ttu-id="6d3f2-202">現今大部分的 Api 和 PowerShell 模組支援使用存取權杖進行驗證的能力。</span><span class="sxs-lookup"><span data-stu-id="6d3f2-202">Most modern APIs and PowerShell modules support the ability to utilize an access token for authentication.</span></span> <span data-ttu-id="6d3f2-203">不過，有一些目前不支援這項功能。</span><span class="sxs-lookup"><span data-stu-id="6d3f2-203">However, there are some that currently do not support this functionality.</span></span> <span data-ttu-id="6d3f2-204">如果您需要幫助您判斷如果您正嘗試利用的 API 或 PowerShell 模組支援使用存取權杖進行驗證，則會張貼訊息上[合作夥伴中心指引安全性群組](https://www.microsoftpartnercommunity.com/t5/Partner-Center-Security-Guidance/ct-p/partner-center-security-guidance)社群。</span><span class="sxs-lookup"><span data-stu-id="6d3f2-204">If you need help determining if the API or PowerShell module you are trying to leverage supports the use of an access token for authentication, then post a message on the [Partner Center Security Guidance Group](https://www.microsoftpartnercommunity.com/t5/Partner-Center-Security-Guidance/ct-p/partner-center-security-guidance) community.</span></span>

#### <a name="aadsts700082"></a><span data-ttu-id="6d3f2-205">AADSTS700082</span><span class="sxs-lookup"><span data-stu-id="6d3f2-205">AADSTS700082</span></span>

<span data-ttu-id="6d3f2-206">一旦您實作安全的應用程式模型架構沒有機會，您會收到下列例外狀況在產生初始的重新整理語彙基元之後的 90 天</span><span class="sxs-lookup"><span data-stu-id="6d3f2-206">Once you have implemented the Secure Application Model framework there is a chance you will receive the following exception 90 days after generating the initial refresh token</span></span>

    The refresh token has expired due to inactivity. The token was issued on 2019-01-02T09:19:53.5422744Z and was inactive for 90.00:00:00

<span data-ttu-id="6d3f2-207">對於 Azure Active Directory 重新整理的最大存留期語彙基元是 90 天。</span><span class="sxs-lookup"><span data-stu-id="6d3f2-207">With respect to Azure Active Directory the maximum lifetime for a refresh token is 90 days.</span></span> <span data-ttu-id="6d3f2-208">若要解決這個錯誤，您必須產生，並安全地儲存新的重新整理權杖。</span><span class="sxs-lookup"><span data-stu-id="6d3f2-208">To address this error, you will need to generate and securely store a new refresh token.</span></span> <span data-ttu-id="6d3f2-209">請注意，就能夠以程式設計方式更新重新整理權杖，因為與 Azure Active directory 存取權杖的每個要求會傳回新的重新整理權杖。</span><span class="sxs-lookup"><span data-stu-id="6d3f2-209">Note it is possible to update the refresh token programmatically because with each request to Azure Active Directory for an access token a new refresh token is returned.</span></span> <span data-ttu-id="6d3f2-210">您可以實作適當的邏輯在到期之前更新安全地儲存重新整理權杖。</span><span class="sxs-lookup"><span data-stu-id="6d3f2-210">You can implement the appropriate logic to update the securely stored refresh token before it expires.</span></span>

<span data-ttu-id="6d3f2-211">請參閱[Azure Active Directory 中的設定權杖存留期](https://docs.microsoft.com/azure/active-directory/develop/active-directory-configurable-token-lifetimes)如需詳細資訊。</span><span class="sxs-lookup"><span data-stu-id="6d3f2-211">See [Configurable token lifetimes in Azure Active Directory](https://docs.microsoft.com/azure/active-directory/develop/active-directory-configurable-token-lifetimes) for more information.</span></span>

## <a name="known-issues"></a><span data-ttu-id="6d3f2-212">已知問題</span><span class="sxs-lookup"><span data-stu-id="6d3f2-212">Known issues</span></span>

### <a name="exchange-online-powershell"></a><span data-ttu-id="6d3f2-213">Exchange Online PowerShell</span><span class="sxs-lookup"><span data-stu-id="6d3f2-213">Exchange Online PowerShell</span></span>

<span data-ttu-id="6d3f2-214">啟用 MFA 後合作夥伴將無法利用其委派的系統管理權限使用 Exchange Online PowerShell 來執行對客戶進行的動作。</span><span class="sxs-lookup"><span data-stu-id="6d3f2-214">When MFA is enabled partners will not be able to utilize their delegated administrative privileges with Exchange Online PowerShell to perform actions against their customers.</span></span> <span data-ttu-id="6d3f2-215">請參閱[連線到 Exchange Online 的 PowerShell，使用 multi-factor authentication](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/mfa-connect-to-exchange-online-powershell)如有關這項限制的詳細資訊。</span><span class="sxs-lookup"><span data-stu-id="6d3f2-215">See [Connect to Exchange Online PowerShell using multi-factor authentication](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/mfa-connect-to-exchange-online-powershell) for more information regarding this limitation.</span></span>

## <a name="resources-and-support"></a><span data-ttu-id="6d3f2-216">資源與支援</span><span class="sxs-lookup"><span data-stu-id="6d3f2-216">Resources and support</span></span>

<span data-ttu-id="6d3f2-217">透過[合作夥伴中心的安全性指引群組社群](https://www.microsoftpartnercommunity.com/t5/Partner-Center-Security-Guidance/ct-p/partner-center-security-guidance)您可以將找到的其他資源，並了解即將來臨的事件，例如技術上班。</span><span class="sxs-lookup"><span data-stu-id="6d3f2-217">Through the [Partner Center Security Guidance Group community](https://www.microsoftpartnercommunity.com/t5/Partner-Center-Security-Guidance/ct-p/partner-center-security-guidance) you can will find additional resources and learn about upcoming events such as technical office hours.</span></span> <span data-ttu-id="6d3f2-218">請參閱[常見問題集](http://assetsprod.microsoft.com/security-requirements-faq.pdf)文件，深入了解需求。</span><span class="sxs-lookup"><span data-stu-id="6d3f2-218">See the [frequently asked questions](http://assetsprod.microsoft.com/security-requirements-faq.pdf) document to learn more about the requirements.</span></span>

### <a name="developers"></a><span data-ttu-id="6d3f2-219">開發人員</span><span class="sxs-lookup"><span data-stu-id="6d3f2-219">Developers</span></span>

- [<span data-ttu-id="6d3f2-220">啟用安全的應用程式模型</span><span class="sxs-lookup"><span data-stu-id="6d3f2-220">Enabling the Secure Application Model</span></span>](https://docs.microsoft.com/partner-center/develop/enable-secure-app-model)
- [<span data-ttu-id="6d3f2-221">合作夥伴中心.NET 範例</span><span class="sxs-lookup"><span data-stu-id="6d3f2-221">Partner Center .NET Samples</span></span>](https://github.com/microsoft/partner-center-dotnet-samples)
- [<span data-ttu-id="6d3f2-222">合作夥伴中心 Java 範例</span><span class="sxs-lookup"><span data-stu-id="6d3f2-222">Partner Center Java Samples</span></span>](https://github.com/microsoft/partner-center-java-samples)
- [<span data-ttu-id="6d3f2-223">合作夥伴中心 PowerShell 實作安全的應用程式模型</span><span class="sxs-lookup"><span data-stu-id="6d3f2-223">Partner Center PowerShell implementing the Secure Application Model</span></span>](https://docs.microsoft.com/powershell/partnercenter/secure-app-model)
