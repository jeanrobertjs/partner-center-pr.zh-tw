---
title: 適用於 CSP 合作夥伴的 Cloudyn 支援的 Azure 成本管理 | 合作夥伴中心
description: Cloudyn 支援的 Azure 成本管理需要對 Partner Center API 佈建存取權。
author: Janet
Keywords: Azure cost management app, manage costs, web apps
robots: ''
ms.localizationpriority: medium
ms.openlocfilehash: 9f5439f47dbc99421e493c9f84f8ea2469ba6525
ms.sourcegitcommit: 123a7f53d633c27eb5f982926d856de47afb1042
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 10/09/2018
ms.locfileid: "4489384"
---
# <a name="azure-cost-management-app-for-azure-csp-partners"></a>Azure CSP 合作夥伴適用的 Azure 成本管理應用程式  

**適用對象：**

-  合作夥伴中心

[取得有關 Azure 成本管理的詳細資訊](https://go.microsoft.com/fwlink/p/?linkid=857893)

## <a name="before-you-begin"></a>在您開始前
在可以使用 Azure 成本管理之前，請先確定您符合下列需求：

- 您是雲端解決方案提供者計畫的合作夥伴。
- 您有能力建立 Partner Center API Web 應用程式。

## <a name="overview"></a>概觀

Cloudyn 支援的 Azure 成本管理是 Web 應用程式，可讓您追蹤並管理您有多少客戶正在使用 Azure 以及使用成本。 您是透過合作夥伴中心 API 使用此應用程式。

## <a name="register-your-web-app-in-the-partner-center"></a>在合作夥伴中心註冊您的 Web 應用程式
當您在合作夥伴中心註冊 Azure Active Directory Web 應用程式，您就啟用對合作夥伴中心 API 的存取權。 
1.  使用[全域系統管理員或系統管理代理人帳戶](create-user-accounts-and-set-permissions.md)登入[合作夥伴中心](https://partnercenter.microsoft.com/en-us/pcv/dashboard/overview)。
2.  從**合作夥伴中心**中，選取 [**帳戶設定** &gt; **[應用程式管理](https://partnercenter.microsoft.com/en-us/pcv/apiintegration/appmanagement)**。
3.  在 **\[Web 應用程式\]** 區段中，按一下 **\[新增 Web 應用程式\]**。
<br> **注意**：如果您先前已建立 Web 應用程式，可以略過步驟 3。
4.  複製並儲存您 Web 應用程式的**商務識別碼** GUID 和**應用程式識別碼** GUID。 您將需要這兩個識別碼，才能使用 30 天免費試用版的 Azure 成本管理應用程式。

## <a name="add-a-secret-key-to-your-app"></a>將秘密金鑰新增到您的應用程式。
1.  在 **\[新增金鑰\]** 按鈕旁邊的下拉式清單中，選取 1 或 2 年期間。
2.  按一下 **\[新增金鑰\]**。 
3.  複製並儲存秘密金鑰值。 您將需要此值，以便使用 30 天免費試用版。<br>
> [!NOTE]  
> 應用程式秘密金鑰就像是到期日較長的密碼。 請將金鑰值儲存在安全的位置，以供未來使用。

## <a name="next-steps"></a>後續步驟
啟動 [30 天免費試用版](https://go.microsoft.com/fwlink/?linkid=857895)。
若要啟動試用版，您需要下列資訊：
- 合作夥伴中心登入憑證
- 商務識別碼 GUID
- 應用程式識別碼 GUID
- 應用程式秘密金鑰值
