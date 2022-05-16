---
title: Maak OFX Reactiebestand via C#
description: Voorbeeldcode voor het maken van OFX antwoordbestand. Gebruik API voorbeeldcode voor het genereren van batch-OFX responsbestanden binnen .NET-gebaseerde applicaties. 
url: /nl/net/create/ofx-response/
family: finance
platformtag: net
feature: create
informat: OFX Response
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Maak OFX Reactiebestanden via C#" h2="OFX maken van responsbestanden zonder dat Microsoft Office of andere software hoeft te worden geïnstalleerd." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Hoe u OFX antwoordbestanden maakt" %}}

Volg de stappen in het codefragment of verbeter het naar gelang uw toepassingsbehoeften nadat u de aanmaakvereisten binnen uw toepassing hebt vervuld.

1. Creëren [OfxResponseDocument klasse](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) voorwerp.1. Wijs de relevante eigenschappen toe met behulp van verschillende klassen geleverd door API like [Aanmeldingsreactie](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse),  [Verklaring TransactieReactie](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse), [Afschrift Transactie](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction)1. Gebruik de ofxVersion V2x of V1x voor respectievelijk xml- en sgml-bestanden van [OfxVersieEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) als parameter in de methode Opslaan.1. Bel de [Opslaan methode](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument/methods/save) door het doelbestand en ofxVersion op te geven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Aanmaakvereiste:" %}}
Om door te gaan met het maken van OFX Reactiebestand, is .NET Finance API de belangrijkste vereiste die moet worden opgenomen in de toepassing voor het genereren van rapporten. 
- Installeer het via de opdrachtregel als ```nuget install Aspose.Finance``` of via Package Manager Console van Visual Studio met ```Install-Package Aspose.Finance```.
- U kunt ook het offline MSI-installatieprogramma of DLL's in een ZIP-bestand downloaden van: [downloads](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# code voor het maken van OFX responsbestanden" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Andere aanmaakopties" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="OFX Bestand aanvragen" description="1.03 of 2.2 Formaat" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/xbrl/" name="XBRL Bestand" description="Uitbreidbare taal voor bedrijfsrapportage" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}