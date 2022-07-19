---
title: QuickMinutes 的应用程序信息
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 07/18/2022
ms.topic: article
ms.service: attestation
certification_type: attested
description: QuickMinutes 的所有可用安全性和符合性信息、其数据处理策略、其Microsoft Cloud App Security应用目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-security-compliance-privsection-zerotrust
ms.openlocfilehash: 462cbb7aa74e6a1f4718554efdfc0e482a832b44
ms.sourcegitcommit: 21d1c42a8e6d9f94b9c8f279bbe37f649ebd4e10
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 07/19/2022
ms.locfileid: "66852684"
---
# <a name="quickminutes"></a>QuickMinutes

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2022 年 6 月 9 日</p>

* <a href="https://teams.microsoft.com/l/app/5f60fe53-d441-4320-8c26-13fdaee9b58a" target="_blank">在 Teams 应用商店中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA200004414" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

QuickMinutes 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | QuickMinutes |
| ID | WA200004414 |
| 支持Office 365客户端 | Microsoft Teams |
| 合作伙伴公司名称 | QuickMinutes |
| 公司的网站 | [https://quickminutes.com](https://quickminutes.com) |
| 应用的使用条款 | [https://quickminutes.com/privacy#/terms_of_service](https://quickminutes.com/privacy#/terms_of_service) |
| 应用的核心功能 | 使用智能数字助理简化会议联机工作流。 |
| 公司总部位置 | 爱尔兰 |
| 应用信息页 | [https://support.quickminutes.com/portal/en-gb/kb/articles/m...](https://support.quickminutes.com/portal/en-gb/kb/articles/microsoft-teams-integration-22-4-2020-1) |
| 用于运行应用的托管环境或服务模型是什么？ | Iaas |
| 应用使用哪些托管云提供商？ | Azure |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

QuickMinutes 提供了此信息，了解此应用如何收集和存储组织数据，以及组织对应用收集的数据的控制。

| **Information** | **响应** |
|:----------------|:-------------|
| 应用或基础结构是否处理与 Microsoft 客户或其设备相关的任何数据？ | 是 |
| 应用会处理哪些数据？ | 当用户使用 Microsoft SSO 向 QuickMinutes 注册新帐户时，我们使用用户配置文件数据在 QuickMinutes DB 中填充用户信息。 QuickMinutes 会拉取用户日历数据，以在 QuickMinutes UI 中显示事件。 我们不会将此信息存储在 QuickMinutes DB 中，只需从图形 API检索信息并将其显示给用户。  |
| 应用是否支持 TLS 1.1 或更高版本？ | 是 |
| 应用或基础结构是否存储任何 Microsoft 客户数据？ | 是 |
| 数据库中存储了哪些数据？ | 用户配置文件信息，例如名字、姓氏、Email和配置文件图片。 我们还存储用户 MS 访问和刷新令牌。 |
| 如果基础结构处理或存储 Microsoft 客户数据，则此数据在地理上存储在哪里？ | 爱尔兰 |
| 是否已建立数据出租和处置流程？ | 是 |
| 帐户终止后数据保留多长时间？ | 不保留 |
| 是否已建立数据访问管理过程？ | 是 |
| 是否将客户数据或客户内容传输到第三方或子处理器？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="security"

下面显示了[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

| **Information** | **响应** |
|:----------------|:-------------|
| 是否对应用执行年度渗透测试？ | 否 |
| 应用是否具有记录的灾难恢复计划，包括备份和还原策略？ | 是 |
| 环境是否使用传统的反恶意软件保护或应用程序控件？ | TraditionalAntiMalware、ApplicationControls |
| 你有一个用于缩进和风险排名安全漏洞的既定过程吗？ | 否 |
| 是否具有管理服务级别协议 (SLA) 的策略来应用修补程序？ | 是 |
| 是否根据修补策略 SLA 执行修补程序管理活动？ | 是 |
| 环境是否有不受支持的操作系统或软件？ | 否 |
| 是否对应用以及支持它的构造进行季度漏洞扫描？ | 否 |
| 外部网络边界上是否安装了防火墙？ | 是 |
| 是否已建立更改管理流程，用于在更改请求部署到生产环境之前查看和批准更改请求？ | 是 |
| 其他人员是否正在审查和批准原始开发人员提交到生产的所有代码更改请求？ | 是 |
| 安全编码做法是否考虑到常见的漏洞类，例如 OWASP 前 10 名？ | 是 |
| 启用了多重身份验证 (MFA) ： | DNSManagement、Credential、CodeRepositories |
| 是否已建立预配、修改和删除员工帐户的过程？ | 是 |
| 是否已将入侵检测和预防 (IDPS) 软件部署在支持应用的网络边界外围？ | 是 |
| 是否在支持应用的所有系统组件上设置了事件日志记录？ | 是 |
| 是否通过人工或自动化工具定期查看所有日志，以检测潜在的安全事件？ | 否 |
| 检测到安全事件时，系统会自动将警报发送给员工进行会审？ | 否 |
| 是否建立了正式的信息安全风险管理流程？ | 否 |
| 是否已记录并建立了正式的安全事件响应流程？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="compliance"

| **Information** | **响应** |
|:----------------|:-------------|
| 应用是否符合 HIPAA)  (健康保险可移植性和会计法？ | 不适用 |
| 应用是否符合 Health Information Trust Alliance、Common Security Framework (HITRUST CSF) ？ | 不适用 |
| 应用是否符合服务组织控制 (SOC 1) ？ | 不适用 |
| 应用是否符合服务组织控制 (SOC 2) ？ | 否 |
| 应用是否符合服务组织控制 (SOC 3) ？ | 否 |
| 是否针对应用及其支持环境执行年度 PCI DSS 评估？ | 不适用 |
| 应用国际标准化组织 (ISO 27001 是否) 认证？ | 否 |
| 应用是否符合国际标准化组织 (ISO 27018) ？ | 不适用 |
| 应用是否符合国际标准化组织 (ISO 27017) ？ | 否 |
| 应用是否符合国际标准化组织 (ISO 27002) ？ | 否 |
| 应用联邦风险和授权管理计划 (FedRAMP 是否) 合规？ | 否 |
| 应用是否符合 FERPA)  (家庭教育权利和隐私法？ | 否 |
| 应用是否符合《儿童在线隐私保护法》 (COPPA) ？ | 否 |
| 应用是否符合 SOX)  (Sarbanes-Oxley法案？ | 不适用 |
| 应用是否符合 NIST 800-171？ | 不适用 |
| 应用是否已通过云安全联盟 (CSA Star) 认证？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="privsection"

| **Information** | **响应** |
|:----------------|:-------------|
| 是否具有 GDPR 或其他隐私或数据保护要求或义务 (，如 CCPA) ？ | 是 |
| 应用是否具有面向外部的隐私通知，描述它如何收集、使用、共享和存储客户数据？ | 是 |
| 隐私策略 URL | https://quickminutes.com/privacy#/privacy_policy |
| 应用是否执行自动决策，包括可能具有法律效果或类似影响的分析？ | 否 |
| 应用是否针对隐私通知中未描述的辅助用途处理客户数据， (即营销、分析) ？ | 否 |
| 你是否处理敏感数据的特殊类别 (，即种族或种族来源、政治观点、宗教或哲学信仰、遗传或生物识别数据、健康数据) 或违反通知法的数据类别？ | 否 |
| 应用是否从未成年人 (（即 16 岁以下的人）收集或处理数据) ？ | 否 |
| 应用是否具有在请求时删除个人个人数据的功能？ | 是 |
| 应用是否能够在请求时限制或限制个人个人数据的处理？ | 否 |
| 应用是否使个人能够更正或更新其个人数据？ | 是 |
| 是否定期执行数据安全和隐私评审 (例如，数据保护影响评估或隐私风险评估) ，以确定与处理应用的个人数据相关的风险？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="zerotrust"

| **Information** | **响应** |
|:----------------|:-------------|
| 应用程序是否与 Microsoft Identity Platform (Azure AD) 集成以进行单一登录、API 访问等？ | 是 |
| 是否已查看并遵守Microsoft 标识平台集成清单中列出的所有适用最佳做法？ | 是 |
| 应用是否使用最新版本的 MSAL (Microsoft 身份验证库) 或 Microsoft Identity Web 进行身份验证？ | 不适用 |
| 应用是否支持条件访问策略？ | 否 |
| 应用是否支持持续访问评估 (CAE)  | 否 |
| 应用是否在代码中存储任何凭据？ | 否 |
| 适用于 Microsoft 365 的应用和加载项可能会在 Microsoft Graph 之外使用其他 Microsoft API。 你的应用或外接程序是否使用其他 Microsoft API？ | 否 |

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 访问数据

>|   **图形权限**  | **权限类型** |          **字距调整**          | **Azure AD 应用 ID** |
>|:------------------------|:--------------------|:------------------------------------|:--------------------|
>| Calendars.ReadWrite | 委托 | QuickMinutes 使用日历范围将 QuickMinutes 会议读取/写入用户 Microsoft 日历 | [e340e520-b8f4-4752-8e1c-60270c863b12](../azure/e340e520-b8f4-4752-8e1c-60270c863b12.md) |
>| People.Read | 委托 | 当用户添加到其 QuickMinutes 组织或组时，QuickMinutes 使用人员范围列出 Microsoft 用户联系人 | [e340e520-b8f4-4752-8e1c-60270c863b12](../azure/e340e520-b8f4-4752-8e1c-60270c863b12.md) |
>| 电子邮件 | 委托 | 电子邮件范围用于使 QuickMinutes 以电子邮件声明的形式访问用户的主要电子邮件地址。 | [e340e520-b8f4-4752-8e1c-60270c863b12](../azure/e340e520-b8f4-4752-8e1c-60270c863b12.md) |
>| openid | 委托 | Microsoft 标识平台令牌终结点上的 QuickMinutes 使用 openid 范围来获取 ID 令牌。 这允许 QuickMinutes 使用令牌代表用户访问图形 API | [e340e520-b8f4-4752-8e1c-60270c863b12](../azure/e340e520-b8f4-4752-8e1c-60270c863b12.md) |
>| 个人资料 | 委托 | 通过 Microsoft SSO 注册用户并创建其 QuickMinutes 帐户时，QuickMinutes 使用配置文件范围访问用户配置文件。 | [e340e520-b8f4-4752-8e1c-60270c863b12](../azure/e340e520-b8f4-4752-8e1c-60270c863b12.md) |

>此应用程序没有其他 API。

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

