﻿---
title: Maak XBRL Bestand via C#
description: Voorbeeldcode voor het maken van XBRL-bestanden. Gebruik API voorbeeldcode voor het genereren van batchbestanden XBRL binnen op .NET gebaseerde applicaties. 
url: /nl/net/create/xbrl/
family: finance
platformtag: net
feature: create
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Maak XBRL bestanden via C#" h2="XBRL bestanden maken zonder dat Microsoft Office of andere software hoeft te worden geïnstalleerd." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Hoe u XBRL bestanden maakt" %}}

Volg de stappen in het codefragment of verbeter het naar gelang uw toepassingsbehoeften voor het genereren van uitbreidbare taalbestanden voor bedrijfsrapportage XBRL. Zorg ervoor dat u aanmaakvereisten hebt binnen uw toepassing.

1. Creëren [XbrlDocument-klasse](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Voorbeeld.1. Een nieuw XBRL instantiedocument maken [XbrlInstanceCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) en [XbrlInstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance).1. Schemareferentie toevoegen met [SchemaRefVerzameling](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemarefcollection)1. Voeg afhankelijk van de aard van de toepassing context, eenheid, item, voetnootlink en meer toe.1. Bel de [Opslaan methode](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) door het doelbestandspad op te geven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Aanmaakvereiste:" %}}
Om door te gaan met het genereren van XBRL documenten, is .NET Finance API de belangrijkste vereiste die moet worden opgenomen in de toepassing. 
- Installeer het via de opdrachtregel als ```nuget install Aspose.Finance``` of via de Package Manager Console van Visual Studio met ```Install-Package Aspose.Finance```.
- U kunt ook het offline MSI-installatieprogramma of DLL's in een ZIP-bestand downloaden van: [downloads](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# code voor het maken van XBRL bestanden" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-schema-reference.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Andere aanmaakopties" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="OFX Verzoek" description="1.03 of 2.2 Formaat" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-response/" name="OFX Reactie" description="1.03 of 2.2 Formaat" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}