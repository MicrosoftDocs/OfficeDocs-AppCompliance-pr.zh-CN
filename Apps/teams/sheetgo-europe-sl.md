---
title: SHEETGO EUROPE SL 提供的 Sheetgo 应用程序信息
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 11/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: 查看 Sheetgo 的所有可用安全性和符合性信息、其数据处理策略、其Microsoft Cloud App Security应用目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 001ad5dcce2a95885420f8413bfbfe03562eb5b2
ms.sourcegitcommit: ef767e1079411056cb3ca86d6b29084e31b0ef1c
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 05/26/2022
ms.locfileid: "65690427"
---
# <a name="sheetgo-application-information"></a>Sheetgo 应用程序信息

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2020 年 11 月 3 日</p>

* <a href="https://teams.microsoft.com/l/app/583de270-58d0-4f94-af06-bf971f82fd94" target="_blank">Teams存储区中的视图</a>
* <a href="https://appsource.microsoft.com/en-US/product/office/WA200002128?tab=Overview" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

SHEETGO EUROPE SL 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | Sheetgo |
| ID | WA200002067 |
| 支持Office 365客户端 | Microsoft Teams |
| 合作伙伴公司名称 | SHEETGO EUROPE SL |
| 合作伙伴网站的 URL | [https://www.sheetgo.com/](https://www.sheetgo.com/) |
| 隐私策略的 URL | [https://www.sheetgo.com/legal/privacy/](https://www.sheetgo.com/legal/privacy/) |
| 使用条款的 URL | [https://www.sheetgo.com/legal/terms/](https://www.sheetgo.com/legal/terms/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

SHEETGO EUROPE SL 提供了此信息，了解此应用如何收集和存储组织数据以及组织对应用收集的数据的控制。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph进行数据访问

列出此应用所需的任何 [Microsoft Graph权](/graph/permissions-reference)限。

>此应用程序不使用 Microsoft Graph。


#### <a name="non-microsoft-services-used"></a>未使用Microsoft 服务

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输的数据，并包含应用需要传输此信息的原因。

>| **将所有非Microsoft 服务 OII 传输到** |  **将传输哪些 OII？** | **传输 OII 的理由？** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| MongoDB：记录系统和用户数据以正常运行，Google BigQuery：记录系统日志使用情况，Google Firestore：一个维护和协调微服务状态的系统，Stripe：付款系统 |  | 这些应用程序不使用其他 Microsoft API |

#### <a name="data-access-via-bots"></a>通过机器人进行数据访问

如果此应用包含机器人或消息传递扩展，则它可以访问最终用户身份信息 (EUII) ：名册 (名字、姓氏、显示名称、团队中任何团队成员的电子邮件地址) 或添加到的聊天。 此应用是否利用此功能？

>未访问 EUII。


#### <a name="telemetry-data"></a>遥测数据

此应用程序的遥测或日志中是否 (OII) 或最终用户身份信息 (EUII) 显示任何组织可识别信息？ 如果是，请描述存储的数据以及什么是保留和删除策略？

>遥测/日志仅包含用户的电子邮件地址作为最终用户可识别信息。 当用户请求时，应用程序支持团队将运行一个内部自动例程，用于模糊遥测/日志中的电子邮件地址，使用户数据不再可识别。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

介绍组织管理员如何控制合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>MongoDB：记录系统和用户数据以运行 Google BigQuery：记录系统日志使用情况 Google Firestore：一个维护和协调微服务状态的系统。 此服务传输的唯一关键数据是使用 AES256 Stripe：付款系统加密的用户凭据。
 
传输中的所有数据都使用 HTTPS 进行安全连接，所有敏感数据都使用 AES256 进行加密

#### <a name="human-review-of-organizational-information"></a>组织信息的人工评审

人类是否参与查看或分析组织识别信息 (OII) 此应用收集或存储的数据？

>是

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

下面显示了[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36141' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36141" target="_blank">在新选项卡中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

