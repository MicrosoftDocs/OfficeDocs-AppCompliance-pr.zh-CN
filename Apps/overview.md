---
title: Microsoft 365 应用合规计划
author: LGerrard
ms.author: Legerrar
description: 计划简介和概述
keywords: microsoft 365 m365 应用发布者证明认证
ms.topic: overview
ms.service: attestation
localization_priority: Priority
ms.openlocfilehash: 17aab158f4fc7803966afed9df88adf9688fcc63
ms.sourcegitcommit: af065aeee2812a85ead9e0de968fc474204a6e8a
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 03/22/2022
ms.locfileid: "63697064"
---
# <a name="microsoft-365-app-compliance-program"></a>Microsoft 365 应用合规计划

Microsoft 365 应用合规性计划是应用安全性和合规性的两个步骤方法，包括发布者验证和 Microsoft 365 认证。 每一层都在下一层的基础上构建 - 提供分层计划来让用户在 Microsoft 365 生态系统中使用应用时建立起所需的信心。  

我们的宗旨是：Microsoft 客户完全信任运行其组织的应用程序。

![实现应用合规性的两层方法](media/Microsoft365AppComplianceBanner.png)

## <a name="publisher-verification"></a>发布者验证

[发布者验证](https://docs.microsoft.com/azure/active-directory/develop/publisher-verification-overview)可帮助管理员和用户了解到应用开发人员与 Microsoft 标识平台集成的真实性。 当应用标记为经过发布者验证，这意味着发布者已使用已完成验证过程的 Microsoft 合作伙伴网络帐户验证了其标识，而且已将此 MPN 帐户与其应用程序注册进行了关联。
发布者验证适用于满足下列条件的应用：  
- 使用 OAuth 2.0 和 OpenID Connect 将用户登录，并使用 Microsoft Graph 等服务端 API 请求数据访问权限。 
- 已以多租户的身份在 Azure AD 中注册。  

> [!IMPORTANT]
> 发布者验证不会妨碍应用开发人员开始或完成发布者证明或 Microsoft 365 认证。 如果不适用于应用，则可能会跳过验证并可开始证明。

## <a name="microsoft-365-certification"></a>Microsoft 365 认证
Microsoft 365 认证过程分为两个阶段： **证明** 和 **认证**。
1.  **证明** 涉及完成有关客户最重要的应用的安全性、数据处理和合规性属性的调查表。 然后，所有信息都以一致、易于阅读的格式在一处发布。 目的是简化和加快应用采用流程，同时向用户保证其在自己租户中使用的应用符合其组织标准。
1.  **认证** 是指根据一组源自领先行业标准框架的控制措施对应用进行全面审核。 在获得认证之前，系统将要求 ISV 提供证据以证明他们满足每个控制措施的要求。 目标是向客户保证，他们可以信任应用，确保已收到 Microsoft 365 认证的应用具有强大的安全性和合规性，以保护他们的数据安全性和隐私。


Microsoft 365认证适用于与以下 Microsoft 产品集成的所有应用：
-   Teams
-   Word
-   Excel
-   PowerPoint 
-   Outlook
- SharePoint
- Project
- OneNote
- **Web 应用** （合作伙伴中心中通过商业市场发布的 SaaS 应用目前为个人预览版，如果你有兴趣参与，请填写此 [表单](https://forms.microsoft.com/Pages/ResponsePage.aspx?id=v4j5cvGGr0GRqy180BHbR3Om82jEdWlAkFiVJRhmM_xUQkY0SjVVOVVLR0RUN0RYNlRWMDRTSjVQRy4u)。

### <a name="get-started"></a>入门
- [如何完成发布者验证](https://docs.microsoft.com/azure/active-directory/develop/mark-app-as-publisher-verified)
- [如何完成 Microsoft 365 认证](https://docs.microsoft.com/microsoft-365-app-certification/docs/certification)

