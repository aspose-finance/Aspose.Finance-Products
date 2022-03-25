---
title: Financiële rapporten converteren via .NET
url: /nl/net/conversion/
description:  C# code om financiële rapporten te converteren in XBRL, iXBRL en OFX file-fomats via .NET bibliotheek.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Financiële rapportbestanden converteren via C#" h2="Conversie van financiële rapportindelingen, waaronder XBRL, iXBRL en OFX bestanden van 1.03 naar 2.2 binnen .NET toepassingen." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) Is een functie rijk, uitbreidbaar en gemakkelijk te gebruiken API. Ontwikkelaars kunnen gemakkelijk XBRL instanties, linkbases en taxonomieschema's valideren met behulp van [Valideren () methode](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) Die moeten voldoen aan de syntaxisvereisten die in de specificatie worden opgelegd. Bovendien kunnen ze XBRL, iXBRL formaten lezen en XBRL exemplaar vanaf het begin maken. Bovendien kunnen ze ** XBRL formaat ** converteren naar iXBRL en Microsoft Excel XLSX-bestanden. API ondersteunt ook het maken van aanvragen/reacties in open financiële uitwisseling (OFX) en converteert OFX bestandsaanvraag/-respons van 1.03 naar 2.2-indeling.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="OFX respons converteren en bestanden aanvragen" %}}

API ondersteunt het maken van OFX aanvraag-en antwoordbestanden door twee klassen aan te bieden. [OfxRequestDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) Voor het maken en laden van OFX verzoekbestanden in 1.03 en 2.2 formaat en [OfxResponseDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) Voor OFX responsbestanden in 1.03-en 2.2-indeling. Voorts, [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) Opsomming met leden V1x dat is 1.x versie, sgml bestandsformaat en V2x 2.x versie, xml bestandsformaat. Na het aanroepen van de Save-methode van OfxRequestDocument-klasse of OfxResponseDocument-klasse, kunnen ontwikkelaars eenvoudig converteren van 1.03 sgml-bestand naar 2.2 xml-indeling.


{{% blocks/products/pf/feature-page-code h3="C# code om OFX reactiebestanden te converteren" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-response-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# code om OFX aanvraagbestanden te converteren" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-request-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Omzetting van XBRL financiële rapporten" %}}

API ondersteunt het converteren van XBRL bestanden naar iXBRL en Microsoft®Excel XLSX-formaat. Conversieproces is eenvoudig, ten eerste laad het bestand via [XbrlDocument Klasse](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument). Gebruik de [Klasse Opties Opties](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions) Voor [SaveFormat](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions/properties/saveformat), Te gebruiken als parameter in de Save-methode van XbrlDocument Class. Voor het opslaan in het iXBLR-bestand, [SaveFormat.IXBRL](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveformat) Zal worden gebruikt en voor het exporteren naar XLSX-formaat zal SaveFormat.XLSX worden gebruikt.

{{% blocks/products/pf/feature-page-code h3="C# code om XBRL naar iXBRL te exporteren" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-ixbrl.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# code voor XBRL naar XLSX-conversie" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-xlsx.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xbrl-to-ixbrl xbrl-to-xlsx" >}}