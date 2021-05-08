---
title: Zoho Corporation Private Limited 针对电子邮件的 ServiceDesk Plus 的应用程序信息
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: ServiceDesk Plus for Email 的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security 应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: dbbafef5141b91c850c916c780cfb2cd89504f52
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 05/06/2021
ms.locfileid: "52252882"
---
# <a name="servicedesk-plus-for-email"></a>ServiceDesk Plus for Email

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2019 年 12 月 16 日</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381518" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

Zoho Corporation Private Limited 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | ServiceDesk Plus for Email |
| ID | WA104381518 |
| Office 365支持的客户端 | Outlook 2013 或更高版本Windows Mac Outlook 2016或更高版本，Outlook Web 上 |
| 合作伙伴公司名称 | Zoho Corporation Private Limited |
| 合作伙伴网站的 URL | [https://www.zoho.com/](https://www.zoho.com/) |
| 隐私策略的 URL | [https://www.manageengine.com/privacy.html](https://www.manageengine.com/privacy.html) |
| 使用条款 URL | [https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US](https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

此信息由 Zoho Corporation Private Limited 提供，用于了解此应用程序如何收集和存储组织数据，以及您的组织将拥有对应用收集的数据的控制。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph所需的](https://docs.microsoft.com/graph/permissions-reference)任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD 应用 ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | 应用程序 |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Files.Read | delegated |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Files.Read.Selected | delegated |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| User.Read | delegated | 用户的电子邮件 ID。 | 允许用户登录，并授予应用对 UPN 的访问权限，以启用无提示登录。 | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| User.Read.All | 应用程序 |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| User.ReadBasic.All | delegated | 电子邮件 ID、姓名、员工 ID、职务、电话、移动、网站、部门、区域设置、用户的个人资料照片。 | 允许从网站导入用户Azure Active Directory。 | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| email | delegated | 用户的电子邮件 ID。 | 查看用户的电子邮件地址。 | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| offline_access | delegated |  | 保持对已赋予其访问权限的数据的访问权限。 | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| 个人资料 | delegated |  | 查看用户的基本个人资料。 | f6d7187a-b437-4eca-bbc5-c1331609fe07 |


#### <a name="non-microsoft-services-used"></a>非Microsoft 服务使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>不Microsoft 服务非活动。



#### <a name="add-in-data-access"></a>加载项数据访问

列出此应用程序访问组织数据所需的权限、此权限的理由和用途 (应用程序对 ) 使用此信息的目的，以及应用程序是否在其数据库中存储此信息。

>| **权限**  | **说明** |
>|:----------------|:----------------|
>| 读取项目 | 此外接程序可以访问活动邮件上的个人信息，例如发件人姓名、收件人姓名、电子邮件地址、邮件正文和附件信息。 加载项可能会将此数据发送给第三方服务。 无法读取或修改&#8217;邮箱中的其他项目。 |
>| 发送数据 | 可以通过 Internet 发送数据 |

#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或 EUII (最终用户可识别) 是否显示在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>我们不会收集遥测/日志中的 EUII/PII。 我们具有查找模式和修复警报的脚本

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>所有数据在 REST 中加密。 只有授权人员才能访问系统，该系统受到保护，并针对所有类型访问进行完全审核。 用于访问的 MFA，授权帐户在公司目录和主机中维护


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

下面将显示[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/18802' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/18802" target="_blank">在新建选项卡中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

