---
title: 通过 C# 创建 OFX 响应文件
description: 创建 OFX 响应文件的示例代码。使用 API 示例代码在基于 .NET 的应用程序中生成批处理 OFX 响应文件。 
url: /zh/net/create/ofx-response/
family: finance
platformtag: net
feature: create
informat: OFX Response
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 C# 创建 OFX 响应文件" h2="OFX 无需安装Microsoft Office或任何其他软件即可创建响应文件。" >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="如何创建 OFX 响应文件" %}}

在应用程序中具有创建要求后，请按照代码段中的步骤进行操作，或根据应用程序的需要对其进行增强。

1. 创建 [OfxResponseDocument类](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) 对象。1. 使用 API 提供的不同类分配相关属性，如 [签名响应](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse),  [StatementTransactionResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse), [报表交易](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction)1. 将ofxVersion V2x或V1x分别用于xml和sgml文件 [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) 作为保存方法中的参数。1. 打电话给 [保存方法](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument/methods/save) 通过提供目标文件和ofxVersion。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="创建要求" %}}
要继续创建 OFX 响应文件，.NET Finance API 是包含在报告生成应用程序中的主要要求。 
- 通过命令行将其安装为 '''nuget Install Aspose.Finance''' 或通过Visual Studio的软件包管理器控制台安装为 '''install-Package Aspose.Finance'''。
- 或者，从以下位置获取ZIP文件中的脱机MSI安装程序或dll [下载](https://downloads.aspose.com/finance/net)。{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# 创建响应文件的代码" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="其他创建选项" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="OFX 请求文件" description="1.03或2.2格式" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/xbrl/" name="XBRL 文件" description="可扩展业务报告语言" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}