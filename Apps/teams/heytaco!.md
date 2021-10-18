---
title: 有关您"您好"的应用程序信息！ 由 HeyTaco！
ms.author: elmalova
author: elenamalova
ms.date: 09/09/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: 有关 HeyTaco！的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 72a600a577b773f1e3de08c7ef10b15b8007d52b
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 10/18/2021
ms.locfileid: "60444871"
---
# <a name="heytaco"></a>HeyTaco!

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2020 年 11 月 3 日</p>

* <a href="https://teams.microsoft.com/l/app/be8d11cf-265a-4974-9912-4ff28c29fc21" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001346" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

由 HeyTaco 提供的信息！ 到 Microsoft：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | HeyTaco! |
| ID | WA200001346 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | HeyTaco! |
| 合作伙伴网站的 URL | [https://www.heytaco.chat](https://www.heytaco.chat) |
| 隐私策略的 URL | [https://www.heytaco.chat/privacy](https://www.heytaco.chat/privacy) |
| 使用条款 URL | [https://www.heytaco.chat/terms](https://www.heytaco.chat/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

此信息由 HeyTaco 提供！ 关于此应用如何收集和存储组织数据，以及你的组织将拥有对应用收集的数据的控制。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph所需的](https://docs.microsoft.com/graph/permissions-reference)任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| email | delegated | 用于匹配从 Slack 到 MS 用户的数据传输Teams | 用于匹配从 Slack 到 MS 团队的数据传输的用户 | [be8d11cf-265a-4974-9912-4ff28c29fc21](https://docs.microsoft.com/microsoft-365-app-certification/azure/be8d11cf-265a-4974-9912-4ff28c29fc21) |
>| openid | delegated | 用于将用户登录到"你好"！ | 用于将用户登录到"你好"！ | [be8d11cf-265a-4974-9912-4ff28c29fc21](https://docs.microsoft.com/microsoft-365-app-certification/azure/be8d11cf-265a-4974-9912-4ff28c29fc21) |
>| 个人资料 | delegated | 用于捕获用户名、配置文件图像、时区偏移、租户 ID 和团队 ID | 用于捕获用户名、头像、时区偏移、租户 ID 和团队 ID | [be8d11cf-265a-4974-9912-4ff28c29fc21](https://docs.microsoft.com/microsoft-365-app-certification/azure/be8d11cf-265a-4974-9912-4ff28c29fc21) |


#### <a name="non-microsoft-services-used"></a>非Microsoft 服务已使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>不Microsoft 服务非活动。

#### <a name="data-access-via-bots"></a>通过机器人访问数据

如果此应用程序包含机器人或消息扩展，则它可以访问最终用户可识别信息 (EUII) ：名单 (名字、姓氏、显示名称、电子邮件地址) （团队中任何团队成员的姓名、姓氏、电子邮件地址) 或添加到其中聊天）。 此应用是否使用了此功能？

>| **访问 EUII 的理由？**  | **EUII 是否存储在数据库 (中) ？** | **存储 EUII 的理由** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| 告知用户他们已收到一个 taco 及其来自哪些人。 | 电子邮件地址 (用于从一个平台迁移到另一个) Name (for greeting the user) Profile image (for display on the leaderboard) Timezone (to properly show tacos given on activity page) Tenant ID (For aggregating data by tenant) Team ID (For aggregating data by team)   |  |


#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或最终用户可识别信息 (EUII) 是否出现在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>EUII 和 OII 未连接到任何日志记录。 仅错误类型和操作类型。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>HeyTaco! 数据库和数据备份托管在 AWS (Amazon Web Services) 。 

Amazon 的数据中心运营经过 ISO 27001、SOC 1 和 SOC 2/SSAE 16/ISAE 3402 (以前 SAS 70 类型 II ) 、PCI 级别 1、FISMA 中等和 Sarbanes-Oxley (SOX) 的认证。

当你通过我们的服务提交信息时，你的信息将受到保护和加密，无论是处于稳定还是通过安全连接传输。 我们实施各种安全措施来维护个人信息的安全。

我们配置了 Privileged Access Management 来保护我们服务器的数据。

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>是

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

下面将显示[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36139' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36139" target="_blank">在新建选项卡中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

