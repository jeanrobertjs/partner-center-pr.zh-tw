---
title: 自訂裝置的現成的體驗，使用 Windows Autopilot 設定檔 |合作夥伴中心
description: 預先設定裝置的 Autopilot 設定檔的全新體驗。
ms.topic: article
ms.date: 02/06/19
author: maggiepuccievans
ms.author: evansma
keywords: autopilot，windows autopilot，microsoft autopilot，全自動部署、 oobe、 登入畫面，現成的
ms.localizationpriority: medium
ms.openlocfilehash: d563ad09d1fa3b67b01835480a348a524455efbc
ms.sourcegitcommit: f1c269f4ac52d5206d65d9585855da309f0aae8a
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 02/20/2019
ms.locfileid: "9083401"
---
# <a name="customize-a-devices-out-of-box-experience-with-windows-autopilot-profiles"></a><span data-ttu-id="ff11a-104">自訂裝置的現成的體驗，使用 Windows Autopilot 設定檔設定</span><span class="sxs-lookup"><span data-stu-id="ff11a-104">Customize a device's out-of-box experience with Windows Autopilot profiles</span></span>

**<span data-ttu-id="ff11a-105">適用對象：</span><span class="sxs-lookup"><span data-stu-id="ff11a-105">Applies to</span></span>**

- <span data-ttu-id="ff11a-106">雲端解決方案提供者直接帳單合作夥伴，間接提供者和間接經銷商</span><span class="sxs-lookup"><span data-stu-id="ff11a-106">CSP direct-bill partners, indirect providers, and indirect resellers</span></span>

<span data-ttu-id="ff11a-107">如果您管理客戶的裝置，您可能需要自訂客戶的使用者的全新體驗 (OOBE)。</span><span class="sxs-lookup"><span data-stu-id="ff11a-107">If you manage customer devices, you may need to customize the out-of-box experience (OOBE) for the customer's users.</span></span> <span data-ttu-id="ff11a-108">您可以預先設定新裝置與 Windows Autopilot 設定檔，再傳遞給客戶的裝置，並將新的設定檔套用至已經購買客戶的裝置。</span><span class="sxs-lookup"><span data-stu-id="ff11a-108">You can pre-configure new devices with Windows Autopilot profiles before delivering the devices to customers and apply new profiles to devices customers have already purchased.</span></span> <span data-ttu-id="ff11a-109">這篇文章說明如何建立和套用 Autopilot 設定檔到合作夥伴中心中的裝置。</span><span class="sxs-lookup"><span data-stu-id="ff11a-109">This article explains how to create and apply Autopilot profiles to devices in Partner Center.</span></span>

<span data-ttu-id="ff11a-110">如果您已經不熟悉 Autopilot，檢閱這些文章中的資訊：</span><span class="sxs-lookup"><span data-stu-id="ff11a-110">If you're not already familiar with Autopilot, review the information in these articles:</span></span>

- [<span data-ttu-id="ff11a-111">Windows Autopilot 概觀</span><span class="sxs-lookup"><span data-stu-id="ff11a-111">Overview of Windows Autopilot</span></span>](https://docs.microsoft.com/windows/deployment/windows-10-auto-pilot)
- [<span data-ttu-id="ff11a-112">Autopilot 部署參考指南</span><span class="sxs-lookup"><span data-stu-id="ff11a-112">Autopilot deployment reference guide</span></span>](http://assetsprod.microsoft.com/autopilot-deployment-program-reference-guide-csp.docx)  

## <a name="overview"></a><span data-ttu-id="ff11a-113">概觀</span><span class="sxs-lookup"><span data-stu-id="ff11a-113">Overview</span></span>

<span data-ttu-id="ff11a-114">透過 Windows Autopilot 功能，在合作夥伴中心，您可以建立自訂的設定檔套用到客戶的裝置。</span><span class="sxs-lookup"><span data-stu-id="ff11a-114">With the Windows Autopilot feature in Partner Center, you can create custom profiles to apply to customer devices.</span></span> <span data-ttu-id="ff11a-115">下列的設定檔設定可供在這篇文章發行的時：</span><span class="sxs-lookup"><span data-stu-id="ff11a-115">The following profile settings were available at the time this article was published:</span></span>

- <span data-ttu-id="ff11a-116">略過隱私權設定。</span><span class="sxs-lookup"><span data-stu-id="ff11a-116">Skip privacy settings.</span></span> <span data-ttu-id="ff11a-117">這個選用的 Autopilot 設定檔設定可讓組織不會詢問在 OOBE 程序的隱私權設定。</span><span class="sxs-lookup"><span data-stu-id="ff11a-117">This optional Autopilot profile setting enables organizations to not ask about privacy settings during the OOBE process.</span></span>

- <span data-ttu-id="ff11a-118">停用在裝置上的建立本機系統管理員帳戶。</span><span class="sxs-lookup"><span data-stu-id="ff11a-118">Disable local admin account creation on the device.</span></span> <span data-ttu-id="ff11a-119">組織可以決定程序完成之後，設定裝置的使用者是否應該有系統管理員存取權。</span><span class="sxs-lookup"><span data-stu-id="ff11a-119">Organizations can decide whether the user setting up the device should have administrator access once the process is complete.</span></span>

- <span data-ttu-id="ff11a-120">自動設定公司或學校的裝置。</span><span class="sxs-lookup"><span data-stu-id="ff11a-120">Automatically set up device for work or school.</span></span> <span data-ttu-id="ff11a-121">以 Autopilot 註冊的所有裝置自動將會視為公司或學校的裝置，因此此問題不會要求在 OOBE 程序。</span><span class="sxs-lookup"><span data-stu-id="ff11a-121">All devices registered with Autopilot will automatically be considered work or school devices, so this question will not be asked during the OOBE process.</span></span>

- <span data-ttu-id="ff11a-122">略過 Cortana、 OneDrive 及 OEM 註冊設定頁面。</span><span class="sxs-lookup"><span data-stu-id="ff11a-122">Skip Cortana, OneDrive, and OEM registration setup pages.</span></span> <span data-ttu-id="ff11a-123">以 Autopilot 註冊的所有裝置將會自動略都過這些頁面的全新體驗 (OOBE) 程序期間。</span><span class="sxs-lookup"><span data-stu-id="ff11a-123">All devices registered with Autopilot will automatically skip these pages during the out-of-box experience (OOBE) process.</span></span>

- <span data-ttu-id="ff11a-124">略過使用者授權合約 (EULA)。</span><span class="sxs-lookup"><span data-stu-id="ff11a-124">Skip End User License Agreement (EULA).</span></span> <span data-ttu-id="ff11a-125">從 Windows 10 版本 1709年開始，組織可以略過 OOBE 程序期間所呈現的使用者授權合約頁面決定。</span><span class="sxs-lookup"><span data-stu-id="ff11a-125">Starting in Windows 10 version 1709, organizations can decide to skip the EULA page presented during the OOBE process.</span></span> <span data-ttu-id="ff11a-126">請參閱[Windows Autopilot EULA 關閉](#windows-autopilot-eula-dismissal)下方的重要資訊考慮關於略過使用者授權合約頁面，在 Windows 安裝期間。</span><span class="sxs-lookup"><span data-stu-id="ff11a-126">See [Windows Autopilot EULA dismissal](#windows-autopilot-eula-dismissal) below for important information to consider about skipping the EULA page during Windows setup.</span></span>

<span data-ttu-id="ff11a-127">下列的設定檔和裝置管理權限和限制套用：</span><span class="sxs-lookup"><span data-stu-id="ff11a-127">The following profile and device management permissions and limitations apply:</span></span>

- <span data-ttu-id="ff11a-128">雲端解決方案提供者合作夥伴可以繼續管理與他們有經銷商關係的現有客戶的 Autopilot 設定檔，即使客戶已移除合作夥伴的委派的系統管理權限。</span><span class="sxs-lookup"><span data-stu-id="ff11a-128">CSP partners can continue to manage Autopilot profiles for existing customers with whom they have reseller relationships, even if the customers have removed the partner's delegated administration privileges.</span></span>

- <span data-ttu-id="ff11a-129">您可以為您已新增由您或其他雲端解決方案提供者合作夥伴的客戶管理現有的裝置。</span><span class="sxs-lookup"><span data-stu-id="ff11a-129">You can manage existing devices for your customers that have been added either by you or by another CSP partner.</span></span>

- <span data-ttu-id="ff11a-130">您無法管理客戶上傳到商務用 Microsoft Store 或 Microsoft Intune 入口網站的裝置。</span><span class="sxs-lookup"><span data-stu-id="ff11a-130">You can’t manage devices your customer has uploaded to Microsoft Store for Business or the Microsoft Intune Portal.</span></span>

## <a name="create-and-manage-autopilot-profiles-in-partner-center"></a><span data-ttu-id="ff11a-131">建立和管理 Autopilot 設定檔，在合作夥伴中心</span><span class="sxs-lookup"><span data-stu-id="ff11a-131">Create and manage Autopilot profiles in Partner Center</span></span>

<span data-ttu-id="ff11a-132">在合作夥伴中心，您可以建立 Windows Autopilot 部署設定檔，並將其套用至裝置。</span><span class="sxs-lookup"><span data-stu-id="ff11a-132">In Partner Center, you can create Windows Autopilot deployment profiles and apply them to devices.</span></span>

>[!NOTE]
><span data-ttu-id="ff11a-133">只有系統管理代理人可以建立和套用設定檔。</span><span class="sxs-lookup"><span data-stu-id="ff11a-133">Only admin agents can create and apply profiles.</span></span>

### <a name="create-a-new-autopilot-profile"></a><span data-ttu-id="ff11a-134">建立新的 Autopilot 設定檔</span><span class="sxs-lookup"><span data-stu-id="ff11a-134">Create a new Autopilot profile</span></span>

1. <span data-ttu-id="ff11a-135">從合作夥伴中心功能表中選取**客戶**，然後選取您要建立的 Autopilot 設定檔的客戶。</span><span class="sxs-lookup"><span data-stu-id="ff11a-135">Select **Customers** from the Partner Center menu and then select the customer you're creating the Autopilot profile for.</span></span>

2. <span data-ttu-id="ff11a-136">客戶的詳細資料頁面上，選取**裝置**。</span><span class="sxs-lookup"><span data-stu-id="ff11a-136">On the customer's detail page, select **Devices**.</span></span>

3. <span data-ttu-id="ff11a-137">**Windows Autopilot 設定檔**底下選取 [**加入新的設定檔**。</span><span class="sxs-lookup"><span data-stu-id="ff11a-137">Under **Windows Autopilot profiles** select **Add new profile**.</span></span>

4. <span data-ttu-id="ff11a-138">輸入設定檔的名稱和描述，然後設定 [OOBE 設定。</span><span class="sxs-lookup"><span data-stu-id="ff11a-138">Enter the profile's name and description and then configure the OOBE settings.</span></span> <span data-ttu-id="ff11a-139">選擇：</span><span class="sxs-lookup"><span data-stu-id="ff11a-139">Choose from:</span></span>  

   - <span data-ttu-id="ff11a-140">略過設定中的隱私權設定</span><span class="sxs-lookup"><span data-stu-id="ff11a-140">Skip privacy settings in setup</span></span>

   - <span data-ttu-id="ff11a-141">停用設定中的本機系統管理員帳戶</span><span class="sxs-lookup"><span data-stu-id="ff11a-141">Disable local admin account in setup</span></span>
  
   - <span data-ttu-id="ff11a-142">自動略過設定中的頁面</span><span class="sxs-lookup"><span data-stu-id="ff11a-142">Automatically skip pages in setup</span></span><br>
        <span data-ttu-id="ff11a-143">（包括*自動選取公司或學校的設定*和*略過 Cortana、 OneDrive 及 OEM 註冊設定頁面*）</span><span class="sxs-lookup"><span data-stu-id="ff11a-143">(Includes *Automatically select setup for work or school* and *Skip Cortana, OneDrive, and OEM registration setup pages*)</span></span>
  
   - <span data-ttu-id="ff11a-144">略過使用者授權合約 (EULA)</span><span class="sxs-lookup"><span data-stu-id="ff11a-144">Skip end user license agreement (EULA)</span></span><br> 
       >[!IMPORTANT] 
       ><span data-ttu-id="ff11a-145">請參閱[Windows Autopilot EULA 關閉](#windows-autopilot-eula-dismissal)下方的重要資訊考慮關於略過使用者授權合約頁面，在 Windows 安裝期間。</span><span class="sxs-lookup"><span data-stu-id="ff11a-145">See [Windows Autopilot EULA dismissal](#windows-autopilot-eula-dismissal) below for important information to consider about skipping the EULA page during Windows setup.</span></span>

5. <span data-ttu-id="ff11a-146">完成時選取 **\[提交\]**。</span><span class="sxs-lookup"><span data-stu-id="ff11a-146">Select **Submit** when finished.</span></span>

### <a name="apply-an-autopilot-profile-to-customer-devices"></a><span data-ttu-id="ff11a-147">適用於客戶裝置的 Autopilot 設定檔</span><span class="sxs-lookup"><span data-stu-id="ff11a-147">Apply an Autopilot profile to customer devices</span></span>

>[!NOTE]
><span data-ttu-id="ff11a-148">下面的指示假設您已經到合作夥伴中心新增客戶的裝置，而且您可以存取他們的裝置清單。</span><span class="sxs-lookup"><span data-stu-id="ff11a-148">The instructions below assume that you've already added the customer's devices to Partner Center and that you can access their device list.</span></span> <span data-ttu-id="ff11a-149">如果您還沒有新增客戶的裝置，依照[新增裝置至客戶帳戶](#add-devices-to-a-customers-account)中的指示，則請依照下列步驟。</span><span class="sxs-lookup"><span data-stu-id="ff11a-149">If you haven't already added the customer's devices, follow the instructions in [Add devices to a customer's account](#add-devices-to-a-customers-account) and then follow the steps below.</span></span>

<span data-ttu-id="ff11a-150">為客戶建立 Autopilot 設定檔之後，您可以將它套用到客戶的裝置。</span><span class="sxs-lookup"><span data-stu-id="ff11a-150">After you create an Autopilot profile for a customer, you can apply it to the customer's devices.</span></span>

1. <span data-ttu-id="ff11a-151">從合作夥伴中心功能表中選取**客戶**，然後選取您建立的 Autopilot 設定檔的客戶。</span><span class="sxs-lookup"><span data-stu-id="ff11a-151">Select **Customers** from the Partner Center menu and then select the customer you created the Autopilot profile for.</span></span>

2. <span data-ttu-id="ff11a-152">客戶的詳細資料頁面上，選取**裝置**。</span><span class="sxs-lookup"><span data-stu-id="ff11a-152">On the customer's detail page, select **Devices**.</span></span>

3. <span data-ttu-id="ff11a-153">在**套用到裝置的設定檔**選取裝置或您想要新增至設定檔，然後選取 [**套用設定檔**的裝置群組。</span><span class="sxs-lookup"><span data-stu-id="ff11a-153">Under **Apply profiles to devices** select the devices or device groups you want to add profiles to and then select **Apply profile**.</span></span> <span data-ttu-id="ff11a-154">您套用的設定檔會出現在**設定檔**] 欄中。</span><span class="sxs-lookup"><span data-stu-id="ff11a-154">The profile you just applied appears in the **Profile** column.</span></span>

4. <span data-ttu-id="ff11a-155">請依照下列步驟來驗證設定檔將會成功套用到裝置。</span><span class="sxs-lookup"><span data-stu-id="ff11a-155">Follow the steps below to verify that the profile will be applied successfully to the device.</span></span>

    <span data-ttu-id="ff11a-156">a.</span><span class="sxs-lookup"><span data-stu-id="ff11a-156">a.</span></span>  <span data-ttu-id="ff11a-157">將裝置連接到網路，並將它開啟。</span><span class="sxs-lookup"><span data-stu-id="ff11a-157">Connect a device to the network and turn it on.</span></span>

    <span data-ttu-id="ff11a-158">b.</span><span class="sxs-lookup"><span data-stu-id="ff11a-158">b.</span></span>  <span data-ttu-id="ff11a-159">確認是否會顯示適當的 OOBE 畫面 (如果有的話)。</span><span class="sxs-lookup"><span data-stu-id="ff11a-159">Verify that the appropriate OOBE screens (if any) appear.</span></span>

    <span data-ttu-id="ff11a-160">c.</span><span class="sxs-lookup"><span data-stu-id="ff11a-160">c.</span></span>  <span data-ttu-id="ff11a-161">當 OOBE 程序停止時，裝置重設為原廠預設設定，以準備進行新的使用者。</span><span class="sxs-lookup"><span data-stu-id="ff11a-161">When the OOBE process stops, reset the device to its factory default settings to prepare it for a new user.</span></span>

### <a name="remove-an-autopilot-profile-from-a-customers-device"></a><span data-ttu-id="ff11a-162">從客戶的裝置移除 Autopilot 設定檔</span><span class="sxs-lookup"><span data-stu-id="ff11a-162">Remove an Autopilot profile from a customer's device</span></span>

1. <span data-ttu-id="ff11a-163">從合作夥伴中心功能表中選取**客戶**，然後選取您建立的 Autopilot 設定檔的客戶。</span><span class="sxs-lookup"><span data-stu-id="ff11a-163">Select **Customers** from the Partner Center menu and then select the customer you created the Autopilot profile for.</span></span>

2. <span data-ttu-id="ff11a-164">客戶的詳細資料頁面上，選取**裝置**。</span><span class="sxs-lookup"><span data-stu-id="ff11a-164">On the customer's detail page, select **Devices**.</span></span>

3. <span data-ttu-id="ff11a-165">在**套用到裝置的設定檔**中，選取您想要移除的設定檔，然後選取 [**移除設定檔**的裝置。</span><span class="sxs-lookup"><span data-stu-id="ff11a-165">Under **Apply profiles to devices** select the devices you want to remove the profile from and then select **Remove profile**.</span></span>

   >[!NOTE]
   ><span data-ttu-id="ff11a-166">從裝置移除設定檔並不會從您的清單刪除設定檔。</span><span class="sxs-lookup"><span data-stu-id="ff11a-166">Removing a profile from a device does not delete the profile from your list.</span></span> <span data-ttu-id="ff11a-167">如果您想要刪除設定檔，請依照[更新或刪除 Autopilot 設定檔](#update-or-delete-an-autopilot-profile)中的指示。</span><span class="sxs-lookup"><span data-stu-id="ff11a-167">If you want to delete a profile, follow the instructions in [Update or delete an Autopilot profile](#update-or-delete-an-autopilot-profile).</span></span>

### <a name="update-or-delete-an-autopilot-profile"></a><span data-ttu-id="ff11a-168">更新或刪除 Autopilot 設定檔</span><span class="sxs-lookup"><span data-stu-id="ff11a-168">Update or delete an Autopilot profile</span></span>

<span data-ttu-id="ff11a-169">如果客戶想要變更的全新體驗，您已經出貨給他們的裝置之後，您可以變更的設定檔，在合作夥伴中心。</span><span class="sxs-lookup"><span data-stu-id="ff11a-169">If a customer wants to change the out-of-box experience after you've shipped the devices to them, you can change the profile in Partner Center.</span></span>

<span data-ttu-id="ff11a-170">當客戶的裝置連線到網際網路時，它會下載最新版的設定檔在 OOBE 程序。</span><span class="sxs-lookup"><span data-stu-id="ff11a-170">When the customer's device connects to the internet, it will download the latest profile version during the OOBE process.</span></span> <span data-ttu-id="ff11a-171">此外，任何時候，客戶將裝置還原為原廠預設設定，裝置將會重新下載最新版的設定檔在 OOBE 程序。</span><span class="sxs-lookup"><span data-stu-id="ff11a-171">Also, any time a customer restores a device to its factory default settings, the device will again download the latest profile version during the OOBE process.</span></span>

1. <span data-ttu-id="ff11a-172">從合作夥伴中心功能表中選取**客戶**，然後選取 [想要您變更 Autopilot 設定檔的客戶。</span><span class="sxs-lookup"><span data-stu-id="ff11a-172">Select **Customers** from the Partner Center menu and then select the customer who wants you to change an Autopilot profile.</span></span>

2. <span data-ttu-id="ff11a-173">客戶的詳細資料頁面上，選取**裝置**。</span><span class="sxs-lookup"><span data-stu-id="ff11a-173">On the customer's detail page, select **Devices**.</span></span>

3. <span data-ttu-id="ff11a-174">在**Windows Autopilot 設定檔**中，選取您需要更新的設定檔。</span><span class="sxs-lookup"><span data-stu-id="ff11a-174">Under **Windows Autopilot profiles** select the profile you need to update.</span></span> <span data-ttu-id="ff11a-175">進行必要的變更，然後選取 [**送出**。</span><span class="sxs-lookup"><span data-stu-id="ff11a-175">Make the required changes and then select **Submit**.</span></span>

<span data-ttu-id="ff11a-176">若要刪除此設定檔，請從右上角的 [\] 頁面選取**刪除設定檔**。</span><span class="sxs-lookup"><span data-stu-id="ff11a-176">To delete this profile, select **Delete profile** from the upper right corner of the page.</span></span>

### <a name="add-devices-to-a-customers-account"></a><span data-ttu-id="ff11a-177">將裝置新增至客戶帳戶</span><span class="sxs-lookup"><span data-stu-id="ff11a-177">Add devices to a customer's account</span></span>

>[!NOTE]
><span data-ttu-id="ff11a-178">銷售專員和系統管理代理人可以將裝置新增至客戶帳戶。</span><span class="sxs-lookup"><span data-stu-id="ff11a-178">Sales agents and admin agents can add devices to a customer's account.</span></span>

<span data-ttu-id="ff11a-179">您可以將自訂的 Autopilot 設定檔套用至客戶裝置之前，您必須能夠存取客戶的裝置清單。</span><span class="sxs-lookup"><span data-stu-id="ff11a-179">Before you can apply custom Autopilot profiles to customer devices, you must be able to access the customer's device list.</span></span>

<span data-ttu-id="ff11a-180">如果您打算使用 OEM 名稱、 序號和型號組合，請注意這些限制：</span><span class="sxs-lookup"><span data-stu-id="ff11a-180">If you plan to use the OEM name, serial number, and model combination, be aware of these limitations:</span></span>

- <span data-ttu-id="ff11a-181">這個 tuple 只適用於較新的裝置 （4 個 k 雜湊，例如），且不支援 128b 雜湊 （RS2 和先前的裝置）。</span><span class="sxs-lookup"><span data-stu-id="ff11a-181">This tuple works only for newer devices (4k hashes, for example) and is not supported for 128b hashes (RS2 and prior devices).</span></span>

- <span data-ttu-id="ff11a-182">Tuple 註冊會區分大小寫，，因此檔案中的資料必須符合模型與製造商的名稱***完全***所提供的 OEM 提供者 （硬體提供者）。</span><span class="sxs-lookup"><span data-stu-id="ff11a-182">The tuple registration is case sensitive, so the data in the file must match the model and manufacturer names ***exactly*** as provided by the OEM provider (hardware provider).</span></span>

<span data-ttu-id="ff11a-183">請依照下列指示將裝置新增至合作夥伴中心中的客戶的帳戶。</span><span class="sxs-lookup"><span data-stu-id="ff11a-183">Follow the instructions below to add devices to a customer's account in Partner Center.</span></span>

1. <span data-ttu-id="ff11a-184">從合作夥伴中心功能表中選取**客戶**，然後選取您想要管理其裝置的客戶。</span><span class="sxs-lookup"><span data-stu-id="ff11a-184">Select **Customers** from the Partner Center menu and then select the customer whose devices you want to manage.</span></span>

2. <span data-ttu-id="ff11a-185">客戶的詳細資料頁面上，選取**裝置**。</span><span class="sxs-lookup"><span data-stu-id="ff11a-185">On the customer's detail page, select **Devices**.</span></span>

3. <span data-ttu-id="ff11a-186">**套用至裝置的設定檔**底下選取 [**新增裝置**。</span><span class="sxs-lookup"><span data-stu-id="ff11a-186">Under **Apply profiles to devices** select **Add devices**.</span></span>

4. <span data-ttu-id="ff11a-187">輸入裝置清單的名稱，然後選取要上傳至合作夥伴中心的客戶清單中的 （在.csv 檔案格式） 的**瀏覽**。</span><span class="sxs-lookup"><span data-stu-id="ff11a-187">Enter a name for the device list and then select **Browse** to upload the customer's list (in .csv file format) to Partner Center.</span></span>

    >[!NOTE]
    ><span data-ttu-id="ff11a-188">您應該與您的裝置購買收到此.csv 檔案。</span><span class="sxs-lookup"><span data-stu-id="ff11a-188">You should have received this .csv file with your device purchase.</span></span> <span data-ttu-id="ff11a-189">如果您沒有收到.csv 檔案，您可以依照下列步驟中[新增 Windows Autopilot 裝置](https://docs.microsoft.com/windows/deployment/windows-autopilot/add-devices#collecting-the-hardware-id-from-existing-devices-using-powershell)建立一個自己。</span><span class="sxs-lookup"><span data-stu-id="ff11a-189">If you didn't receive a .csv file, you can create one yourself by following the steps in [Adding devices to Windows Autopilot](https://docs.microsoft.com/windows/deployment/windows-autopilot/add-devices#collecting-the-hardware-id-from-existing-devices-using-powershell).</span></span>  

5. <span data-ttu-id="ff11a-190">上傳.csv 檔案，然後選取 [**儲存**]。</span><span class="sxs-lookup"><span data-stu-id="ff11a-190">Upload the .csv file and then select **Save**.</span></span>

<span data-ttu-id="ff11a-191">如果您嘗試上傳.csv 檔案時收到錯誤訊息，請檢查檔案的格式。</span><span class="sxs-lookup"><span data-stu-id="ff11a-191">If you get an error message while trying to upload the .csv file, check the format of the file.</span></span> <span data-ttu-id="ff11a-192">您可以使用硬體雜湊，或 OEM 名稱、 序號和模型 （在此欄順序） 或 Windows 產品識別碼。</span><span class="sxs-lookup"><span data-stu-id="ff11a-192">You can use the hardware hash only, or the OEM name, serial number, and model (in that column order), or the Windows Product ID.</span></span> <span data-ttu-id="ff11a-193">您也可以使用**新增裝置**旁邊連結所提供的範例.csv 檔案，來建立裝置清單。</span><span class="sxs-lookup"><span data-stu-id="ff11a-193">You can also use the sample .csv file provided from the link next to **Add devices** to create a device list.</span></span>

## <a name="windows-autopilot-eula-dismissal"></a><span data-ttu-id="ff11a-194">Windows Autopilot EULA 關閉</span><span class="sxs-lookup"><span data-stu-id="ff11a-194">Windows Autopilot EULA dismissal</span></span>

### <a name="important-information"></a><span data-ttu-id="ff11a-195">重要資訊</span><span class="sxs-lookup"><span data-stu-id="ff11a-195">IMPORTANT INFORMATION</span></span>

<span data-ttu-id="ff11a-196">Windows Autopilot 可讓您管理您的客戶的裝置上設定自訂的安裝 Windows。</span><span class="sxs-lookup"><span data-stu-id="ff11a-196">Windows Autopilot allows you to configure customized installations of Windows on devices you manage for your customers.</span></span> <span data-ttu-id="ff11a-197">如果客戶授權若要這樣做，您可以抑制或隱藏通常會顯示給使用者設定 Windows 中，包括 （使用者授權合約） EULA 接受畫面時的特定安裝設定畫面。</span><span class="sxs-lookup"><span data-stu-id="ff11a-197">If authorized to do so by the customer, you can suppress or hide certain set-up screens that are normally presented to users when setting up Windows, including the EULA (End User License Agreement) acceptance screen.</span></span>

<span data-ttu-id="ff11a-198">藉由使用這個函式，表示您同意抑制或隱藏專為使用者提供通知或接受條款表示您已經從您的客戶，以隱藏條款，以及您，代表的取得足夠同意和授權的任何畫面您的客戶 （是否在組織或個別使用者，視情況可能），同意通知並接受任何適用於您客戶的條款。</span><span class="sxs-lookup"><span data-stu-id="ff11a-198">By using this function, you agree that suppressing or hiding any screens that are designed to provide users with notice or acceptance of terms means that you have obtained sufficient consent and authorization from your customer to hide terms, and that you, on behalf of your customer (whether an organization or an individual user as the case may be), consent to any notices and accept any terms that are applicable to your customer.</span></span> <span data-ttu-id="ff11a-199">這包括同意授權條款和條件，或若未使用此工具抑制或隱藏時會對使用者顯示的通知。</span><span class="sxs-lookup"><span data-stu-id="ff11a-199">This includes agreement to the terms and conditions of the license or notice that would be presented to the user if you did not suppress or hide it using this tool.</span></span> <span data-ttu-id="ff11a-200">您的客戶不可在這些裝置上使用 Windows 軟體，如果他們未向 Microsoft 或其授權經銷商有效取得軟體授權。</span><span class="sxs-lookup"><span data-stu-id="ff11a-200">Your customer may not use the Windows software on those devices if the customer has not validly acquired a license for the software from Microsoft or its licensed distributors.</span></span>