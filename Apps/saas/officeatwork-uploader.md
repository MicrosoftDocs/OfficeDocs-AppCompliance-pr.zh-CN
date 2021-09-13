---
title: officeatwork 上传者的应用程序信息
ms.author: elmalova
author: elenamalova
ms.date: 06/23/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: 上载器的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: db984b1c2a02537d29db11b2a5e2d3761c01e774
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 09/12/2021
ms.locfileid: "59278467"
---
# <a name="uploader"></a>上传者

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2021 年 6 月 23 日</p>

* <a href="https://appsource.microsoft.com/product/web-apps/officeatwork-ag.uploader" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

officeatwork 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | 上传者 |
| ID | officeatwork-ag.uploader |
| 合作伙伴公司名称 | officeatwork |
| 合作伙伴网站的 URL | [https://www.officeatwork.com](https://www.officeatwork.com) |
| 隐私策略的 URL | [https://links.officeatwork.com/officeatwork-privacystatement](https://links.officeatwork.com/officeatwork-privacystatement) |
| 使用条款 URL | [https://links.officeatwork.com/officeatwork-licenseterms](https://links.officeatwork.com/officeatwork-licenseterms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

此信息是由 officeatwork 提供的，这些信息与此应用程序如何收集和存储组织数据以及您的组织将拥有对应用收集的数据的控制有关。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph所需的](https://docs.microsoft.com/graph/permissions-reference)任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD 应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Files.ReadWrite.All | delegated | 不存储任何数据。 | OneDrive：能够读取和写入用户数据OneDrive。 | [f5c9f179-b9a5-4364-8f99-18d203b902ad](https://docs.microsoft.com/microsoft-365-app-certification/azure/f5c9f179-b9a5-4364-8f99-18d203b902ad) |
>| Group.ReadWrite.All | delegated | 不存储任何数据。 | Teams：读取和写入组数据。 | [f5c9f179-b9a5-4364-8f99-18d203b902ad](https://docs.microsoft.com/microsoft-365-app-certification/azure/f5c9f179-b9a5-4364-8f99-18d203b902ad) |
>| GroupMember.Read.All | delegated | 不存储任何数据。 | SharePoint联机 - 安全组支持：允许应用列出组、读取基本组属性和读取登录用户有权访问的所有组的成员身份。 | [f5c9f179-b9a5-4364-8f99-18d203b902ad](https://docs.microsoft.com/microsoft-365-app-certification/azure/f5c9f179-b9a5-4364-8f99-18d203b902ad) |
>| Sites.Read.All | delegated | 不存储任何数据。 | SharePoint联机：若要在 SharePoint Online 中读取数据，登录用户有权访问。 启用将数据上载到 SharePoint Online | [f5c9f179-b9a5-4364-8f99-18d203b902ad](https://docs.microsoft.com/microsoft-365-app-certification/azure/f5c9f179-b9a5-4364-8f99-18d203b902ad) |
>| User.Read | delegated | 不存储任何数据。 | Sing-In：使 officeatwork 应用能够读取用户的基本属性。 | [f5c9f179-b9a5-4364-8f99-18d203b902ad](https://docs.microsoft.com/microsoft-365-app-certification/azure/f5c9f179-b9a5-4364-8f99-18d203b902ad) |
>| User.Read.All | delegated | 不存储任何数据。 | Teams：了解用户所属的组。 | [f5c9f179-b9a5-4364-8f99-18d203b902ad](https://docs.microsoft.com/microsoft-365-app-certification/azure/f5c9f179-b9a5-4364-8f99-18d203b902ad) |
>| offline_access | delegated | 不存储任何数据。 | Sing-In：要像没有刷新令牌一样启用自动登录，用户每次启动 officeatwork 应用时必须手动登录。 只有未启用 SSO 的主机应用程序才需要此范围。 | [f5c9f179-b9a5-4364-8f99-18d203b902ad](https://docs.microsoft.com/microsoft-365-app-certification/azure/f5c9f179-b9a5-4364-8f99-18d203b902ad) |
>| openid | delegated | 不存储任何数据。 | Sing-In：允许用户使用其组织和/或 Microsoft 帐户登录 officeatwork 应用。 | [f5c9f179-b9a5-4364-8f99-18d203b902ad](https://docs.microsoft.com/microsoft-365-app-certification/azure/f5c9f179-b9a5-4364-8f99-18d203b902ad) |
>| 个人资料 | delegated | 不存储任何数据。 | Sing-In：在 officeatwork 应用中显示登录用户。 这有助于确保/确认用户登录 officeatwork 应用所使用的帐户。 | [f5c9f179-b9a5-4364-8f99-18d203b902ad](https://docs.microsoft.com/microsoft-365-app-certification/azure/f5c9f179-b9a5-4364-8f99-18d203b902ad) |

#### <a name="data-access-using-other-microsoft-apis"></a>使用其他 Microsoft API 进行数据访问

基于组织构建的应用和Microsoft 365可以使用除 Microsoft Graph 外的其他 Microsoft API 来收集或处理 OII (组织) 。 列出此应用使用的任何 Microsoft GRAPH Microsoft API。

>| **API** |  **是否收集 OII？** |  **收集哪些 OII？** | **收集 OII 的理由？** | **是否存储 OII？** | **存储 OII 的理由** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| SharePoint REST API | 否 |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>非Microsoft 服务使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>不Microsoft 服务非活动。



#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或最终用户可识别信息 (EUII) 是否出现在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>是，事件包括 oid 和 tenantId，并发送到 Azure AppInsights。 事件将在 90 天后自动删除。 如果客户希望删除此数据，他们可以使用隐私声明中提供的链接来开始删除该数据。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>应用程序设置数据 (功能标志、组织 显示名称、tenantId、管理员列表 oids) 存储在 Azure Cosmos DB 实例中 (每个租户) 。 DB 文件已加密，并且访问权限仅限于选定的办公工程师和支持人员。 客户可以使用管理中心 Web 应用访问和处理 officeatwork 应用设置数据。

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

下面将显示[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35750' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35750" target="_blank">在新建选项卡中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>标识信息

此信息由 officeatwork 提供有关此应用程序如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件的信息。

| **Information** | **响应** |
|:----------------|:-------------|
| 你是否与 Microsoft 标识平台 (Azure AD) ？  | 是 |
| 您是否已查看并遵循了 Microsoft 标识平台 清单中列出的所有适用最佳做法？  | 是 |
| 你的应用是否使用 MSAL (Microsoft 身份验证库) 进行身份验证？ | 否 |
| 你的应用是否支持条件访问策略？ | 是 |
| 列出支持的策略类型 | 安全性默认值 |
| 应用是否请求方案最小特权权限？ | 是 |
| 应用的静态注册权限是否准确反映应用将动态和增量请求的权限？ | 否 |
| 你的应用是否支持多租户？ | 是 |
| 你的应用是否具有机密客户端？ | 是 |
| 你是否拥有为应用注册的所有 (统一) URI？ | 是 |
| 对于你的应用，应避免使用什么？ | - 通配符重定向 URI，<br/>- OAuth2 隐式Flow，除非 SPA 需要<br/>- 资源所有者密码凭据 (ROPC) 流 |
| 你的应用是否公开任何 Web API？ | 否 |
| 你的应用是否使用预览 API？ | 否 |
| 你的应用是否使用已弃用 API？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
