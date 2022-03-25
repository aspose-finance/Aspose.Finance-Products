---
title: 通过 C# 验证 XBRL 文件
description: XBRL 文件验证的示例代码。使用 API 示例代码验证基于 .NET 的应用程序中的批处理 XBRL 文件。 
url: /zh/net/validate/xbrl/
family: finance
platformtag: net
feature: validate
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 C# 验证 XBRL 文件" h2="以 XBRL 格式验证财务报告，而无需安装Microsoft Office或任何其他软件。" >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="如何验证 XBRL 文件" %}}

按照代码段中的步骤进行操作，或者根据应用程序的需要对其进行增强，以验证可扩展的业务报告语言 XBRL 文档。请确保您的应用程序中有验证要求。

1. 使用加载 XBRL 文件 [XbrlDocument类](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) 实例。1. 检查加载文件的有效性，以便它必须与 [XBRL 规格](http://www.xbrl.org/specification/inlinexbrl-part1/rec-2013-11-18/inlinexbrl-part1-rec-2013-11-18.html)1. 要检查验证，请使用 [验证 ()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) 方法 [XbrlInstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance) 类。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="验证要求" %}}
要继续验证 XBRL 文档，.NET Finance API 是应用程序中包含的主要要求。 
- 通过命令行将其安装为 '''nuget Install Aspose.Finance''' 或通过Visual Studio的软件包管理器控制台安装为 '''install-Package Aspose.Finance'''。
- 或者，从以下位置获取ZIP文件中的脱机MSI安装程序或dll [下载](https://downloads.aspose.com/finance/net)。{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="验证 XBRL 文件的 C# 代码" offSpacer="" %}}

{{< gist "aspose-com-gists" "1272da1f804f8cef122600269db09fbb" "validate-xbrl-instance-file.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="其他验证选项" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/validate/ixbrl/" name="XBRL" description="内联可扩展业务报告语言" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}