---
title: 通過 .NET 轉換財務報告
url: /zh-hant/net/conversion/
description:  C# 代碼通過 .NET 庫將財務報告轉換為 XBRL、iXBRL 和 OFX 文件格式。
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通過 C# 轉換財務報告文件" h2="在基於 .NET 的應用程序中，財務報告格式轉換包括從 1.03 到 2.2 格式的 XBRL、iXBRL 和 OFX 文件。" >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) 是一個功能豐富、可擴展且易於使用的 API。開發人員可以使用以下方法輕鬆驗證 XBRL 實例、鏈接庫和分類模式 [驗證（）方法](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) 必須符合規範中規定的語法要求。此外，他們可以讀取 XBRL、iXBRL 格式以及從頭開始創建 XBRL 實例。此外，他們可以將 XBRL 格式**轉換為 iXBRL 和 Microsoft Excel XLSX 文件。 API 還支持創建開放金融交換 (OFX) 格式請求/響應，並將 OFX 文件請求/響應從 1.03 格式轉換為 2.2 格式。

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="轉換 OFX 響應和請求文件" %}}

API 通過提供兩個類來支持創建 OFX 請求和響應文件。 [Ofx請求文件](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) 用於創建和加載 1.03 和 2.2 格式的 OFX 請求文件，以及 [Ofx響應文件](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) 用於 1.03 和 2.2 格式的 OFX 響應文件。此外， [Ofx版本枚舉](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) 枚舉具有成員 V1x 即 1.x 版本、sgml 文件格式和 V2x 2.x 版本、xml 文件格式。調用OfxRequestDocument 類或OfxResponseDocument 類的Save 方法後，開發者可以輕鬆地將1.03 的sgml 文件轉換為2.2 的xml 格式。


{{% blocks/products/pf/feature-page-code h3="C# 轉換 OFX 響應文件的代碼" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-response-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# 用於轉換 OFX 請求文件的代碼" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-request-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="XBRL 財務報告轉換" %}}

API 支持將 XBRL 文件轉換為 iXBRL 和 Microsoft® Excel XLSX 格式。轉換過程很簡單，首先通過加載文件 [XbrlDocument 類](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument).使用 [保存選項類](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions) 為了 [保存格式](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions/properties/saveformat), 用作 XbrlDocument 類的 Save 方法中的參數。要保存在 iXBLR 文件中， [保存格式.IXBRL](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveformat) 將使用並導出為 XLSX 格式，將使用 SaveFormat.XLSX。

{{% blocks/products/pf/feature-page-code h3="C# 將 XBRL 導出到 iXBRL 的代碼" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-ixbrl.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="XBRL 到 XLSX 轉換的 C# 代碼" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-xlsx.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xbrl-to-ixbrl xbrl-to-xlsx" >}}