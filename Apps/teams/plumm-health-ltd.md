---
title: 一家由一家由一家电子健康公司提供的应用程序信息
ms.author: elmalova
author: elenamalova
ms.date: 10/14/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: 所有可用的安全与合规性信息（如，一张大写）、其数据处理策略、Microsoft Cloud App Security应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 8fef6e74339b611b06d39e6bbe32f9661e20656c
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 10/18/2021
ms.locfileid: "60429870"
---
# <a name="plumm"></a>Plumm

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2021 年 8 月 18 日</p>

* <a href="https://teams.microsoft.com/l/app/d66da813-3337-4f88-8e08-f01c0bbb8f34" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003326" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

由一名用户向 Microsoft 提供一些信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | Plumm |
| ID | WA200003326 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | Plumm Health LTD |
| 合作伙伴网站的 URL | [https://www.plummhealth.com](https://www.plummhealth.com) |
| 应用程序Teams页的 URL | [https://www.plummhealth.com/about-us](https://www.plummhealth.com/about-us) |
| 隐私策略的 URL | [https://www.plummhealth.com/privacy-policy](https://www.plummhealth.com/privacy-policy) |
| 使用条款 URL | [https://www.plummhealth.com/terms-of-use](https://www.plummhealth.com/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

此信息由一家由一家用户运行状况公司提供，用于了解此应用如何收集和存储组织数据，以及组织将拥有对应用收集的数据的控制。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph](https://docs.microsoft.com/graph/permissions-reference)所需的任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| TeamsActivity.Send | 应用程序 | 在此权限中，我们使用 userID。 这用于根据用户的服务使用情况向用户发送必要的通知。 这一点很重要，以便用户可以在我们的应用中收到其帐户的适当通知。 | 在此权限中，我们不会在数据库中存储任何数据。 事实上，我们使用 userID 根据每个用户的使用情况向每个用户发送相应的通知。 | [b1d1c038-a1f3-4802-be93-0f4a66589e73](https://docs.microsoft.com/microsoft-365-app-certification/azure/b1d1c038-a1f3-4802-be93-0f4a66589e73) |
>| TeamsAppInstallation.ReadWriteForUser.All | 应用程序 | 我们使用此权限接收安装 ID。 对于我们来说，这一点非常重要，以便能够向每个用户发送相应正确的通知。 | 我们不会使用此权限在应用中存储任何数据。 我们不需要它，因为我们只需要通过提供 userID 而获取的安装 ID。 这是在运行时动态获取的，因此无需存储安装 ID。 | [b1d1c038-a1f3-4802-be93-0f4a66589e73](https://docs.microsoft.com/microsoft-365-app-certification/azure/b1d1c038-a1f3-4802-be93-0f4a66589e73) |
>| User.Read | delegated | 我们正在通过此权限收集用户的姓名、图片和电子邮件。 这是必需的，以便我们能够识别单个用户，并且这些数据点应显示在所需的任何位置，如个人配置文件页和电子邮件/通知通信。 | 此权限允许应用查看用户的基本个人资料 (姓名、图片、电子邮件) 。 此数据将用于向我们显示用户的应用帐户上以及电子邮件通信和/或通知上的用户名和/或个人资料图片。 | [b1d1c038-a1f3-4802-be93-0f4a66589e73](https://docs.microsoft.com/microsoft-365-app-certification/azure/b1d1c038-a1f3-4802-be93-0f4a66589e73) |
>| User.Read.All | 应用程序 | 此权限允许应用在没有登录用户的情况下读取用户配置文件。 我们目前仅收集姓名、个人资料图片和电子邮件。 这是必需的，以便我们能够识别单个用户，并且这些数据点应显示在所需的任何位置，如个人配置文件页和电子邮件/通知通信。 | 此权限允许应用查看用户的基本个人资料 (姓名、图片、电子邮件) 。 此数据将用于向我们显示用户的应用帐户上以及电子邮件通信和/或通知上的用户名和/或个人资料图片。 | [b1d1c038-a1f3-4802-be93-0f4a66589e73](https://docs.microsoft.com/microsoft-365-app-certification/azure/b1d1c038-a1f3-4802-be93-0f4a66589e73) |
>| email | delegated | 收集用户的电子邮件 ID。 我们需要此数据，以便向用户授予服务访问权限，并登录到我们的应用，并接收有关他们的帐户和服务在此电子邮件 ID 上的通知。  | 电子邮件 ID 存储在数据库中。 我们需要存储电子邮件 ID，以便唯一标识用户、为用户提供访问应用的访问权限、帮助他们登录并帮助我们接收有关其帐户的通知。 例如，电子邮件 ID 为 abc@xyz.com 登录后，将能够访问我们的应用和服务Teams &quot; &quot; 此电子邮件 ID。 根据使用情况，我们将能够根据该用户/她的电子邮件 ID 向该用户发送通知。 | [b1d1c038-a1f3-4802-be93-0f4a66589e73](https://docs.microsoft.com/microsoft-365-app-certification/azure/b1d1c038-a1f3-4802-be93-0f4a66589e73) |
>| openid | delegated | 对于此权限，我们不会收集任何数据。  | 对于此权限，我们不会收集任何数据。 此权限允许用户使用工作电子邮件 ID 登录我们的应用，并允许应用查看基本用户配置文件信息。 | [b1d1c038-a1f3-4802-be93-0f4a66589e73](https://docs.microsoft.com/microsoft-365-app-certification/azure/b1d1c038-a1f3-4802-be93-0f4a66589e73) |
>| 个人资料 | delegated | 我们正在通过此权限收集用户的姓名、图片和电子邮件。 这是必需的，以便我们能够识别单个用户，并且这些数据点应显示在所需的任何位置，如个人配置文件页和电子邮件/通知通信。 | 此权限允许应用查看用户的基本个人资料 (姓名、图片、电子邮件) 。 此数据将用于向我们显示用户的应用帐户上以及电子邮件通信和/或通知上的用户名和/或个人资料图片。 | [b1d1c038-a1f3-4802-be93-0f4a66589e73](https://docs.microsoft.com/microsoft-365-app-certification/azure/b1d1c038-a1f3-4802-be93-0f4a66589e73) |


#### <a name="non-microsoft-services-used"></a>非Microsoft 服务已使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>| **所有非Microsoft 服务 OII 将转移到** |  **转移了哪些 OII？** | **转移 OII 的理由？** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Intercom | 名字、姓氏、电子邮件 | Intercom 是一种 CRM，可帮助我们管理与所有用户的通信。 因此，我们需要将用户的名字、姓氏和电子邮件 ID 发送到 CRM，以便向用户发送相应的邮件/电子邮件。 |

#### <a name="data-access-via-bots"></a>通过机器人访问数据

如果此应用程序包含机器人或消息扩展，则它可以访问最终用户可识别信息 (EUII) ：名单 (名字、姓氏、显示名称、电子邮件地址) （团队中任何团队成员的姓名、姓氏、电子邮件地址) 或添加到其中聊天）。 此应用是否使用了此功能？

>无法访问 EUII。


#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或 EUII (最终用户可识别) 是否显示在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>我们存储服务使用情况数据，如使用的会话数、已查看课程数、查看的会话数、会话日期等。我们会保留用户数据，直到用户明确要求删除或"忘记"其帐户。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>我们通过服务器管理发送到 CRM 的数据。 运行所需的最小数据将传递到 CRM (Intercom) 。 对于传递到 CRM 的数据、在 Intercom 上保留数据以及删除数据，用户具有完全控制权。 下面是查看 Intercom 的客户数据策略的链接： https://www.intercom.com/legal/terms-and-policies#customer-data

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>是

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>标识信息

此信息已由一家由一家用户运行状况公司提供，用于说明此应用如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件。

| **Information** | **响应** |
|:----------------|:-------------|
| 是否与 Microsoft 标识平台 (Azure AD) ？  | 是 |
| 您是否已查看并遵循了 Microsoft 标识平台 清单中列出的所有适用最佳做法？  | 是 |
| 你的应用是否使用 MSAL (Microsoft 身份验证库) 进行身份验证？ | 是 |
| 你的应用是否支持条件访问策略？ | 否 |
| 应用是否请求方案最小特权权限？ | 是 |
| 应用的静态注册权限是否准确反映应用将动态和增量请求的权限？ | 是 |
| 你的应用是否支持多租户？ | 否 |
| 你的应用是否具有机密客户端？ | 是 |
| 你是否拥有为应用注册的所有 (统一) URI？ | 是 |
| 对于你的应用，应避免使用什么？ | ,<br/><br/>- 资源所有者密码凭据 (ROPC) 流 |
| 你的应用是否公开任何 Web API？ | 是 |
| 您的权限模型是否仅在客户端应用程序收到正确同意时才允许呼叫成功？ | 是 |
| 你的应用是否使用预览 API？ | 否 |
| 你的应用是否使用已弃用 API？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
