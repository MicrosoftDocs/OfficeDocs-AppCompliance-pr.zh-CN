---
title: 由同事与 Insights Inc 一起提供的应用程序信息
ms.author: elmalova
author: elenamalova
ms.date: 06/16/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: 合作者的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 3dc9a5d3bcd6e5bbc356efab77ad15406e9fb772
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 10/16/2021
ms.locfileid: "60414628"
---
# <a name="fellow"></a>Fellow

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2021 年 5 月 21 日</p>

* <a href="https://teams.microsoft.com/l/app/f6671df0-1909-428c-91f7-1c42df04d3e4" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002576" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

由 Insights Inc 向 Microsoft 提供的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | Fellow |
| ID | WA200002576 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | Fellow Insights Inc |
| 合作伙伴网站的 URL | [https://fellow.app](https://fellow.app) |
| 隐私策略的 URL | [https://fellow.app/privacy-policy/](https://fellow.app/privacy-policy/) |
| 使用条款 URL | [https://fellow.app/terms-of-use/](https://fellow.app/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

此信息由 Insights Inc. 提供，与此应用程序如何收集和存储组织数据以及您的组织将拥有对应用收集的数据的控制有关。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph](https://docs.microsoft.com/graph/permissions-reference)所需的任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | 两者 | 同事与用户的日历联系，以便他们能够记录数据。 | 同事存储用户的主日历的所有事件数据。 不存储附件。 这是在"合作者"中用于提供基于日历的笔记记录体验。 | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| Channel.ReadBasic.All | delegated | 我们收集用户是其中一员的频道名称，以便向用户显示可以发送注释的频道列表。 | 我们缓存用户是其中一个成员的频道的名称和 ID，以便允许用户将笔记从"合作者"发送到指定的频道。 | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| Directory.Read.All | 应用程序 | 只有在为整个组织完成了管理员安装时，才收集此数据。 我们使用目录数据同步用户列表并自动预配帐户。 | 如果且仅在管理员从"协作者"内的工作区设置中执行组织范围的安装时，管理员可选择启用所有用户从 Azure AD 自动同步到协作者 (自动预配) 。 在这种情况下，我们将存储用户信息，如 ID、姓名、电子邮件和经理以及组成员身份 (用于团队管理功能) 。 | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| Group.Read.All | 应用程序 | 只有在为整个组织完成了管理员安装时，才收集此数据。 我们使用目录数据同步用户列表并自动预配帐户。 | 如果且仅在管理员从"协作者"内的工作区设置中执行组织范围的安装时，管理员可选择启用所有用户从 Azure AD 自动同步到协作者 (自动预配) 。 在这种情况下，我们将存储用户信息，如 ID、姓名、电子邮件和经理以及组成员身份 (用于团队管理功能) 。 | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| People.Read | delegated | 在特定的联系人 displayNames 和电子邮件地址中收集用户的联系人。 这是在"合作者"中用于提供要邀请加入笔记/共享笔记的用户列表。 | 在特定的联系人 displayNames 和电子邮件地址中收集用户的联系人。 这是在"合作者"中用于提供要邀请加入笔记/共享笔记的用户列表。 | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| People.Read.All | 应用程序 | 只有在为整个组织完成了管理员安装时，才收集此数据。 在特定的联系人 displayNames 和电子邮件地址中收集用户的联系人。 这是在"合作者"中用于提供要邀请加入笔记/共享笔记的用户列表。 | 如果且仅在管理员从"协作者"内的工作区设置中执行组织范围的安装时，管理员可选择启用所有用户从 Azure AD 自动同步到协作者 (自动预配) 。 在这种情况下，将收集特定联系人 displayNames 和电子邮件地址中的用户的联系人。 这是在"合作者"中用于提供要邀请加入笔记/共享笔记的用户列表。 | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| Team.ReadBasic.All | delegated | 将收集用户属于的团队列表。 这是在同事内部使用的，以便允许用户将笔记从"同事"发送到团队。 | 我们缓存用户是团队成员的团队的名称和 ID，以便允许用户将笔记从"协作者"发送到指定的团队频道。 | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| User.Read | delegated | 收集基本用户信息。 用户名、电子邮件、职务。 此信息在"合作者"内用于创建用户帐户和公司帐户。 | 存储基本用户信息。 用户名、电子邮件、职务。 此信息在"合作者"中用于维护用户帐户和公司帐户。 | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| User.Read.All | 应用程序 | 只有在为整个组织完成了管理员安装时，才收集此数据。 我们使用目录数据同步用户列表并自动预配帐户。 | 如果且仅在管理员从"协作者"内的工作区设置中执行组织范围的安装时，管理员可选择启用所有用户从 Azure AD 自动同步到协作者 (自动预配) 。 在这种情况下，我们将存储用户信息，如 ID、姓名、电子邮件和经理以及组成员身份 (用于团队管理功能) 。 | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| offline_access | delegated | 用户的刷新令牌，用于维护对通过其他范围收集的数据的访问。 | 用户的刷新令牌存储在数据库中。 这用于"合作者"，用于同步后台中的事件，实现基于日历的笔记记录体验，以及针对计划事件进行笔记记录的通知。 | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |


#### <a name="non-microsoft-services-used"></a>非Microsoft 服务已使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>不Microsoft 服务非活动。

#### <a name="data-access-via-bots"></a>通过机器人访问数据

如果此应用程序包含机器人或消息扩展，则它可以访问最终用户可识别信息 (EUII) ：名单 (名字、姓氏、显示名称、电子邮件地址) （团队中任何团队成员的姓名、姓氏、电子邮件地址) 或添加到其中聊天）。 此应用是否使用了此功能？

>无法访问 EUII。


#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或 EUII (最终用户可识别) 是否显示在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>同事存储由用户直接提供的信息，包括个人数据。 同事还存储来自第三方系统的一些信息，例如 OAuth 数据、日历数据和 PII（如名称 &amp; 电子邮件）。 我们无限期保留所有数据，只要有必要，并且出于收集目的法律允许保留这些数据。 收到用户的请求后，我们提前安全地删除此信息。 日志数据将保留 30 天。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>所有数据传输均通过安全的 API 传输至后端系统。 根据 AICPA 定义的 SOC 2 框架，合作者采用许多控制措施来确保系统的安全性和机密性。 同事的控制措施接受年度审核，以确保持续合规。 可以请求和 NDA 共享 SOC 2 报告。

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

下面将显示[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/39739' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/39739" target="_blank">在新建选项卡中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>标识信息

此信息由 Insights Inc 提供，用于说明此应用如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件。

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
| 对于你的应用，应避免使用什么？ | ,<br/><br/>- 资源所有者密码凭据 (ROPC) 流 |
| 你的应用是否公开任何 Web API？ | 否 |
| 你的应用是否使用预览 API？ | 否 |
| 你的应用是否使用已弃用 API？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

