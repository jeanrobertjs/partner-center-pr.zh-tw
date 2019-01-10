---
title: 確認 Microsoft Cloud 合約客戶接受 |合作夥伴中心
ms.topic: article
ms.date: 10/29/2018
Description: As a partner, you need to obtain your customer’s acceptance of the Microsoft Cloud Agreement before you can order Microsoft products and services for that customer. To better help partners meet compliance requirements, Microsoft asks partners to confirm acceptance by providing certain details regarding the person who accepted the agreement.
author: v-petand
ms.author: v-petand
keywords: 客戶、 客戶、 同意
ms.localizationpriority: medium
ms.openlocfilehash: 356782420046cb8b49ac4e05981becd253d7049a
ms.sourcegitcommit: dcc0517b2441c5577994b802c455fc726cc5cb35
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 01/10/2019
ms.locfileid: "9000028"
---
# <a name="confirm-customer-acceptance-of-the-microsoft-cloud-agreement"></a>確認 Microsoft Cloud 合約客戶接受

**適用於**
-  合作夥伴中心

身為合作夥伴，您需要之前，您可以訂購 Microsoft 產品及服務，該客戶取得您的客戶接受的 Microsoft Cloud 合約。 為了更進一步協助合作夥伴符合合規需求，Microsoft 要求合作夥伴以確認接受藉由提供接受授權合約的人相關的下列詳細資料： 

-   名字

-   姓氏

-   電子郵件地址

-   電話號碼

-   接受的日期

若要深入了解，請參閱[Microsoft Cloud 合約客戶接受確認常見問題集](https://docs.microsoft.com/en-us/partner-center/confirm-consent-faq)。

## <a name="schedule"></a>排程

**2018 年 8 月 7日日**

-   直接帳單合作夥伴與間接提供者可以確認 Microsoft Cloud 合約客戶接受。 確認是*選擇性*的。

-   客戶接受的確認可以透過合作夥伴中心或合作夥伴中心 API 來完成。

-   客戶接受的確認僅支援公用的 Microsoft Cloud 使用。


**2018 年 11 月 7日日**

-   直接帳單合作夥伴與間接提供者**必須**確認 Microsoft Cloud 合約客戶接受。 確認是*必要*的。

-   如果對於特定客戶未提供確認：

    -   您將無法建立此客戶的新訂單。

    -   您將無法變更此客戶中基座為基礎的現有訂閱的基座計數。

-   客戶接受的確認可以透過合作夥伴中心或合作夥伴中心 API 來完成。

-   客戶接受的確認僅支援公用的 Microsoft Cloud 使用。


## <a name="confirming-customer-acceptance-in-partner-center"></a>確認客戶接受在合作夥伴中心

### <a name="confirm-customer-acceptance-for-a-new-customer"></a>確認客戶接受為新客戶

使用下列程序，以確認客戶接受時在合作夥伴中心建立新的客戶租用戶。 請注意，您必須執行此作業的系統管理代理人或銷售代理程式。 
1.  選取**客戶**，然後按一下 [**新的客戶**，然後選取 [**帳戶資訊**。

2.  輸入**公司**和**主要連絡人**的相關資訊。

![公司資訊](images/mca/mca1.png)

3.  **Microsoft cloud 合約**，選取**客戶已接受的最新的 Microsoft cloud 合約**。 

4.  **合約接受日期**] 下輸入適當的日期。 您無法將其設定在未來的日期。

5.  輸入提供接受之使用者的詳細資料。 

![新增接受日期](images/mca/MCA3.png)

根據預設，會顯示主要連絡人的使用者資訊。 如果這不正確，選取 [**更新**]，然後輸入 [**名字**、**姓氏**、**電子郵件地址**，以及 **電話號碼*（選擇性） 的接受授權合約的人。


6.  選取 [**下一步**繼續進行其餘的步驟，以建立客戶租用戶。

### <a name="confirm-customer-acceptance-for-an-existing-customer"></a>確認客戶接受現有的客戶

您必須是系統管理代理人或銷售代理程式，執行此動作。 

1.  選取**客戶**，然後尋找並選取您想要查看的客戶。 

2.  選取 [**帳戶資訊**。

3.  **Microsoft cloud 合約**，選取 [**更新**]。

![更新](images/mca/mca4.png)

4.  輸入的**名字**、**姓氏**、**電子郵件地址**和**電話號碼**（選用） 接受授權合約的使用者。

5.  **合約接受日期**] 下輸入適當的日期。 您無法將其設定在未來的日期。

6.  選取**儲存並繼續**。

### <a name="confirm-customer-acceptance-while-creating-new-order-for-an-existing-customer"></a>確認客戶接受建立新的順序，現有的客戶時

如果您嘗試建立新的順序，現有的客戶其中您不確定之前，您會收到提示，以完成確認。 您可以使用下列程序來執行此動作。 

1.  輸入的**名字**、**姓氏**、**電子郵件地址**和**電話號碼**（選用） 接受授權合約的使用者。

2.  **合約接受日期**] 下輸入適當的日期。 您無法將其設定在未來的日期。

3.  選取**儲存並繼續**。


### <a name="retrieve-confirmation-of-customer-acceptance-for-an-existing-customer"></a>擷取現有客戶的客戶接受的確認

您可以擷取的客戶接受您提供先前使用下列程序的現有客戶的確認。 您必須是系統管理代理人或銷售代理程式，執行此動作。 

1.  選取**客戶**，然後尋找並選取您想要查看的客戶。 

2.  選取 [**帳戶資訊**。

3.  **Microsoft cloud 合約**，您會看到確認已提供給此客戶。

