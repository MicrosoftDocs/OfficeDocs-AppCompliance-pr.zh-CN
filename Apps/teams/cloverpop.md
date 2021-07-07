---
title: Cloverpop 的应用程序信息
ms.author: elmalova
author: elenamalova
ms.date: 08/24/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Cloverpop 的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: c6be013237c6368624687f7eb297a7149c28a548
ms.sourcegitcommit: 65d4afba6f46d45315b2a90d2b21ce1737707e7b
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 07/02/2021
ms.locfileid: "53281344"
---
# <a name="cloverpop"></a>Cloverpop

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2020 年 8 月 24 日</p>

* <a href="https://teams.microsoft.com/l/app/3f8519a6-2428-4088-8d12-1b4fd234ff19" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001803" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

Cloverpop 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | Cloverpop |
| ID | WA200001803 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | Cloverpop |
| 合作伙伴网站的 URL | [https://www.cloverpop.com/](https://www.cloverpop.com/) |
| 隐私策略的 URL | [https://www.cloverpop.com/privacy-policy/](https://www.cloverpop.com/privacy-policy/) |
| 使用条款 URL | [https://www.cloverpop.com/terms-of-service](https://www.cloverpop.com/terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

Cloverpop 提供了此信息，这些信息与此应用程序如何收集和存储组织数据以及您的组织将拥有对应用收集的数据的控制有关。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph所需的](https://docs.microsoft.com/graph/permissions-reference)任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD 应用 ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | delegated | 等存储用户数据。 email， oid， givenName， familyName， user头像， user object id. organization id (tenantId) ， organization 显示名称， Also we store on our side teams/channels names， ids， teams members. 当用户创建此数据并与决策交互时，我们会将该数据与创建该数据的用户、团队和组织关联。 我们还需要在友好的 UX 中显示此所有权，从而存储显示信息，例如用户&#8217;头像。 | 允许用户登录并授予应用对 UPN 的访问权限，以启用无提示登录&#8221; - 电子邮件、名称、oid、tid、givenName、surname、familyName、用户头像 (photo) 、组织 displayName | 1040474b-572d-4575-a423-95dd262a8b8a |
>| openid | delegated | 存储用户数据（如 ）。 email， oid， givenName， familyName， user头像， user object id. organization id (tenantId) ， organization 显示名称， Also we store on our side teams/channels names， ids， teams members. 当用户创建此数据并与决策交互时，我们会将该数据与创建该数据的用户、团队和组织关联。 我们还需要在友好的 UX 中显示此所有权，从而存储显示信息，例如用户&#8217;头像。 | 若要实现&#8220;Web Teams&#8221;登录。 | 1040474b-572d-4575-a423-95dd262a8b8a |
>| 个人资料 | delegated | 存储用户数据（如 ）。 email， oid， givenName， familyName， user头像， user object id. organization id (tenantId) ， organization 显示名称， Also we store on our side teams/channels names， ids， teams members. 当用户创建此数据并与决策交互时，我们会将该数据与创建该数据的用户、团队和组织关联。 我们还需要在友好的 UX 中显示此所有权，从而存储显示信息，例如用户&#8217;头像。 | 若要实现&#8220;Web Teams&#8221;登录。 | 1040474b-572d-4575-a423-95dd262a8b8a |


#### <a name="non-microsoft-services-used"></a>非Microsoft 服务使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>不Microsoft 服务非活动。

#### <a name="data-access-via-bots"></a>通过机器人访问数据

如果此应用程序包含机器人或消息扩展，则它可以访问最终用户可识别信息 (EUII) ：名单 (名字、姓氏、显示名称、电子邮件地址) （团队中任何团队成员的姓名、姓氏、电子邮件地址) 或添加到其中聊天）。 此应用是否使用了此功能？

>| **访问 EUII 的理由？**  | **EUII 是否存储在数据库 (中) ？** | **存储 EUII 的理由** |
>|:--------------------------------|:---------------------|:--------------------------|
>| 我们访问第一个/最后显示名称个数据，以便准确显示特定用户已采取与决策相关的操作。 我们将电子邮件地址用作 db 中每个用户的唯一标识符，因为允许每个用户属于多个组织。 我们仅在他们与应用交互时（例如，当他们响应投票时）访问此数据。 | 我们存储第一个/显示名称数据，以便准确显示特定用户已采取与决策相关的操作。  我们存储电子邮件地址是因为我们使用它作为 db 中每个用户的唯一标识符，因为允许每个用户属于多个组织。 我们仅在他们与应用交互时（例如，当他们响应投票时）存储此数据。 我们的决策数据应该是决策的记录系统，因此存储数据以标识每个用户参与决策对决策的贡献至关重要。 |  |


#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或 EUII (最终用户可识别) 是否显示在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>是。
在团队中与应用交互时，团队 ID 会显示在我们的日志中。
对于三个全部在美国的创始人，我们只能有限地访问我们的生产日志。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>Cloverpop 应用使用 Ruby on Rails 构建，托管在 Heroku PaaS (平台上，作为一项服务) 它利用 AWS 进行云基础结构。 Heroku 和 AWS 都有可以访问的 SOC 报告。 我们的应用使用 PostgreSQL 进行其余数据存储加密，它是一个多租户环境。
 
我们的所有代码都有针对其编写的自动测试，其中涵盖了数据访问安全性。 每个内部版本都经过严格的代码检查过程的安全性和手动 QA 测试过程，还包括通过可用用户操作检查用户身份验证和数据访问。 我们的生产环境和所有其他环境（如开发和测试）之间是明确分开的。
 
只有选定人员有权访问生产环境和数据库：公司的创始人和少数经过审查的员工已经过背景检查，并且具有量化 (如客户支持) 。

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>是

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

下面将显示[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35992' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35992" target="_blank">在新建选项卡中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

