---
title: 由一台由一台由一台或多万台用于开发应用程序的系统信息
ms.author: elmalova
author: elenamalova
ms.date: 08/03/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: 所有 Available security and compliance information for 一切 Available security and compliance information for 一切，其数据处理策略、Microsoft Cloud App Security应用程序目录信息，以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 8d3a04daba9ebcbcf435f46beb6313c22310fe22
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 10/16/2021
ms.locfileid: "60408977"
---
# <a name="pandadoc"></a>PandaDoc

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2021 年 7 月 19 日</p>

* <a href="https://teams.microsoft.com/l/app/769d6db6-6890-4f70-8088-5943fdeac3c5" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002927" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

由一些客户向 Microsoft 提供的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | PandaDoc |
| ID | WA200002927 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | PandaDoc |
| 合作伙伴网站的 URL | [https://www.pandadoc.com](https://www.pandadoc.com) |
| Teams信息页的 URL | [https://www.pandadoc.com](https://www.pandadoc.com) |
| 隐私策略的 URL | [https://www.pandadoc.com/privacy-notice/?utm_source=microso...](https://www.pandadoc.com/privacy-notice/?utm_source=microsoft-teams&amp;utm_medium=partner&amp;utm_campaign=2021-2-inbd-marketplace-websitevisit-pandadoc-privacy) |
| 使用条款 URL | [https://www.pandadoc.com/terms-of-use/](https://www.pandadoc.com/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

这些信息由一些用户提供，这些信息与此应用程序如何收集和存储组织数据以及组织对应用收集的数据的控制有关。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph所需的](https://docs.microsoft.com/graph/permissions-reference)任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Channel.ReadBasic.All | 两者 | 获取之前接收的每个命令的通道列表 ID，并获取每个通道的文件驱动器 ID。 | 不存储数据 | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| ChannelSettings.Read.All | 两者 | 获取之前接收的每个命令的通道列表 ID，并获取每个通道的文件驱动器 ID。  | 不存储数据 | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| ChannelSettings.ReadWrite.All | 两者 | 获取之前接收的每个命令的通道列表 ID，并获取每个通道的文件驱动器 ID。 | 不存储数据 | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| Directory.Read.All | 两者 | 若要获取团队 ID，Microsoft Teams用户是直接成员的用户。 之后，接收每个命令标识符的通道。 | 不存储数据。 | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| Directory.ReadWrite.All | 两者 | 若要获取团队 ID，Microsoft Teams用户是直接成员的用户。 之后，接收每个命令标识符的通道。 | 不存储数据。 | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| Files.Read | 两者 | For sso user from Tab (example - https://github.com/OfficeDev/msteams-tabs-sso-sample-nodejs) . 需要获取有权访问 Microsoft 令牌的用户Graph进一步获取用户文件。 | 不存储数据。 | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| Files.Read.All | 两者 | For sso user from Tab (example - https://github.com/OfficeDev/msteams-tabs-sso-sample-nodejs) . 需要获取有权访问 Microsoft 令牌的用户Graph进一步获取用户文件。 | 不存储数据。 | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| Files.Read.Selected | 两者 | For sso user from Tab (example - https://github.com/OfficeDev/msteams-tabs-sso-sample-nodejs) . 需要获取有权访问 Microsoft 令牌的用户Graph进一步获取用户文件。 | 不存储数据。 | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| Group.Read.All | 两者 | 获取之前接收的每个命令的通道列表 ID，并获取每个通道的文件驱动器 ID。 文档 - https://docs.microsoft.com/en-us/graph/api/channel-list?view=graph-rest-1.0&amp ;tabs=http | 不存储数据。 | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| Group.ReadWrite.All | 两者 | 获取之前接收的每个命令的通道列表 ID，并获取每个通道的文件驱动器 ID。 文档 - https://docs.microsoft.com/en-us/graph/api/channel-list?view=graph-rest-1.0&amp ;tabs=http | 不存储数据。 | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| Team.ReadBasic.All | 两者 | 获取团队 ID，Microsoft Teams用户是直接成员的用户。 之后，接收每个命令标识符的通道。 若要获取文件保管库 ID，首先需要获取用户输入的团队列表。 | 不存储数据。 | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| TeamSettings.Read.All | 两者 | 若要获取团队 ID，Microsoft Teams用户是直接成员的用户。 之后，接收每个命令标识符的通道。 若要获取文件保管库 ID，首先需要获取用户输入的团队列表。 | 不存储数据。 | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| TeamSettings.ReadWrite.All | 两者 | 或获取团队 ID Microsoft Teams用户是直接成员的用户。 之后，接收每个命令标识符的通道。 若要获取文件保管库 ID，首先需要获取用户输入的团队列表。 | 不存储数据。 | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| TeamsAppInstallation.ReadWriteSelfForTeam.All | 两者 | 需要将应用程序安装在团队中的用户上，在聊天中安装聊天机器人。 | 不存储数据。 | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| TeamsAppInstallation.ReadWriteSelfForUser.All | 两者 | 需要将应用程序安装在团队中的用户上，在聊天中安装聊天机器人。 | 不存储数据。 | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| User.Read | 两者 | For sso user from Tab (example - https://github.com/OfficeDev/msteams-tabs-sso-sample-nodejs) . 需要获取有权访问 Microsoft 令牌的用户Graph进一步获取用户文件。 | 不存储数据。 | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| User.Read.All | 两者 |  用于获取用户是Microsoft Teams直接成员的团队 ID。 之后，接收每个命令标识符的通道。 若要获取文件保管库 ID，首先需要获取用户输入的团队列表。 | 不存储数据。 | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| User.ReadWrite.All | 两者 |  用于获取用户是Microsoft Teams直接成员的团队 ID。 之后，接收每个命令标识符的通道。 若要获取文件保管库 ID，首先需要获取用户输入的团队列表。 | 不存储数据。 | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| email | 两者 | For sso user from Tab (example - https://github.com/OfficeDev/msteams-tabs-sso-sample-nodejs) . 需要获取有权访问 Microsoft 令牌的用户Graph进一步获取用户文件。 | 不存储数据。 | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| offline_access | 两者 | For sso user from Tab (example - https://github.com/OfficeDev/msteams-tabs-sso-sample-nodejs) . 需要获取有权访问 Microsoft 令牌的用户Graph进一步获取用户文件。 | 不存储数据。 | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| openid | 两者 | For sso user from Tab (example - https://github.com/OfficeDev/msteams-tabs-sso-sample-nodejs) . 需要获取有权访问 Microsoft 令牌的用户Graph进一步获取用户文件。 | 不存储数据。 | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| 个人资料 | 两者 | For sso user from Tab (example - https://github.com/OfficeDev/msteams-tabs-sso-sample-nodejs) . 需要获取有权访问 Microsoft 令牌的用户Graph进一步获取用户文件。 | 不存储数据。 | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |

#### <a name="data-access-using-other-microsoft-apis"></a>使用其他 Microsoft API 进行数据访问

基于组织构建的应用和加载项Microsoft 365除 Microsoft Graph 外的其他 Microsoft API 来收集或处理 OII (组织) 。 列出除 Microsoft API Graph此应用使用的任何 Microsoft API。

>| **API** |  **是否收集 OII？** |  **收集哪些 OII？** | **收集 OII 的理由？** | **是否存储 OII？** | **存储 OII 的理由** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| 所创建 Api | 否 |  |  |  |  |
>| MS Graph | 否 |  |  |  |  |
>| Elementor | 否 |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>非Microsoft 服务已使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>不Microsoft 服务非活动。

#### <a name="data-access-via-bots"></a>通过机器人访问数据

如果此应用程序包含机器人或消息扩展，则它可以访问最终用户可识别信息 (EUII) ：名单 (名字、姓氏、显示名称、电子邮件地址) （团队中任何团队成员的姓名、姓氏、电子邮件地址) 或添加到其中聊天）。 此应用是否使用了此功能？

>无法访问 EUII。


#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或 EUII (最终用户可识别) 是否显示在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>应用程序遥测或日志中不显示 OII 或 EUII。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>我们的供应商协议解决了美国和供应商在数据隐私和安全性方面各自的义务，我们每年对重要供应商进行安全/隐私审查。

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

下面将显示[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/21283' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/21283" target="_blank">在新建选项卡中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>标识信息

这些信息由一些由一些用户提供，这些信息是有关此应用如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件的。

| **Information** | **响应** |
|:----------------|:-------------|
| 是否与 Microsoft 标识平台 (Azure AD) ？  | 是 |
| 您是否已查看并遵循了 Microsoft 标识平台 清单中列出的所有适用最佳做法？  | 否 |
| 你的应用是否使用 MSAL (Microsoft 身份验证库) 进行身份验证？ | 否 |
| 你的应用是否支持条件访问策略？ | 否 |
| 应用是否请求方案最小特权权限？ | 是 |
| 应用的静态注册权限是否准确反映应用将动态和增量请求的权限？ | 是 |
| 你的应用是否支持多租户？ | 否 |
| 你的应用是否具有机密客户端？ | 否 |
| 你是否拥有为应用注册的所有 (统一) URI？ | 是 |
| 对于你的应用，应避免使用什么？ | - 通配符重定向 URI，<br/>- OAuth2 隐式Flow，除非 SPA 需要<br/> |
| 你的应用是否公开任何 Web API？ | 否 |
| 你的应用是否使用预览 API？ | 是 |
| 你的应用是否使用已弃用 API？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

