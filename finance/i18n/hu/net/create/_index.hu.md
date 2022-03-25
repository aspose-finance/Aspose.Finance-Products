---
title: Pénzügyi jelentések létrehozása .NET segítségével
url: /hu/net/create/
description:  C# kód pénzügyi jelentések létrehozásához XBRL, és OFX kérelem vagy válasz fájlokat .NET könyvtárban.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Pénzügyi jelentési fájlok létrehozása C# segítségével" h2="Pénzügyi jelentés formátumok létrehozása, beleértve a XBRL és OFX kérelem vagy válasz fájl 1.03 vagy 2.2 formátumban .NET alapú alkalmazások." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) Egy funkció gazdag, bővíthető és könnyen használható pénzügyi jelentés létrehozása és feldolgozása API. A fejlesztők könnyen létrehozhatnak XBRL példányt a semmiből, valamint hozzáadhatják a séma referenciáját, a kontextust, az egységet, az elemet, a lábjegyzet linkjét, a szerepkör referenciáját és 
Arc szerepkör referencia. API megfelelő osztályt biztosít minden egyes funkcióhoz, mint például a kontextushoz, a fejlesztők használhatják [Kontextperiódus](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextperiod), [Kontextentity](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextentity) És [Kontextus](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/context)A "", a "" ", a" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "". 
Ráadásul a API támogatja az open financial exchange (OFX) formátumú kérés/válasz létrehozását is 1.03 vagy 2.2 formátumban.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="XBRL fájl létrehozása az elem hozzáadásával" %}}

A XBRL fájl létrehozásához és az elem hozzáadásához a dokumentumba, a folyamat az, létrehozás [Xbrldocument osztály](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Példány. Készítse elő a megfelelő beállításokat az elemhez a megfelelő API osztályok használatával, mint pl. [Schemaref osztály](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemaref), A fent említett releváns kontextus osztályok és [Fogalomosztály](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/concept)A "", a "" ", a" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "". Végül definiálni és intializálni [Tétel osztály](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/item) Tulajdonságok, valamint hívja a [Mentési módszer](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) To [XBRL létrehozása](https://products.aspose.com/finance/net/create/xbrl/) Fájl lemezbe.

{{% blocks/products/pf/feature-page-code h3="C# kód létrehozásához XBRL fájl hozzáadásával elem" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-item.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="OFX kérés-és válaszfájlok létrehozása" %}}


OFX fájlok generálásához a API biztosít [Ofxrequestdocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) És [Ofxresponsedocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) Osztályok és fejlesztők könnyen [OFX kérelem létrehozása](https://products.aspose.com/finance/net/create/ofx-request/) És válaszfájlok mind 1.03, mind 2.2 formátumban. Az ofxrequestdocument tulajdonságok inicializálásához a API más osztályokat is biztosít, mint pl. [Signonrequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonrequest), [Financialinstitution](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/financialinstitution) És [Statementtransactionrequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionrequest) Osztályok. Hasonlóképpen az ofxresponsedocument tulajdonságainak intializálására a API olyan támogató osztályokat biztosít, mint pl. [Bejelentkezési válasz](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse),  [Statementtransactionresponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse) És [Statementtranzakció](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction)A "", a "" ", a" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "". Az alábbiakban a kód töredékek mindkét esetben a megfelelő osztályok használatával.

{{% blocks/products/pf/feature-page-code h3="C# kód OFX kérés dokumentumok létrehozásához" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# kód OFX válaszdokumentumok generálásához" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}