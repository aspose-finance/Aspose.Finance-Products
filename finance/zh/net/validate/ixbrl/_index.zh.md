---
title: 通过 C# 验证 iXBRL 文件
description: iXBRL 文件验证的示例代码。使用 API 示例代码验证基于 .NET 的应用程序中的批处理 iXBRL 文件。 
url: /zh/net/validate/ixbrl/
family: finance
platformtag: net
feature: validate
informat: iXBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 C# 验证 iXBRL 个文件" h2="无需安装 Microsoft Office 或任何其他软件即可验证 iXBRL 格式的财务报告。" >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="如何验证 iXBRL 文件" %}}

按照代码片段中的步骤或根据您的应用程序需要对其进行增强，以验证可扩展的业务报告语言 iXBRL 文档。确保在您的应用程序中有验证要求。

1. 使用加载 iXBRL 文件 [InlineXbrlDocument 类](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) 实例。1. 检查加载文件的有效性，使其必须与 [iXBRL 规范](http://www.xbrl.org/specification/inlinexbrl-part1/rec-2013-11-18/inlinexbrl-part1-rec-2013-11-18.html)1. 利用 [证实（）](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument/methods/validate) 文件有效性的方法。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="验证要求" %}}
要继续验证 iXBRL 文档，.NET Finance API 是要包含在应用程序中的主要要求。 
- 通过命令行将其安装为 ```nuget install Aspose.Finance``` 或通过 Visual Studio 的包管理器控制台使用 ```Install-Package Aspose.Finance``` 进行安装。
- 或者，从 ZIP 文件中获取离线 MSI 安装程序或 DLL [下载](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="用于验证 iXBRL 个文件的 C# 代码" offSpacer="" %}}

{{< gist "aspose-com-gists" "1272da1f804f8cef122600269db09fbb" "validate-ixbrl-file.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="其他验证选项" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/validate/xbrl/" name="XBRL" description="可扩展的业务报告语言" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}