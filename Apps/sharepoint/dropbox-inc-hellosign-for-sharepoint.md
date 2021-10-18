---
title: helloSign for SharePoint by Dropbox Inc. 的应用程序信息
ms.author: elmalova
author: elenamalova
ms.date: 10/14/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: HelloSign for SharePoint 的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security 应用程序目录信息和 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: fb96325377e779b0bb933aef7238baa38e0c9380
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 10/18/2021
ms.locfileid: "60428415"
---
# <a name="hellosign-for-sharepoint"></a>HelloSign for SharePoint

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2021 年 8 月 3 日</p>

* <a href="https://appsource.microsoft.com/product/office/WA200003245" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

Dropbox Inc. 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | HelloSign for SharePoint |
| ID | WA200003245 |
| Office 365支持的客户端 | SharePoint 2013 或更高版本 |
| 合作伙伴公司名称 | DropboxInc. |
| 合作伙伴网站的 URL | [https://hellosign.com](https://hellosign.com) |
| 隐私策略的 URL | [https://www.hellosign.com/privacy](https://www.hellosign.com/privacy) |
| 使用条款 URL | [https://hellosign.com/terms](https://hellosign.com/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

此信息由 Dropbox Inc. 提供，用于了解此应用程序如何收集和存储组织数据，以及您的组织将拥有对应用收集的数据的控制。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph所需的](https://docs.microsoft.com/graph/permissions-reference)任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Files.ReadWrite.All | 应用程序 | 与 Sites.ReadWrite.All 一起用来将 HelloSign 签名文件写回SharePoint网站 | 我们不会存储任何与此范围相关的数据 | [6fcff87e-0f86-49c3-81eb-bc028d1ccfe6](https://docs.microsoft.com/microsoft-365-app-certification/azure/6fcff87e-0f86-49c3-81eb-bc028d1ccfe6) |
>| Sites.ReadWrite.All | 应用程序 | 这与 Files.ReadWrite.All 一起用于将 HelloSign 签名文件写回SharePoint网站 | 我们不会存储任何与此范围相关的数据 | [6fcff87e-0f86-49c3-81eb-bc028d1ccfe6](https://docs.microsoft.com/microsoft-365-app-certification/azure/6fcff87e-0f86-49c3-81eb-bc028d1ccfe6) |
>| User.Read | delegated | 用于在应用程序中标识用户的电子邮件 | 用于交叉引用基于电子邮件的 HelloSign 帐户的电子邮件 | [6fcff87e-0f86-49c3-81eb-bc028d1ccfe6](https://docs.microsoft.com/microsoft-365-app-certification/azure/6fcff87e-0f86-49c3-81eb-bc028d1ccfe6) |

#### <a name="data-access-using-other-microsoft-apis"></a>使用其他 Microsoft API 进行数据访问

基于组织构建的应用和加载项Microsoft 365除 Microsoft Graph 外的其他 Microsoft API 来收集或处理 OII (组织) 。 列出除 Microsoft API Graph此应用使用的任何 Microsoft API。

>| **API** |  **是否收集 OII？** |  **收集哪些 OII？** | **收集 OII 的理由？** | **是否存储 OII？** | **存储 OII 的理由** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| SharePointAPI | 是 | 电子邮件、租户 ID 和网站 ID | 用于标识和身份验证目的 | 电子邮件、租户 ID、网站 ID | 用于标识和身份验证目的 |

#### <a name="non-microsoft-services-used"></a>非Microsoft 服务使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>| **所有非 Microsoft 服务 OII 将转移到** |  **转移了哪些 OII？** | **转移 OII 的理由？** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| https://www.hellosign.com/subprocessors | 电子邮件、租户 ID、网站 ID | JN Projects， Inc. dba HelloSign (&#8220;HelloSign&#8221;) 使用某些下级处理者来帮助提供服务。 我们使用可能会存储并处理有关你和最终用户的个人数据的服务提供商， (，&#8220;Sub-Processor&#8221;) 。 此页面提供有关这些材料子处理器的标识、位置和角色的重要信息。 在此页面上使用但没有定义的条款在服务条款协议 (&#8220;条款&#8221;) 。 |



#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或 EUII (最终用户可识别) 是否显示在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>应用程序遥测或日志中不显示 OII 或 EUII。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>我们对驻留在合作伙伴系统的数据具有删除、保留和日志记录功能

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>标识信息

此信息已由 Dropbox Inc. 提供有关此应用程序如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件的信息。

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
| 你的应用是否公开任何 Web API？ | 否 |
| 你的应用是否使用预览 API？ | 否 |
| 你的应用是否使用已弃用 API？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
