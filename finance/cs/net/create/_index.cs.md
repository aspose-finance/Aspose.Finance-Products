---
title: Vytvářejte finanční přehledy prostřednictvím .NET
url: /cs/net/create/
description:  C# kód pro vytváření finančních přehledů v XBRL a OFX soubory požadavků nebo odpovědí prostřednictvím knihovny .NET.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Vytvářejte soubory finančního výkaznictví prostřednictvím C#" h2="Vytváření formátů finančních zpráv, včetně souboru požadavků nebo odpovědí XBRL a OFX ve formátu 1.03 nebo 2.2 v aplikacích založených na .NET." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) je funkčně bohatý, rozšiřitelný a snadno použitelný vytváření a zpracování finančních zpráv API. Vývojáři mohou snadno vytvořit XBRL instanci od začátku a také mohou přidat odkaz na schéma, kontext, jednotku, položku, odkaz na poznámku pod čarou, odkaz na roli a 
odkaz na roli oblouku. API poskytuje relevantní třídu pro každou funkci, jako je kontext, který mohou vývojáři použít [ContextPeriod](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextperiod), [ContextEntity](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextentity) a [Kontext](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/context). 
Kromě toho API také podporuje vytváření požadavků / odpovědí ve formátu otevřené finanční burzy (OFX) ve formátu 1.03 nebo 2.2.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Vytvořte soubor XBRL přidáním položky" %}}

Pro vytvoření souboru XBRL a přidání položky do dokumentu, proces je, vytvořte [Třída XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) instance. Připravte relevantní nastavení pro položku pomocí vhodných tříd API, jako např [Třída SchemaRef](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemaref)příslušné kontextové třídy, jak je uvedeno výše a [Koncept třída](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/concept). Nakonec definujte a inicializujte [Třída položky](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/item) vlastnosti a také zavolejte [Uložit metodu](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) na [vytvořit XBRL](https://products.aspose.com/finance/net/create/xbrl/) soubor na disk.

{{% blocks/products/pf/feature-page-code h3="C# Kód pro vytvoření souboru XBRL přidáním položky" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-item.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Vytvořte soubory požadavků a odpovědí OFX" %}}


Pro generování OFX souborů poskytuje API [OfxRequestDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) a [OfxResponseDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) třídy a vývojáři mohou snadno [vytvořit požadavek OFX](https://products.aspose.com/finance/net/create/ofx-request/) a soubory odpovědí ve formátu 1.03 i 2.2. Pro inicializaci vlastností OfxRequestDocument poskytuje API také další třídy, jako např [Žádost o přihlášení](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonrequest), [Finanční instituce](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/financialinstitution) a [StatementTransactionRequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionrequest) třídy. Podobně pro inicializaci vlastností OfxResponseDocument poskytuje API podpůrné třídy, jako je např [SignonResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse),  [StatementTransactionResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse) a [Výpis Transakce](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction). Níže jsou uvedeny fragmenty kódu pro oba případy s použitím příslušných příslušných tříd.

{{% blocks/products/pf/feature-page-code h3="C# Kód pro generování OFX dokumentů požadavku" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Kód pro generování OFX dokumentů odpovědí" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
{{< /blocks/products/pf/feature-page-wrap >}}