---
title: Validera finansiella rapporter via .NET
url: /sv/net/validate/
description:  C# kod för att validera finansiella rapporter i XBRL och iXBRL filer via .NET biblioteket.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Validera finansiella rapporteringsfiler via C#" h2="Validera finansiella rapportformat inklusive XBRL och iXBRL inom .NET baserade program." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) Är en funktion rik, omfattande och lättanvänd finansiell rapport behandling API. Utvecklare kan enkelt ladda, validera, visa eller skapa XBRL och iXBRL-format för finansiella och affärslösningar. API tillhandahåller [XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Klass och klass  [InlineXbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) Klass för att ladda XBRL och iXBRL filer.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Validera XBRL dokument" %}}

Validering av XBRL filen krävs för ett antal fall som kontrollerar data är i rätt struktur och format. För att validera XBLR-dokument, använd först XbrlDocument-klass för att ladda XBRL-filen. För att använda den [Validate)](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) Metod [XbrlInstans](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance) Klass, först intialisera den [XbrlInstance-samlingComment](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) Med XbrlDocument objekt XbrlInstances. Iterar genom varje gång. [XbrlInstance.ValidationErrors](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/properties/validationerrors) För att få rätt felkod och agera därefter genom att skriva ut de anpassade felmeddelandena på konsolen eller skriva i en fil.

{{% blocks/products/pf/feature-page-code h3="C# Kod för att validera XBRL fil" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-xbrl-file.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Validera iXBRL dokument" %}}

För validering av iXLRB, ladda den via in [InlineXbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) Klass och använd dess validate() metod. In i [ValideringErrorCodeComment](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.validator/validationerrorcode) Uppräkning, valideringsfelkoder definieras för varje valideringsregel. Få koder är ContextPeriodNoStartTime, ContextPeriodNoEndTime, SammanhangsperiodStartAfterEnd, SammanhangInstantNoTime, SammanhangScenarioXbrlNamespace, KontextScenarioXbrlSubstitutionGroup etc. Utvecklare kan felsöka och visa koder som slutanvändare eller kan visa riktningen för att lösa problemet.

{{% blocks/products/pf/feature-page-code h3="C# Kod för att validera iXBRL dokument" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-ixbrl-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Validate" >}}