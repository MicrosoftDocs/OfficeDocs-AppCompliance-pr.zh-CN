---
title: Alight 的 Zignals 应用程序信息
ms.author: elmalova
author: elenamalova
ms.date: 08/17/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Zignals 的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 313529eecfcf1e8e129bb22cb5ee4c7b53b9e2c5
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 09/12/2021
ms.locfileid: "59279271"
---
# <a name="zignals"></a>Zignals

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2021 年 8 月 17 日</p>

* <a href="https://teams.microsoft.com/l/app/a0b58ca7-958d-4343-a2dc-a75f2eeb0953" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003201" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

Alight 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | Zignals |
| ID | WA200003201 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | Alight |
| 合作伙伴网站的 URL | [https://www.alight.eu](https://www.alight.eu) |
| 应用程序Teams页的 URL | [https://zignals.eu/zignals-support/](https://zignals.eu/zignals-support/) |
| 隐私策略的 URL | [https://www.zignals.eu/privacy-policy-zignals-for-teams/](https://www.zignals.eu/privacy-policy-zignals-for-teams/) |
| 使用条款 URL | [https://zignals.eu/terms](https://zignals.eu/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

Alight 提供了此信息，这些信息与此应用程序如何收集和存储组织数据以及组织将拥有对应用收集的数据的控制有关。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph所需的](https://docs.microsoft.com/graph/permissions-reference)任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD 应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.Read | delegated | 对于" &quot; 我的会议 &quot; "区域，我们获取用户今天和明天的会议。 | 应用程序数据库中未存储任何信息。 | [a0b58ca7-958d-4343-a2dc-a75f2eeb0953](https://docs.microsoft.com/microsoft-365-app-certification/azure/a0b58ca7-958d-4343-a2dc-a75f2eeb0953) |
>| Sites.ReadWrite.All | delegated | 我们会获取用户关注的所有SharePoint网站，并会显示在"我的团队合作"区域中，并获取用户的所有 SharePoint 任务，并显示在"我的任务" &quot; &quot; &quot; 区域中 &quot; 。 | 应用程序数据库中未存储任何信息。 | [a0b58ca7-958d-4343-a2dc-a75f2eeb0953](https://docs.microsoft.com/microsoft-365-app-certification/azure/a0b58ca7-958d-4343-a2dc-a75f2eeb0953) |
>| Tasks.ReadWrite | delegated | 我们阅读用户的 Planner，并微软待办任务，并显示在"我的任务" &quot; 区域中 &quot; 。 | 应用程序数据库中未存储任何信息。 | [a0b58ca7-958d-4343-a2dc-a75f2eeb0953](https://docs.microsoft.com/microsoft-365-app-certification/azure/a0b58ca7-958d-4343-a2dc-a75f2eeb0953) |
>| Team.ReadBasic.All | delegated | 我们将获取用户加入的团队，并让他们显示在"我的团队合作 &quot; " &quot; 区域中。 | 应用程序数据库中未存储任何信息。 | [a0b58ca7-958d-4343-a2dc-a75f2eeb0953](https://docs.microsoft.com/microsoft-365-app-certification/azure/a0b58ca7-958d-4343-a2dc-a75f2eeb0953) |
>| User.ReadBasic.All | delegated | 在 &quot; "我的 &quot; 文档"区域中，我们显示协作的用户 | 应用程序数据库中未存储任何信息。 | [a0b58ca7-958d-4343-a2dc-a75f2eeb0953](https://docs.microsoft.com/microsoft-365-app-certification/azure/a0b58ca7-958d-4343-a2dc-a75f2eeb0953) |
>| User.ReadWrite | delegated | 用户的最近文档显示在"我的文档" &quot; 区域中 &quot; 。 用户收藏的应用在 MS 应用中存储为架构Graph。 在图形中读取和写入数据需要此权限级别。 | 应用程序数据库中未存储任何信息。 | [a0b58ca7-958d-4343-a2dc-a75f2eeb0953](https://docs.microsoft.com/microsoft-365-app-certification/azure/a0b58ca7-958d-4343-a2dc-a75f2eeb0953) |
>| email | delegated | 获取用户电子邮件 (MS Teams作用域)  | 未存储在 DB 中 | [a0b58ca7-958d-4343-a2dc-a75f2eeb0953](https://docs.microsoft.com/microsoft-365-app-certification/azure/a0b58ca7-958d-4343-a2dc-a75f2eeb0953) |
>| offline_access | delegated | 标准 MS Teams作用域 | 未存储在 DB 中 | [a0b58ca7-958d-4343-a2dc-a75f2eeb0953](https://docs.microsoft.com/microsoft-365-app-certification/azure/a0b58ca7-958d-4343-a2dc-a75f2eeb0953) |
>| openid | delegated | 登录用户。 | 应用程序数据库中未存储任何信息。 | [a0b58ca7-958d-4343-a2dc-a75f2eeb0953](https://docs.microsoft.com/microsoft-365-app-certification/azure/a0b58ca7-958d-4343-a2dc-a75f2eeb0953) |
>| 个人资料 | delegated | 登录过程 MS Teams | 未存储在 DB 中 | [a0b58ca7-958d-4343-a2dc-a75f2eeb0953](https://docs.microsoft.com/microsoft-365-app-certification/azure/a0b58ca7-958d-4343-a2dc-a75f2eeb0953) |


#### <a name="non-microsoft-services-used"></a>非Microsoft 服务使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>不Microsoft 服务非活动。

#### <a name="data-access-via-bots"></a>通过机器人访问数据

如果此应用包含机器人或消息扩展，它可以访问最终用户可识别信息 (EUII) ：名单 (名字、姓氏、显示名称、电子邮件地址) （团队中任何团队成员的姓名、姓氏、电子邮件地址) 或添加到其中聊天）。 此应用是否使用了此功能？

>无法访问 EUII。


#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或最终用户可识别信息 (EUII) 是否出现在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>应用程序遥测或日志中不显示 OII 或 EUII。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>数据仅存储在 Azure 中。 在这里，我们使用管理员界面控制数据 (包括删除、审核等) 

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

Alight 已提供有关此应用如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件的信息。

| **Information** | **响应** |
|:----------------|:-------------|
| 你是否与 Microsoft 标识平台 (Azure AD) ？  | 是 |
| 您是否已审阅并遵循了 Microsoft 标识平台 集成清单中列出的所有适用最佳做法？  | 是 |
| 你的应用是否使用 MSAL (Microsoft 身份验证库) 进行身份验证？ | 否 |
| 你的应用是否支持条件访问策略？ | 否 |
| 应用是否请求方案最小特权权限？ | 是 |
| 应用的静态注册权限是否准确反映应用将动态和增量请求的权限？ | 是 |
| 你的应用是否支持多租户？ | 是 |
| 你的应用是否具有机密客户端？ | 是 |
| 你是否拥有为应用注册的所有 (统一) URI？ | 是 |
| 你的应用是否公开任何 Web API？ | 是 |
| 您的权限模型是否仅在客户端应用程序收到正确同意时才允许呼叫成功？ | 是 |
| 你的应用是否使用预览 API？ | 是 |
| 你的应用是否使用已弃用 API？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
