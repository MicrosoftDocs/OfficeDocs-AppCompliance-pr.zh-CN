---
title: TMI 系统为 Verto 365 提供的应用程序信息
ms.author: elmalova
author: elenamalova
ms.date: 09/14/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Verto 365 的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security 应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: c82879bb30fc4c24b6e4f4bdb9103a2fe2290286
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 10/16/2021
ms.locfileid: "60414418"
---
# <a name="verto-365"></a>Verto 365

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2021 年 9 月 13 日</p>

* <a href="https://teams.microsoft.com/l/app/b27c082b-9d45-490a-b8bb-8dcda46c73f3" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003230" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

TMI 系统提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | Verto 365 |
| ID | WA200003230 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | TMI 系统 |
| 合作伙伴网站的 URL | [https://www.vertocloud.co.uk](https://www.vertocloud.co.uk) |
| 应用程序Teams页的 URL | [https://www.vertocloud.com](https://www.vertocloud.com) |
| 隐私策略的 URL | [https://vertocloud.co.uk/privacy-policy/](https://vertocloud.co.uk/privacy-policy/) |
| 使用条款 URL | [https://vertocloud.co.uk/terms-and-conditions/](https://vertocloud.co.uk/terms-and-conditions/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

TMI 系统提供了此信息，这些信息与此应用程序如何收集和存储组织数据以及您的组织将拥有对应用收集的数据的控制有关。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph](https://docs.microsoft.com/graph/permissions-reference)所需的任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | delegated | 常规用户信息、名字、姓氏 &amp; 电子邮件。 用于创建帐户。 | 名字、姓氏、电子邮件、OID。 OID 用于在数据库中创建帐户，OID 用于将登录名与 Verto 帐户关联。 | [d8843264-a57b-41e3-aea6-b83ea56f6bd6](https://docs.microsoft.com/microsoft-365-app-certification/azure/d8843264-a57b-41e3-aea6-b83ea56f6bd6) |
>| email | delegated | 常规用户信息、名字、姓氏 &amp; 电子邮件。 用于创建帐户。 | 名字、姓氏、电子邮件、OID。 OID 用于在数据库中创建帐户，OID 用于将登录名与 Verto 帐户关联。 | [d8843264-a57b-41e3-aea6-b83ea56f6bd6](https://docs.microsoft.com/microsoft-365-app-certification/azure/d8843264-a57b-41e3-aea6-b83ea56f6bd6) |
>| offline_access | delegated | 用于获取刷新令牌和持久登录 | 不适用 | [d8843264-a57b-41e3-aea6-b83ea56f6bd6](https://docs.microsoft.com/microsoft-365-app-certification/azure/d8843264-a57b-41e3-aea6-b83ea56f6bd6) |
>| openid | delegated | 常规用户信息、名字、姓氏 &amp; 电子邮件。 用于创建帐户。 | 名字、姓氏、电子邮件、OID。 OID 用于在数据库中创建帐户，OID 用于将登录名与 Verto 帐户关联。 | [d8843264-a57b-41e3-aea6-b83ea56f6bd6](https://docs.microsoft.com/microsoft-365-app-certification/azure/d8843264-a57b-41e3-aea6-b83ea56f6bd6) |
>| 个人资料 | delegated | 常规用户信息、名字、姓氏 &amp; 电子邮件。 用于创建帐户。 | 名字、姓氏、电子邮件、OID。 OID 用于在数据库中创建帐户，OID 用于将登录名与 Verto 帐户关联。 | [d8843264-a57b-41e3-aea6-b83ea56f6bd6](https://docs.microsoft.com/microsoft-365-app-certification/azure/d8843264-a57b-41e3-aea6-b83ea56f6bd6) |


#### <a name="non-microsoft-services-used"></a>非Microsoft 服务已使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>不Microsoft 服务非活动。

#### <a name="data-access-via-bots"></a>通过机器人访问数据

如果此应用程序包含机器人或消息扩展，则它可以访问最终用户可识别信息 (EUII) ：名单 (名字、姓氏、显示名称、电子邮件地址) （团队中任何团队成员的姓名、姓氏、电子邮件地址) 或添加到其中聊天）。 此应用是否使用了此功能？

>无法访问 EUII。


#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或 EUII (最终用户可识别) 是否显示在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>组织名称、名字、姓氏、公司电子邮件地址。 保留策略根据客户内部策略灵活执行，但始终在 GDPR 内。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>通过访问控制列表的最终用户权限。 管理员可以删除或隐藏数据，审核日志用户无法更改数据。

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>是

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>标识信息

TMI 系统提供了此信息，这些信息与此应用程序如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件有关。

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
| 对于你的应用，应避免使用什么？ | - 通配符重定向 URI，<br/><br/>- 资源所有者密码凭据 (ROPC) 流 |
| 你的应用是否公开任何 Web API？ | 是 |
| 您的权限模型是否仅在客户端应用程序收到正确同意时才允许呼叫成功？ | 是 |
| 你的应用是否使用预览 API？ | 否 |
| 你的应用是否使用已弃用 API？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

