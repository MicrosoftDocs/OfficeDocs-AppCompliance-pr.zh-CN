---
title: inLogic-Studi.ly Store Office应用程序信息
ms.author: elmalova
author: elenamalova
ms.date: 08/24/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: 所有可用的安全与合规性信息 Studi.ly、其数据处理策略、Microsoft Cloud App Security应用程序目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: d682e758d9632a2c3ac19296dda7083dc8379689
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 07/22/2021
ms.locfileid: "53525566"
---
# <a name="studily"></a>Studi.ly

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2020 年 8 月 24 日</p>

* <a href="https://teams.microsoft.com/l/app/a1eca727-7b59-4439-b269-f4b800030518" target="_blank">在应用商店Teams视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001668" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

inLogic-Office Microsoft 提供的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | Studi.ly |
| ID | WA200001668 |
| Office 365支持的客户端 | Microsoft Teams |
| 合作伙伴公司名称 | inLogic-Office Store |
| 合作伙伴网站的 URL | [https://www.inlogic.dk](https://www.inlogic.dk) |
| 隐私策略的 URL | [https://studi.ly/Studily_Privacy_Statement.pdf](https://studi.ly/Studily_Privacy_Statement.pdf) |
| 使用条款 URL | [https://studi.ly/Studily_Terms_Of_Use_v1.pdf](https://studi.ly/Studily_Terms_Of_Use_v1.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

此信息由 inLogic-Office Store 提供有关此应用如何收集和存储组织数据以及组织将拥有对应用收集的数据的控制的信息。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph所需的](https://docs.microsoft.com/graph/permissions-reference)任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD 应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | delegated | 我们正在将课程、学校和成员以及来自教育 api 的术语信息存储在我们的 api 中，并且我们需要它，因为如果我们每次从图形 api 获取它，这会使应用程序运行缓慢。我们会根据基于时间的事件将其从教育 api 同步到我们的数据库。 |  | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| Directory.Read.All | delegated | 我们正在将课程、学校和成员以及来自教育 api 的术语信息存储在我们的 api 中，并且我们需要它，因为如果我们每次从图形 api 获取它，这会使应用程序运行缓慢。我们会根据基于时间的事件将其从教育 api 同步到我们的数据库。 | 在工作分配和材料组中写入目录。 | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| Directory.ReadWrite.All | 应用程序 | 我们正在将课程、学校和成员以及来自教育 api 的术语信息存储在我们的 api 中，并且我们需要它，因为如果我们每次从图形 api 获取它，这会使应用程序运行缓慢。我们会根据基于时间的事件将其从教育 api 同步到我们的数据库。 | 在工作分配和材料组中写入目录。 | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| EduRoster.Read.All | 应用程序 | 我们正在将课程、学校和成员以及来自教育 api 的术语信息存储在我们的 api 中，我们需要它，因为如果我们每次从图形 api 获取它，这会使应用程序运行缓慢。 我们会根据基于时间的事件将其从教育 api 同步到我们的数据库。 | 阅读教育课程、学校、成员和术语。获取租户的所有课程和学校，以同步到应用数据库。 | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| EduRoster.ReadBasic | delegated | 我们正在将课程、学校和成员以及来自教育 api 的术语信息存储在我们的 api 中，并且我们需要它，因为如果我们每次从图形 api 获取它，这会使应用程序运行缓慢。我们会根据基于时间的事件将其从教育 api 同步到我们的数据库。 | 阅读教育课程、学校、成员和术语。获取租户的所有课程和学校，以同步到应用数据库。 | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| EduRoster.ReadWrite.All | 应用程序 | 我们正在将课程、学校和成员以及来自教育 api 的术语信息存储在我们的 api 中，并且我们需要它，因为如果我们每次从图形 api 获取它，这会使应用程序运行缓慢。我们会根据基于时间的事件将其从教育 api 同步到我们的数据库。 | 阅读教育课程、学校、成员和术语。获取租户的所有课程和学校，以同步到应用数据库。 | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| Files.ReadWrite.All | delegated | 我们正在将课程、学校和成员以及来自教育 api 的术语信息存储在我们的 api 中，并且我们需要它，因为如果我们每次从图形 api 获取它，这会使应用程序运行缓慢。我们会根据基于时间的事件将其从教育 api 同步到我们的数据库。 | 从一个驱动器读取文件 | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| Group.Read.All | delegated | 我们正在将课程、学校和成员以及来自教育 api 的术语信息存储在我们的 api 中，并且我们需要它，因为如果我们每次从图形 api 获取它，这会使应用程序运行缓慢。我们会根据基于时间的事件将其从教育 api 同步到我们的数据库。 | 此权限允许应用获取租户组的不同 claender 事件。、subject、start、end、extensions | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| Group.ReadWrite.All | 两者 | 我们正在将课程、学校和成员以及来自教育 api 的术语信息存储在我们的 api 中，并且我们需要它，因为如果我们每次从图形 api 获取它，这会使应用程序运行缓慢。我们会根据基于时间的事件将其从教育 api 同步到我们的数据库。 | 此权限允许应用获取租户组的不同 claender 事件。、subject、start、end、extensions | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| Member.Read.Hidden | 应用程序 |  |  | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| Sites.ReadWrite.All | 两者 | 我们正在将课程、学校和成员以及来自教育 api 的术语信息存储在我们的 api 中，并且我们需要它，因为如果我们每次从图形 api 获取它，这会使应用程序运行缓慢。我们会根据基于时间的事件将其从教育 api 同步到我们的数据库。 | 从一个驱动器读取文件 | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| User.Read | delegated | 我们正在将课程、学校和成员以及来自教育 api 的术语信息存储在我们的 api 中，并且我们需要它，因为如果我们每次从图形 api 获取它，这会使应用程序运行缓慢。我们会根据基于时间的事件将其从教育 api 同步到我们的数据库。 | 读取用户信息 | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| User.ReadBasic.All | delegated | 我们正在将课程、学校和成员以及来自教育 api 的术语信息存储在我们的 api 中，并且我们需要它，因为如果我们每次从图形 api 获取它，这会使应用程序运行缓慢。我们会根据基于时间的事件将其从教育 api 同步到我们的数据库。 | 读取用户信息 | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |


#### <a name="non-microsoft-services-used"></a>非Microsoft 服务使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>不Microsoft 服务非活动。

#### <a name="data-access-via-bots"></a>通过机器人访问数据

如果此应用程序包含机器人或消息扩展，则它可以访问最终用户可识别信息 (EUII) ：名单 (名字、姓氏、显示名称、电子邮件地址) （团队中任何团队成员的姓名、姓氏、电子邮件地址) 或添加到其中聊天）。 此应用是否使用了此功能？

>无法访问 EUII。


#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或 EUII (最终用户可识别) 是否显示在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>任何此类数据不会显示在日志中

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>它存储在 Azure 虚拟机数据库中，并且默认情况下随子数据库一起提供的任何加密和存储都适用于此应用程序。

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>不支持

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

下面将显示[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35976' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35976" target="_blank">在新建选项卡中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

