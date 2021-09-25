---
title: Yucca Technologies GmbH 的 yuccaHR 应用程序信息
ms.author: elmalova
author: elenamalova
ms.date: 07/05/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: 有关 yuccaHR 的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: f8c41d6300413db28561f03a71d62c48e52bb63f
ms.sourcegitcommit: d5c60e66355ffa8fb84565e565f8bb15a665a099
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 09/24/2021
ms.locfileid: "59785433"
---
# <a name="yuccahr"></a>yuccaHR

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2021 年 7 月 5 日</p>

* <a href="https://teams.microsoft.com/l/app/c3c1cd11-5b38-4de4-9081-44573d9383bf" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003242" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

Yucca Technologies GmbH 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | yuccaHR |
| ID | WA200003242 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | Yucca Technologies GmbH |
| 合作伙伴网站的 URL | [https://www.yuccahr.com](https://www.yuccahr.com) |
| 隐私策略的 URL | [https://www.yuccahr.com/privacy-policy](https://www.yuccahr.com/privacy-policy) |
| 使用条款 URL | [https://www.yuccahr.com/privacy-policy](https://www.yuccahr.com/privacy-policy) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

此信息由 Yucca Technologies GmbH 提供，这些信息与此应用程序如何收集和存储组织数据以及您的组织将拥有对应用收集的数据的控制有关。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph](https://docs.microsoft.com/graph/permissions-reference)所需的任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD 应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | 应用程序 |  创建约会，以根据空位了解两名员工。  | - | [815a5165-fd61-44b8-be99-6301f780bd68](https://docs.microsoft.com/microsoft-365-app-certification/azure/815a5165-fd61-44b8-be99-6301f780bd68) |
>| Channel.ReadBasic.All | 应用程序 | 配置市场活动。  (员工网络)  | ObjectId。 请求频道资源。 | [815a5165-fd61-44b8-be99-6301f780bd68](https://docs.microsoft.com/microsoft-365-app-certification/azure/815a5165-fd61-44b8-be99-6301f780bd68) |
>| ChannelMember.Read.All | 应用程序 | ObjectIds 频道中开始比赛进行市场活动的成员。 | ObjectId。 跟踪员工之间的匹配。 | [815a5165-fd61-44b8-be99-6301f780bd68](https://docs.microsoft.com/microsoft-365-app-certification/azure/815a5165-fd61-44b8-be99-6301f780bd68) |
>| Group.Read.All | 应用程序 |   配置市场活动 (员工网络) 。 | ObjectId。 请求团队资源。 | [815a5165-fd61-44b8-be99-6301f780bd68](https://docs.microsoft.com/microsoft-365-app-certification/azure/815a5165-fd61-44b8-be99-6301f780bd68) |
>| MailboxSettings.Read | 应用程序 | 确定与相应员工聊天的首选语言和导航。 | - | [815a5165-fd61-44b8-be99-6301f780bd68](https://docs.microsoft.com/microsoft-365-app-certification/azure/815a5165-fd61-44b8-be99-6301f780bd68) |
>| User.Read.All | 应用程序 | Name、ObjectId、UserPrinzipalName。 导航到与相应员工聊天。 | - | [815a5165-fd61-44b8-be99-6301f780bd68](https://docs.microsoft.com/microsoft-365-app-certification/azure/815a5165-fd61-44b8-be99-6301f780bd68) |


#### <a name="non-microsoft-services-used"></a>非Microsoft 服务使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>不Microsoft 服务非活动。

#### <a name="data-access-via-bots"></a>通过机器人访问数据

如果此应用包含机器人或消息扩展，则它可以访问最终用户可识别信息 (EUII) ：名单 (名字、姓氏、显示名称、电子邮件地址) （团队中任何团队成员的姓名、姓氏、电子邮件地址) 或添加到其中聊天）。 此应用是否使用了此功能？

>| **访问 EUII 的理由？**  | **EUII 是否存储在数据库 (中) ？** | **存储 EUII 的理由** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| 使用电子邮件计划取消查找免费时间。 | 否 |  |


#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或最终用户可识别信息 (EUII) 是否出现在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>应用程序遥测或日志中不显示 OII 或 EUII。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>客户可以通过向用户发送请求来请求删除服务中存储 support@yuccahr.com。 数据将在一周内删除。

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

此信息由 Yucca Technologies GmbH 提供有关此应用程序如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件的信息。

| **Information** | **响应** |
|:----------------|:-------------|
| 你是否与 Microsoft 标识平台 (Azure AD) ？  | 是 |
| 您是否已查看并遵循了 Microsoft 标识平台 集成清单中列出的所有适用最佳做法？  | 是 |
| 你的应用是否使用 MSAL (Microsoft 身份验证库) 进行身份验证？ | 是 |
| 你的应用是否支持条件访问策略？ | 否 |
| 应用是否请求方案最小特权权限？ | 是 |
| 应用的静态注册权限是否准确反映应用将动态和增量请求的权限？ | 是 |
| 你的应用是否支持多租户？ | 否 |
| 你的应用是否具有机密客户端？ | 是 |
| 你是否拥有为应用注册的所有重定向统一 (URI) URI？ | 是 |
| 你的应用是否公开任何 Web API？ | 是 |
| 您的权限模型是否仅在客户端应用程序收到正确同意时才允许呼叫成功？ | 是 |
| 你的应用是否使用预览 API？ | 否 |
| 你的应用是否使用已弃用 API？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
