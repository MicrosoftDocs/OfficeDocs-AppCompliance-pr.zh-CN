---
title: File Fabric 的应用程序信息存储变得简单
ms.author: elmalova
author: elenamalova
ms.date: 06/30/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: File Fabric 的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 3070723eecc0e7dda11aff31da6b20a785f558b5
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 09/12/2021
ms.locfileid: "59278796"
---
# <a name="file-fabric"></a>File Fabric

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2021 年 6 月 30 日</p>

* <a href="https://teams.microsoft.com/l/app/bd063a87-1e4d-42cf-baea-8cab71839e35" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003017" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

由 Microsoft 存储轻松使用的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | File Fabric |
| ID | WA200003017 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | 存储变得简单 |
| 合作伙伴网站的 URL | [https://storagemadeeasy.com](https://storagemadeeasy.com) |
| 应用程序Teams页的 URL | [https://docs.storagemadeeasy.com/microsoft-teams](https://docs.storagemadeeasy.com/microsoft-teams) |
| 隐私策略的 URL | [https://www.storagemadeeasy.com/privacy](https://www.storagemadeeasy.com/privacy) |
| 使用条款 URL | [https://www.storagemadeeasy.com/terms](https://www.storagemadeeasy.com/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

此信息由"轻松存储此应用如何收集和存储组织数据以及组织将拥有对应用收集的数据的控制的"轻松"提供。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph所需的](https://docs.microsoft.com/graph/permissions-reference)任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD 应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Files.ReadWrite | 应用程序 | 当用户通过应用下载、上载或编辑指定文件时读取或写入的文件数据。 | 未存储文件数据。 | [0752d800-857f-49bd-87eb-e60985516c67](https://docs.microsoft.com/microsoft-365-app-certification/azure/0752d800-857f-49bd-87eb-e60985516c67) |
>| Sites.ReadWrite.All | 应用程序 | 为每个用户收集的元数据&#8217;跨所有文件服务提供联合视图的文件和文件夹。 | 缓存元数据以提供更快的浏览和搜索速度。 | [0752d800-857f-49bd-87eb-e60985516c67](https://docs.microsoft.com/microsoft-365-app-certification/azure/0752d800-857f-49bd-87eb-e60985516c67) |

#### <a name="data-access-using-other-microsoft-apis"></a>使用其他 Microsoft API 进行数据访问

基于组织构建的应用和Microsoft 365可以使用除 Microsoft Graph 外的其他 Microsoft API 来收集或处理 OII (组织) 。 列出此应用使用的任何 Microsoft GRAPH Microsoft API。

>| **API** |  **是否收集 OII？** |  **收集哪些 OII？** | **收集 OII 的理由？** | **是否存储 OII？** | **存储 OII 的理由** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| Azure Blob 存储 | 是 | 对象元数据和数据 | 为每个用户收集的元数据&#8217;跨所有文件服务提供联合视图的文件和文件夹。 当用户通过应用下载、上载或编辑指定对象时读取或写入的对象。 | 存储对象元数据 | 缓存元数据以提供更快的浏览和搜索速度。 |
>| Office 网页版 | 否 |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>非Microsoft 服务使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>| **所有非Microsoft 服务 OII 将转移到** |  **转移了哪些 OII？** | **转移 OII 的理由？** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| 用户可以进行身份验证并连接到他们控制的任何存储服务。 | 文件和对象元数据缓存用于联合浏览和搜索。 读取和更新特定文件或对象时，将传输数据。 | 元数据将联合视图提供到存储中。 数据传输允许安全的通用访问。 |

#### <a name="data-access-via-bots"></a>通过机器人访问数据

如果此应用包含机器人或消息扩展，它可以访问最终用户可识别信息 (EUII) ：名单 (名字、姓氏、显示名称、电子邮件地址) （团队中任何团队成员的姓名、姓氏、电子邮件地址) 或添加到其中聊天）。 此应用是否使用了此功能？

>无法访问 EUII。


#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或最终用户可识别信息 (EUII) 是否出现在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>应用程序遥测或日志中不显示 OII 或 EUII。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>根据 GDPR 的数据处理协议

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

此信息由用户存储此应用如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件。

| **Information** | **响应** |
|:----------------|:-------------|
| 你是否与 Microsoft 标识平台 (Azure AD) ？  | 是 |
| 您是否已审阅并遵循了 Microsoft 标识平台 集成清单中列出的所有适用最佳做法？  | 是 |
| 你的应用是否使用 MSAL (Microsoft 身份验证库) 进行身份验证？ | 否 |
| 你的应用是否支持条件访问策略？ | 否 |
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
