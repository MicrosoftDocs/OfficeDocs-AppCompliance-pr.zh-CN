---
title: LawToolBox 期限 &amp; 事项管理的应用程序信息 - Outlook LawToolBox.com Inc.
ms.author: elmalova
author: elenamalova
ms.date: 10/07/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: LawToolBox 期限事项管理的所有可用安全性和合规性信息 - Outlook、其数据处理策略、Microsoft Cloud App Security 应用程序目录信息以及 CSA STAR 注册表中的安全 &amp; /合规性信息。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: a68d1a5f726e097e8a22639ac15420fc801da3b4
ms.sourcegitcommit: 1d47df35430334cfc0c60f7ea0b62392b99b7cbf
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 10/13/2021
ms.locfileid: "60285972"
---
# <a name="lawtoolbox-deadlines-amp-matter-management---outlook"></a>LawToolBox 期限 &amp; 事项管理 - Outlook

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2021 年 10 月 7 日</p>

* <a href="https://appsource.microsoft.com/product/office/WA104120953" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

LawToolBox.com Inc. 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | LawToolBox 期限 &amp; 事项管理 - Outlook |
| ID | WA104120953 |
| Office 365支持的客户端 | Outlook 2013 或更高版本，Windows Mac Outlook 2016 或更高版本，Outlook 网页版 |
| 合作伙伴公司名称 | LawToolBox.com Inc. |
| 合作伙伴网站的 URL | [https://www.lawtoolbox.com](https://www.lawtoolbox.com) |
| 隐私策略的 URL | [https://www.lawtoolbox.com/privacy-policy/](https://www.lawtoolbox.com/privacy-policy/) |
| 使用条款 URL | [https://www.lawtoolbox.com/customersupport/2019/LawToolBox_...](https://www.lawtoolbox.com/customersupport/2019/LawToolBox_End_User_License_Agreement_and_SLA_LAWTOOLBOX_2019_APR.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

此信息由 LawToolBox.com Inc. 提供，这些信息与此应用程序如何收集和存储组织数据以及您的组织将拥有对应用收集的数据的控制有关。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph所需的](https://docs.microsoft.com/graph/permissions-reference)任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.Read | delegated | 此权限受限，&#8217;他们已有权访问其日历的联系人&#8211;我们使用它来允许用户检索其自己的日历信息 | [可选]读取用户的日历。 | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Calendars.ReadWrite | delegated | 此权限受限，&#8217;他们有权访问的联系人&#8211;我们使用它来允许用户检索自己的日历信息并写入日历 | 在用户的日历中创建日历邀请。 | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Calendars.ReadWrite.Shared | delegated | 此权限受限，&#8217;他们已有权访问其日历的联系人&#8211;我们使用它来允许用户检索其自己的日历信息 | 创建共享日历的日历邀请。 | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Contacts.ReadWrite | delegated | 此权限将限制访问&#8217;已有权访问的联系人的用户。  我们使用此权限允许用户搜索其 O365 联系人并将其添加到 LawToolBox &#8211;我们不会自动添加任何联系人 (如果您不希望使用此功能，并且可以手动添加联系人，则可能会撤消此操作 | [Optional]- 读取用户联系人，将用户从联系人列表连接到组。 | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Contacts.ReadWrite.Shared | delegated | 我们使用此权限允许用户搜索共享的 O365 联系人并添加到 LawToolBox &#8211;我们不会自动添加任何联系人 | [Optional]- 读取用户共享联系人，以提供与案例相关的联系人列表。 | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Directory.AccessAsUser.All | delegated | 我们在管理门户中使用 从 O365 租户检索要添加到帐户的用户列表 | [可选]作为用户读取组和用户信息。 | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Directory.ReadWrite.All | delegated | 我们在管理门户中使用 从 O365 租户检索要添加到帐户的用户列表 | [可选]作为用户读取组和用户信息。 | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Files.Read | delegated | 这允许外接程序读取和列出用户已有权访问的用户文件 | [可选]读取用户OneDrive。 | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Files.Read.All | delegated | 我们使用此权限读取和列出用户已有权访问的用户文件 | [Optional]-Read user's OneDrive。 | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Files.ReadWrite | delegated | 我们读取会议Teams、组OneDrive文件 (如果撤销，将阻止我们的 addin 在应用或应用中列出重要)  | [Optional]-Read and modify files in a user's OneDrive. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Files.ReadWrite.All | delegated | 我们读取会议Teams、组OneDrive文件 (如果撤销，它将阻止 LTB 在应用或应用中列出重要) 。  用户只能使用 addin 读取和列出用户已有权访问的用户文件 | [可选]读取/写入用户OneDrive与"事件"关联的文件。 | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Group.ReadWrite.All | delegated | GroupID、GroupName、GroupEmail | 我们为系统中创建的每个事项创建一个组。 这可帮助用户将与重要信息存储到组，而组又将其数据保存到其自己的租户中。 | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Mail.Read | delegated | 我们使用此权限阅读 Outlook 外接程序中的 PACER 电子邮件以自动打开这一事项，并读取电子邮件中的联系人以添加到我们的联系人系统 | [可选][InProgress]阅读用户的电子邮件了解事项。 | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Mail.ReadWrite | delegated | 我们使用此权限阅读 Outlook 外接程序中的 PACER 电子邮件以自动打开这一事项，并读取电子邮件中的联系人以添加到我们的联系人系统 | [可选][InProgress]读取/写入用户的电子邮件。 | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Mail.ReadWrite.Shared | delegated | 我们使用此权限阅读 Outlook 外接程序中的 PACER 电子邮件以自动打开这一事项，并读取电子邮件中的联系人以添加到我们的联系人系统 | [可选][InProgress]读取/写入用户的电子邮件。 | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Mail.Send | delegated | 我们使用此发送电子邮件作为用户，以允许用户仅向自己发送系统中已有权访问的数据的报告 | [可选][InProgress]以用户用户发送电子邮件截止时间。 | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Tasks.ReadWrite.Shared | delegated | 此权限被限制访问用户&#8217;他们有权访问的任务&#8211;我们使用它来允许用户检索和更新自己的任务信息。 | [Optional]-[InProgress] Read Write Deadlines as Task for users. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| User.Read | delegated | 用于建议将最近的联系人添加到会议或联系人 | 读取用户的信息。 | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| User.ReadWrite | delegated | 用于建议将最近的联系人添加到会议或联系人 | 读取/写入用户的信息。 | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| User.ReadWrite.All | delegated | 这是读取 Teams API、Teams日历事件、创建频道Teams文件共享功能所必需的 | 读取/写入用户的信息。 | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| email | delegated | Email、Office365 UserID、ObjectID、TenantID。 | 读取用户的电子邮件地址。 | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| 个人资料 | delegated | 这是 SSO 身份验证所必需的 - 我们还使用此权限检索保存在 M365 租户上的图像和名称以显示，以便用户知道它们位于正确的工具箱中 | 读取用户配置文件信息。 | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |


#### <a name="non-microsoft-services-used"></a>非Microsoft 服务使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>不Microsoft 服务非活动。



#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或 EUII (最终用户可识别) 是否显示在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>调试日志中的用户电子邮件、用户 ID、AccessToken、组信息

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>我们保留案例记录，除非收到删除数据的请求。

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

下面将显示[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/" target="_blank">在新建选项卡中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>标识信息

此信息由 LawToolBox.com Inc. 提供，用于说明此应用如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件。

| **Information** | **响应** |
|:----------------|:-------------|
| 是否与 Microsoft 标识平台 (Azure AD) ？  | 是 |
| 您是否已审阅并遵循了 Microsoft 标识平台 集成清单中列出的所有适用最佳做法？  | 是 |
| 你的应用是否使用 MSAL (Microsoft 身份验证库) 进行身份验证？ | 是 |
| 你的应用是否支持条件访问策略？ | 是 |
| 列出支持的策略类型 | 为了更好地控制，管理员可以实现应用权限 |
| 应用是否请求方案最小特权权限？ | 是 |
| 应用的静态注册权限是否准确反映应用将动态和增量请求的权限？ | 是 |
| 你的应用是否支持多租户？ | 是 |
| 你的应用是否具有机密客户端？ | 否 |
| 你是否拥有为应用注册的所有 (统一) URI？ | 是 |
| 对于你的应用，应避免使用什么？ | ,<br/>- OAuth2 隐式Flow，除非 SPA 需要<br/> |
| 你的应用是否公开任何 Web API？ | 否 |
| 你的应用是否使用预览 API？ | 否 |
| 你的应用是否使用已弃用 API？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
