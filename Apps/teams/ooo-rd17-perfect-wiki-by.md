---
title: 由 RD17 通过 OOO RD17 设置完美 Wiki 的应用程序信息
ms.author: elmalova
author: elenamalova
ms.date: 08/16/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: RD17 为完美 Wiki 提供的所有安全和合规性信息、其数据处理策略、Microsoft Cloud App Security 应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: deacceb8c77fd935e6ff7dd03fe8195042b8e259
ms.sourcegitcommit: b1e752ea527ba6049cdc4f5d12cbd5b4dbd7f5b3
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 08/27/2021
ms.locfileid: "58673078"
---
# <a name="perfect-wiki-by-rd17"></a>RD17 完美 Wiki

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2021 年 8 月 16 日</p>

* <a href="https://teams.microsoft.com/l/app/40906836-4323-4bbe-875e-3cbb134c40a2" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001679" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

OOO RD17 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | RD17 完美 Wiki |
| ID | WA200001679 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | OOO RD17 |
| 合作伙伴网站的 URL | [https://perfectwikiforteams.com](https://perfectwikiforteams.com) |
| "Teams应用程序信息"页的 URL | [https://perfectwikiforteams.com](https://perfectwikiforteams.com) |
| 隐私策略的 URL | [https://docs.google.com/document/d/e/2PACX-1vQHouhjK2Qof_NK...](https://docs.google.com/document/d/e/2PACX-1vQHouhjK2Qof_NKFVucpN44PO30SFZHDfxWhu-u5wlZI56UW7v3bT-WCM4zH4ZaWGzQR7lnoUpVyU1S/pub) |
| 使用条款 URL | [https://docs.google.com/document/d/e/2PACX-1vTMQNAdgN7xy6n9...](https://docs.google.com/document/d/e/2PACX-1vTMQNAdgN7xy6n9tNvhDe8Sb2AF8A9v8jfG3gJ503cXzIq1nr_Zbq5aShN0mU49fvADgKZ8a58Oha-C/pub) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

OOO RD17 提供了此信息，这些信息与此应用程序如何收集和存储组织数据以及您的组织将拥有对应用收集的数据的控制有关。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph所需的](https://docs.microsoft.com/graph/permissions-reference)任何 Microsoft 权限。

>| **权限**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD 应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Channel.ReadBasic.All | delegated | ChannelId 和 channelName，我们获取该信息以在应用中显示用户 | 我们存储 channelId 和 channelName 以稍后向用户显示 | [b9604964-9c3a-483e-abf2-1b5cba495081](https://docs.microsoft.com/microsoft-365-app-certification/azure/b9604964-9c3a-483e-abf2-1b5cba495081) |
>| Team.ReadBasic.All | delegated | 获取用户的 teamId 并获取团队名称 | teamId 和 teamName，我们使用它来了解哪个团队用户属于哪个团队用户 | [b9604964-9c3a-483e-abf2-1b5cba495081](https://docs.microsoft.com/microsoft-365-app-certification/azure/b9604964-9c3a-483e-abf2-1b5cba495081) |
>| User.Read | delegated | userId，用于了解登录的用户 | 哈希 userId，用于登录用户和从 DB 获取关联数据 | [b9604964-9c3a-483e-abf2-1b5cba495081](https://docs.microsoft.com/microsoft-365-app-certification/azure/b9604964-9c3a-483e-abf2-1b5cba495081) |


#### <a name="non-microsoft-services-used"></a>非Microsoft 服务使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>不Microsoft 服务非活动。

#### <a name="data-access-via-bots"></a>通过机器人访问数据

如果此应用程序包含机器人或消息扩展，则它可以访问最终用户可识别信息 (EUII) ：名单 (名字、姓氏、显示名称、电子邮件地址) （团队中任何团队成员的姓名、姓氏、电子邮件地址) 或添加到其中聊天）。 此应用是否使用了此功能？

>无法访问 EUII。


#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或 EUII (最终用户可识别) 是否显示在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>应用程序遥测或日志中不显示 OII 或 EUII。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>我们对合作伙伴系统的任何操作使用基于角色的访问控制

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

下面将显示[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/" target="_blank">在新建选项卡中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>标识信息

OOO RD17 提供了此应用如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件的信息。

| **Information** | **响应** |
|:----------------|:-------------|
| 你是否与 Microsoft 标识平台 (Azure AD) ？  | 是 |
| 您是否已查看并遵循了 Microsoft 标识平台 清单中列出的所有适用最佳做法？  | 是 |
| 你的应用是否使用 MSAL (Microsoft 身份验证库) 进行身份验证？ | 是 |
| 你的应用是否支持条件访问策略？ | 否 |
| 应用是否请求方案最小特权权限？ | 是 |
| 应用的静态注册权限是否准确反映应用将动态和增量请求的权限？ | 是 |
| 你的应用是否支持多租户？ | 是 |
| 你的应用是否具有机密客户端？ | 是 |
| 你是否拥有为应用注册的所有 (统一) URI？ | 是 |
| 对于你的应用，应避免使用什么？ | - 通配符重定向 URI，<br/>- OAuth2 隐式Flow，除非 SPA 需要<br/>- 资源所有者密码凭据 (ROPC) 流 |
| 你的应用是否公开任何 Web API？ | 是 |
| 您的权限模型是否仅在客户端应用程序收到正确同意时才允许呼叫成功？ | 是 |
| 你的应用是否使用预览 API？ | 否 |
| 你的应用是否使用已弃用 API？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
