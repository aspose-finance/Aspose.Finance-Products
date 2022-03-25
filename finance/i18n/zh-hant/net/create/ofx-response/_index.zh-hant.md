---
title: 通過 C# 創建 OFX 響應文件
description: 創建 OFX 響應文件的示例代碼。 使用 API 示例代碼在基於 .NET 的應用程序中生成批處理 OFX 響應文件。 
url: /zh-hant/net/create/ofx-response/
family: finance
platformtag: net
feature: create
informat: OFX Response
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通過 C# 創建 OFX 響應文件" h2="OFX 無需安裝Microsoft Office或任何其他軟件即可創建響應文件。" >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="如何創建 OFX 響應文件" %}}

在應用程序中具有創建要求後,請按照代碼段中的步驟進行操作,或根據應用程序的需要對其進行增強。

1. 創建 [OfxResponseDocument類](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) 對象。1. 使用 API 提供的不同類分配相關屬性,如 [簽名響應](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse),  [StatementTransactionResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse), [報表交易](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction)1. 將ofxVersion V2x或V1x分別用於xml和sgml文件 [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) 作為保存方法中的參數。1. 打電話給 [保存方法](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument/methods/save) 通過提供目標文件和ofxVersion。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="創建要求" %}}
要繼續創建 OFX 響應文件,.NET Finance API 是包含在報告生成應用程序中的主要要求。 
- 通過命令行將其安裝為 '''nuget Install Aspose.Finance''' 或通過Visual studio的軟件包管理器控制台安裝為 '''install-Package Aspose.Finance'''。
- 或者,從以下位置獲取ZIP文件中的脫機MSI安裝程序或dll [下載](https://downloads.aspose.com/finance/net)。{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# 創建響應文件的代碼" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="其他創建選項" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="OFX 請求文件" description="1.03或2.2格式" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/xbrl/" name="XBRL 文件" description="可擴展業務報告語言" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}