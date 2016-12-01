---
title: "建立使用者帳戶與設定權限 | 合作夥伴中心"
description: "系統管理員能為每個需要存取合作夥伴中心的合作夥伴員工建立使用者帳戶。"
ms.assetid: 75D805AE-9922-4CFD-9427-196047D70963
author: MaggiePucciEvans
translationtype: Human Translation
ms.sourcegitcommit: 14ba85c868e59dd1c77063f5b1b0e9ab8db7f82f
ms.openlocfilehash: 19faea7877a7501b8761b58e084e33f77cf95752

---

# 建立使用者帳戶與設定權限


系統管理員能為每個需要存取合作夥伴中心的合作夥伴員工建立使用者帳戶。 這些工作必須由具有「全域系統管理員」或「使用者管理系統管理員」權限的系統管理員完成。 在 \[帳戶設定\]&gt; \[使用者管理\] 中，您可以新增帳戶並設定或更新權限。

**新增使用者**

1.  在合作夥伴中心，移至 \[儀表板\] 功能表 &gt; \[帳戶設定\]&gt; \[使用者管理\]。
2.  選擇 \[新增使用者\]。

3.  輸入使用者的全名，並為他們建立唯一的電子郵件地址。

4.  選取代理人類型及系統管理員類型。 合作夥伴中心具有以角色為基礎的 UI，所以您在此步驟選取的項目會自訂使用者檢視，只顯示所需的功能。 如需各角色可以採取什麼動作的詳細資訊，請參閱[設定使用者權限](#setuserpermissions)。

5.  新增使用者。 您將看見包含用於全新登入之臨時密碼的確認畫面。 您必須複製此密碼，並將它傳送給新的使用者 – 離開此畫面之後將無法存取它。 在使用者第一次登入時，系統會提示他們更新其密碼。

### <a href="" id="setuserpermissions"></a>設定使用者權限

合作夥伴中心具有以角色為基礎的 UI，這表示您可以自訂使用者檢視，只顯示使用者之職務所需的功能。 對於每個使用者，您都必須選取兩個設定：

-   [代理人] 設定會控制使用者可看見的客戶資料和 Microsoft 資訊類型。

-   [系統管理員] 設定會決定使用者對合作夥伴中心環境，以及對所有其他的 Microsoft 服務 (帳戶、設定檔和支援票證) 擁有多少控制權。 此設定會影響合作夥伴中心外部的項目 -- 「帳單系統管理員」可以存取所有 Microsoft 服務 (甚至與雲端解決方案提供者無關之服務) 的所有帳單，而「全域系統管理員」可以存取雲端解決方案提供者範圍以外的使用者帳戶與客戶帳戶。

    預設設定應一律是 [無系統管理員權限]，除非使用者確實需要其他存取權以執行其工作。

下表說明合作夥伴中心內各角色可執行的整組活動。

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
<li><p>訂用帳戶管理</p></li>
<li><p>客戶的服務健康狀況和 服務要求</p></li>
<li><p>要求委派的系統管理員權限</p></li>
<li><p>檢視價格和優惠</p></li>
<li><p>帳單</p></li>
<li><p>系統管理，代表</p></li>
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
<li><p>訂用帳戶管理</p></li>
<li><p>檢視支援票證</p></li>
<li><p>要求建立關係</p></li>
<li><p>管理潛在客戶</p></li>
<li><p>檢視客戶合約</p></li>
<li><p>註冊加值型經銷商</p></li>
</ul></td>
<td><ul>
<li><p>建立服務或合作夥伴中心的支援票證</p></li>
<li><p>解決支援票證問題</p></li>
<li><p>檢視服務健康狀況</p></li>
<li><p>檢視價格和優惠</p></li>
<li><p>帳單</p></li>
<li><p>系統管理，代表</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><strong>技術服務代理人</strong></p></td>
<td><ul>
<li><p>搜尋並檢視客戶</p></li>
<li><p>編輯客戶詳細資料</p></li>
<li><p>服務健康狀況與服務要求</p></li>
<li><p>系統管理，代表</p></li>
</ul></td>
<td><ul>
<li><p>檢視合作夥伴設定檔</p></li>
<li><p>建立新客戶清單</p></li>
<li><p>編輯客戶帳單資訊</p></li>
<li><p>訂用帳戶管理</p></li>
<li><p>要求建立關係</p></li>
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

 

 

 






<!--HONumber=Nov16_HO4-->


