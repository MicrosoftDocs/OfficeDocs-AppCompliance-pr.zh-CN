---
title: SalesTim 的 SalesTim 应用程序信息
ms.author: elmalova
author: elenamalova
ms.date: 10/27/2020
ms.topic: article
ms.service: attestation
certification_type: certified
description: SalesTim 的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: b15cf2f87b6707b6fa82dfc3968444d7cad85e8a
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 07/22/2021
ms.locfileid: "53524755"
---
# <a name="salestim"></a>SalesTim

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>开发人员上次更新时间：2020 年 10 月 27 日</p>

* <a href="https://teams.microsoft.com/l/app/589748de-ec98-4616-9063-e91c629bd1a4" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001393" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

SalesTim 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | SalesTim |
| ID | WA200001393 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | SalesTim |
| 合作伙伴网站的 URL | [https://www.salestim.com/](https://www.salestim.com/) |
| 隐私策略的 URL | [https://www.salestim.com/legal/privacy/](https://www.salestim.com/legal/privacy/) |
| 使用条款 URL | [https://www.salestim.com/legal/tos/](https://www.salestim.com/legal/tos/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

此信息由 SalesTim 提供有关此应用程序如何收集和存储组织数据以及您的组织将拥有对应用收集的数据的控制的信息。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph所需的](https://docs.microsoft.com/graph/permissions-reference)任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD 应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| AppCatalog.ReadWrite.All | delegated | 不 | 允许应用在企业应用目录中安装和更新自己的程序包。 | [2a651f59-97ce-42bb-97d7-cf7a2af4b635](https://docs.microsoft.com/microsoft-365-app-certification/azure/2a651f59-97ce-42bb-97d7-cf7a2af4b635) |
>| Directory.AccessAsUser.All | delegated | 我们&#8217;仅存储一些用户 ID，而不是配置文件数据。 | 允许用户在应用程序内的各个位置选择其他用户，例如选择工作流中的审批者。 | [2a651f59-97ce-42bb-97d7-cf7a2af4b635](https://docs.microsoft.com/microsoft-365-app-certification/azure/2a651f59-97ce-42bb-97d7-cf7a2af4b635) |
>| Group.ReadWrite.All | delegated | 我们&#8217;存储组/团队的 ID，&#8217;不存储任何组/团队内容。 | 允许应用代表登录用户创建组、读取所有组属性和成员身份。 此外，还允许组所有者管理他们的组并允许组成员更新组内容。 | [2a651f59-97ce-42bb-97d7-cf7a2af4b635](https://docs.microsoft.com/microsoft-365-app-certification/azure/2a651f59-97ce-42bb-97d7-cf7a2af4b635) |
>| Mail.Send | delegated | 我们将&#8217;此操作的元数据，例如通知日期、收件人 (ID) 请求 ID。 | 允许应用在审批工作流期间发送通知电子邮件，例如。 | [2a651f59-97ce-42bb-97d7-cf7a2af4b635](https://docs.microsoft.com/microsoft-365-app-certification/azure/2a651f59-97ce-42bb-97d7-cf7a2af4b635) |
>| Sites.ReadWrite.All | delegated | 我们使用一些 Azure 服务来存储数据，尤其是在 Azure 和 Cosmos DB 上 | 允许应用在团队预配 (管理) 关联的文件和文件夹的驱动器。 | [2a651f59-97ce-42bb-97d7-cf7a2af4b635](https://docs.microsoft.com/microsoft-365-app-certification/azure/2a651f59-97ce-42bb-97d7-cf7a2af4b635) |
>| User.Read.All | delegated | 我们&#8217;仅存储一些用户 ID，而不是配置文件数据。 | 允许应用读取任何用户的完整配置文件属性、报表和经理集。 它尤其用于访问群体定位过程，以根据当前用户配置文件筛选某些内容。 | [2a651f59-97ce-42bb-97d7-cf7a2af4b635](https://docs.microsoft.com/microsoft-365-app-certification/azure/2a651f59-97ce-42bb-97d7-cf7a2af4b635) |
>| offlineaccess | delegated | 不支持 | 允许应用以用户方式执行一些后台操作和操作。 | [2a651f59-97ce-42bb-97d7-cf7a2af4b635](https://docs.microsoft.com/microsoft-365-app-certification/azure/2a651f59-97ce-42bb-97d7-cf7a2af4b635) |


#### <a name="non-microsoft-services-used"></a>非Microsoft 服务使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>| **所有非Microsoft 服务 OII 将转移到** |  **转移了哪些 OII？** | **转移 OII 的理由？** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| 我们将 Intercom 用作我们的主要支持应用程序。 Intercom 可能包含一些基本的用户配置文件信息，如下所述： https://developers.salestim.com/platform/datamanagement.html#support-data |  | 我们正在使用 GitHub API 从我们的生产环境自动生成问题。 我们还将一些技术日志存储在GitHub (中，如下所述 https://developers.salestim.com/platform/datamanagement.html#error-reporting-data) ：。 这些问题和日志可能包含一些基本的用户配置文件信息。 这些问题和日志每 15 天自动删除一次。 |

#### <a name="data-access-via-bots"></a>通过机器人访问数据

如果此应用程序包含机器人或消息扩展，则它可以访问最终用户可识别信息 (EUII) ：名单 (名字、姓氏、显示名称、电子邮件地址) （团队中任何团队成员的姓名、姓氏、电子邮件地址) 或添加到其中聊天）。 此应用是否使用了此功能？

>无法访问 EUII。


#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或 EUII (最终用户可识别) 是否显示在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>此处描述收集的所有数据：如上所述，日志将临时存储 https://developers.salestim.com/platform/datamanagement.html#application-data 15 天，然后自动删除。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>大多数数据存储在 Azure Cosmos DB 中。
对生产环境的访问仅限于两个人，并且这些管理员帐户是强制执行 MFA 的。
这些帐户是专用帐户，不同于我们的公司帐户。
数据在我们使用的所有 Azure 服务中都进行其余加密。
到生产环境的部署通过我们的生产环境中专用受保护的分支GitHub，只有两个人可以批准更改。

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>是

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

下面将显示[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35853' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35853" target="_blank">在新建选项卡中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

