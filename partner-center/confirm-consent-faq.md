---
title: Microsoft Cloud 合約客戶接受確認常見問題集 | 合作夥伴中心
ms.topic: article
ms.date: 03/15/2019
Description: 客戶接受確認的常見問題
author: LauraBrenner
ms.author: labrenne
keywords: 客戶、客戶、同意、常見問題、MCA、Microsoft Cloud 合約
ms.localizationpriority: medium
ms.openlocfilehash: c6681b4b979352b58258837d85d8c88543d16ed0
ms.sourcegitcommit: bae29ab191c72e15259d99c40c69a9e7c3f2b502
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 08/06/2019
ms.locfileid: "68820459"
---
# <a name="microsoft-cloud-agreement-customer-acceptance-confirmation-frequently-asked-questions"></a>Microsoft Cloud 合約客戶接受確認常見問題集

-   [處理程序](##processfaq)

-   [原則](#policyfaq)

-   [提供技術支援](#technicalfaq)

-   [其他資源](#additionalresourcesfaq)


## <a href="" id="processfaq"></a>流程

**確認客戶接受 Microsoft Cloud 合約的新程式為何？**

Microsoft 致力於協助客戶與合作夥伴持續符合規範。 身為 Microsoft 雲端解決方案提供者 (CSP) 計畫的合作夥伴, 您必須負責審查 Microsoft 的條款及條件, 包括可接受的 Microsoft 產品和服務使用。 為了進一步協助合作夥伴符合合規性需求, 並確保透明度, 我們會啟用新的程式, 要求 CSP 合作夥伴確認其客戶已接受 Microsoft Cloud 合約條款。 從2018年8月7日起, 我們在合作夥伴中心儀表板使用者介面中引進了新的欄位, 並為合作夥伴提供這項資訊的合作夥伴中心 API。 一開始, 您可以選擇是否要提供這種確認, 但從2018年11月7日起將會需要。 

**這項需求何時會生效？**

合作夥伴在 2018 年 8 月 7 日此功能上線後即可開始確認接受合約。 自2018年11月7日起, 合作夥伴中心儀表板使用者必須確認客戶接受所有新交易的 Microsoft Cloud 合約。 2019年3月22日, 合作夥伴中心 API 使用者必須執行相同的動作。 應用程式開發介面使用者的期限已延長, 讓他們有更多時間來執行技術。

**新增 |Microsoft 是否會驗證合作夥伴提供的客戶資訊是否正確？**

Microsoft 會驗證所提供的客戶電子郵件地址格式是否正確。 合作夥伴必須負責提供正確的資訊, 並更正任何發現不正確的資訊。 

**新增 |合作夥伴如何證明客戶接受 Microsoft Cloud 合約、是否已簽署、記載、數位化或在紙張上？**

合作夥伴必須負責確保客戶已接受 Microsoft Cloud 合約的條款, 以及管理自己的程式和記錄。 藉由使用合作夥伴中心儀表板或合作夥伴中心 API 程式, 合作夥伴會確認客戶已接受 Microsoft Cloud 合約的條款。

**新增 |Microsoft 會如何檢查客戶的確認程式是否已完成？**

自2018年11月7日起, 當 CSP 合作夥伴使用合作夥伴中心儀表板為新的或現有的客戶起始交易時, Microsoft 的系統會自動檢查合作夥伴中心是否有客戶確認資訊儀錶. 如果沒有，交易將無法完成。 

自2019年3月22日起, 當 CSP 合作夥伴使用合作夥伴中心 API 為新的或現有的客戶起始交易時, Microsoft 的系統會自動檢查客戶確認資訊是否存在。 如果沒有，交易將無法完成。 

**新增 |是否將通知傳送給在確認程式中提供電子郵件地址的客戶？**

沒有任何通知進程。

## <a href="" id="policyfaq"></a>策略

**為什麼 Microsoft 要求合作夥伴確認客戶已接受 Microsoft Cloud 合約？** 

Microsoft Cloud 合約提供對 Microsoft Cloud 產品與服務訂單認可的客戶使用權、條款及條件，以保護合作夥伴、客戶和 Microsoft。 

適當地執行 Microsoft Cloud 合約可確保我們的合作夥伴、客戶和 Microsoft 藉由確認許多重要主題的相互一致, 包括但不限於安全性、隱私權和資料保護。 確認程式可確保透明度和對齊, 並可讓 Microsoft 更進一步協助需要立即回應法規查詢的客戶。

**完成確認程式需要哪些客戶資訊？**
需要與接受此合約之人員相關的下列資訊：
-   接受合約的日期
-   名字和姓氏
-   電子郵件地址
-   電話號碼 (選用) 

**新增 |如果我們不符合到期日, 會發生什麼事？**

合作夥伴在 2018 年 8 月 7 日此功能上線後即可開始確認接受合約。 自2018年11月7日起, 合作夥伴中心儀表板使用者必須確認客戶接受所有新交易的 Microsoft Cloud 合約。 2019年3月22日, 合作夥伴中心 API 使用者必須執行相同的動作。

在強制執行時, 將不會允許現有客戶的新購買或現有訂用帳戶的基座變更, 直到客戶接受獲得確認為止。 對於新客戶，除非確認接受合約，否則不允許進行交易。 自動續約不受此要求條件影響。

**這項需求適用于哪些區域？**

Microsoft 公用雲端下的所有區域都需要確認客戶接受 Microsoft Cloud 合約。 國内雲 (包括 Microsoft Cloud for US Government 和 Microsoft Cloud Germany) 不支援客戶接受合約確認。

**哪些合作夥伴負責確認客戶接受 Microsoft Cloud 合約？**

自2018年11月7日起, 雲端服務提供者 (CSP) 間接提供者和 CSP 直接帳單合作夥伴同時負責確認客戶的接受度, 並可使用合作夥伴中心 API 或合作夥伴中心儀表板來執行這項操作。 間接提供者可能需要先從其間接轉銷商收集必要的資訊, 然後透過合作夥伴中心 API 或合作夥伴中心儀表板, 將其提供給 Microsoft。 依履約, 這是與 Microsoft 有系結合約的間接提供者, 可確保其 CSP 轉銷商的客戶已接受 Microsoft Cloud 合約。 

**哪些客戶案例需要確認客戶接受 Microsoft Cloud 合約？**

當 CSP 合作夥伴想要進行下列交易時, 必須確認接受 Microsoft Cloud 合約:
1.  新客戶完成新購買
2.  現有的客戶完成新購買
3.  現有的客戶將基座計數更新為現有的訂用帳戶

**我可以確認現有客戶的接受與新購買或基座增加嗎？**

是的。 客戶接受可針對 Microsoft Cloud 合約所涵蓋的所有客戶進行確認。

**具有多個 CSP 合作夥伴的客戶需求有哪些？**

確認接受合約是由合作夥伴進行確認。 如果客戶會與多個雲端解決方案提供者合作夥伴進行交易，則每個合作夥伴都需確認接受合約。

**我是 CSP 間接轉銷商, 使用 CSP 間接提供者。我的責任為何？**

依履約, 這是與 Microsoft 有系結合約的間接提供者, 可確保客戶已接受 Microsoft Cloud 合約。 不過，間接提供者可能會與間接經銷商另行安排收集客戶接受合約。 在此情況下，間接提供者將需要先向間接經銷商收集必要的客戶接受合約資訊，然後透過合作夥伴中心 API 或合作夥伴中心儀表板將這些資訊提供給 Microsoft。 您可以在間接提供者提出要求時立即提供所需資訊給他們，以支援此程序。

**我是 CSP 間接提供者。我是否需要與我的 CSP 間接轉銷商協調以進行準備？**

我們建議需要向其間接經銷商收集必要客戶接受合約資訊的間接提供者，立即向其間接經銷商傳達此項要求，來協調這項資訊的交付和接受。

**如何向我的客戶說明, 他們應該確認他們接受 Microsoft Cloud 合約嗎？**

適當執行 Microsoft Cloud 合約可確保 Microsoft、其合作夥伴和客戶的相互一致, 包括但不限於安全性、隱私權和資料保護等許多重要主題。 確認程式可確保透明度和對齊, 並可讓 Microsoft 更進一步協助需要立即回應法規查詢的客戶。

**新增 |如果客戶使用單一 CSP 間接提供者, 但使用多個 CSP 間接轉銷商完成交易, 則每個 CSP 間接轉銷商是否需要提供 CSP 間接提供者與確認資訊？**

CSP 間接提供者會負責提供向 Microsoft 接受之 Microsoft Cloud 合約的確認。 針對每個客戶帳戶, 合作夥伴中心儀表板一次只能記錄一項確認。 

CSP 間接提供者會負責確認負責同意 Microsoft Cloud 合約的客戶聯絡人是否已完成這項作業, 而不論他們使用的 CSP 間接轉銷商人數為何。

**新增 |誰應該是已獲授權的人員, 才能確認是否接受客戶組織內的 Microsoft Cloud 合約？**

合作夥伴必須負責從客戶組織內的人員取得 Microsoft Cloud 合約的客戶接受。 客戶必須負責判斷誰已獲授權可提供接受。 

**新增 |哪個版本的 Microsoft Cloud 合約是負責確認客戶接受的夥伴？合作夥伴是否需要指出客戶已接受哪個版本的 Microsoft Cloud 合約？**

在與新客戶進行 CSP 交易時, 合作夥伴會負責使用最新的 Microsoft Cloud 合約。 當您更新、變更或完成現有客戶的新交易時, 合作夥伴必須確認接受最新的 Microsoft Cloud 合約。 

在更新之前, Microsoft Cloud 合約會更新, 合作夥伴不需要讓客戶立即重新取得 Microsoft Cloud 合約的客戶接受, 但必須先確認同意 Microsoft Cloud 合約更新。 不過, 您可能會想要讓客戶在續約之前接受新的條款, 以利用 Microsoft Cloud 合約中的新功能和改良的條款。

**新增 |我是 CSP 間接轉銷商。如果我記錄客戶接受我的公司記錄中的 Microsoft Cloud 合約, 是否也需要透過合作夥伴中心儀表板或合作夥伴中心 API 提供這項資訊？**

依履約, 這是與 Microsoft 有系結合約的間接提供者, 可確保客戶已接受 Microsoft Cloud 合約。 不過，間接提供者可能會與間接經銷商另行安排收集客戶接受合約。 在此情況下，間接提供者將需要先向間接經銷商收集必要的客戶接受合約資訊，然後透過合作夥伴中心 API 或合作夥伴中心儀表板將這些資訊提供給 Microsoft。

**新增 |如果我的客戶不同意 Microsoft Cloud 合約的條款, 該怎麼辦？**

身為 Microsoft 的 CSP 計畫合作夥伴, 您必須負責客戶在下訂單之前接受 Microsoft Cloud 合約。 這不是新的需求。 基於任何原因, 如果客戶不再同意 Microsoft Cloud 合約, 則合作夥伴必須取消與此客戶相關聯的訂用帳戶。

**新增 |轉銷商可以代表客戶提供同意嗎？**

資料分割

**當我確認客戶已提供接受之後, 我是否需要在未來為客戶重新確認？**

一旦您確認客戶已接受 Microsoft Cloud 合約, 這項資訊就會保留在合作夥伴中心的客戶帳戶區段中, 而且不需要在客戶涵蓋的持續時間內重新確認接受合約條款。 在放置新訂單之前, 您必須先重新確認接受。

在更新之前, Microsoft Cloud 合約會更新, 合作夥伴不需要讓客戶立即重新取得 Microsoft Cloud 合約的客戶接受, 但必須先確認同意 Microsoft Cloud 合約更新。 不過, 您可能會想要讓客戶在續約之前接受新的條款, 以利用 Microsoft Cloud 合約中的新功能和改良的條款。

**新增 |我不熟悉提供 Microsoft my 客戶的直接連絡人資訊。Microsoft 將如何使用此資訊？**

當合作夥伴建立客戶租使用者時, 必須提供客戶的主要連絡人資訊。 根據線上服務條款, 「Microsoft 只會處理來自客戶的記載指示」的個人資料。

## <a href="" id="technicalfaq"></a>提供技術支援

**合作夥伴如何確認客戶接受, 並將其提供給 Microsoft？有哪些工具可支援此程式？**

從2018年8月7日開始, 有兩種方法可協助合作夥伴: 
1.  合作夥伴可以使用合作夥伴中心 API，透過程式設計方式來確認客戶接受合約條款。 
2.  合作夥伴可以使用合作夥伴中心儀表板來確認客戶接受度。

**新增 |我是使用合作夥伴中心 API 的 CSP 合作夥伴。我需要考慮哪些 API 變更？** 

在此情況下, 的 API 會變更為的帳戶:

-   [https://docs.microsoft.com/partner-center/develop/get-confirmation-of-customer-consent](https://docs.microsoft.com/partner-center/develop/get-confirmation-of-customer-consent) 

-   [https://docs.microsoft.com/partner-center/develop/get-agreement-metadata](https://docs.microsoft.com/partner-center/develop/get-agreement-metadata)

-   [https://docs.microsoft.com/partner-center/develop/confirm-customer-consent](https://docs.microsoft.com/partner-center/develop/confirm-customer-consent)

**如果我在執行合作夥伴中心 API 時遇到困難, 該怎麼辦？**

您可以透過合作夥伴中心儀表板手動確認接受合約。

**新增 |除了使用合作夥伴中心儀表板或合作夥伴中心 API 之外, 我可以改以客戶確認資訊來大量上傳檔案嗎？**

目前, 合作夥伴中心儀表板和合作夥伴中心 API 是唯一接受的方法, 可讓客戶接受 Microsoft Cloud 合約的確認。

**新增 |我是使用協力廠商平臺或「中介軟體」的合作夥伴, 其會執行將公司系統與合作夥伴中心連接的功能。我需要做什麼？**

我們建議使用整合合作夥伴中心 API 之平臺的合作夥伴直接與提供者交談, 以整合合作夥伴中心 API 功能來自動化客戶確認流程。

**新增 |您可以提供 API 流程範例來匯入客戶的完整名稱、電子郵件地址, 以及接受 Microsoft Cloud 合約的日期嗎？**

建議合作夥伴參閱合作夥伴中心 API 檔, 以取得詳細資料和範例。

**新增 |如何? 取得最新的 Microsoft Cloud 合約以向客戶顯示, 並在我的 API 程式中使用於確認記錄中嗎？**

目前的合作夥伴中心 API 非常基本, 並不會提供合作夥伴以程式設計方式取得 Microsoft Cloud 合約的複本, 也不會在確認時, 捕捉客戶所接受的 Microsoft Cloud 合約版本。 

**新增 |針對此程式使用合作夥伴中心 API 需要 userID 參數。當訂單是透過未與 Azure AD 整合的協力廠商平臺進行時, 如何? 管理這項需求嗎？**

在此情況下, userID 會識別合作夥伴租使用者下提供客戶同意確認的員工。 如果員工在合作夥伴的租使用者下沒有對應的 Azure AD 使用者帳戶, 則建議您為該用途指定特定的使用者帳戶, 並建立一個程式來個別捕捉提供確認. 

**新增 |為什麼 Microsoft 要求合作夥伴確認客戶同意 Microsoft Cloud 合約, 而不是直接從客戶處取得？**

客戶是從 CSP 合作夥伴購買, 而不是直接向 Microsoft 購買。 若使用 Microsoft 提供的服務, Microsoft 會提供 Microsoft Cloud 合約中記載的條款。 Microsoft Cloud 轉銷商合約要求 CSP 合作夥伴必須先審查並接受 Microsoft Cloud 合約, 然後再訂購訂單。 

**新增 |我同時使用 API 和合作夥伴中心儀表板 web 使用者介面來確認 Microsoft Cloud 合約客戶接受。2018年11月7日之後, 我可以選擇哪些選項來確認客戶接受？**

這兩個選項都可以使用, 並可接受確認 Microsoft Cloud 合約客戶接受。 使用合作夥伴中心儀表板的交易將需要自2018年11月7日起的確認。 使用合作夥伴中心 API 的交易將需要自2019年3月22日起的確認。

## <a href="" id="additionalresourcesfaq"></a>其他資源

若要深入瞭解如何確認客戶接受 Microsoft Cloud 合約, 請參閱[確認客戶接受 Microsoft Cloud 合約](https://docs.microsoft.com/partner-center/confirm-consent)。

若要尋找所有支援語言的區域特定 Microsoft Cloud 合約客戶範本, 請參閱[依區域和語言 Microsoft Cloud 協定](agreements.md)。
