---
title: Financiële rapporten aanmaken via .NET
url: /nl/net/create/
description:  C# code om financiële rapporten te maken in XBRL en OFX aanvragen-of responsbestanden via de .NET bibliotheek.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Financiële rapportagebestanden aanmaken via C#" h2="Het maken van financiële rapportindelingen, waaronder XBRL en OFX aanvraag-of responsbestand in 1.03-of 2.2-indeling binnen .NET toepassingen." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) Is een feature rijk, uitbreidbaar en eenvoudig te gebruiken financiële rapportage creatie en verwerking API. Ontwikkelaars kunnen eenvoudig XBRL exemplaar helemaal opnieuw maken en kunnen ook schemareferentie, context, eenheid, item, voetnootlink, rolverwijzing en 
De verwijzing van de boogrol. API biedt relevante klasse voor elke functie, zoals voor context, kunnen ontwikkelaars gebruiken [Contextperiode](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextperiod), [ContextEntity](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextentity) En [Context](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/context). 
Bovendien ondersteunt API ook het maken van open financiële valuta (OFX)-opmaak van aanvragen/reacties in 1.03-of 2.2-indeling.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Maak XBRL bestand door item toe te voegen" %}}

Om een XBRL-bestand te maken en een item aan het document toe te voegen, is het proces, maak [Klasse XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Instantie. Bereid relevante instellingen voor het item voor door de juiste API klassen te gebruiken, zoals [SchemaRef-klasse](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemaref), Relevante contextklassen zoals hierboven vermeld en [Conceptklasse](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/concept). Definieer en intialiseer ten slotte [Artikelklasse](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/item) Zowel eigenschappen als de [Bewaarmethode](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) Naar [XBRL creëren](https://products.aspose.com/finance/net/create/xbrl/) Bestand in schijf.

{{% blocks/products/pf/feature-page-code h3="C# code om XBRL bestand te maken door item toe te voegen" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-item.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="OFX aanvragen-en reactiebestanden maken" %}}


Voor het genereren van OFX bestanden biedt de API [OfxRequestDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) En [OfxResponseDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) Klassen en ontwikkelaars kunnen gemakkelijk [OFX verzoek aanmaken](https://products.aspose.com/finance/net/create/ofx-request/) En Response-bestanden in zowel 1.03-als 2.2-formaten. Voor het initialiseren van OfxRequestDocument-eigenschappen biedt API ook andere klassen zoals [SignonRequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonrequest), [Financiële instelling](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/financialinstitution) En [StatementTransactionRequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionrequest) Klassen. Evenzo biedt API ondersteunende klassen zoals voor het intialiseren van OfxResponseDocument-eigenschappen [SignonReactie](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse),  [StatementTransactionResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse) En [Statementtransactie](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction). Hieronder staan de codefragmenten voor beide gevallen met behulp van relevante geschikte klassen.

{{% blocks/products/pf/feature-page-code h3="C# code om OFX aanvraagdocumenten te genereren" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# code om OFX responsdocumenten te genereren" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}