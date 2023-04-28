---
title: Skapa finansiella rapporter via Python
url: /sv/python-net/create/
description:  Python-kod för att skapa finansiella rapporter i XBRL och OFX förfrågnings- eller svarsfiler via Python-biblioteket.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Skapa finansiella rapporteringsfiler via Python" h2="Skapa finansiella rapportformat inklusive XBRL och OFX begäran eller svarsfil i 1.03- eller 2.2-format inom Python-baserade applikationer." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance för Python via .NET](https://products.aspose.com/finance/python-net/) är en funktionsrik, utbyggbar och enkel att skapa och bearbeta finansiella rapporter API. Utvecklare kan enkelt skapa XBRL-instanser från början och kan lägga till schemareferens, sammanhang, enhet, objekt, fotnotslänk, rollreferens och 
bågrollreferens. API tillhandahåller relevant klass för varje funktion, till exempel för kontext, utvecklare kan använda ContextPeriod, ContextEntity och Context. 
Dessutom stöder API även öppen ekonomisk utbyte (OFX) format begäran/svar skapande i 1.03 eller 2.2 format.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Skapa XBRL fil genom att lägga till objekt" %}}

För att skapa XBRL-fil och lägga till objekt i dokumentet är processen att skapa XbrlDocument-klassinstans. Förbered relevanta inställningar för objektet genom att använda lämpliga API-klasser som SchemaRef-klassen, relevanta sammanhangsklasser som nämnts ovan och Concept-klassen. Definiera och initialisera slutligen objektklassegenskaper samt anropa sparametoden för att skapa XBRL-fil till disk.

{{% blocks/products/pf/feature-page-code h3="Python Kod för att skapa XBRL fil genom att lägga till objekt" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-xbrl-file-and-add-item.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Skapa OFX förfrågnings- och svarsfiler" %}}


För att generera OFX filer tillhandahåller API klasserna OfxRequestDocument och OfxResponseDocument och utvecklare kan enkelt [skapa OFX-förfrågan](https://products.aspose.com/finance/python-net/create/ofx-request/) och svarsfiler i både 1.03 och 2.2 format. För att initiera OfxRequestDocument-egenskaper tillhandahåller API även andra klasser som SignonRequest, FinancialInstitution och StatementTransactionRequest. På liknande sätt, för initialisering av OfxResponseDocument-egenskaper, tillhandahåller API stödjande klasser som SignonResponse, StatementTransactionResponse och StatementTransaction. Nedan finns kodavsnitten för båda fallen med användning av relevanta lämpliga klasser.

{{% blocks/products/pf/feature-page-code h3="Python Kod för att generera OFX Begärdokument" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-response-files.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Python Kod för att generera OFX svarsdokument" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-response-files.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
{{< /blocks/products/pf/feature-page-wrap >}}