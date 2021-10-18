---
title: 由 88 Limited 提醒的应用程序信息
ms.author: elmalova
author: elenamalova
ms.date: 08/18/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: 所有可用的提醒安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 895830def92409d04bd92f165668a15eba8995ce
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 10/18/2021
ms.locfileid: "60428385"
---
# <a name="remind"></a>Remind

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2020 年 9 月 28 日</p>

* <a href="https://teams.microsoft.com/l/app/88546d4f-9973-4716-98e4-cd181c04bc2d" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001444" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

由 88 但仅限于 Microsoft 的微软提供的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | Remind |
| ID | WA200001444 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | 88 Ventures Limited |
| 合作伙伴网站的 URL | [https://moonbearapp.com](https://moonbearapp.com) |
| 隐私策略的 URL | [https://teamsreminder.app/#privacy](https://teamsreminder.app/#privacy) |
| 使用条款 URL | [https://teamsreminder.app/#terms](https://teamsreminder.app/#terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

此信息由 88 Limited 提供有关此应用如何收集和存储组织数据以及您的组织将拥有对应用收集的数据的控制的信息。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph](https://docs.microsoft.com/graph/permissions-reference)所需的任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Directory.Read.All | delegated | 数据库中未存储任何信息 | 允许管理员浏览已设置公共提醒的用户的组织用户目录 | [88546d4f-9973-4716-98e4-cd181c04bc2d](https://docs.microsoft.com/microsoft-365-app-certification/azure/88546d4f-9973-4716-98e4-cd181c04bc2d) |


#### <a name="non-microsoft-services-used"></a>非Microsoft 服务已使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>不Microsoft 服务非活动。

#### <a name="data-access-via-bots"></a>通过机器人访问数据

如果此应用程序包含机器人或消息扩展，则它可以访问最终用户可识别信息 (EUII) ：名单 (名字、姓氏、显示名称、电子邮件地址) （团队中任何团队成员的姓名、姓氏、电子邮件地址) 或添加到其中聊天）。 此应用是否使用了此功能？

>| **访问 EUII 的理由？**  | **EUII 是否存储在数据库 () ？** | **存储 EUII 的理由** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>|  (1) 当用户在邮件上设置提醒时，机器人会尝试获取最初发送消息的人的姓名，以在用户提醒列表中显示该信息 (2) 当用户为另一个频道或聊天成员设置提醒时，机器人会尝试获取标识 (用户或聊天机器人) 以及被提及用户的名称以在用户的提醒列表 |  (1) 当用户在邮件上设置提醒时，机器人会尝试获取最初发送消息的人的姓名，以在用户提醒列表中显示该信息 (2) 当用户为另一个频道或聊天成员设置提醒时，机器人会尝试获取标识 (用户或聊天机器人) 以及被提及用户的名称以在用户的提醒列表 |  |


#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或 EUII (最终用户可识别) 是否显示在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>不与遥测或日志记录功能共享 EEUI 和 OII

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>静态加密：双因素 (2FA) 限制对 IT 基础结构和客户数据（系统之间的受保护 IP 范围）的访问

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

下面将显示[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36058' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36058" target="_blank">在新建选项卡中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

