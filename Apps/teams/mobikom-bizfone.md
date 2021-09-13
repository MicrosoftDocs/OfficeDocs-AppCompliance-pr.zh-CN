---
title: MobiKOM 的 Bizfone 应用程序信息
ms.author: elmalova
author: elenamalova
ms.date: 08/24/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Bizfone 的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 20f1497c8cb4541982082a6bfbccd0f4968a8663
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 09/12/2021
ms.locfileid: "59277202"
---
# <a name="bizfone"></a>Bizfone

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2021 年 8 月 24 日</p>

* <a href="https://teams.microsoft.com/l/app/5be25d59-35cd-4318-83b0-2a5d5668ddcd" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000874" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

MobiKOM 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | Bizfone |
| ID | WA200000874 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | MobiKOM |
| 合作伙伴网站的 URL | [https://mobikom.dk](https://mobikom.dk) |
| 应用程序Teams页的 URL | [https://mobikom.dk/faq/](https://mobikom.dk/faq/) |
| 隐私策略的 URL | [https://mobikom.dk/privatlivs-og-cookiepolitik/](https://mobikom.dk/privatlivs-og-cookiepolitik/) |
| 使用条款 URL | [https://mobikom.dk/salgs-og-leveringsbetingelser/](https://mobikom.dk/salgs-og-leveringsbetingelser/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

MobiKOM 提供了此信息，这些信息与此应用程序如何收集和存储组织数据以及您的组织将拥有对应用收集的数据的控制有关。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph所需的](https://docs.microsoft.com/graph/permissions-reference)任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD 应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.Read | delegated | 日历用于用户能够向同事显示其国家/地区并使用会议设置其电话 | 日历用于用户能够向同事显示其国家/地区并使用会议设置其电话 | [1dd6ac57-e6f0-4995-a57f-b6d074c16e11](https://docs.microsoft.com/microsoft-365-app-certification/azure/1dd6ac57-e6f0-4995-a57f-b6d074c16e11) |
>| Contacts.Read | delegated | 如果用户想要在应用中显示联系人，以便更轻松地拨打联系人，可以存储这些联系人 | 如果用户想要在应用中显示联系人，以便更轻松地拨打联系人，可以存储这些联系人 | [1dd6ac57-e6f0-4995-a57f-b6d074c16e11](https://docs.microsoft.com/microsoft-365-app-certification/azure/1dd6ac57-e6f0-4995-a57f-b6d074c16e11) |
>| User.Read | delegated | 此应用程序中的用户阅读用于标识目的。 | 此应用程序中的用户阅读用于标识目的。 | [1dd6ac57-e6f0-4995-a57f-b6d074c16e11](https://docs.microsoft.com/microsoft-365-app-certification/azure/1dd6ac57-e6f0-4995-a57f-b6d074c16e11) |
>| User.Read | delegated | 我们不会存储数据。 应用程序仅用于身份验证目的 | 我们不会存储数据。 应用程序仅用于身份验证目的 | [fc8f7563-e8ea-4b6d-9622-82775a21a35a](https://docs.microsoft.com/microsoft-365-app-certification/azure/fc8f7563-e8ea-4b6d-9622-82775a21a35a) |

#### <a name="data-access-using-other-microsoft-apis"></a>使用其他 Microsoft API 进行数据访问

基于此模型构建的应用和Microsoft 365可能会使用除 Microsoft Graph 外的其他 Microsoft API 来收集或处理 OII (组织) 。 列出除 Microsoft API Graph此应用使用的任何 Microsoft API。

>| **API** |  **是否收集 OII？** |  **收集哪些 OII？** | **收集 OII 的理由？** | **是否存储 OII？** | **存储 OII 的理由** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| EWS。AccessAsUser.All | 是 | 公司名称、员工姓名和电话号码 | 能够向应用中的用户显示数据并让他们使用它 | 公司名称、员工姓名和电话号码 | 能够向应用中的用户显示数据并让他们使用它 |

#### <a name="non-microsoft-services-used"></a>非Microsoft 服务使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>| **所有非Microsoft 服务 OII 将转移到** |  **转移了哪些 OII？** | **转移 OII 的理由？** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| 功能区通信、Vox作为、team.blue、Fakturaservice.dk A/S、弹性 | 公司名称、员工姓名和电话号码 | 功能区提供我们的 Teams SBC。 Vox作为国际号码使用，但仅当你拥有这些号码时。 team.blue 是宿主提供商。 FakturaService.dk A/S 用于计费。 弹性用于日志记录 |

#### <a name="data-access-via-bots"></a>通过机器人访问数据

如果此应用包含机器人或消息扩展，它可以访问最终用户可识别信息 (EUII) ：名单 (名字、姓氏、显示名称、电子邮件地址) （团队中任何团队成员的姓名、姓氏、电子邮件地址) 或添加到其中聊天）。 此应用是否使用了此功能？

>无法访问 EUII。


#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或最终用户可识别信息 (EUII) 是否出现在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>应用程序遥测或日志中不显示 OII 或 EUII。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>每个用户都是使用我们的服务的公司的员工。 他们具有可删除和编辑数据的管理员。 DBA 在最终用户获得访问权限之前也已就位

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>是

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

下面将显示[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/" target="_blank">在新建选项卡中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>标识信息

MobiKOM 提供了此信息，这些信息与此应用程序如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件有关。

| **Information** | **响应** |
|:----------------|:-------------|
| 你是否与 Microsoft 标识平台 (Azure AD) ？  | 是 |
| 您是否已审阅并遵循了 Microsoft 标识平台 集成清单中列出的所有适用最佳做法？  | 是 |
| 你的应用是否使用 MSAL (Microsoft 身份验证库) 进行身份验证？ | 否 |
| 你的应用是否支持条件访问策略？ | 是 |
| 列出支持的策略类型 | 多重身份验证 |
| 应用是否请求方案最小特权权限？ | 是 |
| 应用的静态注册权限是否准确反映应用将动态和增量请求的权限？ | 是 |
| 你的应用是否支持多租户？ | 是 |
| 你的应用是否具有机密客户端？ | 否 |
| 你是否拥有为应用注册的所有 (统一) URI？ | 是 |
| 对于你的应用，应避免使用什么？ | - 通配符重定向 URI，<br/>- OAuth2 隐式Flow，除非 SPA 需要<br/>- 资源所有者密码凭据 (ROPC) 流 |
| 你的应用是否公开任何 Web API？ | 否 |
| 你的应用是否使用预览 API？ | 是 |
| 你的应用是否使用已弃用 API？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
