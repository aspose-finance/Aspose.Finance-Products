---
title: Konvertieren Sie Finanzberichte über Python
url: /de/python-net/conversion/
description:  Python-Code zum Konvertieren von Finanzberichten in die Dateiformate XBRL, iXBRL (inline xbrl) und OFX über die Python-Bibliothek.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konvertieren Sie Finanzberichtsdateien über Python" h2="Konvertierung von Finanzberichtsformaten einschließlich XBRL-, iXBRL- und OFX-Datei vom 1.03- in das 2.2-Format in Python-basierten Anwendungen." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance für Python über .NET](https://products.aspose.com/finance/python-net/) ist ein funktionsreiches, erweiterbares und benutzerfreundliches API. Entwickler können XBRL-Instanzen, Linkbases und Taxonomie-Schemata einfach validieren, indem sie die validate()-Methode verwenden, die den in der Spezifikation auferlegten Syntaxanforderungen entsprechen muss. Darüber hinaus können sie XBRL- und iXBRL-Formate lesen sowie XBRL-Instanzen von Grund auf neu erstellen. Darüber hinaus können sie das XBRL-Format** in iXBRL- und Microsoft Excel XLSX-Dateien **konvertieren. API unterstützt auch die Anforderungs-/Antworterstellung im offenen Finanzaustauschformat (OFX) und konvertiert OFX-Dateianforderung/-antwort vom 1.03- in das 2.2-Format.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Konvertieren Sie OFX Antwort- und Anforderungsdateien" %}}

API unterstützt das Erstellen von OFX-Anforderungs- und -Antwortdateien, indem es zwei Klassen bereitstellt. OfxRequestDocument zum Erstellen und Laden von OFX Anforderungsdateien im 1.03- und 2.2-Format und OfxResponseDocument für OFX Antwortdateien im 1.03- und 2.2-Format. Darüber hinaus hat die OfxVersionEnum-Enumeration Member V1x, das ist Version 1.x, sgml-Dateiformat, und V2x 2.x-Version, XML-Dateiformat. Nach dem Aufrufen der save-Methode der OfxRequestDocument-Klasse oder der OfxResponseDocument-Klasse können Entwickler problemlos von der 1.03-SGML-Datei in das 2.2-XML-Format konvertieren.


{{% blocks/products/pf/feature-page-code h3="C# Code zum Konvertieren von OFX Antwortdateien" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-ofx-response-from-1.03-to-2.2.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Code zum Konvertieren von OFX Anforderungsdateien" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-ofx-request-from-1.03-to-2.2.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="XBRL Umwandlung von Finanzberichten" %}}

API unterstützt die Konvertierung von XBRL-Dateien in das Format iXBRL und Microsoft® Excel XLSX. Der Konvertierungsprozess ist einfach, laden Sie zuerst die Datei über die XbrlDocument-Klasse. Verwenden Sie die SaveOptions-Klasse für SaveFormat, die als Parameter in der save-Methode der XbrlDocument-Klasse verwendet werden soll. Zum Speichern in einer iXBLR-Datei wird SaveFormat.IXBRL verwendet, und zum Exportieren in das XLSX-Format wird SaveFormat.XLSX verwendet.

{{% blocks/products/pf/feature-page-code h3="Python Code zum Exportieren von XBRL nach iXBRL" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-xbrl-to-ixbrl.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Python Code für die Umwandlung von XBRL in XLSX" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-xbrl-to-xlsx.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xbrl-to-ixbrl xbrl-to-xlsx" >}}