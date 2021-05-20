---
title: Invillia 开发人员的 Instation 应用程序信息
ms.author: elmalova
author: elenamalova
ms.date: 08/06/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: InStation 的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 40c86e4284ed201fedf63bfe3bbd7570b61049b7
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552243"
---
# <a name="instation"></a>InStation

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2020 年 8 月 6 日</p>

* <a href="https://teams.microsoft.com/l/app/0c841985-9919-4c0a-b87d-b06b301148b3" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001701" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

开发人员 Invillia 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | InStation |
| ID | WA200001701 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | Developers Invillia |
| 合作伙伴网站的 URL | [https://instation.invillia.com/](https://instation.invillia.com/) |
| 隐私策略的 URL | [https://instation.invillia.com/terms#privacy-policy](https://instation.invillia.com/terms#privacy-policy) |
| 使用条款 URL | [https://instation.invillia.com/terms#terms-of-use](https://instation.invillia.com/terms#terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

开发人员 Invillia 提供了此信息，这些信息与此应用程序如何收集和存储组织数据以及您的组织将拥有对应用收集的数据的控制有关。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph所需的](https://docs.microsoft.com/graph/permissions-reference)任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD 应用 ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| OnlineMeetings.Read.All | delegated | stores：id、join_url、join_web_url 和 chat_id。 允许应用创建会议 | stores：id、join_url、join_web_url 和 chat_id。 允许应用创建会议 | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| OnlineMeetings.ReadWrite.All | delegated | stores：id、join_url、join_web_url 和 chat_id。 允许应用创建会议 | stores：id、join_url、join_web_url 和 chat_id。 允许应用创建会议 | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| Presence.Read | delegated | 允许应用在其第一步登录组织 | 活动和可显示性。 允许应用捕获用户状态; | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| Presence.Read.All | delegated | 允许应用在其第一步登录组织， | 活动和可显示性。 允许应用捕获用户状态; | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| User.Read | delegated | 存储：id、mail、显示名称、surname 和 picture。 允许应用搜索用户数据; | 存储：id、mail、显示名称、surname 和 picture。 允许应用搜索用户数据; | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| User.Read.All | delegated | 存储：id、mail、显示名称、surname 和 picture。 允许应用搜索用户数据; | 存储：id、mail、显示名称、surname 和 picture。 允许应用搜索用户数据; | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| email | delegated | 允许应用捕获管理员&#180;首次登录时的基本信息 | 允许应用捕获管理员&#180;首次登录时的基本信息 | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| offline_access | delegated | 存储：令牌和刷新令牌。 允许应用对 MS 令牌执行刷新 | 存储：令牌和刷新令牌。 允许应用对 MS 令牌执行刷新 | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| openid | delegated | 允许应用在其第一步登录组织 | 允许应用在其第一步登录组织 | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| 个人资料 | delegated | 允许应用捕获管理员&#180;首次登录时的基本信息; | 允许应用捕获管理员&#180;首次登录时的基本信息; | 0c841985-9919-4c0a-b87d-b06b301148b3 |


#### <a name="non-microsoft-services-used"></a>非Microsoft 服务使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>不Microsoft 服务非活动。

#### <a name="data-access-via-bots"></a>通过机器人访问数据

如果此应用程序包含机器人或消息扩展，则它可以访问最终用户可识别信息 (EUII) ：名单 (名字、姓氏、显示名称、电子邮件地址) （团队中任何团队成员的姓名、姓氏、电子邮件地址) 或添加到其中聊天）。 此应用是否使用了此功能？

>无法访问 EUII。


#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或 EUII (最终用户可识别) 是否显示在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>我们仅在应用程序中保存用户使用率日志。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>我们仅在应用程序中保存用户使用率日志。 不保密，无需加密，只有我们的特定管理员有权访问此数据。

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

下面将显示[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35954' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35954" target="_blank">在新建选项卡中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

