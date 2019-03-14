---
title: 為客戶帳戶建立多位使用者 | 合作夥伴中心
ms.topic: article
ms.date: 10/29/2018
description: 您可以透過將資料檔案 (以逗號分隔值的檔案格式 (.csv)) 上傳至合作夥伴中心，來一次新增多位使用者至客戶帳戶。
ms.assetid: c6fca2c0-2e6c-41b1-9be8-b363b139f15b
author: MaggiePucciEvans
ms.author: evansma
keywords: 大量上傳, 新增多個使用者至客戶的帳戶, 新增客戶使用者, 大量上傳客戶使用者, 客戶帳戶, 客戶使用者, 使用者
ms.localizationpriority: medium
ms.openlocfilehash: 12bb42d4e1dcf5003ac8790be777c483f216fd6f
ms.sourcegitcommit: 4c34d6fcaf020bcc53eaa5f0379011a56149a14f
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 03/05/2019
ms.locfileid: "57584241"
---
# <a name="add-multiple-users-to-a-customer-account"></a><span data-ttu-id="e5a9b-104">將多個使用者新增到客戶帳戶</span><span class="sxs-lookup"><span data-stu-id="e5a9b-104">Add multiple users to a customer account</span></span>

<span data-ttu-id="e5a9b-105">**適用於**</span><span class="sxs-lookup"><span data-stu-id="e5a9b-105">**Applies to**</span></span>

-  <span data-ttu-id="e5a9b-106">合作夥伴中心</span><span class="sxs-lookup"><span data-stu-id="e5a9b-106">Partner Center</span></span>

<span data-ttu-id="e5a9b-107">您可以新增多個使用者至客戶的帳戶一次上傳到合作夥伴中心的資料檔案以逗點分隔值檔案格式 (.csv)。</span><span class="sxs-lookup"><span data-stu-id="e5a9b-107">You can add multiple users to a customer's account all at once, by uploading a data file in the comma-separated value file format (.csv) to the Partner Center.</span></span> <span data-ttu-id="e5a9b-108">您可以從合作夥伴中心下載範例資料檔案，並編輯它供您使用，或您可以建立新的資料檔案，請使用下面定義的資料模型。</span><span class="sxs-lookup"><span data-stu-id="e5a9b-108">You can download a sample data file from the Partner Center and then edit it for your use, or you can create a new data file using the data model defined below.</span></span>

## <a href="" id="creatingtheimportcsvfile"></a><span data-ttu-id="e5a9b-109">資料檔案的需求</span><span class="sxs-lookup"><span data-stu-id="e5a9b-109">Data file requirements</span></span>


<span data-ttu-id="e5a9b-110">若要使用大量上傳流程新增多位使用者至客戶帳戶，您需要符合以下需求：</span><span class="sxs-lookup"><span data-stu-id="e5a9b-110">To add multiple users to a customer’s account using the bulk upload process, you’ll need to meet the following requirements:</span></span>

-   <span data-ttu-id="e5a9b-111">您必須擁有對客戶帳戶的全域系統管理員權限；</span><span class="sxs-lookup"><span data-stu-id="e5a9b-111">You must have global administrator permissions to the customer account;</span></span>
-   <span data-ttu-id="e5a9b-112">每位使用者都必須有唯一的電子郵件地址，並已附加到客戶的電子郵件網域；</span><span class="sxs-lookup"><span data-stu-id="e5a9b-112">Each user must have a unique email address, appended to the customer's email domain(s);</span></span>
-   <span data-ttu-id="e5a9b-113">您一次最多可以上傳 100 筆記錄。</span><span class="sxs-lookup"><span data-stu-id="e5a9b-113">You can upload up to 100 records at a time.</span></span> <span data-ttu-id="e5a9b-114">如果您需要新增超過 100 位使用者，請建立並上傳其他資料檔案。</span><span class="sxs-lookup"><span data-stu-id="e5a9b-114">If you need to add more than 100 users, create and upload additional data files.</span></span>
-   <span data-ttu-id="e5a9b-115">所有使用者都必須位於相同地理 **\[位置\]**。</span><span class="sxs-lookup"><span data-stu-id="e5a9b-115">All users must be in the same geographic **Location**.</span></span>
-   <span data-ttu-id="e5a9b-116">請只輸入下面描述的資料。</span><span class="sxs-lookup"><span data-stu-id="e5a9b-116">Enter only the data described below.</span></span> <span data-ttu-id="e5a9b-117">沒有直接關聯的資料將會導致上傳失敗。</span><span class="sxs-lookup"><span data-stu-id="e5a9b-117">Extraneous data will cause the upload to fail.</span></span>

<span data-ttu-id="e5a9b-118">請在資料檔案中輸入以下資料：</span><span class="sxs-lookup"><span data-stu-id="e5a9b-118">Enter the following data in the data file:</span></span>

|                 |                                                                              |                                            |
|-----------------|------------------------------------------------------------------------------|--------------------------------------------|
| <span data-ttu-id="e5a9b-119">**資料行名稱**</span><span class="sxs-lookup"><span data-stu-id="e5a9b-119">**Column name**</span></span> | <span data-ttu-id="e5a9b-120">**描述**</span><span class="sxs-lookup"><span data-stu-id="e5a9b-120">**Description**</span></span>                                                              | <span data-ttu-id="e5a9b-121">**限制**</span><span class="sxs-lookup"><span data-stu-id="e5a9b-121">**Limitation**</span></span>                             |
| <span data-ttu-id="e5a9b-122">名字</span><span class="sxs-lookup"><span data-stu-id="e5a9b-122">First name</span></span>      | <span data-ttu-id="e5a9b-123">使用者的名字 (選擇性欄位)</span><span class="sxs-lookup"><span data-stu-id="e5a9b-123">User’s first name (optional field)</span></span>                                           | <span data-ttu-id="e5a9b-124">50 個字元限制</span><span class="sxs-lookup"><span data-stu-id="e5a9b-124">50-character limit</span></span>                         |
| <span data-ttu-id="e5a9b-125">姓氏</span><span class="sxs-lookup"><span data-stu-id="e5a9b-125">Last name</span></span>       | <span data-ttu-id="e5a9b-126">使用者的姓氏 (選擇性欄位)</span><span class="sxs-lookup"><span data-stu-id="e5a9b-126">User's last name (optional field)</span></span>                                            | <span data-ttu-id="e5a9b-127">50 個字元限制</span><span class="sxs-lookup"><span data-stu-id="e5a9b-127">50-character limit</span></span>                         |
| <span data-ttu-id="e5a9b-128">顯示名稱</span><span class="sxs-lookup"><span data-stu-id="e5a9b-128">Display name</span></span>    | <span data-ttu-id="e5a9b-129">在合作夥伴中心 （必填欄位） 中顯示名稱</span><span class="sxs-lookup"><span data-stu-id="e5a9b-129">Name displayed in the Partner Center (required field)</span></span>                            | <span data-ttu-id="e5a9b-130">50 個字元限制</span><span class="sxs-lookup"><span data-stu-id="e5a9b-130">50-character limit</span></span>                         |
| <span data-ttu-id="e5a9b-131">電子郵件</span><span class="sxs-lookup"><span data-stu-id="e5a9b-131">Email</span></span>           | <span data-ttu-id="e5a9b-132">使用者在客戶公司的公司電子郵件地址 (必要欄位)</span><span class="sxs-lookup"><span data-stu-id="e5a9b-132">User’s business email address at customer company (required field)</span></span>           | <span data-ttu-id="e5a9b-133">每位使用者都必須有唯一電子郵件地址</span><span class="sxs-lookup"><span data-stu-id="e5a9b-133">Each user must have a unique email address</span></span> |
| <span data-ttu-id="e5a9b-134">狀態更新</span><span class="sxs-lookup"><span data-stu-id="e5a9b-134">Status update</span></span>   | <span data-ttu-id="e5a9b-135">用來指示是否已經成功建立新的使用者記錄</span><span class="sxs-lookup"><span data-stu-id="e5a9b-135">Used to indicate whether or not the new user record was successfully created</span></span> | <span data-ttu-id="e5a9b-136">\*\*將保留空白\*\*</span><span class="sxs-lookup"><span data-stu-id="e5a9b-136">\*\*Leave empty\*\*</span></span>                        |

 

### <a href="" id="createmultipleuseraccounts"></a><span data-ttu-id="e5a9b-137">若要建立多個使用者帳戶</span><span class="sxs-lookup"><span data-stu-id="e5a9b-137">To create multiple user accounts</span></span>

<a href="" id="creatingtheaccounts"></a>
1.  <span data-ttu-id="e5a9b-138">建立包含上述資料的逗號分隔值 (.csv) 資料檔案。</span><span class="sxs-lookup"><span data-stu-id="e5a9b-138">Create a comma-separated value (.csv) data file with the data described above.</span></span> <span data-ttu-id="e5a9b-139">儲存檔案以便您在之後的步驟中瀏覽該檔案。</span><span class="sxs-lookup"><span data-stu-id="e5a9b-139">Save the file so you can browse to it in a later step.</span></span>
2.  <span data-ttu-id="e5a9b-140">從**合作夥伴中心**功能表上，選取**客戶**，然後從清單中選擇客戶。</span><span class="sxs-lookup"><span data-stu-id="e5a9b-140">From the **Partner Center** menu, select **Customers**, then choose a customer from the list.</span></span>
3.  <span data-ttu-id="e5a9b-141">選取 \[上傳使用者\]。</span><span class="sxs-lookup"><span data-stu-id="e5a9b-141">Select **Upload users**.</span></span>
4.  <span data-ttu-id="e5a9b-142">在 \[上傳使用者資訊\] 底下，選取 \[瀏覽\]。</span><span class="sxs-lookup"><span data-stu-id="e5a9b-142">Under **Upload user info**, select **Browse**.</span></span>
5.  <span data-ttu-id="e5a9b-143">在檔案選取器中，選取您的資料檔案，然後選取 **\[開啟\]**。</span><span class="sxs-lookup"><span data-stu-id="e5a9b-143">In the file selector, select your data file and then select **Open**.</span></span>
6.  <span data-ttu-id="e5a9b-144">選取 **\[驗證\]**。</span><span class="sxs-lookup"><span data-stu-id="e5a9b-144">Select **Validate**.</span></span>

    <span data-ttu-id="e5a9b-145">**附註**  大多數的帳戶建立錯誤會因資料檔案的問題，包括遺漏資訊、 格式不正確或重複的電子郵件地址或檔案中的太多記錄。</span><span class="sxs-lookup"><span data-stu-id="e5a9b-145">**Note**  Most account creation errors are caused by data file issues, including missing information, malformed or duplicated email addresses, or too many records in the file.</span></span>

7.  <span data-ttu-id="e5a9b-146">合作夥伴中心驗證檔案之後，請選取地理**位置**為新的使用者。</span><span class="sxs-lookup"><span data-stu-id="e5a9b-146">After the Partner Center validates the file, select the geographic **Location** for the new users.</span></span>
8.  <span data-ttu-id="e5a9b-147">選取 \[儲存\]。</span><span class="sxs-lookup"><span data-stu-id="e5a9b-147">Select **Save**.</span></span>
9.  <span data-ttu-id="e5a9b-148">下載使用者的暫時密碼資訊。</span><span class="sxs-lookup"><span data-stu-id="e5a9b-148">Download the temporary password information for the users.</span></span>

<span data-ttu-id="e5a9b-149">**重要：** 請務必下載檔案的暫時密碼現在當您將無法執行此操作。</span><span class="sxs-lookup"><span data-stu-id="e5a9b-149">**IMPORTANT:** Be sure to download the file with the temporary passwords now as you won't be able to do this later.</span></span> <span data-ttu-id="e5a9b-150">新的使用者必須他們新帳戶的暫時密碼登入他們的新帳戶。</span><span class="sxs-lookup"><span data-stu-id="e5a9b-150">New users must log in to their new account using the temporary password for their new accounts.</span></span>

10. <span data-ttu-id="e5a9b-151">新的使用者會自動獲派 **\[可以使用授權與服務\]** 的權限。</span><span class="sxs-lookup"><span data-stu-id="e5a9b-151">New users are automatically assigned permissions of **Can use licenses and services** .</span></span> 

 

 



