---
title: RingCentral by RingCentral， Inc. 的应用程序信息
ms.author: elmalova
author: elenamalova
ms.date: 05/18/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: RingCentral 的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: bb0787720195363368e3d822e45f173acee67870
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 07/22/2021
ms.locfileid: "53525396"
---
# <a name="ringcentral"></a>RingCentral

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2021 年 5 月 18 日</p>

* <a href="https://teams.microsoft.com/l/app/2f285d77-896a-4c5f-901e-0902316003b5" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000135" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

RingCentral， Inc. 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | RingCentral |
| ID | WA200000135 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | RingCentral, Inc. |
| 合作伙伴网站的 URL | [https://www.ringcentral.com](https://www.ringcentral.com) |
| "Teams应用程序信息"页的 URL | [https://www.ringcentral.com/apps/ringcentral-for-microsoft-...](https://www.ringcentral.com/apps/ringcentral-for-microsoft-teams) |
| 隐私策略的 URL | [https://www.ringcentral.com/legal/privacy-notice.html](https://www.ringcentral.com/legal/privacy-notice.html) |
| 使用条款 URL | [https://www.ringcentral.com/legal/last-update-October-15-20...](https://www.ringcentral.com/legal/last-update-October-15-2019/eulatos.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

此信息由 RingCentral， Inc. 提供，它有关此应用程序如何收集和存储组织数据，以及你的组织将拥有对应用收集的数据的控制。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph所需的](https://docs.microsoft.com/graph/permissions-reference)任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD 应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | delegated |  允许应用程序通过日历发送会议邀请事件 | 无 | [ 0dd4bfdf-dc86-4f05-9991-a14bc0144ebf](https://docs.microsoft.com/microsoft-365-app-certification/azure/ 0dd4bfdf-dc86-4f05-9991-a14bc0144ebf) |
>| offline_access | delegated |  允许应用程序获取和更新 oauth 令牌 |  访问令牌、用于访问 MS Graph API 的刷新令牌 | [ 0dd4bfdf-dc86-4f05-9991-a14bc0144ebf](https://docs.microsoft.com/microsoft-365-app-certification/azure/ 0dd4bfdf-dc86-4f05-9991-a14bc0144ebf) |
>| User.Read | delegated |  允许应用读取用户的基本个人资料&#8217;电子邮件 (名称) ，以便最终进行联系人匹配。 并且允许用户登录，并关联其 O365 帐户和 RingCentral 帐户 |  电子邮件、名字、姓氏 | [0dd4bfdf-dc86-4f05-9991-a14bc0144ebf](https://docs.microsoft.com/microsoft-365-app-certification/azure/0dd4bfdf-dc86-4f05-9991-a14bc0144ebf) |
>| User.Read.All | delegated | 允许应用程序读取用户的完整个人资料以及电话号码，以便使用我们的服务进行电话呼叫。 | 无 | [0dd4bfdf-dc86-4f05-9991-a14bc0144ebf](https://docs.microsoft.com/microsoft-365-app-certification/azure/0dd4bfdf-dc86-4f05-9991-a14bc0144ebf) |


#### <a name="non-microsoft-services-used"></a>非Microsoft 服务使用

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

>当我们使用另一个组织时，我们仍然控制你的个人信息。我们也有严格的控制措施，以确保&#8217;受保护。 最后，上面的部分介绍了将个人信息共享给其他团体、政府机构和执法机构的情况。  当我们与其他组织共享你的信息时，&#8217;尽可能确保&#8217;受保护。

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>不支持

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

下面将显示[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/11833' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/11833" target="_blank">在新建选项卡中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>标识信息

此信息由 RingCentral， Inc. 提供，用于说明此应用如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件。

| **Information** | **响应** |
|:----------------|:-------------|
| 你是否与 Microsoft 标识平台 (Azure AD) ？  | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
