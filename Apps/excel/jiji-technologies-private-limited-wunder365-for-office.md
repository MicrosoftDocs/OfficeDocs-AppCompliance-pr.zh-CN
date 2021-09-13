---
title: Wunder365 for Office Ji Technologies Private Limited 的应用程序信息
ms.author: elmalova
author: elenamalova
ms.date: 12/15/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Wunder365 for Office 的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security 应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: ab9ea33824f66afecc8af8df74754fc7f2dd6d43
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 09/12/2021
ms.locfileid: "59278912"
---
# <a name="wunder365-for-office"></a>Wunder365 for Office

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2020 年 12 月 15 日</p>

* <a href="https://appsource.microsoft.com/product/office/WA200001529" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

JiJi Technologies Private Limited 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | Wunder365 for Office |
| ID | WA200001529 |
| Office 365支持的客户端 | Excel 2016 Mac、Excel 2013 或更高版本（在 mac Windows、Excel web 版、Word 2016 或更高版本、Word web 版、Word 2013 或 Windows 或更高版本OneNote web 版 |
| 合作伙伴公司名称 | JiJi Technologies Private Limited |
| 合作伙伴网站的 URL | [https://www.jijitechnologies.com](https://www.jijitechnologies.com) |
| 隐私策略的 URL | [https://www.wunder365.com/office-addin-privacy-policy](https://www.wunder365.com/office-addin-privacy-policy) |
| 使用条款 URL | [https://www.wunder365.com/terms-of-service](https://www.wunder365.com/terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

此信息由 JiJi Technologies Private Limited 提供，用于了解此应用如何收集和存储组织数据，以及组织将拥有对应用收集的数据的控制。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph所需的](https://docs.microsoft.com/graph/permissions-reference)任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD 应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Group.ReadWrite.All | delegated | 不存储任何数据。 | 若要获取/更新 Planner 任务，在团队频道中发布任务更新 | [3c95a8b6-b71c-4c4a-8a1a-c7b9b80d9e9c](https://docs.microsoft.com/microsoft-365-app-certification/azure/3c95a8b6-b71c-4c4a-8a1a-c7b9b80d9e9c) |
>| Mail.Send | delegated | 不存储任何数据。 | 允许应用向用户发送电子邮件通知 | [3c95a8b6-b71c-4c4a-8a1a-c7b9b80d9e9c](https://docs.microsoft.com/microsoft-365-app-certification/azure/3c95a8b6-b71c-4c4a-8a1a-c7b9b80d9e9c) |
>| offline_access | delegated | 不存储任何数据。 | 使用户保持登录状态。 | [3c95a8b6-b71c-4c4a-8a1a-c7b9b80d9e9c](https://docs.microsoft.com/microsoft-365-app-certification/azure/3c95a8b6-b71c-4c4a-8a1a-c7b9b80d9e9c) |
>| openid | delegated | 不存储任何数据。 | 允许用户使用帐户登录 | [3c95a8b6-b71c-4c4a-8a1a-c7b9b80d9e9c](https://docs.microsoft.com/microsoft-365-app-certification/azure/3c95a8b6-b71c-4c4a-8a1a-c7b9b80d9e9c) |
>| 个人资料 | delegated | UPN、用户 ID、电子邮件 ID、用于许可验证的租户 ID、免费许可证。 | 允许用户使用帐户登录 | [3c95a8b6-b71c-4c4a-8a1a-c7b9b80d9e9c](https://docs.microsoft.com/microsoft-365-app-certification/azure/3c95a8b6-b71c-4c4a-8a1a-c7b9b80d9e9c) |


#### <a name="non-microsoft-services-used"></a>非Microsoft 服务使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>不Microsoft 服务非活动。



#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或最终用户可识别信息 (EUII) 是否出现在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>我们正在登录到 Azure 应用程序Insights。 我们正在记录租户 ID 和用户的电子邮件 ID，以识别问题并帮助客户解决问题。


#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>所有 Web 应用程序和存储资源均位于未连接到公司 AAD 的订阅中，只有管理员有权访问这些资源。 这些管理员需要 2FA。 


#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

下面将显示[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36250' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36250" target="_blank">在新建选项卡中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>标识信息

此信息由 JiJi Technologies Private Limited 提供有关此应用如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件的信息。

| **Information** | **响应** |
|:----------------|:-------------|
| 你是否与 Microsoft 标识平台 (Azure AD) ？  | 是 |
| 您是否已查看并遵循了 Microsoft 标识平台 清单中列出的所有适用最佳做法？  | 是 |
| 你的应用是否使用 MSAL (Microsoft 身份验证库) 进行身份验证？ | 是 |
| 你的应用是否支持条件访问策略？ | 是 |
| 列出支持的策略类型 | 为具有管理角色的用户要求多重身份验证、需要 Azure 管理任务的多重身份验证、阻止尝试使用旧版身份验证协议的用户登录、需要受信任位置进行 Azure AD 多重身份验证注册、阻止或授予来自特定位置的访问权限、阻止有风险的登录行为 |
| 应用是否请求方案最小特权权限？ | 是 |
| 应用的静态注册权限是否准确反映应用将动态和增量请求的权限？ | 是 |
| 你的应用是否支持多租户？ | 是 |
| 你的应用是否具有机密客户端？ | 是 |
| 你是否拥有为应用注册的所有 (统一) URI？ | 是 |
| 对于你的应用，应避免使用什么？ | - 通配符重定向 URI，<br/>- OAuth2 隐式Flow，除非 SPA 需要<br/>- 资源所有者密码凭据 (ROPC) 流 |
| 你的应用是否公开任何 Web API？ | 否 |
| 你的应用是否使用预览 API？ | 是 |
| 你的应用是否使用已弃用 API？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
