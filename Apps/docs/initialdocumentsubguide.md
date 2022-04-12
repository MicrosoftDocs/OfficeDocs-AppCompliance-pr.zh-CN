---
ms.author: oromalle
title: Microsoft 365认证 - 初始文档提交指南
author: orionomalley
manager: tonybal
description: 初始文档提交是认证的预评估阶段的一部分。
keywords: 应用认证团队Microsoft 365安全合规性 m365 初始文档提交
ms.topic: conceptual
ms.service: certification
ms.openlocfilehash: 23c3cf7a64025bb7269adb35175e8d87bc64224e
ms.sourcegitcommit: ec1d4f7013722fe672830e3664b0fb8b0f33bd37
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/12/2022
ms.locfileid: "64784501"
---
# <a name="microsoft-365-ceritification---initial-document-submission-guide"></a>Microsoft 365证书化 - 初始文档提交指南

初始文档提交是认证的预评估阶段的一部分。 提供的信息将为认证分析师提供确定评估范围内哪些控件和系统组件所需的背景。 本文档仅用作初始文档提交预期的示例。 提供的文档将因解决方案的架构、实现和管理方式而异。

## <a name="what-is-the-hosting-environment-or-service-model-used-to-run-your-app"></a>用于运行应用的托管环境或服务模型是什么？
- 基础结构即服务 (IaaS) 是云服务模型，云服务提供商托管基础结构组件，但 ISV 仍负责单独部署和管理组件，例如虚拟机/操作系统、数据存储和网络组件。 例如，Azure 虚拟机和 Azure 磁盘存储。
- 平台即服务 (PaaS) 是云服务模型，基础结构组件由云服务提供商管理。 ISV 仅负责部署自己的应用程序和服务。 例如，Azure 应用服务、Azure Functions和Azure CDN。
- 在此上下文中托管的 ISV 意味着不使用云服务提供商。 ISV 在本地独立管理自己的服务器、磁盘和网络。
- 此上下文中的混合表示使用了上述多个模型之一。 例如，某些 ISV 可能选择使用 IaaS 服务和 PaaS 服务的混合来支持其应用，或者它们可能具有一些本地 ISV 托管组件，并将其他组件外包给云服务提供商。 如果使用其他服务模型之一，请选择混合。

## <a name="penetration-test-report"></a>渗透测试报表

请包括完整的渗透测试报告，其日期表示在过去 12 个月内已完成。 
-   此报表必须通过手动渗透测试生成，不能是自动扫描/测试工具的输出。
-   此报表必须包含支持应用/添加部署的环境以及支持应用/外接程序操作的任何其他环境。


## <a name="system-component-inventory"></a>系统组件清单

支持基础结构使用的所有系统组件的最新发明。 这将用于帮助在执行评估阶段时进行采样。 如果环境包括 PaaS，如果可以提供所使用的所有 PaaS 服务的详细信息，则会很有用。

**注意：** IaaS/PaaS 将没有任何硬件处于 ISV 控制之下。  在这种情况下，请提供所有虚拟资源的列表或屏幕截图。

**示例：**

|资产名称|资产类型|说明|制造商|模型|
|---|---|---|---|---|
|D212|Windows计算机|虚拟机|不适用|不适用|
|LT101|便携式计算机|工作站|Microsoft|Surface 3|
|C2938|开关|开关|不适用|不适用|
|LXM2|Linux 计算机|测试计算机|不适用|不适用|


## <a name="software-inventory"></a>软件清单

所有软件资产（包括范围内环境中使用的所有软件以及版本）的最新清单。

**示例：**

|软件|发布者|版本|用途|
|---|---|---|---|
|Windows Server|Microsoft 2016 |内部版本 14393|生产环境的服务器操作系统|
|Linux Ubuntu|不适用|16.04 (Xenial) |在 DMZ 中使用的服务器操作系统。|
|ESXi|Vmware|6.5.0 (生成13004031) |用于支持虚拟服务器。|
|Mysql (Windows) |不适用|8.0.2.1|用于存储聊天历史记录的数据库服务器。|
|Tomcat|Apache|7.0.92|客户门户。|
|IIS|Microsoft|10.0|支持 API。|


## <a name="third-party-dependencies"></a>第三方依赖项

列出应用/加载项与当前正在运行的版本一起使用的所有依赖项的文档。

**示例：**

|Web 依赖项|正在使用的当前版本|
|----|----|
|Jquery|3.5.1|
|React|16.13.1|
|引导|4.5.2|
|Express|4.17.1|
|Angular|10.0.14|
|AngularJS|1.8.0|


## <a name="public-ip-addresses"></a>公共 IP 地址

详细介绍支持基础结构使用的所有公共 IP 地址和 URL。 这必须包括分配给环境的完整可路由 IP 范围，除非已实施足够的分段以拆分使用范围 (需要充分的分段证据) 。

**示例：**

|URL|IP 地址|
|-|-|
|https://portal.contoso.com |40.113.200.201 |
|https://filesapi.contoso.com|40.113.200.201|
|https://customerapi.contoso.com|40.113.200.202|
|https://bot.contoso.com|40.113.200.202|
|N/a (Jump Server) |40.113.200.200|


## <a name="resource-endpoints"></a>资源终结点

API 名称终结点地址 Contoso 客户 API https://customerapi.contoso.com Contoso 机器人服务 https://bot.contoso.com Contoso 文件 APIhttps://filesapi.contoso.com

应用使用的所有 API 终结点（包括内部开发的终结点和外部资源终结点）的完整列表。 若要帮助了解环境范围，请在环境中提供 API 终结点位置。

**示例：**

|API 名称|  终结点地址|
|-|-|
|Contoso 客户 API|  https://customerapi.contoso.com|
|Contoso 机器人服务|   https://bot.contoso.com|
|Contoso 文件 API| https://filesapi.contoso.com|
|Microsoft Graph| https://graph.microsoft.com/v1.0/|


## <a name="architectural-diagram"></a>体系结构图

一个逻辑体系结构图，表示应用/外接程序的支持基础结构的高级概述。 这必须包括支持应用/外接程序的所有托管环境和支持基础结构。 此关系图必须描述环境中所有不同的支持系统组件，以帮助认证分析师了解范围内的系统，并帮助确定采样。 另请指示使用的托管环境类型;ISV 托管、IaaS、PaaS 或混合。 在使用 PaaS 的位置，请指示用于在环境中提供支持服务的各种 PaaS 服务。

![体系结构图](../media/Architecturaldiagram.png)

## <a name="data-flow-diagram"></a>数据流图

Flow关系图，详细说明以下内容：
-   数据流向和流出应用/加载项 (包括客户数据) 。
-   支持基础结构中的数据流 (适用) 
-   该图突出显示了存储数据的位置和内容、如何将数据传递给外部第三方 (包括第三方) 的详细信息，以及如何通过开放/公共网络和静态传输数据。

![数据流图](../media/Dataflowdiagram.png)



