---
title: Azure Active Directory tenants and Partner Center | Partner Center
description: "To create a Partner Center account, your company must have an Azure Active Directory (Azure AD) tenant. Azure AD is Microsoft’s cloud-based directory and identity management service."
author: labrenne
robots: 
ms.openlocfilehash: ab16d167fc978d76c96fc6ef7c1b8eabe26a1ad5
ms.sourcegitcommit: c47f8e765def420017abe290f2f7327eab2cbba7
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 07/07/2017
---
# <a name="azure-active-directory-tenants-and-partner-center"></a>Azure Active Directory tenants and Partner Center  

**Applies to**

-  Partner Center

#<a name="why-you-need-an-azure-ad-tenant"></a>Why you need an Azure AD tenant

We need to link your organization’s Azure AD tenant to your new Partner Center account, so your tenant users can sign in to Partner Center with their Azure AD (Microsoft account) user names and passwords.

If your company already has an Azure AD tenant, you can link it to your Partner Center account. 

**注意**：決定使用現有的 Azure AD 租用戶之前，請先考慮租用戶中有多少使用者需要使用合作夥伴中心。 If you have users in the tenant who won’t need to work in Partner Center, consider creating a new tenant for only those users who will need to work in Partner Center.

如果您的公司還沒有 Azure AD 租用戶，您可以在註冊過程中免費建立租用戶。 選取 **\[登入 Azure Active Directory\]** 頁面中的 **\[建立新的租用戶\]**。 


## <a name="not-sure-if-your-company-already-has-an-azure-ad-tenant"></a>不確定您的公司是否已經有 Azure AD 租用戶嗎？

If you’re not sure whether your company has an Azure AD tenant, follow these steps to check. Note that If you have an active subscription to Microsoft Azure or Office 365, you already have an Azure AD tenant.
1.  Sign in to the Azure admin portal at https://ms.portal.azure.com
2.  Select Azure Active Directory from the menu and then select Domain Names.
3.  如果您已經有租用戶，就會列出您的網域名稱。

##<a name="using-an-existing-tenant"></a>使用現有的租用戶

If you want to use an existing Azure AD tenant but you’re having trouble signing in, find the scenario on the diagram below that best matches your situation and follow the recommended steps. 

![有 Azure AD 租用戶嗎？還是您需要建立一個？](images/onboardingAADFlow.png)

如需關於在 Azure AD 中新增網域的詳細資訊，請參閱[在 Azure AD 中新增網域或建立網域關聯](https://docs.microsoft.com/azure/active-directory/active-directory-add-domain)

# <a name="about-microsoft-azure"></a>關於 Microsoft Azure

Microsoft Azure is a public cloud platform that companies can use to build, deploy, and manage applications across a global network of Microsoft-managed datacenters. Companies use Azure to build a virtual IT infrastructure with virtual functions, or services, instead of physical machines. 

When you purchase an Azure subscription, you’re essentially renting a dedicated, secure space in the Azure public cloud, not too different from renting a floor in an office building to house your company’s physical business. To the office building’s owner, your company is a tenant. 

An Azure AD tenant is a dedicated and isolated virtual representation of your company in the Azure public cloud, created for you when you subscribe to a Microsoft cloud service such as Azure, Microsoft Intune, or Office 365. 

您的租用戶會裝載 Azure AD 的使用者和他們的相關資訊 (密碼、設定檔資料、權限等等)。 租用戶也包含群組、應用程式，以及其他有關公司與其安全性的資訊。 
