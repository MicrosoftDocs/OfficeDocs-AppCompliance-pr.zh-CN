---
title: Karma 的应用程序信息（由 Sliday LTD 提供）
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Karma 的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: f8d4c9fdb00dbf16007ca1840aa210ad795dfa61
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 05/06/2021
ms.locfileid: "52251131"
---
# <a name="karma"></a>Karma

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2019 年 12 月 16 日</p>

* <a href="https://teams.microsoft.com/l/app/9ff28b02-ccc5-4cac-9d17-4cf6987c371f" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381640" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

由 Sliday LTD 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | Karma |
| ID | WA104381640 |
| 功能 | 机器人，选项卡，消息传递扩展 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | Sliday LTD |
| 合作伙伴网站的 URL | [https://karmabot.chat/ms](https://karmabot.chat/ms) |
| "Teams应用程序信息"页的 URL | [https://karmabot.readme.io/](https://karmabot.readme.io/) |
| 隐私策略的 URL | [https://karmabot.readme.io/v3.0/docs/privacy-policy-for-mic...](https://karmabot.readme.io/v3.0/docs/privacy-policy-for-microsoft-teams) |
| 使用条款 URL | [https://karmabot.readme.io/docs/karma-end-user-license-agre...](https://karmabot.readme.io/docs/karma-end-user-license-agreement-eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

此信息由 Sliday LTD 提供，用于了解此应用如何收集和存储组织数据，以及您的组织将拥有对应用收集的数据的控制。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph所需的](https://docs.microsoft.com/graph/permissions-reference)任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD 应用 ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | 应用程序 | 名字、姓氏和公司电子邮件地址。面向管理员的报告的名、姓。用于与 Karma 通信的电子邮件地址、帐单用途和存档。 | 管理员同意显示名称。登录并读取用户配置文件。管理员同意说明。允许用户登录应用，并允许应用读取已登录用户的个人资料。 它还允许应用读取已登录用户的基本公司信息。用户同意显示名称签署你并读取你的配置文件。用户同意说明。允许你使用组织帐户登录应用，并允许应用读取你的配置文件。 它还允许应用读取基本公司信息。 | 9ff28b02-ccc5-4cac-9d17-4cf6987c371f |


#### <a name="non-microsoft-services-used"></a>非Microsoft 服务使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>不Microsoft 服务非活动。

#### <a name="data-access-via-bots"></a>通过机器人访问数据

如果此应用程序包含机器人或消息扩展，则它可以访问最终用户可识别信息 (EUII) ：名单 (名字、姓氏、显示名称、电子邮件地址) （团队中任何团队成员的姓名、姓氏、电子邮件地址) 或添加到其中聊天）。 此应用是否使用了此功能？

>| **访问 EUII 的理由？**  | **EUII 是否存储在数据库 (中) ？** | **存储 EUII 的理由** |
>|:--------------------------------|:---------------------|:--------------------------|
>| 名字、姓氏和公司电子邮件地址 名字，面向管理员的姓氏报告与 Karma 通信的电子邮件地址。 出于计费目的和将大量用户拆分为单独的离开，需要名单。 | 面向管理员的报告的名、姓和公司电子邮件地址名字、姓氏。 用于与 Karma、计费目的和 Karma 用户层次结构通信的电子邮件地址。 |  |



#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或 EUII (最终用户可识别) 是否显示在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>我们将租户 ID 和用户 ID 存储在日志中。 二者均无法识别。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>1. **是否有 DLP 解决方案？实施了哪些措施来防止数据泄露？**

是，数据在传输和其余过程中都进行加密。

2. **你实施哪种类型的机制以确保防止数据完整性出错、损坏或滥用，以及控制这些机制的频率**

所有服务器都运行具有不同 RAID 级别的硬件 RAID，但在每种情况下，都需要同时出现多个驱动器故障，以发生任何数据丢失。 我们格外安全，同时具有自动备份和手动备份。 数据库每天自动备份一次，存储七天。
VM 每周自动备份一次，存储 1 个月。

**快照和备份存储在内部不可见的网络上。**

3. **介绍如何确保客户数据在多租户解决方案中与其他客户的正确隔离，以及如何控制非生产环境中不复制或使用生产数据**

存储在不同的数据库中。

4. **对于传输中的数据和静态数据， (、协议、密钥长度) 建议哪种类型的加密**

所有传输数据都通过 TLS 或 SSL 进行加密。 HTTP 由 TLS 1.2 或 TLS 1.3 数据库流量加密，使用 SSL 进行加密。

数据存储在美国数据中心的"数字远地云中心"中。

5. **介绍如何管理唯一加密密钥 (、存储、使用情况、RACI、SOD) 供自己使用以及每个租户使用**

由 Digital Ocean 处理。

6. **介绍提供程序结束时就位的访问管理过程，指出如何确保及时删除不再需要的访问，以及如何控制对作业角色的权限的不足。还介绍重新验证过程及其执行频率**

我们使用双重身份验证来访问控制面板。 只有 3 个人有权访问此帐户，我们每月都会更改密码，保持对访问日志的审核，并确保不再与我们联系的用户已从平台中删除其帐户。

7. **提供在最终实现的过程 (如根、Sys、System 等 ) 、组 ID (供属于同一团队的一些个人使用的常规帐户（例如) 和本地帐户）。介绍如何限制、记录并监视特权帐户的使用和安全设备的访问权限 (例如虚拟机监控程序、防火墙、漏洞扫描程序、网络探查器、API 等 ) 、如何确保更改团队或离开的用户无法再访问组 ID 以及此类 ID 的可跟踪级别**

我们使用 1Password 来共享可共享 ID&#8217;，每次从共享密码密码中访问共享资源时，我们都有单独的活动源。 除非绝对必要，否则我们不会使用共享帐户，而是使用个人帐户。 无法通过共享登录访问 Karma 数据库上的信息。 2FA 用于访问 1Password 以检索单个登录名。

8. **描述确保并监视职责划分得到遵守以及控制频率的过程**

我们每月运行一次会议，其中涵盖义务划分、专用登录使用的重要性和每次登录时 2FA。

我们的 SIEM 包含：防火墙日志、Web 服务器日志和应用程序日志。 SIEM 每天在接收时进行分析。 日志将保留 1 个月，此后将安全删除。

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>是

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

下面将显示[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35674' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35674" target="_blank">在新建选项卡中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

