---
title: 自訂裝置的全新的體驗使用 Windows Autopilot 設定檔 |合作夥伴中心
description: 預先設定裝置的全新的體驗 Autopilot 設定檔。
ms.topic: article
ms.date: 03/18/19
author: maggiepuccievans
ms.author: evansma
keywords: autopilot、 windows autopilot、 microsoft autopilot、 零觸式部署、 oobe、 登入畫面、 立即可用
ms.localizationpriority: medium
ms.openlocfilehash: e940a7ccf79f6b43d3712a2f3ae2f9b150e1473e
ms.sourcegitcommit: b1ab80345b4e4af649fb8cc51d96d798e0791ade
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 04/23/2019
ms.locfileid: "62134708"
---
# <a name="customize-a-devices-out-of-box-experience-with-windows-autopilot-profiles"></a><span data-ttu-id="ba64d-104">自訂裝置的全新的體驗使用 Windows Autopilot 設定檔</span><span class="sxs-lookup"><span data-stu-id="ba64d-104">Customize a device's out-of-box experience with Windows Autopilot profiles</span></span>

<span data-ttu-id="ba64d-105">**適用於**</span><span class="sxs-lookup"><span data-stu-id="ba64d-105">**Applies to**</span></span>

- <span data-ttu-id="ba64d-106">Direct 帳單的 CSP 合作夥伴，間接提供者，以及間接轉售商</span><span class="sxs-lookup"><span data-stu-id="ba64d-106">CSP direct-bill partners, indirect providers, and indirect resellers</span></span>

<span data-ttu-id="ba64d-107">如果您管理客戶的裝置，您可能需要自訂的全新體驗 (OOBE)，為客戶的使用者。</span><span class="sxs-lookup"><span data-stu-id="ba64d-107">If you manage customer devices, you may need to customize the out-of-box experience (OOBE) for the customer's users.</span></span> <span data-ttu-id="ba64d-108">您可以預先設定裝置交給客戶之前的 使用 Windows Autopilot 設定檔的新裝置，並將新的設定檔套用至客戶已購買的裝置。</span><span class="sxs-lookup"><span data-stu-id="ba64d-108">You can pre-configure new devices with Windows Autopilot profiles before delivering the devices to customers and apply new profiles to devices customers have already purchased.</span></span> <span data-ttu-id="ba64d-109">這篇文章說明如何建立和套用到在合作夥伴中心內的裝置的 Autopilot 設定檔。</span><span class="sxs-lookup"><span data-stu-id="ba64d-109">This article explains how to create and apply Autopilot profiles to devices in Partner Center.</span></span>

<span data-ttu-id="ba64d-110">如果您已經不熟悉自動駕駛儀的操作，請檢閱這些文章中的資訊：</span><span class="sxs-lookup"><span data-stu-id="ba64d-110">If you're not already familiar with Autopilot, review the information in these articles:</span></span>

- [<span data-ttu-id="ba64d-111">Windows Autopilot 概觀</span><span class="sxs-lookup"><span data-stu-id="ba64d-111">Overview of Windows Autopilot</span></span>](https://docs.microsoft.com/windows/deployment/windows-10-auto-pilot)
- [<span data-ttu-id="ba64d-112">Autopilot 部署參考指南</span><span class="sxs-lookup"><span data-stu-id="ba64d-112">Autopilot deployment reference guide</span></span>](https://assetsprod.microsoft.com/autopilot-deployment-program-reference-guide-csp.docx)  

## <a name="overview"></a><span data-ttu-id="ba64d-113">總覽</span><span class="sxs-lookup"><span data-stu-id="ba64d-113">Overview</span></span>

<span data-ttu-id="ba64d-114">使用 Windows Autopilot 在合作夥伴中心功能，您可以建立要套用到客戶裝置的自訂設定檔。</span><span class="sxs-lookup"><span data-stu-id="ba64d-114">With the Windows Autopilot feature in Partner Center, you can create custom profiles to apply to customer devices.</span></span> <span data-ttu-id="ba64d-115">下列設定檔設定已發行的這篇文章的時間後可用：</span><span class="sxs-lookup"><span data-stu-id="ba64d-115">The following profile settings were available at the time this article was published:</span></span>

- <span data-ttu-id="ba64d-116">略過隱私權設定。</span><span class="sxs-lookup"><span data-stu-id="ba64d-116">Skip privacy settings.</span></span> <span data-ttu-id="ba64d-117">這個選擇性的 Autopilot 設定檔設定可讓組織不會詢問 OOBE 程序期間的隱私權設定。</span><span class="sxs-lookup"><span data-stu-id="ba64d-117">This optional Autopilot profile setting enables organizations to not ask about privacy settings during the OOBE process.</span></span>

- <span data-ttu-id="ba64d-118">停用裝置上的本機系統管理員帳戶建立。</span><span class="sxs-lookup"><span data-stu-id="ba64d-118">Disable local admin account creation on the device.</span></span> <span data-ttu-id="ba64d-119">組織可以決定程序完成之後，設定裝置的使用者是否應該具有系統管理員存取權。</span><span class="sxs-lookup"><span data-stu-id="ba64d-119">Organizations can decide whether the user setting up the device should have administrator access once the process is complete.</span></span>

- <span data-ttu-id="ba64d-120">自動設定裝置的公司或學校資源。</span><span class="sxs-lookup"><span data-stu-id="ba64d-120">Automatically set up device for work or school.</span></span> <span data-ttu-id="ba64d-121">所有 Autopilot 註冊的裝置會自動被視為工作或學校裝置，因此這個問題不會要求在 OOBE 程序期間。</span><span class="sxs-lookup"><span data-stu-id="ba64d-121">All devices registered with Autopilot will automatically be considered work or school devices, so this question will not be asked during the OOBE process.</span></span>

- <span data-ttu-id="ba64d-122">略過 Cortana、 OneDrive 和 OEM 登錄設定頁面。</span><span class="sxs-lookup"><span data-stu-id="ba64d-122">Skip Cortana, OneDrive, and OEM registration setup pages.</span></span> <span data-ttu-id="ba64d-123">所有 Autopilot 註冊的裝置將會自動略都過這些頁面的全新體驗 (OOBE) 程序期間。</span><span class="sxs-lookup"><span data-stu-id="ba64d-123">All devices registered with Autopilot will automatically skip these pages during the out-of-box experience (OOBE) process.</span></span>

- <span data-ttu-id="ba64d-124">略過使用者授權合約 (EULA)。</span><span class="sxs-lookup"><span data-stu-id="ba64d-124">Skip End User License Agreement (EULA).</span></span> <span data-ttu-id="ba64d-125">從 Windows 10 1709年版開始，組織可以決定略過 OOBE 流程期間所呈現的 EULA 頁面。</span><span class="sxs-lookup"><span data-stu-id="ba64d-125">Starting in Windows 10 version 1709, organizations can decide to skip the EULA page presented during the OOBE process.</span></span> <span data-ttu-id="ba64d-126">請參閱[Windows Autopilot EULA dismissal](#windows-autopilot-eula-dismissal)以下重要的資訊，需要考量的事項略過 [使用者授權合約] 頁面，在 Windows 安裝程式。</span><span class="sxs-lookup"><span data-stu-id="ba64d-126">See [Windows Autopilot EULA dismissal](#windows-autopilot-eula-dismissal) below for important information to consider about skipping the EULA page during Windows setup.</span></span>

<span data-ttu-id="ba64d-127">下列設定檔和裝置的管理使用權限和限制適用於：</span><span class="sxs-lookup"><span data-stu-id="ba64d-127">The following profile and device management permissions and limitations apply:</span></span>

- <span data-ttu-id="ba64d-128">CSP 合作夥伴可以繼續針對現有的客戶能與其轉銷商關係管理 Autopilot 設定檔，即使客戶已移除夥伴的委派的系統管理權限。</span><span class="sxs-lookup"><span data-stu-id="ba64d-128">CSP partners can continue to manage Autopilot profiles for existing customers with whom they have reseller relationships, even if the customers have removed the partner's delegated administration privileges.</span></span>

- <span data-ttu-id="ba64d-129">您可以為您加入的客戶管理現有的裝置。</span><span class="sxs-lookup"><span data-stu-id="ba64d-129">You can manage existing devices for your customers that you have added.</span></span>

- <span data-ttu-id="ba64d-130">您無法管理您的客戶已上傳至 Microsoft Store for Business 或 Microsoft Intune 入口網站的裝置。</span><span class="sxs-lookup"><span data-stu-id="ba64d-130">You can’t manage devices your customer has uploaded to Microsoft Store for Business or the Microsoft Intune Portal.</span></span>

## <a name="create-and-manage-autopilot-profiles-in-partner-center"></a><span data-ttu-id="ba64d-131">建立和管理在合作夥伴中心內的 Autopilot 設定檔</span><span class="sxs-lookup"><span data-stu-id="ba64d-131">Create and manage Autopilot profiles in Partner Center</span></span>

<span data-ttu-id="ba64d-132">在合作夥伴中心，您可以建立 Windows Autopilot 部署設定檔，並將它們套用至裝置。</span><span class="sxs-lookup"><span data-stu-id="ba64d-132">In Partner Center, you can create Windows Autopilot deployment profiles and apply them to devices.</span></span>

>[!NOTE]
><span data-ttu-id="ba64d-133">只管理專員可以建立，並套用設定檔。</span><span class="sxs-lookup"><span data-stu-id="ba64d-133">Only admin agents can create and apply profiles.</span></span>

### <a name="create-a-new-autopilot-profile"></a><span data-ttu-id="ba64d-134">建立新的 Autopilot 設定檔</span><span class="sxs-lookup"><span data-stu-id="ba64d-134">Create a new Autopilot profile</span></span>

1. <span data-ttu-id="ba64d-135">選取 **客戶**合作夥伴中心功能表，然後選取從客戶您正在建立 Autopilot 設定檔。</span><span class="sxs-lookup"><span data-stu-id="ba64d-135">Select **Customers** from the Partner Center menu and then select the customer you're creating the Autopilot profile for.</span></span>

2. <span data-ttu-id="ba64d-136">在客戶的詳細資料頁面上，選取**裝置**。</span><span class="sxs-lookup"><span data-stu-id="ba64d-136">On the customer's detail page, select **Devices**.</span></span>

3. <span data-ttu-id="ba64d-137">底下**Windows Autopilot 設定檔**選取**新增新的設定檔**。</span><span class="sxs-lookup"><span data-stu-id="ba64d-137">Under **Windows Autopilot profiles** select **Add new profile**.</span></span>

4. <span data-ttu-id="ba64d-138">輸入設定檔的名稱和描述，然後設定 OOBE 設定。</span><span class="sxs-lookup"><span data-stu-id="ba64d-138">Enter the profile's name and description and then configure the OOBE settings.</span></span> <span data-ttu-id="ba64d-139">選擇：</span><span class="sxs-lookup"><span data-stu-id="ba64d-139">Choose from:</span></span>  

   - <span data-ttu-id="ba64d-140">略過安裝程式中的隱私權設定</span><span class="sxs-lookup"><span data-stu-id="ba64d-140">Skip privacy settings in setup</span></span>

   - <span data-ttu-id="ba64d-141">停用設定中的本機系統管理員帳戶</span><span class="sxs-lookup"><span data-stu-id="ba64d-141">Disable local admin account in setup</span></span>
  
   - <span data-ttu-id="ba64d-142">自動略過設定中的頁面</span><span class="sxs-lookup"><span data-stu-id="ba64d-142">Automatically skip pages in setup</span></span><br>
        <span data-ttu-id="ba64d-143">(包括*會自動選取的安裝程式，為工作或學校*並*略過 Cortana、 OneDrive 和 OEM 登錄設定頁面*)</span><span class="sxs-lookup"><span data-stu-id="ba64d-143">(Includes *Automatically select setup for work or school* and *Skip Cortana, OneDrive, and OEM registration setup pages*)</span></span>
  
   - <span data-ttu-id="ba64d-144">略過使用者授權合約 (EULA)</span><span class="sxs-lookup"><span data-stu-id="ba64d-144">Skip end user license agreement (EULA)</span></span><br> 
       >[!IMPORTANT] 
       ><span data-ttu-id="ba64d-145">請參閱[Windows Autopilot EULA dismissal](#windows-autopilot-eula-dismissal)以下重要的資訊，需要考量的事項略過 [使用者授權合約] 頁面，在 Windows 安裝程式。</span><span class="sxs-lookup"><span data-stu-id="ba64d-145">See [Windows Autopilot EULA dismissal](#windows-autopilot-eula-dismissal) below for important information to consider about skipping the EULA page during Windows setup.</span></span>

5. <span data-ttu-id="ba64d-146">完成時選取 **\[提交\]**。</span><span class="sxs-lookup"><span data-stu-id="ba64d-146">Select **Submit** when finished.</span></span>

### <a name="apply-an-autopilot-profile-to-customer-devices"></a><span data-ttu-id="ba64d-147">套用到客戶裝置的 Autopilot 設定檔</span><span class="sxs-lookup"><span data-stu-id="ba64d-147">Apply an Autopilot profile to customer devices</span></span>

>[!NOTE]
><span data-ttu-id="ba64d-148">下面的指示會假設，您已新增客戶的裝置到合作夥伴中心，而且您可以存取其裝置的清單。</span><span class="sxs-lookup"><span data-stu-id="ba64d-148">The instructions below assume that you've already added the customer's devices to Partner Center and that you can access their device list.</span></span> <span data-ttu-id="ba64d-149">如果您尚未新增客戶的裝置，請依照下列中的指示[將裝置新增至客戶帳戶](#add-devices-to-a-customers-account)，然後遵循下列步驟。</span><span class="sxs-lookup"><span data-stu-id="ba64d-149">If you haven't already added the customer's devices, follow the instructions in [Add devices to a customer's account](#add-devices-to-a-customers-account) and then follow the steps below.</span></span>

<span data-ttu-id="ba64d-150">客戶建立 Autopilot 設定檔之後，您可以將它套用至客戶的裝置。</span><span class="sxs-lookup"><span data-stu-id="ba64d-150">After you create an Autopilot profile for a customer, you can apply it to the customer's devices.</span></span>

1. <span data-ttu-id="ba64d-151">選取 **客戶**從合作夥伴中心功能表，然後選取您建立客戶的 Autopilot 設定檔。</span><span class="sxs-lookup"><span data-stu-id="ba64d-151">Select **Customers** from the Partner Center menu and then select the customer you created the Autopilot profile for.</span></span>

2. <span data-ttu-id="ba64d-152">在客戶的詳細資料頁面上，選取**裝置**。</span><span class="sxs-lookup"><span data-stu-id="ba64d-152">On the customer's detail page, select **Devices**.</span></span>

3. <span data-ttu-id="ba64d-153">底下**套用至裝置的設定檔**選取的裝置或裝置群組，您想要新增至設定檔，然後選取**將設定檔套用**。</span><span class="sxs-lookup"><span data-stu-id="ba64d-153">Under **Apply profiles to devices** select the devices or device groups you want to add profiles to and then select **Apply profile**.</span></span> <span data-ttu-id="ba64d-154">您剛才套用之設定檔會出現在**設定檔**資料行。</span><span class="sxs-lookup"><span data-stu-id="ba64d-154">The profile you just applied appears in the **Profile** column.</span></span>

4. <span data-ttu-id="ba64d-155">請遵循下列步驟來確認設定檔會將已成功套用至裝置。</span><span class="sxs-lookup"><span data-stu-id="ba64d-155">Follow the steps below to verify that the profile will be applied successfully to the device.</span></span>

    <span data-ttu-id="ba64d-156">a.</span><span class="sxs-lookup"><span data-stu-id="ba64d-156">a.</span></span>  <span data-ttu-id="ba64d-157">將裝置連線到網路，並將它開啟。</span><span class="sxs-lookup"><span data-stu-id="ba64d-157">Connect a device to the network and turn it on.</span></span>

    <span data-ttu-id="ba64d-158">b.</span><span class="sxs-lookup"><span data-stu-id="ba64d-158">b.</span></span>  <span data-ttu-id="ba64d-159">確認是否會顯示適當的 OOBE 畫面 (如果有的話)。</span><span class="sxs-lookup"><span data-stu-id="ba64d-159">Verify that the appropriate OOBE screens (if any) appear.</span></span>

    <span data-ttu-id="ba64d-160">c. </span><span class="sxs-lookup"><span data-stu-id="ba64d-160">c.</span></span>  <span data-ttu-id="ba64d-161">當 OOBE 程序停止之後時，請將裝置重設其原廠預設值，以準備進行新的使用者。</span><span class="sxs-lookup"><span data-stu-id="ba64d-161">When the OOBE process stops, reset the device to its factory default settings to prepare it for a new user.</span></span>

### <a name="remove-an-autopilot-profile-from-a-customers-device"></a><span data-ttu-id="ba64d-162">移除客戶的裝置的 Autopilot 設定檔</span><span class="sxs-lookup"><span data-stu-id="ba64d-162">Remove an Autopilot profile from a customer's device</span></span>

1. <span data-ttu-id="ba64d-163">選取 **客戶**從合作夥伴中心功能表，然後選取您建立客戶的 Autopilot 設定檔。</span><span class="sxs-lookup"><span data-stu-id="ba64d-163">Select **Customers** from the Partner Center menu and then select the customer you created the Autopilot profile for.</span></span>

2. <span data-ttu-id="ba64d-164">在客戶的詳細資料頁面上，選取**裝置**。</span><span class="sxs-lookup"><span data-stu-id="ba64d-164">On the customer's detail page, select **Devices**.</span></span>

3. <span data-ttu-id="ba64d-165">底下**套用至裝置的設定檔**選取您想要移除的設定檔，然後選取的裝置**移除設定檔**。</span><span class="sxs-lookup"><span data-stu-id="ba64d-165">Under **Apply profiles to devices** select the devices you want to remove the profile from and then select **Remove profile**.</span></span>

   >[!NOTE]
   ><span data-ttu-id="ba64d-166">從裝置移除設定檔不會從清單刪除該設定檔。</span><span class="sxs-lookup"><span data-stu-id="ba64d-166">Removing a profile from a device does not delete the profile from your list.</span></span> <span data-ttu-id="ba64d-167">如果您想要刪除設定檔，請依照下列中的指示[更新或刪除 Autopilot 設定檔](#update-or-delete-an-autopilot-profile)。</span><span class="sxs-lookup"><span data-stu-id="ba64d-167">If you want to delete a profile, follow the instructions in [Update or delete an Autopilot profile](#update-or-delete-an-autopilot-profile).</span></span>

### <a name="update-or-delete-an-autopilot-profile"></a><span data-ttu-id="ba64d-168">更新或刪除 Autopilot 設定檔</span><span class="sxs-lookup"><span data-stu-id="ba64d-168">Update or delete an Autopilot profile</span></span>

<span data-ttu-id="ba64d-169">如果客戶想要變更的全新體驗，您已出貨給他們的裝置之後，您可以變更在合作夥伴中心內的設定檔。</span><span class="sxs-lookup"><span data-stu-id="ba64d-169">If a customer wants to change the out-of-box experience after you've shipped the devices to them, you can change the profile in Partner Center.</span></span>

<span data-ttu-id="ba64d-170">當客戶的裝置連線到網際網路時，它會下載最新的設定檔版本 OOBE 程序期間。</span><span class="sxs-lookup"><span data-stu-id="ba64d-170">When the customer's device connects to the internet, it will download the latest profile version during the OOBE process.</span></span> <span data-ttu-id="ba64d-171">此外，客戶會將裝置還原為原廠預設值，任何時候裝置會再次下載最新的設定檔版本 OOBE 程序期間。</span><span class="sxs-lookup"><span data-stu-id="ba64d-171">Also, any time a customer restores a device to its factory default settings, the device will again download the latest profile version during the OOBE process.</span></span>

1. <span data-ttu-id="ba64d-172">選取 **客戶**從合作夥伴中心功能表然後選取想要變更 Autopilot 設定檔的客戶。</span><span class="sxs-lookup"><span data-stu-id="ba64d-172">Select **Customers** from the Partner Center menu and then select the customer who wants you to change an Autopilot profile.</span></span>

2. <span data-ttu-id="ba64d-173">在客戶的詳細資料頁面上，選取**裝置**。</span><span class="sxs-lookup"><span data-stu-id="ba64d-173">On the customer's detail page, select **Devices**.</span></span>

3. <span data-ttu-id="ba64d-174">底下**Windows Autopilot 設定檔**選取您要更新的設定檔。</span><span class="sxs-lookup"><span data-stu-id="ba64d-174">Under **Windows Autopilot profiles** select the profile you need to update.</span></span> <span data-ttu-id="ba64d-175">進行必要的變更，然後按**送出**。</span><span class="sxs-lookup"><span data-stu-id="ba64d-175">Make the required changes and then select **Submit**.</span></span>

<span data-ttu-id="ba64d-176">若要刪除此設定檔，請選取**刪除設定檔**從頁面右上角。</span><span class="sxs-lookup"><span data-stu-id="ba64d-176">To delete this profile, select **Delete profile** from the upper right corner of the page.</span></span>

### <a name="add-devices-to-a-customers-account"></a><span data-ttu-id="ba64d-177">將裝置新增至客戶的帳戶</span><span class="sxs-lookup"><span data-stu-id="ba64d-177">Add devices to a customer's account</span></span>

>[!NOTE]
><span data-ttu-id="ba64d-178">銷售的代理程式和管理專員可以將裝置新增至客戶的帳戶。</span><span class="sxs-lookup"><span data-stu-id="ba64d-178">Sales agents and admin agents can add devices to a customer's account.</span></span>

<span data-ttu-id="ba64d-179">您可以將自訂的 Autopilot 設定檔套用到客戶裝置之前，您必須能夠存取客戶的裝置清單。</span><span class="sxs-lookup"><span data-stu-id="ba64d-179">Before you can apply custom Autopilot profiles to customer devices, you must be able to access the customer's device list.</span></span>

<span data-ttu-id="ba64d-180">如果您打算使用 OEM 名稱、 序號和模型組合，請注意這些限制：</span><span class="sxs-lookup"><span data-stu-id="ba64d-180">If you plan to use the OEM name, serial number, and model combination, be aware of these limitations:</span></span>

- <span data-ttu-id="ba64d-181">此 tuple 只適用於較新的裝置 （4 k 雜湊，例如），且不支援 128b 雜湊 （RS2 和先前的裝置）。</span><span class="sxs-lookup"><span data-stu-id="ba64d-181">This tuple works only for newer devices (4k hashes, for example) and is not supported for 128b hashes (RS2 and prior devices).</span></span>

- <span data-ttu-id="ba64d-182">Tuple 註冊會區分大小寫，所以檔案中的資料必須符合的模型和製造商名稱***完全***OEM 提供者 （硬體提供者） 所提供。</span><span class="sxs-lookup"><span data-stu-id="ba64d-182">The tuple registration is case sensitive, so the data in the file must match the model and manufacturer names ***exactly*** as provided by the OEM provider (hardware provider).</span></span>

<span data-ttu-id="ba64d-183">請遵循下列指示來將裝置新增至在合作夥伴中心內的客戶的帳戶。</span><span class="sxs-lookup"><span data-stu-id="ba64d-183">Follow the instructions below to add devices to a customer's account in Partner Center.</span></span>

1. <span data-ttu-id="ba64d-184">選取 **客戶**從合作夥伴中心功能表然後選取客戶您想要管理其裝置。</span><span class="sxs-lookup"><span data-stu-id="ba64d-184">Select **Customers** from the Partner Center menu and then select the customer whose devices you want to manage.</span></span>

2. <span data-ttu-id="ba64d-185">在客戶的詳細資料頁面上，選取**裝置**。</span><span class="sxs-lookup"><span data-stu-id="ba64d-185">On the customer's detail page, select **Devices**.</span></span>

3. <span data-ttu-id="ba64d-186">底下**套用至裝置的設定檔**選取**將裝置新增**。</span><span class="sxs-lookup"><span data-stu-id="ba64d-186">Under **Apply profiles to devices** select **Add devices**.</span></span>

4. <span data-ttu-id="ba64d-187">輸入 [裝置] 清單的名稱，然後選取**瀏覽**上傳至合作夥伴中心的客戶的清單 （格式為.csv 檔案）。</span><span class="sxs-lookup"><span data-stu-id="ba64d-187">Enter a name for the device list and then select **Browse** to upload the customer's list (in .csv file format) to Partner Center.</span></span>

    >[!NOTE]
    ><span data-ttu-id="ba64d-188">您應該會收到此.csv 檔案與您的裝置購買。</span><span class="sxs-lookup"><span data-stu-id="ba64d-188">You should have received this .csv file with your device purchase.</span></span> <span data-ttu-id="ba64d-189">如果您未收到.csv 檔案，您可以建立自己所遵循的步驟[將裝置新增至 Windows Autopilot](https://docs.microsoft.com/windows/deployment/windows-autopilot/add-devices#collecting-the-hardware-id-from-existing-devices-using-powershell)。</span><span class="sxs-lookup"><span data-stu-id="ba64d-189">If you didn't receive a .csv file, you can create one yourself by following the steps in [Adding devices to Windows Autopilot](https://docs.microsoft.com/windows/deployment/windows-autopilot/add-devices#collecting-the-hardware-id-from-existing-devices-using-powershell).</span></span>  

5. <span data-ttu-id="ba64d-190">上傳.csv 檔案，然後選取**儲存**。</span><span class="sxs-lookup"><span data-stu-id="ba64d-190">Upload the .csv file and then select **Save**.</span></span>

<span data-ttu-id="ba64d-191">如果您嘗試上傳.csv 檔案時收到錯誤訊息，請檢查檔案的格式。</span><span class="sxs-lookup"><span data-stu-id="ba64d-191">If you get an error message while trying to upload the .csv file, check the format of the file.</span></span> <span data-ttu-id="ba64d-192">您可以使用硬體雜湊，或 OEM 名稱、 序號和模型 （依該資料行順序） 或 Windows 產品識別碼。</span><span class="sxs-lookup"><span data-stu-id="ba64d-192">You can use the hardware hash only, or the OEM name, serial number, and model (in that column order), or the Windows Product ID.</span></span> <span data-ttu-id="ba64d-193">您也可以使用所提供的連結旁邊的範例.csv 檔案**將裝置新增**建立裝置清單。</span><span class="sxs-lookup"><span data-stu-id="ba64d-193">You can also use the sample .csv file provided from the link next to **Add devices** to create a device list.</span></span>

## <a name="windows-autopilot-eula-dismissal"></a><span data-ttu-id="ba64d-194">Windows Autopilot EULA dismissal</span><span class="sxs-lookup"><span data-stu-id="ba64d-194">Windows Autopilot EULA dismissal</span></span>

### <a name="important-information"></a><span data-ttu-id="ba64d-195">重要資訊</span><span class="sxs-lookup"><span data-stu-id="ba64d-195">IMPORTANT INFORMATION</span></span>

<span data-ttu-id="ba64d-196">Windows Autopilot 可讓您為您的客戶管理的裝置上設定的 Windows 自訂的安裝。</span><span class="sxs-lookup"><span data-stu-id="ba64d-196">Windows Autopilot allows you to configure customized installations of Windows on devices you manage for your customers.</span></span> <span data-ttu-id="ba64d-197">如果客戶授權若要這樣做，您可以隱藏或隱藏時，Windows，包括使用者授權合約 （終端使用者授權合約） 接受畫面會正常呈現給使用者特定設定畫面。</span><span class="sxs-lookup"><span data-stu-id="ba64d-197">If authorized to do so by the customer, you can suppress or hide certain set-up screens that are normally presented to users when setting up Windows, including the EULA (End User License Agreement) acceptance screen.</span></span>

<span data-ttu-id="ba64d-198">使用此函式，即表示您同意，隱藏或隱藏專為使用者提供通知或接受條款表示您已從您的客戶代表隱藏字詞，而且您，取得足夠的同意和授權的任何畫面客戶 （不論組織或個別使用者與案例可能），任何聲明同意並接受任何條款適用於您的客戶。</span><span class="sxs-lookup"><span data-stu-id="ba64d-198">By using this function, you agree that suppressing or hiding any screens that are designed to provide users with notice or acceptance of terms means that you have obtained sufficient consent and authorization from your customer to hide terms, and that you, on behalf of your customer (whether an organization or an individual user as the case may be), consent to any notices and accept any terms that are applicable to your customer.</span></span> <span data-ttu-id="ba64d-199">這包括同意授權條款和條件，或若未使用此工具抑制或隱藏時會對使用者顯示的通知。</span><span class="sxs-lookup"><span data-stu-id="ba64d-199">This includes agreement to the terms and conditions of the license or notice that would be presented to the user if you did not suppress or hide it using this tool.</span></span> <span data-ttu-id="ba64d-200">您的客戶不可在這些裝置上使用 Windows 軟體，如果他們未向 Microsoft 或其授權經銷商有效取得軟體授權。</span><span class="sxs-lookup"><span data-stu-id="ba64d-200">Your customer may not use the Windows software on those devices if the customer has not validly acquired a license for the software from Microsoft or its licensed distributors.</span></span>