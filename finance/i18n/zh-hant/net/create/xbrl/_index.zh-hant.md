---
title: 通過 C# 創建 XBRL 文件
description: XBRL 文件創建的示例代碼。 使用 API 示例代碼在基於 .NET 的應用程序中批量生成 XBRL 文件。 
url: /zh-hant/net/create/xbrl/
family: finance
platformtag: net
feature: create
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通過 C# 創建 XBRL 文件" h2="無需安裝Microsoft Office或任何其他軟件即可創建 XBRL 文件。" >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="如何創建 XBRL 文件" %}}

按照代碼段中的步驟進行操作,或根據應用程序的需要對其進行增強,以生成可擴展的業務報告語言 XBRL 文件。 確保您的應用程序中有創建要求。

1. 創建 [XbrlDocument類](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) 實例。1. 創建新的 XBRL 實例文檔 [XbrlInstanceCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) 和 [XbrlInstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance)。1. 使用添加架構引用 [SchemaRefCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemarefcollection)1. 根據應用程序性質添加上下文、單位、項目、腳註鍊接等。1. 打電話給 [保存方法](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) 通過提供目標文件路徑。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="創建要求" %}}
要繼續生成 XBRL 文檔,.NET Finance API 是應用程序中包含的主要要求。 
- 通過命令行將其安裝為 '''nuget Install Aspose.Finance''' 或通過Visual studio的軟件包管理器控制台安裝為 '''install-Package Aspose.Finance'''。
- 或者,從以下位置獲取ZIP文件中的脫機MSI安裝程序或dll [下載](https://downloads.aspose.com/finance/net)。{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# 創建文件的代碼" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-schema-reference.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="其他創建選項" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="OFX 請求" description="1.03或2.2格式" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-response/" name="OFX 響應" description="1.03或2.2格式" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}