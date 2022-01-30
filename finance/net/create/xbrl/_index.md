---
title: Create XBRL File via C#
description: Sample code for XBRL file creation. Use API example code for batch XBRL files generation within .NET based applications. 
url: /net/create/xbrl/
family: finance
platformtag: net
feature: create
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Create XBRL Files via C#" h2="XBRL files creation without needing Microsoft Office installed or any other software." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="How to Create XBRL Files" %}}

Follow the steps in code snippet or enhance it as of your application needs for generating extensible business reporting language XBRL files. Be sure of having creation requirements within your application.

1. Create [XbrlDocument class](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Instance.
1. To create a new XBRL instance document [XbrlInstanceCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) and [XbrlInstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance).
1. Add schema reference using [SchemaRefCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemarefcollection)
1. Depending on application nature add context, unit, item, footnote link and more.
1. Call the [Save method](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) by providing the target file path.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Creation Requirement" %}}
To proceed for XBRL documents generation, .NET Finance API is the main requirement to be included within application. 
- Install it via command line as ```nuget install Aspose.Finance``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Finance```.

- Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://downloads.aspose.com/finance/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# code for XBRL files creation" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-schema-reference.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Other Creation Options" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="OFX Request" description="1.03 or 2.2 Format" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-response/" name="OFX Response" description="1.03 or 2.2 Format" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}