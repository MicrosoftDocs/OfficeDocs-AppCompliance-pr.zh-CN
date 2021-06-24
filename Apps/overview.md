---
title: Microsoft 365 应用合规计划
author: LGerrard
ms.author: Legerrar
description: 计划简介和概述
keywords: microsoft 365 m365 应用发布者证明认证
ms.topic: overview
ms.service: attestation
localization_priority: Priority
ms.openlocfilehash: fd06ecd028876a862fa3938253817fae3ff0fea0
ms.sourcegitcommit: 0d46955e7b4c0e1d4208843813793c382344b2f5
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 06/22/2021
ms.locfileid: "53053436"
---
# <a name="microsoft-365-app-compliance-program"></a><span data-ttu-id="e11b5-104">Microsoft 365 应用合规计划</span><span class="sxs-lookup"><span data-stu-id="e11b5-104">Microsoft 365 App Compliance Program</span></span>

<span data-ttu-id="e11b5-105">Microsoft 365 应用合规计划是实现应用安全性和合规性的一种三层方法。</span><span class="sxs-lookup"><span data-stu-id="e11b5-105">The Microsoft 365 App Compliance Program, is a three tier approach to app security and compliance.</span></span> <span data-ttu-id="e11b5-106">每一层都在下一层的基础上构建 - 提供分层计划来让用户在 Microsoft 365 生态系统中使用应用时建立起所需的信心。</span><span class="sxs-lookup"><span data-stu-id="e11b5-106">Each tier builds upon the next – offering a layered program to give users the confidence they need while using apps in the Microsoft 365 ecosystem.</span></span> <span data-ttu-id="e11b5-107">目前，该计划中的所有层都是自发的，由应用开发人员自行决定完成。</span><span class="sxs-lookup"><span data-stu-id="e11b5-107">Currently all tiers in the program are voluntary and are completed at the app developers discretion.</span></span> 

<span data-ttu-id="e11b5-108">我们的宗旨是：Microsoft 客户完全信任运行其组织的应用程序。</span><span class="sxs-lookup"><span data-stu-id="e11b5-108">Our mission statement: Microsoft customers have complete trust in the applications that run their organizations.</span></span>

  ![实现应用合规性的三层方法](media/Microsoft-App-Compliance-Overview.png) 

## <a name="publisher-verification"></a><span data-ttu-id="e11b5-110">发布者验证</span><span class="sxs-lookup"><span data-stu-id="e11b5-110">Publisher Verification</span></span>

<span data-ttu-id="e11b5-111">[发布者验证](https://docs.microsoft.com/azure/active-directory/develop/publisher-verification-overview)可帮助管理员和用户了解到应用开发人员与 Microsoft 标识平台集成的真实性。</span><span class="sxs-lookup"><span data-stu-id="e11b5-111">[Publisher Verification](https://docs.microsoft.com/azure/active-directory/develop/publisher-verification-overview) helps admins and users understand the authenticity of app developers integrating with the Microsoft identity platform.</span></span> <span data-ttu-id="e11b5-112">当应用标记为经过发布者验证，这意味着发布者已使用已完成验证过程的 Microsoft 合作伙伴网络帐户验证了其标识，而且已将此 MPN 帐户与其应用程序注册进行了关联。</span><span class="sxs-lookup"><span data-stu-id="e11b5-112">When an app is marked as publisher verified, it means that the publisher has verified their identity using a Microsoft Partner Network account that has completed the verification process and has associated this MPN account with their application registration.</span></span>
<span data-ttu-id="e11b5-113">发布者验证适用于满足下列条件的应用：</span><span class="sxs-lookup"><span data-stu-id="e11b5-113">Publisher Verification applies to apps that meet the following conditions:</span></span>  
- <span data-ttu-id="e11b5-114">使用 OAuth 2.0 和 OpenID Connect 将用户登录，并使用 Microsoft Graph 等服务端 API 请求数据访问权限。</span><span class="sxs-lookup"><span data-stu-id="e11b5-114">Using OAuth 2.0 and OpenID Connect to sign users in and request access to data using service-side APIs such as Microsoft Graph.</span></span> 
- <span data-ttu-id="e11b5-115">已以多租户的身份在 Azure AD 中注册。</span><span class="sxs-lookup"><span data-stu-id="e11b5-115">Registered in Azure AD as multi-tenant.</span></span>  

> [!IMPORTANT]
> <span data-ttu-id="e11b5-116">发布者验证不会妨碍应用开发人员开始或完成发布者证明或 Microsoft 365 认证。</span><span class="sxs-lookup"><span data-stu-id="e11b5-116">Publisher Verification does not preclude an app developer from starting or completing Publisher Attestation or Microsoft 365 Certification.</span></span> <span data-ttu-id="e11b5-117">如果不适用于应用，则可能会跳过验证并可开始证明。</span><span class="sxs-lookup"><span data-stu-id="e11b5-117">If it does not apply to the app verification may be skipped and the attestation can be started.</span></span>

## <a name="publisher-attestation"></a><span data-ttu-id="e11b5-118">发布者证明</span><span class="sxs-lookup"><span data-stu-id="e11b5-118">Publisher Attestation</span></span>

<span data-ttu-id="e11b5-119">在[发布者证明](https://docs.microsoft.com/microsoft-365-app-certification/docs/enterprise-app-attestation-guide)中，开发人员分享有关其应用服务的一般性、数据处理和安全性与合规性信息。</span><span class="sxs-lookup"><span data-stu-id="e11b5-119">[Publisher Attestation](https://docs.microsoft.com/microsoft-365-app-certification/docs/enterprise-app-attestation-guide) is where developers share general, data handling, and security and compliance information about their app service.</span></span> <span data-ttu-id="e11b5-120">这减少了 IT 管理员直接与应用发布者合作的需求。</span><span class="sxs-lookup"><span data-stu-id="e11b5-120">This reduces the need for IT admins to work directly with app publishers.</span></span> <span data-ttu-id="e11b5-121">对于已完成发布者证明的所有应用，可在一个位置，以一致的格式找到作出知情决策所需的全部信息。</span><span class="sxs-lookup"><span data-stu-id="e11b5-121">All the information needed to make an informed decision can be found for all apps that have completed the publisher attestation in one place and in a consistent format.</span></span> <span data-ttu-id="e11b5-122">目的是简化和加快应用采用流程，同时向用户保证其在自己租户中使用的应用符合其组织标准。</span><span class="sxs-lookup"><span data-stu-id="e11b5-122">The goal is to make it easier and speed up the process of app adoption while assuring customers that the apps they use in their tenants meets their organizational standards.</span></span>

<span data-ttu-id="e11b5-123">发布者证明适用于与下列 Microsoft 平台集成的应用：</span><span class="sxs-lookup"><span data-stu-id="e11b5-123">Publisher Attestation applies to apps that integrate with these Microsoft platforms:</span></span>
-   <span data-ttu-id="e11b5-124">Teams</span><span class="sxs-lookup"><span data-stu-id="e11b5-124">Teams</span></span>
-   <span data-ttu-id="e11b5-125">Word</span><span class="sxs-lookup"><span data-stu-id="e11b5-125">Word</span></span>
-   <span data-ttu-id="e11b5-126">Excel</span><span class="sxs-lookup"><span data-stu-id="e11b5-126">Excel</span></span>
-   <span data-ttu-id="e11b5-127">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="e11b5-127">PowerPoint</span></span> 
-   <span data-ttu-id="e11b5-128">Outlook</span><span class="sxs-lookup"><span data-stu-id="e11b5-128">Outlook</span></span>
- <span data-ttu-id="e11b5-129">SharePoint</span><span class="sxs-lookup"><span data-stu-id="e11b5-129">SharePoint</span></span>
- <span data-ttu-id="e11b5-130">Project</span><span class="sxs-lookup"><span data-stu-id="e11b5-130">Project</span></span>
- <span data-ttu-id="e11b5-131">OneNote</span><span class="sxs-lookup"><span data-stu-id="e11b5-131">OneNote</span></span>
- <span data-ttu-id="e11b5-132">Web 应用程序</span><span class="sxs-lookup"><span data-stu-id="e11b5-132">Web Apps</span></span>

> [!IMPORTANT]
> <span data-ttu-id="e11b5-p105">Microsoft 不对所提供的信息进行验证。开发者仅确认证明文件和相应应用程序性能数据的真实性、准确性和完整性。</span><span class="sxs-lookup"><span data-stu-id="e11b5-p105">Microsoft does not validate the information provided. The developer, solely affirms the veracity, accuracy, and integrity of the attestation documentation and corresponding app performance data.</span></span> 

## <a name="microsoft-365-certification"></a><span data-ttu-id="e11b5-135">Microsoft 365 认证</span><span class="sxs-lookup"><span data-stu-id="e11b5-135">Microsoft 365 Certification</span></span>
<span data-ttu-id="e11b5-136">[Microsoft 365 认证](https://docs.microsoft.com/microsoft-365-app-certification/docs/enterprise-app-certification-guide)向组织提供保证和确信，肯定在使用 Microsoft Teams 应用时数据和隐私都得到充分的保护。</span><span class="sxs-lookup"><span data-stu-id="e11b5-136">The [Microsoft 365 Certification](https://docs.microsoft.com/microsoft-365-app-certification/docs/enterprise-app-certification-guide) offers assurance and confidence to organizations that data and privacy are adequately secured and protected when using Microsoft Teams apps.</span></span> <span data-ttu-id="e11b5-137">认证确认了应用解决方案与 Microsoft 技术兼容、符合云应用安全最佳做法且受到 Microsoft 支持。</span><span class="sxs-lookup"><span data-stu-id="e11b5-137">Certification confirms that an app solution is compatible with Microsoft technologies, compliant with cloud app security best practices, and supported by Microsoft.</span></span><span data-ttu-id="e11b5-138">在此过程中，应用开发人员与第三方评估者合作，共同验证组织的安全性和合规性标准。</span><span class="sxs-lookup"><span data-stu-id="e11b5-138"> During this process, app developers work with a third-party assessor to validate organizational security and compliance standards.</span></span> <span data-ttu-id="e11b5-139">Microsoft 365 认证适用于符合 Publisher Attestation 资格的相同应用程序。</span><span class="sxs-lookup"><span data-stu-id="e11b5-139">Microsoft 365 Certification applies to the same apps that qualify for the Publisher Attestation.</span></span> 


