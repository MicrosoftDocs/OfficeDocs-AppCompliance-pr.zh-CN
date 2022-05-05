---
title: StealthMail by Stealthmail Software Ltd 的应用程序信息
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 05/05/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: 对于 StealthMail 的所有可用安全性和符合性信息、其数据处理策略、其Microsoft Cloud App Security应用目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: a0a31e0eceafbaa4188587411503514692c4b743
ms.sourcegitcommit: 7a7de9f48f6cf5b6acd435412477b6a59127f19a
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 05/05/2022
ms.locfileid: "65225556"
---
# <a name="stealthmail"></a>StealthMail

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2021 年 3 月 31 日</p>

* <a href="https://teams.microsoft.com/l/app/1ed0a549-c730-44c7-a984-a8c658fe9807" target="_blank">Teams存储区中的视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001748" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

秘密邮件软件有限公司提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | StealthMail |
| ID | WA200001748 |
| 支持Office 365客户端 | Microsoft Teams |
| 合作伙伴公司名称 | Stealthmail Software Ltd |
| 合作伙伴网站的 URL | [https://stealthmail.com](https://stealthmail.com) |
| Teams应用程序信息页的 URL | [https://stealthmail.com/product/teams](https://stealthmail.com/product/teams) |
| 隐私策略的 URL | [https://stealthmail.com/privacy-statement](https://stealthmail.com/privacy-statement) |
| 使用条款的 URL | [https://stealthmail.com/terms-and-conditions](https://stealthmail.com/terms-and-conditions) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

此信息由 Stealthmail Software Ltd 提供，介绍此应用如何收集和存储组织数据以及组织对应用收集的数据的控制。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph进行数据访问

列出此应用所需的任何 [Microsoft Graph权](/graph/permissions-reference)限。

>| **权限**  | **(委派/应用程序) 的权限类型** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| ChannelMessage.Read.All | 委托 | 应用程序使用创建的安全电子邮件上的引用将消息发送到通道 | 无 | [1ed0a549-c730-44c7-a984-a8c658fe9807](../azure/1ed0a549-c730-44c7-a984-a8c658fe9807.md) |
>| ChannelMessage.Send | 委托 | 应用程序使用创建的安全电子邮件上的引用将消息发送到通道 | 无 | [1ed0a549-c730-44c7-a984-a8c658fe9807](../azure/1ed0a549-c730-44c7-a984-a8c658fe9807.md) |
>| Chat.ReadWrite | 委托 | 应用程序发送消息以与创建的安全电子邮件上的引用聊天 | 无 | [1ed0a549-c730-44c7-a984-a8c658fe9807](../azure/1ed0a549-c730-44c7-a984-a8c658fe9807.md) |
>| GroupMember.Read.All | 委托 | 应用程序获取通道成员，以便为其生成安全电子邮件 | 无 | [1ed0a549-c730-44c7-a984-a8c658fe9807](../azure/1ed0a549-c730-44c7-a984-a8c658fe9807.md) |
>| User.Read.All | 委托 | 应用程序获取聊天成员，以便为其生成安全电子邮件 | 无 | [1ed0a549-c730-44c7-a984-a8c658fe9807](../azure/1ed0a549-c730-44c7-a984-a8c658fe9807.md) |
>| User.ReadBasic.All | 委托 | 应用程序获取聊天成员，以便为其生成安全电子邮件 | 无 | [1ed0a549-c730-44c7-a984-a8c658fe9807](../azure/1ed0a549-c730-44c7-a984-a8c658fe9807.md) |
>| 电子邮件 | 委托 | 对用户进行身份验证 | 数据库中没有任何存储 | [1ed0a549-c730-44c7-a984-a8c658fe9807](../azure/1ed0a549-c730-44c7-a984-a8c658fe9807.md) |


#### <a name="non-microsoft-services-used"></a>未使用Microsoft 服务

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输的数据，并包含应用需要传输此信息的原因。

>不使用非Microsoft 服务。

#### <a name="data-access-via-bots"></a>通过机器人进行数据访问

如果此应用包含机器人或消息传递扩展，则它可以访问最终用户身份信息 (EUII) ：名册 (名字、姓氏、显示名称、团队中任何团队成员的电子邮件地址) 或添加到的聊天。 此应用是否利用此功能？

>未访问 EUII。


#### <a name="telemetry-data"></a>遥测数据

此应用程序的遥测或日志中是否 (OII) 或最终用户身份信息 (EUII) 显示任何组织可识别信息？ 如果是，请描述存储的数据以及什么是保留和删除策略？

>应用程序遥测或日志中未显示 OII 或 EUII。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

介绍组织管理员如何控制合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>我们无法控制合作伙伴系统中的数据。

#### <a name="human-review-of-organizational-information"></a>组织信息的人工评审

人类是否参与查看或分析组织识别信息 (OII) 此应用收集或存储的数据？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

下面显示了[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/37867' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/37867" target="_blank">在新选项卡中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>标识信息

此信息由 Stealthmail Software Ltd 提供，介绍此应用如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件。

| **Information** | **响应** |
|:----------------|:-------------|
| 是否与 Microsoft 标识平台 (Azure AD) 集成？  | 是 |
| 是否已查看并遵守Microsoft 标识平台集成清单中列出的所有适用最佳做法？  | 是 |
| 应用是否使用 MSAL (Microsoft 身份验证库) 进行身份验证？ | 否 |
| 应用是否支持条件访问策略？ | 不支持 |
| 你的应用是否请求方案的最低特权权限？ | 是 |
| 应用的静态注册权限是否准确反映应用将以动态和增量方式请求的权限？ | 是 |
| 你的应用是否支持多租户？ | 是 |
| 你的应用是否具有机密客户端？ | 否 |
| 是否拥有注册应用的所有重定向统一资源标识符 (URI) ？ | 是 |
| 对于你的应用，你避免使用什么？ | - 通配符重定向 URI，<br/>- OAuth2 隐式Flow，除非 SPA 需要<br/>- 资源所有者密码凭据 (ROPC) 流 |
| 你的应用是否公开任何 Web API？ | 是 |
| 权限模型是否仅允许在客户端应用收到适当同意时调用成功？ | 是 |
| 应用是否使用预览 API？ | 是 |
| 你的应用是否使用已弃用的 API？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
