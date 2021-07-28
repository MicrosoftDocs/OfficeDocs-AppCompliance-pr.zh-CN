---
title: iGlobe Office 365 Planner 的 iPlanner 报告工具的应用程序信息
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: certified
description: 适用于 Office 365 Planner 的 iPlanner 报告工具的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security 应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 3591c67721188d8dc70bf4f2cf0e34bdb9ffc506
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 07/22/2021
ms.locfileid: "53526048"
---
# <a name="iplanner-reporting-tool-for-office-365-planner"></a>适用于 Planner 的 iPlanner Office 365工具

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>开发人员上次更新时间：2019 年 12 月 16 日</p>

* <a href="https://appsource.microsoft.com/product/office/WA104380686" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

iGlobe 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | 适用于 Planner 的 iPlanner Office 365工具 |
| ID | WA104380686 |
| Office 365支持的客户端 | Excel 2016 Mac 上的 Windows、Excel web 版、Excel 2016 或更高版本上的 Windows 或更高版本 |
| 合作伙伴公司名称 | iGlobe |
| 合作伙伴网站的 URL | [https://iglobecrm.com/](https://iglobecrm.com/) |
| 隐私策略的 URL | [https://instassl.iglobecrm.com/legal-information](https://instassl.iglobecrm.com/legal-information) |
| 使用条款 URL | [https://mipa.iglobe.dk/EULA](https://mipa.iglobe.dk/EULA) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

此信息由 iGlobe 提供，用于了解此应用如何收集和存储组织数据，以及组织对应用收集的数据的控制。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph所需的](https://docs.microsoft.com/graph/permissions-reference)任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD 应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | delegated | 应用程序数据库中不存储任何数据。 | 在用户创建日历条目&#8217;任务截止日期的日历。 | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Directory.AccessAsUser.All | delegated | 应用程序数据库中不存储任何数据。 | 检查用户是否同意并有权访问使用 API。 | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Directory.ReadWrite.All | delegated | 应用程序数据库中不存储任何数据。 | 若要获取计划工具任务Outlook 微软待办，请标记电子邮件并更新它们。 创建新的 Planner 任务。 | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Files.ReadWrite.All | delegated | 应用程序数据库中不存储任何数据。 | 以附件形式访问文件，将文件上载到任务。 | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Group.Read.All | delegated | 应用程序数据库中不存储任何数据。 | 获取计划列表并更新任务。 | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Group.ReadWrite.All | delegated | 应用程序数据库中不存储任何数据。 | 若要获取规划器任务并添加新任务，请更新存储桶和线条。 | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Mail.Read | delegated | 应用程序数据库中不存储任何数据。 | User.Read，用于获取计划工具任务Outlook 微软待办标记的电子邮件并更新它们。 创建新的 Planner 任务 | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Mail.ReadWrite | delegated | 应用程序数据库中不存储任何数据。 | 显示邮件并发送邮件。 | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Mail.ReadWrite.All | delegated | 应用程序数据库中不存储任何数据。 | 从所选邮件获取邮件主题。 允许应用从选定的电子邮件获取信息，从而允许将说明字段复制到任务说明中，并允许将附件从邮件或邮件本身保存到任务。 发送通知。 | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Tasks.ReadWrite | delegated | 应用程序数据库中不存储任何数据。 | 若要使登录用户Outlook 微软待办 User.Read，若要获取计划工具任务Outlook 微软待办标记的电子邮件并更新它们。 创建新的 Planner 任务。 | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| User.Read | delegated | 应用程序数据库中不存储任何数据。 | 登录并读取用户个人资料 | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |


#### <a name="non-microsoft-services-used"></a>非Microsoft 服务使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>不Microsoft 服务非活动。



#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或 EUII (最终用户可识别) 是否显示在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>iGlobe 收集数据以有效运行，并提供我们的产品和服务的最佳体验。 对于许可：为管理组织&#8217;许可帐户收集的数据，例如当你部署免费外接程序、创建试用订阅或购买订阅时。 收集以下信息。 
- 出于财务目的：公司名称和地址
- 订阅的用户：用户名和电子邮件

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>所有数据都位于客户自己的租户上。 不存储任何应用程序数据。 新式外接程序在沙盒浏览器中运行，&#8220;进程外&#8221;。 它通过使用数据与用户数据Microsoft 服务。 加载项只能访问用户正使用的数据。

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>不支持

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

下面将显示[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35699' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35699" target="_blank">在新建选项卡中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

