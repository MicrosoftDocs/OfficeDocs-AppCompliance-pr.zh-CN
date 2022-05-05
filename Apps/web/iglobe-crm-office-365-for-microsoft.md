---
title: 适用于 Microsoft 365 的 iGlobe CRM Office 365的应用程序信息
ms.author: elmalova
author: elenamalova
ms.date: 06/22/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: iGlobe CRM 的所有可用安全性和符合性信息Office 365用于Microsoft 365、其数据处理策略、其Microsoft Cloud App Security应用目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 020e2ce913d50c72c401b4d08bc7810173faaa28
ms.sourcegitcommit: 7a7de9f48f6cf5b6acd435412477b6a59127f19a
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 05/05/2022
ms.locfileid: "65225003"
---
# <a name="application-information-for-iglobe-crm-office-365-for-microsoft-365"></a>适用于Microsoft 365的 iGlobe CRM Office 365的应用程序信息

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2021 年 6 月 22 日</p>

* <a href="https://appsource.microsoft.com/product/web-apps/17859280.iglobecrmoffice365" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

iGlobe 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | 适用于Microsoft 365的 iGlobe CRM Office 365 |
| ID | 17859280.iglobecrmoffice365 |
| 合作伙伴公司名称 | iGlobe |
| 合作伙伴网站的 URL | [https://www.iglobecrm.com](https://www.iglobecrm.com) |
| 隐私策略的 URL | [https://www.iglobecrm.com/content/legal-information](https://www.iglobecrm.com/content/legal-information) |
| 使用条款的 URL | [https://iglobecrm.com/content/iglobe-crm-office-365-end-use...](https://iglobecrm.com/content/iglobe-crm-office-365-end-user-license-agreement) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

iGlobe 提供了此信息，了解此应用如何收集和存储组织数据，以及组织对应用收集的数据的控制。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph进行数据访问

列出此应用所需的任何 [Microsoft Graph权](/graph/permissions-reference)限。

>| **权限**  | **委托/应用程序)  (权限的类型** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD应用 ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | 委托 | 应用程序数据库中不存储任何数据。 | 在将会议报告从 canlendar 调用到 iGlobe 时，可以访问用户日历 | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Contacts.ReadWrite | 委托 | Directory.AccessAsUser.All | 允许应用以登录用户身份访问目录中的信息。 | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Directory.Read.All | 委托 | 应用程序数据库中不存储任何数据。 | 检查权限并获取网站和列表。 创建文件夹、获取文件并保存文件。 | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Directory.ReadWrite.All | 委托 | 应用程序数据库中不存储任何数据。 | 允许应用以登录用户身份访问目录中的信息。 | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Files.ReadWrite.All | 委托 | 应用程序数据库中不存储任何数据。 | 读取、更新、创建平移器任务、读取用户最近和共享的文件，以获取SharePoint列表、库和文件。 将文件和数据保存到SharePoint列表。 | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Group.Read.All | 委托 | 应用程序数据库中不存储任何数据。 | 读取、更新、创建平移器任务、读取用户最近和共享的文件，以获取SharePoint列表、库和文件。 将文件保存到SharePoint列表。 | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Group.ReadWrite.All | 委托 | 应用程序数据库中不存储任何数据。 | 读取、更新、创建平移器任务、读取用户最近和共享的文件，以获取SharePoint列表、库和文件。 将文件保存到SharePoint列表。 集成到 iGlobe CRM Office 365 | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Mail.ReadWrite | 委托 | 应用程序数据库中不存储任何数据。 | 将 eamil Svae 到 iGlobe CRM，并从 iGlobe 获取 informatiopn 到新的 e-amil | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Sites.Manage.All | 委托 | 应用程序数据库中不存储任何数据。 | 在 iGlobe CRM 中创建、编辑和删除项目和列表 | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Sites.Read.All | 委托 | 应用程序数据库中不存储任何数据。 | 在 iGlobe CRM 中读取项目 | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Sites.ReadWrite.All | 委托 | 应用程序数据库中不存储任何数据。 | 在 iGlobe CRM 中编辑和删除项目和列表 | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Tasks.ReadWrite | 委托 | 应用程序数据库中不存储任何数据。 | 从 iGlobe CRM 创建 planner 任务 | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| User.Read | 委托 | 应用程序数据库中不存储任何数据。 | 为 speficic 用户获取 iGlobe CRM 的信息 | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |

#### <a name="data-access-using-other-microsoft-apis"></a>使用其他 Microsoft API 进行数据访问

基于Microsoft 365构建的应用和加载项可以使用除 Microsoft Graph 以外的其他 Microsoft API 来收集或处理组织可识别信息 (OII) 。 列出此应用使用的 Microsoft Graph以外的任何 Microsoft API。

>| **API** |  **是否已收集 OII？** |  **收集了哪些 OII？** | **收集 OII 的理由？** | **OII 是否存储？** | **存储 OII 的理由？** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| Exchange - Calendars.ReadWrite.All | 否 |  |  |  |  |
>| Exchange - Mail.Read.All | 否 |  |  |  |  |
>| Exchange - Contacts.Read | 否 |  |  |  |  |
>| Exchange - EWS。AccessAsUser.All | 否 |  |  |  |  |
>| Exchange - Tasks.ReadWrite | 否 |  |  |  |  |
>| SharePoint - AllSites.Manage | 否 |  |  |  |  |
>| SharePoint - AllSites.Read | 否 |  |  |  |  |
>| SharePoint -AllSites.Write | 不支持 |  |  |  |  |
>| SharePoint - MyFiles.Write | 不支持 |  |  |  |  |
>| SharePoint - Sites.Manage.All | 否 |  |  |  |  |
>| SharePoint - Sites.Read.All | 不支持 |  |  |  |  |
>| SharePoint - Sites.ReadWrite.All | 不支持 |  |  |  |  |
>| SharePoint - Sites.Search.All | 不支持 |  |  |  |  |
>| SharePoint - TermStore.Read.All | 不支持 |  |  |  |  |
>| SharePoint - TermStore.ReadWrite.All | 不支持 |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>未使用Microsoft 服务

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输的数据，并包含应用需要传输此信息的原因。

>不使用非Microsoft 服务。



#### <a name="telemetry-data"></a>遥测数据

此应用程序的遥测或日志中是否 (OII) 或最终用户身份信息 (EUII) 显示任何组织可识别信息？ 如果是，请描述存储的数据以及什么是保留和删除策略？

>iGlobe 收集数据以有效运行，并提供产品和服务的最佳体验。 对于许可：收集的数据用于管理组织&#8217;许可帐户，例如部署免费加载项、创建试用订阅或购买订阅时。 收集以下信息。 
- 出于财务目的：公司名称和地址
- 订阅用户：用户名和电子邮件

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

介绍组织管理员如何控制合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>所有数据都位于客户自己的租户上。 不存储应用程序数据。 新式加载项在沙盒浏览器中运行，&#8220;进程外&#8221;。 它使用Microsoft 服务与用户数据交互。 外接程序可能仅访问用户正在使用的数据。

#### <a name="human-review-of-organizational-information"></a>组织信息的人工评审

人类是否参与查看或分析组织识别信息 (OII) 此应用收集或存储的数据？

>不支持

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

下面显示了[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36163' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36163" target="_blank">在新选项卡中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>标识信息

iGlobe 提供了有关此应用如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件的信息。

| **Information** | **响应** |
|:----------------|:-------------|
| 是否与 Microsoft 标识平台 (Azure AD) 集成？  | 是 |
| 是否已查看并遵守Microsoft 标识平台集成清单中列出的所有适用最佳做法？  | 是 |
| 应用是否使用 MSAL (Microsoft 身份验证库) 进行身份验证？ | 否 |
| 应用是否支持条件访问策略？ | 是 |
| 列出支持的策略类型 | 安全默认值和任何其他常见策略（如阻止旧式身份验证* 要求管理员使用 MFA* 要求对 Azure 管理使用 MFA* 要求所有用户使用 MFA* |
| 你的应用是否请求方案的最低特权权限？ | 是 |
| 应用的静态注册权限是否准确反映应用将以动态和增量方式请求的权限？ | 是 |
| 你的应用是否支持多租户？ | 是 |
| 你的应用是否具有机密客户端？ | 是 |
| 是否拥有注册应用的所有重定向统一资源标识符 (URI) ？ | 是 |
| 你的应用是否公开任何 Web API？ | 否 |
| 应用是否使用预览 API？ | 不支持 |
| 你的应用是否使用已弃用的 API？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
