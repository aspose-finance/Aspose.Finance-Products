---
title: 通過 .NET 驗證財務報告
url: /zh-hant/net/validate/
description:  C# 代碼通過 .NET 庫驗證 XBRL 和 iXBRL 文件中的財務報告。
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通過 C# 驗證財務報告文件" h2="在基於 .NET 的應用程序中驗證財務報告格式，包括 XBRL 和 iXBRL。" >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) 是一種功能豐富、可擴展且易於使用的財務報告處理API。開發人員可以輕鬆加載、驗證、查看或創建用於財務和業務解決方案的 XBRL 和 iXBRL 格式。 API 提供 [Xbrl文檔](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) 班級和  [內聯XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) 用於加載 XBRL 和 iXBRL 文件的類。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="驗證 XBRL 文檔" %}}

在許多情況下需要驗證 XBRL 文件，例如檢查數據的結構和格式是否正確。要驗證 XBLR 文檔，首先使用 XbrlDocument 類加載 XBRL 文件。要使用 [證實（）](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) 的方法 [Xbrl實例](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance) 類，首先初始化 [XbrlInstanceCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) 與 XbrlDocument 對象 XbrlInstances。遍歷每個 [XbrlInstance.ValidationErrors](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/properties/validationerrors) 通過在控制台上打印自定義錯誤消息或在文件中寫入來獲取正確的錯誤代碼並採取相應措施。

{{% blocks/products/pf/feature-page-code h3="C# 驗證 XBRL 文件的代碼" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-xbrl-file.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="驗證 iXBRL 文檔" %}}

對於 iXLRB 驗證，通過加載它 [內聯XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) 類並使用其 Validate() 方法。在 [驗證錯誤代碼](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.validator/validationerrorcode) 枚舉，為每個驗證規則定義驗證錯誤代碼。很少有代碼是 ContextPeriodNoStartTime、ContextPeriodNoEndTime、ContextPeriodStartAfterEnd、ContextInstantNoTime、ContextScenarioXbrlNamespace、ContextScenarioXbrlSubstitutionGroup 等。開發人員可以作為最終用戶調試和顯示代碼，也可以顯示解決問題的方向。

{{% blocks/products/pf/feature-page-code h3="C# 驗證 iXBRL 文檔的代碼" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-ixbrl-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Validate" >}}