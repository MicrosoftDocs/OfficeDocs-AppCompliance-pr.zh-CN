---
title: 工作台智能的应用程序信息（按临时）
ms.author: elmalova
author: elenamalova
ms.date: 09/24/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Workbench 智能的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 4aaa94f3a1319a2eb06e332e1f23d4c5a1f07439
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 10/18/2021
ms.locfileid: "60429019"
---
# <a name="workbench-intelligence"></a>Workbench Intelligence

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2021 年 9 月 22 日</p>

* <a href="https://teams.microsoft.com/l/app/d5630318-189a-4912-abae-99b1f8f82cce" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002705" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

由 Temporall 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | Workbench Intelligence |
| ID | WA200002705 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | Temporall |
| 合作伙伴网站的 URL | [https://www.temporall.com](https://www.temporall.com) |
| Teams信息页的 URL | [https://www.temporall.com/teams_intelligence/](https://www.temporall.com/teams_intelligence/) |
| 隐私策略的 URL | [https://temporall.com/privacy-policy/](https://temporall.com/privacy-policy/) |
| 使用条款 URL | [https://www.temporall.com/eula](https://www.temporall.com/eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

这些信息由临时组织提供，有关此应用如何收集和存储组织数据以及你的组织将拥有对应用收集的数据的控制。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph所需的](https://docs.microsoft.com/graph/permissions-reference)任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| AppCatalog.Read.All | delegated | 获取已安装的 Teams 应用的列表，以能够获取已知外部 ID 的本地应用 ID。 | 本地应用 ID。在不同租户上安装应用时，必须能够识别该应用。 | [d5630318-189a-4912-abae-99b1f8f82cce](https://docs.microsoft.com/microsoft-365-app-certification/azure/d5630318-189a-4912-abae-99b1f8f82cce) |
>| Channel.ReadBasic.All | 应用程序 | 频道 ID &amp; 名称。 理由：允许加入/离开频道以同步邮件活动。  | 从获取通道返回的原始数据对象。 理由：临时工作台允许用户根据频道筛选和分类数据。 保存此原始数据以引用原始对象 | [d5630318-189a-4912-abae-99b1f8f82cce](https://docs.microsoft.com/microsoft-365-app-certification/azure/d5630318-189a-4912-abae-99b1f8f82cce) |
>| ChannelMessage.Read.All | 应用程序 | 邮件活动 &amp; 类型以及发件人 &amp; 目标。 从这些路由接收的数据：/teams/${teamId}/channels/${channelId}/messages /teams/${teamId}/channels/${channelId}/messages/${messageId}。 理由：能够计算邮件 &amp; 活动的指标报告。 这构成了我们的网络分析模块的核心，能够绘制用户团队之间的活动 &amp; 图表。 | 我们检测新邮件/回复/反应/提及的数量，这些指标与返回 &amp; 的原始邮件对象一起存储。 数据是必需的，因为它构成了我们的核心功能的一部分。 对邮件数据运行分析需要将分析保存到数据库以实现最佳性能 - 这还减少了对相同数据后续调用的要求 | [d5630318-189a-4912-abae-99b1f8f82cce](https://docs.microsoft.com/microsoft-365-app-certification/azure/d5630318-189a-4912-abae-99b1f8f82cce) |
>| Directory.Read.All | 应用程序 | ClientId、用户列表、组织列表和子频道。 理由：需要将 &amp; 同步用户读取到临时工作台 | 用户名、电子邮件、图标、对话参考。 Justification：&#160;临时工作台允许用户根据通道筛选和分类数据。 组织数据存储在安装后重新连接到团队 | [d5630318-189a-4912-abae-99b1f8f82cce](https://docs.microsoft.com/microsoft-365-app-certification/azure/d5630318-189a-4912-abae-99b1f8f82cce) |
>| Group.ReadWrite.All | 应用程序 | 组 ID &amp; 名称。 理由：将应用安装到每个组/频道 | 组 ID &amp; 名称以及用于引用的原始数据对象。 理由：临时工作台允许用户根据组/团队筛选和分类数据。 保存此原始数据以引用原始对象 | [d5630318-189a-4912-abae-99b1f8f82cce](https://docs.microsoft.com/microsoft-365-app-certification/azure/d5630318-189a-4912-abae-99b1f8f82cce) |
>| TeamMember.Read.All | 应用程序 | 团队的用户成员身份。 理由：允许将用户中的所有用户Teams到临时工作台 | 电子邮件地址、姓名和姓氏。 理由：允许将团队中的用户与临时工作台中的用户进行匹配，以便通过电子邮件同步用户。 | [d5630318-189a-4912-abae-99b1f8f82cce](https://docs.microsoft.com/microsoft-365-app-certification/azure/d5630318-189a-4912-abae-99b1f8f82cce) |
>| TeamsAppInstallation.ReadWriteForTeam.All | 应用程序 | 读取为团队安装的应用列表。 理由：检查我们的应用是否已安装，否则将安装它，以能够通过图形 api 获取消息活动 | 不适用 | [d5630318-189a-4912-abae-99b1f8f82cce](https://docs.microsoft.com/microsoft-365-app-certification/azure/d5630318-189a-4912-abae-99b1f8f82cce) |
>| TeamsAppInstallation.ReadWriteForUser.All | 应用程序 | 读取已安装的应用列表。 检查我们的应用是否已安装，否则将安装它以通过调查表与用户交互 | 不适用 | [d5630318-189a-4912-abae-99b1f8f82cce](https://docs.microsoft.com/microsoft-365-app-certification/azure/d5630318-189a-4912-abae-99b1f8f82cce) |
>| User.Read | delegated | 基本用户 &amp; 公司信息。 理由：用于按用户对邮件活动进行分类，允许机器人参与主动邮件。 | 用户名、电子邮件、图标、对话参考。 理由：允许机器人主动向用户发送包含相关信息的消息。 用于显示数据的组用户 | [d5630318-189a-4912-abae-99b1f8f82cce](https://docs.microsoft.com/microsoft-365-app-certification/azure/d5630318-189a-4912-abae-99b1f8f82cce) |


#### <a name="non-microsoft-services-used"></a>非Microsoft 服务已使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>| **所有非Microsoft 服务 OII 将转移到** |  **转移了哪些 OII？** | **转移 OII 的理由？** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Google 云 | LDAP 信息 | 我们的平台驻留在 Google 云平台上 |

#### <a name="data-access-via-bots"></a>通过机器人访问数据

如果此应用包含机器人或消息扩展，则它可以访问最终用户可识别信息 (EUII) ：名单 (名字、姓氏、显示名称、电子邮件地址) （团队中任何团队成员的姓名、姓氏、电子邮件地址) 或添加到其中聊天）。 此应用是否使用了此功能？

>无法访问 EUII。


#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或 EUII (最终用户可识别) 是否显示在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>应用程序遥测或日志中不显示 OII 或 EUII。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>https://temporall.com/privacy-policy/

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>是

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>标识信息

这些信息由临时服务器提供，用于说明此应用如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件。

| **Information** | **响应** |
|:----------------|:-------------|
| 是否与 Microsoft 标识平台 (Azure AD) ？  | 是 |
| 您是否已审阅并遵循了 Microsoft 标识平台 集成清单中列出的所有适用最佳做法？  | 是 |
| 你的应用是否使用 MSAL (Microsoft 身份验证库) 进行身份验证？ | 是 |
| 你的应用是否支持条件访问策略？ | 否 |
| 应用是否请求方案最小特权权限？ | 是 |
| 应用的静态注册权限是否准确反映应用将动态和增量请求的权限？ | 是 |
| 你的应用是否支持多租户？ | 是 |
| 你的应用是否具有机密客户端？ | 是 |
| 你是否拥有为应用注册的所有 (统一) URI？ | 是 |
| 对于你的应用，应避免使用什么？ | - 通配符重定向 URI，<br/>- OAuth2 隐式Flow，除非 SPA 需要<br/>- 资源所有者密码凭据 (ROPC) 流 |
| 你的应用是否公开任何 Web API？ | 否 |
| 你的应用是否使用预览 API？ | 是 |
| 你的应用是否使用已弃用 API？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
