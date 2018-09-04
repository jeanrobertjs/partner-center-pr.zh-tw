---
title: 確認 Microsoft Cloud 合約客戶接受 |合作夥伴中心
Description: As a partner, you need to obtain your customer’s acceptance of the Microsoft Cloud Agreement before you can order Microsoft products and services for that customer. To better help partners meet compliance requirements, Microsoft asks partners to confirm acceptance by providing certain details regarding the person who accepted the agreement.
author: v-petand
keywords: 客戶，客戶同意
ms.localizationpriority: medium
ms.openlocfilehash: 0c3b3f63f0134793130d8358a1f52e3ed9d41908
ms.sourcegitcommit: 92629114d5081103bfe555081f69997af4ed56f2
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 08/31/2018
ms.locfileid: "2876218"
---
# <a name="confirm-customer-acceptance-of-the-microsoft-cloud-agreement"></a>確認 Microsoft Cloud 合約客戶接受

**適用對象：**
-  合作夥伴中心

身為合作夥伴，您需要之前，您可以訂購 Microsoft 產品及服務，該客戶取得您的客戶接受的 Microsoft Cloud 合約。 為了更進一步協助合作夥伴符合合規性需求，Microsoft 要求合作夥伴以確認接受藉由提供接受授權合約的人相關的下列詳細資料： 

-   名字

-   姓氏

-   電子郵件地址

-   電話號碼

-   接受的日期

若要深入了解，請參閱[Microsoft Cloud 合約客戶接受確認常見問題集](https://docs.microsoft.com/en-us/partner-center/confirm-consent-faq)。

## <a name="schedule"></a>排程

**2018 年 8 月 7日日**

-   直接帳單合作夥伴與間接提供者可以確認 Microsoft Cloud 合約客戶接受。 確認是*選擇性*的。

-   客戶接受的確認可以透過合作夥伴中心儀表板或 Partner Center API 來完成。

-   客戶接受的確認僅支援與 Microsoft 公用雲端。


**2018 年 11 月 7日日**

-   直接帳單合作夥伴與間接提供者**必須**確認 Microsoft Cloud 合約客戶接受。 確認是*必要*的。

-   如果對於特定客戶未提供確認：

    -   您將無法建立新此客戶訂單。

    -   您將無法變更此客戶中的基座為基礎的現有訂閱的基座數目。

-   客戶接受的確認可以透過合作夥伴中心儀表板或 Partner Center API 來完成。

-   客戶接受的確認僅支援與 Microsoft 公用雲端。


## <a name="confirming-customer-acceptance-using-partner-center-dashboard"></a>確認客戶接受使用合作夥伴中心儀表板

### <a name="confirm-customer-acceptance-for-a-new-customer"></a>確認客戶接受為新客戶

若要確認客戶接受您在合作夥伴中心儀表板中建立新的客戶租用戶時使用下列程序。 請注意，您必須執行此作業的系統管理代理人或銷售代理程式。 
1.  選取**客戶**，然後按一下 [**新的客戶**。

2.  請輸入**公司**和**主要連絡人**資訊。

3.  在**Microsoft cloud 合約**、 選取**客戶已接受的最新的 Microsoft cloud 合約**。 

4.  在 [**協定接受日期**，輸入的適當日期。 您無法將此設定為未來的日期。

5.  輸入提供接受之使用者的詳細資料。 

    根據預設，會顯示主要連絡人的使用者資訊。 如果這不正確，選取 [**更新**]，然後輸入 [**名字**、**姓氏**、**電子郵件地址**，以及 **電話號碼*（選擇性） 的接受授權合約的人。

    **附註：** 確認客戶的前接受會成為強制執行，您可能會略過確認不選取**客戶已接受的最新的 Microsoft cloud 合約**的選項，然後選取 [**下一步**。

6.  選取 [**下一步**繼續進行其餘的步驟，以建立客戶租用戶。

### <a name="confirm-customer-acceptance-for-an-existing-customer"></a>確認客戶接受現有的客戶

您必須執行此作業的系統管理代理人或銷售代理程式。 

1.  選取**客戶**，然後尋找並選取您想要查看的客戶。 

2.  選取**的帳戶**。

3.  **Microsoft cloud 合約**，選取 [**更新**]。

4.  **名字**、**姓氏**、**電子郵件地址**及**電話號碼**（選用） 接受授權合約之使用者的輸入。

5.  在 [**協定接受日期**，輸入的適當日期。 您無法將此設定為未來的日期。

6.  選取 [**儲存並繼續**。

### <a name="confirm-customer-acceptance-while-creating-new-order-for-an-existing-customer"></a>確認客戶接受建立新的順序，現有的客戶時

如果您嘗試建立新的順序，現有的客戶其中您不確定之前，您會收到完成確認的提示。 您可以使用下列程序來執行此動作。 

1.  **名字**、**姓氏**、**電子郵件地址**及**電話號碼**（選用） 接受授權合約之使用者的輸入。

2.  在 [**協定接受日期**，輸入的適當日期。 您無法將此設定為未來的日期。

3.  選取 [**儲存並繼續**。

**附註：** 客戶接受的確認成為強制之前，您可以跳確認選取**取消**。

### <a name="retrieve-confirmation-of-customer-acceptance-for-an-existing-customer"></a>擷取確認客戶接受現有的客戶

您可以擷取的客戶接受您提供先前使用下列程序的現有客戶的確認。 您必須執行此作業的系統管理代理人或銷售代理程式。 

1.  選取**客戶**，然後尋找並選取您想要查看的客戶。 

2.  選取**的帳戶**。

3.  **Microsoft cloud 合約**，您會看到確認已提供給此客戶。

