---
title: 通过 C# 创建 OFX 响应文件
description: OFX 响应文件创建的示例代码。使用 API 示例代码在基于 .NET 的应用程序中生成批处理 OFX 响应文件。 
url: /zh/net/create/ofx-response/
family: finance
platformtag: net
feature: create
informat: OFX Response
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 C# 创建 OFX 响应文件" h2="OFX 无需安装 Microsoft Office 或任何其他软件即可创建响应文件。" >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="如何创建 OFX 响应文件" %}}

在您的应用程序中具有创建要求后，按照代码片段中的步骤或根据您的应用程序需要对其进行增强。

1. 创造 [OfxResponseDocument 类](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) 目的。1. 使用 API 提供的不同类分配相关属性，例如 [登录响应](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse),  [语句事务响应](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse), [声明交易](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction)1. 对 xml 和 sgml 文件分别使用 ofxVersion V2x 或 V1x [Ofx版本枚举](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) 作为 Save 方法中的参数。1. 调用 [保存方法](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument/methods/save) 通过提供目标文件和 ofxVersion。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="创作要求" %}}
要继续创建 OFX 响应文件，.NET Finance API 是包含在报告生成应用程序中的主要要求。 
- 通过命令行将其安装为 ```nuget install Aspose.Finance``` 或通过 Visual Studio 的包管理器控制台使用 ```Install-Package Aspose.Finance``` 进行安装。
- 或者，从 ZIP 文件中获取离线 MSI 安装程序或 DLL [下载](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="OFX 响应文件创建的 C# 代码" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="其他创建选项" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="OFX 请求文件" description="1.03 或 2.2 格式" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/xbrl/" name="XBRL 文件" description="可扩展的业务报告语言" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}