---
title: 通过 .NET 转换财务报告
url: /zh/net/conversion/
description:  C# 代码，用于通过 .NET 库转换 XBRL 、 iXBRL 和 OFX 文件文件中的财务报告。
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 C# 转换财务报告文件" h2="财务报表格式转换，包括 XBRL 、 iXBRL 和 OFX 文件在基于 .NET 的应用程序中从1.03格式转换为2.2格式。" >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) 是一项功能丰富，可扩展且易于使用的功能 API。开发人员可以使用以下方法轻松验证 XBRL 实例、链接库和分类模式 [validate() 方法](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) 必须符合规范中规定的语法要求。此外，它们可以读取 XBRL，iXBRL 格式以及从头开始创建 XBRL 实例。此外，它们可以将 XBRL 格式 ** 转换为 iXBRL 和Microsoft Excel XLSX文件。API 还支持开放金融交易所 (OFX) 格式请求/响应创建，并将 OFX 文件请求/响应从1.03转换为2.2格式。

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="转换 OFX 响应和请求文件" %}}

API 支持通过提供两个类来创建 OFX 请求和响应文件。 [OfxRequestDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) 用于创建和加载1.03和2.2格式的 OFX 请求文件 [响应文档](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) 对于1.03和2.2格式的 OFX 响应文件。此外， [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) 枚举成员V1x是1.X版本，sgml文件格式和V2x 2.X版本，xml文件格式。调用OfxRequestDocument类或OfxResponseDocument类的Save方法后，开发人员可以轻松地从1.03 sgml文件转换为2.2 xml格式。


{{% blocks/products/pf/feature-page-code h3="C# 转换 OFX 响应文件的代码" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-response-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# 转换 OFX 请求文件的代码" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-request-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="XBRL 财务报告转换" %}}

API 支持将 XBRL 文件转换为 iXBRL 和Microsoft®Excel XLSX格式转换过程很简单，首先通过 [XbrlDocument类](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument)。使用 [保存选项类](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions) 对于 [保存格式](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions/properties/saveformat),用作XbrlDocument类的保存方法中的参数。为了保存在iXBLR文件中， [保存格式。IXBRL](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveformat) 将被使用，并且对于导出为XLSX格式，将使用SaveFormat.XLSX。

{{% blocks/products/pf/feature-page-code h3="将 XBRL 导出到 iXBRL 的 C# 代码" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-ixbrl.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="XBRL 到XLSX转换的 C# 代码" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-xlsx.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xbrl-to-ixbrl xbrl-to-xlsx" >}}