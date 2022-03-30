---
title: 由 Chimu 软件捕获的 CatchEm 的应用程序信息
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 04/19/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: CatchEm 的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: c3773a334f6b0b778df0f26558517d87c6f7b10a
ms.sourcegitcommit: d8a3d237c4bd435183b9ce95c316b4d7ce9d7201
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 03/23/2022
ms.locfileid: "63772433"
---
# <a name="catchem"></a>CatchEm

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2021 年 3 月 27 日</p>

* <a href="https://teams.microsoft.com/l/app/fc686a41-3bd0-45b3-a56d-f278888fd694" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002639" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

Chimu 软件提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | CatchEm |
| ID | WA200002639 |
| Office 365客户端 | Microsoft Teams |
| 合作伙伴公司名称 | Chimu Software |
| 合作伙伴网站的 URL | [https://chimusoftware.com](https://chimusoftware.com) |
| 应用程序Teams页的 URL | [https://catchem.apps.chimusoftware.com/help](https://catchem.apps.chimusoftware.com/help) |
| 隐私策略的 URL | [https://www.chimusoftware.com/apps/catchem/privacy.html](https://www.chimusoftware.com/apps/catchem/privacy.html) |
| 使用条款 URL | [https://www.chimusoftware.com/apps/catchem/termsofuse.html](https://www.chimusoftware.com/apps/catchem/termsofuse.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

此信息由 Chimu 软件提供，与此应用程序如何收集和存储组织数据以及你的组织将拥有对应用收集的数据的控制有关。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph所需的](/graph/permissions-reference)任何 Microsoft 权限。

>| **权限**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Chat.ReadBasic | delegated | 若要确定应用程序用户的联系人，需要此权限。 AadObjectId：用于唯一标识用户。 TenantId：确定联系人是用户的内部联系人还是外部联系人。 DisplayName、GivenName、Surname：用于标识应用程序用户的联系人。 Email， UserPrincipalName： to help distinguish between contacts with the same name， and to allow &quot;click to chat&quot; functionality. 最新聊天 ID：启用 &quot;单击聊天&quot; 功能 | 若要确定应用程序用户的联系人，需要此权限。 AadObjectId：用于唯一标识用户。 TenantId：确定联系人是用户的内部联系人还是外部联系人。 DisplayName、GivenName、Surname：用于标识应用程序用户的联系人。 Email， UserPrincipalName： to help distinguish between contacts with the same name， and to allow &quot;click to chat&quot; functionality. 最新聊天 ID：启用 &quot;单击聊天&quot; 功能 | fc686a41-3bd0-45b3-a56d-f278888fd694 |
>| People.Read | delegated | 提高外部联系人数据的准确性。 DisplayName：用于标识应用程序用户的联系人。 | 提高外部联系人数据的准确性。 DisplayName：用于标识应用程序用户的联系人。 | fc686a41-3bd0-45b3-a56d-f278888fd694 |
>| Presence.Read.All | delegated | 联系人当前状态 | 不适用 | fc686a41-3bd0-45b3-a56d-f278888fd694 |
>| TeamsActivity.Send | 两者 | 在联系人状态更改时向用户发送通知 | 不适用 | fc686a41-3bd0-45b3-a56d-f278888fd694 |
>| TeamsAppInstallation.ReadWriteSelfForUser | delegated | 为应用程序启用自动更新 | 不适用 | fc686a41-3bd0-45b3-a56d-f278888fd694 |
>| User.Read | delegated | AadObjectId：用于唯一标识用户。 TenantId：确定联系人是用户的内部联系人还是外部联系人。 DisplayName、GivenName、Surname：用于标识应用程序用户的联系人。 电子邮件、IM 地址、UserPrincipalName： &quot;帮助区分同名的联系人并允许单击聊天&quot; 功能。 CompanyName、Country：Analytics。 AccountEnabled、DeletedDateTime：自动删除已禁用用户的用户数据 | AadObjectId：用于唯一标识用户。 TenantId：确定联系人是用户的内部联系人还是外部联系人。 DisplayName、GivenName、Surname：用于标识应用程序用户的联系人。 电子邮件、IM 地址、UserPrincipalName： &quot;帮助区分同名的联系人并允许单击聊天&quot; 功能。 CompanyName、Country：Analytics。 AccountEnabled、DeletedDateTime：自动删除已禁用用户的用户数据 | fc686a41-3bd0-45b3-a56d-f278888fd694 |
>| User.ReadBasic.All | delegated | 提高内部联系人数据的准确性。 AadObjectId：用于唯一标识用户。 TenantId：确定联系人是用户的内部联系人还是外部联系人。 DisplayName、GivenName、Surname：用于标识应用程序用户的联系人。 Email， UserPrincipalName： to help distinguish between contacts with the same name， and to allow &quot;click to chat&quot; functionality. | 提高内部联系人数据的准确性。 AadObjectId：用于唯一标识用户。 TenantId：确定联系人是用户的内部联系人还是外部联系人。 DisplayName、GivenName、Surname：用于标识应用程序用户的联系人。 Email， UserPrincipalName： to help distinguish between contacts with the same name， and to allow &quot;click to chat&quot; functionality. | fc686a41-3bd0-45b3-a56d-f278888fd694 |
>| offline_access | delegated | Graph安全令牌，以允许应用程序在联系人状态更改时通知并更新联系人列表（当用户未主动使用该应用程序时） | Graph安全令牌 | fc686a41-3bd0-45b3-a56d-f278888fd694 |


#### <a name="non-microsoft-services-used"></a>非Microsoft 服务已使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>不Microsoft 服务非活动。

#### <a name="data-access-via-bots"></a>通过机器人访问数据

如果此应用程序包含机器人或消息扩展，则它可以访问最终用户可识别信息 (EUII) ：名单 (名字、姓氏、显示名称、电子邮件地址) （团队中任何团队成员的姓名、姓氏、电子邮件地址) 或添加到其中聊天）。 此应用是否使用了此功能？

>| **访问 EUII 的理由？**  | **EUII 是否存储在数据库 (中) ？** | **存储 EUII 的理由** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| 邮件 &quot;功能&quot; 中的标记需使用联系人显示名称向应用程序用户显示 | 联系人显示名称 | 能够向应用程序用户显示联系人的姓名 |


#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或 EUII (最终用户可识别) 是否显示在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>应用程序遥测或日志中不显示 OII 或 EUII。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>不适用

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>是

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

下面将显示[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36911' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36911" target="_blank">在新建选项卡中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>标识信息

此信息由 Chimu 软件提供，用于了解此应用如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件。

| **Information** | **响应** |
|:----------------|:-------------|
| 是否与 Microsoft 标识平台 (Azure AD) ？  | 是 |
| 您是否已审阅并遵循了 Microsoft 标识平台 集成清单中列出的所有适用最佳做法？  | 是 |
| 你的应用是否使用 MSAL (Microsoft 身份验证库) 进行身份验证？ | 是 |
| 你的应用是否支持条件访问策略？ | 否 |
| 应用是否请求方案最小特权权限？ | 是 |
| 应用的静态注册权限是否准确反映应用将动态和增量请求的权限？ | 否 |
| 你的应用是否支持多租户？ | 是 |
| 你的应用是否具有机密客户端？ | 是 |
| 你是否拥有为应用注册的所有 (统一) URI？ | 是 |
| 你的应用是否公开任何 Web API？ | 是 |
| 您的权限模型是否仅在客户端应用程序收到正确同意时才允许呼叫成功？ | 是 |
| 你的应用是否使用预览 API？ | 是 |
| 你的应用是否使用已弃用 API？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
