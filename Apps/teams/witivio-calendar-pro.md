---
title: 由Pro日历应用程序信息
ms.author: elmalova
author: elenamalova
ms.date: 09/03/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: 日历应用程序的所有可用安全性和合规性Pro、其数据处理策略、Microsoft Cloud App Security应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 5f8b6dcbf99d26e867cc79194cb57c1393316a2b
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 10/16/2021
ms.locfileid: "60414859"
---
# <a name="calendar-pro"></a>Calendar Pro

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2021 年 9 月 2 日</p>

* <a href="https://teams.microsoft.com/l/app/19a29a41-cbca-4152-a2af-dd9728ea35f1" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002152" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

由小马向 Microsoft 提供的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | Calendar Pro |
| ID | WA200002152 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | Witivio |
| 合作伙伴网站的 URL | [https://www.witivio.com](https://www.witivio.com) |
| 隐私策略的 URL | [https://www.teams-pro.com/en/privacy-policy/](https://www.teams-pro.com/en/privacy-policy/) |
| 使用条款 URL | [https://www.teams-pro.com/en/terms-of-use/](https://www.teams-pro.com/en/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

此信息由一位小马提供，这些信息与此应用程序如何收集和存储组织数据以及组织将拥有对应用收集的数据的控制有关。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph](https://docs.microsoft.com/graph/permissions-reference)所需的任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | delegated | 使用数据 | 数据用于在 UI 中显示信息 | [fb507a6d-2eaa-4f1f-b43a-140f388c4445](https://docs.microsoft.com/microsoft-365-app-certification/azure/fb507a6d-2eaa-4f1f-b43a-140f388c4445) |
>| User.ReadBasic.All | delegated | 使用数据 | 数据用于列出启用人员选取器的人 | [fb507a6d-2eaa-4f1f-b43a-140f388c4445](https://docs.microsoft.com/microsoft-365-app-certification/azure/fb507a6d-2eaa-4f1f-b43a-140f388c4445) |
>| email | delegated | 电子邮件已使用 | 电子邮件用于标识 UI 中的用户 | [fb507a6d-2eaa-4f1f-b43a-140f388c4445](https://docs.microsoft.com/microsoft-365-app-certification/azure/fb507a6d-2eaa-4f1f-b43a-140f388c4445) |
>| offline_access | delegated | 使用数据 | 脱机访问用于启用 SSO 和Microsoft Teams | [fb507a6d-2eaa-4f1f-b43a-140f388c4445](https://docs.microsoft.com/microsoft-365-app-certification/azure/fb507a6d-2eaa-4f1f-b43a-140f388c4445) |
>| openid | delegated | 身份验证 | OpenID 用于向用户Microsoft Teams | [fb507a6d-2eaa-4f1f-b43a-140f388c4445](https://docs.microsoft.com/microsoft-365-app-certification/azure/fb507a6d-2eaa-4f1f-b43a-140f388c4445) |
>| 个人资料 | delegated | 使用数据 | 配置文件用于启用 SSO 和 Microsoft Teams | [fb507a6d-2eaa-4f1f-b43a-140f388c4445](https://docs.microsoft.com/microsoft-365-app-certification/azure/fb507a6d-2eaa-4f1f-b43a-140f388c4445) |


#### <a name="non-microsoft-services-used"></a>非Microsoft 服务已使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>不Microsoft 服务非活动。

#### <a name="data-access-via-bots"></a>通过机器人访问数据

如果此应用程序包含机器人或消息扩展，则它可以访问最终用户可识别信息 (EUII) ：名单 (名字、姓氏、显示名称、电子邮件地址) （团队中任何团队成员的姓名、姓氏、电子邮件地址) 或添加到其中聊天）。 此应用是否使用了此功能？

>无法访问 EUII。


#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或 EUII (最终用户可识别) 是否显示在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>遥测包含诊断的 UPN AAD ID。 只有 PROD/Run 管理员有权访问生产遥测。 日志将存储 90 天，并可以通过电子邮件在系统请求时 dpo@witivio.com

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>百里诺仅使用Microsoft Azure欧洲地区部署的组件。 我们使用应用程序见解和 Cosmos DB 进行数据分析和存储。 对于所有用户（包括管理员）来说，都使用 MFA。 管理员具有用于工作站 (的用户帐户) 访问 Azure 资源的权限帐户。

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>是

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>标识信息

此信息由一位小马提供，关于此应用如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件。

| **Information** | **响应** |
|:----------------|:-------------|
| 是否与 Microsoft 标识平台 (Azure AD) ？  | 是 |
| 您是否已审阅并遵循了 Microsoft 标识平台 集成清单中列出的所有适用最佳做法？  | 是 |
| 你的应用是否使用 MSAL (Microsoft 身份验证库) 进行身份验证？ | 是 |
| 你的应用是否支持条件访问策略？ | 否 |
| 应用是否请求方案最小特权权限？ | 是 |
| 应用的静态注册权限是否准确反映应用将动态和增量请求的权限？ | 是 |
| 你的应用是否支持多租户？ | 是 |
| 你的应用是否具有机密客户端？ | 是 |
| 你是否拥有为应用注册的所有 (统一) URI？ | 是 |
| 对于你的应用，应避免使用什么？ | ,<br/>- OAuth2 隐式Flow，除非 SPA 需要<br/> |
| 你的应用是否公开任何 Web API？ | 是 |
| 您的权限模型是否仅在客户端应用程序收到正确同意时才允许呼叫成功？ | 是 |
| 你的应用是否使用预览 API？ | 否 |
| 你的应用是否使用已弃用 API？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

