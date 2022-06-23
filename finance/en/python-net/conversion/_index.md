---
title: Convert Financial Reports via Python
url: /python-net/conversion/
description:  Python code to convert Financial Reports in XBRL, iXBRL(inline xbrl) and OFX file fomats via Python library.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert Financial Report Files via Python" h2="Financial report formats conversion including XBRL, iXBRL and OFX file from 1.03 to 2.2 format within Python based applications." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for Python via .NET](https://products.aspose.com/finance/python-net/) is a feature rich, extensible and easy to use API. Developers can easily validate XBRL instances, linkbases and taxonomy schemas using validate() method that must comply with the syntax requirements imposed in specification. Moreover, they can read XBRL, iXBRL formats as well as create XBRL instance from scratch. Moreover, they can **convert XBRL format** to iXBRL and Microsoft Excel XLSX files. API also supports open financial exchange (OFX) format request / response creation and converts OFX file request / response from 1.03 to 2.2 format.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Convert OFX Response and Request Files" %}}

API supports creating OFX request and response files by providing two classes. OfxRequestDocument for creating and loading OFX request files in 1.03 and 2.2 format and OfxResponseDocument for OFX response files in 1.03 and 2.2 format. Futhermore, OfxVersionEnum Enumeration having members V1x that is 1.x version, sgml file format and V2x 2.x version, xml file format. After calling the save method of OfxRequestDocument class or OfxResponseDocument class, developers can easily convert from 1.03 sgml file to 2.2 xml format.


{{% blocks/products/pf/feature-page-code h3="C# Code to Convert OFX Response Files" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-ofx-response-from-1.03-to-2.2.py" >}} 

{{% /blocks/products/pf/feature-page-code  %}}

{{% blocks/products/pf/feature-page-code h3="C# Code to Convert OFX Request Files" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-ofx-request-from-1.03-to-2.2.py" >}} 

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="XBRL Financial Reports Conversion" %}}

API supports converting XBRL files to iXBRL and Microsoft® Excel XLSX format. Conversion process is simple, firstly load the file via XbrlDocument Class. Use the SaveOptions class for SaveFormat, to be used as parameter in save method of XbrlDocument Class. For saving in iXBLR file, SaveFormat.IXBRL will be used and for exporting into XLSX format, SaveFormat.XLSX will be used.

{{% blocks/products/pf/feature-page-code h3="Python Code to Export XBRL to iXBRL" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-xbrl-to-ixbrl.py" >}} 

{{% /blocks/products/pf/feature-page-code  %}}

{{% blocks/products/pf/feature-page-code h3="Python Code for XBRL to XLSX Conversion" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-xbrl-to-xlsx.py" >}} 

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xbrl-to-ixbrl xbrl-to-xlsx" >}}