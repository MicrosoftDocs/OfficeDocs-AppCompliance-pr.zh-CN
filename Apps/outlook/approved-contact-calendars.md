---
title: 已批准联系人批准的联系人日历的应用程序信息
ms.author: elmalova
author: elenamalova
ms.date: 05/20/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: CSA STAR 注册表中批准的联系人日历的所有可用安全性和合规性信息、其数据处理策略Microsoft Cloud App Security应用程序目录信息和安全/合规性信息。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 6bf401411f26e95a952e75256bc46b8f28efed53
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 10/18/2021
ms.locfileid: "60428154"
---
# <a name="approved-contact-calendars"></a>批准的联系人日历

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>开发人员上次更新时间：2021 年 5 月 10 日</p>

* <a href="https://appsource.microsoft.com/product/office/WA104380294" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般信息

经批准的联系人向 Microsoft 提供的信息：

| **Information** | **响应** |
|:----------------|:-------------|
| 应用名称 | 批准的联系人日历 |
| ID | WA104380294 |
| Office 365支持的客户端 | Outlook 2013 或更高版本，Windows Mac Outlook 2016 或更高版本，Outlook 网页版 |
| 合作伙伴公司名称 | Approved Contact |
| 合作伙伴网站的 URL | [https://www.approvedcontact.com](https://www.approvedcontact.com) |
| 隐私策略的 URL | [https://approvedcontact.com/Privacy%20Policy.pdf](https://approvedcontact.com/Privacy%20Policy.pdf) |
| 使用条款 URL | [https://approvedcontact.com/Terms%20of%20use.pdf](https://approvedcontact.com/Terms%20of%20use.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>应用如何处理数据

批准联系人提供了此信息，这些信息与此应用程序如何收集和存储组织数据以及组织将拥有对应用收集的数据的控制有关。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph

列出[此Graph所需的](https://docs.microsoft.com/graph/permissions-reference)任何 Microsoft 权限。

>| **Permission**  | **委派/应用程序 (的权限类型)** | **是否收集数据？收集它的理由？** | **是否存储数据？存储它的理由？** | **Azure AD应用 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | delegated | 对于日历自动程序，我们将存储用户的忙/闲时间，以便查找多个用户的空闲时间。  | 我们阅读并比较忙/闲时间并安排会议。 | [adef9811-448f-4dd5-88d9-68734050fe58](https://docs.microsoft.com/microsoft-365-app-certification/azure/adef9811-448f-4dd5-88d9-68734050fe58) |
>| Contacts.Read | delegated | 是的，我们存储联系人信息。 | 导入和同步联系人。 | [adef9811-448f-4dd5-88d9-68734050fe58](https://docs.microsoft.com/microsoft-365-app-certification/azure/adef9811-448f-4dd5-88d9-68734050fe58) |
>| User.Read | delegated | 是 | 基本个人资料信息。 | [adef9811-448f-4dd5-88d9-68734050fe58](https://docs.microsoft.com/microsoft-365-app-certification/azure/adef9811-448f-4dd5-88d9-68734050fe58) |
>| User.ReadBasic.All | delegated | 否 | 用于查看同事的配置文件、比较空闲时间以及安排会议室。 | [adef9811-448f-4dd5-88d9-68734050fe58](https://docs.microsoft.com/microsoft-365-app-certification/azure/adef9811-448f-4dd5-88d9-68734050fe58) |
>| offline_access | delegated | 是，脱机用户的忙/闲时间。 | 当用户Graph使用我们网站时，调用" 呼叫"。 | [adef9811-448f-4dd5-88d9-68734050fe58](https://docs.microsoft.com/microsoft-365-app-certification/azure/adef9811-448f-4dd5-88d9-68734050fe58) |
>| openid | delegated | 否 | Office 365SSO。 | [adef9811-448f-4dd5-88d9-68734050fe58](https://docs.microsoft.com/microsoft-365-app-certification/azure/adef9811-448f-4dd5-88d9-68734050fe58) |


#### <a name="non-microsoft-services-used"></a>非Microsoft 服务使用

如果应用与非 Microsoft 服务传输或共享组织数据，请列出应用使用的非 Microsoft 服务、传输哪些数据，并包括应用需要传输此信息的原因的理由。

>不Microsoft 服务非活动。



#### <a name="telemetry-data"></a>遥测数据

OII (组织) 或 EUII (最终用户可识别) 是否显示在此应用程序的遥测或日志中？ 如果是，请描述存储哪些数据以及保留和删除策略是什么？

>是的，我们会记录用于将许可证购买连接到 Commercial Appsource 的电子邮件地址。 我们提供了从日志中删除此信息的能力。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作伙伴存储的数据的组织控制

描述组织的管理员如何控制他们在合作伙伴系统中的信息？例如删除、保留、审核、存档、最终用户策略等。

>只有开发人员可以访问我们的日志。 我们强制使用 2FA 访问所有开发平台。

#### <a name="human-review-of-organizational-information"></a>组织信息的人工审阅

是否涉及人员查看或分析任何组织可识别信息 (OII) 收集或存储的数据？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

下面将显示[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目录中的信息。

<iframe height='1020' title='Microsoft Cloud App Security信息' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/20445' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/20445" target="_blank">在新建选项卡中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>标识信息

批准联系人已提供有关此应用如何处理身份验证、授权、应用程序注册最佳做法和其他标识条件的信息。

| **Information** | **响应** |
|:----------------|:-------------|
| 是否与 Microsoft 标识平台 (Azure AD) ？  | 是 |
| 您是否已审阅并遵循了 Microsoft 标识平台 集成清单中列出的所有适用最佳做法？  | 是 |
| 你的应用是否使用 MSAL (Microsoft 身份验证库) 进行身份验证？ | 是 |
| 你的应用是否支持条件访问策略？ | 否 |
| 应用是否请求方案最小特权权限？ | 是 |
| 应用的静态注册权限是否准确反映应用将动态和增量请求的权限？ | 是 |
| 你的应用是否支持多租户？ | 是 |
| 你的应用是否具有机密客户端？ | 否 |
| 你是否拥有为应用注册的所有 (统一) URI？ | 是 |
| 你的应用是否公开任何 Web API？ | 否 |
| 你的应用是否使用预览 API？ | 否 |
| 你的应用是否使用已弃用 API？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
