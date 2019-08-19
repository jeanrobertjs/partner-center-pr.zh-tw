---
title: 合作夥伴安全性需求常見問題 |合作夥伴中心
ms.topic: article
ms.date: 07/18/2019
description: 關於合作夥伴安全性需求的常見問題
author: isaiahwilliams
ms.author: iswillia
keywords: Azure Active Directory, 雲端解決方案提供者, 雲端解決方案提供者方案, CSP, 控制台廠商, CPV, 多重要素驗證, MFA, 安全應用程式模型, 安全應用程式模型, 安全性
ms.localizationpriority: medium
ms.openlocfilehash: 1f2ae0f07888fdabd16b2eb476af7fac975cd71e
ms.sourcegitcommit: bae29ab191c72e15259d99c40c69a9e7c3f2b502
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 08/06/2019
ms.locfileid: "68820596"
---
# <a name="frequently-asked-questions-about-the-partner-security-requirements"></a>關於合作夥伴安全性需求的常見問題

本文包含[合作夥伴安全性需求](partner-security-requirements.md)的一些常見問題。

## <a name="partner-security-requirements"></a>合作夥伴安全性需求

### <a name="what-are-the-new-partner-security-requirements"></a>新的合作夥伴安全性需求為何？

為了保護我們的合作夥伴和您的客戶, 我們要求合作夥伴立即採取下列動作:  

1. **針對合作夥伴租使用者中的所有使用者啟用多重要素驗證 (MFA)** 。 當您登入 Microsoft 商業雲端服務, 或透過合作夥伴中心或 Api 在 CSP 中交易時, 合作夥伴租使用者中的所有使用者都必須使用多重要素驗證 (MFA)。 透過啟用基準保護原則, 所有合作夥伴租使用者的使用者皆可免費使用 MFA。

2. **採用安全的應用程式模型架構**。 所有與 Microsoft API (例如 Azure Resource Manager、Microsoft Graph 和合作夥伴中心 API) 整合的合作夥伴, 都必須採用安全的應用程式模型架構, 以避免在啟用基準原則時中斷其整合。 
 
啟用多重要素驗證 (MFA) 並採用安全的應用程式模型架構, 可協助保護您的基礎結構, 並保護客戶的資料免于潛在的安全性風險, 例如識別遭竊或其他詐騙事件。  

### <a name="which-partners-need-to-meet-the-requirements"></a>哪些合作夥伴必須符合需求？

這些需求適用于下列合作夥伴群組:
- 所有參與雲端解決方案提供者 (CSP) 方案的合作夥伴組織, 都是使用 Microsoft 商業雲端服務交易的
  - 直接帳單合作夥伴
  - 間接提供者
  - 間接經銷商
- 所有控制台廠商
- 所有 Advisor 方案合作夥伴  

所有透過主權雲端 (世紀、美國政府和德國) 交易的合作夥伴, 都不需要符合8月1日生效的新安全性需求。 不過, 我們強烈建議使用主權 cloud 的所有合作夥伴都採取行動, 並立即採用這些新的安全性需求。 Microsoft 將會針對未來主權雲端的這些安全性需求, 提供額外的詳細資料。

### <a name="what-are-the-key-timelines-and-milestones"></a>關鍵時程表和里程碑有哪些？

與這些安全性需求相關聯的詞彙會立即新增至雲端解決方案提供者計劃指南。 您必須履行這些安全性需求, 以符合您參與 CSP 計畫的2019年8月1日生效。 

### <a name="what-will-happen-if-i-do-not-take-any-actions"></a>如果我沒有採取任何動作, 會發生什麼事？

當這些合作夥伴的安全性需求強制執行之後, 無法遵守這些安全性作法和義務的合作夥伴將無法在雲端解決方案提供者計畫中進行交易, 或管理利用委派系統管理員許可權的客戶租使用者。 我們正在建立需求的強制日期, 並將會通知具有詳細資訊之日期的夥伴。

### <a name="why-is-microsoft-enforcing-these-new-requirements"></a>為什麼 Microsoft 會強制執行這些新需求？
客戶和合作夥伴的安全性和隱私權是 Microsoft 的最高優先順序。 我們會持續看到更複雜的安全性攻擊數目, 主要與身分識別入侵事件有關。 由於預防性控制項在整體防禦策略中扮演重要角色來對抗安全性攻擊, 因此我們將開始強制執行一組強制的安全性需求, 以協助保護合作夥伴及其客戶。

### <a name="does-this-apply-to-all-geographies"></a>這適用于所有地理位置嗎？

是, 這適用于所有地理位置。 我們強烈建議所有合作夥伴透過主權雲端 (世紀、美國政府和德國) 進行交易, 並立即採取這些新的安全性需求。 不過, 這些合作夥伴不一定要符合8月1日生效的新安全性需求。 Microsoft 將會針對未來主權雲端的這些安全性需求, 提供額外的詳細資料。

## <a name="required-actions"></a>必要動作

### <a name="what-are-the-key-actions-i-need-to-take-to-meet-the-requirements"></a>我需要採取哪些關鍵動作來符合需求？  
CSP 計畫中的所有合作夥伴 (直接帳單、間接提供者和間接轉銷商)、顧問和控制台廠商都必須符合需求。

1. **為所有使用者強制執行 MFA**

    CSP 計畫、顧問和控制台廠商中的所有合作夥伴都必須針對其夥伴租使用者中的所有使用者強制執行 MFA。 這可以藉由啟用 [[要求系統管理員使用 MFA](https://docs.microsoft.com/azure/active-directory/conditional-access/howto-baseline-protect-administrators)]、[一般[使用者保護] 基準](https://docs.microsoft.com/azure/active-directory/conditional-access/howto-baseline-protect-end-users)及任何未來的基準原則來完成。 基準原則所提供的功能會持續演進, 以確保合作夥伴和客戶可以受到不斷變動的安全性威脅的保護。 因此, 若要深入瞭解, 請務必參閱[基準原則檔](https://docs.microsoft.com/azure/active-directory/conditional-access/concept-baseline-protection)。

    - 請[參閱基準原則:如需有關如何](https://docs.microsoft.com/azure/active-directory/conditional-access/howto-baseline-protect-administrators)啟用 [要求系統管理員的 mfa] 基準原則的詳細資訊, 請要求系統管理員使用 mfa。
    - 請[參閱基準原則:使用者的保護](https://docs.microsoft.com/azure/active-directory/conditional-access/howto-baseline-protect-end-users) , 以取得如何啟用使用者保護基準原則的詳細資訊。
    - 瞭解[基準保護原則](https://docs.microsoft.com/azure/active-directory/conditional-access/concept-baseline-protection)的概念。

    其他考慮:

    - 間接提供者必須與間接轉銷商合作, 以在合作夥伴中心上線 (如果他們尚未這麼做), 並鼓勵其轉銷商符合需求。
    - 使用[Microsoft Authenticator 應用程式](https://docs.microsoft.com/azure/active-directory/user-help/user-help-auth-app-overview)的唯一驗證方法, 可讓合作夥伴租使用者中的所有使用者免費進行 Azure MFA。
    - 如果需要其他方法 (例如 SMS 或電子郵件), 則可透過[Azure Active Directory Premium](https://docs.microsoft.com/azure/active-directory/fundamentals/active-directory-get-started-premium) sku 取得額外的驗證方法。
    - 當存取 Microsoft 商業雲端服務時, 合作夥伴也可以針對每個使用者運用協力廠商 MFA 解決方案。

2. **採用安全的應用程式模型架構**

    所有已使用任何 Api (例如 Azure Resource Manager、Microsoft Graph、合作夥伴中心 API 等) 開發自訂整合的合作夥伴, 或使用 PowerShell 這類工具來執行自訂自動化, 都必須採用[安全應用程式模型](https://docs.microsoft.com/partner-center/develop/enable-secure-app-model)與 Microsoft 雲端服務整合的架構。 如果未這麼做, 可能會導致 MFA 部署中斷。 下列資源提供有關如何採用模型的總覽和指導方針。

    - [安全應用程式模型總覽](https://docs.microsoft.com/partner-center/develop/enable-secure-app-model)
    - [合作夥伴中心:安全應用程式模型指南](http://assetsprod.microsoft.com/secure-application-model-guide.pdf)
    - [CSP 方案中的合作夥伴: 用於啟用安全應用程式模型的 .NET 範例程式碼](http://github.com/microsoft/Partner-Center-DotNet-Samples/tree/master/secure-app-model)
    - [CSP 方案中的合作夥伴:啟用安全應用程式模型的 JAVA 範例程式碼](http://github.com/microsoft/Partner-Center-Java-Samples/tree/master/secure-app-model)
    - [合作夥伴中心驗證檔](https://docs.microsoft.com/partner-center/develop/partner-center-authentication)
    - [合作夥伴中心 PowerShell 多重要素驗證 (MFA) 檔](https://docs.microsoft.com/partner-center/develop/multi-factor-auth)

    如果您使用的是 [控制台], 則必須洽詢廠商有關採用安全應用程式模型架構的情況。

    控制台廠商必須將 [合作夥伴中心] 上[架](https://docs.microsoft.com/partner-center/enroll-as-cpv)為 [控制台] [廠商], 並立即開始實行這項需求。 請參閱合作夥伴中心: [保護應用程式模型](http://assetsprod.microsoft.com/secure-application-model-guide.pdf)架構。 「控制台」廠商必須接受並管理 CSP 合作夥伴的同意, 而不是認證, 並清除所有現有的 CSP 合作夥伴認證。

## <a name="multi-factor-authentication"></a>多重要素驗證

### <a name="what-is-mfa"></a>什麼是 MFA？

多重要素驗證 (MFA) 是一種安全性機制, 不過, 透過一個以上的必要安全性和驗證程式來驗證個人。 其運作方式是要求下列兩個或多個驗證方法:

- 您知道的資訊 (通常是密碼)
- 您擁有的事物 (不易複製的受信任裝置，例如電話)
- 代表您身分的事物 (生物識別技術)

### <a name="what-are-baseline-protection-policies"></a>何謂基準保護原則？ 

[Microsoft 基準保護原則](https://docs.microsoft.com/azure/active-directory/conditional-access/concept-baseline-protection)(目前預覽) 是一組預先定義的原則, 可協助保護組織免于遭受許多常見的攻擊。 這些常見的攻擊可能包括密碼噴灑、重新執行和網路釣魚。 基準原則適用于所有版本的 Azure Active Directory。 Microsoft 將這些基準保護原則提供給所有人, 因為以身分識別為基礎的攻擊已在過去幾年的增加。 這些原則的目標是要確保所有組織都已啟用基準層級的安全性, 而不需要額外成本。

> [!NOTE]
> Microsoft 基準原則和相關功能將繼續發展, 以更有效地保護合作夥伴和客戶免于不斷改變的安全性威脅。 基準原則可能很快就會有一些命名和分類變更。 我們強烈建議您直接造訪 [基準原則] 頁面, 以查看最新的資訊。

### <a name="what-baseline-policies-must-i-enable"></a>我必須啟用哪些基準原則？

如果您打算利用目前的基準保護原則, 為夥伴租使用者中的每個使用者提供 MFA, 則必須啟用 [[要求系統管理員使用 mfa](https://docs.microsoft.com/azure/active-directory/conditional-access/howto-baseline-protect-administrators) ] 和 [[使用者保護](https://docs.microsoft.com/azure/active-directory/conditional-access/howto-baseline-protect-end-users)] 基準原則。 這些基準保護原則將滿足合作夥伴租使用者中每位使用者的 MFA 需求, 僅適用于透過行動裝置使用 Microsoft Authenticator 應用程式的合作夥伴。

[[要求系統管理員的 MFA] 基準原則](https://docs.microsoft.com/azure/active-directory/conditional-access/howto-baseline-protect-administrators)會用於合作夥伴目錄中的管理使用者, 而 [一般[使用者保護](https://docs.microsoft.com/azure/active-directory/conditional-access/howto-baseline-protect-end-users)] 基準原則是用來保護夥伴租使用者中的非系統管理員 (非系統管理員)。 啟用這些原則會要求使用者註冊 MFA。 使用者成功註冊之後, 系統會根據原則的條件, 在登入嘗試期間提示他們進行 MFA。 基準原則所提供的功能會持續演進, 以確保合作夥伴和客戶可以受到不斷變動的安全性威脅的保護。 因此, 若要深入瞭解, 請務必參閱[基準原則檔](https://docs.microsoft.com/azure/active-directory/conditional-access/concept-baseline-protection)。

### <a name="how-do-i-enable-the-require-mfa-for-admins-policy"></a>如何? 啟用 [要求系統管理員使用 MFA] 原則嗎？ 

[需要 MFA for admins] 基準原則可以透過 Azure 管理入口網站啟用。 請[參閱基準原則:如需如何啟用](https://docs.microsoft.com/azure/active-directory/conditional-access/howto-baseline-protect-administrators)此基準原則的詳細資訊, 請要求系統管理員使用 MFA。

### <a name="how-do-i-enable-the-end-user-protection-policy"></a>如何? 啟用使用者保護原則？

使用者保護基準原則可以透過 Azure 管理入口網站啟用。 請[參閱基準原則:使用者的保護](https://docs.microsoft.com/azure/active-directory/conditional-access/howto-baseline-protect-end-users) , 以取得如何啟用此基準原則的詳細資料。

### <a name="will-the-baseline-policies-be-automatically-enabled"></a>基準原則會自動啟用嗎？ 

否, 若要啟用這些原則, 屬於全域系統管理員、安全性系統管理員或條件式存取系統管理員角色成員的使用者, 必須設定原則以立即使用原則。

### <a name="what-is-the-cost-of-enabling-mfa"></a>啟用 MFA 的成本為何？

Microsoft 透過針對系統管理員和一般[使用者保護](https://docs.microsoft.com/azure/active-directory/conditional-access/howto-baseline-protect-end-users)基準保護原則[需要 mfa](https://docs.microsoft.com/azure/active-directory/conditional-access/howto-baseline-protect-administrators)的執行, 免費提供 mfa。 此版本的 MFA 唯一可用的驗證選項是[Microsoft Authenticator 應用程式](https://docs.microsoft.com/azure/active-directory/user-help/user-help-auth-app-overview)。 如果需要撥打電話或 SMS 訊息, 則必須購買[Azure Active Directory Premium](https://docs.microsoft.com/azure/active-directory/fundamentals/active-directory-get-started-premium)授權。 或者, 您也可以利用協力廠商解決方案, 為合作夥伴租使用者中的每位使用者提供 MFA –在此情況下, 您必須負責確保您的 MFA 解決方案已強制執行, 而且您符合規範。

### <a name="if-i-already-have-an-mfa-solution-what-actions-do-i-need-to-take"></a>如果我已經有 MFA 解決方案, 需要採取哪些動作？

透過這些安全性需求, 合作夥伴租使用者中的使用者在存取 Microsoft 商業雲端服務時, 將需要使用 MFA 進行驗證。 協力廠商解決方案可以用來滿足這些需求。 Microsoft 不再提供對獨立識別提供者的驗證測試, 以符合與 Azure Active Directory 的相容性。 如果您想要測試產品的互通性, 請參閱這些[指導方針](https://www.microsoft.com/download/details.aspx?id=56843)。

### <a name="what-verification-method-can-i-use-to-authenticate-mfa"></a>我可以使用何種驗證方法來驗證 MFA？

Microsoft 透過針對系統管理員和一般[使用者保護](https://docs.microsoft.com/azure/active-directory/conditional-access/howto-baseline-protect-end-users)基準保護原則[需要 mfa](https://docs.microsoft.com/azure/active-directory/conditional-access/howto-baseline-protect-administrators)的執行, 免費提供 mfa。 此版本的 MFA 唯一可用的驗證選項是[Microsoft Authenticator 應用程式](https://docs.microsoft.com/azure/active-directory/user-help/user-help-auth-app-overview)。 如果需要撥打電話或 SMS 訊息, 則必須購買[Azure Active Directory Premium](https://docs.microsoft.com/azure/active-directory/fundamentals/active-directory-get-started-premium)授權。 或者, 您也可以利用協力廠商解決方案, 為合作夥伴租使用者中的每位使用者提供 MFA –在此情況下, 您必須負責確保您的 MFA 解決方案已強制執行, 而且您符合規範。

### <a name="i-use-multiple-partner-tenants-to-transact-do-i-need-to-implement-mfa-on-them-all"></a>我使用多個合作夥伴租使用者來進行交易。 我是否需要對它們執行 MFA？

是, 您必須針對與 CSP 程式或 Advisor 程式相關聯的每個 Azure Active Directory 租使用者強制執行 MFA。 如果您打算購買 Azure Active Directory Premium 授權, 則必須為每個 Azure Active Directory 租使用者中的使用者購買授權。

### <a name="does-each-user-in-my-partner-tenant-need-to-have-mfa-enforced"></a>我的合作夥伴租使用者中的每位使用者都必須強制執行 MFA 嗎？ 

[[需要 mfa for admin](https://docs.microsoft.com/azure/active-directory/conditional-access/howto-baseline-protect-administrators)和一般[使用者保護](https://docs.microsoft.com/azure/active-directory/conditional-access/howto-baseline-protect-end-users)] 基準保護原則會針對您的夥伴租使用者中的每個使用者強制執行 mfa。 如果您要利用這些原則來提供 MFA, 並使用[Microsoft Authenticator](https://docs.microsoft.com/azure/active-directory/user-help/user-help-auth-app-overview)應用程式, 則不需要購買任何額外的授權。 否則, 您將需要購買適當的解決方案, 為您的合作夥伴租使用者中的每位使用者提供 MFA。

### <a name="i-am-a-direct-bill-partner-with-microsoft-what-do-i-need-to-do"></a>我是 Microsoft 的直接帳單合作夥伴。 我需要做什麼？

直接帳單雲端解決方案提供者合作夥伴必須針對其合作夥伴租使用者中的每個使用者強制執行 MFA。

### <a name="i-am-an-indirect-reseller-and-only-transact-though-a-distributor-do-i-still-have-to-do-this"></a>我是間接轉銷商, 而且只能透過散發者進行交易。 我仍然需要這麼做嗎？

所有的間接轉銷商都必須針對其夥伴租使用者中的每個使用者強制執行 MFA。 這是間接轉銷商必須執行的動作。

### <a name="i-do-not-use-the-partner-center-api-do-i-still-need-to-implement-mfa"></a>我不使用合作夥伴中心 API。 我是否仍然需要執行 MFA？

是, 此安全性需求適用于所有使用者, 包括合作夥伴系統管理員使用者和夥伴租使用者中的使用者。

### <a name="which-third-party-vendors-provide-mfa-solutions-compatible-with-azure-active-directory"></a>哪些協力廠商廠商提供與 Azure Active Directory 相容的 MFA 解決方案？

在線上有許多 MFA 解決方案的獨立評論, 例如[Gartner](https://www.gartner.com/en/webinars/3881781)。 在檢查 MFA 廠商和解決方案時, 合作夥伴必須確保他們選擇的解決方案與 Azure Active Directory 相容。

Microsoft 不再提供對獨立識別提供者的驗證測試, 以符合與 Azure Active Directory 的相容性。 如果您想要測試產品的互通性, 請參閱這些[指導方針](https://www.microsoft.com/download/details.aspx?id=56843)。

如需詳細資訊, 請參閱[Azure AD 同盟相容性清單](https://docs.microsoft.com/azure/active-directory/hybrid/how-to-connect-fed-compatibility)。

### <a name="how-can-i-test-mfa-in-our-integration-sandbox"></a>如何在我們的整合沙箱中測試 MFA？

您應該為您的整合沙箱租使用者啟用 [[需要 MFA for admin](https://docs.microsoft.com/azure/active-directory/conditional-access/howto-baseline-protect-administrators) ] 和 [[終端使用者保護](https://docs.microsoft.com/azure/active-directory/conditional-access/howto-baseline-protect-end-users)] 基準原則。 透過此原則, 租使用者中的每個使用者都需要使用 MFA 進行驗證。

### <a name="will-enabling-mfa-effect-how-i-interact-with-my-customers-tenant"></a>啟用 MFA 會影響我與客戶租使用者互動的方式嗎？ 

資料分割 履行這些安全性需求並不會影響您管理客戶的方式。 您執行委派系統管理作業的能力不會中斷。

### <a name="are-my-customers-subject-to-the-partner-security-requirements"></a>我的客戶是否遵守合作夥伴的安全性需求？

否, 您不需要對客戶的 Azure AD 租使用者中的每位使用者強制執行 MFA。 不過, 建議您與每個客戶合作, 以判斷保護其使用者的最佳方式。

### <a name="can-app-passwords-be-used-with-the-baseline-protection-policies"></a>應用程式密碼可以搭配基準保護原則使用嗎？

是, 可以使用[應用程式密碼](https://docs.microsoft.com/azure/active-directory/authentication/howto-mfa-mfasettings#app-passwords)。 您應該參閱使用[此處](https://docs.microsoft.com/azure/active-directory/authentication/howto-mfa-mfasettings#considerations-about-app-passwords)記載的應用程式密碼的考慮, 以判斷是否支援您的需求。

### <a name="can-any-user-be-excluded-from-this-requirement"></a>是否可以將任何使用者排除在此需求之外？ 

否, 您的合作夥伴租使用者中包含服務帳戶的每個使用者都需要使用 MFA 進行驗證。

### <a name="do-the-partner-security-requirements-apply-to-the-integration-sandbox"></a>合作夥伴安全性需求適用于整合沙箱嗎？

是, 合作夥伴安全性需求適用于整合沙箱。 這表示您必須為整合沙箱租使用者中的使用者執行適當的 MFA 解決方案。 建議您執行基準保護原則來提供 MFA。

### <a name="how-do-i-configure-an-emergency-access-break-glass-account"></a>如何? 設定緊急存取 (中斷玻璃) 帳戶嗎？

考慮到建立一或兩個緊急存取帳戶的最佳作法, 以避免不小心鎖定 Azure AD 的租使用者。 關於合作夥伴的安全性需求, 每個使用者都必須使用 MFA 進行驗證。 因此, 這表示您將需要修改緊急存取帳戶的定義。 這可能是利用協力廠商解決方案進行 MFA 的帳戶。

### <a name="how-will-guest-users-be-impacted-by-the-partner-security-requirements"></a>來賓使用者會如何受到合作夥伴安全性需求的影響？

當您存取合作夥伴租使用者中的資源時, 來賓使用者將需要使用 MFA 進行驗證。 合作夥伴的安全性需求不會對來賓使用者存取自己租使用者中資源的影響。

### <a name="if-i-am-using-a-third-party-solution-is-active-directory-federation-service-adfs-required"></a>如果我使用協力廠商解決方案, 需要 Active Directory 同盟服務 (ADFS) 嗎？ 

否, 如果您使用協力廠商解決方案, 則不需要有 Active Directory 同盟服務 (ADFS)。 建議您與解決方案的廠商共同決定其解決方案的需求。

### <a name="is-it-a-requirement-to-enable-the-baseline-protection-policies"></a>是否需要啟用基準保護原則？

否, 您不需要啟用基準保護原則。 唯一的需求是您在合作夥伴租使用者中對每個使用者 (包括服務帳戶) 強制執行 MFA。

### <a name="can-conditional-access-be-used-to-meet-the-mfa-requirement"></a>是否可以使用條件式存取來符合 MFA 需求？

是, 您可以使用條件式存取, 為您的夥伴租使用者中的每個使用者 (包括服務帳戶) 強制執行 MFA。 不過, 由於身為合作夥伴的高度特殊許可權, 我們必須確保每個使用者都有每個單一驗證的 MFA 挑戰。 這表示您將無法利用避開 MFA 需求的條件式存取功能。

### <a name="what-verification-options-are-provided-through-the-implementation-of-the-baseline-protection-policies"></a>哪些驗證選項是透過基準保護原則的執行而提供？ 

關於可透過執行基準保護原則來取得的 MFA 版本, 唯一可用的驗證選項是驗證器應用程式。 使用通話和文字訊息訊息會被視為較不安全。 因此, 這些選項無法透過此版本的 MFA 使用。

### <a name="will-the-service-account-used-by-azure-ad-connect-be-impacted-by-the-partner-security-requirements"></a>Azure AD Connect 所使用的服務帳戶是否會受到合作夥伴安全性需求的影響？

否, Azure AD Connect 所使用的服務帳戶不會受到合作夥伴安全性需求的影響。 如果您在強制執行 MFA 時遇到 Azure AD Connect 的問題, 請向 Microsoft 支援服務開啟技術支援要求。

## <a name="secure-application-model"></a>保護應用程式模型

### <a name="who-should-adopt-the-secure-application-model-to-meet-the-requirements"></a>誰應該採用安全的應用程式模型來符合需求？

Microsoft 引進了一個安全、可擴充的架構, 用於驗證雲端解決方案提供者 (CSP) 合作夥伴, 以及利用多重要素驗證的控制台廠商 (CPV)。 如需詳細資訊, 請參閱[安全應用程式模型指南](http://assetsprod.microsoft.com/secure-application-model-guide.pdf)。 所有已使用任何 Api (例如 Azure Resource Manager、Microsoft Graph、合作夥伴中心 API 等) 開發自訂整合的合作夥伴, 或使用 PowerShell 這類工具來執行自訂自動化, 都必須採用[安全應用程式模型](https://docs.microsoft.com/partner-center/develop/enable-secure-app-model)與 Microsoft 雲端服務整合的架構。

### <a name="what-is-the-secure-application-model"></a>什麼是安全的應用程式模型？

Microsoft 引進了一個安全、可擴充的架構, 用於驗證雲端解決方案提供者 (CSP) 合作夥伴, 以及利用多重要素驗證的控制台廠商 (CPV)。 如需詳細資訊, 請參閱[安全應用程式模型指南](http://assetsprod.microsoft.com/secure-application-model-guide.pdf)。  

### <a name="how-do-i-implement-the-secure-application-model"></a>如何? 實施安全的應用程式模型嗎？

所有已使用任何 Api (例如 Azure Resource Manager、Microsoft Graph、合作夥伴中心 API 等) 開發自訂整合的合作夥伴, 或使用 PowerShell 這類工具來執行自訂自動化, 都必須採用[安全應用程式模型](https://docs.microsoft.com/partner-center/develop/enable-secure-app-model)與 Microsoft 雲端服務整合的架構。 如果未這麼做, 可能會導致 MFA 部署中斷。 下列資源提供有關如何採用模型的總覽和指導方針。

- [安全應用程式模型總覽](https://docs.microsoft.com/partner-center/develop/enable-secure-app-model)
- [合作夥伴中心:安全應用程式模型指南](http://assetsprod.microsoft.com/secure-application-model-guide.pdf)
- [CSP 方案中的合作夥伴: 用於啟用安全應用程式模型的 .NET 範例程式碼](http://github.com/microsoft/Partner-Center-DotNet-Samples/tree/master/secure-app-model)
- [CSP 方案中的合作夥伴:啟用安全應用程式模型的 JAVA 範例程式碼](http://github.com/microsoft/Partner-Center-Java-Samples/tree/master/secure-app-model)
- [合作夥伴中心驗證檔](https://docs.microsoft.com/partner-center/develop/partner-center-authentication)
- [合作夥伴中心 PowerShell 多重要素驗證 (MFA) 檔](https://docs.microsoft.com/partner-center/develop/multi-factor-auth)

如果您使用的是 [控制台], 則必須洽詢廠商有關採用安全應用程式模型架構的情況。

控制台廠商必須將 [合作夥伴中心] 上[架](https://docs.microsoft.com/partner-center/enroll-as-cpv)為 [控制台] [廠商], 並立即開始實行這項需求。 請參閱合作夥伴中心: [保護應用程式模型](http://assetsprod.microsoft.com/secure-application-model-guide.pdf)架構。 「控制台」廠商必須接受並管理 CSP 合作夥伴的同意, 而不是認證, 並清除所有現有的 CSP 合作夥伴認證。

### <a name="who-is-a-control-panel-vendor-cpv"></a>誰是控制台廠商 (CPV)？ 
「控制台廠商」是一個獨立軟體廠商, 可開發應用程式供 CSP 合作夥伴用來與合作夥伴中心 Api 整合。 「控制台」廠商不是可直接存取合作夥伴中心儀表板或 Api 的 CSP 合作夥伴。 詳細描述可在[合作夥伴中心內取得:安全應用程式模型](http://assetsprod.microsoft.com/secure-application-model-guide.pdf)指南。

### <a name="does-the-secure-application-model-need-to-be-implemented-for-the-partner-center-apisdk-only"></a>安全的應用程式模型只需要針對合作夥伴中心 API/SDK 執行嗎？ 

一旦啟用 [*要求系統管理員 MFA*和一般*使用者保護*] 基準原則, 每個使用者都必須使用多重要素驗證進行驗證。 這表示您必須針對要以非互動方式執行的每個 API、CLI 和 PowerShell 模組 (例如 Azure、Azure AD、MS Online、合作夥伴中心等等) 來執行安全的應用程式模型, 並使用使用者認證進行驗證。

### <a name="i-am-using-automation-tools-such-as-powershell-how-do-i-implement-the-secure-application-model"></a>我使用的是自動化工具, 例如 PowerShell。 如何? 實施安全的應用程式模型嗎？  

如果您的自動化目的是要以非互動方式執行, 而且依賴使用者認證來進行驗證, 則您必須執行安全應用程式模型。 請參閱[保護應用程式模型 |合作夥伴中心 PowerShell](https://docs.microsoft.com/powershell/partnercenter/secure-app-model?view=partnercenterps-1.5) , 以取得如何執行此架構的指引。  請注意, 並非所有自動化工具都提供使用存取權杖進行驗證的能力。 如果您需要協助瞭解需要進行哪些變更, 請在[合作夥伴中心安全性指引](https://www.microsoftpartnercommunity.com/t5/Partner-Center-Security-Guidance/ct-p/partner-center-security-guidance)群組上張貼一則訊息。

### <a name="what-user-credentials-should-the-application-administrator-provide-when-performing-the-consent-process"></a>應用程式系統管理員在執行同意流程時, 應該提供哪些使用者認證？ 

建議您使用已獲指派最低許可權許可權的服務帳戶。 就合作夥伴中心 API 而言, 這表示您應該使用已獲指派「銷售代理程式」或「管理員代理人」角色的帳戶。

### <a name="why-should-the-application-administrator-not-provide-global-admin-user-credentials-when-performing-the-consent-process"></a>為什麼應用程式系統管理員在執行同意流程時, 不會提供全域系統管理員使用者認證？

最佳做法是使用最低許可權識別讓您降低風險的方式。 不建議使用具有全域系統管理員許可權的帳戶, 因為這會提供比所需更多的許可權

### <a name="i-am-a-csp-partner-how-do-i-know-if-my-control-panel-vendor-cpv-is-working-on-implementing-the-solution-or-not"></a>我是 CSP 合作夥伴。 如何? 知道我的控制台廠商 (CPV) 是否正在執行解決方案？ 

針對使用「控制台廠商」 (CPV) 解決方案在雲端解決方案提供者 (CSP) 計畫中進行交易的合作夥伴, 您必須負責洽詢 CPV。 

### <a name="i-am-a-cpv-how-do-i-enroll"></a>我是 CPV。 如何? 註冊嗎？ 

若要註冊為「控制台」廠商 (CPV), 請遵循[這裡](https://docs.microsoft.com/partner-center/enroll-as-cpv)提供的指導方針。

若要接收註冊連結, CPVs 必須聯絡[CPVHelp@microsoft.com](mailto:CPVHelp@microsoft.com)並提供與 CPV 具有商務關係的 Microsoft 員工贊助商, 或瞭解他們的業務。 例如, 合作夥伴開發經理 (PDM)。

在合作夥伴中心註冊並註冊您的應用程式後, 您就可以存取合作夥伴中心 Api。 如果您是新的 CPV, 您會透過合作夥伴中心通知收到您的沙箱資訊。 當您以 Microsoft CPV 完成註冊並接受 CPV 合約之後, 就可以:

1. 管理多租使用者應用程式 (在合作夥伴中心新增應用程式以 Azure 入口網站、註冊及取消註冊應用程式)。 注意:CPVs 必須在合作夥伴中心註冊其應用程式, 才能獲得合作夥伴中心 Api 的授權。 將應用程式單獨新增至 Azure 入口網站並不會授權合作夥伴中心 Api 的 CPV 應用程式。
2. 查看及管理您的 CPV 設定檔。
3. 查看和管理需要存取 CPV 功能的使用者。 CPV 可以擁有的唯一角色是全域管理員。

### <a name="i-am-using-the-partner-center-sdk-will-sdk-automatically-adopt-the-secure-application-model"></a>我正在使用合作夥伴中心 SDK。 SDK 會自動採用安全的應用程式模型嗎？ 

否, 您必須遵循[安全應用程式模型指南](http://assetsprod.microsoft.com/secure-application-model-guide.pdf)中提供的指導方針。

### <a name="can-i-generate-a-refresh-token-for-the-secure-application-model-with-accounts-that-do-not-have-mfa-enabled"></a>我可以使用未啟用 MFA 的帳戶來產生安全應用程式模型的重新整理權杖嗎？

是, 您可以使用未強制執行 MFA 的帳戶來產生重新整理權杖。 不過, 這不應該這麼做, 因為使用未啟用 MFA 的帳戶所產生的任何權杖, 將無法因為 MFA 的需求而存取資源。

### <a name="how-should-my-application-obtain-an-access-token-if-we-enable-mfa"></a>如果我們啟用 MFA, 應用程式應該如何取得存取權杖？

您必須遵循[安全的應用程式模型指南](http://assetsprod.microsoft.com/secure-application-model-guide.pdf), 其中提供如何執行此操作的詳細資料, 同時遵守新的安全性需求。 您可以在[這裡](http://github.com/microsoft/Partner-Center-DotNet-Samples/tree/master/secure-app-model)找到 .NET 範例程式碼，在[這裡](http://github.com/microsoft/Partner-Center-Java-Samples/tree/master/secure-app-model)找到 JAVA 範例程式碼。

### <a name="as-a-cpv-do-i-create-an-azure-ad-application-in-our-cpv-tenant-or-the-tenant-of-the-csp-partner"></a>身為 CPV, 我要在 CPV 租使用者或 CSP 合作夥伴的租使用者中建立 Azure AD 應用程式嗎？

CPV 將需要在與其註冊相關聯的租使用者中建立 Azure Active Directory 應用程式, 以做為 CPV。

### <a name="i-am-a-csp-that-is-using-app-only-authentication-do-i-need-to-make-any-changes"></a>我是使用僅限應用程式驗證的 CSP。 我是否需要進行任何變更？

應用程式驗證不會受到影響, 因為使用者認證不會用來要求存取權杖。 如果共用使用者認證, 則「控制台廠商」 (CPVs) 必須採用安全的[應用程式模型架構](http://assetsprod.microsoft.com/secure-application-model-guide.pdf), 並清除任何現有的夥伴認證。

### <a name="as-a-cpv-can-i-leverage-the-app-only-authentication-style-to-get-access-tokens"></a>身為 CPV, 我可以利用僅限應用程式的驗證樣式來取得存取權杖嗎？

否, 「控制台廠商」合作夥伴無法使用「僅限應用程式」驗證樣式來代表合作夥伴要求存取權杖。 它們應該會執行安全的應用程式模型, 這會利用應用程式 + 使用者驗證樣式。

## <a name="key-resources"></a>重要資源

### <a name="how-to-get-started"></a>如何開始使用

- [合作夥伴安全性需求: 逐步指南](https://docs.microsoft.com/partner-center/partner-security-requirements)。
- 將您的問題和意見反應導向此[合作夥伴中心安全性指引群組](https://aka.ms/MPCSecurityGuidance)。
- 參加即將推出的合作夥伴辦公室時數和網路研討會。 請在[這裡查看詳細的排程和資源](https://www.microsoftpartnercommunity.com/t5/Partner-Center-Security-Guidance/ct-p/partner-center-security-guidance)。

### <a name="resources-for-enabling-mfa"></a>啟用 MFA 的資源

- 瞭解[基準保護原則](https://docs.microsoft.com/azure/active-directory/conditional-access/concept-baseline-protection)的概念。
- 請[參閱基準原則:如需有關如何](https://docs.microsoft.com/azure/active-directory/conditional-access/howto-baseline-protect-administrators)啟用 [要求系統管理員的 mfa] 基準原則的詳細資訊, 請要求系統管理員使用 mfa。
- 請[參閱基準原則:使用者的保護](https://docs.microsoft.com/azure/active-directory/conditional-access/howto-baseline-protect-end-users) , 以取得如何啟用使用者保護基準原則的詳細資訊。

### <a name="resources-for-adopting-secure-application-model"></a>採用安全應用程式模型的資源

- [安全應用程式模型總覽](https://docs.microsoft.com/partner-center/develop/enable-secure-app-model)
- [合作夥伴中心:安全應用程式模型指南](http://assetsprod.microsoft.com/secure-application-model-guide.pdf)
- [CSP 方案中的合作夥伴: 用於啟用安全應用程式模型的 .NET 範例程式碼](http://github.com/microsoft/Partner-Center-DotNet-Samples/tree/master/secure-app-model)
- [CSP 方案中的合作夥伴:啟用安全應用程式模型的 JAVA 範例程式碼](http://github.com/microsoft/Partner-Center-Java-Samples/tree/master/secure-app-model)
- [合作夥伴中心驗證檔](https://docs.microsoft.com/partner-center/develop/partner-center-authentication)
- [合作夥伴中心 PowerShell 多重要素驗證 (MFA) 檔](https://docs.microsoft.com/partner-center/develop/multi-factor-auth)

## <a name="support"></a>支援

### <a name="where-can-i-ask-get-support"></a>我可以在何處要求取得支援？

此外, 若要支援利用資源來符合安全性需求, 如果您有合作夥伴的先進支援 (ASfP), 請聯絡您的服務帳戶管理員;如需頂級支援合作夥伴合約 (PSfP), 請洽詢您的服務帳戶管理員和技術客戶經理。

### <a name="how-can-i-get-help-with-enabling-the-baseline-policies"></a>如何取得啟用基準原則的協助？

- 合作夥伴可以利用 MPN 權益的諮詢時數, 取得如何執行安全性需求的更詳細指引。
- Azure Active Directory 的技術產品支援選項可透過您的 MPN 權益取得。 具有使用中 ASfP 或 PSfP 合約存取權的合作夥伴, 可以與相關聯的帳戶管理員 (SAM/TAM) 合作, 以充分瞭解其可用的選項。
- 您可以透過[合作夥伴中心服務要求](https://partner.microsoft.com/dashboard/support/csp/servicerequests/create?category=csp), 存取合作夥伴中心的基準原則實施支援。 選取 [ *MFA & 安全應用程式模型*] 作為主題。

### <a name="how-do-i-get-technical-information-to-adopt-secure-application-model-framework"></a>如何? 取得技術資訊以採用安全的應用程式模型架構嗎？ 

Azure Active Directory 的技術產品支援選項可透過您的 MPN 權益取得。 具有使用中 ASfP 或 PSfP 訂用帳戶存取權的合作夥伴, 可以與相關聯的客戶管理員 (SAM/TAM) 合作, 以充分瞭解其可用的選項。

### <a name="where-can-i-find-more-information-about-technical-common-issues"></a>哪裡可以找到有關技術常見問題的詳細資訊？ 

您可以在[這裡](https://docs.microsoft.com/partner-center/partner-security-requirements#common-issues)找到有關技術常見問題的資訊。
