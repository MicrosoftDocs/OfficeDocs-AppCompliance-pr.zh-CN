---
title: Senso 的应用程序信息
ms.author: elmalova
author: elenamalova
ms.date: 08/02/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Senso 的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: a44620633f9eee6c5d5e18997a58158a16c5e801
ms.sourcegitcommit: 7ef4a79aa28ac4dcce067b1f6f8693eeec6335e9
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 08/13/2021
ms.locfileid: "58245255"
---
# <a name="senso"></a>Senso

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2021 年 8 月 2 日</p>

* <a href="https://teams.microsoft.com/l/app/3973b9d4-b50e-472d-8145-8967e01379b4" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002571" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

Senso 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | Senso |
| ID | WA200002571 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | Senso |
| 合作伙伴网站的 URL | [https://www.senso.cloud](https://www.senso.cloud) |
| Teams信息页的 URL | [https://www.senso.cloud/safeguarding-microsoft-teams/](https://www.senso.cloud/safeguarding-microsoft-teams/) |
| 隐私策略的 URL | [https://www.senso.cloud/privacy](https://www.senso.cloud/privacy) |
| 使用条款 URL | [https://www.senso.cloud/eula](https://www.senso.cloud/eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

Senso 提供了此信息，这些信息与此应用程序如何收集和存储组织数据以及您的组织将拥有对应用收集的数据的控制有关。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph所需的](https://docs.microsoft.com/graph/permissions-reference)任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD 应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Channel.ReadBasic.All | 应用程序 | 读取所有频道的频道名称和说明，以确定在何处标记了违反。   | 当发生冲突时，发件人 (From) ， () 的收件人 (To) ，将记录来自该聊天频道的频道名称、日期、时间和消息，以向冲突提供上下文。  | [a9d28fcf-036e-4a85-9003-332303e3a29b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a9d28fcf-036e-4a85-9003-332303e3a29b) |
>| ChannelMember.Read.All | 应用程序 | 读取所有频道的成员列表和聊天消息。 | 当发生冲突时，发件人 (From) ， () 的收件人 (To) ，将记录来自该聊天频道的频道名称、日期、时间和消息，以向冲突提供上下文。  | [a9d28fcf-036e-4a85-9003-332303e3a29b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a9d28fcf-036e-4a85-9003-332303e3a29b) |
>| ChannelMessage.Read.All | 应用程序 | 读取所有频道消息 | 当发生冲突时，发件人 (From) ， () 的收件人 (To) ，将记录来自该聊天频道的频道名称、日期、时间和消息，以向冲突提供上下文。  | [a9d28fcf-036e-4a85-9003-332303e3a29b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a9d28fcf-036e-4a85-9003-332303e3a29b) |
>| Chat.Read.All | 应用程序 | 读取所有聊天消息 | 当发生冲突时，发件人 (From) ， () 的收件人 (To) ，将记录来自该聊天频道的频道名称、日期、时间和消息，以向冲突提供上下文。  | [a9d28fcf-036e-4a85-9003-332303e3a29b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a9d28fcf-036e-4a85-9003-332303e3a29b) |
>| Directory.Read.All | 应用程序 | 读取目录数据 | 当发生冲突时，发件人 (From) ， () 的收件人 (To) ，将记录来自该聊天频道的频道名称、日期、时间和消息，以向冲突提供上下文。  | [a9d28fcf-036e-4a85-9003-332303e3a29b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a9d28fcf-036e-4a85-9003-332303e3a29b) |
>| Files.Read.All | 应用程序 | 读取所有网站集中的文件 | 当发生冲突时，发件人 (From) ， () 的收件人 (To) ，将记录来自该聊天频道的频道名称、日期、时间和消息，以向冲突提供上下文。  | [a9d28fcf-036e-4a85-9003-332303e3a29b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a9d28fcf-036e-4a85-9003-332303e3a29b) |
>| User.Read | delegated | 登录并读取用户个人资料 | 用于单一登录 | [a9d28fcf-036e-4a85-9003-332303e3a29b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a9d28fcf-036e-4a85-9003-332303e3a29b) |
>| User.Read.All | 应用程序 | 读取所有用户的完整个人资料 | 当发生冲突时，发件人 (From) ， () 的收件人 (To) ，将记录来自该聊天频道的频道名称、日期、时间和消息，以向冲突提供上下文。  | [a9d28fcf-036e-4a85-9003-332303e3a29b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a9d28fcf-036e-4a85-9003-332303e3a29b) |


#### <a name="non-microsoft-services-used"></a>非Microsoft 服务使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>| **所有非Microsoft 服务 OII 将转移到** |  **转移了哪些 OII？** | **转移 OII 的理由？** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Senso.cloud 以下子处理器来提升其服务的性能： https://www.senso.cloud/privacy-policy/ 第 5 节。 个人数据的披露。 | 我们和第三方帐户和第三方提供程序共享的数据的类型在表的第 5 节的右记列中 https://www.senso.cloud/privacy-policy/) (。 | 处理每个请求的合法基础基于您执行的合同或出于我们合法利益 (运营业务、存档数据、提供管理和 IT 服务、网络安全以防止欺诈和数据泄露所必需的合同。 例如，向客户发送帐单联系人通知需要企业邮件地址、电子邮件地址，或者如果通过信用卡支付，在访问客户支持时，需要信息才能提出支持票证。 |

#### <a name="data-access-via-bots"></a>通过机器人访问数据

如果此应用程序包含机器人或消息扩展，则它可以访问最终用户可识别信息 (EUII) ：名单 (名字、姓氏、显示名称、电子邮件地址) （团队中任何团队成员的姓名、姓氏、电子邮件地址) 或添加到其中聊天）。 此应用是否使用了此功能？

>| **访问 EUII 的理由？**  | **EUII 是否存储在数据库 () ？** | **存储 EUII 的理由** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Senso.cloud 以下子处理器来提升其服务的性能： https://www.senso.cloud/privacy-policy/ 第 5 节。 个人数据的披露。 | 我们和第三方帐户和第三方提供程序共享的数据的类型在表的第 5 节的右记列中 https://www.senso.cloud/privacy-policy/) (。 | 处理每个请求的合法基础基于您执行的合同或出于我们合法利益 (运营业务、存档数据、提供管理和 IT 服务、网络安全以防止欺诈和数据泄露所必需的合同。 例如，向客户发送帐单联系人通知需要企业邮件地址、电子邮件地址，或者如果通过信用卡支付，在访问客户支持时，需要信息才能提出支持票证。 |


#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或 EUII (最终用户可识别) 是否显示在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>Senso 监视针对关键字和图像威胁检测库的聊天消息。  如果发生匹配，我们将针对冲突触发器记录以下信息;时间和日期、网站 ID、短语/图像、严重性、From、To、频道名称、状态和触发库供最终用户查看。  我们将仅在必要长的一段时间内保留 PII，以用于披露收集它的目的，包括出于满足任何法律、运营、会计或报告要求的目的

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>对高级开发人员的受限访问、IP 锁定、双重身份验证和审核跟踪。

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>是

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

下面将显示[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/40112' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/40112" target="_blank">在新建选项卡中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>标识信息

Senso 提供了此信息，这些信息与此应用程序如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件有关。

| **Information** | **响应** |
|:----------------|:-------------|
| 你是否与 Microsoft 标识平台 (Azure AD) ？  | 是 |
| 您是否已查看并遵循了 Microsoft 标识平台 集成清单中列出的所有适用最佳做法？  | 是 |
| 你的应用是否使用 MSAL (Microsoft 身份验证库) 进行身份验证？ | 是 |
| 你的应用是否支持条件访问策略？ | 是 |
| 列出支持的策略类型 | 基于角色的访问权限 |
| 应用是否请求方案最小特权权限？ | 是 |
| 应用的静态注册权限是否准确反映应用将动态和增量请求的权限？ | 是 |
| 你的应用是否支持多租户？ | 是 |
| 你的应用是否具有机密客户端？ | 是 |
| 你是否拥有为应用注册的所有 (统一) URI？ | 是 |
| 对于你的应用，应避免使用什么？ | - 通配符重定向 URI，<br/><br/>- 资源所有者密码凭据 (ROPC) 流 |
| 你的应用是否公开任何 Web API？ | 否 |
| 你的应用是否使用预览 API？ | 否 |
| 你的应用是否使用已弃用 API？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
