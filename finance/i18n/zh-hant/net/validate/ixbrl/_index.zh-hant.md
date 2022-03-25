---
title: 通過 C# 驗證 iXBRL 文件
description: iXBRL 文件驗證的示例代碼。 使用 API 示例代碼驗證基於 .NET 的應用程序中的批處理 iXBRL 文件。 
url: /zh-hant/net/validate/ixbrl/
family: finance
platformtag: net
feature: validate
informat: iXBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通過 C# 驗證 iXBRL 文件" h2="以 iXBRL 格式驗證財務報告,而無需安裝Microsoft Office或任何其他軟件。" >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="如何驗證 iXBRL 文件" %}}

按照代碼段中的步驟進行操作,或者根據應用程序的需要對其進行增強,以驗證可擴展的業務報告語言 iXBRL 文檔。 請確保您的應用程序中有驗證要求。

1. 使用加載 iXBRL 文件 [InlineXbrlDocument類](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) 實例。1. 檢查加載文件的有效性,以便它必須與 [iXBRL 規格](http://www.xbrl.org/specification/inlinexbrl-part1/rec-2013-11-18/inlinexbrl-part1-rec-2013-11-18.html)1. 使用 [驗證 ()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument/methods/validate) 文件有效性的方法。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="驗證要求" %}}
要繼續驗證 iXBRL 文檔,.NET Finance API 是應用程序中包含的主要要求。 
- 通過命令行將其安裝為 '''nuget Install Aspose.Finance''' 或通過Visual studio的軟件包管理器控制台安裝為 '''install-Package Aspose.Finance'''。
- 或者,從以下位置獲取ZIP文件中的脫機MSI安裝程序或dll [下載](https://downloads.aspose.com/finance/net)。{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="驗證 iXBRL 文件的 C# 代碼" offSpacer="" %}}

{{< gist "aspose-com-gists" "1272da1f804f8cef122600269db09fbb" "validate-ixbrl-file.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="其他驗證選項" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/validate/xbrl/" name="XBRL" description="可擴展業務報告語言" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}