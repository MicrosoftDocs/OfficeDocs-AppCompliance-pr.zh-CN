---
title: 在出现危机时由 RockDove Solutions， Inc. 的应用程序信息
ms.author: elmalova
author: elenamalova
ms.date: 08/27/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: 在危机情况下，所有可用的安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 4671d37d77d16004c171887f101ade7506598614
ms.sourcegitcommit: 90e6c1e10d55dc337c0884b63782cc14cf71b3c8
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 08/31/2021
ms.locfileid: "58836188"
---
# <a name="in-case-of-crisis"></a>发生危机时

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2021 年 8 月 27 日</p>

* <a href="https://teams.microsoft.com/l/app/cf430644-447e-4572-8467-3892596d05c7" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003194" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

由 RockDove Solutions， Inc. 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | 发生危机时 |
| ID | WA200003194 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | RockDove Solutions， Inc. |
| 合作伙伴网站的 URL | [https://www.rockdovesolutions.com](https://www.rockdovesolutions.com) |
| Teams信息页的 URL | [https://www.rockdovesolutions.com/in-case-of-crisis/in-case...](https://www.rockdovesolutions.com/in-case-of-crisis/in-case-of-crisis-platform) |
| 隐私策略的 URL | [https://www.rockdovesolutions.com/privacy-policy](https://www.rockdovesolutions.com/privacy-policy) |
| 使用条款 URL | [https://www.rockdovesolutions.com/terms-of-use](https://www.rockdovesolutions.com/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

此信息由 RockDove Solutions， Inc. 提供，用于说明此应用程序如何收集和存储组织数据，以及您的组织将拥有对应用收集的数据的控制。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph](https://docs.microsoft.com/graph/permissions-reference)所需的任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD 应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | delegated | 这将提供对用户日历的完全访问权限。 我们的应用显示说明、会议链接以及开始日期和结束日期。 我们的应用还允许用户在 Outlook 日历上创建事件 | 将来，事件 ID 可能存储在数据库中 | [6b4a2fee-5642-41a7-b452-d555fac690b0](https://docs.microsoft.com/microsoft-365-app-certification/azure/6b4a2fee-5642-41a7-b452-d555fac690b0) |
>| Channel.ReadBasic.All | delegated | 向用户频道授予访问权限。  频道的用户列表用于选择要将文件上载到的通道 | 不适用 | [6b4a2fee-5642-41a7-b452-d555fac690b0](https://docs.microsoft.com/microsoft-365-app-certification/azure/6b4a2fee-5642-41a7-b452-d555fac690b0) |
>| Files.ReadWrite | delegated | 不适用 | 不适用 | [6b4a2fee-5642-41a7-b452-d555fac690b0](https://docs.microsoft.com/microsoft-365-app-certification/azure/6b4a2fee-5642-41a7-b452-d555fac690b0) |
>| Files.ReadWrite.All | delegated | 我们允许用户将文件从问题管理上载到Teams | 不适用 | [6b4a2fee-5642-41a7-b452-d555fac690b0](https://docs.microsoft.com/microsoft-365-app-certification/azure/6b4a2fee-5642-41a7-b452-d555fac690b0) |
>| Sites.ReadWrite.All | delegated | 这是上传到私人频道所必需 | 不适用 | [6b4a2fee-5642-41a7-b452-d555fac690b0](https://docs.microsoft.com/microsoft-365-app-certification/azure/6b4a2fee-5642-41a7-b452-d555fac690b0) |
>| Team.ReadBasic.All | delegated | 团队列表是获取用户所属频道列表的必需项。 这使我们能够查看可用上传频道的列表。 | 不适用 | [6b4a2fee-5642-41a7-b452-d555fac690b0](https://docs.microsoft.com/microsoft-365-app-certification/azure/6b4a2fee-5642-41a7-b452-d555fac690b0) |
>| email | delegated | 身份验证后需要获取用户的电子邮件，才能与数据库中的电子邮件进行比较。 如果用户在我们的系统中没有帐户，我们将创建一个帐户。 | 我们存储电子邮件地址并创建应用帐户。 | [6b4a2fee-5642-41a7-b452-d555fac690b0](https://docs.microsoft.com/microsoft-365-app-certification/azure/6b4a2fee-5642-41a7-b452-d555fac690b0) |
>| offline_access | delegated | 这使我们能够刷新图形访问令牌 | 不适用 | [6b4a2fee-5642-41a7-b452-d555fac690b0](https://docs.microsoft.com/microsoft-365-app-certification/azure/6b4a2fee-5642-41a7-b452-d555fac690b0) |
>| openid | delegated | 通过 openid 进行身份验证所需的权限 | 不适用 | [6b4a2fee-5642-41a7-b452-d555fac690b0](https://docs.microsoft.com/microsoft-365-app-certification/azure/6b4a2fee-5642-41a7-b452-d555fac690b0) |


#### <a name="non-microsoft-services-used"></a>非Microsoft 服务已使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>| **所有非 Microsoft 服务 OII 将转移到** |  **转移了哪些 OII？** | **转移 OII 的理由？** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| AWS | 用于身份验证和通信的组织用户的电子邮件地址 | 电子邮件地址在服务中用作用户名，并且我们对 SMTP 应用程序电子邮件服务器使用 AWS |

#### <a name="data-access-via-bots"></a>通过机器人访问数据

如果此应用包含机器人或消息扩展，它可以访问最终用户可识别信息 (EUII) ：名单 (名字、姓氏、显示名称、电子邮件地址) （团队中任何团队成员的姓名、姓氏、电子邮件地址) 或添加到其中聊天）。 此应用是否使用了此功能？

>无法访问 EUII。


#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或 EUII (最终用户可识别) 是否显示在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>电子邮件地址用作系统内的主用户名。  当客户端是最新的时，将保留客户端的用户信息，在客户停止续订其服务合同后，将删除这些信息。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>我们为客户提供合作伙伴管理门户，以管理 (、替换、删除、审核、存档在服务中共享的公司信息。

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

此信息由 RockDove Solutions， Inc. 提供，用于说明此应用程序如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件。

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
| 对于你的应用，应避免使用什么？ | - 通配符重定向 URI，<br/><br/> |
| 你的应用是否公开任何 Web API？ | 否 |
| 你的应用是否使用预览 API？ | 否 |
| 你的应用是否使用已弃用 API？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
