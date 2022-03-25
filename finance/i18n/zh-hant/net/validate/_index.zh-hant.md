---
title: 通過 .NET 驗證財務報告
url: /zh-hant/net/validate/
description:  C# 代碼,用於通過 .NET 庫驗證 XBRL 和 iXBRL 文件中的財務報告。
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通過 C# 驗證財務報告文件" h2="在基於 .NET 的應用程序中驗證財務報告格式,包括 XBRL 和 iXBRL。" >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) 是一個功能豐富、可擴展且易於使用的財務報表處理 API。 開發人員可以輕鬆地為財務和業務解決方案加載、驗證、查看或創建 XBRL 和 iXBRL 格式。 API 提供 [XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) 班級和  [InlineXbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) 用於加載 XBRL 和 iXBRL 文件的類。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="驗證 XBRL 文檔" %}}

對於許多情況,例如檢查數據是否正確的結構和格式,需要對 XBRL 文件進行驗證。 要驗證XBLR文檔,首先使用XbrlDocument類加載 XBRL 文件。 要使用 [驗證 ()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) 方法 [XbrlInstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance) 類,首先初始化 [XbrlInstanceCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) 使用XbrlDocument對象XbrlInstances。 遍歷每個 [XbrlInstance。 驗證錯誤](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/properties/validationerrors) 通過在控制台上打印自定義的錯誤消息或在文件中寫入來獲取正確的錯誤代碼並採取相應的行動。

{{% blocks/products/pf/feature-page-code h3="驗證 XBRL 文件的 C# 代碼" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-xbrl-file.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="驗證 iXBRL 文檔" %}}

對於iXLRB驗證,請通過 [InlineXbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) 類並使用其Validate() 方法。 在 [驗證錯誤代碼](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.validator/validationerrorcode) 枚舉,為每個驗證規則定義了驗證錯誤代碼。 很少有代碼是contextperiodennostarttime、contextperiodenstartafterend、ContextInstantNoTime、ContextScenarioXbrlNamespace、contextscenarioxbrlsubutiongroup等。 開發人員可以調試和顯示最終用戶的代碼,也可以顯示解決問題的方向。

{{% blocks/products/pf/feature-page-code h3="用於驗證 iXBRL 文檔的 C# 代碼" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-ixbrl-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Validate" >}}