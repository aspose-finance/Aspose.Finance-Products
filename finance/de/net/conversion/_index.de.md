---
title: Konvertieren Sie Finanzberichte über .NET
url: /de/net/conversion/
description:  C#-Code zum Konvertieren von Finanzberichten in die Dateiformate XBRL, iXBRL (inline xbrl) und OFX über die .NET-Bibliothek.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konvertieren Sie Finanzberichtsdateien über C#" h2="Konvertierung von Finanzberichtsformaten einschließlich XBRL-, iXBRL- und OFX-Datei vom 1.03- in das 2.2-Format in .NET-basierten Anwendungen." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) ist ein funktionsreiches, erweiterbares und benutzerfreundliches API. Entwickler können XBRL-Instanzen, Linkbases und Taxonomie-Schemata einfach validieren [validate()-Methode](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) die den in der Spezifikation auferlegten Syntaxanforderungen entsprechen müssen. Darüber hinaus können sie XBRL- und iXBRL-Formate lesen sowie XBRL-Instanzen von Grund auf neu erstellen. Darüber hinaus können sie das XBRL-Format** in iXBRL- und Microsoft Excel XLSX-Dateien **konvertieren. API unterstützt auch die Anforderungs-/Antworterstellung im offenen Finanzaustauschformat (OFX) und konvertiert OFX-Dateianforderung/-antwort vom 1.03- in das 2.2-Format.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Konvertieren Sie OFX Antwort- und Anforderungsdateien" %}}

API unterstützt das Erstellen von OFX-Anforderungs- und -Antwortdateien, indem es zwei Klassen bereitstellt. [OfxRequestDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) zum Erstellen und Laden von OFX Anforderungsdateien im 1.03- und 2.2-Format und [OfxResponseDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) für OFX Antwortdateien im Format 1.03 und 2.2. Außerdem, [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) Enumeration mit Mitgliedern V1x, d. h. 1.x-Version, sgml-Dateiformat, und V2x 2.x-Version, xml-Dateiformat. Nach dem Aufrufen der Save-Methode der OfxRequestDocument-Klasse oder der OfxResponseDocument-Klasse können Entwickler problemlos von der 1.03-SGML-Datei in das 2.2-XML-Format konvertieren.


{{% blocks/products/pf/feature-page-code h3="C# Code zum Konvertieren von OFX Antwortdateien" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-response-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Code zum Konvertieren von OFX Anforderungsdateien" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-request-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="XBRL Umwandlung von Finanzberichten" %}}

API unterstützt die Konvertierung von XBRL-Dateien in das Format iXBRL und Microsoft® Excel XLSX. Der Konvertierungsprozess ist einfach, laden Sie zuerst die Datei über [XbrlDocument-Klasse](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument). Verwenden Sie die [SaveOptions-Klasse](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions) zum [Format speichern](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions/properties/saveformat), der als Parameter in der Save-Methode der XbrlDocument-Klasse verwendet werden soll. Zum Speichern in einer iXBLR-Datei [SaveFormat.IXBRL](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveformat) verwendet und für den Export in das XLSX-Format wird SaveFormat.XLSX verwendet.

{{% blocks/products/pf/feature-page-code h3="C# Code zum Exportieren von XBRL nach iXBRL" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-ixbrl.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Code für die Umwandlung von XBRL in XLSX" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-xlsx.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xbrl-to-ixbrl xbrl-to-xlsx" >}}
{{< /blocks/products/pf/feature-page-wrap >}}