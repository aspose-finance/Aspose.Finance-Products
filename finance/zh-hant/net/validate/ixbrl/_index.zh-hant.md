---
title: 通過 C# 驗證 iXBRL 文件
description: iXBRL 文件驗證的示例代碼。使用 API 示例代碼驗證基於 .NET 的應用程序中的批處理 iXBRL 文件。 
url: /zh-hant/net/validate/ixbrl/
family: finance
platformtag: net
feature: validate
informat: iXBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通過 C# 驗證 iXBRL 個文件" h2="無需安裝 Microsoft Office 或任何其他軟件即可驗證 iXBRL 格式的財務報告。" >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="如何驗證 iXBRL 文件" %}}

按照代碼片段中的步驟或根據您的應用程序需要對其進行增強，以驗證可擴展的業務報告語言 iXBRL 文檔。確保在您的應用程序中有驗證要求。

1. 使用加載 iXBRL 文件 [InlineXbrlDocument 類](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) 實例。1. 檢查加載文件的有效性，使其必須與 [iXBRL 規範](http://www.xbrl.org/specification/inlinexbrl-part1/rec-2013-11-18/inlinexbrl-part1-rec-2013-11-18.html)1. 利用 [證實（）](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument/methods/validate) 文件有效性的方法。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="驗證要求" %}}
要繼續驗證 iXBRL 文檔，.NET Finance API 是要包含在應用程序中的主要要求。 
- 通過命令行將其安裝為 ```nuget install Aspose.Finance``` 或通過 Visual Studio 的包管理器控制台使用 ```Install-Package Aspose.Finance``` 進行安裝。
- 或者，從 ZIP 文件中獲取離線 MSI 安裝程序或 DLL [下載](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="用於驗證 iXBRL 個文件的 C# 代碼" offSpacer="" %}}

{{< gist "aspose-com-gists" "1272da1f804f8cef122600269db09fbb" "validate-ixbrl-file.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="其他驗證選項" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/validate/xbrl/" name="XBRL" description="可擴展的業務報告語言" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}