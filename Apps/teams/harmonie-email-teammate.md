---
title: 电子邮件工作组成员的应用程序 harmon.ie
ms.author: elmalova
author: elenamalova
ms.date: 08/10/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Email TeamMate 的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 1aecf8fedde78acae86eb654f066bb443ff387ed
ms.sourcegitcommit: 7ef4a79aa28ac4dcce067b1f6f8693eeec6335e9
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 08/13/2021
ms.locfileid: "58239765"
---
# <a name="email-teammate"></a>Email TeamMate

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2021 年 8 月 10 日</p>

* <a href="https://teams.microsoft.com/l/app/3ae27f31-ceea-4d13-a212-cdc9d786eae1" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002338" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

由 Microsoft harmon.ie 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | Email TeamMate |
| ID | WA200002338 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | harmon.ie |
| 合作伙伴网站的 URL | [https://harmon.ie](https://harmon.ie) |
| Teams信息页的 URL | [https://harmon.ie](https://harmon.ie) |
| 隐私策略的 URL | [https://harmon.ie/legal/privacy-policy](https://harmon.ie/legal/privacy-policy) |
| 使用条款 URL | [https://harmon.ie/legal/teammate-eula](https://harmon.ie/legal/teammate-eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

此信息已由用户 harmon.ie，用于了解此应用如何收集和存储组织数据，以及组织将拥有对应用收集的数据的控制。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph所需的](https://docs.microsoft.com/graph/permissions-reference)任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD 应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Chat.Read | delegated | TeamMate 要求获取特定对话的聊天成员，以便与对话聊天成员共享保存在 SharePoint/One 驱动器中的文件 | 无 | [74a31d8c-1ee9-4fb8-bc22-640ba5f457f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/74a31d8c-1ee9-4fb8-bc22-640ba5f457f4) |
>| Files.ReadWrite.All | delegated | TeamMate 要求将电子邮件附件保存在 &amp; SharePoint / Teams / OneDrive | 无 | [74a31d8c-1ee9-4fb8-bc22-640ba5f457f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/74a31d8c-1ee9-4fb8-bc22-640ba5f457f4) |
>| Mail.ReadWrite | delegated | TeamMate 要求显示用户的电子邮件，以及答复保存到Teams | 无 | [74a31d8c-1ee9-4fb8-bc22-640ba5f457f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/74a31d8c-1ee9-4fb8-bc22-640ba5f457f4) |
>| People.Read | delegated | TeamMate 要求按人员搜索电子邮件，并推荐经常联系的人。 | 无 | [74a31d8c-1ee9-4fb8-bc22-640ba5f457f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/74a31d8c-1ee9-4fb8-bc22-640ba5f457f4) |
>| User.Read | delegated | 允许用户使用其帐户登录到 TeamMate，并允许 TeamMate 查看基本用户配置文件信息 | 无 | [74a31d8c-1ee9-4fb8-bc22-640ba5f457f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/74a31d8c-1ee9-4fb8-bc22-640ba5f457f4) |
>| User.ReadBasic.All | delegated | TeamMate 要求解析聊天成员电子邮件地址，以便与OneDrive共享文件  | 无 | [74a31d8c-1ee9-4fb8-bc22-640ba5f457f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/74a31d8c-1ee9-4fb8-bc22-640ba5f457f4) |


#### <a name="non-microsoft-services-used"></a>非Microsoft 服务使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>不Microsoft 服务非活动。

#### <a name="data-access-via-bots"></a>通过机器人访问数据

如果此应用程序包含机器人或消息扩展，则它可以访问最终用户可识别信息 (EUII) ：名单 (名字、姓氏、显示名称、电子邮件地址) （团队中任何团队成员的姓名、姓氏、电子邮件地址) 或添加到其中聊天）。 此应用是否使用了此功能？

>无法访问 EUII。


#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或 EUII (最终用户可识别) 是否显示在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>使用率数据和用户数量增加

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>-

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

下面将显示[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36364' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36364" target="_blank">在新建选项卡中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>标识信息

此信息已由应用 harmon.ie、授权、应用程序注册最佳做法和其他标识条件的信息提供。

| **Information** | **响应** |
|:----------------|:-------------|
| 你是否与 Microsoft 标识平台 (Azure AD) ？  | 是 |
| 您是否已查看并遵循了 Microsoft 标识平台 集成清单中列出的所有适用最佳做法？  | 是 |
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
| 你的应用是否使用预览 API？ | 是 |
| 你的应用是否使用已弃用 API？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
