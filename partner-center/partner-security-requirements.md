---
title: 合作夥伴的安全性需求 |合作夥伴中心
ms.topic: article
ms.date: 06/25/2019
description: 深入了解的法律顧問及合作夥伴參與雲端解決方案提供者方案的安全性需求。
author: isaiahwilliams
ms.author: iswillia
keywords: Azure Active Directory、 雲端解決方案提供者、 雲端解決方案提供者進行程式設計，CSP、 控制項面板廠商、 CPV、 多重要素驗證、 MFA，保護應用程式模型、 安全的應用程式模型、 安全性
ms.localizationpriority: medium
ms.openlocfilehash: 8f513b96619819cd6ba892625e47731170d22130
ms.sourcegitcommit: de88bb4cd994f1a106a5d02242261042958d4300
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 07/03/2019
ms.locfileid: "67549532"
---
# <a name="partner-security-requirements"></a>合作夥伴的安全性需求

**適用於**

- 在雲端解決方案提供者程式中的所有夥伴
  - 直接的帳單
  - 間接提供者
  - 間接轉銷商
- 所有的控制面板廠商
- 所有的建議程式

安全性和客戶與合作夥伴的隱私權是 microsoft 的最高優先順序。 我們持續看到越來越多的更複雜的安全性攻擊，主要是遭入侵的身分識別相關的變更。 為預防性的控制項來防堵安全性攻擊整體的防禦策略中扮演關鍵角色，我們將開始強制執行一組必要的安全性需求，以協助保護合作夥伴與客戶。

> [!NOTE]
> 我們強烈建議透過主權雲端 (21Vianet，美國政府和德國) 交易的所有交易夥伴採取行動，並立即採用這些新的安全性需求。 不過，這些合作夥伴不需要符合有效的新安全性需求 2019 年 8 月 1 日。 Microsoft 會提供有關在未來的主權雲端的安全性需求強制執行的其他詳細資料。

## <a name="overview-of-the-requirements"></a>需求概觀

所有合作夥伴參與雲端解決方案提供者方案、 控制面板廠商和 Advisor 夥伴，都才能針對每個使用者，包括服務帳戶，其合作夥伴租用戶中強制執行 Multi-factor Authentication (MFA)。 這可以藉由啟用兩個[Azure Active Directory 基準原則](https://docs.microsoft.com/azure/active-directory/conditional-access/concept-baseline-protection)。 基準原則是一組預先定義的原則，協助您保護組織針對許多常見的攻擊。 密碼噴灑、 重新執行和網路釣魚，可以包含這些常見的攻擊。 基準原則可用於所有版本的 Azure Active Directory。 Microsoft 將這些基準保護原則提供給所有人都能進一步讓客戶和合作夥伴來實作-中同級最佳安全性作法。

下表描述應該啟用的兩個基準原則。

|**原則**| |
|-----|-----|
|**適用於系統管理員需要 MFA**|啟用系統管理員原則需要 MFA，必須在系統管理員角色的使用者註冊使用驗證器應用程式的 MFA。 MFA 註冊完成之後，系統管理員必須執行 MFA，每次登入。|
|**終端使用者的保護**|終端使用者保護是風險型 MFA 基準原則所保護的目錄中的所有使用者。 啟用此原則要求所有使用者註冊使用驗證器應用程式的 MFA。 使用者可以忽略 MFA 註冊提示 14 天之後，他們即將遭到封鎖無法登入，直到在註冊 MFA。 一旦註冊過 MFA，將 mfa 提示使用者，只在有風險的登入嘗試。 遭盜用的使用者帳戶會遭到封鎖，直到重設其密碼，並有已關閉風險事件。|

這些原則啟用時，每位使用者將能夠利用 Azure MFA，完全免費。 如果您使用第三方解決方案，您會需要對每個使用者強制執行 MFA，存取 Microsoft 商業雲端服務時。

> [!IMPORTANT]
> 在合作夥伴目錄中的每個使用者都會強制執行 MFA，因為會有影響的任何自動化或利用使用者認證的整合。 若要解決這種影響，您必須修改您的自動化或整合連線到 Microsoft 商業雲端服務的方式。 如果您要連接到此服務支援權杖型的驗證，則建議您實作[保護的應用程式模型架構](https://docs.microsoft.com/partner-center/develop/enable-secure-app-model)。

## <a name="what-actions-do-i-need-to-take"></a>我需要採取哪些動作？ 

若要確保合作夥伴租用戶中的使用者會受到保護，您必須強制執行 MFA，每個使用者 （包括服務帳戶）。 這可藉由啟用[需要系統管理員的 MFA](https://docs.microsoft.com/azure/active-directory/conditional-access/howto-baseline-protect-administrators)並[終端使用者保護](https://docs.microsoft.com/azure/active-directory/conditional-access/howto-baseline-protect-end-users)基準原則。 再啟用這些原則，請務必了解它們的功用，以及它們如何會影響任何自動化或整合和您的使用者。

> [!NOTE]
> [基準原則](https://docs.microsoft.com/azure/active-directory/conditional-access/concept-baseline-protection)會持續改進加班工時。 建議您定期檢閱文件，以深入了解原則的發展。

### <a name="considerations"></a>考量

因為安全性需求會套用至合作夥伴目錄中的所有使用者，數個考量必須對確保順利部署。 這些考量包括識別無法或不應該執行 MFA，以及應用程式與您組織所使用的用戶端不支援新式驗證的 Azure Active Directory 中的使用者。

#### <a name="self-service-password-reset"></a>自助式密碼重設

自助式密碼重設 (SSPR) 是 Azure Active Directory 功能，讓員工能夠重設其密碼，而不需要連絡 IT 人員。 員工必須註冊，或針對自助式密碼重設之前先使用服務註冊。 在註冊期間，員工會選擇啟用其組織的一或多個驗證方法。

SSPR 讓員工能夠快速取得解除封鎖，並繼續運作，無論他們身在何處或一天的時間。 藉由允許使用者自行解除封鎖，非生產時間並提高支援成本，最常見的密碼相關問題，可以減少您的組織。

當[終端使用者保護](https://docs.microsoft.com/azure/active-directory/conditional-access/howto-baseline-protect-end-users)基準原則已啟用任何遭盜用的使用者帳戶會遭到封鎖，直到重設其密碼，並有已關閉風險事件。 有鑑於此，建議您使用每位使用者，身為全域系統管理員，執行下列命令以註冊 sspr

1. 瀏覽至[SSPR [安裝] 頁面](https://aka.ms/ssprsetup)
2. 輸入您的使用者名稱和密碼
3. 設定至少其中一個驗證選項，將用來確認重設您的密碼時，您的身分。  

帳戶已遭入侵系統管理員必須採取一些動作來還原受影響使用者的存取權。 請參閱[步驟來解除封鎖使用者](#recovering-compromised-accounts)如需有關解除封鎖使用者的程序。

#### <a name="legacy-protocols"></a>舊版通訊協定

郵件用戶端會使用舊版驗證通訊協定 （IMAP、 SMTP、 POP3 等） 提出驗證要求。 這些通訊協定不支援 MFA。 大部分的帳戶入侵不良執行者執行嘗試略過 MFA 的舊版通訊協定攻擊所造成。 若要確保登入合作夥伴目錄中的帳戶時，會需要 MFA，和不良執行者不能略過 MFA，這些安全性需求會封鎖舊版通訊協定的所有驗證要求。

### <a name="enabling-the-baseline-policies"></a>啟用基準原則

請參閱[實作合作夥伴的安全性需求的教學課程](tutorials/partner-security-requirements.yml)有關的基準原則實作的引導式體驗。  

#### <a name="require-mfa-for-admins"></a>適用於系統管理員需要 MFA

*需要系統管理員的 MFA*基準原則要求使用 MFA 進行以下的目錄角色，被視為最特殊權限的 Azure Active Directory 角色：

- 全域管理員
- SharePoint 系統管理員
- Exchange 系統管理員
- 條件式存取系統管理員
- 安全性系統管理員
- 技術支援中心管理員 / 密碼管理員
- 計費管理員
- 使用者管理員

在啟用系統管理員原則需要 MFA，上述的九個的系統管理員角色必須註冊 MFA 使用驗證器應用程式。 MFA 註冊完成之後，系統管理員必須執行 MFA 每次登入。

如果貴組織擁有這些帳戶在指令碼或程式碼中使用，請考慮更換它們 [受管理身分識別](https://docs.microsoft.com/azure/active-directory/managed-identities-azure-resources/overview)。

若要啟用此原則，並保護您的系統管理員：

1. 登入 **Azure 入口網站** 為全域管理員、 安全性系統管理員或條件式存取 」 系統管理員。
2. 瀏覽至**Azure Active Directory** > **條件式存取**。
3. 在原則清單中，選取 **基準原則：適用於系統管理員要求 MFA**。
4. 設定**啟用原則**要**立即使用原則**。
5. 按一下  **儲存**。

    ![適用於系統管理員需要 MFA](images/security/baseline-policy-require-mfa-for-admins.png)

> [!WARNING]
> 啟用此原則之前，請確定您的使用者沒有使用舊版驗證通訊協定。 請參閱文章[How to:區塊使用條件式存取的 Azure Active directory 的舊版驗證](https://docs.microsoft.com/azure/active-directory/conditional-access/howto-baseline-protect-legacy-auth#identify-legacy-authentication-use)如需詳細資訊。

> [!IMPORTANT]
> 沒有已知的問題，會影響您連線到 Exchange Online 的 PowerShell，使用委派的系統管理權限的能力。 請參閱[Exchange Online PowerShell](#exchange-online-powershell)已知問題，然後才啟用此原則，如果您使用此 PowerShell 模組。

#### <a name="end-user-protection"></a>終端使用者的保護

終端使用者保護基準原則保護的目錄中的所有使用者。 啟用此原則需要 14 天內註冊 Azure MFA 的所有使用者。 註冊之後，將 mfa 提示使用者，只在有風險的登入嘗試。 遭盜用的使用者帳戶會遭到封鎖，直到重設密碼，以及風險 dismissal。

原則**基準原則：終端使用者保護**隨附預先設定，然後會出現在頂端當您瀏覽至 Azure 入口網站中的 [條件式存取] 刀鋒視窗。

若要啟用此原則，並保護您的使用者：

1. 登入 **Azure 入口網站** 為全域管理員、 安全性系統管理員或條件式存取 」 系統管理員。
2. 瀏覽至**Azure Active Directory** > **條件式存取**。
3. 在原則清單中，選取 **基準原則：終端使用者 protection （預覽）** 。
4. 設定**啟用原則**要**立即使用原則**。
5. 按一下  **儲存**。

    ![終端使用者的保護](images/security/baseline-policy-end-user-protection.png)

> [!WARNING]
> 啟用此原則之前，請確定您的使用者沒有使用舊版驗證通訊協定。 請參閱文章[How to:區塊使用條件式存取的 Azure Active directory 的舊版驗證](https://docs.microsoft.com/azure/active-directory/conditional-access/howto-baseline-protect-legacy-auth#identify-legacy-authentication-use)如需詳細資訊。

> [!IMPORTANT]
> 沒有已知的問題，會影響您連線到 Exchange Online 的 PowerShell，使用委派的系統管理權限的能力。 請參閱[Exchange Online PowerShell](#exchange-online-powershell)已知問題，然後才啟用此原則，如果您使用此 PowerShell 模組。

## <a name="common-issues"></a>常見問題

### <a name="azure-active-directory"></a>Azure Active Directory

#### <a name="aadsts50076"></a>AADSTS50076

啟用後的基準原則，您可能會發現您的自動化或整合會遇到類似下列的例外狀況

    AADSTS50076: Due to a configuration change made by your administrator, or because you moved to a new location, you must use multi-factor authentication to access 'MyApp'.

這個例外狀況的原因是，您會使用使用者認證來進行驗證，以及 MFA 現在是必要。 若要解決這個例外狀況，您必須使用存取權杖進行驗證。 請參閱[保護的應用程式模型指南](http://assetsprod.microsoft.com/secure-application-model-guide.pdf)如需詳細資訊。

>[!IMPORTANT]
>現今大部分的 Api 和 PowerShell 模組支援使用存取權杖進行驗證的能力。 不過，有一些目前不支援這項功能。 如果您需要幫助您判斷如果您正嘗試利用的 API 或 PowerShell 模組支援使用存取權杖進行驗證，則會張貼訊息上[合作夥伴中心指引安全性群組](https://www.microsoftpartnercommunity.com/t5/Partner-Center-Security-Guidance/ct-p/partner-center-security-guidance)社群。

#### <a name="aadsts700082"></a>AADSTS700082

一旦您實作安全的應用程式模型架構沒有機會，您會收到下列例外狀況在產生初始的重新整理語彙基元之後的 90 天

    The refresh token has expired due to inactivity. The token was issued on 2019-01-02T09:19:53.5422744Z and was inactive for 90.00:00:00

對於 Azure Active Directory 重新整理的最大存留期語彙基元是 90 天。 若要解決這個錯誤，您必須產生，並安全地儲存新的重新整理權杖。 請注意，就能夠以程式設計方式更新重新整理權杖，因為與 Azure Active directory 存取權杖的每個要求會傳回新的重新整理權杖。 您可以實作適當的邏輯在到期之前更新安全地儲存重新整理權杖。

請參閱[Azure Active Directory 中的設定權杖存留期](https://docs.microsoft.com/azure/active-directory/develop/active-directory-configurable-token-lifetimes)如需詳細資訊。

### <a name="recovering-compromised-accounts"></a>復原遭盜用的帳戶

為了協助保護我們的客戶，Microsoft 的認證外洩的服務會尋找公開可用的使用者名稱/密碼組。 如果它們符合其中一個使用者，我們會協助立即保護該帳戶。 確認使用者識別為具有外洩的認證入侵。 這些使用者將無法登入，直到重設其密碼。

如果啟用的功能可在其目錄中，指派 Azure AD Premium 授權的使用者可以還原透過自助式密碼重設 (SSPR) 的存取。 不需要進階授權會被封鎖的使用者必須連絡系統管理員執行手動密碼重設及關閉已標幟的使用者風險事件。

#### <a name="steps-to-unblock-a-user"></a>若要解除封鎖使用者的步驟

確認使用者已藉由檢查使用者的登入記錄封鎖原則。

1. 系統管理員必須登入**Azure 入口網站**並瀏覽至**Azure Active Directory** > **使用者**> 按一下使用者的名稱，然後瀏覽登入。
2. 若要起始密碼重設的已封鎖的使用者，系統管理員必須瀏覽至**Azure Active Directory** > **標示有風險的使用者**
3. 按一下以檢視使用者的最近登入活動的相關資訊會封鎖其帳戶的使用者。
4. 按一下 重設密碼將在下次登入時必須變更暫時密碼。
5. 按一下 關閉以重設使用者的風險分數的所有事件。

使用者現在可以登入、 重設其密碼，並存取應用程式。

## <a name="known-issues"></a>已知問題

### <a name="exchange-online-powershell"></a>Exchange Online PowerShell

啟用 MFA 後合作夥伴將無法利用其委派的系統管理權限使用 Exchange Online PowerShell 來執行對客戶進行的動作。 請參閱[連線到 Exchange Online 的 PowerShell，使用 multi-factor authentication](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/mfa-connect-to-exchange-online-powershell)如有關這項限制的詳細資訊。

## <a name="resources-and-support"></a>資源與支援

透過[合作夥伴中心的安全性指引群組社群](https://www.microsoftpartnercommunity.com/t5/Partner-Center-Security-Guidance/ct-p/partner-center-security-guidance)您可以將找到的其他資源，並了解即將來臨的事件，例如技術上班。 請參閱[常見問題集](http://assetsprod.microsoft.com/security-requirements-faq.pdf)文件，深入了解需求。

### <a name="developers"></a>開發人員

- [啟用安全的應用程式模型](https://docs.microsoft.com/partner-center/develop/enable-secure-app-model)
- [合作夥伴中心.NET 範例](https://github.com/microsoft/partner-center-dotnet-samples)
- [合作夥伴中心 Java 範例](https://github.com/microsoft/partner-center-java-samples)
- [合作夥伴中心 PowerShell 實作安全的應用程式模型](https://docs.microsoft.com/powershell/partnercenter/secure-app-model)
