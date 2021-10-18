---
title: AVEPoint， Inc. 的 AVA 应用程序信息
ms.author: elmalova
author: elenamalova
ms.date: 11/01/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: AVA 的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: e5b53fbbc4c65c709324611a9ac645b045e4eaa7
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 10/18/2021
ms.locfileid: "60430000"
---
# <a name="ava"></a>AVA

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2020 年 3 月 23 日</p>

* <a href="https://teams.microsoft.com/l/app/93106045-6f96-41e3-8a9d-694b6bbcac60" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381883" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

AvePoint， Inc. 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | AVA |
| ID | WA104381883 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | AvePoint, Inc. |
| 合作伙伴网站的 URL | [https://www.avepoint.com/](https://www.avepoint.com/) |
| Teams信息页的 URL | [https://www.avepoint.com/support/](https://www.avepoint.com/support/) |
| 隐私策略的 URL | [https://www.avepoint.com/company/privacy-policy/](https://www.avepoint.com/company/privacy-policy/) |
| 使用条款 URL | [https://www.avepoint.com/company/terms-of-use](https://www.avepoint.com/company/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

此信息由 AvePoint， Inc. 提供，用于说明此应用程序如何收集和存储组织数据，以及您的组织将拥有对应用程序收集的数据的控制。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph所需的](https://docs.microsoft.com/graph/permissions-reference)任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Mail.ReadWrite.Shared | delegated | 无 | 搜索用户的电子邮件，将电子邮件移动到指定文件夹 | [6f30434d-3cfa-4cf8-9810-6fcf79ae750a](https://docs.microsoft.com/microsoft-365-app-certification/azure/6f30434d-3cfa-4cf8-9810-6fcf79ae750a) |
>| User.Read | delegated |  用户访问令牌 - 用于搜索和还原用户数据 | 允许用户登录并授予对应用程序的访问令牌 | [6f30434d-3cfa-4cf8-9810-6fcf79ae750a](https://docs.microsoft.com/microsoft-365-app-certification/azure/6f30434d-3cfa-4cf8-9810-6fcf79ae750a) |
>| User.ReadWrite | delegated | DisplayName、UserPrincipalName、JobTitle、Organization、Country、MySiteUrl - 记录使用该应用程序的用户的基本信息 | 获取用户的基本个人资料信息 | [6f30434d-3cfa-4cf8-9810-6fcf79ae750a](https://docs.microsoft.com/microsoft-365-app-certification/azure/6f30434d-3cfa-4cf8-9810-6fcf79ae750a) |

#### <a name="data-access-using-other-microsoft-apis"></a>使用其他 Microsoft API 进行数据访问

基于组织构建的应用和加载项Microsoft 365除 Microsoft Graph 外的其他 Microsoft API 来收集或处理 OII (组织) 。 列出除 Microsoft API Graph此应用使用的任何 Microsoft API。

>| **API** |  **是否收集 OII？** |  **收集哪些 OII？** | **收集 OII 的理由？** | **是否存储 OII？** | **存储 OII 的理由** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| SharePoint REST API | 是 | 在用户的个人网站的回收中搜索文件并还原这些文件。 需要 AllSites.Manage 权限。 |  | 无 |  |

#### <a name="non-microsoft-services-used"></a>非Microsoft 服务已使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>不Microsoft 服务非活动。

#### <a name="data-access-via-bots"></a>通过机器人访问数据

如果此应用程序包含机器人或消息扩展，则它可以访问最终用户可识别信息 (EUII) ：名单 (名字、姓氏、显示名称、电子邮件地址) （团队中任何团队成员的姓名、姓氏、电子邮件地址) 或添加到其中聊天）。 此应用是否使用了此功能？

>无法访问 EUII。


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

::: zone pivot="mcas"

下面将显示[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35842' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35842" target="_blank">在新建选项卡中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

