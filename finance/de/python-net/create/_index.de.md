---
title: Erstellen Sie Finanzberichte über Python
url: /de/python-net/create/
description:  Python-Code zum Erstellen von Finanzberichten in XBRL und OFX Anforderungs- oder Antwortdateien über die Python-Bibliothek.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Erstellen Sie Finanzberichtsdateien über Python" h2="Erstellung von Finanzberichtsformaten, einschließlich XBRL- und OFX-Anforderungs- oder Antwortdatei im 1.03- oder 2.2-Format in Python-basierten Anwendungen." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance für Python über .NET](https://products.aspose.com/finance/python-net/) ist eine funktionsreiche, erweiterbare und benutzerfreundliche Erstellung und Verarbeitung von Finanzberichten API. Entwickler können ganz einfach eine XBRL-Instanz von Grund auf neu erstellen sowie Schemareferenzen, Kontexte, Einheiten, Elemente, Fußnoten-Links, Rollenreferenzen und hinzufügen 
Arc-Rollenreferenz. API stellt relevante Klassen für jede Funktion bereit, z. B. für den Kontext können Entwickler ContextPeriod, ContextEntity und Context verwenden. 
Darüber hinaus unterstützt API auch die Anforderungs-/Antworterstellung im offenen Finanzaustauschformat (OFX) im 1.03- oder 2.2-Format.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Datei XBRL durch Hinzufügen von Element erstellen" %}}

Um die XBRL-Datei zu erstellen und ein Element in das Dokument einzufügen, müssen Sie eine XbrlDocument-Klasseninstanz erstellen. Bereiten Sie relevante Einstellungen für das Element vor, indem Sie geeignete API-Klassen verwenden, z. B. die SchemaRef-Klasse, relevante Kontextklassen wie oben erwähnt und die Concept-Klasse. Definieren und initialisieren Sie schließlich die Eigenschaften der Item-Klasse und rufen Sie die Methode save auf, um die Datei XBRL auf der Festplatte zu erstellen.

{{% blocks/products/pf/feature-page-code h3="Python Code zum Erstellen der Datei XBRL durch Hinzufügen eines Elements" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-xbrl-file-and-add-item.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Erstellen Sie OFX Anforderungs- und Antwortdateien" %}}


Zum Generieren von OFX-Dateien stellt API die Klassen OfxRequestDocument und OfxResponseDocument bereit, und Entwickler können dies problemlos tun [OFX Anfrage erstellen](https://products.aspose.com/finance/python-net/create/ofx-request/) und Antwortdateien in den Formaten 1.03 und 2.2. Zum Initialisieren von OfxRequestDocument-Eigenschaften stellt API auch andere Klassen wie SignonRequest-, FinancialInstitution- und StatementTransactionRequest-Klassen bereit. In ähnlicher Weise stellt API zum Initialisieren von OfxResponseDocument-Eigenschaften unterstützende Klassen wie SignonResponse, StatementTransactionResponse und StatementTransaction bereit. Unten sind die Codeausschnitte für beide Fälle mit der Verwendung relevanter geeigneter Klassen.

{{% blocks/products/pf/feature-page-code h3="Python Code zum Generieren von OFX Anforderungsdokumenten" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-response-files.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Python Code zum Generieren von OFX Antwortdokumenten" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-response-files.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
{{< /blocks/products/pf/feature-page-wrap >}}