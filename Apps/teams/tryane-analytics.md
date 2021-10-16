---
title: Tryane 分析的应用程序信息
ms.author: elmalova
author: elenamalova
ms.date: 09/20/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tryane Analytics 的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 474c7824163b9b457ca3df2e705dc2cb1ccb8845
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 10/16/2021
ms.locfileid: "60410816"
---
# <a name="tryane-analytics"></a>Tryane Analytics

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2021 年 8 月 27 日</p>

* <a href="https://teams.microsoft.com/l/app/87631b95-fcd9-46e9-8d86-3d5205c04fec" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001827" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

Tryane 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | Tryane Analytics |
| ID | WA200001827 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | Tryane |
| 合作伙伴网站的 URL | [https://www.tryane.com](https://www.tryane.com) |
| Teams信息页的 URL | [https://tryane.com/en/produit/tat/](https://tryane.com/en/produit/tat/) |
| 隐私策略的 URL | [https://tryane.com/tryane-analytics/privacy_policy.html](https://tryane.com/tryane-analytics/privacy_policy.html) |
| 使用条款 URL | [https://analytics.tryane.com/docs/en/terms_of_use.html](https://analytics.tryane.com/docs/en/terms_of_use.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

Tryane 提供了此信息，这些信息与此应用程序如何收集和存储组织数据以及组织将拥有对应用收集的数据的控制有关。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph所需的](https://docs.microsoft.com/graph/permissions-reference)任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Channel.ReadBasic.All | 应用程序 | 通道名称和其他属性 | All 列出包含名称、说明的所有频道 | [9b03f15d-1219-4b2f-9699-640be54e1319](https://docs.microsoft.com/microsoft-365-app-certification/azure/9b03f15d-1219-4b2f-9699-640be54e1319) |
>| ChannelMessage.Read.All | 应用程序 | 用户发布的消息数 | 列出所有频道消息&#8217;元数据 | [9b03f15d-1219-4b2f-9699-640be54e1319](https://docs.microsoft.com/microsoft-365-app-certification/azure/9b03f15d-1219-4b2f-9699-640be54e1319) |
>| Directory.Read.All | 应用程序 | 访问 Ms Teams | 在租户中标识具有团队许可证的用户 | [9b03f15d-1219-4b2f-9699-640be54e1319](https://docs.microsoft.com/microsoft-365-app-certification/azure/9b03f15d-1219-4b2f-9699-640be54e1319) |
>| Member.Read.Hidden | 应用程序 | 成员列表 | 获取所有团队、团队&#8217;的成员和隐藏成员身份的列表 | [9b03f15d-1219-4b2f-9699-640be54e1319](https://docs.microsoft.com/microsoft-365-app-certification/azure/9b03f15d-1219-4b2f-9699-640be54e1319) |
>| Reports.Read.All | 应用程序 | Teams | 读取团队中的所有用户活动 | [9b03f15d-1219-4b2f-9699-640be54e1319](https://docs.microsoft.com/microsoft-365-app-certification/azure/9b03f15d-1219-4b2f-9699-640be54e1319) |
>| Team.ReadBasic.All | 应用程序 | 团队 ID、团队名称、频道 ID、频道名称 | 列出所有频道和团队属性 | [9b03f15d-1219-4b2f-9699-640be54e1319](https://docs.microsoft.com/microsoft-365-app-certification/azure/9b03f15d-1219-4b2f-9699-640be54e1319) |
>| User.Read | delegated | 用户 ID、名称、电子邮件地址、创建日期。我们存储此数据是为了在数据上提供使用情况Teams | 在订阅期间标识当前用户 | [9b03f15d-1219-4b2f-9699-640be54e1319](https://docs.microsoft.com/microsoft-365-app-certification/azure/9b03f15d-1219-4b2f-9699-640be54e1319) |


#### <a name="non-microsoft-services-used"></a>非Microsoft 服务已使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>不Microsoft 服务非活动。

#### <a name="data-access-via-bots"></a>通过机器人访问数据

如果此应用程序包含机器人或消息扩展，则它可以访问最终用户可识别信息 (EUII) ：名单 (名字、姓氏、显示名称、电子邮件地址) （团队中任何团队成员的姓名、姓氏、电子邮件地址) 或添加到其中聊天）。 此应用是否使用了此功能？

>无法访问 EUII。


#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或最终用户可识别信息 (EUII) 是否出现在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>IT 安全策略和编码标准中描述的组织规则阻止我们在日志中显示 EUII 和 OII

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>Where/How： Azure/Azure Database for PostgreSQL servers Who可以访问它：我们的应用程序和数据库管理员授权控制： 
 - 单个授权控制：RBAC
 - 系统授权控制：Azure 虚拟网络中的专用终结点

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

下面将显示[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36057' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36057" target="_blank">在新建选项卡中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>标识信息

Tryane 提供了此信息，这些信息与此应用程序如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件有关。

| **Information** | **响应** |
|:----------------|:-------------|
| 是否与 Microsoft 标识平台 (Azure AD) ？  | 是 |
| 您是否已查看并遵循了 Microsoft 标识平台 清单中列出的所有适用最佳做法？  | 是 |
| 你的应用是否使用 MSAL (Microsoft 身份验证库) 进行身份验证？ | 否 |
| 你的应用是否支持条件访问策略？ | 否 |
| 应用是否请求方案最小特权权限？ | 是 |
| 应用的静态注册权限是否准确反映应用将动态和增量请求的权限？ | 是 |
| 你的应用是否支持多租户？ | 是 |
| 你的应用是否具有机密客户端？ | 否 |
| 你是否拥有为应用注册的所有 (统一) URI？ | 是 |
| 对于你的应用，应避免使用什么？ | - 通配符重定向 URI，<br/>- OAuth2 隐式Flow，除非 SPA 需要<br/>- 资源所有者密码凭据 (ROPC) 流 |
| 你的应用是否公开任何 Web API？ | 否 |
| 你的应用是否使用预览 API？ | 否 |
| 你的应用是否使用已弃用 API？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

