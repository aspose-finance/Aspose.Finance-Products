---
title: Erstellen Sie Finanzberichte über .NET
url: /de/net/create/
description:  C#-Code zum Erstellen von Finanzberichten in XBRL und OFX Anforderungs- oder Antwortdateien über die .NET-Bibliothek.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Erstellen Sie Finanzberichtsdateien über C#" h2="Erstellung von Finanzberichtsformaten, einschließlich XBRL- und OFX-Anforderungs- oder Antwortdatei im 1.03- oder 2.2-Format in .NET-basierten Anwendungen." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) ist eine funktionsreiche, erweiterbare und benutzerfreundliche Erstellung und Verarbeitung von Finanzberichten API. Entwickler können ganz einfach eine XBRL-Instanz von Grund auf neu erstellen sowie Schemareferenzen, Kontexte, Einheiten, Elemente, Fußnoten-Links, Rollenreferenzen und hinzufügen 
Arc-Rollenreferenz. API bietet relevante Klasse für jede Funktion, z. B. für Kontext, die Entwickler verwenden können [ContextPeriode](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextperiod), [ContextEntity](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextentity) und [Kontext](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/context). 
Darüber hinaus unterstützt API auch die Anforderungs-/Antworterstellung im offenen Finanzaustauschformat (OFX) im 1.03- oder 2.2-Format.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Datei XBRL durch Hinzufügen von Element erstellen" %}}

Um die XBRL-Datei zu erstellen und dem Dokument ein Element hinzuzufügen, ist der Prozess „Erstellen“. [XbrlDocument-Klasse](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Beispiel. Bereiten Sie relevante Einstellungen für das Element vor, indem Sie geeignete API-Klassen verwenden, z [SchemaRef-Klasse](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemaref)relevante Kontextklassen wie oben erwähnt und [Konzeptklasse](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/concept). Endlich definieren und initialisieren [Artikelklasse](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/item) Eigenschaften sowie Aufruf der [Methode speichern](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) zu [erstelle XBRL](https://products.aspose.com/finance/net/create/xbrl/) Datei auf die Festplatte.

{{% blocks/products/pf/feature-page-code h3="C# Code zum Erstellen der Datei XBRL durch Hinzufügen eines Elements" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-item.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Erstellen Sie OFX Anforderungs- und Antwortdateien" %}}


Zum Generieren von OFX-Dateien stellt API bereit [OfxRequestDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) und [OfxResponseDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) Klassen und Entwickler können leicht [OFX Anfrage erstellen](https://products.aspose.com/finance/net/create/ofx-request/) und Antwortdateien in den Formaten 1.03 und 2.2. Zum Initialisieren von OfxRequestDocument-Eigenschaften stellt API auch andere Klassen wie z [SignonRequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonrequest), [Finanzinstitution](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/financialinstitution) und [StatementTransactionRequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionrequest) Klassen. In ähnlicher Weise stellt API zum Initialisieren von OfxResponseDocument-Eigenschaften unterstützende Klassen wie z [SignonResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse),  [StatementTransactionResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse) und [AnweisungTransaktion](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction). Unten sind die Codeausschnitte für beide Fälle mit der Verwendung relevanter geeigneter Klassen.

{{% blocks/products/pf/feature-page-code h3="C# Code zum Generieren von OFX Anforderungsdokumenten" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Code zum Generieren von OFX Antwortdokumenten" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
{{< /blocks/products/pf/feature-page-wrap >}}