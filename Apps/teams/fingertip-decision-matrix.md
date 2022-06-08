---
title: 手指提示决策矩阵的应用程序信息
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 06/07/2022
ms.topic: article
ms.service: attestation
certification_type: attested
description: 指尖决策矩阵的所有可用安全性和符合性信息、其数据处理策略、Microsoft Cloud App Security 应用目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-security-compliance-privsection-zerotrust
ms.openlocfilehash: 390378f757af6d9fd9afbfd647210827c6f9f3db
ms.sourcegitcommit: dbf716786f7a3c0b84fa4563e47510e4bd3a2fd0
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 06/08/2022
ms.locfileid: "65943178"
---
# <a name="fingertip-decision-matrix"></a>指尖决策矩阵

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2021 年 10 月 6 日</p>

* <a href="https://teams.microsoft.com/l/app/9d9390bb-2d73-4c5e-9609-0ee86fc620ce" target="_blank">在 Teams 应用商店中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA200004070" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

指尖提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | 指尖决策矩阵 |
| ID | WA200004070 |
| 支持 Office 365 客户端 | Microsoft Teams |
| 合作伙伴公司名称 | 指尖 |
| 公司的网站 | [https://www.fingertip.org](https://www.fingertip.org) |
| 应用的使用条款 | [https://www.fingertip.org/terms-of-use/](https://www.fingertip.org/terms-of-use/) |
| 应用的核心功能 | 手指提示决策矩阵可帮助你在需要考虑许多不同因素时在多种替代方法之间做出决定。 它使过程更加清晰和透明，并有助于你确定替代方法的优先级，同时减少偏见的影响。 借助按指尖的决策矩阵，可以使用 Microsoft Teams 协作更准确地一起做出决策。 |
| 公司总部位置 | 芬兰 |
| 应用信息页 | [https://www.fingertip.org/solutions/fingertip-decision-matr...](https://www.fingertip.org/solutions/fingertip-decision-matrix/) |
| 用于运行应用的托管环境或服务模型是什么？ | Iaas |
| 应用使用哪些托管云提供商？ | Azure |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

有关此应用如何收集和存储组织数据以及组织对应用收集的数据的控制，Fingertip 提供了此信息。

| **Information** | **响应** |
|:----------------|:-------------|
| 应用或基础结构是否处理与 Microsoft 客户或其设备相关的任何数据？ | 是 |
| 应用会处理哪些数据？ | 用户配置文件信息，租户 ID |
| 应用是否支持 TLS 1.1 或更高版本？ | 是 |
| 应用或基础结构是否存储任何 Microsoft 客户数据？ | 是 |
| 数据库中存储了哪些数据？ | 用户配置文件信息，租户 ID |
| 如果基础结构处理或存储 Microsoft 客户数据，则此数据在地理上存储在哪里？ | 芬兰 |
| 是否已建立数据出租和处置流程？ | 否 |
| 帐户终止后数据保留多长时间？ |  |
| 是否已建立数据访问管理过程？ | 是 |
| 是否将客户数据或客户内容传输到第三方或子处理器？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="security"

Microsoft [Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 目录中的信息如下所示。

| **Information** | **响应** |
|:----------------|:-------------|
| 是否对应用执行年度渗透测试？ | 是 |
| 应用是否具有记录的灾难恢复计划，包括备份和还原策略？ | 否 |
| 环境是否使用传统的反恶意软件保护或应用程序控件？ | ApplicationControls |
| 你有一个用于缩进和风险排名安全漏洞的既定过程吗？ | 是 |
| 是否具有管理服务级别协议 (SLA) 的策略来应用修补程序？ | 是 |
| 是否根据修补策略 SLA 执行修补程序管理活动？ | 是 |
| 环境是否有不受支持的操作系统或软件？ | 否 |
| 是否对应用以及支持它的构造进行季度漏洞扫描？ | 是 |
| 外部网络边界上是否安装了防火墙？ | 是 |
| 是否已建立更改管理流程，用于在更改请求部署到生产环境之前查看和批准更改请求？ | 是 |
| 其他人员是否正在审查和批准原始开发人员提交到生产的所有代码更改请求？ | 是 |
| 安全编码做法是否考虑到常见的漏洞类，例如 OWASP 前 10 名？ | 是 |
| 启用了多重身份验证 (MFA) ： | CodeRepositories、Credential、DNSManagement |
| 是否已建立预配、修改和删除员工帐户的过程？ | 是 |
| 是否已将入侵检测和预防 (IDPS) 软件部署在支持应用的网络边界外围？ | 是 |
| 是否在支持应用的所有系统组件上设置了事件日志记录？ | 是 |
| 是否通过人工或自动化工具定期查看所有日志，以检测潜在的安全事件？ | 是 |
| 检测到安全事件时，系统会自动将警报发送给员工进行会审？ | 是 |
| 是否建立了正式的信息安全风险管理流程？ | 是 |
| 是否已记录并建立了正式的安全事件响应流程？ | 是 |
| 是否在检测后 72 小时内向受违规影响的监管机构和个人报告应用或服务数据泄露？ | 是 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="compliance"

| **Information** | **响应** |
|:----------------|:-------------|
| 应用是否符合 HIPAA)  (健康保险可移植性和会计法？ | 不适用 |
| 应用是否符合 Health Information Trust Alliance、Common Security Framework (HITRUST CSF) ？ | 不适用 |
| 应用是否符合服务组织控制 (SOC 1) ？ | 否 |
| 应用是否符合服务组织控制 (SOC 2) ？ | 否 |
| 应用是否符合服务组织控制 (SOC 3) ？ | 否 |
| 是否针对应用及其支持环境执行年度 PCI DSS 评估？ | 不适用 |
| 应用国际标准化组织 (ISO 27001 是否) 认证？ | 否 |
| 应用是否符合国际标准化组织 (ISO 27018) ？ | 否 |
| 应用是否符合国际标准化组织 (ISO 27017) ？ | 否 |
| 应用是否符合国际标准化组织 (ISO 27002) ？ | 否 |
| 应用联邦风险和授权管理计划 (FedRAMP 是否) 合规？ | 否 |
| 应用是否符合 FERPA)  (家庭教育权利和隐私法？ | 不适用 |
| 应用是否符合《儿童在线隐私保护法》 (COPPA) ？ | 是 |
| 应用是否符合 SOX)  (Sarbanes-Oxley法案？ | 不适用 |
| 应用是否符合 NIST 800-171？ | 不适用 |
| 应用是否已通过云安全联盟 (CSA Star) 认证？ | 否 |

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
| 应用程序是否与 Microsoft Identity Platform (Azure AD) 集成以进行单一登录、API 访问等？ | 是 |
| 是否已查看并遵守 Microsoft 标识平台集成清单中列出的所有适用最佳做法？ | 是 |
| 应用是否使用最新版本的 MSAL (Microsoft 身份验证库) 或 Microsoft Identity Web 进行身份验证？ | 是 |
| 应用是否支持条件访问策略？ | 是 |
| 列出支持的策略类型 | 多重身份验证，仅允许 Intune 注册的设备访问特定服务，限制用户位置和 IP 范围 |
| 应用是否支持持续访问评估 (CAE)  | 否 |
| 应用是否在代码中存储任何凭据？ | 否 |
| 适用于 Microsoft 365 的应用和加载项可能会在 Microsoft Graph 之外使用其他 Microsoft API。 你的应用或外接程序是否使用其他 Microsoft API？ | 是 |

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 访问数据

>|   **图形权限**  | **权限类型** |          **字距调整**          | **Azure AD 应用 ID** |
>|:------------------------|:--------------------|:------------------------------------|:--------------------|
>| User.Read | 委托 | 用户创建的基本配置文件信息 | [5a6a4d82-42ce-42c4-88f0-df529fe54dcc](../azure/5a6a4d82-42ce-42c4-88f0-df529fe54dcc.md) |
>| User.ReadBasic.All | 委托 | 用户创建的基本配置文件信息 | [5a6a4d82-42ce-42c4-88f0-df529fe54dcc](../azure/5a6a4d82-42ce-42c4-88f0-df529fe54dcc.md) |
>| 电子邮件 | 委托 | 用户创建的基本配置文件信息 | [5a6a4d82-42ce-42c4-88f0-df529fe54dcc](../azure/5a6a4d82-42ce-42c4-88f0-df529fe54dcc.md) |
>| offline_access | 委托 | 对于用户是否断开连接 | [5a6a4d82-42ce-42c4-88f0-df529fe54dcc](../azure/5a6a4d82-42ce-42c4-88f0-df529fe54dcc.md) |
>| openid | 委托 | 登录 | [5a6a4d82-42ce-42c4-88f0-df529fe54dcc](../azure/5a6a4d82-42ce-42c4-88f0-df529fe54dcc.md) |
>| profile | 委托 | 用户创建的基本配置文件信息 | [5a6a4d82-42ce-42c4-88f0-df529fe54dcc](../azure/5a6a4d82-42ce-42c4-88f0-df529fe54dcc.md) |

>此应用程序没有其他 API。

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

