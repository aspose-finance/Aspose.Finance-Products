---
title: 通过 Python 创建 OFX 响应文件
description: OFX 响应文件创建的示例代码。使用 API 示例代码在基于 Python 的应用程序中生成批处理 OFX 响应文件。 
url: /zh/python-net/create/ofx-response/
family: finance
platformtag: python
feature: create
informat: OFX Response
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 Python 创建 OFX 响应文件" h2="OFX 无需安装 Microsoft Office 或任何其他软件即可创建响应文件。" >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="如何创建 OFX 响应文件" %}}

在您的应用程序中具有创建要求后，按照代码片段中的步骤或根据您的应用程序需要对其进行增强。

1. 创建 OfxResponseDocument 类对象。1. 使用 API 提供的不同类分配相关属性，例如 SignonResponse、StatementTransactionResponse、StatementTransaction1. 使用 OfxVersion V2x 或 V1x 分别来自 OfxVersionEnum 的 xml 和 sgml 文件作为保存方法中的参数。1. 通过提供目标文件和ofxVersion来调用save方法。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="创作要求" %}}
要继续创建 OFX 响应文件，请确保您具有以下先决条件。 
- 基于 Microsoft Windows 或 Linux 的操作系统。- Python 3.5 或更高版本。- Aspose.Finance 表示您的项目中引用的 Python。{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="OFX 响应文件创建的 Python 代码" offSpacer="" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-response-files.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="其他创建选项" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/ofx-request/" name="OFX 请求文件" description="1.03 或 2.2 格式" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/xbrl/" name="XBRL 文件" description="可扩展的业务报告语言" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}