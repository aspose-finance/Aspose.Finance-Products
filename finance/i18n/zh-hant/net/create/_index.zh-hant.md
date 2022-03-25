---
title: 通過 .NET 創建財務報告
url: /zh-hant/net/create/
description:  C# 代碼用於在 XBRL 中創建財務報告,並通過 .NET 庫創建 OFX 請求或響應文件。
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通過 C# 創建財務報告文件" h2="財務報表格式的創建包括 XBRL 和 OFX 請求或響應文件的1.03或基於 .NET 的應用程序中的2.2格式。" >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) 是一項功能豐富,可擴展且易於使用的財務報告創建和處理 API。 開發人員可以輕鬆地從頭開始創建 XBRL 實例,並可以添加架構引用,上下文,單位,項目,腳註鍊接,角色引用和 
Arc角色參考。 API 為每個功能提供相關的類,例如為上下文,開發人員可以使用 [上下文周期](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextperiod), [上下文實體](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextentity) 和 [上下文](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/context)。 
此外,API 還支持1.03或2.2格式的開放金融交換 (OFX) 格式請求/響應創建。

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="通過添加項目創建 XBRL 文件" %}}

對於創建 XBRL 文件並將項目添加到文檔中,過程是,創建 [XbrlDocument類](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) 實例。 通過使用適當的 API 類為項目準備相關設置,例如 [SchemaRef類](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemaref),如上所述的相關上下文類和 [概念類](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/concept)。 最後定義和初始化 [項目類別](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/item) 屬性以及調用 [保存方法](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) 到 [創建 XBRL](https://products.aspose.com/finance/net/create/xbrl/) 文件到磁盤。

{{% blocks/products/pf/feature-page-code h3="通過添加項目創建 XBRL 文件的 C# 代碼" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-item.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="創建 OFX 請求和響應文件" %}}


為了生成 OFX 文件,API 提供了 [OfxRequestDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) 和 [響應文檔](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) 類和開發人員可以很容易地 [創建 OFX 請求](https://products.aspose.com/finance/net/create/ofx-request/) 以及1.03和2.2格式的響應文件。 為了初始化xrequestdocument屬性,API 還提供了其他類,例如 [簽名請求](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonrequest), [金融機構](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/financialinstitution) 和 [StatementTransactionRequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionrequest) 類。 同樣,為了初始化OfxResponseDocument屬性,API 提供了支持類,例如 [簽名響應](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse),  [StatementTransactionResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse) 和 [報表交易](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction)。 以下是兩種情況下使用相關適當類的代碼片段。

{{% blocks/products/pf/feature-page-code h3="C# 生成 OFX 請求文檔的代碼" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# 生成 OFX 響應文檔的代碼" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}