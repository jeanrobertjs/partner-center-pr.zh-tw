---
title: Microsoft 了解分析 |合作夥伴中心
ms.topic: article
ms.date: 07/05/2019
description: 如何了解您的學習分析的詳細資訊
author: LauraBrenner
ms.author: labrenne
ms.localizationpriority: medium
ms.openlocfilehash: 09d4ca14c1b407e9010ab26bccaf612f9caad732
ms.sourcegitcommit: bd83621eb29fafbda341ad41814a9ae5c1e78b00
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 07/08/2019
ms.locfileid: "67622526"
---
# <a name="microsoft-learn-analytics-report"></a>Microsoft 了解分析報表

Microsoft 了解報表為您提供包括回呼完成的模組與學習路徑上您公司中的學習模組的詳細資訊。 報表會顯示每個個別的學習模組的狀態。 全域管理員和貴公司的 MPN 系統管理員可以檢視資料。

## <a name="how-to-read-the-report"></a>如何閱讀報告

### <a name="summary-charts"></a>摘要圖表

**訓練人員計數**:對於已完成至少一個模組選取的日期範圍內的所有不同學習模組的計數 

**定型的個人趨勢迷你圖表**:透過每月作用中的學習者的累加計數的月份 

**模組完成計數**:計數的模組完成的交易夥伴的公司中的學習模組選取的日期範圍內。
例如，如果 15 個人，即會完成 「 模組 1 」 和 「 模組 2 」 完成相同的 15 個人，模組完成計數會是 30。 模組完成日期應該落在選取的日期範圍。

**模組完成趨勢迷你圖表**:模組自動完成的月份累計月 

**學習路徑完成計數**:計數的學習路徑完成的夥伴公司中的學習模組所選取的日期範圍內。
例如，如果 「 路徑 1 」 的學習路徑完成 20 的個人，並學習路徑 」 相同的 20 人員完成路徑 2 」、 學習路徑完成計數會是 40。 學習路徑的完成日期應該落在選定的日期範圍內。

**學習路徑完成趨勢迷你圖表**:月的月累加計數的學習路徑自動完成 

### <a name="trained-individuals-monthly-trend"></a>定型的個人每月的趨勢

**X 軸**是選取的時間篩選條件的月份。 

**Y 軸**是作用中的學習者已註冊 （模組中的第一次完成），在該月的計數。 這不是累計的。

### <a name="module-completions-monthly-trend"></a>模組完成每月的趨勢

**X 軸**是選取的時間篩選條件的月份。 

**Y 軸**該月約為計數模組完成。 這不是累計的。

### <a name="learning-path-completions-monthly-trend"></a>學習路徑完成每月的趨勢

**X 軸**是選取的時間篩選條件的月份。 

**Y 軸**為計數模組完成的月份。 這不是累計的。

### <a name="learning-path-completion-tabs"></a>學習路徑完成索引標籤 

- 模組 索引標籤

**模組完成環圈圖**： 模組完成 （在 [摘要] 區段中顯示的計數） 的細項的模組名稱。

數字會顯示在圖表的中心是完成的總模組

**依角色完成**： 角色模組的模組完成的細目。 如果模組是與多個角色相關聯，則每個角色被新增至模組完成的計數。

中的環圈圖中心顯示的數字是模組完成不同的角色數目。 

**依產品的完成**： 模組會對應至該產品所模組完成的細目。 如果模組是與多項產品相關聯，每個產品會加入至模組完成的計數。    

環圈圖的中間顯示的數字是模組完成的不同產品的數目。  

- 學習路徑 索引標籤    

**學習路徑完成環圈圖**： 學習路徑完成 （在 [摘要] 區段中顯示的計數） 的細項的名稱。

**依角色完成**： 分解的學習路徑完成角色。 如果模組是與多個角色相關聯，則每個角色被新增至模組完成的計數。

**依產品的完成**： 分解的學習路徑完成的學習路徑所對應的產品。 如果模組是與多項產品相關聯，每個產品會加入至模組完成的計數。

### <a name="completions-by-learning-individuals"></a>了解個人的自動完成

Microsoft 了解識別學習模組，並提供使用者物件識別碼。 底下**模組 索引標籤**，所有的學習模組會依完成的模組。 它們會顯示其 Microsoft 了解使用者名稱、 物件識別碼和模組計數。 您可以搜尋使用的使用者名稱。

若要取得學習模組的詳細說明如何使用使用者物件識別碼： 

1. 登入[Graph 總管](https://developer.microsoft.com/graph/graph-explorer )。 （您必須是貴公司的 Azure AD 租用戶的全域管理員）。

2. 複製的使用者物件識別碼[反白顯示的區域](https://graph.microsoft.com/v1.0/users/a9633ad7-c8dc-4587-b119-0bc286b0711f)Graph 總管 中。 

