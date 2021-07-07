---
title: 工作板的应用程序信息
ms.author: elmalova
author: elenamalova
ms.date: 06/04/2021
ms.topic: article
ms.service: attestation
certification_type: certified
description: Workboard 的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 94ad01886baec72c516f5e32953d8a7cbea17204
ms.sourcegitcommit: b41944062ede123fa1fadd38706271aae2b01d3f
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 07/02/2021
ms.locfileid: "53265758"
---
# <a name="workboard"></a>Workboard

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>开发人员上次更新时间：2021 年 6 月 4 日</p>

* <a href="https://teams.microsoft.com/l/app/28d0282b-3cd2-49f0-90bb-a016843750c6" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381599" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

Workboard 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | Workboard |
| ID | WA104381599 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | Workboard |
| 合作伙伴网站的 URL | [https://www.workboard.com](https://www.workboard.com) |
| "Teams应用程序信息"页的 URL | [https://www.workboard.com/microsoft/](https://www.workboard.com/microsoft/) |
| 隐私策略的 URL | [https://www.workboard.com/license/privacy-policy.html](https://www.workboard.com/license/privacy-policy.html) |
| 使用条款 URL | [https://www.workboard.com/license/terms_of_use_v1.php](https://www.workboard.com/license/terms_of_use_v1.php) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

此信息由 Workboard 提供，与此应用程序如何收集和存储组织数据以及组织对应用收集的数据的控制有关。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph所需的](https://docs.microsoft.com/graph/permissions-reference)任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD 应用 ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | delegated | 电子邮件地址和用户的 ID。  它用于将用户映射到 WorkBoard 的用户 ID | WorkBoard 仅将用户标识存储在其数据库中 | User.Read |


#### <a name="non-microsoft-services-used"></a>非Microsoft 服务使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>不Microsoft 服务非活动。

#### <a name="data-access-via-bots"></a>通过机器人访问数据

如果此应用程序包含机器人或消息扩展，则它可以访问最终用户可识别信息 (EUII) ：名单 (名字、姓氏、显示名称、电子邮件地址) （团队中任何团队成员的姓名、姓氏、电子邮件地址) 或添加到其中聊天）。 此应用是否使用了此功能？

>| **访问 EUII 的理由？**  | **EUII 是否存储在数据库 (中) ？** | **存储 EUII 的理由** |
>|:--------------------------------|:---------------------|:--------------------------|
>| 用户 ID 用于由 WorkBord Teams主动通知 | 用户电子邮件地址和 ID | 用于将用户映射到 WorkBoard 的用户 ID |


#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或 EUII (最终用户可识别) 是否显示在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>应用程序遥测或日志中不显示 OII 或 EUII。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>WorkBoard 不将组织数据存储在合作伙伴的系统中

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>是

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

下面将显示[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/29004' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/29004" target="_blank">在新建选项卡中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>标识信息

此信息由 Workboard 提供有关此应用程序如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件的信息。

| **Information** | **响应** |
|:----------------|:-------------|
| 你是否与 Microsoft 标识平台 (Azure AD) ？  | 是 |
| 您是否已查看并遵循了 Microsoft 标识平台 清单中列出的所有适用最佳做法？  | 是 |
| 你的应用是否使用 MSAL (Microsoft 身份验证库) 进行身份验证？ | 否 |
| 你的应用是否支持条件访问策略？ | 是 |
| 列出支持的策略类型 | WorkBoard 已实现自己的访问策略，这些策略在应用内强制执行。  用户的组织、团队和标识用于确定访问权限。 |
| 应用是否请求方案最小特权权限？ | 是 |
| 应用的静态注册权限是否准确反映应用将动态和增量请求的权限？ | 是 |
| 你的应用是否支持多租户？ | 是 |
| 你的应用是否具有机密客户端？ | 否 |
| 你是否拥有为应用注册的所有重定向统 (URI) URI？ | 是 |
| 你的应用是否公开任何 Web API？ | 是 |
| 您的权限模型是否仅在客户端应用程序收到正确同意时允许呼叫成功？ | 是 |
| 你的应用是否使用预览 API？ | 否 |
| 你的应用是否使用已弃用 API？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
