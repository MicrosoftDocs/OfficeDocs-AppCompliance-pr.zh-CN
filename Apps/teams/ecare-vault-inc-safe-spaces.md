---
title: eCare Vault Inc 保险箱存储空间的应用程序信息。
ms.author: elmalova
author: elenamalova
ms.date: 08/31/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: CSA STAR 注册表中有关保险箱空间、其数据处理策略、Microsoft Cloud App Security应用程序目录信息和安全/合规性信息的所有可用安全性和合规性信息。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 39ca1a0a99e62bbedb14d0248cb751bf4089a70f
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 10/16/2021
ms.locfileid: "60414688"
---
# <a name="safe-spaces"></a>安全空间

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2021 年 7 月 14 日</p>

* <a href="https://teams.microsoft.com/l/app/ec321cf7-ae3e-4ed4-a707-ff5c18e77313" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002691" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

eCare Vault Inc. 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | 安全空间 |
| ID | WA200002691 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | eCare Vault Inc. |
| 合作伙伴网站的 URL | [https://ecarevault.com](https://ecarevault.com) |
| 应用程序Teams页的 URL | [https://ecarevault.com/ecare-vault-for-teams](https://ecarevault.com/ecare-vault-for-teams) |
| 隐私策略的 URL | [https://ecarevault.com/ecare-vault-privacy-policy](https://ecarevault.com/ecare-vault-privacy-policy) |
| 使用条款 URL | [https://downloads.ecarevault.com/downloads/eCare+Vault+-+Te...](https://downloads.ecarevault.com/downloads/eCare+Vault+-+Terms+of+Service.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

此信息由 eCare Vault Inc. 提供，用于了解此应用程序如何收集和存储组织数据，以及您的组织将拥有对应用收集的数据的控制。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph](https://docs.microsoft.com/graph/permissions-reference)所需的任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| EduRoster.Read | delegated | 名称和出生日期用于预填充输入字段 | 无 - 存储的所有数据都是用户 (预填充到字段中的数据，然后是用户提交的)  | [6919164d-b678-4c3d-a268-e6fbecc1e68d](https://docs.microsoft.com/microsoft-365-app-certification/azure/6919164d-b678-4c3d-a268-e6fbecc1e68d) |
>| Group.Read.All | delegated | 用于获取有关可在应用程序中显示的频道的信息 | 此权限无 | [6919164d-b678-4c3d-a268-e6fbecc1e68d](https://docs.microsoft.com/microsoft-365-app-certification/azure/6919164d-b678-4c3d-a268-e6fbecc1e68d) |
>| GroupMember.Read.All | delegated | AAD用于生成电子保管库团队名单的团队成员 ID | AAD存储用户 ID 以与每个成员的电子邮件保管库用户帐户关联 | [6919164d-b678-4c3d-a268-e6fbecc1e68d](https://docs.microsoft.com/microsoft-365-app-certification/azure/6919164d-b678-4c3d-a268-e6fbecc1e68d) |
>| User.Read | delegated | 电子邮件地址和AAD ID 用于注册 &amp; 用户并将其与电子数据保管库用户帐户关联 | 用户帐户的电子邮件地址AAD ID，以及通过 Bot Framework 向用户发送通知 | [6919164d-b678-4c3d-a268-e6fbecc1e68d](https://docs.microsoft.com/microsoft-365-app-certification/azure/6919164d-b678-4c3d-a268-e6fbecc1e68d) |
>| User.Read.All | delegated | 姓名和AAD ID 和电子邮件地址，仅适用于安装了空格的频道保险箱用户 | 针对AAD保管库用户帐户存储的名称、id 和电子邮件地址 | [6919164d-b678-4c3d-a268-e6fbecc1e68d](https://docs.microsoft.com/microsoft-365-app-certification/azure/6919164d-b678-4c3d-a268-e6fbecc1e68d) |
>| email | delegated | 仅电子邮件地址 | 无 - 用户决定提交表单，这将  | [6919164d-b678-4c3d-a268-e6fbecc1e68d](https://docs.microsoft.com/microsoft-365-app-certification/azure/6919164d-b678-4c3d-a268-e6fbecc1e68d) |
>| openid | delegated | 电子邮件地址和AAD ID 用于注册 &amp; 用户并将其与电子数据保管库用户帐户关联 | 用户帐户的电子邮件地址AAD ID，以及通过 Bot Framework 向用户发送通知 | [6919164d-b678-4c3d-a268-e6fbecc1e68d](https://docs.microsoft.com/microsoft-365-app-certification/azure/6919164d-b678-4c3d-a268-e6fbecc1e68d) |
>| 个人资料 | delegated | 用户名称用于填充用户注册屏幕。 | 无直接 - 用户在注册时选择将其名称提交到系统 | [6919164d-b678-4c3d-a268-e6fbecc1e68d](https://docs.microsoft.com/microsoft-365-app-certification/azure/6919164d-b678-4c3d-a268-e6fbecc1e68d) |

#### <a name="data-access-using-other-microsoft-apis"></a>使用其他 Microsoft API 进行数据访问

基于组织构建的应用和加载项Microsoft 365除 Microsoft Graph 外的其他 Microsoft API 来收集或处理 OII (组织) 。 列出除 Microsoft API Graph此应用使用的任何 Microsoft API。

>| **API** |  **是否收集 OII？** |  **收集哪些 OII？** | **收集 OII 的理由？** | **是否存储 OII？** | **存储 OII 的理由** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| MSAL (Microsoft 身份验证终结点)  | 否 |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>非Microsoft 服务已使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>| **所有非Microsoft 服务 OII 将转移到** |  **转移了哪些 OII？** | **转移 OII 的理由？** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| eCare Vault | 租户/公司信息、用户登录域名、用户登录Microsoft Teams团队 &amp; 频道标识符。 | 保险箱空间是电子数据保管库平台的配套应用程序。 OII 要求将用户从 Microsoft Teams链接到公司的电子保管库用户。 |

#### <a name="data-access-via-bots"></a>通过机器人访问数据

如果此应用程序包含机器人或消息扩展，则它可以访问最终用户可识别信息 (EUII) ：名单 (名字、姓氏、显示名称、电子邮件地址) （团队中任何团队成员的姓名、姓氏、电子邮件地址) 或添加到其中聊天）。 此应用是否使用了此功能？

>无法访问 EUII。


#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或 EUII (最终用户可识别) 是否显示在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>应用程序遥测或日志中不显示 OII 或 EUII。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>所有传输到合作伙伴系统 (不包括任何 OII、PII 或 PHI) 在 BAA 下传输，以确保 HIPAA 合规性。

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>标识信息

此信息由 eCare Vault Inc. 提供，用于了解此应用如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件。

| **Information** | **响应** |
|:----------------|:-------------|
| 是否与 Microsoft 标识平台 (Azure AD) ？  | 是 |
| 您是否已审阅并遵循了 Microsoft 标识平台 集成清单中列出的所有适用最佳做法？  | 是 |
| 你的应用是否使用 MSAL (Microsoft 身份验证库) 进行身份验证？ | 是 |
| 你的应用是否支持条件访问策略？ | 否 |
| 应用是否请求方案最小特权权限？ | 是 |
| 应用的静态注册权限是否准确反映应用将动态和增量请求的权限？ | 是 |
| 你的应用是否支持多租户？ | 是 |
| 你的应用是否具有机密客户端？ | 否 |
| 你是否拥有为应用注册的所有 (统一) URI？ | 是 |
| 对于你的应用，应避免使用什么？ | - 通配符重定向 URI，<br/><br/>- 资源所有者密码凭据 (ROPC) 流 |
| 你的应用是否公开任何 Web API？ | 是 |
| 您的权限模型是否仅在客户端应用程序收到正确同意时才允许呼叫成功？ | 是 |
| 你的应用是否使用预览 API？ | 是 |
| 你的应用是否使用已弃用 API？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

