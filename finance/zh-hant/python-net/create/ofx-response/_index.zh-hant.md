---
title: 通過 Python 創建 OFX 響應文件
description: OFX 響應文件創建的示例代碼。使用 API 示例代碼在基於 Python 的應用程序中生成批處理 OFX 響應文件。 
url: /zh-hant/python-net/create/ofx-response/
family: finance
platformtag: python
feature: create
informat: OFX Response
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通過 Python 創建 OFX 響應文件" h2="OFX 無需安裝 Microsoft Office 或任何其他軟件即可創建響應文件。" >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="如何創建 OFX 響應文件" %}}

在您的應用程序中具有創建要求後，按照代碼片段中的步驟或根據您的應用程序需要對其進行增強。

1. 創建 OfxResponseDocument 類對象。1. 使用 API 提供的不同類分配相關屬性，例如 SignonResponse、StatementTransactionResponse、StatementTransaction1. 使用 OfxVersion V2x 或 V1x 分別來自 OfxVersionEnum 的 xml 和 sgml 文件作為保存方法中的參數。1. 通過提供目標文件和ofxVersion來調用save方法。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="創作要求" %}}
要繼續創建 OFX 響應文件，請確保您具有以下先決條件。 
- 基於 Microsoft Windows 或 Linux 的操作系統。- Python 3.5 或更高版本。- Aspose.Finance 表示您的項目中引用的 Python。{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="OFX 響應文件創建的 Python 代碼" offSpacer="" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-response-files.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="其他創建選項" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/ofx-request/" name="OFX 請求文件" description="1.03 或 2.2 格式" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/xbrl/" name="XBRL 文件" description="可擴展的業務報告語言" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}