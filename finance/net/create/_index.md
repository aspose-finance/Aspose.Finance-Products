---
title: Create Financial Reports via .NET
url: /net/create/
description:  C# code to create Financial Reports in XBRL, and OFX request or response files via .NET library.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Create Financial Report Files via C#" h2="Financial report formats creation including XBRL and OFX request or response file in 1.03 or 2.2 format within .NET based applications." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) is a feature rich, extensible and easy to use financial report creation and processing API. Developers can easily create XBRL instance from scratch as well as can add schema reference, context, unit, item, footnote link, role reference and 
arc role reference. API provides relevant class for each feature such as for context, developers can use [ContextPeriod](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextperiod), [ContextEntity](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextentity) and [Context](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/context). 
Moreover, API also supports open financial exchange (OFX) format request / response creation in 1.03 or 2.2 format.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Create XBRL File by Adding Item" %}}

For creating XBRL file and adding item into the document, process is, create [XbrlDocument class](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) instance. Prepare relevant settings for item by using appropriate API classes such as [SchemaRef class](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemaref), relevant context classes as mentioned above and [Concept class](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/concept). Finally define and intialize [Item class](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/item) properties as well as call the [Save method](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) to [create XBRL](https://products.aspose.com/finance/net/create/xbrl/) file into disk.

{{% blocks/products/pf/feature-page-code h3="C# Code to Create XBRL File by Adding Item" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-item.cs" >}} 

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Create OFX Request and Response Files" %}}


For generating OFX files, the API provides [OfxRequestDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) and [OfxResponseDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) classes and developers can easily [create OFX Request](https://products.aspose.com/finance/net/create/ofx-request/) and Response files in both 1.03 and 2.2 formats. For initializing OfxRequestDocument properties, API also provides other classes such as [SignonRequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonrequest), [FinancialInstitution](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/financialinstitution) and [StatementTransactionRequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionrequest) classes. Similarly, for intializing OfxResponseDocument properties, API provides supportive classes such as [SignonResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse),  [StatementTransactionResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse) and [StatementTransaction](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction). Below are the code snippets for both cases with the use of relevant appropriate classes.

{{% blocks/products/pf/feature-page-code h3="C# Code to Generate OFX Request Documents" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code  %}}

{{% blocks/products/pf/feature-page-code h3="C# Code to Generate OFX Response Documents" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}