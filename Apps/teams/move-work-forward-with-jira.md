---
title: 通过移动工作转发通过 Jira 转发工作的应用程序信息
ms.author: elmalova
author: elenamalova
ms.date: 06/10/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: 有关通过 Jira 推进工作的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security 应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 7120519c2ecb0643465760677b2bef895b1e2f4d
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 07/22/2021
ms.locfileid: "53521263"
---
# <a name="move-work-forward-with-jira"></a>使用 Jira 推动工作

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2021 年 6 月 10 日</p>

* <a href="https://teams.microsoft.com/l/app/79ca2e8f-dd2c-40d5-897e-1b22d41038fe" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002855" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

将工作转发到 Microsoft 提供的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | 使用 Jira 推动工作 |
| ID | WA200002855 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | 推动工作 |
| 合作伙伴网站的 URL | [https://www.moveworkforward.com](https://www.moveworkforward.com) |
| "Teams应用程序信息"页的 URL | [https://www.moveworkforward.com/product/microsoft-teams-jir...](https://www.moveworkforward.com/product/microsoft-teams-jira-connector) |
| 隐私策略的 URL | [https://www.moveworkforward.com/privacy-policy](https://www.moveworkforward.com/privacy-policy) |
| 使用条款 URL | [https://www.moveworkforward.com/license-agreement/eula](https://www.moveworkforward.com/license-agreement/eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

此信息由"移动工作转发"提供，用于了解此应用如何收集和存储组织数据，以及组织将拥有对应用收集的数据的控制。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph所需的](https://docs.microsoft.com/graph/permissions-reference)任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD 应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Channel.Create | delegated | 用于创建问题讨论频道。 | 新创建的频道的 Web URL 将存储为在 Jira 中显示，以便快速访问 Microsoft Teams讨论频道。 | [39d845a0-3fa2-4fba-acc2-61afe40cfcea](https://docs.microsoft.com/microsoft-365-app-certification/azure/39d845a0-3fa2-4fba-acc2-61afe40cfcea) |
>| Channel.ReadBasic.All | delegated | 通道名称和 id 用于将通知从 Jira 发送到 Microsoft Teams。 | 存储通道 ID 和名称以配置从 Jira 到 Microsoft Teams。 | [39d845a0-3fa2-4fba-acc2-61afe40cfcea](https://docs.microsoft.com/microsoft-365-app-certification/azure/39d845a0-3fa2-4fba-acc2-61afe40cfcea) |
>| Team.ReadBasic.All | delegated | 该权限用于让用户选择 Jira 中加入的团队之一。 | 在 Jira 的配置屏幕中显示的团队 ID 和名称。 | [39d845a0-3fa2-4fba-acc2-61afe40cfcea](https://docs.microsoft.com/microsoft-365-app-certification/azure/39d845a0-3fa2-4fba-acc2-61afe40cfcea) |
>| TeamsAppInstallation.ReadForTeam | delegated | 读取团队Teams安装的应用。 当设置发送到Microsoft Teams应用可以发送到安装了自动Teams的计算机。 | Nothing | [39d845a0-3fa2-4fba-acc2-61afe40cfcea](https://docs.microsoft.com/microsoft-365-app-certification/azure/39d845a0-3fa2-4fba-acc2-61afe40cfcea) |
>| User.Read | delegated | 允许用户与同事一起创建讨论频道，在频道消息中单击 @-mention | Nothing | [39d845a0-3fa2-4fba-acc2-61afe40cfcea](https://docs.microsoft.com/microsoft-365-app-certification/azure/39d845a0-3fa2-4fba-acc2-61afe40cfcea) |
>| email | delegated | 电子邮件用于匹配 Atlassian 和 Microsoft 用户 | 不存储电子邮件。 仅在匹配过程中使用。 | [39d845a0-3fa2-4fba-acc2-61afe40cfcea](https://docs.microsoft.com/microsoft-365-app-certification/azure/39d845a0-3fa2-4fba-acc2-61afe40cfcea) |


#### <a name="non-microsoft-services-used"></a>非Microsoft 服务使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>不Microsoft 服务非活动。

#### <a name="data-access-via-bots"></a>通过机器人访问数据

如果此应用程序包含机器人或消息扩展，则它可以访问最终用户可识别信息 (EUII) ：名单 (名字、姓氏、显示名称、电子邮件地址) （团队中任何团队成员的姓名、姓氏、电子邮件地址) 或添加到其中聊天）。 此应用是否使用了此功能？

>| **访问 EUII 的理由？**  | **EUII 是否存储在数据库 (中) ？** | **存储 EUII 的理由** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| 安装应用时，按名称欢迎用户。 匹配 Microsoft Teams 和 Atlassian 用户。 | 不支持 |  |


#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或 EUII (最终用户可识别) 是否显示在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>我们将记录租户 URL，此 URL 在日志中存储最多 5 天。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>我们仅处理提供严格数据隐私保证的服务。

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>不支持

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

下面将显示[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/39108' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/39108" target="_blank">在新建选项卡中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>标识信息

此信息由 Move Work Forward 提供有关此应用如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件的信息。

| **Information** | **响应** |
|:----------------|:-------------|
| 你是否与 Microsoft 标识平台 (Azure AD) ？  | 是 |
| 您是否已查看并遵循了 Microsoft 标识平台 清单中列出的所有适用最佳做法？  | 是 |
| 你的应用是否使用 MSAL (Microsoft 身份验证库) 进行身份验证？ | 是 |
| 你的应用是否支持条件访问策略？ | 不支持 |
| 应用是否请求方案最小特权权限？ | 是 |
| 应用的静态注册权限是否准确反映应用将动态和增量请求的权限？ | 是 |
| 你的应用是否支持多租户？ | 是 |
| 你的应用是否具有机密客户端？ | 不支持 |
| 你是否拥有为应用注册的所有重定向统 (URI) URI？ | 是 |
| 对于你的应用，应避免使用什么？ | - 通配符重定向 URI，<br/><br/>- 资源所有者密码凭据 (ROPC) 流 |
| 你的应用是否公开任何 Web API？ | 不支持 |
| 你的应用是否使用预览 API？ | 不支持 |
| 你的应用是否使用已弃用 API？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
