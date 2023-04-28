---
title: 通過 Python 驗證財務報告
url: /zh-hant/python-net/validate/
description:  Python 代碼通過 Python 庫驗證 XBRL 和 iXBRL 文件中的財務報告。
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通過 Python 驗證財務報告文件" h2="在基於 Python 的應用程序中驗證財務報告格式，包括 XBRL 和 iXBRL。" >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance 通過 .NET 為 Python](https://products.aspose.com/finance/python-net/) 是一種功能豐富、可擴展且易於使用的財務報告處理API。開發人員可以輕鬆加載、驗證、查看或創建用於財務和業務解決方案的 XBRL 和 iXBRL 格式。 API 提供用於加載 XBRL 和 iXBRL 文件的 XbrlDocument 類和 InlineXbrlDocument 類。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="驗證 XBRL 文檔" %}}

在許多情況下需要驗證 XBRL 文件，例如檢查數據的結構和格式是否正確。要驗證 XBLR 文檔，首先使用 XbrlDocument 類加載 XBRL 文件。要使用 XbrlInstance 類的 validate 方法，首先用 XbrlDocument 對象 XbrlInstances 初始化 XbrlInstanceCollection。遍歷每個 XbrlInstance.ValidationErrors 以獲得正確的錯誤代碼，並通過在控制台上打印自定義錯誤消息或寫入文件來採取相應措施。

{{% blocks/products/pf/feature-page-code h3="Python 驗證 XBRL 文件的代碼" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "validate-xbrl-instance-file.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="驗證 iXBRL 文檔" %}}

對於 iXLRB 驗證，通過 InlineXbrlDocument 類加載它並使用它的 validate() 方法。在 ValidationErrorCode 枚舉中，為每個驗證規則定義了驗證錯誤代碼。很少有代碼是 ContextPeriodNoStartTime、ContextPeriodNoEndTime、ContextPeriodStartAfterEnd、ContextInstantNoTime、ContextScenarioXbrlNamespace、ContextScenarioXbrlSubstitutionGroup 等。開發人員可以作為最終用戶調試和顯示代碼，也可以顯示解決問題的方向。

{{% blocks/products/pf/feature-page-code h3="Python 驗證 iXBRL 文檔的代碼" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "validate-ixbrl-file.py" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Validate" >}}
{{< /blocks/products/pf/feature-page-wrap >}}