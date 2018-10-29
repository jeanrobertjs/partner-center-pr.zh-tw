---
title: 為客戶設定 Azure 消費預算 | 合作夥伴中心
ms.topic: article
ms.date: 10/29/2018
description: 在合作夥伴中心，您可以設定每個客戶每月的預算，免得月底的 Azure 帳單金額讓他們很吃驚。
ms.assetid: DDE80361-D04E-432C-BC15-D735D2AE954F
author: MaggiePucciEvans
ms.author: evansma
ms.localizationpriority: medium
ms.openlocfilehash: 98b6a4839b599a43ba6c10506468be7dbd064d43
ms.sourcegitcommit: ed22f6825d3af1d19385198b4d511e4b39d5e353
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 10/29/2018
ms.locfileid: "5794981"
---
# <a name="set-an-azure-spending-budget-for-your-customers"></a><span data-ttu-id="755fd-103">為客戶設定 Azure 消費預算</span><span class="sxs-lookup"><span data-stu-id="755fd-103">Set an Azure spending budget for your customers</span></span>

**<span data-ttu-id="755fd-104">適用於</span><span class="sxs-lookup"><span data-stu-id="755fd-104">Applies to</span></span>**

-  <span data-ttu-id="755fd-105">合作夥伴中心</span><span class="sxs-lookup"><span data-stu-id="755fd-105">Partner Center</span></span>
-  <span data-ttu-id="755fd-106">美國政府適用的 Microsoft Cloud 合作夥伴中心</span><span class="sxs-lookup"><span data-stu-id="755fd-106">Partner Center for Microsoft Cloud for US Government</span></span>
-  <span data-ttu-id="755fd-107">Microsoft Cloud 德國合作夥伴中心</span><span class="sxs-lookup"><span data-stu-id="755fd-107">Partner Center for Microsoft Cloud Germany</span></span>

<span data-ttu-id="755fd-108">為了協助客戶管理他們的 Azure 消費，您可以設定每月消費預算，使其 Azure 帳單金額不致高出預期。</span><span class="sxs-lookup"><span data-stu-id="755fd-108">To help customers manage their Azure spending, you can set a monthly spending budget so that their Azure bill isn’t higher than they anticipated.</span></span> <span data-ttu-id="755fd-109">設定 Azure 消費預算可讓您將客戶的 Azure 消費與當月份預算做比較。</span><span class="sxs-lookup"><span data-stu-id="755fd-109">Setting an Azure spending budget allows you to compare your customers' Azure spending to the budget during the month.</span></span> <span data-ttu-id="755fd-110">有了這項功能，您就可以：</span><span class="sxs-lookup"><span data-stu-id="755fd-110">With this feature, you can:</span></span> 

-   <span data-ttu-id="755fd-111">在客戶的消費金額接近預算限制時收到電子郵件通知</span><span class="sxs-lookup"><span data-stu-id="755fd-111">Be notified by email if a customer's spending is near the budget limit</span></span>
-   <span data-ttu-id="755fd-112">檢閱客戶的每月預估 Azure 費用</span><span class="sxs-lookup"><span data-stu-id="755fd-112">Review your customers’ estimated Azure costs per month</span></span>
-   <span data-ttu-id="755fd-113">發現設定不當的服務，或看出浮現詐騙跡象的異常用量趨勢</span><span class="sxs-lookup"><span data-stu-id="755fd-113">Spot a misconfigured service, or unusual usage trends that might suggest fraud</span></span>
-   <span data-ttu-id="755fd-114">和客戶合作，共同找出根本的問題，並設法管理費用</span><span class="sxs-lookup"><span data-stu-id="755fd-114">Work with the customer to identify the root issue and manage costs</span></span>
-   <span data-ttu-id="755fd-115">如果您和您的客戶皆同意，可以將預算調整為較高金額</span><span class="sxs-lookup"><span data-stu-id="755fd-115">Change the budget to a higher amount if you and your customer are comfortable with it</span></span>

<span data-ttu-id="755fd-116">Azure 消費資料為估計值，實際帳單金額可能會有差異，這個值不含稅、點數、帳務調整或其他需要支付的費用。</span><span class="sxs-lookup"><span data-stu-id="755fd-116">The Azure spending data is an estimate, actual billing amounts may vary, and the value does not reflect taxes, credits, adjustments, or other charges that may apply.</span></span> <span data-ttu-id="755fd-117">消費資料每天重新整理一次。</span><span class="sxs-lookup"><span data-stu-id="755fd-117">Spending data is refreshed once per day.</span></span> <span data-ttu-id="755fd-118">除非您在 Azure 入口網站變更客戶的帳戶設定，否則客戶仍將繼續使用 Azure 服務及資源，並支付相關費用。</span><span class="sxs-lookup"><span data-stu-id="755fd-118">Customers will continue to use—and be charged for—Azure services and resources unless you change their account settings in the Azure portal.</span></span> 

> [!NOTE]  
> <span data-ttu-id="755fd-119">無法在沙箱或測試實際執行環境 (TIP) 帳戶中使用此功能。</span><span class="sxs-lookup"><span data-stu-id="755fd-119">This feature is not available in sandbox or Test in Production (TIP) accounts.</span></span>

**<span data-ttu-id="755fd-120">開啟電子郵件通知</span><span class="sxs-lookup"><span data-stu-id="755fd-120">Turn on email notifications</span></span>**
1.  <span data-ttu-id="755fd-121">從合作夥伴中心功能表中，選取 [ **Azure 消費**。</span><span class="sxs-lookup"><span data-stu-id="755fd-121">From the Partner Center menu, select **Azure spending**.</span></span>
2.  <span data-ttu-id="755fd-122">將 **\[取得電子郵件\]** 選項切換為要在客戶的使用達預算的 80% 以上時收到通知。</span><span class="sxs-lookup"><span data-stu-id="755fd-122">Toggle on the **Get emails** option to be notified when customers use 80% or more of their budget.</span></span> <span data-ttu-id="755fd-123">這樣能協助您留意 Azure 帳單。</span><span class="sxs-lookup"><span data-stu-id="755fd-123">This will help you keep an eye on your Azure bill.</span></span> <span data-ttu-id="755fd-124">您可以將預設的電子郵件地址變更為個人或其他電子郵件以接收通知。</span><span class="sxs-lookup"><span data-stu-id="755fd-124">You can change the default email address to a personal or any other email to receive notifications.</span></span>

**<span data-ttu-id="755fd-125">設定預算</span><span class="sxs-lookup"><span data-stu-id="755fd-125">Set a budget</span></span>**
1.  <span data-ttu-id="755fd-126">從合作夥伴中心功能表中，選取 [ **Azure 消費**。</span><span class="sxs-lookup"><span data-stu-id="755fd-126">From the Partner Center menu, select **Azure spending**.</span></span>
2.  <span data-ttu-id="755fd-127">選取您想要為其設定預算的客戶。</span><span class="sxs-lookup"><span data-stu-id="755fd-127">Select the customer(s) you want to set a budget for.</span></span> 
3. <span data-ttu-id="755fd-128">在 **\[每月預算\]** 方塊中輸入一個值並選取 **\[套用\]**。</span><span class="sxs-lookup"><span data-stu-id="755fd-128">Enter a value in the **Monthly budget** box and then select **Apply**.</span></span>
4.  <span data-ttu-id="755fd-129">若要檢查目前的消費，請返回此頁面。</span><span class="sxs-lookup"><span data-stu-id="755fd-129">To check current spending, return to this page.</span></span>
5.  <span data-ttu-id="755fd-130">也可以從客戶管理頁面的 **\[用量型訂閱\]** 設定個別的預算。</span><span class="sxs-lookup"><span data-stu-id="755fd-130">Individual budgets can also be set under **Usage-based subscriptions** on a customer management page.</span></span>

**<span data-ttu-id="755fd-131">移除預算</span><span class="sxs-lookup"><span data-stu-id="755fd-131">Remove a budget</span></span>**
1.  <span data-ttu-id="755fd-132">從合作夥伴中心功能表中，選取 [ **Azure 消費**。</span><span class="sxs-lookup"><span data-stu-id="755fd-132">From the Partner Center menu, select **Azure spending**.</span></span>
2.  <span data-ttu-id="755fd-133">從清單中選取客戶。</span><span class="sxs-lookup"><span data-stu-id="755fd-133">Select customers from the list.</span></span>
3.  <span data-ttu-id="755fd-134">選取 **\[移除預算\]**。</span><span class="sxs-lookup"><span data-stu-id="755fd-134">Select **Remove budget**.</span></span>

**<span data-ttu-id="755fd-135">查看分項成本</span><span class="sxs-lookup"><span data-stu-id="755fd-135">See itemized costs</span></span>**
1.  <span data-ttu-id="755fd-136">從合作夥伴中心功能表中，選取**客戶**。</span><span class="sxs-lookup"><span data-stu-id="755fd-136">From the Partner Center menu, select **Customers**.</span></span>
2.  <span data-ttu-id="755fd-137">從客戶清單中選取客戶。</span><span class="sxs-lookup"><span data-stu-id="755fd-137">From the customer list, select a customer.</span></span>
3.  <span data-ttu-id="755fd-138">在其客戶管理頁面中，於 **\[用量型訂閱\]** 下選擇一項訂閱。</span><span class="sxs-lookup"><span data-stu-id="755fd-138">On their customer management page, under **Usage-based subscriptions**, choose a subscription.</span></span> <span data-ttu-id="755fd-139">檢視其目前的預估用量及依服務分項的支出清單。</span><span class="sxs-lookup"><span data-stu-id="755fd-139">View its current estimated usage and a list of itemized costs by service.</span></span>


 

 



