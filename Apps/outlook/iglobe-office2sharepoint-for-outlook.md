---
title: 适用于 iGlobe 的 Office2SharePoint Outlook信息
ms.author: elmalova
author: elenamalova
ms.date: 08/28/2021
ms.topic: article
ms.service: attestation
certification_type: certified
description: Office2SharePoint for Outlook 的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security 应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 6c523601bf540cc9a656efafacd020ee049e830d
ms.sourcegitcommit: 9010c9bace5d935309eae5098f5a126a55270eb6
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 09/18/2021
ms.locfileid: "59438323"
---
# <a name="office2sharepoint-for-outlook"></a>Office2SharePoint for Outlook

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>开发人员上次更新时间：2021 年 8 月 28 日</p>

* <a href="https://appsource.microsoft.com/product/office/WA104380689" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

iGlobe 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | Office2SharePoint for Outlook |
| ID | WA104380689 |
| Office 365客户端 | Outlook 2013 或更高版本，Windows Mac Outlook 2016 或更高版本，Outlook 网页版 |
| 合作伙伴公司名称 | iGlobe |
| 合作伙伴网站的 URL | [https://www.iglobecrm.com](https://www.iglobecrm.com) |
| 隐私策略的 URL | [https://www.iglobecrm.com/content/legal-information](https://www.iglobecrm.com/content/legal-information) |
| 使用条款 URL | [https://www.iglobecrm.com/content/end-user-license-agreemen...](https://www.iglobecrm.com/content/end-user-license-agreement-office2sharepoint) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

iGlobe 提供了此信息，这些信息与此应用程序如何收集和存储组织数据以及组织将拥有对应用收集的数据的控制有关。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph](https://docs.microsoft.com/graph/permissions-reference)所需的任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD 应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Directory.AccessAsUser.All | delegated | 应用程序数据库中不存储任何数据。 | 允许应用以登录用户身份访问目录中的信息。 | [5971c986-9d39-409c-a6f8-1385b1f690ef](https://docs.microsoft.com/microsoft-365-app-certification/azure/5971c986-9d39-409c-a6f8-1385b1f690ef) |
>| Directory.Read.All | delegated | 应用程序数据库中不存储任何数据。 | 检查权限并获取网站和列表。 创建文件夹、获取文件和保存文件。 | [5971c986-9d39-409c-a6f8-1385b1f690ef](https://docs.microsoft.com/microsoft-365-app-certification/azure/5971c986-9d39-409c-a6f8-1385b1f690ef) |
>| Directory.ReadWrite.All | delegated | 应用程序数据库中不存储任何数据。 | 检查权限并获取网站和列表。 创建文件夹、获取文件和保存文件。 | [5971c986-9d39-409c-a6f8-1385b1f690ef](https://docs.microsoft.com/microsoft-365-app-certification/azure/5971c986-9d39-409c-a6f8-1385b1f690ef) |
>| Group.Read.All | delegated | 应用程序数据库中不存储任何数据。 | 获取用户组网站。 | [5971c986-9d39-409c-a6f8-1385b1f690ef](https://docs.microsoft.com/microsoft-365-app-certification/azure/5971c986-9d39-409c-a6f8-1385b1f690ef) |
>| Group.ReadWrite.All | delegated | 应用程序数据库中不存储任何数据。 | 访问所选的邮件并获取附件。 From the mail or add from SharePoint or Groups site to the mail. | [5971c986-9d39-409c-a6f8-1385b1f690ef](https://docs.microsoft.com/microsoft-365-app-certification/azure/5971c986-9d39-409c-a6f8-1385b1f690ef) |
>| Sites.Manage.All | delegated | 应用程序数据库中不存储任何数据。 | 允许应用程序代表登录用户创建或删除所有网站集中的文档库和列表。 | [5971c986-9d39-409c-a6f8-1385b1f690ef](https://docs.microsoft.com/microsoft-365-app-certification/azure/5971c986-9d39-409c-a6f8-1385b1f690ef) |
>| Sites.Read.All | delegated | 应用程序数据库中不存储任何数据。 | 获取用户SharePoint网站。 获取文件并保存选定邮件中的附件。 | [5971c986-9d39-409c-a6f8-1385b1f690ef](https://docs.microsoft.com/microsoft-365-app-certification/azure/5971c986-9d39-409c-a6f8-1385b1f690ef) |
>| Sites.ReadWrite.All | delegated | 应用程序数据库中不存储任何数据。 | 获取SharePoint、库和文件。 将文件保存到SharePoint列表中。 | [5971c986-9d39-409c-a6f8-1385b1f690ef](https://docs.microsoft.com/microsoft-365-app-certification/azure/5971c986-9d39-409c-a6f8-1385b1f690ef) |
>| User.Read | delegated | 应用程序数据库中不存储任何数据。 | 为用户获取SharePoint网站、OneDrive和组网站。 | [5971c986-9d39-409c-a6f8-1385b1f690ef](https://docs.microsoft.com/microsoft-365-app-certification/azure/5971c986-9d39-409c-a6f8-1385b1f690ef) |

#### <a name="data-access-using-other-microsoft-apis"></a>使用其他 Microsoft API 进行数据访问

基于组织构建的应用和外接程序Microsoft 365除 Microsoft Graph 外的其他 Microsoft API 来收集或处理 OII (组织) 。 列出除 Microsoft API Graph此应用使用的任何 Microsoft API。

>| **API** |  **是否收集 OII？** |  **收集哪些 OII？** | **收集 OII 的理由？** | **是否存储 OII？** | **存储 OII 的理由** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| Exchange - EWS。AccessAsUser.All | 否 |  |  |  |  |
>| Exchange - Mail.ReadWrite | 否 |  |  |  |  |
>| Exchange - MailboxSettings.ReadWrite | 否 |  |  |  |  |
>| SharePoint - AllSites.Manage | 否 |  |  |  |  |
>| SharePoint - AllSites.Write | 否 |  |  |  |  |
>| SharePoint - MyFiles.Write | 否 |  |  |  |  |
>| SharePoint - User.Read.All | 否 |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>非Microsoft 服务使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>不Microsoft 服务非活动。



#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或最终用户可识别信息 (EUII) 是否显示在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>iGlobe 收集数据以有效运行，并提供我们的产品和服务的最佳体验。 对于许可：为管理组织&#8217;许可帐户收集的数据，例如当你部署免费外接程序、创建试用订阅或购买订阅时。 收集以下信息。 出于财务目的：公司名称和地址 订阅的用户：用户名和电子邮件


#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>所有应用程序数据都位于客户自己的租户上，由租户管理员作为客户租户中的所有其他服务Office 365。 加载项中未存储任何应用程序数据。 新式外接程序在沙盒浏览器中运行，&#8220;进程外&#8221;。 加载项只能访问用户正使用的数据。 它通过使用数据与用户数据Microsoft 服务。

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

下面将显示[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35747' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35747" target="_blank">在新建选项卡中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>标识信息

此信息由 iGlobe 提供有关此应用如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件的信息。

| **Information** | **响应** |
|:----------------|:-------------|
| 你是否与 Microsoft 标识平台 (Azure AD) ？  | 是 |
| 您是否已审阅并遵循了 Microsoft 标识平台清单中列出的所有适用最佳做法？  | 是 |
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
