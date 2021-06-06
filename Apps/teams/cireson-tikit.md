---
title: Cireson 的 Tikit 应用程序信息
ms.author: elmalova
author: elenamalova
ms.date: 05/04/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tikit 的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 3c292fa0c8e0ae526c7258f7adc508fcccaeb9d8
ms.sourcegitcommit: dafa6701f28c66f003efaf2e3a70d61dc3240955
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 06/06/2021
ms.locfileid: "52789964"
---
# <a name="tikit"></a>Tikit

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2021 年 5 月 4 日</p>

* <a href="https://teams.microsoft.com/l/app/b13c40ee-e073-459e-96b5-3f3cca046a37" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002602" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

Cireson 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | Tikit |
| ID | WA200002602 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | Cireson |
| 合作伙伴网站的 URL | [https://tikit.ai](https://tikit.ai) |
| "Teams应用程序信息"页的 URL | [https://tikit.ai](https://tikit.ai) |
| 隐私策略的 URL | [https://tikit.ai/privacy-statement/](https://tikit.ai/privacy-statement/) |
| 使用条款 URL | [https://tikit.ai/terms-service/](https://tikit.ai/terms-service/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

Cireson 提供了此信息，这些信息与此应用程序如何收集和存储组织数据以及您的组织将拥有对应用收集的数据的控制有关。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph所需的](https://docs.microsoft.com/graph/permissions-reference)任何 Microsoft 权限。

>| **权限**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD 应用 ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Device.Read | 应用程序 | 用于单一登录的用户图形信息，通过团队机器人通信  | 我们存储用户角色、系列名称、给定名称、电子邮件、AAD ID Teams用户 ID。 此通知用于应用程序身份验证、安全性、RBAC、团队集成、团队通知和用户关系映射   | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| Directory.AccessAsUser.All | delegated | RBAC 的组名称和角色 | 组名称 &amp; 角色名称，需要提供安全的映射访问控制。 | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| Directory.Read.All | delegated | RBAC 的组名称和角色 | 组名称 &amp; 角色名称，需要提供安全的映射访问控制。 | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| Group.Read.All | 两者 | RBAC 的组名称和角色 | RBAC 的组名称和角色 | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| User.Read | delegated | 用于身份验证的用户角色、系列名称、给定名称、电子邮件、AAD ID Teams用户 ID  | 用于身份验证的用户角色、系列名称、给定名称、电子邮件、AAD ID Teams用户 ID  | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| User.Read.All | 应用程序 | 用于身份验证的用户角色、系列名称、给定名称、电子邮件、AAD ID Teams用户 ID  | 用于身份验证的用户角色、系列名称、给定名称、电子邮件、AAD ID Teams用户 ID  | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| User.ReadBasic.All | delegated | 用于身份验证的用户角色、系列名称、给定名称、电子邮件、AAD ID Teams用户 ID  | 用于身份验证的用户角色、系列名称、给定名称、电子邮件、AAD ID Teams用户 ID  | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| 电子邮件 | delegated | 用于登录和相关实体标识的用户电子邮件。 &quot;已分配用户&quot; | 用于登录和相关实体标识的用户电子邮件。 &quot;已分配用户&quot; | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| openid | delegated | 根据要求通过 MSAL 进行身份验证  | 根据要求通过 MSAL 进行身份验证  | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| 个人资料 | delegated | 根据要求通过 MSAL 进行身份验证  | 根据要求通过 MSAL 进行身份验证  | b13c40ee-e073-459e-96b5-3f3cca046a37 |

#### <a name="data-access-using-other-microsoft-apis"></a>使用其他 Microsoft API 进行数据访问

基于组织构建的应用和加载项Microsoft 365除 Microsoft Graph 外的其他 Microsoft API 来收集或处理 OII (组织) 。 列出除 Microsoft API Graph此应用使用的任何 Microsoft API。

>| **API** |  **是否收集 OII？** |  **收集哪些 OII？** | **收集 OII 的理由？** | **是否存储 OII？** | **存储 OII 的理由** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| QnA Maker | 不支持 |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>非Microsoft 服务使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>不Microsoft 服务非活动。

#### <a name="data-access-via-bots"></a>通过机器人访问数据

如果此应用程序包含机器人或消息扩展，则它可以访问最终用户可识别信息 (EUII) ：名单 (名字、姓氏、显示名称、电子邮件地址) （团队中任何团队成员的姓名、姓氏、电子邮件地址) 或添加到其中聊天）。 此应用是否使用了此功能？

>| **访问 EUII 的理由？**  | **EUII 是否存储在数据库 (中) ？** | **存储 EUII 的理由** |
>|:--------------------------------|:---------------------|:--------------------------|
>| 用户实体关系的名称和电子邮件票证 &quot; 请求程序&quot;  | 名称和电子邮件  | for user entity relationships &quot; Ticket Requestor&quot;  |


#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或 EUII (最终用户可识别) 是否显示在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>我们将公司名称、租户 ID、电子邮件、自动程序客户端 ID 存储在应用见解中，并保留策略为 30 dat。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>合作伙伴系统中没有任何数据。

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>支持

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

下面将显示[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36548' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36548" target="_blank">在新建选项卡中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>标识信息

此信息由 Cireson 提供有关此应用程序如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件的信息。

| **Information** | **响应** |
|:----------------|:-------------|
| 你是否与 Microsoft 标识平台 (Azure AD) ？  | 支持 |
| 您是否已查看并遵循了 Microsoft 标识平台 清单中列出的所有适用最佳做法？  | 支持 |
| 你的应用是否使用 MSAL (Microsoft 身份验证库) 进行身份验证？ | 支持 |
| 你的应用是否支持条件访问策略？ | 支持 |
| 列出支持的策略类型 | 多重身份验证、仅允许 Intune 注册的设备访问特定服务、限制用户位置和 IP 范围 |
| 应用是否请求方案最小特权权限？ | 支持 |
| 应用的静态注册权限是否准确反映应用将动态和增量请求的权限？ | 支持 |
| 你的应用是否支持多租户？ | 支持 |
| 你的应用是否具有机密客户端？ | 支持 |
| 你是否拥有为应用注册的所有重定向统 (URI) URI？ | 支持 |
| 对于你的应用，应避免使用什么？ | - 通配符重定向 URI，<br/>- OAuth2 隐式Flow，除非 SPA 需要<br/>- 资源所有者密码凭据 (ROPC) 流 |
| 你的应用是否公开任何 Web API？ | 支持 |
| 您的权限模型是否仅在客户端应用程序收到正确同意时允许呼叫成功？ | 支持 |
| 你的应用是否使用预览 API？ | 支持 |
| 你的应用是否使用已弃用 API？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
