---
title: 由 H3 Solutions， Inc. 的 AtBot 的应用程序信息
ms.author: elmalova
author: elenamalova
ms.date: 08/10/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: AtBot 的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: b5f7db2aba878720e33c5c1df2236fd034819dfb
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 10/16/2021
ms.locfileid: "60411660"
---
# <a name="atbot"></a>AtBot

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2021 年 8 月 10 日</p>

* <a href="https://teams.microsoft.com/l/app/7c01af81-ae7d-416e-98a3-c139cae8cfb0" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381219" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

H3 Solutions， Inc. 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | AtBot |
| ID | WA104381219 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | H3 Solutions, Inc. |
| 合作伙伴网站的 URL | [https://atbot.io](https://atbot.io) |
| "Teams应用程序信息"页的 URL | [https://admin.atbot.io/Docs/GettingStarted](https://admin.atbot.io/Docs/GettingStarted) |
| 隐私策略的 URL | [https://admin.atbot.io/privacy](https://admin.atbot.io/privacy) |
| 使用条款 URL | [https://admin.atbot.io/terms](https://admin.atbot.io/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

此信息由 H3 Solutions， Inc. 提供，用于说明此应用如何收集和存储组织数据，以及您的组织将拥有对应用收集的数据的控制。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph](https://docs.microsoft.com/graph/permissions-reference)所需的任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Directory.Read.All | 应用程序 | AAD组名称、AAD组 GUID、UPN | 枚举AAD组，以允许对机器人技能进行安全修整。 枚举用户以能够应用许可证。 枚举要添加为管理员/参与者的用户 | [066a6b3a-f7a0-450a-98c7-34db1da31594](https://docs.microsoft.com/microsoft-365-app-certification/azure/066a6b3a-f7a0-450a-98c7-34db1da31594) |
>| Directory.Read.All | delegated | AAD组名称、AAD组 GUID、UPN | 枚举AAD组，以允许对机器人技能进行安全修整。 枚举用户以能够应用许可证。 枚举要添加为管理员/参与者的用户 | [066a6b3a-f7a0-450a-98c7-34db1da31594](https://docs.microsoft.com/microsoft-365-app-certification/azure/066a6b3a-f7a0-450a-98c7-34db1da31594) |
>| People.Read | delegated | 否 | 从"获取人员"操作中枚举Flow。  允许机器人从 Microsoft Graph 中的 /People 终结点检索Graph。 | [066a6b3a-f7a0-450a-98c7-34db1da31594](https://docs.microsoft.com/microsoft-365-app-certification/azure/066a6b3a-f7a0-450a-98c7-34db1da31594) |
>| User.Read | delegated | 租户 ID、UPN | 允许我们访问用户的租户 ID&#8217;UPN，以允许我们将创建的流/逻辑应用与创建它们的用户进行连接。 | [066a6b3a-f7a0-450a-98c7-34db1da31594](https://docs.microsoft.com/microsoft-365-app-certification/azure/066a6b3a-f7a0-450a-98c7-34db1da31594) |
>| email | delegated | 电子邮件地址用于通过我们的支持系统联系支持人员。 | 允许我们访问用户的电子邮件地址。 | [066a6b3a-f7a0-450a-98c7-34db1da31594](https://docs.microsoft.com/microsoft-365-app-certification/azure/066a6b3a-f7a0-450a-98c7-34db1da31594) |
>| offline_access | delegated | 访问/刷新令牌。 | 允许我们使用刷新令牌来保持用户登录。 | [066a6b3a-f7a0-450a-98c7-34db1da31594](https://docs.microsoft.com/microsoft-365-app-certification/azure/066a6b3a-f7a0-450a-98c7-34db1da31594) |
>| openid | delegated | UPN，标识系统内的用户 | 允许用户登录。 | [066a6b3a-f7a0-450a-98c7-34db1da31594](https://docs.microsoft.com/microsoft-365-app-certification/azure/066a6b3a-f7a0-450a-98c7-34db1da31594) |
>| 个人资料 | delegated | UPN | 访问用户的 UPN。 | [066a6b3a-f7a0-450a-98c7-34db1da31594](https://docs.microsoft.com/microsoft-365-app-certification/azure/066a6b3a-f7a0-450a-98c7-34db1da31594) |


#### <a name="non-microsoft-services-used"></a>非Microsoft 服务已使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>不Microsoft 服务非活动。

#### <a name="data-access-via-bots"></a>通过机器人访问数据

如果此应用程序包含机器人或消息扩展，则它可以访问最终用户可识别信息 (EUII) ：名单 (名字、姓氏、显示名称、电子邮件地址) （团队中任何团队成员的姓名、姓氏、电子邮件地址) 或添加到其中聊天）。 此应用是否使用了此功能？

>| **访问 EUII 的理由？**  | **EUII 是否存储在数据库 () ？** | **存储 EUII 的理由** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| 机器人可以访问用户的 UPN，以便@mention用户或发送消息。 | UPN | 我们必须存储 UPN 以允许用户访问系统 |


#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或 EUII (最终用户可识别) 是否显示在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>租户 ID、UPN。 我们使用应用程序Insights我们的日志将持续 90 天，然后自动存档。 (https://docs.microsoft.com/azure/azure-monitor/app/data-retention-privacy)

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>管理员可以删除可能包含组名称/GUID 的AAD配置。
取消服务后，将从许可数据库中删除所有 UPN。
请参阅"Azure 服务"下的Data Residency。  使用 AtBot 生成的大部分客户特定数据都存储在客户的租户中，因此该租户的管理员可以完全控制其中的数据。

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

下面将显示[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35672' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35672" target="_blank">在新建选项卡中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>标识信息

此信息由 H3 Solutions， Inc. 提供有关此应用如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件的信息。

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
| 你的应用是否公开任何 Web API？ | 否 |
| 你的应用是否使用预览 API？ | 否 |
| 你的应用是否使用已弃用 API？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

