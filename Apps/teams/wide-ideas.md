---
title: 通过广泛想法获取广泛想法的应用程序信息
ms.author: elmalova
author: elenamalova
ms.date: 09/24/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: 有关"广泛想法"的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 12bb02bacf02edc9794f3bcdfd417995abafae38
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 10/18/2021
ms.locfileid: "60445320"
---
# <a name="wide-ideas"></a>Wide Ideas

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2021 年 8 月 27 日</p>

* <a href="https://teams.microsoft.com/l/app/2a64f929-bed9-44d9-aa65-d7b921889959" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000819" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

由广泛想法提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | Wide Ideas |
| ID | WA200000819 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | Wide Ideas |
| 合作伙伴网站的 URL | [https://getwideideas.com](https://getwideideas.com) |
| 隐私策略的 URL | [https://getwideideas.com/privacy-policy/](https://getwideideas.com/privacy-policy/) |
| 使用条款 URL | [https://pinpointprod.blob.core.windows.net/marketing/Partne...](https://pinpointprod.blob.core.windows.net/marketing/Partner_21474849364/Product_42949683744/Asset_0831a14b-e5df-4f0b-8385-3c06edaeceeb/GENERALTERMSANDCONDITIONSWideI.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

此信息由有关此应用如何收集和存储组织数据以及组织对应用收集的数据的控制的"广泛想法"提供。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph](https://docs.microsoft.com/graph/permissions-reference)所需的任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Channel.Create | delegated | 在团队中创建频道。  | 我们存储已创建的质询的频道 ID。  | [b0656c15-44aa-4aab-8956-bb97e3016535](https://docs.microsoft.com/microsoft-365-app-certification/azure/b0656c15-44aa-4aab-8956-bb97e3016535) |
>| Directory.Read.All | delegated | 我们使用它从客户目录中列出用户  | 不适用 | [b0656c15-44aa-4aab-8956-bb97e3016535](https://docs.microsoft.com/microsoft-365-app-certification/azure/b0656c15-44aa-4aab-8956-bb97e3016535) |
>| Group.Read.All | delegated | 我们使用它从团队中读取和Microsoft Teams。 | 我们存储团队和团队成员的组 ID。  | [b0656c15-44aa-4aab-8956-bb97e3016535](https://docs.microsoft.com/microsoft-365-app-certification/azure/b0656c15-44aa-4aab-8956-bb97e3016535) |
>| TeamsAppInstallation.ReadWriteForTeam | delegated | 这用于自动在应用中Teams应用  | 我们存储有关在哪个团队中安装应用的信息 | [b0656c15-44aa-4aab-8956-bb97e3016535](https://docs.microsoft.com/microsoft-365-app-certification/azure/b0656c15-44aa-4aab-8956-bb97e3016535) |
>| TeamsTab.Create | delegated | 我们使用它自动创建应用程序， ("想法"的) 创建频道中的质询/搜索想法。 | 不适用 | [b0656c15-44aa-4aab-8956-bb97e3016535](https://docs.microsoft.com/microsoft-365-app-certification/azure/b0656c15-44aa-4aab-8956-bb97e3016535) |
>| User.Read | delegated | 用于通过 SSO 对用户进行身份验证以及同步用户数据 | 我们存储名称、电子邮件和用户 ID。  | [b0656c15-44aa-4aab-8956-bb97e3016535](https://docs.microsoft.com/microsoft-365-app-certification/azure/b0656c15-44aa-4aab-8956-bb97e3016535) |


#### <a name="non-microsoft-services-used"></a>非Microsoft 服务已使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>| **所有非Microsoft 服务 OII 将转移到** |  **转移了哪些 OII？** | **转移 OII 的理由？** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Mailjet 用于电子邮件通知的电子邮件。 | email address | 能够通过活动发送电子邮件通知  |

#### <a name="data-access-via-bots"></a>通过机器人访问数据

如果此应用程序包含机器人或消息扩展，则它可以访问最终用户可识别信息 (EUII) ：名单 (名字、姓氏、显示名称、电子邮件地址) （团队中任何团队成员的姓名、姓氏、电子邮件地址) 或添加到其中聊天）。 此应用是否使用了此功能？

>| **访问 EUII 的理由？**  | **EUII 是否存储在数据库 () ？** | **存储 EUII 的理由** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| 为了在后端创建用户并授予访问链接到团队的内容的权限。 | 存储：名称 - 显示用户名称，电子邮件地址 - 标识用户 | 为了管理后端中内容的权限 |


#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或 EUII (最终用户可识别) 是否显示在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>我们将名称、电子邮件和 IP 号码存储在日志中。 如果组织希望删除任何数据，他们可以将请求发送给我们作为供应商。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>数据存储：所有客户数据存储在Microsoft Azure中。 用户需要经身份验证的 2 个因素Azure AD。 基于角色 (RBAC) 已就位。 对加密Microsoft Azure完全通过加密连接进行。 所有数据都进行其余加密。 所有服务都受 Azure 安全中心最佳保护。 

我们还根据最小特权原则制定访问策略。 


#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

下面将显示[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35870' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35870" target="_blank">在新建选项卡中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>标识信息

此信息由有关此应用如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件的广泛想法提供。

| **Information** | **响应** |
|:----------------|:-------------|
| 是否与 Microsoft 标识平台 (Azure AD) ？  | 是 |
| 您是否已审阅并遵循了 Microsoft 标识平台 集成清单中列出的所有适用最佳做法？  | 是 |
| 你的应用是否使用 MSAL (Microsoft 身份验证库) 进行身份验证？ | 是 |
| 你的应用是否支持条件访问策略？ | 是 |
| 列出支持的策略类型 | MFA |
| 应用是否请求方案最小特权权限？ | 是 |
| 应用的静态注册权限是否准确反映应用将动态和增量请求的权限？ | 是 |
| 你的应用是否支持多租户？ | 是 |
| 你的应用是否具有机密客户端？ | 是 |
| 你是否拥有为应用注册的所有 (统一) URI？ | 是 |
| 对于你的应用，应避免使用什么？ | - 通配符重定向 URI，<br/>- OAuth2 隐式Flow，除非 SPA 需要<br/>- 资源所有者密码凭据 (ROPC) 流 |
| 你的应用是否公开任何 Web API？ | 否 |
| 你的应用是否使用预览 API？ | 否 |
| 你的应用是否使用已弃用 API？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
