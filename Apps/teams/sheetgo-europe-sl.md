---
title: SHEETGO EUROPE SL 中 Sheetgo 的应用程序信息
ms.author: elmalova
author: elenamalova
ms.date: 11/03/2020
ms.topic: article
ms.service: attestation
description: Sheetgo 的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: bd78e2ecd6646a88137cb346d0f64546359ae69f
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/30/2021
ms.locfileid: "52092473"
---
# <a name="sheetgo"></a>Sheetgo

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2020 年 11 月 3 日</p>

* <a href="https://teams.microsoft.com/l/app/583de270-58d0-4f94-af06-bf971f82fd94" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002067" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

SHEETGO EUROPE SL 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | Sheetgo |
| ID | WA200002067 |
| 功能 | 选项卡 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | SHEETGO EUROPE SL |
| 合作伙伴网站的 URL | [https://www.sheetgo.com](https://www.sheetgo.com) |
| 隐私策略的 URL | [https://www.sheetgo.com/legal/privacy/](https://www.sheetgo.com/legal/privacy/) |
| 使用条款 URL | [https://www.sheetgo.com/legal/terms/](https://www.sheetgo.com/legal/terms/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

SHEETGO EUROPE SL 提供了此信息，这些信息与此应用程序如何收集和存储组织数据以及您的组织将拥有对应用收集的数据的控制有关。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph所需的](https://docs.microsoft.com/graph/permissions-reference)任何 Microsoft 权限。

>此应用程序不使用 Microsoft Graph。


#### <a name="non-microsoft-services-used"></a>非Microsoft 服务使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>| **所有非Microsoft 服务 OII 将转移到** |  **转移了哪些 OII？** | **转移 OII 的理由？** |
>|:-------------------|:--------------------------|:--------------------------|
>| MongoDB： Record system and user data in order to function， Google BigQuery： Record system logs usage， Google Firestore： A system which maintains and orchestrates the state of our microservices， Stripe： Payment system |  | 这些应用程序不使用其他 Microsoft API |

#### <a name="data-access-via-bots"></a>通过机器人访问数据

如果此应用程序包含机器人或消息扩展，则它可以访问最终用户可识别信息 (EUII) ：名单 (名字、姓氏、显示名称、电子邮件地址) （团队中任何团队成员的姓名、姓氏、电子邮件地址) 或添加到其中聊天）。 此应用是否使用了此功能？

>无法访问 EUII。



#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或 EUII (最终用户可识别) 是否显示在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>遥测/日志仅包含用户的电子邮件地址作为最终用户可识别信息。 当用户请求时，应用程序支持团队将运行一个内部自动例程，该例程模糊遥测/日志中的电子邮件地址，使用户数据不再可识别。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>MongoDB：记录系统和用户数据以运行 Google BigQuery：记录系统日志使用情况 Google Firestore：一个维护和安排微服务状态的系统。 此服务传输的唯一关键数据是使用 AES256 Stripe： Payment system 加密的用户凭据。
 
传输的所有数据都使用 HTTPS 进行安全连接，所有敏感数据均使用 AES256 进行加密

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>是

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

下面将显示[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36141' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36141" target="_blank">在新建选项卡中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

