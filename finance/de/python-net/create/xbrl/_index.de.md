---
title: XBRL-Datei über Python erstellen
description: Beispielcode für die Dateierstellung XBRL. Verwenden Sie API Beispielcode für die Batch-Generierung von XBRL Dateien in Python-basierten Anwendungen. 
url: /de/python-net/create/xbrl/
family: finance
platformtag: python
feature: create
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Erstellen Sie XBRL Dateien über Python" h2="XBRL-Dateien erstellen, ohne dass Microsoft Office oder andere Software installiert sein muss." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="So erstellen Sie XBRL-Dateien" %}}

Befolgen Sie die Schritte im Code-Snippet oder erweitern Sie es je nach Bedarf Ihrer Anwendung, um erweiterbare XBRL-Dateien für die Geschäftsberichtssprache zu generieren. Stellen Sie sicher, dass Ihre Anwendung Erstellungsanforderungen enthält.

1. Erstellen Sie eine XbrlDocument-Klasseninstanz.1. So erstellen Sie ein neues XBRL-Instanzdokument XbrlInstanceCollection und XbrlInstance.1. Schemareferenz mithilfe von SchemaRefCollection hinzufügen1. Fügen Sie je nach Art der Anwendung Kontext, Einheit, Element, Fußnotenlink und mehr hinzu.1. Rufen Sie die save-Methode auf, indem Sie den Zieldateipfad angeben.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Erstellungsvoraussetzung" %}}
Um mit der Generierung von XBRL Dokumenten fortzufahren, stellen Sie sicher, dass Sie die folgenden Voraussetzungen erfüllen. 
- Microsoft Windows- oder Linux-basiertes Betriebssystem.- Python 3.5 oder höher.- Aspose.Finance für Python, auf die in Ihrem Projekt verwiesen wird.{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python Code für die Erstellung von XBRL Dateien" offSpacer="" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-xbrl-file-and-add-schema-reference.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Andere Erstellungsoptionen" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/ofx-request/" name="OFX Anfrage" description="1.03- oder 2.2-Format" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/ofx-response/" name="OFX Antwort" description="1.03- oder 2.2-Format" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}