---
title: Atlassian 的 Jira Cloud 应用程序信息
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 10/27/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Jira Cloud 的所有可用安全性和符合性信息、其数据处理策略、其Microsoft Cloud App Security应用目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-security-compliance-privsection-zerotrust
ms.openlocfilehash: bcba0e0913aab92a5808c0316443696de0767b54
ms.sourcegitcommit: 5e2cd59a54fc018a6df761b00c18e3ba592d9dba
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/15/2022
ms.locfileid: "64880982"
---
# <a name="jira-cloud"></a>Jira Cloud

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2021 年 8 月 11 日</p>

* <a href="https://teams.microsoft.com/l/app/aa183fd9-7104-46c4-af9f-9ee9b81d717e" target="_blank">Teams存储区中的视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002140" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

Atlassian 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | Jira Cloud |
| ID | WA200002140 |
| 支持Office 365客户端 | Microsoft Teams |
| 合作伙伴公司名称 | Atlassian |
| 公司的网站 | [https://www.atlassian.com](https://www.atlassian.com) |
| 应用的使用条款 | [https://www.atlassian.com/licensing/marketplace/termsofuse](https://www.atlassian.com/licensing/marketplace/termsofuse) |
| 应用的核心功能 | 使团队能够从Microsoft Teams跟踪、更新和管理项目。 |
| 公司总部位置 | 澳大利亚 |
| 应用信息页 | |
| 用于运行应用的托管环境或服务模型是什么？ | Paas |
| 应用使用哪些托管云提供商？ | Aws |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

Atlassian 提供了此信息，了解此应用如何收集和存储组织数据，以及组织对应用收集的数据的控制。

| **Information** | **响应** |
|:----------------|:-------------|
| 应用或基础结构是否处理与 Microsoft 客户或其设备相关的任何数据？ | 是 |
| 应用会处理哪些数据？ | 用户配置文件数据，租户信息 |
| 应用是否支持 TLS 1.1 或更高版本？ | 是 |
| 应用或基础结构是否存储任何 Microsoft 客户数据？ | 可访问 |
| 数据库中存储了哪些数据？ | 租户 ID 和用户 ID |
| 如果基础结构处理或存储 Microsoft 客户数据，则此数据在地理上存储在哪里？ | 美国美国 |
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
| 应用是否具有记录的灾难恢复计划，包括备份和还原策略？ | 否 |
| 环境是否使用传统的反恶意软件保护或应用程序控件？ | TraditionalAntiMalware、ApplicationControls |
| 你有一个用于缩进和风险排名安全漏洞的既定过程吗？ | 可访问 |
| 是否具有管理服务级别协议 (SLA) 的策略来应用修补程序？ | 可访问 |
| 是否根据修补策略 SLA 执行修补程序管理活动？ | 是 |
| 环境是否有不受支持的操作系统或软件？ | 否 |
| 是否对应用以及支持它的构造进行季度漏洞扫描？ | 是 |
| 外部网络边界上是否安装了防火墙？ | 可访问 |
| 是否已建立更改管理流程，用于在更改请求部署到生产环境之前查看和批准更改请求？ | 是 |
| 其他人员是否正在审查和批准原始开发人员提交到生产的所有代码更改请求？ | 是 |
| 安全编码做法是否考虑到常见的漏洞类，例如 OWASP 前 10 名？ | 是 |
| 启用了多重身份验证 (MFA) ： | CodeRepositories、DNSManagement、Credential |
| 是否已建立预配、修改和删除员工帐户的过程？ | 可访问 |
| 是否已将入侵检测和预防 (IDPS) 软件部署在支持应用的网络边界外围？ | 是 |
| 是否在支持应用的所有系统组件上设置了事件日志记录？ | 可访问 |
| 是否通过人工或自动化工具定期查看所有日志，以检测潜在的安全事件？ | 是 |
| 检测到安全事件时，系统会自动将警报发送给员工进行会审？ | 是 |
| 是否建立了正式的信息安全风险管理流程？ | 是 |
| 是否已记录并建立了正式的安全事件响应流程？ | 是 |
| 是否在检测后 72 小时内向受违规影响的监管机构和个人报告应用或服务数据泄露？ | 可访问 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="compliance"

| **Information** | **响应** |
|:----------------|:-------------|
| 应用是否符合 HIPAA)  (健康保险可移植性和会计法？ | 否 |
| 应用是否符合 Health Information Trust Alliance、Common Security Framework (HITRUST CSF) ？ | 否 |
| 应用是否符合服务组织控制 (SOC 1) ？ | 否 |
| 应用是否符合服务组织控制 (SOC 2) ？ | 可访问 |
| 你实现了哪个 SOC 2 认证？ | type2 |
| 最新的 SOC2 认证日期 | 2020-10-31 |
| 应用是否符合服务组织控制 (SOC 3) ？ | 是 |
| 最新的 SOC3 认证日期 | 2020-10-31 |
| 是否针对应用及其支持环境执行年度 PCI DSS 评估？ | 否 |
| 应用国际标准化组织 (ISO 27001 是否) 认证？ | 可访问 |
| 应用是否符合国际标准化组织 (ISO 27018) ？ | 是 |
| 应用是否符合国际标准化组织 (ISO 27017) ？ | 否 |
| 应用是否符合国际标准化组织 (ISO 27002) ？ | 否 |
| 应用联邦风险和授权管理计划 (FedRAMP 是否) 合规？ | 否 |
| 应用是否符合 FERPA)  (家庭教育权利和隐私法？ | 否 |
| 应用是否符合《儿童在线隐私保护法》 (COPPA) ？ | 否 |
| 应用是否符合 SOX)  (Sarbanes-Oxley法案？ | 可访问 |
| 应用是否符合 NIST 800-171？ | 否 |
| 应用是否已通过云安全联盟 (CSA Star) 认证？ | 可访问 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="privsection"

| **Information** | **响应** |
|:----------------|:-------------|
| 是否具有 GDPR 或其他隐私或数据保护要求或义务 (，如 CCPA) ？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="zerotrust"

| **Information** | **响应** |
|:----------------|:-------------|
| 应用程序是否与 Microsoft 标识平台 (Azure AD) 集成以进行单一登录、API 访问等？ | 是 |
| 是否已查看并遵守Microsoft 标识平台集成清单中列出的所有适用最佳做法？ | 是 |
| 应用是否使用最新版本的 MSAL (Microsoft 身份验证库) 或 Microsoft Identity Web 进行身份验证？ | 否 |
| 如果你的应用不使用上述库之一，它使用什么身份验证库或库？ |  |
| 应用是否支持条件访问策略？ | 否 |
| 应用是否支持持续访问评估 (CAE)  | 否 |
| 应用是否在代码中存储任何凭据？ | 否 |
| Microsoft 365的应用和加载项可能会在 Microsoft Graph 之外使用其他 Microsoft API。 你的应用或外接程序是否使用其他 Microsoft API？ | 否 |

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph进行数据访问

>|   **Graph权限**  | **权限类型** |          **字距调整**          | **Azure AD应用 ID** |
>|:------------------------|:--------------------|:------------------------------------|:--------------------|
>| offline_access | 委托 | 在较长时间内代表用户提供对资源的访问权限，以确保最佳用户体验。 | [512b84d2-5840-45d6-8d01-5f073836d039](../azure/512b84d2-5840-45d6-8d01-5f073836d039.md) |
>| openid | 委托 | 获取用户的给定名称、姓氏、首选用户名和对象 ID。 | [512b84d2-5840-45d6-8d01-5f073836d039](../azure/512b84d2-5840-45d6-8d01-5f073836d039.md) |
>| 个人资料 | 委托 | 获取用户的给定名称、姓氏、首选用户名和对象 ID。 | [512b84d2-5840-45d6-8d01-5f073836d039](../azure/512b84d2-5840-45d6-8d01-5f073836d039.md) |

>此应用程序没有其他 API。

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

