---
title: 合作夥伴安全性需求 | 合作夥伴中心
ms.topic: article
ms.date: 09/25/2019
description: 瞭解參與雲端解決方案提供者計畫之顧問和合作夥伴的安全性需求。
author: isaiahwilliams
ms.author: iswillia
keywords: Azure Active Directory, 雲端解決方案提供者, 雲端解決方案提供者計畫, CSP, 控制台廠商, CPV, 多重要素驗證, MFA, 安全應用程式模型, 安全應用程式模型, 安全性
ms.localizationpriority: high
ms.openlocfilehash: ea155cf760850def85146d8c4e7e847fab5d7213
ms.sourcegitcommit: 0195355f4526362f4d89f59ea643a5e422b6a9b2
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 09/27/2019
ms.locfileid: "71318482"
---
# <a name="partner-security-requirements"></a>合作夥伴安全性需求

**適用於**

- 雲端解決方案提供者計畫中的所有合作夥伴
  - 直接帳單
  - 間接提供者
  - 間接轉銷商
- 所有控制台廠商
- 所有顧問

較高的隱私權保護和安全性是我們最優先的考量。 我們知道最佳的防禦是預防，而且我們只與最弱的連結一樣強大。 這就是為什麼我們需要生態系統中的每個人都採取行動，並確保其具備適當的安全性保護。 為了協助保護合作夥伴和客戶，我們針對參與雲端解決方案提供者計畫的顧問、控制台廠商和合作夥伴推出一組強制性的安全性需求。

自 2019 年 8 月 1 日起，所有合作夥伴都必須針對其合作夥伴租用戶的所有使用者 (包括服務帳戶) 強制執行多重要素驗證。

> [!NOTE]
> 我們強烈建議所有合作夥伴透過主權雲端 (21Vianet、US Government 和 Germany) 進行交易，並立即採取這些新的安全性需求。 不過，這些合作夥伴不需要符合 2019 年 8 月 1 日生效的新安全性需求。 Microsoft 未來將針對主權雲端的這些安全性需求強制執行，提供額外的詳細資料。

與合作夥伴安全性需求相關聯的條款已新增至[雲端解決方案提供者計畫指南](https://go.microsoft.com/fwlink/p/?LinkId=617100)。 自 2019 年 8 月 1 日起，參與雲端解決方案提供者計畫的所有合作夥伴都必須遵守條款。 與顧問相關的是，相同的合約需求也將備妥。

一旦強制執行這些需求，未實作強制安全性需求的合作夥伴，將無法在雲端解決方案提供者計畫中進行交易，或利用委派系統管理員權限來管理客戶租用戶。 我們正處於為需求建立技術強制執行日期的過程，並且將通知合作夥伴相關的日期與詳細資訊。

## <a name="what-actions-do-i-need-to-take"></a>我需要採取什麼動作？

基於成為合作夥伴的高度特殊權限本質，我們必須確保每個使用者的每個單一驗證都有 MFA 挑戰。 您可以透過下列其中一種方式來完成這項作業

- 實作 Azure AD Premium 並確保對每個使用者強制執行 MFA
- 實作[基準保護原則](https://docs.microsoft.com/azure/active-directory/conditional-access/concept-baseline-protection)
- 實作協力廠商解決方案，並確保對每個使用者強制執行 MFA

> [!IMPORTANT]
> 實際上強制執行這些需求之後，每個單一驗證都必須有 MFA 挑戰。 存取 Microsoft 商業雲端服務時，您將無法使用條件式存取的任何功能來避免使用 MFA 進行驗證。

### <a name="considerations"></a>考量

因為這些需求適用於您的合作夥伴租用戶中的所有使用者 (包括服務帳戶)，要確保順利部署，需要進行幾項考量。 這些考量包括識別 Azure AD 中無法執行 MFA 的使用者，以及組織所使用不支援新式驗證的應用程式和裝置。

執行任何動作之前，建議您先找出下列各項

#### <a name="do-you-have-an-application-or-device-that-does-not-support-the-use-of-mfa-when-authenticating"></a>您是否有驗證時不支援使用 MFA 的應用程式或裝置？

當您強制執行 MFA 舊版驗證時，將會封鎖使用 IMAP、POP3、SMTP 等通訊協定，因為這些通訊協定不支援 MFA。 若要解決此限制，稱為[應用程式密碼](https://docs.microsoft.com/azure/active-directory/authentication/howto-mfa-mfasettings#app-passwords)的功能可用來確保應用程式或裝置仍然可以進行驗證。 您應該複查[這裡](https://docs.microsoft.com/azure/active-directory/authentication/howto-mfa-mfasettings#considerations-about-app-passwords)所記載、使用應用程式密碼的考量事項，以判斷是否可以在您的環境中使用它們。

#### <a name="do-you-have-users-using-office-365-provided-by-licenses-associated-with-your-partner-tenant"></a>您是否有使用者使用與合作夥伴租用戶使用者相關聯的授權所提供的 Office 365？

在實作任何解決方案之前，建議您先判斷合作夥伴租用戶中的使用者使用的 Microsoft Office 版本為何。 在採取任何動作之前，先複查[規劃 Office 365 部署的多重要素驗證](https://docs.microsoft.com/office365/admin/security-and-compliance/multi-factor-authentication-plan#enable-mfa)。 您的使用者可能會遇到 Outlook 之類應用程式的連線問題。 強制執行 MFA 之前，請務必確定正在使用 Outlook 2013 SP1 或更新版本，且您的組織已啟用新式驗證。 如需詳細資訊，請參閱[在 Exchange Online 中啟用新式驗證](https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/enable-or-disable-modern-authentication-in-exchange-online)。

若要為執行 Windows 且已安裝 Microsoft Office 2013 的任何裝置啟用新式驗證，您將需要建立兩個登錄機碼。 請參閱[為 Windows 裝置上的 Office 2013 啟用新式驗證](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication)。

> [!IMPORTANT]
> 如果您已為使用者啟用 Azure AD MFA，而且有任何執行 Office 2013 的裝置未啟用新式驗證，他們就必須在這些裝置上使用應用程式密碼。 如需有關應用程式密碼的詳細資訊，以及其使用時機/位置/方式，請參閱：[應用程式密碼搭配 Azure Multi-Factor Authentication](https://go.microsoft.com/fwlink/p/?LinkId=528178)。

#### <a name="is-there-a-policy-preventing-any-of-your-users-from-using-their-mobile-devices-while-working"></a>是否有原則防止任何使用者在工作時使用其行動裝置？

請務必找出會防止員工在工作時使用行動裝置的任何公司原則，因為它會影響您所實作的 MFA 解決方案。 部分 MFA 解決方案，例如透過[基準保護原則](https://docs.microsoft.com/azure/active-directory/conditional-access/concept-baseline-protection)所實作的解決方案，只會允許使用驗證器應用程式進行驗證。 如果您的組織有防止使用行動裝置的原則，則應該考量下列其中一個選項

- 部署可在安全系統上執行的以時間為基礎的一次性基礎密碼 (TOTP) 應用程式
- 實作協力廠商解決方案，在可提供最適當驗證選項的合作夥伴租用戶中，為每個使用者強制執行 MFA
- 為受影響的使用者購買 [Azure AD Premium](https://azure.microsoft.com/pricing/details/active-directory/) 授權

支援使用 FIDO 安全性金鑰在基準保護原則的藍圖上。 新增支援之後，您將可以針對驗證的第二個因素使用 FIDO 安全性金鑰。 在那之前，您將受限於使用驗證器應用程式。

#### <a name="what-automation-or-integration-do-you-have-that-leverages-user-credentials-for-authentication"></a>您有會利用使用者認證進行驗證的哪些自動化或整合？

由於需求是對合作夥伴目錄中的每個使用者 (包括服務帳戶) 強制執行 MFA，因此，利用使用者認證進行驗證的任何自動化或整合都會受到影響。 因此，請務必找出在這些情況下所使用的帳戶。 以下是應該考量的應用程式或服務的範例清單

- 用來代表您的客戶佈建資源的控制台
- 與用於發票 (與雲端解決方案提供者計畫相關) 的任何平台整合並支援您的客戶
- 使用 Az、AzureRM、Azure AD、MS Online 等模組的 PowerShell 指令碼

以上清單並不完整。 因此，在利用使用者認證來進行驗證的環境中，請務必執行任何應用程式或服務的完整評估。 若要與 MFA 的需求抗衡，您應該盡可能在[安全應用程式模型架構](https://docs.microsoft.com/partner-center/develop/enable-secure-app-model)中實作指導方針。 以下是可協助您瞭解如何實作安全應用程式模型架構的其他資源

- [合作夥伴中心 .NET 範例](https://github.com/microsoft/partner-center-dotnet-samples) - 此 GitHub 存放庫包含使用 .NET 開發的範例，將示範如何實作安全應用程式模型架構。
- [合作夥伴中心 Java 範例](https://github.com/microsoft/partner-center-java-samples) - 此 GitHub 存放庫包含使用 Java 開發的範例，將示範如何實作安全應用程式模型架構。
- [合作夥伴中心 PowerShell - 安全應用程式模型](https://docs.microsoft.com/powershell/partnercenter/secure-app-model) - 本文章提供如何使用 PowerShell 來實作安全應用程式模型架構的詳細資料。
- [合作夥伴中心安全性指導群組社群](https://www.microsoftpartnercommunity.com/t5/Partner-Center-Security-Guidance/ct-p/partner-center-security-guidance) - 這是線上社群，您可以在其中瞭解近期活動，並詢問您可能會遇到的任何問題。

### <a name="enforcing-mfa-for-all-users"></a>為所有使用者強制執行 MFA

本節將涵蓋如何使用[基準保護原則](https://docs.microsoft.com/azure/active-directory/conditional-access/concept-baseline-protection)，為您的合作夥伴租用戶中的每個使用者 (包括服務帳戶) 強制執行 MFA。 如果您計畫使用 Azure AD Premium，請遵循[這裡](https://docs.microsoft.com/azure/active-directory/authentication/howto-mfa-getstarted)記載的步驟。

> [!NOTE]
> 您可以使用與 Azure AD 相容的協力廠商解決方案，針對所有使用者 (包括服務帳戶) 強制執行 MFA。 如需應如何實作解決方案的詳細資訊，請參閱廠商提供的文件。

基準保護原則是一組預先定義的原則，可協助組織抵禦許多常見的攻擊。 這些常見的攻擊可能包括密碼噴灑、重播和網路釣魚。 基準保護原則可在所有版本的 Azure Active Directory 中取得。 Microsoft 正讓所有人都能使用這些基準保護原則，以進一步讓客戶和合作夥伴實作最佳的安全性作法。

下表說明應啟用的兩個基準保護原則。

|**原則**| |
|-----|-----|
|**要求系統管理員使用 MFA**|啟用 [要求系統管理員使用 MFA] 原則時，將要求系統管理員角色中的使用者使用 Authenticator 應用程式來註冊使用 MFA。 完成 MFA 註冊後，管理員每次登入時都必須執行 MFA。|
|**使用者保護**|使用者保護是以風險為基礎的 MFA 基準保護原則，可保護目錄中的所有使用者。 啟用此原則會要求所有使用者都必須使用驗證器應用程式註冊 MFA。 使用者可以略過 MFA 註冊提示 14 天，在這之後，他們將會遭到封鎖而無法登入，直到他們註冊 MFA 為止。 註冊 MFA 之後，只有在有風險的登入嘗試時，才會提示使用者進行 MFA。 遭盜用的使用者帳戶會遭到封鎖，直到重設其密碼且風險事件已解除為止。|

啟用這些原則時，每個使用者都可以使用驗證器應用程式來利用 Azure MFA 來進行驗證，而不需要額外付費。

#### <a name="configure-self-service-password-reset"></a>設定自助式密碼重設

自助式密碼重設 (SSPR) 是一項 Azure Active Directory 功能，可讓使用者重設其密碼，而不需連絡其支援小組。 使用者必須註冊或由他人為其註冊取得自助式密碼重設，才能使用服務。 在註冊期間，使用者會選擇其組織所啟用的一或多個驗證方法。

啟用[使用者保護](https://docs.microsoft.com/azure/active-directory/conditional-access/howto-baseline-protect-end-users)基準保護原則時，任何遭盜用的使用者帳戶將會遭到封鎖，直到重設其密碼且風險事件已解除為止。 考慮到這一點，建議由身為全域管理員的每位使用者執行下列動作來註冊 SSPR，使得他們不會遭到鎖定。

1. 瀏覽至 [SSPR 設定頁面](https://aka.ms/ssprsetup)
2. 輸入您的使用者名稱和密碼
3. 設定至少其中一個驗證選項，以在重設密碼時用來確認您的身分。  

當帳戶遭到入侵時，系統管理員必須採取行動，以還原受影響使用者的存取權。 如需解除封鎖使用者的程序詳細資訊，請參閱[解除封鎖使用者的步驟](#recovering-compromised-accounts)。

#### <a name="require-mfa-for-admins"></a>要求系統管理員使用 MFA

[要求管理員使用 MFA]  基準原則需要下列目錄角色的 MFA，它們被視為最具特殊權限的 Azure Active Directory 角色：

- 全域管理員
- SharePoint 管理員
- Exchange 系統管理員
- 條件式存取管理員
- 安全性系統管理員
- 服務台管理員/密碼管理員
- 計費管理員
- 使用者管理員

啟用 [要求系統管理員使用 MFA] 原則時，需要以上九個系統管理員角色，才能使用 Authenticator 應用程式來註冊使用 MFA。 完成 MFA 註冊後，管理員每次登入時都必須執行 MFA。

如果您的組織在指令碼或程式碼中使用這些帳戶，請考慮將它們取代為[受管理的身分識別](https://docs.microsoft.com/azure/active-directory/managed-identities-azure-resources/overview)。

若要啟用此原則並保護您的系統管理員：

1. 以全域管理員、安全性系統管理員或條件式存取系統管理員的身分登入 **Azure 入口網站**。
2. 瀏覽至 [Azure Active Directory]   >  [條件式存取]  。
3. 在原則清單中，選取 [基準原則:  要求系統管理員使用 MFA]。
4. 將 [啟用原則]  設定為 [立即使用原則]  。
5. 按一下 **[儲存]** 。

> [!WARNING]
> 啟用此原則之前，請確定您的使用者未使用舊版驗證通訊協定。 透過實作此原則，將會封鎖舊版驗證。

> [!IMPORTANT]
> 有一個已知的問題，會影響您使用委派系統管理權限連接到 Exchange Online PowerShell 的能力。 如果您使用此 PowerShell模組，在啟用此原則之前，請參閱 [Exchange Online PowerShell](#exchange-online-powershell) 已知問題。

#### <a name="end-user-protection"></a>使用者保護

使用者保護基準原則會保護目錄中的所有使用者。 啟用此原則會要求所有使用者都必須在 14 天內註冊 Azure MFA。 註冊之後，只有在有風險的登入嘗試時，才會提示使用者進行 MFA。 遭盜用的使用者帳戶會遭到封鎖，直到重設密碼和風險解除為止。

原則 [基準原則:  使用者保護] 已預先設定，當您瀏覽至 Azure 入口網站中的 [條件式存取] 刀鋒視窗時，將顯示在頂端。

若要啟用此原則並保護您的使用者：

1. 以全域管理員、安全性系統管理員或條件式存取系統管理員的身分登入 **Azure 入口網站**。
2. 瀏覽至 [Azure Active Directory]   >  [條件式存取]  。
3. 在原則清單中，選取 [基準原則:  終端使用者保護 (預覽)]。
4. 將 [啟用原則]  設定為 [立即使用原則]  。
5. 按一下 **[儲存]** 。

> [!WARNING]
> 啟用此原則之前，請確定您的使用者未使用舊版驗證通訊協定。 透過實作此原則，將會封鎖舊版驗證。

> [!IMPORTANT]
> 有一個已知的問題，會影響您使用委派系統管理權限連接到 Exchange Online PowerShell 的能力。 如果您使用此 PowerShell模組，在啟用此原則之前，請參閱 [Exchange Online PowerShell](#exchange-online-powershell) 已知問題。

## <a name="assessing-your-environment"></a>準備您的環境

透過目前的合作夥伴安全性需求，您必須針對合作夥伴租用戶使用者中的每個使用者強制執行 MFA。 由於這項需求可以透過數種不同的方法來完成，因此難以評估是否需要任何額外的動作。 您可以利用 Azure Active Directory 稽核記錄和 [Microsoft 安全分數](https://docs.microsoft.com/office365/securitycompliance/microsoft-secure-score)之類的工具，評估是否需要採取任何其他動作，才能使用 MFA 保護您的租用戶。 Microsoft 正致力於合作夥伴中心的體驗，以提供有關 MFA 和安全應用程式模型需求的快速合規性檢查。

Microsoft 安全分數提供您強大的視覺效果、與其他 Microsoft 產品整合、將的分數與其他公司的分數比較、依類別篩選，以及其他更多功能。 使用此工具，您可以完成組織內的安全性改進動作，並追蹤分數的歷程記錄。 當協力廠商解決方案已解決建議的改進動作時，分數也可以反映出來。

![Microsoft 安全分數](images/security/secure-score.png)

> [!NOTE]
> 為了改善您的 Microsoft 安全分數您可以採取的動作，最多可能需要24小時的時間才會反映出來。

Microsoft 安全分數只會提供安全性狀態的數值表示法。 若要進一步瞭解未受到 MFA 挑戰進行驗證的內容或對象，建議您查詢 Azure Active Directory 的稽核記錄。 您可以使用 [Azure PowerShell](https://docs.microsoft.com/powershell/azure/overview) 模組和下列指令碼來完成此作業。 它會產生一份報告，讓您瞭解在過去一天發生、未受到 MFA 挑戰的驗證嘗試。

```powershell
Login-AzAccount
$context = Get-AzContext

function Get-SignInEvents
{
    param([string]$userId)

    $content = '{"startDateTime":"' + (Get-Date).AddDays(-1).ToUniversalTime().ToString("yyyy-MM-ddT05:00:00.000Z") + '","endDateTime":"' + (Get-Date).ToUniversalTime().ToString("yyyy-MM-ddTHH:mm:ss.fffZ")  + '","userId":"' + $userId +'","riskState":[],"totalRisk":[],"realtimeRisk":[],"tokenIssuerType":[],"isAdfsEnabled":false}'

    $token = [Microsoft.Azure.Commands.Common.Authentication.AzureSession]::Instance.AuthenticationFactory.Authenticate($context.Account, $context.Environment, $context.Tenant.Id, $null, "Never", $null, "74658136-14ec-4630-ad9b-26e160ff0fc6")

    $headers = @{
    'Authorization' = 'Bearer ' + $token.AccessToken
    'Content-Type' = 'application/json'
        'X-Requested-With'= 'XMLHttpRequest'
        'x-ms-client-request-id'= [guid]::NewGuid()
        'x-ms-correlation-id' = [guid]::NewGuid()
    }

    Invoke-RestMethod -Body $content -Header $headers -Method POST -Uri "https://main.iam.ad.ext.azure.com/api/Reports/SignInEventsV3"
}

$report = $()

Get-AzADUser | foreach {
    $events = Get-SignInEvents $_.Id
    $report += $events.Items
}

$report | Where-Object {$_.mfaRequired -eq $false} | Select-Object userPrincipalName, userDisplayName, createdDateTime, resourceDisplayName, loginSucceeded, failureReason, mfaRequired, mfaAuthMethod, mfaAuthDetail, mfaResult, @{Name='policies'; Expression={[string]::join(',', $($_.conditionalAccessPolicies | Select-Object displayName).displayName )}}, conditionalAccessStatus | Export-Csv report.csv
```

執行上述指令碼之後，report.csv 檔案中會提供詳細資料。 其中將包含過去一天發生、使用者未受到 MFA 挑戰的驗證嘗試清單。 您將需要複查每個項目，以判斷這是否為預期的行為，並視需要採取動作。

![評估報告](images/security/assessment-report.png)

## <a name="common-issues"></a>常見問題

### <a name="azure-active-directory"></a>Azure Active Directory

#### <a name="aadsts50076"></a>AADSTS50076

啟用基準原則之後，您可能會發現您的自動化或整合遇到如下的例外狀況

    AADSTS50076: Due to a configuration change made by your administrator, or because you moved to a new location, you must use multi-factor authentication to access 'MyApp'.

此例外狀況的原因是您要使用使用者認證進行驗證，而且現在需要 MFA。 若要解決這個例外狀況，您必須利用存取權杖來進行驗證。 如需詳細資訊，請參閱[安全應用程式模型指南](http://assetsprod.microsoft.com/secure-application-model-guide.pdf)。

>[!IMPORTANT]
>大部分的新式 API 和 PowerShell 模組都支援使用存取權杖進行驗證的能力。 不過，有一些目前不支援此功能。 如果您需要協助來判斷您嘗試利用的 API 或 PowerShell 模組是否支援使用存取權杖進行驗證，請在[合作夥伴中心安全性指導群組](https://www.microsoftpartnercommunity.com/t5/Partner-Center-Security-Guidance/ct-p/partner-center-security-guidance)社群上張貼訊息。

#### <a name="aadsts700082"></a>AADSTS700082

一旦您實作安全應用程式模型架構，於產生初始重新整理權杖的 90天後，您可能會收到下列例外狀況

    The refresh token has expired due to inactivity. The token was issued on 2019-01-02T09:19:53.5422744Z and was inactive for 90.00:00:00

關於 Azure Active Directory，重新整理權杖的最長存留期為90天。 若要解決此錯誤，您將需要產生並安全地儲存新的重新整理權杖。 請注意，您可以透過程式設計的方式更新重新整理權杖，因為隨著對 Azure Active Directory 要求取得存取權杖的每個要求，都會傳回新的重新整理權杖。 您可以實作適當的邏輯，以在到期之前更新安全儲存的重新整理權杖。

如需詳細資訊，請參閱 [Azure Active Directory 中可設定的權杖存留期](https://docs.microsoft.com/azure/active-directory/develop/active-directory-configurable-token-lifetimes)。

### <a name="recovering-compromised-accounts"></a>復原遭盜用的帳戶

為了協助保護客戶，Microsoft 的外洩認證服務會尋找公開可用的使用者名稱/密碼組。 如果它們符合我們的其中一個使用者，我們會立即協助保護該帳戶。 識別為有外洩認證的使用者會確認遭到入侵。 這些使用者在重設密碼之前，將會遭到封鎖而無法登入。

獲指派 Azure AD Premium 授權的使用者可以於其目錄中啟用該功能的情況下，透過自助式密碼重設 (SSPR) 來還原存取權。 遭到封鎖、沒有 Premium 授權的使用者，必須連絡系統管理員來執行手動密碼重設，並解除已標幟的使用者風險事件。

#### <a name="steps-to-unblock-a-user"></a>解除封鎖使用者的步驟

檢查使用者的登入記錄，確認使用者已遭到原則封鎖。

1. 系統管理員必須登入 **Azure 入口網站**，並瀏覽至 [Azure Active Directory]   >  [使用者]  > 按一下使用者的名稱，然後瀏覽以進行登入。
2. 若要對已封鎖的使用者初始化密碼重設，系統管理員必須瀏覽至 [Azure Active Directory]   >  [標幟為有風險的使用者] 
3. 按一下帳戶已遭封鎖的使用者，以檢視使用者最近登入活動的相關資訊。
4. 按一下 [重設密碼]，指派必須在下次登入時變更的暫時密碼。
5. 按一下 [關閉所有事件] 以重設使用者的風險分數。

使用者現在可以登入、重設其密碼，並存取應用程式。

## <a name="known-issues"></a>已知問題

### <a name="exchange-online-powershell"></a>Exchange Online PowerShell

強制執行 MFA 時，合作夥伴將無法利用其委派的系統管理權限搭配 Exchange Online PowerShell 來對客戶執行動作。 如需有關此限制的詳細資訊，請參閱[使用多重要素驗證連接到 Exchange Online PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/mfa-connect-to-exchange-online-powershell)。

若要解決此限制，您可以建立新的帳戶，並且絕不使用它來執行互動式驗證。 建議您利用 [Azure AD PowerShell](https://docs.microsoft.com/powershell/module/azuread/) 來建立新帳戶並執行初始設定。 下列 PowerShell 可以用來建立及設定帳戶

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

下一次使用此帳戶透過 PowerShell 連線到 Exchange Online 時，它會如預期般運作。

> [!IMPORTANT]
> 在執行 MFA 時，讓合作夥伴可利用其委派的系統管理權限搭配 Exchange Online PowerShell 對客戶執行動作的功能，未來將會推出。 在那之前，您應該先利用此解決方法。

## <a name="resources-and-support"></a>資源與支援

透過[合作夥伴中心安全性指導群組社群](https://www.microsoftpartnercommunity.com/t5/Partner-Center-Security-Guidance/ct-p/partner-center-security-guidance)，您可以找到其他資源，並瞭解近期的活動，例如技術辦公室工作時間。 若要深入瞭解需求，請參閱[常見問題檔](partner-security-requirements-faq.md)。
