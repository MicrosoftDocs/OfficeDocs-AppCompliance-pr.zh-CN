---
title: 工作板的应用程序信息
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 06/04/2021
ms.topic: article
ms.service: attestation
certification_type: certified
description: 工作板的所有可用安全性和符合性信息、其数据处理策略、其Microsoft Cloud App Security应用目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: b20a6e58680109d719fca48cf8f2152c9239026a
ms.sourcegitcommit: 7a7de9f48f6cf5b6acd435412477b6a59127f19a
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 05/05/2022
ms.locfileid: "65222453"
---
# <a name="application-information-for-workboard"></a>工作板的应用程序信息

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>开发人员上次更新时间：2021 年 6 月 4 日</p>

* <a href="https://teams.microsoft.com/l/app/28d0282b-3cd2-49f0-90bb-a016843750c6" target="_blank">Teams存储区中的视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381599" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

工作板提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | Workboard |
| ID | WA104381599 |
| 支持Office 365客户端 | Microsoft Teams |
| 合作伙伴公司名称 | Workboard |
| 合作伙伴网站的 URL | [https://www.workboard.com](https://www.workboard.com) |
| Teams应用程序信息页的 URL | [https://www.workboard.com/microsoft/](https://www.workboard.com/microsoft/) |
| 隐私策略的 URL | [https://www.workboard.com/license/privacy-policy.html](https://www.workboard.com/license/privacy-policy.html) |
| 使用条款的 URL | [https://www.workboard.com/license/terms_of_use_v1.php](https://www.workboard.com/license/terms_of_use_v1.php) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

工作板提供了此信息，了解此应用如何收集和存储组织数据，以及组织对应用收集的数据的控制。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph进行数据访问

列出此应用所需的任何 [Microsoft Graph权](/graph/permissions-reference)限。

>| **权限**  | **(委派/应用程序) 的权限类型** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | 委托 | 电子邮件地址和用户 ID。  它用于将用户映射到 WorkBoard 的用户 ID | WorkBoard 仅将用户的标识存储在数据库中 | [User.Read](/microsoft-365-app-certification/azure/User.Read) |


#### <a name="non-microsoft-services-used"></a>未使用Microsoft 服务

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输的数据，并包含应用需要传输此信息的原因。

>不使用非Microsoft 服务。

#### <a name="data-access-via-bots"></a>通过机器人进行数据访问

如果此应用包含机器人或消息传递扩展，则它可以访问最终用户身份信息 (EUII) ：名册 (名字、姓氏、显示名称、团队中任何团队成员的电子邮件地址) 或添加到的聊天。 此应用是否利用此功能？

>| **访问 EUII 的理由？**  | **EUII 是否存储在数据库 () 中？** | **存储 EUII 的理由？** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| 用户 ID 用于 WorkBord 发送到Teams的主动通知 | 用户电子邮件地址和 ID | 用于将用户映射到 WorkBoard 的用户 ID |


#### <a name="telemetry-data"></a>遥测数据

此应用程序的遥测或日志中是否 (OII) 或最终用户身份信息 (EUII) 显示任何组织可识别信息？ 如果是，请描述存储的数据以及什么是保留和删除策略？

>应用程序遥测或日志中未显示 OII 或 EUII。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

介绍组织管理员如何控制合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>WorkBoard 不将组织数据存储在合作伙伴的系统中

#### <a name="human-review-of-organizational-information"></a>组织信息的人工评审

人类是否参与查看或分析组织识别信息 (OII) 此应用收集或存储的数据？

>是

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

下面显示了[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/29004' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/29004" target="_blank">在新选项卡中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>标识信息

工作板提供了有关此应用如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件的信息。

| **Information** | **响应** |
|:----------------|:-------------|
| 是否与 Microsoft 标识平台 (Azure AD) 集成？  | 是 |
| 是否已查看并遵守Microsoft 标识平台集成清单中列出的所有适用最佳做法？  | 是 |
| 应用是否使用 MSAL (Microsoft 身份验证库) 进行身份验证？ | 否 |
| 应用是否支持条件访问策略？ | 是 |
| 列出支持的策略类型 | WorkBoard 已实现自己的访问策略，这些策略在应用中强制实施。  用户的组织、团队和标识用于确定访问权限。 |
| 你的应用是否请求方案的最低特权权限？ | 是 |
| 应用的静态注册权限是否准确反映应用将以动态和增量方式请求的权限？ | 是 |
| 你的应用是否支持多租户？ | 是 |
| 你的应用是否具有机密客户端？ | 不支持 |
| 是否拥有注册应用的所有重定向统一资源标识符 (URI) ？ | 是 |
| 你的应用是否公开任何 Web API？ | 是 |
| 权限模型是否仅允许在客户端应用收到适当同意时调用成功？ | 是 |
| 应用是否使用预览 API？ | 否 |
| 你的应用是否使用已弃用的 API？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
