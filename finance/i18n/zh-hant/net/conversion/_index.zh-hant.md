---
title: 通過 .NET 轉換財務報告
url: /zh-hant/net/conversion/
description:  C# 代碼,用於通過 .NET 庫轉換 XBRL 、 iXBRL 和 OFX 文件文件中的財務報告。
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通過 C# 轉換財務報告文件" h2="財務報表格式轉換,包括 XBRL 、 iXBRL 和 OFX 文件在基於 .NET 的應用程序中從1.03格式轉換為2.2格式。" >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) 是一項功能豐富,可擴展且易於使用的功能 API。 開發人員可以使用以下方法輕鬆驗證 XBRL 實例、鍊接庫和分類模式 [Validate() 方法](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) 必須符合規範中規定的語法要求。 此外,它們可以讀取 XBRL,iXBRL 格式以及從頭開始創建 XBRL 實例。 此外,它們可以將 XBRL 格式 ** 轉換為 iXBRL 和Microsoft Excel XLSX文件。 API 還支持開放金融交易所 (OFX) 格式請求/響應創建,並將 OFX 文件請求/響應從1.03轉換為2.2格式。

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="轉換 OFX 響應和請求文件" %}}

API 支持通過提供兩個類來創建 OFX 請求和響應文件。 [OfxRequestDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) 用於創建和加載1.03和2.2格式的 OFX 請求文件 [響應文檔](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) 對於1.03和2.2格式的 OFX 響應文件。 此外, [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) 枚舉成員V1x是1.X版本,sgml文件格式和V2x 2.X版本,xml文件格式。 調用OfxRequestDocument類或OfxResponseDocument類的Save方法後,開發人員可以輕鬆地從1.03 sgml文件轉換為2.2 xml格式。


{{% blocks/products/pf/feature-page-code h3="C# 轉換 OFX 響應文件的代碼" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-response-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# 轉換 OFX 請求文件的代碼" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-request-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="XBRL 財務報告轉換" %}}

API 支持將 XBRL 文件轉換為 iXBRL 和Microsoft®Excel XLSX格式轉換過程很簡單,首先通過 [XbrlDocument類](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument)。 使用 [保存選項類](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions) 對於 [保存格式](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions/properties/saveformat),用作XbrlDocument類的保存方法中的參數。 為了保存在iXBLR文件中, [保存格式。 IXBRL](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveformat) 將被使用,並且對於導出為XLSX格式,將使用SaveFormat.XLSX。

{{% blocks/products/pf/feature-page-code h3="將 XBRL 導出到 iXBRL 的 C# 代碼" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-ixbrl.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="XBRL 到XLSX轉換的 C# 代碼" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-xlsx.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xbrl-to-ixbrl xbrl-to-xlsx" >}}