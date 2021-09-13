---
title: 用于排列器的应用程序信息（由排列器， Inc.
ms.author: elmalova
author: elenamalova
ms.date: 06/15/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: 用于排列器的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 3ccc0e501a899fcb5dc613c254de9aa62911d023
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 09/12/2021
ms.locfileid: "59276792"
---
# <a name="arrangr"></a>Arrangr

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2021 年 6 月 15 日</p>

* <a href="https://teams.microsoft.com/l/app/57de46f8-193a-400c-9a34-c862333aed55" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002975" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

由排列器， Inc. 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | Arrangr |
| ID | WA200002975 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | Arrangr, Inc. |
| 合作伙伴网站的 URL | [https://arrangr.com](https://arrangr.com) |
| 应用程序Teams页的 URL | [https://arrangr.com/welcome](https://arrangr.com/welcome) |
| 隐私策略的 URL | [https://arrangr.com/privacy_policy](https://arrangr.com/privacy_policy) |
| 使用条款 URL | [https://arrangr.com/terms_of_use](https://arrangr.com/terms_of_use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

此信息由排列器， Inc. 提供，关于此应用程序如何收集和存储组织数据以及你的组织将拥有对应用收集的数据的控制。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph所需的](https://docs.microsoft.com/graph/permissions-reference)任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD 应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | delegated | 我们收集用户日历的名称及其日历事件的详细信息，以便于安排会议。 | 我们存储已连接的任何日历的名称，以便他们可以看到和更改已连接的日历 | [57de46f8-193a-400c-9a34-c862333aed55](https://docs.microsoft.com/microsoft-365-app-certification/azure/57de46f8-193a-400c-9a34-c862333aed55) |
>| Channel.ReadBasic.All | delegated | 收集可供用户使用的频道列表，以便我们可以向用户显示频道列表，以便他们选取一个频道来共享一个排列器邀请。 | 我们不将信息存储在用户频道上 | [57de46f8-193a-400c-9a34-c862333aed55](https://docs.microsoft.com/microsoft-365-app-certification/azure/57de46f8-193a-400c-9a34-c862333aed55) |
>| ChannelMessage.Send | delegated | 此权限用于代表用户将排列器邀请发送到团队频道。 不用于收集数据。 | 不存储通过此权限收集的数据。 | [57de46f8-193a-400c-9a34-c862333aed55](https://docs.microsoft.com/microsoft-365-app-certification/azure/57de46f8-193a-400c-9a34-c862333aed55) |
>| Chat.ReadWrite | delegated | 此权限用于将排列器邀请Teams用户进行聊天。 此权限不用于收集数据。 | 不存储通过此权限收集的数据。 | [57de46f8-193a-400c-9a34-c862333aed55](https://docs.microsoft.com/microsoft-365-app-certification/azure/57de46f8-193a-400c-9a34-c862333aed55) |
>| ChatMessage.Send | delegated | 此权限用于将排列器邀请发送到一对一，并代表用户发送群聊。 不用于收集数据。 | 不存储通过此权限收集的数据。 | [57de46f8-193a-400c-9a34-c862333aed55](https://docs.microsoft.com/microsoft-365-app-certification/azure/57de46f8-193a-400c-9a34-c862333aed55) |
>| OnlineMeetings.ReadWrite | delegated | 在生成Microsoft Teams时，排列器会收集会议链接。 我们Teams用户生成会议，以便他们可以在 Arranger 上Teams呼叫。 | 我们存储会议链接，以便可以与相应的各方共享这些链接以加入会议。 | [57de46f8-193a-400c-9a34-c862333aed55](https://docs.microsoft.com/microsoft-365-app-certification/azure/57de46f8-193a-400c-9a34-c862333aed55) |
>| People.Read | delegated | 我们收集与用户相关的人员的姓名和电子邮件。 这样，我们就可以让用户轻松选择他们作为排列器邀请的收件人。 | 如果用户最终选择了通过此 API 提供的收件人，我们将保存该收件人的姓名和电子邮件，以便召开会议，并方便用户以后再次选择他们作为收件人。 | [57de46f8-193a-400c-9a34-c862333aed55](https://docs.microsoft.com/microsoft-365-app-certification/azure/57de46f8-193a-400c-9a34-c862333aed55) |
>| Team.ReadBasic.All | delegated | 我们收集用户邀请Teams，以便他们可以选择要连接到排列器的用户Teams以及想要共享排列器邀请的团队。 | 排列器存储用户选择Teams排列器"的名称，以便我们可以在设置中显示这些 Teams，并让他们在决定在何处共享"排列器"邀请时从 Teams 中选择。 | [57de46f8-193a-400c-9a34-c862333aed55](https://docs.microsoft.com/microsoft-365-app-certification/azure/57de46f8-193a-400c-9a34-c862333aed55) |
>| TeamsAppInstallation.ReadWriteSelfForUser | delegated | 我们阅读我们的应用是否已安装在用户的 Teams 帐户中，以便可以询问他们是否想要安装应用，以便可以安装应用。 | 我们不会存储通过此权限收集的数据。 | [57de46f8-193a-400c-9a34-c862333aed55](https://docs.microsoft.com/microsoft-365-app-certification/azure/57de46f8-193a-400c-9a34-c862333aed55) |
>| 个人资料 | delegated | 名称和电子邮件地址 | 名称和电子邮件地址，以便向用户显示他们连接到服务的帐户。 | [57de46f8-193a-400c-9a34-c862333aed55](https://docs.microsoft.com/microsoft-365-app-certification/azure/57de46f8-193a-400c-9a34-c862333aed55) |

#### <a name="data-access-using-other-microsoft-apis"></a>使用其他 Microsoft API 进行数据访问

基于组织构建的应用和Microsoft 365可以使用除 Microsoft Graph 外的其他 Microsoft API 来收集或处理 OII (组织) 。 列出此应用使用的任何 Microsoft GRAPH Microsoft API。

>| **API** |  **是否收集 OII？** |  **收集哪些 OII？** | **收集 OII 的理由？** | **是否存储 OII？** | **存储 OII 的理由** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| Outlook | 是 | 名称、电子邮件、日历名称、日历事件信息 | 我们收集此信息以允许用户将其日历连接到排列器以方便安排会议 | 名称、电子邮件、日历名称 | 我们存储此信息，以便向用户显示他们连接到服务的帐户和日历 |

#### <a name="non-microsoft-services-used"></a>非Microsoft 服务使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>| **所有非Microsoft 服务 OII 将转移到** |  **转移了哪些 OII？** | **转移 OII 的理由？** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Google 云、SendGrid、Stripe、Quaderno | Google 云存储所有用户数据、用户名和电子邮件与 SendGrid 共享，以便向用户发送电子邮件、带区接收的用户名、电子邮件和付款信息以用于处理付款。 Quaderno 接收用户名、电子邮件和地理信息，以便帮助遵守销售税。 | 需要 Google 云来存储数据以记住用户，并提供他们选择在排列器中存储的信息。 若要将电子邮件发送到我们的用途，我们必须将其电子邮件地址提供给 SendGrid。 若要收集付款，我们必须在 Stripe 中处理他们的付款信息，但我们不会将付款信息存储在自己的服务器上。 需要 Quaderno 来计算销售税并确保我们遵守销售税法规。 |

#### <a name="data-access-via-bots"></a>通过机器人访问数据

如果此应用包含机器人或消息扩展，它可以访问最终用户可识别信息 (EUII) ：名单 (名字、姓氏、显示名称、电子邮件地址) （团队中任何团队成员的姓名、姓氏、电子邮件地址) 或添加到其中聊天）。 此应用是否使用了此功能？

>| **访问 EUII 的理由？**  | **EUII 是否存储在数据库 (中) ？** | **存储 EUII 的理由** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| 用户将使用我们的消息传递扩展来安排与其他人的会议。 我们需要向用户显示他们登录的帐户，并且我们需要能够将其发送的邀请与正确的排列器用户关联。 | 用户名、电子邮件和通信信息。 | 需要此信息来协调各方之间的会议，并与他们共享连接详细信息以及他们与谁会面。 |


#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或最终用户可识别信息 (EUII) 是否出现在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>应用程序遥测或日志中不显示 OII 或 EUII。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>我们通过 API 控制存储在 Google 云数据存储中的数据，并可以删除所需的任何数据。 我们的用户能够请求删除其帐户和删除其数据。

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

此信息由排列器， Inc. 提供有关此应用程序如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件的信息。

| **Information** | **响应** |
|:----------------|:-------------|
| 你是否与 Microsoft 标识平台 (Azure AD) ？  | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
