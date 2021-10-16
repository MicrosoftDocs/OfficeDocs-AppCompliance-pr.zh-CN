---
title: 员工培训管理的应用程序信息（按SharePoint|Sapiens
ms.author: elmalova
author: elenamalova
ms.date: 07/27/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: 员工培训管理的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 37505e2f1ba531b3aa1a03a3fb8c93e6da8f121a
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 10/16/2021
ms.locfileid: "60410916"
---
# <a name="employee-training-management"></a>员工培训管理

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2021 年 5 月 31 日</p>

* <a href="https://teams.microsoft.com/l/app/17b6b751-7463-4afd-a3ae-ad26a20c8904" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001512" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

由用户提供的信息SharePoint|Sapiens 到 Microsoft：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | 员工培训管理 |
| ID | WA200001512 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | SharePoint|Sapiens |
| 合作伙伴网站的 URL | [https://www.sharepointsapiens.com](https://www.sharepointsapiens.com) |
| 应用程序Teams页的 URL | [https://www.sharepointsapiens.com/employee-training-managem...](https://www.sharepointsapiens.com/employee-training-management-office365/documentation/teams/) |
| 隐私策略的 URL | [https://www.sharepointsapiens.com/privacy/](https://www.sharepointsapiens.com/privacy/) |
| 使用条款 URL | [https://addins.sharepointsapiens.com/licensing/services-agr...](https://addins.sharepointsapiens.com/licensing/services-agreement.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

此信息由 SharePoint|Sapiens about how this app collects and stores organizational data and the control that your organization will have over the data the app collects.

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph所需的](https://docs.microsoft.com/graph/permissions-reference)任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.ReadBasic.All | delegated | 电子邮件地址和会议室Exchange和资源的名称，以启用会议室和资源预订 | 不存储任何数据 | [9e8e113c-8a08-4606-b08a-de4decc7252f](https://docs.microsoft.com/microsoft-365-app-certification/azure/9e8e113c-8a08-4606-b08a-de4decc7252f) |

#### <a name="data-access-using-other-microsoft-apis"></a>使用其他 Microsoft API 进行数据访问

基于组织构建的应用和加载项Microsoft 365除 Microsoft Graph 外的其他 Microsoft API 来收集或处理 OII (组织) 。 列出除 Microsoft API Graph此应用使用的任何 Microsoft API。

>| **API** |  **是否收集 OII？** |  **收集哪些 OII？** | **收集 OII 的理由？** | **是否存储 OII？** | **存储 OII 的理由** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| Office 365 Exchange Online | 否 |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>非Microsoft 服务使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>| **所有非 Microsoft 服务 OII 将转移到** |  **转移了哪些 OII？** | **转移 OII 的理由？** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Mailgun.com (可选) ，Stripe.com (可选)  | 计费的公司名称和地址（如果 Stripe.com 邮件服务用于帐单、日历邀请以及用户电子邮件地址的回复和回复） | 如果您选择使用我们的邮件服务而不是 Exchange联机电子邮件服务，则服务会通过 mail进行 API 和基础结构发送和接收电子邮件。 如果您选择使用自己的邮箱Exchange邮箱，mail时不会处理任何数据。 如果选择使用信用卡支付订阅费用，收集的数据将受用户控制和 stripe.com。 如果选择通过 PO 和发票而不是信用卡进行购买，则系统不会处理任何 stripe.com。 |

#### <a name="data-access-via-bots"></a>通过机器人访问数据

如果此应用包含机器人或消息扩展，则它可以访问最终用户可识别信息 (EUII) ：名单 (名字、姓氏、显示名称、电子邮件地址) （团队中任何团队成员的姓名、姓氏、电子邮件地址) 或添加到其中聊天）。 此应用是否使用了此功能？

>无法访问 EUII。


#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或 EUII (最终用户可识别) 是否显示在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>不存储 EUII。 TenantID SharePoint域将存储在应用的遥测中。 日志和遥测数据将存储 90 天。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>所有数据存储在客户的网站SharePoint中。 我们不会将客户数据存储在任何其他位置，应用程序设置、许可证和使用信息除外。

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>是

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

下面将显示[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36018' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36018" target="_blank">在新建选项卡中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>标识信息

此信息由用户SharePoint|Sapiens about how this app handles authentication， authorization， application registration best practices， and other Identity criteria.

| **Information** | **响应** |
|:----------------|:-------------|
| 是否与 Microsoft 标识平台 (Azure AD) ？  | 是 |
| 您是否已查看并遵循了 Microsoft 标识平台 清单中列出的所有适用最佳做法？  | 是 |
| 你的应用是否使用 MSAL (Microsoft 身份验证库) 进行身份验证？ | 是 |
| 你的应用是否支持条件访问策略？ | 否 |
| 应用是否请求方案最小特权权限？ | 是 |
| 应用的静态注册权限是否准确反映应用将动态和增量请求的权限？ | 是 |
| 你的应用是否支持多租户？ | 是 |
| 你的应用是否具有机密客户端？ | 是 |
| 你是否拥有为应用注册的所有 (统一) URI？ | 是 |
| 对于你的应用，应避免使用什么？ | - 通配符重定向 URI，<br/><br/> |
| 你的应用是否公开任何 Web API？ | 否 |
| 你的应用是否使用预览 API？ | 否 |
| 你的应用是否使用已弃用 API？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

