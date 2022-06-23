---
title: 通过 Python 创建 XBRL 文件
description: XBRL 文件创建的示例代码。使用 API 示例代码在基于 Python 的应用程序中生成批处理 XBRL 文件。 
url: /zh/python-net/create/xbrl/
family: finance
platformtag: python
feature: create
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 Python 创建 XBRL 个文件" h2="XBRL 无需安装 Microsoft Office 或任何其他软件即可创建文件。" >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="如何创建 XBRL 文件" %}}

遵循代码片段中的步骤或根据您的应用程序需要对其进行增强，以生成可扩展的业务报告语言 XBRL 文件。确保在您的应用程序中有创建要求。

1. 创建 XbrlDocument 类实例。1. 创建一个新的 XBRL 实例文档 XbrlInstanceCollection 和 XbrlInstance。1. 使用 SchemaRefCollection 添加架构引用1. 根据应用程序性质添加上下文、单元、项目、脚注链接等。1. 通过提供目标文件路径来调用 save 方法。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="创作要求" %}}
要继续生成 XBRL 文档，请确保您具有以下先决条件。 
- 基于 Microsoft Windows 或 Linux 的操作系统。- Python 3.5 或更高版本。- Aspose.Finance 表示您的项目中引用的 Python。{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XBRL 文件创建的 Python 代码" offSpacer="" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-xbrl-file-and-add-schema-reference.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="其他创建选项" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/ofx-request/" name="OFX 请求" description="1.03 或 2.2 格式" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/ofx-response/" name="OFX 响应" description="1.03 或 2.2 格式" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}