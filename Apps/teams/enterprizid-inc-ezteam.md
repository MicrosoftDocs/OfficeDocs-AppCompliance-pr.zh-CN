---
title: EnterprizID Inc 针对 ezTeam 的应用程序信息
ms.author: elmalova
author: elenamalova
ms.date: 03/18/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: ezTeam 的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 0c7b8022a8d629af9dbce0c2f97c381b4a15ca2b
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 10/16/2021
ms.locfileid: "60414658"
---
# <a name="ezteam"></a>ezTeam

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2021 年 2 月 24 日</p>

* <a href="https://teams.microsoft.com/l/app/b02f0b53-d3b7-4d53-85a9-f820f5ab33c7" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002546" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

EnterprizID Inc 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | ezTeam |
| ID | WA200002546 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | EnterprizID Inc |
| 合作伙伴网站的 URL | [https://enterprizid.com](https://enterprizid.com) |
| 应用程序Teams页的 URL | [https://enterprizid.com/discover/](https://enterprizid.com/discover/) |
| 隐私策略的 URL | [https://enterprizid.com/privacy-policy/](https://enterprizid.com/privacy-policy/) |
| 使用条款 URL | [https://enterprizid.com/terms-of-use/](https://enterprizid.com/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

此信息由 EnterprizID Inc 提供有关此应用程序如何收集和存储组织数据以及您的组织将拥有对应用收集的数据的控制的信息。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph所需的](https://docs.microsoft.com/graph/permissions-reference)任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| AppCatalog.Read.All | delegated | 应用程序列表Teams，以便我们可以在请求创建过程中Teams列表 | 不适用 | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| Application.Read.All | delegated | 允许此应用代表已登录的用户读取应用程序和服务主体。 | 不适用 | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| Directory.AccessAsUser.All | delegated | 允许应用以登录用户身份访问目录中的信息。 | 不适用 | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| Directory.Read.All | delegated | 允许应用程序读取组织目录中的数据，如用户、组和应用程序。 | Teams所有权和成员身份信息  | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| Directory.Read.All | 应用程序 | 允许应用在没有登录用户的情况下读取组织目录中的数据（如用户、组和应用）。 | 不适用 | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| Directory.ReadWrite.All | delegated | 允许应用读取和写入组织目录中的数据，例如用户和组 | 不适用 | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| Directory.ReadWrite.All | 应用程序 | 允许应用在没有登录用户的情况下读取和写入组织目录中的数据（如用户和组）。不允许删除用户或组。 | 不适用 | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| Files.Read.All | 应用程序 | 允许应用在没有登录用户的情况下读取所有网站集中的全部文件。 | 最终用户管理下的数据量（以 GB 为单位） | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| Group.Create | 应用程序 | 允许应用在没有登录用户的情况下创建组。 | 新的组属性详细信息。 | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| Group.Read.All | delegated | 允许应用代表登录用户列出组，并读取其属性以及所有组成员身份。 用于确定我的Teams  | 不适用 | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| Group.Read.All | 应用程序 | 允许应用在没有登录用户的情况下读取组属性和成员身份，并读取所有组的日历和对话。 | 不适用 | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| Group.ReadWrite.All | delegated | 允许应用代表登录用户创建组并读取所有组属性和成员身份。  | 不适用 | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| Group.ReadWrite.All | 应用程序 | 允许应用创建组、读取所有组属性和成员身份、更新组属性和成员身份以及删除组。 还允许应用读取和写入组日历和对话。  | 团队的最后一次活动。 | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| GroupMember.Read.All | 应用程序 | 允许应用在没有已登录用户的情况下读取所有组的成员身份和基本组属性。 | 不适用 | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| GroupMember.ReadWrite.All | 应用程序 | 允许应用在没有已登录用户的情况下列出组、读取基本属性、读取和更新应用有权访问的组的成员身份。 | 不适用 | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| People.Read.All | 应用程序 | 允许应用在没有登录用户的情况下读取任何用户的相关人的得分列表。 | 不适用 | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| Reports.Read.All | delegated | 允许应用代表已登录用户读取所有服务使用情况报告。 | 不适用 | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| Reports.Read.All | 应用程序 | 允许应用在没有登录用户的情况下读取所有服务使用情况报告。 | 每个组的上一个用户活动 | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| Sites.ReadWrite.All | 应用程序 | 允许应用在没有登录用户的情况下创建、读取、更新和删除所有网站集中的文档和列表项。 | 按每个用户的大小排名前 10 位的网站 | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| User.Read | delegated | 允许用户登录应用，并允许应用读取登录用户的个人资料。 | 不适用 | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| User.Read.All | 应用程序 | 允许应用在没有登录用户的情况下读取用户配置文件。 | 不适用 | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| offline_access | delegated | 允许应用查看和更新你向它提供访问权限的数据，即使用户当前没有使用该应用。  | 机器人通知 | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| openid | delegated | 允许用户以其工作或学校帐户登录应用，并允许应用查看用户的基本个人资料信息。 | 不适用 | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| 个人资料 | delegated | 允许应用查看用户的基本个人资料 (姓名、图片、用户名)  | 不适用 | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |


#### <a name="non-microsoft-services-used"></a>非Microsoft 服务已使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>不Microsoft 服务非活动。

#### <a name="data-access-via-bots"></a>通过机器人访问数据

如果此应用程序包含机器人或消息扩展，则它可以访问最终用户可识别信息 (EUII) ：名单 (名字、姓氏、显示名称、电子邮件地址) （团队中任何团队成员的姓名、姓氏、电子邮件地址) 或添加到其中聊天）。 此应用是否使用了此功能？

>| **访问 EUII 的理由？**  | **EUII 是否存储在数据库 () ？** | **存储 EUII 的理由** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| 欢迎消息、审批和证明流程通知 | 我们存储显示名称的标识  | 我们的工具允许最终用户为不同的服务项创建请求，并存储请求者显示名称。 请求将遵循审批工作流，我们需要审批者显示名称才能显示在请求详细信息中。 此外，在团队认证过程中的成员中，我们显示名称成员的列表。 |


#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或 EUII (最终用户可识别) 是否显示在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>EndUser 和组织全名。 保留和删除策略位于"保留 https://enterprizid.com/privacy-policy &quot; 你的个人数据"部分 &quot; 下

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>我们已在 Azure 中启用 privileged Access Management (PMA) ，并且具有连接到资源的特权标识确实使用 2FA 来增强安全性。 我们使用 Azure 作为云合作伙伴提供商，并受 Azure 的隐私和使用条款的约束

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>是

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

下面将显示[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36552' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36552" target="_blank">在新建选项卡中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>标识信息

此信息由 EnterprizID Inc 提供有关此应用程序如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件的信息。

| **Information** | **响应** |
|:----------------|:-------------|
| 是否与 Microsoft 标识平台 (Azure AD) ？  | 是 |
| 您是否已审阅并遵循了 Microsoft 标识平台 集成清单中列出的所有适用最佳做法？  | 是 |
| 你的应用是否使用 MSAL (Microsoft 身份验证库) 进行身份验证？ | 否 |
| 你的应用是否支持条件访问策略？ | 否 |
| 应用是否请求方案最小特权权限？ | 是 |
| 应用的静态注册权限是否准确反映应用将动态和增量请求的权限？ | 是 |
| 你的应用是否支持多租户？ | 是 |
| 你的应用是否具有机密客户端？ | 否 |
| 你是否拥有为应用注册的所有 (统一) URI？ | 是 |
| 对于你的应用，应避免使用什么？ | - 通配符重定向 URI，<br/>- OAuth2 隐式Flow，除非 SPA 需要<br/>- 资源所有者密码凭据 (ROPC) 流 |
| 你的应用是否公开任何 Web API？ | 是 |
| 您的权限模型是否仅在客户端应用程序收到正确同意时才允许呼叫成功？ | 是 |
| 你的应用是否使用预览 API？ | 是 |
| 你的应用是否使用已弃用 API？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

