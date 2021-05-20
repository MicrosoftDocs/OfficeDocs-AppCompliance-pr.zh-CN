---
title: 波罗兰语的应用程序信息
ms.author: elmalova
author: elenamalova
ms.date: 11/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: 所有可用的针对"一致性"的安全和合规性信息、其数据处理策略、Microsoft Cloud App Security应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 49b17e202fb358284b9a36ed33646926d649afe3
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553453"
---
# <a name="retro"></a>Retro

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2020 年 11 月 3 日</p>

* <a href="https://teams.microsoft.com/l/app/434e1a1a-2ed7-4e45-9588-04f5099fd876" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001892" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

由波罗地语提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | Retro |
| ID | WA200001892 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | Baltic Amadeus |
| 合作伙伴网站的 URL | [https://www.ba.lt/en/](https://www.ba.lt/en/) |
| 隐私策略的 URL | [https://retro.ba.lt/privacypolicy](https://retro.ba.lt/privacypolicy) |
| 使用条款 URL | [https://retro.ba.lt/termsandconditions](https://retro.ba.lt/termsandconditions) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

这些信息由波罗地语提供，关于此应用如何收集和存储组织数据以及你的组织将拥有对应用收集的数据的控制。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph所需的](https://docs.microsoft.com/graph/permissions-reference)任何 Microsoft 权限。

>此应用程序不使用 Microsoft Graph。


#### <a name="non-microsoft-services-used"></a>非Microsoft 服务使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>| **所有非Microsoft 服务 OII 将转移到** |  **转移了哪些 OII？** | **转移 OII 的理由？** |
>|:-------------------|:--------------------------|:--------------------------|
>| 后向应用具有其自己的 Web API，该 API 不被视为 Microsoft 服务。 如前所述，它存储"电子邮件"和"全名"以用于标识和适当的内容显示目的。 此数据不会发送到任何其他位置。 此外，为将 sprint 数据导出到 Atlassian confluence 空间，一个可选功能。 为此，用户必须输入其多余的用户名和密码。 此数据仅用于代表用户向 api 提出经过身份验证的请求，不会在任意位置存储和记录。 |  | 在 Azure 中注册的代理也具有自己的 Web API。 若要使用它，必须通过 Microsoft 标识平台对用户进行身份验证。 用户必须经过身份验证，以便"反病毒"应用可以服务器用户特定的内容 |

#### <a name="data-access-via-bots"></a>通过机器人访问数据

如果此应用程序包含机器人或消息扩展，则它可以访问最终用户可识别信息 (EUII) ：名单 (名字、姓氏、显示名称、电子邮件地址) （团队中任何团队成员的姓名、姓氏、电子邮件地址) 或添加到其中聊天）。 此应用是否使用了此功能？

>| **访问 EUII 的理由？**  | **EUII 是否存储在数据库 (中) ？** | **存储 EUII 的理由** |
>|:--------------------------------|:---------------------|:--------------------------|
>| 机器人访问名单，以检查加入或离开团队的成员。 基于这一点，它会从项目添加或停用该用户，以便用户不再显示在 sprint 参与者列表中。 | 电子邮件和 FullName 链接在一起，并存储在数据库中。 电子邮件用于用户标识，以便显示登录用户的适当内容。 FullName 用于显示 puproses，因此其他用户可以知道他们要评估或编写反馈的用户。  |  |


#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或 EUII (最终用户可识别) 是否显示在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>否。 在"改进"应用中生成遥测/日志的唯一过程是错误日志记录。 错误日志不包括任何 EUII 或 OII

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>数据存储在 azure sql server 数据库中。 它通过"逆时"应用和"喜欢"机器人进行存储。
默认情况下，azure sql 数据库启用了透明数据加密。
数据库被锁定在基本身份验证后面。

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>是

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

下面将显示[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36148' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36148" target="_blank">在新建选项卡中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

