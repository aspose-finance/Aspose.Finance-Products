---
title: Vytvářejte finanční přehledy prostřednictvím Python
url: /cs/python-net/create/
description:  Python kód pro vytváření finančních přehledů v XBRL a OFX soubory požadavků nebo odpovědí prostřednictvím knihovny Python.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Vytvářejte soubory finančního výkaznictví prostřednictvím Python" h2="Vytváření formátů finančních zpráv, včetně souboru požadavků nebo odpovědí XBRL a OFX ve formátu 1.03 nebo 2.2 v aplikacích založených na Python." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance za Python prostřednictvím .NET](https://products.aspose.com/finance/python-net/) je funkčně bohatý, rozšiřitelný a snadno použitelný vytváření a zpracování finančních zpráv API. Vývojáři mohou snadno vytvořit XBRL instanci od začátku a také mohou přidat odkaz na schéma, kontext, jednotku, položku, odkaz na poznámku pod čarou, odkaz na roli a 
odkaz na roli oblouku. API poskytuje relevantní třídu pro každou funkci, jako je kontext, vývojáři mohou použít ContextPeriod, ContextEntity a Context. 
Kromě toho API také podporuje vytváření požadavků / odpovědí ve formátu otevřené finanční burzy (OFX) ve formátu 1.03 nebo 2.2.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Vytvořte soubor XBRL přidáním položky" %}}

Pro vytvoření souboru XBRL a přidání položky do dokumentu, proces je, vytvořte instanci třídy XbrlDocument. Připravte relevantní nastavení pro položku pomocí vhodných tříd API, jako je třída SchemaRef, relevantní kontextové třídy, jak je uvedeno výše, a třída Concept. Nakonec definujte a inicializujte vlastnosti třídy Item a také zavolejte metodu uložení pro vytvoření souboru XBRL na disk.

{{% blocks/products/pf/feature-page-code h3="Python Kód pro vytvoření souboru XBRL přidáním položky" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-xbrl-file-and-add-item.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Vytvořte soubory požadavků a odpovědí OFX" %}}


Pro generování OFX souborů poskytuje API třídy OfxRequestDocument a OfxResponseDocument a vývojáři mohou snadno [vytvořit požadavek OFX](https://products.aspose.com/finance/python-net/create/ofx-request/) a soubory odpovědí ve formátu 1.03 i 2.2. Pro inicializaci vlastností OfxRequestDocument poskytuje API také další třídy, jako jsou třídy SignonRequest, FinancialInstitution a StatementTransactionRequest. Podobně pro inicializaci vlastností OfxResponseDocument poskytuje API podpůrné třídy, jako je SignonResponse, StatementTransactionResponse a StatementTransaction. Níže jsou uvedeny fragmenty kódu pro oba případy s použitím příslušných příslušných tříd.

{{% blocks/products/pf/feature-page-code h3="Python Kód pro generování OFX dokumentů požadavku" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-response-files.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Python Kód pro generování OFX dokumentů odpovědí" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-response-files.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
{{< /blocks/products/pf/feature-page-wrap >}}