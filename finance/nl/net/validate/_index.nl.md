---
title: Valideer financiële rapporten via .NET
url: /nl/net/validate/
description:  C# code om financiële rapporten in XBRL en iXBRL bestanden te valideren via .NET bibliotheek.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Valideer financiële rapportagebestanden via C#" h2="Valideren van formaten voor financiële rapporten, waaronder XBRL en iXBRL binnen op .NET gebaseerde applicaties." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) is een uitgebreide, uitbreidbare en gebruiksvriendelijke verwerking van financiële rapporten API. Ontwikkelaars kunnen eenvoudig XBRL- en iXBRL-indelingen laden, valideren, bekijken of maken voor financiële en zakelijke oplossingen. API biedt [XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) klasse en  [InlineXbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) class voor het laden van XBRL- en iXBRL-bestanden.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Valideer XBRL Document" %}}

Validatie van XBRL-bestand is nodig voor een aantal gevallen, bijvoorbeeld om te controleren of de gegevens de juiste structuur en indeling hebben. Om XBLR-documenten te valideren, gebruikt u eerst de XbrlDocument-klasse om het XBRL-bestand te laden. om de te gebruiken [valideren()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) methode van [XbrlInstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance) class, initialiseer eerst de [XbrlInstanceCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) met XbrlDocument-object XbrlInstances. Door elk herhalen [XbrlInstance.ValidationErrors](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/properties/validationerrors) om de juiste foutcode te krijgen en dienovereenkomstig te handelen door de aangepaste foutmeldingen op de console af te drukken of in een bestand te schrijven.

{{% blocks/products/pf/feature-page-code h3="C# Code om XBRL Bestand te valideren" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-xbrl-file.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Valideer iXBRL Document" %}}

Voor iXLRB-validatie, laad het via [InlineXbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) class en gebruik de Validate()-methode. In [ValidatieFoutcode](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.validator/validationerrorcode) opsomming, worden validatiefoutcodes gedefinieerd voor elke validatieregel. Enkele codes zijn ContextPeriodNoStartTime, ContextPeriodNoEndTime, ContextPeriodStartAfterEnd, ContextInstantNoTime, ContextScenarioXbrlNamespace, ContextScenarioXbrlSubstitutionGroup enz. Ontwikkelaars kunnen debuggen en codes weergeven vanaf eindgebruikers of kunnen de richting aangeven voor het oplossen van het probleem.

{{% blocks/products/pf/feature-page-code h3="C# Code om iXBRL Document te valideren" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-ixbrl-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Validate" >}}
{{< /blocks/products/pf/feature-page-wrap >}}