---
title: 通过 Python 创建财务报告
url: /zh/python-net/create/
description:  在 XBRL 中创建财务报告的 Python 代码，以及通过 Python 库的 OFX 请求或响应文件。
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 Python 创建财务报告文件" h2="在基于 Python 的应用程序中创建财务报告格式，包括 1.03 或 2.2 格式的 XBRL 和 OFX 请求或响应文件。" >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance 通过 .NET 为 Python](https://products.aspose.com/finance/python-net/) 是一种功能丰富、可扩展且易于使用的财务报告创建和处理API。开发人员可以轻松地从头开始创建 XBRL 实例，还可以添加架构引用、上下文、单元、项目、脚注链接、角色引用和 
arc 角色参考。 API 为每个功能提供相关类，例如上下文，开发者可以使用 ContextPeriod、ContextEntity 和 Context。 
此外，API 还支持 1.03 或 2.2 格式的开放式金融交换 (OFX) 格式请求/响应创建。

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="通过添加项目创建 XBRL 文件" %}}

为了创建XBRL文件并将项目添加到文档中，过程是创建 XbrlDocument 类实例。使用适当的 API 类（如 SchemaRef 类、上述相关上下文类和概念类）为项目准备相关设置。最后定义并初始化 Item 类属性，并调用 save 方法将 XBRL 文件创建到磁盘中。

{{% blocks/products/pf/feature-page-code h3="Python 通过添加项目创建 XBRL 文件的代码" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-xbrl-file-and-add-item.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="创建 OFX 请求和响应文件" %}}


为了生成 OFX 文件，API 提供了 OfxRequestDocument 和 OfxResponseDocument 类，开发人员可以轻松地 [创建 OFX 请求](https://products.aspose.com/finance/python-net/create/ofx-request/) 和 1.03 和 2.2 格式的响应文件。为了初始化 OfxRequestDocument 属性，API 还提供了其他类，例如 SignonRequest、FinancialInstitution 和 StatementTransactionRequest 类。同样，为了初始化 OfxResponseDocument 属性，API 提供了支持类，例如 SignonResponse、StatementTransactionResponse 和 StatementTransaction。下面是使用相关适当类的两种情况的代码片段。

{{% blocks/products/pf/feature-page-code h3="Python 生成代码 OFX 请求文档" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-response-files.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Python 生成 OFX 响应文档的代码" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-response-files.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
{{< /blocks/products/pf/feature-page-wrap >}}