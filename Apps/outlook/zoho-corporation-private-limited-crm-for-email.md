---
title: Zoho Corporation Private Limited 的电子邮件 Zoho CRM 的应用程序信息
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: 适用于电子邮件的 Zoho CRM 的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security 应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 730750ad7dddfcccaa9f940e88e34793d4e35869
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 05/06/2021
ms.locfileid: "52252892"
---
# <a name="zoho-crm-for-email"></a>用于电子邮件的 Zoho CRM

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2019 年 12 月 16 日</p>

* <a href="https://appsource.microsoft.com/product/office/WA104379468" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

Zoho Corporation Private Limited 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | 用于电子邮件的 Zoho CRM |
| ID | WA104379468 |
| Office 365支持的客户端 | Outlook 2013 或更高版本Windows Mac Outlook 2016或更高版本，Outlook Web 上 |
| 合作伙伴公司名称 | Zoho Corporation Private Limited |
| 合作伙伴网站的 URL | [https://www.zoho.com/](https://www.zoho.com/) |
| 隐私策略的 URL | [https://www.zoho.com/privacy.html](https://www.zoho.com/privacy.html) |
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
>| Calendars.ReadWrite | delegated | 存储日历文件夹 ID 以将联系人从 Zoho CRM 同步 &amp; 到 Microsoft，反之亦然。 存储日历event_name、event_location、participant_details等日历信息。 | 允许用户将 Office365 事件与 Zoho CRM 同步。 | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Contacts.ReadWrite | delegated | 存储联系人文件夹 ID 以将联系人从 Zoho CRM 同步 &amp; 到 Microsoft，反之亦然。 存储联系人first_name、last_name、电子邮件地址等。 | 允许用户将 Office365 联系人与 Zoho CRM 同步。 | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Files.Read | delegated |  | 允许用户将 Office365 文件导入 Zoho CRM。 | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Files.Read.All | delegated |  | 允许用户将 Office365 文件导入 Zoho CRM。 | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Files.Read.Selected | delegated | UserPrincipalName 存储用于用户标识 | 允许用户将 Office365 文件导入 Zoho CRM。 | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| User.ReadBasic.All | delegated | 用户属性，first_name、last_name电子邮件地址。 | 读取所有用户的基本个人资料 | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| email | delegated | 存储 UserPrincipaName 以用于用户缩进 | 查看用户的电子邮件地址 | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| offline_access | delegated |  | 保留对已授予其访问权限的数据的访问权限 | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| 个人资料 | delegated |  | 查看用户的基本个人资料 | f6d7187a-b437-4eca-bbc5-c1331609fe07 |


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

>我们不会在遥测和日志中收集 EUII/PII。 我们具有脚本，以查找并发出警报，以修复任何可见的此类数据

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>客户可以选择需要通过 EAR 加密加密的数据 (静态加密) 证书限制。默认情况下，密码将进行哈希处理。 通过隔离的专用网络提供对服务器的逻辑访问 &amp; ，并且高度安全且


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

下面将显示[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/22307' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/22307" target="_blank">在新建选项卡中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

