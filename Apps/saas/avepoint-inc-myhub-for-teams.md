---
title: AvePoint Inc. Teams MyHub 应用程序信息
ms.author: elmalova
author: elenamalova
ms.date: 10/06/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: MyHub for Teams 的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security 应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 09e1b6500f75bde564b3f4cf40538516fb6dbae4
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 10/18/2021
ms.locfileid: "60429229"
---
# <a name="myhub-for-teams"></a>MyHub for Teams

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2021 年 9 月 29 日</p>

* <a href="https://appsource.microsoft.com/product/web-apps/avepoint.myhubforteams" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

AvePoint Inc. 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | MyHub for Teams |
| ID | avepoint.myhubforteams |
| 合作伙伴公司名称 | AvePoint Inc. |
| 合作伙伴网站的 URL | [https://www.avepoint.com](https://www.avepoint.com) |
| 隐私策略的 URL | [https://www.avepoint.com/company/privacy-policy](https://www.avepoint.com/company/privacy-policy) |
| 使用条款 URL | [https://www.avepoint.com/company/terms-of-use](https://www.avepoint.com/company/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

此信息由 AvePoint Inc. 提供，有关此应用程序如何收集和存储组织数据以及您的组织将拥有对应用程序收集的数据的控制。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph所需的](https://docs.microsoft.com/graph/permissions-reference)任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Directory.Read.All | 两者 | 从数据处理的角度来看，存储应用程序配置数据 | 读取目录数据 | [4d69a8e1-9c38-4b33-b76f-9d59b5ae051b](https://docs.microsoft.com/microsoft-365-app-certification/azure/4d69a8e1-9c38-4b33-b76f-9d59b5ae051b) |
>| Group.ReadWrite.All | 两者 | 从数据处理的角度来看，存储应用程序配置数据 | 读取和写入所有组 | [4d69a8e1-9c38-4b33-b76f-9d59b5ae051b](https://docs.microsoft.com/microsoft-365-app-certification/azure/4d69a8e1-9c38-4b33-b76f-9d59b5ae051b) |
>| Mail.Send | delegated | 从数据处理的角度来看，存储应用程序配置数据 | 以用户身份发送邮件 | [4d69a8e1-9c38-4b33-b76f-9d59b5ae051b](https://docs.microsoft.com/microsoft-365-app-certification/azure/4d69a8e1-9c38-4b33-b76f-9d59b5ae051b) |
>| Reports.Read.All | 应用程序 | 从数据处理的角度来看，存储应用程序配置数据 | 读取所有使用情况报告 | [4d69a8e1-9c38-4b33-b76f-9d59b5ae051b](https://docs.microsoft.com/microsoft-365-app-certification/azure/4d69a8e1-9c38-4b33-b76f-9d59b5ae051b) |
>| Sites.FullControl.All | 应用程序 | 从数据处理的角度来看，存储应用程序配置数据 | 具有对所有网站集的完全控制权限 | [4d69a8e1-9c38-4b33-b76f-9d59b5ae051b](https://docs.microsoft.com/microsoft-365-app-certification/azure/4d69a8e1-9c38-4b33-b76f-9d59b5ae051b) |
>| Sites.Read.All | 应用程序 | 从数据处理的角度来看，存储应用程序配置数据 | 读取所有网站集中的项目 | [4d69a8e1-9c38-4b33-b76f-9d59b5ae051b](https://docs.microsoft.com/microsoft-365-app-certification/azure/4d69a8e1-9c38-4b33-b76f-9d59b5ae051b) |
>| Sites.ReadWrite.All | delegated | 从数据处理的角度来看，存储应用程序配置数据 | 编辑或删除所有网站集中的项目 | [4d69a8e1-9c38-4b33-b76f-9d59b5ae051b](https://docs.microsoft.com/microsoft-365-app-certification/azure/4d69a8e1-9c38-4b33-b76f-9d59b5ae051b) |
>| User.Read.All | 两者 | 从数据处理的角度来看，存储应用程序配置数据 | 读取所有用户&#65533;配置文件 | [4d69a8e1-9c38-4b33-b76f-9d59b5ae051b](https://docs.microsoft.com/microsoft-365-app-certification/azure/4d69a8e1-9c38-4b33-b76f-9d59b5ae051b) |


#### <a name="non-microsoft-services-used"></a>非Microsoft 服务已使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>不Microsoft 服务非活动。



#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或最终用户可识别信息 (EUII) 是否出现在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>是，用户的电子邮件和租户 ID 将显示在日志中。 日志存储在安全的位置，只有授权人员可以在疑难解答过程中访问。 这些日志将在 60 天后存档，用于安全审核，并且将在一年后删除。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>应用程序数据存储在Azure SQL 数据库Azure 存储。 Azure SQL和Azure 存储加密已启用。
只有授权管理员可以访问数据。 管理员登录需要 MFA。 将审核操作。 IP 允许列表还用于限制对数据的访问。

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>标识信息

此信息由 AvePoint Inc. 提供有关此应用程序如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件的信息。

| **Information** | **响应** |
|:----------------|:-------------|
| 是否与 Microsoft 标识平台 (Azure AD) ？  | 是 |
| 您是否已查看并遵循了 Microsoft 标识平台 清单中列出的所有适用最佳做法？  | 是 |
| 你的应用是否使用 MSAL (Microsoft 身份验证库) 进行身份验证？ | 是 |
| 你的应用是否支持条件访问策略？ | 是 |
| 列出支持的策略类型 | 应用程序与 Azure AD联合，因此可以使用所有条件访问规则。 |
| 应用是否请求方案最小特权权限？ | 是 |
| 应用的静态注册权限是否准确反映应用将动态和增量请求的权限？ | 是 |
| 你的应用是否支持多租户？ | 是 |
| 你的应用是否具有机密客户端？ | 是 |
| 你是否拥有为应用注册的所有 (统一) URI？ | 是 |
| 你的应用是否公开任何 Web API？ | 是 |
| 您的权限模型是否仅在客户端应用程序收到正确同意时才允许呼叫成功？ | 是 |
| 你的应用是否使用预览 API？ | 是 |
| 你的应用是否使用已弃用 API？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
