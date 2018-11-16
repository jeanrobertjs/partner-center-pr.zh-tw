---
title: 代表您的客戶管理 Azure Reservations | 合作夥伴中心
ms.topic: article
ms.date: 10/29/2018
Description: Managing Azure reservations on behalf of your customers.
author: v-petand
ms.author: v-petand
keywords: azure，保留區，管理，帳單，購買、 取消、 exchange，提前終止費用
ms.localizationpriority: medium
ms.openlocfilehash: fde21951dacab70a9f9b03d853647aabcc40d9af
ms.sourcegitcommit: 7a68540d64d17c4d9139da4f94d679f9d91b67c4
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 11/15/2018
ms.locfileid: "7011408"
---
# <a name="manage-microsoft-azure-reservations-on-behalf-of-your-customers"></a>代表您的客戶管理 Microsoft Azure Reservations

**適用對象：**

-  合作夥伴中心
-  Microsoft Azure 入口網站
-  雲端解決方案提供者中的合作夥伴

若要管理您客戶的 Azure reservations 購買後，您選取的客戶和保留區，您想要在合作夥伴中心管理，然後在 Azure 入口網站中對保留區進行變更。 

1. 若要開始，從合作夥伴中心功能表中選取**客戶**，然後選取您想要管理其保留區的客戶。 

2. 客戶的詳細資料頁面在功能表上，選取**Azure reservations** ，然後選取您想要管理的特定保留區。  

3. 在 **\[動作\]** 下方，選取 **\[管理\]** 以移至 Azure 入口網站中客戶的保留區記錄。 在保留區詳細資料頁面上，依照下列步驟以完成任務。  

    | **選取**   | **以**    |
    |:-----------------------------|:-----------------|
    | **概觀**   | 檢視客戶保留區的詳細資料，包括到期日期、範圍和使用率資料。 **注意** 選擇 **\[退款\]** 可建立按比例計算的退款支援要求。 選取 **\[交換\]** 可建立交換未使用的保留區期限的支援要求。  
    | **存取控制 (IAM)**   | 管理客戶保留區資訊的存取權。|
    | **設定**   | 變更保留區的範圍和/或保留區相關聯的 Azure 訂閱。    |
    | **內容**   | 檢視保留區的屬性，並將保留區識別碼和保留區訂單識別碼複製到剪貼簿。 **注意** 當您代表客戶要求支援時，支援人員可能會請您提供保留區識別碼和保留區訂單識別碼。    |
    | **新的支援要求**    | 向 Microsoft 支援服務要求協助。   |
 
## <a name="cancel-or-exchange-a-reservation"></a>取消或交換保留區 

如果在任何時候客戶企業需要變更，他們可能會想要取消保留區並取得退款或交換保留區的按比例計算的退款金額會用於朝向新的保留區的價格。

在這兩種案例中，Microsoft 退款金額給您，讓您接著可以與您的客戶管理產生的財務交易。 Microsoft 不會連絡客戶直接有關帳單、 取消或退款。   
 

**取消的運作方式**

要求客戶可以取消保留區隨時 （退款金額每年 $50000 美元）。 取消保留區，可讓客戶来傳回的量將 Azure reservations 的剩餘月份提早終止費用。 剩下的按比例計算的餘額，減去提早終止費用，被退還至您的帳戶，以便您可將客戶的帳戶。 

請參閱下方的取消詳細資料和費用。


|**取消日期**<br> （天）   |**Usage**    |**取消貸記金額**  |**提早終止**<br> 費用    |**退款上限** | 
|:----------------------------------|:------------|:-----------|:--------------------------------|:--------------|
|5 或更少                         | 否          | 100%       | 否                              | $50000 美元   |
|5 或更少                         | 是         | 專業版分級  | 否                              | $50000 美元   |
|超過 5                        | 否          | 專業版分級  | 12%                             | $50000 美元   |
|超過 5                        | 是         | 專業版分級  | 12%                             | $50000 美元   |


**交換的運作方式** 

如果客戶想要向您購買原先購買比不同保留區，他們可以要求 exchange。 交換保留區可以取消保留區，因為它可讓客戶使用新的保留區的價格朝向依比例計算的退款金額的吸引人的替代方法。 

按比例計算的退款金額是貸記到您的帳戶，以便您可以提供客戶 exchange。


## <a name="request-a-refund-or-exchange-on-behalf-of-a-customer"></a>代表客戶要求退款或交換 

若要代表客戶提出退款或交換的支援要求，您將在合作夥伴中心，選取客戶和保留區，然後在 Azure 入口網站建立支援要求。 

>[!NOTE]
>Microsoft 支援服務專員可能會請您提供保留區識別碼和保留區訂單識別碼。 您可以在 Azure 入口網站中保留區的 **\[內容\]** 頁面上找到此資訊。 

1. 若要開始，從合作夥伴中心功能表中選取**客戶**，然後選取想要退款的客戶。 

2. 在客戶的詳細資料頁面上，選取 **\[Azure Reservations\]**，然後選取客戶想要退款的特定保留區。  

3. 在底下**的動作**，選取以移至 Azure 入口網站中客戶的保留區記錄並初始化支援要求的**退款**。  

4. 在 **\[新的支援要求\]** 頁面上，依照下列步驟來要求退款。 每個步驟之後選取 **\[下一步\]**。 

    |**步驟**                    |**選項**    |
    |:---------------------------|:-----------------|
    |**1 基本知識**                |問題類型：計費  |
    |**2 問題**               |問題類型︰ 保留區管理。 分類：交換與退款。 |
    |**3 連絡人資訊**   |選取您的喜好設定，然後輸入所需的資訊。 

5.  完成時選取 **\[建立\]**。

## <a name="azure-reservations-resources"></a>Azure Reservations 資源
|**如需以下相關資訊**   |**請閱讀本文**    |
|:-----------------------------|:-----------------|
|雲端解決方案提供者中的 Azure Reservations 概觀  | [銷售 Microsoft Azure 保留的執行個體](azure-reservations.md) |
|為您在合作夥伴中心的客戶購買 Azure reservations   |[購買 Azure Reservations](azure-reservations-buying.md) |
|判斷正確的 VM 大小，並確認客戶 VM 使用率   |[調整 VM 大小以提供最大 Azure Reservations 使用率](azure-usage.md)   |
|使用合作夥伴中心 API 購買 Azure Reservations | 合作夥伴中心開發人員文件中的[購買 Azure 保留的 VM 執行個體](https://docs.microsoft.com/partner-center/develop/purchase-azure-reservations)

