---
title: BlackBerry 的 BlackBerry AtHoc 的应用程序信息
ms.author: elmalova
author: elenamalova
ms.date: 08/05/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: BlackBerry AtHoc 的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security 应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 38e85981b12faf81ce3b737300aacdbee42dc2a1
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 10/16/2021
ms.locfileid: "60415199"
---
# <a name="blackberry-athoc"></a>BlackBerry AtHoc

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2021 年 6 月 23 日</p>

* <a href="https://teams.microsoft.com/l/app/f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003065" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

BlackBerry 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | BlackBerry AtHoc |
| ID | WA200003065 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | BlackBerry |
| 合作伙伴网站的 URL | [https://www.blackberry.com](https://www.blackberry.com) |
| Teams信息页的 URL | [https://www.blackberry.com/us/en/products/blackberry-athoc](https://www.blackberry.com/us/en/products/blackberry-athoc) |
| 隐私策略的 URL | [https://www.blackberry.com/us/en/legal/privacy-policy](https://www.blackberry.com/us/en/legal/privacy-policy) |
| 使用条款 URL | [https://www.athoc.com/pss/terms.html#](https://www.athoc.com/pss/terms.html#) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

BlackBerry 提供了此信息，这些信息与此应用程序如何收集和存储组织数据以及您的组织将拥有对应用收集的数据的控制有关。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph所需的](https://docs.microsoft.com/graph/permissions-reference)任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| ChannelMessage.Send | delegated | 我们访问用户&#8217;基本详细信息，如主体名称，并链接到团队常规频道 (已登录用户有权) 向团队发送警报卡。 | 我们不&#8217;数据库，而是在自动程序内存中存储用户数据。 我们将已登录用户的主体名称、AAD令牌、BlackBerry AtHoc 令牌、BlackBerry AtHoc 服务器首选项/配置存储在自动程序内存中。 需要将 API 请求发送到 Microsoft Graph API 和 BlackBerry AtHoc Server 的信息。 | [f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7](https://docs.microsoft.com/microsoft-365-app-certification/azure/f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7) |
>| Group.Read.All | delegated | 我们访问用户&#8217;基本详细信息，如主体名称，并链接到团队常规频道 (已登录用户有权) 向团队发送警报卡。 | 我们不&#8217;数据库，而是在自动程序内存中存储用户数据。 我们将已登录用户的主体名称、AAD令牌、BlackBerry AtHoc 令牌、BlackBerry AtHoc 服务器首选项/配置存储在自动程序内存中。 需要将 API 请求发送到 Microsoft Graph API 和 BlackBerry AtHoc Server 的信息。 | [f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7](https://docs.microsoft.com/microsoft-365-app-certification/azure/f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7) |
>| User.Read | delegated | 我们访问用户&#8217;基本详细信息，如主体名称，并链接到团队常规频道 (已登录用户有权) 向团队发送警报卡。 | 我们不&#8217;数据库，而是在自动程序内存中存储用户数据。 我们将已登录用户的主体名称、AAD令牌、BlackBerry AtHoc 令牌、BlackBerry AtHoc 服务器首选项/配置存储在自动程序内存中。 需要将 API 请求发送到 Microsoft Graph API 和 BlackBerry AtHoc Server 的信息。 | [f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7](https://docs.microsoft.com/microsoft-365-app-certification/azure/f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7) |
>| email | delegated | 我们访问用户&#8217;基本详细信息，如主体名称，并链接到团队常规频道 (已登录用户有权) 向团队发送警报卡。 | 我们不&#8217;数据库，而是在自动程序内存中存储用户数据。 我们将已登录用户的主体名称、AAD令牌、BlackBerry AtHoc 令牌、BlackBerry AtHoc 服务器首选项/配置存储在自动程序内存中。 需要将 API 请求发送到 Microsoft Graph API 和 BlackBerry AtHoc Server 的信息。 | [f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7](https://docs.microsoft.com/microsoft-365-app-certification/azure/f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7) |
>| openid | delegated | 我们访问用户&#8217;基本详细信息，如主体名称，并链接到团队常规频道 (已登录用户有权) 向团队发送警报卡。 | 我们不&#8217;数据库，而是在自动程序内存中存储用户数据。 我们将已登录用户的主体名称、AAD令牌、BlackBerry AtHoc 令牌、BlackBerry AtHoc 服务器首选项/配置存储在自动程序内存中。 需要将 API 请求发送到 Microsoft Graph API 和 BlackBerry AtHoc Server 的信息。 | [f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7](https://docs.microsoft.com/microsoft-365-app-certification/azure/f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7) |
>| 个人资料 | delegated | 我们访问用户&#8217;基本详细信息，如主体名称，并链接到团队常规频道 (已登录用户有权) 向团队发送警报卡。 | 我们不&#8217;数据库，而是在自动程序内存中存储用户数据。 我们将已登录用户的主体名称、AAD令牌、BlackBerry AtHoc 令牌、BlackBerry AtHoc 服务器首选项/配置存储在自动程序内存中。 需要将 API 请求发送到 Microsoft Graph API 和 BlackBerry AtHoc Server 的信息。 | [f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7](https://docs.microsoft.com/microsoft-365-app-certification/azure/f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7) |


#### <a name="non-microsoft-services-used"></a>非Microsoft 服务已使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>不Microsoft 服务非活动。

#### <a name="data-access-via-bots"></a>通过机器人访问数据

如果此应用程序包含机器人或消息扩展，则它可以访问最终用户可识别信息 (EUII) ：名单 (名字、姓氏、显示名称、电子邮件地址) （团队中任何团队成员的姓名、姓氏、电子邮件地址) 或添加到其中聊天）。 此应用是否使用了此功能？

>无法访问 EUII。


#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或最终用户可识别信息 (EUII) 是否出现在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>应用程序遥测或日志中不显示 OII 或 EUII。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>不适用

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>是

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

下面将显示[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/12225' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/12225" target="_blank">在新建选项卡中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>标识信息

BlackBerry 已提供有关此应用如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件的信息。

| **Information** | **响应** |
|:----------------|:-------------|
| 是否与 Microsoft 标识平台 (Azure AD) ？  | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

