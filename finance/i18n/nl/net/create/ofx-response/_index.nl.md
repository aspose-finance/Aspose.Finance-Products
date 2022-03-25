---
title: Creëer OFX reactiebestand via C#
description: Voorbeeldcode voor het maken van OFX responsbestanden. Gebruik API voorbeeldcode voor het genereren van OFX responsbestanden in .NET toepassingen. 
url: /nl/net/create/ofx-response/
family: finance
platformtag: net
feature: create
informat: OFX Response
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Creëer OFX reactiebestanden via C#" h2="OFX responsbestanden maken zonder dat Microsoft Office geïnstalleerd of andere software nodig is." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="OFX reactiebestanden maken" %}}

Volg de stappen in het codefragment of verbeter het vanaf de behoeften van uw toepassing nadat u de aanmaakvereisten in uw toepassing hebt.

1. Creëer [OfxResponseDocument klasse](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) Object.1. Wijs de relevante eigenschappen toe met behulp van verschillende klassen die worden geleverd door API zoals [SignonReactie](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse),  [StatementTransactionResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse), [Statementtransactie](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction)1. Gebruik de ofxVersion V2x of V1x voor respectievelijk xml-en sgml-bestanden van [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) Als parameter in de methode Opslaan.1. Bel de [Bewaarmethode](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument/methods/save) Door het verstrekken van het doelbestand en ofxVersion.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Creatievereiste" %}}
Om door te gaan voor het maken van OFX Response-bestanden, is .NET Finance API de belangrijkste vereiste om te worden opgenomen in de rapportgeneratietoepassing. 
- Installeer het via de opdrachtregel als '''nuget install Aspose.Finance''' of via Package Manager Console van Visual Studio met '''' Install-Package Aspose.Finance''.
- Als alternatief kunt u het offline MSI-installatieprogramma of DLL's in een ZIP-bestand van [Downloads](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# code voor het maken van OFX responsbestanden" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Andere creatie-opties" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="OFX Bestand aanvragen" description="1.03 of 2.2 Formaat" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/xbrl/" name="XBRL Bestand" description="Uitbreidbare zakelijke rapportagetaal" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}