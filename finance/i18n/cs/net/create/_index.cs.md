---
title: Vytvořit finanční zprávy pomocí .NET
url: /cs/net/create/
description:  C# kód pro vytváření finančních zpráv v XBRL a OFX soubory žádosti nebo odpovědi prostřednictvím knihovny .NET.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Vytvořit soubory účetního výkaznictví pomocí C#" h2="Vytvoření formátů finančních zpráv, včetně XBRL a OFX souboru požadavků nebo odpovědí ve formátu 1.03 nebo 2.2 v aplikacích založených na .NET." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) Je funkcí bohatá, rozšiřovatelná a snadno použitelná tvorba a zpracování finančních zpráv API. Vývojáři mohou snadno vytvořit instance XBRL od nuly, stejně jako mohou přidat odkaz na schématu, kontext, jednotku, položku, odkaz na poznámku pod čarou, odkaz na roli a 
Odkaz na roli arc. API poskytuje relevantní třídu pro každou funkci, například pro kontext, mohou vývojáři použít [Kontextperiod](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextperiod), [Kontextentity](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextentity) A [Kontext](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/context)A. 
API navíc podporuje také vytváření požadavků/odpovědí ve formátu open financial exchange (OFX) ve formátu 1.03 nebo 2.2.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Vytvořit soubor XBRL přidáním položky" %}}

Pro vytvoření XBRL souboru a přidání položky do dokumentu je proces, vytvořit [Třída xbrldocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Instance. Připravte příslušné nastavení položky pomocí vhodných tříd API, jako jsou [Třída schemaref](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemaref), Příslušné kontextové třídy, jak je uvedeno výše, a [Třída konceptu](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/concept)A. Konečně definovat a intializovat [Třída položek](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/item) Vlastnosti, stejně jako volání [Uložit metodu](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) Do [Vytvořit XBRL](https://products.aspose.com/finance/net/create/xbrl/) Soubor do disku.

{{% blocks/products/pf/feature-page-code h3="C# kód pro vytvoření XBRL souboru přidáním položky" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-item.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Vytvořit OFX soubory žádosti a odpovědi" %}}


Pro generování souborů OFX poskytuje API [Dokument ofxrequestdocument (angl.: + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + +](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) A [Ofxresponsedocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) Třídy a vývojáři mohou snadno [Vytvořit požadavek OFX](https://products.aspose.com/finance/net/create/ofx-request/) A soubory odezvy ve formátu 1.03 a 2.2. Pro inicializaci vlastností ofxrequestdocument poskytuje API také jiné třídy, jako je např. [Signonrequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonrequest), [Finanční instituce](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/financialinstitution) A [Vyžádání o transakci](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionrequest) Třídy. Similarly, for intializing ofxresponsedocument properties, API provides supportive classes such as [Signonresponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse),  [Prohlášení transakceresponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse) A [Prohlášení transakce](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction)A. Níže jsou uvedeny kódové úryvky pro oba případy s použitím příslušných vhodných tříd.

{{% blocks/products/pf/feature-page-code h3="C# kód pro generování dokumentů OFX" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# kód pro generování dokumentů odezvy OFX" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}