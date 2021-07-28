---
title: Springworks HR Tech 针对 Trivia 的应用程序信息
ms.author: elmalova
author: elenamalova
ms.date: 01/13/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Trivia 的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: e22205d2584abd257a6fdff585f129fb915ff6b2
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 07/22/2021
ms.locfileid: "53528358"
---
# <a name="trivia"></a>Trivia

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2021 年 1 月 13 日</p>

* <a href="https://teams.microsoft.com/l/app/391082c3-968b-47b1-9c92-b5daf008000b" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001956" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

Springworks HR Tech 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | Trivia |
| ID | WA200001956 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | Springworks HR Tech |
| 合作伙伴网站的 URL | [https://www.springworks.in](https://www.springworks.in) |
| "Teams应用程序信息"页的 URL | [https://www.springworks.in/trivia](https://www.springworks.in/trivia) |
| 隐私策略的 URL | [https://trivia.springworks.in/policy](https://trivia.springworks.in/policy) |
| 使用条款 URL | [https://trivia.springworks.in/tnc](https://trivia.springworks.in/tnc) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

此信息由 Springworks HR Tech 提供有关此应用程序如何收集和存储组织数据以及您的组织将拥有对应用程序收集的数据的控制的信息。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph所需的](https://docs.microsoft.com/graph/permissions-reference)任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD 应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Group.Read.All | delegated | 不支持 | 获取用户Teams的用户列表 | [43bc466a-7678-476f-b904-2d933c5bbfc3](https://docs.microsoft.com/microsoft-365-app-certification/azure/43bc466a-7678-476f-b904-2d933c5bbfc3) |
>| Team.ReadBasic.All | delegated | 是，存储已添加自动程序的团队列表 | 收集有关工作区中所有团队的基本信息 | [43bc466a-7678-476f-b904-2d933c5bbfc3](https://docs.microsoft.com/microsoft-365-app-certification/azure/43bc466a-7678-476f-b904-2d933c5bbfc3) |
>| User.Read.All | delegated | 是，用于存储用户的唯一 aadObjectId。 用户的各种详细信息，如用户名、电子邮件等，并显示在 Trivia 仪表板上 | 获取工作区中所有用户的详细信息 | [43bc466a-7678-476f-b904-2d933c5bbfc3](https://docs.microsoft.com/microsoft-365-app-certification/azure/43bc466a-7678-476f-b904-2d933c5bbfc3) |
>| openid | delegated | 是，用于存储登录应用的用户。 |  允许用户将应用与帐户一同使用，允许应用使用用户数据 | [43bc466a-7678-476f-b904-2d933c5bbfc3](https://docs.microsoft.com/microsoft-365-app-certification/azure/43bc466a-7678-476f-b904-2d933c5bbfc3) |
>| 个人资料 | delegated | 是，用于存储测验和其他功能的用户 ID 和主机名称，并唯一标识它们 | 若要读取用户的基本个人资料信息（如用户名、电子邮件） | [43bc466a-7678-476f-b904-2d933c5bbfc3](https://docs.microsoft.com/microsoft-365-app-certification/azure/43bc466a-7678-476f-b904-2d933c5bbfc3) |


#### <a name="non-microsoft-services-used"></a>非Microsoft 服务使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>| **所有非Microsoft 服务 OII 将转移到** |  **转移了哪些 OII？** | **转移 OII 的理由？** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| AWS、Mailchimp、Stripe。  | 客户名称、电子邮件、IP、付款信息 | 我们使用这些第三方来为客户提供最佳客户体验 |

#### <a name="data-access-via-bots"></a>通过机器人访问数据

如果此应用程序包含机器人或消息扩展，则它可以访问最终用户可识别信息 (EUII) ：名单 (名字、姓氏、显示名称、电子邮件地址) （团队中任何团队成员的姓名、姓氏、电子邮件地址) 或添加到其中聊天）。 此应用是否使用了此功能？

>| **访问 EUII 的理由？**  | **EUII 是否存储在数据库 (中) ？** | **存储 EUII 的理由** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| 此数据用于显示和存储测验和其他此类功能的参与者列表 | 名称、电子邮件 | 是，存储测验的主机和参与者的数据，以及用于分析和与主机通信的其他功能（如果出现错误） |


#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或 EUII (最终用户可识别) 是否显示在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>OII：组织名称，租户 ID 显示在日志中;EUII：aad 对象 ID、全名、电子邮件显示在日志中。 我们有 30 天的保留期，之后日志将自动删除。 


#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>存储在 RDS、AWS 中的数据。 已加密。 访问权限仅对一位DevOps工程师、工程主管和创建者访问

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>是

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

下面将显示[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36138' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36138" target="_blank">在新建选项卡中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>标识信息

此信息由 Springworks HR Tech 提供有关此应用程序如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件的信息。

| **Information** | **响应** |
|:----------------|:-------------|
| 你是否与 Microsoft 标识平台 (Azure AD) ？  | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
