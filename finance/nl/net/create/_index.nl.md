---
title: Maak financiële rapporten via .NET
url: /nl/net/create/
description:  C# code om financiële rapporten te maken in XBRL en OFX verzoek- of antwoordbestanden via de .NET-bibliotheek.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Maak financiële rapportagebestanden via C#" h2="Aanmaken van formaten voor financiële rapporten, waaronder XBRL en OFX verzoek- of responsbestanden in 1.03- of 2.2-indeling binnen op .NET gebaseerde applicaties." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) is een rijke, uitbreidbare en gebruiksvriendelijke aanmaak en verwerking van financiële rapporten API. Ontwikkelaars kunnen eenvoudig XBRL instantie helemaal opnieuw maken en kunnen schemaverwijzing, context, eenheid, item, voetnootlink, rolverwijzing en 
arc-rolreferentie. API biedt relevante klasse voor elke functie, zoals voor context, die ontwikkelaars kunnen gebruiken [ContextPeriode](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextperiod), [ContextEntiteit](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextentity) en [Context](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/context). 
Bovendien ondersteunt API ook het aanmaken van verzoeken/antwoorden in open financiële uitwisseling (OFX) in 1.03 of 2.2 formaat.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Maak XBRL-bestand door item toe te voegen" %}}

Voor het maken van een XBRL-bestand en het toevoegen van een item aan het document, is het proces create [XbrlDocument-klasse](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) voorbeeld. Bereid relevante instellingen voor het item voor door de juiste API klassen te gebruiken, zoals: [SchemaRef-klasse](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemaref)relevante contextklassen zoals hierboven vermeld en [concept klasse](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/concept). Eindelijk definiëren en initialiseren [Artikelklasse](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/item) eigenschappen en bel de [Opslaan methode](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) tot [maak XBRL](https://products.aspose.com/finance/net/create/xbrl/) bestand op schijf.

{{% blocks/products/pf/feature-page-code h3="C# Code om XBRL bestand te maken door item toe te voegen" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-item.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Maak OFX verzoek- en antwoordbestanden" %}}


Voor het genereren van OFX bestanden biedt de API [OfxVerzoekDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) en [OfxReactieDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) klassen en ontwikkelaars kunnen gemakkelijk [maak OFX Verzoek](https://products.aspose.com/finance/net/create/ofx-request/) en responsbestanden in zowel 1.03- als 2.2-indeling. Voor het initialiseren van OfxRequestDocument-eigenschappen biedt API ook andere klassen zoals [Aanmeldingsverzoek](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonrequest), [Financiele instelling](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/financialinstitution) en [Verklaring TransactieVerzoek](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionrequest) klassen. Evenzo biedt API voor het initialiseren van OfxResponseDocument-eigenschappen ondersteunende klassen zoals: [Aanmeldingsreactie](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse),  [Verklaring TransactieReactie](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse) en [Afschrift Transactie](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction). Hieronder staan de codefragmenten voor beide gevallen met het gebruik van relevante toepasselijke klassen.

{{% blocks/products/pf/feature-page-code h3="C# Code om OFX Documenten op te vragen" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Code om OFX Antwoorddocumenten te genereren" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
{{< /blocks/products/pf/feature-page-wrap >}}