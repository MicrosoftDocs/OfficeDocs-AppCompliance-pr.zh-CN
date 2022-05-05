---
title: LMS365 的应用程序信息
ms.author: elmalova
author: elenamalova
ms.date: 06/23/2021
ms.topic: article
ms.service: attestation
certification_type: certified
description: LMS365 的所有可用安全性和符合性信息、其数据处理策略、其Microsoft Cloud App Security应用目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 7136a0f4a71f54772dc250433686996f2d236a19
ms.sourcegitcommit: 7a7de9f48f6cf5b6acd435412477b6a59127f19a
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 05/05/2022
ms.locfileid: "65224986"
---
# <a name="application-information-for-lms365-by-elearningforce-international-aps"></a>ELEARNINGFORCE International Aps 提供的 LMS365 应用程序信息

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>开发人员上次更新时间：2021 年 6 月 23 日</p>

* <a href="https://appsource.microsoft.com/product/web-apps/elearningforce.lms365_spfx" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

ELEARNINGFORCE International Aps 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | LMS365 |
| ID | elearningforce.lms365_spfx |
| 合作伙伴公司名称 | ELEARNINGFORCE 国际 Aps |
| 合作伙伴网站的 URL | [https://www.elearningforce.com](https://www.elearningforce.com) |
| 隐私策略的 URL | [https://www.lms365.com/privacy](https://www.lms365.com/privacy) |
| 使用条款的 URL | [https://www.elearningforce.com/LMS365-SaaS-Terms](https://www.elearningforce.com/LMS365-SaaS-Terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

ELEARNINGFORCE International Aps 提供了此信息，了解此应用如何收集和存储组织数据以及组织对应用收集的数据的控制。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph进行数据访问

列出此应用所需的任何 [Microsoft Graph权](/graph/permissions-reference)限。

>| **权限**  | **委托/应用程序)  (权限的类型** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD应用 ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| GroupMember.Read.All | 应用程序 | 无 | 允许应用扩展 AD 组成员，这是将用户组注册到课程所必需的。 | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| Mail.Send | 委托 | 无 | 在为通知配置电子邮件帐户期间动态请求权限。 允许应用发送通知电子邮件 | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| RoleManagement.Read.Directory | 应用程序 | 无 | 允许应用在租户预配期间获取SharePoint域。 域用于 URL 构造。 | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| User.Invite.All | 委托 | 无 | 允许应用代表当前登录用户邀请外部用户 | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| User.Read | 委托 | 无 | 登录并读取用户配置文件。 | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| User.Read.All | 委托 | 无 | 允许应用读取当前登录用户的完整配置文件。 | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| User.Read.All | 应用程序 | 允许应用读取完整的用户配置文件。 它&#8217;读取用户&#8217;管理器以生成层次结构报表所需。 | 以下个人数据存储在应用程序中用于 Learner Management &amp; Manager 仪表板功能的相应客户的专用数据库中。 帐户名称、用户显示名称、电子邮件地址、部门、职务、Office、国家/地区、城市、经理 ID/电子邮件 | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| 个人资料 | 委托 | 无 | 查看用户的基本配置文件。 | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |

#### <a name="data-access-using-other-microsoft-apis"></a>使用其他 Microsoft API 进行数据访问

基于Microsoft 365构建的应用和加载项可以使用除 Microsoft Graph 以外的其他 Microsoft API 来收集或处理组织可识别信息 (OII) 。 列出此应用使用的 Microsoft Graph以外的任何 Microsoft API。

>| **API** |  **是否已收集 OII？** |  **收集了哪些 OII？** | **收集 OII 的理由？** | **OII 是否存储？** | **存储 OII 的理由？** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| SharePoint | 否 |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>未使用Microsoft 服务

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输的数据，并包含应用需要传输此信息的原因。

>不使用非Microsoft 服务。



#### <a name="telemetry-data"></a>遥测数据

此应用程序的遥测或日志中是否 (OII) 或最终用户身份信息 (EUII) 显示任何组织可识别信息？ 如果是，请描述存储的数据以及什么是保留和删除策略？

>是的，我们使用Insights Log Analytics 遥测/日志，这些遥测数据/日志仅用于故障拍摄，并具有 90 天的保留策略，之后将删除所有数据。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

介绍组织管理员如何控制合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>LMS365 配备了清除函数，可从客户端 LMS365 数据库中删除任何个人数据。

#### <a name="human-review-of-organizational-information"></a>组织信息的人工评审

人类是否参与查看或分析组织识别信息 (OII) 此应用收集或存储的数据？

>不支持

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

下面显示了[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35695' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35695" target="_blank">在新选项卡中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>标识信息

ELEARNINGFORCE 国际 Aps 提供了此信息，了解此应用如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件。

| **Information** | **响应** |
|:----------------|:-------------|
| 是否与 Microsoft 标识平台 (Azure AD) 集成？  | 是 |
| 是否已查看并遵守Microsoft 标识平台集成清单中列出的所有适用最佳做法？  | 是 |
| 应用是否使用 MSAL (Microsoft 身份验证库) 进行身份验证？ | 是 |
| 应用是否支持条件访问策略？ | 是 |
| 列出支持的策略类型 | 设备平台、设备状态、客户端应用 |
| 你的应用是否请求方案的最低特权权限？ | 是 |
| 应用的静态注册权限是否准确反映应用将以动态和增量方式请求的权限？ | 是 |
| 你的应用是否支持多租户？ | 是 |
| 你的应用是否具有机密客户端？ | 否 |
| 是否拥有注册应用的所有重定向统一资源标识符 (URI) ？ | 是 |
| 你的应用是否公开任何 Web API？ | 是 |
| 权限模型是否仅允许在客户端应用收到适当同意时调用成功？ | 是 |
| 应用是否使用预览 API？ | 否 |
| 你的应用是否使用已弃用的 API？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
