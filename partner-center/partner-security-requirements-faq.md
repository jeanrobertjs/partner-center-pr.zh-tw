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
# <a name="frequently-asked-questions-about-the-partner-security-requirements"></a>關於合作夥伴安全性需求的常見問題

本文包含[合作夥伴安全性需求](partner-security-requirements.md)的一些常見問題。 您可以在[這裡](http://assetsprod.microsoft.com/security-requirements-faq.pdf)找到完整的常見問題清單。

## <a name="conditional-access"></a>條件式存取

### <a name="can-conditional-access-be-used"></a>是否可以使用條件式存取？

是, 您可以使用條件式存取, 為您的夥伴租使用者中的每個使用者 (包括服務帳戶) 強制執行 MFA。 不過, 由於身為合作夥伴的高度特殊許可權, 我們必須確保每個使用者都有每個單一驗證的 MFA 挑戰。 這表示您將無法利用避開 MFA 需求的條件式存取功能。

## <a name="multi-factor-authentication"></a>多重要素驗證

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

### <a name="what-verification-options-are-provided-through-the-implementation-of-the-baseline-protection-policies"></a>哪些驗證選項是透過基準保護原則的執行而提供？ 

關於可透過執行基準保護原則來取得的 MFA 版本, 唯一可用的驗證選項是驗證器應用程式。 使用通話和文字訊息訊息會被視為較不安全。 因此, 這些選項無法透過此版本的 MFA 使用。

### <a name="will-the-service-account-used-by-azure-ad-connect-be-impacted-by-the-partner-security-requirements"></a>Azure AD Connect 所使用的服務帳戶是否會受到合作夥伴安全性需求的影響？

否, Azure AD Connect 所使用的服務帳戶不會受到合作夥伴安全性需求的影響。 如果您在強制執行 MFA 時遇到 Azure AD Connect 的問題, 請向 Microsoft 支援服務開啟技術支援要求。
