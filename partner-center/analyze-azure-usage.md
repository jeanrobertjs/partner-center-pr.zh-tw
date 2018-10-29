---
title: 分析 Azure 使用率 |合作夥伴中心
ms.date: 07/12/2018
Description: Get data about the usage of your customers' Azure subscriptions.
Author: Xansky
ms.author: mhopkins
ms.assetid: E7081190-C1FA-47C1-963B-6EBA1B33703B
ms.topic: article
keywords: 業務資料
ms.localizationpriority: medium
ms.openlocfilehash: e5ed6ce99a8319ce2e86b8522f1bdf40ccf5b2f9
ms.sourcegitcommit: ed22f6825d3af1d19385198b4d511e4b39d5e353
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 10/29/2018
ms.locfileid: "5795661"
---
# <a name="get-data-about-the-usage-of-your-customers-azure-subscriptions"></a><span data-ttu-id="f3d22-103">取得您客戶 Azure 訂閱使用狀況的相關資料</span><span class="sxs-lookup"><span data-stu-id="f3d22-103">Get data about the usage of your customers' Azure subscriptions</span></span> 

**<span data-ttu-id="f3d22-104">適用對象：</span><span class="sxs-lookup"><span data-stu-id="f3d22-104">Applies to</span></span>**
- <span data-ttu-id="f3d22-105">合作夥伴中心</span><span class="sxs-lookup"><span data-stu-id="f3d22-105">Partner Center</span></span>

<span data-ttu-id="f3d22-106">資料推動業務決策。</span><span class="sxs-lookup"><span data-stu-id="f3d22-106">Data drives business decisions.</span></span> <span data-ttu-id="f3d22-107">使用**Azure 使用量**頁面中的計量，找出您的成功與需要更多人注意的領域。</span><span class="sxs-lookup"><span data-stu-id="f3d22-107">Use the metrics in the **Azure usage** page to identify your successes and areas that need more attention.</span></span> <span data-ttu-id="f3d22-108">在規劃新的業務務目標時，請使用此資訊。</span><span class="sxs-lookup"><span data-stu-id="f3d22-108">Use this information as you plan new business goals.</span></span>

> [!NOTE]
> <span data-ttu-id="f3d22-109">Azure 使用量分析是僅適用於雲端解決方案提供者計畫中的合作夥伴。</span><span class="sxs-lookup"><span data-stu-id="f3d22-109">Azure usage  analytics is available only for partners in the Cloud Solution Provider program.</span></span>

<span data-ttu-id="f3d22-110">我們正在追蹤下列計量︰</span><span class="sxs-lookup"><span data-stu-id="f3d22-110">We are tracking the following metrics:</span></span>

**<span data-ttu-id="f3d22-111">摘要</span><span class="sxs-lookup"><span data-stu-id="f3d22-111">Summary</span></span>**  
 - <span data-ttu-id="f3d22-112">**售出的總 Azure 訂閱**： 訂閱售出的指定的時間內</span><span class="sxs-lookup"><span data-stu-id="f3d22-112">**Total Azure subscriptions sold**: Number of subscriptions sold in the specified time period</span></span>  
 - <span data-ttu-id="f3d22-113">**使用方式的客戶**： 使用 Azure 的使用方式中指定的時間週期的客戶數目</span><span class="sxs-lookup"><span data-stu-id="f3d22-113">**Customers with usage**: Number of customers with Azure usage in the specified time period</span></span>  
 - <span data-ttu-id="f3d22-114">**不使用方式的客戶**： 不在指定的時間期間內的 Azure 使用率的客戶數目</span><span class="sxs-lookup"><span data-stu-id="f3d22-114">**Customers without usage**: Number of customers without Azure usage in the specified time period</span></span>  

**<span data-ttu-id="f3d22-115">類別中的前 5 個客戶</span><span class="sxs-lookup"><span data-stu-id="f3d22-115">Top 5 customers in category</span></span>**  
 -  <span data-ttu-id="f3d22-116">指定類別前 5 個客戶</span><span class="sxs-lookup"><span data-stu-id="f3d22-116">The top 5 customers for the specified category</span></span>  

**<span data-ttu-id="f3d22-117">訂閱，而不使用方式</span><span class="sxs-lookup"><span data-stu-id="f3d22-117">Subscriptions without usage</span></span>**  
 -  <span data-ttu-id="f3d22-118">在指定的時間期間內沒有 Azure 使用量的 sepcific 訂閱清單</span><span class="sxs-lookup"><span data-stu-id="f3d22-118">List of sepcific subscriptions without Azure usage in the specified time period</span></span>  

**<span data-ttu-id="f3d22-119">Azure 訂用帳戶變換</span><span class="sxs-lookup"><span data-stu-id="f3d22-119">Azure subscription churn</span></span>**  
 - <span data-ttu-id="f3d22-120">**使用中訂閱**： 依日期的使用中訂閱計數</span><span class="sxs-lookup"><span data-stu-id="f3d22-120">**Active subscriptions**: Count of active subscriptions by date</span></span>  
 - <span data-ttu-id="f3d22-121">**Deprovisioned 訂閱**： 訂閱的計數辭去或暫停的日期</span><span class="sxs-lookup"><span data-stu-id="f3d22-121">**Deprovisioned subscriptions**: Count of subscriptions deprovisioned or suspended by date</span></span>  

**<span data-ttu-id="f3d22-122">客戶的計數</span><span class="sxs-lookup"><span data-stu-id="f3d22-122">Customer count</span></span>**
 - <span data-ttu-id="f3d22-123">在指定的時間期間取得的新客戶</span><span class="sxs-lookup"><span data-stu-id="f3d22-123">New customers acquired during the specified time period</span></span>  

**<span data-ttu-id="f3d22-124">Azure 訂用帳戶留存率</span><span class="sxs-lookup"><span data-stu-id="f3d22-124">Azure subscription retention</span></span>**  
 - <span data-ttu-id="f3d22-125">已續約的訂閱數目。</span><span class="sxs-lookup"><span data-stu-id="f3d22-125">The number of subscriptions that were renewed.</span></span>   
  