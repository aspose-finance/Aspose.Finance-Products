---
title: Validieren Sie Finanzberichte über Python
url: /de/python-net/validate/
description:  Python-Code zum Validieren von Finanzberichten in XBRL- und iXBRL-Dateien über die Python-Bibliothek.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Validieren Sie Finanzberichtsdateien über Python" h2="Validierung von Finanzberichtsformaten einschließlich XBRL und iXBRL in Python-basierten Anwendungen." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance für Python über .NET](https://products.aspose.com/finance/python-net/) ist eine funktionsreiche, erweiterbare und benutzerfreundliche Finanzberichtsverarbeitung API. Entwickler können ganz einfach XBRL- und iXBRL-Formate für Finanz- und Geschäftslösungen laden, validieren, anzeigen oder erstellen. API stellt die Klassen XbrlDocument und InlineXbrlDocument zum Laden von XBRL- und iXBRL-Dateien bereit.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Validieren Sie XBRL Dokument" %}}

Die Validierung der XBRL-Datei ist für eine Reihe von Fällen erforderlich, z. B. um zu überprüfen, ob die Daten die richtige Struktur und das richtige Format haben. Um XBLR-Dokumente zu validieren, verwenden Sie zunächst die Klasse XbrlDocument, um die Datei XBRL zu laden. Um die Methode validate der Klasse XbrlInstance zu verwenden, initialisieren Sie zunächst die XbrlInstanceCollection mit dem XbrlDocument-Objekt XbrlInstances. Durchlaufen Sie jede XbrlInstance.ValidationErrors, um den richtigen Fehlercode zu erhalten, und handeln Sie entsprechend, indem Sie die benutzerdefinierten Fehlermeldungen auf der Konsole drucken oder in eine Datei schreiben.

{{% blocks/products/pf/feature-page-code h3="Python Code zum Validieren der Datei XBRL" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "validate-xbrl-instance-file.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Validieren Sie iXBRL Dokument" %}}

Laden Sie es für die iXLRB-Validierung über die InlineXbrlDocument-Klasse und verwenden Sie die Methode validate(). In der ValidationErrorCode-Enumeration werden Validierungsfehlercodes für jede Validierungsregel definiert. Einige der Codes sind ContextPeriodNoStartTime, ContextPeriodNoEndTime, ContextPeriodStartAfterEnd, ContextInstantNoTime, ContextScenarioXbrlNamespace, ContextScenarioXbrlSubstitutionGroup usw. Entwickler können Codes von Endbenutzern debuggen und anzeigen oder die Richtung zur Lösung des Problems aufzeigen.

{{% blocks/products/pf/feature-page-code h3="Python Code zum Validieren des Dokuments iXBRL" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "validate-ixbrl-file.py" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Validate" >}}
{{< /blocks/products/pf/feature-page-wrap >}}