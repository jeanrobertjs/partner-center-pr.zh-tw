---
title: "透過 Windows Autopilot 簡化裝置設定 | 合作夥伴中心"
description: "在合作夥伴中心新增 Windows AutoPilot 部署設定檔，以透過 Windows Autopilot 簡化裝置設定"
author: KPacquer
keywords: "autopilot, windows autopilot, microsoft autopilot, 全自動部署, oobe, 登入畫面"
robots: NOINDEX,NOFOLLOW
ms.openlocfilehash: aa650ee5f2848694fe44d4751d52f8014e0d22a8
ms.sourcegitcommit: e8b504fa98b3ec4c7c8fd954f63ea81299791906
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 07/01/2017
---
# <a name="simplify-device-setup-with-windows-autopilot"></a><span data-ttu-id="4c4a4-104">透過 Windows Autopilot 簡化裝置設定</span><span class="sxs-lookup"><span data-stu-id="4c4a4-104">Simplify device setup with Windows Autopilot</span></span> 

<span data-ttu-id="4c4a4-105">只需幾個步驟，Windows Autopilot 即可從第一次開機開始精簡並保護新的 Windows 10 專業版裝置的裝置設定。</span><span class="sxs-lookup"><span data-stu-id="4c4a4-105">Windows Autopilot streamlines and secures device setup for new Windows 10 Pro devices from first boot in only a few steps.</span></span> <span data-ttu-id="4c4a4-106">若要深入了解，請參閱 [Windows AutoPilot 概觀](https://docs.microsoft.com/windows/deployment/windows-10-auto-pilot)。</span><span class="sxs-lookup"><span data-stu-id="4c4a4-106">To learn more, see [Overview of Windows AutoPilot](https://docs.microsoft.com/windows/deployment/windows-10-auto-pilot).</span></span>

## <a name="features"></a><span data-ttu-id="4c4a4-107">功能</span><span class="sxs-lookup"><span data-stu-id="4c4a4-107">Features</span></span>

*  <span data-ttu-id="4c4a4-108">**\[停用本機系統管理員權限\]**，適用於設定裝置的使用者</span><span class="sxs-lookup"><span data-stu-id="4c4a4-108">**Disable local administrator permissions** for the end users setting up devices</span></span>
*  <span data-ttu-id="4c4a4-109">**\[顯示組織的登入頁面\]**。</span><span class="sxs-lookup"><span data-stu-id="4c4a4-109">**Show an organization's login page**.</span></span> <span data-ttu-id="4c4a4-110">組織可以預先定義登入頁面，這個頁面會新增裝置做為工作裝置，並將裝置與 Azure Active Directory 聯結。</span><span class="sxs-lookup"><span data-stu-id="4c4a4-110">The organization can predefine a logon page that adds the device as a work device, and joins the device with Azure Active Directory.</span></span>
*  <span data-ttu-id="4c4a4-111">OOBE 完成後，**\[在 Mobile Device Manager (MDM) 中註冊裝置\]** (例如：Microsoft Intune)。</span><span class="sxs-lookup"><span data-stu-id="4c4a4-111">**Enroll the device into a Mobile Device Manager (MDM)**, for example: Microsoft Intune, after OOBE is complete.</span></span>
*  <span data-ttu-id="4c4a4-112">**\[簡化全新體驗 (OOBE)\]**，可透過 Windows AutoPilot 部署設定檔，只使用必要的步驟和決策。</span><span class="sxs-lookup"><span data-stu-id="4c4a4-112">**Streamline the out-of-box experience (OOBE)** to use just the steps and decisions required, using a Windows AutoPilot Deployment profile.</span></span> 

## <a name="requirements"></a><span data-ttu-id="4c4a4-113">需求</span><span class="sxs-lookup"><span data-stu-id="4c4a4-113">Requirements</span></span>

*  <span data-ttu-id="4c4a4-114">預先安裝 Windows 10 專業版 Creators Update (版本 1703 或更新版本) 的裝置</span><span class="sxs-lookup"><span data-stu-id="4c4a4-114">Devices pre-installed with Windows 10 Pro Creators Update (version 1703 or later)</span></span>
*  <span data-ttu-id="4c4a4-115">稱為硬體雜湊 (128 HWH 或 4k HWH) 的裝置識別碼，通常由 OEM 提供。</span><span class="sxs-lookup"><span data-stu-id="4c4a4-115">Device identifier known as a hardware hash (128 HWH or 4k HWH), which is typically provided by an OEM.</span></span> <span data-ttu-id="4c4a4-116">您可以使用識別碼，在合作夥伴中心指派組織設定檔。</span><span class="sxs-lookup"><span data-stu-id="4c4a4-116">You'll use identifiers to assign organization profiles in Partner Center.</span></span> <span data-ttu-id="4c4a4-117">2017 年 8 月之後，將不再需要硬體雜湊。</span><span class="sxs-lookup"><span data-stu-id="4c4a4-117">After August 2017 you will no longer need the hardware hash.</span></span> 
*  <span data-ttu-id="4c4a4-118">裝置必須能夠存取網際網路。</span><span class="sxs-lookup"><span data-stu-id="4c4a4-118">The devices must have access to the internet.</span></span> <span data-ttu-id="4c4a4-119">當裝置無法連線時，會顯示預設 Windows 全新體驗 (OOBE) 畫面。</span><span class="sxs-lookup"><span data-stu-id="4c4a4-119">When the device can’t connect, it shows the default Windows out-of-box experience (OOBE) screens.</span></span>
*  <span data-ttu-id="4c4a4-120">在 MDM 中註冊裝置必須有 Azure Active Directory Premium。</span><span class="sxs-lookup"><span data-stu-id="4c4a4-120">Enrolling the device into an MDM requires Azure Active Directory Premium.</span></span>

## <a name="add-organization-login-pages-to-oobe"></a><span data-ttu-id="4c4a4-121">將組織登入頁面新增至 OOBE</span><span class="sxs-lookup"><span data-stu-id="4c4a4-121">Add organization login pages to OOBE</span></span>

<span data-ttu-id="4c4a4-122">若要新增組織專屬頁面，請將裝置新增至組織的 [Azure AD 目錄](https://go.microsoft.com/fwlink/?linkid=848958)並建立登入頁面。</span><span class="sxs-lookup"><span data-stu-id="4c4a4-122">To add organization-specific pages, add the devices into your organization’s [Azure AD directory](https://go.microsoft.com/fwlink/?linkid=848958) and create login pages.</span></span>


## <a name="remove-windows-pages-from-oobe-with-a-windows-autopilot-deployment-profile"></a><span data-ttu-id="4c4a4-123">使用 Windows AutoPilot 設定檔從 OOBE 移除 Windows 頁面</span><span class="sxs-lookup"><span data-stu-id="4c4a4-123">Remove Windows pages from OOBE with a Windows AutoPilot deployment profile</span></span>

### <a name="examples-of-settings-in-a-windows-autopilot-deployment-profile"></a><span data-ttu-id="4c4a4-124">Windows AutoPilot 部署設定檔中的設定範例</span><span class="sxs-lookup"><span data-stu-id="4c4a4-124">Examples of settings in a Windows AutoPilot deployment profile</span></span>
*  <span data-ttu-id="4c4a4-125">略過設定中的隱私權設定</span><span class="sxs-lookup"><span data-stu-id="4c4a4-125">Skip Privacy Settings in setup</span></span>
*  <span data-ttu-id="4c4a4-126">停用設定中的本機系統管理員帳戶</span><span class="sxs-lookup"><span data-stu-id="4c4a4-126">Disable local admin account in setup</span></span>
*  <span data-ttu-id="4c4a4-127">自動略過設定中的頁面</span><span class="sxs-lookup"><span data-stu-id="4c4a4-127">Automatically skip pages in setup</span></span>
   *  <span data-ttu-id="4c4a4-128">自動選取公司或學校的設定</span><span class="sxs-lookup"><span data-stu-id="4c4a4-128">Automatically select setup for work or school</span></span>
   *  <span data-ttu-id="4c4a4-129">略過 Cortana、OneDrive 及 OEM 註冊設定頁面</span><span class="sxs-lookup"><span data-stu-id="4c4a4-129">Skip Cortana, OneDrive, and OEM registration setup pages</span></span>

### <a name="add-devices-and-apply-a-profile"></a><span data-ttu-id="4c4a4-130">新增裝置並套用設定檔</span><span class="sxs-lookup"><span data-stu-id="4c4a4-130">Add devices and apply a profile</span></span>

<span data-ttu-id="4c4a4-131">您可以在合作夥伴中心建立 Windows AutoPilot 部署設定檔，並將其套用至裝置清單。</span><span class="sxs-lookup"><span data-stu-id="4c4a4-131">In Partner Center, you can create a Windows AutoPilot deployment profile and apply it to a list of the devices.</span></span>

<span data-ttu-id="4c4a4-132">若要進行裝置設定，請將裝置清單上傳至合作夥伴中心、建立適用於這些裝置的設定檔，然後加以套用。</span><span class="sxs-lookup"><span data-stu-id="4c4a4-132">To configure devices, upload a list of the devices into Partner Center, create a profile that applies to the devices, and apply it.</span></span>

1.  <span data-ttu-id="4c4a4-133">將裝置清單新增至合作夥伴中心</span><span class="sxs-lookup"><span data-stu-id="4c4a4-133">Add the list of devices into Partner Center.</span></span> <span data-ttu-id="4c4a4-134">(銷售專員和系統管理代理人擁有可將裝置清單新增至合作夥伴中心的存取權)。</span><span class="sxs-lookup"><span data-stu-id="4c4a4-134">(Sales agents and admin agents have access to add the list of devices into Partner Center.)</span></span>

    <span data-ttu-id="4c4a4-135">a.</span><span class="sxs-lookup"><span data-stu-id="4c4a4-135">a.</span></span>  <span data-ttu-id="4c4a4-136">使用下列主題中的 PowerShell 指令碼建立 .csv 檔案：[Windows AutoPilot 概觀](https://docs.microsoft.com/windows/deployment/windows-10-auto-pilot)。</span><span class="sxs-lookup"><span data-stu-id="4c4a4-136">Create a .csv file using the PowerShell script from the topic: [Overview of Windows AutoPilot](https://docs.microsoft.com/windows/deployment/windows-10-auto-pilot).</span></span> <span data-ttu-id="4c4a4-137">這個 .csv 檔案內含裝置資訊，包括序號、OEM 名稱、型號名稱、產品識別碼和裝置識別碼。</span><span class="sxs-lookup"><span data-stu-id="4c4a4-137">This .csv file contains device info including the serial number, OEM name, model name, product ID and device identifier.</span></span> 

    <span data-ttu-id="4c4a4-138">b.</span><span class="sxs-lookup"><span data-stu-id="4c4a4-138">b.</span></span>  <span data-ttu-id="4c4a4-139">從 [合作夥伴中心] 儀表板，移至 **\[客戶\]**> 選取收到裝置的客戶 >**\[裝置\] > \[新增裝置\]**。</span><span class="sxs-lookup"><span data-stu-id="4c4a4-139">From the Partner Center dashboard, go to **Customers** > select the customer that’s receiving the devices > **Devices > Add devices**.</span></span>

    <span data-ttu-id="4c4a4-140">c.</span><span class="sxs-lookup"><span data-stu-id="4c4a4-140">c.</span></span>  <span data-ttu-id="4c4a4-141">命名裝置批次，例如「Contoso 銷售部門電腦 – 2017 年 4 月訂單」。</span><span class="sxs-lookup"><span data-stu-id="4c4a4-141">Name the batch of devices, for example, “Contoso Sales Department PCs – April 2017 order.”</span></span> 

    <span data-ttu-id="4c4a4-142">d.</span><span class="sxs-lookup"><span data-stu-id="4c4a4-142">d.</span></span>  <span data-ttu-id="4c4a4-143">按一下 **\[瀏覽\]** > 選取裝置資訊檔案 > **\[驗證\]**。</span><span class="sxs-lookup"><span data-stu-id="4c4a4-143">Click **Browse** > select the device info file > **Validate**.</span></span>

    <span data-ttu-id="4c4a4-144">**注意：**如果您在嘗試上傳 .csv 檔案後收到錯誤訊息，請檢查檔案的格式。</span><span class="sxs-lookup"><span data-stu-id="4c4a4-144">**Note:** If you get an error message after trying to upload the .csv file, check the format of the file.</span></span> <span data-ttu-id="4c4a4-145">8 月之後，您可以只使用 [硬體雜湊]，或使用 OEM 名稱、序號和型號等欄位 (依此順序)，或是 Windows 產品識別碼。</span><span class="sxs-lookup"><span data-stu-id="4c4a4-145">After August, you can use the Hardware Hash only, or the OEM name, serial number, and model in that column order, or the Windows Product ID.</span></span> <span data-ttu-id="4c4a4-146">您也可以使用 **\[新增裝置\]** 旁邊連結所提供的範例 .csv 檔案。</span><span class="sxs-lookup"><span data-stu-id="4c4a4-146">You can also use the sample .csv file provided from the link next to **Add devices**.</span></span>

2.  <span data-ttu-id="4c4a4-147">建立可套用至裝置的設定檔</span><span class="sxs-lookup"><span data-stu-id="4c4a4-147">Create a profile that you can apply to the devices.</span></span> <span data-ttu-id="4c4a4-148">(只有系統管理代理人擁有可在合作夥伴中心建立和套用設定檔的存取權)。</span><span class="sxs-lookup"><span data-stu-id="4c4a4-148">(Only admin agents have access to create and apply profiles in Partner Center.)</span></span>

    <span data-ttu-id="4c4a4-149">a.</span><span class="sxs-lookup"><span data-stu-id="4c4a4-149">a.</span></span>  <span data-ttu-id="4c4a4-150">在 **\[裝置\]** 中按一下 **\[新增設定檔\]**。</span><span class="sxs-lookup"><span data-stu-id="4c4a4-150">From **Devices**, click **Add new profile**.</span></span>

    <span data-ttu-id="4c4a4-151">b.</span><span class="sxs-lookup"><span data-stu-id="4c4a4-151">b.</span></span>  <span data-ttu-id="4c4a4-152">命名設定檔，例如「Contoso 桌面設定檔 – 略過所有 OOBE」。</span><span class="sxs-lookup"><span data-stu-id="4c4a4-152">Name the profile, for example, “Contoso Desktop Profile – Skip All OOBE”.</span></span>

    <span data-ttu-id="4c4a4-153">c.</span><span class="sxs-lookup"><span data-stu-id="4c4a4-153">c.</span></span>  <span data-ttu-id="4c4a4-154">設定 OOBE 設定。</span><span class="sxs-lookup"><span data-stu-id="4c4a4-154">Configure the OOBE settings.</span></span> <span data-ttu-id="4c4a4-155">例如，核取設定中的 **\[略過快速設定\]**。</span><span class="sxs-lookup"><span data-stu-id="4c4a4-155">For example, check **Skip Express Settings in setup**.</span></span>

    <span data-ttu-id="4c4a4-156">d.</span><span class="sxs-lookup"><span data-stu-id="4c4a4-156">d.</span></span>  <span data-ttu-id="4c4a4-157">按一下 **\[提交\]**。</span><span class="sxs-lookup"><span data-stu-id="4c4a4-157">Click **Submit**.</span></span>

3.  <span data-ttu-id="4c4a4-158">套用設定檔。</span><span class="sxs-lookup"><span data-stu-id="4c4a4-158">Apply the profile.</span></span>

    <span data-ttu-id="4c4a4-159">a.</span><span class="sxs-lookup"><span data-stu-id="4c4a4-159">a.</span></span>  <span data-ttu-id="4c4a4-160">從 **\[裝置\]** 的 **\[指派和刪除裝置\]** 窗格中選取您想要設定的裝置。</span><span class="sxs-lookup"><span data-stu-id="4c4a4-160">From **Devices**, in the **Assign and delete devices** pane, select the devices that you want to configure.</span></span> <span data-ttu-id="4c4a4-161">若要選取整個批次，請按一下批次名稱 (例如「Contoso 銷售部門電腦 – 2017 年 3 月訂單」) 旁邊的核取方塊。</span><span class="sxs-lookup"><span data-stu-id="4c4a4-161">To select an entire batch, click the checkbox next to the batch name (for example, “Contoso Sales Department PCs – March 2017 order”).</span></span>

    <span data-ttu-id="4c4a4-162">b.</span><span class="sxs-lookup"><span data-stu-id="4c4a4-162">b.</span></span>  <span data-ttu-id="4c4a4-163">按一下 **\[套用設定檔\]**，然後選取設定檔 (例如「Contoso 桌面設定檔 – 略過所有 OOBE」)。</span><span class="sxs-lookup"><span data-stu-id="4c4a4-163">Click **Apply profile**, and select the profile (for example, “Contoso Desktop Profile – Skip All OOBE”).</span></span> <span data-ttu-id="4c4a4-164">裝置會在 [設定檔] 欄中顯示設定檔。</span><span class="sxs-lookup"><span data-stu-id="4c4a4-164">The devices will show the profile in the Profile column.</span></span>

4.  <span data-ttu-id="4c4a4-165">選用：測試看看您的設定檔是否有作用。</span><span class="sxs-lookup"><span data-stu-id="4c4a4-165">Optional: Test to see that your profile works.</span></span>

    <span data-ttu-id="4c4a4-166">a.</span><span class="sxs-lookup"><span data-stu-id="4c4a4-166">a.</span></span>  <span data-ttu-id="4c4a4-167">將裝置連線至網路並開啟。</span><span class="sxs-lookup"><span data-stu-id="4c4a4-167">Connect a device to the network, and turn it on.</span></span>

    <span data-ttu-id="4c4a4-168">b.</span><span class="sxs-lookup"><span data-stu-id="4c4a4-168">b.</span></span>  <span data-ttu-id="4c4a4-169">確認是否會顯示適當的 OOBE 畫面 (如果有的話)。</span><span class="sxs-lookup"><span data-stu-id="4c4a4-169">Verify that the appropriate OOBE screens (if any) appear.</span></span>

    <span data-ttu-id="4c4a4-170">c.</span><span class="sxs-lookup"><span data-stu-id="4c4a4-170">c.</span></span>  <span data-ttu-id="4c4a4-171">若要為新的使用者準備裝置，請完成 OOBE 體驗，然後將裝置重設為原廠預設設定。</span><span class="sxs-lookup"><span data-stu-id="4c4a4-171">To prepare the device for a new user, complete the OOBE experience, then reset the device to its factory default settings.</span></span>


## <a name="to-update-or-delete-a-profile"></a><span data-ttu-id="4c4a4-172">若要更新或刪除設定檔</span><span class="sxs-lookup"><span data-stu-id="4c4a4-172">To update or delete a profile</span></span> 

<span data-ttu-id="4c4a4-173">將設定檔指派給裝置後，就可以將其更新，即使您已經將裝置交給客戶，也能更新。</span><span class="sxs-lookup"><span data-stu-id="4c4a4-173">Once you’ve assigned a profile to a device, you can update it, even if you’ve already given the device to your customer.</span></span> <span data-ttu-id="4c4a4-174">當裝置連線至網際網路時，會在 OOBE 程序中下載您最新版本的設定檔。</span><span class="sxs-lookup"><span data-stu-id="4c4a4-174">When the device connects to the internet, it downloads the latest version of your profile during the OOBE process.</span></span> <span data-ttu-id="4c4a4-175">如果客戶將其裝置還原為原廠預設設定，裝置將會重新下載設定檔的最新更新。</span><span class="sxs-lookup"><span data-stu-id="4c4a4-175">If your customer restores their device to its factory default settings, the device will again download the latest updates to your profile.</span></span> 

###<a name="you-can-remove-a-profile-from-a-device"></a><span data-ttu-id="4c4a4-176">您可以從裝置移除設定檔</span><span class="sxs-lookup"><span data-stu-id="4c4a4-176">You can remove a profile from a device</span></span>
1. <span data-ttu-id="4c4a4-177">選取您要從中移除設定檔的裝置 (或裝置批次)。</span><span class="sxs-lookup"><span data-stu-id="4c4a4-177">Select the device (or batch of devices) you want to remove the profile from.</span></span> 

2. <span data-ttu-id="4c4a4-178">在 **\[指派和刪除裝置\]** 窗格中選取 **\[移除設定檔\]**。</span><span class="sxs-lookup"><span data-stu-id="4c4a4-178">In **Assign and delete devices** pane, select **Remove profile**.</span></span>

3. <span data-ttu-id="4c4a4-179">移至您要移除和刪除的設定檔。</span><span class="sxs-lookup"><span data-stu-id="4c4a4-179">Go to the profile you want to remove and delete it.</span></span> <span data-ttu-id="4c4a4-180">設定檔將會從所有裝置中刪除。</span><span class="sxs-lookup"><span data-stu-id="4c4a4-180">The profile will be deleted from all devices.</span></span>

<span data-ttu-id="4c4a4-181">從 **\[裝置\]** 選取設定檔。</span><span class="sxs-lookup"><span data-stu-id="4c4a4-181">From **Devices**, select the profile.</span></span> <span data-ttu-id="4c4a4-182">您可以在此處修改現有的設定。</span><span class="sxs-lookup"><span data-stu-id="4c4a4-182">From here, you can modify the existing settings.</span></span>
