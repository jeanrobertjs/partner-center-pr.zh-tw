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
# <a name="customize-a-devices-out-of-box-experience-with-windows-autopilot-profiles"></a>自訂裝置的現成的體驗，使用 Windows Autopilot 設定檔設定

**適用對象：**

- 雲端解決方案提供者直接帳單合作夥伴，間接提供者和間接經銷商

如果您管理客戶的裝置，您可能需要自訂客戶的使用者的全新體驗 (OOBE)。 您可以預先設定新裝置與 Windows Autopilot 設定檔，再傳遞給客戶的裝置，並將新的設定檔套用至已經購買客戶的裝置。 這篇文章說明如何建立和套用 Autopilot 設定檔到合作夥伴中心中的裝置。

如果您已經不熟悉 Autopilot，檢閱這些文章中的資訊：

- [Windows Autopilot 概觀](https://docs.microsoft.com/windows/deployment/windows-10-auto-pilot)
- [Autopilot 部署參考指南](http://assetsprod.microsoft.com/autopilot-deployment-program-reference-guide-csp.docx)  

## <a name="overview"></a>概觀

透過 Windows Autopilot 功能，在合作夥伴中心，您可以建立自訂的設定檔套用到客戶的裝置。 下列的設定檔設定可供在這篇文章發行的時：

- 略過隱私權設定。 這個選用的 Autopilot 設定檔設定可讓組織不會詢問在 OOBE 程序的隱私權設定。

- 停用在裝置上的建立本機系統管理員帳戶。 組織可以決定程序完成之後，設定裝置的使用者是否應該有系統管理員存取權。

- 自動設定公司或學校的裝置。 以 Autopilot 註冊的所有裝置自動將會視為公司或學校的裝置，因此此問題不會要求在 OOBE 程序。

- 略過 Cortana、 OneDrive 及 OEM 註冊設定頁面。 以 Autopilot 註冊的所有裝置將會自動略都過這些頁面的全新體驗 (OOBE) 程序期間。

- 略過使用者授權合約 (EULA)。 從 Windows 10 版本 1709年開始，組織可以略過 OOBE 程序期間所呈現的使用者授權合約頁面決定。 請參閱[Windows Autopilot EULA 關閉](#windows-autopilot-eula-dismissal)下方的重要資訊考慮關於略過使用者授權合約頁面，在 Windows 安裝期間。

下列的設定檔和裝置管理權限和限制套用：

- 雲端解決方案提供者合作夥伴可以繼續管理與他們有經銷商關係的現有客戶的 Autopilot 設定檔，即使客戶已移除合作夥伴的委派的系統管理權限。

- 您可以為您已新增由您或其他雲端解決方案提供者合作夥伴的客戶管理現有的裝置。

- 您無法管理客戶上傳到商務用 Microsoft Store 或 Microsoft Intune 入口網站的裝置。

## <a name="create-and-manage-autopilot-profiles-in-partner-center"></a>建立和管理 Autopilot 設定檔，在合作夥伴中心

在合作夥伴中心，您可以建立 Windows Autopilot 部署設定檔，並將其套用至裝置。

>[!NOTE]
>只有系統管理代理人可以建立和套用設定檔。

### <a name="create-a-new-autopilot-profile"></a>建立新的 Autopilot 設定檔

1. 從合作夥伴中心功能表中選取**客戶**，然後選取您要建立的 Autopilot 設定檔的客戶。

2. 客戶的詳細資料頁面上，選取**裝置**。

3. **Windows Autopilot 設定檔**底下選取 [**加入新的設定檔**。

4. 輸入設定檔的名稱和描述，然後設定 [OOBE 設定。 選擇：  

   - 略過設定中的隱私權設定

   - 停用設定中的本機系統管理員帳戶
  
   - 自動略過設定中的頁面<br>
        （包括*自動選取公司或學校的設定*和*略過 Cortana、 OneDrive 及 OEM 註冊設定頁面*）
  
   - 略過使用者授權合約 (EULA)<br> 
       >[!IMPORTANT] 
       >請參閱[Windows Autopilot EULA 關閉](#windows-autopilot-eula-dismissal)下方的重要資訊考慮關於略過使用者授權合約頁面，在 Windows 安裝期間。

5. 完成時選取 **\[提交\]**。

### <a name="apply-an-autopilot-profile-to-customer-devices"></a>適用於客戶裝置的 Autopilot 設定檔

>[!NOTE]
>下面的指示假設您已經到合作夥伴中心新增客戶的裝置，而且您可以存取他們的裝置清單。 如果您還沒有新增客戶的裝置，依照[新增裝置至客戶帳戶](#add-devices-to-a-customers-account)中的指示，則請依照下列步驟。

為客戶建立 Autopilot 設定檔之後，您可以將它套用到客戶的裝置。

1. 從合作夥伴中心功能表中選取**客戶**，然後選取您建立的 Autopilot 設定檔的客戶。

2. 客戶的詳細資料頁面上，選取**裝置**。

3. 在**套用到裝置的設定檔**選取裝置或您想要新增至設定檔，然後選取 [**套用設定檔**的裝置群組。 您套用的設定檔會出現在**設定檔**] 欄中。

4. 請依照下列步驟來驗證設定檔將會成功套用到裝置。

    a.  將裝置連接到網路，並將它開啟。

    b.  確認是否會顯示適當的 OOBE 畫面 (如果有的話)。

    c.  當 OOBE 程序停止時，裝置重設為原廠預設設定，以準備進行新的使用者。

### <a name="remove-an-autopilot-profile-from-a-customers-device"></a>從客戶的裝置移除 Autopilot 設定檔

1. 從合作夥伴中心功能表中選取**客戶**，然後選取您建立的 Autopilot 設定檔的客戶。

2. 客戶的詳細資料頁面上，選取**裝置**。

3. 在**套用到裝置的設定檔**中，選取您想要移除的設定檔，然後選取 [**移除設定檔**的裝置。

   >[!NOTE]
   >從裝置移除設定檔並不會從您的清單刪除設定檔。 如果您想要刪除設定檔，請依照[更新或刪除 Autopilot 設定檔](#update-or-delete-an-autopilot-profile)中的指示。

### <a name="update-or-delete-an-autopilot-profile"></a>更新或刪除 Autopilot 設定檔

如果客戶想要變更的全新體驗，您已經出貨給他們的裝置之後，您可以變更的設定檔，在合作夥伴中心。

當客戶的裝置連線到網際網路時，它會下載最新版的設定檔在 OOBE 程序。 此外，任何時候，客戶將裝置還原為原廠預設設定，裝置將會重新下載最新版的設定檔在 OOBE 程序。

1. 從合作夥伴中心功能表中選取**客戶**，然後選取 [想要您變更 Autopilot 設定檔的客戶。

2. 客戶的詳細資料頁面上，選取**裝置**。

3. 在**Windows Autopilot 設定檔**中，選取您需要更新的設定檔。 進行必要的變更，然後選取 [**送出**。

若要刪除此設定檔，請從右上角的 [\] 頁面選取**刪除設定檔**。

### <a name="add-devices-to-a-customers-account"></a>將裝置新增至客戶帳戶

>[!NOTE]
>銷售專員和系統管理代理人可以將裝置新增至客戶帳戶。

您可以將自訂的 Autopilot 設定檔套用至客戶裝置之前，您必須能夠存取客戶的裝置清單。

如果您打算使用 OEM 名稱、 序號和型號組合，請注意這些限制：

- 這個 tuple 只適用於較新的裝置 （4 個 k 雜湊，例如），且不支援 128b 雜湊 （RS2 和先前的裝置）。

- Tuple 註冊會區分大小寫，，因此檔案中的資料必須符合模型與製造商的名稱***完全***所提供的 OEM 提供者 （硬體提供者）。

請依照下列指示將裝置新增至合作夥伴中心中的客戶的帳戶。

1. 從合作夥伴中心功能表中選取**客戶**，然後選取您想要管理其裝置的客戶。

2. 客戶的詳細資料頁面上，選取**裝置**。

3. **套用至裝置的設定檔**底下選取 [**新增裝置**。

4. 輸入裝置清單的名稱，然後選取要上傳至合作夥伴中心的客戶清單中的 （在.csv 檔案格式） 的**瀏覽**。

    >[!NOTE]
    >您應該與您的裝置購買收到此.csv 檔案。 如果您沒有收到.csv 檔案，您可以依照下列步驟中[新增 Windows Autopilot 裝置](https://docs.microsoft.com/windows/deployment/windows-autopilot/add-devices#collecting-the-hardware-id-from-existing-devices-using-powershell)建立一個自己。  

5. 上傳.csv 檔案，然後選取 [**儲存**]。

如果您嘗試上傳.csv 檔案時收到錯誤訊息，請檢查檔案的格式。 您可以使用硬體雜湊，或 OEM 名稱、 序號和模型 （在此欄順序） 或 Windows 產品識別碼。 您也可以使用**新增裝置**旁邊連結所提供的範例.csv 檔案，來建立裝置清單。

## <a name="windows-autopilot-eula-dismissal"></a>Windows Autopilot EULA 關閉

### <a name="important-information"></a>重要資訊

Windows Autopilot 可讓您管理您的客戶的裝置上設定自訂的安裝 Windows。 如果客戶授權若要這樣做，您可以抑制或隱藏通常會顯示給使用者設定 Windows 中，包括 （使用者授權合約） EULA 接受畫面時的特定安裝設定畫面。

藉由使用這個函式，表示您同意抑制或隱藏專為使用者提供通知或接受條款表示您已經從您的客戶，以隱藏條款，以及您，代表的取得足夠同意和授權的任何畫面您的客戶 （是否在組織或個別使用者，視情況可能），同意通知並接受任何適用於您客戶的條款。 這包括同意授權條款和條件，或若未使用此工具抑制或隱藏時會對使用者顯示的通知。 您的客戶不可在這些裝置上使用 Windows 軟體，如果他們未向 Microsoft 或其授權經銷商有效取得軟體授權。