---
title: 按 Chrono Innovation 进行时间跟踪的 Chronoscope 应用程序信息
ms.author: elmalova
author: elenamalova
ms.date: 07/23/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: 有关 Chronoscope 时间跟踪、其数据处理策略、Microsoft Cloud App Security 应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息的所有可用安全性和合规性信息。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 9e87baec293d3c18e48da28e1714fce9703f446f
ms.sourcegitcommit: 34fde42f42c623b37d1db154bf348bdc8b76a8c7
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 08/19/2021
ms.locfileid: "58407363"
---
# <a name="chronoscope-time-tracking"></a>Chronoscope 时间跟踪

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2021 年 7 月 23 日</p>

* <a href="https://teams.microsoft.com/l/app/5b3ded07-fa1a-4fd8-a323-e5fe3f8cf740" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003095" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

由 Chrono Innovation 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | Chronoscope 时间跟踪 |
| ID | WA200003095 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | Chrono Innovation |
| 合作伙伴网站的 URL | [https://www.chronoinnovation.com](https://www.chronoinnovation.com) |
| "Teams应用程序信息"页的 URL | [https://www.chronoscope.app](https://www.chronoscope.app) |
| 隐私策略的 URL | [https://www.chronoscope.app/privacy-policy](https://www.chronoscope.app/privacy-policy) |
| 使用条款 URL | [https://www.chronoscope.app/terms-of-service](https://www.chronoscope.app/terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

此信息由 Chrono Innovation 提供有关此应用程序如何收集和存储组织数据以及您的组织将拥有对应用收集的数据的控制的信息。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph所需的](https://docs.microsoft.com/graph/permissions-reference)任何 Microsoft 权限。

>| **权限**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD 应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| AccessReview.Read.All | 应用程序 | teams tenantId 、teams addObjectId 和 teams 用户帐户信息。 链接 Chronoscope 用户时，我们验证电子邮件是否与 Teams 帐户匹配，以便无需用户手动步骤即可链接帐户 | teams tenantId 、teams addObjectId 和 teams 用户帐户信息。 链接 Chronoscope 用户时，我们验证电子邮件是否与 Teams 帐户匹配，以便无需用户手动步骤即可链接帐户 | [9bc8244d-a186-4b12-809e-c47b3eee73c6](https://docs.microsoft.com/microsoft-365-app-certification/azure/9bc8244d-a186-4b12-809e-c47b3eee73c6) |


#### <a name="non-microsoft-services-used"></a>非Microsoft 服务使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>不Microsoft 服务非活动。

#### <a name="data-access-via-bots"></a>通过机器人访问数据

如果此应用程序包含机器人或消息扩展，则它可以访问最终用户可识别信息 (EUII) ：名单 (名字、姓氏、显示名称、电子邮件地址) （团队中任何团队成员的姓名、姓氏、电子邮件地址) 或添加到其中聊天）。 此应用是否使用了此功能？

>| **访问 EUII 的理由？**  | **EUII 是否存储在数据库 (中) ？** | **存储 EUII 的理由** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| 为了查找团队用户工作垃圾邮件在链接 Chronoscope 用户时，我们验证电子邮件是否与 Teams 帐户匹配，以便无需手动从应用程序数据库中的 user.ce 链接帐户并验证该团队用户 | tenantId ， 用户帐户信息，如 userId ， addObjectId ， givenName ，email ，role，objectId | 链接 Chronoscope 用户时，我们会验证电子邮件是否与 Teams 帐户匹配，以便无需用户手动步骤即可链接帐户。 此外，能够推送通知有关预填充的用户时间条目，以便他们可以保存/编辑/删除它们。 |


#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或 EUII (最终用户可识别) 是否显示在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>与时间条目有关的信息。 Chrono Innovation 将在 Chronoscope 帐户删除 90 天后删除客户数据

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>管理员可完全控制驻留在任何合作伙伴系统中的信息

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

此信息由 Chrono Innovation 提供有关此应用程序如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件的信息。

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
| 你是否拥有为应用注册的所有 (统一) URI？ | 是 |
| 对于你的应用，应避免使用什么？ | - 通配符重定向 URI，<br/>- OAuth2 隐式Flow，除非 SPA 需要<br/> |
| 你的应用是否公开任何 Web API？ | 否 |
| 你的应用是否使用预览 API？ | 否 |
| 你的应用是否使用已弃用 API？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
