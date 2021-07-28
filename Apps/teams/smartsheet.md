---
title: Smartsheet 的应用程序信息
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Smartsheet 的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 3b6f823a27352d3623826cf09f97c9a2f560307a
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 07/22/2021
ms.locfileid: "53528298"
---
# <a name="smartsheet"></a>Smartsheet

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2019 年 12 月 16 日</p>

* <a href="https://teams.microsoft.com/l/app/f4d81e8e-4500-44c2-8328-9e06cbe037c5" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA104380975" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

Smartsheet 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | Smartsheet |
| ID | WA104380975 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | Smartsheet |
| 合作伙伴网站的 URL | [https://www.smartsheet.com](https://www.smartsheet.com) |
| "Teams应用程序信息"页的 URL | [https://help.smartsheet.com/articles/2476201-interact-with-...](https://help.smartsheet.com/articles/2476201-interact-with-smartsheet-items-in-microsoft-teams) |
| 隐私策略的 URL | [https://www.smartsheet/legal/privacy](https://www.smartsheet/legal/privacy) |
| 使用条款 URL | [https://Default 用户协议 https://www.smartsheet.com/.. ：。](https://Default User Agreement: https://www.smartsheet.com/legal/user-agreement) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

Smartsheet 提供了此信息，这些信息与此应用程序如何收集和存储组织数据以及您的组织将拥有对应用程序收集的数据的控制有关。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph所需的](https://docs.microsoft.com/graph/permissions-reference)任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD 应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| AppCatalog.ReadWrite.All | delegated | 无。 | 允许应用代表用户安装应用。 | [c68947ae-a07f-44ce-9a13-7b559251731d](https://docs.microsoft.com/microsoft-365-app-certification/azure/c68947ae-a07f-44ce-9a13-7b559251731d) |
>| Directory.Read.All | delegated | tenantId，用于检索要显示在 UI 中的信息。 | 允许我们读取此租户使用的应用，以便我们检查是否需要为它们安装应用。 | [c68947ae-a07f-44ce-9a13-7b559251731d](https://docs.microsoft.com/microsoft-365-app-certification/azure/c68947ae-a07f-44ce-9a13-7b559251731d) |
>| Group.Read.All | delegated | 用于邮件传递的 teamId/groupId。 | 允许应用读取有关组、 (Teams团队) 以及对话的基本信息。 | [c68947ae-a07f-44ce-9a13-7b559251731d](https://docs.microsoft.com/microsoft-365-app-certification/azure/c68947ae-a07f-44ce-9a13-7b559251731d) |
>| Group.ReadWrite.All | delegated | 用于邮件传递的 teamId/groupId。 | 允许应用在团队中启动新对话。 此权限还包括上述 Read.All 作用域，但我们出于技术原因也需要此作用域。 | [c68947ae-a07f-44ce-9a13-7b559251731d](https://docs.microsoft.com/microsoft-365-app-certification/azure/c68947ae-a07f-44ce-9a13-7b559251731d) |
>| User.Read.All | delegated | userId。 | 允许我们在身份验证过程中读取有关用户的基本信息。 | [c68947ae-a07f-44ce-9a13-7b559251731d](https://docs.microsoft.com/microsoft-365-app-certification/azure/c68947ae-a07f-44ce-9a13-7b559251731d) |
>| offline_access | delegated | refreshToken。 | 允许应用在使用应用时代表用户接收刷新令牌并刷新身份验证令牌。 | [c68947ae-a07f-44ce-9a13-7b559251731d](https://docs.microsoft.com/microsoft-365-app-certification/azure/c68947ae-a07f-44ce-9a13-7b559251731d) |

#### <a name="data-access-using-other-microsoft-apis"></a>使用其他 Microsoft API 进行数据访问

基于组织构建的应用和加载项Microsoft 365除 Microsoft Graph 外的其他 Microsoft API 来收集或处理 OII (组织) 。 列出除 Microsoft API Graph此应用使用的任何 Microsoft API。

>| **API** |  **是否收集 OII？** |  **收集哪些 OII？** | **收集 OII 的理由？** | **是否存储 OII？** | **存储 OII 的理由** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| Bot Framework API | 是 | 我们使用 Bot Framework API 将消息作为团队应用传递。 Smartsheet 存储 userId 信息，以跟踪智能表自动程序正在与谁交谈。 |  | 无 |  |

#### <a name="non-microsoft-services-used"></a>非Microsoft 服务使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>| **所有非Microsoft 服务 OII 将转移到** |  **转移了哪些 OII？** | **转移 OII 的理由？** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Smartsheet 将信息存储在由 E一ix 托管的生产数据中心环境和 AWS S3 中（我们将客户附件存储在专用加密桶中）中处于加密的处于非安全状态。 |  | 我们使用机器人框架 API 将消息作为 Teams 应用提供。 Smartsheet 存储 userId 信息，以跟踪智能表自动程序正在与谁交谈。 |

#### <a name="data-access-via-bots"></a>通过机器人访问数据

如果此应用程序包含机器人或消息扩展，则它可以访问最终用户可识别信息 (EUII) ：名单 (名字、姓氏、显示名称、电子邮件地址) （团队中任何团队成员的姓名、姓氏、电子邮件地址) 或添加到其中聊天）。 此应用是否使用了此功能？

>| **访问 EUII 的理由？**  | **EUII 是否存储在数据库 (中) ？** | **存储 EUII 的理由** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Smartsheet 使用它来帮助跟踪机器人在说话的人。 在初始身份验证流期间，我们在 Smartsheet 通知系统中为用户创建自动程序记录。 | 对于适用于自动Teams的 Smartsheet，我们存储来自 Teams 的用户电子邮件和 userId，以帮助跟踪机器人与谁交谈。  Smartsheet 存储 tenantIds 以帮助列出用户是目录中的一部分的组，以及用于邮件传递的 groupId。 |  |


#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或 EUII (最终用户可识别) 是否显示在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>不支持

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>Smartsheet 加密所有存储的用户信息，我们的管理员需要使用 2FA。 Smartsheet 作为无视图 SaaS 提供程序运行，默认情况下，我们不会查看客户选择上载或输入到平台的内容。

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>不支持

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

下面将显示[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/11934' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/11934" target="_blank">在新建选项卡中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

