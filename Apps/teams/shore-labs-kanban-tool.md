---
title: 由实验室提供的看板工具的应用程序信息
ms.author: elmalova
author: elenamalova
ms.date: 08/19/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: 有关看板工具的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: f8ab41264bce6b78ce099a0b295e381e7102a4ca
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 10/18/2021
ms.locfileid: "60430160"
---
# <a name="kanban-tool"></a>Kanban Tool

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2021 年 6 月 15 日</p>

* <a href="https://teams.microsoft.com/l/app/b3c15d4f-1972-4836-a1eb-7575dd56a17e" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002121" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

由 Labs 实验室提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | Kanban Tool |
| ID | WA200002121 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | Shore Labs |
| 合作伙伴网站的 URL | [https://www.shorelabs.com](https://www.shorelabs.com) |
| "Teams应用程序信息"页的 URL | [https://kanbantool.com](https://kanbantool.com) |
| 隐私策略的 URL | [https://kanbantool.com/policy/privacy](https://kanbantool.com/policy/privacy) |
| 使用条款 URL | [https://kanbantool.com/policy/terms-of-service](https://kanbantool.com/policy/terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

这些信息由 Labs 实验室提供，用于了解此应用如何收集和存储组织数据，以及组织将拥有对应用收集的数据的控制。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph](https://docs.microsoft.com/graph/permissions-reference)所需的任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| email | delegated | 用于通信、标识匹配和通知传递的用户电子邮件地址。 | 电子邮件地址。 | [4e820d60-9e62-403c-accd-857b987cc13c](https://docs.microsoft.com/microsoft-365-app-certification/azure/4e820d60-9e62-403c-accd-857b987cc13c) |
>| Team.ReadBasic.All | delegated | 用户是直接成员的团队的标识符和名称。 它们用于在看板工具中自动将用户分配给正确的组。 | 登录用户是其直接成员的团队标识符和名称将映射到"看板工具"中的组。 这允许基于组的访问管理和在同一Boards团队之间共享看板。 | [a8ead1a3-85e1-42a3-9ed0-9afb97482b31](https://docs.microsoft.com/microsoft-365-app-certification/azure/a8ead1a3-85e1-42a3-9ed0-9afb97482b31) |
>| User.Read | delegated | 已登录用户的基本公司信息。 它用于填充新帐户的帐户详细信息，并识别属于你的组织的用户，以便提供单一Sign-On功能。 | 名称和组织的唯一 Microsoft 标识符。 | [a8ead1a3-85e1-42a3-9ed0-9afb97482b31](https://docs.microsoft.com/microsoft-365-app-certification/azure/a8ead1a3-85e1-42a3-9ed0-9afb97482b31) |
>| offline_access | delegated | 允许用户登录后，使用"使用 Microsoft 登录"功能和同步已给予应用访问权限的数据。 | 保持对已赋予其访问权限的数据的访问权限。 | [a8ead1a3-85e1-42a3-9ed0-9afb97482b31](https://docs.microsoft.com/microsoft-365-app-certification/azure/a8ead1a3-85e1-42a3-9ed0-9afb97482b31) |
>| openid | delegated | 打开 ID 令牌，以允许用户通过"使用 Microsoft 登录"按钮使用工作或学校帐户登录应用。 | Microsoft 标识系统中用户帐户的不可变标识符。 | [a8ead1a3-85e1-42a3-9ed0-9afb97482b31](https://docs.microsoft.com/microsoft-365-app-certification/azure/a8ead1a3-85e1-42a3-9ed0-9afb97482b31) |
>| 个人资料 | delegated | 在"看板工具"中自动填充并及时与"看板工具"中Microsoft Teams。 | 用户的全名。 | [a8ead1a3-85e1-42a3-9ed0-9afb97482b31](https://docs.microsoft.com/microsoft-365-app-certification/azure/a8ead1a3-85e1-42a3-9ed0-9afb97482b31) |


#### <a name="non-microsoft-services-used"></a>非Microsoft 服务已使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>| **所有非 Microsoft 服务 OII 将转移到** |  **转移了哪些 OII？** | **转移 OII 的理由？** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| 看板工具使用下列子处理器来提升其服务的性能： https://kanbantool.com/policy/privacy#appointed-subprocessors |   | 我们使用这些第三方提供和维护技术基础结构，并协助进行计费和付款处理。 |

#### <a name="data-access-via-bots"></a>通过机器人访问数据

如果此应用程序包含机器人或消息扩展，则它可以访问最终用户可识别信息 (EUII) ：名单 (名字、姓氏、显示名称、电子邮件地址) （团队中任何团队成员的姓名、姓氏、电子邮件地址) 或添加到其中聊天）。 此应用是否使用了此功能？

>无法访问 EUII。


#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或 EUII (最终用户可识别) 是否显示在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>我们会自动收集有关你的帐户和服务中的活动的技术信息。 此类信息存储在内部日志文件中，可能包含 OII 和 EUII 数据（如果它是您进行活动的一部分）。 我们不会与任何第三方共享日志文件。 日志数据收集的目的是出于法律和监管原因，旨在识别任何潜在安全漏洞或滥用服务的来源，以用于请求速率限制和性能分析

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>帐户管理员具有完全访问权限，包括修改和删除与帐户相关的个人数据的能力，并且是实际数据控制者。

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>标识信息

由 Labs 实验室提供了此信息，这些信息与此应用程序如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件有关。

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
| 对于你的应用，应避免使用什么？ | ,<br/>- OAuth2 隐式Flow，除非 SPA 需要<br/>- 资源所有者密码凭据 (ROPC) 流 |
| 你的应用是否公开任何 Web API？ | 是 |
| 您的权限模型是否仅在客户端应用程序收到正确同意时才允许呼叫成功？ | 是 |
| 你的应用是否使用预览 API？ | 否 |
| 你的应用是否使用已弃用 API？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
