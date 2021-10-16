---
title: Vonage 商业通信的应用程序信息（按 Vonage）
ms.author: elmalova
author: elenamalova
ms.date: 08/05/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Vonage Business Communications 的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security 应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 7b87151f6898c83a24b4878a3c6e60b7d951c974
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 10/16/2021
ms.locfileid: "60414378"
---
# <a name="vonage-business-communications"></a>Vonage Business Communications

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2021 年 6 月 23 日</p>

* <a href="https://teams.microsoft.com/l/app/47c6b242-a067-426c-9a02-0f680a42c488" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002988" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

Vonage 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | Vonage Business Communications |
| ID | WA200002988 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | Vonage |
| 合作伙伴网站的 URL | [https://www.vonage.com](https://www.vonage.com) |
| "Teams应用程序信息"页的 URL | [https://www.vonage.com/unified-communications/](https://www.vonage.com/unified-communications/) |
| 隐私策略的 URL | [https://www.vonage.com/legal/privacy-policy](https://www.vonage.com/legal/privacy-policy) |
| 使用条款 URL | [https://www.vonage.com/legal/unified-communications/tos/glo...](https://www.vonage.com/legal/unified-communications/tos/global-vbc-tos/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

Vonage 提供了此信息，这些信息与此应用程序如何收集和存储组织数据以及您的组织将拥有对应用收集的数据的控制有关。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph](https://docs.microsoft.com/graph/permissions-reference)所需的任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| TeamsActivity.Send | 应用程序 | 没有存储具有此权限的数据 | 没有存储具有此权限的数据 | [1d8a304e-ea67-4aa2-9345-2793419cf83f](https://docs.microsoft.com/microsoft-365-app-certification/azure/1d8a304e-ea67-4aa2-9345-2793419cf83f) |
>| User.Read | delegated | 获取 Azure 用户 ID 和租户 ID，以便我们稍后可以向此用户发送通知。 |  获取 Azure 用户 ID 和租户 ID，以便稍后我们可以在用户收到短信/彩信时向该用户发送通知 | [1d8a304e-ea67-4aa2-9345-2793419cf83f](https://docs.microsoft.com/microsoft-365-app-certification/azure/1d8a304e-ea67-4aa2-9345-2793419cf83f) |


#### <a name="non-microsoft-services-used"></a>非Microsoft 服务已使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>不Microsoft 服务非活动。

#### <a name="data-access-via-bots"></a>通过机器人访问数据

如果此应用程序包含机器人或消息扩展，则它可以访问最终用户可识别信息 (EUII) ：名单 (名字、姓氏、显示名称、电子邮件地址) （团队中任何团队成员的姓名、姓氏、电子邮件地址) 或添加到其中聊天）。 此应用是否使用了此功能？

>无法访问 EUII。


#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或 EUII (最终用户可识别) 是否显示在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>应用程序遥测或日志中不显示 OII 或 EUII。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>我们将 usersId 和 tenantId 存储在 AWS 上的安全数据库中，一旦用户注销，该信息将被删除。

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>是

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

下面将显示[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/38766' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/38766" target="_blank">在新建选项卡中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>标识信息

Vonage 提供了此信息，这些信息与此应用程序如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件有关。

| **Information** | **响应** |
|:----------------|:-------------|
| 是否与 Microsoft 标识平台 (Azure AD) ？  | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

