---
title: Corel 的 MindManager 应用程序信息
ms.author: elmalova
author: elenamalova
ms.date: 06/01/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: MindManager 的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: f9cd3639b4c7abf8cb5472213e11faa879fb7917
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 10/16/2021
ms.locfileid: "60411086"
---
# <a name="mindmanager"></a>MindManager

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2021 年 5 月 3 日</p>

* <a href="https://teams.microsoft.com/l/app/cebe4a59-b076-47f3-a7bf-79148daf82f7" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002261" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

Corel 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | MindManager |
| ID | WA200002261 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | Corel |
| 合作伙伴网站的 URL | [https://www.mindmanager.com](https://www.mindmanager.com) |
| 隐私策略的 URL | [https://www.corel.com/en/corel-privacy-policy/](https://www.corel.com/en/corel-privacy-policy/) |
| 使用条款 URL | [https://www.mindjet.com/go/mmcloudterms](https://www.mindjet.com/go/mmcloudterms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

Corel 提供了此信息，这些信息与此应用程序如何收集和存储组织数据以及组织将拥有对应用收集的数据的控制有关。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph](https://docs.microsoft.com/graph/permissions-reference)所需的任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| ChannelMessage.Send | delegated | 有关在 MindManager 文件中所做的更改的信息，这些更改随后可以发布为消息 | 文件元数据、文件内容 - 对于文件浏览器，用户可以浏览文件以打开 MindManager (.mmap) 文件。 | [51e2b67d-9854-446a-8da1-cdd89ef0b987](https://docs.microsoft.com/microsoft-365-app-certification/azure/51e2b67d-9854-446a-8da1-cdd89ef0b987) |
>| Chat.Send | delegated | 有关在 MindManager 文件中所做的更改的信息，这些更改随后可以发布为消息 | 文件元数据、文件内容 - 对于文件浏览器，用户可以浏览文件以打开 MindManager (.mmap) 文件。 | [51e2b67d-9854-446a-8da1-cdd89ef0b987](https://docs.microsoft.com/microsoft-365-app-certification/azure/51e2b67d-9854-446a-8da1-cdd89ef0b987) |
>| Files.ReadWrite | delegated | 网站列表、文件夹列表、文件元数据、文件内容 - 对于文件浏览器，用户可以浏览文件以打开 MindManager (.mmap) 文件。 | - 配置文件数据：标识用户并显示其配置文件 - 文件内容：在共同编辑会话期间 (对 MindManager .mmap 文件进行实时协作)  | [51e2b67d-9854-446a-8da1-cdd89ef0b987](https://docs.microsoft.com/microsoft-365-app-certification/azure/51e2b67d-9854-446a-8da1-cdd89ef0b987) |
>| Sites.ReadWrite.All | delegated | 网站列表、文件夹列表、文件元数据、文件内容 - 对于文件浏览器，用户可以浏览文件以打开 MindManager (.mmap) 文件。 | 文件内容：在共同编辑会话期间 (对 MindManager .mmap 文件进行实时协作)  | [51e2b67d-9854-446a-8da1-cdd89ef0b987](https://docs.microsoft.com/microsoft-365-app-certification/azure/51e2b67d-9854-446a-8da1-cdd89ef0b987) |
>| User.Read | delegated | 配置文件数据：标识用户并显示其配置文件 | 配置文件数据：标识用户并显示其配置文件 | [51e2b67d-9854-446a-8da1-cdd89ef0b987](https://docs.microsoft.com/microsoft-365-app-certification/azure/51e2b67d-9854-446a-8da1-cdd89ef0b987) |
>| offline_access | delegated | 这样，我们以后可以代表用户将文件保存回其原始位置（如果需要）。 | 文件内容：在共同编辑会话期间 (对 MindManager .mmap 文件进行实时协作)  | [51e2b67d-9854-446a-8da1-cdd89ef0b987](https://docs.microsoft.com/microsoft-365-app-certification/azure/51e2b67d-9854-446a-8da1-cdd89ef0b987) |


#### <a name="non-microsoft-services-used"></a>非Microsoft 服务已使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>| **所有非 Microsoft 服务 OII 将转移到** |  **转移了哪些 OII？** | **转移 OII 的理由？** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Amazon Web Services | 组织名称、组织域 | 组织需要在我们的应用程序基础结构中设置帐户，以在 Teams |

#### <a name="data-access-via-bots"></a>通过机器人访问数据

如果此应用程序包含机器人或消息扩展，则它可以访问最终用户可识别信息 (EUII) ：名单 (名字、姓氏、显示名称、电子邮件地址) （团队中任何团队成员的姓名、姓氏、电子邮件地址) 或添加到其中聊天）。 此应用是否使用了此功能？

>无法访问 EUII。


#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或 EUII (最终用户可识别) 是否显示在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>应用程序遥测或日志中不显示 OII 或 EUII。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>此处介绍： https://www.mindjet.com/go/mmcloudterms

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

下面将显示[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/38778' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/38778" target="_blank">在新建选项卡中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>标识信息

Corel 已提供有关此应用如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件的信息。

| **Information** | **响应** |
|:----------------|:-------------|
| 是否与 Microsoft 标识平台 (Azure AD) ？  | 是 |
| 您是否已审阅并遵循了 Microsoft 标识平台 集成清单中列出的所有适用最佳做法？  | 是 |
| 你的应用是否使用 MSAL (Microsoft 身份验证库) 进行身份验证？ | 否 |
| 你的应用是否支持条件访问策略？ | 否 |
| 应用是否请求方案最小特权权限？ | 是 |
| 应用的静态注册权限是否准确反映应用将动态和增量请求的权限？ | 是 |
| 你的应用是否支持多租户？ | 是 |
| 你的应用是否具有机密客户端？ | 是 |
| 你是否拥有为应用注册的所有 (统一) URI？ | 是 |
| 对于你的应用，应避免使用什么？ | - 通配符重定向 URI，<br/>- OAuth2 隐式Flow，除非 SPA 需要<br/>- 资源所有者密码凭据 (ROPC) 流 |
| 你的应用是否公开任何 Web API？ | 是 |
| 您的权限模型是否仅在客户端应用程序收到正确同意时才允许呼叫成功？ | 是 |
| 你的应用是否使用预览 API？ | 否 |
| 你的应用是否使用已弃用 API？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

