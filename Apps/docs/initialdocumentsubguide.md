---
ms.author: oromalle
title: Microsoft 365认证 - 初始文档提交指南
author: orionomalley
description: Microsoft 365认证提交指南粒度视图
keywords: 应用认证团队Microsoft 365合规性 m365 初始文档提交
ms.topic: conceptual
ms.service: certification
ms.openlocfilehash: 0f879ce6b02fb469b0210500e4706d468ccb4011
ms.sourcegitcommit: 3e72bc447a90cd8b0313dab55f6a9374be8ae358
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 12/01/2021
ms.locfileid: "61261674"
---
# <a name="microsoft-365-ceritification---initial-document-submission-guide"></a>Microsoft 365认证 - 初始文档提交指南

初始文档提交是认证预评估阶段的一部分。 提供的信息将为认证分析师提供识别哪些控制措施和系统组件在评估范围内所需的背景知识。 本文档仅用作初始文档提交的预期内容的示例。 您提供的文档因解决方案的构建、实现和管理方式而异。

## <a name="what-is-the-hosting-environment-or-service-model-used-to-run-your-app"></a>用于运行应用的托管环境或服务模型是什么？
- 基础结构即服务 (IaaS) 是云服务提供商托管基础结构组件的云服务模型，但 ISV 仍负责单独部署和管理组件，如虚拟机/操作系统、数据存储和网络组件。 例如，Azure 虚拟机和 Azure 磁盘存储。
- 平台即服务 (PaaS) 是一种云服务模型，其中基础结构组件由云服务提供商管理。 ISV 仅负责部署自己的应用程序和服务。 例如，Azure 应用服务、Azure 函数和 Azure CDN。
- 在此上下文中托管的 ISV 意味着没有使用云服务提供商。 ISV 以物理方式管理自己的服务器、磁盘和独立本地网络。
- 此上下文中的混合意味着使用了上述模型之一。 例如，一些 ISV 可能会选择混合使用 IaaS 服务和 PaaS 服务来支持其应用，或者他们可能有一些本地 ISV 托管组件，并将其他组件外包给云服务提供商。 如果使用其他服务模型之一，请选择"混合"。

## <a name="penetration-test-report"></a>渗透测试报告

请包含完整的渗透测试报告，其中日期表明过去 12 个月内已完成。 
-   此报告必须通过手动渗透测试生成，它不能是自动扫描/测试工具的输出。
-   此报告必须包含支持部署应用/添加的环境，以及支持应用/加载项操作的其他环境。


## <a name="system-component-inventory"></a>系统组件清单

支持基础结构使用的所有系统组件最新设计。 这将用于在执行评估阶段时帮助采样。 如果您的环境包括 PaaS，如果您可以提供使用的所有 PaaS 服务的详细信息，这将非常有用。

**注意：** IaaS/PaaS 将没有任何受 ISV 控制的硬件。  在这种情况下，请提供所有虚拟资源的列表或屏幕截图。

**示例：**

|资产名称|    资产类型| 说明|    制造商|   模型|
|-|-|-|-|-|
|D212|  Windows 计算机|   虚拟机|    不适用| 不适用|
|LT101| 便携式计算机| 工作站|    Microsoft|  Surface 3|
|C2938| 开关| 开关|不适用|不适用|     
|LXM2|  Linux 计算机|  测试计算机|不适用|不适用|       


## <a name="software-inventory"></a>软件清单

所有软件资产（包括范围内环境中使用的所有软件以及版本）的最新版本清单。

**示例：**

|软件|  Publisher|  版本|     用途|
|-|-|-|-|
|Windows Server|    Microsoft 2016 | 内部版本 14393| 生产环境的服务器操作系统|.
|Linux Ubuntu|  不适用|    16.04 (Xenial) | DMZ 中使用的服务器操作系统。|
|ESXi|  VMWare| 6.5.0 (内部13004031) | 用于支持虚拟服务器。|
|Mysql (Windows) |   不适用|    8.0.2.1|    用于存储聊天历史记录的数据库服务器。|
|Tomcat|        Apache| 7.0.92| 客户门户。|
|IIS|   Microsoft|  10.0|   支持 API。|


## <a name="third-party-dependencies"></a>第三方依赖项

列出应用/加载项使用的当前运行版本的所有依赖项的文档。

**示例：**

|Web 依赖项|  当前使用的版本|
|-|-|
|JQuery|    3.5.1|
|React| 16.13.1|
|Bootstrap| 4.5.2|
|Express|   4.17.1|
|Angular|   10.0.14|
|AngularJS| 1.8.0|


## <a name="public-ip-addresses"></a>公用 IP 地址

详细说明支持基础结构使用的所有公用 IP 地址和 URL。 这必须包括分配给环境的完整可路由 IP 范围，除非已实现适当的分段来拆分使用中的范围 (因此需要足够的分段证据) 。

**示例：**

|URL|  IP 地址|
|-|-|
|https://portal.contoso.com |40.113.200.201 |
|https://filesapi.contoso.com|  40.113.200.201|
|https://customerapi.contoso.com|   40.113.200.202|
|https://bot.contoso.com|   40.113.200.202|
|N/A (Jump Server) | 40.113.200.200|


## <a name="resource-endpoints"></a>资源终结点

API 名称终结点地址 Contoso Customer API    https://customerapi.contoso.com Contoso Bot Service https://bot.contoso.com Contoso Files API   https://filesapi.contoso.com

应用使用的所有 API 终结点的完整列表，包括内部开发终结点和外部资源终结点。 若要帮助了解环境范围，请提供环境中 API 终结点位置。

**示例：**

|API 名称|  终结点地址|
|-|-|
|Contoso 客户 API|  https://customerapi.contoso.com|
|Contoso Bot Service|   https://bot.contoso.com|
|Contoso 文件 API| https://filesapi.contoso.com|
|Microsoft Graph| https://graph.microsoft.com/v1.0/|


## <a name="architectural-diagram"></a>体系结构图

逻辑体系结构图，表示应用/加载项支持基础结构的简要概述。 这必须包括所有托管环境和支持应用/外接程序的基础结构。 此图必须描述环境中所有不同的支持系统组件，以帮助认证分析师了解范围内的系统并帮助确定采样。 另请指示使用哪种托管环境类型;ISV 托管、IaaS、PaaS 或混合。 使用 PaaS 时，请指明用于在环境中提供支持服务的各种 PaaS 服务。

![体系结构图](../media/Architecturaldiagram.png)

## <a name="data-flow-diagram"></a>数据Flow图

Flow详述以下内容的图表：
-   数据流入和流出应用/加载项 (包括客户数据) 。
-   如果适用，支持基础结构 (数据流) 
-   这些图表突出显示了存储在何处和存储哪些数据、如何将数据传递给外部第三方 (包括哪些第三方) 以及如何通过开放/公共网络及其余网络传输时保护数据的详细信息。

![数据Flow图](../media/Dataflowdiagram.png)



