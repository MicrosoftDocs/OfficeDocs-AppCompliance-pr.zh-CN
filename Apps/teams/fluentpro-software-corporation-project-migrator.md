---
title: FluentPro 软件Project迁移程序的应用程序信息
ms.author: elmalova
author: elenamalova
ms.date: 08/17/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: 有关迁移程序的所有Project合规性信息、其数据处理策略、Microsoft Cloud App Security应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: c36f0ed0642705518d18a88068cd67c54f752ede
ms.sourcegitcommit: b1e752ea527ba6049cdc4f5d12cbd5b4dbd7f5b3
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 08/27/2021
ms.locfileid: "58673085"
---
# <a name="project-migrator"></a>Project迁移程序

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2021 年 8 月 17 日</p>

* <a href="https://teams.microsoft.com/l/app/8cd35615-e306-4b3d-8e93-17520129b60a" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003160" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

FluentPro 软件公司提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | Project迁移程序 |
| ID | WA200003160 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | FluentPro 软件公司 |
| 合作伙伴网站的 URL | [https://projectmigrator.com](https://projectmigrator.com) |
| Teams信息页的 URL | [https://help.fluentpro.com/147404-project-migrator](https://help.fluentpro.com/147404-project-migrator) |
| 隐私策略的 URL | [https://projectmigrator.com/privacy-policy](https://projectmigrator.com/privacy-policy) |
| 使用条款 URL | [https://projectmigrator.com/terms-of-use](https://projectmigrator.com/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

FluentPro Software Corporation 提供了此信息，这些信息与此应用程序如何收集和存储组织数据以及您的组织将拥有对应用收集的数据的控制有关。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph所需的](https://docs.microsoft.com/graph/permissions-reference)任何 Microsoft 权限。

>| **权限**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD 应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Directory.Read.All | delegated | 读取组及其成员身份，以便迁移到其他租户。 | 不存储此权限的数据。  | [77b31e8c-65d0-484d-a72f-9404ec9dfcfa](https://docs.microsoft.com/microsoft-365-app-certification/azure/77b31e8c-65d0-484d-a72f-9404ec9dfcfa) |
>| Group.ReadWrite.All | delegated | 组名称、成员、计划和任务。 使用 Planner 数据迁移的组、计划和任务信息。 | 组名称、计划名称和任务名称。 用于迁移信息的摘要。  | [77b31e8c-65d0-484d-a72f-9404ec9dfcfa](https://docs.microsoft.com/microsoft-365-app-certification/azure/77b31e8c-65d0-484d-a72f-9404ec9dfcfa) |
>| Sites.ReadWrite.All | delegated | 迁移SharePoint MS Planner 任务附件的文档。 | 不存储此权限的数据。  | [77b31e8c-65d0-484d-a72f-9404ec9dfcfa](https://docs.microsoft.com/microsoft-365-app-certification/azure/77b31e8c-65d0-484d-a72f-9404ec9dfcfa) |
>| User.Read | delegated | 用于存储链接到帐户的 MS Planner 迁移摘要信息的 UPN。 | UPN。 | [77b31e8c-65d0-484d-a72f-9404ec9dfcfa](https://docs.microsoft.com/microsoft-365-app-certification/azure/77b31e8c-65d0-484d-a72f-9404ec9dfcfa) |
>| User.ReadBasic.All | delegated | 使用用户信息迁移 MS Planner 任务分配和组成员身份。 | 不存储此权限的数据。  | [77b31e8c-65d0-484d-a72f-9404ec9dfcfa](https://docs.microsoft.com/microsoft-365-app-certification/azure/77b31e8c-65d0-484d-a72f-9404ec9dfcfa) |
>| offline_access | delegated | 刷新和访问令牌用于访问 MS Planner 数据。 | 存储加密刷新令牌以访问 MS Planner 数据。 | [77b31e8c-65d0-484d-a72f-9404ec9dfcfa](https://docs.microsoft.com/microsoft-365-app-certification/azure/77b31e8c-65d0-484d-a72f-9404ec9dfcfa) |
>| User.Read | delegated | 名字、姓氏、公司名称、电话公司电子邮件。 此数据用于注册和身份验证过程。 | First Name， Last Name， Company Name， 电话， Corporate Email， UPN. | [c36d31a2-8de1-4eb5-9e7d-01da45244c04](https://docs.microsoft.com/microsoft-365-app-certification/azure/c36d31a2-8de1-4eb5-9e7d-01da45244c04) |


#### <a name="non-microsoft-services-used"></a>非Microsoft 服务已使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>不Microsoft 服务非活动。

#### <a name="data-access-via-bots"></a>通过机器人访问数据

如果此应用包含机器人或消息扩展，它可以访问最终用户可识别信息 (EUII) ：名单 (名字、姓氏、显示名称、电子邮件地址) （团队中任何团队成员的姓名、姓氏、电子邮件地址) 或添加到其中聊天）。 此应用是否使用了此功能？

>无法访问 EUII。


#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或 EUII (最终用户可识别) 是否显示在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>应用程序遥测或日志中不显示 OII 或 EUII。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>https://projectmigrator.com/privacy-policy

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

FluentPro Software Corporation 提供了此信息，这些信息与此应用程序如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件有关。

| **Information** | **响应** |
|:----------------|:-------------|
| 你是否与 Microsoft 标识平台 (Azure AD) ？  | 是 |
| 您是否已查看并遵循了 Microsoft 标识平台 清单中列出的所有适用最佳做法？  | 否 |
| 你的应用是否使用 MSAL (Microsoft 身份验证库) 进行身份验证？ | 是 |
| 你的应用是否支持条件访问策略？ | 否 |
| 应用是否请求方案最小特权权限？ | 是 |
| 应用的静态注册权限是否准确反映应用将动态和增量请求的权限？ | 是 |
| 你的应用是否支持多租户？ | 是 |
| 你的应用是否具有机密客户端？ | 是 |
| 你是否拥有为应用注册的所有 (统一) URI？ | 是 |
| 你的应用是否公开任何 Web API？ | 否 |
| 你的应用是否使用预览 API？ | 是 |
| 你的应用是否使用已弃用 API？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
