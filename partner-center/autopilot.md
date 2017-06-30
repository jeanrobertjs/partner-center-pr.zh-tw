---
title: "新增全自動部署設定檔，以透過 Windows Autopilot 簡化裝置設定 | 合作夥伴中心"
description: "在合作夥伴中心新增全自動部署設定檔，以透過 Windows Autopilot 簡化裝置設定"
author: KPacquer
keywords: "autopilot, windows autopilot, microsoft autopilot, ztd, 全自動部署, oobe, 登入畫面"
robots: NOINDEX,NOFOLLOW
ms.openlocfilehash: c51d9204b352b548a4095e96944aacdbcde97fa2
ms.sourcegitcommit: c2a12d6a18b9631916f6dd8301a4752ecc03296b
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 06/19/2017
---
# <a name="add-a-zero-touch-deployment-profile-to-simplify-device-setup-with-windows-autopilot"></a>新增全自動部署設定檔，以透過 Windows Autopilot 簡化裝置設定

只需幾個步驟，Windows Autopilot 即可從第一次開機開始精簡並保護新的 Windows 10 專業版裝置的裝置設定。 

## <a name="features"></a>功能

*  **\[停用本機系統管理員權限\]**，適用於設定裝置的使用者
*  **\[顯示組織的登入頁面\]**。 組織可以預先定義登入頁面，這個頁面會新增裝置做為工作裝置，並將裝置與 Azure Active Directory 聯結。
*  OOBE 完成後，**\[在 MDM 中註冊裝置\]** (例如：Microsoft Intune)。
*  **\[簡化全新體驗 (OOBE)\]**，可透過全自動部署 (ZTD) 設定檔，只使用必要的步驟和決策。 

## <a name="requirements"></a>需求

*  預先安裝 Windows 10 專業版 Creators Update (版本 1703 或更新版本) 的裝置
*  稱為硬體雜湊 (128 HWH 或 4k HWH) 的裝置識別碼，通常由 OEM 提供。 您可以使用識別碼，在合作夥伴中心指派組織設定檔。
*  裝置必須能夠存取網際網路。 當裝置無法連線時，會顯示預設 Windows 全新體驗 (OOBE) 畫面。
*  在 MDM 中註冊裝置必須有 Azure Active Directory Premium。

## <a name="add-organization-login-pages-to-oobe"></a>將組織登入頁面新增至 OOBE

若要新增組織專屬頁面，請將裝置新增至組織的 [Azure AD 目錄](https://go.microsoft.com/fwlink/?linkid=848958)並建立登入頁面。


## <a name="remove--windows-pages-from-oobe-with-a-zero-touch-deployment-ztd-profile"></a>使用全自動部署 (ZTD) 設定檔從 OOBE 移除 Windows 頁面

### <a name="examples-of-settings-in-a-ztd-profile"></a>ZTD 設定檔中設定的範例
*  略過設定中的隱私權設定
*  停用設定中的本機系統管理員帳戶
*  自動略過設定中的頁面
   *  自動選取公司或學校的設定
   *  略過 Cortana、OneDrive 及 OEM 註冊設定頁面

### <a name="add-devices-and-apply-a-profile"></a>新增裝置並套用設定檔

您可以在合作夥伴中心建立 ZTD 設定檔，並將其套用至裝置清單。

若要進行裝置設定，請將裝置清單上傳至合作夥伴中心、建立適用於這些裝置的設定檔，然後加以套用。

1.  將裝置清單新增至合作夥伴中心 (銷售專員和系統管理代理人擁有可將裝置清單新增至合作夥伴中心的存取權)。

    a.  向您的 OEM 索取一個列出新裝置的 .csv 檔案。 此檔案包含序號、產品識別碼，以及從 OEM Activation 3.0 工具產生的裝置識別碼。 

    b.  從 [合作夥伴中心] 儀表板，移至 **\[客戶\]**> 選取收到裝置的客戶 >**\[裝置\] > \[新增裝置\]**。

    c.  命名裝置批次，例如「Contoso 銷售部門電腦 – 2017 年 4 月訂單」。 

    d.  按一下 **\[瀏覽\]** > 選取裝置資訊檔案 > **\[驗證\]**。

2.  建立可套用至裝置的設定檔 (只有系統管理代理人擁有可在合作夥伴中心建立和套用設定檔的存取權)。

    a.  在 **\[裝置\]** 中按一下 **\[新增設定檔\]**。

    b.  命名設定檔，例如「Contoso 桌面設定檔 – 略過所有 OOBE」。

    c.  設定 OOBE 設定。 例如，核取設定中的 **\[略過快速設定\]**。

    d.  按一下 **\[提交\]**。

3.  套用設定檔。

    a.  從 **\[裝置\]** 的 **\[指派和刪除裝置\]** 窗格中選取您想要設定的裝置。 若要選取整個批次，請按一下批次名稱 (例如「Contoso 銷售部門電腦 – 2017 年 3 月訂單」) 旁邊的核取方塊。

    b.  按一下 **\[套用設定檔\]**，然後選取設定檔 (例如「Contoso 桌面設定檔 – 略過所有 OOBE」)。 裝置會在 [設定檔] 欄中顯示設定檔。

4.  選用：測試看看您的設定檔是否有作用。

    a.  將裝置連線至網路並開啟。

    b.  確認是否會顯示適當的 OOBE 畫面 (如果有的話)。

    c.  若要為新的使用者準備裝置，請完成 OOBE 體驗，然後將裝置重設為原廠預設設定。


## <a name="to-update-or-delete-a-profile"></a>若要更新或刪除設定檔 

將設定檔指派給裝置後，就可以將其更新，即使您已經將裝置交給客戶，也能更新。 當裝置連線至網際網路時，會在 OOBE 程序中下載您最新版本的設定檔。 如果客戶將其裝置還原為原廠預設設定，裝置將會重新下載設定檔的最新更新。 

###<a name="you-can-remove-a-profile-from-a-device"></a>您可以從裝置移除設定檔
1. 選取您要從中移除設定檔的裝置 (或裝置批次)。 

2. 在 **\[指派和刪除裝置\]** 窗格中選取 **\[移除設定檔\]**。

3. 移至您要移除和刪除的設定檔。 設定檔將會從所有裝置中刪除。


從 **\[裝置\]** 選取設定檔。 您可以在此處修改現有的設定。

