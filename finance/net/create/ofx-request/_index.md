---
title: Create OFX Request File via C#
description: Sample code for OFX request file creation. Use API example code for batch OFX request files generation within .NET based applications. 
url: /net/create/ofx-request/
family: finance
platformtag: net
feature: create
informat: OFX Request
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Create OFX Request Files via C#" h2="OFX request files creation without needing Microsoft Office installed or any other software." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="How to Create OFX Request Files" %}}

After having the OFX Request files creation requirements within your application, Follow the steps in code snippet or enhance it as of your requirement.

1. Create [OfxRequestDocument class](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) object.
1. Assign the relevant properties using different classes provided by API like [SignonRequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonrequest), [FinancialInstitution](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/financialinstitution), [StatementTransactionRequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionrequest)
1. Use the ofxVersion V2x or V1x for xml and sgml files respectively from [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) as parameter in Save method.
1. Call the [Save method](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument/methods/save) by providing the target file and ofxVersion.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Creation Requirement" %}}
To proceed for OFX Request file creation, .NET Finance API is the main requirement to be included within report generation application. 
- Install it via command line as ```nuget install Aspose.Finance``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Finance```.

- Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://downloads.aspose.com/finance/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# code for OFX request files creation" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-request-files.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Other Creation Options" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-response/" name="OFX Response File" description="1.03 or 2.2 Format" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/xbrl/" name="XBRL File" description="Extensible Business Reporting Language" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}