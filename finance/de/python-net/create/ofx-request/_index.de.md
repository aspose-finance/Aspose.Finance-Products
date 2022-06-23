---
title: OFX Anforderungsdatei über Python erstellen
description: Beispielcode für die Erstellung der Anforderungsdatei OFX. Verwenden Sie API Beispielcode für die Batch-Generierung von OFX Anforderungsdateien in Python-basierten Anwendungen. 
url: /de/python-net/create/ofx-request/
family: finance
platformtag: python
feature: create
informat: OFX Request
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Erstellen Sie OFX Anforderungsdateien über Python" h2="OFX Fordern Sie die Erstellung von Dateien an, ohne dass Microsoft Office oder andere Software installiert sein muss." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="So erstellen Sie OFX-Anforderungsdateien" %}}

Nachdem Sie die OFX-Anforderungen zum Erstellen von Dateien in Ihrer Anwendung erfüllt haben, befolgen Sie die Schritte im Code-Snippet oder erweitern Sie es gemäß Ihren Anforderungen.

1. Erstellen Sie ein OfxRequestDocument-Klassenobjekt.2. Weisen Sie die relevanten Eigenschaften zu, indem Sie verschiedene Klassen verwenden, die von API bereitgestellt werden, wie SignonRequest, FinancialInstitution], StatementTransactionRequest
3. Verwenden Sie die ofxVersion V2x oder V1x für xml- bzw. sgml-Dateien aus OfxVersionEnum als Parameter in der Save-Methode.
4. Rufen Sie die save-Methode auf, indem Sie die Zieldatei und ofxVersion angeben.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Erstellungsvoraussetzung" %}}
Stellen Sie sicher, dass Sie die folgenden Voraussetzungen erfüllen, um mit der Erstellung der OFX Anforderungsdatei fortzufahren. 
- Microsoft Windows- oder Linux-basiertes Betriebssystem.- Python 3.5 oder höher.- Aspose.Finance für Python, auf die in Ihrem Projekt verwiesen wird.{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python-Code für die Erstellung von OFX Anforderungsdateien" offSpacer="" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-request-files.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Andere Erstellungsoptionen" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/ofx-response/" name="OFX Antwortdatei" description="1.03- oder 2.2-Format" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/xbrl/" name="XBRL Datei" description="Erweiterbare Sprache für die Geschäftsberichterstattung" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}