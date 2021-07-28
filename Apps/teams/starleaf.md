---
title: StarLeaf 的应用程序信息
ms.author: elmalova
author: elenamalova
ms.date: 08/24/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: StarLeaf 的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 8f9878d4de6e09c283c6d13ee7351de9fb5f0eb8
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 07/22/2021
ms.locfileid: "53528228"
---
# <a name="starleaf"></a>StarLeaf

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2020 年 8 月 24 日</p>

* <a href="https://teams.microsoft.com/l/app/220b3db0-e3be-40df-8148-f0e0c33a986a" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000185" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

StarLeaf 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | StarLeaf |
| ID | WA200000185 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | StarLeaf |
| 合作伙伴网站的 URL | [https://www.starleaf.com](https://www.starleaf.com) |
| 隐私策略的 URL | [https://support.starleaf.com/legal-information/starleaf-pri...](https://support.starleaf.com/legal-information/starleaf-privacy-notice/) |
| 使用条款 URL | [https://support.starleaf.com/legal-information/starleaf-clo...](https://support.starleaf.com/legal-information/starleaf-cloud-services-customer-terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

StarLeaf 提供了此信息，这些信息与此应用程序如何收集和存储组织数据以及组织将拥有对应用收集的数据的控制有关。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph所需的](https://docs.microsoft.com/graph/permissions-reference)任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD 应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | 应用程序 | 我们存储会议的 iCalUId、会议的时间/日期、与会者电子邮件地址以及使用 Office.js 自定义属性接口在会议中读取和写入的 Single-Value-Extended-Property。 iCalUId 用于将用户的 outlook 日历中的&#8217;与服务上的视频会议关联。 时间/日期和与会者用于在正确的时间为服务上的合适人员提供视频会议。 SVEP 用于我们的 O365 加载项，为用户提供一个界面来设置有关服务上的视频会议的详细信息，例如录制。 | 用于订阅 webhook 通知，以跟踪用户对日历中的事件所做的更改，并更新服务以保持一致。 它还用于在用户与我们的 Teams 应用交互并安排服务上的会议时，在日历中创建事件。 | [6e86b349-768f-4953-ac2e-fb03f92db4be](https://docs.microsoft.com/microsoft-365-app-certification/azure/6e86b349-768f-4953-ac2e-fb03f92db4be) |
>| User.Read | 应用程序 | 我们存储 oauth 刷新令牌，以能够登录。 我们存储用户配置文件 ID，以便能够与该用户将来的 OAuth 尝试进行比较，并确保我们&#8217;存储其详细信息两次。  | 允许用户登录应用，并允许我们的应用&#8217;电子邮件地址，以将登录名与服务上的帐户相关联。  | [6e86b349-768f-4953-ac2e-fb03f92db4be](https://docs.microsoft.com/microsoft-365-app-certification/azure/6e86b349-768f-4953-ac2e-fb03f92db4be) |


#### <a name="non-microsoft-services-used"></a>非Microsoft 服务使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>| **所有非Microsoft 服务 OII 将转移到** |  **转移了哪些 OII？** | **转移 OII 的理由？** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| 如果出现技术支持问题，则数据可能会传输到 SalesForce 进行案例管理。 如果用户使用 PSTN 拨入功能，则呼叫将流经 Twilio、Plivo 或 Vox作为源 |  | 不适用 |

#### <a name="data-access-via-bots"></a>通过机器人访问数据

如果此应用程序包含机器人或消息扩展，则它可以访问最终用户可识别信息 (EUII) ：名单 (名字、姓氏、显示名称、电子邮件地址) （团队中任何团队成员的姓名、姓氏、电子邮件地址) 或添加到其中聊天）。 此应用是否使用了此功能？

>| **访问 EUII 的理由？**  | **EUII 是否存储在数据库 (中) ？** | **存储 EUII 的理由** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| 机器人访问团队名单，以便代表通过机器人预订会议的用户/主持人预订会议。 这允许 StarLeaf 通过一个按钮加入会议提供无缝加入体验。 | 名字、姓氏、电子邮件地址。 这允许 StarLeaf 机器人代表与机器人交互的用户/主机预订会议，并邀请团队的其他成员加入会议。 |  |


#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或 EUII (最终用户可识别) 是否显示在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>能。 日志包括用户名、IP 地址、呼叫详细信息记录、有关连接质量的信息 (数据包丢失、比特率) 、设备类型、呼叫进度。 技术支持团队和高级开发人员可以使用这些信息来诊断服务问题。 数据在 90 天后匿名处理。 保护此数据的控制措施根据 ISO/IEC 27001 认证进行审核。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>数据存储在用户&#8217;帐户所在的数据中心内的 StarLeaf&#8217;自己的日志服务器上，并备份到同一个管辖地内的一个或多个数据存储。 数据访问权限由使用按用户密码（经过强度检查）的单个用户帐户进行。 StarLeaf&#8217;针对 HR 系统和公司 Active Directory 组自动审核服务用户帐户，以在发现异常时向安全与合规团队发出警报。

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>是

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

下面将显示[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35997' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35997" target="_blank">在新建选项卡中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

