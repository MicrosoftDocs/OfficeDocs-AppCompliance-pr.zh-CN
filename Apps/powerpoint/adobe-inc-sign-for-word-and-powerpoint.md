---
title: Adobe Sign for Word 的应用程序信息PowerPoint Adobe Inc.
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
description: Adobe Sign for Word 和 PowerPoint 的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security 应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: ff7f1fa854f53fae54febb8e3dd3a90bdab138af
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/30/2021
ms.locfileid: "52093108"
---
# <a name="adobe-sign-for-word-and-powerpoint"></a>Adobe Sign for Word and PowerPoint

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>开发人员上次更新时间：2019 年 12 月 16 日</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381155" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

Adobe Inc. 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | Adobe Sign for Word and PowerPoint |
| ID | WA104381155 |
| Office 365支持的客户端 | Word 2016 Mac、PowerPoint 2013 Service Pack 1 或更高版本（位于 Windows、Windows、Word web 版、PowerPoint web 版、PowerPoint 2016 或更高版本上的 Word 2013 Service Pack 1 或更高版本） |
| 合作伙伴公司名称 | Adobe Inc. |
| 合作伙伴网站的 URL | [https://www.adobe.com/](https://www.adobe.com/) |
| 隐私策略的 URL | [https://www.adobe.com/privacy/policies-business/esign.html](https://www.adobe.com/privacy/policies-business/esign.html) |
| 使用条款 URL | [https://support.office.com/client/61994a3b-2c87-41c4-a88d-a...](https://support.office.com/client/61994a3b-2c87-41c4-a88d-a6455efa362d?omkt=en) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

此信息由 Adobe Inc. 提供，用于了解此应用如何收集和存储组织数据，以及组织将拥有对应用收集的数据的控制。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph所需的](https://docs.microsoft.com/graph/permissions-reference)任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD 应用 ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Mail.ReadWrite | 应用程序 | 我们需要电子邮件数据，以提取每个交易的 Adobe 签名历史记录和审核跟踪报告。 https://helpx.adobe.com/sign/using/audit-reports-transaction-history.html | 填充附加的文档、发件人和收件人电子邮件以及电子邮件中的邮件内容到 Adobe sign 以发送进行签名。 这是为了节省用户在 Adobe Sign 中重新键入这些字段的时间。 签署协议后，我们将自动撰写一封新电子邮件，让用户发送电子邮件，通知其收件人交易已完成。 |  |
>| People.Read | delegated |  | 若要在"发送供签名"体验中自动填充电子邮件地址，请键入一些初始字母，无需用户 &quot; &quot; 键入整个电子邮件。 |  |
>| User.Read | delegated |  | 要读取用户配置文件并基本上匹配其 (，他们的电子邮件) 我们的数据库，以便他们可以使用 Adobe Sign。 |  |
>| offline_access | delegated |  | 在当前令牌过期时刷新访问令牌。 例如，当用户在签名发送窗口中将其保持非活动状态的时间太长时，我们需要在用户处于活动状态时 &quot; &quot; 刷新新令牌。 |  |
>| openid | delegated | 电子邮件是 Adobe Sign 中用户的唯一标识符。 我们存储电子邮件 ID，以便可以将该用户的所有活动映射到其 Adobe Sign 记录。  | 登录以确保用户同意使用 Adobe Sign 应用的权限。 |  |


#### <a name="non-microsoft-services-used"></a>非Microsoft 服务使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>不Microsoft 服务非活动。



#### <a name="add-in-data-access"></a>加载项数据访问

列出此应用程序访问组织数据所需的权限、此权限的理由和用途 (应用程序对 ) 使用此信息的目的，以及应用程序是否在其数据库中存储此信息。

>| **权限**  | **说明** |
>|:----------------|:----------------|
>| 读写文档 | 可以读取和更改文档 |
>| 发送数据 | 可以通过 Internet 发送数据 |

#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或 EUII (最终用户可识别) 是否显示在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>无。 我们不会在遥测或日志中记录任何 EUII 或 OII。 此过程是您自己的安全审查，用于验证我们是否未执行此操作。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>在我们的系统中，对于应用程序，我们没有任何客户管理员Microsoft Teams交互。

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

下面将显示[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/11641' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/11641" target="_blank">在新建选项卡中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

