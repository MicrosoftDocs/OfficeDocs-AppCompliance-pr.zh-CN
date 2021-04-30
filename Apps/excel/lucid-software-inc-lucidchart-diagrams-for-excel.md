---
title: Lucid Software Inc Excel的 Lucidchart 图表的应用程序信息
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
description: 用于 Excel 的 Lucidchart 图表的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security 应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 42bb36d92b71f3ca303fe924ea3ac260854ac03f
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/30/2021
ms.locfileid: "52092843"
---
# <a name="lucidchart-diagrams-for-excel"></a>用于图表的 Lucidchart Excel

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2019 年 12 月 16 日</p>

* <a href="https://appsource.microsoft.com/product/office/WA104380194" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

Lucid Software Inc 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | 用于图表的 Lucidchart Excel |
| ID | WA104380194 |
| Office 365支持的客户端 | Excel 2016 Mac 或更高版本，Excel 2013 或更高版本（Windows，Excel web 版 |
| 合作伙伴公司名称 | Lucid Software Inc |
| 合作伙伴网站的 URL | [https://www.lucidchart.com/](https://www.lucidchart.com/) |
| 隐私策略的 URL | [https://www.lucidchart.com/pages/privacy](https://www.lucidchart.com/pages/privacy) |
| 使用条款 URL | [https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US](https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

此信息由 Lucid Software Inc 提供有关此应用程序如何收集和存储组织数据以及您的组织将拥有对应用收集的数据的控制的信息。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph所需的](https://docs.microsoft.com/graph/permissions-reference)任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD 应用 ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| email | delegated | 姓名和电子邮件地址。 | 电子邮件、openid 和配置文件权限使 Lucidchart 可以生成用户的 openid 令牌，并获取足够的有关用户的基本信息，以便在必要时为用户注册 Lucidchart 帐户。 为了验证从 Microsoft 返回的数据，我们请求获取其响应已签名的公钥。 作为 SSO 流的一部分，不会从 Microsoft 接收或发送给 Microsoft 其他数据。 |  |
>| openid | delegated | 姓名和电子邮件地址。 | 电子邮件、openid 和配置文件权限使 Lucidchart 可以生成用户的 openid 令牌，并获取足够的有关用户的基本信息，以便在必要时为用户注册 Lucidchart 帐户。 为了验证从 Microsoft 返回的数据，我们请求获取其响应已签名的公钥。 作为 SSO 流的一部分，不会从 Microsoft 接收或发送给 Microsoft 其他数据。 |  |
>| 个人资料 | delegated | 姓名和电子邮件地址。 | 电子邮件、openid 和配置文件权限使 Lucidchart 可以生成用户的 openid 令牌，并获取足够的有关用户的基本信息，以便在必要时为用户注册 Lucidchart 帐户。 为了验证从 Microsoft 返回的数据，我们请求获取其响应已签名的公钥。 作为 SSO 流的一部分，不会从 Microsoft 接收或发送给 Microsoft 其他数据。 |  |

#### <a name="data-access-using-other-microsoft-apis"></a>使用其他 Microsoft API 进行数据访问

基于组织构建的应用和加载项Microsoft 365除 Microsoft Graph 外的其他 Microsoft API 来收集或处理 OII (组织) 。 列出除 Microsoft API Graph此应用使用的任何 Microsoft API。

>| **API** |  **是否收集 OII？** |  **收集哪些 OII？** | **收集 OII 的理由？** | **是否存储 OII？** | **存储 OII 的理由** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| 适用于 Office 的 JavaScript API | 是 | 我们使用 javascript SDK Office OneDrive，使用 OneDrive.open OneDrive打开 () 。 我们不会生成任何访问令牌，也不向自己OneDrive任何请求;OneDrive文件选择器 SDK 为我们这样做。 我们仅看到用户选择的文件名。 |  | 如果用户使用文件选择器选择OneDrive文件，我们将存储文件名。 |  |

#### <a name="non-microsoft-services-used"></a>非Microsoft 服务使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>| **所有非Microsoft 服务 OII 将转移到** |  **转移了哪些 OII？** | **转移 OII 的理由？** |
>|:-------------------|:--------------------------|:--------------------------|
>| Lucidchart 数据存储在 AWS 中。 |  | 我们不使用任何 Microsoft API。 我们使用 openID 获取基本用户数据来执行 SSO。 我们使用其文件选取器 API，但这不会授予我们访问用户文件的访问权限，只是提供通过选取器提交给我们的文件的访问权限。 |



#### <a name="add-in-data-access"></a>加载项数据访问

列出此应用程序访问组织数据所需的权限、此权限的理由和用途 (应用程序对 ) 使用此信息的目的，以及应用程序是否在其数据库中存储此信息。

>| **权限**  | **说明** |
>|:----------------|:----------------|
>| 读写文档 | 可以读取和更改文档 |
>| 发送数据 | 可以通过 Internet 发送数据 |

#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或 EUII (最终用户可识别) 是否显示在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>出于安全和支持原因，我们将记录电子邮件和 IP 地址。 第三方系统中记录日志的所有访问实际上 &amp; 不可更改。 对日志的访问需要 MFA。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>Lucidchart 数据存储在 AWS 中。 它处于其余时间且正在传输中加密。 Lucidchart 使用最小特权和 MFA 规则。

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

下面将显示[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/12761' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/12761" target="_blank">在新建选项卡中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

