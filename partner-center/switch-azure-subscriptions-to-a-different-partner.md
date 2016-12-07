---
title: "將 Azure 訂用帳戶切換為其他合作夥伴 | 合作夥伴中心"
description: "客戶可以變更雲端解決方案提供者計畫中要針對 Microsoft Azure 服務使用的合作夥伴。 不過，這是需要合作夥伴和客戶雙方手動操作的程序。"
ms.assetid: 42D1D9AB-613D-4FC1-A846-EE769923E699
author: MaggiePucciEvans
translationtype: Human Translation
ms.sourcegitcommit: 14ba85c868e59dd1c77063f5b1b0e9ab8db7f82f
ms.openlocfilehash: 29ced9a3a7256f86f0f8708a4c72ac75b9269ffc

---

# 將 Azure 訂用帳戶切換為其他合作夥伴


客戶可以變更雲端解決方案提供者計畫中要針對 Microsoft Azure 服務使用的合作夥伴。 不過，這是需要合作夥伴和客戶雙方手動操作的程序。

**注意**：目前沒有可供 Azure 客戶從 EA、Open 或其他授權方案切換至雲端解決方案提供者的自動程序。 這是需要合作夥伴和客戶手動操作的程序。 此外，目前無法變更 Office 365、Enterprise Mobility Suite 或 Microsoft Dynamics CRM 訂閱之雲端解決方案提供者訂閱的合作夥伴。

 

**切換 Azure 訂用帳戶的合作夥伴**

1.  如果要將 Azure 訂用帳戶移轉至新的合作夥伴，客戶必須開始該程序，並以書面方式連絡其目前記錄的雲端解決方案提供者合作夥伴。

2.  該訂用帳戶的雲端解決方案提供者必須執行下列工作：

    從合作夥伴中心建立 Azure 服務票證以要求訂用帳戶移轉：

    -   在合作夥伴中心儀表板功能表中，選取 \[客戶\]，從清單中選取客戶，然後選取 \[服務管理\]。 在 \[支援票證\] 區段底下，選取 \[新增票證\] 下拉式清單並選擇 \[Microsoft Azure\]。

    -   在 Azure 入口網站中，選取 \[新增支援要求\]。

        在步驟 1 中，選擇 \[訂用帳戶管理\] 做為問題類型，指定您想要移轉的訂用帳戶識別碼，然後選擇 \[雲端解決方案提供者\] 做為支援方案。

        在步驟 2 中，選取 \[C–影響最小\]，然後選擇 \[其他一般問題\] 做為問題類型。

        下載[雲端解決方案提供者訂閱移轉表單](https://assets.windowsphone.com/5222c408-e546-4e01-b72a-2ec7d4c43d57/CSP_Subscription_Transfer_Form_Azure_InvariantCulture_Default.zip)。

3.  訂用帳戶的目前雲端解決方案提供者合作夥伴：請填寫[雲端解決方案提供者訂閱移轉表單](https://assets.windowsphone.com/5222c408-e546-4e01-b72a-2ec7d4c43d57/CSP_Subscription_Transfer_Form_Azure_InvariantCulture_Default.zip)，簽署該表單，然後將它寄給客戶。 如果要填寫表單，您將會需要下列資訊：

    -   目前合作夥伴的連絡資訊和 Microsoft ID。 在 \[合作夥伴中心\] 功能表中，選取 \[帳戶設定\] &gt; \[組織設定檔\]，並使用列於該處的 \[Microsoft ID\]、\[組織名稱\] 與 \[地址\]。

    -   客戶的 Microsoft ID。 在 [合作夥伴中心] 功能表中，選取 [客戶]，然後展開客戶的列表以查看其 [Microsoft ID]。

    -   要移轉的訂閱識別碼。 在展開的客戶列表中，選取 \[檢視訂閱\]，然後展開已選擇的訂閱以查看 \[訂閱識別碼\]。

4.  客戶和訂閱的新雲端解決方案提供者：

    檢閱表單，填寫新合作夥伴的相關資訊，然後簽署該表單。 確認新客戶已準備好合約協定。 將表單重新寄給目前記錄的合作夥伴。

    *重要*：如果新的雲端解決方案提供者與客戶之間沒有經銷商關係，則他們必須在移轉之前建立關係。 [您可以在這裡找到相關做法的資訊](https://int.msdn.microsoft.com/en-us/library/partnercenter/mt750320.aspx)。

5.  目前的雲端解決方案提供者合作夥伴︰

    請確定表單包含兩個合作夥伴系統管理員的連絡資訊 - Microsoft 支援服務將會連絡這兩個系統管理員以驗證移轉。 請確定三個簽名皆已正確簽署，然後使用 [檔案上傳] 選項將已完成的表單連結至現有的服務要求。 一位 Microsoft 支援服務工程師將會在上班時間的 8 小時內回覆您，以驗證接收及完成。

6.  新的雲端解決方案提供者合作夥伴：

    更新 Azure 訂用帳戶設定以將舊合作夥伴從帳戶中移除。 如果要查看已佈建的角色指派，請執行兩個 Powershell Commandlet。

    -   在帳戶上將新合作夥伴新增為經銷商：

        **PS C:\\&gt; Add-AzureRMAccount -tenant "CustomerDomainName"**

        尋找 customerDomainName：在 \[合作夥伴中心\] 功能表中，選取 \[客戶\]。 從客戶清單中選取客戶。 在 [客戶] 功能表中，選取 [帳戶]，並使用 [網域名稱] 的內容。

    -   在帳戶上檢視角色，包括先前的雲端解決方案提供者合作夥伴：

        **PS C:\\&gt; Get-AzureRMRoleAssignment**

    透過在 Azure 入口網站中管理訂用帳戶，來移除過時的訂用帳戶及資源存取權限。 在 [合作夥伴中心] 功能表中，選取 [客戶]。 展開客戶的列表並選取 [檢視訂閱]。 在 [客戶] 功能表中選取 [服務管理]。 在 [Microsoft Azure] 下方，按一下連結以移至 [Microsoft Azure 管理入口網站]。

 

 






<!--HONumber=Nov16_HO4-->


