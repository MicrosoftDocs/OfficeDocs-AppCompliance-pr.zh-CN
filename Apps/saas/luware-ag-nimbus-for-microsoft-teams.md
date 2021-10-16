---
title: Luware AG Microsoft Teams Luware Nimbus 的应用程序信息
ms.author: elmalova
author: elenamalova
ms.date: 10/07/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Luware Nimbus for Microsoft Teams 的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security 应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: d7139f3ca934da20e58bb9f838217796ca5644da
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 10/16/2021
ms.locfileid: "60410486"
---
# <a name="luware-nimbus-for-microsoft-teams"></a>Luware Nimbus for Microsoft Teams

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2021 年 10 月 1 日</p>

* <a href="https://appsource.microsoft.com/product/web-apps/luwareagzurich.advanced_routing_azure_marketplace" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

Luware AG 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | Luware Nimbus for Microsoft Teams |
| ID | luwareagzurich.advanced_routing_azure_marketplace |
| 合作伙伴公司名称 | Luware AG |
| 合作伙伴网站的 URL | [https://luware.com](https://luware.com) |
| 隐私策略的 URL | [https://luware.com/en/privacy-policy](https://luware.com/en/privacy-policy) |
| 使用条款 URL | [https://luware.com/en/agreements/saas/](https://luware.com/en/agreements/saas/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

Luware AG 提供了此信息，这些信息与此应用程序如何收集和存储组织数据以及组织将拥有对应用收集的数据的控制有关。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph所需的](https://docs.microsoft.com/graph/permissions-reference)任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.Read | delegated | 助理控制台：读取登录用户的日历显示带约会的日历 | 无 | [23694b6c-5a4a-45ce-9c6a-37c5f1880d4e](https://docs.microsoft.com/microsoft-365-app-certification/azure/23694b6c-5a4a-45ce-9c6a-37c5f1880d4e) |
>| Calendars.Read.Shared | delegated | 助理控制台：读取共享日历以显示带约会的日历 | 无 | [23694b6c-5a4a-45ce-9c6a-37c5f1880d4e](https://docs.microsoft.com/microsoft-365-app-certification/azure/23694b6c-5a4a-45ce-9c6a-37c5f1880d4e) |
>| Contacts.Read | delegated | 助理控制台：搜索Exchange登录用户的联系人 | 无 | [23694b6c-5a4a-45ce-9c6a-37c5f1880d4e](https://docs.microsoft.com/microsoft-365-app-certification/azure/23694b6c-5a4a-45ce-9c6a-37c5f1880d4e) |
>| Contacts.Read.Shared | delegated | 助理控制台：在共享联系人Exchange搜索 | 无 | [23694b6c-5a4a-45ce-9c6a-37c5f1880d4e](https://docs.microsoft.com/microsoft-365-app-certification/azure/23694b6c-5a4a-45ce-9c6a-37c5f1880d4e) |
>| GroupMember.Read.All | 应用程序 | 获取团队成员、读取安全组 | 我们将此信息存储为通过组成员身份管理呼叫中心代理 | [23694b6c-5a4a-45ce-9c6a-37c5f1880d4e](https://docs.microsoft.com/microsoft-365-app-certification/azure/23694b6c-5a4a-45ce-9c6a-37c5f1880d4e) |
>| Presence.Read.All | delegated | 在助理控制台页面上的联系人搜索中显示状态 | 无 | [23694b6c-5a4a-45ce-9c6a-37c5f1880d4e](https://docs.microsoft.com/microsoft-365-app-certification/azure/23694b6c-5a4a-45ce-9c6a-37c5f1880d4e) |
>| User.Read | delegated | 从已登录 (用户记录获取 UserInformation)  | 无 | [23694b6c-5a4a-45ce-9c6a-37c5f1880d4e](https://docs.microsoft.com/microsoft-365-app-certification/azure/23694b6c-5a4a-45ce-9c6a-37c5f1880d4e) |
>| User.Read.All | 两者 | Nimbus 应用 - 获取 CallerInformation。 在拨打到联系人中心的内部呼叫时，我们将对可能是谁进行反向查找，以便向代理显示该信息。 在助理控制台 (委派权限) 我们搜索整个内部目录以查找转移目标。 | 对于报告调用最多的 REasons，我们将存储该数据。 | [23694b6c-5a4a-45ce-9c6a-37c5f1880d4e](https://docs.microsoft.com/microsoft-365-app-certification/azure/23694b6c-5a4a-45ce-9c6a-37c5f1880d4e) |
>| User.ReadBasic.All | delegated | 有限用户搜索 | 无 | [23694b6c-5a4a-45ce-9c6a-37c5f1880d4e](https://docs.microsoft.com/microsoft-365-app-certification/azure/23694b6c-5a4a-45ce-9c6a-37c5f1880d4e) |
>| Calls.AccessMedia.All | 应用程序 | 其中许多应用/机器人 (每个联系人中心队列一) ：订阅 DTMF 提示音，客户可以在其中实际选择他的位置在 IVR 中 | 用于报告原因的通过 IVR 的选定方式的所有 DTMF 信息 | [7e1fc6b3-90a7-4a98-a766-5627193e95bc](https://docs.microsoft.com/microsoft-365-app-certification/azure/7e1fc6b3-90a7-4a98-a766-5627193e95bc) |
>| Calls.Initiate.All | 应用程序 | 其中许多应用/机器人 (每个联系人中心队列) 一个：呼叫代理  | 用于报告原因的所有 CDR 信息 | [7e1fc6b3-90a7-4a98-a766-5627193e95bc](https://docs.microsoft.com/microsoft-365-app-certification/azure/7e1fc6b3-90a7-4a98-a766-5627193e95bc) |
>| Calls.InitiateGroupCall.All | 应用程序 | 其中许多应用/机器人 (每个联系人中心队列) 一个：呼叫代理  | 用于报告原因的所有 CDR 信息 | [7e1fc6b3-90a7-4a98-a766-5627193e95bc](https://docs.microsoft.com/microsoft-365-app-certification/azure/7e1fc6b3-90a7-4a98-a766-5627193e95bc) |
>| Calls.JoinGroupCall.All | 应用程序 | 其中许多应用/机器人 (每个联系人中心队列) 一个：加入升级的呼叫以播放通知 | 用于报告原因的所有 CDR 信息 | [7e1fc6b3-90a7-4a98-a766-5627193e95bc](https://docs.microsoft.com/microsoft-365-app-certification/azure/7e1fc6b3-90a7-4a98-a766-5627193e95bc) |


#### <a name="non-microsoft-services-used"></a>非Microsoft 服务使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>不Microsoft 服务非活动。



#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或 EUII (最终用户可识别) 是否显示在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>聚合报告数据 (呼叫详细信息记录、呼叫者信息、呼叫处理和呼叫旅程详细信息等 ) ：24 个月的配置数据：客户合同持续时间 +30 天应用程序日志：临时存储内部应用程序日志 (，以帮助我们的支持工程师对应用程序组件的性能和操作进行故障排除) 30 天。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>https://luware.com/en/privacy-policy/

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>是

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>标识信息

Luware AG 提供了此信息，这些信息与此应用程序如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件有关。

| **Information** | **响应** |
|:----------------|:-------------|
| 是否与 Microsoft 标识平台 (Azure AD) ？  | 是 |
| 您是否已审阅并遵循了 Microsoft 标识平台 集成清单中列出的所有适用最佳做法？  | 是 |
| 你的应用是否使用 MSAL (Microsoft 身份验证库) 进行身份验证？ | 是 |
| 你的应用是否支持条件访问策略？ | 是 |
| 列出支持的策略类型 | 客户端应用、用户和组 |
| 应用是否请求方案最小特权权限？ | 是 |
| 应用的静态注册权限是否准确反映应用将动态和增量请求的权限？ | 是 |
| 你的应用是否支持多租户？ | 是 |
| 你的应用是否具有机密客户端？ | 是 |
| 你是否拥有为应用注册的所有 (统一) URI？ | 是 |
| 对于你的应用，应避免使用什么？ | - 通配符重定向 URI，<br/>- OAuth2 隐式Flow，除非 SPA 需要<br/>- 资源所有者密码凭据 (ROPC) 流 |
| 你的应用是否公开任何 Web API？ | 是 |
| 您的权限模型是否仅在客户端应用程序收到正确同意时才允许呼叫成功？ | 是 |
| 你的应用是否使用预览 API？ | 是 |
| 你的应用是否使用已弃用 API？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

