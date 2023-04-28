---
title: Financiële rapporten converteren via .NET
url: /nl/net/conversion/
description:  C# code om financiële rapporten om te zetten in XBRL, iXBRL(inline xbrl) en OFX bestandsformaten via de .NET bibliotheek.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Converteer financiële rapportbestanden via C#" h2="Conversie van financiële rapportformaten inclusief XBRL, iXBRL en OFX bestanden van 1.03 naar 2.2 formaat binnen .NET gebaseerde applicaties." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) is rijk aan functies, uitbreidbaar en gebruiksvriendelijk API. Ontwikkelaars kunnen eenvoudig XBRL instanties, linkbases en taxonomieschema's valideren met [valideer() methode](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) die moeten voldoen aan de in de specificatie gestelde syntaxisvereisten. Bovendien kunnen ze XBRL, iXBRL-indelingen lezen en XBRL-instantie helemaal opnieuw maken. Bovendien kunnen ze **XBRL-indeling** converteren naar iXBRL en Microsoft Excel XLSX-bestanden. API ondersteunt ook open financiële uitwisseling (OFX) formaat verzoek / reactie creatie en converteert OFX bestandsverzoek / antwoord van 1.03 naar 2.2 formaat.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Converteer OFX antwoord- en verzoekbestanden" %}}

API ondersteunt het maken van OFX verzoek- en antwoordbestanden door twee klassen aan te bieden. [OfxVerzoekDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) voor het maken en laden van OFX aanvraagbestanden in 1.03 en 2.2 formaat en [OfxReactieDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) voor OFX antwoordbestanden in de indeling 1.03 en 2.2. Bovendien, [OfxVersieEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) Opsomming met leden V1x dat is 1.x-versie, sgml-bestandsformaat en V2x 2.x-versie, xml-bestandsformaat. Na het aanroepen van de Save-methode van de OfxRequestDocument-klasse of OfxResponseDocument-klasse, kunnen ontwikkelaars eenvoudig het 1.03 sgml-bestand converteren naar het 2.2 xml-formaat.


{{% blocks/products/pf/feature-page-code h3="C# Code om OFX antwoordbestanden te converteren" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-response-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Code om OFX aanvraagbestanden te converteren" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-request-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="XBRL Conversie van financiële rapporten" %}}

API ondersteunt het converteren van XBRL bestanden naar iXBRL en Microsoft® Excel XLSX-indeling. Het conversieproces is eenvoudig, laad eerst het bestand via [XbrlDocument-klasse](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument). Gebruik de [klasse SaveOptions](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions) voor [OpslaanFormaat](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions/properties/saveformat), te gebruiken als parameter in de Save-methode van XbrlDocument Class. Voor opslaan in iXBLR-bestand, [SaveFormat.IXBRL](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveformat) wordt gebruikt en voor het exporteren naar XLSX-indeling wordt SaveFormat.XLSX gebruikt.

{{% blocks/products/pf/feature-page-code h3="C# Code om te exporteren XBRL naar iXBRL" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-ixbrl.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Code voor XBRL naar XLSX-conversie" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-xlsx.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xbrl-to-ixbrl xbrl-to-xlsx" >}}
{{< /blocks/products/pf/feature-page-wrap >}}