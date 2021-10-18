---
title: ThoughtWire Corp 的 ThoughtWire EWS 的应用程序信息。
ms.author: elmalova
author: elenamalova
ms.date: 09/15/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: ThoughtWire EWS 的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security 应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: ebff314a2e2532b6d4b1c2a8e89e600fced83512
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 10/18/2021
ms.locfileid: "60429510"
---
# <a name="thoughtwire-ews"></a>ThoughtWire EWS

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2021 年 6 月 17 日</p>

* <a href="https://teams.microsoft.com/l/app/ed27363f-755e-4658-b7bf-409d475959d6" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003239" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

ThoughtWire Corp. 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | ThoughtWire EWS |
| ID | WA200003239 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | ThoughtWire 公司 |
| 合作伙伴网站的 URL | [https://thoughtwire.com](https://thoughtwire.com) |
| 隐私策略的 URL | [https://thoughtwire.com/privacy-policy](https://thoughtwire.com/privacy-policy) |
| 使用条款 URL | [https://www.thoughtwire.com/end-user-license-agreement/](https://www.thoughtwire.com/end-user-license-agreement/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

此信息由 ThoughtWire Corp. 提供，用于了解此应用如何收集和存储组织数据，以及组织将拥有对应用收集的数据的控制。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph](https://docs.microsoft.com/graph/permissions-reference)所需的任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Group.Create | 应用程序 | 允许应用程序为医院单位创建组/团队。 | 无 | [49a15c37-4eca-48b1-a327-7a8b5a3b399c](https://docs.microsoft.com/microsoft-365-app-certification/azure/49a15c37-4eca-48b1-a327-7a8b5a3b399c) |
>| Group.ReadWrite.All | 应用程序 | 应用程序必须确定需要创建/重新创建哪些组，以及管理成员身份。 | 无 | [49a15c37-4eca-48b1-a327-7a8b5a3b399c](https://docs.microsoft.com/microsoft-365-app-certification/azure/49a15c37-4eca-48b1-a327-7a8b5a3b399c) |
>| GroupMember.ReadWrite.All | 应用程序 | 必需，这样应用程序才能管理组成员身份。 即，随着班次的变化，在团队中添加/删除医生。 | 无 | [49a15c37-4eca-48b1-a327-7a8b5a3b399c](https://docs.microsoft.com/microsoft-365-app-certification/azure/49a15c37-4eca-48b1-a327-7a8b5a3b399c) |
>| TeamMember.ReadWrite.All | 应用程序 | 必需，这样应用程序才能管理组成员身份。 即，随着班次的变化，在团队中添加/删除医生。 | 无 | [49a15c37-4eca-48b1-a327-7a8b5a3b399c](https://docs.microsoft.com/microsoft-365-app-certification/azure/49a15c37-4eca-48b1-a327-7a8b5a3b399c) |
>| TeamsAppInstallation.ReadWriteForTeam | 应用程序 | 允许应用程序自动将 ThoughtWire 自动程序安装到其创建/管理的团队中。 | 无 | [49a15c37-4eca-48b1-a327-7a8b5a3b399c](https://docs.microsoft.com/microsoft-365-app-certification/azure/49a15c37-4eca-48b1-a327-7a8b5a3b399c) |
>| User.Read | 应用程序 | 允许应用程序在管理成员身份和/或检索用户名以标识应用程序中的用户时，根据需要检索用户的 A按要求。 | 无 | [49a15c37-4eca-48b1-a327-7a8b5a3b399c](https://docs.microsoft.com/microsoft-365-app-certification/azure/49a15c37-4eca-48b1-a327-7a8b5a3b399c) |


#### <a name="non-microsoft-services-used"></a>非Microsoft 服务已使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>不Microsoft 服务非活动。

#### <a name="data-access-via-bots"></a>通过机器人访问数据

如果此应用程序包含机器人或消息扩展，则它可以访问最终用户可识别信息 (EUII) ：名单 (名字、姓氏、显示名称、电子邮件地址) （团队中任何团队成员的姓名、姓氏、电子邮件地址) 或添加到其中聊天）。 此应用是否使用了此功能？

>| **访问 EUII 的理由？**  | **EUII 是否存储在数据库 () ？** | **存储 EUII 的理由** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| 标识执行操作的用户需要用户名。 | 用户名和用户 ID | 通知和事件的审核。 |


#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或 EUII (最终用户可识别) 是否显示在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>应用程序遥测或日志中不显示 OII 或 EUII。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>ThoughtWire 选择符合或超过我们自身数据控制流程的合作伙伴。 除非绝对需要，否则不会向合作伙伴系统提供数据。 所有 ThoughtWire 服务和相关合作伙伴系统都经过客户审查并获得批准。

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>标识信息

此信息由 ThoughtWire Corp. 提供有关此应用如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件的信息。

| **Information** | **响应** |
|:----------------|:-------------|
| 是否与 Microsoft 标识平台 (Azure AD) ？  | 是 |
| 您是否已审阅并遵循了 Microsoft 标识平台 集成清单中列出的所有适用最佳做法？  | 是 |
| 你的应用是否使用 MSAL (Microsoft 身份验证库) 进行身份验证？ | 否 |
| 你的应用是否支持条件访问策略？ | 否 |
| 应用是否请求方案最小特权权限？ | 是 |
| 应用的静态注册权限是否准确反映应用将动态和增量请求的权限？ | 是 |
| 你的应用是否支持多租户？ | 否 |
| 你的应用是否具有机密客户端？ | 是 |
| 你是否拥有为应用注册的所有 (统一) URI？ | 是 |
| 对于你的应用，应避免使用什么？ | - 通配符重定向 URI，<br/>- OAuth2 隐式Flow，除非 SPA 需要<br/>- 资源所有者密码凭据 (ROPC) 流 |
| 你的应用是否公开任何 Web API？ | 是 |
| 您的权限模型是否仅在客户端应用程序收到正确同意时才允许呼叫成功？ | 是 |
| 你的应用是否使用预览 API？ | 否 |
| 你的应用是否使用已弃用 API？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
