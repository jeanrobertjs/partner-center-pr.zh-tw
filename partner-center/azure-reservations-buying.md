---
title: 代表您的客戶購買 Microsoft Azure Reservations | 合作夥伴中心
ms.topic: article
ms.date: 03/15/2019
Description: 您可以購買 Azure 保留的項目代表您的客戶在合作夥伴中心。
author: LauraBrenner
ms.author: v-petand
keywords: azure, 保留區, 管理, 計費, 購買
ms.localizationpriority: medium
ms.custom: seodec18
ms.openlocfilehash: bf9d3bf1869a151172931f100cf10b28a7d75f27
ms.sourcegitcommit: b1ab80345b4e4af649fb8cc51d96d798e0791ade
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 04/23/2019
ms.locfileid: "62134678"
---
# <a name="buy-microsoft-azure-reservations-on-behalf-of-your-customers-in-partner-center"></a>購買 Microsoft Azure 保留項目代表您的客戶在合作夥伴中心 

**適用於**

-  合作夥伴中心
-  Microsoft Azure 入口網站
-  雲端解決方案提供者中的合作夥伴

## <a name="before-you-begin"></a>開始之前

代表客戶購買 Azure 保留的項目之前，請檢閱下列重要資訊。

-   在您代表客戶購買保留區之前，客戶必須已擁有有效的 Azure 訂閱
  
-   例如，SQL Database 或 SUSE Linux 軟體軟體訂用帳戶成本不包含在 Azure 保留的項目價格

-   Microsoft 的商業價格給您不包含稅金，除非您的位置是巴西。 如果位置是巴西，給您的商業價格包含適當的稅金 
 
-   銷售人員和技術支援中心需能代表客戶明確的存取 Azure 訂閱，以便在 Azure 入口網站與檔案支援要求中購買或管理訂閱，包括換貨與退款  

-   如果您是間接提供者，而且透過 Azure 入口網站購買 Azure Reservations，記錄可查夥伴 (間接經銷商) 將繼承自您選取的 Azure 雲端解決方案提供者訂閱。 

-   Azure Reservations 的記錄可查夥伴在購買後即無法變更。 您可以取消現有的保留區，並透過新的記錄可查夥伴購買新的保留區。 

-   如果客戶想將 Azure 訂閱從直接或 EA 轉移至雲端解決方案提供者，保留區無法轉移。 

## <a name="azure-reservations-unavailable-markets"></a>Azure 保留的項目無法使用市場

>[!IMPORTANT] 
>Azure 保留的項目*不是*用於以下市場：  
>  
> | 無法使用的市場 | &nbsp; | &nbsp; |
> |--------------------------------|-----------------------------------|------------------------------------------|
> | 奧蘭島                  | 格陵蘭                         | 帛琉                                    |
> | 美屬薩摩亞                 | 格瑞那達                           | 巴布亞紐幾內亞                         |
> | 安道爾                        | 哥德普洛                        | 皮特康群島                         |
> | 安圭拉                       | 關島                              | 留尼旺                                  |
> | 南極大陸                     | 根息                          | 俄羅斯聯邦                       |
> | 安地卡及巴布達            | 幾內亞                            | 沙巴                                     |
> | 阿路巴                          | 幾內亞比索                     | 聖巴瑟米                         |
> | 亞塞拜然                     | 蓋亞納                            | 聖露西亞                              |
> | 白俄羅斯                        | 海地                             | 聖馬丁                             |
> | 貝南                          | 赫德島及麥當勞群島 | 聖匹島                |
> | 不丹                         | 印度                             | 聖文森及格瑞那丁         |
> | 波奈                        | 曼城島                       | 薩摩亞獨立國                                    |
> | 布威島                  | 央棉群島                         | 聖馬利諾                               |
> | 巴西                         | 澤西島                            | 聖多美普林西比                    |
> | 英屬印度洋領土 | 哈薩克                        | 塞席爾                               |
> | 英屬維爾京群島         | 吉里巴斯                          | 獅子山                             |
> | 布吉納法索                   | 大韓民國                | 聖佑達修斯                           |
> | 蒲隆地                        | Kosovo                            | 荷屬聖馬丁                             |
> | 柬埔寨                       | 寮國                              | 索羅門群島                          |
> | 中非共和國       | 賴索托                           | 索馬利亞                                  |
> | 查德                           | 賴比瑞亞                           | 南喬治亞及南三明治群島 |
> | 中國                          | 馬達加斯加                        | 南蘇丹                              |
> | 聖誕島               | 馬拉威                            | 聖赫勒拿、 阿森松、 垂斯坦昆哈群島   |
> | 可可斯群島        | 馬爾地夫                          | 蘇利南                                 |
> | 葛摩                        | 馬利                              | 冷岸                                 |
> | 剛果共和國                          | 馬紹爾群島                  | 史瓦濟蘭                                |
> | 剛果民主共和國 (DRC)                    | 馬丁尼克                        | 台灣                                   |
> | 柯克群島                   | 茅利塔尼亞                        | 東帝汶                              |
> | 吉布地                       | 馬約特島                           | 多哥                                     |
> | 多米尼克                       | 密克羅尼西亞                        | 托克勞群島                                  |
> | 赤道幾內亞              | 蒙特色拉特島                        | 東加                                    |
> | 厄利垂亞                        | 莫三比克                        | 土克斯及開科斯群島                 |
> | 福克蘭群島               | 緬甸                           | 吐瓦魯                                   |
> | 法屬圭亞那                  | 諾魯                             | 美國外島                    |
> | 法屬玻里尼西亞               | 新喀里多尼亞群島                     | 烏克蘭                                  |
> | 法屬南半球領土    | 尼日                             | 萬那杜                                  |
> | 加彭                          | 紐威島                              | 梵蒂岡                             |
> | 甘比亞                         | 諾福克島                    | 瓦利斯及福杜納                        |
> | 直布羅陀                      | 北馬里安納群島          | 葉門                                    |
> |

## <a name="purchase-azure-reservations"></a>購買 Azure 保留的項目

請遵循下列步驟來購買 Microsoft Azure 保留項目代表您的客戶在合作夥伴中心。

1. 選取 **客戶**從合作夥伴中心功能表。  

2. 在 **\[客戶\]** 頁面上，尋找想要購買 Azure Reservations 的客戶，然後選取向下箭號來展開客戶列。  

3. 選取 **\[新增產品\]**，然後選取 **\[Azure\]**。 

    a. 選擇從客戶的市場區隔**區段**清單。

    b. 選擇**預約**從產品**型別**清單。

    c.  選擇的客戶想從保留的項目類型**保留項目型別**清單。

4. Azure Reservations 必須關聯至有效的 Azure 訂閱。 選擇您想要新增 Azure 保留項目要從客戶的訂用帳戶**客戶訂用帳戶**清單。 

   >[!IMPORTANT]
   >如果客戶尚未作用中的 Azure 訂用帳戶，請選取**線上服務**現在新增一個。 

5. 使用篩選來尋找符合您的客戶需求的虛擬機器上的 Azure 保留的項目。  

6. 尋找您想要購買的 reservation(s) 後，請輸入在中，客戶將需要的保留執行個體的數目**Quantity** ，然後選取**新增至購物車**。  

7. 重複步驟 5 和 6，直到您新增所有必要的項目至訂單。 選取 **\[檢閱\]** 確認您的訂單正確無誤。  

8. 在 **\[檢視您的訂單\]** 頁面上，您可以： 

    - 確認或變更保留執行個體數量。

    - 選取保留區的範圍。 保留區的範圍可以涵蓋一個訂閱或多個訂閱 (共用範圍)。 如果您設定範圍為單一訂用帳戶的保留項目，請保留折扣會套用到此訂用帳戶只。 如果選取共用，保留區折扣會套用至在客戶帳單內容中的任何訂閱。 

      >[!NOTE] 
      >如果您選擇的保留範圍限制為單一的 Azure 訂用帳戶，您可能需要增加訂用帳戶的 vCPU 配額。 若要增加訂用帳戶的 vCPU 配額，您必須在 Azure 入口網站中建立支援要求。 請依照下列指示[本主題中](https://docs.microsoft.com/azure/azure-supportability/resource-manager-core-quotas-request)建立要求。    

    - 如果您是提供者合作夥伴，請選取您想要與產品建立關聯的經銷商。

9. 選取 **\[購買\]** 購買訂單。 您的訂單，包括您的訂單編號的詳細資料會顯示在**確認**頁面。 選取 **\[完成\]** 移至 **\[訂購記錄\]** 頁面。 

10. 若要管理客戶的保留項目，在 Azure 入口網站中，尋找客戶在您**客戶**頁面上，然後選取 向下箭頭以展開客戶的資料列。 選取 **\[Microsoft Azure 管理入口網站\]** 以在 Azure 入口網站中開啟客戶記錄。

## <a name="azure-reservations-resources"></a>Azure Reservations 資源
|**如需詳細資訊**   |**請閱讀本**    |
|:-----------------------------|:-----------------|
|雲端解決方案提供者中的 Azure Reservations 概觀  | [銷售 Microsoft Azure 保留的執行個體](azure-reservations.md) |
|管理 Azure 保留在合作夥伴中心內的項目 | [管理 Azure 保留在合作夥伴中心內的項目](azure-reservations-manage.md)
|判斷正確的 VM 大小，並確認客戶 VM 使用率   |[VM 調整大小的最大的 Azure 保留使用情況](azure-usage.md)   |
|使用合作夥伴中心 API 購買 Azure Reservations | 合作夥伴中心開發人員文件中的[購買 Azure 保留的 VM 執行個體](https://docs.microsoft.com/partner-center/develop/purchase-azure-reservations)
|

 


 
