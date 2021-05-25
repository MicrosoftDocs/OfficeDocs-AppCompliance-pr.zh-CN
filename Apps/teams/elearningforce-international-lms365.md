---
title: ELEARNINGFORCE International 的 LMS365 应用程序信息
ms.author: elmalova
author: elenamalova
ms.date: 03/18/2021
ms.topic: article
ms.service: attestation
certification_type: certified
description: LMS365 的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security 应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: f8e10bb30857c055ab4916c4f944225d50ef44ba
ms.sourcegitcommit: abce882d3e2ca5b9b0b47fc4a26c01e6e111a9b4
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 05/24/2021
ms.locfileid: "52629657"
---
# <a name="lms365"></a>LMS365

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>开发人员上次更新时间：2021 年 3 月 18 日</p>

* <a href="https://teams.microsoft.com/l/app/d136f17e-df84-47f2-97a4-13aa24c0c647" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381467" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

ELEARNINGFORCE International 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | LMS365 |
| ID | WA104381467 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | ELEARNINGFORCE International |
| 合作伙伴网站的 URL | [https://www.elearningforce.com](https://www.elearningforce.com) |
| "Teams应用程序信息"页的 URL | [https://www.elearningforce.com/teams](https://www.elearningforce.com/teams) |
| 隐私策略的 URL | [https://www.elearningforce.com/privacy](https://www.elearningforce.com/privacy) |
| 使用条款 URL | [https://www.elearningforce.com/LMS365-SaaS-Terms](https://www.elearningforce.com/LMS365-SaaS-Terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

此信息由 ELEARNINGFORCE International 提供有关此应用程序如何收集和存储组织数据以及您的组织将拥有对应用收集的数据的控制的信息。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph所需的](https://docs.microsoft.com/graph/permissions-reference)任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD 应用 ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| GroupMember.Read.All | 应用程序 | 无 | 允许应用扩展 AD 组的成员，这是将一组用户注册到课程所必需的。 | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| Mail.Send | delegated | 无 | 在配置用于通知的电子邮件帐户期间动态请求权限。 允许应用发送通知电子邮件 | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| RoleManagement.Read.Directory | 应用程序 | 无 | 允许应用在SharePoint期间获取域。 域用于 URL 构造。 | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| User.Invite.All | delegated | 无 | 允许应用代表当前登录的用户邀请外部用户 | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| User.Read | delegated | 无 | 登录并读取用户配置文件。 | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| User.Read.All | delegated | 无 | 允许应用读取当前登录用户的完整个人资料。 | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| User.Read.All | 应用程序 | 允许应用读取完整的用户配置文件。 需要&#8217;用户和管理员&#8217;构建层次结构报告。 | 以下个人数据存储在专用数据库中，供相应客户在应用程序中用于管理管理器仪表板 &amp; 功能。 帐户名称、用户显示名称、电子邮件地址、部门、职务、Office、国家/地区、城市、经理 ID/电子邮件 | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| 个人资料 | delegated | 无 | 查看用户的基本个人资料。 | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |

#### <a name="data-access-using-other-microsoft-apis"></a>使用其他 Microsoft API 进行数据访问

基于组织构建的应用和加载项Microsoft 365除 Microsoft Graph 外的其他 Microsoft API 来收集或处理 OII (组织) 。 列出除 Microsoft API Graph此应用使用的任何 Microsoft API。

>| **API** |  **是否收集 OII？** |  **收集哪些 OII？** | **收集 OII 的理由？** | **是否存储 OII？** | **存储 OII 的理由** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| SharePoint | 否 |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>非Microsoft 服务使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>不Microsoft 服务非活动。

#### <a name="data-access-via-bots"></a>通过机器人访问数据

如果此应用程序包含机器人或消息扩展，则它可以访问最终用户可识别信息 (EUII) ：名单 (名字、姓氏、显示名称、电子邮件地址) （团队中任何团队成员的姓名、姓氏、电子邮件地址) 或添加到其中聊天）。 此应用是否使用了此功能？

>| **访问 EUII 的理由？**  | **EUII 是否存储在数据库 (中) ？** | **存储 EUII 的理由** |
>|:--------------------------------|:---------------------|:--------------------------|
>| 我们仅在机器人欢迎用户时使用名字来显示个性化消息。 | 个人数据存储在专用 Azure 数据库中，供相应客户在 LMS365 应用程序中用于管理管理器仪表板功能 &amp; 。 | 帐户名称、用户显示名称、电子邮件地址、部门、职务、Office、国家/地区、城市、经理 ID/电子邮件 |


#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或 EUII (最终用户可识别) 是否显示在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>是的，我们使用 Insights Log Analytics 遥测/日志，这些遥测/日志仅用于问题处理，并且保留策略为 90 天，之后将删除所有数据。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>LMS365 配备了清除功能，可删除客户端 LMS365 数据库的任何个人数据。

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

下面将显示[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35695' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35695" target="_blank">在新建选项卡中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>标识信息

此信息由 ELEARNINGFORCE International 提供有关此应用程序如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件的信息。

| **Information** | **响应** |
|:----------------|:-------------|
| 你是否与 Microsoft 标识平台 (Azure AD) ？  | 是 |
| 您是否已查看并遵循了 Microsoft 标识平台 清单中列出的所有适用最佳做法？  | 是 |
| 你的应用是否使用 MSAL (Microsoft 身份验证库) 进行身份验证？ | 是 |
| 你的应用是否支持条件访问策略？ | 是 |
| 列出支持的策略类型 | 设备平台、设备状态、客户端应用 |
| 应用是否请求方案最小特权权限？ | 是 |
| 应用的静态注册权限是否准确反映应用将动态和增量请求的权限？ | 是 |
| 你的应用是否支持多租户？ | 是 |
| 你的应用是否具有机密客户端？ | 否 |
| 你是否拥有为应用注册的所有重定向统 (URI) URI？ | 是 |
| 你的应用是否公开任何 Web API？ | 是 |
| 您的权限模型是否仅在客户端应用程序收到正确同意时允许呼叫成功？ | 是 |
| 你的应用是否使用预览 API？ | 否 |
| 你的应用是否使用已弃用 API？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
