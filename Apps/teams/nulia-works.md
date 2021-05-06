---
title: Nulia Works 的应用程序信息（由 Nulia 提供）
ms.author: elmalova
author: elenamalova
ms.date: 03/11/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Nulia Works 的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 9650ee1b5595967b9bc11cce5ed29addacb264e3
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 05/06/2021
ms.locfileid: "52250600"
---
# <a name="nulia-works"></a>Nulia Works

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2021 年 3 月 11 日</p>

* <a href="https://teams.microsoft.com/l/app/e49e0f69-600c-460c-80b3-8809a9d97a4c" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002051" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

Nulia 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | Nulia Works |
| ID | WA200002051 |
| 功能 | 选项卡，连接器 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | Nulia |
| 合作伙伴网站的 URL | [https://nulia.com](https://nulia.com) |
| "Teams应用程序信息"页的 URL | [https://nulia.com/product](https://nulia.com/product) |
| 隐私策略的 URL | [https://nulia.com/privacy](https://nulia.com/privacy) |
| 使用条款 URL | [https://nulia.com/terms](https://nulia.com/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

Nulia 提供了此信息，这些信息与此应用程序如何收集和存储组织数据以及您的组织将拥有对应用收集的数据的控制有关。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph所需的](https://docs.microsoft.com/graph/permissions-reference)任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD 应用 ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.Read | 应用程序 | 我们使用收集的数据为用户对技能和结果的进度进行评分。 我们收集多个 O365 工作负荷的使用率计数。 | 我们将收集的所有数据存储在 blob 存储中。 我们使用此数据为用户对技能分数和结果进度进行评分。 例如，我们将计算用户具有的日历事件数。 该值会影响其技能进度。 | 我们为每个客户创建新的应用程序 ID。 例如，我们的 Nulia 租户使用应用程序 ID：623B1D5D-6D82-493E-9990-1FBFE82ED046 |
>| Contacts.Read | 应用程序 | 我们使用收集的数据为用户对技能和结果的进度进行评分。 我们收集多个 O365 工作负荷的使用率计数。 | 我们将收集的所有数据存储在 blob 存储中。 我们使用此数据为用户对技能分数和结果进度进行评分。 例如，我们将计算用户已创建的联系人数。 该值会影响其技能进度。 | 我们为每个客户创建新的应用程序 ID。 例如，我们的 Nulia 租户使用应用程序 ID：623B1D5D-6D82-493E-9990-1FBFE82ED046 |
>| Files.Read.All | 应用程序 | 我们使用收集的数据为用户对技能和结果的进度进行评分。 我们收集多个 O365 工作负荷的使用率计数。 | 我们将收集的所有数据存储在 blob 存储中。 我们使用此数据为用户对技能分数和结果进度进行评分。 例如，我们将计算用户正在与计算机同步的文件数。 该值会影响其技能进度。 | 我们为每个客户创建新的应用程序 ID。 例如，我们的 Nulia 租户使用应用程序 ID：623B1D5D-6D82-493E-9990-1FBFE82ED046 |
>| Group.Read.All | 应用程序 | 我们使用收集的数据为用户对技能和结果的进度进行评分。 我们收集多个 O365 工作负荷的使用率计数。 | 我们将收集的所有数据存储在 blob 存储中。 我们使用此数据为用户对技能分数和结果进度进行评分。 例如，我们会从组中检索Teams用户所属的用户。 该值会影响其技能进度。 | 我们为每个客户创建新的应用程序 ID。 例如，我们的 Nulia 租户使用应用程序 ID：623B1D5D-6D82-493E-9990-1FBFE82ED046 |
>| Mail.Read | 应用程序 | 我们使用收集的数据为用户对技能和结果的进度进行评分。 我们收集多个 O365 工作负荷的使用率计数。 | 我们将收集的所有数据存储在 blob 存储中。 我们使用此数据为用户对技能分数和结果进度进行评分。 例如，我们将计算用户已创建的自定义邮件文件夹的数量。 该值会影响其技能进度。 | 我们为每个客户创建新的应用程序 ID。 例如，我们的 Nulia 租户使用应用程序 ID：623B1D5D-6D82-493E-9990-1FBFE82ED046 |
>| MailboxSettings.Read | 应用程序 | 我们使用收集的数据为用户对技能和结果的进度进行评分。 我们收集多个 O365 工作负荷的使用率计数。 | 我们将收集的所有数据存储在 blob 存储中。 我们使用此数据为用户对技能分数和结果进度进行评分。 例如，我们查看用户是否设置了外出答复。 该值会影响其技能进度。 | 我们为每个客户创建新的应用程序 ID。 例如，我们的 Nulia 租户使用应用程序 ID：623B1D5D-6D82-493E-9990-1FBFE82ED046 |
>| Notes.Read | 应用程序 | 我们使用收集的数据为用户对技能和结果的进度进行评分。 我们收集多个 O365 工作负荷的使用率计数。 | 我们将收集的所有数据存储在 blob 存储中。 我们使用此数据为用户对技能分数和结果进度进行评分。 例如，我们将计算用户共享的笔记本数。 该值会影响其技能进度。 | 我们为每个客户创建新的应用程序 ID。 例如，我们的 Nulia 租户使用应用程序 ID：623B1D5D-6D82-493E-9990-1FBFE82ED046 |
>| Reports.Read.All | 应用程序 | 我们使用收集的数据为用户对技能和结果的进度进行评分。 我们收集多个 O365 工作负荷的使用率计数。 | 我们将收集的所有数据存储在 blob 存储中。 我们使用此数据为用户对技能分数和结果进度进行评分。 例如，我们会从用户报告中检索他们Teams发送的邮件。 该值会影响其技能进度。 | 我们为每个客户创建新的应用程序 ID。 例如，我们的 Nulia 租户使用应用程序 ID：623B1D5D-6D82-493E-9990-1FBFE82ED046 |
>| Sites.Read.All | 应用程序 | 我们使用收集的数据为用户对技能和结果的进度进行评分。 我们收集多个 O365 工作负荷的使用率计数。 | 我们将收集的所有数据存储在 blob 存储中。 我们使用此数据为用户对技能分数和结果进度进行评分。 例如，我们将计算用户创建的网站集的数量。 该值会影响其技能进度。 | 我们为每个客户创建新的应用程序 ID。 例如，我们的 Nulia 租户使用应用程序 ID：623B1D5D-6D82-493E-9990-1FBFE82ED046 |
>| User.Read | 应用程序 | 显示用户的个人资料、显示名称和个人资料图片。 | 我们将显示名称和部门保存在数据库中，因此无需每次Graph点击率。 我们不存储个人资料图片。 | 我们为每个客户创建新的应用程序 ID。 例如，我们的 Nulia 租户使用应用程序 ID：623B1D5D-6D82-493E-9990-1FBFE82ED046 |
>| Organization.Read.All | 应用程序 | 我们将收集租户的名称和Yammer URL。 当用户单击应用中与Yammer活动相关的"试用"按钮时，我们使用此按钮 &quot; &quot; Yammer应用。 | 我们将收集的所有数据存储在 blob 存储中。 例如，当用户单击应用中与Yammer活动相关的"试用"按钮时，我们使用此按钮Yammer &quot; &quot; 应用。 | 我们使用收集的数据为用户对技能和结果的进度进行评分。 我们收集多个 O365 工作负荷的使用率计数。 |


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

>我们不控制合作伙伴系统上的数据

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

下面将显示[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36557' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36557" target="_blank">在新建选项卡中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>标识信息

Nu一直提供有关此应用程序如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件的信息。

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
| 你是否拥有为应用注册的所有重定向统 (URI) URI？ | 是 |
| 对于你的应用，应避免使用什么？ | - 通配符重定向 URI，<br/>- OAuth2 隐式Flow，除非 SPA 需要<br/>- 资源所有者密码凭据 (ROPC) 流 |
| 你的应用是否公开任何 Web API？ | 是 |
| 您的权限模型是否仅在客户端应用程序收到正确同意时允许呼叫成功？ | 是 |
| 你的应用是否使用预览 API？ | 否 |
| 你的应用是否使用已弃用 API？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
