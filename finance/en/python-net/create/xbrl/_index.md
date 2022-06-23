---
title: Create XBRL File via Python
description: Sample code for XBRL file creation. Use API example code for batch XBRL files generation within Python based applications. 
url: /python-net/create/xbrl/
family: finance
platformtag: python
feature: create
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Create XBRL Files via Python" h2="XBRL files creation without needing Microsoft Office installed or any other software." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="How to Create XBRL Files" %}}

Follow the steps in code snippet or enhance it as of your application needs for generating extensible business reporting language XBRL files. Be sure of having creation requirements within your application.

1. Create XbrlDocument class Instance.
1. To create a new XBRL instance document XbrlInstanceCollection and XbrlInstance.
1. Add schema reference using SchemaRefCollection
1. Depending on application nature add context, unit, item, footnote link and more.
1. Call the save method by providing the target file path.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Creation Requirement" %}}
To proceed for XBRL documents generation, make sure that you have the following prerequisites. 
-  Microsoft Windows or Linux based OS.
-  Python 3.5 or later.
-  Aspose.Finance for Python referenced in your project.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python code for XBRL files creation" offSpacer="" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-xbrl-file-and-add-schema-reference.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Other Creation Options" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/ofx-request/" name="OFX Request" description="1.03 or 2.2 Format" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/ofx-response/" name="OFX Response" description="1.03 or 2.2 Format" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}