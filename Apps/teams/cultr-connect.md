---
title: 由来自 连接 的应用程序信息
ms.author: elmalova
author: elenamalova
ms.date: 08/19/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: 所有可用的 Security and compliance information for 连接、 its data handling policies、 its Microsoft Cloud App Security app catalog information和 security/compliance information in the CSA STAR registry.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: b27b187fe2d898f873fecbde6a45bdc908edeb1b
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 10/16/2021
ms.locfileid: "60412462"
---
# <a name="cultr-connect"></a>Cultr Connect

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2021 年 6 月 28 日</p>

* <a href="https://teams.microsoft.com/l/app/3b1655d0-505a-4b03-a01f-519a91f77625" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003008" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

由用户提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | Cultr Connect |
| ID | WA200003008 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | Cultr |
| 合作伙伴网站的 URL | [https://cultr.works](https://cultr.works) |
| 应用程序Teams页的 URL | [https://cultr.works/how-it-works/](https://cultr.works/how-it-works/) |
| 隐私策略的 URL | [https://cultr.works/privacy-policy/](https://cultr.works/privacy-policy/) |
| 使用条款 URL | [https://cultr.works/terms-of-use/](https://cultr.works/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

此信息由用户提供，关于此应用如何收集和存储组织数据，以及你的组织将拥有对应用收集的数据的控制。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph](https://docs.microsoft.com/graph/permissions-reference)所需的任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Group.Read.All | 应用程序 | 标识用户以更新用户信息和发送数据。 | 基本用户信息。 | [3b1655d0-505a-4b03-a01f-519a91f77625](https://docs.microsoft.com/microsoft-365-app-certification/azure/3b1655d0-505a-4b03-a01f-519a91f77625) |
>| GroupMember.Read.All | 应用程序 | 标识用户以更新用户信息和发送数据。 | 基本用户信息。 | [3b1655d0-505a-4b03-a01f-519a91f77625](https://docs.microsoft.com/microsoft-365-app-certification/azure/3b1655d0-505a-4b03-a01f-519a91f77625) |
>| Organization.Read.All | 应用程序 | 标识用户以更新用户信息和发送数据。 | 基本用户信息。 | [3b1655d0-505a-4b03-a01f-519a91f77625](https://docs.microsoft.com/microsoft-365-app-certification/azure/3b1655d0-505a-4b03-a01f-519a91f77625) |
>| TeamMember.Read.All | 应用程序 | 标识用户以更新用户信息和发送数据。 | 基本用户信息。 | [3b1655d0-505a-4b03-a01f-519a91f77625](https://docs.microsoft.com/microsoft-365-app-certification/azure/3b1655d0-505a-4b03-a01f-519a91f77625) |
>| User.Read | 应用程序 | 标识用户以更新用户信息和发送数据。 | 基本用户信息。 | [3b1655d0-505a-4b03-a01f-519a91f77625](https://docs.microsoft.com/microsoft-365-app-certification/azure/3b1655d0-505a-4b03-a01f-519a91f77625) |
>| User.Read.All | 应用程序 | 标识用户以更新用户信息和发送数据。 | 基本用户信息。 | [3b1655d0-505a-4b03-a01f-519a91f77625](https://docs.microsoft.com/microsoft-365-app-certification/azure/3b1655d0-505a-4b03-a01f-519a91f77625) |
>| User.ReadBasic.All | 应用程序 | 标识要发送相关数据的用户。 | 基本用户信息。 | [3b1655d0-505a-4b03-a01f-519a91f77625](https://docs.microsoft.com/microsoft-365-app-certification/azure/3b1655d0-505a-4b03-a01f-519a91f77625) |
>| openid | 应用程序 | 标识用户以更新用户信息和发送数据。 | 基本用户信息。 | [3b1655d0-505a-4b03-a01f-519a91f77625](https://docs.microsoft.com/microsoft-365-app-certification/azure/3b1655d0-505a-4b03-a01f-519a91f77625) |


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

>不能控制数据。

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>标识信息

此信息已由一些用户提供有关此应用如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件的信息。

| **Information** | **响应** |
|:----------------|:-------------|
| 是否与 Microsoft 标识平台 (Azure AD) ？  | 是 |
| 您是否已审阅并遵循了 Microsoft 标识平台 集成清单中列出的所有适用最佳做法？  | 是 |
| 你的应用是否使用 MSAL (Microsoft 身份验证库) 进行身份验证？ | 否 |
| 你的应用是否支持条件访问策略？ | 否 |
| 应用是否请求方案最小特权权限？ | 是 |
| 应用的静态注册权限是否准确反映应用将动态和增量请求的权限？ | 是 |
| 你的应用是否支持多租户？ | 是 |
| 你的应用是否具有机密客户端？ | 是 |
| 你是否拥有为应用注册的所有 (统一) URI？ | 是 |
| 对于你的应用，应避免使用什么？ | ,<br/><br/>- 资源所有者密码凭据 (ROPC) 流 |
| 你的应用是否公开任何 Web API？ | 否 |
| 你的应用是否使用预览 API？ | 否 |
| 你的应用是否使用已弃用 API？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

