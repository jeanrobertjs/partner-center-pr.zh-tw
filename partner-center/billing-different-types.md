---
title: 了解計費合作夥伴中心中的類型 |合作夥伴中心
ms.topic: article
ms.date: 03/01/2019
Description: 不同計費類型，計費週期，和帳單寄送日期的詳細資訊
author: MaggiePucciEvans
ms.author: evansma
keywords: 計費、 付款、 訂單、 對帳檔案、 偵察檔案
ms.localizationpriority: medium
ms.custom: seodec18
ms.openlocfilehash: 4b2b42c0d9bbb2654bbd486f987e3d5da9c562a2
ms.sourcegitcommit: b1ab80345b4e4af649fb8cc51d96d798e0791ade
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 04/23/2019
ms.locfileid: "62135378"
---
# <a name="understanding-the-types-of-billing-in-partner-center"></a>了解合作夥伴中心的帳單類型

**適用於**

-  合作夥伴中心
-  CSP 計劃中的合作夥伴

根據您為您的客戶購買的產品類型，您可能會有不同的計費週期，並在同一個月份的不同日計費。 這篇文章會說明哪些方面受到變更啟動 2019 年 3 月 1 日，以及變更如何影響您。

## <a name="billing-for-recurring-charges"></a>週期性費用的計費

週期性費用的授權和使用方式為基礎的訂用帳戶的計費體驗不會變更。 我們會繼續向您收取費用，在您選取做為您的帳單寄送日期的月份天數，並在計費期間會繼續在此日期之前的月份。 如果您選取您的帳單寄送日期的月份第 15 天，您將支付從一個月 15 日至 14 日下, 一個日曆月份的所有活動。 發票和對帳檔案是正式推出的 2-4 天之後您的帳單寄送日期。

如之前，我們會針對向您收費的貨幣位於該國家/地區中的這些產品，無論客戶的位置為何您銷售產品。

## <a name="billing-for-one-time-and-select-recurring-charges"></a>計費一次，然後選取週期性費用

我們開始 2019 年 3 月 1 日，Microsoft 和第三方 ISV 產品引進新的計費體驗，針對週期性和一次性費用。

這些產品，計費週期在下個月的第一天開始，並將於下個月的最後一天結束。 我們將提供您發票的下個月 8 日當天。 

換句話說，5 月 1 日與 2019 5 月 31 日之間進行任何交易將出現在您的發票 June 8。 任何要年 6 月 1 和 2019 年 6 月 30 日之間的交易上會出現您的發票年 7 月 8。 您可能會在相同的發票上的週期性和單次購買計費。 

當您想要 （比方說，之間 5 月 1 日和年 6 月 7），並查看最新的帳戶活動，而不必等候支付發票，您也可以查看您帳戶的餘額/帳單。 請注意，當我們 8 日上張貼您的帳單時，它會包含稅金和任何其他適用的費用和信用額度，因此最後可能會與您在計費週期內所看到的內容不同。 

您將相同的方式，現在該怎麼做，在合作夥伴中心內或透過 API 存取您的發票。 即會顯示在每月 8 日當天的午夜 UTC 之前。 

|**計費體驗**|**產品類型**|**帳單日期**|**計費週期**|**帳單貨幣**|**目前的活動可以使用？**|
|:----------------|:--------------|:--------------|:--------------|:--------------|:--------------|
|週期性費用，以授權為基礎和基於使用方式的訂用帳戶 |從所有的產品[online services 目錄](https://partner.microsoft.com/commerce/preferredoffers/list)。 範例包括 Office 365，Microsoft 365、 Azure Active Directory、 Azure （隨用隨付），Dynamics 365，power Bi Pro |您選取您在建立您的合作夥伴中心帳戶時的日期 |計費日期前月份。 |您要在中找到的國家/地區當地貨幣。 例如，如果您的公司位於英國，我們會向您收取費用在英國英鎊 (GBP)。 如果您的公司位於印度，我們會向您收取費用在印度 Rupees （幣）。  |否 |
|Microsoft 和第三方 Isv 產品的週期性和一次性費用 |所有 SaaS 訂用帳戶、 Azure 保留的項目和 Microsoft 和第三方 Isv 所提供的軟體 （永久的而且訂用帳戶為基礎） 產品。 請參閱中的可用產品[Marketplace](https://partner.microsoft.com/commerce/sales?type=Any&category=Any)。 範例包括 SUSE Linux 軟體 （軟體訂用帳戶），Windows Server 2019 Essentials （永久軟體），Azure ISV SaaS 產品訂用帳戶。 |每個月 8 日的一天 |從每個日曆月份的最後一天的第一天 |位客戶的國家/地區當地貨幣。 這表示您會收到個別的發票和對帳檔案中的國家/地區當地貨幣計費週期內銷售給每位客戶。 |是 |
