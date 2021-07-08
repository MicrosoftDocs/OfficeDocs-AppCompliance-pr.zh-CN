---
title: Microsoft 365 应用合规计划
author: LGerrard
ms.author: Legerrar
description: 计划简介和概述
keywords: microsoft 365 m365 应用发布者证明认证
ms.topic: overview
ms.service: attestation
localization_priority: Priority
ms.openlocfilehash: c644414281f46696ff49f3b9eb1341f02e96f0ba
ms.sourcegitcommit: 78dbace87a9b5027ea5aa23a6be9b8c613bd06ce
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 07/07/2021
ms.locfileid: "53315112"
---
# <a name="microsoft-365-app-compliance-program"></a>Microsoft 365 应用合规计划

Microsoft 365 应用合规计划是实现应用安全性和合规性的一种三层方法。 每一层都在下一层的基础上构建 - 提供分层计划来让用户在 Microsoft 365 生态系统中使用应用时建立起所需的信心。 目前，该计划中的所有层都是自发的，由应用开发人员自行决定完成。 

我们的宗旨是：Microsoft 客户完全信任运行其组织的应用程序。

  ![实现应用合规性的三层方法](media/Microsoft-App-Compliance-Overview.png) 

## <a name="publisher-verification"></a>发布者验证

[发布者验证](https://docs.microsoft.com/azure/active-directory/develop/publisher-verification-overview)可帮助管理员和用户了解到应用开发人员与 Microsoft 标识平台集成的真实性。 当应用标记为经过发布者验证，这意味着发布者已使用已完成验证过程的 Microsoft 合作伙伴网络帐户验证了其标识，而且已将此 MPN 帐户与其应用程序注册进行了关联。
发布者验证适用于满足下列条件的应用：  
- 使用 OAuth 2.0 和 OpenID Connect 将用户登录，并使用 Microsoft Graph 等服务端 API 请求数据访问权限。 
- 已以多租户的身份在 Azure AD 中注册。  

> [!IMPORTANT]
> 发布者验证不会妨碍应用开发人员开始或完成发布者证明或 Microsoft 365 认证。 如果不适用于应用，则可能会跳过验证并可开始证明。

## <a name="publisher-attestation"></a>发布者证明

在[发布者证明](https://docs.microsoft.com/microsoft-365-app-certification/docs/enterprise-app-attestation-guide)中，开发人员分享有关其应用服务的一般性、数据处理和安全性与合规性信息。 这减少了 IT 管理员直接与应用发布者合作的需求。 对于已完成发布者证明的所有应用，可在一个位置，以一致的格式找到作出知情决策所需的全部信息。 目的是简化和加快应用采用流程，同时向用户保证其在自己租户中使用的应用符合其组织标准。

发布者证明适用于 WebApps 以及与以下 Microsoft 产品集成的所有应用：
-   Teams
-   Word
-   Excel
-   PowerPoint 
-   Outlook
- SharePoint
- Project
- OneNote

> [!IMPORTANT]
> Microsoft 不对所提供的信息进行验证。开发者仅确认证明文件和相应应用程序性能数据的真实性、准确性和完整性。 

## <a name="microsoft-365-certification"></a>Microsoft 365 认证
[Microsoft 365 认证](https://docs.microsoft.com/microsoft-365-app-certification/docs/enterprise-app-certification-guide)向组织提供保证和确信，肯定在使用 Microsoft Teams 应用时数据和隐私都得到充分的保护。 认证确认了应用解决方案与 Microsoft 技术兼容、符合云应用安全最佳做法且受到 Microsoft 支持。在此过程中，应用开发人员与第三方评估者合作，共同验证组织的安全性和合规性标准。 Microsoft 365 认证适用于符合 Publisher Attestation 资格的相同应用程序。 


