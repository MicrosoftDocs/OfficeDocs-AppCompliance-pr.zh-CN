---
title: Meaplus AB 的 SEFOS 应用程序信息
ms.author: elmalova
author: elenamalova
ms.date: 09/09/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: SEFOS 的所有可用安全性和合规性信息、其数据处理策略、Microsoft Cloud App Security应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 14da720eee4a70152a3239d43154f0b47b0c56ea
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 10/16/2021
ms.locfileid: "60414548"
---
# <a name="sefos"></a>SEFOS

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2021 年 6 月 15 日</p>

* <a href="https://teams.microsoft.com/l/app/a9b13f17-540f-4b08-a48c-75051b68677e" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003219" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

Meaplus AB 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | SEFOS |
| ID | WA200003219 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | Meaplus AB |
| 合作伙伴网站的 URL | [https://www.meaplus.com](https://www.meaplus.com) |
| "Teams应用程序信息"页的 URL | [https://sefos.se/en/sefos-i-teams/](https://sefos.se/en/sefos-i-teams/) |
| 隐私策略的 URL | [https://www.meaplus.com/privacy-policy/](https://www.meaplus.com/privacy-policy/) |
| 使用条款 URL | [https://www.meaplus.com/wp-content/uploads/2020/02/Meaplus-...](https://www.meaplus.com/wp-content/uploads/2020/02/Meaplus-end_user_agreement.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

Meaplus AB 提供了此信息，这些信息与此应用程序如何收集和存储组织数据以及您的组织将拥有对应用收集的数据的控制有关。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph](https://docs.microsoft.com/graph/permissions-reference)所需的任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | delegated | 代表用户创建会议 | 无 | [23b236c3-685d-49f0-a7bf-012ef3dc9ec3](https://docs.microsoft.com/microsoft-365-app-certification/azure/23b236c3-685d-49f0-a7bf-012ef3dc9ec3) |
>| Mail.Send | delegated | 发送会议邀请 | 无 | [23b236c3-685d-49f0-a7bf-012ef3dc9ec3](https://docs.microsoft.com/microsoft-365-app-certification/azure/23b236c3-685d-49f0-a7bf-012ef3dc9ec3) |
>| MailboxSettings.Read | delegated | 收集已验证用户的时区 | 无 | [23b236c3-685d-49f0-a7bf-012ef3dc9ec3](https://docs.microsoft.com/microsoft-365-app-certification/azure/23b236c3-685d-49f0-a7bf-012ef3dc9ec3) |
>| People.Read | delegated | 在经过身份验证的用户地址簿中搜索 | 无 | [23b236c3-685d-49f0-a7bf-012ef3dc9ec3](https://docs.microsoft.com/microsoft-365-app-certification/azure/23b236c3-685d-49f0-a7bf-012ef3dc9ec3) |
>| User.Read | delegated | 登录并读取用户个人资料 | 无 | [23b236c3-685d-49f0-a7bf-012ef3dc9ec3](https://docs.microsoft.com/microsoft-365-app-certification/azure/23b236c3-685d-49f0-a7bf-012ef3dc9ec3) |
>| email | delegated | 用于标识 SEFOS 中的用户的电子邮件地址。 | 无 | [23b236c3-685d-49f0-a7bf-012ef3dc9ec3](https://docs.microsoft.com/microsoft-365-app-certification/azure/23b236c3-685d-49f0-a7bf-012ef3dc9ec3) |
>| openid | delegated | 登录用户 | 无 | [23b236c3-685d-49f0-a7bf-012ef3dc9ec3](https://docs.microsoft.com/microsoft-365-app-certification/azure/23b236c3-685d-49f0-a7bf-012ef3dc9ec3) |
>| 个人资料 | delegated | 读取用户配置文件 | 无 | [23b236c3-685d-49f0-a7bf-012ef3dc9ec3](https://docs.microsoft.com/microsoft-365-app-certification/azure/23b236c3-685d-49f0-a7bf-012ef3dc9ec3) |


#### <a name="non-microsoft-services-used"></a>非Microsoft 服务已使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>不Microsoft 服务非活动。

#### <a name="data-access-via-bots"></a>通过机器人访问数据

如果此应用程序包含机器人或消息扩展，则它可以访问最终用户可识别信息 (EUII) ：名单 (名字、姓氏、显示名称、电子邮件地址) （团队中任何团队成员的姓名、姓氏、电子邮件地址) 或添加到其中聊天）。 此应用是否使用了此功能？

>无法访问 EUII。


#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或 EUII (最终用户可识别) 是否显示在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>应用程序遥测或日志中不显示 OII 或 EUII。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>不适用，这是一个分布式系统，其中每个组织在本地安装中控制自己的信息。 . 

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>标识信息

Meaplus AB 已提供有关此应用如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件的信息。

| **Information** | **响应** |
|:----------------|:-------------|
| 是否与 Microsoft 标识平台 (Azure AD) ？  | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

