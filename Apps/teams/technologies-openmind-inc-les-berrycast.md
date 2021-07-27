---
title: 由 Technologies Openmind Inc， Les 的 Berrycast 的应用程序信息
ms.author: elmalova
author: elenamalova
ms.date: 07/23/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Berrycast 的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 714db08e839b60403a567b2cab1af888c4cb7b6f
ms.sourcegitcommit: c545fba57f8ca821caf6ef55f5b4b068b5f35984
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 07/24/2021
ms.locfileid: "53578228"
---
# <a name="berrycast"></a>Berrycast

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2021 年 7 月 23 日</p>

* <a href="https://teams.microsoft.com/l/app/c7cde650-1e32-11eb-af14-639b3a7d6491" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002798" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

由 Technologies Openmind Inc， Les 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | Berrycast |
| ID | WA200002798 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | Technologies Openmind Inc, Les |
| 合作伙伴网站的 URL | [https://www.berrycast.com](https://www.berrycast.com) |
| 隐私策略的 URL | [https://www.berrycast.com/privacy-policy](https://www.berrycast.com/privacy-policy) |
| 使用条款 URL | [https://www.berrycast.com/terms-of-use](https://www.berrycast.com/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

此信息由 Technologies Openmind Inc， Les 提供有关此应用程序如何收集和存储组织数据以及您的组织将拥有对应用收集的数据的控制的信息。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph所需的](https://docs.microsoft.com/graph/permissions-reference)任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD 应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| People.Read | delegated | 获取所有用户联系人 | 存储联系人电子邮件、用户姓名、姓氏和图片，以便快速共享记录 | [094f3986-3951-4f0c-88fa-514d117c8dd0](https://docs.microsoft.com/microsoft-365-app-certification/azure/094f3986-3951-4f0c-88fa-514d117c8dd0) |
>| User.Read | delegated | 使用名字和姓氏 (基本信息标识用户)  | 显示名字。 应用程序中的 lastname 和 picture | [094f3986-3951-4f0c-88fa-514d117c8dd0](https://docs.microsoft.com/microsoft-365-app-certification/azure/094f3986-3951-4f0c-88fa-514d117c8dd0) |
>| email | delegated | 标识用户 | 标识用户进行日志记录并发送通知 | [094f3986-3951-4f0c-88fa-514d117c8dd0](https://docs.microsoft.com/microsoft-365-app-certification/azure/094f3986-3951-4f0c-88fa-514d117c8dd0) |
>| offline_access | delegated | 保留对已授予其访问权限的数据的访问权限 | 不适用 | [094f3986-3951-4f0c-88fa-514d117c8dd0](https://docs.microsoft.com/microsoft-365-app-certification/azure/094f3986-3951-4f0c-88fa-514d117c8dd0) |
>| openid | delegated | 标识用户 | 标识用户进行日志记录 | [094f3986-3951-4f0c-88fa-514d117c8dd0](https://docs.microsoft.com/microsoft-365-app-certification/azure/094f3986-3951-4f0c-88fa-514d117c8dd0) |


#### <a name="non-microsoft-services-used"></a>非Microsoft 服务使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>| **所有非Microsoft 服务 OII 将转移到** |  **转移了哪些 OII？** | **转移 OII 的理由？** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| 条带、Intercom、MixPanel、时幅 | email， user unique identification， firstname， lastname  | 处理安全付款、执行市场营销活动、提供高效的客户服务并跟踪用户分析以改进产品 |

#### <a name="data-access-via-bots"></a>通过机器人访问数据

如果此应用程序包含机器人或消息扩展，则它可以访问最终用户可识别信息 (EUII) ：名单 (名字、姓氏、显示名称、电子邮件地址) （团队中任何团队成员的姓名、姓氏、电子邮件地址) 或添加到其中聊天）。 此应用是否使用了此功能？

>无法访问 EUII。


#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或 EUII (最终用户可识别) 是否显示在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>如果用户删除其帐户，则电子邮件、名字、姓氏以及我们删除所有数据 

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>如果用户删除其帐户，我们会删除与该用户相关的所有数据。

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>是

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

下面将显示[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/38163' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/38163" target="_blank">在新建选项卡中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>标识信息

此信息由 Technologies Openmind Inc、 Les 提供有关此应用程序如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件的信息。

| **Information** | **响应** |
|:----------------|:-------------|
| 你是否与 Microsoft 标识平台 (Azure AD) ？  | 是 |
| 您是否已查看并遵循了 Microsoft 标识平台 清单中列出的所有适用最佳做法？  | 是 |
| 你的应用是否使用 MSAL (Microsoft 身份验证库) 进行身份验证？ | 否 |
| 你的应用是否支持条件访问策略？ | 否 |
| 应用是否请求方案最小特权权限？ | 是 |
| 应用的静态注册权限是否准确反映应用将动态和增量请求的权限？ | 是 |
| 你的应用是否支持多租户？ | 否 |
| 你的应用是否具有机密客户端？ | 否 |
| 你是否拥有为应用注册的所有重定向统 (URI) URI？ | 是 |
| 你的应用是否公开任何 Web API？ | 是 |
| 您的权限模型是否仅在客户端应用程序收到正确同意时允许呼叫成功？ | 否 |
| 你的应用是否使用预览 API？ | 否 |
| 你的应用是否使用已弃用 API？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
