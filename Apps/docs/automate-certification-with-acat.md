---
title: 使用适用于Microsoft 365的应用合规性自动化工具自动执行Microsoft 365认证
description: 使用应用合规性自动化工具Microsoft 365 (ACAT) 自动执行Microsoft 365认证。
author: yjin81
ms.author: yajin1
manager: zhshang
ms.service: certification
ms.topic: how-to
ms.date: 04/13/2022
ms.custom: template-how-to
ms.openlocfilehash: b708f68ed5717d08b321f02f3ba09989a77fdf17
ms.sourcegitcommit: e639149031755df8cd50c03341b6507146cc48b0
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 06/01/2022
ms.locfileid: "65793019"
---
# <a name="automate-microsoft-365-certification-with-app-compliance-automation-tool-for-microsoft-365"></a>使用适用于Microsoft 365的应用合规性自动化工具自动执行Microsoft 365认证

适用于 Microsoft 365 (ACAT 的应用合规性自动化工具) 与Microsoft 365应用符合性计划协作，以满足Microsoft 365认证所需的一些控制。 本文将帮助你开始使用 ACAT，并将符合性评估与Microsoft 365认证配合使用。

> [!IMPORTANT]
> ACAT 目前为专用预览版。 如果要加入专用预览版计划，请 [在此](https://aka.ms/acat/private/signup)处注册。

> [!NOTE]
> 若要向 ACAT 专用预览版提供反馈，可以从此 [表单](https://aka.ms/acat/feedback)开始。 一旦我们收到消息，ACAT 产品团队将尽快跟进你。 

## <a name="create-your-first-compliance-report-to-onboard-acat"></a>创建要载入 ACAT 的第一个符合性报告

ACAT 使你能够专注于应用程序的符合性或应用程序 (的特定环境，例如生产、暂存等) 。 它允许创建 **符合性报告** ，可在其中根据应用程序的云基础结构或应用程序的特定环境定义合规性边界。

> [!IMPORTANT]
> 由于 ACAT 是专用预览版，因此无法直接在Azure 门户中搜索它。 请注册 [ACAT 专用预览版计划](https://aka.ms/acat/private/signup) ，并从支持团队获取访问权限。

- 在Azure 门户中搜索并启动 ***应用合规性自动化工具以Microsoft 365***。
- 从左侧转到 ***“报*** 表”。

:::image type="complex" source="../media/ACAT/getstarted-create-report-inline.png" lightbox="../media/ACAT/getstarted-create-report.png" alt-text="创建符合性报告":::
   转到“报表”以创建新的符合性报告 :::image-end:::

- 选择 ***“创建新报表*** ”，开始使用适当的配置创建第一个符合性报表。 
    - **基本信息**
        - **报表名称**：符合性报告的名称是必需的，不能在租户中重复。 它可能是数字、字母表和下划线的组合。 建议对符合性报告使用有意义的名称，例如，指示特定的应用程序或环境。
        - **触发时间**：ACAT 将每天为合规性报告生成符合性评估。 此配置用于指定何时应触发生成。 
        - **选择订阅**：在专用预览版中，ACAT 允许通过在特定订阅中选择 Azure 资源来定义合规性报告的范围。 可以根据云基础结构选择适当的订阅。 如果应用程序的订阅不在列表中，则需要向管理员请求权限。 
        - **选择资源**：指定订阅后，根据云基础结构选择适当的资源。 默认情况下，将自动选择所有资源。 还可以按筛选器 (（例如资源组、标记等）搜索资源) ，然后选择资源。 
    
    :::image type="complex" source="../media/ACAT/getstarted-report-config-basic-inline.png" lightbox="../media/ACAT/getstarted-report-config-basic.png" alt-text="基本配置":::
       符合性报告的基本配置 :::image-end:::

    - **Microsoft 365认证**：创建过程中，Microsoft 365认证配置是可选的。  以后开始发布应用后，可以对其进行配置。
        - **产品/服务 GUID**：产品/服务 GUID 是 [Microsoft 合作伙伴网络](https://partner.microsoft.com/dashboard)中市场产品/服务的唯一标识符。 选择 *“了解详细* 信息”，获取有关如何获取唯一标识符的分步说明。
    
    :::image type="complex" source="../media/ACAT/getstarted-report-config-m365-inline.png" lightbox="../media/ACAT/getstarted-report-config-m365.png" alt-text="Microsoft 365认证配置":::
       有关Microsoft 365认证的配置:::image-end:::

确认配置并创建符合性报告后，ACAT 会自动从以下源收集符合性相关数据。 

- 为订阅启用[Microsoft Defender for Cloud](https://azure.microsoft.com/services/defender-for-cloud/) (免费层) 。 
- 为订阅启用一些自定义策略。 

> [!NOTE]
> 如果创建成功，ACAT 将从第二天开始收集合规性报告并生成合规性评估。 

## <a name="audit-the-compliance-assessments-with-your-compliance-report"></a>使用合规性报告审核合规性评估

借助 ACAT，可以了解合规性报告的运行时状态，并轻松审核合规性评估。 

- 从左侧转到 ***“报*** 表”。 可以获取现有合规性报告的简要摘要。
    - **运行时状态**：运行时状态指示 ACAT 在上一代中是否仍正确管理合规性报告。 运行时状态有三种状态。 
        - **活动**：合规性报告持续且成功运行。 
        - **失败**：ACAT 未能为上一代的此合规性报告生成合规性评估。 此状态可能由于多种原因而发生，例如，订阅中的配置不正确，无法阻止路由到 ACAT 的符合性数据、ACAT 发生系统故障或中断等。 
        - **禁用**：此符合性报告已禁用 (手动暂停) 。 此功能未在专用预览版中启用。 
    - **上次触发时间** 和 **下一次触发时间**：ACAT 将每天生成合规性报告的符合性评估。 *上次触发时间* 指示最后一代触发的时间， *下一个触发器时间* 指示下一代的触发时间。 
    - **Microsoft 365认证**：了解Microsoft 365认证控件的合规性报告的状态。 Microsoft 365认证符合性状态的三种状态包括：
        - **已通过**：完全自动化的Microsoft 365认证控件不会失败。
        - **失败**：检测到完全自动化Microsoft 365认证控制的客户责任失败。
        - **手动**：此状态包括两种类型的控件： *部分自动手动控件* （由 ACAT 部分自动化，仍需要一些手动收集合规性证据的努力）和 *手动控制* （需要充分手动收集合规性证据）。 ACAT 自动执行部分客户对部分自动化控件的责任。 可以使用它的符合性状态进行参考，但不能将其直接用于Microsoft 365认证审核。
    
    :::image type="complex" source="../media/ACAT/getstarted-report-list-inline.png" lightbox="../media/ACAT/getstarted-report-list.png" alt-text="合规性报告列表":::
       现有符合性报告的列表。
    :::image-end:::

除了了解现有合规性报告的高级摘要外，还可以在 ACAT 中审核团队的合规性评估详细信息。 单击报表名称，获取特定合规性报表的符合性评估详细信息。 ACAT 将显示如下所示的详细信息。

- **设置**：可以使用设置更改合规性报 *表* 的配置。 在专用预览版中，可以更改与认证相关的Microsoft 365配置。 
- **下载报表**：ACAT 允许将符合性报告的评估下载为 csv 文件，其格式可与合作伙伴共享以进行协作。
    - **云基础结构清单**：此文件包含此符合性报告的资源详细信息。 它可用于描述应用程序的云清单。 
    - **Microsoft 365认证合规性评估**：此文件包括从认证控制Microsoft 365视图中对合规性报告的符合性评估。 

:::image type="complex" source="../media/ACAT/getstarted-report-detail-toolbar-inline.png" lightbox="../media/ACAT/getstarted-report-detail-toolbar.png" alt-text="合规性报表工具栏":::
    符合性报表的工具栏。
:::image-end:::

- **概要**：本部分指示符合性报告的状态和配置。 

:::image type="complex" source="../media/ACAT/getstarted-report-detail-essential-inline.png" lightbox="../media/ACAT/getstarted-report-detail-essential.png" alt-text="合规性报告基本信息":::
    合规性报表的要点。
:::image-end:::

- **评估结果**
    - Microsoft 365认证控件的符合性状态分为五个类别。 
        - **已通过**：完全自动化的Microsoft 365认证控件不会失败。
        - **失败**：检测到完全自动化Microsoft 365认证控制的客户责任失败。
        - **通过 - 需要其他证据**：部分自动化Microsoft 365认证控制不会失败。 仍需手动收集控件的其他证据。
        - **失败 - 需要其他证据**：检测到部分自动化Microsoft 365认证控制的客户责任失败。
        - **手动控制**：ACAT 不会自动执行任何客户对Microsoft 365认证控制的责任。 
    - 合规性评估由Microsoft 365认证控制系列和控制组织。 
        - 通过单击控件名称，详细了解合规性控制以及如何收集手动控制的符合性证据。 
        - 扩展完全自动化控件和部分自动化控件时，可以了解客户负责该控件的更多合规性详细信息。 
        - 对于每个客户责任，还可以通过单击操作按钮来发现相关资源的符合性状态以及故障资源的修正步骤。 
            - **不正常的资源**：需要跟进修正步骤来修复不正常的资源。 
            - **不适用的资源**：需要跟进 N/A 原因来设置资源，然后 ACAT 可以收集资源的符合性评估。

:::image type="complex" source="../media/ACAT/getstarted-report-detail-assessment-inline.png" lightbox="../media/ACAT/getstarted-report-detail-assessment.png" alt-text="合规性报告评估":::
    合规性报告的符合性评估。
:::image-end:::

## <a name="use-your-first-compliance-report-with-microsoft-r365-certification-audit"></a>将第一个合规性报告与 Microsoft r365 认证审核配合使用

在将合规性报告与Microsoft 365认证配合使用之前，需要将产品/服务 GUID 配置为将合规性报告与市场产品/服务相关联。 有两个选项： 

- 在合规性报告的创建过程中，在 *Microsoft 365认证* 选项卡中配置产品/服务 GUID。 
- 如果已创建合规性报告，请转到此合规性报告 *的设置* 来配置产品/服务 GUID。

配置产品/服务 GUID 后，请转到 [Microsoft 合作伙伴网络](https://partner.microsoft.com/dashboard) 以启动应用符合性。 *初始文档* 是Microsoft 365认证的第一阶段。 在此阶段中，如果针对是否使用 ACAT 的问题选择“ *是* ”，则可以选择此审核的正确合规性报告。 Microsoft 365认证将自动将完全自动化控件的符合性评估提交给审核员，从而节省时间和精力。 

## <a name="get-high-level-overview-of-your-compliance-reports"></a>获取合规性报告的高级概述 

***概述使*** 你更好地了解合规性报告的高级状态。 

- **合规性报告运行时状态**：此概述将提供符合性报告的运行时状态统计信息。
    - **活动**：合规性报告持续且成功运行。 
    - **失败**：ACAT 未能为上一代中的此合规性报告生成合规性评估。 此状态可能由于多种原因而发生，例如，订阅中的配置不正确，无法阻止路由到 ACAT 的符合性数据、ACAT 发生系统故障或中断等。 
    - **禁用**：此符合性报告已禁用 (手动暂停) 。 此功能未在专用预览版中启用。 

:::image type="complex" source="../media/ACAT/getstarted-overview-runtime-inline.png" lightbox="../media/ACAT/getstarted-overview-runtime.png" alt-text="运行时状态概述":::
    合规性报告运行时状态概述。
:::image-end:::

- **活动法规合规性报告**：此概述将为你提供每个 *活动* 合规性报告的合规性结果统计信息。
    - **已通过**：完全自动化的Microsoft 365认证控件不会失败。
    - **失败**：检测到完全自动化Microsoft 365认证控制的客户责任失败。
    - **手动**：此状态包括两种类型的控件： *部分自动手动控件* （由 ACAT 部分自动化，仍需要一些手动收集合规性证据的努力）和 *手动控制* （需要充分手动收集合规性证据）。 ACAT 自动执行部分客户对部分自动化控件的责任。 可以使用它的符合性状态进行参考，但不能将其直接用于Microsoft 365认证审核。

:::image type="complex" source="../media/ACAT/getstarted-overview-compliance-inline.png" lightbox="../media/ACAT/getstarted-overview-compliance.png" alt-text="合规性状态概述":::
    活动合规性报告的符合性状态概述。
:::image-end:::

## <a name="troubleshooting"></a>疑难解答 

### <a name="why-is-the-compliance-report-created-failed-due-to-authorization-error"></a>为什么创建的符合性报告因授权错误而失败？ 

创建合规性报表时，ACAT 会为订阅设置环境以自动收集符合性数据，此操作需要订阅的特定权限。 可以检查订阅权限，如下所示。 

- 在 [Azure 门户](https://portal.azure.com/?microsoft_azure_appcomplianceautomation_assettypeoptions=%7B%22AppComplianceAutomation%22:%7B%22options%22:%22%22%7D%7D)中搜索和启动 **订阅**。
- 转到要用于创建符合性报告的订阅。 
- 转到 **访问控件 (左侧的 IAM)** 。 
- 选择 **“查看我的访问权限** ”以检查你的权限。
    - 如果组织使用 [Azure 内置角色](/azure/role-based-access-control/built-in-roles)，则角色分配应至少包括以下角色之一：
        - [资源策略参与者](/azure/role-based-access-control/built-in-roles#resource-policy-contributor)[和安全管理员](/azure/role-based-access-control/built-in-roles#security-admin)
        - 具有更高权限的其他角色分配 (例如 [“所有者](/azure/role-based-access-control/built-in-roles#owner)”等) 

### <a name="how-to-report-an-acat-issue-or-warning"></a>如何报告 ACAT 问题或警告？ 

当你在 ACAT 中遇到问题并想要联系 [ACAT 专用预览版计划](mailto:acatprivatepreview@microsoft.com) 寻求帮助时，我们需要你的帮助来收集证据，以便更好地了解你的方案。

- 获取 ACAT 错误或警告的详细信息
    - 转到 [Azure 门户](https://portal.azure.com/?microsoft_azure_appcomplianceautomation_assettypeoptions=%7B%22AppComplianceAutomation%22:%7B%22options%22:%22%22%7D%7D)上 **的通知**。
    - 在 **活动日志中选择更多事件** 
    
    
    
    - 切换到 **目录活动** 
    - 正确更改 **Timespan** 并将 **租户资源提供程序** 设置为 *Microsoft.AppComplianceAutomation* ，以筛选出活动日志中的 ACAT 错误或警告。 
    
    :::image type="complex" source="../media/ACAT/getstarted-troubleshoot-log-settings.png" alt-text="活动日志":::
        在活动日志中查找 ACAT 日志。
    :::image-end:::

    - 找出 ACAT 错误或警告，选择以获取详细信息并将详细信息另存为文件。
    
- 检查订阅是否由 ACAT 正确设置。 
    - 在 [Azure 门户](https://portal.azure.com/?microsoft_azure_appcomplianceautomation_assettypeoptions=%7B%22AppComplianceAutomation%22:%7B%22options%22:%22%22%7D%7D)中搜索和启动 **订阅**。
    - 转到要用于创建符合性报告的订阅。 
    - 选择 **“资源提供程序** ”以检查这些提供程序的状态是否 *已注册*。
        - Microsoft.Security
        - Microsoft.ResourceGraph
    - 返回 [Azure 门户，](https://portal.azure.com/?microsoft_azure_appcomplianceautomation_assettypeoptions=%7B%22AppComplianceAutomation%22:%7B%22options%22:%22%22%7D%7D)并启动 **Resource Graph资源管理器**。
    - 选择 **“新建查询**”
    - 运行此查询以检查策略分配，并将结果下载为 CSV。 

    ```kusto
    resourcecontainers
    | where type == "microsoft.resources/subscriptions/resourcegroups"
    | where name contains "acat"
    ```

    - 运行此查询以检查自动化并下载结果作为 CSV。

    ```kusto
    resources
    | where type == "microsoft.security/automations"
    | where name contains "acat"
    ```

    - 运行此查询以检查评估并下载结果作为 CSV。 需要将占位符 ***your-subscriptionId*** 替换为要查询的特定订阅。

    ```kusto
    SecurityResources
      | where type == 'microsoft.security/assessments'
      | where subscriptionId == "your-subscriptionId"
      | extend metadata=properties.metadata,
      status=properties.status,
      links=properties.links,
      displayName=properties.displayName,
      resourceDetails=properties.resourceDetails,
      description=properties.metadata.description
      | project type, id, name, description, metadata, status, resourceDetails, links, displayName
    ```