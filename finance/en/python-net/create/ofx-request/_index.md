---
title: Create OFX Request File via Python
description: Sample code for OFX request file creation. Use API example code for batch OFX request files generation within Python based applications. 
url: /python-net/create/ofx-request/
family: finance
platformtag: python
feature: create
informat: OFX Request
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Create OFX Request Files via Python" h2="OFX request files creation without needing Microsoft Office installed or any other software." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="How to Create OFX Request Files" %}}

After having the OFX Request files creation requirements within your application, Follow the steps in code snippet or enhance it as of your requirement.

1. Create OfxRequestDocument class object.
2. Assign the relevant properties using different classes provided by API like SignonRequest, FinancialInstitution], StatementTransactionRequest
3. Use the ofxVersion V2x or V1x for xml and sgml files respectively from OfxVersionEnum as parameter in Save method.
4. Call the save method by providing the target file and ofxVersion.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Creation Requirement" %}}
To proceed for OFX Request file creation, make sure that you have the following prerequisites. 
-  Microsoft Windows or Linux based OS.
-  Python 3.5 or later.
-  Aspose.Finance for Python referenced in your project.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python code for OFX request files creation" offSpacer="" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-request-files.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Other Creation Options" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/ofx-response/" name="OFX Response File" description="1.03 or 2.2 Format" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/xbrl/" name="XBRL File" description="Extensible Business Reporting Language" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}