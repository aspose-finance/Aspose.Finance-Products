---
title: XBRL bestand aanmaken via C#
description: Voorbeeldcode voor het maken van XBRL bestanden. Gebruik API voorbeeldcode voor het genereren van XBRL bestanden in .NET toepassingen. 
url: /nl/net/create/xbrl/
family: finance
platformtag: net
feature: create
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="XBRL bestanden aanmaken via C#" h2="XBRL bestanden maken zonder dat Microsoft Office geïnstalleerd of andere software nodig is." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Hoe XBRL bestanden te maken" %}}

Volg de stappen in het codefragment of verbeter het vanaf de behoeften van uw toepassing voor het genereren van uitbreidbare zakelijke rapportagetaal XBRL bestanden. Zorg ervoor dat u aanmaakvereisten hebt binnen uw aanvraag.

1. Creëer [Klasse XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Aanleg.1. Een nieuw XBRL instantiedocument maken [XbrlInstanceCollectie](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) En [XbrlInstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance).1. Schema-referentie toevoegen met behulp van [SchemaRefCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemarefcollection)1. Afhankelijk van de toepassing de natuur toe te voegen context, eenheid, item, voetnoot link en meer.1. Bel de [Bewaarmethode](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) Door het doelbestandspad te bieden.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Creatievereiste" %}}
Als u wilt doorgaan met het genereren van XBRL documenten, is .NET Finance API de belangrijkste vereiste om in de toepassing te worden opgenomen. 
- Installeer het via de opdrachtregel als '''nuget install Aspose.Finance''' of via Package Manager Console van Visual Studio met '''' Install-Package Aspose.Finance''.
- Als alternatief kunt u het offline MSI-installatieprogramma of DLL's in een ZIP-bestand van [Downloads](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# code voor het maken van XBRL bestanden" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-schema-reference.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Andere creatie-opties" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="OFX verzoek" description="1.03 of 2.2 Formaat" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-response/" name="OFX Reactie" description="1.03 of 2.2 Formaat" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}