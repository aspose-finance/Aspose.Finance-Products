---
title: 通过 C# 查看 XBRL 文件
description: XBRL 文件查看的示例代码。使用 API 示例代码查看基于 .NET 的应用程序中的批处理 XBRL 文件。 
url: /zh/net/view/xbrl/
family: finance
platformtag: net
feature: view
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 C# 查看 XBRL 个文件" h2="无需安装 Microsoft Office 或任何其他软件即可查看 XBRL 格式的财务报告。" >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="如何查看 XBRL 文件" %}}

按照代码片段中的步骤操作或根据您的应用程序需要对其进行增强，以读取可扩展的业务报告语言 XBRL 文件。确保在您的应用程序中有阅读要求。

1. 创造 [XbrlDocument 类](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) 实例。2. 将有效 XBRL 文件的名称作为参数传递。
3. 要获取文件的内部详细信息，请使用相关类，例如 [SchemaRefCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemarefcollection), [语境](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/context), [单元](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/unit) 
4. 显示这些信息

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="阅读要求" %}}
要继续查看 XBRL 文档，.NET Finance API 是包含在应用程序中的主要要求。 
- 通过命令行将其安装为 ```nuget install Aspose.Finance``` 或通过 Visual Studio 的包管理器控制台使用 ```Install-Package Aspose.Finance``` 进行安装。
- 或者，从 ZIP 文件中获取离线 MSI 安装程序或 DLL [下载](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# 代码读取 XBRL 个文件" offSpacer="" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "read-xbrl-file.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="其他查看选项" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/view/ixbrl/" name="iXBRL" description="内联可扩展业务报告语言" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}