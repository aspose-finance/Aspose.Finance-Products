---
title: 通过 C# 创建 iXBRL(inline xbrl) 文件
description: iXBRL（内联 xbrl）文件创建的示例代码。使用 API 示例代码在基于 .NET 的应用程序中生成批处理 iXBRL（内联 xbrl）文件。 
url: /zh/net/create/ixbrl/
family: finance
platformtag: net
feature: create
informat: iXBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 C# 创建 iXBRL(inline xbrl) 文件" h2="iXBRL（内联 xbrl）文件创建，无需安装 Microsoft Office 或任何其他软件。" >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="如何创建iXBRL（内联 xbrl）文件" %}}

按照代码片段中的步骤操作或根据您的应用程序需要对其进行增强，以生成可扩展的业务报告语言 iXBRL（内联 xbrl）文件。确保在您的应用程序中有创建要求。

1. 创造 [InlineXbrlDocument 类](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) 实例。2.构建元素dom树
3. 调用 [保存方法](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline.inlinexbrldocument/save/methods/1) 通过提供目标文件路径。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="创作要求" %}}
要继续生成iXBRL（内联 xbrl）文档，.NET Finance API 是要包含在应用程序中的主要要求。 
- 通过命令行将其安装为 ```nuget install Aspose.Finance``` 或通过 Visual Studio 的包管理器控制台使用 ```Install-Package Aspose.Finance``` 进行安装。
- 或者，从 ZIP 文件中获取离线 MSI 安装程序或 DLL [下载](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XBRL 文件创建的 C# 代码" offSpacer="" %}}

{{< gist "aspose-finance-gists" "e4ec79e68a0658a63611ae321b110a48" "create-ixbrl.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="其他创建选项" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="OFX 请求" description="1.03 或 2.2 格式" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-response/" name="OFX 响应" description="1.03 或 2.2 格式" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}