---
title: 按用户 monday.com 的应用程序 monday.com
ms.author: elmalova
author: elenamalova
ms.date: 09/28/2020
ms.topic: article
ms.service: attestation
description: 所有可用的安全与合规性信息 monday.com、其数据处理策略、Microsoft Cloud App Security应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: cf4fc476626fe4f623c6941cc2da096ec2a1ae41
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/30/2021
ms.locfileid: "52092773"
---
# <a name="mondaycom"></a>monday.com

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2020 年 9 月 28 日</p>

* <a href="https://teams.microsoft.com/l/app/eab2d3ce-6d6a-4415-abc4-5f40a8317b1f" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001798" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

由 Microsoft monday.com 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | monday.com |
| ID | WA200001798 |
| 功能 | 机器人，选项卡，消息传递扩展 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | monday.com |
| 合作伙伴网站的 URL | [https://monday.com](https://monday.com) |
| 隐私策略的 URL | [https://monday.com/privacy](https://monday.com/privacy) |
| 使用条款 URL | [https://monday.com/terms/tos](https://monday.com/terms/tos) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

此信息已由用户 monday.com，这些信息与此应用程序如何收集和存储组织数据以及组织将拥有对应用收集的数据的控制有关。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph所需的](https://docs.microsoft.com/graph/permissions-reference)任何 Microsoft 权限。

>此应用程序不使用 Microsoft Graph。


#### <a name="non-microsoft-services-used"></a>非Microsoft 服务使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>| **所有非Microsoft 服务 OII 将转移到** |  **转移了哪些 OII？** | **转移 OII 的理由？** |
>|:-------------------|:--------------------------|:--------------------------|
>| monday.com 将以下子处理器用于其服务的性能：&#160;https://monday.com/terms/subprocessors |  | monday.com API。 我们使用以下 Microsoft 框架来提升服务 (如上述) 响应所述：&#8216;botframework-connector&#8217; &#8216;&#8217; &#8216;@micorosft/teams-js&#8217; |

#### <a name="data-access-via-bots"></a>通过机器人访问数据

如果此应用程序包含机器人或消息扩展，则它可以访问最终用户可识别信息 (EUII) ：名单 (名字、姓氏、显示名称、电子邮件地址) （团队中任何团队成员的姓名、姓氏、电子邮件地址) 或添加到其中聊天）。 此应用是否使用了此功能？

>无法访问 EUII。



#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或 EUII (最终用户可识别) 是否显示在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>monday.com 在有限时段内存储包含用户生成内容的应用程序日志，以便我们的 R D 人员能够排查 Bug 和 &amp; 用户报告的问题。 根据我们的数据保留策略，包含 IP 地址的安全日志将保留更长时间。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>monday.com 服务托管在跨多个可用性区域北部都位于北部都斯的 AWS 基础结构上，而 DR 站点则建立在不同的区域中。 某些备份数据存储在美国、 (GCP) 。 对 monday.com 服务的访问权限由用户组织的管理员控制，并且通过利用以下功能实现：
- 用户类型
- 帐户级别的权限
- Workspaces
- 板类型
- 板级权限
- 列级别权限 monday.com 支持以下身份验证方法：
- 凭据
- Google SSO (for Pro plan) 
- 帐户管理员可以选择通过 短信 或通过验证器应用为 Enterprise 计划) 2FA 启用 Okta、OneLogin 和自定义 SAML 2.0 (，帐户管理员可通过平台的管理员面板选择启用。
所有其余数据都使用 AES-256 进行加密。 在开放网络中传输的所有数据至少使用 TLS 1.3 (TLS 1.2 进行) 。

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>是

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

下面将显示[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35338' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35338" target="_blank">在新建选项卡中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

