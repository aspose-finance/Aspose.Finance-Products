---
title: 通過 Python 驗證 XBRL 文件
description: XBRL 文件驗證的示例代碼。使用 API 示例代碼驗證基於 Python 的應用程序中的批處理 XBRL 文件。 
url: /zh-hant/python-net/validate/xbrl/
family: finance
platformtag: python
feature: validate
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通過 Python 驗證 XBRL 個文件" h2="無需安裝 Microsoft Office 或任何其他軟件即可驗證 XBRL 格式的財務報告。" >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="如何驗證 XBRL 文件" %}}

按照代碼片段中的步驟或根據您的應用程序需要對其進行增強，以驗證可擴展的業務報告語言 XBRL 文檔。確保在您的應用程序中有驗證要求。

1. 使用 XbrlDocument 類實例加載 XBRL 文件。2.檢查加載文件的有效性，使其必須與 [XBRL 規範](http://www.xbrl.org/specification/inlinexbrl-part1/rec-2013-11-18/inlinexbrl-part1-rec-2013-11-18.html)
3. 要檢查有效性，請使用 XbrlInstance 類的 validate 方法。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="驗證要求" %}}
要繼續驗證 XBRL 文檔，請確保您具有以下先決條件。 
- 基於 Microsoft Windows 或 Linux 的操作系統。- Python 3.5 或更高版本。- Aspose.Finance 表示您的項目中引用的 Python。{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="用於驗證 XBRL 個文件的 Python 代碼" offSpacer="" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "validate-xbrl-instance-file.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="其他驗證選項" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/validate/ixbrl/" name="XBRL" description="內聯可擴展業務報告語言" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}