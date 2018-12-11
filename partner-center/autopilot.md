---
title: 透過 Windows Autopilot 簡化裝置設定 | 合作夥伴中心
ms.topic: article
ms.date: 10/29/2018
description: 在合作夥伴中心新增 Windows AutoPilot 部署設定檔，以透過 Windows Autopilot 簡化裝置設定
author: KPacquer
ms.author: kenpacq
keywords: autopilot, windows autopilot, microsoft autopilot, 全自動部署, oobe, 登入畫面
ms.localizationpriority: medium
ms.openlocfilehash: 3d6e6e015424eb8be83bae21b2e15bdc072e480b
ms.sourcegitcommit: 777225c8bf16e4a8811a9d88aceb45fcba1cd959
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 12/11/2018
ms.locfileid: "8917560"
---
<!--Maggie, 12/7/18 - removed line telling indirect resellers to go through their indirect providers for autopilot stuff as per Bhavya Chopra in bug 19841770.-->

# <a name="simplify-device-setup-with-windows-autopilot"></a><span data-ttu-id="81b97-104">透過 Windows Autopilot 簡化裝置設定</span><span class="sxs-lookup"><span data-stu-id="81b97-104">Simplify device setup with Windows Autopilot</span></span> 

<span data-ttu-id="81b97-105">只需幾個步驟，Windows Autopilot 即可從第一次開機開始精簡並保護新的 Windows 10 專業版裝置的裝置設定。</span><span class="sxs-lookup"><span data-stu-id="81b97-105">Windows Autopilot streamlines and secures device setup for new Windows 10 Pro devices from first boot in only a few steps.</span></span> <span data-ttu-id="81b97-106">若要深入了解，請參閱 [Windows AutoPilot 概觀](https://docs.microsoft.com/windows/deployment/windows-10-auto-pilot)。</span><span class="sxs-lookup"><span data-stu-id="81b97-106">To learn more, see [Overview of Windows AutoPilot](https://docs.microsoft.com/windows/deployment/windows-10-auto-pilot).</span></span>

## <a name="features"></a><span data-ttu-id="81b97-107">功能</span><span class="sxs-lookup"><span data-stu-id="81b97-107">Features</span></span>

- <span data-ttu-id="81b97-108">**\[停用本機系統管理員權限\]**，適用於設定裝置的使用者</span><span class="sxs-lookup"><span data-stu-id="81b97-108">**Disable local administrator permissions** for the end users setting up devices</span></span>
- <span data-ttu-id="81b97-109">**\[顯示組織的登入頁面\]**。</span><span class="sxs-lookup"><span data-stu-id="81b97-109">**Show an organization's login page**.</span></span> <span data-ttu-id="81b97-110">組織可以預先定義的登入頁面，做為工作裝置，新增裝置，並將裝置與 Azure Active Directory。</span><span class="sxs-lookup"><span data-stu-id="81b97-110">The organization can pre-define a logon page that adds the device as a work device, and joins the device with Azure Active Directory.</span></span>
- <span data-ttu-id="81b97-111">OOBE 完成後，**\[在 Mobile Device Manager (MDM) 中註冊裝置\]** (例如：Microsoft Intune)。</span><span class="sxs-lookup"><span data-stu-id="81b97-111">**Enroll the device into a Mobile Device Manager (MDM)**, for example: Microsoft Intune, after OOBE is complete.</span></span>
- <span data-ttu-id="81b97-112">**\[簡化全新體驗 (OOBE)\]**，可透過 Windows AutoPilot 部署設定檔，只使用必要的步驟和決策。</span><span class="sxs-lookup"><span data-stu-id="81b97-112">**Streamline the out-of-box experience (OOBE)** to use just the steps and decisions required, using a Windows AutoPilot Deployment profile.</span></span>

## <a name="requirements"></a><span data-ttu-id="81b97-113">需求</span><span class="sxs-lookup"><span data-stu-id="81b97-113">Requirements</span></span>

- <span data-ttu-id="81b97-114">已預先安裝 Windows 10 專業版 Creators Update (1703 版或更新版本) 或 Windows 10 Pro for Advanced PCs 的裝置。</span><span class="sxs-lookup"><span data-stu-id="81b97-114">Devices pre-installed with Windows 10 Pro Creators Update (version 1703 or later) or Windows 10 Pro for Advanced PCs.</span></span>
- <span data-ttu-id="81b97-115">稱為硬體雜湊 (128 HWH 或 4k HWH) 的裝置識別碼，通常由 OEM 提供。</span><span class="sxs-lookup"><span data-stu-id="81b97-115">Device identifier known as a hardware hash (128 HWH or 4k HWH), which is typically provided by an OEM.</span></span> <span data-ttu-id="81b97-116">您可以使用識別碼指派組織設定檔，在合作夥伴中心。</span><span class="sxs-lookup"><span data-stu-id="81b97-116">You'll use identifiers to assign organization profiles in the Partner Center.</span></span>
- <span data-ttu-id="81b97-117">裝置必須能夠存取網際網路。</span><span class="sxs-lookup"><span data-stu-id="81b97-117">The devices must have access to the internet.</span></span> <span data-ttu-id="81b97-118">當裝置無法連線時，會顯示預設 Windows 全新體驗 (OOBE) 畫面。</span><span class="sxs-lookup"><span data-stu-id="81b97-118">When the device can’t connect, it shows the default Windows out-of-box experience (OOBE) screens.</span></span>
- <span data-ttu-id="81b97-119">在 MDM 中註冊裝置必須有 Azure Active Directory Premium。</span><span class="sxs-lookup"><span data-stu-id="81b97-119">Enrolling the device into an MDM requires Azure Active Directory Premium.</span></span>

## <a name="add-company-branded-sign-in-pages-to-oobe"></a><span data-ttu-id="81b97-120">將公司品牌登入頁面新增至 OOBE</span><span class="sxs-lookup"><span data-stu-id="81b97-120">Add company-branded sign-in pages to OOBE</span></span>

<span data-ttu-id="81b97-121">若要新增公司專屬頁面，將裝置加入到您的公司[的 Azure AD 目錄](https://go.microsoft.com/fwlink/?linkid=848958)，並建立登入頁面。</span><span class="sxs-lookup"><span data-stu-id="81b97-121">To add company-specific pages, add the devices into your company's [Azure AD directory](https://go.microsoft.com/fwlink/?linkid=848958) and create login pages.</span></span>

## <a name="remove-windows-pages-from-oobe-with-a-windows-autopilot-deployment-profile"></a><span data-ttu-id="81b97-122">使用 Windows AutoPilot 設定檔從 OOBE 移除 Windows 頁面</span><span class="sxs-lookup"><span data-stu-id="81b97-122">Remove Windows pages from OOBE with a Windows AutoPilot deployment profile</span></span>

### <a name="examples-of-settings-in-a-windows-autopilot-deployment-profile"></a><span data-ttu-id="81b97-123">Windows AutoPilot 部署設定檔中的設定範例</span><span class="sxs-lookup"><span data-stu-id="81b97-123">Examples of settings in a Windows AutoPilot deployment profile</span></span>

- <span data-ttu-id="81b97-124">略過設定中的隱私權設定</span><span class="sxs-lookup"><span data-stu-id="81b97-124">Skip Privacy Settings in setup</span></span>
- <span data-ttu-id="81b97-125">停用設定中的本機系統管理員帳戶</span><span class="sxs-lookup"><span data-stu-id="81b97-125">Disable local admin account in setup</span></span>
- <span data-ttu-id="81b97-126">自動略過設定中的頁面</span><span class="sxs-lookup"><span data-stu-id="81b97-126">Automatically skip pages in setup</span></span>
  - <span data-ttu-id="81b97-127">自動選取公司或學校的設定</span><span class="sxs-lookup"><span data-stu-id="81b97-127">Automatically select setup for work or school</span></span>
  - <span data-ttu-id="81b97-128">略過 Cortana、OneDrive 及 OEM 註冊設定頁面</span><span class="sxs-lookup"><span data-stu-id="81b97-128">Skip Cortana, OneDrive, and OEM registration setup pages</span></span>

### <a name="add-devices-and-apply-a-profile"></a><span data-ttu-id="81b97-129">新增裝置並套用設定檔</span><span class="sxs-lookup"><span data-stu-id="81b97-129">Add devices and apply a profile</span></span>

<span data-ttu-id="81b97-130">從合作夥伴中心，您可以建立 Windows AutoPilot 部署設定檔，並將它套用到裝置的清單。</span><span class="sxs-lookup"><span data-stu-id="81b97-130">From Partner Center, you can create a Windows AutoPilot deployment profile and apply it to a list of the devices.</span></span>

<span data-ttu-id="81b97-131">若要進行裝置設定，請上傳裝置清單、建立適用於這些裝置的設定檔，然後加以套用。</span><span class="sxs-lookup"><span data-stu-id="81b97-131">To configure devices, upload a list of the devices, create a profile that applies to the devices, and apply it.</span></span>

1.  <span data-ttu-id="81b97-132">新增裝置清單。</span><span class="sxs-lookup"><span data-stu-id="81b97-132">Add the list of devices.</span></span>

    <span data-ttu-id="81b97-133">銷售代理人和系統管理代理人擁有將裝置清單新增至合作夥伴中心的存取權限。</span><span class="sxs-lookup"><span data-stu-id="81b97-133">Sales agents and admin agents have access to add the list of devices into Partner Center.</span></span>

    <span data-ttu-id="81b97-134">a.</span><span class="sxs-lookup"><span data-stu-id="81b97-134">a.</span></span> <span data-ttu-id="81b97-135">建立.csv 檔案，使用[Windows AutoPilot 概觀](https://docs.microsoft.com/windows/deployment/windows-10-auto-pilot)主題中的 PowerShell 指令碼。</span><span class="sxs-lookup"><span data-stu-id="81b97-135">Create a .csv file using the PowerShell script from the topic [Overview of Windows AutoPilot](https://docs.microsoft.com/windows/deployment/windows-10-auto-pilot).</span></span> <span data-ttu-id="81b97-136">這個 .csv 檔案內含裝置資訊，包括序號、OEM 名稱、型號名稱、產品識別碼和裝置識別碼。</span><span class="sxs-lookup"><span data-stu-id="81b97-136">This .csv file contains device info including the serial number, OEM name, model name, product ID and device identifier.</span></span> 

    <span data-ttu-id="81b97-137">b.</span><span class="sxs-lookup"><span data-stu-id="81b97-137">b.</span></span> <span data-ttu-id="81b97-138">從合作夥伴中心，移至**客戶**> 選取收到裝置的客戶 >**裝置 > 將裝置新增**。</span><span class="sxs-lookup"><span data-stu-id="81b97-138">From Partner Center, go to **Customers** > select the customer that’s receiving the devices > **Devices > Add devices**.</span></span>

    <span data-ttu-id="81b97-139">c.</span><span class="sxs-lookup"><span data-stu-id="81b97-139">c.</span></span> <span data-ttu-id="81b97-140">命名裝置批次，例如「Contoso 銷售部門電腦 – 2017 年 4 月訂單」。</span><span class="sxs-lookup"><span data-stu-id="81b97-140">Name the batch of devices, for example, “Contoso Sales Department PCs – April 2017 order.”</span></span> 

    <span data-ttu-id="81b97-141">d.</span><span class="sxs-lookup"><span data-stu-id="81b97-141">d.</span></span> <span data-ttu-id="81b97-142">選取 [**瀏覽**> 選取裝置資訊檔案 >**驗證**。</span><span class="sxs-lookup"><span data-stu-id="81b97-142">Select **Browse** > select the device info file > **Validate**.</span></span>

    <span data-ttu-id="81b97-143">**注意：** 如果您在嘗試上傳 .csv 檔案後收到錯誤訊息，請檢查檔案的格式。</span><span class="sxs-lookup"><span data-stu-id="81b97-143">**Note:** If you get an error message after trying to upload the .csv file, check the format of the file.</span></span> <span data-ttu-id="81b97-144">8 月之後，您可以只使用 [硬體雜湊]，或使用 OEM 名稱、序號和型號等欄位 (依此順序)，或是 Windows 產品識別碼。</span><span class="sxs-lookup"><span data-stu-id="81b97-144">After August, you can use the Hardware Hash only, or the OEM name, serial number, and model in that column order, or the Windows Product ID.</span></span> <span data-ttu-id="81b97-145">您也可以使用 **\[新增裝置\]** 旁邊連結所提供的範例 .csv 檔案。</span><span class="sxs-lookup"><span data-stu-id="81b97-145">You can also use the sample .csv file provided from the link next to **Add devices**.</span></span>

2.  <span data-ttu-id="81b97-146">建立可套用至裝置的設定檔</span><span class="sxs-lookup"><span data-stu-id="81b97-146">Create a profile that you can apply to the devices.</span></span> <span data-ttu-id="81b97-147">（只有系統管理代理人擁有可建立和套用設定檔，在合作夥伴中心的存取權）。</span><span class="sxs-lookup"><span data-stu-id="81b97-147">(Only admin agents have access to create and apply profiles in the Partner Center.)</span></span>

    <span data-ttu-id="81b97-148">a.</span><span class="sxs-lookup"><span data-stu-id="81b97-148">a.</span></span>  <span data-ttu-id="81b97-149">從**裝置**中，選取 [**加入新的設定檔**。</span><span class="sxs-lookup"><span data-stu-id="81b97-149">From **Devices**, select **Add new profile**.</span></span>

    <span data-ttu-id="81b97-150">b.</span><span class="sxs-lookup"><span data-stu-id="81b97-150">b.</span></span>  <span data-ttu-id="81b97-151">命名設定檔，例如「Contoso 桌面設定檔 – 略過所有 OOBE」。</span><span class="sxs-lookup"><span data-stu-id="81b97-151">Name the profile, for example, “Contoso Desktop Profile – Skip All OOBE”.</span></span>

    <span data-ttu-id="81b97-152">c.</span><span class="sxs-lookup"><span data-stu-id="81b97-152">c.</span></span>  <span data-ttu-id="81b97-153">設定 OOBE 設定。</span><span class="sxs-lookup"><span data-stu-id="81b97-153">Configure the OOBE settings.</span></span> <span data-ttu-id="81b97-154">例如，核取設定中的 **\[略過快速設定\]**。</span><span class="sxs-lookup"><span data-stu-id="81b97-154">For example, check **Skip Express Settings in setup**.</span></span>

    <span data-ttu-id="81b97-155">d.</span><span class="sxs-lookup"><span data-stu-id="81b97-155">d.</span></span>  <span data-ttu-id="81b97-156">選取 **\[提交\]**。</span><span class="sxs-lookup"><span data-stu-id="81b97-156">Select **Submit**.</span></span>

3.  <span data-ttu-id="81b97-157">套用設定檔。</span><span class="sxs-lookup"><span data-stu-id="81b97-157">Apply the profile.</span></span>

    <span data-ttu-id="81b97-158">a.</span><span class="sxs-lookup"><span data-stu-id="81b97-158">a.</span></span>  <span data-ttu-id="81b97-159">從 **\[裝置\]** 的 **\[指派和刪除裝置\]** 窗格中選取您想要設定的裝置。</span><span class="sxs-lookup"><span data-stu-id="81b97-159">From **Devices**, in the **Assign and delete devices** pane, select the devices that you want to configure.</span></span> <span data-ttu-id="81b97-160">若要選取整個批次，請按一下批次名稱 (例如「Contoso 銷售部門電腦 – 2017 年 3 月訂單」) 旁邊的核取方塊。</span><span class="sxs-lookup"><span data-stu-id="81b97-160">To select an entire batch, click the checkbox next to the batch name (for example, “Contoso Sales Department PCs – March 2017 order”).</span></span>

    <span data-ttu-id="81b97-161">b.</span><span class="sxs-lookup"><span data-stu-id="81b97-161">b.</span></span>  <span data-ttu-id="81b97-162">選取**套用設定檔**，然後選取設定檔 (例如，「 Contoso 桌面設定檔 – 略過所有 OOBE 」)。</span><span class="sxs-lookup"><span data-stu-id="81b97-162">Select **Apply profile**, and select the profile (for example, “Contoso Desktop Profile – Skip All OOBE”).</span></span> <span data-ttu-id="81b97-163">裝置會在 [設定檔] 欄中顯示設定檔。</span><span class="sxs-lookup"><span data-stu-id="81b97-163">The devices will show the profile in the Profile column.</span></span>

4.  <span data-ttu-id="81b97-164">選用：測試看看您的設定檔是否有作用。</span><span class="sxs-lookup"><span data-stu-id="81b97-164">Optional: Test to see that your profile works.</span></span>

    <span data-ttu-id="81b97-165">a.</span><span class="sxs-lookup"><span data-stu-id="81b97-165">a.</span></span>  <span data-ttu-id="81b97-166">將裝置連接到網路，然後開啟。</span><span class="sxs-lookup"><span data-stu-id="81b97-166">Connect a device to the network and then turn it on.</span></span>

    <span data-ttu-id="81b97-167">b.</span><span class="sxs-lookup"><span data-stu-id="81b97-167">b.</span></span>  <span data-ttu-id="81b97-168">確認是否會顯示適當的 OOBE 畫面 (如果有的話)。</span><span class="sxs-lookup"><span data-stu-id="81b97-168">Verify that the appropriate OOBE screens (if any) appear.</span></span>

    <span data-ttu-id="81b97-169">c.</span><span class="sxs-lookup"><span data-stu-id="81b97-169">c.</span></span>  <span data-ttu-id="81b97-170">若要為新的使用者準備裝置，請完成 OOBE 體驗，然後將裝置重設為原廠預設設定。</span><span class="sxs-lookup"><span data-stu-id="81b97-170">To prepare the device for a new user, complete the OOBE experience, then reset the device to its factory default settings.</span></span>

## <a name="to-update-or-delete-a-profile"></a><span data-ttu-id="81b97-171">若要更新或刪除設定檔</span><span class="sxs-lookup"><span data-stu-id="81b97-171">To update or delete a profile</span></span> 

<span data-ttu-id="81b97-172">您已指派給裝置的設定檔之後，您可以更新它，，即使您已經提供裝置給您的客戶。</span><span class="sxs-lookup"><span data-stu-id="81b97-172">After you’ve assigned a profile to a device, you can update it, even if you’ve already given the device to your customer.</span></span> <span data-ttu-id="81b97-173">當裝置連線至網際網路時，會在 OOBE 程序中下載您最新版本的設定檔。</span><span class="sxs-lookup"><span data-stu-id="81b97-173">When the device connects to the internet, it downloads the latest version of your profile during the OOBE process.</span></span> <span data-ttu-id="81b97-174">如果客戶將其裝置還原為原廠預設設定，裝置將會重新下載設定檔的最新更新。</span><span class="sxs-lookup"><span data-stu-id="81b97-174">If your customer restores their device to its factory default settings, the device will again download the latest updates to your profile.</span></span> 

### <a name="remove-a-profile-from-a-device"></a><span data-ttu-id="81b97-175">從裝置移除設定檔</span><span class="sxs-lookup"><span data-stu-id="81b97-175">Remove a profile from a device</span></span>

1. <span data-ttu-id="81b97-176">選取您要從中移除設定檔的裝置 (或裝置批次)。</span><span class="sxs-lookup"><span data-stu-id="81b97-176">Select the device (or batch of devices) you want to remove the profile from.</span></span> 

2. <span data-ttu-id="81b97-177">在 **\[指派和刪除裝置\]** 窗格中選取 **\[移除設定檔\]**。</span><span class="sxs-lookup"><span data-stu-id="81b97-177">In **Assign and delete devices** pane, select **Remove profile**.</span></span>

3. <span data-ttu-id="81b97-178">移至您要移除和刪除的設定檔。</span><span class="sxs-lookup"><span data-stu-id="81b97-178">Go to the profile you want to remove and delete it.</span></span> <span data-ttu-id="81b97-179">設定檔將會從所有裝置中刪除。</span><span class="sxs-lookup"><span data-stu-id="81b97-179">The profile will be deleted from all devices.</span></span>

<span data-ttu-id="81b97-180">從 **\[裝置\]** 選取設定檔。</span><span class="sxs-lookup"><span data-stu-id="81b97-180">From **Devices**, select the profile.</span></span> <span data-ttu-id="81b97-181">您可以在此處修改現有的設定。</span><span class="sxs-lookup"><span data-stu-id="81b97-181">From here, you can modify the existing settings.</span></span>

## <a name="windows-autopilot-eula-dismissal--important-information"></a><span data-ttu-id="81b97-182">Windows Autopilot EULA 關閉 – 重要資訊</span><span class="sxs-lookup"><span data-stu-id="81b97-182">Windows Autopilot EULA dismissal – important information</span></span>

<span data-ttu-id="81b97-183">使用此工具可讓您在為客戶管理的裝置上設定個別 Windows 安裝。</span><span class="sxs-lookup"><span data-stu-id="81b97-183">Using this tool allows you to configure individual installations of Windows on devices you manage for your customers.</span></span> <span data-ttu-id="81b97-184">如果獲得客戶授權，您可以選擇抑制或隱藏安裝 Windows 時，通常會對使用者顯示的特定安裝畫面，包括 EULA 接受畫面。</span><span class="sxs-lookup"><span data-stu-id="81b97-184">If authorized to do so by the customer, you may choose to suppress or hide certain set-up screens that are normally presented to users when setting up Windows, including the EULA acceptance screen.</span></span> 

<span data-ttu-id="81b97-185">使用此功能表示您同意抑制或隱藏專為通知使用者或接受條款所設計的任何畫面，表示您您已獲得客戶的充分同意和授權以隱藏條款，並代表客戶 (組織或個別使用者，視情況而定) 同意通知並接受適用於您客戶的條款。</span><span class="sxs-lookup"><span data-stu-id="81b97-185">By using this function, you agree that suppressing or hiding any screens that are designed to provide users with notice or acceptance of terms means that you have obtained sufficient consent and authorization from your customer to hide terms, and that you on behalf of your customer (whether an organization or an individual user as the case may be), consent to any notices and accept any terms that are applicable to your customer.</span></span> <span data-ttu-id="81b97-186">這包括同意授權條款和條件，或若未使用此工具抑制或隱藏時會對使用者顯示的通知。</span><span class="sxs-lookup"><span data-stu-id="81b97-186">This includes agreement to the terms and conditions of the license or notice that would be presented to the user if you did not suppress or hide it using this tool.</span></span> <span data-ttu-id="81b97-187">您的客戶不可在這些裝置上使用 Windows 軟體，如果他們未向 Microsoft 或其授權經銷商有效取得軟體授權。</span><span class="sxs-lookup"><span data-stu-id="81b97-187">Your customer may not use the Windows software on those devices if the customer has not validly acquired a license for the software from Microsoft or its licensed distributors.</span></span>