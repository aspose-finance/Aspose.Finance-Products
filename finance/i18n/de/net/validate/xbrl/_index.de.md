---
title: Validiere XBRL Datei über C#
description: Beispielcode für die Dateivalidierung XBRL. Verwenden Sie API-Beispielcode, um Batch-XBRL-Dateien in .NET-basierten Anwendungen zu validieren. 
url: /de/net/validate/xbrl/
family: finance
platformtag: net
feature: validate
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Validiere XBRL Dateien über C#" h2="Validierung von Finanzberichten im XBRL-Format, ohne dass Microsoft Office oder andere Software installiert sein muss." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="So validieren Sie XBRL-Dateien" %}}

Befolgen Sie die Schritte im Code-Snippet oder erweitern Sie es gemäß Ihren Anwendungsanforderungen zum Validieren von Dokumenten in der erweiterbaren Sprache für Geschäftsberichte XBRL. Stellen Sie sicher, dass Ihre Anwendung Validierungsanforderungen enthält.

1. Laden Sie die Datei XBRL mit [XbrlDocument-Klasse](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Beispiel.1. Um die Gültigkeit der geladenen Datei zu überprüfen, damit sie mit übereinstimmen muss [XBRL Spezifikation](http://www.xbrl.org/specification/inlinexbrl-part1/rec-2013-11-18/inlinexbrl-part1-rec-2013-11-18.html)1. Um die Gültigkeit zu überprüfen, verwenden Sie [Bestätigen()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) Methode von [XbrlInstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance) Klasse.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Validierungsanforderung" %}}
Um mit der Validierung von XBRL-Dokumenten fortzufahren, ist .NET Finance API die Hauptanforderung, die in den Antrag aufgenommen werden muss. 
- Installieren Sie es über die Befehlszeile als ```nuget install Aspose.Finance``` oder über die Package Manager Console von Visual Studio mit ```Install-Package Aspose.Finance```.
- Alternativ können Sie den Offline-MSI-Installer oder DLLs in einer ZIP-Datei herunterladen [Downloads](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# Code zum Validieren von XBRL Dateien" offSpacer="" %}}

{{< gist "aspose-com-gists" "1272da1f804f8cef122600269db09fbb" "validate-xbrl-instance-file.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Andere Validierungsoptionen" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/validate/ixbrl/" name="XBRL" description="Erweiterbare Inline-Business-Reporting-Sprache" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}