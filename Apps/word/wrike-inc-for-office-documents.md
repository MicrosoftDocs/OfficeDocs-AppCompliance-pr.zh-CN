---
title: Wrike 公司Office文档的 Wrike 信息。
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 03/23/2020
ms.topic: article
ms.service: attestation
certification_type: certified
description: Wrike 适用于Office文档的所有可用安全性和符合性信息、其数据处理策略、其Microsoft Cloud App Security应用目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 4a4839637f40d86c24537bbac722110a1260ff7f
ms.sourcegitcommit: 7a7de9f48f6cf5b6acd435412477b6a59127f19a
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 05/05/2022
ms.locfileid: "65226036"
---
# <a name="information-about-wrike-for-office-documents"></a>有关 Wrike for Office 文档的信息

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>开发人员上次更新时间：2020 年 3 月 23 日</p>

* <a href="https://appsource.microsoft.com/product/office/WA104379841" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

Wrike Inc. 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | Office文档的 Wrike |
| ID | WA104379841 |
| 支持Office 365客户端 | Excel 2016或更高版本的Windows，Word 2013 或更高版本Windows，PowerPoint 2013 或更高版本的Windows，Excel 2016或更高版本的 Mac，Excel web 版，Word 2016或更高版本的 Mac，Word web 版、PowerPoint 2016或更高版本的 Mac、PowerPoint web 版 |
| 合作伙伴公司名称 | Wrike Inc. |
| 合作伙伴网站的 URL | [https://www.wrike.com/](https://www.wrike.com/) |
| 隐私策略的 URL | [https://www.wrike.com/privacy/](https://www.wrike.com/privacy/) |
| 使用条款的 URL | [https://www.wrike.com/terms/](https://www.wrike.com/terms/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

Wrike Inc. 提供了此信息，了解此应用如何收集和存储组织数据，以及组织对应用收集的数据的控制。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph进行数据访问

列出此应用所需的任何 [Microsoft Graph权](/graph/permissions-reference)限。

>此应用程序不使用 Microsoft Graph。

#### <a name="data-access-using-other-microsoft-apis"></a>使用其他 Microsoft API 进行数据访问

基于Microsoft 365构建的应用和加载项可以使用除 Microsoft Graph 以外的其他 Microsoft API 来收集或处理组织可识别信息 (OII) 。 列出此应用使用的 Microsoft Graph以外的任何 Microsoft API。

>| **API** |  **是否已收集 OII？** |  **收集了哪些 OII？** | **收集 OII 的理由？** | **OII 是否存储？** | **存储 OII 的理由？** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| 适用于 Office 的 JavaScript API | 是 | 外接程序使用Office.js API 与Office应用程序集成。 |  | Wrike 的数据库中未存储任何组织数据。 |  |

#### <a name="non-microsoft-services-used"></a>未使用Microsoft 服务

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输的数据，并包含应用需要传输此信息的原因。

>| **将所有非Microsoft 服务 OII 传输到** |  **将传输哪些 OII？** | **传输 OII 的理由？** |
>|:-------------------|:--------------------------|:--------------------------|
>| Wrike 与以下有权访问某些数据的供应商集成：Marketo 是电子邮件潜在顾客捕获服务 - 仅向其提供名称和电子邮件。 外展是基于云的销售活动 - 仅向其提供名称和电子邮件。 Salesforce CRM 系统 - 具有联系信息和计费 (没有敏感数据) 客户信息。 Zuora - 计费和票务客户。 所有供应商都有一个 DPA。 |  | 我们使用 JS Office API，但不收集/处理/存储任何组织信息。 |



#### <a name="telemetry-data"></a>遥测数据

此应用程序的遥测或日志中是否 (OII) 或最终用户身份信息 (EUII) 显示任何组织可识别信息？ 如果是，请描述存储的数据以及什么是保留和删除策略？

>否

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

介绍组织管理员如何控制合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>Wrike 具有一个多租户体系结构，它通过基于客户元数据的访问控制以逻辑方式隔离客户&#8217;数据。 根据特定 Wrike 帐户中基于角色的访问规则，此元数据与特定租户及其访问权限相关联。 数据在逻辑上是隔离和隔离的，并且只能通过应用程序访问数据，以确保安全和隐私。 应用程序级别的安全性阻止租户访问或修改另一租户拥有的应用程序数据。 Wrike 的应用程序具有广泛的身份验证、基于角色的访问控制、授权以及数据共享和控制机制， (查看 https://help.wrike.com/hc/en-us/articles/209603589-Access-Roles ，并且 https://help.wrike.com/hc/en-us/articles/209602969) 仅允许授权用户访问数据。 此外，静态加密适用于通过 Web 应用程序和 API 上传到文件存储中的 Wrike 服务器的用户文件;这些文件使用 AES 256 位加密自动加密。 此外，所有服务器都使用文件系统加密进行静态加密，此外，Wrike 还为客户管理的加密密钥提供了 Wrike Lock 加载项，请参阅 https://www.wrike.com/add-on-wrike-lock/ 和 https://help.wrike.com/hc/en-us/articles/360012347934-Wrike-Lock查看。 作为额外的数据安全层，Wrike 提供审核和报告功能，使管理员能够进行全面的安全评审，同时能够提高对 Wrike 帐户中所发生情况的可见性，可以在其中找到 https://help.wrike.com/hc/en-us/articles/209606309-Audit-Reports更多详细信息。 最后，Wrike 提供了允许对访问角色进行精细跟踪的功能，以帮助客户完全审核现有数据共享，查看详细信息 https://help.wrike.com/hc/en-us/articles/360002004534-Access-Reports。
在两种情况下，可以考虑对客户数据的访问：
- Wrike 支持团队的访问：如果发生故障排除或验证问题，需要支持访问帐户;只能由你授予该访问权限。 这由系统生成的安全令牌启用，你向我们的支持团队提供带外安全令牌，使支持人员能够更深入地深入探讨在有限的时间内解决问题。 此系统性方法可确保 Wrike 中存储的数据具有额外的机密性。
- Wrike 运营团队的访问权限：Wrike 运营团队负责维护和支持生产环境，包括监视、修补和更新、将新版本交付到生产环境等。严格禁止在程序和技术方面访问此案件，并实施严格的授权控制，包括但不限于 VPN、2FA 和个人证书，此外，Wrike 操作安全团队使用 HIDS (基于主机的入侵检测系统) 和审查详细信息对其进行监视。 如果 Amazon KMS (Wrike Lock 功能) ，则客户数据将加密存储在 Wrike 数据库中，因此 Wrike 运营团队不会直接或间接提供数据，因为数据可以使用对客户的 Amazon KMS 的访问进行解密，该访问仅由客户管理和控制。

#### <a name="human-review-of-organizational-information"></a>组织信息的人工评审

人类是否参与查看或分析组织识别信息 (OII) 此应用收集或存储的数据？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

下面显示了[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/21522' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/21522" target="_blank">在新选项卡中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

