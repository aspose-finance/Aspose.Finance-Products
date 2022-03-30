---
title: Validera finansiella rapporter via .NET
url: /sv/net/validate/
description:  C#-kod för att validera finansiella rapporter i XBRL- och iXBRL-filer via .NET-biblioteket.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Validera finansiella rapporteringsfiler via C#" h2="Validera finansiella rapportformat inklusive XBRL och iXBRL inom .NET-baserade applikationer." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) är en funktionsrik, utbyggbar och lättanvänd finansiell rapportbehandling API. Utvecklare kan enkelt ladda, validera, visa eller skapa XBRL- och iXBRL-format för finansiella och affärslösningar. API tillhandahåller [XbrlDokument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) klass och  [InlineXbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) klass för att ladda XBRL- och iXBRL-filer.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Validera XBRL dokument" %}}

Validering av XBRL-filen behövs för ett antal fall, till exempel för att kontrollera att data har rätt struktur och format. För att validera XBLR-dokument, använd först XbrlDocument-klassen för att ladda XBRL-filen. Att använda [bekräfta()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) metod av [XbrlInstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance) klass, initialisera först [XbrlInstanceCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) med XbrlDocument-objektet XbrlInstances. Iterera genom varje [XbrlInstance.ValidationErrors](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/properties/validationerrors) för att få rätt felkod och agera därefter genom att skriva ut de anpassade felmeddelandena på konsolen eller skriva i en fil.

{{% blocks/products/pf/feature-page-code h3="C# Kod för att validera XBRL-fil" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-xbrl-file.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Validera iXBRL dokument" %}}

För iXLRB-validering, ladda den via [InlineXbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) klass och använd dess Validate()-metod. I [ValidationErrorCode](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.validator/validationerrorcode) uppräkning, valideringsfelkoder definieras för varje valideringsregel. Ett fåtal koder är ContextPeriodNoStartTime, ContextPeriodNoEndTime, ContextPeriodStartAfterEnd, ContextInstantNoTime, ContextScenarioXbrlNamespace, ContextScenarioXbrlSubstitutionGroup etc. Utvecklare kan felsöka och visa koder för slutanvändare eller kan visa riktningen för slutanvändare.

{{% blocks/products/pf/feature-page-code h3="C# Kod för att validera iXBRL dokument" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-ixbrl-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Validate" >}}