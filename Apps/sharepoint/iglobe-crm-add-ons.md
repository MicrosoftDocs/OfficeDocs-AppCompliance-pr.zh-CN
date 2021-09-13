---
title: iGlobe CRM 加载项的应用程序信息（由 iGlobe 提供）
ms.author: elmalova
author: elenamalova
ms.date: 08/12/2021
ms.topic: article
ms.service: attestation
certification_type: certified
description: iGlobe CRM 加载项的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security 应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 3d5551ff00fa5439329176cf412a45d0490d6d64
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 09/12/2021
ms.locfileid: "59279436"
---
# <a name="iglobe-crm-add-ons"></a>iGlobe CRM 加载项

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>开发人员上次更新时间：2021 年 8 月 12 日</p>

* <a href="https://appsource.microsoft.com/product/office/WA200002010" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

iGlobe 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | iGlobe CRM 加载项 |
| ID | WA200002010 |
| Office 365支持的客户端 | SharePoint 2016 或更高版本 |
| 合作伙伴公司名称 | iGlobe |
| 合作伙伴网站的 URL | [https://www.iglobecrm.com](https://www.iglobecrm.com) |
| 隐私策略的 URL | [https://iglobecrm.com/content/legal-information](https://iglobecrm.com/content/legal-information) |
| 使用条款 URL | [https://iglobecrm.com/content/iglobe-crm-office-365-end-use...](https://iglobecrm.com/content/iglobe-crm-office-365-end-user-license-agreement) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

此信息由 iGlobe 提供，用于了解此应用如何收集和存储组织数据，以及组织对应用收集的数据的控制。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph所需的](https://docs.microsoft.com/graph/permissions-reference)任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD 应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | delegated | 应用程序数据库中不存储任何数据。 | 在将会议报告从 canlendar 提交到 iGlobe 时，有权访问用户日历 | [0bb1641a-3b3b-47f7-a11e-01279d92abfb](https://docs.microsoft.com/microsoft-365-app-certification/azure/0bb1641a-3b3b-47f7-a11e-01279d92abfb) |
>| Contacts.ReadWrite | delegated |  Directory.AccessAsUser.All | 允许应用以登录用户身份访问目录中的信息。 | [0bb1641a-3b3b-47f7-a11e-01279d92abfb](https://docs.microsoft.com/microsoft-365-app-certification/azure/0bb1641a-3b3b-47f7-a11e-01279d92abfb) |
>| Directory.Read.All | delegated | 应用程序数据库中不存储任何数据。 | 检查权限并获取网站和列表。 创建文件夹、获取文件和保存文件。 | [0bb1641a-3b3b-47f7-a11e-01279d92abfb](https://docs.microsoft.com/microsoft-365-app-certification/azure/0bb1641a-3b3b-47f7-a11e-01279d92abfb) |
>| Directory.ReadWrite.All | delegated | 应用程序数据库中不存储任何数据。 | 允许应用以登录用户身份访问目录中的信息。 | [0bb1641a-3b3b-47f7-a11e-01279d92abfb](https://docs.microsoft.com/microsoft-365-app-certification/azure/0bb1641a-3b3b-47f7-a11e-01279d92abfb) |
>| Files.ReadWrite.All | delegated | 应用程序数据库中不存储任何数据。 | 读取、更新、创建平移器任务、读取用户的最近文件和共享文件、获取SharePoint列表、库和文件。 将文件和数据保存到SharePoint列表中。 | [0bb1641a-3b3b-47f7-a11e-01279d92abfb](https://docs.microsoft.com/microsoft-365-app-certification/azure/0bb1641a-3b3b-47f7-a11e-01279d92abfb) |
>| Group.Read.All | delegated | 应用程序数据库中不存储任何数据。 | 读取、更新、创建平移器任务、读取用户的最近文件和共享文件、获取SharePoint列表、库和文件。 将文件保存到SharePoint列表中。 | [0bb1641a-3b3b-47f7-a11e-01279d92abfb](https://docs.microsoft.com/microsoft-365-app-certification/azure/0bb1641a-3b3b-47f7-a11e-01279d92abfb) |
>| Group.ReadWrite.All | delegated | 应用程序数据库中不存储任何数据。 | 读取、更新、创建平移器任务、读取用户的最近文件和共享文件、获取SharePoint列表、库和文件。 将文件保存到SharePoint列表中。 与 iGlobe CRM Office 365 | [0bb1641a-3b3b-47f7-a11e-01279d92abfb](https://docs.microsoft.com/microsoft-365-app-certification/azure/0bb1641a-3b3b-47f7-a11e-01279d92abfb) |
>| Mail.ReadWrite | delegated | 应用程序数据库中不存储任何数据。 | Svae the eamil to iGlobe CRM and get informatiopn from iGlobe to a new e-amil | [0bb1641a-3b3b-47f7-a11e-01279d92abfb](https://docs.microsoft.com/microsoft-365-app-certification/azure/0bb1641a-3b3b-47f7-a11e-01279d92abfb) |
>| Sites.Manage.All | delegated | 应用程序数据库中不存储任何数据。 | 在 iGlobe CRM 中创建、编辑和删除项目和列表 | [0bb1641a-3b3b-47f7-a11e-01279d92abfb](https://docs.microsoft.com/microsoft-365-app-certification/azure/0bb1641a-3b3b-47f7-a11e-01279d92abfb) |
>| Sites.Read.All | delegated | 应用程序数据库中不存储任何数据。 | 读取 iGlobe CRM 中的项目 | [0bb1641a-3b3b-47f7-a11e-01279d92abfb](https://docs.microsoft.com/microsoft-365-app-certification/azure/0bb1641a-3b3b-47f7-a11e-01279d92abfb) |
>| Sites.ReadWrite.All | delegated | 应用程序数据库中不存储任何数据。 |  编辑和删除 iGlobe CRM 中的项目和列表 | [0bb1641a-3b3b-47f7-a11e-01279d92abfb](https://docs.microsoft.com/microsoft-365-app-certification/azure/0bb1641a-3b3b-47f7-a11e-01279d92abfb) |
>| Tasks.ReadWrite | delegated | 应用程序数据库中不存储任何数据。 | 从 iGlobe CRM 创建计划工具任务 | [0bb1641a-3b3b-47f7-a11e-01279d92abfb](https://docs.microsoft.com/microsoft-365-app-certification/azure/0bb1641a-3b3b-47f7-a11e-01279d92abfb) |
>| User.Read | delegated | 应用程序数据库中不存储任何数据。 | 获取子用户 iGlobe CRM 的信息 | [0bb1641a-3b3b-47f7-a11e-01279d92abfb](https://docs.microsoft.com/microsoft-365-app-certification/azure/0bb1641a-3b3b-47f7-a11e-01279d92abfb) |

#### <a name="data-access-using-other-microsoft-apis"></a>使用其他 Microsoft API 进行数据访问

基于组织构建的应用和Microsoft 365可以使用除 Microsoft Graph 外的其他 Microsoft API 来收集或处理 OII (组织) 。 列出此应用使用的任何 Microsoft GRAPH Microsoft API。

>| **API** |  **是否收集 OII？** |  **收集哪些 OII？** | **收集 OII 的理由？** | **是否存储 OII？** | **存储 OII 的理由** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| Exchange - Calendars.ReadWrite.All | 否 |  |  |  |  |
>| Exchange - Mail.Read.All | 否 |  |  |  |  |
>| Exchange - Contacts.Read | 否 |  |  |  |  |
>| Exchange - EWS。AccessAsUser.All | 否 |  |  |  |  |
>| Exchange - Tasks.ReadWrite | 否 |  |  |  |  |
>| SharePoint - AllSites.Manage | 否 |  |  |  |  |
>| SharePoint - AllSites.Read | 否 |  |  |  |  |
>|  SharePoint -AllSites.Write | 否 |  |  |  |  |
>| SharePoint - MyFiles.Write | 否 |  |  |  |  |
>| SharePoint - Sites.Manage.All | 否 |  |  |  |  |
>| SharePoint - Sites.Read.All | 否 |  |  |  |  |
>| SharePoint - Sites.ReadWrite.All | 否 |  |  |  |  |
>| SharePoint - Sites.Search.All | 否 |  |  |  |  |
>|  SharePoint - TermStore.Read.All | 否 |  |  |  |  |
>| SharePoint - TermStore.ReadWrite.All | 否 |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>非Microsoft 服务使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>不Microsoft 服务非活动。



#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或最终用户可识别信息 (EUII) 是否出现在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>iGlobe 收集数据以有效操作，并提供我们的产品和服务的最佳体验。 对于许可：为管理组织&#8217;许可帐户收集的数据，例如当你部署免费外接程序、创建试用订阅或购买订阅时。 收集以下信息。 
- 出于财务目的：公司名称和地址
- 订阅的用户：用户名和电子邮件

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>所有数据都位于客户自己的租户上。 不存储应用程序数据。 新式外接程序在沙盒浏览器中运行，&#8220;进程外&#8221;。 它通过使用数据与用户数据Microsoft 服务。 加载项只能访问用户正使用的数据。

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

下面将显示[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36163' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36163" target="_blank">在新建选项卡中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>标识信息

此信息由 iGlobe 提供有关此应用如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件的信息。

| **Information** | **响应** |
|:----------------|:-------------|
| 你是否与 Microsoft 标识平台 (Azure AD) ？  | 是 |
| 您是否已审阅并遵循了 Microsoft 标识平台 集成清单中列出的所有适用最佳做法？  | 是 |
| 你的应用是否使用 MSAL (Microsoft 身份验证库) 进行身份验证？ | 否 |
| 你的应用是否支持条件访问策略？ | 是 |
| 列出支持的策略类型 | 安全默认值和任何其他常见策略（如阻止旧版身份验证* 要求管理员使用 MFA* 需要 Azure 管理的 MFA* 要求所有用户使用 MFA* |
| 应用是否请求方案最小特权权限？ | 是 |
| 应用的静态注册权限是否准确反映应用将动态和增量请求的权限？ | 是 |
| 你的应用是否支持多租户？ | 是 |
| 你的应用是否具有机密客户端？ | 是 |
| 你是否拥有为应用注册的所有 (统一) URI？ | 是 |
| 你的应用是否公开任何 Web API？ | 否 |
| 你的应用是否使用预览 API？ | 否 |
| 你的应用是否使用已弃用 API？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
