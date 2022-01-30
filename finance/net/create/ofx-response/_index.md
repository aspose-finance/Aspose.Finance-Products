---
title: Create OFX Response File via C#
description: Sample code for OFX response file creation. Use API example code for batch OFX response files generation within .NET based applications. 
url: /net/create/ofx-response/
family: finance
platformtag: net
feature: create
informat: OFX Response
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Create OFX Response Files via C#" h2="OFX response files creation without needing Microsoft Office installed or any other software." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="How to Create OFX Response Files" %}}

Follow the steps in code snippet or enhance it as of your application needs after having the creation requirements within your application.

1. Create [OfxResponseDocument class](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) object.
1. Assign the relevant properties using different classes provided by API like [SignonResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse),  [StatementTransactionResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse), [StatementTransaction](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction)
1. Use the ofxVersion V2x or V1x for xml and sgml files respectively from [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) as parameter in Save method.
1. Call the [Save method](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument/methods/save) by providing the target file and ofxVersion.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Creation Requirement" %}}
To proceed for OFX Response file creation, .NET Finance API is the main requirement to be included within report generation application. 
- Install it via command line as ```nuget install Aspose.Finance``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Finance```.

- Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://downloads.aspose.com/finance/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# code for OFX response files creation" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Other Creation Options" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="OFX Request File" description="1.03 or 2.2 Format" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/xbrl/" name="XBRL File" description="Extensible Business Reporting Language" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}