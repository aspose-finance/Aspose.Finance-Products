---
title: 通過 C# 查看 iXBRL 文件
description: iXBRL 文件查看的示例代碼。使用 API 示例代碼查看基於 .NET 的應用程序中的批處理 iXBRL 文件。 
url: /zh-hant/net/view/ixbrl/
family: finance
platformtag: net
feature: view
informat: iXBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通過 C# 查看 iXBRL 個文件" h2="無需安裝 Microsoft Office 或任何其他軟件即可查看 iXBRL 格式的財務報告。" >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="如何查看 iXBRL 文件" %}}

遵循代碼片段中的步驟或根據您的應用程序需要對其進行增強，以查看可擴展的業務報告語言 iXBRL 文檔。確保在您的應用程序中有閱讀要求。

1. 創造 [InlineXbrlDocument 類](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) 實例。2. 將有效 iXBRL 文件的名稱作為參數傳遞。
3. 要獲取文件的內部詳細信息，請使用相關類，例如 [內聯事實](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinefact), [語境](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/context), [單元](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/unit) 
4. 顯示這些信息

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="閱讀要求" %}}
要繼續查看 iXBRL 文檔，.NET Finance API 是包含在應用程序中的主要要求。 
- 通過命令行將其安裝為 ```nuget install Aspose.Finance``` 或通過 Visual Studio 的包管理器控制台使用 ```Install-Package Aspose.Finance``` 進行安裝。
- 或者，從 ZIP 文件中獲取離線 MSI 安裝程序或 DLL [下載](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# 代碼讀取 iXBRL 個文件" offSpacer="" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "read-ixbrl-file.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="其他查看選項" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/view/xbrl/" name="XBRL" description="可擴展的業務報告語言" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}