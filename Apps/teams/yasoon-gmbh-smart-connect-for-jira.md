---
title: 用于 Jira 连接应用程序信息（由 yasoon GmbH）
ms.author: elmalova
author: elenamalova
ms.date: 07/22/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Smart 连接 for Jira 的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security 应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 4342897ef390842396e62798debc54e146a979e3
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 10/16/2021
ms.locfileid: "60413253"
---
# <a name="smart-connect-for-jira"></a>Smart Connect for Jira

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2021 年 7 月 21 日</p>

* <a href="https://teams.microsoft.com/l/app/6402de97-ce33-4386-bf28-b37e9e139c09" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002055" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

yasoon GmbH 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | Smart Connect for Jira |
| ID | WA200002055 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | yasoon GmbH |
| 合作伙伴网站的 URL | [https://www.yasoon.com](https://www.yasoon.com) |
| 应用程序Teams页的 URL | [https://yasoon.com/microsoft-teams-for-jira/](https://yasoon.com/microsoft-teams-for-jira/) |
| 隐私策略的 URL | [https://yasoon.com/privacy-policy-services/](https://yasoon.com/privacy-policy-services/) |
| 使用条款 URL | [https://pinpointprod.blob.core.windows.net/marketing/Partne...](https://pinpointprod.blob.core.windows.net/marketing/Partner_21474846970/Product_42949680957/Asset_3f25ec80-eacb-454f-8cc2-eeee583b65c6/170825EULAOfficeaddinEN.doc) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

此信息由 yasoon GmbH 提供，用于了解此应用如何收集和存储组织数据，以及组织将拥有对应用收集的数据的控制。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph所需的](https://docs.microsoft.com/graph/permissions-reference)任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Channel.ReadBasic.All | delegated | 该权限用于让用户选择 Jira 中加入的频道之一。 | 通道 ID，用于缓存 | [89d5ca9f-d63b-4885-bd30-6e7433c1540c](https://docs.microsoft.com/microsoft-365-app-certification/azure/89d5ca9f-d63b-4885-bd30-6e7433c1540c) |
>| ChannelMessage.Read.Group | 应用程序 | 允许应用在 Jira 中显示链接的频道消息。 | 用于将邮件链接到 Jira 问题的邮件 ID | [89d5ca9f-d63b-4885-bd30-6e7433c1540c](https://docs.microsoft.com/microsoft-365-app-certification/azure/89d5ca9f-d63b-4885-bd30-6e7433c1540c) |
>| ChannelMessage.Send | delegated | 没有使用数据，此 API 用于让用户从 Jira 回复频道消息。 | 无 | [89d5ca9f-d63b-4885-bd30-6e7433c1540c](https://docs.microsoft.com/microsoft-365-app-certification/azure/89d5ca9f-d63b-4885-bd30-6e7433c1540c) |
>| ChannelSettings.Read.Group | 应用程序 | 用于查找有关频道的详细信息。 | 无 | [89d5ca9f-d63b-4885-bd30-6e7433c1540c](https://docs.microsoft.com/microsoft-365-app-certification/azure/89d5ca9f-d63b-4885-bd30-6e7433c1540c) |
>| Chat.ReadWrite | delegated | 用于允许用户向聊天添加新回复并查看来自 Jira 的聊天消息。 | 无 | [89d5ca9f-d63b-4885-bd30-6e7433c1540c](https://docs.microsoft.com/microsoft-365-app-certification/azure/89d5ca9f-d63b-4885-bd30-6e7433c1540c) |
>| Member.Read.Group | 应用程序 | 用于权限检查，允许应用验证用户的团队成员身份。 | 无 | [89d5ca9f-d63b-4885-bd30-6e7433c1540c](https://docs.microsoft.com/microsoft-365-app-certification/azure/89d5ca9f-d63b-4885-bd30-6e7433c1540c) |
>| Team.ReadBasic.All | delegated | 该权限用于让用户选择 Jira 中加入的团队之一。 | 用于缓存的团队 ID | [89d5ca9f-d63b-4885-bd30-6e7433c1540c](https://docs.microsoft.com/microsoft-365-app-certification/azure/89d5ca9f-d63b-4885-bd30-6e7433c1540c) |
>| TeamSettings.Read.Group | 应用程序 | 允许应用读取团队设置以遵守某些默认值。 | 无 | [89d5ca9f-d63b-4885-bd30-6e7433c1540c](https://docs.microsoft.com/microsoft-365-app-certification/azure/89d5ca9f-d63b-4885-bd30-6e7433c1540c) |
>| User.ReadBasic.All | delegated | 允许用户在频道消息中选择同事 @-mention | 无 | [89d5ca9f-d63b-4885-bd30-6e7433c1540c](https://docs.microsoft.com/microsoft-365-app-certification/azure/89d5ca9f-d63b-4885-bd30-6e7433c1540c) |


#### <a name="non-microsoft-services-used"></a>非Microsoft 服务使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>| **所有非 Microsoft 服务 OII 将转移到** |  **转移了哪些 OII？** | **转移 OII 的理由？** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| 可以在此处看到 Atlassian Jira 以及我们的承包商之一： https://go.yasoon.com/contractors | 邮件元数据 (ID、时间戳) 、用户和组织元数据 (用户 ID、组织 id) 和用户电子邮件地址 | 支持应用功能 (例如，将 Atlassian 帐户与 Office 帐户) 并支持更快地解决问题。 |

#### <a name="data-access-via-bots"></a>通过机器人访问数据

如果此应用包含机器人或消息扩展，则它可以访问最终用户可识别信息 (EUII) ：名单 (名字、姓氏、显示名称、电子邮件地址) （团队中任何团队成员的姓名、姓氏、电子邮件地址) 或添加到其中聊天）。 此应用是否使用了此功能？

>| **访问 EUII 的理由？**  | **EUII 是否存储在数据库 (中) ？** | **存储 EUII 的理由** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| 将用户Teams用户 Atlassian Jira 帐户匹配 | 否 |  |


#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或 EUII (最终用户可识别) 是否显示在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>用户元数据 (id) 

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>我们仅处理提供严格数据隐私保证的服务。 

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

下面将显示[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36422' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36422" target="_blank">在新建选项卡中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>标识信息

此信息由 yasoon GmbH 提供有关此应用如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件的信息。

| **Information** | **响应** |
|:----------------|:-------------|
| 是否与 Microsoft 标识平台 (Azure AD) ？  | 是 |
| 您是否已审阅并遵循了 Microsoft 标识平台 集成清单中列出的所有适用最佳做法？  | 是 |
| 你的应用是否使用 MSAL (Microsoft 身份验证库) 进行身份验证？ | 是 |
| 你的应用是否支持条件访问策略？ | 否 |
| 应用是否请求方案最小特权权限？ | 是 |
| 应用的静态注册权限是否准确反映应用将动态和增量请求的权限？ | 是 |
| 你的应用是否支持多租户？ | 是 |
| 你的应用是否具有机密客户端？ | 否 |
| 你是否拥有为应用注册的所有 (统一) URI？ | 是 |
| 对于你的应用，应避免使用什么？ | - 通配符重定向 URI，<br/>- OAuth2 隐式Flow，除非 SPA 需要<br/>- 资源所有者密码凭据 (ROPC) 流 |
| 你的应用是否公开任何 Web API？ | 否 |
| 你的应用是否使用预览 API？ | 否 |
| 你的应用是否使用已弃用 API？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

