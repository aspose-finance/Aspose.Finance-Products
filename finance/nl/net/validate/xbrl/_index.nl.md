---
title: Valideer XBRL Bestand via C#
description: Voorbeeldcode voor XBRL bestandsvalidatie. Gebruik API voorbeeldcode om batchbestanden XBRL binnen .NET-gebaseerde applicaties te valideren. 
url: /nl/net/validate/xbrl/
family: finance
platformtag: net
feature: validate
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Valideer XBRL bestanden via C#" h2="Financiële rapporten valideren in XBRL-indeling zonder dat Microsoft Office of andere software hoeft te worden geïnstalleerd." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Hoe u XBRL bestanden kunt valideren" %}}

Volg de stappen in het codefragment of verbeter het naar gelang uw toepassingsbehoeften voor het valideren van uitbreidbare documenten in de taal voor bedrijfsrapportage XBRL. Zorg ervoor dat u valideringsvereisten hebt in uw toepassing.

1. Laad XBRL bestand met [XbrlDocument-klasse](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Voorbeeld.1. Om de geldigheid van het geladen bestand te controleren, zodat het moet overeenkomen met: [XBRL specificatie](http://www.xbrl.org/specification/inlinexbrl-part1/rec-2013-11-18/inlinexbrl-part1-rec-2013-11-18.html)1. Gebruik . om de validiteit te controleren [valideren()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) methode van [XbrlInstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance) klas.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Validatievereiste:" %}}
Om door te gaan met het valideren van XBRL documenten, is .NET Finance API de belangrijkste vereiste die moet worden opgenomen in de aanvraag. 
- Installeer het via de opdrachtregel als ```nuget install Aspose.Finance``` of via de Package Manager Console van Visual Studio met ```Install-Package Aspose.Finance```.
- U kunt ook het offline MSI-installatieprogramma of DLL's in een ZIP-bestand downloaden van: [downloads](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# code om XBRL bestanden te valideren" offSpacer="" %}}

{{< gist "aspose-com-gists" "1272da1f804f8cef122600269db09fbb" "validate-xbrl-instance-file.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Andere validatieopties" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/validate/ixbrl/" name="XBRL" description="Inline uitbreidbare taal voor bedrijfsrapportage" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}