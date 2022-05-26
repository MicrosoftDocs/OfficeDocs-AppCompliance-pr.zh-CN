---
title: SalesTim 的应用程序信息
ms.author: elmalova
manager: tonybal
author: elenamalova
ms.date: 06/24/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: 查看 SalesTim 的所有可用安全性和符合性信息、其数据处理策略、其Microsoft Cloud App Security应用目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 9bf1f4057ad73ba33a8ae3ba0ff02c74851cdecf
ms.sourcegitcommit: ef767e1079411056cb3ca86d6b29084e31b0ef1c
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 05/26/2022
ms.locfileid: "65688117"
---
# <a name="application-information-for-salestim-by-salestim"></a>SalesTim by SalesTim 的应用程序信息

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2021 年 6 月 24 日</p>

* <a href="https://appsource.microsoft.com/product/web-apps/salestim.salestim" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

SalesTim 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | SalesTim |
| ID | salestim.salestim |
| 合作伙伴公司名称 | SalesTim |
| 合作伙伴网站的 URL | [https://nbold.co/](https://nbold.co/) |
| 隐私策略的 URL | [https://www.salestim.com/legal/privacy/](https://www.salestim.com/legal/privacy/) |
| 使用条款的 URL | [https://www.salestim.com/legal/tos/](https://www.salestim.com/legal/tos/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

SalesTim 提供了此信息，了解此应用如何收集和存储组织数据以及组织对应用收集的数据的控制。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph进行数据访问

列出此应用所需的任何 [Microsoft Graph权](/graph/permissions-reference)限。

>| **权限**  | **委托/应用程序)  (权限的类型** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD 应用 ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| AppCatalog.ReadWrite.All | 委托 | 否 | 允许应用在公司应用目录中安装和更新其自己的包。 | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Directory.AccessAsUser.All | 委托 | 我们&#8217;只存储一些用户 ID，而不是配置文件数据。 | 允许用户在应用程序的不同位置选择其他用户，例如在工作流中选择审批者。 | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Group.ReadWrite.All | 委托 | 我们&#8217;只存储组/团队 ID，&#8217;不存储任何组/团队内容。 | 允许应用创建组，代表已登录用户读取所有组属性和成员身份。 此外，还允许组所有者管理他们的组并允许组成员更新组内容。 | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Mail.Send | 委托 | 我们&#8217;重新存储此操作的元数据，例如通知日期、仅) 的收件人 (ID、请求 ID。 | 允许应用发送通知电子邮件，例如在审批工作流期间。 | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Sites.ReadWrite.All | 委托 | 我们使用一些 Azure 服务来存储数据，尤其是 Azure 上的 Redis 和 Cosmos DB | 允许应用在团队预配过程中管理与团队关联 (文件和文件夹) 驱动器。 | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| User.Read.All | 委托 | 我们&#8217;只存储一些用户 ID，而不是配置文件数据。 | 允许应用读取任何用户的完整配置文件属性、报表和管理器集。 它特别在受众目标过程中使用，以根据当前用户配置文件筛选某些内容。 | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| offline_access | 委托 | 否 | 允许应用以用户身份执行一些后台操作和操作。 | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |


#### <a name="non-microsoft-services-used"></a>未使用Microsoft 服务

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输的数据，并包含应用需要传输此信息的原因。

>| **将所有非Microsoft 服务 OII 传输到** |  **将传输哪些 OII？** | **传输 OII 的理由？** |
>|:-------------------|:--------------------------|:--------------------------|
>| 我们使用 Intercom 作为主要支持应用程序。 Intercom 可能包含一些基本的用户配置文件信息，如下所述： https://developers.salestim.com/platform/datamanagement.html#support-data | 公司名称 | 我们使用GitHub API 从生产环境中自动生成问题。 我们还在GitHub (中存储一些技术日志，如下所述： https://developers.salestim.com/platform/datamanagement.html#error-reporting-data) 这些问题和日志可能包含一些基本的用户配置文件信息。 这些问题和日志每 15 天自动删除一次。 |



#### <a name="telemetry-data"></a>遥测数据

此应用程序的遥测或日志中是否 (OII) 或最终用户身份信息 (EUII) 显示任何组织可识别信息？ 如果是，请描述存储的数据以及什么是保留和删除策略？

>此处描述了收集的所有数据： https://developers.salestim.com/platform/datamanagement.html#application-data 如所述，日志暂时存储 15 天，然后自动删除。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

介绍组织管理员如何控制合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>大多数数据存储在 Azure Cosmos DB 中。
对生产环境的访问仅限于两个人，并且这些管理员帐户是强制执行 MFA 的。
这些帐户是专用的，不同于我们的公司帐户。
数据会在我们使用的所有 Azure 服务中进行静态加密。
通过我们GitHub环境中的专用受保护分支自动部署到生产环境，只有两个人可以批准更改。

#### <a name="human-review-of-organizational-information"></a>组织信息的人工评审

人类是否参与查看或分析组织识别信息 (OII) 此应用收集或存储的数据？

>是

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

下面显示了[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35853' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35853" target="_blank">在新选项卡中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>标识信息

SalesTim 提供了有关此应用如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件的信息。

| **Information** | **响应** |
|:----------------|:-------------|
| 是否与 Microsoft Identity Platform (Azure AD) 集成？  | 是 |
| 是否已查看并遵守Microsoft 标识平台集成清单中列出的所有适用最佳做法？  | 是 |
| 应用是否使用 MSAL (Microsoft 身份验证库) 进行身份验证？ | 是 |
| 应用是否支持条件访问策略？ | 是 |
| 列出支持的策略类型 | MFA，位置条件 |
| 你的应用是否请求方案的最低特权权限？ | 是 |
| 应用的静态注册权限是否准确反映应用将以动态和增量方式请求的权限？ | 是 |
| 你的应用是否支持多租户？ | 是 |
| 你的应用是否具有机密客户端？ | 是 |
| 是否拥有注册应用的所有重定向统一资源标识符 (URI) ？ | 是 |
| 对于你的应用，你避免使用什么？ | ,<br/>- OAuth2 隐式Flow，除非 SPA 需要<br/> |
| 你的应用是否公开任何 Web API？ | 是 |
| 权限模型是否仅允许在客户端应用收到适当同意时调用成功？ | 是 |
| 应用是否使用预览 API？ | 否 |
| 你的应用是否使用已弃用的 API？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
