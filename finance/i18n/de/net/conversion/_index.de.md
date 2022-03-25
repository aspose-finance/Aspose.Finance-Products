---
title: Konvertieren von Finanz berichten über .NET
url: /de/net/conversion/
description:  C#-Code zum Konvertieren von Finanz berichten in XBRL, iXBRL und OFX Datei fomats über .NET Bibliothek.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konvertieren von Finanz berichts dateien über C#" h2="Finanz berichts formate Konvertierung einschl ießlich XBRL, iXBRL und OFX Datei von 1.03 in 2.2 Format innerhalb von .NET basierten Anwendungen." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) Ist eine Funktion reich, erweiterbar und einfach zu bedienen API. Entwickler können mit Hilfe von XBRL Instanzen, Linkbasen und Taxonomie-Schemas problemlos validieren [Validierung methode ()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) Die den in der Spezifikation festgelegten Syntax anforderungen entsprechen müssen. Darüber hinaus können sie XBRL, iXBRL Formate lesen und XBRL Instanz von Grund auf neu erstellen. Darüber hinaus können sie ** XBRL Format ** in iXBRL und Microsoft Excel XLSX-Dateien konvertieren. API unterstützt auch die Erstellung von Anfragen/Antworten im Open Financial Exchange-Format (OFX) und konvertiert die Datei anforderung/-Antwort von OFX im Format 1.03 in das Format 2.2.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="OFX Antwort-und Anforderung dateien konvertieren" %}}

API unterstützt das Erstellen von OFX Anforderung-und Antwort dateien, indem zwei Klassen bereit gestellt werden. [OfxRequest Document](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) Zum Erstellen und Laden von OFX Anforderung dateien im Format 1.03 und 2.2 und [OfxResponse Document](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) Für OFX Antwort dateien im Format 1.03 und 2.2. Darüber hinaus, [OfxVersion Enum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) Aufzählung mit Mitgliedern V1x, die 1.x- Version, sgml-Dateiformat und V2x 2.xversion, xml-Dateiformat ist. Nach dem Aufruf der Save-Methode der OfxRequestDocument-Klasse oder der OfxResponse Document-Klasse können Entwickler problemlos von der 1,03-sgml-Datei in das 2,2-xml-Format konvertieren.


{{% blocks/products/pf/feature-page-code h3="C# Code zum Konvertieren von OFX Antwort dateien" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-response-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Code zum Konvertieren von OFX Anforderung dateien" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-request-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="XBRL Umrechnung von Finanz berichten" %}}

API unterstützt die Konvertierung von XBRL-Dateien in iXBRL und Microsoft®Excel XLSX-Format. Konvertierungs prozess ist einfach, zuerst laden Sie die Datei über [XbrlDocument-Klasse](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument). Verwenden Sie die [SaveOptions-Klasse](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions) Für [SaveFormat](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions/properties/saveformat), Die als Parameter in der Save-Methode der XbrlDocument-Klasse verwendet werden soll. Zum Speichern in der iXBLR-Datei, [SaveFormat.IXBRL](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveformat) Wird verwendet und für den Export in das XLSX-Format wird SaveFormat.XLSX verwendet.

{{% blocks/products/pf/feature-page-code h3="C# Code zum Export von XBRL nach iXBRL" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-ixbrl.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Code für XBRL in XLSX-Konvertierung" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-xlsx.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xbrl-to-ixbrl xbrl-to-xlsx" >}}