---
title: Create OFX Response File via Python
description: Sample code for OFX response file creation. Use API example code for batch OFX response files generation within Python based applications. 
url: /python-net/create/ofx-response/
family: finance
platformtag: python
feature: create
informat: OFX Response
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Create OFX Response Files via Python" h2="OFX response files creation without needing Microsoft Office installed or any other software." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="How to Create OFX Response Files" %}}

Follow the steps in code snippet or enhance it as of your application needs after having the creation requirements within your application.

1. Create OfxResponseDocument class object.
1. Assign the relevant properties using different classes provided by API like SignonResponse, StatementTransactionResponse, StatementTransaction
1. Use the ofxVersion V2x or V1x for xml and sgml files respectively from OfxVersionEnum as parameter in save method.
1. Call the save method by providing the target file and ofxVersion.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Creation Requirement" %}}
To proceed for OFX Response file creation, make sure that you have the following prerequisites. 
-  Microsoft Windows or Linux based OS.
-  Python 3.5 or later.
-  Aspose.Finance for Python referenced in your project.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python code for OFX response files creation" offSpacer="" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-response-files.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Other Creation Options" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/ofx-request/" name="OFX Request File" description="1.03 or 2.2 Format" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/xbrl/" name="XBRL File" description="Extensible Business Reporting Language" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}