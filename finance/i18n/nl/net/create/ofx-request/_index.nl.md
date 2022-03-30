---
title: Maak OFX aanvraagbestand via C#
description: Voorbeeldcode voor het maken van OFX verzoekbestand. Gebruik API voorbeeldcode voor het genereren van batch-OFX aanvraagbestanden binnen .NET-gebaseerde applicaties. 
url: /nl/net/create/ofx-request/
family: finance
platformtag: net
feature: create
informat: OFX Request
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Maak OFX aanvraagbestanden via C#" h2="OFX verzoek om het maken van bestanden zonder dat Microsoft Office of andere software hoeft te worden geïnstalleerd." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Hoe u OFX aanvraagbestanden maakt" %}}

Nadat u de OFXvereisten voor het maken van bestanden voor het maken van bestanden in uw toepassing hebt ontvangen, volgt u de stappen in het codefragment of verbetert u deze naar wens.

1. Creëren [OfxRequestDocument klasse](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) voorwerp.1. Wijs de relevante eigenschappen toe met behulp van verschillende klassen geleverd door API like [Aanmeldingsverzoek](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonrequest), [Financiele instelling](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/financialinstitution), [Verklaring TransactieVerzoek](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionrequest)1. Gebruik de ofxVersion V2x of V1x voor respectievelijk xml- en sgml-bestanden van [OfxVersieEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) als parameter in de methode Opslaan.1. Bel de [Opslaan methode](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument/methods/save) door het doelbestand en ofxVersion op te geven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Aanmaakvereiste:" %}}
Om door te gaan met OFX Aanmaken van bestand aanvragen, is .NET Finance API de belangrijkste vereiste die moet worden opgenomen in de toepassing voor het genereren van rapporten. 
- Installeer het via de opdrachtregel als ```nuget install Aspose.Finance``` of via de Package Manager Console van Visual Studio met ```Install-Package Aspose.Finance```.
- U kunt ook het offline MSI-installatieprogramma of DLL's in een ZIP-bestand downloaden van: [downloads](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# code voor het maken van OFX verzoekbestanden" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-request-files.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Andere aanmaakopties" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-response/" name="OFX Reactiebestand" description="1.03 of 2.2 Formaat" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/xbrl/" name="XBRL Bestand" description="Uitbreidbare taal voor bedrijfsrapportage" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}