---
title: 供 AssemblyHR Inc. 程序集使用的应用程序信息。
ms.author: elmalova
author: elenamalova
ms.date: 06/08/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: 程序集的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 3597930ccf3200a42afe3ac7335199cbe5e9e885
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 10/16/2021
ms.locfileid: "60411106"
---
# <a name="assembly"></a>Assembly

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2021 年 5 月 21 日</p>

* <a href="https://teams.microsoft.com/l/app/3e674b5f-ba5d-41cc-8b06-e065b4394aeb" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002271" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

由用户向 Microsoft 提供的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | Assembly |
| ID | WA200002271 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | CarrotHR Inc. |
| 合作伙伴网站的 URL | [https://www.joinassembly.com](https://www.joinassembly.com) |
| "Teams应用程序信息"页的 URL | [https://www.joinassembly.com/about](https://www.joinassembly.com/about) |
| 隐私策略的 URL | [https://joinassembly.com/privacy-policy](https://joinassembly.com/privacy-policy) |
| 使用条款 URL | [https://joinassembly.com/terms-of-service](https://joinassembly.com/terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

此信息由一家由用户提供的，这些信息与此应用程序如何收集和存储组织数据以及组织对应用收集的数据的控制有关。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph](https://docs.microsoft.com/graph/permissions-reference)所需的任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Channel.Create | delegated | 允许用户从应用将应用分配到新创建的频道 | 我们存储频道 ID 以保持应用与正确频道同步 | [0a1b7ca8-390e-4f55-a7b5-eee089c5a905](https://docs.microsoft.com/microsoft-365-app-certification/azure/0a1b7ca8-390e-4f55-a7b5-eee089c5a905) |
>| Directory.Read.All | 应用程序 | 保持配置文件同步，以便成员在程序集中正确搜索 | 可用于在程序集中保持成员可搜索的其他任何配置文件信息 | [0a1b7ca8-390e-4f55-a7b5-eee089c5a905](https://docs.microsoft.com/microsoft-365-app-certification/azure/0a1b7ca8-390e-4f55-a7b5-eee089c5a905) |
>| Group.Read.All | delegated | 我们观察数据以确保他们可以将应用分配给正确的组 | 我们不存储组 | [0a1b7ca8-390e-4f55-a7b5-eee089c5a905](https://docs.microsoft.com/microsoft-365-app-certification/azure/0a1b7ca8-390e-4f55-a7b5-eee089c5a905) |
>| Teams.ReadBasic.All | 应用程序 | 能够将应用分配给正确的团队选项卡 | 我们不存储团队期望我们追加到的团队  | [0a1b7ca8-390e-4f55-a7b5-eee089c5a905](https://docs.microsoft.com/microsoft-365-app-certification/azure/0a1b7ca8-390e-4f55-a7b5-eee089c5a905) |
>| TeamsTab.Create | 应用程序 | 我们使用它来允许正确将应用追加到频道/团队 | 我们不会收集或存储选项卡数据 | [0a1b7ca8-390e-4f55-a7b5-eee089c5a905](https://docs.microsoft.com/microsoft-365-app-certification/azure/0a1b7ca8-390e-4f55-a7b5-eee089c5a905) |
>| email | delegated | 用户的电子邮件，以便我们可以授予他们访问其特定帐户的权限 | 用户的电子邮件，以便我们可以授予他们访问其特定帐户和匹配标识的权限 | [0a1b7ca8-390e-4f55-a7b5-eee089c5a905](https://docs.microsoft.com/microsoft-365-app-certification/azure/0a1b7ca8-390e-4f55-a7b5-eee089c5a905) |
>| 个人资料 | delegated | 用于自动填充程序集并保持与程序集中的更改Microsoft Teams | 用户的全名 | [0a1b7ca8-390e-4f55-a7b5-eee089c5a905](https://docs.microsoft.com/microsoft-365-app-certification/azure/0a1b7ca8-390e-4f55-a7b5-eee089c5a905) |


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

>删除、保留、审核、存档

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

下面将显示[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/39111' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/39111" target="_blank">在新建选项卡中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>标识信息

此信息由一家由用户提供的，这些信息与此应用程序如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件有关。

| **Information** | **响应** |
|:----------------|:-------------|
| 是否与 Microsoft 标识平台 (Azure AD) ？  | 是 |
| 您是否已审阅并遵循了 Microsoft 标识平台 集成清单中列出的所有适用最佳做法？  | 是 |
| 你的应用是否使用 MSAL (Microsoft 身份验证库) 进行身份验证？ | 否 |
| 你的应用是否支持条件访问策略？ | 否 |
| 应用是否请求方案最小特权权限？ | 是 |
| 应用的静态注册权限是否准确反映应用将动态和增量请求的权限？ | 否 |
| 你的应用是否支持多租户？ | 是 |
| 你的应用是否具有机密客户端？ | 是 |
| 你是否拥有为应用注册的所有 (统一) URI？ | 是 |
| 对于你的应用，应避免使用什么？ | - 通配符重定向 URI，<br/>- OAuth2 隐式Flow，除非 SPA 需要<br/>- 资源所有者密码凭据 (ROPC) 流 |
| 你的应用是否公开任何 Web API？ | 是 |
| 您的权限模型是否仅在客户端应用程序收到正确同意时才允许呼叫成功？ | 是 |
| 你的应用是否使用预览 API？ | 否 |
| 你的应用是否使用已弃用 API？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

