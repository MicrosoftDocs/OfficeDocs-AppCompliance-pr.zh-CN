---
title: Guru 技术的 Guru 应用程序信息
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 04/19/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Guru 的所有可用安全性和符合性信息、其数据处理策略、其Microsoft Cloud App Security应用目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: b623d0d92400219e5ad31d58ade4d98409aced98
ms.sourcegitcommit: 7a7de9f48f6cf5b6acd435412477b6a59127f19a
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 05/05/2022
ms.locfileid: "65226556"
---
# <a name="guru"></a>Guru

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2021 年 3 月 1 日</p>

* <a href="https://teams.microsoft.com/l/app/094bf90e-e413-4740-b2dc-68d624d0e40e" target="_blank">Teams存储区中的视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001719" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

Guru Technologies 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | Guru |
| ID | WA200001719 |
| 支持Office 365客户端 | Microsoft Teams |
| 合作伙伴公司名称 | Guru Technologies |
| 合作伙伴网站的 URL | [https://www.getguru.com](https://www.getguru.com) |
| Teams应用程序信息页的 URL | [https://www.getguru.com/integrations/microsoft-teams](https://www.getguru.com/integrations/microsoft-teams) |
| 隐私策略的 URL | [https://www.getguru.com/privacy/](https://www.getguru.com/privacy/) |
| 使用条款的 URL | [https://www.getguru.com/terms-of-service](https://www.getguru.com/terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

Guru Technologies 提供了此信息，了解此应用如何收集和存储组织数据以及组织对应用收集的数据的控制。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph进行数据访问

列出此应用所需的任何 [Microsoft Graph权](/graph/permissions-reference)限。

>此应用程序不使用 Microsoft Graph。


#### <a name="non-microsoft-services-used"></a>未使用Microsoft 服务

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输的数据，并包含应用需要传输此信息的原因。

>| **将所有非Microsoft 服务 OII 传输到** |  **将传输哪些 OII？** | **传输 OII 的理由？** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Guru 的最终用户应用程序和内部数据库 | 当用户或公司为Teams设置 Guru 应用时，Guru 会记录和访问与其用户配置文件关联的常见信息，例如用户名、电子邮件和公司名称 | 鉴于用户必须同时具有Teams帐户和 Guru 帐户才能使用集成，我们跟踪并跟踪哪些用户启用集成以帮助为这些用户提供支持和管理 |

#### <a name="data-access-via-bots"></a>通过机器人进行数据访问

如果此应用包含机器人或消息传递扩展，则它可以访问最终用户身份信息 (EUII) ：名册 (名字、姓氏、显示名称、团队中任何团队成员的电子邮件地址) 或添加到的聊天。 此应用是否利用此功能？

>未访问 EUII。


#### <a name="telemetry-data"></a>遥测数据

此应用程序的遥测或日志中是否 (OII) 或最终用户身份信息 (EUII) 显示任何组织可识别信息？ 如果是，请描述存储的数据以及什么是保留和删除策略？

>当用户或公司为Teams设置 Guru 应用时，Guru 会记录和访问与其用户配置文件关联的常见信息，例如用户名、电子邮件和公司名称。 帐户终止后，数据将保留 90 天，然后删除。 

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

介绍组织管理员如何控制合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>Guru 团队设置允许团队中的管理员确定要按集合预配的组 () 和访问/角色控件，并能够向备用人员添加、删除和重新分配卡片。 Enterprise已部署 SSO 的客户也具有 SSO 提供程序控制台的优势，可通过 SCIM 载入/卸载和建立组

#### <a name="human-review-of-organizational-information"></a>组织信息的人工评审

人类是否参与查看或分析组织识别信息 (OII) 此应用收集或存储的数据？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

下面显示了[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36912' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36912" target="_blank">在新选项卡中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>标识信息

Guru Technologies 提供了此信息，了解此应用如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件。

| **Information** | **响应** |
|:----------------|:-------------|
| 是否与 Microsoft 标识平台 (Azure AD) 集成？  | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
