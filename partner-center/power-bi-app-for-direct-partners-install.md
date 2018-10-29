---
title: 安裝和預覽適用於 Microsoft Power BI 的合作夥伴中心分析應用程式 | 合作夥伴中心
ms.topic: article
ms.date: 10/29/2018
description: 請依照下列步驟，預覽適用於 Power BI 的合作夥伴中心分析應用程式 (適用於雲端解決方案提供者直接合作夥伴)。
fwlink: https://go.microsoft.com/fwlink/?linkid=852583
author: labrenne
ms.author: labrenne
ms.localizationpriority: medium
ms.openlocfilehash: f176b71072a67043df2ffe59b004b0ae8411dd4a
ms.sourcegitcommit: ed22f6825d3af1d19385198b4d511e4b39d5e353
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 10/29/2018
ms.locfileid: "5795531"
---
# <a name="install-and-preview-the-partner-center-analytics-app-for-microsoft-power-bi"></a>安裝和預覽適用於 Microsoft Power BI 的合作夥伴中心分析應用程式

**適用於**

-   合作夥伴中心

## <a name="before-you-begin"></a>開始之前

安裝合作夥伴中心分析應用程式預覽版之前，請先確定您符合下列需求。

-   您在雲端解決方案提供者計畫及合作夥伴中心都是直接合作夥伴。 如果您在業務上與 Microsoft 及客戶直接往來，即是直接合作夥伴。

-   您有 Microsoft Power BI Professional 或 Microsoft Power BI Premium 的使用中訂閱。

-   您可以登入 Power BI。

-   您可以用全域管理員、系統管理代理人或帳單系統管理員的身分登入[貴公司的 Azure Active Directory (Azure AD) 租用戶](azure-active-directory-tenants-and-partner-center.md)。

## <a name="to-install-the-app"></a>若要安裝應用程式

1. 開始進行[安裝程序](https://app.powerbi.com/getdata/services/partneranalytics?cpcode=PartnerCenterAnalytics&getDataForceConnect=true&alwaysPromptForContentProviderCreds=true)。

2. 在 **\[已經有帳戶名稱了嗎?\]** 下方選取 **\[登入\]**。 

3.  在下一個頁面上，輸入您的 Power BI 的使用者名稱和密碼，然後選取 **\[登入\]**。 

4.  在 **\[連線到合作夥伴中心分析\]** 快顯視窗中，確認 **\[驗證方法\]** 已設定為 **\[oAuth2\]**，如果沒有如此設定，請從清單選取 **\[oAuth2\]**。 

    > [!NOTE]  
>  這個視窗可能需要幾分鐘才會出現。

5.  在 **\[合作夥伴中心分析連接器\]** 頁面上，使用貴公司 Azure AD 租用戶的全域管理員、系統管理代理人或帳單系統管理員認證登入，然後選取 **\[登入\]**。
 
6.  出現存取權提示時，選取 **\[接受\]**。 

將合作夥伴中心分析服務連線到 Power BI 後，資料將會開始載入。 視資料數量而定，這最多可能需要花費 10 分鐘。 

資料完成載入後，您可以開始在 Power BI 中使用合作夥伴中心分析應用程式儀表板和報告。

## <a name="next-steps"></a>後續步驟

[使用適用於 Microsoft Power BI 的合作夥伴中心分析應用程式來檢視業務資料](power-bi-app-for-direct-partners-use.md)
