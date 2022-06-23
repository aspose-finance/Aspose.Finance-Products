---
title: OFX Anforderungsdatei über C# erstellen
description: Beispielcode für die Erstellung der Anforderungsdatei OFX. Verwenden Sie API Beispielcode für die Batch-Generierung von OFX Anforderungsdateien in .NET-basierten Anwendungen. 
url: /de/net/create/ofx-request/
family: finance
platformtag: net
feature: create
informat: OFX Request
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Erstellen Sie OFX Anforderungsdateien über C#" h2="OFX Fordern Sie die Erstellung von Dateien an, ohne dass Microsoft Office oder andere Software installiert sein muss." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="So erstellen Sie OFX-Anforderungsdateien" %}}

Nachdem Sie die OFX-Anforderungen zum Erstellen von Dateien in Ihrer Anwendung erfüllt haben, befolgen Sie die Schritte im Code-Snippet oder erweitern Sie es gemäß Ihren Anforderungen.

1. Schaffen [OfxRequestDocument-Klasse](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) Objekt.1. Weisen Sie die relevanten Eigenschaften mithilfe verschiedener Klassen zu, die von API like bereitgestellt werden [SignonRequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonrequest), [Finanzinstitution](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/financialinstitution), [StatementTransactionRequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionrequest)1. Verwenden Sie die ofxVersion V2x oder V1x für xml- bzw. sgml-Dateien ab [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) als Parameter in der Save-Methode.1. Ruf den [Methode speichern](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument/methods/save) indem Sie die Zieldatei und ofxVersion angeben.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Erstellungsvoraussetzung" %}}
Um mit der Erstellung der OFX Anforderungsdatei fortzufahren, ist .NET Finance API die Hauptvoraussetzung, um in die Berichterstellungsanwendung aufgenommen zu werden. 
- Installieren Sie es über die Befehlszeile als ```nuget install Aspose.Finance``` oder über die Package Manager Console von Visual Studio mit ```Install-Package Aspose.Finance```.
- Alternativ können Sie den Offline-MSI-Installer oder DLLs in einer ZIP-Datei herunterladen [Downloads](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C#-Code für die Erstellung von OFX Anforderungsdateien" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-request-files.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Andere Erstellungsoptionen" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-response/" name="OFX Antwortdatei" description="1.03- oder 2.2-Format" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/xbrl/" name="XBRL Datei" description="Erweiterbare Sprache für die Geschäftsberichterstattung" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}