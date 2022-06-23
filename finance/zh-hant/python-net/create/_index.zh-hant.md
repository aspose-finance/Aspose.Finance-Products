---
title: 通過 Python 創建財務報告
url: /zh-hant/python-net/create/
description:  在 XBRL 中創建財務報告的 Python 代碼，以及通過 Python 庫的 OFX 請求或響應文件。
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通過 Python 創建財務報告文件" h2="在基於 Python 的應用程序中創建財務報告格式，包括 1.03 或 2.2 格式的 XBRL 和 OFX 請求或響應文件。" >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance 通過 .NET 為 Python](https://products.aspose.com/finance/python-net/) 是一種功能豐富、可擴展且易於使用的財務報告創建和處理API。開發人員可以輕鬆地從頭開始創建 XBRL 實例，還可以添加架構引用、上下文、單元、項目、腳註鏈接、角色引用和 
arc 角色參考。 API 為每個功能提供相關類，例如上下文，開發者可以使用 ContextPeriod、ContextEntity 和 Context。 
此外，API 還支持 1.03 或 2.2 格式的開放式金融交換 (OFX) 格式請求/響應創建。

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="通過添加項目創建 XBRL 文件" %}}

為了創建XBRL文件並將項目添加到文檔中，過程是創建 XbrlDocument 類實例。使用適當的 API 類（如 SchemaRef 類、上述相關上下文類和概念類）為項目準備相關設置。最後定義並初始化 Item 類屬性，並調用 save 方法將 XBRL 文件創建到磁盤中。

{{% blocks/products/pf/feature-page-code h3="Python 通過添加項目創建 XBRL 文件的代碼" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-xbrl-file-and-add-item.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="創建 OFX 請求和響應文件" %}}


為了生成 OFX 文件，API 提供了 OfxRequestDocument 和 OfxResponseDocument 類，開發人員可以輕鬆地 [創建 OFX 請求](https://products.aspose.com/finance/python-net/create/ofx-request/) 和 1.03 和 2.2 格式的響應文件。為了初始化 OfxRequestDocument 屬性，API 還提供了其他類，例如 SignonRequest、FinancialInstitution 和 StatementTransactionRequest 類。同樣，為了初始化 OfxResponseDocument 屬性，API 提供了支持類，例如 SignonResponse、StatementTransactionResponse 和 StatementTransaction。下面是使用相關適當類的兩種情況的代碼片段。

{{% blocks/products/pf/feature-page-code h3="Python 生成代碼 OFX 請求文檔" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-response-files.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Python 生成 OFX 響應文檔的代碼" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-response-files.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}