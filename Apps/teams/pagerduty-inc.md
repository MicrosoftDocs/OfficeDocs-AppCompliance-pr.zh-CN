---
title: PagerDuty， Inc. 的 PagerDuty 的应用程序信息
ms.author: elmalova
author: elenamalova
ms.date: 09/01/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: PagerDuty 的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 7c929966d7ab24f4e353ced553ea89737d5b7058
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 10/18/2021
ms.locfileid: "60430170"
---
# <a name="pagerduty"></a>PagerDuty

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2021 年 8 月 27 日</p>

* <a href="https://teams.microsoft.com/l/app/c8c302dc-4e77-4536-890d-0c2bffbef9cc" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001637" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

PagerDuty， Inc. 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | PagerDuty |
| ID | WA200001637 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | PagerDuty， Inc. |
| 合作伙伴网站的 URL | [https://www.pagerduty.com](https://www.pagerduty.com) |
| 应用程序Teams页的 URL | [https://www.pagerduty.com/integrations/microsoft-teams](https://www.pagerduty.com/integrations/microsoft-teams) |
| 隐私策略的 URL | [https://www.pagerduty.com/privacy-policy/](https://www.pagerduty.com/privacy-policy/) |
| 使用条款 URL | [https://www.pagerduty.com/service-terms-use/](https://www.pagerduty.com/service-terms-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

此信息由 PagerDuty， Inc. 提供，有关此应用程序如何收集和存储组织数据以及您的组织将拥有对应用收集的数据的控制。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph](https://docs.microsoft.com/graph/permissions-reference)所需的任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| OnlineMeetings.ReadWrite | delegated | 从会议创建/获取响应中，我们使用此类字段：join_web_url、audioConferencing。 需要这些字段才能向用户显示指向会议的链接或在会议中连接的替代方式。 | 我们保存：join_web_url、audioConferencing。 需要这些字段才能向用户显示指向会议的链接或在会议中连接的替代方式。 | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| TeamsAppInstallation.ReadForTeam | delegated | 用于将 pagerduty 应用添加到聊天。 | 用于将 pagerduty 应用添加到聊天。 | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| TeamsAppInstallation.ReadWriteForTeam.All | delegated | 用于将 pagerduty 应用添加到聊天。 | 用于将 pagerduty 应用添加到聊天。 | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| TeamsTab.ReadWrite.All | delegated | 用于将 pagerduty 应用添加为会议中的选项卡 | 用于将 pagerduty 应用添加为会议中的选项卡 | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| User.Read | delegated | 使用数据：id、userPrincipalName 。它用于让 Microsoft 团队用户将他们作为参与者添加到会议 | 使用数据：id、userPrincipalName 。它用于让 Microsoft 团队用户将他们作为参与者添加到会议 | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| User.ReadBasic.All | delegated | 使用数据：id、userPrincipalName 。它用于让 Microsoft 团队用户将他们作为参与者添加到会议 | 使用数据：id、userPrincipalName 。它用于让 Microsoft 团队用户将他们作为参与者添加到会议 | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| email | delegated | 用于授权和令牌请求。 使用数据：access_token、refresh_token、expires_in、作用域 | access_token、refresh_token、expires_in、作用域。 此数据是获取用户和联机会议相关信息的必需数据 | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| offline_access | delegated | 用于授权和令牌请求。 使用数据：access_token、refresh_token、expires_in、作用域 | access_token、refresh_token、expires_in、作用域。 此数据用于重新获取有关用户和联机会议的信息 | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| openid | delegated | 用于授权和令牌请求。 使用数据：access_token、refresh_token、expires_in、作用域 | access_token、refresh_token、expires_in、作用域。 重新提供此数据，用于获取有关用户和创建/获取联机会议的信息 | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| 个人资料 | delegated | 用于授权和令牌请求。 使用数据：access_token、refresh_token、expires_in、作用域 | access_token、refresh_token、expires_in、作用域。 重新提供此数据，用于获取有关用户和创建/获取联机会议的信息 | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| OnlineMeetings.ReadWrite | delegated | 从会议创建/获取响应中，我们使用此类字段：join_web_url、audioConferencing。 需要这些字段才能向用户显示指向会议的链接或在会议中连接的替代方式。 | 我们保存：join_web_url、audioConferencing。 需要这些字段才能向用户显示指向会议的链接或在会议中连接的替代方式。 | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| TeamsAppInstallation.ReadForTeam | delegated | 用于将 pagerduty 应用添加到聊天。 | 用于将 pagerduty 应用添加到聊天。 | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| TeamsAppInstallation.ReadForTeam.All | delegated | 用于将 pagerduty 应用添加到聊天。 | 用于将 pagerduty 应用添加到聊天。 | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| TeamsTab.ReadWrite.All | delegated | 用于将 pagerduty 应用添加为会议中的选项卡 | 用于将 pagerduty 应用添加为会议中的选项卡 | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| User.Read | delegated | 使用数据：id、userPrincipalName 。它用于让 Microsoft 团队用户将他们作为参与者添加到会议 | 使用数据：id、userPrincipalName 。它用于让 Microsoft 团队用户将他们作为参与者添加到会议 | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| User.ReadBasic.All | delegated | 使用数据：id、userPrincipalName 。它用于让 Microsoft 团队用户将他们作为参与者添加到会议 | 使用数据：id、userPrincipalName 。它用于让 Microsoft 团队用户将他们作为参与者添加到会议 | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| email | delegated | 用于授权和令牌请求。 使用数据：access_token、refresh_token、expires_in、作用域 | access_token、refresh_token、expires_in、作用域。 此数据是获取用户和联机会议相关信息的必需数据 | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| offline_access | delegated | 用于授权和令牌请求。 使用数据：access_token、refresh_token、expires_in、作用域 | access_token、refresh_token、expires_in、作用域。 此数据是获取用户和联机会议相关信息的必需数据 | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| openid | delegated | 用于授权和令牌请求。 使用数据：access_token、refresh_token、expires_in、作用域 | access_token、refresh_token、expires_in、作用域。 重新提供此数据，用于获取有关用户和创建/获取联机会议的信息 | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| 个人资料 | delegated | 用于授权和令牌请求。 使用数据：access_token、refresh_token、expires_in、作用域 | access_token、refresh_token、expires_in、作用域。 重新提供此数据，用于获取有关用户和创建/获取联机会议的信息 | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |


#### <a name="non-microsoft-services-used"></a>非Microsoft 服务已使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>| **所有非Microsoft 服务 OII 将转移到** |  **转移了哪些 OII？** | **转移 OII 的理由？** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| PagerDuty 维护的数据仅限于监视产品中的计算机数据，PII 信息仅限于：公司电子邮件地址、名字、姓氏和电话号码。 可在此处找到有权访问该数据的子处理器列表： https://www.pagerduty.com/subprocessors/ | PagerDuty 维护的数据仅限于监视产品中的计算机数据，PII 信息仅限于：公司电子邮件地址、名字、姓氏和电话号码。 可在此处找到有权访问该数据的子处理器列表： https://www.pagerduty.com/subprocessors/ | PagerDuty 维护的数据仅限于监视产品中的计算机数据，PII 信息仅限于：公司电子邮件地址、名字、姓氏和电话号码。 可在此处找到有权访问该数据的子处理器列表：有关数据隐私详细信息， https://www.pagerduty.com/subprocessors/ 请参阅： https://www.pagerduty.com/privacy-policy/ |

#### <a name="data-access-via-bots"></a>通过机器人访问数据

如果此应用程序包含机器人或消息扩展，则它可以访问最终用户可识别信息 (EUII) ：名单 (名字、姓氏、显示名称、电子邮件地址) （团队中任何团队成员的姓名、姓氏、电子邮件地址) 或添加到其中聊天）。 此应用是否使用了此功能？

>无法访问 EUII。


#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或 EUII (最终用户可识别) 是否显示在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>应用程序遥测或日志中不显示 OII 或 EUII。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>PagerDuty 要求数据安全标准至少与 PagerDuty 维护的数据安全标准一样严格，由我们传输数据的所有供应商维护，包括已签署 DPA 形式的合同义务。 有关我们的数据安全标准的更多信息，可在此处找到： https://www.pagerduty.com/data-security-policy/

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>标识信息

此信息由 PagerDuty， Inc. 提供有关此应用程序如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件的信息。

| **Information** | **响应** |
|:----------------|:-------------|
| 是否与 Microsoft 标识平台 (Azure AD) ？  | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
