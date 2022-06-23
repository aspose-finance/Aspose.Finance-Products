---
title: Validera finansiella rapporter via Python
url: /sv/python-net/validate/
description:  Python-kod för att validera finansiella rapporter i XBRL- och iXBRL-filer via Python-biblioteket.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Validera finansiella rapporteringsfiler via Python" h2="Validera finansiella rapportformat inklusive XBRL och iXBRL inom Python-baserade applikationer." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance för Python via .NET](https://products.aspose.com/finance/python-net/) är en funktionsrik, utbyggbar och lättanvänd finansiell rapportbehandling API. Utvecklare kan enkelt ladda, validera, visa eller skapa XBRL- och iXBRL-format för finansiella och affärslösningar. API tillhandahåller klassen XbrlDocument och InlineXbrlDocument-klassen för att ladda XBRL- och iXBRL-filer.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Validera XBRL dokument" %}}

Validering av XBRL-filen behövs för ett antal fall, till exempel för att kontrollera att data har rätt struktur och format. För att validera XBLR-dokument, använd först XbrlDocument-klassen för att ladda XBRL-filen. För att använda valideringsmetoden för XbrlInstance-klassen, initialisera först XbrlInstanceCollection med XbrlDocument-objektet XbrlInstances. Iterera igenom varje XbrlInstance.ValidationErrors för att få rätt felkod och agera därefter genom att skriva ut de anpassade felmeddelandena på konsolen eller skriva i en fil.

{{% blocks/products/pf/feature-page-code h3="Python Kod för att validera XBRL-fil" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "validate-xbrl-instance-file.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Validera iXBRL dokument" %}}

För iXLRB-validering, ladda den via InlineXbrlDocument-klassen och använd dess validate()-metod. I ValidationErrorCode-uppräkning definieras valideringsfelkoder för varje valideringsregel. Ett fåtal koder är ContextPeriodNoStartTime, ContextPeriodNoEndTime, ContextPeriodStartAfterEnd, ContextInstantNoTime, ContextScenarioXbrlNamespace, ContextScenarioXbrlSubstitutionGroup etc. Utvecklare kan felsöka och visa koder för slutanvändare eller kan visa riktningen för slutanvändare.

{{% blocks/products/pf/feature-page-code h3="Python Kod för att validera iXBRL dokument" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "validate-ixbrl-file.py" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Validate" >}}