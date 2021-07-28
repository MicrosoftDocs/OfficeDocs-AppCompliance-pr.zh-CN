---
title: Adobe Sign 的应用程序信息（由 Adobe Systems Inc.
ms.author: elmalova
author: elenamalova
ms.date: 03/01/2021
ms.topic: article
ms.service: attestation
certification_type: certified
description: Adobe Sign 的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 98b936fd86d111e9bb6c194318dab50d115b6a28
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 07/22/2021
ms.locfileid: "53525916"
---
# <a name="adobe-sign"></a>Adobe Sign

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>开发人员上次更新时间：2021 年 3 月 1 日</p>

* <a href="https://teams.microsoft.com/l/app/0f56a9d1-f502-40f9-a9e8-816d7adbb68b" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381233" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

Adobe Systems Inc. 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | Adobe Sign |
| ID | WA104381233 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | Adobe Systems Inc. |
| 合作伙伴网站的 URL | [https://acrobat.adobe.com/us/en/sign.html](https://acrobat.adobe.com/us/en/sign.html) |
| "Teams应用程序信息"页的 URL | [https://helpx.adobe.com/sign/help/adobesign_microsoft_teams...](https://helpx.adobe.com/sign/help/adobesign_microsoft_teams.html) |
| 隐私策略的 URL | [https://www.adobe.com/privacy/policy.html](https://www.adobe.com/privacy/policy.html) |
| 使用条款 URL | [https://www.adobe.com/legal/terms.html](https://www.adobe.com/legal/terms.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

此信息由 Adobe Systems Inc. 提供，用于了解此应用如何收集和存储组织数据，以及组织将拥有对应用收集的数据的控制。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph所需的](https://docs.microsoft.com/graph/permissions-reference)任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD 应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Mail.ReadWrite | delegated | 填充附加的文档、发件人和收件人电子邮件以及电子邮件中的邮件内容到 Adobe sign 以发送进行签名。 这是为了节省用户在 Adobe Sign 中重新键入这些字段的时间。 签署协议后，我们将自动撰写一封新电子邮件，让用户发送电子邮件，通知其收件人交易已完成。 | Adobe Sign 将附件另存为临时文件，其有效期为 24 小时。 | [72d5ac5d-a427-408b-907d-72da3f33ddd1](https://docs.microsoft.com/microsoft-365-app-certification/azure/72d5ac5d-a427-408b-907d-72da3f33ddd1) |
>| People.Read | delegated | 若要在"发送供签名"体验中自动填充电子邮件地址，请键入一些初始字母，无需用户 &quot; &quot; 键入整个电子邮件。 | Adobe Sign 将仅存储协议中的收件人电子邮件和 displayName。 | [72d5ac5d-a427-408b-907d-72da3f33ddd1](https://docs.microsoft.com/microsoft-365-app-certification/azure/72d5ac5d-a427-408b-907d-72da3f33ddd1) |
>| User.Read | delegated | 要读取用户配置文件并基本上匹配其 (，他们的电子邮件和 userId) 我们的数据库，以便他们可以使用 Adobe Sign。 | 要读取用户配置文件并基本上匹配其 (，他们的电子邮件和 userId) 我们的数据库，以便他们可以使用 Adobe Sign。 | [72d5ac5d-a427-408b-907d-72da3f33ddd1](https://docs.microsoft.com/microsoft-365-app-certification/azure/72d5ac5d-a427-408b-907d-72da3f33ddd1) |
>| offline_access | delegated | 在当前令牌过期时刷新访问令牌。 例如，当用户在签名发送窗口中将其保持非活动状态的时间过长时，我们需要刷新新令牌以保持 &quot; &quot; 用户处于活动状态 | 在当前令牌过期时刷新访问令牌。 例如，当用户在签名发送窗口中，并且将其保持非活动状态的时间太长时，我们需要刷新新令牌以保持 &quot; &quot; 用户处于活动状态。 | [72d5ac5d-a427-408b-907d-72da3f33ddd1](https://docs.microsoft.com/microsoft-365-app-certification/azure/72d5ac5d-a427-408b-907d-72da3f33ddd1) |
>| openid | delegated | 电子邮件和 UserId。 登录以确保用户同意使用 Adobe Sign 应用的权限。  | 电子邮件是 Adobe Sign 中用户的唯一标识符。 我们存储电子邮件 ID，以便可以将该用户的所有活动映射到其 Adobe Sign 记录。  | [72d5ac5d-a427-408b-907d-72da3f33ddd1](https://docs.microsoft.com/microsoft-365-app-certification/azure/72d5ac5d-a427-408b-907d-72da3f33ddd1) |

#### <a name="data-access-using-other-microsoft-apis"></a>使用其他 Microsoft API 进行数据访问

基于组织构建的应用和加载项Microsoft 365除 Microsoft Graph 外的其他 Microsoft API 来收集或处理 OII (组织) 。 列出除 Microsoft API Graph此应用使用的任何 Microsoft API。

>| **API** |  **是否收集 OII？** |  **收集哪些 OII？** | **收集 OII 的理由？** | **是否存储 OII？** | **存储 OII 的理由** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| TeamsAPI | 不支持 |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>非Microsoft 服务使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>不Microsoft 服务非活动。

#### <a name="data-access-via-bots"></a>通过机器人访问数据

如果此应用程序包含机器人或消息扩展，则它可以访问最终用户可识别信息 (EUII) ：名单 (名字、姓氏、显示名称、电子邮件地址) （团队中任何团队成员的姓名、姓氏、电子邮件地址) 或添加到其中聊天）。 此应用是否使用了此功能？

>| **访问 EUII 的理由？**  | **EUII 是否存储在数据库 (中) ？** | **存储 EUII 的理由** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| 用于自定义聊天消息和身份验证 | UserPrincipalName、name、email 和 objectId | 我们存储此信息用于自定义异步响应和身份验证目的 |


#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或 EUII (最终用户可识别) 是否显示在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>我们的日志包含足以识别并解决客户问题的信息。 日志将保留 90 天，并且访问受到限制。 我们的数据库存储用户脱机时进行身份验证的哈希标识信息。 数据库保留策略自上次使用起 30 天

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>在我们的系统中，对于应用程序，我们没有任何客户管理员Microsoft Teams交互。

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>是

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

下面将显示[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/11641' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/11641" target="_blank">在新建选项卡中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>标识信息

此信息由 Adobe Systems Inc. 提供有关此应用如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件的信息。

| **Information** | **响应** |
|:----------------|:-------------|
| 你是否与 Microsoft 标识平台 (Azure AD) ？  | 是 |
| 您是否已查看并遵循了 Microsoft 标识平台 清单中列出的所有适用最佳做法？  | 是 |
| 你的应用是否使用 MSAL (Microsoft 身份验证库) 进行身份验证？ | 不支持 |
| 你的应用是否支持条件访问策略？ | 不支持 |
| 应用是否请求方案最小特权权限？ | 是 |
| 应用的静态注册权限是否准确反映应用将动态和增量请求的权限？ | 是 |
| 你的应用是否支持多租户？ | 是 |
| 你的应用是否具有机密客户端？ | 不支持 |
| 你是否拥有为应用注册的所有重定向统 (URI) URI？ | 是 |
| 对于你的应用，应避免使用什么？ | - 通配符重定向 URI，<br/>- OAuth2 隐式Flow，除非 SPA 需要<br/>- 资源所有者密码凭据 (ROPC) 流 |
| 你的应用是否公开任何 Web API？ | 是 |
| 您的权限模型是否仅在客户端应用程序收到正确同意时允许呼叫成功？ | 是 |
| 你的应用是否使用预览 API？ | 不支持 |
| 你的应用是否使用已弃用 API？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
