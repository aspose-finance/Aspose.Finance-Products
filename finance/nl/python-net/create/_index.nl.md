---
title: Maak financiële rapporten via Python
url: /nl/python-net/create/
description:  Python code om financiële rapporten te maken in XBRL en OFX verzoek- of antwoordbestanden via de Python-bibliotheek.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Maak financiële rapportagebestanden via Python" h2="Aanmaken van formaten voor financiële rapporten, waaronder XBRL en OFX verzoek- of responsbestanden in 1.03- of 2.2-indeling binnen op Python gebaseerde applicaties." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance voor Python via .NET](https://products.aspose.com/finance/python-net/) is een rijke, uitbreidbare en gebruiksvriendelijke aanmaak en verwerking van financiële rapporten API. Ontwikkelaars kunnen eenvoudig XBRL instantie helemaal opnieuw maken en kunnen schemaverwijzing, context, eenheid, item, voetnootlink, rolverwijzing en 
arc-rolreferentie. API biedt relevante klasse voor elke functie, zoals voor context, ontwikkelaars kunnen ContextPeriod, ContextEntity en Context gebruiken. 
Bovendien ondersteunt API ook het aanmaken van verzoeken/antwoorden in open financiële uitwisseling (OFX) in 1.03 of 2.2 formaat.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Maak XBRL-bestand door item toe te voegen" %}}

Voor het maken van een XBRL-bestand en het toevoegen van een item aan het document, is het proces het maken van een XbrlDocument-klasse-instantie. Bereid relevante instellingen voor het item voor door geschikte API-klassen te gebruiken, zoals SchemaRef-klasse, relevante contextklassen zoals hierboven vermeld en Concept-klasse. Definieer en initialiseer tenslotte de eigenschappen van de itemklasse en roep de opslagmethode aan om een XBRL-bestand op schijf te maken.

{{% blocks/products/pf/feature-page-code h3="Python Code om XBRL bestand te maken door item toe te voegen" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-xbrl-file-and-add-item.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Maak OFX verzoek- en antwoordbestanden" %}}


Voor het genereren van OFX-bestanden biedt de API OfxRequestDocument- en OfxResponseDocument-klassen en kunnen ontwikkelaars gemakkelijk [maak OFX Verzoek](https://products.aspose.com/finance/python-net/create/ofx-request/) en responsbestanden in zowel 1.03- als 2.2-indeling. Voor het initialiseren van OfxRequestDocument-eigenschappen biedt API ook andere klassen, zoals SignonRequest, FinancialInstitution en StatementTransactionRequest-klassen. Evenzo biedt API voor het initialiseren van OfxResponseDocument-eigenschappen ondersteunende klassen zoals SignonResponse, StatementTransactionResponse en StatementTransaction. Hieronder staan de codefragmenten voor beide gevallen met het gebruik van relevante toepasselijke klassen.

{{% blocks/products/pf/feature-page-code h3="Python Code om OFX Documenten op te vragen" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-response-files.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Python Code om OFX Antwoorddocumenten te genereren" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-response-files.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
{{< /blocks/products/pf/feature-page-wrap >}}