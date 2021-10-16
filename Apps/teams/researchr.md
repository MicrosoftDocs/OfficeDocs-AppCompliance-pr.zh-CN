---
title: 按 KBE 方法重新组织HR 的应用程序&#26666;&#24335;&#20250;&#31038;
ms.author: elmalova
author: elenamalova
ms.date: 08/20/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: 用于 researcHR 的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security 应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: bc174eb69b69cdf2d04c27bc4649f18111d87811
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 10/16/2021
ms.locfileid: "60412802"
---
# <a name="researchr"></a>researcHR

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2021 年 8 月 5 日</p>

* <a href="https://teams.microsoft.com/l/app/13a58c36-8f58-46e7-90dd-16084830876c" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002557" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

KBE 向 Microsoft&#26666;&#24335;&#20250;&#31038; 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | researcHR |
| ID | WA200002557 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | KBE&#26666;&#24335;&#20250;&#31038; |
| 合作伙伴网站的 URL | [https://app.researchr.work/corporate](https://app.researchr.work/corporate) |
| 应用程序Teams页的 URL | [https://app.researchr.work](https://app.researchr.work) |
| 隐私策略的 URL | [https://researchr.work/privacypolicy](https://researchr.work/privacypolicy) |
| 使用条款 URL | [https://app.researchr.work/tos](https://app.researchr.work/tos) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

此信息由 KBE&#26666;&#24335;&#20250;&#31038; ，它用于了解此应用程序如何收集和存储组织数据，以及组织将拥有对应用收集的数据的控制。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph](https://docs.microsoft.com/graph/permissions-reference)所需的任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Channel.Create | 应用程序 | 我们使用此范围允许机器人在客户端上创建新Teams通道。 请参阅： https://docs.microsoft.com/en-us/graph/api/channel-post | 我们不会在数据库中存储这些数据。 | [82df726e-0de2-46af-b4f1-0645fd95fc97](https://docs.microsoft.com/microsoft-365-app-certification/azure/82df726e-0de2-46af-b4f1-0645fd95fc97) |
>| Directory.Read.All | 应用程序 | 我们使用此范围获取通道的 ID 和名称，以在网站上显示这些数据。 请参阅： https://docs.microsoft.com/en-us/graph/api/channel-list | 我们不会在数据库中存储这些数据。 | [82df726e-0de2-46af-b4f1-0645fd95fc97](https://docs.microsoft.com/microsoft-365-app-certification/azure/82df726e-0de2-46af-b4f1-0645fd95fc97) |
>| Group.Read.All | 应用程序 | 我们使用此范围获取通道的 ID 和名称，以在网站上显示这些数据。 请参阅： https://docs.microsoft.com/en-us/graph/api/channel-list | 我们不会在数据库中存储这些数据。 | [82df726e-0de2-46af-b4f1-0645fd95fc97](https://docs.microsoft.com/microsoft-365-app-certification/azure/82df726e-0de2-46af-b4f1-0645fd95fc97) |
>| Team.ReadBasic.All | 应用程序 | 我们使用此范围获取团队成员，以便用户可以在我们的网站上看到他们的团队成员。 请参阅： https://docs.microsoft.com/en-us/graph/api/group-list-members | 我们不会在数据库外存储这些数据。 | [82df726e-0de2-46af-b4f1-0645fd95fc97](https://docs.microsoft.com/microsoft-365-app-certification/azure/82df726e-0de2-46af-b4f1-0645fd95fc97) |
>| User.Read.All | 应用程序 | 我们使用此范围获取用户加入的频道，以便用户可以在我们的网站上查看其加入的团队。 请参阅： https://docs.microsoft.com/en-us/graph/api/user-list-joinedteams | 我们不会在数据库中存储这些数据。 | [82df726e-0de2-46af-b4f1-0645fd95fc97](https://docs.microsoft.com/microsoft-365-app-certification/azure/82df726e-0de2-46af-b4f1-0645fd95fc97) |
>| User.ReadBasic.All | delegated | 我们使用此范围启用 OAuth 登录并收集用户AAD ID、访问令牌和刷新令牌。 请参阅： https://docs.microsoft.com/en-us/graph/auth-v2-user | 我们将用户的 AAD ID、访问令牌和刷新令牌存储在数据库中，以便用户可以使用 OAuth 登录我们网站。 | [82df726e-0de2-46af-b4f1-0645fd95fc97](https://docs.microsoft.com/microsoft-365-app-certification/azure/82df726e-0de2-46af-b4f1-0645fd95fc97) |
>| offline_access | delegated | 我们使用此范围获取刷新令牌，以便我们可以刷新已验证用户的访问令牌，而无需任何用户交互。 请参阅： https://docs.microsoft.com/en-us/azure/active-directory/develop/v2-permissions-and-consent#offline_access | 我们将刷新令牌存储在数据库中，以便我们可以刷新访问令牌，而无需任何用户交互。 | [82df726e-0de2-46af-b4f1-0645fd95fc97](https://docs.microsoft.com/microsoft-365-app-certification/azure/82df726e-0de2-46af-b4f1-0645fd95fc97) |


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

>数据库中的所有数据都经过加密。 数据库数据的备份将按照我们的内部操作策略执行和存储一段时间。 如果用户取消此服务，我们将在不延迟的情况下删除用户的用户信息，除非在必要范围内履行法律规定的存储义务。 以下是详细信息。 https://app.researchr.work/privacypolicy

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>标识信息

此信息由 KBE&#26666;&#24335;&#20250;&#31038; ，它提供有关此应用程序如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件的信息。

| **Information** | **响应** |
|:----------------|:-------------|
| 是否与 Microsoft 标识平台 (Azure AD) ？  | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

