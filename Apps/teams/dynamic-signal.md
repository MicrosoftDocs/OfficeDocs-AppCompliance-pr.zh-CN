---
title: 动态信号的动态信号的应用程序信息
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: 有关动态信号的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 0d3c59f6809bafe16eec2a1d709f40a980576b1b
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552223"
---
# <a name="dynamic-signal"></a>Dynamic Signal

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2019 年 12 月 16 日</p>

* <a href="https://teams.microsoft.com/l/app/6f98619e-a822-4a74-8ee9-af6a358f2750" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000102" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

由 Microsoft 动态信号提供的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | Dynamic Signal |
| ID | WA200000102 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | Dynamic Signal |
| 合作伙伴网站的 URL | [https://dynamicsignal.com](https://dynamicsignal.com) |
| "Teams应用程序信息"页的 URL | [https://support.dynamicsignal.com/hc/en-us/requests/new?tic...](https://support.dynamicsignal.com/hc/en-us/requests/new?ticket_form_id=360000290032) |
| 隐私策略的 URL | [https://dynamicsignal.com/privacy/](https://dynamicsignal.com/privacy/) |
| 使用条款 URL | [https://dynamicsignal.com/terms-of-use/platform-terms-of-us...](https://dynamicsignal.com/terms-of-use/platform-terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

此信息由动态信号提供，这些信息与此应用程序如何收集和存储组织数据以及组织将拥有对应用收集的数据的控制有关。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph所需的](https://docs.microsoft.com/graph/permissions-reference)任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD 应用 ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | delegated | 动态信号将用户从 Azure AD 同步到其平台，以允许用户实时简化激活和停用。 数据存储在动态信号中，以允许用户在同步过程中使用该应用程序。 | 读取特定用户的权限，以将动态信号平台用户与 Azure AD 同步。 | 79ff4a2a-e22b-47d5-94dc-ef76fe46af75 |
>| User.Read.All | delegated | 动态信号将用户从 Azure AD 同步到其平台，以允许用户实时简化激活和停用。 数据存储在动态信号中，以允许用户在同步过程中使用该应用程序。 | 读取特定用户的权限，以将动态信号平台用户与 Azure AD 同步。 | 79ff4a2a-e22b-47d5-94dc-ef76fe46af75 |
>| offline_access | delegated | 动态信号将用户从 Azure AD 同步到其平台，以允许用户实时简化激活和停用。 数据存储在动态信号中，以允许用户在同步过程中使用该应用程序。 | 保留对租户组和团队的访问权限。 | 79ff4a2a-e22b-47d5-94dc-ef76fe46af75 |
>| openid | delegated | 动态信号将用户从 Azure AD 同步到其平台，以允许用户实时简化激活和停用。 数据存储在动态信号中，以允许用户在同步过程中使用该应用程序。 | 使用动态信号应用程序对用户进行身份验证。 | 79ff4a2a-e22b-47d5-94dc-ef76fe46af75 |


#### <a name="non-microsoft-services-used"></a>非Microsoft 服务使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>不Microsoft 服务非活动。

#### <a name="data-access-via-bots"></a>通过机器人访问数据

如果此应用程序包含机器人或消息扩展，则它可以访问最终用户可识别信息 (EUII) ：名单 (名字、姓氏、显示名称、电子邮件地址) （团队中任何团队成员的姓名、姓氏、电子邮件地址) 或添加到其中聊天）。 此应用是否使用了此功能？

>| **访问 EUII 的理由？**  | **EUII 是否存储在数据库 (中) ？** | **存储 EUII 的理由** |
>|:--------------------------------|:---------------------|:--------------------------|
>| openid 使用 openid directory.readwrite.all 访问租户的域和组，向团队添加应用offline_access保留租户组和团队的访问权限 | openid 允许独立身份验证。 directory.readwrite.all 对租户的域和组的访问权限，将应用添加到团队 offline_access 保留对租户组和团队的访问权限 注意：动态信号的应用程序使用团队机器人将动态信号中创建的组和权限应用到 Teams 以便动态信号中处于活动状态的用户可以访问 Teams 内的相同组和用户。 |  |


#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或 EUII (最终用户可识别) 是否显示在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>动态信号应用和平台利用用户信息促进与 Microsoft Teams。 此信息适用于在动态信号平台中具有适当权限的用户。 相关信息包括名称、显示名称和电子邮件。 此信息根据具有动态信号许可证的各自组织的策略存储在动态信号平台日志中。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>注册期间收集并存储在动态信号平台中的 PII 数据包括：名字、姓氏、电子邮件/标识符以及品牌和/或代理合作伙伴设置的任何自定义字段。 当成员使用 oAuth 注册 Facebook 或 Twitter 时，会向动态信号平台显示一些公开的用户数据以预填充数据。 此数据包括姓名、位置和照片。 用户可以控制在社区 BIO 页面上向用户呈现的信息和数据。 成员可以选择加载个人照片或品牌照片、连接社交帐户/频道以及计划中的使用情况/点，以在生物页面中呈现。

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

下面将显示[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35740' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35740" target="_blank">在新建选项卡中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

