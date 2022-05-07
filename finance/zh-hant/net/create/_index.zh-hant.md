---
title: 通過 .NET 創建財務報告
url: /zh-hant/net/create/
description:  在 XBRL 中創建財務報告的 C# 代碼，以及通過 .NET 庫的 OFX 請求或響應文件。
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通過 C# 創建財務報告文件" h2="在基於 .NET 的應用程序中創建財務報告格式，包括 1.03 或 2.2 格式的 XBRL 和 OFX 請求或響應文件。" >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) 是一種功能豐富、可擴展且易於使用的財務報告創建和處理API。開發人員可以輕鬆地從頭開始創建 XBRL 實例，還可以添加架構引用、上下文、單元、項目、腳註鏈接、角色引用和 
arc 角色參考。 API 為每個功能（例如上下文）提供相關類，開發人員可以使用 [上下文期間](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextperiod), [上下文實體](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextentity) 和 [語境](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/context). 
此外，API 還支持 1.03 或 2.2 格式的開放式金融交換 (OFX) 格式請求/響應創建。

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="通過添加項目創建 XBRL 文件" %}}

對於創建 XBRL 文件並將項目添加到文檔中，過程是，創建 [XbrlDocument 類](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) 實例。使用適當的 API 類為項目準備相關設置，例如 [SchemaRef 類](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemaref)，如上所述的相關上下文類和 [概念類](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/concept).最後定義和初始化 [物品類別](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/item) 屬性以及調用 [保存方法](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) 到 [創建XBRL](https://products.aspose.com/finance/net/create/xbrl/) 文件到磁盤。

{{% blocks/products/pf/feature-page-code h3="C# 通過添加項目創建 XBRL 文件的代碼" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-item.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="創建 OFX 請求和響應文件" %}}


為了生成 OFX 文件，API 提供 [Ofx請求文件](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) 和 [Ofx響應文件](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) 類和開發人員可以輕鬆 [創建 OFX 請求](https://products.aspose.com/finance/net/create/ofx-request/) 和 1.03 和 2.2 格式的響應文件。為了初始化 OfxRequestDocument 屬性，API 還提供了其他類，例如 [登錄請求](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonrequest), [金融機構](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/financialinstitution) 和 [聲明交易請求](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionrequest) 類。同樣，為了初始化 OfxResponseDocument 屬性，API 提供了支持類，例如 [登錄響應](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse),  [語句事務響應](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse) 和 [聲明交易](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction).下面是使用相關適當類的兩種情況的代碼片段。

{{% blocks/products/pf/feature-page-code h3="C# 生成代碼 OFX 請求文檔" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# 生成 OFX 響應文檔的代碼" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}