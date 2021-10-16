---
title: IsLucid 的应用程序信息（由 UAB Lucid 协议提供）
ms.author: elmalova
author: elenamalova
ms.date: 09/02/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: isLucid 的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 7270fa4f4a08ca820d1fe7452dea13fb107f2294
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 10/16/2021
ms.locfileid: "60414899"
---
# <a name="islucid"></a>isLucid

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2021 年 8 月 9 日</p>

* <a href="https://teams.microsoft.com/l/app/a5711b63-5e70-4e4e-b040-0d714b64f684" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002385" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

UAB Lucid 协议提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | isLucid |
| ID | WA200002385 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | UAB Lucid 协议 |
| 合作伙伴网站的 URL | [https://islucid.com](https://islucid.com) |
| Teams信息页的 URL | [https://islucid.com](https://islucid.com) |
| 隐私策略的 URL | [https://islucid.com/privacy-policy/](https://islucid.com/privacy-policy/) |
| 使用条款 URL | [https://islucid.com/eula/](https://islucid.com/eula/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

此信息由 UAB Lucid 协议提供，这些协议与此应用程序如何收集和存储组织数据以及您的组织将拥有对应用收集的数据的控制有关。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph所需的](https://docs.microsoft.com/graph/permissions-reference)任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calls.AccessMedia.All | 两者 | 在用户单独同意每个呼叫的情况下 (启动的转录) 访问音频流。 音频流将转发到转录服务，以便用户获得进一步的功能。 | Azure 上的独立容器中的应用商店 (blob 存储，Cosmos每个客户端的 DB 中) 转录和相关元数据信息。 这要求为用户提供对会议信息的进一步访问，该用户使用该应用程序并参与特定会议。 | [98b70422-b0b2-41bf-8673-60d85f5d38c7](https://docs.microsoft.com/microsoft-365-app-certification/azure/98b70422-b0b2-41bf-8673-60d85f5d38c7) |
>| Calls.JoinGroupCall.All | 两者 | 在用户单独同意每个呼叫的情况下 (启动的转录) 访问音频流。 音频流将转发到转录服务，以便用户获得进一步的功能。 | Azure 上的独立容器中的应用商店 (blob 存储，Cosmos每个客户端的 DB 中) 转录和相关元数据信息。 这要求为用户提供对会议信息的进一步访问，该用户使用该应用程序并参与特定会议。 | [98b70422-b0b2-41bf-8673-60d85f5d38c7](https://docs.microsoft.com/microsoft-365-app-certification/azure/98b70422-b0b2-41bf-8673-60d85f5d38c7) |
>| Group.ReadWrite.All | 两者 | 当用户使用与 Microsoft Planner 的集成通过呼叫创建任务并自动存储在 MS Planner 中时，isLucid 会收集该用户的可用组、计划、被分配者。 如果没有此权限，用户将无法使用 isLucid 从转录创建任务 | 存储任务标题、任务创建者、任务时间戳、任务说明，以便用户可以访问从特定会议创建的任务历史记录。 | [98b70422-b0b2-41bf-8673-60d85f5d38c7](https://docs.microsoft.com/microsoft-365-app-certification/azure/98b70422-b0b2-41bf-8673-60d85f5d38c7) |
>| OnlineMeetings.Read.All | 两者 | 应用程序收集会议标题，以便用户 (会议结束后) 可以更轻松地找到以前的脚本和任务。 | 会议标题、会议组织者的时间戳 | [98b70422-b0b2-41bf-8673-60d85f5d38c7](https://docs.microsoft.com/microsoft-365-app-certification/azure/98b70422-b0b2-41bf-8673-60d85f5d38c7) |
>| Tasks.ReadWrite | 两者 | 当用户使用与 Microsoft Planner 的集成通过呼叫创建任务并自动存储在 MS Planner 中时，isLucid 会收集该用户的可用组、计划、被分配者。 如果没有此权限，用户将无法使用 isLucid 从转录创建任务 | 存储任务标题、任务创建者、任务时间戳、任务说明，以便用户可以访问从特定会议创建的任务历史记录。 | [98b70422-b0b2-41bf-8673-60d85f5d38c7](https://docs.microsoft.com/microsoft-365-app-certification/azure/98b70422-b0b2-41bf-8673-60d85f5d38c7) |
>| User.ReadWrite.All | 两者 | 当用户使用与 Microsoft Planner 的集成通过呼叫创建任务并自动存储在 MS Planner 中时，isLucid 会收集该用户的可用组、计划、被分配者。 如果没有此权限，用户将无法使用 isLucid 从转录创建任务 | 存储任务标题、任务创建者、任务时间戳、任务说明，以便用户可以访问从特定会议创建的任务历史记录。 | [98b70422-b0b2-41bf-8673-60d85f5d38c7](https://docs.microsoft.com/microsoft-365-app-certification/azure/98b70422-b0b2-41bf-8673-60d85f5d38c7) |
>| openid | 两者 | 收集的用户 ID、租户 ID，Azure Active Directory我们的用户提供登录功能 | 用户 ID、用于进一步权限管理的租户 ID | [98b70422-b0b2-41bf-8673-60d85f5d38c7](https://docs.microsoft.com/microsoft-365-app-certification/azure/98b70422-b0b2-41bf-8673-60d85f5d38c7) |


#### <a name="non-microsoft-services-used"></a>非Microsoft 服务已使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>| **所有非Microsoft 服务 OII 将转移到** |  **转移了哪些 OII？** | **转移 OII 的理由？** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| hubspot.com | 姓名、姓氏、电子邮件电话新注册的用户的数量 | 我们使用 Hubspot CRM 维护销售相关信息 |

#### <a name="data-access-via-bots"></a>通过机器人访问数据

如果此应用程序包含机器人或消息扩展，则它可以访问最终用户可识别信息 (EUII) ：名单 (名字、姓氏、显示名称、电子邮件地址) （团队中任何团队成员的姓名、姓氏、电子邮件地址) 或添加到其中聊天）。 此应用是否使用了此功能？

>| **访问 EUII 的理由？**  | **EUII 是否存储在数据库 (中) ？** | **存储 EUII 的理由** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| 机器人支持将音频流发送到转录服务。 若要提供可读转录，我们需要将音频与用户 (扬声器) 。 如果不提供此类信息脚本，则毫无用处 | 姓名、姓氏、状态（如果是来宾帐户或 Microsoft 帐户） | 机器人支持将音频流发送到转录服务。 若要提供可读转录，我们需要将音频与用户 (扬声器) 。 会议参与者信息还与使用户能够查看谁正在参加会议有关。 |


#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或最终用户可识别信息 (EUII) 是否出现在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>使用我们的服务的用户正在生成脚本。 在脚本中，会议参与者 (姓名、姓氏) 显示。 呼叫过程中可能会提到任何内容。 只要用户使用我们的服务，我们就存储用户的此数据。 客户端结束使用后，我们将在 30 天内销毁所有关联的数据。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>当客户端购买为托管解决方案时，我们不会控制客户端上的任何数据。 对于 SaaS 解决方案，我们允许用户使用服务取消，然后删除与Cosmos关联的 DB 实例。 我们正在将信息发送到合规性 API

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>是

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>标识信息

此信息由 UAB Lucid 协议提供，这些协议与此应用程序如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件有关。

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
| 你的应用是否公开任何 Web API？ | 是 |
| 您的权限模型是否仅在客户端应用程序收到正确同意时才允许呼叫成功？ | 是 |
| 你的应用是否使用预览 API？ | 是 |
| 你的应用是否使用已弃用 API？ | 是 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

