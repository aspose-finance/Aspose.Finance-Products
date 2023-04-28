---
title: Validieren Sie Finanzberichte über .NET
url: /de/net/validate/
description:  C#-Code zum Validieren von Finanzberichten in XBRL- und iXBRL-Dateien über die .NET-Bibliothek.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Validieren Sie Finanzberichtsdateien über C#" h2="Validierung von Finanzberichtsformaten einschließlich XBRL und iXBRL in .NET-basierten Anwendungen." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) ist eine funktionsreiche, erweiterbare und benutzerfreundliche Finanzberichtsverarbeitung API. Entwickler können ganz einfach XBRL- und iXBRL-Formate für Finanz- und Geschäftslösungen laden, validieren, anzeigen oder erstellen. API bietet [XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Klasse und  [InlineXbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) Klasse zum Laden von XBRL- und iXBRL-Dateien.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Validieren Sie XBRL Dokument" %}}

Die Validierung der XBRL-Datei ist für eine Reihe von Fällen erforderlich, z. B. um zu überprüfen, ob die Daten die richtige Struktur und das richtige Format haben. Um XBLR-Dokumente zu validieren, verwenden Sie zunächst die Klasse XbrlDocument, um die Datei XBRL zu laden. Um die zu verwenden [bestätigen()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) Methode von [XbrlInstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance) Klasse, initialisieren Sie zuerst die [XbrlInstanceCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) mit XbrlDocument-Objekt XbrlInstances. Iterieren Sie durch jeden [XbrlInstance.ValidationErrors](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/properties/validationerrors) um den richtigen Fehlercode zu erhalten und entsprechend zu handeln, indem Sie die benutzerdefinierten Fehlermeldungen auf der Konsole drucken oder in eine Datei schreiben.

{{% blocks/products/pf/feature-page-code h3="C# Code zum Validieren der Datei XBRL" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-xbrl-file.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Validieren Sie iXBRL Dokument" %}}

Laden Sie es für die iXLRB-Validierung über [InlineXbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) Klasse und verwenden Sie ihre Methode Validate(). Im [Validierungsfehlercode](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.validator/validationerrorcode) Enumeration werden Validierungsfehlercodes für jede Validierungsregel definiert. Einige der Codes sind ContextPeriodNoStartTime, ContextPeriodNoEndTime, ContextPeriodStartAfterEnd, ContextInstantNoTime, ContextScenarioXbrlNamespace, ContextScenarioXbrlSubstitutionGroup usw. Entwickler können Codes von Endbenutzern debuggen und anzeigen oder die Richtung zur Lösung des Problems aufzeigen.

{{% blocks/products/pf/feature-page-code h3="C# Code zum Validieren des Dokuments iXBRL" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-ixbrl-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Validate" >}}
{{< /blocks/products/pf/feature-page-wrap >}}