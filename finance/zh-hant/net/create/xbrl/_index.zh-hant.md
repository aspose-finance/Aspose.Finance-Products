---
title: 通過 C# 創建 XBRL 文件
description: XBRL 文件創建的示例代碼。使用 API 示例代碼在基於 .NET 的應用程序中生成批處理 XBRL 文件。 
url: /zh-hant/net/create/xbrl/
family: finance
platformtag: net
feature: create
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通過 C# 創建 XBRL 個文件" h2="XBRL 無需安裝 Microsoft Office 或任何其他軟件即可創建文件。" >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="如何創建 XBRL 文件" %}}

遵循代碼片段中的步驟或根據您的應用程序需要對其進行增強，以生成可擴展的業務報告語言 XBRL 文件。確保在您的應用程序中有創建要求。

1. 創建 [XbrlDocument 類](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) 實例。1. 創建新的 XBRL 實例文檔 [XbrlInstanceCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) 和 [Xbrl實例](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance).1. 使用添加架構引用 [SchemaRefCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemarefcollection)1. 根據應用程序性質添加上下文、單元、項目、腳註鏈接等。1. 調用 [保存方法](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) 通過提供目標文件路徑。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="創作要求" %}}
要繼續生成 XBRL 文檔，.NET Finance API 是要包含在應用程序中的主要要求。 
- 通過命令行將其安裝為 ```nuget install Aspose.Finance``` 或通過 Visual Studio 的包管理器控制台使用 ```Install-Package Aspose.Finance``` 進行安裝。
- 或者，從 ZIP 文件中獲取離線 MSI 安裝程序或 DLL [下載](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XBRL 文件創建的 C# 代碼" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-schema-reference.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="其他創建選項" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="OFX 請求" description="1.03 或 2.2 格式" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-response/" name="OFX 響應" description="1.03 或 2.2 格式" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}