---
title: 按 KBE&#26666;&#24335;&#20250;&#31038;的 researcHR 的应用程序信息
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 08/05/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: 用于 researcHR 的所有可用安全性和符合性信息、其数据处理策略、其Microsoft Cloud App Security应用目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 66460d332f54b1868fbcd2895b6de088bb362d97
ms.sourcegitcommit: 7a7de9f48f6cf5b6acd435412477b6a59127f19a
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 05/05/2022
ms.locfileid: "65229006"
---
# <a name="researchr"></a>researcHR

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2021 年 8 月 5 日</p>

* <a href="https://teams.microsoft.com/l/app/13a58c36-8f58-46e7-90dd-16084830876c" target="_blank">Teams存储区中的视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002557" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

KBE&#26666;&#24335;&#20250;&#31038; 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | researcHR |
| ID | WA200002557 |
| 支持Office 365客户端 | Microsoft Teams |
| 合作伙伴公司名称 | KBE&#26666;&#24335;&#20250;&#31038; |
| 合作伙伴网站的 URL | [https://app.researchr.work/corporate](https://app.researchr.work/corporate) |
| Teams应用程序信息页的 URL | [https://app.researchr.work](https://app.researchr.work) |
| 隐私策略的 URL | [https://researchr.work/privacypolicy](https://researchr.work/privacypolicy) |
| 使用条款的 URL | [https://app.researchr.work/tos](https://app.researchr.work/tos) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

KBE&#26666;&#24335;&#20250;&#31038; 提供了此信息，了解此应用如何收集和存储组织数据以及组织对应用收集的数据的控制。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph进行数据访问

列出此应用所需的任何 [Microsoft Graph权](/graph/permissions-reference)限。

>| **权限**  | **(委派/应用程序) 的权限类型** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Channel.Create | 应用程序 | 我们使用此范围允许机器人在Teams客户端上创建新通道。 请参阅：/graph/api/channel-post | 我们不会将这些数据存储在数据库中。 | [82df726e-0de2-46af-b4f1-0645fd95fc97](../azure/82df726e-0de2-46af-b4f1-0645fd95fc97.md) |
>| Directory.Read.All | 应用程序 | 我们使用此范围获取频道 ID 和名称，以便在我们的网站上显示这些数据。 请参阅：/graph/api/channel-list | 我们不会将这些数据存储在数据库中。 | [82df726e-0de2-46af-b4f1-0645fd95fc97](../azure/82df726e-0de2-46af-b4f1-0645fd95fc97.md) |
>| Group.Read.All | 应用程序 | 我们使用此范围获取频道 ID 和名称，以便在我们的网站上显示这些数据。 请参阅：/graph/api/channel-list | 我们不会将这些数据存储在数据库中。 | [82df726e-0de2-46af-b4f1-0645fd95fc97](../azure/82df726e-0de2-46af-b4f1-0645fd95fc97.md) |
>| Team.ReadBasic.All | 应用程序 | 我们使用此范围获取团队成员，以便用户可以在我们的网站上查看其团队成员。 请参阅：/graph/api/group-list-members | 我们不会将这些数据存储在 Out 数据库上。 | [82df726e-0de2-46af-b4f1-0645fd95fc97](../azure/82df726e-0de2-46af-b4f1-0645fd95fc97.md) |
>| User.Read.All | 应用程序 | 我们使用此范围获取用户加入的频道，以便用户可以在我们的网站上看到其加入的团队。 请参阅：/graph/api/user-list-joinedteams | 我们不会将这些数据存储在数据库中。 | [82df726e-0de2-46af-b4f1-0645fd95fc97](../azure/82df726e-0de2-46af-b4f1-0645fd95fc97.md) |
>| User.ReadBasic.All | 委托 | 我们使用此范围启用 OAuth 登录并收集用户的AAD ID、访问令牌和刷新令牌。 请参阅：/graph/auth-v2-user | 我们将用户的AAD ID、访问令牌和刷新令牌存储在我们的数据库中，以便用户可以使用 OAuth 登录到我们的网站。 | [82df726e-0de2-46af-b4f1-0645fd95fc97]../azure/82df726e-0de2-46af-b4f1-0645fd95fc97.md)  |
>| offline_access | 委托 | 我们使用此范围获取刷新令牌，以便我们可以在没有任何用户交互的情况下刷新经过身份验证的用户的访问令牌。 请参阅：/azure/active-directory/develop/v2-permissions-and-consent#offline_access | 我们将刷新令牌存储在数据库中，以便无需任何用户交互即可刷新访问令牌。 | [82df726e-0de2-46af-b4f1-0645fd95fc97](../azure/82df726e-0de2-46af-b4f1-0645fd95fc97.md) |


#### <a name="non-microsoft-services-used"></a>未使用Microsoft 服务

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输的数据，并包含应用需要传输此信息的原因。

>不使用非Microsoft 服务。

#### <a name="data-access-via-bots"></a>通过机器人进行数据访问

如果此应用包含机器人或消息传递扩展，则它可以访问最终用户身份信息 (EUII) ：名册 (名字、姓氏、显示名称、团队中任何团队成员的电子邮件地址) 或添加到的聊天。 此应用是否利用此功能？

>未访问 EUII。


#### <a name="telemetry-data"></a>遥测数据

此应用程序的遥测或日志中是否 (OII) 或最终用户身份信息 (EUII) 显示任何组织可识别信息？ 如果是，请描述存储的数据以及什么是保留和删除策略？

>应用程序遥测或日志中未显示 OII 或 EUII。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

介绍组织管理员如何控制合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>数据库中的所有数据都已加密。 数据库数据的备份将根据我们的内部操作策略在一定的时间段内进行和存储。 如果用户取消此服务，我们将立即删除用户的用户信息，但履行法律规定的存储义务所必需的程度除外。 下面是详细信息。 https://app.researchr.work/privacypolicy

#### <a name="human-review-of-organizational-information"></a>组织信息的人工评审

人类是否参与查看或分析组织识别信息 (OII) 此应用收集或存储的数据？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

下面显示了[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/" target="_blank">在新选项卡中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>标识信息

KBE&#26666;&#24335;&#20250;&#31038; 提供了此信息，了解此应用如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件。

| **Information** | **响应** |
|:----------------|:-------------|
| 是否与 Microsoft 标识平台 (Azure AD) 集成？  | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
