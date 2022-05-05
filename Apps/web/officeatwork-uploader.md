---
title: 上传器的应用程序信息
ms.author: elmalova
author: elenamalova
ms.date: 06/23/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: 上传器的所有可用安全性和符合性信息、其数据处理策略、其Microsoft Cloud App Security应用目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 0dec6f3975671223610272950956d4e5fd4085c0
ms.sourcegitcommit: 7a7de9f48f6cf5b6acd435412477b6a59127f19a
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 05/05/2022
ms.locfileid: "65226106"
---
# <a name="application-information-for-uploader-by-officeatwork"></a>Officeatwork 上传器的应用程序信息

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2021 年 6 月 23 日</p>

* <a href="https://appsource.microsoft.com/product/web-apps/officeatwork-ag.uploader" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

Officeatwork 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | 上传者 |
| ID | officeatwork-ag.uploader |
| 合作伙伴公司名称 | officeatwork |
| 合作伙伴网站的 URL | [https://www.officeatwork.com](https://www.officeatwork.com) |
| 隐私策略的 URL | [https://links.officeatwork.com/officeatwork-privacystatement](https://links.officeatwork.com/officeatwork-privacystatement) |
| 使用条款的 URL | [https://links.officeatwork.com/officeatwork-licenseterms](https://links.officeatwork.com/officeatwork-licenseterms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

此信息由 Officeatwork 提供，说明此应用如何收集和存储组织数据，以及组织对应用收集的数据的控制。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph进行数据访问

列出此应用所需的任何 [Microsoft Graph权](/graph/permissions-reference)限。

>| **权限**  | **委托/应用程序)  (权限的类型** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD应用 ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Files.ReadWrite.All | 委托 | 不存储任何数据。 | OneDrive：能够读取数据并将数据写入用户的OneDrive。 | f5c9f179-b9a5-4364-8f99-18d203b902ad |
>| Group.ReadWrite.All | 委托 | 不存储任何数据。 | Teams：读取数据并将数据写入组。 | f5c9f179-b9a5-4364-8f99-18d203b902ad |
>| GroupMember.Read.All | 委托 | 不存储任何数据。 | SharePoint联机 - 安全组支持：允许应用列出组、读取基本组属性以及读取登录用户有权访问的所有组的成员身份。 | f5c9f179-b9a5-4364-8f99-18d203b902ad |
>| Sites.Read.All | 委托 | 不存储任何数据。 | SharePoint联机：若要在 SharePoint Online 中启用读取数据，登录用户有权访问。 启用将数据上传到SharePoint联机 | f5c9f179-b9a5-4364-8f99-18d203b902ad |
>| User.Read | 委托 | 不存储任何数据。 | 单接：使 officeatwork 应用能够读取用户的基本属性。 | f5c9f179-b9a5-4364-8f99-18d203b902ad |
>| User.Read.All | 委托 | 不存储任何数据。 | Teams：了解用户所属的组。 | f5c9f179-b9a5-4364-8f99-18d203b902ad |
>| offline_access | 委托 | 不存储任何数据。 | 单一登录：若要通过刷新令牌启用自动登录，用户每次启动 officeatwork 应用时都必须手动登录。 此范围仅适用于未启用 SSO 的主机应用程序。 | f5c9f179-b9a5-4364-8f99-18d203b902ad |
>| openid | 委托 | 不存储任何数据。 | 单击：使用户能够使用其组织和/或 Microsoft 帐户登录 Officeatwork 应用。 | f5c9f179-b9a5-4364-8f99-18d203b902ad |
>| 个人资料 | 委托 | 不存储任何数据。 | 登录：在 officeatwork 应用中显示已登录用户。 这有助于向用户保证/确认用于登录 officeatwork 应用的帐户。 | f5c9f179-b9a5-4364-8f99-18d203b902ad |

#### <a name="data-access-using-other-microsoft-apis"></a>使用其他 Microsoft API 进行数据访问

基于Microsoft 365构建的应用和加载项可以使用除 Microsoft Graph 以外的其他 Microsoft API 来收集或处理组织可识别信息 (OII) 。 列出此应用使用的 Microsoft Graph以外的任何 Microsoft API。

>| **API** |  **是否已收集 OII？** |  **收集了哪些 OII？** | **收集 OII 的理由？** | **OII 是否存储？** | **存储 OII 的理由？** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| SharePoint REST API | 否 |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>未使用Microsoft 服务

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输的数据，并包含应用需要传输此信息的原因。

>不使用非Microsoft 服务。



#### <a name="telemetry-data"></a>遥测数据

此应用程序的遥测或日志中是否 (OII) 或最终用户身份信息 (EUII) 显示任何组织可识别信息？ 如果是，请描述存储的数据以及什么是保留和删除策略？

>是的，事件包括 oid 和 tenantId，并发送到 Azure AppInsights。 90 天后会自动删除这些事件。 如果客户希望删除此数据，他们可以使用隐私声明中提供的链接来启动删除该数据。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

介绍组织管理员如何控制合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>应用程序设置数据 (功能标志、组织显示名称、tenantId、管理员 oid 列表) 存储在 Azure Cosmos 数据库实例中， (每个租户) 一个文件。 DB 文件已加密，访问权限仅限于选定的 Officeatwork 工程师和支持人员。 客户可以使用管理中心 Web 应用访问和操作 officeatwork 应用设置数据。

#### <a name="human-review-of-organizational-information"></a>组织信息的人工评审

人类是否参与查看或分析组织识别信息 (OII) 此应用收集或存储的数据？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

下面显示了[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35750' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35750" target="_blank">在新选项卡中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>标识信息

有关此应用如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件的 Officeatwork 提供了此信息。

| **Information** | **响应** |
|:----------------|:-------------|
| 是否与 Microsoft 标识平台 (Azure AD) 集成？  | 是 |
| 是否已查看并遵守Microsoft 标识平台集成清单中列出的所有适用最佳做法？  | 是 |
| 应用是否使用 MSAL (Microsoft 身份验证库) 进行身份验证？ | 否 |
| 应用是否支持条件访问策略？ | 是 |
| 列出支持的策略类型 | 安全性默认值 |
| 你的应用是否请求方案的最低特权权限？ | 是 |
| 应用的静态注册权限是否准确反映应用将以动态和增量方式请求的权限？ | 否 |
| 你的应用是否支持多租户？ | 是 |
| 你的应用是否具有机密客户端？ | 是 |
| 是否拥有注册应用的所有重定向统一资源标识符 (URI) ？ | 是 |
| 对于你的应用，你避免使用什么？ | - 通配符重定向 URI，<br/>- OAuth2 隐式Flow，除非 SPA 需要<br/>- 资源所有者密码凭据 (ROPC) 流 |
| 你的应用是否公开任何 Web API？ | 否 |
| 应用是否使用预览 API？ | 不支持 |
| 你的应用是否使用已弃用的 API？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
