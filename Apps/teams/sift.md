---
title: Sift by Sift 的应用程序信息
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 04/26/2022
ms.topic: article
ms.service: attestation
certification_type: attested
description: 适用于 Sift 的所有可用安全性和符合性信息、其数据处理策略、其Microsoft Cloud App Security应用目录信息以及 CSA STAR 注册表中的安全/合规性信息。
zone_pivot_groups: app-info-data-security-compliance-privsection-zerotrust
ms.openlocfilehash: e512af6a13192347f76e98516a1a3b8ed48bef09
ms.sourcegitcommit: b0c1d8160b4e9a27f23a9d723f7e76d38ab12d9e
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/29/2022
ms.locfileid: "65125296"
---
# <a name="sift"></a>筛选

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2022 年 4 月 25 日</p>

* <a href="https://teams.microsoft.com/l/app/d2a1ed44-6cca-44d2-9b9c-1c9c1d597093" target="_blank">Teams存储区中的视图</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002545" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

Sift 提供给 Microsoft 的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | 筛选 |
| ID | WA200002545 |
| 支持Office 365客户端 | Microsoft Teams |
| 合作伙伴公司名称 | 筛选 |
| 公司的网站 | [https://www.justsift.com](https://www.justsift.com) |
| 应用的使用条款 | [https://www.justsift.com/sift-msteams-eula](https://www.justsift.com/sift-msteams-eula) |
| 应用的核心功能 | 查找、发现组织人员并与之建立联系 |
| 公司总部位置 | 美国美国 |
| 应用信息页 | [https://www.justsift.com/integrating-sift/with-microsoft-te...](https://www.justsift.com/integrating-sift/with-microsoft-teams) |
| 用于运行应用的托管环境或服务模型是什么？ | Paas |
| 应用使用哪些托管云提供商？ | Azure |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

Sift 提供了此信息，了解此应用如何收集和存储组织数据，以及组织对应用收集的数据的控制。

| **Information** | **响应** |
|:----------------|:-------------|
| 应用或基础结构是否处理与 Microsoft 客户或其设备相关的任何数据？ | 可访问 |
| 应用会处理哪些数据？ | Teams应用要求获取基本配置文件信息并同意查看来自Azure AD用户的会议数据。 它还自愿从用户收集其他配置文件信息，以增强其在平台内的配置文件。 |
| 应用是否支持 TLS 1.1 或更高版本？ | 是 |
| 应用或基础结构是否存储任何 Microsoft 客户数据？ | 是 |
| 数据库中存储了哪些数据？ | 如果管理用户授予许可，则收集 Microsoft graph 中的用户配置文件信息。 |
| 如果基础结构处理或存储 Microsoft 客户数据，则此数据在地理上存储在哪里？ | 美国美国 |
| 是否已建立数据出租和处置流程？ | 是 |
| 帐户终止后数据保留多长时间？ |  |
| 是否已建立数据访问管理过程？ | 可访问 |
| 是否将客户数据或客户内容传输到第三方或子处理器？ | 可访问 |
| 是否已与共享 Microsoft 客户数据的任何第三方服务达成数据共享协议？ | 可访问 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="security"

下面显示了[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

| **Information** | **响应** |
|:----------------|:-------------|
| 是否对应用执行年度渗透测试？ | 是 |
| 应用是否具有记录的灾难恢复计划，包括备份和还原策略？ | 是 |
| 环境是否使用传统的反恶意软件保护或应用程序控件？ | ApplicationControls、TraditionalAntiMalware |
| 你有一个用于缩进和风险排名安全漏洞的既定过程吗？ | 是 |
| 是否具有管理服务级别协议 (SLA) 的策略来应用修补程序？ | 是 |
| 是否根据修补策略 SLA 执行修补程序管理活动？ | 是 |
| 环境是否有不受支持的操作系统或软件？ | 否 |
| 是否对应用以及支持它的构造进行季度漏洞扫描？ | 是 |
| 外部网络边界上是否安装了防火墙？ | 是 |
| 是否已建立更改管理流程，用于在更改请求部署到生产环境之前查看和批准更改请求？ | 是 |
| 其他人员是否正在审查和批准原始开发人员提交到生产的所有代码更改请求？ | 是 |
| 安全编码做法是否考虑到常见的漏洞类，例如 OWASP 前 10 名？ | 否 |
| 启用了多重身份验证 (MFA) ： | CodeRepositories、DNSManagement、Credential |
| 是否已建立预配、修改和删除员工帐户的过程？ | 可访问 |
| 是否已将入侵检测和预防 (IDPS) 软件部署在支持应用的网络边界外围？ | 可访问 |
| 是否在支持应用的所有系统组件上设置了事件日志记录？ | 可访问 |
| 是否通过人工或自动化工具定期查看所有日志，以检测潜在的安全事件？ | 是 |
| 检测到安全事件时，系统会自动将警报发送给员工进行会审？ | 是 |
| 是否建立了正式的信息安全风险管理流程？ | 是 |
| 是否已记录并建立了正式的安全事件响应流程？ | 可访问 |
| 是否在检测后 72 小时内向受违规影响的监管机构和个人报告应用或服务数据泄露？ | 是 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="compliance"

| **Information** | **响应** |
|:----------------|:-------------|
| 应用是否符合 HIPAA)  (健康保险可移植性和会计法？ | 不适用 |
| 应用是否符合 Health Information Trust Alliance、Common Security Framework (HITRUST CSF) ？ | 不适用 |
| 应用是否符合服务组织控制 (SOC 1) ？ | 否 |
| 应用是否符合服务组织控制 (SOC 2) ？ | 可访问 |
| 你实现了哪个 SOC 2 认证？ | type2 |
| 最新的 SOC2 认证日期 | 2022-04-25 |
| 应用是否符合服务组织控制 (SOC 3) ？ | 否 |
| 是否针对应用及其支持环境执行年度 PCI DSS 评估？ | 否 |
| 应用国际标准化组织 (ISO 27001 是否) 认证？ | 否 |
| 应用是否符合国际标准化组织 (ISO 27018) ？ | 否 |
| 应用是否符合国际标准化组织 (ISO 27017) ？ | 否 |
| 应用是否符合国际标准化组织 (ISO 27002) ？ | 否 |
| 应用联邦风险和授权管理计划 (FedRAMP 是否) 合规？ | 否 |
| 应用是否符合 FERPA)  (家庭教育权利和隐私法？ | 不适用 |
| 应用是否符合《儿童在线隐私保护法》 (COPPA) ？ | 不适用 |
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
| 隐私策略 URL | https://www.justsift.com/privacy-policy |
| 应用是否执行自动决策，包括可能具有法律效果或类似影响的分析？ | 否 |
| 应用是否针对隐私通知中未描述的辅助用途处理客户数据， (即营销、分析) ？ | 否 |
| 你是否处理敏感数据的特殊类别 (，即种族或种族来源、政治观点、宗教或哲学信仰、遗传或生物识别数据、健康数据) 或违反通知法的数据类别？ | 否 |
| 应用是否从未成年人 (（即 16 岁以下的人）收集或处理数据) ？ | 否 |
| 应用是否具有在请求时删除个人个人数据的功能？ | 可访问 |
| 应用是否能够在请求时限制或限制个人个人数据的处理？ | 可访问 |
| 应用是否使个人能够更正或更新其个人数据？ | 可访问 |
| 是否定期执行数据安全和隐私评审 (例如，数据保护影响评估或隐私风险评估) ，以确定与处理应用的个人数据相关的风险？ | 是 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="zerotrust"

| **Information** | **响应** |
|:----------------|:-------------|
| 应用程序是否与 Microsoft 标识平台 (Azure AD) 集成以进行单一登录、API 访问等？ | 是 |
| 是否已查看并遵守Microsoft 标识平台集成清单中列出的所有适用最佳做法？ | 否 |
| 应用是否使用最新版本的 MSAL (Microsoft 身份验证库) 或 Microsoft Identity Web 进行身份验证？ | 可访问 |
| 应用是否支持条件访问策略？ | 否 |
| 应用是否支持持续访问评估 (CAE)  | 否 |
| 应用是否在代码中存储任何凭据？ | 否 |
| Microsoft 365的应用和加载项可能会在 Microsoft Graph 之外使用其他 Microsoft API。 你的应用或外接程序是否使用其他 Microsoft API？ | 否 |

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph进行数据访问

>|   **Graph权限**  | **权限类型** |          **字距调整**          | **Azure AD应用 ID** |
>|:------------------------|:--------------------|:------------------------------------|:--------------------|
>| Group.Read.All | 委托 | 从Graph检索组信息，以便按组筛选检索到的用户 | [270b510a-7cfb-4a9a-8071-5ceab03cf357](../azure/270b510a-7cfb-4a9a-8071-5ceab03cf357.md) |
>| User.Read.All | 委托 | 从Graph检索用户对象，以便在产品中预配和持续更新员工配置文件 | [270b510a-7cfb-4a9a-8071-5ceab03cf357](../azure/270b510a-7cfb-4a9a-8071-5ceab03cf357.md) |
>| OnlineMeetingArtifact.Read.All | 委托 | 对于Teams应用中的会议扩展，我们需要有权检索有关会议参与者的信息 | [d2a1ed44-6cca-44d2-9b9c-1c9c1d597093](../azure/d2a1ed44-6cca-44d2-9b9c-1c9c1d597093.md) |
>| OnlineMeetings.Read | 委托 | 对于Teams应用中的会议扩展，我们需要有权检索有关会议参与者的信息 | [d2a1ed44-6cca-44d2-9b9c-1c9c1d597093](../azure/d2a1ed44-6cca-44d2-9b9c-1c9c1d597093.md) |

>此应用程序没有其他 API。

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

