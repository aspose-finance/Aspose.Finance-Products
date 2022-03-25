---
title: 通过 C# 创建 XBRL 文件
description: XBRL 文件创建的示例代码。使用 API 示例代码在基于 .NET 的应用程序中批量生成 XBRL 文件。 
url: /zh/net/create/xbrl/
family: finance
platformtag: net
feature: create
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 C# 创建 XBRL 文件" h2="无需安装Microsoft Office或任何其他软件即可创建 XBRL 文件。" >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="如何创建 XBRL 文件" %}}

按照代码段中的步骤进行操作，或根据应用程序的需要对其进行增强，以生成可扩展的业务报告语言 XBRL 文件。确保您的应用程序中有创建要求。

1. 创建 [XbrlDocument类](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) 实例。1. 创建新的 XBRL 实例文档 [XbrlInstanceCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) 和 [XbrlInstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance)。1. 使用添加架构引用 [SchemaRefCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemarefcollection)1. 根据应用程序性质添加上下文、单位、项目、脚注链接等。1. 打电话给 [保存方法](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) 通过提供目标文件路径。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="创建要求" %}}
要继续生成 XBRL 文档，.NET Finance API 是应用程序中包含的主要要求。 
- 通过命令行将其安装为 '''nuget Install Aspose.Finance''' 或通过Visual Studio的软件包管理器控制台安装为 '''install-Package Aspose.Finance'''。
- 或者，从以下位置获取ZIP文件中的脱机MSI安装程序或dll [下载](https://downloads.aspose.com/finance/net)。{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# 创建文件的代码" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-schema-reference.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="其他创建选项" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="OFX 请求" description="1.03或2.2格式" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-response/" name="OFX 响应" description="1.03或2.2格式" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}