---
title: Easy2Meet B.V 的 Easy2Meet 的应用程序信息。
ms.author: elmalova
author: elenamalova
ms.date: 09/21/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Easy2Meet 的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 726f9ed549b3c200fda568f8b5d7a7f73c1a93ee
ms.sourcegitcommit: d5c60e66355ffa8fb84565e565f8bb15a665a099
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 09/24/2021
ms.locfileid: "59785458"
---
# <a name="easy2meet"></a>Easy2Meet

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2021 年 9 月 21 日</p>

* <a href="https://teams.microsoft.com/l/app/8dbb8c54-678e-4c02-bc35-0f393416e532" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003277" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

Easy2Meet B.V 提供的信息。 到 Microsoft：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | Easy2Meet |
| ID | WA200003277 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | Easy2Meet B.V. |
| 合作伙伴网站的 URL | [https://www.easy2meet.eu](https://www.easy2meet.eu) |
| "Teams应用程序信息"页的 URL | [https://www.easy2meet.eu](https://www.easy2meet.eu) |
| 隐私策略的 URL | [https://www.easy2meet.eu/hubfs/PrivacyStatement.pdf](https://www.easy2meet.eu/hubfs/PrivacyStatement.pdf) |
| 使用条款 URL | [https://www.easy2meet.eu/hubfs/PDF%20contractueel/Easy2Meet...](https://www.easy2meet.eu/hubfs/PDF%20contractueel/Easy2Meet%20General%20Terms%20and%20Conditions%20Sept%202020%20EN.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

此信息由 Easy2Meet B.V 提供。 关于此应用如何收集和存储组织数据，以及你的组织将拥有对应用收集的数据的控制。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph](https://docs.microsoft.com/graph/permissions-reference)所需的任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD 应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Directory.Read.All | delegated | 我们需要用户信息来管理 Easy2Meet 中的用户和会议 | 电子邮件和名称。 我们需要此权限来管理用户和会议。 | [286a2e24-18ad-432d-8698-694bcd77ecfc](https://docs.microsoft.com/microsoft-365-app-certification/azure/286a2e24-18ad-432d-8698-694bcd77ecfc) |
>| 电子邮件 | delegated | 查看当前用户的电子邮件地址。 我们需要电子邮件地址来发送会议邀请 | 电子邮件和名称。 我们需要此权限来管理用户和会议。 | [286a2e24-18ad-432d-8698-694bcd77ecfc](https://docs.microsoft.com/microsoft-365-app-certification/azure/286a2e24-18ad-432d-8698-694bcd77ecfc) |
>| openid | delegated | 我们在此处不收集数据。 我们使用此密码登录用户 | 我们在此处不收集数据。 我们使用此密码登录用户。 | [286a2e24-18ad-432d-8698-694bcd77ecfc](https://docs.microsoft.com/microsoft-365-app-certification/azure/286a2e24-18ad-432d-8698-694bcd77ecfc) |
>| profile | delegated | 我们需要用户信息来管理 Easy2Meet 中的用户和会议 | 电子邮件和名称。 我们需要此权限来管理用户和会议。 | [286a2e24-18ad-432d-8698-694bcd77ecfc](https://docs.microsoft.com/microsoft-365-app-certification/azure/286a2e24-18ad-432d-8698-694bcd77ecfc) |

#### <a name="data-access-using-other-microsoft-apis"></a>使用其他 Microsoft API 进行数据访问

基于组织构建的应用和Microsoft 365可能会使用除 Microsoft Graph 外的其他 Microsoft API 来收集或处理 OII (组织) 。 列出除 Microsoft API Graph此应用使用的任何 Microsoft API。

>| **API** |  **是否收集 OII？** |  **收集哪些 OII？** | **收集 OII 的理由？** | **是否存储 OII？** | **存储 OII 的理由** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| SharePoint Online | 否 |  |  |  |  |
>| MS Exchange Online | 否 |  |  |  |  |

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

>审核

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

此信息由 Easy2Meet B.V 提供。 关于此应用如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件。

| **Information** | **响应** |
|:----------------|:-------------|
| 你是否与 Microsoft 标识平台 (Azure AD) ？  | 是 |
| 您是否已查看并遵循了 Microsoft 标识平台 集成清单中列出的所有适用最佳做法？  | 是 |
| 你的应用是否使用 MSAL (Microsoft 身份验证库) 进行身份验证？ | 是 |
| 你的应用是否支持条件访问策略？ | 否 |
| 应用是否请求方案最小特权权限？ | 是 |
| 应用的静态注册权限是否准确反映应用将动态和增量请求的权限？ | 是 |
| 你的应用是否支持多租户？ | 是 |
| 你的应用是否具有机密客户端？ | 是 |
| 你是否拥有为应用注册的所有重定向统一 (URI) URI？ | 是 |
| 你的应用是否公开任何 Web API？ | 是 |
| 您的权限模型是否仅在客户端应用程序收到正确同意时才允许呼叫成功？ | 是 |
| 你的应用是否使用预览 API？ | 否 |
| 你的应用是否使用已弃用 API？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
