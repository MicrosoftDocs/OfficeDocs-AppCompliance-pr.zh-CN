---
ms.author: oromalle
title: Microsoft 365 认证提交指南
author: orionomalley
description: Microsoft 365 认证提交指南粒度视图
keywords: 应用认证团队 Microsoft 365 安全合规性 m365
ms.topic: conceptual
ms.service: attestation
ms.openlocfilehash: 4d0f09b3a1dd6bde7022e93d08a491e2855d90a7
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/28/2021
ms.locfileid: "52070861"
---
# <a name="microsoft-365-certification-submission-guide"></a><span data-ttu-id="31cea-104">Microsoft 365 认证提交指南</span><span class="sxs-lookup"><span data-stu-id="31cea-104">Microsoft 365 Certification Submission Guide</span></span>

<span data-ttu-id="31cea-105">**本文内容：**</span><span class="sxs-lookup"><span data-stu-id="31cea-105">**In this article:**</span></span>
- [<span data-ttu-id="31cea-106">简介</span><span class="sxs-lookup"><span data-stu-id="31cea-106">Introduction</span></span>](#introduction)
- [<span data-ttu-id="31cea-107">先决条件</span><span class="sxs-lookup"><span data-stu-id="31cea-107">Prerequisites</span></span>](#prerequisites) 
- [<span data-ttu-id="31cea-108">Microsoft 365 认证规范更新</span><span class="sxs-lookup"><span data-stu-id="31cea-108">Microsoft 365 Certification Specification Updates</span></span>](#microsoft-365-certification-specification-updates)
- [<span data-ttu-id="31cea-109">认证范围</span><span class="sxs-lookup"><span data-stu-id="31cea-109">Certification Scope</span></span>](#certification-scope)
- [<span data-ttu-id="31cea-110">认证过程</span><span class="sxs-lookup"><span data-stu-id="31cea-110">Certification Process</span></span>](#certification-process)
- [<span data-ttu-id="31cea-111">合规性证据</span><span class="sxs-lookup"><span data-stu-id="31cea-111">Compliance Evidence</span></span>](#compliance-evidence) 
- [<span data-ttu-id="31cea-112">初始文档提交</span><span class="sxs-lookup"><span data-stu-id="31cea-112">Initial Document submission</span></span>](#initial-document-submission) 
- [<span data-ttu-id="31cea-113">证据收集和评估活动</span><span class="sxs-lookup"><span data-stu-id="31cea-113">Evidence Collection and Assessment Activities</span></span>](#evidence-collection-and-assessment-activities)
- [<span data-ttu-id="31cea-114">认证条件</span><span class="sxs-lookup"><span data-stu-id="31cea-114">Certification Criteria</span></span>](#app-certification-criteria)
- [<span data-ttu-id="31cea-115">Application Security</span><span class="sxs-lookup"><span data-stu-id="31cea-115">Application Security</span></span>](#application-security)
- [<span data-ttu-id="31cea-116">操作安全性</span><span class="sxs-lookup"><span data-stu-id="31cea-116">Operational Security</span></span>](#operational-security) 
- [<span data-ttu-id="31cea-117">数据处理安全和隐私</span><span class="sxs-lookup"><span data-stu-id="31cea-117">Data Handling Security and Privacy</span></span>](#data-handling-security-and-privacy)
- [<span data-ttu-id="31cea-118">可选的外部合规性框架审查</span><span class="sxs-lookup"><span data-stu-id="31cea-118">Optional External Compliance Frameworks Review</span></span>](#optional-external-compliance-frameworks-review)
- [<span data-ttu-id="31cea-119">附录 A</span><span class="sxs-lookup"><span data-stu-id="31cea-119">Appendix A</span></span>](#appendix-a)
- [<span data-ttu-id="31cea-120">附录 B</span><span class="sxs-lookup"><span data-stu-id="31cea-120">Appendix B</span></span>](#appendix-b) 
- [<span data-ttu-id="31cea-121">附录 C</span><span class="sxs-lookup"><span data-stu-id="31cea-121">Appendix C</span></span>](#appendix-c) 
- [<span data-ttu-id="31cea-122">附录 D</span><span class="sxs-lookup"><span data-stu-id="31cea-122">Appendix D</span></span>](#appendix-d) 
- [<span data-ttu-id="31cea-123">附录 E</span><span class="sxs-lookup"><span data-stu-id="31cea-123">Appendix E</span></span>](#appendix-e) 
- [<span data-ttu-id="31cea-124">附录 F</span><span class="sxs-lookup"><span data-stu-id="31cea-124">Appendix F</span></span>](#appendix-f) 
- [<span data-ttu-id="31cea-125">附录 G </span><span class="sxs-lookup"><span data-stu-id="31cea-125">Appendix G </span></span>](#appendix-g)
- [<span data-ttu-id="31cea-126">了解详细信息</span><span class="sxs-lookup"><span data-stu-id="31cea-126">Learn more</span></span>](#learn-more) 
- [<span data-ttu-id="31cea-127">术语表</span><span class="sxs-lookup"><span data-stu-id="31cea-127">Glossary</span></span>](#glossary) 


## <a name="introduction"></a><span data-ttu-id="31cea-128">简介</span><span class="sxs-lookup"><span data-stu-id="31cea-128">Introduction</span></span>

<span data-ttu-id="31cea-129">作为 Microsoft 365 应用合规性计划的一部分，Microsoft 365 认证向企业组织提供保证和信心，确保数据和隐私在将第三方开发人员应用/外接程序集成到 Microsoft 365 平台时受到充分保护和保护。</span><span class="sxs-lookup"><span data-stu-id="31cea-129">Part of the Microsoft 365 App Compliance program, the Microsoft 365 Certification offers assurance and confidence to enterprise organizations that data and privacy are adequately secured and protected when integrating third-party developer apps/add-ins into the Microsoft 365 platform.</span></span> <span data-ttu-id="31cea-130">通过验证的应用程序和加载项在整个 **Microsoft 365** 生态系统中将被指定为 Microsoft 365 认证。</span><span class="sxs-lookup"><span data-stu-id="31cea-130">Applications and add-ins that pass validation will be designated **Microsoft 365 Certified** throughout the Microsoft 365 ecosystem.</span></span> 

<span data-ttu-id="31cea-131">通过参与 Microsoft 365 认证计划，即表示你同意这些补充条款，并遵守适用于你参与 Microsoft Corporation ("、"Microsoft"、"we"、"us"或"our") 的 Microsoft 365 认证计划的任何随附文档。</span><span class="sxs-lookup"><span data-stu-id="31cea-131">By participating in the Microsoft 365 Certification  program, you are agreeing to these supplemental terms and to comply with any accompanying documentation that applies to your participation in the Microsoft 365 Certification program with Microsoft Corporation ("Microsoft", "we", "us",  or "our").</span></span> <span data-ttu-id="31cea-132">你表示并保证你有权代表自己、公司以及/或其他实体接受这些 Microsoft 365 认证补充条款（如果适用）。</span><span class="sxs-lookup"><span data-stu-id="31cea-132">You represent and warrant to us that you have the authority to accept these Microsoft 365 Certification supplemental terms on behalf of yourself, a company, and/or other entity, as applicable.</span></span> <span data-ttu-id="31cea-133">我们可能会随时更改、修订或终止这些补充条款。</span><span class="sxs-lookup"><span data-stu-id="31cea-133">We may change, amend or terminate these supplemental terms at any time.</span></span> <span data-ttu-id="31cea-134">你在任何更改或修正后继续参与 Microsoft 365 认证计划意味着你同意新的补充条款。</span><span class="sxs-lookup"><span data-stu-id="31cea-134">Your continued participation in the Microsoft 365 Certification program after any change or amendment means you agree to the new supplemental terms.</span></span> <span data-ttu-id="31cea-135">如果你不同意新的补充条款或我们终止这些补充条款，则必须停止参与 Microsoft 365 认证计划。</span><span class="sxs-lookup"><span data-stu-id="31cea-135">If you do not agree to the new supplemental terms or if we terminate these supplemental terms, you must stop participating in the Microsoft 365 Certification program.</span></span>

<span data-ttu-id="31cea-136">本文档面向 ISV (Independent Software Vendors) ，提供有关 Microsoft 365 认证过程、启动该过程的先决条件以及 ISV 必须拥有的特定安全控制的详细信息。</span><span class="sxs-lookup"><span data-stu-id="31cea-136">This document is aimed at ISVs (Independent Software Vendors) to provide information on the Microsoft 365 Certification process, prerequisites to starting the process and details of specific security controls that ISVs must have in place.</span></span>  <span data-ttu-id="31cea-137">Microsoft 365 应用合规性计划的常规信息位于 Microsoft 365 应用合规性计划页面 [下](https://docs.microsoft.com/microsoft-365-app-certification/overview)。</span><span class="sxs-lookup"><span data-stu-id="31cea-137">General information of the Microsoft 365 App Compliance program can be found under the Microsoft 365 App Compliance program [page](https://docs.microsoft.com/microsoft-365-app-certification/overview).</span></span> 

> [!IMPORTANT]
> <span data-ttu-id="31cea-138">目前，Microsoft 365 认证受到限制：</span><span class="sxs-lookup"><span data-stu-id="31cea-138">Currently, Microsoft 365 Certification is limited:</span></span>
>* <span data-ttu-id="31cea-139">Microsoft Teams 应用程序 (选项卡、聊天机器人等) 。</span><span class="sxs-lookup"><span data-stu-id="31cea-139">Microsoft Teams applications (Tabs, Bots, etc.) .</span></span>
>* <span data-ttu-id="31cea-140">Sharepoint 应用程序/外接程序</span><span class="sxs-lookup"><span data-stu-id="31cea-140">Sharepoint Apps/Add-ins</span></span>
>* <span data-ttu-id="31cea-141">Office 外接程序 (Word、Excel、PowerPoint、Outlook、Project、OneNote) </span><span class="sxs-lookup"><span data-stu-id="31cea-141">Office Add-ins (Word, Excel, PowerPoint, Outlook, Project, OneNote)</span></span>

## <a name="prerequisites"></a><span data-ttu-id="31cea-142">先决条件</span><span class="sxs-lookup"><span data-stu-id="31cea-142">Prerequisites</span></span>

### <a name="publisher-attestation"></a><span data-ttu-id="31cea-143">发布者证明</span><span class="sxs-lookup"><span data-stu-id="31cea-143">Publisher Attestation</span></span>

<span data-ttu-id="31cea-144">在被授予 Microsoft 365 认证过程之前，你必须已完成发布者证明。</span><span class="sxs-lookup"><span data-stu-id="31cea-144">Before being awarded the Microsoft 365 Certification process you must have completed Publisher Attestation.</span></span> <span data-ttu-id="31cea-145">但是，你可以先启动 Microsoft 365 认证过程，然后完成发布者证明。</span><span class="sxs-lookup"><span data-stu-id="31cea-145">However, you may start the Microsoft 365 Certification process prior to completing Publisher Attestation.</span></span>  

### <a name="read-the-microsoft-365-certification-specification"></a><span data-ttu-id="31cea-146">阅读 Microsoft 365 认证规范</span><span class="sxs-lookup"><span data-stu-id="31cea-146">Read the Microsoft 365 Certification Specification</span></span>

<span data-ttu-id="31cea-147">Microsoft 建议所有 ISV (独立软件供应商) 完整阅读此 Microsoft 365 认证规范，以确保范围内环境和应用/外接程序符合所有适用的控制措施。</span><span class="sxs-lookup"><span data-stu-id="31cea-147">Microsoft recommends all ISVs (Independent Software Vendor) to read this Microsoft 365 Certification Specification in its entirety to ensure all applicable controls are being met by the in-scope environment and the app/add-in.</span></span> <span data-ttu-id="31cea-148">这将有助于确保评估过程顺畅。</span><span class="sxs-lookup"><span data-stu-id="31cea-148">This will help ensure a smooth assessment process.</span></span>

## <a name="microsoft-365-certification-specification-updates"></a><span data-ttu-id="31cea-149">Microsoft 365 认证规范更新</span><span class="sxs-lookup"><span data-stu-id="31cea-149">Microsoft 365 Certification Specification Updates</span></span> 

<span data-ttu-id="31cea-150">预计大约每 6 到 12 个月更新一次 Microsoft 365 认证规范。</span><span class="sxs-lookup"><span data-stu-id="31cea-150">Updates to the Microsoft 365 Certification specification are anticipated approximately every six to twelve months.</span></span> <span data-ttu-id="31cea-151">这些更新可能会引入新的目标安全域和/或安全控件。</span><span class="sxs-lookup"><span data-stu-id="31cea-151">These updates might introduce new target security domains and / or security controls.</span></span> <span data-ttu-id="31cea-152">更新将基于开发人员的反馈、威胁环境的变化，并随着计划的成熟而提高计划的安全基线。</span><span class="sxs-lookup"><span data-stu-id="31cea-152">Updates will be based on developer feedback, changes to the threat landscape, and to increase the security baseline of the program as it matures.</span></span> 

<span data-ttu-id="31cea-153">已启动 Microsoft 365 认证评估的 ISV 可以继续使用在评估启动时有效的 Microsoft 365 认证规范版本进行评估。</span><span class="sxs-lookup"><span data-stu-id="31cea-153">ISVs that have already started the Microsoft 365 Certification assessment can continue the assessment with the version of the Microsoft 365 Certification Specification that was valid when the assessment was started.</span></span> <span data-ttu-id="31cea-154">所有新提交（包括年度重新认证）都需要根据发布的版本进行评估。</span><span class="sxs-lookup"><span data-stu-id="31cea-154">All new submissions, including annual recertification, will be required to be assessed against the version published.</span></span>

> [!NOTE]
> <span data-ttu-id="31cea-155">你无需遵守此 Microsoft 365 认证规范内的所有控制措施，即获得认证。</span><span class="sxs-lookup"><span data-stu-id="31cea-155">You are not required to comply with all the controls within this Microsoft 365 Certification Specification to be awarded a certification.</span></span> <span data-ttu-id="31cea-156">但是，对于本 Microsoft 365 认证 (中讨论的每个安全域，) 不会泄露的阈值。</span><span class="sxs-lookup"><span data-stu-id="31cea-156">However, passing thresholds (which will not be disclosed) are in place for each of the security domains discussed within this Microsoft 365 Certification Specification.</span></span> <span data-ttu-id="31cea-157">某些控件将被分类为"硬失败"，这意味着缺少这些安全控制将导致评估失败。</span><span class="sxs-lookup"><span data-stu-id="31cea-157">Some controls will be classed as a ‘**Hard Fail**’ which means the lack of these security controls will result in a failed assessment.</span></span> 

## <a name="certification-scope"></a><span data-ttu-id="31cea-158">认证范围</span><span class="sxs-lookup"><span data-stu-id="31cea-158">Certification Scope</span></span>

<span data-ttu-id="31cea-159">**范围内环境** 是支持传递应用/加载项代码的环境，并支持应用/加载项可以与应用/加载项通信的任何后端系统。</span><span class="sxs-lookup"><span data-stu-id="31cea-159">The **in-scope environment** is the environment that supports delivery of the app/add-in code and supports any backend systems that the app/add-in may be communicating with.</span></span> <span data-ttu-id="31cea-160">除非已进行适当的分段且已连接到的环境不会影响范围内环境的安全性，否则任何其他已连接环境也将包含在范围内。</span><span class="sxs-lookup"><span data-stu-id="31cea-160">Any additional connected-to environments will also be included in scope unless adequate segmentation is in place AND the connected-to environments cannot impact the security of the in-scope environment.</span></span> <span data-ttu-id="31cea-161">任何灾难恢复环境也需要包括在评估范围内，因为如果主环境发生任何情况，则需要这些环境来安装服务。</span><span class="sxs-lookup"><span data-stu-id="31cea-161">Any disaster recovery environments will also need to be included within the scope of the assessment as these environments would be required to fulfil the service should anything happen to the primary environment.</span></span>  <span data-ttu-id="31cea-162">范围 **内系统组件一** 词引用范围内环境中使用的所有   设备和系统。 </span><span class="sxs-lookup"><span data-stu-id="31cea-162">The term  **in-scope system components** reference **ALL** devices and systems that are used within the in-scope environment.</span></span> <span data-ttu-id="31cea-163">作用域内组件包括但不限于：</span><span class="sxs-lookup"><span data-stu-id="31cea-163">In-scope components include, but are not limited to:</span></span>
* <span data-ttu-id="31cea-164">Web 应用程序 () 。</span><span class="sxs-lookup"><span data-stu-id="31cea-164">The web application(s).</span></span>
* <span data-ttu-id="31cea-165">服务器。</span><span class="sxs-lookup"><span data-stu-id="31cea-165">Servers.</span></span>
* <span data-ttu-id="31cea-166">防火墙 (或等效) 。</span><span class="sxs-lookup"><span data-stu-id="31cea-166">Firewalls (or equivalent).</span></span>
* <span data-ttu-id="31cea-167">开关。</span><span class="sxs-lookup"><span data-stu-id="31cea-167">Switches.</span></span>
* <span data-ttu-id="31cea-168">负载平衡器。</span><span class="sxs-lookup"><span data-stu-id="31cea-168">Load balancers.</span></span>
* <span data-ttu-id="31cea-169">虚拟基础结构。</span><span class="sxs-lookup"><span data-stu-id="31cea-169">Virtual infrastructure.</span></span>
* <span data-ttu-id="31cea-170">云提供商 Web 管理门户</span><span class="sxs-lookup"><span data-stu-id="31cea-170">Cloud provider web management portals</span></span> 

> [!IMPORTANT]
> <span data-ttu-id="31cea-171">范围内环境必须具有 DMZ，并且应用/外接程序的支持环境必须与内部业务系统和公司环境分段，从而将评估活动的范围限定为仅范围内系统。</span><span class="sxs-lookup"><span data-stu-id="31cea-171">The in-scope environment, must have a DMZ and the supporting environment of the app/add-in must be segmented from the internal business systems and corporate environments thus limiting the scope of the assessment activities to the in-scope systems only.</span></span> <span data-ttu-id="31cea-172">认证分析师将在评估期间验证分段技术，并查看渗透测试报告，其中应包括测试，以验证使用的任何分段技术的有效性。</span><span class="sxs-lookup"><span data-stu-id="31cea-172">Certification analysts will validate segmentation techniques during the assessment along with reviewing penetration testing reports which should have included testing to validate the effectiveness of any segmentation techniques in use.</span></span>

### <a name="infrastructure-as-a-service-iaas-platform-as-a-service-paas-and-software-as-a-service-saas"></a><span data-ttu-id="31cea-173">IaaS 服务 (基础结构) 、平台为服务 (PaaS) 和软件 (SaaS) </span><span class="sxs-lookup"><span data-stu-id="31cea-173">Infrastructure as a Service (IaaS), Platform as a Service (PaaS) and Software as a Service (SaaS)</span></span> 
<span data-ttu-id="31cea-174">其中 IaaS 和/或 PaaS 用于支持审核中的应用程序或外接程序代码交付的基础结构，云平台提供商将负责在整个认证过程中评估的一些安全控制。</span><span class="sxs-lookup"><span data-stu-id="31cea-174">Where IaaS and/or PaaS is used to support the infrastructure of the application or add-in code delivery under review, the Cloud platform provider will be responsible for some of the security controls assessed throughout the certification process.</span></span> <span data-ttu-id="31cea-175">因此，云平台提供商需要通过外部合规性报告（如 [PCI DSS](bookmark://pci-dss)合规性   证明 (AOC) 、ISO27001 或 [SOC 2](bookmark://soc-2)类型 II 报告）向认证分析师提供独立的外部安全最佳做法验证。  </span><span class="sxs-lookup"><span data-stu-id="31cea-175">Therefore, certification analysts will need to be provided with independent external verification of security best practices by the Cloud platform provider through external compliance reports such as [PCI DSS](bookmark://pci-dss) Attestation of Compliance (AOC), ISO27001 or [SOC 2](bookmark://soc-2) Type II reports.</span></span> 

<span data-ttu-id="31cea-176">附录 F 根据以下部署类型以及应用/外接程序是否将传输 M365 数据，详细说明可能适用的安全控件：</span><span class="sxs-lookup"><span data-stu-id="31cea-176">Appendix F provides details of what security controls will likely be applicable based on the following deployment types and based upon whether the app/add-in exfiltrates M365 data or not:</span></span> 
* <span data-ttu-id="31cea-177">ISV 托管</span><span class="sxs-lookup"><span data-stu-id="31cea-177">ISV Hosted</span></span> 
* <span data-ttu-id="31cea-178">IaaS 托管</span><span class="sxs-lookup"><span data-stu-id="31cea-178">IaaS Hosted</span></span> 
* <span data-ttu-id="31cea-179">PaaS/Serverless Hosted</span><span class="sxs-lookup"><span data-stu-id="31cea-179">PaaS/Serverless Hosted</span></span> 
* <span data-ttu-id="31cea-180">混合托管</span><span class="sxs-lookup"><span data-stu-id="31cea-180">Hybrid Hosted</span></span> 
* <span data-ttu-id="31cea-181">共享托管</span><span class="sxs-lookup"><span data-stu-id="31cea-181">Shared Hosted</span></span> 

<span data-ttu-id="31cea-182">在部署 IaaS 或 PaaS 时，你需要提供在这些部署类型中托管的环境的证据。</span><span class="sxs-lookup"><span data-stu-id="31cea-182">Where IaaS or PaaS is deployed, you will need to provide evidence of the environment being hosted within these deployment types.</span></span>

### <a name="sampling"></a><span data-ttu-id="31cea-183">采样</span><span class="sxs-lookup"><span data-stu-id="31cea-183">Sampling</span></span>

<span data-ttu-id="31cea-184">支持认证评估的证据请求应基于范围内系统组件的示例，考虑不同的操作系统、设备的主要功能和不同的设备类型。</span><span class="sxs-lookup"><span data-stu-id="31cea-184">Requests for evidence in support of the certification assessment should be based on a sample of the in-scope system components in consideration of different operating systems, primary function of the device, and different device types.</span></span> <span data-ttu-id="31cea-185">将在认证过程开始时选择一个合适的示例。</span><span class="sxs-lookup"><span data-stu-id="31cea-185">A suitable sample will be selected at the start of the certification process.</span></span> <span data-ttu-id="31cea-186">下表应用作示例大小的指导：</span><span class="sxs-lookup"><span data-stu-id="31cea-186">The following table should be used as a guide on what the sample size may be:</span></span>

|<span data-ttu-id="31cea-187">总体大小</span><span class="sxs-lookup"><span data-stu-id="31cea-187">Population Size</span></span>              | <span data-ttu-id="31cea-188">示例</span><span class="sxs-lookup"><span data-stu-id="31cea-188">Sample</span></span>                  |
|---------------------------- |-------------------------|
|<span data-ttu-id="31cea-189"><5</span><span class="sxs-lookup"><span data-stu-id="31cea-189"><5</span></span>|<span data-ttu-id="31cea-190">1</span><span class="sxs-lookup"><span data-stu-id="31cea-190">1</span></span>|
|<span data-ttu-id="31cea-191">>5 & <10</span><span class="sxs-lookup"><span data-stu-id="31cea-191">>5 & <10</span></span>|<span data-ttu-id="31cea-192">2</span><span class="sxs-lookup"><span data-stu-id="31cea-192">2</span></span>|
|<span data-ttu-id="31cea-193">>9 & <25</span><span class="sxs-lookup"><span data-stu-id="31cea-193">>9 & <25</span></span>|<span data-ttu-id="31cea-194">3</span><span class="sxs-lookup"><span data-stu-id="31cea-194">3</span></span>|
|<span data-ttu-id="31cea-195">>24</span><span class="sxs-lookup"><span data-stu-id="31cea-195">>24</span></span>|<span data-ttu-id="31cea-196">4 </span><span class="sxs-lookup"><span data-stu-id="31cea-196">4</span></span>|

> [!NOTE]
><span data-ttu-id="31cea-197">如果在初始示例中包含的设备之间发现了差异，则评估期间可能会增加样本大小。</span><span class="sxs-lookup"><span data-stu-id="31cea-197">If discrepancies are identified between devices included within the initial sample, the sample size may be increased during the assessment.</span></span> 

## <a name="certification-process"></a><span data-ttu-id="31cea-198">认证过程</span><span class="sxs-lookup"><span data-stu-id="31cea-198">Certification Process</span></span>

<span data-ttu-id="31cea-199">在开始认证过程之前，你需要已成功启动或完成发布者证明。</span><span class="sxs-lookup"><span data-stu-id="31cea-199">Before starting the certification process, you would need to have successfully started or completed your Publisher Attestation.</span></span> <span data-ttu-id="31cea-200">你的证明响应将用于支持 Microsoft 365 认证过程，并继续如下操作：</span><span class="sxs-lookup"><span data-stu-id="31cea-200">Your attestation responses will be used in support of the Microsoft 365 Certification process and proceeds as follows:</span></span> 

1. <span data-ttu-id="31cea-201">查看 Publisher 证明文档以确保与当前环境保持一致</span><span class="sxs-lookup"><span data-stu-id="31cea-201">Review your Publisher Attestation documentation to ensure alignment with your current environment</span></span> 
2. <span data-ttu-id="31cea-202">通过电子邮件请求获得 Microsoft 365 认证 <AppCert@microsoft.com></span><span class="sxs-lookup"><span data-stu-id="31cea-202">Request to progress to the Microsoft 365 Certification by emailing <AppCert@microsoft.com></span></span> 
3. <span data-ttu-id="31cea-203">认证分析师将在开始 Microsoft 365 认证过程之前打开一个对话</span><span class="sxs-lookup"><span data-stu-id="31cea-203">Certification analysts will open a dialogue before starting the Microsoft 365 Certification process</span></span>   
4. <span data-ttu-id="31cea-204">提交 [初始文档提交](#initial-document-submission)</span><span class="sxs-lookup"><span data-stu-id="31cea-204">Submit your [Initial Document Submission](#initial-document-submission)</span></span>
5. <span data-ttu-id="31cea-205">认证分析师将提供需要证据的控制措施列表，从而正式启动 Microsoft 365 认证流程</span><span class="sxs-lookup"><span data-stu-id="31cea-205">Certification analyst will provide a listing of controls for which evidence is required, which formally starts the Microsoft 365 Certification process</span></span>
6. <span data-ttu-id="31cea-206">提交证据，证明在 60 天内满足所有范围内 Microsoft 365 认证控制措施，以完成 Microsoft 365 认证</span><span class="sxs-lookup"><span data-stu-id="31cea-206">Submit evidence that demonstrates that all in-scope Microsoft 365 Certification controls have been met within a 60-day window to complete Microsoft 365 Certification</span></span> 

> [!IMPORTANT]
> <span data-ttu-id="31cea-207">**提交期限：** 预计评估过程平均需要 15 天，但你可以及时响应证据请求。</span><span class="sxs-lookup"><span data-stu-id="31cea-207">**Submission time frame:** It is anticipated that on average the assessment process should take 15 days, provided you are able to respond to evidence requests within a timely manner.</span></span> <span data-ttu-id="31cea-208">Microsoft 建议确保已阅读此认证提交指南，并确信你可以满足其中提供的控制措施，并且可在开始认证过程之前提供足够证据。</span><span class="sxs-lookup"><span data-stu-id="31cea-208">Microsoft recommends that you ensure this certification submission guide has been read and be confident that you can meet the controls set out within it, and you can provide enough evidence before starting the certification process.</span></span> <span data-ttu-id="31cea-209">开始认证过程后，最多允许 60 天完成评估，否则已收集的证据将过时。</span><span class="sxs-lookup"><span data-stu-id="31cea-209">Upon starting the certification process, a maximum of 60 days is permitted to complete the assessment, otherwise evidence already collected becomes stale.</span></span> <span data-ttu-id="31cea-210">如果在 60 天时间段后未达到成功评估，则提交将失败，并且必须重新开始该过程。</span><span class="sxs-lookup"><span data-stu-id="31cea-210">If, after the 60-day time-period, a successful assessment is not reached, the submission will be issued a fail and the process must start again.</span></span> <span data-ttu-id="31cea-211">如果由于不符合 Microsoft 365 认证规范或 60 天时间段已到达且未提供足够证据而颁发失败，Microsoft 不会公开失败结果。</span><span class="sxs-lookup"><span data-stu-id="31cea-211">If a fail is issued due to failing to meet the Microsoft 365 Certification Specification or because the 60-day time-period is reached and enough evidence is not provided, failing results will not be made public by Microsoft.</span></span> 

## <a name="compliance-evidence"></a><span data-ttu-id="31cea-212">合规性证据</span><span class="sxs-lookup"><span data-stu-id="31cea-212">Compliance Evidence</span></span>

<span data-ttu-id="31cea-213">尽管这不是必需的，但如果您当前符合其他外部安全框架，您可以选择使用这些认证来满足某些 Microsoft 365 认证控制措施。</span><span class="sxs-lookup"><span data-stu-id="31cea-213">Although it is not required, if you are currently in compliance with other external security frameworks, you can elect to use these certifications to satisfy some of the Microsoft 365 Certification controls.</span></span> <span data-ttu-id="31cea-214">认证分析师将检查任何受支持的外部安全框架的范围和安全控制范围，以确定可以从 Microsoft 365 认证评估中排除哪些控制措施，从而提供外部安全框架的范围，包括 Microsoft 365 认证评估的范围环境。</span><span class="sxs-lookup"><span data-stu-id="31cea-214">Certification analysts will review the scope and security control coverage of any supported external security frameworks to determine which controls can be excluded from the Microsoft 365 Certification assessment, providing the scope of the external security frameworks include the in-scope environments for the Microsoft 365 Certification assessment.</span></span> 

<span data-ttu-id="31cea-215">认证分析师将尝试将现有外部安全框架与 Microsoft 365 认证规范保持一致。</span><span class="sxs-lookup"><span data-stu-id="31cea-215">Certification analysts will try to align existing external security frameworks to the Microsoft 365 Certification specification.</span></span> <span data-ttu-id="31cea-216">但是，如果支持文档无法保证 Microsoft 365 认证控制措施已作为外部安全框架审核/评估的一部分进行评估，则需要提供所实施控制措施的其他证据。</span><span class="sxs-lookup"><span data-stu-id="31cea-216">However, if supporting documentation is unable to provide assurance that Microsoft 365 Certification controls were assessed as part of the external security frameworks audit/assessment you will need to provide additional evidence of the said controls being in place.</span></span> 

<span data-ttu-id="31cea-217">目前，可用于支持 Microsoft 365 认证评估的外部安全框架包括：</span><span class="sxs-lookup"><span data-stu-id="31cea-217">Currently, the external security frameworks that can be used in support of the Microsoft 365 Certification assessment include:</span></span>

*  <span data-ttu-id="31cea-218">[ISMS](#isms) /[IEC](#iec) - IS0/IEC 27001 规范</span><span class="sxs-lookup"><span data-stu-id="31cea-218">[ISMS](#isms)/[IEC](#iec) - IS0/IEC 27001 specification</span></span> 
*  [<span data-ttu-id="31cea-219">PCI DSS</span><span class="sxs-lookup"><span data-stu-id="31cea-219">PCI DSS</span></span>](#pci-dss)
*  [<span data-ttu-id="31cea-220">SOC 2</span><span class="sxs-lookup"><span data-stu-id="31cea-220">SOC 2</span></span>](#soc-2)

<span data-ttu-id="31cea-221">文档必须充分证明 Microsoft 365 认证的范围内环境已包含在这些外部安全框架范围内。</span><span class="sxs-lookup"><span data-stu-id="31cea-221">Documentation must adequately demonstrate that the in-scope environment for the Microsoft 365 Certification was included within the scope of these external security frameworks.</span></span> <span data-ttu-id="31cea-222">通过接受由信誉良好的外部第三方公司进行的有效认证的证据，可以验证这些安全框架。</span><span class="sxs-lookup"><span data-stu-id="31cea-222">Validation of these security frameworks will be fulfilled by accepting evidence of valid certifications conducted by reputable external third-party companies.</span></span> <span data-ttu-id="31cea-223">这些信誉良好的公司必须是相关合规性计划的国际认证机构的成员。</span><span class="sxs-lookup"><span data-stu-id="31cea-223">These reputable companies must be members of international accreditation bodies for relevant compliance programs.</span></span><span data-ttu-id="31cea-224">请参阅 [ISO](https://www.iso.org/certification.html) 27001 ISO 认证和标准化 [标准以及](https://www.pcisecuritystandards.org/assessors_and_solutions/qualified_security_assessors) PCI DSS (QSA) 认证。</span><span class="sxs-lookup"><span data-stu-id="31cea-224"> See [ISO Certification and Conformity Standards](https://www.iso.org/certification.html) for ISO 27001 and [Qualified Security Assessors](https://www.pcisecuritystandards.org/assessors_and_solutions/qualified_security_assessors) (QSA) for PCI DSS.</span></span> 

<span data-ttu-id="31cea-225">下表重点介绍了认证分析师在此验证过程中所需的文档：</span><span class="sxs-lookup"><span data-stu-id="31cea-225">The following table highlights documentation required by certification analysts as part of this validation process:</span></span>

| <span data-ttu-id="31cea-226">**标准**</span><span class="sxs-lookup"><span data-stu-id="31cea-226">**Standard**</span></span> | <span data-ttu-id="31cea-227">**要求**</span><span class="sxs-lookup"><span data-stu-id="31cea-227">**Requirements**</span></span> |
| ----- | ----- |
| <span data-ttu-id="31cea-228">**[ISO 27001](#iso-27001)**</span><span class="sxs-lookup"><span data-stu-id="31cea-228">**[ISO 27001](#iso-27001)**</span></span> | <span data-ttu-id="31cea-229">需要面向公众的 ISO  () 声明版本和颁发的 ISO 27001 证书的副本。</span><span class="sxs-lookup"><span data-stu-id="31cea-229">A public facing version of the **Statement of Applicability** (SOA) and a copy of the ISO 27001 certificate issued will be required.</span></span>  <span data-ttu-id="31cea-230">该 ISO 总结了你在 114 个信息安全控制措施中的位置，并用于确定 ISO 27001 证书中是否排除任何不令人信意的控制措施。</span><span class="sxs-lookup"><span data-stu-id="31cea-230">The SOA summarizes your position on each of the 114 information security controls and  will be used to identify if any exclusion of controls that are not satisfactorily detailed in the ISO 27001 certificate.</span></span> <span data-ttu-id="31cea-231">如果无法通过查看面向公众的 ISO 版本来确定这一点，那么，如果 ISO 27001 将用于验证某些 Microsoft 365 认证规范控件，则分析员可能需要访问完整的 ISO。</span><span class="sxs-lookup"><span data-stu-id="31cea-231">If this can't be determined by reviewing the public facing version of the SOA, the analyst might need access to the full SOA if ISO 27001 will be used to validate some of the Microsoft 365 Certification Specification controls.</span></span>  <span data-ttu-id="31cea-232">除了验证 ISO 27001 评估活动的范围之外，分析师还将确认审核公司的有效性，如上所述。</span><span class="sxs-lookup"><span data-stu-id="31cea-232">In addition to validating the scope of the ISO 27001 assessment activities, the analysts will also confirm the validity of the audit company as described above.</span></span>|
|<span data-ttu-id="31cea-233">**[PCI DSS](#pci-dss)**</span><span class="sxs-lookup"><span data-stu-id="31cea-233">**[PCI DSS](#pci-dss)**</span></span>| <span data-ttu-id="31cea-234">必须提供 AOC (一) 级别 **1** 合规性证明文档，以清楚地标识范围内应用程序和系统组件。</span><span class="sxs-lookup"><span data-stu-id="31cea-234">A valid **Level 1 Attestation of Compliance** (AOC) document must be provided clearly identifying the in-scope application and system components.</span></span>  <span data-ttu-id="31cea-235">自我评估 AOC **不会** 被接受为会议安全最佳做法的证据。</span><span class="sxs-lookup"><span data-stu-id="31cea-235">A self-assessment AOC **will not** be accepted as evidence of meeting security best practices.</span></span> <span data-ttu-id="31cea-236">AOC 将用于确定哪些 Microsoft 365 认证规范控制措施已作为 PCI DSS 评估的一部分进行评估和确认。</span><span class="sxs-lookup"><span data-stu-id="31cea-236">The AOC will be used to determine which of the Microsoft 365 Certification Specification controls have been evaluated and confirmed as part of the PCI DSS assessment.</span></span>|
|<span data-ttu-id="31cea-237">**[SOC 2](#soc-2)**</span><span class="sxs-lookup"><span data-stu-id="31cea-237">**[SOC 2](#soc-2)**</span></span>|<span data-ttu-id="31cea-238">**SOC 2 (类型 I** 或类型 II) 报告必须是最近 15 个月内发布的当前 (，并且声明的时间段是从) 年 27 个月内开始的，以用作符合此 Microsoft 365 认证规范中任何评估控制措施的证据。</span><span class="sxs-lookup"><span data-stu-id="31cea-238">The **SOC 2 (Type I or Type II)** report must be current (issued within the last 15 months and the declared time period started within the last 27 months) to be used as evidence of conformity with any of the assessment controls within this Microsoft 365 Certification Specification.</span></span>|


## <a name="microsoft-365-certification"></a><span data-ttu-id="31cea-239">Microsoft 365 认证</span><span class="sxs-lookup"><span data-stu-id="31cea-239">Microsoft 365 Certification</span></span>

<span data-ttu-id="31cea-240">支持的外部安全框架可以用作满足某些 Microsoft 365 认证控制措施的证据。</span><span class="sxs-lookup"><span data-stu-id="31cea-240">Supported external security frameworks can be used as evidence of meeting some of the Microsoft 365 Certification controls.</span></span> <span data-ttu-id="31cea-241">在考虑外部安全框架之前，认证分析师将使用上面提交的文档查看外部安全框架的范围和安全控制范围。</span><span class="sxs-lookup"><span data-stu-id="31cea-241">Before external security frameworks can be considered, certification analysts will review the scope and security control coverage of the external security framework using the documentation submitted above.</span></span> 

<span data-ttu-id="31cea-242">以下附录可用于确定外部安全框架和 Microsoft 365 认证规范之间可能存在的潜在差异，如下所示：</span><span class="sxs-lookup"><span data-stu-id="31cea-242">The following appendixes can be used to identify where potential gaps between the external security framework and the Microsoft 365 Certification specification exist as follows:</span></span> 

|<span data-ttu-id="31cea-243">**框架**</span><span class="sxs-lookup"><span data-stu-id="31cea-243">**Framework**</span></span> | <span data-ttu-id="31cea-244">**其他注意事项**</span><span class="sxs-lookup"><span data-stu-id="31cea-244">**Additional considerations**</span></span> |
|-------------- | --------------------|
|<span data-ttu-id="31cea-245">ISO 27001</span><span class="sxs-lookup"><span data-stu-id="31cea-245">ISO 27001</span></span>| <span data-ttu-id="31cea-246">[**附录 C：**](#appendix-c)证据收集 – ISO 27001 的增量。</span><span class="sxs-lookup"><span data-stu-id="31cea-246">[**Appendix C**](#appendix-c): Evidence Collection – Deltas for ISO 27001.</span></span>|
|<span data-ttu-id="31cea-247">PCI DSS</span><span class="sxs-lookup"><span data-stu-id="31cea-247">PCI DSS</span></span> | <span data-ttu-id="31cea-248">[**附录 D：**](#appendix-d)证据收集 – PCI DSS 的增量。</span><span class="sxs-lookup"><span data-stu-id="31cea-248">[**Appendix D**](#appendix-d): Evidence Collection – Deltas for PCI DSS.</span></span>|
|<span data-ttu-id="31cea-249">SOC 2</span><span class="sxs-lookup"><span data-stu-id="31cea-249">SOC 2</span></span>| <span data-ttu-id="31cea-250">[**附录 E：**](#appendix-e)证据收集 – SOC 2 的增量。</span><span class="sxs-lookup"><span data-stu-id="31cea-250">[**Appendix E**](#appendix-e): Evidence Collection – Deltas for SOC 2.</span></span>|

> [!NOTE]
> <span data-ttu-id="31cea-251">尽管上述外部安全标准/框架可以提交为证据，以满足某些 Microsoft 365 认证控制措施的要求，但通过 Microsoft 365 认证并不意味着你将成功通过针对这些标准/框架的审核。</span><span class="sxs-lookup"><span data-stu-id="31cea-251">Although the above-mentioned external security standards/frameworks can be submitted as evidence to meet some of the Microsoft 365 Certification controls, passing the Microsoft 365 Certification doesn't mean that you will successfully pass an audit against those standards/frameworks.</span></span> <span data-ttu-id="31cea-252">Microsoft 365 认证规范只是这些安全标准/框架的一小部分，它允许 Microsoft 在安全状态方面获得一级保证。</span><span class="sxs-lookup"><span data-stu-id="31cea-252">The Microsoft 365 Certification Specification is only a small subset of those security standards/frameworks that allows Microsoft to gain a level of assurance in reference to your security posture.</span></span>

## <a name="initial-document-submission"></a><span data-ttu-id="31cea-253">初始文档提交</span><span class="sxs-lookup"><span data-stu-id="31cea-253">Initial document submission</span></span>

<span data-ttu-id="31cea-254">初始文档提交将帮助认证分析师执行范围确定范围，并确定评估范围内的内容。</span><span class="sxs-lookup"><span data-stu-id="31cea-254">The initial document submission will help certification analysts perform scoping and determine what will be in scope for your assessment.</span></span> <span data-ttu-id="31cea-255">此后，你需要提交用于执行评估的支持文档和证据。</span><span class="sxs-lookup"><span data-stu-id="31cea-255">After which you will be required to submit supporting documentation and evidence used to carry out the assessment.</span></span> <span data-ttu-id="31cea-256">初始提交必须包含下面指定的信息：</span><span class="sxs-lookup"><span data-stu-id="31cea-256">Your initial submission must include the information specified below:</span></span>

| <span data-ttu-id="31cea-257">**文档 &nbsp; 概述**</span><span class="sxs-lookup"><span data-stu-id="31cea-257">**Documentation&nbsp;Overview**</span></span>     |   <span data-ttu-id="31cea-258">**文档详细信息**</span><span class="sxs-lookup"><span data-stu-id="31cea-258">**Documentation Details**</span></span>  |
| -------------------------| -----------------------------|
|<span data-ttu-id="31cea-259">**应用/加载项说明**</span><span class="sxs-lookup"><span data-stu-id="31cea-259">**App/Add-in Description**</span></span> | <span data-ttu-id="31cea-260">应用程序/外接程序的用途和功能的说明。</span><span class="sxs-lookup"><span data-stu-id="31cea-260">A description of the app/add-in’s purpose and functionality.</span></span> <span data-ttu-id="31cea-261">这应该为认证分析师提供对应用/加载项功能及其用途的深入了解</span><span class="sxs-lookup"><span data-stu-id="31cea-261">This should provide the certification analyst with a good understanding of how the app/add-in functions and what it is intended use is</span></span>
|<span data-ttu-id="31cea-262">**渗透测试报告**</span><span class="sxs-lookup"><span data-stu-id="31cea-262">**Penetration Testing Report**</span></span> |<span data-ttu-id="31cea-263">过去 12 个月内完成的渗透测试报告。</span><span class="sxs-lookup"><span data-stu-id="31cea-263">A penetration testing report completed within the last 12 months.</span></span> <span data-ttu-id="31cea-264">此报告必须包含支持部署应用/添加的环境，以及支持应用/加载项操作的其他环境。</span><span class="sxs-lookup"><span data-stu-id="31cea-264">This report must include the environment that supports the deployment of the app/add along with any additional environment that supports the operation of the app/add-in.</span></span> <span data-ttu-id="31cea-265">**注意** ：如果不执行年度渗透测试，可以选择通过认证过程完成测试。</span><span class="sxs-lookup"><span data-stu-id="31cea-265">**Note:** if you do not do annual penetration testing, you can elect to have them done through the certification process.</span></span>|
|<span data-ttu-id="31cea-266">**体系结构图**</span><span class="sxs-lookup"><span data-stu-id="31cea-266">**Architecture diagrams**</span></span>|<span data-ttu-id="31cea-267">逻辑体系结构图，表示应用/加载项支持基础结构的简要概述。</span><span class="sxs-lookup"><span data-stu-id="31cea-267">A logical architecture diagram representing a high-level overview of your app's / add-in’s supporting infrastructure.</span></span> <span data-ttu-id="31cea-268">这必须 **包括所有** 托管环境和支持应用/外接程序的基础结构。</span><span class="sxs-lookup"><span data-stu-id="31cea-268">This must include **all** hosting environments and supporting infrastructure supporting the app/add-in.</span></span> <span data-ttu-id="31cea-269">此图必须描述环境中所有不同的支持系统组件，以帮助认证分析师了解范围内的系统并帮助确定采样。</span><span class="sxs-lookup"><span data-stu-id="31cea-269">This diagram MUST depict all the different supporting system components within the environment to help certification analysts understand systems in scope and help to determine sampling.</span></span> <span data-ttu-id="31cea-270">另请指示使用哪种托管环境类型;ISV 托管、IaaS、PaaS 或混合。</span><span class="sxs-lookup"><span data-stu-id="31cea-270">Please also indicate what hosting environment type is used; ISV Hosted, IaaS, PaaS, or Hybrid.</span></span> <span data-ttu-id="31cea-271">**注意：** 使用 SaaS 时，请指明用于在环境中提供支持服务的各种 SaaS 服务。</span><span class="sxs-lookup"><span data-stu-id="31cea-271">**Note:** Where SaaS is used, please indicate the various SaaS services that are used to provide the supporting services within the environment.</span></span>|
|<span data-ttu-id="31cea-272">**公共占用空间**</span><span class="sxs-lookup"><span data-stu-id="31cea-272">**Public Footprint**</span></span> | <span data-ttu-id="31cea-273">详细说明 **支持** 基础结构使用的所有公用 IP 地址和 URL。</span><span class="sxs-lookup"><span data-stu-id="31cea-273">Detailing **all** public IP Addresses and URLs used by the supporting infrastructure.</span></span> <span data-ttu-id="31cea-274">这必须包括分配给环境的完整可路由 IP 范围，除非已实现适当的分段以拆分使用中的范围 (因此需要足够的分段证据) </span><span class="sxs-lookup"><span data-stu-id="31cea-274">This must include the full routable IP range allocated to the environment unless adequate segmentation has been implemented to split the range in use (adequate evidence of segmentation will be required)</span></span>|
|<span data-ttu-id="31cea-275">**数据流图**</span><span class="sxs-lookup"><span data-stu-id="31cea-275">**Data flow diagrams**</span></span> |<span data-ttu-id="31cea-276">详细说明以下内容的流程图：</span><span class="sxs-lookup"><span data-stu-id="31cea-276">Flow diagrams detailing the following:</span></span>
||<span data-ttu-id="31cea-277">&#x2713; M365 数据流流入和流出应用/外接程序 ([EUII](#euii) 和 [OII](#oii) ) 。</span><span class="sxs-lookup"><span data-stu-id="31cea-277">&#x2713; M365 Data flows to and from the App / Add-in (including [EUII](#euii) and [OII](#oii) ).</span></span>|
||<span data-ttu-id="31cea-278">&#x2713;支持基础结构中的 M365 数据流 (适用) </span><span class="sxs-lookup"><span data-stu-id="31cea-278">&#x2713; M365 Data flows within the supporting infrastructure(where applicable)</span></span>|
||<span data-ttu-id="31cea-279">&#x2713;图表突出显示了存储在何处和存储哪些数据、如何将数据传递给外部第三方 (包括哪些第三方) 以及如何在开放/公共网络和其余网络传输过程中保护数据的详细信息。</span><span class="sxs-lookup"><span data-stu-id="31cea-279">&#x2713; Diagrams highlighting where and what data is stored, how data is passed to external third parties(including details of what third parties) , and how data is protected in transit over open/public networks and at rest.</span></span>|
|<span data-ttu-id="31cea-280">**API 终结点详细信息**</span><span class="sxs-lookup"><span data-stu-id="31cea-280">**API Endpoint Details**</span></span>| <span data-ttu-id="31cea-281">应用使用的所有 API 终结点的完整列表。</span><span class="sxs-lookup"><span data-stu-id="31cea-281">A complete listing of all API Endpoints used by your app.</span></span> <span data-ttu-id="31cea-282">若要帮助了解环境范围，请提供环境中 API 终结点位置。</span><span class="sxs-lookup"><span data-stu-id="31cea-282">To help understand the environment scope, provide API endpoint locations within your environment.</span></span>                                
|<span data-ttu-id="31cea-283">**Microsoft API 权限**</span><span class="sxs-lookup"><span data-stu-id="31cea-283">**Microsoft API Permissions**</span></span>| <span data-ttu-id="31cea-284">提供文档 **，** 详细说明所有使用的 Microsoft API 以及请求应用/外接程序正常运行的权限以及请求的权限的理由</span><span class="sxs-lookup"><span data-stu-id="31cea-284">Provide documentation detailing **ALL** the Microsoft APIs that are used along with what permissions are being requested for the app/add-in to function along with a justification for the requested permissions</span></span>|
|<span data-ttu-id="31cea-285">**数据存储类型**</span><span class="sxs-lookup"><span data-stu-id="31cea-285">**Data storage types**</span></span> |<span data-ttu-id="31cea-286">数据存储和处理描述：</span><span class="sxs-lookup"><span data-stu-id="31cea-286">Data storage and handling documents describing:</span></span>|
||<span data-ttu-id="31cea-287">&#x2713;接收和存储客户 M365 数据 [EUII](#euii) 和 [OII](#oii) 的程度</span><span class="sxs-lookup"><span data-stu-id="31cea-287">&#x2713; To what extent is your customers M365 Data [EUII](#euii) and [OII](#oii) is being received and stored</span></span>|
||<span data-ttu-id="31cea-288">&#x2713;数据保留期。</span><span class="sxs-lookup"><span data-stu-id="31cea-288">&#x2713; The data retention period.</span></span>|
||<span data-ttu-id="31cea-289">&#x2713;捕获客户 M365 数据的原因。</span><span class="sxs-lookup"><span data-stu-id="31cea-289">&#x2713; Why the customer M365 Data is being captured.</span></span>|
||<span data-ttu-id="31cea-290">&#x2713;存储客户 M365 数据的位置 (应包含在上面提供的数据流图中) 。</span><span class="sxs-lookup"><span data-stu-id="31cea-290">&#x2713; Where customer M365 Data is stored (should be included within data flow diagrams supplied above).</span></span>|
|<span data-ttu-id="31cea-291">**合规性确认**</span><span class="sxs-lookup"><span data-stu-id="31cea-291">**Compliance confirmation**</span></span>|<span data-ttu-id="31cea-292">Publisher 证明提交中包含的外部安全框架的支持文档，或查看 Microsoft 365 认证控制措施时考虑的文档。</span><span class="sxs-lookup"><span data-stu-id="31cea-292">Supporting documentation for external security frameworks included within the Publisher Attestation submission or to be considered when reviewing Microsoft 365 Certification controls.</span></span> <span data-ttu-id="31cea-293">目前支持以下三种：</span><span class="sxs-lookup"><span data-stu-id="31cea-293">Currently, the following three are supported:</span></span>|
||<span data-ttu-id="31cea-294">&#x2713; AOC (PCI [DSS](#pci-dss)) 。</span><span class="sxs-lookup"><span data-stu-id="31cea-294">&#x2713; [PCI DSS](#pci-dss) Attestation of Compliance (AOC).</span></span>|
||<span data-ttu-id="31cea-295">&#x2713; [SOC 2](#soc-2) 类型 I/类型 II 报告。</span><span class="sxs-lookup"><span data-stu-id="31cea-295">&#x2713; [SOC 2](#soc-2) Type I/Type II reports.</span></span>|
||<span data-ttu-id="31cea-296">&#x2713; [ISMS](#isms)  /  [IEC](#iec) - 1S0/IEC 27001 SoA (适用性声明) 认证。</span><span class="sxs-lookup"><span data-stu-id="31cea-296">&#x2713; [ISMS](#isms) / [IEC](#iec) - 1S0/IEC 27001 Statement of Applicability (SoA) and Certification.</span></span>|
|<span data-ttu-id="31cea-297">**Web 依赖项**</span><span class="sxs-lookup"><span data-stu-id="31cea-297">**Web Dependencies**</span></span>|<span data-ttu-id="31cea-298">列出应用/加载项使用的当前运行版本的所有依赖项的文档。</span><span class="sxs-lookup"><span data-stu-id="31cea-298">Documentation listing all dependencies used by the app / add-in with the current running versions.</span></span>|
|<span data-ttu-id="31cea-299">**软件清单**</span><span class="sxs-lookup"><span data-stu-id="31cea-299">**Software Inventory**</span></span>|<span data-ttu-id="31cea-300">最新软件清单，包括范围内环境中使用的所有软件以及版本。</span><span class="sxs-lookup"><span data-stu-id="31cea-300">An up-to-date software inventory which includes all software used within the in-scope environment along with the versions.</span></span>|
|<span data-ttu-id="31cea-301">**硬件清单**</span><span class="sxs-lookup"><span data-stu-id="31cea-301">**Hardware Inventory**</span></span>| <span data-ttu-id="31cea-302">支持基础结构使用最新的硬件清单。</span><span class="sxs-lookup"><span data-stu-id="31cea-302">An up-to-date hardware inventory used by the supporting infrastructure.</span></span> <span data-ttu-id="31cea-303">这将用于在执行评估阶段时帮助采样。</span><span class="sxs-lookup"><span data-stu-id="31cea-303">This will be used to help with sampling when performing the assessment phase.</span></span> <span data-ttu-id="31cea-304">如果您的环境包括 PaaS，请提供使用的服务的详细信息。</span><span class="sxs-lookup"><span data-stu-id="31cea-304">If your environment includes PaaS provide details of services consumed.</span></span>|

## <a name="evidence-collection-and-assessment-activities"></a><span data-ttu-id="31cea-305">证据收集和评估活动</span><span class="sxs-lookup"><span data-stu-id="31cea-305">Evidence Collection and Assessment Activities</span></span>

<span data-ttu-id="31cea-306">通过可靠的证据收集和评估活动，认证分析师将能够评估你的安全状况，以获取足够级别的数据安全保证，并遵循 Microsoft 365 认证规范控制措施。</span><span class="sxs-lookup"><span data-stu-id="31cea-306">Through robust evidence collection and assessment activities, certification analysts will be able to assess your security posture to obtain an adequate level of data security assurance and adherence to the Microsoft 365 Certification Specification controls.</span></span> <span data-ttu-id="31cea-307">认证分析师将按如下方式实现此目的：</span><span class="sxs-lookup"><span data-stu-id="31cea-307">Certification analysts will achieve this as follows:</span></span> 

<span data-ttu-id="31cea-308">**证据收集**</span><span class="sxs-lookup"><span data-stu-id="31cea-308">**Evidence Collection**</span></span>

* <span data-ttu-id="31cea-309">初始文档，在上文的初始 [文档提交部分中](#initial-document-submission) 突出显示</span><span class="sxs-lookup"><span data-stu-id="31cea-309">Initial documentation, highlighted within the [Initial Documentation Submission](#initial-document-submission) section above</span></span> 
* <span data-ttu-id="31cea-310">策略文档</span><span class="sxs-lookup"><span data-stu-id="31cea-310">Policy documents</span></span> 
* <span data-ttu-id="31cea-311">处理文档</span><span class="sxs-lookup"><span data-stu-id="31cea-311">Process documents</span></span> 
* <span data-ttu-id="31cea-312">系统配置设置</span><span class="sxs-lookup"><span data-stu-id="31cea-312">System configuration settings</span></span> 
* <span data-ttu-id="31cea-313">更改票证</span><span class="sxs-lookup"><span data-stu-id="31cea-313">Change tickets</span></span> 
* <span data-ttu-id="31cea-314">更改控件记录</span><span class="sxs-lookup"><span data-stu-id="31cea-314">Change control records</span></span> 
* <span data-ttu-id="31cea-315">系统报告</span><span class="sxs-lookup"><span data-stu-id="31cea-315">System reports</span></span>

<span data-ttu-id="31cea-316">各种方法将用于收集完成评估过程所需的证据。</span><span class="sxs-lookup"><span data-stu-id="31cea-316">Various methods will be used to collect the evidence necessary to complete the assessment process.</span></span>  <span data-ttu-id="31cea-317">此证据收集可能的形式为：</span><span class="sxs-lookup"><span data-stu-id="31cea-317">This evidence collection may be in the form of:</span></span> 
* <span data-ttu-id="31cea-318">文档</span><span class="sxs-lookup"><span data-stu-id="31cea-318">Documents</span></span> 
* <span data-ttu-id="31cea-319">屏幕截图</span><span class="sxs-lookup"><span data-stu-id="31cea-319">Screenshots</span></span> 
* <span data-ttu-id="31cea-320">访谈</span><span class="sxs-lookup"><span data-stu-id="31cea-320">Interviews</span></span> 
* <span data-ttu-id="31cea-321">屏幕共享</span><span class="sxs-lookup"><span data-stu-id="31cea-321">Screensharing</span></span> 

<span data-ttu-id="31cea-322">在评估过程中将确定使用的证据收集技术。</span><span class="sxs-lookup"><span data-stu-id="31cea-322">The evidence collection techniques used will be determined during the assessment process.</span></span> 

<span data-ttu-id="31cea-323">**评估活动**</span><span class="sxs-lookup"><span data-stu-id="31cea-323">**Assessment Activities**</span></span>

<span data-ttu-id="31cea-324">认证分析师将查看你提供的证据，以确定你是否充分满足此 Microsoft 365 认证规范中的控制措施。</span><span class="sxs-lookup"><span data-stu-id="31cea-324">Certification analysts will review evidence you provide to determine if you have adequately met controls within this Microsoft 365 Certification Specification.</span></span> 

<span data-ttu-id="31cea-325">如果可能，为了缩短完成评估所需时间，应提前提供初始文档提交中详述的任何或 [](#initial-document-submission)   所有文档。</span><span class="sxs-lookup"><span data-stu-id="31cea-325">Where possible and to reduce the amount of time required to complete the assessment, any or all of the documentation detailed in the [Initial Documentation Submission](#initial-document-submission) should be provided in advance.</span></span>

<span data-ttu-id="31cea-326">认证分析师将首先查看初始文档提交和发布者证明信息中提供的证据，以确定适当的查询行、采样大小以及需要获取更多证据，如上所述。</span><span class="sxs-lookup"><span data-stu-id="31cea-326">Certification analysts will first review the evidence provided from the initial documentation submission and the Publisher Attestation information to identify appropriate lines of inquiry, sampling size, and the need for further evidence to be obtained as detailed above.</span></span>  <span data-ttu-id="31cea-327">认证分析师将分析收集的所有信息，以得出如何以及是否满足此 Microsoft 365 认证规范中的控制措施结论。</span><span class="sxs-lookup"><span data-stu-id="31cea-327">Certification analysts will analyze all information gathered to draw conclusions as to how and if you are meeting the controls within this Microsoft 365 Certification Specification.</span></span> 

## <a name="app-certification-criteria"></a><span data-ttu-id="31cea-328">应用认证条件</span><span class="sxs-lookup"><span data-stu-id="31cea-328">App Certification Criteria</span></span>

<span data-ttu-id="31cea-329">您的应用程序、支持基础结构和支持文档将跨以下安全域进行评估：</span><span class="sxs-lookup"><span data-stu-id="31cea-329">Your app, supporting infrastructure, and supporting documentation will be assessed across the following security domains:</span></span>

1. [<span data-ttu-id="31cea-330">**Application Security**</span><span class="sxs-lookup"><span data-stu-id="31cea-330">**Application Security**</span></span>](#application-security)
1. [<span data-ttu-id="31cea-331">**操作安全性/安全部署**</span><span class="sxs-lookup"><span data-stu-id="31cea-331">**Operational Security / Secure Deployment**</span></span>](#operational-security)
1. [<span data-ttu-id="31cea-332">**数据处理安全和隐私**</span><span class="sxs-lookup"><span data-stu-id="31cea-332">**Data Handling Security and Privacy**</span></span>](#data-handling-security-and-privacy)
1. [<span data-ttu-id="31cea-333">**可选的外部合规性框架审查**</span><span class="sxs-lookup"><span data-stu-id="31cea-333">**Optional External Compliance Framework Review**</span></span>](#optional-external-compliance-frameworks-review)

<span data-ttu-id="31cea-334">其中每个安全域都包括特定的关键控制措施，这些控制措施包含一个或多个特定要求，这些要求将在评估过程中进行评估。</span><span class="sxs-lookup"><span data-stu-id="31cea-334">Each of these security domains include specific key controls encompassing one or more specific requirements that will be evaluated as part of the assessment process.</span></span> <span data-ttu-id="31cea-335">为确保 Microsoft 365 认证对各种规模的开发人员均包含，四个安全域均使用评分系统进行评估，以确定每个域的总体分数。</span><span class="sxs-lookup"><span data-stu-id="31cea-335">To ensure that Microsoft 365 Certification is inclusive to developers of all sizes, each of the four security domains is assessed using a scoring system to determine an overall score from each of the domains.</span></span> <span data-ttu-id="31cea-336">根据未达到 Microsoft 365 认证控制措施的感知风险，每个 Microsoft 365 认证控制措施的分数在 1 (低) 和 3 (高) 之间分配。</span><span class="sxs-lookup"><span data-stu-id="31cea-336">Scores for each of the Microsoft 365 Certification controls are allocated between 1 (low) and 3 (high) based upon the perceived risk of that control not being met.</span></span> <span data-ttu-id="31cea-337">这四个安全域都有一个被视为通过的最小百分比标记。</span><span class="sxs-lookup"><span data-stu-id="31cea-337">Each of the four security domains will have a minimum percentage mark to be deemed a pass.</span></span> <span data-ttu-id="31cea-338">此规范的某些元素包括一些自动失败条件：</span><span class="sxs-lookup"><span data-stu-id="31cea-338">Certain elements of this specification include some automatic fail criteria:</span></span>

- <span data-ttu-id="31cea-339">API 权限不遵循 PoLP (最小特权) 。</span><span class="sxs-lookup"><span data-stu-id="31cea-339">API permissions not following the principle of least privilege (PoLP).</span></span>  
- <span data-ttu-id="31cea-340">没有渗透测试报告（如果需要）。</span><span class="sxs-lookup"><span data-stu-id="31cea-340">No penetration testing report when it is required.</span></span>
- <span data-ttu-id="31cea-341">无反恶意软件防御</span><span class="sxs-lookup"><span data-stu-id="31cea-341">No anti-malware defenses</span></span>
- <span data-ttu-id="31cea-342">未用于保护管理访问的多重身份验证。</span><span class="sxs-lookup"><span data-stu-id="31cea-342">Multi-Factor authentication not being used to protect administrative access.</span></span>  
- <span data-ttu-id="31cea-343">无修补过程。</span><span class="sxs-lookup"><span data-stu-id="31cea-343">No patching processes.</span></span>  
- <span data-ttu-id="31cea-344">没有合适的 [GDPR](#gdpr) 隐私声明。</span><span class="sxs-lookup"><span data-stu-id="31cea-344">No suitable [GDPR](#gdpr) privacy notice.</span></span>  

## <a name="application-security"></a><span data-ttu-id="31cea-345">Application Security</span><span class="sxs-lookup"><span data-stu-id="31cea-345">Application Security</span></span>

<span data-ttu-id="31cea-346">应用程序安全域重点关注以下三个方面：</span><span class="sxs-lookup"><span data-stu-id="31cea-346">The application security domain focuses upon the follow three areas:</span></span> 
* <span data-ttu-id="31cea-347">GraphAPI 权限验证</span><span class="sxs-lookup"><span data-stu-id="31cea-347">GraphAPI Permission Validation</span></span> 
* <span data-ttu-id="31cea-348">外部连接性检查</span><span class="sxs-lookup"><span data-stu-id="31cea-348">External Connectivity Checks</span></span>
* <span data-ttu-id="31cea-349">应用程序安全测试</span><span class="sxs-lookup"><span data-stu-id="31cea-349">Application Security Testing</span></span> 

<span data-ttu-id="31cea-350">**GraphAPI 权限验证**</span><span class="sxs-lookup"><span data-stu-id="31cea-350">**GraphAPI Permission Validation**</span></span>

<span data-ttu-id="31cea-351">执行 GraphAPI 权限验证以验证应用/外接程序不会请求过度许可的权限。</span><span class="sxs-lookup"><span data-stu-id="31cea-351">GraphAPI permission validation is carried out to validate the app/add-in does not request overly permissive permissions.</span></span> <span data-ttu-id="31cea-352">这是通过手动检查请求的权限来实施。</span><span class="sxs-lookup"><span data-stu-id="31cea-352">This is carried out by manually checking what permissions are requested.</span></span> <span data-ttu-id="31cea-353">认证分析师将针对发布者证明提交交叉引用这些检查，并评估所请求的访问级别以确保满足"最小特权"做法。</span><span class="sxs-lookup"><span data-stu-id="31cea-353">Certification analysts will cross reference these checks against the Publisher Attestation submission and evaluate the level of access being requested to ensure ‘least privilege’ practices are being met.</span></span> <span data-ttu-id="31cea-354">如果认证分析师认为不满足这些"最小特权"做法，认证分析师将就验证所请求权限的业务理由进行开放式讨论。</span><span class="sxs-lookup"><span data-stu-id="31cea-354">Where certification analysts believe these ‘least privilege’ practices are not being met, certification analysts will have an open discussion with you to validate the business justification for the permissions being requested.</span></span> <span data-ttu-id="31cea-355">在此审阅过程中发现的与发布者证明提交的任何差异也会获得反馈，以便可以更新你的发布者证明。</span><span class="sxs-lookup"><span data-stu-id="31cea-355">Any discrepancies against your Publisher Attestation submission found during this review will also get feedback so your Publisher Attestation can be updated.</span></span> 

<span data-ttu-id="31cea-356">**外部连接性检查**</span><span class="sxs-lookup"><span data-stu-id="31cea-356">**External Connectivity Checks**</span></span>

<span data-ttu-id="31cea-357">作为评估的一部分，分析员将执行应用程序功能的演练，以标识 M365 外部的连接。</span><span class="sxs-lookup"><span data-stu-id="31cea-357">As part of the assessment, an Analyst will perform a light walk through of the applications functionality to identify connections outside of M365.</span></span>  <span data-ttu-id="31cea-358">任何未标识为 Microsoft 或直接连接到服务的连接都将在评估期间进行标记和讨论。</span><span class="sxs-lookup"><span data-stu-id="31cea-358">Any connections which are not identified as being Microsoft or direct connections to your service will be flagged and discussed during the assessment.</span></span>

<span data-ttu-id="31cea-359">**应用程序安全测试**</span><span class="sxs-lookup"><span data-stu-id="31cea-359">**Application Security Testing**</span></span>

<span data-ttu-id="31cea-360">充分审查与应用/外接程序和支持环境相关的风险对于为客户提供应用/外接程序安全性的保证至关重要。</span><span class="sxs-lookup"><span data-stu-id="31cea-360">An adequate review of the risks associated with your app/add-in and supporting environment is essential in providing customers with assurance in the security of the app/add-in.</span></span> <span data-ttu-id="31cea-361">如果应用程序具有与 Microsoft 未发布的任何服务的任何连接，则必须执行渗透测试形式的应用程序安全测试。</span><span class="sxs-lookup"><span data-stu-id="31cea-361">Application security testing in the form of penetration testing MUST be carried out if your application has any connectivity to any service not published by Microsoft.</span></span> <span data-ttu-id="31cea-362">如果你的应用在没有连接到任何非 Microsoft 服务或后端的情况下独立运行，则不需要渗透测试。</span><span class="sxs-lookup"><span data-stu-id="31cea-362">If your app operates standalone without connectivity to any non-Microsoft service or backend, then penetration testing is not required.</span></span>


### <a name="penetration-testing-scope"></a><span data-ttu-id="31cea-363">渗透测试范围</span><span class="sxs-lookup"><span data-stu-id="31cea-363">Penetration Testing Scope</span></span>

<span data-ttu-id="31cea-364">渗透测试 **活动必须** 包括支持应用程序/外接程序部署 (例如;其中，应用程序/外接程序代码的托管位置通常是清单文件) 中的资源，以及支持应用程序/外接程序应用程序运行的其他 (例如;如果应用/外接程序与 Microsoft 365 外部的其他 Web 应用程序) 。</span><span class="sxs-lookup"><span data-stu-id="31cea-364">Penetration testing activities **MUST** include the environment that supports the deployment of the app/add-in (for example; where the app/add-in code is hosted which will typically be the resource within the manifest file) along with any additional environment that supports the operation of the app/add-in (for example; if the app/add-in talks to other web applications outside of Microsoft 365).</span></span>  <span data-ttu-id="31cea-365">定义范围时，需要小心以确保所有渗透测试活动中还包括任何会影响范围内环境安全性的"已连接到"系统或环境。</span><span class="sxs-lookup"><span data-stu-id="31cea-365">When defining the scope, care needs to be taken to ensure that any “connected-to” systems or environments that can impact upon the security of the in-scope environment is also included within ALL penetration testing activities.</span></span> 

<span data-ttu-id="31cea-366">当使用技术将范围内环境与其他环境分割时，渗透测试活动必须验证这种分段技术的有效性。</span><span class="sxs-lookup"><span data-stu-id="31cea-366">Where techniques are used to segment the in-scope environments from other environments, penetration testing activities MUST validate the effectiveness of said segmentation techniques.</span></span> <span data-ttu-id="31cea-367">这必须在渗透测试报告中详细说明。</span><span class="sxs-lookup"><span data-stu-id="31cea-367">This must be detailed within the penetration testing report.</span></span> 
 

### <a name="testspecification"></a><span data-ttu-id="31cea-368">测试规范</span><span class="sxs-lookup"><span data-stu-id="31cea-368">Test Specification</span></span> 

|<span data-ttu-id="31cea-369">测试</span><span class="sxs-lookup"><span data-stu-id="31cea-369">Test</span></span> | <span data-ttu-id="31cea-370">控件</span><span class="sxs-lookup"><span data-stu-id="31cea-370">Controls</span></span> |
|-------|-----------|
|<span data-ttu-id="31cea-371">**渗透测试**</span><span class="sxs-lookup"><span data-stu-id="31cea-371">**Penetration testing**</span></span>| <span data-ttu-id="31cea-372">应用程序和基础结构渗透 **测试** 必须每 12 个月 (一次，) 一家信誉良好的独立公司执行。</span><span class="sxs-lookup"><span data-stu-id="31cea-372">Application and infrastructure penetration testing **MUST** take place annually (every 12 months) and conducted by a reputable independent company.</span></span> <span data-ttu-id="31cea-373">在渗透测试完成后的一个月内或更早地完成对已识别的关键和高风险漏洞的修正，具体取决于已记录修补过程。</span><span class="sxs-lookup"><span data-stu-id="31cea-373">Remediation of identified critical and high-risk vulnerabilities **MUST** be completed within one month of the conclusion of the penetration testing, or sooner depending on the documented patching process.</span></span><span data-ttu-id="31cea-374">IP 地址、 (API 终结点等的完整外部占用空间必须包含在渗透测试范围内) 并且必须记录在渗透测试报告中。IP 地址 (URL、API 终结点等的完整外部占用空间必须包含在渗透测试范围内) 并且必须记录在渗透测试报告中。</span><span class="sxs-lookup"><span data-stu-id="31cea-374"> The full external footprint (IP Addresses, URLs, API Endpoints, etc.) MUST be included within the scope of penetration testing and must be documented within the penetration testing report.The full external footprint (IP Addresses, URLs, API Endpoints, etc.) *\*MUST** be included within the scope of penetration testing and must be documented within the penetration testing report.</span></span>                                                                                                                                                                           <span data-ttu-id="31cea-375">Web 应用程序渗透测试必须包括所有漏洞类;例如，最新的 OWASP 前 10 或 SANS 前 25 个 CWE。</span><span class="sxs-lookup"><span data-stu-id="31cea-375">Web application penetration testing MUST include all vulnerability classes; for example, the most current OWASP Top 10 or SANS Top 25 CWE.</span></span>                                                                                                                                                                                <span data-ttu-id="31cea-376">不需要由渗透测试公司重新测试识别的漏洞 — 修正和自我审查已足够，但评估期间必须提供足以证明修正的足够证据。 </span><span class="sxs-lookup"><span data-stu-id="31cea-376">Retesting of identified vulnerabilities by the penetration testing company is not required — remediation and self-review is sufficient however, adequate evidence to demonstrate sufficient remediation **MUST** be provided during the assessment.</span></span>|

### <a name="application-security-testing-reportreview"></a><span data-ttu-id="31cea-377">应用程序安全测试报告审阅</span><span class="sxs-lookup"><span data-stu-id="31cea-377">Application Security Testing Report Review</span></span>

<span data-ttu-id="31cea-378">将审核渗透测试报告，以确保没有满足以下自动失败 **条件的漏洞：**</span><span class="sxs-lookup"><span data-stu-id="31cea-378">Penetration testing reports will be reviewed to ensure there are no vulnerabilities that meet the following **automatic failure criteria:**</span></span>

* <span data-ttu-id="31cea-379">存在不受支持的操作系统。</span><span class="sxs-lookup"><span data-stu-id="31cea-379">Presence of an unsupported operating system.</span></span> 

* <span data-ttu-id="31cea-380">存在默认、可枚举或可猜测的管理帐户。</span><span class="sxs-lookup"><span data-stu-id="31cea-380">Presence of default, enumerable, or guessable administrative accounts.</span></span>

* <span data-ttu-id="31cea-381">是否存在SQL注入风险。\*</span><span class="sxs-lookup"><span data-stu-id="31cea-381">Presence of SQL injection risks.\*</span></span>

* <span data-ttu-id="31cea-382">存在跨网站脚本。\*</span><span class="sxs-lookup"><span data-stu-id="31cea-382">Presence of cross-site scripting.\*</span></span>

* <span data-ttu-id="31cea-383">存在目录遍历 (路径) 漏洞。\*</span><span class="sxs-lookup"><span data-stu-id="31cea-383">Presence of directory traversal (file path) vulnerabilities.\*</span></span>

* <span data-ttu-id="31cea-384">存在 HTTP 漏洞，例如标头响应拆分、请求分割和异步攻击。\*</span><span class="sxs-lookup"><span data-stu-id="31cea-384">Presence of HTTP vulnerabilities, e.g., Header response splitting, Request smuggling, and Desync attacks.\*</span></span>

* <span data-ttu-id="31cea-385">存在源代码泄漏 ( [包括 LFI](#lfi)) 。\*</span><span class="sxs-lookup"><span data-stu-id="31cea-385">Presence of source code disclosure (including [LFI](#lfi)).\*</span></span>

* <span data-ttu-id="31cea-386">CVSS 修补程序管理准则定义的任何关键分数或高分。</span><span class="sxs-lookup"><span data-stu-id="31cea-386">Any critical or high score as defined by the CVSS patch management guidelines.</span></span>

* <span data-ttu-id="31cea-387">任何重大技术漏洞，很容易利用它来破坏大量 EUII 或 OUI。</span><span class="sxs-lookup"><span data-stu-id="31cea-387">Any significant technical vulnerability which can be readily exploited to compromise a large amount of EUII or OUI.</span></span>

<span data-ttu-id="31cea-388">\*不考虑漏洞 CVSS 分数</span><span class="sxs-lookup"><span data-stu-id="31cea-388">\*Regardless of the vulnerabilities CVSS Score</span></span>

> [!IMPORTANT]
><span data-ttu-id="31cea-389">报告必须能够提供足够保证，确保可以演示应用程序安全测试规范一节中详述的所有内容。</span><span class="sxs-lookup"><span data-stu-id="31cea-389">Reports must be able to provide enough assurance that everything detailed within the Application Security Test Specification section can be demonstrated.</span></span>


### <a name="penetration-testing-requirements-and-cost"></a><span data-ttu-id="31cea-390">渗透测试要求和成本</span><span class="sxs-lookup"><span data-stu-id="31cea-390">Penetration Testing Requirements and Cost</span></span>

<span data-ttu-id="31cea-391">对于当前不参与渗透测试的 ISV，渗透测试包含在 Microsoft 365 认证下。</span><span class="sxs-lookup"><span data-stu-id="31cea-391">For ISVs that currently do not engage in penetration testing, penetration testing is included under the Microsoft 365 Certification.</span></span> <span data-ttu-id="31cea-392">Microsoft 将安排并支付渗透测试的成本，最多 12 天的手动测试。</span><span class="sxs-lookup"><span data-stu-id="31cea-392">Microsoft will arrange and cover the cost of a penetration test for up to 12 days of manual testing.</span></span> <span data-ttu-id="31cea-393">渗透测试成本根据测试环境所需的天数计算。</span><span class="sxs-lookup"><span data-stu-id="31cea-393">Penetration tests costs are calculated based on the number of days required to test the environment.</span></span> <span data-ttu-id="31cea-394">任何超过 12 天的测试费用都将由 ISV 负责。</span><span class="sxs-lookup"><span data-stu-id="31cea-394">Any expenses exceeding 12 days of testing will be the responsibility of the ISV.</span></span> <span data-ttu-id="31cea-395">ISV 还将负责证明在授予认证之前已修复渗透测试中标识的漏洞，但不需要生成干净报告。</span><span class="sxs-lookup"><span data-stu-id="31cea-395">The ISV will also be responsible for demonstrating that vulnerabilities identified in the penetration test have been remediated prior to a certification being awarded, but do not need to produce a clean report.</span></span>

<span data-ttu-id="31cea-396">一旦安排渗透测试，ISV 将负责与重新计划和取消相关的费用，如下所示：</span><span class="sxs-lookup"><span data-stu-id="31cea-396">Once a penetration test is arranged, the ISV is responsible for fees associated with rescheduling and cancellations as follows:</span></span>

| <span data-ttu-id="31cea-397">**重新计划费用时间刻度**</span><span class="sxs-lookup"><span data-stu-id="31cea-397">**Rescheduling Fee Timescale**</span></span> | <span data-ttu-id="31cea-398">**应付款比例**</span><span class="sxs-lookup"><span data-stu-id="31cea-398">**Proportion Payable**</span></span> |
|------------------|------------------------|
| <span data-ttu-id="31cea-399">在计划开始日期前 30 天之前，收到重新计划请求。</span><span class="sxs-lookup"><span data-stu-id="31cea-399">Re-schedule request received more than 30 days prior to scheduled start date.</span></span> | <span data-ttu-id="31cea-400">0% 付款</span><span class="sxs-lookup"><span data-stu-id="31cea-400">0% Payable</span></span> |
| <span data-ttu-id="31cea-401">在计划开始日期前 8 到 30 天内收到重新计划请求。</span><span class="sxs-lookup"><span data-stu-id="31cea-401">Re-schedule request received 8 to 30 days prior to scheduled start date.</span></span> | <span data-ttu-id="31cea-402">25% 应付款</span><span class="sxs-lookup"><span data-stu-id="31cea-402">25% Payable</span></span> |
| <span data-ttu-id="31cea-403">在计划开始日期前 2 到 7 天内收到公司重新预订日期的重新计划请求。</span><span class="sxs-lookup"><span data-stu-id="31cea-403">Re-schedule request received within 2 to 7 days prior to scheduled start date with a firm re-booking date.</span></span>| <span data-ttu-id="31cea-404">50% 应付款</span><span class="sxs-lookup"><span data-stu-id="31cea-404">50% Payable</span></span> |
| <span data-ttu-id="31cea-405">在开始日期前 2 天内收到重新计划请求。</span><span class="sxs-lookup"><span data-stu-id="31cea-405">Re-schedule request received less than 2 days before the start date.</span></span> | <span data-ttu-id="31cea-406">100% 应付款</span><span class="sxs-lookup"><span data-stu-id="31cea-406">100% Payable</span></span> |

| <span data-ttu-id="31cea-407">**取消费用时间刻度**</span><span class="sxs-lookup"><span data-stu-id="31cea-407">**Cancellation Fee Timescale**</span></span> | <span data-ttu-id="31cea-408">**应付款比例**</span><span class="sxs-lookup"><span data-stu-id="31cea-408">**Proportion Payable**</span></span> |
|------------------|------------------------|
| <span data-ttu-id="31cea-409">取消请求在计划开始日期前 30 天之前收到。</span><span class="sxs-lookup"><span data-stu-id="31cea-409">Cancellation request received more than 30 days prior to scheduled start date.</span></span> | <span data-ttu-id="31cea-410">25% 应付款</span><span class="sxs-lookup"><span data-stu-id="31cea-410">25% Payable</span></span> |
| <span data-ttu-id="31cea-411">取消请求在计划开始日期前 8 到 30 天收到。</span><span class="sxs-lookup"><span data-stu-id="31cea-411">Cancellation request received 8 to 30 days days prior to scheduled start date.</span></span> | <span data-ttu-id="31cea-412">50% 应付款</span><span class="sxs-lookup"><span data-stu-id="31cea-412">50% Payable</span></span> |
| <span data-ttu-id="31cea-413">在计划开始日期前 7 天内收到的取消请求。</span><span class="sxs-lookup"><span data-stu-id="31cea-413">Cancellation request received within 7 days prior to scheduled start date.</span></span> | <span data-ttu-id="31cea-414">90% 应付款</span><span class="sxs-lookup"><span data-stu-id="31cea-414">90% Payable</span></span> |

## <a name="operational-security"></a><span data-ttu-id="31cea-415">操作安全性</span><span class="sxs-lookup"><span data-stu-id="31cea-415">Operational Security</span></span>

<span data-ttu-id="31cea-416">此域衡量应用的支持基础结构和部署过程与安全最佳做法的一致性。</span><span class="sxs-lookup"><span data-stu-id="31cea-416">This domain measures the alignment of your app's supporting infrastructure and deployment processes with security best practices.</span></span>

### <a name="test-specification"></a><span data-ttu-id="31cea-417">测试规范</span><span class="sxs-lookup"><span data-stu-id="31cea-417">Test Specification</span></span>

|<span data-ttu-id="31cea-418">测试</span><span class="sxs-lookup"><span data-stu-id="31cea-418">Test</span></span> | <span data-ttu-id="31cea-419">控件</span><span class="sxs-lookup"><span data-stu-id="31cea-419">Controls</span></span> |
| ------------------------|------------------------------ |
| <span data-ttu-id="31cea-420">**恶意软件保护**</span><span class="sxs-lookup"><span data-stu-id="31cea-420">**Malware Protection**</span></span> | <span data-ttu-id="31cea-421">您必须在通常受恶意软件影响的所有范围内系统上部署恶意软件保护机制。</span><span class="sxs-lookup"><span data-stu-id="31cea-421">You must deploy malware protection mechanisms on all in-scope systems that are commonly affected by malware.</span></span> <span data-ttu-id="31cea-422">这些保护机制可能包括使用防病毒软件或防止恶意软件的应用程序控制技术。</span><span class="sxs-lookup"><span data-stu-id="31cea-422">These protection mechanisms can include the use of anti-virus software or application control techniques that protect against malware.</span></span> <span data-ttu-id="31cea-423">使用防病毒软件或应用程序控制时，它必须满足以下条件。</span><span class="sxs-lookup"><span data-stu-id="31cea-423">Where anti-virus software or application control is used, it MUST meet the following criteria.</span></span>                                                                                            <span data-ttu-id="31cea-424">防病毒 (包括反恶意软件产品) 必须满足以下条件：</span><span class="sxs-lookup"><span data-stu-id="31cea-424">Anti-virus (also including anti-malware products) MUST meet the following:</span></span> |
||<span data-ttu-id="31cea-425">&#x2713;防病毒软件正在范围内的所有系统组件上运行。</span><span class="sxs-lookup"><span data-stu-id="31cea-425">&#x2713; Anti-virus software is running on all system components within scope.</span></span>|
||<span data-ttu-id="31cea-426">&#x2713;防病毒软件在 (30 天内保持) 。</span><span class="sxs-lookup"><span data-stu-id="31cea-426">&#x2713; Anti-virus software is kept up to date (within 30 days).</span></span>|
||<span data-ttu-id="31cea-427">&#x2713;防病毒签名在 1 天内 (保持最新) 。</span><span class="sxs-lookup"><span data-stu-id="31cea-427">&#x2713; Anti-virus signatures are kept up to date (within 1 day).</span></span>|
||<span data-ttu-id="31cea-428">&#x2713;必须配置访问时扫描和/或定期扫描以及通知。</span><span class="sxs-lookup"><span data-stu-id="31cea-428">&#x2713; Either on-access scanning and/or periodic scans with notifications must be configured.</span></span>  <span data-ttu-id="31cea-429">如果使用访问扫描，则还必须配置每周扫描，但是如果未配置访问扫描，则必须配置每日扫描。</span><span class="sxs-lookup"><span data-stu-id="31cea-429">Where on-access scanning is used, weekly scans **MUST** also be configured, however if on-access scanning is not configured, daily scanning must be configured.</span></span>|
||<span data-ttu-id="31cea-430">&#x2713;防病毒软件 **的配置** 必须如下所示。</span><span class="sxs-lookup"><span data-stu-id="31cea-430">&#x2713; Anti-virus software **MUST** be configured as follows.</span></span>|
||<span data-ttu-id="31cea-431">&emsp;&#x25fc;阻止可疑恶意软件。</span><span class="sxs-lookup"><span data-stu-id="31cea-431">&emsp;&#x25fc; Block suspected malware.</span></span>|
||<span data-ttu-id="31cea-432">&emsp;&#x25fc;隔离可疑恶意软件。</span><span class="sxs-lookup"><span data-stu-id="31cea-432">&emsp;&#x25fc; Quarantine suspected malware.</span></span>|
||<span data-ttu-id="31cea-433">&emsp;&#x25fc;对可疑恶意软件发出警报。</span><span class="sxs-lookup"><span data-stu-id="31cea-433">&emsp;&#x25fc; Provide an alert on suspected malware.</span></span>|
||<span data-ttu-id="31cea-434">&#x2713; **防病毒软件必须配置为** 记录所有活动。</span><span class="sxs-lookup"><span data-stu-id="31cea-434">&#x2713; Anti-virus software **MUST** be configured to log all activities.</span></span>
||<span data-ttu-id="31cea-435">&#x2713;策略和过程 **必须** 到位，以推广强大的反恶意软件做法。</span><span class="sxs-lookup"><span data-stu-id="31cea-435">&#x2713; Policies and procedures **MUST** be in place to promote strong anti-malware practices.</span></span>|
||<span data-ttu-id="31cea-436">或</span><span class="sxs-lookup"><span data-stu-id="31cea-436">or</span></span>|
||<span data-ttu-id="31cea-437">必须在所有范围内系统上配置应用程序控件，以满足以下要求：</span><span class="sxs-lookup"><span data-stu-id="31cea-437">Application controls MUST be configured on all in-scope system to meet the following:</span></span>|
||<span data-ttu-id="31cea-438">&#x2713;允许对范围内系统组件执行的所有允许的应用程序都必须得到组织正式批准。</span><span class="sxs-lookup"><span data-stu-id="31cea-438">&#x2713; All allowed applications permitted to execute on in-scope system components MUST be formally approved by the organization..</span></span>|
||<span data-ttu-id="31cea-439">&#x2713;组织必须维护已批准应用程序的完整列表以及该应用程序的业务理由。</span><span class="sxs-lookup"><span data-stu-id="31cea-439">&#x2713; The organization MUST maintain a complete list of approved applications with business justification for the application.</span></span>|
||<span data-ttu-id="31cea-440">&#x2713;特定应用程序控制机制必须完整记录：即列入白名单的位置;代码签名等。</span><span class="sxs-lookup"><span data-stu-id="31cea-440">&#x2713; Specific application control mechanisms MUST be fully documented: i.e. whitelisted locations; code signing, etc.</span></span>|
||<span data-ttu-id="31cea-441">&#x2713;应用程序控件必须配置为文档。</span><span class="sxs-lookup"><span data-stu-id="31cea-441">&#x2713; Application control MUST be configured as document.</span></span>|
||<span data-ttu-id="31cea-442">&#x2713;已记录的应用程序审批流程必须已就位且可审核。</span><span class="sxs-lookup"><span data-stu-id="31cea-442">&#x2713; Documented process for application approvals must be in place and auditable.</span></span>|
|<span data-ttu-id="31cea-443">**修补程序管理**</span><span class="sxs-lookup"><span data-stu-id="31cea-443">**Patch Management**</span></span>|<span data-ttu-id="31cea-444">**您必须** 已制定有文档的修补策略和过程，以确保及时进行修补。</span><span class="sxs-lookup"><span data-stu-id="31cea-444">You **MUST** have documented patching policies and procedures in place that ensure patching is conducted in a timely manner.</span></span> <span data-ttu-id="31cea-445">必须 **建立一** 个可靠的流程，以根据 CVSS V3.1 建议的风险排名分数或等效评分分类识别、排名和修补新的安全漏洞：</span><span class="sxs-lookup"><span data-stu-id="31cea-445">A robust process **MUST** be in place that identifies, ranks, and patches new security vulnerabilities based on the CVSS V3.1 **Recommended Risk Ranking Scores**, or equivalent scoring taxonomy:</span></span> 
||<span data-ttu-id="31cea-446">**CVSS** v3.1 (中建议的风险排名分数范围) </span><span class="sxs-lookup"><span data-stu-id="31cea-446">**Recommended Risk Ranking Scores** (CVSS v3.1 Base Score Range)</span></span>|
||<span data-ttu-id="31cea-447">&emsp;**关键**：9.0 - 10.0。</span><span class="sxs-lookup"><span data-stu-id="31cea-447">&emsp; **Critical**: 9.0 - 10.0.</span></span>|
||<span data-ttu-id="31cea-448">&emsp;**高**：7.0 - 8.9。</span><span class="sxs-lookup"><span data-stu-id="31cea-448">&emsp; **High**: 7.0 - 8.9.</span></span>|
||<span data-ttu-id="31cea-449">&emsp;**中等**：4.0 - 6.9。</span><span class="sxs-lookup"><span data-stu-id="31cea-449">&emsp; **Medium**: 4.0 - 6.9.</span></span>|
||<span data-ttu-id="31cea-450">&emsp;**低**：0.1 - 3.9。</span><span class="sxs-lookup"><span data-stu-id="31cea-450">&emsp; **Low**: 0.1 - 3.9.</span></span>|
||<span data-ttu-id="31cea-451">&emsp;**无**：0.0</span><span class="sxs-lookup"><span data-stu-id="31cea-451">&emsp; **None**: 0.0</span></span> |
|| <span data-ttu-id="31cea-452">**重要** 说明：识别新漏洞的过程必须足够可靠，以便根据已定义的已记录修补窗口识别和修补漏洞。</span><span class="sxs-lookup"><span data-stu-id="31cea-452">**IMPORTANT**: The process to identify new vulnerabilities must be robust enough to allow for the identification and patching of vulnerabilities in line with the documented patching window you have defined.</span></span> |
|<span data-ttu-id="31cea-453">**Patching**</span><span class="sxs-lookup"><span data-stu-id="31cea-453">**Patching**</span></span>|<span data-ttu-id="31cea-454">&#x2713;任何严重、高或中等风险问题都必须在ISV 预先确定且有记录的时间范围内进行修复，ISV 代表必须解决问题之前所解决的 **最短时段。**</span><span class="sxs-lookup"><span data-stu-id="31cea-454">&#x2713; Any Critical, High, or Medium risk issues **MUST** be patched within a pre-determined and documented period decided by the ISV which represents the minimal window of time before the issue **must be** resolved.</span></span>  <span data-ttu-id="31cea-455">尽管修补窗口由 ISV 定义，但该窗口需在合理的时间范围内。</span><span class="sxs-lookup"><span data-stu-id="31cea-455">Although the patching window is defined by the ISV, the window needs to be within a reasonable timeframe.</span></span> <span data-ttu-id="31cea-456">例如，修复关键漏洞的三个月并不合理，因此在 Microsoft 365 认证评估中被拒绝。</span><span class="sxs-lookup"><span data-stu-id="31cea-456">For example, three months to patch a Critical vulnerability would not be reasonable and therefore rejected within your Microsoft 365 Certification assessment.</span></span>|
||<span data-ttu-id="31cea-457">&#x2713;有关如何执行修补的策略和过程必须已制定，并且必须包括环境中使用的所有适用的操作系统、应用程序和软件组件。</span><span class="sxs-lookup"><span data-stu-id="31cea-457">&#x2713; Policies and procedures detailing how patching is conducted **MUST** be in place and **MUST** include all applicable operating systems, applications and software components used within the environment.</span></span> <span data-ttu-id="31cea-458">这包括应用/加载项中使用的任何 Web 依赖项。</span><span class="sxs-lookup"><span data-stu-id="31cea-458">This includes any web dependencies used within the app/add-in.</span></span>|
||<span data-ttu-id="31cea-459">&#x2713;不得在环境中使用供应商不再支持的软件组件和操作系统。 </span><span class="sxs-lookup"><span data-stu-id="31cea-459">&#x2713; Software components and operating systems no longer supported by the vendor **MUST** not be used within the environment.</span></span> <span data-ttu-id="31cea-460">必须 **制定支持** 策略，以确保将不受支持的软件组件/操作系统从环境中删除，并且必须制定一个流程来确定软件组件何时结束使用。</span><span class="sxs-lookup"><span data-stu-id="31cea-460">Supporting policies **MUST** be in place to ensure unsupported software components / operating systems will be removed from the environment and a process to identify when software components go end-of-life must be in place.</span></span>|
|<span data-ttu-id="31cea-461">**漏洞扫描**</span><span class="sxs-lookup"><span data-stu-id="31cea-461">**Vulnerability scanning**</span></span>|<span data-ttu-id="31cea-462">漏洞扫描必须包括：</span><span class="sxs-lookup"><span data-stu-id="31cea-462">Vulnerability scanning must include:</span></span>|
||<span data-ttu-id="31cea-463">&#x2713;针对基础结构和 Web 应用程序扫描的作用域内环境的完整公共占用 (URL 和 IP 地址执行季度外部漏洞) 。</span><span class="sxs-lookup"><span data-stu-id="31cea-463">&#x2713; Quarterly external vulnerability scanning carried out against the **FULL** public footprint of the in-scope environment (URLs AND IP Addresses for Infrastructure and Web Application scanning).</span></span>|
||<span data-ttu-id="31cea-464">&#x2713;按季度验证的内部漏洞扫描对作用域内系统组件执行， (PaaS) 。</span><span class="sxs-lookup"><span data-stu-id="31cea-464">&#x2713; Quarterly authenticated internal vulnerability scanning carried out against in-scope system components (not for PaaS).</span></span>|
||<span data-ttu-id="31cea-465">&#x2713;记录漏洞修正策略必须已制定，以确保系统组件不会受到已知漏洞的影响，具体方法为根据定义的 CVSS \*\*\*\* 建议的风险排名分数 (修复漏洞的时间线，) 。</span><span class="sxs-lookup"><span data-stu-id="31cea-465">&#x2713; A documented vulnerability remediation policy **MUST** be in place to ensure system components are free from known vulnerabilities by detailing the timeline to fix vulnerabilities based upon your defined CVSS **Recommended Risk Ranking Scores**(see above).</span></span>|
||<span data-ttu-id="31cea-466">&#x2713;执行持续重新扫描，直到按照ISV 的修正策略的定义，在要求的时间线内修复确定的风险排名漏洞。</span><span class="sxs-lookup"><span data-stu-id="31cea-466">&#x2713; Ongoing re-scans **MUST** be carried out until identified risk ranked vulnerabilities are remediated within the required timeline, as defined by the ISV’s remediation policy.</span></span> <span data-ttu-id="31cea-467">尽管修正时间线由 ISV 定义，但该窗口需在合理的时间范围内。</span><span class="sxs-lookup"><span data-stu-id="31cea-467">Although the remediation timeline is defined by the ISV, the window needs to be within a reasonable timeframe.</span></span> <span data-ttu-id="31cea-468">例如，修正关键漏洞的三个月在 Microsoft 365 认证评估中并不合理，因此被拒绝。</span><span class="sxs-lookup"><span data-stu-id="31cea-468">For example, three months to remediate a Critical vulnerability would not be reasonable and therefore rejected within your Microsoft 365 Certification assessment.</span></span>|
|<span data-ttu-id="31cea-469">**防火墙**</span><span class="sxs-lookup"><span data-stu-id="31cea-469">**Firewalls**</span></span>|<span data-ttu-id="31cea-470">支持基础结构应具有防火墙或 (，其中将按如下) 使用云服务：</span><span class="sxs-lookup"><span data-stu-id="31cea-470">Your supporting infrastructure will be expected to have a firewall (or equivalent where Cloud services are being consumed) configured as follows:</span></span>|
||<span data-ttu-id="31cea-471">&#x2713; **必须** 安装在公开范围内环境的所有 Internet 连接上。</span><span class="sxs-lookup"><span data-stu-id="31cea-471">&#x2713; **MUST** be installed on all internet connections exposing the in-scope environments.</span></span>|
||<span data-ttu-id="31cea-472">&#x2713; **所有** DMZs (安全区域) 任何受信任的网络之间安装。</span><span class="sxs-lookup"><span data-stu-id="31cea-472">&#x2713; **MUST** be installed between all DMZs (Demilitarized Zones) and any trusted networks.</span></span>|
||<span data-ttu-id="31cea-473">&#x2713;所有公共访问 **必须** 终止于 DMZ 安全 (区) 。</span><span class="sxs-lookup"><span data-stu-id="31cea-473">&#x2713; All public access **MUST** terminate in a DMZ (Demilitarized Zone).</span></span> |
||<span data-ttu-id="31cea-474">&#x2713;安装到生产环境之前，必须更改默认管理凭据。</span><span class="sxs-lookup"><span data-stu-id="31cea-474">&#x2713; Default administrative credentials **MUST** be changed, prior to installation into production environments.</span></span>|
||<span data-ttu-id="31cea-475">&#x2713;任何方向 (范围内防火墙允许的所有流量) 必须经过审批过程，并且所有协议、服务和端口都必须记录有业务理由。</span><span class="sxs-lookup"><span data-stu-id="31cea-475">&#x2713; ­All traffic permitted through in-scope firewalls (in either direction) **MUST** go through an approval process and all protocols, services and ports must be documented with business justifications.</span></span>|
||<span data-ttu-id="31cea-476">&#x2713;防火墙规则必须与记录允许的规则一起配置。</span><span class="sxs-lookup"><span data-stu-id="31cea-476">&#x2713; Firewall rules must be configured in-line with the documented permitted rules.</span></span>|
||<span data-ttu-id="31cea-477">&#x2713;，必须在所有防火墙非控制台管理界面上启用强加密，以遵守附录 **B。**</span><span class="sxs-lookup"><span data-stu-id="31cea-477">&#x2713; ­Strong cryptography, in line with **Appendix B**, **MUST** be enabled on all firewall non-console administrative interfaces.</span></span>|
||<span data-ttu-id="31cea-478">&#x2713;必须针对防火墙管理 (启用 MFA) 多重身份验证。 </span><span class="sxs-lookup"><span data-stu-id="31cea-478">&#x2713; Multi-factor authentication (MFA) **MUST** be enabled for firewall administrative access..</span></span>|
||<span data-ttu-id="31cea-479">&#x2713;防火墙 **审查必须至少每** 六个月执行一次。</span><span class="sxs-lookup"><span data-stu-id="31cea-479">&#x2713;­ Firewall reviews **MUST** be conducted at least every six months.</span></span>|
||<span data-ttu-id="31cea-480">认证分析将检查防火墙规则基础，以检查是否存在流向潜在第三方出口流量以验证外部第三方数据共享。</span><span class="sxs-lookup"><span data-stu-id="31cea-480">Certification analysis will review the firewall rules base for the presence of egress traffic flows to potential third parties to validate external third-party data sharing.</span></span>  |
||<span data-ttu-id="31cea-481">**WAF (Web 应用程序) 。**</span><span class="sxs-lookup"><span data-stu-id="31cea-481">**Web Application Firewall (WAF)**.</span></span> <span data-ttu-id="31cea-482">如果部署 WAF 或等效措施以帮助防范 Web 应用程序威胁和漏洞，将提供额外的信用额度。</span><span class="sxs-lookup"><span data-stu-id="31cea-482">Additional credit will be given if a WAF or equivalent measure is deployed to help protect against web application threats and vulnerabilities.</span></span> <span data-ttu-id="31cea-483">如果存在，支持策略 **和过程应** 随以下 WAF 配置一起到位：</span><span class="sxs-lookup"><span data-stu-id="31cea-483">If present, supporting policies and procedures **SHOULD** be in place along with the following WAF configurations:</span></span> |
||<span data-ttu-id="31cea-484">&#x2713; WAF 应在主动防御模式下运行 (自动阻止识别的攻击) 或在监视模式下 (主动监视/调查警报) 。</span><span class="sxs-lookup"><span data-stu-id="31cea-484">&#x2713; WAF SHOULD operate in active defense mode (automatically blocking identified attacks) or in monitoring mode (actively monitoring/investigating alerts).</span></span>|
||<span data-ttu-id="31cea-485">&#x2713;配置为支持 SSL 卸载的[WAF。](#ssl)</span><span class="sxs-lookup"><span data-stu-id="31cea-485">&#x2713; WAF configured to support [SSL](#ssl) offloading.</span></span>|
||<span data-ttu-id="31cea-486">&#x2713; WAF 应按照 [OWASP](#owasp) \*\*\*\* 核心规则集   (3.0 或 3.1) 进行配置，以防范以下大多数问题：</span><span class="sxs-lookup"><span data-stu-id="31cea-486">&#x2713; WAF SHOULD be configured as per the [OWASP](#owasp) **Core Rule Set** (3.0 or 3.1) to protect against the majority of the following:</span></span>|
||<span data-ttu-id="31cea-487">&emsp;&#x25fc;协议和编码问题。</span><span class="sxs-lookup"><span data-stu-id="31cea-487">&emsp;&#x25fc; Protocol and encoding issues.</span></span>|
||<span data-ttu-id="31cea-488">&emsp;&#x25fc;标头注入、请求拆分和响应拆分。</span><span class="sxs-lookup"><span data-stu-id="31cea-488">&emsp;&#x25fc; Header injection, request smuggling, and response splitting.</span></span>|
||<span data-ttu-id="31cea-489">&emsp;&#x25fc;文件和路径遍历攻击。</span><span class="sxs-lookup"><span data-stu-id="31cea-489">&emsp;&#x25fc; File and path traversal attacks.</span></span>|
||<span data-ttu-id="31cea-490">&emsp;&#x25fc;远程文件包含 (RFI) 攻击。</span><span class="sxs-lookup"><span data-stu-id="31cea-490">&emsp;&#x25fc; Remote file inclusion (RFI) attacks.</span></span>|
||<span data-ttu-id="31cea-491">&emsp;&#x25fc;远程代码执行攻击。</span><span class="sxs-lookup"><span data-stu-id="31cea-491">&emsp;&#x25fc; Remote code execution attacks.</span></span>|
||<span data-ttu-id="31cea-492">&emsp;&#x25fc; PHP 注入攻击。</span><span class="sxs-lookup"><span data-stu-id="31cea-492">&emsp;&#x25fc; PHP-injection attacks.</span></span>|
||<span data-ttu-id="31cea-493">&emsp;&#x25fc;跨网站脚本攻击。</span><span class="sxs-lookup"><span data-stu-id="31cea-493">&emsp;&#x25fc; Cross-site scripting attacks.</span></span>|
||<span data-ttu-id="31cea-494">&emsp;&#x25fc; SQL注入攻击。</span><span class="sxs-lookup"><span data-stu-id="31cea-494">&emsp;&#x25fc; SQL-injection attacks.</span></span>|
||<span data-ttu-id="31cea-495">&emsp;&#x25fc;会话修复攻击。</span><span class="sxs-lookup"><span data-stu-id="31cea-495">&emsp;&#x25fc; Session-fixation attacks.</span></span>|
|<span data-ttu-id="31cea-496">**更改控件**</span><span class="sxs-lookup"><span data-stu-id="31cea-496">**Change Control**</span></span>|<span data-ttu-id="31cea-497">必须 **制定更改控制** 策略和过程，以确保以旨在维护环境的安全性、稳定性和完整性的方式实现更改。</span><span class="sxs-lookup"><span data-stu-id="31cea-497">Change control policies and procedures **MUST** be in place to ensure that changes are implemented in a manner aimed at maintaining the security, stability, and integrity of the environment.</span></span> <span data-ttu-id="31cea-498">需要以下 **更改控制条件** ：</span><span class="sxs-lookup"><span data-stu-id="31cea-498">The following change control criteria **ARE** required:</span></span>|
||<span data-ttu-id="31cea-499">&#x2713;职责分离 - 开发和测试环境必须与生产环境分开。</span><span class="sxs-lookup"><span data-stu-id="31cea-499">&#x2713; Separation of duties—development and test environments **MUST** be separate from the production environments.</span></span>|
||<span data-ttu-id="31cea-500">&#x2713;生产环境 **中的敏感数据不得** 在开发/测试环境中使用。</span><span class="sxs-lookup"><span data-stu-id="31cea-500">&#x2713; Sensitive data from production environments **MUST** not be used within development/test environments.</span></span>|
||<span data-ttu-id="31cea-501">&#x2713;引入生产环境之前，必须在测试/开发环境中测试所有更改。</span><span class="sxs-lookup"><span data-stu-id="31cea-501">&#x2713; All changes MUST be tested within a test/development environment prior to being introduced into the production environment.</span></span>|
||<span data-ttu-id="31cea-502">&#x2713;投入生产 **之前** ，将引发 **和** 授权更改请求。</span><span class="sxs-lookup"><span data-stu-id="31cea-502">&#x2713; Change requests **ARE** raised and authorized **PRIOR** to going into production.</span></span>|
||<span data-ttu-id="31cea-503">&#x2713;更改请求至少 **必须包括：**</span><span class="sxs-lookup"><span data-stu-id="31cea-503">&#x2713; At a minimum, change requests **MUST** include:</span></span>|
||<span data-ttu-id="31cea-504">&emsp;&#x25fc;影响文档。</span><span class="sxs-lookup"><span data-stu-id="31cea-504">&emsp;&#x25fc; Documentation of impact.</span></span>|
||<span data-ttu-id="31cea-505">&emsp;&#x25fc;记录退出过程。</span><span class="sxs-lookup"><span data-stu-id="31cea-505">&emsp;&#x25fc; Documented back-out procedures.</span></span>|
||<span data-ttu-id="31cea-506">&#x2713;更改 **请求必须** 标记为已完成，只有在成功执行功能测试之后。</span><span class="sxs-lookup"><span data-stu-id="31cea-506">&#x2713; Change requests **MUST** be marked as complete, only **AFTER** successful functionality testing has been carried out.</span></span>|
|<span data-ttu-id="31cea-507">**安全软件开发/部署**</span><span class="sxs-lookup"><span data-stu-id="31cea-507">**Secure Software Development/Deployment**</span></span>|<span data-ttu-id="31cea-508">安全性需要处于软件开发实践的最前端，以最大限度地降低将编码漏洞引入应用/外接程序的风险，从而维护安全的环境和保护数据。</span><span class="sxs-lookup"><span data-stu-id="31cea-508">Security needs to be at the forefront of software development practices to minimize the risk of introducing coding vulnerabilities into the app / add-in, thereby maintaining a secure environment, and securing data.</span></span> <span data-ttu-id="31cea-509">以下软件开发安全做法 **必须** 到位：</span><span class="sxs-lookup"><span data-stu-id="31cea-509">The following software development secure practices **MUST** be in place:</span></span> |
||<span data-ttu-id="31cea-510">&#x2713;您必须已建立和记录涵盖整个软件开发生命周期的软件开发过程。</span><span class="sxs-lookup"><span data-stu-id="31cea-510">&#x2713; You MUST have an established and documented software development process covering the entire software-development lifecycle.</span></span>|
||<span data-ttu-id="31cea-511">&#x2713;所有代码更改都必须由原始开发人员外的其他用户进行审阅和授权过程。</span><span class="sxs-lookup"><span data-stu-id="31cea-511">&#x2713; All code changes MUST go through a review and authorization process by someone other than the original developer.</span></span>|
||<span data-ttu-id="31cea-512">&#x2713;安全编码实践和审查技术 **必须** 解决 [OWASP 前 10](https://owasp.org/www-project-top-ten) 或 SANS 前 [25](https://www.sans.org/top25-software-errors) 大 CWE 漏洞类的问题。</span><span class="sxs-lookup"><span data-stu-id="31cea-512">&#x2713; Secure coding practices and review techniques **MUST** address the [OWASP Top 10](https://owasp.org/www-project-top-ten) or [SANS Top 25 CWE](https://www.sans.org/top25-software-errors) Vulnerability Classes.</span></span>|
||<span data-ttu-id="31cea-513">&#x2713; **开发人员必须至少** 每年接受安全软件编码培训。</span><span class="sxs-lookup"><span data-stu-id="31cea-513">&#x2713; Developers **MUST** undergo secure software coding training at least annually.</span></span>|
||<span data-ttu-id="31cea-514">&#x2713;代码 **库必须** 受 MFA 保护。</span><span class="sxs-lookup"><span data-stu-id="31cea-514">&#x2713; Code repositories **MUST** be secured by MFA.</span></span>|
||<span data-ttu-id="31cea-515">&#x2713;必须实施适当的 **访问控制** ，以保护代码库免受恶意代码修改。</span><span class="sxs-lookup"><span data-stu-id="31cea-515">&#x2713; Adequate access controls **MUST** be in place to protect code repositories against malicious code modifications.</span></span>|
||<span data-ttu-id="31cea-516">**注意**：Microsoft 发布了 [](https://www.microsoft.com/en-us/securityengineering/sdl/)SDL 安全 (生命周期) ，Microsoft 遵循它以支持其产品中的安全保证和合规性要求。</span><span class="sxs-lookup"><span data-stu-id="31cea-516">**Note**: Microsoft has published the [Security Development Lifecycle](https://www.microsoft.com/en-us/securityengineering/sdl/) (SDL) that Microsoft follows to support security assurance and compliance requirements within its products.</span></span> <span data-ttu-id="31cea-517">SDL 通过减少软件漏洞的数量和严重性来帮助开发人员构建更安全的软件，同时降低开发成本。</span><span class="sxs-lookup"><span data-stu-id="31cea-517">The SDL helps developers build more secure software by reducing the number and severity of vulnerabilities in software, while reducing development cost.</span></span>|
|<span data-ttu-id="31cea-518">**帐户管理**</span><span class="sxs-lookup"><span data-stu-id="31cea-518">**Account Management**</span></span>| <span data-ttu-id="31cea-519">作用域内系统组件帐户管理以及支持策略和过程 **必须满足** 以下要求：</span><span class="sxs-lookup"><span data-stu-id="31cea-519">In-scope system component account management as well as supporting policies and procedures **MUST** meet the following:</span></span> |
||<span data-ttu-id="31cea-520">&#x2713;在 (系统组件) 或删除供应商或 ISV 用户的默认凭据。 </span><span class="sxs-lookup"><span data-stu-id="31cea-520">&#x2713; Default credentials (Vendor or ISV) **ARE** either disabled or removed across all in-scope system components.</span></span>|
||<span data-ttu-id="31cea-521">&#x2713;帐户创建、修改 **和删除必须** 经过已建立的审批流程。</span><span class="sxs-lookup"><span data-stu-id="31cea-521">&#x2713; Account creation, modification and deletion **MUST** go through an established approval process.</span></span>|
||<span data-ttu-id="31cea-522">&#x2713;超过 3 个月的帐户必须禁用或删除，因此 ISV 需要具有实现此目的的机制。 </span><span class="sxs-lookup"><span data-stu-id="31cea-522">&#x2713; Accounts that have not been used for over 3 months **MUST** be disabled or deleted, therefore, ISV needs to have a mechanism of achieving this.</span></span>|
||<span data-ttu-id="31cea-523">&#x2713;强密码策略或其他合适的 **缓解必须配置为** 保护用户凭据。</span><span class="sxs-lookup"><span data-stu-id="31cea-523">&#x2713;Strong password policies or other suitable mitigation **MUST** be configured to protect user credentials.</span></span> <span data-ttu-id="31cea-524">以下密码策略应用作指南：</span><span class="sxs-lookup"><span data-stu-id="31cea-524">The following password policy should be used as a guideline:</span></span>|
||<span data-ttu-id="31cea-525">&emsp;&#x25fc;最短密码长度为 8 个字符</span><span class="sxs-lookup"><span data-stu-id="31cea-525">&emsp;&#x25fc; Minimum password length of eight characters</span></span>|
||<span data-ttu-id="31cea-526">&emsp;&#x25fc;尝试次数不超过 10 次的帐户锁定阈值</span><span class="sxs-lookup"><span data-stu-id="31cea-526">&emsp;&#x25fc; Account lockout threshold of no more than 10 attempts</span></span>|
||<span data-ttu-id="31cea-527">&emsp;&#x25fc;密码至少五个密码的密码历史记录</span><span class="sxs-lookup"><span data-stu-id="31cea-527">&emsp;&#x25fc; Password history of a minimum of five passwords</span></span>|
||<span data-ttu-id="31cea-528">&emsp;&#x25fc;强制使用强密码</span><span class="sxs-lookup"><span data-stu-id="31cea-528">&emsp;&#x25fc; Enforcement of the use of strong passwords</span></span>|
||<span data-ttu-id="31cea-529">&#x2713;向每个用户颁发唯一用户帐户;不使用共享帐户。</span><span class="sxs-lookup"><span data-stu-id="31cea-529">&#x2713; Unique user accounts MUST be issued to each user; no shared accounts are to be used.</span></span>|
||<span data-ttu-id="31cea-530">&#x2713;最小特权原则必须适用于所有用户，用于实现此目的的机制应 (即使用组) 。</span><span class="sxs-lookup"><span data-stu-id="31cea-530">&#x2713; Least privilege principles **MUST** apply to all users, the mechanism used to achieve this should be documented (i.e. the use of groups).</span></span> |
||<span data-ttu-id="31cea-531">&#x2713;适当的服务帐户强化必须记录并执行，例如禁用交互式登录、仅限特定主机登录等。</span><span class="sxs-lookup"><span data-stu-id="31cea-531">&#x2713; Suitable service account hardening **MUST** be documented and carried out, for example, interactive logon disabled, logons limited to specific hosts, etc.</span></span> |
||<span data-ttu-id="31cea-532">&#x2713;远程访问解决方案 **必须**：</span><span class="sxs-lookup"><span data-stu-id="31cea-532">&#x2713; Remote Access solutions **MUST**:</span></span> |
||<span data-ttu-id="31cea-533">&emsp;&#x25fc;利用 MFA (多重身份验证) </span><span class="sxs-lookup"><span data-stu-id="31cea-533">&emsp;&#x25fc; utilize MFA (Multi Factor Authentication)</span></span>|
||<span data-ttu-id="31cea-534">&emsp;&#x25fc;使用符合或超过传输中数据配置文件的传输保护配置文件中的数据，如附录 A 中所述</span><span class="sxs-lookup"><span data-stu-id="31cea-534">&emsp;&#x25fc; utilize a data in transit protection profile that meets or exceeds the data-in-transit configuration profile as described in Appendix A</span></span>|
||<span data-ttu-id="31cea-535">&#x2713;如果公共 DNS 的管理在作用域内环境之外，则必须将能够进行 DNS 修改的所有用户帐户配置为使用 MFA。</span><span class="sxs-lookup"><span data-stu-id="31cea-535">&#x2713; Where the management of Public DNS is outside of the in-scope environment, all user accounts able to make DNS modifications MUST be configured to use MFA.</span></span>|
||<span data-ttu-id="31cea-536">**注意** ：云管理门户还需要满足适用的帐户管理要求，请参阅附录 F 了解更多详细信息。</span><span class="sxs-lookup"><span data-stu-id="31cea-536">**Note** : Cloud Management Portals will also need to meet applicable account management requirements, see Appendix F for further details.</span></span>|
|<span data-ttu-id="31cea-537">**入侵检测和防护 (可选)**</span><span class="sxs-lookup"><span data-stu-id="31cea-537">**Intrusion Detection and Prevention (OPTIONAL)**</span></span>| <span data-ttu-id="31cea-538">如果 IDPS (入侵检测和防护系统) 范围内支持环境的外围使用，则额外信用。</span><span class="sxs-lookup"><span data-stu-id="31cea-538">Extra credit will be given where IDPS (Intrusion Detection and Prevention System) is used at the perimeter of the in-scope supporting environments.</span></span>  <span data-ttu-id="31cea-539">以下推荐的控件包括：</span><span class="sxs-lookup"><span data-stu-id="31cea-539">The following recommended controls include:</span></span> |
||<span data-ttu-id="31cea-540">&#x2713; IDPS 应部署在支持环境的外围</span><span class="sxs-lookup"><span data-stu-id="31cea-540">&#x2713; IDPS SHOULD be deployed at the perimeter of the supporting environment</span></span> |
||<span data-ttu-id="31cea-541">&#x2713; IDPS 签名应保持最新（在过去一天内）</span><span class="sxs-lookup"><span data-stu-id="31cea-541">&#x2713; IDPS signatures SHOULD be kept current, within the past day</span></span> |
||<span data-ttu-id="31cea-542">&#x2713; TLS 检查配置 IDPS</span><span class="sxs-lookup"><span data-stu-id="31cea-542">&#x2713; IDPS SHOULD be configured for TLS inspection</span></span> |
||<span data-ttu-id="31cea-543">&#x2713;所有入站和出站流量配置 IDPS</span><span class="sxs-lookup"><span data-stu-id="31cea-543">&#x2713; IDPS SHOULD be configured for ALL inbound and outbound traffic</span></span> |
||<span data-ttu-id="31cea-544">&#x2713; IDPS 应配置为发出警报</span><span class="sxs-lookup"><span data-stu-id="31cea-544">&#x2713; IDPS SHOULD be configured for alerting</span></span> |
|<span data-ttu-id="31cea-545">**事件日志记录**</span><span class="sxs-lookup"><span data-stu-id="31cea-545">**Event Logging**</span></span> |<span data-ttu-id="31cea-546">日志记录范围 **必须\*\*\*\*包括所有** 范围内系统组件和应用程序，包括恶意软件保护机制。</span><span class="sxs-lookup"><span data-stu-id="31cea-546">Logging coverage **MUST** include **ALL** in-scope system components and applications, including malware protection mechanisms.</span></span> <span data-ttu-id="31cea-547">必须 **记录以下** 事件：</span><span class="sxs-lookup"><span data-stu-id="31cea-547">The following events **MUST** be logged:</span></span>|
||<span data-ttu-id="31cea-548">&emsp;&#x25fc;用户访问系统组件和应用程序</span><span class="sxs-lookup"><span data-stu-id="31cea-548">&emsp;&#x25fc; Users access to system components and the application</span></span>|
||<span data-ttu-id="31cea-549">&emsp;&#x25fc;高特权用户执行的所有操作</span><span class="sxs-lookup"><span data-stu-id="31cea-549">&emsp;&#x25fc; All actions taken by a high-privileged user</span></span>|
||<span data-ttu-id="31cea-550">&emsp;&#x25fc;逻辑访问尝试无效</span><span class="sxs-lookup"><span data-stu-id="31cea-550">&emsp;&#x25fc; Invalid logical access attempts</span></span>|
||<span data-ttu-id="31cea-551">&emsp;&#x25fc;特权帐户创建/修改</span><span class="sxs-lookup"><span data-stu-id="31cea-551">&emsp;&#x25fc; Privileged account creation / modification</span></span>|
||<span data-ttu-id="31cea-552">&emsp;&#x25fc;事件日志篡改</span><span class="sxs-lookup"><span data-stu-id="31cea-552">&emsp;&#x25fc; Event log tampering</span></span>|
||<span data-ttu-id="31cea-553">&emsp;&#x25fc;禁用安全工具;例如，反恶意软件或事件日志记录</span><span class="sxs-lookup"><span data-stu-id="31cea-553">&emsp;&#x25fc; Disabling of security tools; for example, Anti-Malware or event logging</span></span>|
||<span data-ttu-id="31cea-554">&emsp;&#x25fc;反恶意软件日志记录;例如，更新、恶意软件检测、扫描失败</span><span class="sxs-lookup"><span data-stu-id="31cea-554">&emsp;&#x25fc; Anti-Malware logging; for example, updates, malware detection, scan failures</span></span>|
||<span data-ttu-id="31cea-555">&emsp;&#x25fc; IDPS/WAF (（如果已) </span><span class="sxs-lookup"><span data-stu-id="31cea-555">&emsp;&#x25fc; IDPS/WAF events (if configured)</span></span>|
||<span data-ttu-id="31cea-556">事件日志 **必须** 包含以下信息：</span><span class="sxs-lookup"><span data-stu-id="31cea-556">­Event logs **MUST** include the following information:</span></span>|
||<span data-ttu-id="31cea-557">&emsp;&#x25fc;用户标识</span><span class="sxs-lookup"><span data-stu-id="31cea-557">&emsp;&#x25fc; User Identification</span></span> |
||<span data-ttu-id="31cea-558">&emsp;&#x25fc; 事件的类型</span><span class="sxs-lookup"><span data-stu-id="31cea-558">&emsp;&#x25fc; Type of event</span></span> |
||<span data-ttu-id="31cea-559">&emsp;&#x25fc;日期和时间</span><span class="sxs-lookup"><span data-stu-id="31cea-559">&emsp;&#x25fc; Date and time</span></span> |
||<span data-ttu-id="31cea-560">&emsp;&#x25fc;成功/失败指示器</span><span class="sxs-lookup"><span data-stu-id="31cea-560">&emsp;&#x25fc; Success/Failure indicator</span></span>|
||<span data-ttu-id="31cea-561">&emsp;&#x25fc;标签以标识受影响的系统</span><span class="sxs-lookup"><span data-stu-id="31cea-561">&emsp;&#x25fc; Label to identify the affected system</span></span> |
||<span data-ttu-id="31cea-562">必须跨 **所有** 范围内系统组件使用时间同步，以协助取证调查。</span><span class="sxs-lookup"><span data-stu-id="31cea-562">­Time-synchronization **MUST** be used across all in-scope system components to aid in forensic investigations.</span></span>|
||<span data-ttu-id="31cea-563">时间同步 **必须** 配置为使用同一主要 (和辅助（如果需要) 源）</span><span class="sxs-lookup"><span data-stu-id="31cea-563">Time-synchronization **MUST** be configured to utilize the same primary (and secondary if required) time source</span></span>|
||<span data-ttu-id="31cea-564">DMZ (中面向公众的系统) 必须将日志写入内部集中日志记录存储库。</span><span class="sxs-lookup"><span data-stu-id="31cea-564">­Public facing systems (systems within the DMZ) **MUST** write logs to an internal centralized logging repository.</span></span> <span data-ttu-id="31cea-565">集中日志记录存储库不能位于 DMZ 内。</span><span class="sxs-lookup"><span data-stu-id="31cea-565">The centralized logging repository must not be within the DMZ.</span></span>|
||<span data-ttu-id="31cea-566">必须保护 **审核** 线索，以确保威胁参与者无法更改日志数据。</span><span class="sxs-lookup"><span data-stu-id="31cea-566">­ Audit trails **MUST** be secured to ensure log data cannot be altered by a threat actor.</span></span> <span data-ttu-id="31cea-567">只能对授权人员访问集中日志记录存储库。</span><span class="sxs-lookup"><span data-stu-id="31cea-567">Access to the centralized logging repository must be limited to authorized personnel only.</span></span>|
||<span data-ttu-id="31cea-568">日志 **必须** 立即可用 30 天。</span><span class="sxs-lookup"><span data-stu-id="31cea-568">­ Logs **MUST** be immediately available for 30 days.</span></span> <span data-ttu-id="31cea-569">日志记录 **数据** 至少必须保留 90 天。</span><span class="sxs-lookup"><span data-stu-id="31cea-569">Logging data **MUST** be retained for a minimum of 90 days.</span></span>|
|<span data-ttu-id="31cea-570">**Reviewing**</span><span class="sxs-lookup"><span data-stu-id="31cea-570">**Reviewing**</span></span> |<span data-ttu-id="31cea-571">审核过程以及支持策略和过程 **必须满足** 以下要求：</span><span class="sxs-lookup"><span data-stu-id="31cea-571">Review processes as well as supporting policies and procedures **MUST** meet the following:</span></span>|
||<span data-ttu-id="31cea-572">&#x2713;执行每日日志检查或利用自动日志分析和警报技术查看来自所有范围内系统组件的事件，以确定任何潜在的安全事件。</span><span class="sxs-lookup"><span data-stu-id="31cea-572">&#x2713; Perform daily log reviews or utilize automated log analysis and alerting technology to review events from all in-scope system components to identify any potential security events.</span></span>|
||<span data-ttu-id="31cea-573">&#x2713;必须立即 **跟进潜在的安全** 事件。</span><span class="sxs-lookup"><span data-stu-id="31cea-573">&#x2713; Potential security events **MUST** be immediately followed up.</span></span>|
|<span data-ttu-id="31cea-574">**警报**</span><span class="sxs-lookup"><span data-stu-id="31cea-574">**Alerting**</span></span> |<span data-ttu-id="31cea-575">警报过程以及支持策略和过程 **必须满足** 以下要求：</span><span class="sxs-lookup"><span data-stu-id="31cea-575">Alerting processes as well as supporting policies and procedures **MUST** meet the following:</span></span> |
||<span data-ttu-id="31cea-576">&#x2713;记录的安全事件（对系统、操作或数据的安全造成风险）必须触发即时警报，例如 (列表或) ：</span><span class="sxs-lookup"><span data-stu-id="31cea-576">&#x2713; Logged security events that pose a risk to the security of your systems, operations or data MUST trigger an immediate alert, for example (not an exhaustive list):</span></span>|
||<span data-ttu-id="31cea-577">&emsp;&#x25fc;特权帐户创建/修改</span><span class="sxs-lookup"><span data-stu-id="31cea-577">&emsp;&#x25fc; Privilege account creation / modifications</span></span>|
||<span data-ttu-id="31cea-578">&emsp;&#x25fc;恶意软件事件</span><span class="sxs-lookup"><span data-stu-id="31cea-578">&emsp;&#x25fc; Malware events</span></span>|
||<span data-ttu-id="31cea-579">&emsp;&#x25fc;禁用安全工具</span><span class="sxs-lookup"><span data-stu-id="31cea-579">&emsp;&#x25fc; Disabling security tools</span></span>|
||<span data-ttu-id="31cea-580">&emsp;&#x25fc;事件日志篡改</span><span class="sxs-lookup"><span data-stu-id="31cea-580">&emsp;&#x25fc; Event log tampering</span></span>|
||<span data-ttu-id="31cea-581">&emsp;&#x25fc; IDPS/WAF (（如果已配置) </span><span class="sxs-lookup"><span data-stu-id="31cea-581">&emsp;&#x25fc; IDPS / WAF events (if configured)</span></span> |
||<span data-ttu-id="31cea-582">&#x2713; 24/7 (员工必须始终) 响应触发的警报。</span><span class="sxs-lookup"><span data-stu-id="31cea-582">&#x2713; Staff MUST always be available (24/7) to react to triggered alerts.</span></span>|
|<span data-ttu-id="31cea-583">**风险管理**</span><span class="sxs-lookup"><span data-stu-id="31cea-583">**Risk management**</span></span>|<span data-ttu-id="31cea-584">必须制定并执行风险评估方法，其中包括：</span><span class="sxs-lookup"><span data-stu-id="31cea-584">A risk-assessment methodology must be developed and conducted that includes the following:</span></span>|
||<span data-ttu-id="31cea-585">&#x2713;正式定义的过程。</span><span class="sxs-lookup"><span data-stu-id="31cea-585">&#x2713; A formally defined process.</span></span>|
||<span data-ttu-id="31cea-586">&#x2713;至少每年执行一次。</span><span class="sxs-lookup"><span data-stu-id="31cea-586">&#x2713; Performed at least annually.</span></span>|
||<span data-ttu-id="31cea-587">&#x2713;包括范围内环境中的所有资产。</span><span class="sxs-lookup"><span data-stu-id="31cea-587">&#x2713; Includes all assets within the in-scope environment.</span></span>|
||<span data-ttu-id="31cea-588">&#x2713;识别针对所有已包含资产的威胁和漏洞。</span><span class="sxs-lookup"><span data-stu-id="31cea-588">&#x2713; Identifies threats and vulnerabilities against all included assets.</span></span>|
||<span data-ttu-id="31cea-589">&#x2713; 包括使用已定义的影响和可能性矩阵。</span><span class="sxs-lookup"><span data-stu-id="31cea-589">&#x2713; Includes the use of defined impact and likelihood matrices.</span></span>|
||<span data-ttu-id="31cea-590">&#x2713;会导致创建风险注册和相应的风险处理计划。</span><span class="sxs-lookup"><span data-stu-id="31cea-590">&#x2713; Results in the creation of a risk register and corresponding risk treatment plan.</span></span>|
|<span data-ttu-id="31cea-591">**事件响应**</span><span class="sxs-lookup"><span data-stu-id="31cea-591">**Incident response**</span></span>|<span data-ttu-id="31cea-592">需要周密 **的事件响应计划** ， **并且至少** 必须包括：</span><span class="sxs-lookup"><span data-stu-id="31cea-592">A thorough incident response plan **IS** required and **MUST** include as a minimum:</span></span>|
||<span data-ttu-id="31cea-593">&#x2713;作用域内系统组件和应用程序的最低范围。</span><span class="sxs-lookup"><span data-stu-id="31cea-593">&#x2713; At a minimum, coverage of the in-scope systems components and applications.</span></span>|
||<span data-ttu-id="31cea-594">&#x2713;预期威胁模型的特定事件响应过程。</span><span class="sxs-lookup"><span data-stu-id="31cea-594">&#x2713; Specific incident response procedures for expected threat models.</span></span>|
||<span data-ttu-id="31cea-595">&#x2713;记录的通信过程，确保及时通知所有关键利益干系人以及任何相关外部机构，例如;付款品牌/收购者、监管机构 ([GDPR](#gdpr)) 符合强制报告要求。</span><span class="sxs-lookup"><span data-stu-id="31cea-595">&#x2713; Documented communications process, ensuring the timely notification of all key stakeholders and any relevant external bodies such as; payment brands/acquirers, regulatory bodies and supervisory authorities ([GDPR](#gdpr)) in line with mandated reporting requirements.</span></span>|
||<span data-ttu-id="31cea-596">&#x2713;事件响应根据所总结的经验、组织变更以及行业发展进行更新。</span><span class="sxs-lookup"><span data-stu-id="31cea-596">&#x2713; The incident response is updated based upon lessons learned, organizational changes and to incorporate industry developments.</span></span>|
||<span data-ttu-id="31cea-597">&#x2713;事件响应团队成员年度培训。</span><span class="sxs-lookup"><span data-stu-id="31cea-597">&#x2713; Annual training for members of the incident response team.</span></span>|

## <a name="data-handling-security-and-privacy"></a><span data-ttu-id="31cea-598">数据处理安全和隐私</span><span class="sxs-lookup"><span data-stu-id="31cea-598">Data Handling Security and Privacy</span></span>

<span data-ttu-id="31cea-599">应用程序用户、中间服务和 ISV 系统之间传输的数据需要通过支持最低 TLS v1.1 的 TLS 连接进行加密保护。*请参阅*[**附录 A。**](#appendix-a)</span><span class="sxs-lookup"><span data-stu-id="31cea-599">Data in transit between the application user, intermediary services, and ISV’s systems will be required to be protected by encryption through a TLS connection supporting a minimum of TLS v1.1.*See* [**Appendix A**](#appendix-a).</span></span>

<span data-ttu-id="31cea-600">在您的应用程序检索和存储 M365 数据的位置，您需要实现遵循附录 B 中定义的规范的 [**数据存储加密方案**](#appendix-a)。</span><span class="sxs-lookup"><span data-stu-id="31cea-600">Where your application retrieves and stores M365 data you will be required to implement a data storage encryption scheme that follows the specification as defined in [**Appendix B**](#appendix-a).</span></span>

### <a name="test-specification"></a><span data-ttu-id="31cea-601">测试规范</span><span class="sxs-lookup"><span data-stu-id="31cea-601">Test Specification</span></span>

|<span data-ttu-id="31cea-602">测试</span><span class="sxs-lookup"><span data-stu-id="31cea-602">Test</span></span> | <span data-ttu-id="31cea-603">控件</span><span class="sxs-lookup"><span data-stu-id="31cea-603">Controls</span></span> |
| -----------------------|-------------------------------- |
|<span data-ttu-id="31cea-604">**传输中的数据**</span><span class="sxs-lookup"><span data-stu-id="31cea-604">**Data in Transit**</span></span>| <span data-ttu-id="31cea-605">敏感数据的传输必须使用最低 TLS 1.1，附录 A 中所述的一些例外情况除外。</span><span class="sxs-lookup"><span data-stu-id="31cea-605">Transmission of sensitive data MUST use a minimum of TLS 1.1 with a few exceptions described in Appendix A.</span></span>|
||<span data-ttu-id="31cea-606">敏感数据的 **传输必须** 按照附录 B 中所述的加密配置文件进行适当加密。</span><span class="sxs-lookup"><span data-stu-id="31cea-606">Transmission of sensitive data **MUST** be suitably encrypted in line with encryption profiles described in Appendix B.</span></span>|
||<span data-ttu-id="31cea-607">必须禁用 TLS 压缩。</span><span class="sxs-lookup"><span data-stu-id="31cea-607">TLS compression must be disabled.</span></span>|
||<span data-ttu-id="31cea-608">HSTS (HTTP 严格传输) **必须** 配置为 >= 15552000</span><span class="sxs-lookup"><span data-stu-id="31cea-608">HSTS (HTTP Strict Transport Security) **MUST** be configured to >= 15552000</span></span>|
|<span data-ttu-id="31cea-609">**Rest 数据**</span><span class="sxs-lookup"><span data-stu-id="31cea-609">**Data at Rest**</span></span>| <span data-ttu-id="31cea-610">敏感数据存储 **必须** 按照附录 B 中所述的加密配置文件进行保护，这些配置文件涵盖加密、算法、密钥大小、哈希和消息身份验证的最低要求。</span><span class="sxs-lookup"><span data-stu-id="31cea-610">Sensitive data storage **MUST** be protected in line with the encryption profiles described in Appendix B covering minimum requirements of encryption, algorithms, key sizes, hashing and message authentication.</span></span>|
||<span data-ttu-id="31cea-611">必须记录所有存储的数据类型。</span><span class="sxs-lookup"><span data-stu-id="31cea-611">All stored data types MUST be documented.</span></span>|
|<span data-ttu-id="31cea-612">**数据保留和处置**</span><span class="sxs-lookup"><span data-stu-id="31cea-612">**Data Retention and Disposal**</span></span>|<span data-ttu-id="31cea-613">必须通过 **实施至少** 包括以下各项的数据保留和处置策略、过程来将敏感数据存储保持在最低程度：</span><span class="sxs-lookup"><span data-stu-id="31cea-613">Sensitive data storage **MUST** be kept to a minimum by implementing data retention and disposal policies, procedures and processes that minimally include:</span></span>|
||<span data-ttu-id="31cea-614">&#x2713;文档，将数据存储量和保留时间限制为法律、法规和/或业务要求所需的时间。</span><span class="sxs-lookup"><span data-stu-id="31cea-614">&#x2713; Document and limit data storage amount and retention time to that which is required for legal, regulatory, and/or business requirements.</span></span>|
||<span data-ttu-id="31cea-615">&#x2713;文档和部署流程，以在不再需要时安全地删除敏感数据，并符合已记录的策略。</span><span class="sxs-lookup"><span data-stu-id="31cea-615">&#x2713; Document and deploy processes for secure deletion of sensitive data when no longer needed, in-line with documented policies.</span></span>|
||<span data-ttu-id="31cea-616">&#x2713;文档并部署季度流程，以标识并安全删除超过定义的保留期的已存储敏感数据。</span><span class="sxs-lookup"><span data-stu-id="31cea-616">&#x2713; Document and deploy a quarterly process for identifying and securely deleting stored sensitive data that exceeds the defined retention period.</span></span>|
|<span data-ttu-id="31cea-617">**数据访问管理**</span><span class="sxs-lookup"><span data-stu-id="31cea-617">**Data Access Management**</span></span>|<span data-ttu-id="31cea-618">限制具有合法业务原因的用户的数据访问可帮助组织防止因经验不足或恶意错误处理敏感数据。</span><span class="sxs-lookup"><span data-stu-id="31cea-618">Limiting data access to those with a legitimate business reason helps organizations prevent mishandling of sensitive data through inexperience or malice.</span></span> <span data-ttu-id="31cea-619">应用/外接程序接收的敏感数据和加密密钥的访问需要经过记录的批准 (电子版或书面) ，供所有访问级别的授权方访问，并且必须包括演示该策略的已批准和验证权限列表，这些权限包含如下指定要求：</span><span class="sxs-lookup"><span data-stu-id="31cea-619">Sensitive data, received by the app/add-in and access to encryption keys requires documented approval (electronic or in writing) for authorized parties at all access levels to access and must include a listing of approved and verified privileges demonstrating the policy incorporates the specified requirements as follows:</span></span> |
||<span data-ttu-id="31cea-620">&#x2713;定义仅对专门需要此类特权访问的角色的访问需求和特权分配。</span><span class="sxs-lookup"><span data-stu-id="31cea-620">&#x2713; Defining access needs and privilege assignments only to roles that specifically require such privileged access.</span></span> |
||<span data-ttu-id="31cea-621">&#x2713;限制对执行工作职责所需的最小特权的访问。</span><span class="sxs-lookup"><span data-stu-id="31cea-621">&#x2713; Restricting access to the least privileges necessary to perform job responsibilities.</span></span>|
||<span data-ttu-id="31cea-622">&#x2713;确保所有使用 M365 数据的第三方都符合数据共享协议。</span><span class="sxs-lookup"><span data-stu-id="31cea-622">&#x2713; Ensure data sharing agreements are in place with all third-parties consuming M365 data.</span></span>|
|<span data-ttu-id="31cea-623">**GDPR**</span><span class="sxs-lookup"><span data-stu-id="31cea-623">**GDPR**</span></span>| <span data-ttu-id="31cea-624">作为 Microsoft 365 认证过程的一部分，你必须通过以下方法证明遵守 GDPR：</span><span class="sxs-lookup"><span data-stu-id="31cea-624">As part of the Microsoft 365 Certification process, you must demonstrate adherence to the GDPR, either by:</span></span>|
||<span data-ttu-id="31cea-625">&#x2713;由有经验的外部审核公司独立审查 GDPR 一致性。</span><span class="sxs-lookup"><span data-stu-id="31cea-625">&#x2713; Providing an independent review of the GDPR conformance by an experienced external audit company.</span></span> <span data-ttu-id="31cea-626">你可能需要提交报告进行审阅或允许分析员查看报告。</span><span class="sxs-lookup"><span data-stu-id="31cea-626">You will be required to submit the report for review or allow the analyst to view the report.</span></span> <span data-ttu-id="31cea-627">报告应提供足够详细的信息，以便不仅验证外部审核员的评估，而且还提供足以确保外部审核已确认符合 GDPR 的可信度。</span><span class="sxs-lookup"><span data-stu-id="31cea-627">The report should provide enough details to not only validate the external auditor’s assessment but also provide enough confidence that the external review has confirmed conformance to the GDPR.</span></span>|
||<span data-ttu-id="31cea-628">或</span><span class="sxs-lookup"><span data-stu-id="31cea-628">or</span></span>|
||<span data-ttu-id="31cea-629">&#x2713;提交进一步的证据以提供对数据隐私法律承诺的额外保证，如下所示：</span><span class="sxs-lookup"><span data-stu-id="31cea-629">&#x2713; Submitting further evidence to provide additional assurance of your commitment to data privacy laws, as follows:</span></span>|
||<span data-ttu-id="31cea-630">&#x25fc; A documented subject access request (SAR) process designed to meet the requests of customers and meet the30 day requirement of the GDPR.</span><span class="sxs-lookup"><span data-stu-id="31cea-630">&#x25fc; A documented subject access request (SAR) process designed to meet the requests of customers and meet the thirty-day requirement of the GDPR.</span></span> <span data-ttu-id="31cea-631">建议提供足够的数据发现工具，以确保在这些时间范围内实现 SAR。</span><span class="sxs-lookup"><span data-stu-id="31cea-631">It is recommended that adequate data discovery tooling is in place to ensure a SAR is fulfilled within these time frames.</span></span> <span data-ttu-id="31cea-632">**注意** ：在未使用这些工具的地方，需要演示工作原理，并演示流程如何保证发现所有数据主体的信息。</span><span class="sxs-lookup"><span data-stu-id="31cea-632">**Note** : Where these tools are not used, you will need to demonstrate how this works and demonstrate how the processes are able to guarantee discovery of all data subject’s information.</span></span>|
||<span data-ttu-id="31cea-633">&#x25fc;隐私声明必须存在于网站上，并包含以下信息：</span><span class="sxs-lookup"><span data-stu-id="31cea-633">&#x25fc;Privacy Notices must be present on the website and contain the following information:</span></span>
||
||<span data-ttu-id="31cea-634">如果独立 GDPR 报告不可用，则必须将以下内容作为 M365 认证评估的一部分进行审阅：</span><span class="sxs-lookup"><span data-stu-id="31cea-634">Where an independent GDPR report isn’t available, the following must be in place to be reviewed as part of the M365 Certification assessment:</span></span> |
||<span data-ttu-id="31cea-635">&#x2713; A documented subject access request (SAR) process designed to meet the requests of customers and meet the30 day requirement of the GDPR.</span><span class="sxs-lookup"><span data-stu-id="31cea-635">&#x2713; A documented subject access request (SAR) process designed to meet the requests of customers and meet the thirty-day requirement of the GDPR.</span></span>  <span data-ttu-id="31cea-636">建议提供足够的数据发现工具来确保在这些不使用这些工具的时间范围内实现 SAR，你将需要演示这一点的工作原理，并演示这些过程如何保证发现所有数据主体的信息。</span><span class="sxs-lookup"><span data-stu-id="31cea-636">It is recommended that adequate data discovery tooling is in place to ensure a SAR is fulfilled within these time frames, where these tools aren't used, you will need to demonstrate how this works and demonstrate how the processes are able to guarantee discovery of all data subject’s information.</span></span>|
||<span data-ttu-id="31cea-637">&#x2713;隐私声明必须存在于网站上，并包含以下信息：</span><span class="sxs-lookup"><span data-stu-id="31cea-637">&#x2713; Privacy Notices must be present on the website and contain the following information:</span></span>|
||<span data-ttu-id="31cea-638">&emsp;&emsp;&#x25a1;组织联系人详细信息。</span><span class="sxs-lookup"><span data-stu-id="31cea-638">&emsp;&emsp;&#x25a1; Organizations contact details.</span></span>|
||<span data-ttu-id="31cea-639">&emsp;&emsp;&#x25a1;正在处理的个人数据的类型。</span><span class="sxs-lookup"><span data-stu-id="31cea-639">&emsp;&emsp;&#x25a1; Type of personal data being processed.</span></span>|
||<span data-ttu-id="31cea-640">&emsp;&emsp;&#x25a1;第 6 条 (*个人数据的*) 。</span><span class="sxs-lookup"><span data-stu-id="31cea-640">&emsp;&emsp;&#x25a1; Lawfulness of processing personal data (*Article 6*).</span></span>|
||<span data-ttu-id="31cea-641">&emsp;&emsp;&#x25a1;数据主体权利的详细信息：</span><span class="sxs-lookup"><span data-stu-id="31cea-641">&emsp;&emsp;&#x25a1; Details of data subject's rights:</span></span>|
||<span data-ttu-id="31cea-642">&emsp;&emsp;&#x25a1;第 *13 (14* 条通知) 。</span><span class="sxs-lookup"><span data-stu-id="31cea-642">&emsp;&emsp;&#x25a1; Right to be informed (*Articles13 and 14*).</span></span>
||<span data-ttu-id="31cea-643">&emsp;&emsp;&#x25a1;第 *15* 条 (主体的) 。</span><span class="sxs-lookup"><span data-stu-id="31cea-643">&emsp;&emsp;&#x25a1; Right of access by the data subject (*Article 15*).</span></span>|
||<span data-ttu-id="31cea-644">&emsp;&emsp;&#x25a1;第 *16* 条 (纠正) 。</span><span class="sxs-lookup"><span data-stu-id="31cea-644">&emsp;&emsp;&#x25a1; Right of rectification (*Article 16*).</span></span>|
||<span data-ttu-id="31cea-645">&emsp;&emsp;&#x25a1;第 *17* 条 (清除) 。</span><span class="sxs-lookup"><span data-stu-id="31cea-645">&emsp;&emsp;&#x25a1; Right to erasure (*Article 17*).</span></span>|
||<span data-ttu-id="31cea-646">&emsp;&emsp;&#x25a1;第 *18* 条 (限制处理) 。</span><span class="sxs-lookup"><span data-stu-id="31cea-646">&emsp;&emsp;&#x25a1; Right to restriction of processing (*Article 18*).</span></span>|
||<span data-ttu-id="31cea-647">&emsp;&emsp;&#x25a1;第 *20 条 (数据可移植* 性) 。</span><span class="sxs-lookup"><span data-stu-id="31cea-647">&emsp;&emsp;&#x25a1; Right to data portability (*Article 20*).</span></span>|
||<span data-ttu-id="31cea-648">&emsp;&emsp;&#x25a1;第 *21* 条 (对象) 。</span><span class="sxs-lookup"><span data-stu-id="31cea-648">&emsp;&emsp;&#x25a1; Right to object (*Article 21*).</span></span>|
||<span data-ttu-id="31cea-649">&emsp;&emsp;&#x25a1;与自动决策标记相关的权限，包括 (*第 22* 条) 。</span><span class="sxs-lookup"><span data-stu-id="31cea-649">&emsp;&emsp;&#x25a1; Rights in relation to automated decision-marking, including profiling (*Article 22*).</span></span>|
||<span data-ttu-id="31cea-650">&#x2713;第三方共享信息必须签署协议，以确保数据主体数据的处理符合数据隐私法。</span><span class="sxs-lookup"><span data-stu-id="31cea-650">&#x2713; Information sharing with third-parties must have agreements in place to ensure processing of data subject’s data are in line with data privacy laws.</span></span>|

## <a name="optional-external-compliance-frameworks-review"></a><span data-ttu-id="31cea-651">可选的外部合规性框架审查</span><span class="sxs-lookup"><span data-stu-id="31cea-651">Optional External Compliance Frameworks Review</span></span>

<span data-ttu-id="31cea-652">如果外部安全框架已包含在发布者证明中，认证分析师将需要在 Microsoft 365 认证评估中检查这些安全合规性框架的有效性。</span><span class="sxs-lookup"><span data-stu-id="31cea-652">If external security frameworks have been included within the Publisher Attestation, certification analysts will need to check the validity of those security compliance frameworks as part of the Microsoft 365 Certification assessment.</span></span>
<span data-ttu-id="31cea-653">以下受支持的外部安全合规性框架的证据包括：</span><span class="sxs-lookup"><span data-stu-id="31cea-653">Evidence for the following supported external security compliance frameworks include:</span></span>

* <span data-ttu-id="31cea-654">[ISMS](#isms) / [IEC](#iec) - IS0/IEC 27001 规范</span><span class="sxs-lookup"><span data-stu-id="31cea-654">[ISMS](#isms)/ [IEC](#iec) - IS0/IEC 27001 specification</span></span></h5>
* [<span data-ttu-id="31cea-655">PCI DSS</span><span class="sxs-lookup"><span data-stu-id="31cea-655">PCI DSS</span></span>](#pci-dss)
* [<span data-ttu-id="31cea-656">SOC 2</span><span class="sxs-lookup"><span data-stu-id="31cea-656">SOC 2</span></span>](#soc-2)

<span data-ttu-id="31cea-657">合规性证据部分中 [确定](#compliance-evidence) 的文档将用于执行此审查。</span><span class="sxs-lookup"><span data-stu-id="31cea-657">Documentation identified within the [Compliance Evidence](#compliance-evidence) section will be used to perform this review.</span></span>

### <a name="test-specifications"></a><span data-ttu-id="31cea-658">测试规范</span><span class="sxs-lookup"><span data-stu-id="31cea-658">Test Specifications</span></span>

<span data-ttu-id="31cea-659">&#x2713;应用程序/外接程序支持环境和任何支持业务流程必须包含在任何受支持的外部安全合规性框架范围内，并且必须在提供的文档中清楚地说明。</span><span class="sxs-lookup"><span data-stu-id="31cea-659">&#x2713; The App/Add-in supporting environment **AND** any supporting business processes **MUST** be included within the scope of any supported external security compliance frameworks and must be clearly indicated in supplied documentation.</span></span>

<span data-ttu-id="31cea-660">&#x2713;支持的外部安全合规性框架必须是最新的，即过去 12 个月内 (或 15months 内（如果当前正在进行重新评估，并且可在) 中提供证据）。</span><span class="sxs-lookup"><span data-stu-id="31cea-660">&#x2713; Supported external security compliance frameworks **MUST** be current, i.e. within the past 12 months (or within 15months if the re-assessment is currently being carried out and evidence can be provided).</span></span>

<span data-ttu-id="31cea-661">&#x2713;支持的外部安全合规性 **框架必须由经** 认证的独立公司执行。</span><span class="sxs-lookup"><span data-stu-id="31cea-661">&#x2713; Supported external security compliance frameworks **MUST** be carried out by an independent accredited company.</span></span>

## <a name="appendix-a"></a><span data-ttu-id="31cea-662">附录 A</span><span class="sxs-lookup"><span data-stu-id="31cea-662">Appendix A</span></span>

### <a name="tls-profile-configuration-requirements"></a><span data-ttu-id="31cea-663">TLS 配置文件配置要求</span><span class="sxs-lookup"><span data-stu-id="31cea-663">TLS Profile configuration requirements</span></span>

<span data-ttu-id="31cea-664">所有网络流量（无论是在虚拟网络、云服务还是数据中心内）都必须使用最低 TLS v1.1 进行保护 (建议使用 TLS v1.2+) 或其他适用的协议。</span><span class="sxs-lookup"><span data-stu-id="31cea-664">All network traffic, whether within a virtual network, cloud service, or a data center, must be protected with a minimum of TLS v1.1 (TLS v1.2+ is recommended) or other applicable protocol.</span></span> <span data-ttu-id="31cea-665">此要求的例外情况是：</span><span class="sxs-lookup"><span data-stu-id="31cea-665">Exceptions to this requirement are:</span></span>

* <span data-ttu-id="31cea-666">**HTTP 到 HTTPS 重定向**。</span><span class="sxs-lookup"><span data-stu-id="31cea-666">**HTTP-to-HTTPS redirect**.</span></span> <span data-ttu-id="31cea-667">应用可以通过 HTTP 响应，将客户端重定向到 HTTPS，但响应不得包含任何敏感数据 (Cookie、标头、内容) 。</span><span class="sxs-lookup"><span data-stu-id="31cea-667">Your app can respond over HTTP to redirect clients to HTTPS, but the response must not contain any sensitive data (cookies, headers, content).</span></span> <span data-ttu-id="31cea-668">除了重定向到 HTTPS 和响应运行状况探测器外，不允许其他 HTTP 响应。</span><span class="sxs-lookup"><span data-stu-id="31cea-668">No other HTTP responses other than redirects to HTTPS and responding to health probes are allowed.</span></span> <span data-ttu-id="31cea-669">请参阅下文。</span><span class="sxs-lookup"><span data-stu-id="31cea-669">See below.</span></span>
* <span data-ttu-id="31cea-670">**运行状况探测器**。</span><span class="sxs-lookup"><span data-stu-id="31cea-670">**Health probes**.</span></span> <span data-ttu-id="31cea-671">只有当检查方不支持 **HTTPS** 运行状况探测器时，你的应用才能通过 HTTP 响应运行状况探测器。</span><span class="sxs-lookup"><span data-stu-id="31cea-671">Your app can respond to health probes over HTTP **only if** HTTPS health probes are not supported by the checking party.</span></span>
* <span data-ttu-id="31cea-672">**证书访问**。</span><span class="sxs-lookup"><span data-stu-id="31cea-672">**Certificate access**.</span></span> <span data-ttu-id="31cea-673">允许通过 HTTP 访问 CRL、OCSP 和 AIA 终结点，以便进行证书验证和吊销检查。</span><span class="sxs-lookup"><span data-stu-id="31cea-673">Access to CRL, OCSP, and AIA endpoints for the purposes of certificate validation and revocation checking is allowed over HTTP.</span></span>
* <span data-ttu-id="31cea-674">**本地通信**。</span><span class="sxs-lookup"><span data-stu-id="31cea-674">**Local communications**.</span></span> <span data-ttu-id="31cea-675">你的应用可以使用 HTTP (或其他非受保护协议) 不离开操作系统的通信，例如 e.</span><span class="sxs-lookup"><span data-stu-id="31cea-675">Your app can use HTTP (or other non-protected protocols) for communications that do not leave the operating system, e.</span></span> <span data-ttu-id="31cea-676">g.</span><span class="sxs-lookup"><span data-stu-id="31cea-676">g.</span></span> <span data-ttu-id="31cea-677">连接到 localhost 上公开的 Web 服务器终结点。</span><span class="sxs-lookup"><span data-stu-id="31cea-677">connecting to a web server endpoint exposed on localhost.</span></span>

<span data-ttu-id="31cea-678">必须 **禁用** TLS 压缩。</span><span class="sxs-lookup"><span data-stu-id="31cea-678">TLS Compression **MUST** be disabled.</span></span>

## <a name="appendix-b"></a><span data-ttu-id="31cea-679">附录 B</span><span class="sxs-lookup"><span data-stu-id="31cea-679">Appendix B</span></span>

### <a name="encryption-profile-configuration-requirements"></a><span data-ttu-id="31cea-680">加密配置文件配置要求</span><span class="sxs-lookup"><span data-stu-id="31cea-680">Encryption Profile Configuration Requirements</span></span>

<span data-ttu-id="31cea-681">仅允许加密基元和参数，如下所示：</span><span class="sxs-lookup"><span data-stu-id="31cea-681">Only cryptographic primitives and parameters are permitted as follows:</span></span>

### <a name="symmetric-cryptography"></a><span data-ttu-id="31cea-682">对称加密</span><span class="sxs-lookup"><span data-stu-id="31cea-682">Symmetric cryptography</span></span>

<span data-ttu-id="31cea-683">**加密**</span><span class="sxs-lookup"><span data-stu-id="31cea-683">**Encryption**</span></span>

<span data-ttu-id="31cea-684">&emsp;&#x2713;仅允许使用 AES、BitLocker、一线或 TDES。</span><span class="sxs-lookup"><span data-stu-id="31cea-684">&emsp;&#x2713; Only AES, BitLocker, Blowfish or TDES are allowed.</span></span> <span data-ttu-id="31cea-685">任何受支持的密钥长度 >=128 都允许使用 (128、192 和 256 位) 并且建议使用 (256 位密钥) 。</span><span class="sxs-lookup"><span data-stu-id="31cea-685">Any of the supported key lengths >=128 are allowed (128, 192, and 256 bits) and may be used (256-bit keys are recommended).</span></span>

<span data-ttu-id="31cea-686">&emsp;&#x2713;仅允许 CBC 模式。</span><span class="sxs-lookup"><span data-stu-id="31cea-686">&emsp;&#x2713; Only CBC mode is allowed.</span></span> <span data-ttu-id="31cea-687">每个加密操作必须使用新的、随机生成的初始化矢量 (IV) 。</span><span class="sxs-lookup"><span data-stu-id="31cea-687">Every encryption operation must use a fresh, randomly generated initialization vector (IV).</span></span>

<span data-ttu-id="31cea-688">&emsp;&#x2713;不允许使用流密码（如 RC4）。 </span><span class="sxs-lookup"><span data-stu-id="31cea-688">&emsp;&#x2713; Use of stream ciphers, such as RC4, **IS NOT** allowed.</span></span>

<span data-ttu-id="31cea-689">**哈希函数**</span><span class="sxs-lookup"><span data-stu-id="31cea-689">**Hash functions**</span></span>

<span data-ttu-id="31cea-690">&emsp;&#x2713;所有新代码都必须使用 SHA-256、SHA-384 或 SHA-512 (统称为 SHA-2) 。</span><span class="sxs-lookup"><span data-stu-id="31cea-690">&emsp;&#x2713; All new code must use SHA-256, SHA-384, or SHA-512 (collectively referred to as SHA-2).</span></span> <span data-ttu-id="31cea-691">输出可能会被截断为不小于 128 位</span><span class="sxs-lookup"><span data-stu-id="31cea-691">Output may be truncated to no less than 128 bits</span></span>

<span data-ttu-id="31cea-692">&emsp;&#x2713; SHA-1 可能仅用于兼容性原因。</span><span class="sxs-lookup"><span data-stu-id="31cea-692">&emsp;&#x2713; SHA-1 may only be used for compatibility reasons.</span></span>

<span data-ttu-id="31cea-693">&emsp;&#x2713; MD5、MD4、MD2 和其他哈希函数，即使对于非加密应用程序，也不允许使用。</span><span class="sxs-lookup"><span data-stu-id="31cea-693">&emsp;&#x2713; Use of MD5, MD4, MD2 and other hash functions IS NOT allowed, even for non-cryptographic applications.</span></span>

<span data-ttu-id="31cea-694">**邮件身份验证**</span><span class="sxs-lookup"><span data-stu-id="31cea-694">**Message authentication**</span></span>

<span data-ttu-id="31cea-695">&emsp;&#x2713;所有新代码都必须将 HMAC 与批准的哈希函数之一一使用。</span><span class="sxs-lookup"><span data-stu-id="31cea-695">&emsp;&#x2713; All new code MUST use HMAC with one of the approved hash functions.</span></span> <span data-ttu-id="31cea-696">HMAC 的输出可能会被截断为不小于 128 位。</span><span class="sxs-lookup"><span data-stu-id="31cea-696">Output of HMAC may be truncated to no less than 128 bits.</span></span>

<span data-ttu-id="31cea-697">&emsp;&#x2713; HMAC-SHA1 可能仅用于兼容性原因。</span><span class="sxs-lookup"><span data-stu-id="31cea-697">&emsp;&#x2713; HMAC-SHA1 may only be used for compatibility reasons.</span></span>

<span data-ttu-id="31cea-698">&emsp;&#x2713; HMAC 密钥必须至少为 128 位。</span><span class="sxs-lookup"><span data-stu-id="31cea-698">&emsp;&#x2713; HMAC key MUST be at least 128 bits.</span></span> <span data-ttu-id="31cea-699">建议使用 256 位密钥。</span><span class="sxs-lookup"><span data-stu-id="31cea-699">256-bit keys are recommended.</span></span>

### <a name="asymmetric-algorithms"></a><span data-ttu-id="31cea-700">非对称算法</span><span class="sxs-lookup"><span data-stu-id="31cea-700">Asymmetric algorithms</span></span>

<span data-ttu-id="31cea-701">**加密**</span><span class="sxs-lookup"><span data-stu-id="31cea-701">**Encryption**</span></span>

<span data-ttu-id="31cea-702">&emsp;&#x2713; RSA。</span><span class="sxs-lookup"><span data-stu-id="31cea-702">&emsp;&#x2713; RSA is allowed.</span></span> <span data-ttu-id="31cea-703">Key **必须至少** 为 2048 位，并且必须使用 OAEP 填充。</span><span class="sxs-lookup"><span data-stu-id="31cea-703">Key **MUST** be at least 2048 bits and OAEP padding must be used.</span></span> <span data-ttu-id="31cea-704">仅出于兼容性原因才允许使用 PKCS 填充。</span><span class="sxs-lookup"><span data-stu-id="31cea-704">Use of PKCS padding only allowed for compatibility reasons.</span></span>

<span data-ttu-id="31cea-705">**Signatures**</span><span class="sxs-lookup"><span data-stu-id="31cea-705">**Signatures**</span></span>

<span data-ttu-id="31cea-706">&emsp;&#x2713; RSA。</span><span class="sxs-lookup"><span data-stu-id="31cea-706">&emsp;&#x2713; RSA is allowed.</span></span> <span data-ttu-id="31cea-707">Key **必须至少** 为 2048 位，并且必须使用 PSS 填充。</span><span class="sxs-lookup"><span data-stu-id="31cea-707">Key **MUST** be at least 2048 bits and PSS padding must be used.</span></span> <span data-ttu-id="31cea-708">仅出于兼容性原因才允许使用 PKCS 填充。</span><span class="sxs-lookup"><span data-stu-id="31cea-708">Use of PKCS padding only allowed for compatibility reasons.</span></span>

<span data-ttu-id="31cea-709">&emsp;&#x2713;ECDSA。</span><span class="sxs-lookup"><span data-stu-id="31cea-709">&emsp;&#x2713;ECDSA is allowed.</span></span> <span data-ttu-id="31cea-710">Key **必须至少** 为 256 位。</span><span class="sxs-lookup"><span data-stu-id="31cea-710">Key **MUST** be at least 256 bits.</span></span> <span data-ttu-id="31cea-711">必须使用 NIST P-256、P-384 或 P-521 曲线。</span><span class="sxs-lookup"><span data-stu-id="31cea-711">NIST P-256, P-384 or P-521 curve must be used.</span></span>

<span data-ttu-id="31cea-712">**密钥交换**</span><span class="sxs-lookup"><span data-stu-id="31cea-712">**Key Exchange**</span></span>

<span data-ttu-id="31cea-713">&emsp;&#x2713; ECDH。</span><span class="sxs-lookup"><span data-stu-id="31cea-713">&emsp;&#x2713; ECDH is allowed.</span></span> <span data-ttu-id="31cea-714">Key **必须至少** 为 256 位。</span><span class="sxs-lookup"><span data-stu-id="31cea-714">Key **MUST** be at least 256 bits.</span></span> <span data-ttu-id="31cea-715">必须使用 NIST P-256、P-384 或 P-521 曲线。</span><span class="sxs-lookup"><span data-stu-id="31cea-715">NIST P-256, P-384 or P-521 curve must be used.</span></span>

<span data-ttu-id="31cea-716">&emsp;&#x2713; ECDH。</span><span class="sxs-lookup"><span data-stu-id="31cea-716">&emsp;&#x2713; ECDH is allowed.</span></span> <span data-ttu-id="31cea-717">Key **必须至少** 为 256 位。</span><span class="sxs-lookup"><span data-stu-id="31cea-717">Key **MUST** be at least 256 bits.</span></span> <span data-ttu-id="31cea-718">必须使用 NIST P-256、P-384 或 P-521 曲线。</span><span class="sxs-lookup"><span data-stu-id="31cea-718">NIST P-256, P-384 or P-521 curve must be used.</span></span>

## <a name="appendix-c"></a><span data-ttu-id="31cea-719">附录 C</span><span class="sxs-lookup"><span data-stu-id="31cea-719">Appendix C</span></span>

### <a name="evidence-collection--delta-for-iso-27001"></a><span data-ttu-id="31cea-720">Evidence Collection – ISO 27001 的 Delta</span><span class="sxs-lookup"><span data-stu-id="31cea-720">Evidence Collection – Delta for ISO 27001</span></span>

<span data-ttu-id="31cea-721">如果已获得 ISO27001 合规性，则以下增量的 (差距) ISO 27001 未完全覆盖，至少需要作为此 Microsoft 365 认证的一部分进行审核。</span><span class="sxs-lookup"><span data-stu-id="31cea-721">Where you have already attained ISO27001 compliance, the following delta’s (gaps) not wholly covered by ISO 27001 will, at a minimum, need to be reviewed as part of this Microsoft 365 Certification.</span></span>

> [!NOTE]
> <span data-ttu-id="31cea-722">作为 Microsoft 365 认证评估的一部分，认证分析师将确定任何映射的 ISO 27001 控制措施是否未作为 ISO 27001 评估的一部分包含在内，并可能决定对发现包含的控制措施进行示例验证，以提供进一步保证。</span><span class="sxs-lookup"><span data-stu-id="31cea-722">As part of your Microsoft 365 Certification assessment, the certification analyst will determine if any of the mapped ISO 27001 controls were not included as part of the ISO 27001 assessment and may also decide to sample controls that were found to be included to provide further assurance.</span></span> <span data-ttu-id="31cea-723">ISO 27001 中缺少的任何要求都需要包含在 Microsoft 365 认证评估活动中。</span><span class="sxs-lookup"><span data-stu-id="31cea-723">Any requirements missing from the ISO 27001 will need to be included within your Microsoft 365 Certification assessment activities.</span></span>

<span data-ttu-id="31cea-724">**恶意软件保护 – 防病毒**</span><span class="sxs-lookup"><span data-stu-id="31cea-724">**Malware Protection – Anti Virus**</span></span>

<span data-ttu-id="31cea-725">如果已使用应用程序控制对恶意软件进行保护，且在 ISO 27001 报告中进行了证明，则无需进一步调查。</span><span class="sxs-lookup"><span data-stu-id="31cea-725">If malware protection is in place using application control and is attested to within ISO 27001 Report no further investigation is necessary.</span></span> <span data-ttu-id="31cea-726">如果没有应用程序控制，认证分析师将需要识别和评估应用程序控制机制的证据，以防止恶意软件在环境中触发。</span><span class="sxs-lookup"><span data-stu-id="31cea-726">If no application control is in place, certification analysts will need to identify and assess evidence of application control mechanisms to prevent detonation of malware within the environment.</span></span> <span data-ttu-id="31cea-727">这将要求您：</span><span class="sxs-lookup"><span data-stu-id="31cea-727">This will require you to:</span></span>

* <span data-ttu-id="31cea-728">演示防病毒软件正在所有采样的系统组件上运行。</span><span class="sxs-lookup"><span data-stu-id="31cea-728">Demonstrate that anti-virus software is running across all sampled system components.</span></span>

* <span data-ttu-id="31cea-729">演示跨所有采样的系统组件配置了防病毒功能，以自动阻止恶意软件、隔离&警报或发出警报。</span><span class="sxs-lookup"><span data-stu-id="31cea-729">Demonstrate that anti-virus is configured across all sampled system components to either automatically block malware, to quarantine & alert or to alert.</span></span>

* <span data-ttu-id="31cea-730">防病毒软件 **必须配置为** 记录所有活动。</span><span class="sxs-lookup"><span data-stu-id="31cea-730">Anti-virus software **MUST** be configured to log all activities.</span></span>

<span data-ttu-id="31cea-731">**修补程序管理 – 修补**</span><span class="sxs-lookup"><span data-stu-id="31cea-731">**Patch Management – Patching**</span></span>

<span data-ttu-id="31cea-732">由于 ISO 27001 审核未专门评估此类别，因此将需要：</span><span class="sxs-lookup"><span data-stu-id="31cea-732">As ISO 27001 audits do not specifically assess this category, this will require you to:</span></span>

* <span data-ttu-id="31cea-733">供应商不再支持的软件组件和 **操作系统不得在** 环境中使用。</span><span class="sxs-lookup"><span data-stu-id="31cea-733">Software components and operating systems no longer supported by the vendor **MUST** not be used within the environment.</span></span> <span data-ttu-id="31cea-734">必须制定支持策略，以确保将不受支持的软件组件/操作系统从环境中删除，并且必须制定一个流程来确定软件组件何时结束使用</span><span class="sxs-lookup"><span data-stu-id="31cea-734">Supporting policies MUST be in place to ensure unsupported software components / operating systems will be removed from the environment and a process to identify when software components go end-of-life must be in place</span></span>

<span data-ttu-id="31cea-735">**漏洞扫描**</span><span class="sxs-lookup"><span data-stu-id="31cea-735">**Vulnerability Scanning**</span></span>  

<span data-ttu-id="31cea-736">由于 ISO 27001 审核未专门评估此类别，因此将需要：</span><span class="sxs-lookup"><span data-stu-id="31cea-736">As ISO 27001 audits do not specifically assess this category, this will require you to:</span></span>

* <span data-ttu-id="31cea-737">证明执行季度内部和外部漏洞扫描。</span><span class="sxs-lookup"><span data-stu-id="31cea-737">Demonstrate that quarterly internal and external vulnerability scanning is conducted.</span></span>

* <span data-ttu-id="31cea-738">确认支持文档已根据风险级别和规范进行漏洞修正，如下所示：</span><span class="sxs-lookup"><span data-stu-id="31cea-738">Confirm supporting documentation is in place for vulnerability remediation based on risk ranking and in line with the specification as follows:</span></span>
 
 <span data-ttu-id="31cea-739">&#x2713;解决与内部扫描的风险分级一致的所有严重和高风险问题。</span><span class="sxs-lookup"><span data-stu-id="31cea-739">&#x2713; Fix all Critical and Highs risk issues in-line with the risk ranking for Internal scanning.</span></span>
 
 <span data-ttu-id="31cea-740">&#x2713;外部扫描的风险级别，解决所有关键、高和中等风险问题。</span><span class="sxs-lookup"><span data-stu-id="31cea-740">&#x2713; Fix all Critical, Highs and Medium risk issues in-line with the risk ranking for external scanning.</span></span>
 
 <span data-ttu-id="31cea-741">&#x2713;演示修正是按照记录漏洞修正策略进行。</span><span class="sxs-lookup"><span data-stu-id="31cea-741">&#x2713; Demonstrate that remediation is conducted in-line with the documented vulnerability remediation policy.</span></span>

<span data-ttu-id="31cea-742">**防火墙 – 防火墙 (或等效技术)**</span><span class="sxs-lookup"><span data-stu-id="31cea-742">**Firewall – Firewalls (or equivalent technologies)**</span></span>

<span data-ttu-id="31cea-743">由于 ISO 27001 审核未专门评估此类别，因此将需要：</span><span class="sxs-lookup"><span data-stu-id="31cea-743">As ISO 27001 audits do not specifically assess this category, this will require you to:</span></span>

* <span data-ttu-id="31cea-744">演示防火墙安装在作用域内环境的边界上。</span><span class="sxs-lookup"><span data-stu-id="31cea-744">Demonstrate that firewalls are installed on the boundary of the in-scope environment.</span></span>

* <span data-ttu-id="31cea-745">演示防火墙安装在 DMZ 和受信任的网络之间。</span><span class="sxs-lookup"><span data-stu-id="31cea-745">Demonstrate that firewalls are installed between the DMZ and trusted networks.</span></span>

*   <span data-ttu-id="31cea-746">演示所有公共访问在 DMZ 中终止。</span><span class="sxs-lookup"><span data-stu-id="31cea-746">Demonstrate that all public access terminates in the DMZ.</span></span>

*   <span data-ttu-id="31cea-747">演示在安装到实时环境之前更改了默认管理凭据。</span><span class="sxs-lookup"><span data-stu-id="31cea-747">Demonstrate that default administrative credentials are changed prior to installation into the live environment.</span></span>

*   <span data-ttu-id="31cea-748">演示所有允许通过防火墙 (流量) 通过授权过程，这导致记录具有业务理由的所有流量。</span><span class="sxs-lookup"><span data-stu-id="31cea-748">Demonstrate that all permitted traffic through the firewall(s) goes through an authorization process which results in the documentation of all traffic with a business justification.</span></span>

*   <span data-ttu-id="31cea-749">演示所有防火墙均配置为丢弃未明确定义的流量。</span><span class="sxs-lookup"><span data-stu-id="31cea-749">Demonstrate that all firewalls are configured to drop traffic not explicitly defined.</span></span>

*   <span data-ttu-id="31cea-750">演示防火墙仅支持所有非控制台管理界面上的强加密。</span><span class="sxs-lookup"><span data-stu-id="31cea-750">Demonstrate that firewalls support only strong cryptography on all non-console administrative interfaces.</span></span>

*   <span data-ttu-id="31cea-751">演示向 Internet 公开的防火墙的非控制台管理接口支持 MFA。</span><span class="sxs-lookup"><span data-stu-id="31cea-751">Demonstrate that firewall's non-console administrative interfaces exposed to the Internet support MFA.</span></span>

*   <span data-ttu-id="31cea-752">证明防火墙规则评审至少每 6 个月执行一次</span><span class="sxs-lookup"><span data-stu-id="31cea-752">Demonstrate that firewall rule reviews are conducted at least every 6 months</span></span>

<span data-ttu-id="31cea-753">**防火墙 – WAF (Web 应用程序)**</span><span class="sxs-lookup"><span data-stu-id="31cea-753">**Firewall – Web Application Firewalls (WAF)**</span></span>  

<span data-ttu-id="31cea-754">如果部署 WAF 以帮助防范 Web 应用程序威胁和应用程序可能暴露给的漏洞，将提供额外的信用。</span><span class="sxs-lookup"><span data-stu-id="31cea-754">Additional credit will be provided if a WAF is deployed to help protect against the myriad of web application threats and vulnerabilities that the application can be exposed to.</span></span> <span data-ttu-id="31cea-755">当存在 WAF 或类似项时，这将需要你：</span><span class="sxs-lookup"><span data-stu-id="31cea-755">When a WAF or similar is present, this will require you to:</span></span>

* <span data-ttu-id="31cea-756">演示 WAF 在主动防御模式下配置，或通过警报进行更多监视。</span><span class="sxs-lookup"><span data-stu-id="31cea-756">Demonstrate the WAF is configured in active defense mode or monitoring more with alerting.</span></span>

* <span data-ttu-id="31cea-757">演示 WAF 配置为支持 SSL 卸载。</span><span class="sxs-lookup"><span data-stu-id="31cea-757">Demonstrate the WAF is configured to support SSL Offloading.</span></span>

* <span data-ttu-id="31cea-758">根据 OWASP 核心规则集 (3.0 或 3.1) 配置，以抵御以下大多数攻击类型：</span><span class="sxs-lookup"><span data-stu-id="31cea-758">Is configured as per the OWASP Core Rule Set (3.0 or 3.1) to protect against most of the following attack types:</span></span>

<span data-ttu-id="31cea-759">&#x2713;协议和编码问题。</span><span class="sxs-lookup"><span data-stu-id="31cea-759">&#x2713; Protocol and encoding issues.</span></span>

<span data-ttu-id="31cea-760">&#x2713;标头注入、请求拆分和响应拆分。</span><span class="sxs-lookup"><span data-stu-id="31cea-760">&#x2713; Header injection, request smuggling, and response splitting.</span></span>

<span data-ttu-id="31cea-761">&#x2713;文件和路径遍历攻击。</span><span class="sxs-lookup"><span data-stu-id="31cea-761">&#x2713; File and path traversal attacks.</span></span>

<span data-ttu-id="31cea-762">&#x2713;远程文件包含 (RFI) 攻击。</span><span class="sxs-lookup"><span data-stu-id="31cea-762">&#x2713; Remote file inclusion (RFI) attacks.</span></span>

<span data-ttu-id="31cea-763">&#x2713;远程代码执行攻击。</span><span class="sxs-lookup"><span data-stu-id="31cea-763">&#x2713; Remote code execution attacks.</span></span>

<span data-ttu-id="31cea-764">&#x2713; PHP 注入攻击。</span><span class="sxs-lookup"><span data-stu-id="31cea-764">&#x2713; PHP-injection attacks.</span></span>

<span data-ttu-id="31cea-765">&#x2713;跨网站脚本攻击。</span><span class="sxs-lookup"><span data-stu-id="31cea-765">&#x2713; Cross-site scripting attacks.</span></span>

<span data-ttu-id="31cea-766">&#x2713; SQL注入攻击。</span><span class="sxs-lookup"><span data-stu-id="31cea-766">&#x2713; SQL-injection attacks.</span></span>

<span data-ttu-id="31cea-767">&#x2713;会话修复攻击。</span><span class="sxs-lookup"><span data-stu-id="31cea-767">&#x2713; Session-fixation attacks.</span></span>

<span data-ttu-id="31cea-768">**更改控件**</span><span class="sxs-lookup"><span data-stu-id="31cea-768">**Change Control**</span></span>

<span data-ttu-id="31cea-769">由于 ISO 27001 审核未专门评估更改请求流程的一些元素，因此将需要：</span><span class="sxs-lookup"><span data-stu-id="31cea-769">As ISO 27001 audits do not specifically assess some elements of Change Request processes, this will require you to:</span></span>

* <span data-ttu-id="31cea-770">演示更改请求具有以下详细信息：</span><span class="sxs-lookup"><span data-stu-id="31cea-770">Demonstrate that change requests have the following details:</span></span>

<span data-ttu-id="31cea-771">&#x2713;记录的影响。</span><span class="sxs-lookup"><span data-stu-id="31cea-771">&#x2713; Documented impact.</span></span>

<span data-ttu-id="31cea-772">&#x2713;执行哪些功能测试的详细信息。</span><span class="sxs-lookup"><span data-stu-id="31cea-772">&#x2713; Details of what functionality testing is to be conducted.</span></span>

<span data-ttu-id="31cea-773">&#x2713;任何退出过程的详细信息。</span><span class="sxs-lookup"><span data-stu-id="31cea-773">&#x2713; Details of any back-out procedures.</span></span>

* <span data-ttu-id="31cea-774">演示在更改完成后执行功能测试。</span><span class="sxs-lookup"><span data-stu-id="31cea-774">Demonstrate that functionality testing is conducted after changes are completed.</span></span>

* <span data-ttu-id="31cea-775">演示执行功能测试后注销更改请求。</span><span class="sxs-lookup"><span data-stu-id="31cea-775">Demonstrate that change requests are signed off after functionality testing is conducted.</span></span>

<span data-ttu-id="31cea-776">**帐户管理**</span><span class="sxs-lookup"><span data-stu-id="31cea-776">**Account Management**</span></span>

<span data-ttu-id="31cea-777">由于 ISO 27001 审核没有专门评估帐户管理流程的一些要素，因此将需要：</span><span class="sxs-lookup"><span data-stu-id="31cea-777">As ISO 27001 audits do not specifically assess some elements of account management processes, this will require you to:</span></span>

*   <span data-ttu-id="31cea-778">演示如何&#x2713;重放攻击，以缓解重播攻击 (如 MFA、Kerberos) 。</span><span class="sxs-lookup"><span data-stu-id="31cea-778">Demonstrate how &#x2713;s are implemented to mitigate replay attacks (e.g. MFA, Kerberos).</span></span>
*   <span data-ttu-id="31cea-779">演示如何禁用或删除 3 个月内未使用的帐户。</span><span class="sxs-lookup"><span data-stu-id="31cea-779">Demonstrate how accounts that have not been used in 3 months are either disabled or deleted.</span></span>
*   <span data-ttu-id="31cea-780">&#x2713;或其他合适的缓解必须配置为保护用户凭据。</span><span class="sxs-lookup"><span data-stu-id="31cea-780">&#x2713;  or other suitable mitigations must be configured to protect user credentials.</span></span> <span data-ttu-id="31cea-781">以下最低密码策略应用作指南：</span><span class="sxs-lookup"><span data-stu-id="31cea-781">The following minimum password policy should be used as a guideline:</span></span>

<span data-ttu-id="31cea-782">&#x2713;最短密码长度为 8 个字符。</span><span class="sxs-lookup"><span data-stu-id="31cea-782">&#x2713; Minimum password length of 8 characters.</span></span>

<span data-ttu-id="31cea-783">&#x2713;帐户锁定阈值不超过 10 次。</span><span class="sxs-lookup"><span data-stu-id="31cea-783">&#x2713; Account lockout threshold of no more than 10 attempts.</span></span>
 
<span data-ttu-id="31cea-784">&#x2713;密码至少五个密码的密码历史记录。</span><span class="sxs-lookup"><span data-stu-id="31cea-784">&#x2713; Password history of a minimum of five passwords.</span></span>
 
<span data-ttu-id="31cea-785">&#x2713;强制使用强密码。</span><span class="sxs-lookup"><span data-stu-id="31cea-785">&#x2713; Enforcement of the use of strong passwords.</span></span>
 
*   <span data-ttu-id="31cea-786">演示已针对所有远程访问解决方案配置 MFA。</span><span class="sxs-lookup"><span data-stu-id="31cea-786">Demonstrate that MFA is configured for all remote access solutions.</span></span>

*   <span data-ttu-id="31cea-787">演示在所有远程访问解决方案上配置了强加密。</span><span class="sxs-lookup"><span data-stu-id="31cea-787">Demonstrate that strong encryption is configured on all remote access solutions.</span></span>

*   <span data-ttu-id="31cea-788">如果公共 DNS 的管理在作用域内环境之外，则必须将能够进行 DNS 修改的所有用户帐户配置为使用 MFA。</span><span class="sxs-lookup"><span data-stu-id="31cea-788">Where the management of Public DNS is outside of the in-scope environment, all user accounts able to make DNS modifications MUST be configured to use MFA.</span></span>

<span data-ttu-id="31cea-789">**入侵检测和防护 (可选)**</span><span class="sxs-lookup"><span data-stu-id="31cea-789">**Intrusion Detection and Prevention (OPTIONAL)**</span></span>

<span data-ttu-id="31cea-790">由于 ISO 27001 审核未专门评估入侵检测和防护服务 (IDPS) 流程的一些要素，因此，这将要求您：</span><span class="sxs-lookup"><span data-stu-id="31cea-790">As ISO 27001 audits do not specifically assess some elements of Intrusion Detection and Prevention Services (IDPS) processes, this will require you to:</span></span>

*   <span data-ttu-id="31cea-791">应在支持 **环境的** 外围部署 IDPS。</span><span class="sxs-lookup"><span data-stu-id="31cea-791">IDPS **SHOULD** be deployed at the perimeter of the supporting environment.</span></span>

*   <span data-ttu-id="31cea-792">IDPS **签名应** 保持最新（在过去一天内）。</span><span class="sxs-lookup"><span data-stu-id="31cea-792">IDPS signatures **SHOULD** be kept current, within the past day.</span></span>

*   <span data-ttu-id="31cea-793">应为 TLS 检查配置 **IDPS。**</span><span class="sxs-lookup"><span data-stu-id="31cea-793">IDPS **SHOULD** be configured for TLS inspection.</span></span>

*   <span data-ttu-id="31cea-794">应为 **所有** 入站和出站流量配置 IDPS。</span><span class="sxs-lookup"><span data-stu-id="31cea-794">IDPS **SHOULD** be configured for ALL inbound and outbound traffic.</span></span>

*   <span data-ttu-id="31cea-795">应 **配置** IDPS 以发出警报。</span><span class="sxs-lookup"><span data-stu-id="31cea-795">IDPS **SHOULD** be configured for alerting.</span></span>

<span data-ttu-id="31cea-796">**事件日志记录**</span><span class="sxs-lookup"><span data-stu-id="31cea-796">**Event Logging**</span></span>

<span data-ttu-id="31cea-797">由于 ISO 27001 审核未专门评估安全事件日志记录流程的一些元素，因此将需要：</span><span class="sxs-lookup"><span data-stu-id="31cea-797">As ISO 27001 audits do not specifically assess some elements of security event logging processes, this will require you to:</span></span>

* <span data-ttu-id="31cea-798">证明面向公众的系统正在登录到不在 DMZ 内的集中日志记录解决方案。</span><span class="sxs-lookup"><span data-stu-id="31cea-798">Demonstrate that public facing systems are logging to a centralized logging solution which isn't within the DMZ.</span></span>

* <span data-ttu-id="31cea-799">演示至少 30 天的日志记录数据如何立即可用，并保留 90 天。</span><span class="sxs-lookup"><span data-stu-id="31cea-799">Demonstrate how a minimum of 30 days’ worth of logging data is immediately available, with 90 days being retained.</span></span>

<span data-ttu-id="31cea-800">**查看 (日志记录数据)**</span><span class="sxs-lookup"><span data-stu-id="31cea-800">**Reviewing (Logging Data)**</span></span>

<span data-ttu-id="31cea-801">由于 ISO 27001 审核未专门评估此类别的某些元素，这将要求您：</span><span class="sxs-lookup"><span data-stu-id="31cea-801">As ISO 27001 audits do not specifically assess some elements of this category, this will require you to:</span></span>

*   <span data-ttu-id="31cea-802">演示如何执行每日日志检查，以及如何标识异常和异常，以演示如何处理这些异常和异常。</span><span class="sxs-lookup"><span data-stu-id="31cea-802">Demonstrate how daily log reviews are conducted and how exceptions and anomalies are identified showing how these are handled.</span></span>

<span data-ttu-id="31cea-803">**警报**</span><span class="sxs-lookup"><span data-stu-id="31cea-803">**Alerting**</span></span>

<span data-ttu-id="31cea-804">由于 ISO 27001 审核未专门评估此类别的某些元素，这将要求您：</span><span class="sxs-lookup"><span data-stu-id="31cea-804">As ISO 27001 audits do not specifically assess some elements of this category, this will require you to:</span></span>

* <span data-ttu-id="31cea-805">演示如何将安全事件配置为触发警报以立即会审。</span><span class="sxs-lookup"><span data-stu-id="31cea-805">Demonstrate how security events are configured to trigger alerts for immediate triage.</span></span>

* <span data-ttu-id="31cea-806">演示员工如何 24/7 响应安全警报。</span><span class="sxs-lookup"><span data-stu-id="31cea-806">Demonstrate how staff are available 24/7 to respond to security alerts.</span></span>

<span data-ttu-id="31cea-807">**风险管理**</span><span class="sxs-lookup"><span data-stu-id="31cea-807">**Risk Management**</span></span>

<span data-ttu-id="31cea-808">由于 ISO 27001 审核未专门评估风险评估流程的一些要素，这将要求您：</span><span class="sxs-lookup"><span data-stu-id="31cea-808">As ISO 27001 audits do not specifically assess some elements of risk assessment processes, this will require you to:</span></span>

* <span data-ttu-id="31cea-809">证明已建立正式的风险管理流程。</span><span class="sxs-lookup"><span data-stu-id="31cea-809">Demonstrate that a formal risk management process is established.</span></span>

<span data-ttu-id="31cea-810">**事件响应**</span><span class="sxs-lookup"><span data-stu-id="31cea-810">**Incident Response**</span></span>

<span data-ttu-id="31cea-811">由于 ISO 27001 审核未专门评估事件响应策略和流程的一些要素，因此需要您：</span><span class="sxs-lookup"><span data-stu-id="31cea-811">As ISO 27001 audits do not specifically assess some elements of incident response policies and processes, this will require you to:</span></span>

*   <span data-ttu-id="31cea-812">证明事件响应计划/过程包括：</span><span class="sxs-lookup"><span data-stu-id="31cea-812">Demonstrate that the incident response plan/procedure includes:</span></span>

<span data-ttu-id="31cea-813">&#x2713;预期威胁模型的特定响应过程。</span><span class="sxs-lookup"><span data-stu-id="31cea-813">&#x2713; Specific response procedures for expected threat models.</span></span>

<span data-ttu-id="31cea-814">&#x2713;事件处理功能，与 NIST 网络安全框架 (识别、保护、检测、响应、恢复) 。</span><span class="sxs-lookup"><span data-stu-id="31cea-814">&#x2713; Incident handling capabilities aligning to NIST Cybersecurity Framework (Identify, Protect, Detect, Respond, Recover).</span></span>
 
<span data-ttu-id="31cea-815">&#x2713; IRP 涵盖范围内系统。</span><span class="sxs-lookup"><span data-stu-id="31cea-815">&#x2713; The IRP covers the in-scope systems.</span></span>
 
<span data-ttu-id="31cea-816">&#x2713;事件响应团队年度培训。</span><span class="sxs-lookup"><span data-stu-id="31cea-816">&#x2713; Annual training for the incident response team.</span></span>

## <a name="appendix-d"></a><span data-ttu-id="31cea-817">附录 D</span><span class="sxs-lookup"><span data-stu-id="31cea-817">Appendix D</span></span>

### <a name="evidence-collection--deltas-for-pci-dss"></a><span data-ttu-id="31cea-818">Evidence Collection – PCI DSS 的增量</span><span class="sxs-lookup"><span data-stu-id="31cea-818">Evidence Collection – Deltas for PCI DSS</span></span>

<span data-ttu-id="31cea-819">如果已经获得 PCI DSS 合规性，以下 delta 的 (差距) PCI DSS 未完全覆盖，至少需要作为此 Microsoft 365 认证的一部分进行审核。</span><span class="sxs-lookup"><span data-stu-id="31cea-819">Where you have already attained PCI DSS compliance, the following delta’s (gaps) not wholly covered by PCI DSS will, at a minimum, need to be reviewed as part of this Microsoft 365 Certification.</span></span>

> [!NOTE]
> <span data-ttu-id="31cea-820">作为 Microsoft 365 认证评估的一部分，认证分析师将确定任何映射的 PCI DSS 控制措施是否未作为 PCI DSS 评估的一部分包含在内，并可能决定对发现包含的控制措施进行采样以提供进一步保证。</span><span class="sxs-lookup"><span data-stu-id="31cea-820">As part of the Microsoft 365 Certification assessment, the certification analyst will determine if any of the mapped PCI DSS controls were not included as part of the PCI DSS assessment and may also decide to sample controls that were found to be included to provide further assurance.</span></span> <span data-ttu-id="31cea-821">PCI DSS 中缺少的任何要求都需要包含在 Microsoft 365 认证评估活动中。</span><span class="sxs-lookup"><span data-stu-id="31cea-821">Any requirements missing from the PCI DSS will need to be included into the Microsoft 365 Certification assessment activities.</span></span>

<span data-ttu-id="31cea-822">**恶意软件保护 - 应用程序控制**</span><span class="sxs-lookup"><span data-stu-id="31cea-822">**Malware Protection - Application Control**</span></span>

<span data-ttu-id="31cea-823">如果恶意软件防护是通过防病毒进行，且在 PCI DSS 报告中进行了证明，则无需进一步调查。</span><span class="sxs-lookup"><span data-stu-id="31cea-823">If malware protection is in place through use of anti-virus and is attested to within PCI DSS Report no further investigation is necessary.</span></span> <span data-ttu-id="31cea-824">如果没有防病毒功能，认证分析师将需要识别和评估应用程序控制机制的证据，以防止恶意软件在环境中触发。</span><span class="sxs-lookup"><span data-stu-id="31cea-824">If no anti-virus is in place, certification analysts will need to identify and assess evidence of application control mechanisms to prevent detonation of malware within the environment.</span></span> <span data-ttu-id="31cea-825">这将要求您：</span><span class="sxs-lookup"><span data-stu-id="31cea-825">This will require you to:</span></span> 

*   <span data-ttu-id="31cea-826">演示如何执行应用程序审批并确认已完成此操作。</span><span class="sxs-lookup"><span data-stu-id="31cea-826">Demonstrate how the application approval is conducted and confirm that this is completed.</span></span>

*   <span data-ttu-id="31cea-827">演示存在具有业务理由的已批准应用程序的完整列表。</span><span class="sxs-lookup"><span data-stu-id="31cea-827">Demonstrate that a complete list of approved applications with business justification exists.</span></span>

*   <span data-ttu-id="31cea-828">提供或演示支持文档，详细说明了如何配置应用程序控制软件以满足特定应用程序控制机制 (如允许列表、代码签名等) 。</span><span class="sxs-lookup"><span data-stu-id="31cea-828">Provide or demonstrate supporting documentation is in place detailing how application control software is configured to meet specific application control mechanisms (i.e. whitelisting, code signing, etc.).</span></span>

*   <span data-ttu-id="31cea-829">演示跨所有示例系统组件，应用程序控件配置为已记录。</span><span class="sxs-lookup"><span data-stu-id="31cea-829">Demonstrate that across all sampled system components, application control is configured as documented.</span></span>

<span data-ttu-id="31cea-830">**修补程序管理 – 风险排名**</span><span class="sxs-lookup"><span data-stu-id="31cea-830">**Patch Management – Risk Ranking**</span></span>

<span data-ttu-id="31cea-831">由于 PCI DSS 审核未专门评估此类别，这将要求您：</span><span class="sxs-lookup"><span data-stu-id="31cea-831">As PCI DSS audits do not specifically assess this category, this will require you to:</span></span>

* <span data-ttu-id="31cea-832">演示如何执行漏洞的风险分级。</span><span class="sxs-lookup"><span data-stu-id="31cea-832">Demonstrate how risk ranking of vulnerabilities is conducted.</span></span>

<span data-ttu-id="31cea-833">**漏洞扫描**</span><span class="sxs-lookup"><span data-stu-id="31cea-833">**Vulnerability Scanning**</span></span>

<span data-ttu-id="31cea-834">由于 PCI DSS 审核未专门评估此类别，这将要求您：</span><span class="sxs-lookup"><span data-stu-id="31cea-834">As PCI DSS audits do not specifically assess this category, this will require you to:</span></span>

* <span data-ttu-id="31cea-835">证明修正是按照记录漏洞修正策略内行进行的。</span><span class="sxs-lookup"><span data-stu-id="31cea-835">Demonstrate that remediation is conducted in-line with the documented vulnerability remediation policy.</span></span>

<span data-ttu-id="31cea-836">**防火墙 – 防火墙 (或等效技术)**</span><span class="sxs-lookup"><span data-stu-id="31cea-836">**Firewall – Firewalls (or equivalent technologies)**</span></span>

<span data-ttu-id="31cea-837">由于 PCI DSS 审核未专门评估此类别，这将要求您：</span><span class="sxs-lookup"><span data-stu-id="31cea-837">As PCI DSS audits do not specifically assess this category, this will require you to:</span></span>

* <span data-ttu-id="31cea-838">演示防火墙仅支持所有非控制台管理界面上的强加密。</span><span class="sxs-lookup"><span data-stu-id="31cea-838">Demonstrate that firewalls support only strong cryptography on all non-console administrative interfaces.</span></span>

* <span data-ttu-id="31cea-839">演示向 Internet 公开的防火墙的非控制台管理接口支持 MFA。</span><span class="sxs-lookup"><span data-stu-id="31cea-839">Demonstrate that firewall's non-console administrative interfaces exposed to the Internet support MFA.</span></span>

<span data-ttu-id="31cea-840">如果部署了 Web 应用程序防火墙 (WAF) 以帮助防范应用程序可能暴露给的 Web 应用程序威胁和漏洞，将提供额外的信用。</span><span class="sxs-lookup"><span data-stu-id="31cea-840">Additional credit will be provided if a Web Application Firewall (WAF) s deployed to help protect against the myriad of web application threats and vulnerabilities that the application can be exposed to.</span></span> <span data-ttu-id="31cea-841">当存在 WAF 或类似项时，这将需要你：</span><span class="sxs-lookup"><span data-stu-id="31cea-841">When a WAF or similar is present, this will require you to:</span></span>

* <span data-ttu-id="31cea-842">演示 WAF 在主动防御模式下配置，或通过警报进行更多监视。</span><span class="sxs-lookup"><span data-stu-id="31cea-842">Demonstrate the WAF is configured in active defense mode or monitoring more with alerting.</span></span>

* <span data-ttu-id="31cea-843">演示 WAF 配置为支持 SSL 卸载。</span><span class="sxs-lookup"><span data-stu-id="31cea-843">Demonstrate the WAF is configured to support SSL offloading.</span></span>

* <span data-ttu-id="31cea-844">根据 OWASP 核心规则集 (3.0 或 3.1) 配置，以抵御以下大多数攻击类型：</span><span class="sxs-lookup"><span data-stu-id="31cea-844">Is configured as per the OWASP Core Rule Set (3.0 or 3.1) to protect against most of the following attack types:</span></span>

<span data-ttu-id="31cea-845">&#x2713;协议和编码问题。</span><span class="sxs-lookup"><span data-stu-id="31cea-845">&#x2713; Protocol and encoding issues.</span></span>

<span data-ttu-id="31cea-846">&#x2713;标头注入、请求拆分和响应拆分。</span><span class="sxs-lookup"><span data-stu-id="31cea-846">&#x2713; Header injection, request smuggling, and response splitting.</span></span>

<span data-ttu-id="31cea-847">&#x2713;文件和路径遍历攻击。</span><span class="sxs-lookup"><span data-stu-id="31cea-847">&#x2713; File and path traversal attacks.</span></span>

<span data-ttu-id="31cea-848">&#x2713;远程文件包含 (RFI) 攻击。</span><span class="sxs-lookup"><span data-stu-id="31cea-848">&#x2713; Remote file inclusion (RFI) attacks.</span></span>

<span data-ttu-id="31cea-849">&#x2713;远程代码执行攻击。</span><span class="sxs-lookup"><span data-stu-id="31cea-849">&#x2713; Remote code execution attacks.</span></span>

<span data-ttu-id="31cea-850">&#x2713; PHP 注入攻击。</span><span class="sxs-lookup"><span data-stu-id="31cea-850">&#x2713; PHP-injection attacks.</span></span>

<span data-ttu-id="31cea-851">&#x2713;跨网站脚本攻击。</span><span class="sxs-lookup"><span data-stu-id="31cea-851">&#x2713; Cross-site scripting attacks.</span></span>

<span data-ttu-id="31cea-852">&#x2713; SQL注入攻击。</span><span class="sxs-lookup"><span data-stu-id="31cea-852">&#x2713; SQL-injection attacks.</span></span>

<span data-ttu-id="31cea-853">&#x2713;会话修复攻击。</span><span class="sxs-lookup"><span data-stu-id="31cea-853">&#x2713; Session-fixation attacks.</span></span>

<span data-ttu-id="31cea-854">**更改控件**</span><span class="sxs-lookup"><span data-stu-id="31cea-854">**Change Control**</span></span>

<span data-ttu-id="31cea-855">由于 PCI DSS 审核未专门评估更改请求流程的一些元素，因此这将要求您：</span><span class="sxs-lookup"><span data-stu-id="31cea-855">As PCI DSS audits do not specifically assess some elements of Change Request processes, this will require you to:</span></span>

* <span data-ttu-id="31cea-856">演示在生产环境中提出更改请求之前。</span><span class="sxs-lookup"><span data-stu-id="31cea-856">Demonstrate that change requests are raised before being made in production environments.</span></span>

* <span data-ttu-id="31cea-857">演示更改在进入生产之前获得授权。</span><span class="sxs-lookup"><span data-stu-id="31cea-857">Demonstrate that changes are authorized before going into production.</span></span>

* <span data-ttu-id="31cea-858">演示在更改完成后执行功能测试。</span><span class="sxs-lookup"><span data-stu-id="31cea-858">Demonstrate that functionality testing is conducted after changes are completed.</span></span>

* <span data-ttu-id="31cea-859">演示执行功能测试后注销更改请求。</span><span class="sxs-lookup"><span data-stu-id="31cea-859">Demonstrate that change requests are signed off after functionality testing is conducted.</span></span>

<span data-ttu-id="31cea-860">**安全软件开发/部署**</span><span class="sxs-lookup"><span data-stu-id="31cea-860">**Secure Software Development/Deployment**</span></span>

<span data-ttu-id="31cea-861">由于 PCI DSS 审核不会专门访问安全软件开发和部署流程的一些元素;这将需要你：</span><span class="sxs-lookup"><span data-stu-id="31cea-861">As PCI DSS audits do not specifically access some elements of secure software development and deployment processes; this will require to you:</span></span>

* <span data-ttu-id="31cea-862">代码库必须受 MFA 保护。</span><span class="sxs-lookup"><span data-stu-id="31cea-862">Code repositories MUST be secured by MFA.</span></span>

*   <span data-ttu-id="31cea-863">必须实施适当的访问控制，以保护代码库免受恶意代码修改。</span><span class="sxs-lookup"><span data-stu-id="31cea-863">Adequate access controls MUST be in place to protect code repositories against malicious code modifications.</span></span>

<span data-ttu-id="31cea-864">**帐户管理**</span><span class="sxs-lookup"><span data-stu-id="31cea-864">**Account Management**</span></span>

<span data-ttu-id="31cea-865">由于 PCI DSS 审核未专门评估帐户管理流程的一些要素，这将要求您：</span><span class="sxs-lookup"><span data-stu-id="31cea-865">As PCI DSS audits do not specifically assess some elements of account management processes, this will require you to:</span></span>

* <span data-ttu-id="31cea-866">演示如何实施授权机制来缓解重播攻击 (例如 MFA、Kerberos) 。</span><span class="sxs-lookup"><span data-stu-id="31cea-866">Demonstrate how the authorization mechanisms are implemented to mitigate replay attacks (e.g. MFA, Kerberos).</span></span>

* <span data-ttu-id="31cea-867">必须将强密码策略或其他合适的缓解配置为保护用户凭据。</span><span class="sxs-lookup"><span data-stu-id="31cea-867">Strong password policies or other suitable mitigations must be configured to protect user credentials.</span></span> <span data-ttu-id="31cea-868">以下最低密码策略应用作指南：</span><span class="sxs-lookup"><span data-stu-id="31cea-868">The following minimum password policy should be used as a guideline:</span></span> 

<span data-ttu-id="31cea-869">&#x2713;最短密码长度为 8 个字符。</span><span class="sxs-lookup"><span data-stu-id="31cea-869">&#x2713; Minimum password length of 8 characters.</span></span>

<span data-ttu-id="31cea-870">&#x2713;帐户锁定阈值不超过 10 次。</span><span class="sxs-lookup"><span data-stu-id="31cea-870">&#x2713; Account lockout threshold of no more than 10 attempts.</span></span>

<span data-ttu-id="31cea-871">&#x2713;密码至少五个密码的密码历史记录。</span><span class="sxs-lookup"><span data-stu-id="31cea-871">&#x2713; Password history of a minimum of five passwords.</span></span>

<span data-ttu-id="31cea-872">&#x2713;强制使用强密码。</span><span class="sxs-lookup"><span data-stu-id="31cea-872">&#x2713; Enforcement of the use of strong passwords.</span></span>

* <span data-ttu-id="31cea-873">演示在所有远程访问解决方案上配置了强加密。</span><span class="sxs-lookup"><span data-stu-id="31cea-873">Demonstrate that strong encryption is configured on all remote access solutions.</span></span>

* <span data-ttu-id="31cea-874">如果公共 DNS 的管理在作用域内环境之外，则必须将能够进行 DNS 修改的所有用户帐户配置为使用 MFA。</span><span class="sxs-lookup"><span data-stu-id="31cea-874">Where the management of Public DNS is outside of the in-scope environment, all user accounts able to make DNS modifications MUST be configured to use MFA.</span></span>

<span data-ttu-id="31cea-875">**入侵检测和防护 (可选)**</span><span class="sxs-lookup"><span data-stu-id="31cea-875">**Intrusion Detection and Prevention (OPTIONAL)**</span></span>

<span data-ttu-id="31cea-876">由于 PCI DSS 审核未专门评估 IDPS (的入侵检测和防护服务) ，这将要求您：</span><span class="sxs-lookup"><span data-stu-id="31cea-876">As PCI DSS audits do not specifically assess some elements of Intrusion Detection and Prevention Services (IDPS) processes, this will require you to:</span></span>

* <span data-ttu-id="31cea-877">应为 TLS 检查配置 IDPS。</span><span class="sxs-lookup"><span data-stu-id="31cea-877">IDPS SHOULD be configured for TLS inspection.</span></span>

*   <span data-ttu-id="31cea-878">应为所有入站和出站流量配置 IDPS。</span><span class="sxs-lookup"><span data-stu-id="31cea-878">IDPS SHOULD be configured for ALL inbound and outbound traffic.</span></span>

<span data-ttu-id="31cea-879">**风险管理**</span><span class="sxs-lookup"><span data-stu-id="31cea-879">**Risk Management**</span></span>

<span data-ttu-id="31cea-880">由于 PCI DSS 审核未专门评估风险评估流程的一些要素，这将要求您：</span><span class="sxs-lookup"><span data-stu-id="31cea-880">As PCI DSS audits do not specifically assess some elements of risk assessment processes, this will require you to:</span></span>

* <span data-ttu-id="31cea-881">演示风险评估包括影响和可能性矩阵。</span><span class="sxs-lookup"><span data-stu-id="31cea-881">Demonstrate the risk assessment includes impact and likelihood matrices.</span></span>

<span data-ttu-id="31cea-882">**事件响应**</span><span class="sxs-lookup"><span data-stu-id="31cea-882">**Incident Response**</span></span>

<span data-ttu-id="31cea-883">由于 PCI DSS 审核未专门评估事件响应策略和流程的一些要素，因此开发人员需要：</span><span class="sxs-lookup"><span data-stu-id="31cea-883">As PCI DSS audits don't specifically assess some elements of incident response policies and processes, this will require the developer to:</span></span>

* <span data-ttu-id="31cea-884">演示符合 NIST 网络安全框架的事件处理功能 (识别、保护、检测、响应、恢复) 。</span><span class="sxs-lookup"><span data-stu-id="31cea-884">Demonstrate Incident handling capabilities align to NIST Cybersecurity Framework (Identify, Protect, Detect, Respond, Recover).</span></span>

## <a name="appendix-e"></a><span data-ttu-id="31cea-885">附录 E</span><span class="sxs-lookup"><span data-stu-id="31cea-885">Appendix E</span></span>

### <a name="evidence-collection---deltas-for-soc-2"></a><span data-ttu-id="31cea-886">证据收集 - SOC 2 的增量</span><span class="sxs-lookup"><span data-stu-id="31cea-886">Evidence Collection - Deltas for SOC 2</span></span>

<span data-ttu-id="31cea-887">如果已获得 SOC 2 合规性，需要作为此 Microsoft 365 认证一部分查看以下增量的 (差距) 未完全涵盖在 SOC 2 中。</span><span class="sxs-lookup"><span data-stu-id="31cea-887">Where you have already attained SOC 2 compliance, the following delta’s (gaps) not wholly covered by SOC 2 will need to be reviewed as part of this Microsoft 365 Certification.</span></span>

> [!NOTE]
> <span data-ttu-id="31cea-888">作为 Microsoft 365 认证评估的一部分，认证分析师将确定任何映射的 SOC 2 控制措施是否未作为 SOC 2 评估的一部分包含在内，并可能决定对发现包含的控制措施进行采样以提供进一步保证。</span><span class="sxs-lookup"><span data-stu-id="31cea-888">As part of the Microsoft 365 Certification assessment, the certification analyst will determine if any of the mapped SOC 2 controls were not included as part of your SOC 2 assessment and may also decide to sample controls that were found to be included to provide further assurance.</span></span> <span data-ttu-id="31cea-889">SOC 2 评估中缺少的任何要求都需要包含在 Microsoft 365 认证评估活动中。</span><span class="sxs-lookup"><span data-stu-id="31cea-889">Any requirements missing from your SOC 2 assessment will need to be included as part of the Microsoft 365 Certification assessment activities.</span></span>

<span data-ttu-id="31cea-890">**恶意软件保护 - 应用程序控制**</span><span class="sxs-lookup"><span data-stu-id="31cea-890">**Malware Protection - Application Control**</span></span>

<span data-ttu-id="31cea-891">如果恶意软件防护是通过防病毒进行，且在 SOC 2 报告中进行了证明，则无需进一步调查。</span><span class="sxs-lookup"><span data-stu-id="31cea-891">If malware protection is in place through use of anti-virus and is attested to within your SOC 2 report no further investigation is necessary.</span></span> <span data-ttu-id="31cea-892">如果没有防病毒功能，认证分析师将需要识别和评估应用程序控制机制的证据，以防止恶意软件在环境中触发。</span><span class="sxs-lookup"><span data-stu-id="31cea-892">If no anti-virus is in place, certification analysts will need to identify and assess evidence of application control mechanisms to prevent detonation of malware within the environment.</span></span> <span data-ttu-id="31cea-893">这将要求您：</span><span class="sxs-lookup"><span data-stu-id="31cea-893">This will require you to:</span></span>

* <span data-ttu-id="31cea-894">提供或演示支持文档，详细说明了如何配置应用程序控制软件以满足特定应用程序控制机制 (如允许列表、代码签名等) 。</span><span class="sxs-lookup"><span data-stu-id="31cea-894">Provide or demonstrate supporting documentation is in place detailing how application control software is configured to meet specific application control mechanisms (i.e. whitelisting, code signing, etc.).</span></span>

* <span data-ttu-id="31cea-895">演示如何执行应用程序审批并确认已完成此操作。</span><span class="sxs-lookup"><span data-stu-id="31cea-895">Demonstrate how the application approval is conducted and confirm that this is completed.</span></span>

*   <span data-ttu-id="31cea-896">演示存在具有业务理由的已批准应用程序的完整列表。</span><span class="sxs-lookup"><span data-stu-id="31cea-896">Demonstrate that a complete list of approved applications with business justification exists.</span></span>

*   <span data-ttu-id="31cea-897">演示跨所有示例系统组件，应用程序控件配置为已记录。</span><span class="sxs-lookup"><span data-stu-id="31cea-897">Demonstrate that across all sampled system components, application control is configured as documented.</span></span>

<span data-ttu-id="31cea-898">**修补程序管理 – 修补**</span><span class="sxs-lookup"><span data-stu-id="31cea-898">**Patch Management – Patching**</span></span>

<span data-ttu-id="31cea-899">由于 SOC 2 审核未专门评估此类别，这将要求您：</span><span class="sxs-lookup"><span data-stu-id="31cea-899">As SOC 2 audits do not specifically assess this category, this will require you to:</span></span>

*   <span data-ttu-id="31cea-900">必须在正常修补活动窗口中修复任何低、中、高或关键问题。</span><span class="sxs-lookup"><span data-stu-id="31cea-900">Any Low, Medium, High, or Critical issue must be patched within normal patching activity windows.</span></span>

*   <span data-ttu-id="31cea-901">供应商不再支持的软件组件和操作系统不得在环境中使用。</span><span class="sxs-lookup"><span data-stu-id="31cea-901">Software components and operating systems no longer supported by the vendor MUST not be used within the environment.</span></span> <span data-ttu-id="31cea-902">必须制定支持策略，以确保将不受支持的软件组件/操作系统从环境中删除，并且必须制定一个流程来确定软件组件何时结束使用。</span><span class="sxs-lookup"><span data-stu-id="31cea-902">Supporting policies MUST be in place to ensure unsupported software components / operating systems will be removed from the environment and a process to identify when software components go end-of-life must be in place.</span></span>

<span data-ttu-id="31cea-903">**防火墙 – 防火墙**</span><span class="sxs-lookup"><span data-stu-id="31cea-903">**Firewall – Firewalls**</span></span>

<span data-ttu-id="31cea-904">由于 SOC 2 审核未专门评估对防火墙访问控制列表的变更控制，这将要求您：</span><span class="sxs-lookup"><span data-stu-id="31cea-904">As SOC 2 audits do not specifically assess change controls to firewall access control lists, this will require you to:</span></span>

* <span data-ttu-id="31cea-905">演示所有允许通过防火墙 (流量) 通过授权过程，这导致记录具有业务理由的所有流量。</span><span class="sxs-lookup"><span data-stu-id="31cea-905">Demonstrate that all permitted traffic through the firewall(s) goes through an authorization process which results in the documentation of all traffic with a business justification.</span></span>

* <span data-ttu-id="31cea-906">演示防火墙规则评审至少每六个月执行一次。</span><span class="sxs-lookup"><span data-stu-id="31cea-906">Demonstrate that firewall rule reviews are conducted at least every six months.</span></span>

<span data-ttu-id="31cea-907">如果部署了 Web 应用程序防火墙 (WAF) 或类似防火墙以帮助防范应用程序可能暴露给的 Web 应用程序威胁和漏洞，将提供额外的信用。</span><span class="sxs-lookup"><span data-stu-id="31cea-907">Additional credit will be provided if a Web Application Firewall (WAF) or similar is deployed to help protect against the myriad of web application threats and vulnerabilities that the application can be exposed to.</span></span> <span data-ttu-id="31cea-908">当存在 WAF 或类似项时，这将需要你：</span><span class="sxs-lookup"><span data-stu-id="31cea-908">When a WAF or similar is present, this will require you to:</span></span>

* <span data-ttu-id="31cea-909">演示 WAF 在主动防御模式下配置，或通过警报进行更多监视。</span><span class="sxs-lookup"><span data-stu-id="31cea-909">Demonstrate the WAF is configured in active defense mode or monitoring more with alerting.</span></span>

* <span data-ttu-id="31cea-910">演示 WAF 配置为支持 SSL 卸载。</span><span class="sxs-lookup"><span data-stu-id="31cea-910">Demonstrate the WAF is configured to support SSL offloading.</span></span>

* <span data-ttu-id="31cea-911">根据 OWASP 核心规则集 ( (3.0 或 3.1) 进行配置，以抵御大多数以下攻击类型：</span><span class="sxs-lookup"><span data-stu-id="31cea-911">Is configured as per the OWASP Core Rule Set ((3.0 or 3.1) to protect against the majority of the following attack types:</span></span>

<span data-ttu-id="31cea-912">&emsp;&#x2713;协议和编码问题。</span><span class="sxs-lookup"><span data-stu-id="31cea-912">&emsp;&#x2713; Protocol and encoding issues.</span></span>

<span data-ttu-id="31cea-913">&emsp;&#x2713;标头注入、请求拆分和响应拆分。</span><span class="sxs-lookup"><span data-stu-id="31cea-913">&emsp;&#x2713; Header injection, request smuggling, and response splitting.</span></span>

<span data-ttu-id="31cea-914">&emsp;&#x2713;文件和路径遍历攻击。</span><span class="sxs-lookup"><span data-stu-id="31cea-914">&emsp;&#x2713; File and path traversal attacks.</span></span>

<span data-ttu-id="31cea-915">&emsp;&#x2713;远程文件包含 (RFI) 攻击。</span><span class="sxs-lookup"><span data-stu-id="31cea-915">&emsp;&#x2713; Remote file inclusion (RFI) attacks.</span></span>

<span data-ttu-id="31cea-916">&emsp;&#x2713;远程代码执行攻击。</span><span class="sxs-lookup"><span data-stu-id="31cea-916">&emsp;&#x2713; Remote code execution attacks.</span></span>

<span data-ttu-id="31cea-917">&emsp;&#x2713; PHP 注入攻击。</span><span class="sxs-lookup"><span data-stu-id="31cea-917">&emsp;&#x2713; PHP-injection attacks.</span></span>

<span data-ttu-id="31cea-918">&emsp;&#x2713;跨网站脚本攻击。</span><span class="sxs-lookup"><span data-stu-id="31cea-918">&emsp;&#x2713; Cross-site scripting attacks.</span></span>

<span data-ttu-id="31cea-919">&emsp;&#x2713; SQL注入攻击。</span><span class="sxs-lookup"><span data-stu-id="31cea-919">&emsp;&#x2713; SQL-injection attacks.</span></span>

<span data-ttu-id="31cea-920">&emsp;&#x2713;会话修复攻击。</span><span class="sxs-lookup"><span data-stu-id="31cea-920">&emsp;&#x2713; Session-fixation attacks.</span></span>

<span data-ttu-id="31cea-921">**更改控件**</span><span class="sxs-lookup"><span data-stu-id="31cea-921">**Change Control**</span></span>

<span data-ttu-id="31cea-922">由于 SOC 2 审核没有专门评估更改请求流程的一些元素，因此需要开发人员：</span><span class="sxs-lookup"><span data-stu-id="31cea-922">As SOC 2 audits don't specifically assess some elements of Change Request processes, this will require the developer to:</span></span>

* <span data-ttu-id="31cea-923">演示如何将开发/测试环境与强制职责分离的生产环境分开。</span><span class="sxs-lookup"><span data-stu-id="31cea-923">Demonstrate how development / test environments are separate from the production environment enforcing separation of duties.</span></span>

* <span data-ttu-id="31cea-924">演示在开发/测试环境中如何使用实时数据。</span><span class="sxs-lookup"><span data-stu-id="31cea-924">Demonstrate how live data isn't used within the development / test environments.</span></span>

* <span data-ttu-id="31cea-925">演示在更改完成后执行功能测试。</span><span class="sxs-lookup"><span data-stu-id="31cea-925">Demonstrate that functionality testing is conducted after changes are completed.</span></span>

* <span data-ttu-id="31cea-926">演示执行功能测试后注销更改请求。</span><span class="sxs-lookup"><span data-stu-id="31cea-926">Demonstrate that change requests are signed off after functionality testing is conducted.</span></span>

<span data-ttu-id="31cea-927">**安全软件开发/部署**</span><span class="sxs-lookup"><span data-stu-id="31cea-927">**Secure Software Development/Deployment**</span></span>

<span data-ttu-id="31cea-928">由于 SOC 2 审核不会专门访问安全软件开发和部署流程的一些元素;这将需要你：</span><span class="sxs-lookup"><span data-stu-id="31cea-928">As SOC 2 audits do not specifically access some elements of secure software development and deployment processes; this will require to you:</span></span>

*   <span data-ttu-id="31cea-929">您必须已建立并记录涵盖整个软件开发生命周期的软件开发过程。</span><span class="sxs-lookup"><span data-stu-id="31cea-929">You MUST have an established and documented software development process covering the entire software-development lifecycle.</span></span>

*   <span data-ttu-id="31cea-930">开发人员必须至少每年接受安全软件编码培训。</span><span class="sxs-lookup"><span data-stu-id="31cea-930">Developers MUST undergo secure software coding training at least annually.</span></span>

*   <span data-ttu-id="31cea-931">代码库必须受 MFA 保护。</span><span class="sxs-lookup"><span data-stu-id="31cea-931">Code repositories MUST be secured by MFA.</span></span>

*   <span data-ttu-id="31cea-932">必须实施适当的访问控制，以保护代码库免受恶意代码修改。</span><span class="sxs-lookup"><span data-stu-id="31cea-932">Adequate access controls MUST be in place to protect code repositories against malicious code modifications.</span></span>

<span data-ttu-id="31cea-933">**帐户管理**</span><span class="sxs-lookup"><span data-stu-id="31cea-933">**Account Management**</span></span>

<span data-ttu-id="31cea-934">由于 SOC2 审核没有专门评估帐户管理流程的一些要素，因此这将要求您：</span><span class="sxs-lookup"><span data-stu-id="31cea-934">As SOC2 audits do not specifically assess some elements of account management processes, this will require you to:</span></span>

*   <span data-ttu-id="31cea-935">演示如何实施授权机制来缓解重播攻击 (例如 MFA、Kerberos) 。</span><span class="sxs-lookup"><span data-stu-id="31cea-935">Demonstrate how the authorization mechanisms are implemented to mitigate replay attacks (e.g. MFA, Kerberos).</span></span>

*   <span data-ttu-id="31cea-936">演示如何禁用或删除 3 个月内未使用的帐户。</span><span class="sxs-lookup"><span data-stu-id="31cea-936">Demonstrate how accounts that have not been used in 3 months are either disabled or deleted.</span></span>

*   <span data-ttu-id="31cea-937">必须将强密码策略或其他合适的缓解配置为保护用户凭据。</span><span class="sxs-lookup"><span data-stu-id="31cea-937">Strong password policies or other suitable mitigations must be configured to protect user credentials.</span></span> <span data-ttu-id="31cea-938">以下最低密码策略应用作指南：</span><span class="sxs-lookup"><span data-stu-id="31cea-938">The following minimum password policy should be used as a guideline:</span></span>

<span data-ttu-id="31cea-939">&emsp;&#x2713;最短密码长度为 8 个字符。</span><span class="sxs-lookup"><span data-stu-id="31cea-939">&emsp;&#x2713; Minimum password length of 8 characters.</span></span>

<span data-ttu-id="31cea-940">&emsp;&#x2713;帐户锁定阈值不超过 10 次。</span><span class="sxs-lookup"><span data-stu-id="31cea-940">&emsp;&#x2713; Account lockout threshold of no more than 10 attempts.</span></span>

<span data-ttu-id="31cea-941">&emsp;&#x2713;密码至少 5 个的密码历史记录。</span><span class="sxs-lookup"><span data-stu-id="31cea-941">&emsp;&#x2713; Password history of a minimum of 5 passwords.</span></span>

<span data-ttu-id="31cea-942">&emsp;&#x2713;强制使用强密码</span><span class="sxs-lookup"><span data-stu-id="31cea-942">&emsp;&#x2713; Enforcement of the use of strong passwords</span></span>

*   <span data-ttu-id="31cea-943">演示向所有用户颁发唯一用户帐户。</span><span class="sxs-lookup"><span data-stu-id="31cea-943">Demonstrate that unique user accounts are issued to all users.</span></span>

*   <span data-ttu-id="31cea-944">如果公共 DNS 的管理在作用域内环境之外，则必须将能够进行 DNS 修改的所有用户帐户配置为使用 MFA。</span><span class="sxs-lookup"><span data-stu-id="31cea-944">Where the management of Public DNS is outside of the in-scope environment, all user accounts able to make DNS modifications MUST be configured to use MFA.</span></span>

<span data-ttu-id="31cea-945">**入侵检测和防护 (可选) 。**</span><span class="sxs-lookup"><span data-stu-id="31cea-945">**Intrusion Detection and Prevention (OPTIONAL).**</span></span>

<span data-ttu-id="31cea-946">由于 SOC 2 审核未专门评估 IDPS (IDPS) 的一些元素，因此这将要求您：</span><span class="sxs-lookup"><span data-stu-id="31cea-946">As SOC 2 audits do not specifically assess some elements of Intrusion Detection and Prevention Services (IDPS) processes, this will require you to:</span></span>

*   <span data-ttu-id="31cea-947">IDPS 签名应保持最新（在过去一天内）</span><span class="sxs-lookup"><span data-stu-id="31cea-947">IDPS signatures SHOULD be kept current, within the past day</span></span>

*   <span data-ttu-id="31cea-948">应为 TLS 检查配置 IDPS</span><span class="sxs-lookup"><span data-stu-id="31cea-948">IDPS SHOULD be configured for TLS inspection</span></span>

*   <span data-ttu-id="31cea-949">应为所有入站和出站流量配置 IDPS</span><span class="sxs-lookup"><span data-stu-id="31cea-949">IDPS SHOULD be configured for ALL inbound and outbound traffic</span></span>

<span data-ttu-id="31cea-950">**事件日志记录**</span><span class="sxs-lookup"><span data-stu-id="31cea-950">**Event Logging**</span></span>

<span data-ttu-id="31cea-951">由于 SOC 2 审核没有专门评估安全事件日志记录流程的一些元素，因此这将要求您：</span><span class="sxs-lookup"><span data-stu-id="31cea-951">As SOC 2 audits do not specifically assess some elements of security event logging processes, this will require you to:</span></span>

* <span data-ttu-id="31cea-952">演示如何在示例集内的所有系统组件上将以下系统配置为记录以下事件</span><span class="sxs-lookup"><span data-stu-id="31cea-952">Demonstrate how, on all system components within the sample set the following system are configured to log the following events</span></span>

<span data-ttu-id="31cea-953">&emsp;&#x2713;用户访问系统组件和应用程序 (应用程序) 。</span><span class="sxs-lookup"><span data-stu-id="31cea-953">&emsp;&#x2713; User access to system components and the application(s).</span></span>

<span data-ttu-id="31cea-954">&emsp;&#x2713;高特权用户执行的所有操作。</span><span class="sxs-lookup"><span data-stu-id="31cea-954">&emsp;&#x2713; All actions taken by a high privileged user.</span></span>

<span data-ttu-id="31cea-955">&emsp;&#x2713;无效的逻辑访问尝试。</span><span class="sxs-lookup"><span data-stu-id="31cea-955">&emsp;&#x2713; Invalid logical access attempts.</span></span>

<span data-ttu-id="31cea-956">演示记录的事件包含;至少，以下信息：</span><span class="sxs-lookup"><span data-stu-id="31cea-956">Demonstrate that logged events contain; at a minimum, the following information:</span></span>

<span data-ttu-id="31cea-957">&emsp;&#x2713;用户。</span><span class="sxs-lookup"><span data-stu-id="31cea-957">&emsp;&#x2713; User.</span></span>

<span data-ttu-id="31cea-958">&emsp;&#x2713;事件的类型。</span><span class="sxs-lookup"><span data-stu-id="31cea-958">&emsp;&#x2713; Type of Event.</span></span>

<span data-ttu-id="31cea-959">&emsp;&#x2713;日期和时间。</span><span class="sxs-lookup"><span data-stu-id="31cea-959">&emsp;&#x2713; Date and Time.</span></span>

<span data-ttu-id="31cea-960">&emsp;&#x2713;"成功/失败"指示器。</span><span class="sxs-lookup"><span data-stu-id="31cea-960">&emsp;&#x2713; Success/Failure indicator.</span></span>

<span data-ttu-id="31cea-961">&emsp;&#x2713;标签来标识受影响的系统。</span><span class="sxs-lookup"><span data-stu-id="31cea-961">&emsp;&#x2713; Label to identify the affected system.</span></span>

*   <span data-ttu-id="31cea-962">演示示例集内的所有系统组件均配置为使用时间同步，并且这些组件与主要/辅助时间服务器相同。</span><span class="sxs-lookup"><span data-stu-id="31cea-962">Demonstrate that all system components within the sample set are configured to utilize time-synchronization and that these are the same as the primary/secondary time servers.</span></span>

* <span data-ttu-id="31cea-963">证明面向公众的系统正在登录到不在 DMZ 内的集中日志记录解决方案。</span><span class="sxs-lookup"><span data-stu-id="31cea-963">Demonstrate that public facing systems are logging to a centralized logging solution which isn't within the DMZ.</span></span>

*   <span data-ttu-id="31cea-964">证明面向公众的系统正在登录到不在 DMZ 内的集中日志记录解决方案。</span><span class="sxs-lookup"><span data-stu-id="31cea-964">Demonstrate that public facing systems are logging to a centralized logging solution which isn't within the DMZ.</span></span>

* <span data-ttu-id="31cea-965">演示如何保护集中日志记录解决方案免受日志记录数据未经授权的篡改。</span><span class="sxs-lookup"><span data-stu-id="31cea-965">Demonstrate how the centralized logging solution is protected from unauthorized tampering of logging data.</span></span>

* <span data-ttu-id="31cea-966">演示至少 30 天的日志记录数据如何立即可用，并保留 90 天以上。</span><span class="sxs-lookup"><span data-stu-id="31cea-966">Demonstrate how a minimum of 30 days’ worth of logging data is immediately available, with 90 days’ or more being retained.</span></span>

<span data-ttu-id="31cea-967">**风险管理**</span><span class="sxs-lookup"><span data-stu-id="31cea-967">**Risk Management**</span></span>

<span data-ttu-id="31cea-968">由于 SOC2 审核没有专门评估风险评估流程的一些要素，因此需要您：</span><span class="sxs-lookup"><span data-stu-id="31cea-968">As SOC2 audits do not specifically assess some elements of risk assessment processes, this will require you to:</span></span>

* <span data-ttu-id="31cea-969">证明至少每年进行一次正式的风险评估。</span><span class="sxs-lookup"><span data-stu-id="31cea-969">Demonstrate that a formal risk assessment is conducted at least annually.</span></span>

<span data-ttu-id="31cea-970">*事件响应。*</span><span class="sxs-lookup"><span data-stu-id="31cea-970">*Incident Response.*</span></span>

<span data-ttu-id="31cea-971">由于 SOC2 审核没有专门评估事件响应策略和流程的一些要素，因此，这将要求您：</span><span class="sxs-lookup"><span data-stu-id="31cea-971">As SOC2 audits do not specifically assess some elements of incident response policies and processes, this will require you to:</span></span>

* <span data-ttu-id="31cea-972">证明事件响应计划/过程包括：</span><span class="sxs-lookup"><span data-stu-id="31cea-972">Demonstrate that the incident response plan/procedure includes:</span></span>

<span data-ttu-id="31cea-973">&emsp;&#x2713;预期威胁模型的特定响应过程。</span><span class="sxs-lookup"><span data-stu-id="31cea-973">&emsp;&#x2713; Specific response procedures for expected threat models.</span></span>

<span data-ttu-id="31cea-974">&emsp;&#x2713;记录的通信过程，以确保及时通知关键利益干系人 (支付品牌/收购者、监管机构、监管机构、控制器、客户等。</span><span class="sxs-lookup"><span data-stu-id="31cea-974">&emsp;&#x2713; Documented communications process to ensure timely notification of key stakeholders (payment brands/acquirers, regulatory bodies, supervisory authorities, directors, customers, etc.</span></span>

## <a name="appendix-f"></a><span data-ttu-id="31cea-975">附录 F</span><span class="sxs-lookup"><span data-stu-id="31cea-975">Appendix F</span></span>

### <a name="hosting-deployment-types"></a><span data-ttu-id="31cea-976">托管部署类型</span><span class="sxs-lookup"><span data-stu-id="31cea-976">Hosting Deployment Types</span></span>

<span data-ttu-id="31cea-977">Microsoft 确认你将在不同的托管环境中部署应用程序并存储应用/外接程序代码。</span><span class="sxs-lookup"><span data-stu-id="31cea-977">Microsoft acknowledges you will deploy applications and store app/add-in code within different hosting environments.</span></span> <span data-ttu-id="31cea-978">Microsoft 365 认证中某些安全控件的整体职责取决于所使用的托管环境。</span><span class="sxs-lookup"><span data-stu-id="31cea-978">The overall responsibilities of some of the security controls within the Microsoft 365 Certification will depend on the hosting environment being used.</span></span> <span data-ttu-id="31cea-979">附录 F 查看常见部署类型，并针对评估过程中评估的安全控件进行映射。</span><span class="sxs-lookup"><span data-stu-id="31cea-979">Appendix F looks at common deployment types and maps these against the security controls that are evaluated as part of the assessment process.</span></span> <span data-ttu-id="31cea-980">已确定以下托管部署类型：</span><span class="sxs-lookup"><span data-stu-id="31cea-980">The following hosting deployment types have been identified:</span></span>

|  |  |
|-----|------|
|<span data-ttu-id="31cea-981">**ISV 托管**</span><span class="sxs-lookup"><span data-stu-id="31cea-981">**ISV Hosted**</span></span>|<span data-ttu-id="31cea-982">ISV 托管类型可以定义为你负责用于支持应用/外接程序环境的基础结构。</span><span class="sxs-lookup"><span data-stu-id="31cea-982">ISV hosted types can be defined as where you are responsible for the infrastructure used to support the app/add-in environment.</span></span> <span data-ttu-id="31cea-983">这可以在物理上位于您自己的数据中心或具有共同位置服务的第三方数据中心内。</span><span class="sxs-lookup"><span data-stu-id="31cea-983">This can be physically located within your own data centers or third-party data centers with a co-location service.</span></span> <span data-ttu-id="31cea-984">最终，您拥有对支持基础结构和操作环境的完全所有权和管理控制。</span><span class="sxs-lookup"><span data-stu-id="31cea-984">Ultimately, you have full ownership and administrative control over the supporting infrastructure and operating environment.</span></span>|
|<span data-ttu-id="31cea-985">**IaaS (服务)  (**https://azure.microsoft.com/en-gb/overview/what-is-iaas/)</span><span class="sxs-lookup"><span data-stu-id="31cea-985">**Infrastructure as a Service (IaaS)** (https://azure.microsoft.com/en-gb/overview/what-is-iaas/)</span></span>|<span data-ttu-id="31cea-986">基础结构即服务是一项服务提供的服务，通过该服务，云服务提供商和云解决方案提供商代表其 (基础结构) 。</span><span class="sxs-lookup"><span data-stu-id="31cea-986">Infrastructure as a Service is a service that is provided whereby the physical supporting infrastructure is managed and maintained on their behalf by the cloud service provider (CSP).</span></span> <span data-ttu-id="31cea-987">通常，云解决方案提供商负责网络、存储、物理服务器和虚拟化基础结构。</span><span class="sxs-lookup"><span data-stu-id="31cea-987">Typically, networking, storage, physical servers, and the virtualization infrastructure is all the responsibility of the CSP.</span></span> <span data-ttu-id="31cea-988">操作系统、中间件、运行时、数据和应用程序由你负责。</span><span class="sxs-lookup"><span data-stu-id="31cea-988">The Operating System, Middleware, Runtime, Data and Applications are the responsibilities of you.</span></span> <span data-ttu-id="31cea-989">防火墙功能也将由第三方进行管理和维护，但维护防火墙规则基础通常仍由消费者负责。</span><span class="sxs-lookup"><span data-stu-id="31cea-989">Firewalling capabilities would also be managed and maintained by the third-party, however maintenance of the firewall rule base would usually be still the consumers responsibility.</span></span>|
|<span data-ttu-id="31cea-990">**PaaS (平台作为服务/无)  (**https://azure.microsoft.com/en-gb/overview/what-is-paas/)</span><span class="sxs-lookup"><span data-stu-id="31cea-990">**Platform as a Service/Serverless (PaaS)** (https://azure.microsoft.com/en-gb/overview/what-is-paas/)</span></span>| <span data-ttu-id="31cea-991">借助平台即服务，你可以预配提供可以使用的服务的托管平台。</span><span class="sxs-lookup"><span data-stu-id="31cea-991">With Platform as a Service, you are provisioned with a managed platform presenting a service that can be consumed.</span></span> <span data-ttu-id="31cea-992">无需执行 sysadmin 功能，因为操作系统和支持基础结构由 CSP 管理。</span><span class="sxs-lookup"><span data-stu-id="31cea-992">You do not need to perform sysadmin functions as the operating system and supporting infrastructure is managed by the CSP.</span></span> <span data-ttu-id="31cea-993">当组织不希望呈现 Web 服务，而是专注于创建 Web 应用程序源代码和在云托管 Web 服务上发布 Web 应用程序时，通常会使用这种方法。</span><span class="sxs-lookup"><span data-stu-id="31cea-993">This would typically be used when organizations do not want to be concerned with presenting a web service and instead can concentrate on creating the web application source code and publishing the web application on the cloud managed web services.</span></span>  <span data-ttu-id="31cea-994">另一个示例可能是数据库服务，其中向数据库提供连接，但支持基础结构和数据库应用程序从使用者抽象。</span><span class="sxs-lookup"><span data-stu-id="31cea-994">Another example may be a database service where connectivity is given to a database, however the supporting infrastructure and database application is abstracted from the consumer.</span></span>   <span data-ttu-id="31cea-995">**注意：无服务器和 PaaS 类似，因此对于 Microsoft 365 认证托管部署类型的无服务器和 PasS，这两者被视为相同**</span><span class="sxs-lookup"><span data-stu-id="31cea-995">**Note: Serverless and PaaS are similar so for the purpose of the Microsoft 365 Certification Hosting Deployment Type's Serverless and PasS are deemed the same**</span></span>|
|<span data-ttu-id="31cea-996">**混合托管**</span><span class="sxs-lookup"><span data-stu-id="31cea-996">**Hybrid Hosted**</span></span>|<span data-ttu-id="31cea-997">使用混合托管类型，可以利用多种托管类型来支持支持环境的各个部分。</span><span class="sxs-lookup"><span data-stu-id="31cea-997">With the hybrid hosted type, you may utilize multiple hosted types to support various parts of the supporting environment.</span></span> <span data-ttu-id="31cea-998">这可能是在多个 M365 堆栈中利用应用/外接程序的情况。</span><span class="sxs-lookup"><span data-stu-id="31cea-998">This may be more the case where apps/add-ins are utilized across multiple M365 stacks.</span></span> <span data-ttu-id="31cea-999">尽管 Microsoft 365 认证将支持跨多个 M365 服务开发应用/加载项，但需要根据每个适用的"托管类型映射"评估跨应用/外接程序) 支持环境的整个 (。</span><span class="sxs-lookup"><span data-stu-id="31cea-999">Although the Microsoft 365 Certification will support where apps/add-ons across multiple M365 services are developed, an assessment of the entire (across app/add-ins) supporting environment would need to be assessed in line with each of the applicable "Hosted Type Mappings".</span></span> <span data-ttu-id="31cea-1000">有时，您可以对单个外接程序使用不同的托管类型，如果执行的是这一点，则条件的适用性仍然需要在各种托管类型中遵循"托管类型映射"条件。</span><span class="sxs-lookup"><span data-stu-id="31cea-1000">Occasionally, you may utilize different hosted types for a single add-in, where this is being carried out, applicability of criteria will need to still follow the "Hosted Type Mappings" criteria across the various hosted types.</span></span>|
|<span data-ttu-id="31cea-1001">**共享托管**</span><span class="sxs-lookup"><span data-stu-id="31cea-1001">**Shared Hosting**</span></span>|<span data-ttu-id="31cea-1002">共享托管是你将环境托管在由多个单个使用者共享的平台中的地方。</span><span class="sxs-lookup"><span data-stu-id="31cea-1002">Shared hosting is where you are hosting the environment within a platform that shared by multiple individual consumers.</span></span> <span data-ttu-id="31cea-1003">由于采用云，共享托管并不常见，因此未编写 Microsoft 365 认证规范来说明这一点。</span><span class="sxs-lookup"><span data-stu-id="31cea-1003">The Microsoft 365 Certification Specification was not written to account for this due to the adoption of cloud, shared hosting is not common.</span></span> <span data-ttu-id="31cea-1004">如果认为正在使用此功能，请联系 Microsoft，因为需要创建其他要求，以考虑此类型托管类型下的其他风险。</span><span class="sxs-lookup"><span data-stu-id="31cea-1004">If you believe this is being used please contact Microsoft as additional requirements will need to be created to account for the additional risks under this type of hosting type.</span></span>|


## <a name="appendix-g"></a><span data-ttu-id="31cea-1005">附录 G</span><span class="sxs-lookup"><span data-stu-id="31cea-1005">Appendix G</span></span>

### <a name="microsoft-365-certification-process-workflow"></a><span data-ttu-id="31cea-1006">Microsoft 365 认证流程工作流</span><span class="sxs-lookup"><span data-stu-id="31cea-1006">Microsoft 365 Certification Process Workflow</span></span>

![工作流](ProcessFlow.jpg)

## <a name="learn-more"></a><span data-ttu-id="31cea-1008">了解详细信息</span><span class="sxs-lookup"><span data-stu-id="31cea-1008">Learn more</span></span>

[<span data-ttu-id="31cea-1009">Microsoft 365 应用合规性计划概述</span><span class="sxs-lookup"><span data-stu-id="31cea-1009">Microsoft 365 App Compliance Program Overview</span></span>](~/overview.md)  
[<span data-ttu-id="31cea-1010">什么是 Microsoft 365 应用发布服务器证明？</span><span class="sxs-lookup"><span data-stu-id="31cea-1010">What is Microsoft 365 App Publisher Attestation?</span></span>](~/docs/attestation.md)  
[<span data-ttu-id="31cea-1011">什么是 Microsoft 365 认证？</span><span class="sxs-lookup"><span data-stu-id="31cea-1011">What is Microsoft 365 Certification?</span></span>](~/docs/enterprise-app-certification-guide.md)

## <a name="glossary"></a><span data-ttu-id="31cea-1012">术语表</span><span class="sxs-lookup"><span data-stu-id="31cea-1012">Glossary</span></span>

### <a name="aia"></a><span data-ttu-id="31cea-1013">AIA</span><span class="sxs-lookup"><span data-stu-id="31cea-1013">AIA</span></span>

<span data-ttu-id="31cea-1014">\*颁发机构信息访问是一种服务位置描述符，用于查找证书颁发机构证书。</span><span class="sxs-lookup"><span data-stu-id="31cea-1014">\*Authority Information Access is a service location descriptor used to find the certificate of the issuing certificate authority.</span></span>

### <a name="crl"></a><span data-ttu-id="31cea-1015">CRL</span><span class="sxs-lookup"><span data-stu-id="31cea-1015">CRL</span></span>

<span data-ttu-id="31cea-1016">\*证书吊销列表为安全套接字层 (SSL) 终结点提供了一种验证从远程主机收到的证书是否有效和可信赖的方式。</span><span class="sxs-lookup"><span data-stu-id="31cea-1016">\*Certificate Revocation List provide a means for a Secure Sockets Layer (SSL) endpoint to verify that a certificate received from a remote host is valid and trustworthy.</span></span>

### <a name="cvss-score"></a><span data-ttu-id="31cea-1017">CVSS 分数</span><span class="sxs-lookup"><span data-stu-id="31cea-1017">CVSS score</span></span>

<span data-ttu-id="31cea-1018">\*常见漏洞评分系统是一个已发布的标准，用于衡量漏洞并基于漏洞的严重性计算数字分数。</span><span class="sxs-lookup"><span data-stu-id="31cea-1018">\*Common Vulnerability Scoring System is a published standard that measures vulnerability and calculates a numerical score based on its severity.</span></span>

### <a name="cvss-patch-management-guidelines"></a><span data-ttu-id="31cea-1019">CVSS 修补程序管理指南</span><span class="sxs-lookup"><span data-stu-id="31cea-1019">CVSS patch management guidelines</span></span>

* <span data-ttu-id="31cea-1020">Critical (9.0 - 10.0) </span><span class="sxs-lookup"><span data-stu-id="31cea-1020">Critical (9.0 - 10.0)</span></span>
* <span data-ttu-id="31cea-1021">高 (7.0 - 8.9) </span><span class="sxs-lookup"><span data-stu-id="31cea-1021">High (7.0 - 8.9)</span></span>
* <span data-ttu-id="31cea-1022">中等 (4.0 - 6.9) </span><span class="sxs-lookup"><span data-stu-id="31cea-1022">Medium (4.0 - 6.9)</span></span>
* <span data-ttu-id="31cea-1023">低 (0.0 - 3.9) </span><span class="sxs-lookup"><span data-stu-id="31cea-1023">Low (0.0 - 3.9)</span></span>

### <a name="dmz"></a><span data-ttu-id="31cea-1024">DMZ</span><span class="sxs-lookup"><span data-stu-id="31cea-1024">DMZ</span></span>

<span data-ttu-id="31cea-1025">\*安全区域是物理或逻辑中间网络，可直接与外部或非属性网络交互，同时使主机的内部专用网络保持独立。</span><span class="sxs-lookup"><span data-stu-id="31cea-1025">\*Demilitarized zone is a physical or logical intermediate network that interacts directly external or non-propriety networks while keeping the host's internal, private network separate and isolated.</span></span>

### <a name="euii"></a><span data-ttu-id="31cea-1026">EUII</span><span class="sxs-lookup"><span data-stu-id="31cea-1026">EUII</span></span>

<span data-ttu-id="31cea-1027">*最终用户可识别信息*。</span><span class="sxs-lookup"><span data-stu-id="31cea-1027">*End-user identifiable information*.</span></span>

### <a name="gdpr"></a><span data-ttu-id="31cea-1028">GDPR</span><span class="sxs-lookup"><span data-stu-id="31cea-1028">GDPR</span></span>

<span data-ttu-id="31cea-1029">\*一般数据保护条例是欧盟 (欧盟) 欧盟隐私和数据保护条例，适用于所有欧盟公民的数据，无论您的应用程序网站位于何处。</span><span class="sxs-lookup"><span data-stu-id="31cea-1029">\*General Data Protection Regulation is a European Union (EU) privacy and data protection regulation for all EU citizens’ data regardless of where your application site is located.</span></span>

### <a name="hsts"></a><span data-ttu-id="31cea-1030">HSTS</span><span class="sxs-lookup"><span data-stu-id="31cea-1030">HSTS</span></span>

<span data-ttu-id="31cea-1031">\*HTTP 严格传输安全利用 HTTP 响应标头，指示 Web 浏览器仅通过 HTTPS 访问内容。</span><span class="sxs-lookup"><span data-stu-id="31cea-1031">\*HTTP Strict Transport Security utilizes a HTTP response header instructing the web browser to only access content over HTTPS.</span></span>  <span data-ttu-id="31cea-1032">这是旨在防止降级攻击和 Cookie 劫持。</span><span class="sxs-lookup"><span data-stu-id="31cea-1032">This is designed to protect against downgrade attacks and cookie hijacking.</span></span>

### <a name="iec"></a><span data-ttu-id="31cea-1033">IEC</span><span class="sxs-lookup"><span data-stu-id="31cea-1033">IEC</span></span>

<span data-ttu-id="31cea-1034">\*国际工业委员会。</span><span class="sxs-lookup"><span data-stu-id="31cea-1034">\*International Electrotechnical Commission.</span></span>

### <a name="isms"></a><span data-ttu-id="31cea-1035">ISMS</span><span class="sxs-lookup"><span data-stu-id="31cea-1035">ISMS</span></span>

<span data-ttu-id="31cea-1036">\*信息安全管理系统。</span><span class="sxs-lookup"><span data-stu-id="31cea-1036">\*Information Security Management System.</span></span>

### <a name="isv"></a><span data-ttu-id="31cea-1037">ISV</span><span class="sxs-lookup"><span data-stu-id="31cea-1037">ISV</span></span>

<span data-ttu-id="31cea-1038">独立安全供应商是开发、营销和销售第三方软件和硬件平台上运行的软件的个人和组织。</span><span class="sxs-lookup"><span data-stu-id="31cea-1038">Independent Security Vendors are individuals and organizations who develop, market and sell software that runs on third-party software and hardware platforms.</span></span>

### <a name="iso-27001"></a><span data-ttu-id="31cea-1039">ISO 27001</span><span class="sxs-lookup"><span data-stu-id="31cea-1039">ISO 27001</span></span>

<span data-ttu-id="31cea-1040">信息安全管理系统规范框架，用于组织风险管理策略和过程过程中的所有技术控制。</span><span class="sxs-lookup"><span data-stu-id="31cea-1040">An information security management system specification framework for all technical controls in an organizations risk management policies and procedures processes.</span></span>

### <a name="lfi"></a><span data-ttu-id="31cea-1041">LFI</span><span class="sxs-lookup"><span data-stu-id="31cea-1041">LFI</span></span>

<span data-ttu-id="31cea-1042">*本地文件* 包含允许攻击者通过 Web 浏览器将文件包含在服务器上。</span><span class="sxs-lookup"><span data-stu-id="31cea-1042">*Local File Inclusion* allows an attacker to include files on a server through the web browser.</span></span>

### <a name="nist"></a><span data-ttu-id="31cea-1043">NIST</span><span class="sxs-lookup"><span data-stu-id="31cea-1043">NIST</span></span>

<span data-ttu-id="31cea-1044">美国国家标准协会 *(* NIST) （美国商务部的非监管机构）为美国公共部门组织提供指导，以评估和批准其预防、检测和响应网络攻击的能力。</span><span class="sxs-lookup"><span data-stu-id="31cea-1044">The *National Institute of Standards* (NIST), a non-regulatory agency of the U.S. Department of Commerce  provides guidance for private sector organizations in the US to assess and approve their ability to prevent, detect, and respond to cyber attacks.</span></span>

### <a name="non-significant-changes"></a><span data-ttu-id="31cea-1045">非重大更改</span><span class="sxs-lookup"><span data-stu-id="31cea-1045">Non-Significant changes</span></span>

* <span data-ttu-id="31cea-1046">次要 Bug 修复。</span><span class="sxs-lookup"><span data-stu-id="31cea-1046">Minor Bug fixes.</span></span>
* <span data-ttu-id="31cea-1047">性能改进较小。</span><span class="sxs-lookup"><span data-stu-id="31cea-1047">Minor performance improvements.</span></span>
* <span data-ttu-id="31cea-1048">操作系统/库/客户端和服务器应用程序修补程序。</span><span class="sxs-lookup"><span data-stu-id="31cea-1048">Operating systems/libraries/client and server application patches.</span></span>

### <a name="ocsp"></a><span data-ttu-id="31cea-1049">OCSP</span><span class="sxs-lookup"><span data-stu-id="31cea-1049">OCSP</span></span>

<span data-ttu-id="31cea-1050">*联机证书状态协议* 用于检查 X.509 数字证书的吊销状态。</span><span class="sxs-lookup"><span data-stu-id="31cea-1050">*Online Certificate Status Protocol* is used to check the revocation status of X.509 digital certificates.</span></span>

### <a name="oii"></a><span data-ttu-id="31cea-1051">OII</span><span class="sxs-lookup"><span data-stu-id="31cea-1051">OII</span></span>

<span data-ttu-id="31cea-1052">*组织可识别信息*。</span><span class="sxs-lookup"><span data-stu-id="31cea-1052">*Organizational identifiable information*.</span></span>

### <a name="owasp"></a><span data-ttu-id="31cea-1053">OWASP</span><span class="sxs-lookup"><span data-stu-id="31cea-1053">OWASP</span></span>

<span data-ttu-id="31cea-1054">*打开 Web 应用程序安全项目*。</span><span class="sxs-lookup"><span data-stu-id="31cea-1054">*Open Web Application Security Project*.</span></span>

### <a name="pci-dss"></a><span data-ttu-id="31cea-1055">PCI DSS</span><span class="sxs-lookup"><span data-stu-id="31cea-1055">PCI DSS</span></span>

<span data-ttu-id="31cea-1056">*支付卡行业数据安全标准*，一个维护全球信用卡数据安全标准的组织。</span><span class="sxs-lookup"><span data-stu-id="31cea-1056">*Payment Card Industry Data Security Standard*, an organization that maintains standards for the safety of cardholder data worldwide.</span></span>

### <a name="pen-testing"></a><span data-ttu-id="31cea-1057">笔测试</span><span class="sxs-lookup"><span data-stu-id="31cea-1057">Pen testing</span></span>

<span data-ttu-id="31cea-1058">*渗透测试* 是一种通过模拟恶意攻击来查找攻击者可以利用的安全漏洞来测试 Web 应用的方法。</span><span class="sxs-lookup"><span data-stu-id="31cea-1058">*Penetration testing* is a method of testing a web app by simulating malicious attacks to find security vulnerabilities that an attacker could exploit.</span></span>

### <a name="saml"></a><span data-ttu-id="31cea-1059">SAML</span><span class="sxs-lookup"><span data-stu-id="31cea-1059">SAML</span></span>

<span data-ttu-id="31cea-1060">*安全声明标记语言* 是一种在用户、标识提供程序和服务提供商之间交换身份验证和授权数据的开放式标准。</span><span class="sxs-lookup"><span data-stu-id="31cea-1060">*Security Assertion Markup Language* is s an open standard for exchanging authentication and authorization data between the user, the identity provider and the service provider.</span></span>

### <a name="sensitive-data"></a><span data-ttu-id="31cea-1061">敏感数据</span><span class="sxs-lookup"><span data-stu-id="31cea-1061">Sensitive Data</span></span>

* <span data-ttu-id="31cea-1062">访问控制数据。</span><span class="sxs-lookup"><span data-stu-id="31cea-1062">Access control data.</span></span>
* <span data-ttu-id="31cea-1063">客户内容。</span><span class="sxs-lookup"><span data-stu-id="31cea-1063">Customer content.</span></span>
* <span data-ttu-id="31cea-1064">最终用户标识信息。</span><span class="sxs-lookup"><span data-stu-id="31cea-1064">End-user identity information.</span></span>
* <span data-ttu-id="31cea-1065">支持数据。</span><span class="sxs-lookup"><span data-stu-id="31cea-1065">Support data.</span></span>
* <span data-ttu-id="31cea-1066">公共个人数据。</span><span class="sxs-lookup"><span data-stu-id="31cea-1066">Public personal data.</span></span>
* <span data-ttu-id="31cea-1067">最终用户假名信息。</span><span class="sxs-lookup"><span data-stu-id="31cea-1067">End-user pseudonymous information.</span></span>

### <a name="significant-changes"></a><span data-ttu-id="31cea-1068">重大更改</span><span class="sxs-lookup"><span data-stu-id="31cea-1068">Significant changes</span></span>

* <span data-ttu-id="31cea-1069">宿主环境的重定位。</span><span class="sxs-lookup"><span data-stu-id="31cea-1069">Relocation of the hosting environment.</span></span>
* <span data-ttu-id="31cea-1070">对支持基础结构的主要升级;例如，实现新防火墙、主要升级到面向前端的服务等。</span><span class="sxs-lookup"><span data-stu-id="31cea-1070">Major upgrades to the supporting infrastructure; for example, implementation of a new firewall, major upgrades to front facing services, etc.</span></span>
* <span data-ttu-id="31cea-1071">向你的应用添加功能和/或扩展。</span><span class="sxs-lookup"><span data-stu-id="31cea-1071">Addition of capabilities and /or extensions to your app.</span></span>
* <span data-ttu-id="31cea-1072">用于捕获其他敏感数据的应用更新。</span><span class="sxs-lookup"><span data-stu-id="31cea-1072">Updates to your app that capture additional sensitive Data.</span></span>
* <span data-ttu-id="31cea-1073">对应用数据流或授权模型所做的更改</span><span class="sxs-lookup"><span data-stu-id="31cea-1073">Changes to your app's data flows or authorization models</span></span>
* <span data-ttu-id="31cea-1074">添加 API 终结点或 API 终结点函数。</span><span class="sxs-lookup"><span data-stu-id="31cea-1074">Addition of API endpoints or API endpoint functions.</span></span>

### <a name="soc-2"></a><span data-ttu-id="31cea-1075">SOC 2</span><span class="sxs-lookup"><span data-stu-id="31cea-1075">SOC 2</span></span>

<span data-ttu-id="31cea-1076">*服务组织控制 2* 是一种技术审核过程，包含五项信任服务原则，以确保服务提供商安全地管理组织客户端的数据和隐私。</span><span class="sxs-lookup"><span data-stu-id="31cea-1076">*Service Organization Control 2*, a technical auditing procedure comprised of five Trust Service Principles to ensure that service providers securely manage the data and privacy for an organization's clients.</span></span>

### <a name="ssl"></a><span data-ttu-id="31cea-1077">SSL</span><span class="sxs-lookup"><span data-stu-id="31cea-1077">SSL</span></span>

<span data-ttu-id="31cea-1078">*安全套接字层*。</span><span class="sxs-lookup"><span data-stu-id="31cea-1078">*Secure Sockets Layer*.</span></span>

### <a name="tls"></a><span data-ttu-id="31cea-1079">TLS</span><span class="sxs-lookup"><span data-stu-id="31cea-1079">TLS</span></span>

<span data-ttu-id="31cea-1080">*传输层安全性*。</span><span class="sxs-lookup"><span data-stu-id="31cea-1080">*Transport Layer Security*.</span></span>
