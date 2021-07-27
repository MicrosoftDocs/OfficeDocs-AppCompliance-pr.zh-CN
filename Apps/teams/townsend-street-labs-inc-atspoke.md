---
title: AtSpoke 的应用程序信息（由）（由一家位于美国）的由一家 Street Labs， Inc.
ms.author: elmalova
author: elenamalova
ms.date: 06/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: atSpoke 的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 2d72ea33577e386c61be6bcd09feeba813e9e1f5
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 07/22/2021
ms.locfileid: "53528098"
---
# <a name="atspoke"></a>atSpoke

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2020 年 6 月 3 日</p>

* <a href="https://teams.microsoft.com/l/app/dfaf15dc-4e94-4484-a25d-79358fe70d8b" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001454" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

由 Microsoft 的一家 Street Labs， Inc. 提供的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | atSpoke |
| ID | WA200001454 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | Townsend Street Labs, Inc. |
| 合作伙伴网站的 URL | [https://www.atspoke.com/](https://www.atspoke.com/) |
| 隐私策略的 URL | [https://www.atspoke.com/privacy-policy/](https://www.atspoke.com/privacy-policy/) |
| 使用条款 URL | [https://www.atspoke.com/terms-of-service/](https://www.atspoke.com/terms-of-service/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

此信息由一家由一家（美国）的一家 Street Labs， Inc. 提供，用于了解此应用程序如何收集和存储组织数据，以及您的组织将拥有对应用收集的数据的控制。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph所需的](https://docs.microsoft.com/graph/permissions-reference)任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD 应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Group.ReadWrite.All | delegated | atSpoke 存储 Microsoft 组 ID | 允许读取和写入 atSpoke 和 Microsoft Teams。  | [dfaf15dc-4e94-4484-a25d-79358fe70d8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/dfaf15dc-4e94-4484-a25d-79358fe70d8b) |
>| User.ReadWrite.All | delegated | atSpoke 存储用户电子邮件和用户 ID | 允许读取和写入 atSpoke 和 Microsoft Teams。 | [dfaf15dc-4e94-4484-a25d-79358fe70d8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/dfaf15dc-4e94-4484-a25d-79358fe70d8b) |
>| offline_access | delegated | atSpoke 不会存储任何数据。 | 这用于后台同步。 | [dfaf15dc-4e94-4484-a25d-79358fe70d8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/dfaf15dc-4e94-4484-a25d-79358fe70d8b) |


#### <a name="non-microsoft-services-used"></a>非Microsoft 服务使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>| **所有非Microsoft 服务 OII 将转移到** |  **转移了哪些 OII？** | **转移 OII 的理由？** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| 是的，我们使用第三方服务以提高运行效率。 Google， Inc.：逻辑卷上存储的数据、本机 Google 云网络的存储备份、服务和 API 日志或应用程序日志。 记录的事务事件可能包含用户标识符 () 、联系人信息和客户内容。 MongoDB， Inc.：存储在基于云的数据库集合中的数据。 - 客户内容，其中包括用户提交的请求、用户添加的请求响应和用户添加的知识文章。 - 用户标识符 (创建分支用户帐户的用户姓名、电子邮件、头像和) 。 Mail且 Technologies， Inc.：用于发送电子邮件通信的用户标识符和联系人信息 (即名称和电子邮件) 。 Twilio， Inc.：用户电话号码和客户内容：通过使用 Twilio&#8217;服务交换的内容，例如文本、邮件正文、语音和视频媒体、图像和声音。 Mixpanel， Inc.：传输的个人数据包括姓名、电子邮件、IP 地址和包含在邮件内容中的个人数据。 Cloudinary， Inc.：最终用户提交的基于文件的客户内容。 弹性搜索， Inc.：记录的应用程序事务事件可能包含客户内容的截断文本。 用户：联系人信息、使用情况信息、订阅者授权用户的非传统标识符，以及订阅者或授权用户提交到平台的其他任何个人数据。 Mode Analytics， Inc.：用户标识符 (信息) 每个用户的分析。 DataDog：记录的应用程序事务事件可能包含客户内容的截断文本;日志保留期为 14 天。 Fullstory， Inc.：录制在我们的 Web 用户界面上采取的操作;包括用于标识目的的分支用户帐户。 |  | 我们使用的是 Bot Framework REST API。 我们使用此 API 向 askSpoke 自动程序服务发送和接收消息。 |

#### <a name="data-access-via-bots"></a>通过机器人访问数据

如果此应用程序包含机器人或消息扩展，则它可以访问最终用户可识别信息 (EUII) ：名单 (名字、姓氏、显示名称、电子邮件地址) （团队中任何团队成员的姓名、姓氏、电子邮件地址) 或添加到其中聊天）。 此应用是否使用了此功能？

>| **访问 EUII 的理由？**  | **EUII 是否存储在数据库 (中) ？** | **存储 EUII 的理由** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| 它允许 atSpoke 从用户Microsoft Teams创建用户和定义权限。 | atSpoke 仅存储电子邮件Microsoft Teams用户可以以有效用户登录 atSpoke。 |  |


#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或 EUII (最终用户可识别) 是否显示在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>包含在我们的应用程序日志中，有用户的名和姓、用户的电子邮件地址以及为用户和组分配的 Azure 对象 ID。 日志仅保留 14 天，此时日志将自动过期。 日志访问受到保护，并且只有某些员工才有权访问日志。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>应用程序数据存储在托管的 MongoDB 实例中。 通过需要审批的标准化用户访问请求流程设置对 Managed Service Atlas MongoDB Database 的访问。 通过管理注销执行定期用户访问评审。 我们限制有权访问敏感客户数据的员工数量，并且不允许直接从任何计算机修改数据。&#8232;远程访问此数据库需要多重身份验证。 使用 AES-256 位加密对数据库及所有备份进行静态加密。


#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>是

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

下面将显示[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35866' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35866" target="_blank">在新建选项卡中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

