---
title: 适用于Microsoft 365的应用合规性自动化工具
author: xu-hong
ms.author: hongxu6
manager: zhshang
description: 应用合规性自动化工具Microsoft 365概述
keywords: 应用认证自动化Microsoft 365
ms.topic: conceptual
ms.service: certification
ms.openlocfilehash: debd3c9e2ecd1538446d09f5019ea995260345fd
ms.sourcegitcommit: 785d1c5d829e44e0ad696b85c92be81f549b989e
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 05/17/2022
ms.locfileid: "65433381"
---
# <a name="app-compliance-automation-tool-for-microsoft-365"></a>适用于Microsoft 365的应用合规性自动化工具
在本文中，你将了解用于Microsoft 365 (ACAT) 的应用合规性自动化工具，以及它如何简化合规性和获得Microsoft 365认证。

> [!IMPORTANT]
> ACAT 目前处于 *专用预览版* 中。 若要加入专用预览版计划，请联系 [acatprivatepreview@microsoft.com](mailto:acatprivatepreview@microsoft.com)。

## <a name="what-is-app-compliance-automation-tool-for-microsoft-365"></a>什么是应用合规性自动化工具Microsoft 365
适用于 Microsoft 365 (ACAT) 的应用合规性自动化工具是 Azure 门户中的一项服务，可帮助简化使用Microsoft 365客户数据并通过合作伙伴中心发布的任何应用的合规性过程。 适用于Microsoft 365的应用合规性自动化工具是一种以应用程序为中心的合规性自动化工具，可帮助你更轻松、更方便地完成Microsoft 365认证。 在专用预览版中，ACAT 可用于在 Azure 上运行的应用。

使用此工具，可以快速定义应用程序的符合性边界，自动监视合规性结果，并更轻松地完成合规性审核。 合规性边界是支持应用交付的云基础结构，以及应用可能与之通信的任何后端系统。

除了为Microsoft 365认证提供更快的跟踪外，ACAT 还可以帮助你在各种符合性方案中Microsoft 365应用程序：

- 有关Microsoft 365认证职责的详细视图和修正步骤。
- 自动每日报表可帮助你持续获取符合性结果。
- 可在应用程序生命周期的早期阶段用作指导的安全性和符合性最佳做法。

## <a name="benefits-of-acat"></a>ACAT 的优势
以应用程序为中心的合规性旅程。
- ACAT 每天报告应用程序的云环境的符合性状态，你可以将其与当前的云基础结构符合性策略集成。
- 即使在应用开发阶段，开发人员也可以调用 ACAT。

加快获得Microsoft 365认证的过程。
- ACAT 完全自动执行某些Microsoft 365认证控制。
- Microsoft 正在积极开发一个持续增长的自动化列表。

与Microsoft 365认证工作流的本机集成。
- ACAT 与合作伙伴中心完全集成，以实现Microsoft 365认证目的。

## <a name="concepts-of-acat"></a>ACAT 的概念
### <a name="regulatory-compliance-report"></a>法规合规性报告 
在 ACAT 中，可以通过为其创建合规性报告来审核应用程序的符合性状态。 可以通过指定生成应用程序的 Azure 资源来定义应用程序的符合性边界。 基于不同的开发环境和阶段为一个应用程序创建多个报表。

创建报表后，ACAT 将开始收集预定义触发器时间的符合性数据，然后生成符合性结果作为报表。 同时，ACAT 将继续持续监视合规性报表的符合性更改，直到选择删除报表。

### <a name="microsoft-365-certification-control-results"></a>Microsoft 365认证控制结果
在法规合规性报告中，符合性结果由包含其相应状态的控件组织，这些状态由 ACAT 标记：
- **已通过**：完全自动化的Microsoft 365认证控件不会失败。
- **失败**：检测到完全自动化Microsoft 365认证控制的客户责任失败。
- **通过 - 需要其他证据**：*部分自动化* Microsoft 365认证控制不会失败。
- **失败 - 需要其他证据**：检测到 *部分自动化* Microsoft 365认证控制的客户责任失败。
- **手动控制**：ACAT 不会自动执行任何客户对Microsoft 365认证控制的责任。

### <a name="customer-responsibility"></a>客户责任
有一组客户责任与需要满足的每个控件相关联。 它们由你在以下方面保留：数据、终结点、帐户、访问管理等。

ACAT 收集每个客户责任的数据，并返回其评估结果。 它还提供修正操作，这是我们的指南，可帮助你符合Microsoft 365认证标准。


## <a name="faq"></a>常见问题
### <a name="what-are-manual-controls-and-partially-automated-controls"></a>什么是手动控件和部分自动化控件？
每个合规性控制都与一组客户职责相关联，ACAT 会为其收集合规性数据。 但是，从现在起，并非所有针对Microsoft 365认证的控制都由 ACAT 涵盖 (目前正在努力扩大覆盖范围) 。 对于部分自动化控件，ACAT 会自动执行部分客户责任。 可以使用它的符合性状态进行参考，但不能将其直接用于Microsoft 365认证审核。 对于手动控件，ACAT 当前不会自动执行任何客户责任。

### <a name="i-made-the-suggested-changes-base-on-the-remediation-suggestion-yet-the-control-is-still-failing"></a>我根据修正建议进行了建议的更改， 但控制仍然失败
在采取措施解决故障后，需要等待 ACAT 提取刷新的评估结果以更新控制状态。 评估在预设置的触发器时间每 24 小时运行一次。

### <a name="how-is-the-compliance-report-used-in-the-certification-process"></a>如何在认证过程中使用合规性报告？
ACAT 与[合作伙伴中心](https://partner.microsoft.com/dashboard)无缝集成，以完成Microsoft 365认证过程。 在创建合规性报表期间，可以编辑Microsoft 365认证配置，即产品/服务 GUID。 它在创建过程中是可选的，稍后开始发布应用程序时可以对其进行配置。

## <a name="learn-more"></a>了解详细信息

* [使用 ACAT 入门](https://aka.ms/acat/getstarted)
* [详细了解Microsoft 365认证](https://aka.ms/acat/m365cert)
