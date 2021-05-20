---
title: LiveTiles 的 Reach 应用程序信息
ms.author: elmalova
author: elenamalova
ms.date: 03/22/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Reach 的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 83df050a6f58bc1d0b7d49239b40ddf2ba80849a
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 05/19/2021
ms.locfileid: "52551993"
---
# <a name="reach"></a>Reach

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2021 年 3 月 22 日</p>

* <a href="https://teams.microsoft.com/l/app/5df8ebd2-bf7b-4fb5-bb35-0bfbf5d10a23" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002045" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

LiveTiles 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | Reach |
| ID | WA200002045 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | LiveTiles |
| 合作伙伴网站的 URL | [https://livetilesglobal.com](https://livetilesglobal.com) |
| "Teams应用程序信息"页的 URL | [https://livetilesglobal.com/products/livetiles-reach/](https://livetilesglobal.com/products/livetiles-reach/) |
| 隐私策略的 URL | [https://livetilesglobal.com/privacy-policy](https://livetilesglobal.com/privacy-policy) |
| 使用条款 URL | [https://livetilesglobal.com/eula](https://livetilesglobal.com/eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

LiveTiles 提供了此信息，这些信息与此应用程序如何收集和存储组织数据以及组织将拥有对应用收集的数据的控制有关。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph所需的](https://docs.microsoft.com/graph/permissions-reference)任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD 应用 ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| TeamsActivity.Send | 应用程序 | 无 | 无 | a7c1920d-3ac0-42db-9757-078a2b321fd8  |
>| User.Read | delegated | 用户 DisplayName、用户电子邮件地址、UPN。 需要允许用户登录应用并获取已登录用户的基本信息，如显示名称。 电子邮件地址用于发送电子邮件通知。  | 用户 DisplayName、用户电子邮件地址、UPN。 需要允许用户登录应用并获取已登录用户的基本信息，如显示名称。 电子邮件地址用于发送电子邮件通知。  | d492530a-8cff-481c-90da-9c3c3f1be7da |
>| User.ReadBasic.All | delegated | 用户显示名称、用户电子邮件地址、UPN、用户部门、用户职务、用户移动电话号码、用户电话号码、用户Office位置。 若要允许用户在 Phonebook (应用程序内搜索其他用户，) 查看其他用户的基本个人资料和联系信息，此为必需项。  | 无 | d492530a-8cff-481c-90da-9c3c3f1be7da |
>| Directory.Read.All | 应用程序 | 组成员身份，目录中的 AD 组。 用户的组成员身份存储在缓存中，以最大限度地减少对 Microsoft Graph API 的调用。 必须允许用户搜索 Active Directory 组。 此外，应用程序需要此权限才能解析后端 Web 作业中用户的 AD 组成员身份。 | 用户的组成员身份。 用户的组成员身份存储在缓存中，以最大限度地减少对 Microsoft Graph API 的调用。 必须允许用户搜索 Active Directory 组。 此外，应用程序需要此权限才能解析后端 Web 作业中用户的 AD 组成员身份。  | d492530a-8cff-481c-90da-9c3c3f1be7da  |
>| User.Read.All | 应用程序 | 从用户配置文件中检索的数据取决于应用程序中指定的访问群体定位功能配置。 需要允许应用在没有登录用户的情况下读取用户配置文件。 应用程序中的信息定位功能需要读取配置文件数据，以便基于特定配置文件属性值向特定用户显示该信息。  | 无 | d492530a-8cff-481c-90da-9c3c3f1be7da  |


#### <a name="non-microsoft-services-used"></a>非Microsoft 服务使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>| **所有非Microsoft 服务 OII 将转移到** |  **转移了哪些 OII？** | **转移 OII 的理由？** |
>|:-------------------|:--------------------------|:--------------------------|
>| SendGrid、OneSignal | 电子邮件地址显示名称 | 通过电子邮件和移动推送通知向用户发送通知 |

#### <a name="data-access-via-bots"></a>通过机器人访问数据

如果此应用程序包含机器人或消息扩展，则它可以访问最终用户可识别信息 (EUII) ：名单 (名字、姓氏、显示名称、电子邮件地址) （团队中任何团队成员的姓名、姓氏、电子邮件地址) 或添加到其中聊天）。 此应用是否使用了此功能？

>无法访问 EUII。


#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或 EUII (最终用户可识别) 是否显示在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>电子邮件地址 UPN。 最多保留 60 天，删除后

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>管理员可以联系支持人员进行任何查询

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

下面将显示[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36551' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36551" target="_blank">在新建选项卡中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>标识信息

LiveTiles 提供了此信息，这些信息与此应用程序如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件有关。

| **Information** | **响应** |
|:----------------|:-------------|
| 你是否与 Microsoft 标识平台 (Azure AD) ？  | 是 |
| 您是否已查看并遵循了 Microsoft 标识平台 清单中列出的所有适用最佳做法？  | 否 |
| 你的应用是否使用 MSAL (Microsoft 身份验证库) 进行身份验证？ | 是 |
| 你的应用是否支持条件访问策略？ | 是 |
| 列出支持的策略类型 | 多重身份验证，限制用户位置和 IP 范围 |
| 应用是否请求方案最小特权权限？ | 是 |
| 应用的静态注册权限是否准确反映应用将动态和增量请求的权限？ | 是 |
| 你的应用是否支持多租户？ | 是 |
| 你的应用是否具有机密客户端？ | 否 |
| 你是否拥有为应用注册的所有重定向统 (URI) URI？ | 是 |
| 对于你的应用，应避免使用什么？ | - 通配符重定向 URI，<br/>- OAuth2 隐式Flow，除非 SPA 需要<br/>- 资源所有者密码凭据 (ROPC) 流 |
| 你的应用是否公开任何 Web API？ | 是 |
| 您的权限模型是否仅在客户端应用程序收到正确同意时允许呼叫成功？ | 是 |
| 你的应用是否使用预览 API？ | 是 |
| 你的应用是否使用已弃用 API？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
