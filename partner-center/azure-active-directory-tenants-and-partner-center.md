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
# <a name="azure-active-directory-tenants-and-partner-center"></a><span data-ttu-id="3b77d-104">Azure Active Directory 租用戶和合作夥伴中心</span><span class="sxs-lookup"><span data-stu-id="3b77d-104">Azure Active Directory tenants and Partner Center</span></span>  

**<span data-ttu-id="3b77d-105">適用於</span><span class="sxs-lookup"><span data-stu-id="3b77d-105">Applies to</span></span>**

-  <span data-ttu-id="3b77d-106">合作夥伴中心</span><span class="sxs-lookup"><span data-stu-id="3b77d-106">Partner Center</span></span>

## <a name="why-you-need-an-azure-ad-tenant"></a><span data-ttu-id="3b77d-107">為什麼您需要 Azure AD 租用戶</span><span class="sxs-lookup"><span data-stu-id="3b77d-107">Why you need an Azure AD tenant</span></span>

<span data-ttu-id="3b77d-108">我們需要將您組織的 Azure AD 租用戶連結到您的新合作夥伴中心帳戶，讓您的租用戶使用者可以使用 Azure AD (Microsoft 帳戶) 使用者名稱和密碼來登入合作夥伴中心。</span><span class="sxs-lookup"><span data-stu-id="3b77d-108">We need to link your organization’s Azure AD tenant to your new Partner Center account, so your tenant users can sign in to Partner Center with their Azure AD (Microsoft account) user names and passwords.</span></span>

<span data-ttu-id="3b77d-109">如果您的公司已經有 Azure AD 租用戶，就可以將其連結至您的合作夥伴中心帳戶。</span><span class="sxs-lookup"><span data-stu-id="3b77d-109">If your company already has an Azure AD tenant, you can link it to your Partner Center account.</span></span> 

>**<span data-ttu-id="3b77d-110">注意</span><span class="sxs-lookup"><span data-stu-id="3b77d-110">Note</span></span>**<br> <span data-ttu-id="3b77d-111">在您決定使用現有的 Azure AD 租用戶之前，請先考慮租用戶中有多少使用者需要使用合作夥伴中心。</span><span class="sxs-lookup"><span data-stu-id="3b77d-111">Before you decide to use an existing Azure AD tenant, think about how many users in the tenant will need to work in Partner Center.</span></span> <span data-ttu-id="3b77d-112">如果租用戶中有不需要使用合作夥伴中心的使用者，請考慮為那些需要使用合作夥伴中心的使用者建立專屬的新租用戶端。</span><span class="sxs-lookup"><span data-stu-id="3b77d-112">If you have users in the tenant who won’t need to work in Partner Center, consider creating a new tenant for only those users who will need to work in Partner Center.</span></span>

<span data-ttu-id="3b77d-113">如果您的公司還沒有 Azure AD 租用戶，您可以在註冊過程中免費建立租用戶。</span><span class="sxs-lookup"><span data-stu-id="3b77d-113">If your company doesn’t already have an Azure AD tenant, you can create one for free during the enrollment process.</span></span> <span data-ttu-id="3b77d-114">選取 **\[登入 Azure Active Directory\]** 頁面中的 **\[建立新的租用戶\]**。</span><span class="sxs-lookup"><span data-stu-id="3b77d-114">Select **Create new tenant** on the **Sign in to Azure Active Directory** page.</span></span> 

### <a name="not-sure-if-your-company-already-has-an-azure-ad-tenant"></a><span data-ttu-id="3b77d-115">不確定您的公司是否已經有 Azure AD 租用戶嗎？</span><span class="sxs-lookup"><span data-stu-id="3b77d-115">Not sure if your company already has an Azure AD tenant?</span></span>

<span data-ttu-id="3b77d-116">如果不確定您的公司是否有 Azure AD 租用戶端，請依照下列步驟檢查。</span><span class="sxs-lookup"><span data-stu-id="3b77d-116">If you’re not sure whether your company has an Azure AD tenant, follow these steps to check.</span></span> <span data-ttu-id="3b77d-117">請注意，如果您有使用中的 Microsoft Azure 或 Office 365 訂用帳戶，就已經擁有 Azure AD 租用戶。</span><span class="sxs-lookup"><span data-stu-id="3b77d-117">Note that If you have an active subscription to Microsoft Azure or Office 365, you already have an Azure AD tenant.</span></span>
1.  <span data-ttu-id="3b77d-118">登入 Azure 管理入口網站 (網址為 https://ms.portal.azure.com)。</span><span class="sxs-lookup"><span data-stu-id="3b77d-118">Sign in to the Azure admin portal at https://ms.portal.azure.com</span></span>
2.  <span data-ttu-id="3b77d-119">從功能表選取 [Azure Active Directory]，然後選取 [網域名稱]。</span><span class="sxs-lookup"><span data-stu-id="3b77d-119">Select Azure Active Directory from the menu and then select Domain Names.</span></span>
3.  <span data-ttu-id="3b77d-120">如果您已經有租用戶，將會列出您的網域名稱。</span><span class="sxs-lookup"><span data-stu-id="3b77d-120">If you already have a tenant, your domain name will be listed.</span></span>

### <a name="using-an-existing-tenant"></a><span data-ttu-id="3b77d-121">使用現有的租用戶嗎？</span><span class="sxs-lookup"><span data-stu-id="3b77d-121">Using an existing tenant?</span></span>

<span data-ttu-id="3b77d-122">如果您想要使用現有的 Azure AD 租用戶，但無法登入時，請在下面圖表中尋找最符合您的情形的案例，並依照建議的步驟進行。</span><span class="sxs-lookup"><span data-stu-id="3b77d-122">If you want to use an existing Azure AD tenant but you’re having trouble signing in, find the scenario on the diagram below that best matches your situation and follow the recommended steps.</span></span> 

![有 Azure AD 租用戶嗎？還是您需要建立一個？](images/onboardingAADFlow.png)

<span data-ttu-id="3b77d-124">如需關於在 Azure AD 中新增網域的詳細資訊，請參閱[在 Azure AD 中新增網域或建立網域關聯](https://docs.microsoft.com/azure/active-directory/active-directory-add-domain)</span><span class="sxs-lookup"><span data-stu-id="3b77d-124">For more information about adding domains in Azure AD, see [Add or associate a domain in Azure AD](https://docs.microsoft.com/azure/active-directory/active-directory-add-domain)</span></span>

## <a name="about-microsoft-azure"></a><span data-ttu-id="3b77d-125">關於 Microsoft Azure</span><span class="sxs-lookup"><span data-stu-id="3b77d-125">About Microsoft Azure</span></span>

<span data-ttu-id="3b77d-126">Microsoft Azure 是一個公用雲端平台，公司可以用來在 Microsoft 管理的資料中心全球網路上建置、部署和管理應用程式。</span><span class="sxs-lookup"><span data-stu-id="3b77d-126">Microsoft Azure is a public cloud platform that companies can use to build, deploy, and manage applications across a global network of Microsoft-managed datacenters.</span></span> <span data-ttu-id="3b77d-127">公司會利用 Azure，透過虛擬功能或服務 (而不是實體機器) 來建置虛擬 IT 基礎結構。</span><span class="sxs-lookup"><span data-stu-id="3b77d-127">Companies use Azure to build a virtual IT infrastructure with virtual functions, or services, instead of physical machines.</span></span> 

<span data-ttu-id="3b77d-128">當您購買 Azure  訂用帳戶時，基本上就是在租借 Azure 公用雲端的專用安全空間，這跟您租用辦公大樓的場地來經營公司的實體業務沒有太大區別。</span><span class="sxs-lookup"><span data-stu-id="3b77d-128">When you purchase an Azure subscription, you’re essentially renting a dedicated, secure space in the Azure public cloud, not too different from renting a floor in an office building to house your company’s physical business.</span></span> <span data-ttu-id="3b77d-129">相對於辦公大樓的擁有者，您的公司就是租用戶。</span><span class="sxs-lookup"><span data-stu-id="3b77d-129">To the office building’s owner, your company is a tenant.</span></span> 

<span data-ttu-id="3b77d-130">Azure AD 租用戶是您公司在 Azure 公用雲端的專用且隔離的虛擬表示，這已在您訂閱 Microsoft 雲端服務 (例如 Azure、Microsoft Intune 或 Office 365) 時建立。</span><span class="sxs-lookup"><span data-stu-id="3b77d-130">An Azure AD tenant is a dedicated and isolated virtual representation of your company in the Azure public cloud, created for you when you subscribe to a Microsoft cloud service such as Azure, Microsoft Intune, or Office 365.</span></span> 

<span data-ttu-id="3b77d-131">您的租用戶會裝載 Azure AD 的使用者和他們的相關資訊 (密碼、設定檔資料、權限等等)。</span><span class="sxs-lookup"><span data-stu-id="3b77d-131">Your tenant hosts your Azure AD users and the information about them - their passwords, profile data, permissions, and so on.</span></span> <span data-ttu-id="3b77d-132">租用戶也會包含群組、應用程式和其他有關公司及其安全性的資訊。</span><span class="sxs-lookup"><span data-stu-id="3b77d-132">The tenant also contains groups,applications, and other information pertaining to a company and its security.</span></span> 

<span data-ttu-id="3b77d-133">深入了解 Azure AD，請參閱 [Azure Active Directory 文件](https://docs.microsoft.com/ azure/active-directory/)。</span><span class="sxs-lookup"><span data-stu-id="3b77d-133">To learn more about Azure AD, see the [Azure Active Directory Documentation](https://docs.microsoft.com/ azure/active-directory/).</span></span> 