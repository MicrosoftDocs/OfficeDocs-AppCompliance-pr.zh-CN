---
title: Casedoc 虚拟听力的应用程序信息
ms.author: elmalova
author: elenamalova
ms.date: 09/28/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Casedoc 虚拟听力的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security 应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: c10a429f38ed32c5c11cdab448eb1e523301978a
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 10/18/2021
ms.locfileid: "60427144"
---
# <a name="casedoc-virtual-hearing"></a>Casedoc 虚拟听觉

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2021 年 9 月 28 日</p>

* <a href="https://teams.microsoft.com/l/app/3e701664-cc46-49e4-b356-1a7ac6500998" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003164" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

Casedoc 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | Casedoc 虚拟听觉 |
| ID | WA200003164 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | Casedoc |
| 合作伙伴网站的 URL | [https://www.casedoc.com](https://www.casedoc.com) |
| 应用程序Teams页的 URL | [https://casedoc.com/virtual-hearing-for-teams/](https://casedoc.com/virtual-hearing-for-teams/) |
| 隐私策略的 URL | [https://casedoc.com/wp-content/uploads/2021/07/Casedoc_Priv...](https://casedoc.com/wp-content/uploads/2021/07/Casedoc_Privacy_Policy_2021.pdf) |
| 使用条款 URL | [https://casedoc.com/wp-content/uploads/2020/10/Casedoc_Cust...](https://casedoc.com/wp-content/uploads/2020/10/Casedoc_Customer_Agreement.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

Casedoc 提供了此信息，这些信息与此应用程序如何收集和存储组织数据以及您的组织将拥有对应用收集的数据的控制有关。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph](https://docs.microsoft.com/graph/permissions-reference)所需的任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| AppCatalog.ReadWrite.All | delegated | 要添加到会议选项卡的查找应用程序 | 不存储任何数据 | [3e701664-cc46-49e4-b356-1a7ac6500998](https://docs.microsoft.com/microsoft-365-app-certification/azure/3e701664-cc46-49e4-b356-1a7ac6500998) |
>| Calendars.ReadWrite | 应用程序 | 查找列表用户日历事件，用于在应用中显示会议列表和数据。 | 不存储任何数据 | [3e701664-cc46-49e4-b356-1a7ac6500998](https://docs.microsoft.com/microsoft-365-app-certification/azure/3e701664-cc46-49e4-b356-1a7ac6500998) |
>| Directory.ReadWrite.All | 应用程序 | 未收集数据 | 不存储任何数据 | [3e701664-cc46-49e4-b356-1a7ac6500998](https://docs.microsoft.com/microsoft-365-app-certification/azure/3e701664-cc46-49e4-b356-1a7ac6500998) |
>| Files.ReadWrite.All | 应用程序 | 列出应用上传的文件 | 不存储任何数据 | [3e701664-cc46-49e4-b356-1a7ac6500998](https://docs.microsoft.com/microsoft-365-app-certification/azure/3e701664-cc46-49e4-b356-1a7ac6500998) |
>| Group.ReadWrite.All | 应用程序 | 未收集数据 | 不存储任何数据 | [3e701664-cc46-49e4-b356-1a7ac6500998](https://docs.microsoft.com/microsoft-365-app-certification/azure/3e701664-cc46-49e4-b356-1a7ac6500998) |
>| MailboxSettings.Read | 应用程序 | 用户邮件设置，时区。 用于显示用户的正确时区 | 不存储任何数据 | [3e701664-cc46-49e4-b356-1a7ac6500998](https://docs.microsoft.com/microsoft-365-app-certification/azure/3e701664-cc46-49e4-b356-1a7ac6500998) |
>| OnlineMeetings.ReadWrite | delegated | 读取和存储会议数据，用于在应用中显示会议数据 | 不存储任何数据 | [3e701664-cc46-49e4-b356-1a7ac6500998](https://docs.microsoft.com/microsoft-365-app-certification/azure/3e701664-cc46-49e4-b356-1a7ac6500998) |
>| TeamsAppInstallation.ReadForUser | delegated | 为用户安装的列表应用，用于将应用添加到会议选项卡。 | 不存储任何数据 | [3e701664-cc46-49e4-b356-1a7ac6500998](https://docs.microsoft.com/microsoft-365-app-certification/azure/3e701664-cc46-49e4-b356-1a7ac6500998) |
>| TeamsAppInstallation.ReadWriteForUser | delegated | 用于将应用添加到会议选项卡。 | 不存储任何数据 | [3e701664-cc46-49e4-b356-1a7ac6500998](https://docs.microsoft.com/microsoft-365-app-certification/azure/3e701664-cc46-49e4-b356-1a7ac6500998) |
>| TeamsTab.Create | delegated | 用于向会议添加选项卡。 | 不存储任何数据 | [3e701664-cc46-49e4-b356-1a7ac6500998](https://docs.microsoft.com/microsoft-365-app-certification/azure/3e701664-cc46-49e4-b356-1a7ac6500998) |
>| TeamsTab.ReadWrite.All | delegated | 用于向会议添加选项卡。 | 不存储任何数据 | [3e701664-cc46-49e4-b356-1a7ac6500998](https://docs.microsoft.com/microsoft-365-app-certification/azure/3e701664-cc46-49e4-b356-1a7ac6500998) |
>| User.Read.All | 应用程序 | 用于查找会议用户。 | 不存储任何数据 | [3e701664-cc46-49e4-b356-1a7ac6500998](https://docs.microsoft.com/microsoft-365-app-certification/azure/3e701664-cc46-49e4-b356-1a7ac6500998) |


#### <a name="non-microsoft-services-used"></a>非Microsoft 服务已使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>不Microsoft 服务非活动。

#### <a name="data-access-via-bots"></a>通过机器人访问数据

如果此应用程序包含机器人或消息扩展，则它可以访问最终用户可识别信息 (EUII) ：名单 (名字、姓氏、显示名称、电子邮件地址) （团队中任何团队成员的姓名、姓氏、电子邮件地址) 或添加到其中聊天）。 此应用是否使用了此功能？

>无法访问 EUII。


#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或最终用户可识别信息 (EUII) 是否出现在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>审核日志，根据 ISMS 策略保留 ISO 27001

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>不适用

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>标识信息

Casedoc 提供了此信息，这些信息与此应用程序如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件有关。

| **Information** | **响应** |
|:----------------|:-------------|
| 是否与 Microsoft 标识平台 (Azure AD) ？  | 是 |
| 您是否已查看并遵循了 Microsoft 标识平台 清单中列出的所有适用最佳做法？  | 是 |
| 你的应用是否使用 MSAL (Microsoft 身份验证库) 进行身份验证？ | 是 |
| 你的应用是否支持条件访问策略？ | 否 |
| 应用是否请求方案最小特权权限？ | 是 |
| 应用的静态注册权限是否准确反映应用将动态和增量请求的权限？ | 是 |
| 你的应用是否支持多租户？ | 是 |
| 你的应用是否具有机密客户端？ | 是 |
| 你是否拥有为应用注册的所有 (统一) URI？ | 是 |
| 对于你的应用，应避免使用什么？ | - 通配符重定向 URI，<br/><br/> |
| 你的应用是否公开任何 Web API？ | 是 |
| 您的权限模型是否仅在客户端应用程序收到正确同意时才允许呼叫成功？ | 否 |
| 你的应用是否使用预览 API？ | 是 |
| 你的应用是否使用已弃用 API？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
