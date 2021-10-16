---
title: 通过销售渠道推广销售Outlook服务的应用程序信息
ms.author: elmalova
author: elenamalova
ms.date: 08/19/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: 适用于 Outlook 的推广销售活动的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security 应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 483fb4fd6741e479403e4cd05ad284b50a87f9c4
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 10/16/2021
ms.locfileid: "60413554"
---
# <a name="outreach-sales-engagement-for-outlook"></a>推广销售Outlook

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2021 年 6 月 14 日</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381052" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

由 Microsoft 推广提供的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | 推广销售Outlook |
| ID | WA104381052 |
| Office 365支持的客户端 | Outlook 2013 或更高版本，Windows Mac Outlook 2016 或更高版本，Outlook 网页版 |
| 合作伙伴公司名称 | 推广 |
| 合作伙伴网站的 URL | [https://www.outreach.io](https://www.outreach.io) |
| 隐私策略的 URL | [https://www.outreach.io/legal/privacy-policy/](https://www.outreach.io/legal/privacy-policy/) |
| 使用条款 URL | [https://www.outreach.io/terms](https://www.outreach.io/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

此应用程序如何收集和存储组织数据以及组织将拥有对应用收集的数据的控制权的信息已由推广部门提供。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph](https://docs.microsoft.com/graph/permissions-reference)所需的任何 Microsoft 权限。

>此应用程序不使用 Microsoft Graph。

#### <a name="data-access-using-other-microsoft-apis"></a>使用其他 Microsoft API 进行数据访问

基于组织构建的应用和加载项Microsoft 365除 Microsoft Graph 外的其他 Microsoft API 来收集或处理 OII (组织) 。 列出除 Microsoft API Graph此应用使用的任何 Microsoft API。

>| **API** |  **是否收集 OII？** |  **收集哪些 OII？** | **收集 OII 的理由？** | **是否存储 OII？** | **存储 OII 的理由** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| Outlook外接程序 API 、EWS API、O36 REST API | 否 |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>非Microsoft 服务已使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>| **所有非Microsoft 服务 OII 将转移到** |  **转移了哪些 OII？** | **转移 OII 的理由？** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Salesforce CRM | 与 Salesforce 的外向集成允许在两种服务之间安全地双向同步有限的数据集，包括;组织名称、电子邮件地址和用户名。 | 外向的智能双向同步可确保两个系统中数据之间的完全保真度。 在推广&#8212;通话、电子邮件等&#8212;活动都会自动记录在 Salesforce 中，冲突解决会检测并解决冲突，以保持数据安全。 它适用于 Salesforce Aloha 和 Lightning 版本。 |



#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或 EUII (最终用户可识别) 是否显示在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>推广不会将保留期应用于客户&#8217;数据。 推广作为数据处理者运行，因此，未经客户明确许可&#8217;我们的客户绝不会更改数据。 根据我们的 MSA 和 DPA，所有客户数据在业务关系结束后的 60 天内被删除。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>出于合同和监管原因，还需要进行推广，以便及时通知所有客户使用新的或变更给下级处理者。 对于大多数推广客户，此期限为 30 天。 但是，我们还有一些客户要求提前 60 和 90 天通知。 在向所有客户发送新子处理通知的法律要求通知且所需适用时间范围通过之后，才能传输任何客户数据。

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>是

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>标识信息

此应用程序如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件，由推广机构提供此信息。

| **Information** | **响应** |
|:----------------|:-------------|
| 是否与 Microsoft 标识平台 (Azure AD) ？  | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

