---
title: Validate XBRL File via C#
description: Sample code for XBRL file validation. Use API example code to validate batch XBRL files within .NET based applications. 
url: /net/validate/xbrl/
family: finance
platformtag: net
feature: validate
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Validate XBRL Files via C#" h2="Validating financial reports in XBRL format without needing Microsoft Office installed or any other software." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="How to Validate XBRL Files" %}}

Follow the steps in code snippet or enhance it as of your application needs for validating extensible business reporting language XBRL documents. Be sure of having validating requirements within your application.

1. Load XBRL file using [XbrlDocument class](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Instance.
1. To check validity of the loaded file, so that it must match with [XBRL specification](http://www.xbrl.org/specification/inlinexbrl-part1/rec-2013-11-18/inlinexbrl-part1-rec-2013-11-18.html)
1. To check the validatity, use [Validate()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) method of [XbrlInstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance) class.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Validating Requirement" %}}
To proceed for validating XBRL documents, .NET Finance API is the main requirement to be included within application. 
- Install it via command line as ```nuget install Aspose.Finance``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Finance```.

- Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://downloads.aspose.com/finance/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# code to validate XBRL files" offSpacer="" %}}

{{< gist "aspose-com-gists" "1272da1f804f8cef122600269db09fbb" "validate-xbrl-instance-file.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Other Validating Options" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/validate/ixbrl/" name="XBRL" description="Inline Extensible Business Reporting Language" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}