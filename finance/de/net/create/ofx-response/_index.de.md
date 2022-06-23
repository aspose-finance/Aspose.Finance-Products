---
title: OFX Antwortdatei über C# erstellen
description: Beispielcode für die Erstellung der OFX-Antwortdatei. Verwenden Sie API Beispielcode für die Batch-Generierung von OFX Antwortdateien in .NET-basierten Anwendungen. 
url: /de/net/create/ofx-response/
family: finance
platformtag: net
feature: create
informat: OFX Response
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="OFX Antwortdateien über C# erstellen" h2="OFX Erstellung von Antwortdateien, ohne dass Microsoft Office oder andere Software installiert sein muss." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="So erstellen Sie OFX-Antwortdateien" %}}

Befolgen Sie die Schritte im Code-Snippet oder erweitern Sie es gemäß Ihren Anwendungsanforderungen, nachdem Sie die Erstellungsanforderungen in Ihrer Anwendung festgelegt haben.

1. Schaffen [OfxResponseDocument-Klasse](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) Objekt.1. Weisen Sie die relevanten Eigenschaften mithilfe verschiedener Klassen zu, die von API like bereitgestellt werden [SignonResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse),  [StatementTransactionResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse), [AnweisungTransaktion](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction)1. Verwenden Sie die ofxVersion V2x oder V1x für xml- bzw. sgml-Dateien ab [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) als Parameter in der Save-Methode.1. Ruf den [Methode speichern](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument/methods/save) indem Sie die Zieldatei und ofxVersion angeben.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Erstellungsvoraussetzung" %}}
Um mit der Erstellung der OFX Antwortdatei fortzufahren, ist .NET Finance API die Hauptanforderung, die in die Berichterstellungsanwendung aufgenommen werden muss. 
- Installieren Sie es über die Befehlszeile als ```nuget install Aspose.Finance``` oder über die Package Manager Console von Visual Studio mit ```Install-Package Aspose.Finance```.
- Alternativ können Sie den Offline-MSI-Installer oder DLLs in einer ZIP-Datei herunterladen [Downloads](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# Code für die Erstellung von OFX Antwortdateien" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Andere Erstellungsoptionen" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="OFX Datei anfordern" description="1.03- oder 2.2-Format" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/xbrl/" name="XBRL Datei" description="Erweiterbare Sprache für die Geschäftsberichterstattung" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}