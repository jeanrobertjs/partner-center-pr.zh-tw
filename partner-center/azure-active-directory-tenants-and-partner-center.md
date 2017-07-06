---
title: "Azure Active Directory 租用戶和合作夥伴中心 | 合作夥伴中心"
description: "若要建立合作夥伴中心帳戶，您的公司必須有 Azure Active Directory (Azure AD) 租用戶。 Azure AD 是 Microsoft 的雲端式目錄及身分識別管理服務。"
author: labrenne
robots: 
ms.openlocfilehash: 9a9a3c3aa239017fe8ecf655f79acbfab6ff8a0b
ms.sourcegitcommit: d7c4ca62acd1ef1026c7d322e40f55a83a80e72a
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 06/28/2017
---
# <a name="azure-active-directory-tenants-and-partner-center"></a>Azure Active Directory 租用戶和合作夥伴中心  

**適用於**

-  合作夥伴中心

## <a name="why-you-need-an-azure-ad-tenant"></a>為什麼您需要 Azure AD 租用戶

我們需要將您組織的 Azure AD 租用戶連結到您的新合作夥伴中心帳戶，讓您的租用戶使用者可以使用 Azure AD (Microsoft 帳戶) 使用者名稱和密碼來登入合作夥伴中心。

如果您的公司已經有 Azure AD 租用戶，就可以將其連結至您的合作夥伴中心帳戶。 

>**注意**<br> 在您決定使用現有的 Azure AD 租用戶之前，請先考慮租用戶中有多少使用者需要使用合作夥伴中心。 如果租用戶中有不需要使用合作夥伴中心的使用者，請考慮為那些需要使用合作夥伴中心的使用者建立專屬的新租用戶端。

如果您的公司還沒有 Azure AD 租用戶，您可以在註冊過程中免費建立租用戶。 選取 **\[登入 Azure Active Directory\]** 頁面中的 **\[建立新的租用戶\]**。 

### <a name="not-sure-if-your-company-already-has-an-azure-ad-tenant"></a>不確定您的公司是否已經有 Azure AD 租用戶嗎？

如果不確定您的公司是否有 Azure AD 租用戶端，請依照下列步驟檢查。 請注意，如果您有使用中的 Microsoft Azure 或 Office 365 訂用帳戶，就已經擁有 Azure AD 租用戶。
1.  登入 Azure 管理入口網站 (網址為 https://ms.portal.azure.com)。
2.  從功能表選取 [Azure Active Directory]，然後選取 [網域名稱]。
3.  如果您已經有租用戶，將會列出您的網域名稱。

### <a name="using-an-existing-tenant"></a>使用現有的租用戶嗎？

如果您想要使用現有的 Azure AD 租用戶，但無法登入時，請在下面圖表中尋找最符合您的情形的案例，並依照建議的步驟進行。 

![有 Azure AD 租用戶嗎？還是您需要建立一個？](images/onboardingAADFlow.png)

如需關於在 Azure AD 中新增網域的詳細資訊，請參閱[在 Azure AD 中新增網域或建立網域關聯](https://docs.microsoft.com/azure/active-directory/active-directory-add-domain)

## <a name="about-microsoft-azure"></a>關於 Microsoft Azure

Microsoft Azure 是一個公用雲端平台，公司可以用來在 Microsoft 管理的資料中心全球網路上建置、部署和管理應用程式。 公司會利用 Azure，透過虛擬功能或服務 (而不是實體機器) 來建置虛擬 IT 基礎結構。 

當您購買 Azure  訂用帳戶時，基本上就是在租借 Azure 公用雲端的專用安全空間，這跟您租用辦公大樓的場地來經營公司的實體業務沒有太大區別。 相對於辦公大樓的擁有者，您的公司就是租用戶。 

Azure AD 租用戶是您公司在 Azure 公用雲端的專用且隔離的虛擬表示，這已在您訂閱 Microsoft 雲端服務 (例如 Azure、Microsoft Intune 或 Office 365) 時建立。 

您的租用戶會裝載 Azure AD 的使用者和他們的相關資訊 (密碼、設定檔資料、權限等等)。 租用戶也會包含群組、應用程式和其他有關公司及其安全性的資訊。 

深入了解 Azure AD，請參閱 [Azure Active Directory 文件](https://docs.microsoft.com/ azure/active-directory/)。 