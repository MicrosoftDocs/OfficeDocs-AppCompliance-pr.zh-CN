---
title: xto10x 技术 10xGoals 的应用程序信息
ms.author: elmalova
author: elenamalova
ms.date: 08/19/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: 10xGoals 的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security 应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 82730906a833ef43df8a3eafaee1111cf6889472
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 10/16/2021
ms.locfileid: "60411357"
---
# <a name="10xgoals"></a>10xGoals

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2021 年 7 月 8 日</p>

* <a href="https://teams.microsoft.com/l/app/950aa4fb-0583-4b13-9b5f-bbc92b9cc376" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003122" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

xto10x 技术提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | 10xGoals |
| ID | WA200003122 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | xto10x Technologies |
| 合作伙伴网站的 URL | [https://www.xto10x.com/10xgoals/](https://www.xto10x.com/10xgoals/) |
| Teams信息页的 URL | [https://www.xto10x.com/10xgoals/](https://www.xto10x.com/10xgoals/) |
| 隐私策略的 URL | [https://www.xto10x.com/security/privacy-policy/](https://www.xto10x.com/security/privacy-policy/) |
| 使用条款 URL | [https://www.xto10x.com/security/terms-of-use/](https://www.xto10x.com/security/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

xto10x 技术提供了此信息，这些信息与此应用程序如何收集和存储组织数据以及您的组织将拥有对应用收集的数据的控制有关。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph所需的](https://docs.microsoft.com/graph/permissions-reference)任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Directory.Read.All | 应用程序 | 获取用户电子邮件和 azure id，以便应用可以主动为组织所有用户安装应用。  | 由于此应用首先需要 10xGoals 服务订阅，因此用户电子邮件和用户的 azure ID 将发送到 10xGoals 服务，以便当某些活动与该用户相关时，它可以向用户的团队应用发送主动通知。 | [950aa4fb-0583-4b13-9b5f-bbc92b9cc376](https://docs.microsoft.com/microsoft-365-app-certification/azure/950aa4fb-0583-4b13-9b5f-bbc92b9cc376) |
>| TeamsAppInstallation.ReadWriteSelfForUser.All | 应用程序 | 必须这样做，以便应用可以提取已安装的 teamsAppDefinition 供管理员使用，然后为组织所有用户主动安装自身。  | 任何内容都存储在从此 api 提取的数据库中。 | [950aa4fb-0583-4b13-9b5f-bbc92b9cc376](https://docs.microsoft.com/microsoft-365-app-certification/azure/950aa4fb-0583-4b13-9b5f-bbc92b9cc376) |


#### <a name="non-microsoft-services-used"></a>非Microsoft 服务已使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>| **所有非Microsoft 服务 OII 将转移到** |  **转移了哪些 OII？** | **转移 OII 的理由？** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| 10xGoals， AWS | 用户电子邮件和用户的 AzureId。  | 由于此应用首先需要 10xGoals 服务订阅，因此用户电子邮件和用户的 azure ID 将发送到 10xGoals 服务，以便当某些活动与该用户相关时，系统可以主动向用户发送通知。 |

#### <a name="data-access-via-bots"></a>通过机器人访问数据

如果此应用程序包含机器人或消息扩展，则它可以访问最终用户可识别信息 (EUII) ：名单 (名字、姓氏、显示名称、电子邮件地址) （团队中任何团队成员的姓名、姓氏、电子邮件地址) 或添加到其中聊天）。 此应用是否使用了此功能？

>| **访问 EUII 的理由？**  | **EUII 是否存储在数据库 (中) ？** | **存储 EUII 的理由** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| 由于此应用首先需要 10xGoals 服务订阅，因此用户电子邮件和用户的 azure ID 将发送到 10xGoals 服务，以便当某些活动与该用户相关时，它可以向用户的团队应用发送主动通知。 | 否 |  |


#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或最终用户可识别信息 (EUII) 是否出现在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>tenantId of org 存储为具有差异欢迎消息，具体取决于租户是否已授予所需的权限。 如果租户已授予权限，该组织中的其他用户无需再次查看授予权限流。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>不适用

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>标识信息

xto10x 技术已提供有关此应用如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件的信息。

| **Information** | **响应** |
|:----------------|:-------------|
| 是否与 Microsoft 标识平台 (Azure AD) ？  | 是 |
| 您是否已查看并遵循了 Microsoft 标识平台 清单中列出的所有适用最佳做法？  | 是 |
| 你的应用是否使用 MSAL (Microsoft 身份验证库) 进行身份验证？ | 是 |
| 你的应用是否支持条件访问策略？ | 否 |
| 应用是否请求方案最小特权权限？ | 是 |
| 应用的静态注册权限是否准确反映应用将动态和增量请求的权限？ | 是 |
| 你的应用是否支持多租户？ | 否 |
| 你的应用是否具有机密客户端？ | 否 |
| 你是否拥有为应用注册的所有 (统一) URI？ | 是 |
| 你的应用是否公开任何 Web API？ | 是 |
| 您的权限模型是否仅在客户端应用程序收到正确同意时才允许呼叫成功？ | 是 |
| 你的应用是否使用预览 API？ | 否 |
| 你的应用是否使用已弃用 API？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

