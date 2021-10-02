---
title: 星号的应用程序信息
ms.author: elmalova
author: elenamalova
ms.date: 09/28/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Aster 的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 10fcbb93f3d6e7b8c851b1f1ecaf63a57f4d1204
ms.sourcegitcommit: 874e586a5a9a5eb0c5c5aae0c59f7c75c0742ec4
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 10/01/2021
ms.locfileid: "60080894"
---
# <a name="aster"></a>星号

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2021 年 9 月 28 日</p>

* <a href="https://teams.microsoft.com/l/app/2d8e8042-66df-4605-8c3a-9ca8962f3e99" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002379" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

Aster 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | 星号 |
| ID | WA200002379 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | 星号 |
| 合作伙伴网站的 URL | [https://asterapp.co](https://asterapp.co) |
| "Teams应用程序信息"页的 URL | [https://asterapp.co/solution/](https://asterapp.co/solution/) |
| 隐私策略的 URL | [https://asterapp.co/politique-de-confidentialite/](https://asterapp.co/politique-de-confidentialite/) |
| 使用条款 URL | [https://asterapp.co/conditions-generales/](https://asterapp.co/conditions-generales/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

此信息由 Aster 提供，用于了解此应用如何收集和存储组织数据，以及组织将拥有对应用收集的数据的控制。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph](https://docs.microsoft.com/graph/permissions-reference)所需的任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD 应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Directory.Read.All | delegated | 用于发送 Sharepoint 文档 Planner 任务的目录列表 | 无 | [27c89ce8-b449-4959-b801-988d8b727512](https://docs.microsoft.com/microsoft-365-app-certification/azure/27c89ce8-b449-4959-b801-988d8b727512) |
>| Group.ReadWrite.All | delegated | 用于发送现有或已创建组中 Sharepoint 文档 Planner 任务的组列表 | 无 | [27c89ce8-b449-4959-b801-988d8b727512](https://docs.microsoft.com/microsoft-365-app-certification/azure/27c89ce8-b449-4959-b801-988d8b727512) |
>| Notes.ReadWrite.All | delegated | 备注要写入OneNote | 无 | [27c89ce8-b449-4959-b801-988d8b727512](https://docs.microsoft.com/microsoft-365-app-certification/azure/27c89ce8-b449-4959-b801-988d8b727512) |
>| Tasks.ReadWrite.Shared | delegated | 任务、分配、截止时间 | 所有这些数据用于将 API 任务Graph Aster 任务同步 | [27c89ce8-b449-4959-b801-988d8b727512](https://docs.microsoft.com/microsoft-365-app-certification/azure/27c89ce8-b449-4959-b801-988d8b727512) |
>| User.Read | delegated | 用于标识用户的用户电子邮件 | 分配中的用户电子邮件，例如 | [27c89ce8-b449-4959-b801-988d8b727512](https://docs.microsoft.com/microsoft-365-app-certification/azure/27c89ce8-b449-4959-b801-988d8b727512) |
>| offline_access | delegated | 未收集数据，只是似乎刷新令牌 | 无 | [27c89ce8-b449-4959-b801-988d8b727512](https://docs.microsoft.com/microsoft-365-app-certification/azure/27c89ce8-b449-4959-b801-988d8b727512) |


#### <a name="non-microsoft-services-used"></a>非Microsoft 服务使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>不Microsoft 服务非活动。

#### <a name="data-access-via-bots"></a>通过机器人访问数据

如果此应用包含机器人或消息扩展，则它可以访问最终用户可识别信息 (EUII) ：团队中任何团队成员的姓名、姓氏、显示名称、电子邮件地址 (名单或添加到其中的任何团队成员的电子邮件地址) 。 此应用是否使用了此功能？

>| **访问 EUII 的理由？**  | **EUII 是否存储在数据库 (中) ？** | **存储 EUII 的理由** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| 以人工和个性化方式与用户通信 | 否 |  |


#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或最终用户可识别信息 (EUII) 是否出现在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>记录所有访问，使用用户电子邮件进行标识

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>RGPD 合约

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

此信息由 Aster 提供，用于说明此应用如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件。

| **Information** | **响应** |
|:----------------|:-------------|
| 你是否与 Azure AD (Microsoft 标识平台) ？  | 是 |
| 您是否已审阅并遵循了 Microsoft 标识平台 集成清单中列出的所有适用最佳做法？  | 是 |
| 你的应用是否使用 MSAL (Microsoft 身份验证库) 进行身份验证？ | 否 |
| 你的应用是否支持条件访问策略？ | 否 |
| 应用是否请求方案最小特权权限？ | 是 |
| 应用的静态注册权限是否准确反映应用将动态和增量请求的权限？ | 否 |
| 你的应用是否支持多租户？ | 是 |
| 你的应用是否具有机密客户端？ | 是 |
| 你是否拥有为应用注册的所有 (统一) URI？ | 是 |
| 你的应用是否公开任何 Web API？ | 否 |
| 你的应用是否使用预览 API？ | 否 |
| 你的应用是否使用已弃用 API？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
