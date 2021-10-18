---
title: Lucid Software 的 Lucidspark 应用程序信息
ms.author: elmalova
author: elenamalova
ms.date: 06/14/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Lucidspark 的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 863883b8e18984bc6a52ed2829811b74e99bf34c
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 10/18/2021
ms.locfileid: "60429700"
---
# <a name="lucidspark"></a>Lucidspark

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2021 年 5 月 13 日</p>

* <a href="https://teams.microsoft.com/l/app/e9ab21fa-5fd5-48bb-a85d-4de7ced89cd1" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002583" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

Lucid Software 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | Lucidspark |
| ID | WA200002583 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | Lucid Software |
| 合作伙伴网站的 URL | [https://lucid.co](https://lucid.co) |
| Teams信息页的 URL | [https://lucidchart.zendesk.com](https://lucidchart.zendesk.com) |
| 隐私策略的 URL | [https://lucid.co/privacy](https://lucid.co/privacy) |
| 使用条款 URL | [https://lucid.co/tos](https://lucid.co/tos) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

此信息由 Lucid Software 提供，用于了解此应用如何收集和存储组织数据，以及组织对应用收集的数据的控制。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph所需的](https://docs.microsoft.com/graph/permissions-reference)任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| email | delegated | 姓名和电子邮件地址。 | 电子邮件、openid 和配置文件权限使 Lucidspark 可以生成用户的 openid 令牌，并获取有关该用户的足够基本信息，以便在必要时为用户注册 Lucidspark 帐户。 为了验证从 Microsoft 返回的数据，我们请求获取其响应已签名的公钥。 作为 SSO 流的一部分，不会从 Microsoft 接收或发送给 Microsoft 其他数据。 | [3557d5c0-bcab-410b-8a03-f7045aa48de0](https://docs.microsoft.com/microsoft-365-app-certification/azure/3557d5c0-bcab-410b-8a03-f7045aa48de0) |
>| openid | delegated | 姓名和电子邮件地址。 | 电子邮件、openid 和配置文件权限使 Lucidspark 可以生成用户的 openid 令牌，并获取有关该用户的足够基本信息，以便在必要时为用户注册 Lucidspark 帐户。 为了验证从 Microsoft 返回的数据，我们请求获取其响应已签名的公钥。 作为 SSO 流的一部分，不会从 Microsoft 接收或发送给 Microsoft 其他数据。 | [3557d5c0-bcab-410b-8a03-f7045aa48de0](https://docs.microsoft.com/microsoft-365-app-certification/azure/3557d5c0-bcab-410b-8a03-f7045aa48de0) |
>| 个人资料 | delegated | 姓名和电子邮件地址。 | 电子邮件、openid 和配置文件权限使 Lucidspark 可以生成用户的 openid 令牌，并获取有关该用户的足够基本信息，以便在必要时为用户注册 Lucidspark 帐户。 为了验证从 Microsoft 返回的数据，我们请求获取其响应已签名的公钥。 作为 SSO 流的一部分，不会从 Microsoft 接收或发送给 Microsoft 其他数据。 | [3557d5c0-bcab-410b-8a03-f7045aa48de0](https://docs.microsoft.com/microsoft-365-app-certification/azure/3557d5c0-bcab-410b-8a03-f7045aa48de0) |


#### <a name="non-microsoft-services-used"></a>非Microsoft 服务已使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>| **所有非Microsoft 服务 OII 将转移到** |  **转移了哪些 OII？** | **转移 OII 的理由？** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Lucidspark 和 lucidchart 数据存储在 AWS 和Flakeflake 中 | 组织名称、联系人信息和许可证级别 | 我们不使用任何 Microsoft API。 我们使用 openID 获取基本用户数据来执行 SSO。 我们使用其文件选取器 API，但这不会授予我们访问用户文件的访问权限，只是提供通过选取器提交给我们的文件的访问权限。 |

#### <a name="data-access-via-bots"></a>通过机器人访问数据

如果此应用程序包含机器人或消息扩展，则它可以访问最终用户可识别信息 (EUII) ：名单 (名字、姓氏、显示名称、电子邮件地址) （团队中任何团队成员的姓名、姓氏、电子邮件地址) 或添加到其中聊天）。 此应用是否使用了此功能？

>无法访问 EUII。


#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或最终用户可识别信息 (EUII) 是否出现在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>出于安全和支持原因，我们将记录电子邮件和 IP 地址。 第三方系统中记录日志的所有访问实际上 &amp; 不可更改。 对日志的访问需要 MFA。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>Lucidspark 和 lucidchart 数据存储在 AWS 中。 它处于其余时间且正在传输中加密。 Lucid 使用最小特权和 MFA 规则。

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

下面将显示[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/39482' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/39482" target="_blank">在新建选项卡中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>标识信息

此信息由 Lucid Software 提供有关此应用程序如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件的信息。

| **Information** | **响应** |
|:----------------|:-------------|
| 是否与 Microsoft 标识平台 (Azure AD) ？  | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
