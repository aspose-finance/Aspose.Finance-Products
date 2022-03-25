---
title: Financiële rapporten valideren via .NET
url: /nl/net/validate/
description:  C# code om financiële rapporten in XBRL en iXBRL bestanden te valideren via de .NET bibliotheek.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Bestanden voor financiële rapportage valideren via C#" h2="Het valideren van financiële rapportindelingen, waaronder XBRL en iXBRL, binnen .NET applicaties." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) Is een feature rijk, uitbreidbaar en eenvoudig te gebruiken financiële rapportverwerking API. Ontwikkelaars kunnen gemakkelijk XBRL en iXBRL formaten laden, valideren, bekijken of aanmaken voor financiële en zakelijke oplossingen. API biedt [Xbrldocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Klasse en  [InlineXbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) Klasse voor het laden van XBRL en iXBRL bestanden.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="XBRL document valideren" %}}

Validatie van XBRL bestand is nodig voor een aantal gevallen, zoals om te controleren of gegevens in de juiste structuur en formaat zijn. Om XBLR-documenten te valideren, gebruik eerst XbrlDocument-klasse om het XBRL-bestand te laden. Om de [Valideren ()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) Methode van [XbrlInstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance) Klasse, ten eerste intialize de [XbrlInstanceCollectie](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) Met XbrlDocument-object XbrlInstances. Itereer door elk [XbrlInstance. Validationfouten](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/properties/validationerrors) Om de juiste foutcode te krijgen en dienovereenkomstig te handelen door de aangepaste foutmeldingen op de console af te drukken of binnen een bestand te schrijven.

{{% blocks/products/pf/feature-page-code h3="C# code om XBRL bestand te valideren" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-xbrl-file.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="iXBRL document valideren" %}}

Voor iXLRB-validatie, laad het via [InlineXbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) Klasse en gebruik de Validate()-methode. In [ValidationErrorCode](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.validator/validationerrorcode) Opsomming, validatie foutcodes zijn gedefinieerd voor elke validatieregel. Er zijn maar weinig codes: ContextPeriodNoStartTime, ContextPeriodNoEndTime, ContextPeriodStartAfterEnd, ContextInstantNoTime, ContextScenarioXbrlSubstitutionGroup enz. Ontwikkelaars kunnen codes debuggen en weergeven vanaf eindgebruikers of kunnen de richting weergeven om het probleem op te lossen.

{{% blocks/products/pf/feature-page-code h3="C# code om iXBRL document te valideren" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-ixbrl-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Validate" >}}