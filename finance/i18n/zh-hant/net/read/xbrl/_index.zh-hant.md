---
title: 通過 C# 讀取 XBRL 文件
description: XBRL 文件讀取的示例代碼。 使用 API 示例代碼讀取基於 .NET 的應用程序中的批處理 XBRL 文件。 
url: /zh-hant/net/read/xbrl/
family: finance
platformtag: net
feature: read
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通過 C# 讀取 XBRL 文件" h2="閱讀 XBRL 格式的財務報告,而無需安裝Microsoft Office或任何其他軟件。" >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="如何讀取 XBRL 文件" %}}

按照代碼段中的步驟進行操作,或者根據您的應用程序需要對其進行增強,以讀取可擴展的業務報告語言 XBRL 文件。 確保您的應用程序中有閱讀要求。

1. 創建 [XbrlDocument類](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) 實例。1. 傳遞有效 XBRL 文件的名稱作為參數。1. 要獲取文件的內部詳細信息,請使用相關的類,例如 [SchemaRefCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemarefcollection), [上下文](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/context), [單位](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/unit) 
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="閱讀要求" %}}
要繼續閱讀 XBRL 文檔,.NET Finance API 是應用程序中包含的主要要求。 
- 通過命令行將其安裝為 '''nuget Install Aspose.Finance''' 或通過Visual studio的軟件包管理器控制台安裝為 '''install-Package Aspose.Finance'''。
- 或者,從以下位置獲取ZIP文件中的脫機MSI安裝程序或dll [下載](https://downloads.aspose.com/finance/net)。{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# 讀取 XBRL 文件的代碼" offSpacer="" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "read-xbrl-file.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="其他閱讀選項" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/read/ixbrl/" name="iXBRL" description="內聯可擴展業務報告語言" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}