---
title: 確認客戶接受 Microsoft 客戶合約 |合作夥伴中心
ms.topic: article
ms.date: 04/16/2019
Description: 身為合作夥伴, 您必須先取得客戶的 Microsoft 客戶合約接受者, 才能訂購該客戶的 Microsoft 產品和服務。 為了進一步協助合作夥伴符合合規性需求, Microsoft 會要求合作夥伴提供有關接受合約之人員的特定詳細資料, 以確認接受。
author: LauraBrenner
ms.author: labrenne
keywords: 客戶、客戶、同意、MCA、Microsoft Cloud 合約、Microsoft 客戶合約、客戶合約範本
ms.localizationpriority: medium
ms.openlocfilehash: 6ca8eb3acdee0114f01dbd5952e9c092859147a2
ms.sourcegitcommit: ee722dc2b9d82557d273738b64cec6d8cb435084
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 07/31/2019
ms.locfileid: "68681754"
---
# <a name="confirm-customer-acceptance-of-the-microsoft-customer-agreement-preview"></a>確認客戶接受 Microsoft 客戶合約 (預覽)

目前, 客戶必須接受並簽署適用的**Microsoft Cloud 合約**, CSP 合作夥伴才能代表客戶下訂單。 然後, 合作夥伴必須提供簽署者的相關資訊給 Microsoft, 以確認客戶的接受度。 如果客戶未確認其接受 Microsoft Cloud 合約:
- 您將無法為此客戶建立新訂單。
- 您將無法變更此客戶現有基座型訂閱的基座數目。

如需如何使用合作夥伴中心儀表板或 API 來確認客戶接受 Microsoft Cloud 合約的詳細資訊, 請參閱[確認客戶接受 Microsoft Cloud 合約](confirm-consent.md)。

Microsoft 將在2019年10月1日引進 CSP 計畫的**Microsoft 客戶合約**, 以取代 Microsoft Cloud 合約。 為了協助合作夥伴遷移至新的合約, 在2019年1月31日前, CSP 方案中將支援目前的 Microsoft Cloud 合約。 如需更多時間軸詳細資料, 請參閱下表:

| Date | 里程碑 | 詳細資料 |
|------------|------------|--------------------------------|
|2019年8月01日|沙箱中提供 UX 預覽|合作夥伴可以在 CSP 沙箱環境中使用合作夥伴中心儀表板, 確認客戶接受 Microsoft 客戶合約。 具有 CSP 沙箱環境存取權的合作夥伴可預覽使用者體驗變更。 沒有沙箱存取權的合作夥伴可以深入瞭解本主題中的變更。|
|2019年9月2日|API 預覽適用于沙箱。|合作夥伴可以在 CSP 沙箱環境中使用合作夥伴中心 API 來確認客戶接受 Microsoft 客戶合約。 API 合作夥伴可以使用此機會預覽 API 變更, 並開始處理 API 整合以支援新的合約。|
|2019年10月01日|可在生產環境中使用的 Microsoft 客戶合約|Microsoft 會將 Microsoft 客戶合約引進 CSP 計畫, 以取代 Microsoft Cloud 合約。 合作夥伴可以在生產環境中使用合作夥伴中心儀表板和 API, 確認客戶接受 Microsoft 客戶合約。 CSP 合作夥伴計畫中仍支援 Microsoft Cloud 合約。 不過, 建議合作夥伴開始遷移至 Microsoft 客戶合約。 現有訂用帳戶的新購買和基座計數變更將需要 Microsoft 客戶合約或 Microsoft Cloud 合約的合作夥伴確認。 某些新供應專案 (例如新的 Azure 方案) 將需要確認 Microsoft 客戶合約。|
|2019年1月31日|已從生產環境中移除 Microsoft Cloud 合約|CSP 合作夥伴計畫中不再接受 Microsoft Cloud 合約。 現有訂閱的新購買和基座計數變更將需要合作夥伴提供 Microsoft 客戶合約的確認。 這項需求適用于新客戶及先前可能已接受 Microsoft Cloud 合約的現有客戶。|


## <a name="confirm-customer-acceptance-for-new-customers"></a>確認客戶接受新客戶

當您在合作夥伴中心建立新的客戶租使用者時, 請使用下列步驟來確認客戶是否接受 Microsoft 客戶合約。 您必須是系統管理員代理程式或銷售代理程式, 才能執行這些步驟。

1. 選取 **\[客戶\]** ，然後選取 **\[新客戶\]** 。

2. 在 [**帳戶資訊**] 底下, 輸入公司及其主要連絡人的資訊。

3. 在 [ **microsoft 合約**] 底下, 選取**microsoft 客戶合約**。

4. 在 **\[合約接受日期\]** 下方，輸入適當的日期。 您不能將此設定為未來日期。

5. 請確定顯示的主要使用者連絡人資訊是正確的。 如果不正確, 請選取 [**更新**], 然後輸入接受合約之人員的**名字**、**姓氏**、**電子郵件地址**和**電話號碼**(選擇性)。

6. 選取 **\[下一步\]** 以繼續建立客戶租用戶的其餘步驟。

![新客戶](images/mcua1.png)

## <a name="confirm-customer-acceptance-for-existing-customers"></a>確認客戶接受現有客戶

您必須是管理員代理程式或銷售代理程式才能執行此動作:

1. 選取 [**客戶**]。 尋找並選取 [客戶]。

2. 選取 [**帳戶資訊**]。

3. 在 [ **Microsoft 客戶合約**] 底下, 選取 [**更新**]。

4. 輸入接受合約之人員的 [**名字**]、[**姓氏**]、[**電子郵件地址**] 和 [**電話號碼**] (選擇性)。 在 **\[合約接受日期\]** 下方，輸入適當的日期。 您不能將此設定為未來日期。

5. 選取 [**儲存**並繼續]。

![現有客戶](images/mcua2.png)

## <a name="retrieve-confirmation-of-customer-acceptance"></a>取得客戶接受的確認

您可以使用下列步驟來取得現有客戶已接受 Microsoft 客戶合約的確認。 您必須是系統管理代理人或銷售代理人，才能執行此動作。

1. 選取 **\[客戶\]** ，然後尋找並選取您想要查看的客戶。

2. 選取 [**帳戶資訊**]。

3. 在 [ **Microsoft cloud 合約**] 底下, 如果此客戶未提供確認, 請參閱。


