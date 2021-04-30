---
title: Zoom.ai Inc Zoom.ai 会议助理的应用程序信息
ms.author: elmalova
author: elenamalova
ms.date: 03/17/2020
ms.topic: article
ms.service: attestation
description: 有关会议助理的所有可用 Zoom.ai 信息、其数据处理策略、Microsoft Cloud App Security应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: c5928d1ba26624bbae26fdf0dab09fbb4ddcded6
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/30/2021
ms.locfileid: "52093201"
---
# <a name="zoomai-meeting-assistant"></a>Zoom.ai Meeting Assistant

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2020 年 3 月 17 日</p>

* <a href="https://teams.microsoft.com/l/app/cac7469b-37cc-44f5-bf08-ff6654d35819" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000150" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

Zoom.ai Inc 向 Microsoft 提供的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | Zoom.ai Meeting Assistant |
| ID | WA200000150 |
| 功能 | 机器人，选项卡，连接器 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | Zoom.ai Inc |
| 合作伙伴网站的 URL | [https://zoom.ai](https://zoom.ai) |
| "Teams应用程序信息"页的 URL | [https://faq.zoom.ai/](https://faq.zoom.ai/) |
| 隐私策略的 URL | [https://zoom.ai/privacy](https://zoom.ai/privacy) |
| 使用条款 URL | [https://zoom.ai/terms-of-use](https://zoom.ai/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

此信息由 Zoom.ai Inc 提供有关此应用程序如何收集和存储组织数据以及您的组织将拥有对应用收集的数据的控制的信息。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph所需的](https://docs.microsoft.com/graph/permissions-reference)任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD 应用 ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | 两者 | 会议缓存在 Azure 上的 mongoDB 中，但说明已加密。 | 访问用户的日历事件。 |  |
>| Contacts.ReadWrite | 两者 | 联系人姓名和电子邮件地址。 | 读取用户的联系人 (以便我们可以邀请他们参加) 。 |  |
>| Group.Read.All | 两者 | 组名称和成员。 |  (可选) 读取公司用户组 (组或) 。 |  |
>| Mail.Read | 两者 | 联系人电子邮件/名称、交互频率/频率。 |  (可选) 用于将电子邮件元数据读取到用户最重要的联系人通过 (联系人机器学习) 。 |  |
>| MailboxSettings.ReadWrite | 两者 | 用户的时区。 | 用户的时区。 |  |
>| User.Read.All | 两者 | 用户的名称 &amp; 电子邮件 (联系人联系人) 。 |  (可选) 读取公司 (与同事或同事进行)  |  |
>| offline_access | 应用程序 | 否 | 我们需要随时通过后端读取和写入，无需用户存在。 |  |


#### <a name="non-microsoft-services-used"></a>非Microsoft 服务使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>不Microsoft 服务非活动。

#### <a name="data-access-via-bots"></a>通过机器人访问数据

如果此应用程序包含机器人或消息扩展，则它可以访问最终用户可识别信息 (EUII) ：名单 (名字、姓氏、显示名称、电子邮件地址) （团队中任何团队成员的姓名、姓氏、电子邮件地址) 或添加到其中聊天）。 此应用是否使用了此功能？

>| **访问 EUII 的理由？**  | **EUII 是否存储在数据库 (中) ？** | **存储 EUII 的理由** |
>|:--------------------------------|:---------------------|:--------------------------|
>| 导入同事的姓名/电子邮件，以便我们的会议助理机器人可以安排与同事的会议 | 名称 &amp; 电子邮件。 两者均存储在我们的数据库中以便快速查找和进行部分名称 (例如。 与 Joe P)  |  |



#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或 EUII (最终用户可识别) 是否显示在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>用户和/或联系人的电子邮件地址用于将事件记录到日志提供程序 LogIP。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>所有数据都存储在位于加拿大温哥华的 MS Azure 云数据中心中。 多个字段使用 AES256 进行加密。 只有工程师和后端服务器可以通过用户/服务级别凭据访问数据库。

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

下面将显示[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35668' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35668" target="_blank">在新建选项卡中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

