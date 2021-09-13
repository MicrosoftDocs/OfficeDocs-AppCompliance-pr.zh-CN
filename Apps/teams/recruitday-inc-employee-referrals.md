---
title: 由 Recruitday Inc. 针对员工引荐的应用程序信息。
ms.author: elmalova
author: elenamalova
ms.date: 06/03/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: 有关员工引荐的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 2aa10a6034260c3774a134eeace4e677f29c83ba
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 09/12/2021
ms.locfileid: "59278607"
---
# <a name="employee-referrals"></a>员工引荐

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2021 年 6 月 3 日</p>

* <a href="https://teams.microsoft.com/l/app/c179cdf6-f93d-4aa3-9e2d-e934e5a81846" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002708" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

由 Recruitday Inc. 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | 员工引荐 |
| ID | WA200002708 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | Recruitday Inc. |
| 合作伙伴网站的 URL | [https://www.recruitday.com](https://www.recruitday.com) |
| 应用程序Teams页的 URL | [https://employer.recruitday.com/solutions/employee-referral...](https://employer.recruitday.com/solutions/employee-referrals/microsoft-teams) |
| 隐私策略的 URL | [https://www.recruitday.com/privacy-policy](https://www.recruitday.com/privacy-policy) |
| 使用条款 URL | [https://www.recruitday.com/terms-of-use](https://www.recruitday.com/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

此信息由 Recruitday Inc. 提供，用于了解此应用程序如何收集和存储组织数据，以及您的组织将拥有对应用收集的数据的控制。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph所需的](https://docs.microsoft.com/graph/permissions-reference)任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD 应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | 两者 | 应用用户的名字和姓氏 (，即员工) 主要由 HR 用户用来轻松识别推荐了引荐应用程序跟踪并奖励付款的员工。 它还将用于在发送系统生成的电子邮件通知时正确地址员工。 | 应用用户的名字和姓氏 (，即员工) 主要由 HR 用户用来轻松识别推荐了引荐应用程序跟踪并奖励付款的员工。 它还将用于在发送系统生成的电子邮件通知时正确地址员工。 | [7414b436-87d1-4904-9d52-ff47885b89f1](https://docs.microsoft.com/microsoft-365-app-certification/azure/7414b436-87d1-4904-9d52-ff47885b89f1) |


#### <a name="non-microsoft-services-used"></a>非Microsoft 服务使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>不Microsoft 服务非活动。

#### <a name="data-access-via-bots"></a>通过机器人访问数据

如果此应用程序包含机器人或消息扩展，则它可以访问最终用户可识别信息 (EUII) ：名单 (名字、姓氏、显示名称、电子邮件地址) （团队中任何团队成员的姓名、姓氏、电子邮件地址) 或添加到其中聊天）。 此应用是否使用了此功能？

>| **访问 EUII 的理由？**  | **EUII 是否存储在数据库 (中) ？** | **存储 EUII 的理由** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| 1. 由 Recruitday 出于以下目的进行处理：1.1。 创建员工帐户 1.2。 发送与事务和提醒 2 有关的系统生成通知。 用户组织出于以下目的进行处理：2.1。 标识引荐 2.2 的来源。 确定谁将获得成功引荐 2.3 的引荐奖励。 确定将阻止哪些员工访问系统 (例如阻止访问)  | 名字、姓氏、电子邮件地址 | 1. 由 Recruitday 出于以下目的进行处理：1.1。 创建员工帐户 1.2。 发送与事务和提醒 2 有关的系统生成通知。 用户组织出于以下目的进行处理：2.1。 标识引荐 2.2 的来源。 确定谁将获得成功引荐 2.3 的引荐奖励。 确定将阻止哪些员工访问系统 (例如阻止访问)  |


#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或最终用户可识别信息 (EUII) 是否出现在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>应用程序遥测或日志中不显示 OII 或 EUII。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>管理员可以通过门户存档用户数据。 其他功能（如删除、更新等）将可以通过向 Recruitday 请求完成。

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

此信息由 Recruitday Inc. 提供，用于说明此应用程序如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件。

| **Information** | **响应** |
|:----------------|:-------------|
| 你是否与 Microsoft 标识平台 (Azure AD) ？  | 是 |
| 您是否已审阅并遵循了 Microsoft 标识平台 集成清单中列出的所有适用最佳做法？  | 是 |
| 你的应用是否使用 MSAL (Microsoft 身份验证库) 进行身份验证？ | 是 |
| 你的应用是否支持条件访问策略？ | 否 |
| 应用是否请求方案最小特权权限？ | 是 |
| 应用的静态注册权限是否准确反映应用将动态和增量请求的权限？ | 是 |
| 你的应用是否支持多租户？ | 否 |
| 你的应用是否具有机密客户端？ | 否 |
| 你是否拥有为应用注册的所有 (统一) URI？ | 是 |
| 你的应用是否公开任何 Web API？ | 否 |
| 你的应用是否使用预览 API？ | 否 |
| 你的应用是否使用已弃用 API？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
