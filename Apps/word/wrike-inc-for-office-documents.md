---
title: Wrike for Office Documents 的应用程序信息
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 03/23/2020
ms.topic: article
ms.service: attestation
certification_type: certified
description: Wrike for Office Documents 的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security 应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 253c8d631397d0d17a96e75f8a5d3c20ea784133
ms.sourcegitcommit: b7ef94cf5fb12f6730a8688834ceee4f8fe8e0da
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 03/25/2022
ms.locfileid: "64463555"
---
# <a name="wrike-for-office-documents"></a>用于文档Office的 Wrike

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>开发人员上次更新时间：2020 年 3 月 23 日</p>

* <a href="https://appsource.microsoft.com/product/office/WA104379841" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

Wrike Inc. 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | 用于文档Office的 Wrike |
| ID | WA104379841 |
| Office 365客户端 | Excel 2016 Windows、Word 2013 或更高版本（位于 Windows、PowerPoint 2013 或更高版本、Windows 或更高版本、Excel 2016 或更高版本、Mac 上的 Excel web 版、Word 2016 或更高版本上）Word web 版、PowerPoint 2016 Mac 或更高版本，PowerPoint web 版 |
| 合作伙伴公司名称 | Wrike Inc. |
| 合作伙伴网站的 URL | [https://www.wrike.com/](https://www.wrike.com/) |
| 隐私策略的 URL | [https://www.wrike.com/privacy/](https://www.wrike.com/privacy/) |
| 使用条款 URL | [https://www.wrike.com/terms/](https://www.wrike.com/terms/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

此信息由 Wrike Inc. 提供，用于了解此应用程序如何收集和存储组织数据，以及您的组织将拥有对应用收集的数据的控制。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph所需的](/graph/permissions-reference)任何 Microsoft 权限。

>此应用程序不使用 Microsoft Graph。

#### <a name="data-access-using-other-microsoft-apis"></a>使用其他 Microsoft API 进行数据访问

基于组织构建的应用和Microsoft 365可能会使用 Microsoft Graph 外的其他 Microsoft API 来收集或处理 OII (组织) 。 列出除 Microsoft API Graph此应用使用的任何 Microsoft API。

>| **API** |  **是否收集 OII？** |  **收集哪些 OII？** | **收集 OII 的理由？** | **是否存储 OII？** | **存储 OII 的理由** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| 适用于 Office 的 JavaScript API | 是 | 外接程序使用 Office.js API 与 Office 应用程序集成。 |  | 没有组织数据存储在 Wrike 的数据库中。 |  |

#### <a name="non-microsoft-services-used"></a>非Microsoft 服务已使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>| **所有非Microsoft 服务 OII 将转移到** |  **转移了哪些 OII？** | **转移 OII 的理由？** |
>|:-------------------|:--------------------------|:--------------------------|
>| Wrike 与有权访问某些数据的以下供应商集成：Marketo 是电子邮件线索捕获服务 ，仅会向它们提供名称和电子邮件。 推广是基于云的销售活动 - 仅向它们提供名称和电子邮件。 Salesforce CRM 系统 - 具有联系人信息和帐单 (客户) 敏感数据。 Zuora - 计费和开票客户。 所有供应商都有一个 DPA。 |  | 我们使用 JS Office API，但我们不收集/处理/存储任何组织信息。 |



#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或 EUII (最终用户可识别) 是否显示在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>否

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>Wrike 具有多租户体系结构，可基于客户元数据&#8217;访问控制来逻辑隔离客户的数据。 此元数据根据特定 Wrike 帐户中基于角色的访问规则与特定租户及其访问权限相关联。 数据在逻辑上隔离和隔离，并且只能通过应用程序访问数据，以确保安全和隐私。 应用程序级别的安全性阻止租户访问或修改另一个租户所拥有的应用程序数据。 Wrike 的应用程序具有广泛的身份验证、基于角色的访问控制、授权以及数据共享 (机制，https://help.wrike.com/hc/en-us/articles/209603589-Access-Roleshttps://help.wrike.com/hc/en-us/articles/209602969)并且只允许授权用户访问数据。 此外，静态加密适用于通过 Web 应用程序和 API 上传到文件存储中的 Wrike 服务器的用户文件;文件使用 AES 256 位加密自动加密。 此外，所有服务器都使用文件系统加密进行静态加密，此外，Wrike 还为客户管理的加密密钥提供 Wrike Lock https://www.wrike.com/add-on-wrike-lock/ https://help.wrike.com/hc/en-us/articles/360012347934-Wrike-Lock外接程序，请参阅 和 。 作为额外的数据安全层，Wrike 提供审核和报告功能，使管理员能够执行完全安全审查，同时能够更深入了解其 Wrike https://help.wrike.com/hc/en-us/articles/209606309-Audit-Reports帐户中发生的情况，更多详细信息可在 找到。 最后，Wrike 提供允许精细跟踪访问角色的功能，帮助客户完全审核现有数据共享，有关详细信息，请参阅 https://help.wrike.com/hc/en-us/articles/360002004534-Access-Reports。
在两种情况下，可考虑访问客户数据：
- Wrike 支持团队的访问：如果问题排查或验证，需要支持人员访问你的帐户;该访问权限仅能由你授予。 这由系统生成的安全令牌启用，你可以向支持团队提供带外令牌，从而允许支持在有限的时间深入地解决问题。 此保守方法可确保存储在 Wrike 中的数据的额外机密性。
- Wrike 运营团队的访问：Wrike 运营团队负责维护和支持生产环境，包括监视、修补和更新、将新内部版本交付到生产环境等。在过程和技术方面均严格禁止此访问，并且严格授权控制（包括但不限于 VPN、2FA 和个人证书）已到位，此外，还使用 HIDS (基于主机的入侵检测系统) 对访问进行详细监视，由 Wrike 操作安全团队进行审核。 对于 Amazon KMS (Wrike Lock 功能) ，客户数据存储在 Wrike 数据库中，因此 Wrike 运营团队不能直接或间接地获取该数据，因为数据可以使用客户 Amazon KMS 的访问权限进行解密，该访问仅由客户管理和控制。

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

下面将显示[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/21522' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/21522" target="_blank">在新建选项卡中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

