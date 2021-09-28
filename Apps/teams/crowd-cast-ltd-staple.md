---
title: 要通过众转换进行装订的应用程序信息， Ltd.
ms.author: elmalova
author: elenamalova
ms.date: 09/27/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: 可供装订的所有安全和合规性信息、其数据处理策略、Microsoft Cloud App Security应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: fa258f568d799ceb8891cd374aa33277dbc6c2c4
ms.sourcegitcommit: 3ac3366e04e24db2d12183ef212738d5b599f553
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 09/28/2021
ms.locfileid: "59975204"
---
# <a name="staple"></a>装订

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2021 年 9 月 27 日</p>

* <a href="https://teams.microsoft.com/l/app/ac9ca94a-e666-4f61-959a-12c063e13e69" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003281" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

由 Cast， Ltd. 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | 装订 |
| ID | WA200003281 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | Crowd Cast, Ltd. |
| 合作伙伴网站的 URL | [https://crowdcast.jp/ja/](https://crowdcast.jp/ja/) |
| "Teams应用程序信息"页的 URL | [https://intercom.help/staple/ja](https://intercom.help/staple/ja) |
| 隐私策略的 URL | [https://crowdcast.jp/ja/privacy/](https://crowdcast.jp/ja/privacy/) |
| 使用条款 URL | [https://go.microsoft.com](https://go.microsoft.com) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

有关此应用程序如何收集和存储组织数据以及你的组织将拥有对应用收集的数据的控制的信息，由 Cast， Ltd. 提供。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph](https://docs.microsoft.com/graph/permissions-reference)所需的任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD 应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Organization.Read.All | 应用程序 | 用于收集租户 ID。用于确保通过平台身份验证的用户是特定租户的成员。 | 租户 ID。用于确保通过平台身份验证的用户是特定租户的成员。 | [ac9ca94a-e666-4f61-959a-12c063e13e69](https://docs.microsoft.com/microsoft-365-app-certification/azure/ac9ca94a-e666-4f61-959a-12c063e13e69) |
>| TeamsAppInstallation.ReadWriteSelfForUser.All | 应用程序 | Teams应用将自身安装到用户团队 | 不适用 | [ac9ca94a-e666-4f61-959a-12c063e13e69](https://docs.microsoft.com/microsoft-365-app-certification/azure/ac9ca94a-e666-4f61-959a-12c063e13e69) |
>| AppCatalog.Read.All | delegated | 读取用户的应用程序目录，以查看是否安装了 Teams 应用。 | 不适用 | [bbdcd676-7448-453c-bec7-70e5384bc290](https://docs.microsoft.com/microsoft-365-app-certification/azure/bbdcd676-7448-453c-bec7-70e5384bc290) |
>| User.Read | delegated | 用于读取用户 ID，以确保将邮件发送到正确的用户。 | 存储的用户 ID，用于向用户发送主动邮件。 | [bbdcd676-7448-453c-bec7-70e5384bc290](https://docs.microsoft.com/microsoft-365-app-certification/azure/bbdcd676-7448-453c-bec7-70e5384bc290) |
>| openid | delegated | 登录用户以读取其基本个人资料信息 | 不适用 | [bbdcd676-7448-453c-bec7-70e5384bc290](https://docs.microsoft.com/microsoft-365-app-certification/azure/bbdcd676-7448-453c-bec7-70e5384bc290) |


#### <a name="non-microsoft-services-used"></a>非Microsoft 服务使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>不Microsoft 服务非活动。

#### <a name="data-access-via-bots"></a>通过机器人访问数据

如果此应用包含机器人或消息扩展，则它可以访问最终用户可识别信息 (EUII) ：名单 (名字、姓氏、显示名称、电子邮件地址) （团队中任何团队成员的姓名、姓氏、电子邮件地址) 或添加到其中聊天）。 此应用是否使用了此功能？

>无法访问 EUII。


#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或最终用户可识别信息 (EUII) 是否出现在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>应用程序遥测或日志中不显示 OII 或 EUII。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>我们的组织的管理员控制 AWS、Heroku (合作伙伴系统中) 。

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>否

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

有关此应用程序如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件的信息，由 Crowd Cast， Ltd. 提供。

| **Information** | **响应** |
|:----------------|:-------------|
| 你是否与 Microsoft 标识平台 (Azure AD) ？  | 是 |
| 您是否已查看并遵循了 Microsoft 标识平台 集成清单中列出的所有适用最佳做法？  | 是 |
| 你的应用是否使用 MSAL (Microsoft 身份验证库) 进行身份验证？ | 否 |
| 你的应用是否支持条件访问策略？ | 否 |
| 应用是否请求方案最小特权权限？ | 是 |
| 应用的静态注册权限是否准确反映应用将动态和增量请求的权限？ | 是 |
| 你的应用是否支持多租户？ | 是 |
| 你的应用是否具有机密客户端？ | 否 |
| 你是否拥有为应用注册的所有重定向统一 (URI) URI？ | 是 |
| 对于你的应用，应避免使用什么？ | - 通配符重定向 URI，<br/>- OAuth2 隐式Flow，除非 SPA 需要<br/>- 资源所有者密码凭据 (ROPC) 流 |
| 你的应用是否公开任何 Web API？ | 是 |
| 您的权限模型是否仅在客户端应用程序收到正确同意时才允许呼叫成功？ | 是 |
| 你的应用是否使用预览 API？ | 否 |
| 你的应用是否使用已弃用 API？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
