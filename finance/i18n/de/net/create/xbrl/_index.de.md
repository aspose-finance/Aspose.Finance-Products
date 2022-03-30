---
title: XBRL-Datei über C# erstellen
description: Beispielcode für die Dateierstellung XBRL. Verwenden Sie API Beispielcode für die Batch-Generierung von XBRL Dateien in .NET-basierten Anwendungen. 
url: /de/net/create/xbrl/
family: finance
platformtag: net
feature: create
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Erstellen Sie XBRL Dateien über C#" h2="XBRL-Dateien erstellen, ohne dass Microsoft Office oder andere Software installiert sein muss." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="So erstellen Sie XBRL-Dateien" %}}

Befolgen Sie die Schritte im Code-Snippet oder erweitern Sie es je nach Bedarf Ihrer Anwendung, um erweiterbare XBRL-Dateien für die Geschäftsberichtssprache zu generieren. Stellen Sie sicher, dass Ihre Anwendung Erstellungsanforderungen enthält.

1. Schaffen [XbrlDocument-Klasse](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Beispiel.1. So erstellen Sie ein neues XBRL-Instanzdokument [XbrlInstanceCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) und [XbrlInstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance).1. Schemareferenz hinzufügen mit [SchemaRefCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemarefcollection)1. Fügen Sie je nach Art der Anwendung Kontext, Einheit, Element, Fußnotenlink und mehr hinzu.1. Ruf den ... an [Methode speichern](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) durch Angabe des Zieldateipfads.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Erstellungsvoraussetzung" %}}
Um mit der Generierung von XBRL Dokumenten fortzufahren, ist .NET Finance API die Hauptanforderung, die in die Bewerbung aufgenommen werden muss. 
- Installieren Sie es über die Befehlszeile als ```nuget install Aspose.Finance``` oder über die Package Manager Console von Visual Studio mit ```Install-Package Aspose.Finance```.
- Alternativ können Sie den Offline-MSI-Installer oder DLLs in einer ZIP-Datei herunterladen [Downloads](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# Code für die Erstellung von XBRL Dateien" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-schema-reference.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Andere Erstellungsoptionen" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="OFX Anfrage" description="1.03- oder 2.2-Format" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-response/" name="OFX Antwort" description="1.03- oder 2.2-Format" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}