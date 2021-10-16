---
title: 由数字计算机Enterprise FormMachines 的应用程序信息
ms.author: elmalova
author: elenamalova
ms.date: 07/15/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: FormMachines 的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: be8e514f248b177d0b09e856d5537e770d50220c
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 10/16/2021
ms.locfileid: "60411046"
---
# <a name="formmachines"></a>FormMachines

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2021 年 7 月 5 日</p>

* <a href="https://teams.microsoft.com/l/app/54d8b826-3e30-4589-a77a-ed99cfbbb4c9" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001217" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

由数字Enterprise提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | FormMachines |
| ID | WA200001217 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | Enterprise Digital Machines |
| 合作伙伴网站的 URL | [https://www.formmachines.com](https://www.formmachines.com) |
| 应用程序Teams页的 URL | [https://www.FormMachines.com](https://www.FormMachines.com) |
| 隐私策略的 URL | [https://www.formmachines.com/dist/docs#/statements_and_agre...](https://www.formmachines.com/dist/docs#/statements_and_agreements/privacy) |
| 使用条款 URL | [https://www.formmachines.com/dist/docs#/statements_and_agre...](https://www.formmachines.com/dist/docs#/statements_and_agreements/terms_of_service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

此信息由 Enterprise Digital Machines 提供有关此应用如何收集和存储组织数据以及组织将拥有对应用收集的数据的控制的信息。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph](https://docs.microsoft.com/graph/permissions-reference)所需的任何 Microsoft 权限。

>此应用程序不使用 Microsoft Graph。


#### <a name="non-microsoft-services-used"></a>非Microsoft 服务已使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>不Microsoft 服务非活动。

#### <a name="data-access-via-bots"></a>通过机器人访问数据

如果此应用程序包含机器人或消息扩展，则它可以访问最终用户可识别信息 (EUII) ：名单 (名字、姓氏、显示名称、电子邮件地址) （团队中任何团队成员的姓名、姓氏、电子邮件地址) 或添加到其中聊天）。 此应用是否使用了此功能？

>无法访问 EUII。


#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或 EUII (最终用户可识别) 是否显示在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>在我们的错误日志中，我们通常只记录与错误本身相关的信息。 但是，为了向特定客户提供帮助，我们可能会识别相关域，但无法识别客户本身。 错误日志联机查看，而不是下载和查看。 90 天后将自动删除错误日志。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>数据存储在基于 Azure 美国数据中心中。 客户端提供的数据（如模板和提交）在 DB/BLOB 中加密。 文件附件存储在专用 Azure BLOB 容器中，用户必须先进行身份验证，然后才能访问它们。 我们最多有两个管理员可以访问我们的生产资产，以进行故障排除和部署。 这两个管理员帐户的分区方式与所有其他帐户不同。 管理员访问权限的数量不会超过 2。 

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>是

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

下面将显示[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36144' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36144" target="_blank">在新建选项卡中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>标识信息

此信息由数字计算机Enterprise此应用如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件。

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
| 对于你的应用，应避免使用什么？ | - 通配符重定向 URI，<br/>- OAuth2 隐式Flow，除非 SPA 需要<br/>- 资源所有者密码凭据 (ROPC) 流 |
| 你的应用是否公开任何 Web API？ | 是 |
| 您的权限模型是否仅在客户端应用程序收到正确同意时才允许呼叫成功？ | 是 |
| 你的应用是否使用预览 API？ | 否 |
| 你的应用是否使用已弃用 API？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

