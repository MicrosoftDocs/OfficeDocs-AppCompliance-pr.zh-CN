---
title: Prezi 应用程序信息：Prezi 视频
ms.author: elmalova
author: elenamalova
ms.date: 06/23/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Prezi Video 的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 8e7e9c70ee848fd284e3297a915ec9847d3ef1ee
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 07/22/2021
ms.locfileid: "53521242"
---
# <a name="prezi-video"></a>Prezi Video

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2020 年 6 月 23 日</p>

* <a href="https://teams.microsoft.com/l/app/78bbd675-511e-41a2-9a1a-8793920efa9e" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001577" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

Prezi 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | Prezi Video |
| ID | WA200001577 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | Prezi |
| 合作伙伴网站的 URL | [https://prezi.com](https://prezi.com) |
| 隐私策略的 URL | [https://prezi.com/privacy-policy/](https://prezi.com/privacy-policy/) |
| 使用条款 URL | [https://prezi.com/terms-of-use/](https://prezi.com/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

Prezi 提供了此信息，这些信息与此应用程序如何收集和存储组织数据以及组织将拥有对应用收集的数据的控制有关。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph所需的](https://docs.microsoft.com/graph/permissions-reference)任何 Microsoft 权限。

>此应用程序不使用 Microsoft Graph。


#### <a name="non-microsoft-services-used"></a>非Microsoft 服务使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>| **所有非Microsoft 服务 OII 将转移到** |  **转移了哪些 OII？** | **转移 OII 的理由？** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| 有关详细信息，请访问 https://prezi.com/privacy-policy/ |  | 以下 API/SDK 与 1 一起用于集成。 Botbuilder-SDK (python) ：使用此 SDK，Azure Active Directory API (对象 ID aad_object_id) 。 我们需要此信息将用户映射到Microsoft Teams上创建的任何 Prezi 视频相关 prezi.com。  2. Botbuilder-js (javascript) ：Microsoft Teams SDK 不收集特定数据。 |

#### <a name="data-access-via-bots"></a>通过机器人访问数据

如果此应用程序包含机器人或消息扩展，则它可以访问最终用户可识别信息 (EUII) ：名单 (名字、姓氏、显示名称、电子邮件地址) （团队中任何团队成员的姓名、姓氏、电子邮件地址) 或添加到其中聊天）。 此应用是否使用了此功能？

>| **访问 EUII 的理由？**  | **EUII 是否存储在数据库 (中) ？** | **存储 EUII 的理由** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| 机器人无法访问提及的名单信息。 | 机器人无法访问提及的名单信息。 |  |


#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或 EUII (最终用户可识别) 是否显示在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>应用程序日志中不显示 EUII 或 OII。


#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>我们将以下信息存储在 RDS 数据库中：

1. Azure Active Directory API (引用的对象 ID aad_object_id) 存储为Microsoft Teams用户&#8217;视频。 系统aad_object_id上的 Microsoft&#8217;官方聊天机器人 sdk 安全地检索到此内容。

2. 在 prezi.com 上创建的视频链接。 在 prezi.com 上创建的内容按以下 URL 的第 14 节存储： https://prezi.com/privacy-policy/ 

对高风险外部系统的访问权限 (AWS) 通过 OneLogin (的第三方统一身份和访问管理) 。

对统一标识和访问管理平台中的人员强制执行密码策略和多重身份验证。 基于情况，不需要从 Office IP 地址进行多重身份验证。

默认情况下，AWS 托管的服务和数据库无法从任何位置访问;必须手动添加显式入站规则。

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>是

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

下面将显示[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/17887' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/17887" target="_blank">在新建选项卡中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

