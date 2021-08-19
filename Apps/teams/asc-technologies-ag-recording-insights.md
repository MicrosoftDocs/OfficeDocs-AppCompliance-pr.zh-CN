---
title: ASC Technologies AG Insights ASC 录制服务的应用程序信息
ms.author: elmalova
author: elenamalova
ms.date: 06/02/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: ASC Recording Insights 的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security 应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: efeac55591daa01827df42e8b473acdea8ee66f5
ms.sourcegitcommit: 3660f89e183c638979a31c295ac059daa6c387dd
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 08/18/2021
ms.locfileid: "58391865"
---
# <a name="asc-recording-insights"></a>ASC 录制Insights

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2021 年 6 月 2 日</p>

* <a href="https://teams.microsoft.com/l/app/8f79287d-5850-42f1-9af2-48ddf6ef89a8" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000708" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

ASC Technologies AG 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | ASC 录制Insights |
| ID | WA200000708 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | ASC Technologies AG |
| 合作伙伴网站的 URL | [https://asctechnologies.com/english/index.html](https://asctechnologies.com/english/index.html) |
| "Teams应用程序信息"页的 URL | [https://asctechnologies.com/english/ASC_Recording_Insights_...](https://asctechnologies.com/english/ASC_Recording_Insights_Compliance_Recording_for_Microsoft_Teams.html) |
| 隐私策略的 URL | [https://teams.asc-recording.app/privacy](https://teams.asc-recording.app/privacy) |
| 使用条款 URL | [https://asctechnologies.com/english/asc_impressum.html](https://asctechnologies.com/english/asc_impressum.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

此信息由 ASC Technologies AG 提供，用于了解此应用如何收集和存储组织数据，以及您的组织将拥有对应用收集的数据的控制。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph所需的](https://docs.microsoft.com/graph/permissions-reference)任何 Microsoft 权限。

>| **权限**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD 应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.Read | 应用程序 | 用户会议的信息 | 会议的对象 ID | [a22e0150-3615-46aa-b0a7-086c87a9f38d](https://docs.microsoft.com/microsoft-365-app-certification/azure/a22e0150-3615-46aa-b0a7-086c87a9f38d) |
>| Chat.Read | 应用程序 | 生成的用户聊天 | 聊天的对象 ID | [a22e0150-3615-46aa-b0a7-086c87a9f38d](https://docs.microsoft.com/microsoft-365-app-certification/azure/a22e0150-3615-46aa-b0a7-086c87a9f38d) |
>| Chat.Read.All | 应用程序 | 生成的用户聊天 | 聊天的对象 ID | [a22e0150-3615-46aa-b0a7-086c87a9f38d](https://docs.microsoft.com/microsoft-365-app-certification/azure/a22e0150-3615-46aa-b0a7-086c87a9f38d) |
>| Group.Read.All | 应用程序 | 成员资格 AD 组用户 | AD 组的对象 ID | [a22e0150-3615-46aa-b0a7-086c87a9f38d](https://docs.microsoft.com/microsoft-365-app-certification/azure/a22e0150-3615-46aa-b0a7-086c87a9f38d) |
>| OnlineMeetings.Read.All | 应用程序 | 用户会议的信息 | 会议的对象 ID | [a22e0150-3615-46aa-b0a7-086c87a9f38d](https://docs.microsoft.com/microsoft-365-app-certification/azure/a22e0150-3615-46aa-b0a7-086c87a9f38d) |
>| User.Read | 应用程序 | 用户的名和姓 | 用户的对象 ID | [a22e0150-3615-46aa-b0a7-086c87a9f38d](https://docs.microsoft.com/microsoft-365-app-certification/azure/a22e0150-3615-46aa-b0a7-086c87a9f38d) |
>| User.ReadBasic.All | 应用程序 | 用户的基本数据 | 用户的对象 ID | [a22e0150-3615-46aa-b0a7-086c87a9f38d](https://docs.microsoft.com/microsoft-365-app-certification/azure/a22e0150-3615-46aa-b0a7-086c87a9f38d) |

#### <a name="data-access-using-other-microsoft-apis"></a>使用其他 Microsoft API 进行数据访问

基于组织构建的应用和Microsoft 365可以使用除 Microsoft Graph 外的其他 Microsoft API 来收集或处理 OII (个人身份) 。 列出此应用使用的任何 Microsoft GRAPH Microsoft API。

>| **API** |  **是否收集 OII？** |  **收集哪些 OII？** | **收集 OII 的理由？** | **是否存储 OII？** | **存储 OII 的理由** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| 导出 API | 否 |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>非Microsoft 服务使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>不Microsoft 服务非活动。

#### <a name="data-access-via-bots"></a>通过机器人访问数据

如果此应用包含机器人或消息扩展，则它可以访问最终用户可识别信息 (EUII) ：名单 (名字、姓氏、显示名称、电子邮件地址) （团队中任何团队成员的姓名、姓氏、电子邮件地址) ）或添加到其中聊天。 此应用是否使用了此功能？

>无法访问 EUII。


#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或最终用户可识别信息 (EUII) 是否出现在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>应用程序遥测或日志中不显示 OII 或 EUII。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>在合作伙伴的系统中没有数据

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析 OII (或) 收集或存储的任何组织可识别信息？

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

此信息由 ASC Technologies AG 提供有关此应用如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件的信息。

| **Information** | **响应** |
|:----------------|:-------------|
| 你是否与 Microsoft 标识平台 (Azure AD) ？  | 是 |
| 您是否已审阅并遵循了 Microsoft 标识平台 集成清单中列出的所有适用最佳做法？  | 是 |
| 你的应用是否使用 MSAL (Microsoft 身份验证库) 进行身份验证？ | 是 |
| 你的应用是否支持条件访问策略？ | 否 |
| 应用是否请求方案最小特权权限？ | 是 |
| 应用的静态注册权限是否准确反映应用将动态和增量请求的权限？ | 是 |
| 你的应用是否支持多租户？ | 是 |
| 你的应用是否具有机密客户端？ | 是 |
| 你是否拥有为应用注册的所有 (统一) URI？ | 是 |
| 对于你的应用，应避免使用什么？ | ,<br/>- OAuth2 隐式Flow，除非 SPA 需要<br/> |
| 你的应用是否公开任何 Web API？ | 否 |
| 你的应用是否使用预览 API？ | 否 |
| 你的应用是否使用已弃用 API？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
