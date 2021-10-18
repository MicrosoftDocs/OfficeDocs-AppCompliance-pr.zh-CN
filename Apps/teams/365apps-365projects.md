---
title: 365 项目的应用程序信息 （按 365Apps）
ms.author: elmalova
author: elenamalova
ms.date: 03/18/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: 365 项目的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security 应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 30670ebb5d80435dfbe77b3e735aeb72a695907c
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 10/18/2021
ms.locfileid: "60430914"
---
# <a name="365projects"></a>365Projects

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2021 年 3 月 16 日</p>

* <a href="https://teams.microsoft.com/l/app/a9c31598-b014-4e20-b3bd-3d275fa738d3" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002160" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

365Apps 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | 365Projects |
| ID | WA200002160 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | 365Apps |
| 合作伙伴网站的 URL | [https://365apps.com.au](https://365apps.com.au) |
| 应用程序Teams页的 URL | [https://365projects.app](https://365projects.app) |
| 隐私策略的 URL | [https://365projects.app/privacy](https://365projects.app/privacy) |
| 使用条款 URL | [https://365projects.app/eula](https://365projects.app/eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

此信息由 365Apps 提供有关此应用程序如何收集和存储组织数据以及您的组织将拥有对应用收集的数据的控制的信息。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph](https://docs.microsoft.com/graph/permissions-reference)所需的任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Channel.ReadBasic.All | delegated | 团队中将项目与频道链接的频道 | 团队中将项目与频道链接的频道 | [99a0a9b1-5d28-45df-9f99-792aa32795f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/99a0a9b1-5d28-45df-9f99-792aa32795f4) |
>| Group.Read.All | delegated | 获取工作组规划器/规划器任务，如果另一个最小特权范围允许应用获取用户计划和计划任务，但遗憾的是没有允许此操作的范围 | 未存储在 DB 中 | [99a0a9b1-5d28-45df-9f99-792aa32795f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/99a0a9b1-5d28-45df-9f99-792aa32795f4) |
>| Group.ReadWrite.All | 应用程序 | 创建Teams  | 未存储在 DB 中 | [99a0a9b1-5d28-45df-9f99-792aa32795f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/99a0a9b1-5d28-45df-9f99-792aa32795f4) |
>| People.Read | delegated | 用户名，将它们添加为工作组成员或为其分配任务 | 用户 Guid 存储在任务分配中 | [99a0a9b1-5d28-45df-9f99-792aa32795f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/99a0a9b1-5d28-45df-9f99-792aa32795f4) |
>| Team.ReadBasic.All | delegated | 加入的团队名称，将项目链接到Teams频道 | 团队 Guid 存储在项目元数据中以建立链接 | [99a0a9b1-5d28-45df-9f99-792aa32795f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/99a0a9b1-5d28-45df-9f99-792aa32795f4) |
>| User.Read | delegated | 获取用户信息以在标头中显示此信息  | 首次预配租户时，用户电子邮件存储为所有者 | [99a0a9b1-5d28-45df-9f99-792aa32795f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/99a0a9b1-5d28-45df-9f99-792aa32795f4) |
>| User.Read.All | delegated | 读取用户以更新任务分配 | 仅存储用户 Guid，未在 DB 中存储任何个人识别信息 | [99a0a9b1-5d28-45df-9f99-792aa32795f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/99a0a9b1-5d28-45df-9f99-792aa32795f4) |


#### <a name="non-microsoft-services-used"></a>非Microsoft 服务已使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>不Microsoft 服务非活动。

#### <a name="data-access-via-bots"></a>通过机器人访问数据

如果此应用程序包含机器人或消息扩展，则它可以访问最终用户可识别信息 (EUII) ：名单 (名字、姓氏、显示名称、电子邮件地址) （团队中任何团队成员的姓名、姓氏、电子邮件地址) 或添加到其中聊天）。 此应用是否使用了此功能？

>无法访问 EUII。


#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或 EUII (最终用户可识别) 是否显示在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>应用程序遥测或日志中不显示 OII 或 EUII。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>应用不会存储除应用管理员 Guid 之外的用户数据 (用户在租户内使用应用)  

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

下面将显示[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36555' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36555" target="_blank">在新建选项卡中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>标识信息

此信息由 365Apps 提供有关此应用程序如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件的信息。

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
| 对于你的应用，应避免使用什么？ | ,<br/>- OAuth2 隐式Flow，除非 SPA 需要<br/> |
| 你的应用是否公开任何 Web API？ | 是 |
| 您的权限模型是否仅在客户端应用程序收到正确同意时才允许呼叫成功？ | 是 |
| 你的应用是否使用预览 API？ | 否 |
| 你的应用是否使用已弃用 API？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
