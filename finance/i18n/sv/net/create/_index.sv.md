---
title: Skapa finansiella rapporter via .NET
url: /sv/net/create/
description:  C# kod för att skapa finansiella rapporter i XBRL, och OFX begär eller svarsfiler via .NET biblioteket.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Skapa finansiella rapporteringsfiler via C#" h2="Skapande av finansiella rapportformat inklusive XBRL och OFX efterfrågan eller svarsfil i 1.03 eller 2.2 format inom .NET baserade program." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) Är en funktion rik, omfattande och lättanvänd finansiell rapport skapande och bearbetning API. Utvecklare kan enkelt skapa XBRL instans från grunden samt kan lägga till schemareferens, kontext, enhet, objekt, Fotnotlänk, rollreferens 
Arc-rollreferens. API tillhandahåller relevant klass för varje funktion som för sammanhang, utvecklare kan använda utvecklare [Sammanhangsperiod](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextperiod), [SammanhangEntity](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextentity) Och och [Sammanhanget](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/context). 
Dessutom stöder API även förfrågan öppen finansiell utbyte (OFX) format / svar skapande i 1.03 eller 2.2 format.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Skapa XBRL fil genom att lägga till objekt" %}}

För att skapa XBRL filen och lägga till objekt i dokumentet, är processen, skapa [XbrlDokumentklass](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Instans. Förbered relevanta inställningar för objektet genom att använda lämpliga API klasser som t.ex. [SchemaRef- klass](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemaref), Relevanta sammanhangsklasser enligt ovan. [Begreppsklass](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/concept). Slutligen definiera och intialisera [Punktklass](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/item) Egenskaper samt kaller [Spara metoden](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) Till följd [Skapa XBRL](https://products.aspose.com/finance/net/create/xbrl/) Fil till disk.

{{% blocks/products/pf/feature-page-code h3="C# Kod att skapa XBRL fil genom att lägga till objekt" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-item.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Skapa OFX Begär och svarsfiler" %}}


För att skapa OFX filer, tillhandahåller API [OfxRequestDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) Och och [OfxResponseDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) Klasser och utvecklare kan lätt [Skapa OFX begära](https://products.aspose.com/finance/net/create/ofx-request/) Och svarsfiler i både 1.03 och 2.2 format. För att initiera OfxRequestDocument- egenskaper, tillhandahåller API också andra klasser såsom t.ex. [SignonRequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonrequest), [Finansiella institutioner](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/financialinstitution) Och och [UttalandeTransactionRequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionrequest) Lektioner. På samma sätt, för att intialisera OfxResponseDocument- egenskaper, tillhandahåller API stödjande klasser som t.ex. [SignonResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse),  [Uttalande Transaction Respons](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse) Och och [UttalandeTransaktioner](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction). Nedan följer koden för båda fallen med relevanta lämpliga klasser.

{{% blocks/products/pf/feature-page-code h3="C# Kod för att skapa OFX Begär dokument" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Kod för att skapa OFX Svarsdokument" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}