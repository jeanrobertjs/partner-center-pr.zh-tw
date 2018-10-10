---
title: 適用於 CSP 合作夥伴的 Cloudyn 支援的 Azure 成本管理 | 合作夥伴中心
description: Cloudyn 支援的 Azure 成本管理需要對 Partner Center API 佈建存取權。
author: Janet
Keywords: Azure cost management app, manage costs, web apps
robots: ''
ms.localizationpriority: medium
ms.openlocfilehash: 9f5439f47dbc99421e493c9f84f8ea2469ba6525
ms.sourcegitcommit: 123a7f53d633c27eb5f982926d856de47afb1042
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 10/09/2018
ms.locfileid: "4489384"
---
# <a name="azure-cost-management-app-for-azure-csp-partners"></a><span data-ttu-id="72aa8-103">Azure CSP 合作夥伴適用的 Azure 成本管理應用程式</span><span class="sxs-lookup"><span data-stu-id="72aa8-103">Azure cost management app for Azure CSP partners</span></span>  

**<span data-ttu-id="72aa8-104">適用對象：</span><span class="sxs-lookup"><span data-stu-id="72aa8-104">Applies to</span></span>**

-  <span data-ttu-id="72aa8-105">合作夥伴中心</span><span class="sxs-lookup"><span data-stu-id="72aa8-105">Partner Center</span></span>

[<span data-ttu-id="72aa8-106">取得有關 Azure 成本管理的詳細資訊</span><span class="sxs-lookup"><span data-stu-id="72aa8-106">Get More information about Azure Cost Management</span></span>](https://go.microsoft.com/fwlink/p/?linkid=857893)

## <a name="before-you-begin"></a><span data-ttu-id="72aa8-107">在您開始前</span><span class="sxs-lookup"><span data-stu-id="72aa8-107">Before you begin</span></span>
<span data-ttu-id="72aa8-108">在可以使用 Azure 成本管理之前，請先確定您符合下列需求：</span><span class="sxs-lookup"><span data-stu-id="72aa8-108">Before you can use Azure Cost Management, be sure you meet the following requirements:</span></span>

- <span data-ttu-id="72aa8-109">您是雲端解決方案提供者計畫的合作夥伴。</span><span class="sxs-lookup"><span data-stu-id="72aa8-109">You are a partner in the Cloud Solution Provider program.</span></span>
- <span data-ttu-id="72aa8-110">您有能力建立 Partner Center API Web 應用程式。</span><span class="sxs-lookup"><span data-stu-id="72aa8-110">You have the ability to create a Partner Center API web app.</span></span>

## <a name="overview"></a><span data-ttu-id="72aa8-111">概觀</span><span class="sxs-lookup"><span data-stu-id="72aa8-111">Overview</span></span>

<span data-ttu-id="72aa8-112">Cloudyn 支援的 Azure 成本管理是 Web 應用程式，可讓您追蹤並管理您有多少客戶正在使用 Azure 以及使用成本。</span><span class="sxs-lookup"><span data-stu-id="72aa8-112">Azure cost management by Cloudyn is a web app that allows you to track and manage how much your customers are using Azure and the costs of that usage.</span></span> <span data-ttu-id="72aa8-113">您是透過合作夥伴中心 API 使用此應用程式。</span><span class="sxs-lookup"><span data-stu-id="72aa8-113">You use it through the Partner Center API.</span></span>

## <a name="register-your-web-app-in-the-partner-center"></a><span data-ttu-id="72aa8-114">在合作夥伴中心註冊您的 Web 應用程式</span><span class="sxs-lookup"><span data-stu-id="72aa8-114">Register your web app in the Partner Center</span></span>
<span data-ttu-id="72aa8-115">當您在合作夥伴中心註冊 Azure Active Directory Web 應用程式，您就啟用對合作夥伴中心 API 的存取權。</span><span class="sxs-lookup"><span data-stu-id="72aa8-115">When you register an Azure Active Directory web app in Partner Center you enable access to the the Partner Center API.</span></span> 
1.  <span data-ttu-id="72aa8-116">使用[全域系統管理員或系統管理代理人帳戶](create-user-accounts-and-set-permissions.md)登入[合作夥伴中心](https://partnercenter.microsoft.com/en-us/pcv/dashboard/overview)。</span><span class="sxs-lookup"><span data-stu-id="72aa8-116">Sign into [the Partner Center](https://partnercenter.microsoft.com/en-us/pcv/dashboard/overview) using a [global admin or admin agent account](create-user-accounts-and-set-permissions.md).</span></span>
2.  <span data-ttu-id="72aa8-117">從**合作夥伴中心**中，選取 [**帳戶設定** &gt; **[應用程式管理](https://partnercenter.microsoft.com/en-us/pcv/apiintegration/appmanagement)**。</span><span class="sxs-lookup"><span data-stu-id="72aa8-117">From the **Partner Center**, select **Account settings** &gt; **[App management](https://partnercenter.microsoft.com/en-us/pcv/apiintegration/appmanagement)**.</span></span>
3.  <span data-ttu-id="72aa8-118">在 **\[Web 應用程式\]** 區段中，按一下 **\[新增 Web 應用程式\]**。</span><span class="sxs-lookup"><span data-stu-id="72aa8-118">In the **Web App** section, click **Add new web app**.</span></span>
<br> <span data-ttu-id="72aa8-119">**注意**：如果您先前已建立 Web 應用程式，可以略過步驟 3。</span><span class="sxs-lookup"><span data-stu-id="72aa8-119">**Note**: If you have previously created a web app, you can skip step 3.</span></span>
4.  <span data-ttu-id="72aa8-120">複製並儲存您 Web 應用程式的**商務識別碼** GUID 和**應用程式識別碼** GUID。</span><span class="sxs-lookup"><span data-stu-id="72aa8-120">Copy and save the **Commerce ID** GUID and the **App ID** GUID for your web app.</span></span> <span data-ttu-id="72aa8-121">您將需要這兩個識別碼，才能使用 30 天免費試用版的 Azure 成本管理應用程式。</span><span class="sxs-lookup"><span data-stu-id="72aa8-121">You will need both IDs to use the 30-day free trial of the Azure cost management app.</span></span>

## <a name="add-a-secret-key-to-your-app"></a><span data-ttu-id="72aa8-122">將秘密金鑰新增到您的應用程式。</span><span class="sxs-lookup"><span data-stu-id="72aa8-122">Add a secret key to your app</span></span>
1.  <span data-ttu-id="72aa8-123">在 **\[新增金鑰\]** 按鈕旁邊的下拉式清單中，選取 1 或 2 年期間。</span><span class="sxs-lookup"><span data-stu-id="72aa8-123">In the drop down next to the **Add key** button, select a duration of 1 or 2 years.</span></span>
2.  <span data-ttu-id="72aa8-124">按一下 **\[新增金鑰\]**。</span><span class="sxs-lookup"><span data-stu-id="72aa8-124">Click **Add key**.</span></span> 
3.  <span data-ttu-id="72aa8-125">複製並儲存秘密金鑰值。</span><span class="sxs-lookup"><span data-stu-id="72aa8-125">Copy and save the secret key value.</span></span> <span data-ttu-id="72aa8-126">您將需要此值，以便使用 30 天免費試用版。</span><span class="sxs-lookup"><span data-stu-id="72aa8-126">You will need this for the 30-day free trial.</span></span><br>
> [!NOTE]  
> <span data-ttu-id="72aa8-127">應用程式秘密金鑰就像是到期日較長的密碼。</span><span class="sxs-lookup"><span data-stu-id="72aa8-127">The application secret keys are like passwords with longer expiration dates.</span></span> <span data-ttu-id="72aa8-128">請將金鑰值儲存在安全的位置，以供未來使用。</span><span class="sxs-lookup"><span data-stu-id="72aa8-128">Please save the key value in a secure location for future use.</span></span>

## <a name="next-steps"></a><span data-ttu-id="72aa8-129">後續步驟</span><span class="sxs-lookup"><span data-stu-id="72aa8-129">Next steps</span></span>
<span data-ttu-id="72aa8-130">啟動 [30 天免費試用版](https://go.microsoft.com/fwlink/?linkid=857895)。</span><span class="sxs-lookup"><span data-stu-id="72aa8-130">Start a [30-day free trial](https://go.microsoft.com/fwlink/?linkid=857895).</span></span>
<span data-ttu-id="72aa8-131">若要啟動試用版，您需要下列資訊：</span><span class="sxs-lookup"><span data-stu-id="72aa8-131">You need the following details to start the trial:</span></span>
- <span data-ttu-id="72aa8-132">合作夥伴中心登入憑證</span><span class="sxs-lookup"><span data-stu-id="72aa8-132">Partner Center sign in credentials</span></span>
- <span data-ttu-id="72aa8-133">商務識別碼 GUID</span><span class="sxs-lookup"><span data-stu-id="72aa8-133">Commerce ID GUID</span></span>
- <span data-ttu-id="72aa8-134">應用程式識別碼 GUID</span><span class="sxs-lookup"><span data-stu-id="72aa8-134">App ID GUID</span></span>
- <span data-ttu-id="72aa8-135">應用程式秘密金鑰值</span><span class="sxs-lookup"><span data-stu-id="72aa8-135">Application secret key value</span></span>
