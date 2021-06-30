---
title: SaaS 应用用户指南
author: LGerrard
ms.author: legerrar
description: 适用于应用合规性Microsoft 365 SaaS 的 ISV 用户指南
keywords: 适用于应用合规性Microsoft 365 SaaS 的 ISV 用户指南
ms.topic: conceptual
ms.service: attestation
ms.openlocfilehash: b3b8c37a1babf2f941f5764fddd30523319d9a34
ms.sourcegitcommit: f6f3551bf1c00013efb6313ca3dc280de697137d
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 06/29/2021
ms.locfileid: "53202750"
---
# <a name="partners-user-guide-for-microsoft-365-app-compliance-program---saas"></a><span data-ttu-id="a37b2-104">适用于应用合规性计划Microsoft 365合作伙伴的用户指南 - SaaS</span><span class="sxs-lookup"><span data-stu-id="a37b2-104">Partner's User Guide for Microsoft 365 App Compliance Program - SaaS</span></span>

|<span data-ttu-id="a37b2-105">阶段</span><span class="sxs-lookup"><span data-stu-id="a37b2-105">Phase</span></span>|<span data-ttu-id="a37b2-106">Title</span><span class="sxs-lookup"><span data-stu-id="a37b2-106">Title</span></span>|
|---|---|
|<span data-ttu-id="a37b2-107">阶段 1</span><span class="sxs-lookup"><span data-stu-id="a37b2-107">Phase 1</span></span>| <span data-ttu-id="a37b2-108">发布者证明</span><span class="sxs-lookup"><span data-stu-id="a37b2-108">Publisher Attestation</span></span>|
|<span data-ttu-id="a37b2-109">阶段 2</span><span class="sxs-lookup"><span data-stu-id="a37b2-109">Phase 2</span></span>| <span data-ttu-id="a37b2-110">Microsoft 365 认证</span><span class="sxs-lookup"><span data-stu-id="a37b2-110">Microsoft 365 Certification</span></span>|

## <a name="1-overview"></a><span data-ttu-id="a37b2-111">1. 概述</span><span class="sxs-lookup"><span data-stu-id="a37b2-111">1. Overview</span></span> 

<span data-ttu-id="a37b2-112">本文档是我们的合作伙伴的分步用户指南，已注册 Microsoft 365 应用合规性计划，旨在通过合作伙伴中心门户为 SaaS 应用进行 Publisher 证明和认证。</span><span class="sxs-lookup"><span data-stu-id="a37b2-112">This document acts as a step-by-step user guide for our partners, enrolled for Microsoft 365 App Compliance program aiming to undergo Publisher Attestation and Certification for their SaaS apps, though the Partner Center portal.</span></span>

## <a name="2-acronyms--definitions"></a><span data-ttu-id="a37b2-113">2. 首字母缩略&定义</span><span class="sxs-lookup"><span data-stu-id="a37b2-113">2. Acronyms & Definitions</span></span>
|<span data-ttu-id="a37b2-114">首字母缩略词</span><span class="sxs-lookup"><span data-stu-id="a37b2-114">Acronym</span></span> | <span data-ttu-id="a37b2-115">定义</span><span class="sxs-lookup"><span data-stu-id="a37b2-115">Definition</span></span> |
|----|----|
|[<span data-ttu-id="a37b2-116">电脑 (合作伙伴中心) </span><span class="sxs-lookup"><span data-stu-id="a37b2-116">PC (Partner Center)</span></span>](https://partner.microsoft.com/)|<span data-ttu-id="a37b2-117">所有 Microsoft 合作伙伴的门户。</span><span class="sxs-lookup"><span data-stu-id="a37b2-117">A portal for all Microsoft partners.</span></span> <span data-ttu-id="a37b2-118">合作伙伴登录到合作伙伴中心并提交自我评估调查表。</span><span class="sxs-lookup"><span data-stu-id="a37b2-118">A partner logs in to Partner Center and submits self-assessment questionnaire.</span></span> <span data-ttu-id="a37b2-119">应用合规性[Microsoft 365中心](https://partner.microsoft.com/dashboard/home)</span><span class="sxs-lookup"><span data-stu-id="a37b2-119">Partner Center for [Microsoft 365 App Compliance](https://partner.microsoft.com/dashboard/home)</span></span>|
|<span data-ttu-id="a37b2-120">ISV</span><span class="sxs-lookup"><span data-stu-id="a37b2-120">ISV</span></span> | <span data-ttu-id="a37b2-121">独立软件供应商 a.k.a.</span><span class="sxs-lookup"><span data-stu-id="a37b2-121">Independent Software Vendor a.k.a.</span></span> <span data-ttu-id="a37b2-122">合作伙伴或开发人员</span><span class="sxs-lookup"><span data-stu-id="a37b2-122">Partner or Developer</span></span> |
|<span data-ttu-id="a37b2-123">应用源</span><span class="sxs-lookup"><span data-stu-id="a37b2-123">App Source</span></span> | <span data-ttu-id="a37b2-124">应用程序目录</span><span class="sxs-lookup"><span data-stu-id="a37b2-124">Catalog of apps</span></span> |
|<span data-ttu-id="a37b2-125">示例</span><span class="sxs-lookup"><span data-stu-id="a37b2-125">Example</span></span> |[<span data-ttu-id="a37b2-126">Now virtual agent</span><span class="sxs-lookup"><span data-stu-id="a37b2-126">Now virtual agent</span></span>](https://appsource.microsoft.com/product/office/WA104381816)|

## <a name="3-publisher-attestation-workflow"></a><span data-ttu-id="a37b2-127">3. Publisher证明工作流</span><span class="sxs-lookup"><span data-stu-id="a37b2-127">3. Publisher Attestation Workflow</span></span>

<span data-ttu-id="a37b2-128">**主页：** 这是合作伙伴登录到合作伙伴中心后登录页面。</span><span class="sxs-lookup"><span data-stu-id="a37b2-128">**Home Page**: This is the landing page once a partner logs in to Partner Center.</span></span>

![合作伙伴中心主屏幕](../media/Saas1.PNG)
  
<span data-ttu-id="a37b2-130">**步骤 1：** 在页面左侧的导航栏上：</span><span class="sxs-lookup"><span data-stu-id="a37b2-130">**Step 1** : On the left side of the page, on the navigation bar:</span></span>

- <span data-ttu-id="a37b2-131">选择商业市场</span><span class="sxs-lookup"><span data-stu-id="a37b2-131">Select Commercial Marketplace</span></span>
- <span data-ttu-id="a37b2-132">选择概述</span><span class="sxs-lookup"><span data-stu-id="a37b2-132">Select Overview</span></span>

![合作伙伴中心中的商业市场](../media/Saas2.PNG)
  
<span data-ttu-id="a37b2-134">选择"概述"后，合作伙伴可以看到可用于启动合规性计划Microsoft 365列表。</span><span class="sxs-lookup"><span data-stu-id="a37b2-134">Upon selecting ‘Overview’, partner can see list of apps available to start the Microsoft 365 Compliance program.</span></span>
  
<span data-ttu-id="a37b2-135">**步骤 2：** 从列表中选择应用以开始Publisher证明过程。</span><span class="sxs-lookup"><span data-stu-id="a37b2-135">**Step 2**: Select an app from the list to begin the Publisher Attestation process.</span></span>

![在商业市场中选择应用](../media/Saas3.PNG)

<span data-ttu-id="a37b2-137">选择应用时，会弹出另一个导航栏，并添加选项"应用合规性"。</span><span class="sxs-lookup"><span data-stu-id="a37b2-137">On selecting an app, another navigation bar will pop up with option ‘App Compliance’.</span></span>
  
<span data-ttu-id="a37b2-138">**步骤 3：** 选择"应用合规性"</span><span class="sxs-lookup"><span data-stu-id="a37b2-138">**Step 3**: Select 'App Compliance’</span></span>
  
![商业市场中的应用合规性](../media/Saas4.PNG)
  
<span data-ttu-id="a37b2-140">**步骤 4：** 填写个人证明的自我Publisher调查表。</span><span class="sxs-lookup"><span data-stu-id="a37b2-140">**Step 4**: Fill out the self-assessment questionnaire for Publisher Attestation.</span></span>

![完整Publisher证明](../media/UserGuidePhotos/5.5.png)
  
<span data-ttu-id="a37b2-142">**注意 如果你要返回以更新/重新提交应用程序，请单击"选择产品"下拉列表，选择应用并单击"克隆"。**</span><span class="sxs-lookup"><span data-stu-id="a37b2-142">**NOTE If you are coming back to update/re-submit your application, click dropdown for ‘Choose the product’, select the app and click ‘Clone’.**</span></span>

![克隆功能](../media/UserGuidePhotos/05.png)

<span data-ttu-id="a37b2-144">**您还可以利用表单导入/导出以脱机方式完成表单，并完成导入。**</span><span class="sxs-lookup"><span data-stu-id="a37b2-144">**You can also leverage the Import/Export feature to complete the form offline and import it once completed.**</span></span>

![导入导出功能](../media/UserGuidePhotos/06.png)
 
<span data-ttu-id="a37b2-146">**步骤 5：** 完成后，单击"提交"，评估现在将为"正在审查"。</span><span class="sxs-lookup"><span data-stu-id="a37b2-146">**Step 5**: Once completed, click on ‘Submit’, the assessment will now be ‘Under Review’.</span></span>
 
 <span data-ttu-id="a37b2-147">![提交Publisher确认 ](../media/UserGuidePhotos/07.png) ![ 提交](../media/UserGuidePhotos/08.png)</span><span class="sxs-lookup"><span data-stu-id="a37b2-147">![Submit Publisher Attesation](../media/UserGuidePhotos/07.png) ![Confirmation of submission](../media/UserGuidePhotos/08.png)</span></span>
  
<span data-ttu-id="a37b2-148">**批准/拒绝方案：**</span><span class="sxs-lookup"><span data-stu-id="a37b2-148">**Approve/Reject Scenarios:**</span></span>
  
<span data-ttu-id="a37b2-149">A.</span><span class="sxs-lookup"><span data-stu-id="a37b2-149">A.</span></span> <span data-ttu-id="a37b2-150">Publisher证明拒绝</span><span class="sxs-lookup"><span data-stu-id="a37b2-150">Publisher Attestation Rejection</span></span>
- <span data-ttu-id="a37b2-151">如果拒绝，合作伙伴可以：</span><span class="sxs-lookup"><span data-stu-id="a37b2-151">In case of rejection, a partner can:</span></span>
     - <span data-ttu-id="a37b2-152">查看故障报告</span><span class="sxs-lookup"><span data-stu-id="a37b2-152">View failure report</span></span>
          - <span data-ttu-id="a37b2-153">合作伙伴将通过电子邮件收到通知，他们可以查看合作伙伴中心中的故障报告</span><span class="sxs-lookup"><span data-stu-id="a37b2-153">Partner will be notified via email, and they can view the failure report in Partner Center</span></span>
     - <span data-ttu-id="a37b2-154">更新和重新提交自我评估调查表。</span><span class="sxs-lookup"><span data-stu-id="a37b2-154">Update and re-submit self-assessment questionnaire.</span></span>
        
![Publisher已拒绝证明](../media/UserGuidePhotos/09.png)

<span data-ttu-id="a37b2-156">B.</span><span class="sxs-lookup"><span data-stu-id="a37b2-156">B.</span></span>  <span data-ttu-id="a37b2-157">Publisher证明审批</span><span class="sxs-lookup"><span data-stu-id="a37b2-157">Publisher Attestation Approval</span></span>
- <span data-ttu-id="a37b2-158">经批准后，合作伙伴可以：</span><span class="sxs-lookup"><span data-stu-id="a37b2-158">Upon approval, the partner can:</span></span>
     - <span data-ttu-id="a37b2-159">更新并重新提交证明</span><span class="sxs-lookup"><span data-stu-id="a37b2-159">Update and resubmit attestation</span></span>
     - <span data-ttu-id="a37b2-160">查看已完成Publisher证明</span><span class="sxs-lookup"><span data-stu-id="a37b2-160">View completed Publisher Attestation</span></span>
     - <span data-ttu-id="a37b2-161">开始Microsoft 365认证过程</span><span class="sxs-lookup"><span data-stu-id="a37b2-161">Start the Microsoft 365 Certification process</span></span>
        
 ![Publisher证明已完成](../media/UserGuidePhotos/10.png)       
  
 ![开始Microsoft 365认证](../media/UserGuidePhotos/11.png)
  
<span data-ttu-id="a37b2-164">**发布Publisher证明审批：适用于发布者证明应用的 AppSource 中的链接示例。**</span><span class="sxs-lookup"><span data-stu-id="a37b2-164">**Post Publisher Attestation Approval: Example of link in AppSource for publisher attested apps.**</span></span>
  
![批准的联系人示例](../media/UserGuidePhotos/12.png)
   
## <a name="4---microsoft-365-certification-workflow"></a><span data-ttu-id="a37b2-166">4. Microsoft 365认证工作流</span><span class="sxs-lookup"><span data-stu-id="a37b2-166">4.   Microsoft 365 Certification Workflow</span></span>
  
<span data-ttu-id="a37b2-167">合作伙伴可以通过选中复选框并单击"提交"开始认证过程</span><span class="sxs-lookup"><span data-stu-id="a37b2-167">A partner can begin the Certification process by selecting the checkbox and clicking ‘Submit’</span></span>
  
![开始Microsoft 365认证](../media/UserGuidePhotos/13.png) 
  
<span data-ttu-id="a37b2-169">**步骤 1：** 初始文档提交</span><span class="sxs-lookup"><span data-stu-id="a37b2-169">**Step 1** : Initial Document Submission</span></span>

<span data-ttu-id="a37b2-170">填写所有详细信息，上传相关文档，然后单击"提交"</span><span class="sxs-lookup"><span data-stu-id="a37b2-170">Fill out all the details, upload relevant documents and click ‘Submit’</span></span>
  
<span data-ttu-id="a37b2-171">![初始文档提交 ](../media/UserGuidePhotos/14.png) 
 ![ 提交初始文档提交](../media/UserGuidePhotos/15.png)</span><span class="sxs-lookup"><span data-stu-id="a37b2-171">![Initial Document Submission](../media/UserGuidePhotos/14.png) 
![Submit Initial Document Submission](../media/UserGuidePhotos/15.png)</span></span>
  
<span data-ttu-id="a37b2-172">单击提交后，将审核初始文档提交。</span><span class="sxs-lookup"><span data-stu-id="a37b2-172">On clicking submit, the initial document submission will be under review.</span></span>

![正在审阅的初始文档提交](../media/UserGuidePhotos/16.png)
  
<span data-ttu-id="a37b2-174">分析员请求修订，以防初始文档不足或相关。</span><span class="sxs-lookup"><span data-stu-id="a37b2-174">An analyst requests a revision in case the initial documents are not sufficient or relevant.</span></span> <span data-ttu-id="a37b2-175">分析师将与合作伙伴合作，帮助获取正确的文档进行审批。</span><span class="sxs-lookup"><span data-stu-id="a37b2-175">The analyst will work with the partner to help get the right documents for approval.</span></span>

![所需的更新](../media/UserGuidePhotos/17.png)

<span data-ttu-id="a37b2-177">分析员批准初始文档提交后，合作伙伴需要提交控制要求。</span><span class="sxs-lookup"><span data-stu-id="a37b2-177">Once the analyst approves the initial document submission, the partner needs to submit the control requirements.</span></span>
  
<span data-ttu-id="a37b2-178">**步骤 2：** 控制要求提交</span><span class="sxs-lookup"><span data-stu-id="a37b2-178">**Step 2**: Control Requirement Submission</span></span>
  
<span data-ttu-id="a37b2-179">填写所有详细信息、上传相关文档并单击"提交"</span><span class="sxs-lookup"><span data-stu-id="a37b2-179">Fill out all the details, upload relevant documents and Click ‘Submit’</span></span>

![完全控制要求](../media/UserGuidePhotos/18.png)
  
![Upload控制要求](../media/UserGuidePhotos/19.png)

![满足控制要求](../media/UserGuidePhotos/20.png)
 
<span data-ttu-id="a37b2-183">单击"提交"后，将审核初始文档提交。</span><span class="sxs-lookup"><span data-stu-id="a37b2-183">On clicking Submit, the initial document submission will be under review.</span></span>

![正在审查的提交](../media/UserGuidePhotos/21.png)
  
<span data-ttu-id="a37b2-185">分析员请求修订，以防控制要求文档不足或相关。</span><span class="sxs-lookup"><span data-stu-id="a37b2-185">An analyst requests a revision in case the control requirement documents are not sufficient or relevant.</span></span> <span data-ttu-id="a37b2-186">分析师将与合作伙伴合作，帮助获取正确的文档进行审批。</span><span class="sxs-lookup"><span data-stu-id="a37b2-186">The analyst will work with the partner to help get the right documents for approval.</span></span>

![需要更新证据](../media/UserGuidePhotos/22.png)

![需要更新哪些控件](../media/UserGuidePhotos/23.png)
  
![正在审阅](../media/UserGuidePhotos/24.png) 
 
<span data-ttu-id="a37b2-190">如果提交不符合审批标准，分析员将拒绝提交。</span><span class="sxs-lookup"><span data-stu-id="a37b2-190">In case the submission does not satisfy the approval standards, the analyst will reject the submission.</span></span>
  
<span data-ttu-id="a37b2-191">合作伙伴可以与分析师合作，以提供相关信息和文档。</span><span class="sxs-lookup"><span data-stu-id="a37b2-191">The partner can work with the analyst to provide the relevant information and documents.</span></span>

![已拒绝认证](../media/UserGuidePhotos/25.png)
  
<span data-ttu-id="a37b2-193">满足所有安全标准后，分析员将批准提交，并且合作伙伴Microsoft 365认证。</span><span class="sxs-lookup"><span data-stu-id="a37b2-193">Once all the security standards have been met, the analyst will approve the submission and the partner will be Microsoft 365 Certified.</span></span>

![Microsoft 365应用认证已批准](../media/UserGuidePhotos/26.png)
  
<span data-ttu-id="a37b2-195">**认证审批后：AppSource Microsoft 365认证徽章的示例。**</span><span class="sxs-lookup"><span data-stu-id="a37b2-195">**Post Certification Approval: Example of Microsoft 365 certification badge in AppSource.**</span></span> 

![认证审批后](../media/UserGuidePhotos/27.png)
 
## <a name="5---microsoft-365-renewal-workflow"></a><span data-ttu-id="a37b2-197">5. Microsoft 365续订工作流：</span><span class="sxs-lookup"><span data-stu-id="a37b2-197">5.   Microsoft 365 Renewal Workflow:</span></span>
  
<span data-ttu-id="a37b2-198">**Microsoft 365Publisher证明和认证续订工作流：**</span><span class="sxs-lookup"><span data-stu-id="a37b2-198">**Microsoft 365 Publisher Attestation and Certification Renewal Workflow:**</span></span>  

<span data-ttu-id="a37b2-199">Microsoft 365应用合规性计划现在提供年度续订流程。</span><span class="sxs-lookup"><span data-stu-id="a37b2-199">Microsoft 365 App Compliance program now offers an annual renewal process.</span></span> <span data-ttu-id="a37b2-200">在此过程中，应用开发人员可以更新其现有Publisher证明调查表和认证Microsoft 365文档。</span><span class="sxs-lookup"><span data-stu-id="a37b2-200">During this process, app developers can update their existing Publisher Attestation questionnaire and documents required for Microsoft 365 Certification.</span></span> 
 
<span data-ttu-id="a37b2-201">**优点：**</span><span class="sxs-lookup"><span data-stu-id="a37b2-201">**Benefits:**</span></span> 

- <span data-ttu-id="a37b2-202">在 AppSource、Office 应用商店、Teams应用商店和各种管理门户中维护你的认证锁屏提醒，以将你的应用与其他门户区分。</span><span class="sxs-lookup"><span data-stu-id="a37b2-202">Maintain your certification badge in AppSource, the Office Store, the Teams Store and various admin portals to differentiate your app from others.</span></span> 
- <span data-ttu-id="a37b2-203">提高客户对使用认证应用的信心。</span><span class="sxs-lookup"><span data-stu-id="a37b2-203">Increase customer confidence in using your certified app.</span></span> 
- <span data-ttu-id="a37b2-204">使用更新的认证信息帮助 IT 管理员做出明智的决策。</span><span class="sxs-lookup"><span data-stu-id="a37b2-204">Help IT admins make informed decisions with updated certification information.</span></span>

<span data-ttu-id="a37b2-205">合作伙伴中心提供 [新的续订流程](https://partner.microsoft.com/dashboard/home) ，以提供无缝体验。</span><span class="sxs-lookup"><span data-stu-id="a37b2-205">The new renewal process is available in [Partner Center](https://partner.microsoft.com/dashboard/home) to provide a seamless experience.</span></span> <span data-ttu-id="a37b2-206">从到期日期前 90 天开始，将在合作伙伴中心中显示续订提醒。</span><span class="sxs-lookup"><span data-stu-id="a37b2-206">A renewal reminder will be shown in Partner Center starting 90 days before the expiration date.</span></span> <span data-ttu-id="a37b2-207">定期提醒也会在到期前的 90、60 和 30 天内通过电子邮件发送。</span><span class="sxs-lookup"><span data-stu-id="a37b2-207">Periodic reminders will also be sent via email at 90, 60 and 30 days before expiration.</span></span> 
 
<span data-ttu-id="a37b2-208">**阶段 1：Publisher证明续订：**</span><span class="sxs-lookup"><span data-stu-id="a37b2-208">**Phase 1: Publisher Attestation Renewal:**</span></span>
  
<span data-ttu-id="a37b2-209">应用Publisher证明答案将需要每年重新提交。</span><span class="sxs-lookup"><span data-stu-id="a37b2-209">The app’s Publisher Attestation answers will need to be resubmitted on an annual basis.</span></span> <span data-ttu-id="a37b2-210">当证明接近 1 年标志时，将发送电子邮件提醒，鼓励重新提交证明。</span><span class="sxs-lookup"><span data-stu-id="a37b2-210">When the attestation nears the 1-year mark, an email reminder will be sent encouraging a resubmission of the attestation.</span></span> 
 
<span data-ttu-id="a37b2-211">**步骤 1：** 选择 **续订** 以续订Publisher证明。</span><span class="sxs-lookup"><span data-stu-id="a37b2-211">**Step 1**: Select **Renew** to renew the Publisher Attestation.</span></span>
  
![Renewel approved](../media/UserGuidePhotos/31.png)
  
<span data-ttu-id="a37b2-213">**步骤 2：** 查看上一Publisher证明答案，并根据需要使用最新信息进行更新。</span><span class="sxs-lookup"><span data-stu-id="a37b2-213">**Step 2**: Review the previous Publisher Attestation answers and update with the latest information as needed.</span></span> 
  
<span data-ttu-id="a37b2-214">准备好Publisher提交证明进行续订。</span><span class="sxs-lookup"><span data-stu-id="a37b2-214">Submit Publisher Attestation for renewal when ready.</span></span> <span data-ttu-id="a37b2-215">M365 应用合规性分析师将审核此内容。</span><span class="sxs-lookup"><span data-stu-id="a37b2-215">It will be reviewed by an M365 App Compliance analyst.</span></span>

![续订到证明](../media/UserGuidePhotos/29.png)
  
<span data-ttu-id="a37b2-217">**Publisher证明续订已批准：**</span><span class="sxs-lookup"><span data-stu-id="a37b2-217">**Publisher Attestation Renewal Approved:**</span></span>
  
![提交以续订](../media/UserGuidePhotos/30.png)
  
<span data-ttu-id="a37b2-219">**Publisher证明已过期：**</span><span class="sxs-lookup"><span data-stu-id="a37b2-219">**Publisher Attestation Expired:**</span></span>
  
<span data-ttu-id="a37b2-220">需要在到期日期之前续订应用的信息，以维护 Microsoft 文档上的Publisher证明页面。及时续订还将确保在各种店面继续使用应用的标记和图标。</span><span class="sxs-lookup"><span data-stu-id="a37b2-220">The app’s information needs to be renewed before the expiration date to maintain the app’s Publisher Attestation page on the Microsoft docs. Timely renewal will also ensure continued badging and icons for the app in various storefronts.</span></span> 
 
![Renewel approved](../media/UserGuidePhotos/31.png)

<span data-ttu-id="a37b2-222">**注意**：一旦Publisher，可以随时通过单击"续订"启动证明续订过程。</span><span class="sxs-lookup"><span data-stu-id="a37b2-222">**Note**: Once expired, Publisher Attestation renewal process can be started anytime by clicking ‘Renew’.</span></span>
 
<span data-ttu-id="a37b2-223">**阶段 2：Microsoft 365认证续订**</span><span class="sxs-lookup"><span data-stu-id="a37b2-223">**Phase 2: Microsoft 365 Certification Renewal**</span></span>
  
<span data-ttu-id="a37b2-224">需要每年重新提交应用的认证信息。</span><span class="sxs-lookup"><span data-stu-id="a37b2-224">The app’s certification information needs to be resubmitted on an annual basis.</span></span> <span data-ttu-id="a37b2-225">这需要重新验证当前环境的作用域内控件。</span><span class="sxs-lookup"><span data-stu-id="a37b2-225">This will require revalidation of the in-scope controls of your current environment.</span></span> <span data-ttu-id="a37b2-226">当认证接近 1 年标记时，将发送电子邮件通知，鼓励重新提交文档和证据。</span><span class="sxs-lookup"><span data-stu-id="a37b2-226">When the Certification nears 1-year mark an email notification will be sent encouraging a resubmission of the documents and evidence.</span></span>
 
![证明续订](../media/UserGuidePhotos/32.png) 

<span data-ttu-id="a37b2-228">**认证续订批准/拒绝方案：**</span><span class="sxs-lookup"><span data-stu-id="a37b2-228">**Certification Renewal Approve/Reject Scenarios:**</span></span>

<span data-ttu-id="a37b2-229">**方案 1：**</span><span class="sxs-lookup"><span data-stu-id="a37b2-229">**Scenario 1:**</span></span> 

<span data-ttu-id="a37b2-230">证书续订已开始，正在审查中。</span><span class="sxs-lookup"><span data-stu-id="a37b2-230">Certification renewal has started and is under review.</span></span>
 
![认证续订](../media/UserGuidePhotos/33.png) 

<span data-ttu-id="a37b2-232">方案 1A：</span><span class="sxs-lookup"><span data-stu-id="a37b2-232">Scenario 1A:</span></span> 

<span data-ttu-id="a37b2-233">证书续订拒绝：</span><span class="sxs-lookup"><span data-stu-id="a37b2-233">Certification renewal rejection:</span></span> 
- <span data-ttu-id="a37b2-234">如果：</span><span class="sxs-lookup"><span data-stu-id="a37b2-234">Certification may be rejected if:</span></span> 
     - <span data-ttu-id="a37b2-235">应用没有所需的工具、进程或配置，并且将无法在认证窗口中实现所需的更改。</span><span class="sxs-lookup"><span data-stu-id="a37b2-235">The app does not have the required tooling, processes, or configurations in place and will not be able to implement required changes within the certification window.</span></span> 
     - <span data-ttu-id="a37b2-236">应用具有未解决的漏洞，无法在认证窗口中修复。</span><span class="sxs-lookup"><span data-stu-id="a37b2-236">The app has outstanding vulnerabilities in place and cannot be fixed within the certification window.</span></span> 
 
![认证拒绝](../media/UserGuidePhotos/34.png)

<span data-ttu-id="a37b2-238">方案 1B：</span><span class="sxs-lookup"><span data-stu-id="a37b2-238">Scenario 1B:</span></span> 

<span data-ttu-id="a37b2-239">认证续订已批准</span><span class="sxs-lookup"><span data-stu-id="a37b2-239">Certification renewal is approved</span></span>

![认证续订审批](../media/UserGuidePhotos/35.png)

<span data-ttu-id="a37b2-241">**认证过期：**</span><span class="sxs-lookup"><span data-stu-id="a37b2-241">**Certification Expiration:**</span></span>

<span data-ttu-id="a37b2-242">需要在到期日期之前续订应用信息，才能在 Microsoft 文档上维护应用的认证页面。及时续订还将确保在 AppSource 和团队应用商店中为应用持续提供标记和图标。</span><span class="sxs-lookup"><span data-stu-id="a37b2-242">The app’s information needs to be renewed before the expiration date to maintain app’s Certification page on the Microsoft docs. Timely renewal will also ensure continued badging and icons for the app in AppSource and Team Store.</span></span>

![认证续订审批](../media/UserGuidePhotos/36.png)
  
<span data-ttu-id="a37b2-244">注意：一旦Publisher，可以随时通过单击"续订"启动证明和认证过程。</span><span class="sxs-lookup"><span data-stu-id="a37b2-244">Note: Once expired, Publisher Attestation and Certification process can be started anytime by clicking ‘Renew’.</span></span> 
