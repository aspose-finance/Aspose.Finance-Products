---
title: 通过 .NET 创建财务报告
url: /zh/net/create/
description:  C# 代码用于在 XBRL 中创建财务报告，并通过 .NET 库创建 OFX 请求或响应文件。
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 C# 创建财务报告文件" h2="财务报表格式的创建包括 XBRL 和 OFX 请求或响应文件的1.03或基于 .NET 的应用程序中的2.2格式。" >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) 是一项功能丰富，可扩展且易于使用的财务报告创建和处理 API。开发人员可以轻松地从头开始创建 XBRL 实例，并可以添加架构引用，上下文，单位，项目，脚注链接，角色引用和 
arc角色参考。API 为每个功能提供相关的类，例如为上下文，开发人员可以使用 [上下文周期](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextperiod), [上下文实体](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextentity) 和 [上下文](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/context)。 
此外，API 还支持1.03或2.2格式的开放金融交换 (OFX) 格式请求/响应创建。

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="通过添加项目创建 XBRL 文件" %}}

对于创建 XBRL 文件并将项目添加到文档中，过程是，创建 [XbrlDocument类](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) 实例。通过使用适当的 API 类为项目准备相关设置，例如 [SchemaRef类](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemaref),如上所述的相关上下文类和 [概念类](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/concept)。最后定义和初始化 [项目类别](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/item) 属性以及调用 [保存方法](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) 到 [创建 XBRL](https://products.aspose.com/finance/net/create/xbrl/) 文件到磁盘。

{{% blocks/products/pf/feature-page-code h3="通过添加项目创建 XBRL 文件的 C# 代码" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-item.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="创建 OFX 请求和响应文件" %}}


为了生成 OFX 文件，API 提供了 [OfxRequestDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) 和 [响应文档](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) 类和开发人员可以很容易地 [创建 OFX 请求](https://products.aspose.com/finance/net/create/ofx-request/) 以及1.03和2.2格式的响应文件。为了初始化xrequestdocument属性，API 还提供了其他类，例如 [签名请求](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonrequest), [金融机构](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/financialinstitution) 和 [StatementTransactionRequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionrequest) 类。同样，为了初始化OfxResponseDocument属性，API 提供了支持类，例如 [签名响应](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse),  [StatementTransactionResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse) 和 [报表交易](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction)。以下是两种情况下使用相关适当类的代码片段。

{{% blocks/products/pf/feature-page-code h3="C# 生成 OFX 请求文档的代码" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# 生成 OFX 响应文档的代码" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}