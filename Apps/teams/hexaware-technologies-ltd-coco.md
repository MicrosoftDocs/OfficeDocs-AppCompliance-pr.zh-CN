---
title: Hexaware Technologies Ltd. 针对 COCO 的应用程序信息。
ms.author: elmalova
author: elenamalova
ms.date: 06/23/2020
ms.topic: article
ms.service: attestation
certification_type: certified
description: COCO 的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 8a25a95b277f41f30477182c9eec0b3b25b9351e
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 09/12/2021
ms.locfileid: "59279219"
---
# <a name="coco"></a>COCO

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>开发人员上次更新时间：2020 年 6 月 23 日</p>

* <a href="https://teams.microsoft.com/l/app/c3f021f9-1fe2-44c7-972e-58f3cd0e7762" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001468" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

Hexaware Technologies Ltd. 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | COCO |
| ID | WA200001468 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | Hexaware Technologies Ltd. |
| 合作伙伴网站的 URL | [https://hexaware.com](https://hexaware.com) |
| 隐私策略的 URL | [https://hexaware.com/wp-content/uploads/2020/03/Teams_COCO-...](https://hexaware.com/wp-content/uploads/2020/03/Teams_COCO-Privacy-Policy-and-Additional-Terms_V2.1.pdf) |
| 使用条款 URL | [https://hexaware.com/wp-content/uploads/2020/03/Teams_COCO-...](https://hexaware.com/wp-content/uploads/2020/03/Teams_COCO-Privacy-Policy-and-Additional-Terms_V2.1.pdf#page=6) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

此信息由 Hexaware Technologies Ltd. 提供，用于说明此应用程序如何收集和存储组织数据，以及您的组织将拥有对应用收集的数据的控制。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph所需的](https://docs.microsoft.com/graph/permissions-reference)任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD 应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Directory.AccessAsUser.All | delegated | 无 | 以登录用户访问目录 | [82eb2bf2-969c-46da-9e89-1db59ac4fbb3](https://docs.microsoft.com/microsoft-365-app-certification/azure/82eb2bf2-969c-46da-9e89-1db59ac4fbb3) |
>| Directory.Read.All | 应用程序 | 无 | 读取目录数据 | [82eb2bf2-969c-46da-9e89-1db59ac4fbb3](https://docs.microsoft.com/microsoft-365-app-certification/azure/82eb2bf2-969c-46da-9e89-1db59ac4fbb3) |
>| Directory.ReadWrite.All | delegated | 无 | 读取和写入目录数据 | [82eb2bf2-969c-46da-9e89-1db59ac4fbb3](https://docs.microsoft.com/microsoft-365-app-certification/azure/82eb2bf2-969c-46da-9e89-1db59ac4fbb3) |
>| User.Read | delegated | 无 | 登录并读取用户个人资料 | [82eb2bf2-969c-46da-9e89-1db59ac4fbb3](https://docs.microsoft.com/microsoft-365-app-certification/azure/82eb2bf2-969c-46da-9e89-1db59ac4fbb3) |
>| User.Read.All | 应用程序 | 无 | 读取所有用户的完整个人资料 | [82eb2bf2-969c-46da-9e89-1db59ac4fbb3](https://docs.microsoft.com/microsoft-365-app-certification/azure/82eb2bf2-969c-46da-9e89-1db59ac4fbb3) |
>| User.ReadWrite.All | delegated | 无 | 读取和写入所有用户的完整个人资料 | [82eb2bf2-969c-46da-9e89-1db59ac4fbb3](https://docs.microsoft.com/microsoft-365-app-certification/azure/82eb2bf2-969c-46da-9e89-1db59ac4fbb3) |
>| openid | delegated | 无 | 让用户登录 | [82eb2bf2-969c-46da-9e89-1db59ac4fbb3](https://docs.microsoft.com/microsoft-365-app-certification/azure/82eb2bf2-969c-46da-9e89-1db59ac4fbb3) |


#### <a name="non-microsoft-services-used"></a>非Microsoft 服务使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>不Microsoft 服务非活动。

#### <a name="data-access-via-bots"></a>通过机器人访问数据

如果此应用程序包含机器人或消息扩展，则它可以访问最终用户可识别信息 (EUII) ：名单 (名字、姓氏、显示名称、电子邮件地址) （团队中任何团队成员的姓名、姓氏、电子邮件地址) 或添加到其中聊天）。 此应用是否使用了此功能？

>| **访问 EUII 的理由？**  | **EUII 是否存储在数据库 (中) ？** | **存储 EUII 的理由** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| 维护会话数据 | 姓名、电子邮件 ID |  |


#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或最终用户可识别信息 (EUII) 是否出现在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>不适用

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>https://hexaware.com/wp-content/uploads/2020/03/Teams_COCO-Privacy-Policy-and-Additional-Terms_V2.1.pdf

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>是

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

下面将显示[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35906' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35906" target="_blank">在新建选项卡中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

