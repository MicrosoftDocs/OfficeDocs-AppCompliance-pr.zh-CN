---
title: 休假跟踪程序休假跟踪程序的应用程序信息
ms.author: elmalova
author: elenamalova
ms.date: 09/21/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: 有关休假跟踪程序的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 8756d04cf394bdf7b6126f32764696466b34d729
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 10/18/2021
ms.locfileid: "60440585"
---
# <a name="vacation-tracker"></a>Vacation Tracker

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2021 年 9 月 15 日</p>

* <a href="https://teams.microsoft.com/l/app/eab5463e-8168-40ee-887a-7ac78de1d266" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002167" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

由休假跟踪程序提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | Vacation Tracker |
| ID | WA200002167 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | Vacation Tracker |
| 合作伙伴网站的 URL | [https://vacationtracker.io](https://vacationtracker.io) |
| 应用程序Teams页的 URL | [https://vacationtracker.io/vacation-calendar-tracker-featur...](https://vacationtracker.io/vacation-calendar-tracker-features/) |
| 隐私策略的 URL | [https://vacationtracker.io/privacy-policy/](https://vacationtracker.io/privacy-policy/) |
| 使用条款 URL | [https://vacationtracker.io/terms-of-service/](https://vacationtracker.io/terms-of-service/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

休假跟踪程序提供了此信息，这些信息与此应用程序如何收集和存储组织数据以及组织将拥有对应用收集的数据的控制有关。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph](https://docs.microsoft.com/graph/permissions-reference)所需的任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Group.Read.All | delegated | 在用户设置其每周或每日通知时，我们会读取公共频道的 ID 和名称。 | 用户可以选择希望从休假跟踪程序接收每日或每周通知的频道。 当用户选择其首选频道时，我们将存储通道 ID。 | [eab5463e-8168-40ee-887a-7ac78de1d266](https://docs.microsoft.com/microsoft-365-app-certification/azure/eab5463e-8168-40ee-887a-7ac78de1d266) |
>| Team.ReadBasic.All | delegated | 我们列出Microsoft Teams注册期间加入的团队用户，以允许用户选择要注册休假跟踪程序的团队。 他们也可以注册整个组织。 | 只有当用户Microsoft Teams作为单个团队注册休假跟踪程序，而不是作为整个组织注册为一 (，我们才存储所选团队的) 。 我们使用团队 ID 将已登录的用户与休假跟踪程序中的现有帐户连接。 | [eab5463e-8168-40ee-887a-7ac78de1d266](https://docs.microsoft.com/microsoft-365-app-certification/azure/eab5463e-8168-40ee-887a-7ac78de1d266) |
>| User.Read | delegated | 我们将收集基本用户的信息，包括其名称、ID 和租户 ID。 我们使用此数据在休假跟踪器中将登录的用户连接到其组织。 | 我们存储用户的名称、ID 和租户 ID。 我们使用此数据在休假跟踪器中将登录的用户连接到其组织。 | [eab5463e-8168-40ee-887a-7ac78de1d266](https://docs.microsoft.com/microsoft-365-app-certification/azure/eab5463e-8168-40ee-887a-7ac78de1d266) |
>| User.Read.All | delegated | 我们的用户可以从他们的组织或Microsoft 365导入Microsoft Teams用户。 我们使用此权限仅为所选团队或组织导入Microsoft Teams用户。 | 我们存储有关已导入用户的基本信息，包括他们的姓名、电子邮件地址和用户 ID。 | [eab5463e-8168-40ee-887a-7ac78de1d266](https://docs.microsoft.com/microsoft-365-app-certification/azure/eab5463e-8168-40ee-887a-7ac78de1d266) |
>| User.ReadBasic.All | delegated | 我们允许用户从他们的组织或他们的团队导入Microsoft Teams用户。 我们使用此权限在导入弹出窗口中列出可用用户及其电子邮件地址。 | 当用户选择要导入休假跟踪程序的同事时，我们将存储有关这些导入用户的基本信息，包括他们的姓名、电子邮件地址和用户 ID。 | [eab5463e-8168-40ee-887a-7ac78de1d266](https://docs.microsoft.com/microsoft-365-app-certification/azure/eab5463e-8168-40ee-887a-7ac78de1d266) |
>| email | delegated | 当用户使用 Microsoft AAD时，我们会将用户的电子邮件地址存储为唯一标识符。 | 我们将用户的电子邮件存储为唯一标识符。 我们不会使用此电子邮件进行通信，用户输入在注册期间用于通信的业务电子邮件地址。 | [eab5463e-8168-40ee-887a-7ac78de1d266](https://docs.microsoft.com/microsoft-365-app-certification/azure/eab5463e-8168-40ee-887a-7ac78de1d266) |
>| offline_access | delegated | 我们不会收集具有此权限的任何数据。 它用于维护访问我们有权访问的数据的权限。 | 我们不会存储具有此权限的任何数据。 | [eab5463e-8168-40ee-887a-7ac78de1d266](https://docs.microsoft.com/microsoft-365-app-certification/azure/eab5463e-8168-40ee-887a-7ac78de1d266) |
>| openid | delegated | 我们使用此权限登录或注册用户休假跟踪程序。 我们不会收集具有此权限的任何特定数据。 | 我们使用此权限登录或注册用户休假跟踪程序。 我们不会存储具有此权限的任何特定数据。 | [eab5463e-8168-40ee-887a-7ac78de1d266](https://docs.microsoft.com/microsoft-365-app-certification/azure/eab5463e-8168-40ee-887a-7ac78de1d266) |
>| 个人资料 | delegated | 我们将收集基本用户的信息，包括其名称、ID 和租户 ID。 我们使用此数据在休假跟踪器中将登录的用户连接到其组织。 | 我们存储用户的名称、ID 和租户 ID。 我们使用此数据在休假跟踪器中将登录的用户连接到其组织。 | [eab5463e-8168-40ee-887a-7ac78de1d266](https://docs.microsoft.com/microsoft-365-app-certification/azure/eab5463e-8168-40ee-887a-7ac78de1d266) |


#### <a name="non-microsoft-services-used"></a>非Microsoft 服务已使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>| **所有非Microsoft 服务 OII 将转移到** |  **转移了哪些 OII？** | **转移 OII 的理由？** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Stripe, AWS, Crisp, Customer.io, Segment, Amplitude, Google Tag Manager | 用户输入 (输入的公司名称)  | 当用户注册时，他们输入其公司名称，我们将此名称用作产品内的组织名称 |

#### <a name="data-access-via-bots"></a>通过机器人访问数据

如果此应用程序包含机器人或消息扩展，则它可以访问最终用户可识别信息 (EUII) ：名单 (名字、姓氏、显示名称、电子邮件地址) （团队中任何团队成员的姓名、姓氏、电子邮件地址) 或添加到其中聊天）。 此应用是否使用了此功能？

>| **访问 EUII 的理由？**  | **EUII 是否存储在数据库 (中) ？** | **存储 EUII 的理由** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| 机器人可以看到有关与机器人通信的用户的基本信息。 但是，我们不会存储或使用该信息。 我们仅使用用户的 ID、对话 ID 和发送给自动程序的消息。 | 我们存储用户的电子邮件地址、 (Microsoft AAD) 中定义的用户名和 Microsoft (中AAD)  | 我们将电子邮件地址用作用户的唯一标识符以及用户名和个人资料照片，以允许同一公司的管理员和审批者在我们的仪表板中识别其员工。  |


#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或最终用户可识别信息 (EUII) 是否出现在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>公司名称，根据我们针对此类数据的标准一年保留策略进行保留和删除

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>首先，我们将收集用户所需的最少数据量。 然后，我们与合作伙伴共享最低可能的数据保留策略，以便所有数据在一年内删除（如果适用）。

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>是

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

下面将显示[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36417' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36417" target="_blank">在新建选项卡中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>标识信息

休假跟踪程序已提供有关此应用如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件的信息。

| **Information** | **响应** |
|:----------------|:-------------|
| 是否与 Microsoft 标识平台 (Azure AD) ？  | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
