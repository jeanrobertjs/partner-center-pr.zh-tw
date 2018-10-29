---
title: 調整 Microsoft Azure VM 大小以提供最大保留區使用率 |合作夥伴中心
ms.topic: article
ms.date: 10/29/2018
Description: Information on purchasing and managing Azure reservations
author: v-petand
ms.author: v-petand
keywords: azure, 保留區, vm, 管理, 使用率, 調整大小
ms.localizationpriority: medium
ms.openlocfilehash: 00978e8e000dded2e4f7bb5d5d6506711e521c86
ms.sourcegitcommit: ed22f6825d3af1d19385198b4d511e4b39d5e353
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 10/29/2018
ms.locfileid: "5795921"
---
# <a name="microsoft-azure-vm-sizing-for-maximum-reservation-usage"></a><span data-ttu-id="fbf7e-103">調整 Microsoft Azure VM 大小以提供最大保留區使用率</span><span class="sxs-lookup"><span data-stu-id="fbf7e-103">Microsoft Azure VM sizing for maximum reservation usage</span></span> 

**<span data-ttu-id="fbf7e-104">適用對象：</span><span class="sxs-lookup"><span data-stu-id="fbf7e-104">Applies to</span></span>**

-  <span data-ttu-id="fbf7e-105">合作夥伴中心</span><span class="sxs-lookup"><span data-stu-id="fbf7e-105">Partner Center</span></span>
-  <span data-ttu-id="fbf7e-106">Azure 入口網站</span><span class="sxs-lookup"><span data-stu-id="fbf7e-106">Azure portal</span></span>
-  <span data-ttu-id="fbf7e-107">雲端解決方案提供者中的合作夥伴</span><span class="sxs-lookup"><span data-stu-id="fbf7e-107">Partners in CSP</span></span>

## <a name="determine-the-vm-size-for-a-customers-azure-reservation"></a><span data-ttu-id="fbf7e-108">判斷客戶 Azure Reservations 的 VM 大小</span><span class="sxs-lookup"><span data-stu-id="fbf7e-108">Determine the VM size for a customer’s Azure reservation</span></span> 

<span data-ttu-id="fbf7e-109">代表您的客戶購買 Microsoft Azure Reservations 時，您需要選擇符合客戶運算需求的虛擬機器 (VM) 大小。</span><span class="sxs-lookup"><span data-stu-id="fbf7e-109">When buying Microsoft Azure reservations on behalf of your customers, you’ll need to choose a virtual machine (VM) sized to meet the customer’s computing needs.</span></span> <span data-ttu-id="fbf7e-110">您可以使用下列其中一個方法來找到此項資訊：</span><span class="sxs-lookup"><span data-stu-id="fbf7e-110">You can find this information using one of these methods:</span></span>

-   <span data-ttu-id="fbf7e-111">Azure 使用量 API</span><span class="sxs-lookup"><span data-stu-id="fbf7e-111">Azure utilization API</span></span>
-   <span data-ttu-id="fbf7e-112">Azure 入口網站</span><span class="sxs-lookup"><span data-stu-id="fbf7e-112">The Azure portal</span></span>
-   <span data-ttu-id="fbf7e-113">Azure PowerShell</span><span class="sxs-lookup"><span data-stu-id="fbf7e-113">Azure PowerShell</span></span>
-   <span data-ttu-id="fbf7e-114">Azure Resource Manager (ARM) API</span><span class="sxs-lookup"><span data-stu-id="fbf7e-114">The Azure Resource Manager (ARM) API</span></span>

<span data-ttu-id="fbf7e-115">以下列出使用每種方法的指示。</span><span class="sxs-lookup"><span data-stu-id="fbf7e-115">Instructions for using each of these methods are below.</span></span> <span data-ttu-id="fbf7e-116">購買保留區之後，保留區折扣會自動套用到符合保留區屬性和數量的虛擬機器。</span><span class="sxs-lookup"><span data-stu-id="fbf7e-116">After you buy a reservation, the reservation discount is applied automatically to virtual machines matching the attributes and quantity of the reservation.</span></span> <span data-ttu-id="fbf7e-117">您不需要指派保留區給 VM。</span><span class="sxs-lookup"><span data-stu-id="fbf7e-117">You don’t need to assign the reservation to a VM.</span></span>

>[!NOTE]
><span data-ttu-id="fbf7e-118">保留區折扣不適用於傳統或促銷 VM。</span><span class="sxs-lookup"><span data-stu-id="fbf7e-118">Reservation discounts don’t apply to classic or promotional VMs.</span></span>

>[!IMPORTANT]
><span data-ttu-id="fbf7e-119">若要正確找出代表您客戶購買的 VM 大小和類型，您必須使用以下所述的其中一種方法，因為合作夥伴中心對帳檔案不會正確顯示 VM 系列類型。</span><span class="sxs-lookup"><span data-stu-id="fbf7e-119">To correctly identify the type and size of VM to buy on behalf of your customer, you must use one of the methods described below as the VM series type is not correctly displayed in Partner Center reconciliation files.</span></span>


**<span data-ttu-id="fbf7e-120">使用 Azure 使用量 API，取得 VM 大小調整資訊</span><span class="sxs-lookup"><span data-stu-id="fbf7e-120">Get VM sizing information using the Azure utilization API</span></span>**

1.  <span data-ttu-id="fbf7e-121">使用 API 回應中 additionalInfo 的 ServiceType 屬性值，找出要購買的 VM 大小。</span><span class="sxs-lookup"><span data-stu-id="fbf7e-121">Use the value for ServiceType attribute from additionalInfo in the API response to identify the VM size to buy.</span></span> 

2.  <span data-ttu-id="fbf7e-122">如需詳細資訊，請參閱[合作夥伴中心 API](https://docs.microsoft.com/partner-center/develop/) 中的[取得客戶的 Azure 使用率記錄](https://docs.microsoft.com/partner-center/develop/get-a-customer-s-utilization-record-for-azure) (英文)。</span><span class="sxs-lookup"><span data-stu-id="fbf7e-122">For more information, see [Get a customer’s utilization records for Azure](https://docs.microsoft.com/partner-center/develop/get-a-customer-s-utilization-record-for-azure) in the [Partner Center API](https://docs.microsoft.com/partner-center/develop/).</span></span> 

**<span data-ttu-id="fbf7e-123">使用 Microsoft Azure 入口網站，取得 VM 大小調整資訊</span><span class="sxs-lookup"><span data-stu-id="fbf7e-123">Get VM sizing information using the Microsoft Azure portal</span></span>**

1.  <span data-ttu-id="fbf7e-124">在合作夥伴中心，移至**客戶**\] 頁面。</span><span class="sxs-lookup"><span data-stu-id="fbf7e-124">In Partner Center, go to your **Customers** page.</span></span>

2.  <span data-ttu-id="fbf7e-125">尋找想要購買 Azure VM 保留區的客戶，然後選取向下箭號來展開客戶資訊。</span><span class="sxs-lookup"><span data-stu-id="fbf7e-125">Find the customer who wants to buy Azure VM reservations and then select the down arrow to expand the customer’s information.</span></span> <span data-ttu-id="fbf7e-126">選取 **\[Microsoft Azure 管理入口網站\]** 以在 Azure 入口網站中開啟客戶記錄。</span><span class="sxs-lookup"><span data-stu-id="fbf7e-126">Select **Microsoft Azure Management Portal** to open the customer’s record in the Azure portal.</span></span> 

3.  <span data-ttu-id="fbf7e-127">從入口網站功能表選取 **\[虛擬機器\]**，然後選取您要購買保留區的 VM。</span><span class="sxs-lookup"><span data-stu-id="fbf7e-127">Select **Virtual machines** from the portal menu and then select the VM for which you want to buy a reservation.</span></span> 

4.  <span data-ttu-id="fbf7e-128">在 VM 的詳細資料頁面上，尋找大小及地區資訊 (如下所示)，並使用此資訊在合作夥伴中心中購買保留區。</span><span class="sxs-lookup"><span data-stu-id="fbf7e-128">On the VM’s detail page, find the size and region information, as illustrated below, and use this information to purchase the reservation in Partner Center.</span></span>  

    ![](images/usage1.png)

**<span data-ttu-id="fbf7e-129">使用 Microsoft Azure PowerShell 取得 VM 大小調整資訊</span><span class="sxs-lookup"><span data-stu-id="fbf7e-129">Get VM sizing information using Microsoft Azure PowerShell</span></span>**

<span data-ttu-id="fbf7e-130">使用下列影像中的資訊，取得您要購買保留區的 VM 大小與位置。</span><span class="sxs-lookup"><span data-stu-id="fbf7e-130">Use the information in the image below to get the location and size of the VM for which you want to buy a reservation.</span></span> 

![](images/usage2.png)

**<span data-ttu-id="fbf7e-131">使用 Azure Resource Manager (ARM) API 取得 VM 大小調整資訊</span><span class="sxs-lookup"><span data-stu-id="fbf7e-131">Get VM sizing information using the Azure Resource Manager (ARM) API</span></span>**

1.  <span data-ttu-id="fbf7e-132">使用 ARMClient 或 ARM API，呼叫您要購買保留區之 VM 的 ARM 用戶端。</span><span class="sxs-lookup"><span data-stu-id="fbf7e-132">Using the ARMClient or the ARM APIs, call the ARM client for the VM for which you want to buy a reservation.</span></span>

2.  <span data-ttu-id="fbf7e-133">/subscriptions/<Subscription ID>/resourceGroups/<Resource group name>/providers/Microsoft.Compute/virtualMachines/<VM Instance Name>?api-version=2017-12-01</span><span class="sxs-lookup"><span data-stu-id="fbf7e-133">/subscriptions/<Subscription ID>/resourceGroups/<Resource group name>/providers/Microsoft.Compute/virtualMachines/<VM Instance Name>?api-version=2017-12-01</span></span>

3.  <span data-ttu-id="fbf7e-134">呼叫會傳回 **vmSize** 和 **location** 的值，如下所示。</span><span class="sxs-lookup"><span data-stu-id="fbf7e-134">The call returns the values for **vmSize** and **location**, as illustrated below.</span></span>

    ![](images/usage3.png)
    ![](images/usage4.png)
 

## <a name="verify-azure-vm-usage-and-reservation-discount"></a><span data-ttu-id="fbf7e-135">確認 Azure VM 使用率與保留區折扣</span><span class="sxs-lookup"><span data-stu-id="fbf7e-135">Verify Azure VM usage and reservation discount</span></span>

<span data-ttu-id="fbf7e-136">代表客戶購買 Azure 保留的 VM 執行個體後，預先支付 VM 空間的折扣會自動套用到符合客戶保留區屬性和數量的虛擬機器。</span><span class="sxs-lookup"><span data-stu-id="fbf7e-136">After you purchase an Azure Reserved VM Instance on behalf of a customer, the discount for paying for VM space in advance is automatically applied to the virtual machines that match the attributes and quantity of the customer’s reservation.</span></span> 

<span data-ttu-id="fbf7e-137">您可以使用下列其中一項方法，確認客戶的保留區使用率，並查看適用於保留區折扣的虛擬機器：</span><span class="sxs-lookup"><span data-stu-id="fbf7e-137">You can verify the customer’s reservation usage and see which virtual machines the reservation discounts are applied to by using one of the following methods:</span></span>   

-   <span data-ttu-id="fbf7e-138">Azure 入口網站</span><span class="sxs-lookup"><span data-stu-id="fbf7e-138">The Azure portal</span></span>
-   <span data-ttu-id="fbf7e-139">Azure 使用量 API</span><span class="sxs-lookup"><span data-stu-id="fbf7e-139">Azure utilization API</span></span>

<span data-ttu-id="fbf7e-140">以下列出使用每種方法的指示。</span><span class="sxs-lookup"><span data-stu-id="fbf7e-140">Instructions for using each of these methods are below.</span></span>

>[!NOTE]
><span data-ttu-id="fbf7e-141">只有 Azure 使用量 API 會顯示折扣套用的虛擬機器。</span><span class="sxs-lookup"><span data-stu-id="fbf7e-141">Only the Azure utilization API shows which virtual machine the discount is being applied to.</span></span>  

### <a name="verify-the-customers-reservation-usage-in-the-microsoft-azure-portal"></a><span data-ttu-id="fbf7e-142">在 Microsoft Azure 入口網站中確認客戶的保留區使用率</span><span class="sxs-lookup"><span data-stu-id="fbf7e-142">Verify the customer’s reservation usage in the Microsoft Azure portal</span></span>

1.  <span data-ttu-id="fbf7e-143">在合作夥伴中心，移至**客戶**\] 頁面。</span><span class="sxs-lookup"><span data-stu-id="fbf7e-143">In Partner Center, go to your **Customers** page.</span></span>

2.  <span data-ttu-id="fbf7e-144">尋找您要確認其保留區折扣和使用率的客戶，然後選取向下箭號來展開客戶資訊。</span><span class="sxs-lookup"><span data-stu-id="fbf7e-144">Find the customer whose reservation discount and usage you want to verify and then select the down arrow to expand the customer’s information.</span></span> <span data-ttu-id="fbf7e-145">選取 **\[Microsoft Azure 管理入口網站\]** 以在 Azure 入口網站中開啟客戶記錄。</span><span class="sxs-lookup"><span data-stu-id="fbf7e-145">Select **Microsoft Azure Management Portal** to open the customer’s record in the Azure portal.</span></span> 

3.  <span data-ttu-id="fbf7e-146">從入口網站功能表選取 **\[保留區\]**，然後選取您要查看其使用率的保留區。</span><span class="sxs-lookup"><span data-stu-id="fbf7e-146">Select **Reservations** from the portal menu and then select the reservation you want to check usage for.</span></span> 

4.  <span data-ttu-id="fbf7e-147">在 **\[概觀\]** 頁面上檢查保留區的使用率圖形，其中會顯示多少保留區已套用到虛擬機器。</span><span class="sxs-lookup"><span data-stu-id="fbf7e-147">On the **Overview** page check the reservation’s utilization graph, which shows how much of the reservation was applied to virtual machines.</span></span> 

    >[!NOTE]
    ><span data-ttu-id="fbf7e-148">使用率資料可能會延遲最多 8 小時。</span><span class="sxs-lookup"><span data-stu-id="fbf7e-148">Utilization data may be delayed by up to 8 hours.</span></span>
    
    <span data-ttu-id="fbf7e-149">a.</span><span class="sxs-lookup"><span data-stu-id="fbf7e-149">a.</span></span>  <span data-ttu-id="fbf7e-150">如果保留區使用率是 100%，表示您的客戶已獲得保留區購買可提供的所有可能節省情形。</span><span class="sxs-lookup"><span data-stu-id="fbf7e-150">If the reservation’s utilization is 100%, your customer is getting all the possible savings that the reservation purchase can provide.</span></span> 
    
    <span data-ttu-id="fbf7e-151">b。</span><span class="sxs-lookup"><span data-stu-id="fbf7e-151">b.</span></span>  <span data-ttu-id="fbf7e-152">如果保留區使用率是 0%，表示折扣不適用於任何虛擬機器。</span><span class="sxs-lookup"><span data-stu-id="fbf7e-152">If the reservation’s usage is 0%, the discount is not being applied to any virtual machine.</span></span> 
    
    <span data-ttu-id="fbf7e-153">c.</span><span class="sxs-lookup"><span data-stu-id="fbf7e-153">c.</span></span>  <span data-ttu-id="fbf7e-154">如果保留區使用率介於 1% 和 99% 之間，表示有未使用的權益。</span><span class="sxs-lookup"><span data-stu-id="fbf7e-154">If the reservation’s usage is between 1% and 99%, there are unused benefits.</span></span> 

5.  <span data-ttu-id="fbf7e-155">若要避免發生這種情形，請在購買之前正確判斷支援客戶運算需求的 VM 大小。</span><span class="sxs-lookup"><span data-stu-id="fbf7e-155">To avoid this situation, determine the correct size VM to support the customer’s computing needs before making the purchase.</span></span>

### <a name="verify-the-customers-reservation-usage-with-the-azure-utilization-api"></a><span data-ttu-id="fbf7e-156">使用 Azure 使用量 API 確認客戶的保留區使用率</span><span class="sxs-lookup"><span data-stu-id="fbf7e-156">Verify the customer’s reservation usage with the Azure utilization API</span></span>

>[!NOTE]
><span data-ttu-id="fbf7e-157">只有 Azure 使用量 API 會顯示折扣套用的虛擬機器。</span><span class="sxs-lookup"><span data-stu-id="fbf7e-157">Only the Azure utilization API shows which virtual machine the discount is being applied to.</span></span>  

<span data-ttu-id="fbf7e-158">您可以使用 Azure 使用量 API 取得保留區使用率資料，來確認客戶獲得保留區折扣，並查看折扣套用到那些 VM (虛擬機器)。</span><span class="sxs-lookup"><span data-stu-id="fbf7e-158">You can get reservation usage data with the Azure utilization API to verify that the customer is getting the reservation discount and to see which VMs (virtual machines) the discount is applied to.</span></span> <span data-ttu-id="fbf7e-159">比較範例 A 和範例 B，了解如何確認客戶的保留區使用率。</span><span class="sxs-lookup"><span data-stu-id="fbf7e-159">Compare Example A to Example B to see how to verify a customer’s reservation usage.</span></span> 

![](images\usage5.png)

-   <span data-ttu-id="fbf7e-160">ReservationId 可識別用於套用折扣至 VM 的 Azure 保留區。</span><span class="sxs-lookup"><span data-stu-id="fbf7e-160">The reservationId identifies the Azure reservation that was used to apply the discount to the VM.</span></span>
-   <span data-ttu-id="fbf7e-161">consumptionMeter 是已套用保留區折扣之 VM 的 MeterId。</span><span class="sxs-lookup"><span data-stu-id="fbf7e-161">consumptionMeter is the MeterId for the VM that has the reservation discount applied to it.</span></span>
-   <span data-ttu-id="fbf7e-162">由於已套用保留區折扣，所以 ReservationMeter 會顯示 $0 費用。</span><span class="sxs-lookup"><span data-stu-id="fbf7e-162">The ReservationMeter shows $0 cost since the reservation discount was applied.</span></span> 

<span data-ttu-id="fbf7e-163">如需詳細資訊，請參閱[合作夥伴中心 API](https://docs.microsoft.com/partner-center/develop/) 中的[取得客戶的 Azure 使用率記錄](https://docs.microsoft.com/partner-center/develop/get-a-customer-s-utilization-record-for-azure) (英文)。</span><span class="sxs-lookup"><span data-stu-id="fbf7e-163">For more information, see [Get a customer’s utilization records for Azure](https://docs.microsoft.com/partner-center/develop/get-a-customer-s-utilization-record-for-azure) in the [Partner Center API](https://docs.microsoft.com/partner-center/develop/).</span></span>

>[!IMPORTANT]
><span data-ttu-id="fbf7e-164">軟體成本 (例如 Microsoft Windows Server) 目前不包含在 VM 保留區的價格中，並會在訂單記錄和發票中顯示為不同的一行項目。</span><span class="sxs-lookup"><span data-stu-id="fbf7e-164">Software costs, such as Microsoft Windows Server, are not currently included in the price of a VM reservation and will appear as separate line items in the order record and on your invoice.</span></span> <span data-ttu-id="fbf7e-165">不過，如果客戶擁有 Azure Hybrid Use Benefit，將不會套用軟體成本。</span><span class="sxs-lookup"><span data-stu-id="fbf7e-165">However, if a customer has the Azure Hybrid Use Benefit, the software costs will not be applied.</span></span> <span data-ttu-id="fbf7e-166">如需詳細資訊，請參閱 [Windows 軟體的成本不包括在保留執行個體內](https://docs.microsoft.com/azure/billing/billing-reserved-instance-windows-software-costs)。</span><span class="sxs-lookup"><span data-stu-id="fbf7e-166">For more information, see [Windows software costs not included with Reserved Instances](https://docs.microsoft.com/azure/billing/billing-reserved-instance-windows-software-costs).</span></span>  

## <a name="azure-reservations-resources"></a><span data-ttu-id="fbf7e-167">Azure Reservations 資源</span><span class="sxs-lookup"><span data-stu-id="fbf7e-167">Azure reservations resources</span></span>
|**<span data-ttu-id="fbf7e-168">如需以下相關資訊</span><span class="sxs-lookup"><span data-stu-id="fbf7e-168">For information about</span></span>**   |**<span data-ttu-id="fbf7e-169">請閱讀本文</span><span class="sxs-lookup"><span data-stu-id="fbf7e-169">Read this</span></span>**    |
|:-----------------------------|:-----------------|
|<span data-ttu-id="fbf7e-170">雲端解決方案提供者中的 Azure Reservations 概觀</span><span class="sxs-lookup"><span data-stu-id="fbf7e-170">Azure reservations in CSP overview</span></span>  | [<span data-ttu-id="fbf7e-171">銷售 Microsoft Azure 保留的 VM 執行個體</span><span class="sxs-lookup"><span data-stu-id="fbf7e-171">Sell Microsoft Azure Reserved VM Instances</span></span>](azure-reservations.md)
|<span data-ttu-id="fbf7e-172">為您在合作夥伴中心的客戶購買 Azure reservations</span><span class="sxs-lookup"><span data-stu-id="fbf7e-172">Purchasing Azure reservations for your customers in Partner Center</span></span>   |[<span data-ttu-id="fbf7e-173">購買 Azure Reservations</span><span class="sxs-lookup"><span data-stu-id="fbf7e-173">Buy Azure reservations</span></span>](azure-reservations-buying.md)
| <span data-ttu-id="fbf7e-174">管理 Azure reservations，在合作夥伴中心</span><span class="sxs-lookup"><span data-stu-id="fbf7e-174">Managing Azure reservations in Partner Center</span></span> | [<span data-ttu-id="fbf7e-175">管理 Azure reservations，在合作夥伴中心</span><span class="sxs-lookup"><span data-stu-id="fbf7e-175">Managing Azure reservations in Partner Center</span></span>](azure-reservations-manage.md)
|<span data-ttu-id="fbf7e-176">在 Azure 入口網站中購買 Azure Reservations</span><span class="sxs-lookup"><span data-stu-id="fbf7e-176">Purchasing Azure reservations in the Azure portal</span></span> | <span data-ttu-id="fbf7e-177">Azure 說明中的[預付具有 Azure 保留的 VM 執行個體的虛擬機器](https://docs.microsoft.com/azure/virtual-machines/windows/prepay-reserved-vm-instances)</span><span class="sxs-lookup"><span data-stu-id="fbf7e-177">[Prepay for virtual machines with Azure Reserved VM Instances](https://docs.microsoft.com/azure/virtual-machines/windows/prepay-reserved-vm-instances) in the Azure Help</span></span> |
|<span data-ttu-id="fbf7e-178">在 Azure 入口網站中管理 Azure Reservations</span><span class="sxs-lookup"><span data-stu-id="fbf7e-178">Managing Azure reservations in the Azure portal</span></span>   |<span data-ttu-id="fbf7e-179">Azure 說明中的[管理保留的 VM 執行個體](https://docs.microsoft.com/azure/billing/billing-manage-reserved-vm-instance)</span><span class="sxs-lookup"><span data-stu-id="fbf7e-179">[Manage reserved VM instances](https://docs.microsoft.com/azure/billing/billing-manage-reserved-vm-instance) in the Azure Help</span></span>  |
|<span data-ttu-id="fbf7e-180">使用合作夥伴中心 API 購買 Azure Reservations</span><span class="sxs-lookup"><span data-stu-id="fbf7e-180">Purchasing Azure reservations using the Partner Center API</span></span> | <span data-ttu-id="fbf7e-181">合作夥伴中心開發人員文件中的[購買 Azure 保留的 VM 執行個體](https://docs.microsoft.com/partner-center/develop/purchase-azure-reservations)</span><span class="sxs-lookup"><span data-stu-id="fbf7e-181">[Purchase Azure Reserved VM Instances](https://docs.microsoft.com/partner-center/develop/purchase-azure-reservations) in the Partner Center developer documentation</span></span>



