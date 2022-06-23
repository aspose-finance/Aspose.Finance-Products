---
title: OFX Antwortdatei über Python erstellen
description: Beispielcode für die Erstellung der OFX-Antwortdatei. Verwenden Sie API Beispielcode für die Batch-Generierung von OFX Antwortdateien in Python-basierten Anwendungen. 
url: /de/python-net/create/ofx-response/
family: finance
platformtag: python
feature: create
informat: OFX Response
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="OFX Antwortdateien über Python erstellen" h2="OFX Erstellung von Antwortdateien, ohne dass Microsoft Office oder andere Software installiert sein muss." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="So erstellen Sie OFX-Antwortdateien" %}}

Befolgen Sie die Schritte im Code-Snippet oder erweitern Sie es gemäß Ihren Anwendungsanforderungen, nachdem Sie die Erstellungsanforderungen in Ihrer Anwendung festgelegt haben.

1. Erstellen Sie ein OfxResponseDocument-Klassenobjekt.1. Weisen Sie die relevanten Eigenschaften mithilfe verschiedener von API bereitgestellter Klassen wie SignonResponse, StatementTransactionResponse, StatementTransaction zu1. Verwenden Sie die ofxVersion V2x oder V1x für xml- bzw. sgml-Dateien aus OfxVersionEnum als Parameter in der save-Methode.1. Rufen Sie die save-Methode auf, indem Sie die Zieldatei und ofxVersion angeben.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Erstellungsvoraussetzung" %}}
Um mit der Erstellung der OFX-Antwortdatei fortzufahren, stellen Sie sicher, dass Sie die folgenden Voraussetzungen erfüllen. 
- Microsoft Windows- oder Linux-basiertes Betriebssystem.- Python 3.5 oder höher.- Aspose.Finance für Python, auf die in Ihrem Projekt verwiesen wird.{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python Code für die Erstellung von OFX Antwortdateien" offSpacer="" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-response-files.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Andere Erstellungsoptionen" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/ofx-request/" name="OFX Datei anfordern" description="1.03- oder 2.2-Format" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/xbrl/" name="XBRL Datei" description="Erweiterbare Sprache für die Geschäftsberichterstattung" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}