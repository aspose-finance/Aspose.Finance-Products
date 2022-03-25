---
title: XBRL bestand lezen via C#
description: Voorbeeldcode voor het lezen van XBRL bestanden. Gebruik API voorbeeldcode om batch XBRL-bestanden te lezen binnen .NET gebaseerde applicaties. 
url: /nl/net/read/xbrl/
family: finance
platformtag: net
feature: read
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="XBRL bestanden lezen via C#" h2="Het lezen van financiële rapporten in XBRL formaat zonder dat Microsoft Office geïnstalleerd of andere software." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="XBRL bestanden lezen" %}}

Volg de stappen in het codefragment of verbeter het vanaf de behoeften van uw toepassing voor het lezen van uitbreidbare zakelijke rapportagetaal XBRL bestanden. Zorg ervoor dat u leesvereisten heeft binnen uw toepassing.

1. Creëer [Klasse XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Aanleg.1. Geef de naam van een geldig XBRL bestand door als parameter.1. Om de innerlijke details van het bestand te krijgen, gebruikt u de relevante klassen zoals [SchemaRefCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemarefcollection), [Context](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/context), [Eenheid](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/unit) 
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Leesvereiste" %}}
Als u XBRL documenten wilt lezen, is .NET Finance API de belangrijkste vereiste om in de toepassing te worden opgenomen. 
- Installeer het via de opdrachtregel als '''nuget install Aspose.Finance''' of via Package Manager Console van Visual Studio met '''' Install-Package Aspose.Finance''.
- Als alternatief kunt u het offline MSI-installatieprogramma of DLL's in een ZIP-bestand van [Downloads](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# code om XBRL bestanden te lezen" offSpacer="" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "read-xbrl-file.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Andere leesopties" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/read/ixbrl/" name="iXBRL" description="Inline extensibele zakelijke rapportagetaal" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}