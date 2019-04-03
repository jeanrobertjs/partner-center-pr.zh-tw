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
ms.sourcegitcommit: f5dbd07185059aa5faddf1c5daa556f634ce97ee
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 03/19/2019
ms.locfileid: "58162218"
---
# <a name="customize-a-devices-out-of-box-experience-with-windows-autopilot-profiles"></a>自訂裝置的全新的體驗使用 Windows Autopilot 設定檔

**適用於**

- Direct 帳單的 CSP 合作夥伴，間接提供者，以及間接轉售商

如果您管理客戶的裝置，您可能需要自訂的全新體驗 (OOBE)，為客戶的使用者。 您可以預先設定裝置交給客戶之前的 使用 Windows Autopilot 設定檔的新裝置，並將新的設定檔套用至客戶已購買的裝置。 這篇文章說明如何建立和套用到在合作夥伴中心內的裝置的 Autopilot 設定檔。

如果您已經不熟悉自動駕駛儀的操作，請檢閱這些文章中的資訊：

- [Windows Autopilot 概觀](https://docs.microsoft.com/windows/deployment/windows-10-auto-pilot)
- [Autopilot 部署參考指南](https://assetsprod.microsoft.com/autopilot-deployment-program-reference-guide-csp.docx)  

## <a name="overview"></a>總覽

使用 Windows Autopilot 在合作夥伴中心功能，您可以建立要套用到客戶裝置的自訂設定檔。 下列設定檔設定已發行的這篇文章的時間後可用：

- 略過隱私權設定。 這個選擇性的 Autopilot 設定檔設定可讓組織不會詢問 OOBE 程序期間的隱私權設定。

- 停用裝置上的本機系統管理員帳戶建立。 組織可以決定程序完成之後，設定裝置的使用者是否應該具有系統管理員存取權。

- 自動設定裝置的公司或學校資源。 所有 Autopilot 註冊的裝置會自動被視為工作或學校裝置，因此這個問題不會要求在 OOBE 程序期間。

- 略過 Cortana、 OneDrive 和 OEM 登錄設定頁面。 所有 Autopilot 註冊的裝置將會自動略都過這些頁面的全新體驗 (OOBE) 程序期間。

- 略過使用者授權合約 (EULA)。 從 Windows 10 1709年版開始，組織可以決定略過 OOBE 流程期間所呈現的 EULA 頁面。 請參閱[Windows Autopilot EULA dismissal](#windows-autopilot-eula-dismissal)以下重要的資訊，需要考量的事項略過 [使用者授權合約] 頁面，在 Windows 安裝程式。

下列設定檔和裝置的管理使用權限和限制適用於：

- CSP 合作夥伴可以繼續針對現有的客戶能與其轉銷商關係管理 Autopilot 設定檔，即使客戶已移除夥伴的委派的系統管理權限。

- 您可以為您加入的客戶管理現有的裝置。

- 您無法管理您的客戶已上傳至 Microsoft Store for Business 或 Microsoft Intune 入口網站的裝置。

## <a name="create-and-manage-autopilot-profiles-in-partner-center"></a>建立和管理在合作夥伴中心內的 Autopilot 設定檔

在合作夥伴中心，您可以建立 Windows Autopilot 部署設定檔，並將它們套用至裝置。

>[!NOTE]
>只管理專員可以建立，並套用設定檔。

### <a name="create-a-new-autopilot-profile"></a>建立新的 Autopilot 設定檔

1. 選取 **客戶**合作夥伴中心功能表，然後選取從客戶您正在建立 Autopilot 設定檔。

2. 在客戶的詳細資料頁面上，選取**裝置**。

3. 底下**Windows Autopilot 設定檔**選取**新增新的設定檔**。

4. 輸入設定檔的名稱和描述，然後設定 OOBE 設定。 選擇：  

   - 略過安裝程式中的隱私權設定

   - 停用設定中的本機系統管理員帳戶
  
   - 自動略過設定中的頁面<br>
        (包括*會自動選取的安裝程式，為工作或學校*並*略過 Cortana、 OneDrive 和 OEM 登錄設定頁面*)
  
   - 略過使用者授權合約 (EULA)<br> 
       >[!IMPORTANT] 
       >請參閱[Windows Autopilot EULA dismissal](#windows-autopilot-eula-dismissal)以下重要的資訊，需要考量的事項略過 [使用者授權合約] 頁面，在 Windows 安裝程式。

5. 完成時選取 **\[提交\]**。

### <a name="apply-an-autopilot-profile-to-customer-devices"></a>套用到客戶裝置的 Autopilot 設定檔

>[!NOTE]
>下面的指示會假設，您已新增客戶的裝置到合作夥伴中心，而且您可以存取其裝置的清單。 如果您尚未新增客戶的裝置，請依照下列中的指示[將裝置新增至客戶帳戶](#add-devices-to-a-customers-account)，然後遵循下列步驟。

客戶建立 Autopilot 設定檔之後，您可以將它套用至客戶的裝置。

1. 選取 **客戶**從合作夥伴中心功能表，然後選取您建立客戶的 Autopilot 設定檔。

2. 在客戶的詳細資料頁面上，選取**裝置**。

3. 底下**套用至裝置的設定檔**選取的裝置或裝置群組，您想要新增至設定檔，然後選取**將設定檔套用**。 您剛才套用之設定檔會出現在**設定檔**資料行。

4. 請遵循下列步驟來確認設定檔會將已成功套用至裝置。

    a.  將裝置連線到網路，並將它開啟。

    b.  確認是否會顯示適當的 OOBE 畫面 (如果有的話)。

    c.   當 OOBE 程序停止之後時，請將裝置重設其原廠預設值，以準備進行新的使用者。

### <a name="remove-an-autopilot-profile-from-a-customers-device"></a>移除客戶的裝置的 Autopilot 設定檔

1. 選取 **客戶**從合作夥伴中心功能表，然後選取您建立客戶的 Autopilot 設定檔。

2. 在客戶的詳細資料頁面上，選取**裝置**。

3. 底下**套用至裝置的設定檔**選取您想要移除的設定檔，然後選取的裝置**移除設定檔**。

   >[!NOTE]
   >從裝置移除設定檔不會從清單刪除該設定檔。 如果您想要刪除設定檔，請依照下列中的指示[更新或刪除 Autopilot 設定檔](#update-or-delete-an-autopilot-profile)。

### <a name="update-or-delete-an-autopilot-profile"></a>更新或刪除 Autopilot 設定檔

如果客戶想要變更的全新體驗，您已出貨給他們的裝置之後，您可以變更在合作夥伴中心內的設定檔。

當客戶的裝置連線到網際網路時，它會下載最新的設定檔版本 OOBE 程序期間。 此外，客戶會將裝置還原為原廠預設值，任何時候裝置會再次下載最新的設定檔版本 OOBE 程序期間。

1. 選取 **客戶**從合作夥伴中心功能表然後選取想要變更 Autopilot 設定檔的客戶。

2. 在客戶的詳細資料頁面上，選取**裝置**。

3. 底下**Windows Autopilot 設定檔**選取您要更新的設定檔。 進行必要的變更，然後按**送出**。

若要刪除此設定檔，請選取**刪除設定檔**從頁面右上角。

### <a name="add-devices-to-a-customers-account"></a>將裝置新增至客戶的帳戶

>[!NOTE]
>銷售的代理程式和管理專員可以將裝置新增至客戶的帳戶。

您可以將自訂的 Autopilot 設定檔套用到客戶裝置之前，您必須能夠存取客戶的裝置清單。

如果您打算使用 OEM 名稱、 序號和模型組合，請注意這些限制：

- 此 tuple 只適用於較新的裝置 （4 k 雜湊，例如），且不支援 128b 雜湊 （RS2 和先前的裝置）。

- Tuple 註冊會區分大小寫，所以檔案中的資料必須符合的模型和製造商名稱***完全***OEM 提供者 （硬體提供者） 所提供。

請遵循下列指示來將裝置新增至在合作夥伴中心內的客戶的帳戶。

1. 選取 **客戶**從合作夥伴中心功能表然後選取客戶您想要管理其裝置。

2. 在客戶的詳細資料頁面上，選取**裝置**。

3. 底下**套用至裝置的設定檔**選取**將裝置新增**。

4. 輸入 [裝置] 清單的名稱，然後選取**瀏覽**上傳至合作夥伴中心的客戶的清單 （格式為.csv 檔案）。

    >[!NOTE]
    >您應該會收到此.csv 檔案與您的裝置購買。 如果您未收到.csv 檔案，您可以建立自己所遵循的步驟[將裝置新增至 Windows Autopilot](https://docs.microsoft.com/windows/deployment/windows-autopilot/add-devices#collecting-the-hardware-id-from-existing-devices-using-powershell)。  

5. 上傳.csv 檔案，然後選取**儲存**。

如果您嘗試上傳.csv 檔案時收到錯誤訊息，請檢查檔案的格式。 您可以使用硬體雜湊，或 OEM 名稱、 序號和模型 （依該資料行順序） 或 Windows 產品識別碼。 您也可以使用所提供的連結旁邊的範例.csv 檔案**將裝置新增**建立裝置清單。

## <a name="windows-autopilot-eula-dismissal"></a>Windows Autopilot EULA dismissal

### <a name="important-information"></a>重要資訊

Windows Autopilot 可讓您為您的客戶管理的裝置上設定的 Windows 自訂的安裝。 如果客戶授權若要這樣做，您可以隱藏或隱藏時，Windows，包括使用者授權合約 （終端使用者授權合約） 接受畫面會正常呈現給使用者特定設定畫面。

使用此函式，即表示您同意，隱藏或隱藏專為使用者提供通知或接受條款表示您已從您的客戶代表隱藏字詞，而且您，取得足夠的同意和授權的任何畫面客戶 （不論組織或個別使用者與案例可能），任何聲明同意並接受任何條款適用於您的客戶。 這包括同意授權條款和條件，或若未使用此工具抑制或隱藏時會對使用者顯示的通知。 您的客戶不可在這些裝置上使用 Windows 軟體，如果他們未向 Microsoft 或其授權經銷商有效取得軟體授權。