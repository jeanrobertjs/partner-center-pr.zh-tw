---
title: "建立使用者帳戶與設定權限 | 合作夥伴中心"
description: "系統管理員能為每個需要存取合作夥伴中心的合作夥伴員工建立使用者帳戶。"
ms.assetid: 75D805AE-9922-4CFD-9427-196047D70963
author: MaggiePucciEvans
ms.openlocfilehash: 842071dad94251ee498c9dee3e8b689e2e036485
ms.sourcegitcommit: c2a12d6a18b9631916f6dd8301a4752ecc03296b
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 06/19/2017
---
# <a name="create-user-accounts-and-assign-permissions"></a>建立使用者帳戶與指派權限

**適用於**

-  合作夥伴中心

為需要合作夥伴中心存取的員工建立帳戶。 這些工作必須由具有「使用者管理系統管理員」權限的系統管理員完成。 

## <a name="add-a-new-user"></a>新增使用者

1. 在 **\[儀表板\]** 功能表中，選取 **\[帳戶設定\] > \[使用者管理\]**。

2.  選取 **\[新增使用者\]**。

3.  輸入使用者的全名和唯一電子郵件地址。

4.  選取代理人類型及系統管理員類型。 合作夥伴中心存取權是以角色為基礎，讓您可以指派權限，自訂使用者檢視，只顯示使用者完成特定工作所需的功能。 如需各角色可以採取什麼動作的詳細資訊，請參閱[指派使用者權限](#assignuserpermissions)。

5.  選取 **\[新增\]** 建立使用者帳戶。 在下一頁，確認使用者的詳細資料。

>**重要**<br>
記下此頁面上顯示的新使用者登入資訊。 請務必將這項資訊複製及傳送給新的使用者，因為稍後您將無法再次存取。 <br>

>使用者必須使用其使用者名稱和暫時密碼登入合作夥伴中心。 當使用者第一次登入合作夥伴中心時，系統會提示他們變更密碼。    


### <a href="" id="assignuserpermissions"></a>指派使用者權限

合作夥伴中心存取權是以角色為基礎，讓您可以指派權限，自訂使用者檢視，只顯示使用者完成特定工作所需的功能。 

對於每個使用者，您都必須選取兩個權限等級：

-   代理人權限控制使用者可以查看並變更的客戶資料和帳戶資訊類型。

-   系統管理員權限控制使用者必須擁有的合作夥伴中心功能存取層級。 此設定會影響合作夥伴中心外部的項目 -- 帳單系統管理員可以存取所有 Microsoft 服務 (甚至與 CSP 無關之服務) 的帳單，而全域系統管理員可以存 CSP 範圍以外的使用者帳戶與客戶帳戶。

>**重要** 預設設定應一律是 **\[無系統管理員權限\]**，除非使用者的職務需要其他存取權以完成工作並支援客戶。

下表解釋在合作夥伴中心各角色可以採取什麼動作。

<table>
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>合作夥伴中心內的角色</strong></p></td>
<td><p><strong>可執行</strong></p></td>
<td><p><strong>不可執行</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>系統管理代理人</strong></p></td>
<td><ul>
<li><p>客戶管理</p></li>
<li><p>將裝置清單新增至合作夥伴中心</p></li>
<p><li>建立設定檔並將其套用至裝置</p></li>
<li><p>訂用帳戶管理</p></li>
<li><p>客戶的服務健康狀況和服務要求</p></li>
<li><p>要求委派的系統管理員權限</p></li>
<li><p>檢視價格和優惠</p></li>
<li><p>帳單</p></li>
<li><p>代表客戶管理</p></li>
<li><p>註冊加值型經銷商</p></li>
</ul></td>
<td><ul>
<li><p>使用者管理</p></li>
<li><p>合作夥伴中心服務要求</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>銷售代理人</strong></p></td>
<td><ul>
<li><p>客戶管理</p></li>
<li><p>將裝置清單新增至合作夥伴中心</p></li>
<li><p>訂用帳戶管理</p></li>
<li><p>檢視支援票證</p></li>
<li><p>要求與客戶建立關係</p></li>
<li><p>管理潛在客戶</p></li>
<li><p>檢視客戶合約</p></li>
<li><p>註冊加值型經銷商</p></li>
</ul></td>
<td><ul>
<li><p>針對合作夥伴中心問題，建立服務要求</p></li>
<li><p>解決支援票證問題</p></li>
<li><p>檢視服務健康狀況</p></li>
<li><p>檢視價格和優惠</p></li>
<li><p>帳單</p></li>
<li><p>代表客戶管理</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><strong>技術服務代理人</strong></p></td>
<td><ul>
<li><p>搜尋並檢視客戶</p></li>
<li><p>編輯客戶詳細資料</p></li>
<li><p>服務健康狀況</p></li>
<li><p>代表客戶要求支援 (注意：您必須是系統管理代理人，才能完成 Office 365 訂閱的這項工作)</p></li>
<li><p>代表客戶管理訂閱及服務 (注意：您必須是系統管理代理人，才能完成 Office 365 訂閱的這項工作)</p></li>
</ul></td>
<td><ul>
<li><p>檢視合作夥伴設定檔</p></li>
<li><p>建立新客戶帳戶</p></li>
<li><p>編輯客戶帳單資訊</p></li>
<li><p>管理訂閱</p></li>
<li><p>要求與客戶建立關係</p></li>
<li><p>管理潛在客戶</p></li>
<li><p>檢視價格和優惠</p></li>
<li><p>檢視客戶合約</p></li>
<li><p>帳單</p></li>
<li><p>註冊加值型經銷商</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>全域系統管理員</strong></p></td>
<td><ul>
<li><p>具有能存取所有 Microsoft 帳戶/服務的完整權限</p></li>
<li><p>建立合作夥伴中心的支援票證</p></li>
<li><p>檢視合約、價格清單和優惠</p></li>
<li><p>帳單</p></li>
<li><p>檢視、建立和管理合作夥伴使用者</p></li>
</ul></td>
<td></td>
</tr>
<tr class="even">
<td><p><strong>帳單管理</strong></p></td>
<td><ul>
<li><p>具有能存取所有 Microsoft 帳單的完整權限</p></li>
<li><p>檢視合約、價格清單和優惠</p></li>
<li><p>帳單</p></li>
</ul></td>
<td></td>
</tr>
<tr class="odd">
<td><p><strong>使用者管理系統管理員</strong></p></td>
<td><ul>
<li><p>檢視、建立和管理使用者</p></li>
<li><p>檢視所有合作夥伴設定檔</p></li>
</ul></td>
<td></td>
</tr>
</tbody>
</table>

 

 

 



