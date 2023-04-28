---
title: Skapa finansiella rapporter via .NET
url: /sv/net/create/
description:  C#-kod för att skapa finansiella rapporter i XBRL och OFX förfrågnings- eller svarsfiler via .NET-biblioteket.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Skapa finansiella rapporteringsfiler via C#" h2="Skapa finansiella rapportformat inklusive XBRL och OFX begäran eller svarsfil i 1.03- eller 2.2-format inom .NET-baserade applikationer." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) är en funktionsrik, utbyggbar och enkel att skapa och bearbeta finansiella rapporter API. Utvecklare kan enkelt skapa XBRL-instanser från början och kan lägga till schemareferens, sammanhang, enhet, objekt, fotnotslänk, rollreferens och 
bågrollreferens. API tillhandahåller relevant klass för varje funktion, till exempel för sammanhang som utvecklare kan använda [ContextPeriod](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextperiod), [ContextEntity](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextentity) och [Sammanhang](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/context). 
Dessutom stöder API även öppen ekonomisk utbyte (OFX) format begäran/svar skapande i 1.03 eller 2.2 format.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Skapa XBRL fil genom att lägga till objekt" %}}

För att skapa XBRL-fil och lägga till objekt i dokumentet är processen, skapa [XbrlDocument-klass](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) exempel. Förbered relevanta inställningar för objektet genom att använda lämpliga API klasser som t.ex [SchemaRef klass](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemaref)relevanta sammanhangsklasser som nämnts ovan och [Konceptklass](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/concept). Slutligen definiera och initialisera [Artikelklass](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/item) fastigheter samt kalla den [Spara metod](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) till [skapa XBRL](https://products.aspose.com/finance/net/create/xbrl/) fil till disken.

{{% blocks/products/pf/feature-page-code h3="C# Kod för att skapa XBRL fil genom att lägga till objekt" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-item.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Skapa OFX förfrågnings- och svarsfiler" %}}


För generering av OFX filer tillhandahåller API [OfxRequestDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) och [OfxResponseDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) klasser och utvecklare kan enkelt [skapa OFX-förfrågan](https://products.aspose.com/finance/net/create/ofx-request/) och svarsfiler i både 1.03 och 2.2 format. För att initiera OfxRequestDocument-egenskaper tillhandahåller API även andra klasser som t.ex [SignonRequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonrequest), [Finansiell institution](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/financialinstitution) och [StatementTransactionRequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionrequest) klasser. På samma sätt, för initialisering av OfxResponseDocument-egenskaper, tillhandahåller API stödjande klasser som t.ex. [SignonResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse),  [StatementTransactionResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse) och [Utdrag Transaktion](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction). Nedan finns kodavsnitten för båda fallen med användning av relevanta lämpliga klasser.

{{% blocks/products/pf/feature-page-code h3="C# Kod för att generera OFX Begärdokument" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Kod för att generera OFX svarsdokument" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
{{< /blocks/products/pf/feature-page-wrap >}}