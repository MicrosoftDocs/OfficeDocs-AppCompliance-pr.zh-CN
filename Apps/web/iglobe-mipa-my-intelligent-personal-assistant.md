---
title: MIPA 的应用程序信息 - iGlobe 个人助理我的智能数据
ms.author: elmalova
author: elenamalova
ms.date: 06/22/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: MIPA 的所有可用安全性和合规性信息 - 我的智能 个人助理、其数据处理策略、Microsoft Cloud App Security 应用程序目录信息和 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 684cd61aec216db5bc60bb92abd2d93963c2138a
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 09/12/2021
ms.locfileid: "59279387"
---
# <a name="mipa---my-intelligent-personal-assistant"></a>MIPA - 我的智能个人助理

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2021 年 6 月 22 日</p>

* <a href="https://appsource.microsoft.com/product/web-apps/17859280.mipa" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

iGlobe 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | MIPA - 我的智能个人助理 |
| ID | 17859280.mipa |
| 合作伙伴公司名称 | iGlobe |
| 合作伙伴网站的 URL | [https://www.iglobecrm.com](https://www.iglobecrm.com) |
| 隐私策略的 URL | [https://instassl.iglobecrm.com/legal-information](https://instassl.iglobecrm.com/legal-information) |
| 使用条款 URL | [https://mipa.iglobe.dk/EULA](https://mipa.iglobe.dk/EULA) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

iGlobe 提供了此信息，这些信息与此应用程序如何收集和存储组织数据以及组织将拥有对应用收集的数据的控制有关。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph所需的](https://docs.microsoft.com/graph/permissions-reference)任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD 应用 ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | delegated | 应用程序数据库中不存储任何数据。 | 读取和更新日历完整部分 | e854ea05-68ab-4204-如果为 db4a784fb4d8 |
>| Contacts.ReadWrite | delegated | 应用程序数据库中不存储任何数据。 | 读取和更新日历完整部分 | e854ea05-68ab-4204-如果为 db4a784fb4d8 |
>| Directory.AccessAsUser.All | delegated | 应用程序数据库中不存储任何数据。 | 读取、更新、创建平移器任务、读取用户的最近文件和共享文件。 检查用户是否同意并有权访问使用 API。 | e854ea05-68ab-4204-如果为 db4a784fb4d8 |
>| Directory.ReadWrite.All | delegated | 应用程序数据库中不存储任何数据。 | 读取、更新、创建平移器任务、读取用户的最近文件和共享文件、SharePoint列表、库和文件。 将文件保存到SharePoint列表中。 | e854ea05-68ab-4204-如果为 db4a784fb4d8 |
>| Files.ReadWrite.All | delegated | 应用程序数据库中不存储任何数据。 | 读取、更新、创建平移器任务、读取用户的最近文件和共享文件、SharePoint列表、库和文件。 将文件保存到SharePoint列表中。 | e854ea05-68ab-4204-如果为 db4a784fb4d8 |
>| Group.Read.All | delegated | 应用程序数据库中不存储任何数据。 | 读取、更新、创建平移器任务、读取用户的最近文件和共享文件、SharePoint列表、库和文件。 将文件保存到SharePoint列表中。 | e854ea05-68ab-4204-如果为 db4a784fb4d8 |
>| Group.ReadWrite.All | delegated | 应用程序数据库中不存储任何数据。 | 读取、更新、创建平移器任务、读取用户的最近文件和共享文件、SharePoint列表、库和文件。 将文件保存到SharePoint列表中。 与 iGlobe CRM Office 365 | e854ea05-68ab-4204-如果为 db4a784fb4d8 |
>| Mail.ReadWrite | delegated | 应用程序数据库中不存储任何数据。 | 读取和更新已标记的邮件 | e854ea05-68ab-4204-如果为 db4a784fb4d8 |
>| MailboxSettings.ReadWrite | delegated | 应用程序数据库中不存储任何数据。 | 读取和更新 calender 整个、读取和更新标记的邮件、读取和更新Outlook 微软待办整个 | e854ea05-68ab-4204-如果为 db4a784fb4d8 |
>| Tasks.ReadWrite | delegated | 应用程序数据库中不存储任何数据。 | 读取并更新 calender 的整个内容、读取Outlook更新为 Do Entreies | e854ea05-68ab-4204-如果为 db4a784fb4d8 |
>| User.Read | delegated | 应用程序数据库中不存储任何数据。 | 读取并更新 calender 的整个内容、读取Outlook更新为 Do Entreies | e854ea05-68ab-4204-如果为 db4a784fb4d8 |
>| User.Read.All | delegated | 应用程序数据库中不存储任何数据。 | 读取和更新日历完整，读取和更新Outlook日历、读取、更新、创建平移器任务 | e854ea05-68ab-4204-如果为 db4a784fb4d8 |
>| User.ReadBasic.All | delegated | 应用程序数据库中不存储任何数据。 | 读取和更新日历完整，读取和更新Outlook日历、读取、更新、创建平移器任务 | e854ea05-68ab-4204-如果为 db4a784fb4d8 |
>| User.ReadWrite | delegated | 应用程序数据库中不存储任何数据。 | 读取并更新 calender 的整个内容、读取Outlook更新为 Do Entreies | e854ea05-68ab-4204-如果为 db4a784fb4d8 |
>| email | delegated | 应用程序数据库中不存储任何数据。 | 允许应用读取用户的主电子邮件地址 ( SSO) 。 | e854ea05-68ab-4204-如果为 db4a784fb4d8 |
>| offline_access | delegated | 应用程序数据库中不存储任何数据。 | 允许应用查看和更新你向它提供访问权限的数据，即使用户当前没有使用该应用。 这不会为应用授予针对 SSO (任何其他) 。 | e854ea05-68ab-4204-如果为 db4a784fb4d8 |
>| openid | delegated | 应用程序数据库中不存储任何数据。 | 允许用户使用工作或学校帐户登录应用，并允许应用查看 SSO (的基本) 。 | e854ea05-68ab-4204-如果为 db4a784fb4d8 |
>| 个人资料 | delegated | 应用程序数据库中不存储任何数据。 | 读取和更新日历完整，读取和更新Outlook日历、读取、更新、创建平移器任务 | e854ea05-68ab-4204-如果为 db4a784fb4d8 |

#### <a name="data-access-using-other-microsoft-apis"></a>使用其他 Microsoft API 进行数据访问

基于组织构建的应用和Microsoft 365可以使用除 Microsoft Graph 外的其他 Microsoft API 来收集或处理 OII (组织) 。 列出此应用使用的任何 Microsoft GRAPH Microsoft API。

>| **API** |  **是否收集 OII？** |  **收集哪些 OII？** | **收集 OII 的理由？** | **是否存储 OII？** | **存储 OII 的理由** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| Exchange - Calendars.ReadWrite.All | 否 |  |  |  |  |
>| Exchange - EWS。AccessAsUser.All | 否 |  |  |  |  |
>| Exchange - Mail.Read | 否 |  |  |  |  |
>| Exchange - Mail.ReadWrite.All | 否 |  |  |  |  |
>| Exchange - MailboxSettings.Read | 否 |  |  |  |  |
>| Exchange - MailboxSettings.ReadWrite | 否 |  |  |  |  |
>| Exchange - Tasks.ReadWrite | 否 |  |  |  |  |
>| SharePoint - MyFiles.Read | 否 |  |  |  |  |
>| SharePoint - MyFiles.Write | 否 |  |  |  |  |

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

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35699' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35699" target="_blank">在新建选项卡中查看</a>

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
| 应用的静态注册权限是否准确反映应用将动态和增量请求的权限？ | 否 |
| 你的应用是否支持多租户？ | 是 |
| 你的应用是否具有机密客户端？ | 是 |
| 你是否拥有为应用注册的所有 (统一) URI？ | 是 |
| 你的应用是否公开任何 Web API？ | 否 |
| 你的应用是否使用预览 API？ | 否 |
| 你的应用是否使用已弃用 API？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
