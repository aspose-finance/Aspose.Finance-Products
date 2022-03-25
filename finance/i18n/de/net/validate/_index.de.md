---
title: Finanz berichte über .NET validieren
url: /de/net/validate/
description:  C#-Code zur Validierung von Finanz berichten in XBRL-und iXBRL-Dateien über die .NET-Bibliothek.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Finanz berichter statt ungs dateien über C# validieren" h2="Validierung von Finanz berichts formaten einschl ießlich XBRL und iXBRL innerhalb von .NET basierten Anwendungen." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) Ist eine funktions reiche, erweiterbare und benutzer freundliche Finanz berichts verarbeitung API. Entwickler können problemlos XBRL-und iXBRL-Formate für Finanz-und Geschäfts lösungen laden, validieren, anzeigen oder erstellen. API stellt zur Verfügung [Xbrl Dokument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Klasse und  [InlineXbrl Dokument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) Klasse zum Laden von XBRL-und iXBRL-Dateien.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Validieren Sie XBRL Dokument" %}}

Die Validierung der XBRL-Datei ist für eine Reihe von Fällen erforderlich, z. B. um zu überprüfen, ob die Daten in der richtigen Struktur und im richtigen Format vorliegen. Um XBLR-Dokumente zu validieren, verwenden Sie zunächst die Xbrl Document-Klasse, um die XBRL-Datei zu laden. Um die [Validieren ()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) Methode der [Xbrl Instance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance) Klasse, erstens initial isieren die [XbrlInstance Collection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) Mit Xbrl Document Objekt Xbrl Instances. Iterieren Sie durch jeden [Xbrl Instance. Validierung fehler](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/properties/validationerrors) Um den richtigen Fehler code zu erhalten und entsprechend zu handeln, indem Sie die angepassten Fehler meldungen auf der Konsole drucken oder innerhalb einer Datei schreiben.

{{% blocks/products/pf/feature-page-code h3="C# Code zum Validieren der XBRL-Datei" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-xbrl-file.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Validieren Sie iXBRL Dokument" %}}

Laden Sie für die iXLRB-Validierung über [InlineXbrl Dokument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) Klasse und verwenden Sie seine Valid ate()-Methode. In [Validierung ErrorCode](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.validator/validationerrorcode) Aufzählung und Validierung fehler codes werden für jede Validierung regel definiert. Nur wenige Codes sind Context Period NoStart Time, Context PeriodNoEndTime, Context Period Start After End, Context InstantNoTime, Context ScenarioXbrl Names pace, Context ScenarioXbrl Substitution Group usw. Entwickler können Codes als Endbenutzer debuggen und anzeigen oder die Richtung zur Lösung des Problems anzeigen.

{{% blocks/products/pf/feature-page-code h3="C# Code zur Validierung von iXBRL Dokument" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-ixbrl-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Validate" >}}