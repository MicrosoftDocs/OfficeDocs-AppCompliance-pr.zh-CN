---
title: MoveInSync WorkInSync 的应用程序信息
ms.author: elmalova
author: elenamalova
ms.date: 09/01/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: WorkInSync 的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: c3976dcaddcc5121b58cd65836b19df1f057e79b
ms.sourcegitcommit: 23a1fdeaf3905ab5f7acfbb378c7c23aaedcdc29
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 09/03/2021
ms.locfileid: "58873749"
---
# <a name="workinsync"></a>WorkInSync

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2021 年 9 月 1 日</p>

* <a href="https://teams.microsoft.com/l/app/4e00663a-be72-4de1-a163-269a477a7a6e" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002974" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

MoveInSync 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | WorkInSync |
| ID | WA200002974 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | MoveInSync |
| 合作伙伴网站的 URL | [https://www.workinsync.io](https://www.workinsync.io) |
| 应用程序Teams页的 URL | [https://www.workinsync.io/teams-app-for-workinsync/](https://www.workinsync.io/teams-app-for-workinsync/) |
| 隐私策略的 URL | [https://www.workinsync.io/privacy-policy/](https://www.workinsync.io/privacy-policy/) |
| 使用条款 URL | [https://www.workinsync.io/terms-and-condition/](https://www.workinsync.io/terms-and-condition/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

MoveInSync 提供了此信息，这些信息与此应用程序如何收集和存储组织数据以及组织将拥有对应用收集的数据的控制有关。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph所需的](https://docs.microsoft.com/graph/permissions-reference)任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD 应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Directory.Read.All | delegated | 1。获取可传递的组的成员详细信息。 在频道上下文中安装时，它们用于"团队活动"选项卡。 2. 获取组织中用户的用户配置文件 &amp;  详细信息列表。 当在个人上下文中安装"团队活动"选项卡时，会使用这些选项卡作为回退显示团队成员的预览，以防人员 API 在非 outlook 用户 (失败)  | 无 | [fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc](https://docs.microsoft.com/microsoft-365-app-certification/azure/fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc) |
>| People.Read | delegated | 若要获取与要显示在"团队活动"选项卡中的已登录用户最相关的人员，则安装在个人上下文中。 | 无 | [fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc](https://docs.microsoft.com/microsoft-365-app-certification/azure/fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc) |
>| Presence.Read | delegated | 在个人和频道上下文中的"团队活动"选项卡中获取用户列表状态信息 | 无 | [fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc](https://docs.microsoft.com/microsoft-365-app-certification/azure/fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc) |
>| Presence.Read.All | delegated | 在个人和频道上下文中的"团队活动"选项卡中获取用户列表状态信息 | 无 | [fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc](https://docs.microsoft.com/microsoft-365-app-certification/azure/fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc) |
>| User.Read.All | 应用程序 | 用于获取任何用户的报告管理器信息，以向经理发送预订和签入/签出通知 | 无 | [fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc](https://docs.microsoft.com/microsoft-365-app-certification/azure/fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc) |
>| User.ReadBasic.All | delegated | 用于读取员工的个人资料照片 | 无 | [fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc](https://docs.microsoft.com/microsoft-365-app-certification/azure/fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc) |
>| email | delegated | 使用客户端库获取 SSO Teams需要 | 无 | [fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc](https://docs.microsoft.com/microsoft-365-app-certification/azure/fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc) |
>| offline_access | delegated | 使用客户端库获取 SSO Teams需要 | 无 | [fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc](https://docs.microsoft.com/microsoft-365-app-certification/azure/fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc) |
>| openid | delegated | 使用客户端库获取 SSO Teams需要 | 无 | [fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc](https://docs.microsoft.com/microsoft-365-app-certification/azure/fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc) |
>| 个人资料 | delegated | 使用客户端库获取 SSO Teams需要 | 无 | [fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc](https://docs.microsoft.com/microsoft-365-app-certification/azure/fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc) |


#### <a name="non-microsoft-services-used"></a>非Microsoft 服务使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>不Microsoft 服务非活动。

#### <a name="data-access-via-bots"></a>通过机器人访问数据

如果此应用包含机器人或消息扩展，则它可以访问最终用户可识别信息 (EUII) ：名单 (名字、姓氏、显示名称、电子邮件地址) （团队中任何团队成员的姓名、姓氏、电子邮件地址) 或添加到其中聊天）。 此应用是否使用了此功能？

>| **访问 EUII 的理由？**  | **EUII 是否存储在数据库 (中) ？** | **存储 EUII 的理由** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| 1. 我们会读取员工的电子邮件地址 (用户原则名称) WorkInSync 注册用户列表进行匹配。  | 否 |  |


#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或最终用户可识别信息 (EUII) 是否出现在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>应用程序遥测或日志中不显示 OII 或 EUII。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>数据不与合作伙伴系统共享或存储在合作伙伴系统中。 所有数据存储完全归 WorkInSync 所有，并且仅由 WorkInSync 管理。

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>否

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

此信息由 MoveInSync 提供有关此应用如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件的信息。

| **Information** | **响应** |
|:----------------|:-------------|
| 你是否与 Microsoft 标识平台 (Azure AD) ？  | 是 |
| 您是否已查看并遵循了集成清单中列出的所有适用的Microsoft 标识平台做法？  | 是 |
| 你的应用是否使用 MSAL (Microsoft 身份验证库) 进行身份验证？ | 否 |
| 你的应用是否支持条件访问策略？ | 是 |
| 列出支持的策略类型 | 多重身份验证 |
| 应用是否请求方案最小特权权限？ | 是 |
| 应用的静态注册权限是否准确反映应用将动态和增量请求的权限？ | 是 |
| 你的应用是否支持多租户？ | 是 |
| 你的应用是否具有机密客户端？ | 是 |
| 你是否拥有为应用注册的所有重定向统一 (URI) URI？ | 是 |
| 对于你的应用，应避免使用什么？ | - 通配符重定向 URI，<br/><br/>- 资源所有者密码凭据 (ROPC) 流 |
| 你的应用是否公开任何 Web API？ | 否 |
| 你的应用是否使用预览 API？ | 否 |
| 你的应用是否使用已弃用 API？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
