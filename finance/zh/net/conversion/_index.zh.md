---
title: 通过 .NET 转换财务报告
url: /zh/net/conversion/
description:  C# 代码通过 .NET 库转换 XBRL、iXBRL（内联 xbrl）和 OFX 文件格式的财务报告。
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 C# 转换财务报告文件" h2="在基于 .NET 的应用程序中，财务报告格式转换包括从 1.03 到 2.2 格式的 XBRL、iXBRL 和 OFX 文件。" >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) 是一个功能丰富、可扩展且易于使用的 API。开发人员可以使用以下方法轻松验证 XBRL 实例、链接库和分类模式 [验证（）方法](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) 必须符合规范中规定的语法要求。此外，他们可以读取 XBRL、iXBRL 格式以及从头开始创建 XBRL 实例。此外，他们可以将 XBRL 格式**转换为 iXBRL 和 Microsoft Excel XLSX 文件。 API 还支持创建开放金融交换 (OFX) 格式请求/响应，并将 OFX 文件请求/响应从 1.03 格式转换为 2.2 格式。

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="转换 OFX 响应和请求文件" %}}

API 通过提供两个类来支持创建 OFX 请求和响应文件。 [Ofx请求文件](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) 用于创建和加载 1.03 和 2.2 格式的 OFX 请求文件，以及 [Ofx响应文件](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) 用于 1.03 和 2.2 格式的 OFX 响应文件。此外， [Ofx版本枚举](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) 枚举具有成员 V1x 即 1.x 版本、sgml 文件格式和 V2x 2.x 版本、xml 文件格式。调用OfxRequestDocument 类或OfxResponseDocument 类的Save 方法后，开发者可以轻松地将1.03 的sgml 文件转换为2.2 的xml 格式。


{{% blocks/products/pf/feature-page-code h3="C# 转换 OFX 响应文件的代码" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-response-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# 用于转换 OFX 请求文件的代码" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-request-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="XBRL 财务报告转换" %}}

API 支持将 XBRL 文件转换为 iXBRL 和 Microsoft® Excel XLSX 格式。转换过程很简单，首先通过加载文件 [XbrlDocument 类](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument).使用 [保存选项类](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions) 为了 [保存格式](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions/properties/saveformat), 用作 XbrlDocument 类的 Save 方法中的参数。要保存在 iXBLR 文件中， [保存格式.IXBRL](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveformat) 将使用并导出为 XLSX 格式，将使用 SaveFormat.XLSX。

{{% blocks/products/pf/feature-page-code h3="C# 将 XBRL 导出到 iXBRL 的代码" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-ixbrl.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="XBRL 到 XLSX 转换的 C# 代码" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-xlsx.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xbrl-to-ixbrl xbrl-to-xlsx" >}}