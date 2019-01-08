---
title: 自訂裝置的全新的體驗，使用 Windows Autopilot 設定檔 |合作夥伴中心
description: 預先設定裝置的 Autopilot 設定檔的內建的跨體驗。
author: maggiepuccievans
keywords: autopilot，windows autopilot，microsoft autopilot，全自動部署、 oobe、 登入畫面的內建的跨
ms.localizationpriority: medium
ms.openlocfilehash: 70740212f433ad6eb4f2f04d63708fff436024ad
ms.sourcegitcommit: 3871c82c1075206a33eae7cd395a5a36edb2d1fc
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 01/08/2019
ms.locfileid: "8995932"
---
# <a name="customize-a-devices-out-of-box-experience-with-windows-autopilot-profiles"></a>自訂裝置的全新的體驗，使用 Windows Autopilot 設定檔設定

**適用於**

- 雲端解決方案提供者直接帳單合作夥伴，間接提供者和間接經銷商

如果您管理客戶的裝置，您可能需要自訂的全新體驗 (OOBE) 的客戶的使用者。 您可以預先設定新裝置與 Windows Autopilot 設定檔之前傳遞給客戶的裝置，並將新的設定檔套用至已經購買客戶的裝置。 本文說明如何建立和套用 Autopilot 設定檔到合作夥伴中心中的裝置。

如果您不熟悉已經 Autopilot，檢閱這些文章中的資訊：

- [Windows Autopilot 概觀](https://docs.microsoft.com/windows/deployment/windows-10-auto-pilot)
- [Autopilot 部署參考指南](http://assetsprod.microsoft.com/autopilot-deployment-program-reference-guide-csp.docx)  

## <a name="overview"></a>概觀

透過 Windows Autopilot 功能，在合作夥伴中心，您可以建立自訂的設定檔，以套用到客戶的裝置。 下列的設定檔設定可供在這篇文章發行的時：

- 略過隱私權設定。 此選用的 Autopilot 設定檔設定可讓組織不在 OOBE 程序期間詢問有關隱私權設定。

- 停用在裝置上的建立本機系統管理員帳戶。 組織可以決定程序完成之後，設定裝置的使用者是否應該有系統管理員存取權。

- 自動設定公司或學校的裝置。 使用 Autopilot 註冊的所有裝置自動將會視為公司或學校的裝置，因此此問題不會要求在 OOBE 程序。

- 略過 Cortana、 OneDrive 及 OEM 註冊設定頁面。 使用 Autopilot 註冊的所有裝置將會自動略都過這些頁面的內建的全新體驗 (OOBE) 程序期間。

- 略過使用者授權合約 (EULA)。 從 Windows 10 版本 1709年開始，組織可以略過 OOBE 程序期間所呈現的使用者授權合約頁面決定。 請參閱[Windows Autopilot EULA 關閉](#windows-autopilot-eula-dismissal)下方的重要資訊考慮關於 Windows 安裝程式期間略過使用者授權合約頁面。

下列的設定檔和裝置管理權限和限制套用：

- 雲端解決方案提供者合作夥伴可以繼續管理與他們有經銷商關係的現有客戶的 Autopilot 設定檔，即使客戶已移除合作夥伴的委派的系統管理權限。

- 您可以為您已新增由您或其他雲端解決方案提供者合作夥伴的客戶管理現有的裝置。

- 您無法管理客戶上傳到商務用 Microsoft Store 或 Microsoft Intune 入口網站的裝置。

## <a name="create-and-manage-autopilot-profiles-in-partner-center"></a>建立和管理合作夥伴中心中的 Autopilot 設定檔

在合作夥伴中心，您可以建立 Windows Autopilot 部署設定檔，並將其套用至裝置。

>[!NOTE]
>只有系統管理代理人可以建立和套用設定檔。

### <a name="create-a-new-autopilot-profile"></a>建立新的 Autopilot 設定檔

1. 從合作夥伴中心功能表中選取**客戶**，然後選取您要建立的 Autopilot 設定檔的客戶。

2. 客戶的詳細資料頁面上，選取**裝置**。

3. **Windows Autopilot 設定檔**底下選取 [**加入新的設定檔**。

4. 輸入設定檔的名稱和描述，然後再設定 OOBE 設定。 選擇：  

   - 略過設定中的隱私權設定

   - 停用設定中的本機系統管理員帳戶
  
   - 自動略過設定中的頁面<br>
        （包括*自動選取公司或學校的設定*和*略過 Cortana、 OneDrive 及 OEM 註冊設定頁面*）
  
   - 略過使用者授權合約 (EULA)<br> 
       >[!IMPORTANT] 
       >請參閱[Windows Autopilot EULA 關閉](#windows-autopilot-eula-dismissal)下方的重要資訊考慮關於 Windows 安裝程式期間略過使用者授權合約頁面。

5. 完成時選取 **\[提交\]**。

### <a name="apply-an-autopilot-profile-to-customer-devices"></a>適用於客戶裝置的 Autopilot 設定檔

>[!NOTE]
>下面的指示假設您已經到合作夥伴中心新增客戶的裝置，您可以存取其裝置的清單。 如果您尚未新增客戶的裝置，依照[新增裝置到客戶的帳戶](#add-devices-to-a-customers-account)中的指示，則請依照下列步驟。

為客戶建立 Autopilot 設定檔之後，您可以將它套用到客戶的裝置。

1. 從合作夥伴中心功能表中選取**客戶**，然後選取您建立的 Autopilot 設定檔的客戶。

2. 客戶的詳細資料頁面上，選取**裝置**。

3. **套用至裝置的設定檔**底下選取的裝置或您想要新增至設定檔，然後選取 [**套用設定檔**的裝置群組。 **設定檔**] 欄中顯示您套用設定檔。

4. 請依照下列步驟來驗證設定檔將會成功套用到裝置。

    a.  將裝置連接到網路，並將它開啟。

    b.  確認是否會顯示適當的 OOBE 畫面 (如果有的話)。

    c.  當 OOBE 程序會停止時，重設裝置，以其原廠預設設定為新使用者準備它。

### <a name="remove-an-autopilot-profile-from-a-customers-device"></a>從客戶的裝置移除 Autopilot 設定檔

1. 從合作夥伴中心功能表中選取**客戶**，然後選取您建立的 Autopilot 設定檔的客戶。

2. 客戶的詳細資料頁面上，選取**裝置**。

3. 在**套用到裝置的設定檔**中，選取您想要移除的設定檔，然後選取 [**移除設定檔**的裝置。

   >[!NOTE]
   >從裝置移除設定檔並不會從您的清單中刪除設定檔。 如果您想要刪除設定檔，請依照[更新或刪除 Autopilot 設定檔](#update-or-delete-an-autopilot-profile)中的指示。

### <a name="update-or-delete-an-autopilot-profile"></a>更新或刪除 Autopilot 設定檔

如果客戶想要變更的全新體驗，您已經出貨給他們的裝置之後，您可以變更在合作夥伴中心設定檔。

當客戶的裝置連線到網際網路時，它會在 OOBE 程序期間下載最新版的設定檔。 此外，的隨時客戶將裝置還原為原廠預設設定，裝置將會重新下載最新的設定檔版本在 OOBE 程序。

1. 從合作夥伴中心功能表中選取**客戶**，然後選取 [想要您變更 Autopilot 設定檔的客戶。

2. 客戶的詳細資料頁面上，選取**裝置**。

3. **Windows Autopilot 設定檔**底下選取您需要更新的設定檔。 進行必要的變更，然後選取 [**送出**。

若要刪除此設定檔，請從右上角的頁面選取**刪除設定檔**。

### <a name="add-devices-to-a-customers-account"></a>將裝置新增至客戶帳戶

>[!NOTE]
>銷售專員和系統管理代理人可以將裝置新增至客戶的帳戶。

您可以將自訂的 Autopilot 設定檔套用至客戶裝置之前，您必須能夠存取客戶的裝置清單。

如果您打算使用 OEM 名稱、 序號和型號組合，請注意這些限制：

- 這個 tuple 只適用於較新的裝置 （4 個 k 雜湊，例如） 並不支援 128b 雜湊 （RS2 和先前的裝置）。

- Tuple 註冊會區分大小寫，，因此檔案中的資料必須符合模型與製造商的名稱***完全***所提供的 OEM 提供者 （硬體提供者）。

請依照下列指示將裝置新增至合作夥伴中心中的客戶的帳戶。

1. 從合作夥伴中心功能表中選取**客戶**，然後選取您想要管理其裝置的客戶。

2. 客戶的詳細資料頁面上，選取**裝置**。

3. 在**套用到裝置的設定檔**選取 [**新增裝置**。

4. 輸入裝置清單的名稱，然後選取 [**瀏覽**上傳至合作夥伴中心的客戶的清單中 （在.csv 檔案格式）。

    >[!NOTE]
    >您應該與您的裝置購買收到此.csv 檔案。 如果您沒有收到.csv 檔案，您可以依照下列步驟中[新增 Windows Autopilot 裝置](https://docs.microsoft.com/windows/deployment/windows-autopilot/add-devices#collecting-the-hardware-id-from-existing-devices-using-powershell)建立一個自己。  

5. 上傳.csv 檔案，然後選取 [**儲存**。

如果您嘗試上傳.csv 檔案時收到錯誤訊息，請檢查檔案的格式。 您可以使用硬體雜湊只，或使用 OEM 名稱、 序號，和模型 （在此欄順序） 或 Windows 產品識別碼。 您也可以使用**新增裝置**旁邊連結所提供的範例.csv 檔案，來建立裝置清單。

## <a name="windows-autopilot-eula-dismissal"></a>Windows Autopilot EULA 關閉

### <a name="important-information"></a>重要資訊

Windows Autopilot 可讓您管理您的客戶的裝置上設定自訂的安裝 Windows。 如果客戶授權若要這樣做，您可以抑制或隱藏特定安裝畫面，通常會顯示給使用者時設定 Windows，包括 （使用者授權合約） EULA 接受畫面。

使用此函式，表示您同意抑制或隱藏專為提供使用者或接受條款表示您已經從您的客戶，以隱藏條款，以及您，代表的取得足夠同意和授權的任何畫面您的客戶 （是否在組織或個別使用者，視情況可能），同意通知並接受任何適用於您客戶的條款。 這包括同意授權條款和條件，或若未使用此工具抑制或隱藏時會對使用者顯示的通知。 您的客戶不可在這些裝置上使用 Windows 軟體，如果他們未向 Microsoft 或其授權經銷商有效取得軟體授權。