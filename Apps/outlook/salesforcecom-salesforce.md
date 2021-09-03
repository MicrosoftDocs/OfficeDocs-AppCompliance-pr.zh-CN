---
title: Salesforce 的应用程序信息（按 salesforce.com
ms.author: elmalova
author: elenamalova
ms.date: 08/24/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Salesforce 的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 152885012f81c077fc0bb018fda7080867c54986
ms.sourcegitcommit: cd30c7ec09b1a06fb0b5696d10739a27c8434c53
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 09/03/2021
ms.locfileid: "58884610"
---
# <a name="salesforce"></a>Salesforce

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2021 年 8 月 24 日</p>

* <a href="https://appsource.microsoft.com/product/office/WA104379334" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

由 Microsoft salesforce.com 以下信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | Salesforce |
| ID | WA104379334 |
| Office 365支持的客户端 | Outlook 2013 或更高版本，Windows Mac Outlook 2016 或更高版本，Outlook 网页版 |
| 合作伙伴公司名称 | salesforce.com |
| 合作伙伴网站的 URL | [https://www.salesforce.com](https://www.salesforce.com) |
| 隐私策略的 URL | [https://www.salesforce.com/company/privacy/](https://www.salesforce.com/company/privacy/) |
| 使用条款 URL | [https://www.salesforce.com/content/dam/web/en_us/www/docume...](https://www.salesforce.com/content/dam/web/en_us/www/documents/legal/Agreements/software-order-form-supplements/Salesforce_Outlook_TOU_Order_Form_Addendum.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

此信息由用户 salesforce.com，这些信息与此应用程序如何收集和存储组织数据以及组织将拥有对应用收集的数据的控制有关。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph所需的](https://docs.microsoft.com/graph/permissions-reference)任何 Microsoft 权限。

>此应用程序不使用 Microsoft Graph。

#### <a name="data-access-using-other-microsoft-apis"></a>使用其他 Microsoft API 进行数据访问

基于组织构建的应用和加载项Microsoft 365除 Microsoft Graph 外的其他 Microsoft API 来收集或处理 OII (组织) 。 列出此应用使用的任何 Microsoft GRAPH Microsoft API。

>| **API** |  **是否收集 OII？** |  **收集哪些 OII？** | **收集 OII 的理由？** | **是否存储 OII？** | **存储 OII 的理由** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| 适用于 Office 的 JavaScript API | 是 | 外接程序使用来自 Office.js 和 EWS 的函数复制有关电子邮件的内容和附件Outlook用户已决定登录到 Salesforce。 日历端使用类似功能将约会记录到 Salesforce 中。 | 外接程序使用来自 Office.js 和 EWS 的函数复制有关电子邮件的内容和附件Outlook用户已决定登录到 Salesforce。 日历端使用类似功能将约会记录到 Salesforce 中。 | 外接程序使用 getUserIdentityTokenAsync 等函数获取当前 Outlook 用户标识、GetItem (.js 和 EWS) ，以在保存为 Salesforce 记录时获取和设置 AdditionalProperties 和当前电子邮件的内容。 GetAttachment (EWS) 从 Exchange 检索附件并添加到配对的 Salesforce 电子邮件 UpdateItem (.js) ，GetFolder (.js) ，获取草稿文件夹 CreateItem (.js) ，用于创建草稿邮件。 | 外接程序使用 getUserIdentityTokenAsync 等函数获取当前 Outlook 用户标识、GetItem (.js 和 EWS) ，以在保存为 Salesforce 记录时获取和设置 AdditionalProperties 和当前电子邮件的内容。 GetAttachment (EWS) 从 Exchange 检索附件并添加到配对的 Salesforce 电子邮件 UpdateItem (.js) ，GetFolder (.js) ，获取草稿文件夹 CreateItem (.js) ，用于创建草稿邮件。 |
>| Exchange Web 服务 (EWS) | 是 | 外接程序使用来自 Office.js 和 EWS 的函数复制有关电子邮件的内容和附件Outlook用户已决定登录到 Salesforce。 日历端使用类似功能将约会记录到 Salesforce 中。 | 外接程序使用来自 Office.js 和 EWS 的函数复制有关电子邮件的内容和附件Outlook用户已决定登录到 Salesforce。 日历端使用类似功能将约会记录到 Salesforce 中。 | 外接程序使用 getUserIdentityTokenAsync 等函数获取当前 Outlook 用户标识、GetItem (.js 和 EWS) ，以在保存为 Salesforce 记录时获取和设置 AdditionalProperties 和当前电子邮件的内容。 GetAttachment (EWS) 从 Exchange 检索附件并添加到配对的 Salesforce 电子邮件 UpdateItem (.js) ，GetFolder (.js) ，获取草稿文件夹 CreateItem (.js) ，用于创建草稿邮件。 | 外接程序使用 getUserIdentityTokenAsync 等函数获取当前 Outlook 用户标识、GetItem (.js 和 EWS) ，以在保存为 Salesforce 记录时获取和设置 AdditionalProperties 和当前电子邮件的内容。 GetAttachment (EWS) 从 Exchange 检索附件并添加到配对的 Salesforce 电子邮件 UpdateItem (.js) ，GetFolder (.js) ，获取草稿文件夹 CreateItem (.js) ，用于创建草稿邮件。 |

#### <a name="non-microsoft-services-used"></a>非Microsoft 服务使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>不Microsoft 服务非活动。



#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或最终用户可识别信息 (EUII) 是否出现在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>否

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>Salesforce 存储在安全指南中进行了介绍，该指南位于 https://resources.docs.salesforce.com/222/latest/en-us/sfdc/pdf/salesforce_security_impl_guide.pdf

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

下面将显示[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/" target="_blank">在新建选项卡中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>标识信息

此信息已由用户 salesforce.com 此应用如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件。

| **Information** | **响应** |
|:----------------|:-------------|
| 你是否与 Microsoft 标识平台 (Azure AD) ？  | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
