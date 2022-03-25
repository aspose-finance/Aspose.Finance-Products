---
title: Erstellen von Finanz berichten über .NET
url: /de/net/create/
description:  C#-Code zum Erstellen von Finanz berichten in XBRL und OFX Anforderung-oder Antwort dateien über .NET Bibliothek.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Erstellen von Financial Reporting-Dateien über C#" h2="Erstellung von Finanz berichts formaten einschl ießlich XBRL-und OFX-Anforderung-oder Antwort datei im Format 1.03 oder 2.2 innerhalb von .NET-basierten Anwendungen." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) Ist eine funktions reiche, erweiterbare und einfach zu verwendende Erstellung und Verarbeitung von Finanz berichten API. Entwickler können auf einfache Weise eine XBRL-Instanz von Grund auf neu erstellen und Schema referenz, Kontext, Einheit, Element, Fußnoten link, Rollen referenz und 
Bogen rollen referenz. API bietet relevante Klasse für jedes Feature, wie z. B. für den Kontext, können Entwickler verwenden [Kontext period](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextperiod), [Kontext heit](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextentity) Und [Kontext](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/context). 
Darüber hinaus unterstützt API auch die Erstellung von Anfragen/Antworten im Open Financial Exchange-Format (OFX) im Format 1.03 oder 2.2.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Erstellen Sie XBRL Datei, indem Sie das Element hinzufügen" %}}

Um XBRL-Datei zu erstellen und Element in das Dokument hinzuzufügen, ist der Prozess, erstellen [Xbrl Document Klasse](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Instanz. Bereiten Sie relevante Einstellungen für Artikel vor, indem Sie geeignete API-Klassen wie z. [SchemaRef-Klasse](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemaref), Relevante Kontext klassen wie oben erwähnt und [Konzept klasse](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/concept). Schließlich definieren und intialisieren [Artikel klasse](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/item) Eigenschaften sowie rufen Sie die [Methode speichern](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) Zu [XBRL erstellen](https://products.aspose.com/finance/net/create/xbrl/) Datei in die Diskette.

{{% blocks/products/pf/feature-page-code h3="C# Code zum Erstellen einer XBRL-Datei durch Hinzufügen von Artikeln" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-item.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="OFX Anforderung-und Antwort dateien erstellen" %}}


Zum Generieren von OFX-Dateien bietet die API [OfxRequest Document](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) Und [OfxResponse Document](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) Klassen und Entwickler können leicht [OFX Anfrage erstellen](https://products.aspose.com/finance/net/create/ofx-request/) Und Antwort dateien in den Formaten 1.03 und 2.2. Zum Initial isieren von OfxRequestDocument-Eigenschaften stellt API auch andere Klassen wie z. [Signon Request](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonrequest), [Finanz institution](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/financialinstitution) Und [Erklärung Transaktion antrag](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionrequest) Klassen. In ähnlicher Weise bietet API für die Intialisierung von OfxResponseDocument-Eigenschaften unterstützende Klassen wie [Signon Response](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse),  [Erklärung Transaction Response](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse) Und [Erklärung transaktion](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction). Nachfolgend finden Sie die Code-Snippets für beide Fälle unter Verwendung einschlägiger geeigneter Klassen.

{{% blocks/products/pf/feature-page-code h3="C# Code zum Generieren von OFX Anfordern von Dokumenten" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Code zur Generierung von OFX Antwort dokumenten" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}