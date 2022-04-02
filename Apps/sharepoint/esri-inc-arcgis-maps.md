---
title: 由 地图， Inc. 创建的 Arc适用于 Arc适用于 ARCSI 的应用程序信息。
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 07/21/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Arc CSA 应用程序的所有可用安全性和合规性地图、其数据处理策略、Microsoft Cloud App Security 应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 9696ad3964cc45583a04981bb4580320d5aefa59
ms.sourcegitcommit: b7ef94cf5fb12f6730a8688834ceee4f8fe8e0da
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 03/25/2022
ms.locfileid: "64463605"
---
# <a name="arcgis-maps"></a>ArcGIS 地图

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2021 年 7 月 21 日</p>

* <a href="https://appsource.microsoft.com/product/office/WA200003118" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

由 Microsoft 提供的由 Microsoft 提供的以下信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | ArcGIS 地图 |
| ID | WA200003118 |
| Office 365客户端 | SharePoint 2016 或更高版本 |
| 合作伙伴公司名称 | 如果为Insi，则使用 |
| 合作伙伴网站的 URL | [https://www.esri.com](https://www.esri.com) |
| 隐私策略的 URL | [https://www.esri.com/legal/privacy-arcgis](https://www.esri.com/legal/privacy-arcgis) |
| 使用条款 URL | [https://www.esri.com/en-us/legal/terms/master-agreement-pro...](https://www.esri.com/en-us/legal/terms/master-agreement-product) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

此信息由以下公司提供：此应用程序如何收集和存储组织数据，以及您的组织将拥有对应用收集的数据的控制。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph所需的](/graph/permissions-reference)任何 Microsoft 权限。

>此应用程序不使用 Microsoft Graph。


#### <a name="non-microsoft-services-used"></a>非Microsoft 服务已使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>不Microsoft 服务非活动。



#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或 EUII (最终用户可识别) 是否显示在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>应用程序遥测或日志中不显示 OII 或 EUII。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>客户管理员可以控制其用户对组织或项目级别的数据的访问。 在读取或写入数据之前，将针对访问控制列表检查请求。 在最终用户和外部服务之间传输的数据使用 HTTPS (TLS 1.2 仅) 。

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

下面将显示[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/27233' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/27233" target="_blank">在新建选项卡中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>标识信息

此信息由 Windows 公司提供，与此应用程序如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件有关。

| **Information** | **响应** |
|:----------------|:-------------|
| 是否与 Microsoft 标识平台 (Azure AD) ？  | 是 |
| 您是否已审阅并遵循了 Microsoft 标识平台 集成清单中列出的所有适用最佳做法？  | 是 |
| 你的应用是否使用 MSAL (Microsoft 身份验证库) 进行身份验证？ | 否 |
| 你的应用是否支持条件访问策略？ | 是 |
| 列出支持的策略类型 | Arc功能联机依赖于基于角色的访问控制 (RBAC) 模型。 解决方案中的所有用户都需要具有被授予其访问权限的角色。 |
| 应用是否请求方案最小特权权限？ | 是 |
| 应用的静态注册权限是否准确反映应用将动态和增量请求的权限？ | 否 |
| 你的应用是否支持多租户？ | 是 |
| 你的应用是否具有机密客户端？ | 是 |
| 你是否拥有为应用注册的所有 (统一) URI？ | 是 |
| 你的应用是否公开任何 Web API？ | 是 |
| 您的权限模型是否仅在客户端应用程序收到正确同意时才允许呼叫成功？ | 是 |
| 你的应用是否使用预览 API？ | 否 |
| 你的应用是否使用已弃用 API？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
