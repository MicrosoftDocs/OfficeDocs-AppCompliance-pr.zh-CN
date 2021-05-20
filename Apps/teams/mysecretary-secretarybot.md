---
title: MySecretary 的为一位用户提供一些应用程序信息，这些应用程序信息由 MySecretary 提供
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: 所有 Available security and compliance information for一切 Available security and compliance information for 一切，其数据处理策略、Microsoft Cloud App Security应用程序目录信息，以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: bff3e6ebffc94861dc4112375ac943124b4fe386
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 05/19/2021
ms.locfileid: "52551882"
---
# <a name="secretarybot"></a>SecretaryBot

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2019 年 12 月 16 日</p>

* <a href="https://teams.microsoft.com/l/app/256ff1bc-fd16-4f82-aeb3-8a6977ff2ec4" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381085" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

MySecretary 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | SecretaryBot |
| ID | WA104381085 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | MySecretary |
| 合作伙伴网站的 URL | [https://secretarybot.wordpress.com/](https://secretarybot.wordpress.com/) |
| "Teams应用程序信息"页的 URL | [https://secretarybot.wordpress.com/faq/](https://secretarybot.wordpress.com/faq/) |
| 隐私策略的 URL | [https://secretarybot.wordpress.com/privacy-policy/](https://secretarybot.wordpress.com/privacy-policy/) |
| 使用条款 URL | [https://secretarybot.wordpress.com/terms-of-use/](https://secretarybot.wordpress.com/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

MySecretary 提供了此信息，这些信息与此应用程序如何收集和存储组织数据以及您的组织将拥有对应用收集的数据的控制有关。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph所需的](https://docs.microsoft.com/graph/permissions-reference)任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD 应用 ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.Read.Shared | delegated |  | 获取用户及其同事的空闲时间信息。 |  |
>| Calendars.ReadWrite | delegated |  | 发送会议请求，而不是用户。 |  |
>| MailboxSettings.Read | delegated | 用于显示正确语言存储语言。 节省时区以正确调用 MS Graph日历 API | 获取用户的语言和时区设置。 |  |
>| People.Read | delegated |  | 尝试查找与用户具有强关系的同事。 |  |
>| User.Read | delegated | 存储用户名、城市、国家/地区以及用于用户分析的语言。 存储用于联系客户的电子邮件。 我们从未使用过电子邮件地址，但可能用于提供支持。 | 尝试查找用户的国家/地区及首选语言。 它用于 MailboxSettings.Read 的备份。 |  |
>| email | delegated | 具体步骤请见上文。 | 用于存储电子邮件。 |  |
>| openid | delegated |  | 对于 OpenID 身份验证。 |  |
>| 个人资料 | delegated | 保存 OID 以在 MS 标识系统中标识用户的唯一 ID。 | 获取用户名和 OID。 以后尝试使用 OID Outlook Addin 连接。 |  |


#### <a name="non-microsoft-services-used"></a>非Microsoft 服务使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>不Microsoft 服务非活动。

#### <a name="data-access-via-bots"></a>通过机器人访问数据

如果此应用程序包含机器人或消息扩展，则它可以访问最终用户可识别信息 (EUII) ：名单 (名字、姓氏、显示名称、电子邮件地址) （团队中任何团队成员的姓名、姓氏、电子邮件地址) 或添加到其中聊天）。 此应用是否使用了此功能？

>| **访问 EUII 的理由？**  | **EUII 是否存储在数据库 (中) ？** | **存储 EUII 的理由** |
>|:--------------------------------|:---------------------|:--------------------------|
>| 使用此信息安排团队会议 | 否 |  |


#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或 EUII (最终用户可识别) 是否显示在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>OII 或 EUII 数据确实显示在遥测或日志中。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>我们尚未向最终用户提供管理控制，但如果最终用户请求我们删除数据，我们可以按照他们的请求操作。


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

下面将显示[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35678' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35678" target="_blank">在新建选项卡中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

