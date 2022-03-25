---
title: Erstellen Sie OFX Antwort datei über C#
description: Beispielcode für die Erstellung von OFX Antwort datei. Verwenden Sie API Beispielcode für die Generierung von Stapel-OFX-Antwort dateien in .NET-basierten Anwendungen. 
url: /de/net/create/ofx-response/
family: finance
platformtag: net
feature: create
informat: OFX Response
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Erstellen Sie OFX Antwort dateien über C#" h2="Erstellung von OFX Antwort dateien, ohne dass Microsoft Office oder andere Software installiert werden muss." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="So erstellen Sie OFX Antwort dateien" %}}

Befolgen Sie die Schritte im Code-Snippet oder verbessern Sie es nach den Anforderungen Ihrer Anwendung, nachdem Sie die Erstellung sanford rungen in Ihrer Anwendung haben.

1. Erstellen [OfxResponse Document-Klasse](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) Objekt.1. Weisen Sie die relevanten Eigenschaften mit verschiedenen Klassen zu, die von API wie [Signon Response](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse),  [Erklärung Transaction Response](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse), [Erklärung transaktion](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction)1. Verwenden Sie die ofxVersion V2x oder V1x für xml bzw. sgml-Dateien von [OfxVersion Enum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) Als Parameter in Save-Methode.1. Rufen Sie die [Methode speichern](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument/methods/save) Durch Bereitstellung der Zieldatei und ofxVersion.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Schöpfung sanford erung" %}}
Um mit der Erstellung von OFX Antwort dateien fortzufahren, ist .NET Finance API die Haupt anforderung, die in die Anwendung zur Berichts generierung aufgenommen werden muss. 
- Installieren Sie es über die Befehlszeile als "nuget install Aspose.Finance" oder über die Package Manager-Konsole von Visual Studio mit "Install-Package Aspose.Finance".
- Alternativ können Sie das Offline-MSI-Installation programm oder DLLs in einer ZIP-Datei von [Downloads](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C#-Code für die Erstellung von OFX Antwort dateien" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Andere Erstellung optionen" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="OFX Antrags datei" description="1,03 oder 2.2 Format" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/xbrl/" name="XBRL Datei" description="Extensible Business Reporting Sprache" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}