---
title: 合作夥伴安全性需求 |合作夥伴中心
ms.topic: article
ms.date: 08/05/2019
description: 瞭解參與雲端解決方案提供者計畫之顧問和合作夥伴的安全性需求。
author: isaiahwilliams
ms.author: iswillia
keywords: Azure Active Directory, 雲端解決方案提供者, 雲端解決方案提供者方案, CSP, 控制台廠商, CPV, 多重要素驗證, MFA, 安全應用程式模型, 安全應用程式模型, 安全性
ms.localizationpriority: medium
ms.openlocfilehash: 39081f42c326665bdc30bf25df302d9ae00d9723
ms.sourcegitcommit: fe21430f96e203d279714623888224662d2782a2
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 08/05/2019
ms.locfileid: "68787250"
---
# <a name="partner-security-requirements"></a>合作夥伴安全性需求

**適用於**

- 雲端解決方案提供者方案中的所有合作夥伴
  - 直接帳單
  - 間接提供者
  - 間接轉銷商
- 所有控制台廠商
- 所有顧問

較高的隱私權保護和安全性是我們最優先的考慮。 我們知道最佳防禦功能是預防性的, 而且我們只會與最弱的連結一樣強大。 這就是為什麼我們需要生態系統中的每個人都採取行動, 並確保其具備適當的安全性保護。 為協助保護合作夥伴和客戶, 我們針對參與雲端解決方案提供者計畫的顧問、控制台廠商和合作夥伴, 引進了一組強制性的安全性需求。

自2019年8月1日起, 所有合作夥伴都必須針對其合作夥伴租使用者中的所有使用者 (包括服務帳戶) 強制執行多重要素驗證。

> [!NOTE]
> 我們強烈建議所有合作夥伴透過主權雲端 (世紀、美國政府和德國) 進行交易, 並立即採取這些新的安全性需求。 不過, 這些合作夥伴不需要符合2019年8月1日生效的新安全性需求。 Microsoft 將會針對未來主權雲端的這些安全性需求, 提供額外的詳細資料。

與合作夥伴安全性需求相關聯的條款已新增至[雲端解決方案提供者計劃指南](https://go.microsoft.com/fwlink/p/?LinkId=617100)。 自2019年8月1日起, 參與雲端解決方案提供者計畫的所有合作夥伴都必須遵守條款。 與顧問相關的是, 相同的合約需求也已就緒。

未實行強制安全性需求的合作夥伴將無法在雲端解決方案提供者計畫中進行交易, 或在強制執行這些需求之後, 利用委派系統管理員許可權來管理客戶租使用者。 我們正在建立需求的技術強制性日期, 並會以詳細語音總機合作夥伴的日期。

## <a name="what-actions-do-i-need-to-take"></a>我需要採取哪些動作？

基於成為合作夥伴的高度特殊許可權性質, 我們必須確保每個使用者都有每個單一驗證的 MFA 挑戰。 您可以透過下列其中一種方式來完成這項作業

- 執行 Azure AD Premium 並確保每個使用者都強制執行 MFA
- 執行[基準保護原則](https://docs.microsoft.com/azure/active-directory/conditional-access/concept-baseline-protection)
- 執行協力廠商解決方案, 並確保對每個使用者強制執行 MFA

> [!IMPORTANT]
> 在技術上強制執行這些需求之後, 每個單一驗證都必須有 MFA 挑戰。 存取 Microsoft 商業雲端服務時, 您將無法使用條件式存取的任何功能來避免使用 MFA 進行驗證。

### <a name="considerations"></a>考量

因為這些需求適用于您的夥伴租使用者中的所有使用者, 包括服務帳戶, 所以需要進行幾項考慮以確保部署順利。 這些考慮包括識別 Azure AD 中無法執行 MFA 的使用者, 以及不支援新式驗證的組織所使用的應用程式和裝置。

在執行任何動作之前, 建議您先找出下列各項

#### <a name="do-you-have-an-application-or-device-that-does-not-support-the-use-of-mfa-when-authenticating"></a>您的應用程式或裝置是否在驗證時不支援使用 MFA？

當您強制執行 MFA 舊版驗證時, 將會封鎖使用 IMAP、POP3、SMTP 等通訊協定, 因為這些通訊協定不支援 MFA。 若要解決這項限制, 可使用稱為「[應用程式密碼](https://docs.microsoft.com/azure/active-directory/authentication/howto-mfa-mfasettings#app-passwords)」的功能, 以確保應用程式或裝置仍然可以進行驗證。 您應該參閱使用[這裡](https://docs.microsoft.com/azure/active-directory/authentication/howto-mfa-mfasettings#considerations-about-app-passwords)記載的應用程式密碼的考慮, 以判斷它們是否可以在您的環境中使用。

#### <a name="do-you-have-users-using-office-365-provided-by-licenses-associated-with-your-partner-tenant"></a>您是否有使用者使用與合作夥伴租使用者相關聯的授權所提供的 Office 365？

在執行任何解決方案之前, 建議您先判斷合作夥伴租使用者中的使用者使用的 Microsoft Office 版本為何。 在採取任何動作之前, 請先參閱[Office 365 部署的多重要素驗證規劃](https://docs.microsoft.com/office365/admin/security-and-compliance/multi-factor-authentication-plan#enable-mfa)。 您的使用者可能會遇到 Outlook 之類應用程式的連線問題。 強制執行 MFA 之前, 請務必確定正在使用 Outlook 2013 SP1 或更新版本, 且您的組織已啟用新式驗證。 如需詳細資訊, 請參閱[在 Exchange Online 中啟用新式驗證](https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/enable-or-disable-modern-authentication-in-exchange-online)。

若要為執行 Windows 且已安裝 Microsoft Office 2013 的任何裝置啟用新式驗證, 您將需要建立兩個登錄機碼。 請參閱[在 Windows 裝置上啟用 Office 2013 的新式驗證](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication)。

> [!IMPORTANT]
> 如果您已為使用者啟用 Azure AD MFA, 而且有任何執行 Office 2013 的裝置未啟用新式驗證, 他們就必須在這些裝置上使用應用程式密碼。 如需有關應用程式密碼的詳細資訊, 以及其使用時機和時機, 請參閱:[使用 Azure 多重要素驗證的應用程式密碼](https://go.microsoft.com/fwlink/p/?LinkId=528178)。

#### <a name="is-there-a-policy-preventing-any-of-your-users-from-using-their-mobile-devices-while-working"></a>是否有原則防止任何使用者在工作時使用其行動裝置？

請務必找出任何公司原則, 以防止員工在工作時使用行動裝置, 因為它會影響您所執行的 MFA 解決方案。 有 MFA 解決方案, 例如透過執行[基準保護原則](https://docs.microsoft.com/azure/active-directory/conditional-access/concept-baseline-protection)所提供的解決方案, 只允許使用驗證器應用程式進行驗證。 如果您的組織有防止使用行動裝置的原則, 則您應該考慮下列其中一個選項

- 部署可安裝驗證器應用程式的虛擬化 Android 裝置
- 執行協力廠商解決方案, 以針對合作夥伴租使用者中提供最適當驗證選項的每位使用者強制執行 MFA
- 為受影響的使用者購買[Azure AD Premium](https://azure.microsoft.com/pricing/details/active-directory/)授權

#### <a name="what-automation-or-integration-do-you-have-that-leverages-user-credentials-for-authentication"></a>您有哪些自動化或整合可以利用使用者認證進行驗證？

由於需求是對每個使用者強制執行 MFA, 包括服務帳戶, 因此, 任何利用使用者認證進行驗證的自動化或整合都會受到影響。 因此, 請務必識別在這些情況下所使用的帳戶。 以下是應該考慮的應用程式或服務範例清單

- 用來代表您的客戶布建資源的控制台
- 與用於發票的任何平臺整合 (與 CSP 計畫相關) 並支援您的客戶
- 使用 Az、AzureRM、Azure AD、MS Online 等模組的 PowerShell 腳本

上述清單並不完整。 因此, 請務必在您的環境中執行任何應用程式或服務的完整評估, 利用使用者認證來進行驗證。 若要對抗 MFA 的需求, 您應該盡可能在[安全的應用程式模型架構](https://docs.microsoft.com/partner-center/develop/enable-secure-app-model)中執行指引。 以下是可協助您瞭解如何執行安全應用程式模型架構的其他資源

- [合作夥伴中心 .Net 範例](https://github.com/microsoft/partner-center-dotnet-samples)-此 GitHub 存放庫包含使用 .net 開發的範例, 可示範如何執行安全的應用程式模型架構。
- [合作夥伴中心 JAVA 範例](https://github.com/microsoft/partner-center-java-samples)-此 GitHub 存放庫包含使用 JAVA 開發的範例, 可示範如何執行安全的應用程式模型架構。
- [合作夥伴中心 PowerShell-安全應用程式模型](https://docs.microsoft.com/powershell/partnercenter/secure-app-model)-這篇文章提供如何使用 PowerShell 來執行安全應用程式模型架構的詳細資料。
- [合作夥伴中心安全性指引群組社區](https://www.microsoftpartnercommunity.com/t5/Partner-Center-Security-Guidance/ct-p/partner-center-security-guidance)-這是線上社區, 您可以在其中瞭解近期活動, 並詢問您可能會遇到的任何問題。

### <a name="enforcing-mfa-for-all-users"></a>為所有使用者強制執行 MFA

本節將涵蓋如何使用[基準保護原則](https://docs.microsoft.com/azure/active-directory/conditional-access/concept-baseline-protection), 為您的夥伴租使用者中的每個使用者 (包括服務帳戶) 強制執行 MFA。 如果您打算使用 Azure AD Premium, 請遵循[這裡](https://docs.microsoft.com/azure/active-directory/authentication/howto-mfa-getstarted)記載的步驟。

> [!NOTE]
> 協力廠商解決方案與 Azure AD 相容, 可以用來針對所有使用者 (包括服務帳戶) 強制執行 MFA。 如需如何實作為解決方案的詳細資訊, 請參閱廠商提供的檔。

基準保護原則是一組預先定義的原則, 可協助組織抵禦許多常見的攻擊。 這些常見的攻擊可能包括密碼噴灑、重新執行和網路釣魚。 基準保護原則適用于所有版本的 Azure Active Directory。 Microsoft 致力於讓所有人都能使用這些基準保護原則, 以進一步讓客戶和合作夥伴執行最佳的安全性作法。

下表說明應啟用的兩個基準保護原則。

|**原則**| |
|-----|-----|
|**需要系統管理員的 MFA**|啟用 [需要 MFA for admins] 原則時, 系統管理員角色中的使用者將需要使用驗證器應用程式註冊 MFA。 一旦完成 MFA 註冊, 系統管理員就必須在每次登入時執行 MFA。|
|**終端使用者保護**|終端使用者保護是以風險為基礎的 MFA 基準保護原則, 可保護目錄中的所有使用者。 若要啟用此原則, 所有使用者都必須使用驗證器應用程式註冊 MFA。 使用者可以略過14天的 MFA 登錄提示, 在這之後, 他們將會遭到封鎖而無法登入, 直到他們註冊 MFA 為止。 註冊 MFA 之後, 只有在有風險的登入嘗試時, 才會提示使用者進行 MFA。 遭盜用的使用者帳戶會遭到封鎖, 直到重設其密碼且已關閉風險事件為止。|

啟用這些原則時, 每個使用者都可以使用驗證器應用程式來利用 Azure MFA 來進行驗證, 而不需要額外付費。

#### <a name="configure-self-service-password-reset"></a>設定自助式密碼重設

自助式密碼重設 (SSPR) 是一項 Azure Active Directory 功能, 可讓使用者重設其密碼, 而不需要洽詢其支援小組。 使用者必須註冊或註冊自助式密碼重設, 才能使用服務。 在註冊期間, 使用者會選擇其組織所啟用的一或多個驗證方法。

啟用 [[使用者保護](https://docs.microsoft.com/azure/active-directory/conditional-access/howto-baseline-protect-end-users)] 基準保護原則時, 任何遭盜用的使用者帳戶將會遭到封鎖, 直到重設其密碼且已關閉風險事件為止。 考慮到這一點, 建議每位使用者 (身為全域系統管理員) 執行下列動作來註冊 SSPR, 讓他們不會遭到鎖定。

1. 流覽至 [ [SSPR 設定] 頁面](https://aka.ms/ssprsetup)
2. 輸入您的使用者名稱和密碼
3. 設定至少一個驗證選項, 以在重設密碼時用來確認您的身分。  

當帳戶遭到入侵時, 系統管理員必須採取行動, 以還原受影響之使用者的存取權。 如需解除封鎖使用者程式的詳細資訊, 請參閱[解除封鎖使用者的步驟](#recovering-compromised-accounts)。

#### <a name="require-mfa-for-admins"></a>需要系統管理員的 MFA

系統管理員基準原則的 [*需要 mfa* ] 需要下列目錄角色的 mfa, 視為最具許可權的 Azure Active Directory 角色:

- 全域管理員
- SharePoint 管理員
- Exchange 系統管理員
- 條件式存取管理員
- 安全性系統管理員
- 服務台管理員/密碼管理員
- 計費管理員
- 使用者系統管理員

啟用 [需要 MFA for admins] 原則時, 必須使用驗證器應用程式註冊 MFA, 以上九個系統管理員角色才會需要。 MFA 註冊完成後, 系統管理員每次登入時都必須執行 MFA。

如果您的組織在腳本或程式碼中使用這些帳戶, 請考慮將它們取代為 [受控](https://docs.microsoft.com/azure/active-directory/managed-identities-azure-resources/overview)識別。

若要啟用此原則並保護您的系統管理員:

1. 以全域管理員、安全性系統管理員或條件式存取系統管理員的身分登入 **Azure 入口網站** 。
2. 流覽至**Azure Active Directory**  > **條件式存取**。
3. 在原則清單中, 選取 **[基準原則]:需要系統管理員**的 MFA。
4. 將 [**啟用原則**] 設定為**立即使用原則**。
5. 按一下 [ **儲存**]。

> [!WARNING]
> 啟用此原則之前, 請確定您的使用者未使用舊版驗證通訊協定。 透過此原則的執行, 將會封鎖舊版驗證。

> [!IMPORTANT]
> 有一個已知的問題, 它會影響您使用委派系統管理許可權連接到 Exchange Online PowerShell 的能力。 如果您使用此 PowerShell 模組, 請在啟用此原則之前, 先參閱[Exchange Online PowerShell](#exchange-online-powershell)已知問題。

#### <a name="end-user-protection"></a>終端使用者保護

使用者保護基準原則會保護目錄中的所有使用者。 若要啟用此原則, 所有使用者都必須在14天內註冊 Azure MFA。 註冊之後, 只有在有風險的登入嘗試時, 才會提示使用者進行 MFA。 遭盜用的使用者帳戶會遭到封鎖, 直到重設密碼和風險關閉為止。

原則**基準原則:使用者保護**已預先設定, 當您流覽至 Azure 入口網站中的 [條件式存取] 分頁時, 將會顯示在頂端。

若要啟用此原則並保護您的使用者:

1. 以全域管理員、安全性系統管理員或條件式存取系統管理員的身分登入 **Azure 入口網站** 。
2. 流覽至**Azure Active Directory**  > **條件式存取**。
3. 在原則清單中, 選取 **[基準原則]:終端使用者保護 (預覽)** 。
4. 將 [**啟用原則**] 設定為**立即使用原則**。
5. 按一下 [ **儲存**]。

> [!WARNING]
> 啟用此原則之前, 請確定您的使用者未使用舊版驗證通訊協定。 透過此原則的執行, 將會封鎖舊版驗證。

> [!IMPORTANT]
> 有一個已知問題, 會影響您使用委派系統管理許可權連接到 Exchange Online PowerShell 的能力。 如果您使用此 PowerShell 模組, 請在啟用此原則之前, 先參閱[Exchange Online PowerShell](#exchange-online-powershell)已知問題。

## <a name="common-issues"></a>常見問題

### <a name="azure-active-directory"></a>Azure Active Directory

#### <a name="aadsts50076"></a>AADSTS50076

啟用基準原則之後, 您可能會發現您的自動化或整合遇到如下的例外狀況

    AADSTS50076: Due to a configuration change made by your administrator, or because you moved to a new location, you must use multi-factor authentication to access 'MyApp'.

此例外狀況的原因是您要使用使用者認證進行驗證, 而且現在需要 MFA。 若要解決這個例外狀況, 您必須利用存取權杖來進行驗證。 如需詳細資訊, 請參閱[安全應用程式模型指南](http://assetsprod.microsoft.com/secure-application-model-guide.pdf)。

>[!IMPORTANT]
>大部分的新式 Api 和 PowerShell 模組都支援使用存取權杖進行驗證的能力。 不過, 有一些目前不支援這種功能。 如果您需要協助來判斷您嘗試利用的 API 或 PowerShell 模組是否支援使用存取權杖進行驗證, 請在[合作夥伴中心安全性指引群組](https://www.microsoftpartnercommunity.com/t5/Partner-Center-Security-Guidance/ct-p/partner-center-security-guidance)社區上張貼一則訊息。

#### <a name="aadsts700082"></a>AADSTS700082

一旦您已執行安全的應用程式模型架構, 在產生初始重新整理權杖之後, 您可能會收到下列例外狀況90天

    The refresh token has expired due to inactivity. The token was issued on 2019-01-02T09:19:53.5422744Z and was inactive for 90.00:00:00

關於 Azure Active Directory 重新整理權杖的最長存留期為90天。 若要解決此錯誤, 您將需要產生並安全地儲存新的重新整理權杖。 請注意, 您可以透過程式設計的方式更新重新整理權杖, 因為每個要求都會傳回新的重新整理權杖, 以針對存取權杖 Azure Active Directory。 您可以先執行適當的邏輯, 以更新安全儲存的重新整理權杖, 然後才到期。

如需詳細資訊, 請參閱[Azure Active Directory 中可](https://docs.microsoft.com/azure/active-directory/develop/active-directory-configurable-token-lifetimes)設定的權杖存留期。

### <a name="recovering-compromised-accounts"></a>復原遭盜用的帳戶

為了協助保護客戶, Microsoft 流失的認證服務會尋找公開可用的使用者名稱/密碼組。 如果它們符合我們的其中一個使用者, 我們會立即協助保護該帳戶。 識別為有流失認證的使用者已確認遭到入侵。 這些使用者在重設密碼之前, 將會遭到封鎖而無法登入。

指派 Azure AD Premium 授權的使用者可以在其目錄中啟用功能的情況下, 透過自助式密碼重設 (SSPR) 來還原存取權。 沒有 premium 授權的使用者會遭到封鎖, 必須洽詢系統管理員以執行手動密碼重設, 並關閉已加上旗標的使用者風險事件。

#### <a name="steps-to-unblock-a-user"></a>解除封鎖使用者的步驟

檢查使用者的登入記錄, 確認使用者已遭到原則封鎖。

1. 系統管理員必須登入**Azure 入口網站**並流覽至 [ **Azure Active Directory**  > **使用者**] > 按一下使用者的名稱, 然後流覽至 [登入]。
2. 若要起始已封鎖使用者的密碼重設, 系統管理員必須流覽  > 至**標示有風險的 Azure Active Directory 使用者**
3. 按一下已封鎖帳戶的使用者, 以查看使用者最近登入活動的相關資訊。
4. 按一下 [重設密碼], 指派必須在下次登入時變更的暫時密碼。
5. 按一下 [關閉所有事件] 以重設使用者的風險分數。

使用者現在可以登入、重設其密碼, 並存取應用程式。

## <a name="known-issues"></a>已知問題

### <a name="exchange-online-powershell"></a>Exchange Online PowerShell

強制執行 MFA 時, 合作夥伴將無法利用其委派的系統管理許可權與 Exchange Online PowerShell 來對客戶執行動作。 如需此限制的詳細資訊, 請參閱[使用多重要素驗證連接到 Exchange Online PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/mfa-connect-to-exchange-online-powershell) 。

若要解決這項限制, 您可以建立新的帳戶, 而不要使用它來執行互動式驗證。 建議您利用[Azure AD PowerShell](https://docs.microsoft.com/powershell/module/azuread/)來建立新帳戶, 並執行初始設定。 下列 PowerShell 可以用來建立及設定帳戶

```powershell
Import-Module AzureAD
Connect-AzureAD

$PasswordProfile = New-Object -TypeName Microsoft.Open.AzureAD.Model.PasswordProfile

$PasswordProfile.Password = "Password"
$PasswordProfile.ForceChangePasswordNextLogin = $false

$user = New-AzureADUser -DisplayName "New User" -PasswordProfile $PasswordProfile -UserPrincipalName "NewUser@contoso.com" -AccountEnabled $true

# Uncomment the following two lines if you want the account to have Admin Agent privileges
# $adminAgentsGroup = Get-AzureADGroup -Filter "DisplayName eq 'AdminAgents'"
# Add-AzureADGroupMember -ObjectId $adminAgentsGroup.ObjectId -RefObjectId $user.ObjectId
```

下次透過 PowerShell 連線到 Exchange Online 時, 請使用此帳戶, 它會如預期般運作。

> [!IMPORTANT]
> 能夠讓合作夥伴利用其委派的系統管理許可權, 搭配 Exchange Online PowerShell 對客戶執行動作, 而在執行 MFA 時, 將會在未來推出。 在那之前, 您應該先利用這方面的工作。

## <a name="resources-and-support"></a>資源與支援

透過[合作夥伴中心安全性指引群組的社區](https://www.microsoftpartnercommunity.com/t5/Partner-Center-Security-Guidance/ct-p/partner-center-security-guidance), 您可以找到其他資源, 並瞭解近期的活動, 例如技術辦公時間。 若要深入瞭解需求, 請參閱[常見問題](partner-security-requirements-faq.md)檔。
