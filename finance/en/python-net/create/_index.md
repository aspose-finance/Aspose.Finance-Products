---
title: Create Financial Reports via Python
url: /python-net/create/
description:  Python code to create Financial Reports in XBRL, and OFX request or response files via Python library.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Create Financial Reporting Files via Python" h2="Financial report formats creation including XBRL and OFX request or response file in 1.03 or 2.2 format within Python based applications." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for Python via .NET](https://products.aspose.com/finance/python-net/) is a feature rich, extensible and easy to use financial report creation and processing API. Developers can easily create XBRL instance from scratch as well as can add schema reference, context, unit, item, footnote link, role reference and 
arc role reference. API provides relevant class for each feature such as for context, developers can use ContextPeriod, ContextEntity and Context. 
Moreover, API also supports open financial exchange (OFX) format request / response creation in 1.03 or 2.2 format.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Create XBRL File by Adding Item" %}}

For creating XBRL file and adding item into the document, process is, create XbrlDocument class instance. Prepare relevant settings for item by using appropriate API classes such as SchemaRef class, relevant context classes as mentioned above and Concept class. Finally define and intialize Item class properties as well as call the save method to create XBRL file into disk.

{{% blocks/products/pf/feature-page-code h3="Python Code to Create XBRL File by Adding Item" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-xbrl-file-and-add-item.py" >}} 

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Create OFX Request and Response Files" %}}


For generating OFX files, the API provides OfxRequestDocument and OfxResponseDocument classes and developers can easily [create OFX Request](https://products.aspose.com/finance/python-net/create/ofx-request/) and Response files in both 1.03 and 2.2 formats. For initializing OfxRequestDocument properties, API also provides other classes such as SignonRequest, FinancialInstitution and StatementTransactionRequest classes. Similarly, for intializing OfxResponseDocument properties, API provides supportive classes such as SignonResponse,  StatementTransactionResponse and StatementTransaction. Below are the code snippets for both cases with the use of relevant appropriate classes.

{{% blocks/products/pf/feature-page-code h3="Python Code to Generate OFX Request Documents" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-response-files.py" >}} 

{{% /blocks/products/pf/feature-page-code  %}}

{{% blocks/products/pf/feature-page-code h3="Python Code to Generate OFX Response Documents" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-response-files.py" >}} 

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}