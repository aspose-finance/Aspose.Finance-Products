---
title: Convert Financial Reports via .NET
url: /net/conversion/
description:  C# code to convert Financial Reports in XBRL, iXBRL and OFX file fomats via .NET library.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert Financial Report Files via C#" h2="Financial report formats conversion including XBRL, iXBRL and OFX file from 1.03 to 2.2 format within .NET based applications." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) is a feature rich, extensible and easy to use API. Developers can easily validate XBRL instances, linkbases and taxonomy schemas using [validate() method](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) that must comply with the syntax requirements imposed in specification. Moreover, they can read XBRL, iXBRL formats as well as create XBRL instance from scratch. Moreover, they can **convert XBRL format** to iXBRL and Microsoft Excel XLSX files. API also supports open financial exchange (OFX) format request / response creation and converts OFX file request / response from 1.03 to 2.2 format.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Convert OFX Response and Request Files" %}}

API supports creating OFX request and response files by providing two classes. [OfxRequestDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) for creating and loading OFX request files in 1.03 and 2.2 format and [OfxResponseDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) for OFX response files in 1.03 and 2.2 format. Futhermore, [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) Enumeration having members V1x that is 1.x version, sgml file format and V2x 2.x version, xml file format. After calling the Save method of OfxRequestDocument class or OfxResponseDocument class, developers can easily convert from 1.03 sgml file to 2.2 xml format.


{{% blocks/products/pf/feature-page-code h3="C# Code to Convert OFX Response Files" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-response-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code  %}}

{{% blocks/products/pf/feature-page-code h3="C# Code to Convert OFX Request Files" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-request-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="XBRL Financial Reports Conversion" %}}

API supports converting XBRL files to iXBRL and Microsoft® Excel XLSX format. Conversion process is simple, firstly load the file via [XbrlDocument Class](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument). Use the [SaveOptions class](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions) for [SaveFormat](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions/properties/saveformat), to be used as parameter in Save method of XbrlDocument Class. For saving in iXBLR file, [SaveFormat.IXBRL](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveformat) will be used and for exporting into XLSX format, SaveFormat.XLSX will be used.

{{% blocks/products/pf/feature-page-code h3="C# Code to Export XBRL to iXBRL" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-ixbrl.cs" >}} 

{{% /blocks/products/pf/feature-page-code  %}}

{{% blocks/products/pf/feature-page-code h3="C# Code for XBRL to XLSX Conversion" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-xlsx.cs" >}} 

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xbrl-to-ixbrl xbrl-to-xlsx" >}}