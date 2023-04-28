---
title: 通過 Python 轉換財務報告
url: /zh-hant/python-net/conversion/
description:  Python 代碼通過 Python 庫轉換 XBRL、iXBRL（內聯 xbrl）和 OFX 文件格式的財務報告。
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通過 Python 轉換財務報告文件" h2="在基於 Python 的應用程序中，財務報告格式轉換包括從 1.03 到 2.2 格式的 XBRL、iXBRL 和 OFX 文件。" >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance 通過 .NET 為 Python](https://products.aspose.com/finance/python-net/) 是一個功能豐富、可擴展且易於使用的 API。開發人員可以使用 validate() 方法輕鬆驗證 XBRL 實例、鏈接庫和分類模式，該方法必須符合規範中規定的語法要求。此外，他們可以讀取 XBRL、iXBRL 格式以及從頭開始創建 XBRL 實例。此外，他們可以將 XBRL 格式**轉換為 iXBRL 和 Microsoft Excel XLSX 文件。 API 還支持開放金融交換 (OFX) 格式請求/響應創建，並將 OFX 文件請求/響應從 1.03 格式轉換為 2.2 格式。

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="轉換 OFX 響應和請求文件" %}}

API 通過提供兩個類來支持創建 OFX 請求和響應文件。 OfxRequestDocument 用於創建和加載 OFX 1.03 和 2.2 格式的請求文件，OfxResponseDocument 用於創建和加載 OFX 1.03 和 2.2 格式的響應文件。此外，OfxVersionEnum Enumeration 具有成員 V1x，即 1.x 版本，sgml 文件格式和 V2x 2.x 版本，xml 文件格式。調用OfxRequestDocument 類或OfxResponseDocument 類的save 方法後，開發者可以輕鬆地將1.03 的sgml 文件轉換為2.2 的xml 格式。


{{% blocks/products/pf/feature-page-code h3="C# 轉換 OFX 響應文件的代碼" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-ofx-response-from-1.03-to-2.2.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# 用於轉換 OFX 請求文件的代碼" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-ofx-request-from-1.03-to-2.2.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="XBRL 財務報告轉換" %}}

API 支持將 XBRL 文件轉換為 iXBRL 和 Microsoft® Excel XLSX 格式。轉換過程很簡單，首先通過 XbrlDocument 類加載文件。將 SaveOptions 類用於 SaveFormat，用作 XbrlDocument 類的保存方法中的參數。要保存在 iXBLR 文件中，將使用 SaveFormat.IXBRL，要導出為 XLSX 格式，將使用 SaveFormat.XLSX。

{{% blocks/products/pf/feature-page-code h3="Python 將 XBRL 導出到 iXBRL 的代碼" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-xbrl-to-ixbrl.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="XBRL 到 XLSX 轉換的 Python 代碼" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-xbrl-to-xlsx.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xbrl-to-ixbrl xbrl-to-xlsx" >}}
{{< /blocks/products/pf/feature-page-wrap >}}