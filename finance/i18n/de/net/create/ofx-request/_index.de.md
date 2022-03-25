---
title: Erstellen Sie OFX Anfrage datei über C#
description: Beispielcode für die Erstellung von OFX-Anforderung dateien. Verwenden Sie API Beispielcode für die Generierung von Stapel-OFX-Anforderung dateien in .NET-basierten Anwendungen. 
url: /de/net/create/ofx-request/
family: finance
platformtag: net
feature: create
informat: OFX Request
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Erstellen Sie OFX Anforderung dateien über C#" h2="OFX Erstellung von Dateien anfordern, ohne dass Microsoft Office oder eine andere Software installiert werden muss." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="So erstellen Sie OFX Anforderung dateien" %}}

Nachdem Sie die Anforderungen für die Erstellung von OFX Dateien in Ihrer Anwendung erstellt haben, befolgen Sie die Schritte im Code-Snippet oder verbessern Sie es ab Ihrer Anforderung.

1. Erstellen [OfxRequestDocument-Klasse](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) Objekt.1. Weisen Sie die relevanten Eigenschaften mit verschiedenen Klassen zu, die von API wie [Signon Request](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonrequest), [Finanz institution](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/financialinstitution), [Erklärung Transaktion antrag](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionrequest)1. Verwenden Sie die ofxVersion V2x oder V1x für xml bzw. sgml-Dateien von [OfxVersion Enum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) Als Parameter in Save-Methode.1. Rufen Sie die [Methode speichern](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument/methods/save) Durch Bereitstellung der Zieldatei und ofxVersion.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Schöpfung sanford erung" %}}
Um mit der Erstellung von OFX Request-Dateien fortzufahren, ist .NET Finance API die Haupt anforderung, die in die Anwendung zur Berichts generierung aufgenommen werden muss. 
- Installieren Sie es über die Befehlszeile als "nuget install Aspose.Finance" oder über die Package Manager-Konsole von Visual Studio mit "Install-Package Aspose.Finance".
- Alternativ können Sie das Offline-MSI-Installation programm oder DLLs in einer ZIP-Datei von [Downloads](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C#-Code für die Erstellung von OFX-Anforderung dateien" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-request-files.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Andere Erstellung optionen" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-response/" name="OFX Antwort datei" description="1,03 oder 2.2 Format" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/xbrl/" name="XBRL Datei" description="Extensible Business Reporting Sprache" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}