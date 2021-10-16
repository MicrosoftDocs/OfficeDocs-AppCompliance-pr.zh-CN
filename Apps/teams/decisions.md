---
title: 决策的应用程序信息
ms.author: elmalova
author: elenamalova
ms.date: 08/18/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: 有关决策的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 99e01d0ad5874c62f51a3f78b5b612766f397ea1
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 10/16/2021
ms.locfileid: "60415139"
---
# <a name="decisions"></a>决策

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2021 年 6 月 2 日</p>

* <a href="https://teams.microsoft.com/l/app/d3d1be68-066c-4967-a74b-9edcf902dcfb" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381880" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

决策提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | 决策 |
| ID | WA104381880 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | 决策 |
| 合作伙伴网站的 URL | [https://www.meetingdecisions.com](https://www.meetingdecisions.com) |
| "Teams应用程序信息"页的 URL | [https://www.meetingdecisions.com](https://www.meetingdecisions.com) |
| 隐私策略的 URL | [https://www.meetingdecisions.com/privacy](https://www.meetingdecisions.com/privacy) |
| 使用条款 URL | [https://www.meetingdecisions.com/terms-of-service](https://www.meetingdecisions.com/terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

此信息由有关此应用程序如何收集和存储组织数据以及您的组织将拥有对应用收集的数据的控制的决策提供。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph](https://docs.microsoft.com/graph/permissions-reference)所需的任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | delegated | 用于从用户日历&#8217;信息，以启用会议列表和搜索等功能。 它还为用户提供了从"决策"中删除项目时从日历中删除特定会议的选项。 | 客户数据存储在租户&#8217;客户Office 365，并且所有客户数据仅在客户设备上进行处理。 决策数据库仅维护对租户中Office 365对象的引用，而不是实际数据。 有关详细信息 https://www.meetingdecisions.com/security-and-privacy ，请参阅 。 | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Chat.ReadWrite | delegated | 用于发送投票决策，并直接将单个议程项的演讲者列表Microsoft Teams会议聊天。 | 客户数据存储在租户&#8217;客户Office 365，并且所有客户数据仅在客户设备上进行处理。 决策数据库仅维护对租户中Office 365对象的引用，而不是实际数据。 有关详细信息 https://www.meetingdecisions.com/security-and-privacy ，请参阅 。 | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Directory.Read.All | delegated | 用于收集注册时Office 365租户的基本信息，例如租户名称和验证域。 此外，还需要验证组成员身份。 | 客户数据存储在租户&#8217;客户Office 365，并且所有客户数据仅在客户设备上进行处理。 决策数据库仅维护对租户中Office 365对象的引用，而不是实际数据。 有关详细信息 https://www.meetingdecisions.com/security-and-privacy ，请参阅 。 | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Files.Read.All | delegated | 用于读取与用户共享的文件，以便将这些文件合并到 PDF 会议书籍。 | 客户数据存储在租户&#8217;客户Office 365，并且所有客户数据仅在客户设备上进行处理。 决策数据库仅维护对租户中Office 365对象的引用，而不是实际数据。 有关详细信息 https://www.meetingdecisions.com/security-and-privacy ，请参阅 。 | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Files.ReadWrite.All | delegated | 用于为用户提供对个人文件注释的支持。 批注文件将私有存储在用户&#8217;中OneDrive for Business。 | 客户数据存储在租户&#8217;客户Office 365，并且所有客户数据仅在客户设备上进行处理。 决策数据库仅维护对租户中Office 365对象的引用，而不是实际数据。 有关详细信息 https://www.meetingdecisions.com/security-and-privacy ，请参阅 。 | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Group.ReadWrite.All | delegated | 用于在会议议程、相关文件和组对话Office 365组&#8217;SharePoint网站创建文件夹结构。   注意：决策用户绝不会访问任何资源 (例如，) 他们还没有权限访问组织的 Office 365 租户中的组。 | 客户数据存储在租户&#8217;客户Office 365，并且所有客户数据仅在客户设备上进行处理。 决策数据库仅维护对租户中Office 365对象的引用，而不是实际数据。 有关详细信息 https://www.meetingdecisions.com/security-and-privacy ，请参阅 。 | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Mail.Send | delegated | 用于允许决策用户向会议参与者发送通知，例如议程更新和共同创作者会议的链接。 电子邮件发送到会议参与者或会议所有者选择的通讯组列表。 所有发送的通知和电子邮件都是由"决策"用户主动发送的。  注意：这不会授予用户通过"决策"访问其收件箱的访问权限。 | 客户数据存储在租户&#8217;客户Office 365，并且所有客户数据仅在客户设备上进行处理。 决策数据库仅维护对租户中Office 365对象的引用，而不是实际数据。 有关详细信息 https://www.meetingdecisions.com/security-and-privacy ，请参阅 。 | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| MailboxSettings.Read | delegated | 用于标识用户&#8217;首选项。 | 客户数据存储在租户&#8217;客户Office 365，并且所有客户数据仅在客户设备上进行处理。 决策数据库仅维护对租户中Office 365对象的引用，而不是实际数据。 有关详细信息 https://www.meetingdecisions.com/security-and-privacy ，请参阅 。 | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Notes.ReadWrite | delegated | 用于为会议设置专用笔记本以记录笔记并准备备注和问题。 它还允许组会议分钟数存储在其共享OneNote笔记本中（如果组选择使用OneNote）。 | 客户数据存储在租户&#8217;客户Office 365，并且所有客户数据仅在客户设备上进行处理。 决策数据库仅维护对租户中Office 365对象的引用，而不是实际数据。 有关详细信息 https://www.meetingdecisions.com/security-and-privacy ，请参阅 。 | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Sites.ReadWrite.All | delegated | 用于为会议信息在私人频道创建文件夹结构。 | 客户数据存储在租户&#8217;客户Office 365，并且所有客户数据仅在客户设备上进行处理。 决策数据库仅维护对租户中Office 365对象的引用，而不是实际数据。 有关详细信息 https://www.meetingdecisions.com/security-and-privacy ，请参阅 。 | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Tasks.ReadWrite | delegated | 用于将任务和决策同步到 Microsoft Planner。 它还允许用户将任务和决策导出到Excel。 | 客户数据存储在租户&#8217;客户Office 365，并且所有客户数据仅在客户设备上进行处理。 决策数据库仅维护对租户中Office 365对象的引用，而不是实际数据。 有关详细信息 https://www.meetingdecisions.com/security-and-privacy ，请参阅 。 | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| TeamsAppInstallation.ReadWriteForUser | delegated | 需要以编程方式在聊天中安装"决策"应用。 为会议体验添加"决策"选项卡之前，需要执行这一操作。 | 客户数据存储在租户&#8217;客户Office 365，并且所有客户数据仅在客户设备上进行处理。 决策数据库仅维护对租户中Office 365对象的引用，而不是实际数据。 有关详细信息 https://www.meetingdecisions.com/security-and-privacy ，请参阅 。 | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| TeamsAppInstallation.ReadWriteForUser.All | delegated | 需要以编程方式在聊天中安装"决策"应用。 为会议体验添加"决策"选项卡之前，需要执行这一操作。 | 客户数据存储在租户&#8217;客户Office 365，并且所有客户数据仅在客户设备上进行处理。 决策数据库仅维护对租户中Office 365对象的引用，而不是实际数据。 有关详细信息 https://www.meetingdecisions.com/security-and-privacy ，请参阅 。 | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| TeamsTab.Create | delegated | 需要在会议中添加"会议/频道"选项卡Teams。 | 客户数据存储在租户&#8217;客户Office 365，并且所有客户数据仅在客户设备上进行处理。 决策数据库仅维护对租户中Office 365对象的引用，而不是实际数据。 有关详细信息 https://www.meetingdecisions.com/security-and-privacy ，请参阅 。 | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| TeamsTab.Read.All | delegated | 检查选项卡是否安装是必需的。 | 客户数据存储在租户&#8217;客户Office 365，并且所有客户数据仅在客户设备上进行处理。 决策数据库仅维护对租户中Office 365对象的引用，而不是实际数据。 有关详细信息 https://www.meetingdecisions.com/security-and-privacy ，请参阅 。 | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| User.ReadBasic.All | delegated | 用于显示组的成员和外部参与者的名字和姓氏、照片和电子邮件地址。 | 客户数据存储在租户&#8217;客户Office 365，并且所有客户数据仅在客户设备上进行处理。 决策数据库仅维护对租户中Office 365对象的引用，而不是实际数据。 有关详细信息 https://www.meetingdecisions.com/security-and-privacy ，请参阅 。 | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| 个人资料 | delegated | 用于登录。 | 客户数据存储在租户&#8217;客户Office 365，并且所有客户数据仅在客户设备上进行处理。 决策数据库仅维护对租户中Office 365对象的引用，而不是实际数据。 有关详细信息 https://www.meetingdecisions.com/security-and-privacy ，请参阅 。 | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |


#### <a name="non-microsoft-services-used"></a>非Microsoft 服务已使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>不Microsoft 服务非活动。

#### <a name="data-access-via-bots"></a>通过机器人访问数据

如果此应用程序包含机器人或消息扩展，则它可以访问最终用户可识别信息 (EUII) ：名单 (名字、姓氏、显示名称、电子邮件地址) （团队中任何团队成员的姓名、姓氏、电子邮件地址) 或添加到其中聊天）。 此应用是否使用了此功能？

>无法访问 EUII。


#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或 EUII (最终用户可识别) 是否显示在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>应用程序遥测或日志中不显示 OII 或 EUII。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>客户在使用软件时提供的数据仅提供给客户。  该服务在云服务和Microsoft Office 365上Microsoft Azure。 所有客户数据存储在租户Microsoft Office 365中。 在服务上存储或处理的所有数据都是匿名数据，个人不可跟踪。 因此，决策不会代表客户存储、收集或处理个人数据。

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>标识信息

此信息由有关此应用程序如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件的决策提供。

| **Information** | **响应** |
|:----------------|:-------------|
| 是否与 Microsoft 标识平台 (Azure AD) ？  | 是 |
| 您是否已审阅并遵循了 Microsoft 标识平台 集成清单中列出的所有适用最佳做法？  | 是 |
| 你的应用是否使用 MSAL (Microsoft 身份验证库) 进行身份验证？ | 是 |
| 你的应用是否支持条件访问策略？ | 是 |
| 列出支持的策略类型 | 全部 |
| 应用是否请求方案最小特权权限？ | 是 |
| 应用的静态注册权限是否准确反映应用将动态和增量请求的权限？ | 是 |
| 你的应用是否支持多租户？ | 是 |
| 你的应用是否具有机密客户端？ | 是 |
| 你是否拥有为应用注册的所有 (统一) URI？ | 是 |
| 对于你的应用，应避免使用什么？ | - 通配符重定向 URI，<br/>- OAuth2 隐式Flow，除非 SPA 需要<br/>- 资源所有者密码凭据 (ROPC) 流 |
| 你的应用是否公开任何 Web API？ | 是 |
| 您的权限模型是否仅在客户端应用程序收到正确同意时才允许呼叫成功？ | 是 |
| 你的应用是否使用预览 API？ | 否 |
| 你的应用是否使用已弃用 API？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

