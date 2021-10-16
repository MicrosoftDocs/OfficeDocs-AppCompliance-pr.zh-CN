---
title: Ataira Power BI协作的应用程序信息
ms.author: elmalova
author: elenamalova
ms.date: 07/27/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: 有关 Power BI 协作、其数据处理策略、Microsoft Cloud App Security应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息的所有可用安全性和合规性信息。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 2e015b1596c02f6841609f1dba61577f25c738e4
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 10/16/2021
ms.locfileid: "60411911"
---
# <a name="power-bi-collaboration"></a>Power BI 协作

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2021 年 6 月 14 日</p>

* <a href="https://teams.microsoft.com/l/app/90381cb0-998f-4ba3-9699-130201de5ddb" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381384" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

Ataira 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | Power BI 协作 |
| ID | WA104381384 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | Ataira |
| 合作伙伴网站的 URL | [https://www.ataira.com](https://www.ataira.com) |
| 应用程序Teams页的 URL | [https://www.ataira.com/Microsoft/PowerBI/Collaboration](https://www.ataira.com/Microsoft/PowerBI/Collaboration) |
| 隐私策略的 URL | [https://www.ataira.com/PrivacyPolicy](https://www.ataira.com/PrivacyPolicy) |
| 使用条款 URL | [https://www.ataira.com/TermsofUse](https://www.ataira.com/TermsofUse) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

Ataira 提供了此信息，这些信息与此应用程序如何收集和存储组织数据以及组织将拥有对应用收集的数据的控制有关。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph所需的](https://docs.microsoft.com/graph/permissions-reference)任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | delegated | Also permissions for ChannelMessage.Send Team.ReadBasic.All User.Read. 它们用于允许用户选择通知Teams组和频道 | 使用情况、错误和许可证监视。 [callback_group_id] ，[datetime_id] ，[session_id] ，[app_type] ，[raw_url] ，[user_id] ，[list_name] ，[user_name] ，[state] ，[priority] ，[user_domain] ，[url_text]] ，[group_name] ，[title_name] ，[comments] ，[file_name] ，[description] ，[group_pbi_name] ，[item_type] ，[organization_id] ，[user_objectid] ，[organization_displayName] ，[group_id] | [00738e07-f9a4-4bf5-b6f9-851ec7ea31d5](https://docs.microsoft.com/microsoft-365-app-certification/azure/00738e07-f9a4-4bf5-b6f9-851ec7ea31d5) |

#### <a name="data-access-using-other-microsoft-apis"></a>使用其他 Microsoft API 进行数据访问

基于组织构建的应用和加载项Microsoft 365除 Microsoft Graph 外的其他 Microsoft API 来收集或处理 OII (组织) 。 列出除 Microsoft API Graph此应用使用的任何 Microsoft API。

>| **API** |  **是否收集 OII？** |  **收集哪些 OII？** | **收集 OII 的理由？** | **是否存储 OII？** | **存储 OII 的理由** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| https://analysis.windows.net/powerbi/api/ | 是 | 用户电子邮件， 工作区名称， 项目名称， 嵌入 URL | 用于在加载项界面中SharePoint报表和仪表板 | [api_pbi_id] ，[datetime_id] ，[session_id] ，[user_name] ，[user_domain] ，[WorkSpace_Name] ，[WorkSpace_Id] ，[item_Id] ，[item_type] ，[item_name] ，[webUrl] ，[embedUrl] ，[displayName] ，[item_title] ，[isOwnedByMe] | 使用情况、错误和许可证监视 |

#### <a name="non-microsoft-services-used"></a>非Microsoft 服务使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>不Microsoft 服务非活动。

#### <a name="data-access-via-bots"></a>通过机器人访问数据

如果此应用包含机器人或消息扩展，则它可以访问最终用户可识别信息 (EUII) ：名单 (名字、姓氏、显示名称、电子邮件地址) （团队中任何团队成员的姓名、姓氏、电子邮件地址) 或添加到其中聊天）。 此应用是否使用了此功能？

>无法访问 EUII。


#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或 EUII (最终用户可识别) 是否显示在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>填充报表和仪表板所需的Power BI元数据，对 Graph Teams API 进行身份验证。 可以在网站上找到更多数据和隐私策略。 https://www.ataira.com/PrivacyPolicy 然后在"应用配置"页上也专门针对数据隐私。 https://www.ataira.com/Microsoft/PowerBI/CollaborationSupport

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

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/41844' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/41844" target="_blank">在新建选项卡中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>标识信息

Ataira 已提供有关此应用如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件的信息。

| **Information** | **响应** |
|:----------------|:-------------|
| 是否与 Microsoft 标识平台 (Azure AD) ？  | 是 |
| 您是否已查看并遵循了 Microsoft 标识平台 清单中列出的所有适用最佳做法？  | 是 |
| 你的应用是否使用 MSAL (Microsoft 身份验证库) 进行身份验证？ | 是 |
| 你的应用是否支持条件访问策略？ | 是 |
| 列出支持的策略类型 | 多重身份验证 仅允许 Intune 注册的设备访问特定服务 限制用户位置和 IP 范围 |
| 应用是否请求方案最小特权权限？ | 是 |
| 应用的静态注册权限是否准确反映应用将动态和增量请求的权限？ | 是 |
| 你的应用是否支持多租户？ | 是 |
| 你的应用是否具有机密客户端？ | 是 |
| 你是否拥有为应用注册的所有 (统一) URI？ | 是 |
| 你的应用是否公开任何 Web API？ | 是 |
| 您的权限模型是否仅在客户端应用程序收到正确同意时才允许呼叫成功？ | 是 |
| 你的应用是否使用预览 API？ | 否 |
| 你的应用是否使用已弃用 API？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

