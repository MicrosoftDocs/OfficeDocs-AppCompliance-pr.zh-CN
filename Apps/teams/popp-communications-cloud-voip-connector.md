---
title: 通过 POPP 通信的 POPP 云 VoIP 连接器的应用程序信息
ms.author: elmalova
author: elenamalova
ms.date: 10/01/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: 所有可用的针对 POPP 云 VoIP 连接器的安全和合规性信息、其数据处理策略、Microsoft Cloud App Security 应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 42930c1020e86aeb6f55fb81929f30285e17dae3
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 10/16/2021
ms.locfileid: "60414969"
---
# <a name="popp-cloud-voip-connector"></a>POPP 云 VoIP 连接器

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2021 年 9 月 20 日</p>

* <a href="https://teams.microsoft.com/l/app/b8e57f6b-31cf-468e-9e99-81f0395cb1f9" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003306" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

由与 Microsoft 通信的一些内容：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | POPP 云 VoIP 连接器 |
| ID | WA200003306 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | POPP Communications |
| 合作伙伴网站的 URL | [https://popp.com](https://popp.com) |
| 隐私策略的 URL | [https://popp.com/terms/privacy-policy/](https://popp.com/terms/privacy-policy/) |
| 使用条款 URL | [https://popp.com/pvnterms/](https://popp.com/pvnterms/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

此信息由一些通信提供，这些信息与此应用程序如何收集和存储组织数据以及组织将拥有对应用收集的数据的控制有关。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph](https://docs.microsoft.com/graph/permissions-reference)所需的任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| ChannelMember.Read.All | delegated | 用户 ID 和当前频道成员的显示名称。 应用使用它向用户显示要调用的频道成员列表。 | 元开关不存储此数据。 | [b8e57f6b-31cf-468e-9e99-81f0395cb1f9](https://docs.microsoft.com/microsoft-365-app-certification/azure/b8e57f6b-31cf-468e-9e99-81f0395cb1f9) |
>| Chat.Read | delegated |  收集或使用了哪些数据？ 添加收集数据或使用数据的理由。 用户 ID 和显示当前聊天成员的名称。 应用使用它向用户显示要调用的聊天成员列表。 | 元开关不存储此数据。 | [b8e57f6b-31cf-468e-9e99-81f0395cb1f9](https://docs.microsoft.com/microsoft-365-app-certification/azure/b8e57f6b-31cf-468e-9e99-81f0395cb1f9) |
>| TeamMember.Read.All | delegated | 用户 ID 和当前团队成员的显示名称。 应用使用它向用户显示要呼叫的团队成员列表。 | 元开关不存储此数据。 | [b8e57f6b-31cf-468e-9e99-81f0395cb1f9](https://docs.microsoft.com/microsoft-365-app-certification/azure/b8e57f6b-31cf-468e-9e99-81f0395cb1f9) |
>| User.Read.All | delegated |  收集或使用了哪些数据？ 添加收集数据或使用数据的理由。 用户的业务和移动电话号码。 这是必需的，以便可以发起拨打这些号码的电话呼叫。 |   元开关不存储此数据 | [b8e57f6b-31cf-468e-9e99-81f0395cb1f9](https://docs.microsoft.com/microsoft-365-app-certification/azure/b8e57f6b-31cf-468e-9e99-81f0395cb1f9) |
>| openid | delegated | 用户授权令牌，授权应用访问Graph列出的其他 API 终结点。 | 元开关不存储此数据。 | [b8e57f6b-31cf-468e-9e99-81f0395cb1f9](https://docs.microsoft.com/microsoft-365-app-certification/azure/b8e57f6b-31cf-468e-9e99-81f0395cb1f9) |

#### <a name="data-access-using-other-microsoft-apis"></a>使用其他 Microsoft API 进行数据访问

基于组织构建的应用和加载项Microsoft 365除 Microsoft Graph 外的其他 Microsoft API 来收集或处理 OII (组织) 。 列出除 Microsoft API Graph此应用使用的任何 Microsoft API。

>| **API** |  **是否收集 OII？** |  **收集哪些 OII？** | **收集 OII 的理由？** | **是否存储 OII？** | **存储 OII 的理由** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| Microsoft 标识平台 | 否 |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>非Microsoft 服务已使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>| **所有非Microsoft 服务 OII 将转移到** |  **转移了哪些 OII？** | **转移 OII 的理由？** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Metaswitch Networks and POPP Communications | 以下 OII 将转移到 MCT 托管自动程序服务器：Azure AD 租户 ID 团队 ID 团队 ID 频道/聊天 ID 消息内容也会传输，其中可能包含 OII 以下 OII 可能会传输到通信 JSON API：电话 个业务组中用户的数量 电子邮件地址的域 用户 IP 地址 | 添加转移 OII 的原因的理由 应用&#8217;主要用途是方便电话呼叫。 如果用户尝试进行电话呼叫，则必须提供此信息以登录到其通信帐户并将该呼叫关联回正确的用户。  传输到 MCT 托管自动程序服务器的 OII 内置于自动程序框架 API 中，用于与 Teams 集成且无法避免。 |

#### <a name="data-access-via-bots"></a>通过机器人访问数据

如果此应用程序包含机器人或消息扩展，则它可以访问最终用户可识别信息 (EUII) ：名单 (名字、姓氏、显示名称、电子邮件地址) （团队中任何团队成员的姓名、姓氏、电子邮件地址) 或添加到其中聊天）。 此应用是否使用了此功能？

>| **访问 EUII 的理由？**  | **EUII 是否存储在数据库 () ？** | **存储 EUII 的理由** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| 应用程序&#8217;的主要目的是促进电话呼叫。 如果用户尝试进行电话呼叫，则必须为呼叫中各方提供 EUII，以在正确的电话用户之间建立呼叫。 | 否 |  |


#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或 EUII (最终用户可识别) 是否显示在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>应用程序遥测或日志中不显示 OII 或 EUII。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>元开关和 POPP 存储数据的时间不会超过从通信 Web 加载 MCT 网页的即时需要。 数据不会保留，将立即删除。

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>标识信息

此信息由一些（有关此应用程序如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件）的一些通信提供。

| **Information** | **响应** |
|:----------------|:-------------|
| 是否与 Microsoft 标识平台 (Azure AD) ？  | 是 |
| 您是否已审阅并遵循了 Microsoft 标识平台 集成清单中列出的所有适用最佳做法？  | 否 |
| 你的应用是否使用 MSAL (Microsoft 身份验证库) 进行身份验证？ | 是 |
| 你的应用是否支持条件访问策略？ | 是 |
| 列出支持的策略类型 | 条件访问策略，只要这种支持由用于身份验证的 MSAL 库自动提供。  |
| 应用是否请求方案最小特权权限？ | 是 |
| 应用的静态注册权限是否准确反映应用将动态和增量请求的权限？ | 是 |
| 你的应用是否支持多租户？ | 否 |
| 你的应用是否具有机密客户端？ | 否 |
| 你是否拥有为应用注册的所有 (统一) URI？ | 是 |
| 对于你的应用，应避免使用什么？ | - 通配符重定向 URI，<br/><br/> |
| 你的应用是否公开任何 Web API？ | 否 |
| 你的应用是否使用预览 API？ | 否 |
| 你的应用是否使用已弃用 API？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

