---
title: LawToolBox.com Inc. 的 LawToolBox 的应用程序信息
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
description: LawToolBox 的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: f738fb665687934f677d0bc3a5105e41831106ac
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/30/2021
ms.locfileid: "52092825"
---
# <a name="lawtoolbox"></a>LawToolBox

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2019 年 12 月 16 日</p>

* <a href="https://teams.microsoft.com/l/app/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381656" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

LawToolBox.com Inc. 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | LawToolBox |
| ID | WA104381656 |
| 功能 | 机器人，选项卡，消息传递扩展 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | LawToolBox.com Inc. |
| 合作伙伴网站的 URL | [https://www.lawtoolbox.com](https://www.lawtoolbox.com) |
| "Teams应用程序信息"页的 URL | [https://www.lawtoolbox.com/Ads/Adchk.cfm?eaid=718](https://www.lawtoolbox.com/Ads/Adchk.cfm?eaid=718) |
| 隐私策略的 URL | [https://www.lawtoolbox.com/privacy-policy/](https://www.lawtoolbox.com/privacy-policy/) |
| 使用条款 URL | [https://www.lawtoolbox.com/Ads/Adchk.cfm?eaid=661](https://www.lawtoolbox.com/Ads/Adchk.cfm?eaid=661) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

此信息由 LawToolBox.com Inc. 提供，用于了解此应用程序如何收集和存储组织数据，以及您的组织将拥有对应用收集的数据的控制。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph所需的](https://docs.microsoft.com/graph/permissions-reference)任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD 应用 ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.Read | delegated |  | [可选]读取用户的日历。 | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Calendars.ReadWrite | delegated |  | 在用户的日历中创建日历邀请。 | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Calendars.ReadWrite.Shared | delegated |  | 创建共享日历的日历邀请。 | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Contacts.ReadWrite | delegated |  | [Optional]- 读取用户联系人，将用户从联系人列表连接到组。 | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Contacts.ReadWrite.Shared | delegated |  | [Optional]- 读取用户共享联系人，以提供与案例相关的联系人列表。 | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Directory.AccessAsUser.All | delegated |  | [可选]作为用户读取组和用户信息。 | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Directory.ReadWrite.All | delegated |  | [可选]作为用户读取组和用户信息。 | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Files.Read | delegated |  | [可选]读取用户OneDrive。 | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Files.Read.All | delegated |  | [Optional]-Read user's OneDrive。 | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Files.ReadWrite | delegated |  | [Optional]-Read and modify files in a user's OneDrive. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Files.ReadWrite.All | delegated |  | [可选]读/写用户OneDrive事件关联的文件。 | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Group.ReadWrite.All | delegated | GroupID、GroupName、GroupEmail | 我们为系统中创建的每个事项创建一个组。 这可帮助用户将与重要信息存储到组，而组又将其数据保存到其自己的租户中。 | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Mail.Read | delegated |  | [可选][InProgress]阅读用户的电子邮件了解事项。 | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Mail.ReadWrite | delegated |  | [可选][InProgress]读取/写入用户的电子邮件。 | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Mail.ReadWrite.Shared | delegated |  | [可选][InProgress]读取/写入用户的电子邮件。 | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Mail.Send | delegated |  | [可选][InProgress]以用户用户发送电子邮件截止时间。 | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Tasks.ReadWrite.Shared | delegated |  | [Optional]-[InProgress] Read Write Deadlines as Task for users. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| User.Read | delegated |  | 读取用户的信息。 | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| User.ReadWrite | delegated |  | 读取/写入用户的信息。 | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| User.ReadWrite.All | delegated |  | 读取/写入用户的信息。 | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| email | delegated | Email、Office365 UserID、ObjectID、TenantID。 | 读取用户的电子邮件地址。 | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| 个人资料 | delegated |  | 读取用户配置文件信息。 | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |


#### <a name="non-microsoft-services-used"></a>非Microsoft 服务使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>不Microsoft 服务非活动。

#### <a name="data-access-via-bots"></a>通过机器人访问数据

如果此应用程序包含机器人或消息扩展，则它可以访问最终用户可识别信息 (EUII) ：名单 (名字、姓氏、显示名称、电子邮件地址) （团队中任何团队成员的姓名、姓氏、电子邮件地址) 或添加到其中聊天）。 此应用是否使用了此功能？

>| **访问 EUII 的理由？**  | **EUII 是否存储在数据库 (中) ？** | **存储 EUII 的理由** |
>|:--------------------------------|:---------------------|:--------------------------|
>| 确定团队中新添加的用户并检查潜在潜在客户 | Email、UserId |  |



#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或 EUII (最终用户可识别) 是否显示在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>调试日志中的用户电子邮件、用户 ID、AccessToken、组信息

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>我们保留案例记录，除非收到删除数据的请求。


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

下面将显示[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35680' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35680" target="_blank">在新建选项卡中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

