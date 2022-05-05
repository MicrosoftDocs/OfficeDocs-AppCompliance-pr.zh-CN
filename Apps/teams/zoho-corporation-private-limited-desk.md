---
title: Zoho Corporation Private Limited 的 Zoho Desk 应用程序信息
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 04/19/2022
ms.topic: article
ms.service: attestation
certification_type: attested
description: Zoho Desk 的所有可用安全性和符合性信息、其数据处理策略、其Microsoft Cloud App Security应用目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-security-compliance-privsection-zerotrust
ms.openlocfilehash: 6386c25acea352558965af02c99a49cd79baff6b
ms.sourcegitcommit: 7a7de9f48f6cf5b6acd435412477b6a59127f19a
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 05/05/2022
ms.locfileid: "65227979"
---
# <a name="zoho-desk"></a>Zoho Desk

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2021 年 10 月 20 日</p>

* [Teams存储区中的视图](https://teams.microsoft.com/l/app/091ec948-c0ee-4d56-aa9e-51c3d8316a9c)
* [在 AppSource 中查看](https://appsource.microsoft.com/product/office/WA104382044)

::: zone pivot="general"

### <a name="general-information"></a>一般信息

Zoho Corporation Private Limited 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | Zoho Desk |
| ID | WA104382044 |
| 支持Office 365客户端 | Microsoft Teams |
| 合作伙伴公司名称 | Zoho Corporation Private Limited |
| 公司的网站 | [https://www.zoho.com](https://www.zoho.com) |
| 应用的使用条款 | [https://www.zoho.com/terms.html](https://www.zoho.com/terms.html) |
| 应用的核心功能 | Zoho Desk 是基于 Web 的帮助台软件，可让你高效地管理客户支持活动。 使用 Zoho Desk，可以轻松地在支持台票证上分配、跟踪和设置警报。 可以为业务自定义 Zoho Desk，并确保客户支持体验的满意度。 |
| 公司总部位置 | 美国美国 |
| 应用信息页 | [https://www.zoho.com/desk/help/](https://www.zoho.com/desk/help/) |
| 用于运行应用的托管环境或服务模型是什么？ | IsvHosted |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

Zoho Corporation Private Limited 提供了此信息，了解此应用如何收集和存储组织数据以及组织对应用收集的数据的控制。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph进行数据访问

列出此应用所需的任何 [Microsoft Graph权](/graph/permissions-reference)限。

>| **权限**  | **(委派/应用程序) 的权限类型** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Files.Read | 委托 |  | 读取用户文件。 |  |
>| Files.Read.All | 委托 |  | 读取用户可以访问的所有文件。 |  |
>| User.Read | 委托 |  | 登录并读取用户配置文件。 |  |
>| User.ReadBasic.All | 委托 |  | 读取所有用户的基本配置文件。 |  |
>| 电子邮件 | 委托 |  | 查看用户的电子邮件地址。 |  |
>| offline_access | 委托 |  | 维护对已授予其访问权限的数据的访问权限。 |  |
>| 个人资料 | 委托 |  | 查看用户的基本配置文件。 |  |


#### <a name="non-microsoft-services-used"></a>未使用Microsoft 服务

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输的数据，并包含应用需要传输此信息的原因。

>不使用非Microsoft 服务。

#### <a name="data-access-via-bots"></a>通过机器人进行数据访问

如果此应用包含机器人或消息传递扩展，则它可以访问最终用户身份信息 (EUII) ：名册 (名字、姓氏、显示名称、团队中任何团队成员的电子邮件地址) 或添加到的聊天。 此应用是否利用此功能？

>未访问 EUII。


#### <a name="telemetry-data"></a>遥测数据

此应用程序的遥测或日志中是否 (OII) 或最终用户身份信息 (EUII) 显示任何组织可识别信息？ 如果是，请描述存储的数据以及什么是保留和删除策略？

>否

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

介绍组织管理员如何控制合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>1) 用户界面中有一个选项可删除具有删除选项的 Zoho 桌面中的实体、管理员和代理可以执行此操作。2) 我们还可以选择导出管理员可以导出和实现的用途。  3) 在客户请求后，我们会在后端进行审核，可以提供此信息。

| **Information** | **响应** |
|:----------------|:-------------|
| 应用或基础结构是否处理与 Microsoft 客户或其设备相关的任何数据？ | 是 |
| 应用会处理哪些数据？ | 配置文件数据，个人对话 Webhook。 |
| 应用是否支持 TLS 1.1 或更高版本？ | 是 |
| 应用或基础结构是否存储任何 Microsoft 客户数据？ | 是 |
| 数据库中存储了哪些数据？ | 用户 ID、用户名、电子邮件地址 |
| 如果基础结构处理或存储 Microsoft 客户数据，则此数据在地理上存储在哪里？ | 美国、爱尔兰、荷兰美国 () 、中国、日本、印度、澳大利亚 |
| 是否已建立数据出租和处置流程？ | 是 |
| 帐户终止后数据保留多长时间？ | 小于 90 天 |
| 是否已建立数据访问管理过程？ | 是 |
| 是否将客户数据或客户内容传输到第三方或子处理器？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="security"

下面显示了[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/28308' frameborder='no'></iframe>在新的 
| **tabInformation** | **响应** |
|:----------------|:-------------|
| 

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/28308" target="_blank">中查看</a>你是否对应用执行年度渗透测试？ | 是的 |
| ，应用是否具有记录的灾难恢复计划，包括备份和还原策略？ | 是的 |
| ，你的环境是否使用传统的反恶意软件保护或应用程序控件？ | 传统AntiMalware、ApplicationControls |
| 是否具有一个用于缩进和风险排名安全漏洞的既定过程？ | 是的 |
| ，你有一个策略来管理服务级别协议 (SLA) 来应用修补程序？ | 是的 |
| ，是否根据修补策略 SLA 执行修补程序管理活动？ | 是的 |
| ，环境是否有不受支持的操作系统或软件？ | 否 |
| ，是否对应用以及支持它的构造进行季度漏洞扫描？ | 是的 |
| ，外部网络边界上是否安装了防火墙？ | 是的 |
| ，你有一个已建立的更改管理流程，用于在更改请求部署到生产环境之前审查和批准更改请求？ | 是的 |
| ，其他人员是否正在审查和批准原始开发人员提交到生产的所有代码更改请求？ | 是的 |
| ，安全编码做法是否考虑到常见的漏洞类，如 OWASP 前 10 名？ | 是， |
| 启用了多重身份验证 (MFA) ： | CodeRepositories、DNSManagement、Credential |
| 是否已建立预配、修改和删除员工帐户的过程？ | 是的 |
| ，是否在支持应用的网络边界的外围部署了入侵检测和预防 (IDPS) 软件？ | 是的 |
| ，是否在支持应用的所有系统组件上设置了事件日志记录？ | 是的 |
| ，是否所有日志都按人工或自动化工具定期查看，以检测潜在的安全事件？ | 是 |
| 当检测到安全事件时，系统会自动将警报发送给员工进行会审？ | 是的 |
| ，是否建立了正式的信息安全风险管理流程？ | 是的 |
| ，是否已记录并建立了正式的安全事件响应流程？ | 是的 |
| ，是否在检测后 72 小时内向受违规影响的监管机构和个人报告应用或服务数据泄露？ | 是的 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="compliance"

| **Information** | **响应** |
|:----------------|:-------------|
| 应用是否符合 HIPAA)  (健康保险可移植性和会计法？ | 是 |
| 应用是否符合 Health Information Trust Alliance、Common Security Framework (HITRUST CSF) ？ | 否 |
| 应用是否符合服务组织控制 (SOC 1) ？ | 否 |
| 应用是否符合服务组织控制 (SOC 2) ？ | 是 |
| 你实现了哪个 SOC 2 认证？ | type2 |
| 最新的 SOC2 认证日期 | 2021-11-30 |
| 应用是否符合服务组织控制 (SOC 3) ？ | 否 |
| 是否针对应用及其支持环境执行年度 PCI DSS 评估？ | 不支持 |
| 应用国际标准化组织 (ISO 27001 是否) 认证？ | 是 |
| 应用是否符合国际标准化组织 (ISO 27018) ？ | 是 |
| 应用是否符合国际标准化组织 (ISO 27017) ？ | 是 |
| 应用是否符合国际标准化组织 (ISO 27002) ？ | 否 |
| 应用联邦风险和授权管理计划 (FedRAMP 是否) 合规？ | 不支持 |
| 应用是否符合 FERPA)  (家庭教育权利和隐私法？ | 不支持 |
| 应用是否符合《儿童在线隐私保护法》 (COPPA) ？ | 不支持 |
| 应用是否符合 SOX)  (Sarbanes-Oxley法案？ | 不支持 |
| 应用是否符合 NIST 800-171？ | 不支持 |
| 应用是否已通过云安全联盟 (CSA Star) 认证？ | 是 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="privsection"

| **Information** | **响应** |
|:----------------|:-------------|
| 是否具有 GDPR 或其他隐私或数据保护要求或义务 (，如 CCPA) ？ | 是 |
| 应用是否具有面向外部的隐私通知，描述它如何收集、使用、共享和存储客户数据？ | 是 |
| 隐私策略 URL | https://www.zoho.com/terms.html |
| 应用是否执行自动决策，包括可能具有法律效果或类似影响的分析？ | 否 |
| 应用是否针对隐私通知中未描述的辅助用途处理客户数据， (即营销、分析) ？ | 不支持 |
| 你是否处理敏感数据的特殊类别 (，即种族或种族来源、政治观点、宗教或哲学信仰、遗传或生物识别数据、健康数据) 或违反通知法的数据类别？ | 不支持 |
| 应用是否从未成年人 (（即 16 岁以下的人）收集或处理数据) ？ | 不支持 |
| 应用是否具有在请求时删除个人个人数据的功能？ | 是 |
| 应用是否能够在请求时限制或限制个人个人数据的处理？ | 是 |
| 应用是否使个人能够更正或更新其个人数据？ | 是 |
| 是否定期执行数据安全和隐私评审 (例如，数据保护影响评估或隐私风险评估) ，以确定与处理应用的个人数据相关的风险？ | 是 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="zerotrust"

| **Information** | **响应** |
|:----------------|:-------------|
| 应用程序是否与 Microsoft 标识平台 (Azure AD) 集成以进行单一登录、API 访问等？ | 是 |
| 是否已查看并遵守Microsoft 标识平台集成清单中列出的所有适用最佳做法？ | 是 |
| 应用是否使用最新版本的 MSAL (Microsoft 身份验证库) 或 Microsoft Identity Web 进行身份验证？ | 是 |
| 如果你的应用不使用上述库之一，它使用什么身份验证库或库？ |  |
| 应用是否支持条件访问策略？ | 是 |
| 列出支持的策略类型 | 多重身份验证，要求特定应用程序使用组织管理的设备，阻止有风险的登录行为，限制对管理角色以外的人员的访问权限  |
| 应用是否支持持续访问评估 (CAE)  | 是 |
| 应用是否在代码中存储任何凭据？ | 不支持 |
| Microsoft 365的应用和加载项可能会在 Microsoft Graph 之外使用其他 Microsoft API。 你的应用或外接程序是否使用其他 Microsoft API？ | 不支持 |

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph进行数据访问

>|   **Graph权限**  | **权限类型** |          **字距调整**          | **Azure AD应用 ID** |
>|:------------------------|:--------------------|:------------------------------------|:--------------------|
>| Contacts.Read | 委托 | 读取用户联系人 | [8a35e217-58cf-4eab-b2b4-384260d3d7f3](../azure/8a35e217-58cf-4eab-b2b4-384260d3d7f3.md) |
>| Files.Read | 委托 | 读取用户文件 | [8a35e217-58cf-4eab-b2b4-384260d3d7f3](../azure/8a35e217-58cf-4eab-b2b4-384260d3d7f3.md) |
>| Files.Read.All | 委托 | 读取用户可以访问的所有文件 | [8a35e217-58cf-4eab-b2b4-384260d3d7f3](../azure/8a35e217-58cf-4eab-b2b4-384260d3d7f3.md) |
>| Files.Read.Selected | 委托 | 读取用户选择的文件 | [8a35e217-58cf-4eab-b2b4-384260d3d7f3](../azure/8a35e217-58cf-4eab-b2b4-384260d3d7f3.md) |
>| User.Read | 委托 | 登录并读取用户个人资料 | [8a35e217-58cf-4eab-b2b4-384260d3d7f3](../azure/8a35e217-58cf-4eab-b2b4-384260d3d7f3.md) |
>| User.ReadBasic.All | 委托 | 读取所有用户的基本个人资料 | [8a35e217-58cf-4eab-b2b4-384260d3d7f3](../azure/8a35e217-58cf-4eab-b2b4-384260d3d7f3.md) |
>| 电子邮件 | 委托 | 查看用户的电子邮件地址 | [8a35e217-58cf-4eab-b2b4-384260d3d7f3](../azure/8a35e217-58cf-4eab-b2b4-384260d3d7f3.md) |
>| offline_access | 委托 | 保留对已授予其访问权限的数据的访问权限 | [8a35e217-58cf-4eab-b2b4-384260d3d7f3](../azure/8a35e217-58cf-4eab-b2b4-384260d3d7f3.md) |
>| 个人资料 | 委托 | 查看用户的基本个人资料 | [8a35e217-58cf-4eab-b2b4-384260d3d7f3](../azure/8a35e217-58cf-4eab-b2b4-384260d3d7f3.md) |

>此应用程序没有其他 API。

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

