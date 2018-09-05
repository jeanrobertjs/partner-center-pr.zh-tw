---
title: 透過 Windows Autopilot 簡化裝置設定 | 合作夥伴中心
description: 在合作夥伴中心新增 Windows AutoPilot 部署設定檔，以透過 Windows Autopilot 簡化裝置設定
author: KPacquer
keywords: autopilot, windows autopilot, microsoft autopilot, 全自動部署, oobe, 登入畫面
ms.localizationpriority: medium
ms.openlocfilehash: b9fc13accd5d229f66ed425ace68e0df00e14016
ms.sourcegitcommit: 92629114d5081103bfe555081f69997af4ed56f2
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 08/31/2018
ms.locfileid: "2877578"
---
# <a name="simplify-device-setup-with-windows-autopilot"></a>透過 Windows Autopilot 簡化裝置設定 

只需幾個步驟，Windows Autopilot 即可從第一次開機開始精簡並保護新的 Windows 10 專業版裝置的裝置設定。 若要深入了解，請參閱 [Windows AutoPilot 概觀](https://docs.microsoft.com/windows/deployment/windows-10-auto-pilot)。

## <a name="features"></a>功能

*  **\[停用本機系統管理員權限\]**，適用於設定裝置的使用者
*  **\[顯示組織的登入頁面\]**。 組織可以預先定義登入頁面，這個頁面會新增裝置做為工作裝置，並將裝置與 Azure Active Directory 聯結。
*  OOBE 完成後，**\[在 Mobile Device Manager (MDM) 中註冊裝置\]** (例如：Microsoft Intune)。
*  **\[簡化全新體驗 (OOBE)\]**，可透過 Windows AutoPilot 部署設定檔，只使用必要的步驟和決策。 

## <a name="requirements"></a>需求

*  已預先安裝 Windows 10 專業版 Creators Update (1703 版或更新版本) 或 Windows 10 Pro for Advanced PCs 的裝置。
*  稱為硬體雜湊 (128 HWH 或 4k HWH) 的裝置識別碼，通常由 OEM 提供。 您可以使用識別碼，在合作夥伴儀表板指派組織設定檔。 
*  裝置必須能夠存取網際網路。 當裝置無法連線時，會顯示預設 Windows 全新體驗 (OOBE) 畫面。
*  在 MDM 中註冊裝置必須有 Azure Active Directory Premium。

## <a name="add-organization-login-pages-to-oobe"></a>將組織登入頁面新增至 OOBE

若要新增組織專屬頁面，請將裝置新增至組織的 [Azure AD 目錄](https://go.microsoft.com/fwlink/?linkid=848958)並建立登入頁面。


## <a name="remove-windows-pages-from-oobe-with-a-windows-autopilot-deployment-profile"></a>使用 Windows AutoPilot 設定檔從 OOBE 移除 Windows 頁面

**Windows AutoPilot 部署設定檔中的設定範例**
*  略過設定中的隱私權設定
*  停用設定中的本機系統管理員帳戶
*  自動略過設定中的頁面
   *  自動選取公司或學校的設定
   *  略過 Cortana、OneDrive 及 OEM 註冊設定頁面

### <a name="add-devices-and-apply-a-profile"></a>新增裝置並套用設定檔

您可以在合作夥伴儀表板建立 Windows AutoPilot 部署設定檔，並將其套用至裝置清單。

若要進行裝置設定，請上傳裝置清單、建立適用於這些裝置的設定檔，然後加以套用。

1.  新增裝置清單。

    銷售專員和系統管理代理人擁有將裝置清單新增至合作夥伴儀表板的存取權限。
    
    間接經銷商可以和他們的間接提供者合作來新增這份清單。

    a.  使用下列主題中的 PowerShell 指令碼建立 .csv 檔案：[Windows AutoPilot 概觀](https://docs.microsoft.com/windows/deployment/windows-10-auto-pilot)。 這個 .csv 檔案內含裝置資訊，包括序號、OEM 名稱、型號名稱、產品識別碼和裝置識別碼。 

    b。  從儀表板，移至 **\[客戶\]**> 選取收到裝置的客戶 >**\[裝置\] > \[新增裝置\]**。

    c.  命名裝置批次，例如「Contoso 銷售部門電腦 – 2017 年 4 月訂單」。 

    d.  按一下 **\[瀏覽\]** > 選取裝置資訊檔案 > **\[驗證\]**。

    **注意：** 如果您在嘗試上傳 .csv 檔案後收到錯誤訊息，請檢查檔案的格式。 8 月之後，您可以只使用 [硬體雜湊]，或使用 OEM 名稱、序號和型號等欄位 (依此順序)，或是 Windows 產品識別碼。 您也可以使用 **\[新增裝置\]** 旁邊連結所提供的範例 .csv 檔案。

2.  建立可套用至裝置的設定檔 (只有系統管理代理人擁有可在合作夥伴儀表板建立和套用設定檔的存取權)。

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

### <a name="you-can-remove-a-profile-from-a-device"></a>您可以從裝置移除設定檔
1. 選取您要從中移除設定檔的裝置 (或裝置批次)。 

2. 在 **\[指派和刪除裝置\]** 窗格中選取 **\[移除設定檔\]**。

3. 移至您要移除和刪除的設定檔。 設定檔將會從所有裝置中刪除。

從 **\[裝置\]** 選取設定檔。 您可以在此處修改現有的設定。

## <a name="windows-autopilot-eula-dismissal--important-information"></a>Windows Autopilot EULA 關閉 – 重要資訊

使用此工具可讓您在為客戶管理的裝置上設定個別 Windows 安裝。 如果獲得客戶授權，您可以選擇抑制或隱藏安裝 Windows 時，通常會對使用者顯示的特定安裝畫面，包括 EULA 接受畫面。 

使用此功能表示您同意抑制或隱藏專為通知使用者或接受條款所設計的任何畫面，表示您您已獲得客戶的充分同意和授權以隱藏條款，並代表客戶 (組織或個別使用者，視情況而定) 同意通知並接受適用於您客戶的條款。 這包括同意授權條款和條件，或若未使用此工具抑制或隱藏時會對使用者顯示的通知。 您的客戶不可在這些裝置上使用 Windows 軟體，如果他們未向 Microsoft 或其授權經銷商有效取得軟體授權。


