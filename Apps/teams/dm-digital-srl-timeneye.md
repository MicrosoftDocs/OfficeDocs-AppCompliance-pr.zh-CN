---
title: DM Digital SRL 的 Timeneye 应用程序信息
ms.author: elmalova
author: elenamalova
ms.date: 08/31/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Timeneye 的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: ab8d61b542baaacd406df7596ecdcd4d8c87e327
ms.sourcegitcommit: 23a1fdeaf3905ab5f7acfbb378c7c23aaedcdc29
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 09/03/2021
ms.locfileid: "58873737"
---
# <a name="timeneye"></a>Timeneye

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2021 年 8 月 31 日</p>

* <a href="https://teams.microsoft.com/l/app/015bf4ec-bc37-4931-9862-ef8686da652b" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001950" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

DM Digital SRL 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | Timeneye |
| ID | WA200001950 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | DM 数字 SRL |
| 合作伙伴网站的 URL | [https://www.dmdigital.it](https://www.dmdigital.it) |
| 隐私策略的 URL | [https://www.timeneye.com/privacy-policy](https://www.timeneye.com/privacy-policy) |
| 使用条款 URL | [https://www.timeneye.com/terms-and-conditions](https://www.timeneye.com/terms-and-conditions) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

DM Digital SRL 提供了此信息，这些信息与此应用程序如何收集和存储组织数据以及您的组织将拥有对应用收集的数据的控制有关。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph](https://docs.microsoft.com/graph/permissions-reference)所需的任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD 应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.Read | delegated | 事件 Start/End DateTime、事件主题、事件 ID、事件 Web URI。 根据日历事件生成建议。 | 事件 Start/End DateTime、事件主题、事件 ID、事件 Web URI。 能够将生成的建议链接到相关的日历事件。 | [56412014-bafe-474e-95b4-ebfea106a167](https://docs.microsoft.com/microsoft-365-app-certification/azure/56412014-bafe-474e-95b4-ebfea106a167) |
>| Calendars.Read.Shared | delegated | 事件 Start/End DateTime、事件主题、事件 ID、事件 Web URI。 我们使用此信息根据日历事件生成建议。 | 事件 Start/End DateTime、事件主题、事件 ID、事件 Web URI。 我们使用此信息将生成的建议链接到相关的日历事件。 | [56412014-bafe-474e-95b4-ebfea106a167](https://docs.microsoft.com/microsoft-365-app-certification/azure/56412014-bafe-474e-95b4-ebfea106a167) |
>| Directory.Read.All | delegated | 用户的组 ID。 我们使用此信息来检查用户是这些组的成员，以便可以同步其组的规划人员。 | 用户的组 ID。 我们使用此信息来检查用户是这些组的成员，以便可以同步其组的规划人员。 | [56412014-bafe-474e-95b4-ebfea106a167](https://docs.microsoft.com/microsoft-365-app-certification/azure/56412014-bafe-474e-95b4-ebfea106a167) |
>| Group.Read.All | delegated | 组名称、组 ID。 我们在同步规划器项目时使用这些信息。 | 组名称、组 ID。  | [56412014-bafe-474e-95b4-ebfea106a167](https://docs.microsoft.com/microsoft-365-app-certification/azure/56412014-bafe-474e-95b4-ebfea106a167) |
>| Tasks.Read | delegated | 任务列表名称、任务列表 ID。 在同步计划程序项目时，我们使用此信息。 | 任务列表名称、任务列表 ID。 在同步计划程序项目时，我们使用此信息。 | [56412014-bafe-474e-95b4-ebfea106a167](https://docs.microsoft.com/microsoft-365-app-certification/azure/56412014-bafe-474e-95b4-ebfea106a167) |
>| User.Read | delegated | email， name. 我们使用此信息登录用户/创建用户帐户 | email， name. 我们使用此信息登录用户/创建用户帐户 | [56412014-bafe-474e-95b4-ebfea106a167](https://docs.microsoft.com/microsoft-365-app-certification/azure/56412014-bafe-474e-95b4-ebfea106a167) |
>| User.ReadBasic.All | delegated | 用户名、电子邮件。 我们使用此信息，以便用户可以将其他用户从 Planner/Microsoft 导入到服务。 | 用户名、电子邮件。 在服务中创建新用户所需的基本信息。 | [56412014-bafe-474e-95b4-ebfea106a167](https://docs.microsoft.com/microsoft-365-app-certification/azure/56412014-bafe-474e-95b4-ebfea106a167) |
>| email | delegated | 电子邮件。 我们使用此信息登录用户/创建用户帐户 | 电子邮件。 我们使用此信息登录用户/创建用户帐户 | [56412014-bafe-474e-95b4-ebfea106a167](https://docs.microsoft.com/microsoft-365-app-certification/azure/56412014-bafe-474e-95b4-ebfea106a167) |
>| offline_access | delegated | 在用户未联机时同步 planner/calendar 所需的权限。 | 在用户未联机时同步 planner/calendar 所需的权限。 | [56412014-bafe-474e-95b4-ebfea106a167](https://docs.microsoft.com/microsoft-365-app-certification/azure/56412014-bafe-474e-95b4-ebfea106a167) |
>| openid | delegated | id_token。 通过 Microsoft SSO 登录用户 | id_token。 通过 Microsoft SSO 登录用户。 | [56412014-bafe-474e-95b4-ebfea106a167](https://docs.microsoft.com/microsoft-365-app-certification/azure/56412014-bafe-474e-95b4-ebfea106a167) |
>| 个人资料 | delegated | email， name. 我们使用此信息登录用户/创建用户帐户 | email， name.我们使用此信息登录用户/创建用户帐户 | [56412014-bafe-474e-95b4-ebfea106a167](https://docs.microsoft.com/microsoft-365-app-certification/azure/56412014-bafe-474e-95b4-ebfea106a167) |

#### <a name="data-access-using-other-microsoft-apis"></a>使用其他 Microsoft API 进行数据访问

基于组织构建的应用和Microsoft 365可以使用除 Microsoft Graph 外的其他 Microsoft API 来收集或处理 OII (组织) 。 列出此应用使用的任何 Microsoft GRAPH Microsoft API。

>| **API** |  **是否收集 OII？** |  **收集哪些 OII？** | **收集 OII 的理由？** | **是否存储 OII？** | **存储 OII 的理由** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| Outlook日历 API | 否 |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>非Microsoft 服务使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>不Microsoft 服务非活动。

#### <a name="data-access-via-bots"></a>通过机器人访问数据

如果此应用程序包含机器人或消息扩展，它可以访问最终用户可识别信息 (EUII) ：名单 (名字、姓氏、显示名称、电子邮件地址) （团队中任何团队成员的姓名、姓氏、电子邮件地址) 或添加到其中聊天）。 此应用是否使用了此功能？

>无法访问 EUII。


#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或最终用户可识别信息 (EUII) 是否出现在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>用户名和电子邮件、公司计费详细信息。 删除帐户/用户时，将删除该信息。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>我们不会将合理信息传递到我们的合作伙伴系统，但出于支持、票证和计费目的的用户电子邮件除外。 在系统中删除帐户时，将删除该信息。

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>是

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

DM Digital SRL 提供了此信息，这些信息与此应用程序如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件有关。

| **Information** | **响应** |
|:----------------|:-------------|
| 你是否与 Microsoft 标识平台 (Azure AD) ？  | 是 |
| 您是否已查看并遵循了集成清单中列出的所有适用的Microsoft 标识平台做法？  | 是 |
| 你的应用是否使用 MSAL (Microsoft 身份验证库) 进行身份验证？ | 是 |
| 你的应用是否支持条件访问策略？ | 否 |
| 应用是否请求方案最小特权权限？ | 是 |
| 应用的静态注册权限是否准确反映应用将动态和增量请求的权限？ | 是 |
| 你的应用是否支持多租户？ | 是 |
| 你的应用是否具有机密客户端？ | 是 |
| 你是否拥有为应用注册的所有重定向统一 (URI) URI？ | 是 |
| 对于你的应用，应避免使用什么？ | - 通配符重定向 URI，<br/>- OAuth2 隐式Flow，除非 SPA 需要<br/>- 资源所有者密码凭据 (ROPC) 流 |
| 你的应用是否公开任何 Web API？ | 是 |
| 您的权限模型是否仅在客户端应用程序收到正确同意时才允许呼叫成功？ | 是 |
| 你的应用是否使用预览 API？ | 否 |
| 你的应用是否使用已弃用 API？ | 是 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
