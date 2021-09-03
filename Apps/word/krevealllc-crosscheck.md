---
title: CrossCheck 的应用程序信息（由 kRevealLLC）
ms.author: elmalova
author: elenamalova
ms.date: 08/24/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: CrossCheck 的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 245f732d796db9f59f0404a72d3df08aca364c76
ms.sourcegitcommit: 23a1fdeaf3905ab5f7acfbb378c7c23aaedcdc29
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 09/03/2021
ms.locfileid: "58873742"
---
# <a name="crosscheck"></a>CrossCheck

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2021 年 8 月 24 日</p>

* <a href="https://appsource.microsoft.com/product/office/WA200003198" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

kRevealLLC 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | CrossCheck |
| ID | WA200003198 |
| Office 365支持的客户端 | Word 2016 Mac、Word web 版、Word 2013 或更高版本的 Windows |
| 合作伙伴公司名称 | kRevealLLC |
| 合作伙伴网站的 URL | [https://kreveal.com](https://kreveal.com) |
| 隐私策略的 URL | [https://crosscheck.krevealaddins.com/docs/privacy.htm](https://crosscheck.krevealaddins.com/docs/privacy.htm) |
| 使用条款 URL | [https://crosscheck.krevealaddins.com/docs/license.htm](https://crosscheck.krevealaddins.com/docs/license.htm) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

kRevealLLC 提供了此信息，这些信息与此应用程序如何收集和存储组织数据以及您的组织将拥有对应用收集的数据的控制有关。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph](https://docs.microsoft.com/graph/permissions-reference)所需的任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD 应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| openid | 应用程序 | 不收集或使用任何数据。 | 创建帐户时将存储用户的电子邮件地址，供将来授权。 将记录登录和登录尝试。 | [5edad654-f2d5-41d8-bfc0-92c2735252e1](https://docs.microsoft.com/microsoft-365-app-certification/azure/5edad654-f2d5-41d8-bfc0-92c2735252e1) |


#### <a name="non-microsoft-services-used"></a>非Microsoft 服务使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>不Microsoft 服务非活动。



#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或最终用户可识别信息 (EUII) 是否出现在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>用户的电子邮件地址和登录日期。 保留，直到用户终止服务协议并随后删除。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>没有合作伙伴系统。

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

kRevealLLC 提供了此信息，这些信息与此应用程序如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件有关。

| **Information** | **响应** |
|:----------------|:-------------|
| 你是否与 Microsoft 标识平台 (Azure AD) ？  | 是 |
| 您是否已查看并遵循了集成清单中列出的所有适用的Microsoft 标识平台做法？  | 是 |
| 你的应用是否使用 MSAL (Microsoft 身份验证库) 进行身份验证？ | 否 |
| 你的应用是否支持条件访问策略？ | 否 |
| 应用是否请求方案最小特权权限？ | 是 |
| 应用的静态注册权限是否准确反映应用将动态和增量请求的权限？ | 是 |
| 你的应用是否支持多租户？ | 是 |
| 你的应用是否具有机密客户端？ | 否 |
| 你是否拥有为应用注册的所有重定向统一 (URI) URI？ | 是 |
| 对于你的应用，应避免使用什么？ | - 通配符重定向 URI，<br/>- OAuth2 隐式Flow，除非 SPA 需要<br/>- 资源所有者密码凭据 (ROPC) 流 |
| 你的应用是否公开任何 Web API？ | 否 |
| 你的应用是否使用预览 API？ | 否 |
| 你的应用是否使用已弃用 API？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
