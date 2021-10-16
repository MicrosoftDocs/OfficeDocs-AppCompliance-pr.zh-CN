---
title: Appfluence Inc 的优先级矩阵的应用程序信息
ms.author: elmalova
author: elenamalova
ms.date: 06/23/2021
ms.topic: article
ms.service: attestation
certification_type: certified
description: 优先级矩阵的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: f92d80badce772b5de28faef4a6330b58ea204c1
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 10/16/2021
ms.locfileid: "60413103"
---
# <a name="priority-matrix"></a>Priority Matrix

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>开发人员上次更新时间：2021 年 6 月 23 日</p>

* <a href="https://teams.microsoft.com/l/app/5be2b320-a5b7-4221-893c-dee506e4e365" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA104382005" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

Appfluence Inc 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | Priority Matrix |
| ID | WA104382005 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | Appence Inc |
| 合作伙伴网站的 URL | [https://appfluence.com/office-365-project-management-integr...](https://appfluence.com/office-365-project-management-integration/) |
| "Teams应用程序信息"页的 URL | [https://appfluence.com/project-management-integration-for-m...](https://appfluence.com/project-management-integration-for-microsoft-teams/) |
| 隐私策略的 URL | [https://appfluence.com/privacy/](https://appfluence.com/privacy/) |
| 使用条款 URL | [https://appfluence.com/eula](https://appfluence.com/eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

Appfluence Inc 提供了此信息，这些信息与此应用程序如何收集和存储组织数据以及您的组织将拥有对应用收集的数据的控制有关。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph](https://docs.microsoft.com/graph/permissions-reference)所需的任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.Read | delegated | 只有在将新用户添加到帐户时，我们才存储他们的电子邮件。 | 在新建帐户时，我们使用它来建议其他团队成员。 | [5be2b320-a5b7-4221-893c-dee506e4e365](https://docs.microsoft.com/microsoft-365-app-certification/azure/5be2b320-a5b7-4221-893c-dee506e4e365) |
>| User.ReadBasic.All | delegated | 只有在将新用户添加到帐户时，我们才存储他们的电子邮件。 | 在新建帐户时，我们使用它来建议其他团队成员。 | [5be2b320-a5b7-4221-893c-dee506e4e365](https://docs.microsoft.com/microsoft-365-app-certification/azure/5be2b320-a5b7-4221-893c-dee506e4e365) |
>| offline_access | delegated | 我们存储登录令牌是为了代表用户执行请求 | 刷新令牌，无需打扰用户。  (优先级矩阵Teams)  | [5be2b320-a5b7-4221-893c-dee506e4e365](https://docs.microsoft.com/microsoft-365-app-certification/azure/5be2b320-a5b7-4221-893c-dee506e4e365) |
>| Files.Read.All | delegated | 我们不会存储任何文件信息，除非用户明确且有意创建链接到原始文件的优先级矩阵项。 | 在我们的通过 Web 应用和 Outlook/Teams 外接程序 () 提供的一对一功能) 中，我们使用此功能突出显示系统中两个用户之间共享的 SharePoint/OneDrive 文件，以便促进会议和总体协作。 | [affadfb6-f17b-428f-97f9-9aae3b6175bc](https://docs.microsoft.com/microsoft-365-app-certification/azure/affadfb6-f17b-428f-97f9-9aae3b6175bc) |
>| User.Read | delegated | 基本用户配置文件信息 (显示名称、名字、姓氏、电子邮件、头像) 我们存储。 | 获取用户的姓名、电子邮件、头像，以向我们个性化设置其帐户。 | [affadfb6-f17b-428f-97f9-9aae3b6175bc](https://docs.microsoft.com/microsoft-365-app-certification/azure/affadfb6-f17b-428f-97f9-9aae3b6175bc) |
>| openid | delegated | 存储 SSO 连接以指示用户的登录模式。 | 为了通过单一登录登录用户。 | [affadfb6-f17b-428f-97f9-9aae3b6175bc](https://docs.microsoft.com/microsoft-365-app-certification/azure/affadfb6-f17b-428f-97f9-9aae3b6175bc) |
>| Calendars.Read | delegated | 少量日历事件将转换为系统中存储的任务。 | 读取日历事件，以便它们可以显示在一对一视图中。 还初始化新帐户。  | [d76f016f-52c7-41b5-835b-900361d7040c](https://docs.microsoft.com/microsoft-365-app-certification/azure/d76f016f-52c7-41b5-835b-900361d7040c) |
>| Mail.Read | delegated | 我们将系统中创建的任务与原始邮件的链接一起存储。 | 在我们的Outlook中用于将电子邮件转换为任务，以及以一对一视图显示共享工作。 | [d76f016f-52c7-41b5-835b-900361d7040c](https://docs.microsoft.com/microsoft-365-app-certification/azure/d76f016f-52c7-41b5-835b-900361d7040c) |
>| Tasks.Read | delegated | 有些Outlook/Planner 任务将在我们的系统中复制，以帮助新用户。 | 我们启动新用户帐户及其Graph任务。 | [d76f016f-52c7-41b5-835b-900361d7040c](https://docs.microsoft.com/microsoft-365-app-certification/azure/d76f016f-52c7-41b5-835b-900361d7040c) |


#### <a name="non-microsoft-services-used"></a>非Microsoft 服务已使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>不Microsoft 服务非活动。

#### <a name="data-access-via-bots"></a>通过机器人访问数据

如果此应用程序包含机器人或消息扩展，则它可以访问最终用户可识别信息 (EUII) ：名单 (名字、姓氏、显示名称、电子邮件地址) （团队中任何团队成员的姓名、姓氏、电子邮件地址) 或添加到其中聊天）。 此应用是否使用了此功能？

>| **访问 EUII 的理由？**  | **EUII 是否存储在数据库 () ？** | **存储 EUII 的理由** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| 机器人能够创建任务并将其分配给特定的团队成员，因此需要知道他们的姓名。 | 否 |  |


#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或 EUII (最终用户可识别) 是否显示在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>是的，我们将用户的电子邮件用作他们在系统中的唯一 ID，用于跟踪应用程序错误，并跟踪系统 (下载、登录、应用程序版本等) 以便我们的客户服务团队可以针对客户查询提供提示响应。 作为 GDPR 合规性的一部分，我们将在删除请求的 2 周内删除所有客户数据，尽管实际上我们在同一天这样做，因为我们有内部脚本以半自动方式完成此操作。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>应用程序数据安全地存储在加密数据库中，且访问权限仅限于一小组管理员。 为了进一步保证访问安全，我们强制执行双重身份验证，限制对一组受控 IP 地址的访问，并在其专用子网中定位数据库，直接从开放 Internet 访问。

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

下面将显示[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35667' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35667" target="_blank">在新建选项卡中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>标识信息

Appfluence Inc 已提供有关此应用如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件的信息。

| **Information** | **响应** |
|:----------------|:-------------|
| 是否与 Microsoft 标识平台 (Azure AD) ？  | 是 |
| 您是否已审阅并遵循了 Microsoft 标识平台 集成清单中列出的所有适用最佳做法？  | 是 |
| 你的应用是否使用 MSAL (Microsoft 身份验证库) 进行身份验证？ | 否 |
| 你的应用是否支持条件访问策略？ | 否 |
| 应用是否请求方案最小特权权限？ | 是 |
| 应用的静态注册权限是否准确反映应用将动态和增量请求的权限？ | 是 |
| 你的应用是否支持多租户？ | 是 |
| 你的应用是否具有机密客户端？ | 是 |
| 你是否拥有为应用注册的所有 (统一) URI？ | 是 |
| 对于你的应用，应避免使用什么？ | - 通配符重定向 URI，<br/><br/>- 资源所有者密码凭据 (ROPC) 流 |
| 你的应用是否公开任何 Web API？ | 是 |
| 您的权限模型是否仅在客户端应用程序收到正确同意时才允许呼叫成功？ | 是 |
| 你的应用是否使用预览 API？ | 否 |
| 你的应用是否使用已弃用 API？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

