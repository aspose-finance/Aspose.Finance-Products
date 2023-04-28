---
title: Valideer financiële rapporten via Python
url: /nl/python-net/validate/
description:  Python code om financiële rapporten in XBRL en iXBRL bestanden te valideren via Python bibliotheek.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Valideer financiële rapportagebestanden via Python" h2="Valideren van formaten voor financiële rapporten, waaronder XBRL en iXBRL binnen op Python gebaseerde applicaties." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance voor Python via .NET](https://products.aspose.com/finance/python-net/) is een uitgebreide, uitbreidbare en gebruiksvriendelijke verwerking van financiële rapporten API. Ontwikkelaars kunnen eenvoudig XBRL- en iXBRL-indelingen laden, valideren, bekijken of maken voor financiële en zakelijke oplossingen. API biedt XbrlDocument-klasse en InlineXbrlDocument-klasse voor het laden van XBRL- en iXBRL-bestanden.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Valideer XBRL Document" %}}

Validatie van XBRL-bestand is nodig voor een aantal gevallen, bijvoorbeeld om te controleren of de gegevens de juiste structuur en indeling hebben. Om XBLR-documenten te valideren, gebruikt u eerst de XbrlDocument-klasse om het XBRL-bestand te laden. Om de valideringsmethode van de XbrlInstance-klasse te gebruiken, moet u eerst de XbrlInstanceCollection initialiseren met het XbrlDocument-object XbrlInstances. Doorloop elke XbrlInstance.ValidationErrors om de juiste foutcode te krijgen en handel dienovereenkomstig door de aangepaste foutmeldingen op de console af te drukken of in een bestand te schrijven.

{{% blocks/products/pf/feature-page-code h3="Python Code om XBRL Bestand te valideren" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "validate-xbrl-instance-file.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Valideer iXBRL Document" %}}

Voor iXLRB-validatie laadt u het via de InlineXbrlDocument-klasse en gebruikt u de methode valideren(). In ValidationErrorCode-opsomming worden validatiefoutcodes gedefinieerd voor elke validatieregel. Enkele codes zijn ContextPeriodNoStartTime, ContextPeriodNoEndTime, ContextPeriodStartAfterEnd, ContextInstantNoTime, ContextScenarioXbrlNamespace, ContextScenarioXbrlSubstitutionGroup enz. Ontwikkelaars kunnen debuggen en codes weergeven vanaf eindgebruikers of kunnen de richting aangeven voor het oplossen van het probleem.

{{% blocks/products/pf/feature-page-code h3="Python Code om iXBRL Document te valideren" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "validate-ixbrl-file.py" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Validate" >}}
{{< /blocks/products/pf/feature-page-wrap >}}