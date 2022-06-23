---
title: 通過 C# 創建 OFX 響應文件
description: OFX 響應文件創建的示例代碼。使用 API 示例代碼在基於 .NET 的應用程序中生成批處理 OFX 響應文件。 
url: /zh-hant/net/create/ofx-response/
family: finance
platformtag: net
feature: create
informat: OFX Response
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通過 C# 創建 OFX 響應文件" h2="OFX 無需安裝 Microsoft Office 或任何其他軟件即可創建響應文件。" >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="如何創建 OFX 響應文件" %}}

在您的應用程序中具有創建要求後，按照代碼片段中的步驟或根據您的應用程序需要對其進行增強。

1. 創造 [OfxResponseDocument 類](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) 目的。1. 使用 API 提供的不同類分配相關屬性，例如 [登錄響應](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse),  [語句事務響應](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse), [聲明交易](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction)1. 對 xml 和 sgml 文件分別使用 ofxVersion V2x 或 V1x [Ofx版本枚舉](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) 作為 Save 方法中的參數。1. 調用 [保存方法](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument/methods/save) 通過提供目標文件和 ofxVersion。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="創作要求" %}}
要繼續創建 OFX 響應文件，.NET Finance API 是包含在報告生成應用程序中的主要要求。 
- 通過命令行將其安裝為 ```nuget install Aspose.Finance``` 或通過 Visual Studio 的包管理器控制台使用 ```Install-Package Aspose.Finance``` 進行安裝。
- 或者，從 ZIP 文件中獲取離線 MSI 安裝程序或 DLL [下載](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="OFX 響應文件創建的 C# 代碼" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="其他創建選項" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="OFX 請求文件" description="1.03 或 2.2 格式" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/xbrl/" name="XBRL 文件" description="可擴展的業務報告語言" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}