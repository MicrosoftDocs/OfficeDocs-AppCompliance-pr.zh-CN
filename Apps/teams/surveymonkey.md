---
title: SurveyMonkey 的应用程序信息 SurveyMonkey
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: SurveyMonkey 的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: daf5de5437a08ca8b748157a5e136bbe7b114122
ms.sourcegitcommit: 65d4afba6f46d45315b2a90d2b21ce1737707e7b
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 07/02/2021
ms.locfileid: "53280814"
---
# <a name="surveymonkey"></a>SurveyMonkey

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2019 年 12 月 16 日</p>

* <a href="https://teams.microsoft.com/l/app/0fd925a0-357f-4d25-8456-b3022aaa41a9" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381088" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

SurveyMonkey 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | SurveyMonkey |
| ID | WA104381088 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | SurveyMonkey |
| 合作伙伴网站的 URL | [https://www.surveymonkey.com](https://www.surveymonkey.com) |
| "Teams应用程序信息"页的 URL | [https://help.surveymonkey.com/articles/en_US/kb/Microsoft-T...](https://help.surveymonkey.com/articles/en_US/kb/Microsoft-Teams-Integration) |
| 隐私策略的 URL | [https://www.surveymonkey.com/mp/legal/privacy-policy/](https://www.surveymonkey.com/mp/legal/privacy-policy/) |
| 使用条款 URL | [https://www.surveymonkey.com/mp/legal/terms-of-use/](https://www.surveymonkey.com/mp/legal/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

SurveyMonkey 提供了此信息，这些信息与此应用程序如何收集和存储组织数据以及您的组织将拥有对应用收集的数据的控制有关。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph所需的](https://docs.microsoft.com/graph/permissions-reference)任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD 应用 ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Group.ReadWrite.All | delegated | 否 | 提供要共享调查的组/频道列表 |  |


#### <a name="non-microsoft-services-used"></a>非Microsoft 服务使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>| **所有非Microsoft 服务 OII 将转移到** |  **转移了哪些 OII？** | **转移 OII 的理由？** |
>|:-------------------|:--------------------------|:--------------------------|
>| 仅 MS 用户 ID 存储在 SurveyMonkey 中，以便将响应和调查与团队用户关联。 |  | 对于团队，我们使用 Microsoft Teams创建、调查和调查结果任务模块模式中的 javascript SDK。 |

#### <a name="data-access-via-bots"></a>通过机器人访问数据

如果此应用程序包含机器人或消息扩展，则它可以访问最终用户可识别信息 (EUII) ：名单 (名字、姓氏、显示名称、电子邮件地址) （团队中任何团队成员的姓名、姓氏、电子邮件地址) 或添加到其中聊天）。 此应用是否使用了此功能？

>| **访问 EUII 的理由？**  | **EUII 是否存储在数据库 (中) ？** | **存储 EUII 的理由** |
>|:--------------------------------|:---------------------|:--------------------------|
>| 我们调用 v3/conversations/{id}/pagedmembers，以检查该应用是否添加到团队并获取成员计数。 它用于内部跟踪使用情况，我们仅查看聊天名单的大小，其他信息将被忽略。 | 是的，聊天的大小存储在单个 (整数)  |  |


#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或 EUII (最终用户可识别) 是否显示在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>EUII - 只要调查收到响应，就会创建成功/失败日志，并且我们尝试通过连接器将响应发送到 Teams，此日志包括 user_id、survey_id、integration_id (数据库中可用于查找 MS 团队 ID、MS 用户 ID) 

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>我们的主要数据中心位于 NV 的拉斯维加斯，辅助数据中心位于加利福尼亚的圣达拉拉。 SurveyMonkey 在这些位置拥有并运行其所有服务器和基础结构。 我们还为位于加拿大的某些 SurveyMonkey 客户Enterprise加拿大数据驻留。 所有数据都使用带 AES256 的 TDE 进行其余加密，传输中的数据使用 TLS 1.2 进行加密。

SurveyMonkey 使用中心用户身份验证来维护标识和访问管理。 此系统管理对任意及所有企业以及生产基础结构、系统和服务的所有身份验证和授权。 将每季度维护和审查严格访问策略。 评论包括但不限于：用户访问列表、策略组和第三方访问评审。 若要访问我们的生产环境 (即获取特权帐户) ，需要获得经理批准、完成大量必需培训以及获得安全团队的批准。 此时，会预配一个额外的 VPN 帐户，此帐户&#8216;普通&#8217; 帐户与 &#8216;特权&#8217;帐户。

仅允许公司颁发的设备访问我们的生产网络。 所有无线供应商默认设置在安装前均会更改，包括但不限于默认的无线加密密钥、密码和 SNMP 社区字符串。 2FA 和 VPN 需要远程执行。 我们有一个单独的 Wifi 网络，用于公司办公室的来宾访问。

所有服务、协议和允许的端口都必须有记录的业务理由和批准，包括针对视为不安全的协议实施的安全功能的使用。 路由器和防火墙配置为限制向未经授权的方或意外方泄露 IP，并限制对 DMZ 防火墙和路由器规则集内的 IP 地址的入站 Internet 访问，至少每六个月检查一次。

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>是

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

下面将显示[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/12024' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/12024" target="_blank">在新建选项卡中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

