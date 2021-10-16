---
title: Regroove 解决方案为 Navo 提供的应用程序信息
ms.author: elmalova
author: elenamalova
ms.date: 01/20/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Navo 的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 554d59fbb03382ab517bb2f928823a33b2ec4ee0
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 10/16/2021
ms.locfileid: "60411527"
---
# <a name="navo"></a>Navo

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2020 年 8 月 24 日</p>

* <a href="https://teams.microsoft.com/l/app/d8653da2-4682-4b92-b659-485087957897" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001047" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

Regroove 解决方案提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | Navo |
| ID | WA200001047 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | Regroove Solutions |
| 合作伙伴网站的 URL | [https://regroove.ca ; https://getnavo.com](https://regroove.ca ; https://getnavo.com) |
| 隐私策略的 URL | [https://getnavo.com/privacy-policy/](https://getnavo.com/privacy-policy/) |
| 使用条款 URL | [https://getnavo.com/terms-of-service/](https://getnavo.com/terms-of-service/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

此信息由 Regroove Solutions 提供，它有关此应用程序如何收集和存储组织数据，以及您的组织将拥有对应用收集的数据的控制。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph](https://docs.microsoft.com/graph/permissions-reference)所需的任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Directory.Read.All | 应用程序 | 我们存储用户计数，并按计费周期查询一次。 我们还使用租赁 ID 作为组织的 ID。 | 允许我们计算租赁中用于计费的用户数。 它还允许我们查询用户位于哪些组，以便可以使用安全修整来保护某些数据。 我们还查询组织的租赁 ID。 | [75ce4e02-e37b-479c-81c7-438348a2a251](https://docs.microsoft.com/microsoft-365-app-certification/azure/75ce4e02-e37b-479c-81c7-438348a2a251) |
>| User.Read | delegated | 不存储任何数据 | 登录并读取用户个人资料 | [75ce4e02-e37b-479c-81c7-438348a2a251](https://docs.microsoft.com/microsoft-365-app-certification/azure/75ce4e02-e37b-479c-81c7-438348a2a251) |


#### <a name="non-microsoft-services-used"></a>非Microsoft 服务已使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>| **所有非Microsoft 服务 OII 将转移到** |  **转移了哪些 OII？** | **转移 OII 的理由？** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| 我们将租户 ID 和用户计数存储在 Stripe 中。 |  | User.Read | Delegated | 登录并读取用户配置文件 - 未存储任何数据 |

#### <a name="data-access-via-bots"></a>通过机器人访问数据

如果此应用程序包含机器人或消息扩展，则它可以访问最终用户可识别信息 (EUII) ：名单 (名字、姓氏、显示名称、电子邮件地址) （团队中任何团队成员的姓名、姓氏、电子邮件地址) 或添加到其中聊天）。 此应用是否使用了此功能？

>无法访问 EUII。


#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或 EUII (最终用户可识别) 是否显示在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>是的，在应用程序Insights存储用户经过身份验证的 ID 和租户 ID (用户帐户 id) 。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>我们存储的所有数据 (服务（如 Stripe 或 Application Insights) ）存储在 Azure Cosmos 数据库中。 所有管理员都使用 2FA，并且访问权限仅限于我们员工的子集。

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>是

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

下面将显示[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35974' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35974" target="_blank">在新建选项卡中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


