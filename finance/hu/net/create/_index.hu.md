---
title: "Pénzügyi jelentések létrehozása a következőn keresztül: .NET"
url: /hu/net/create/
description:  C# kódot pénzügyi jelentések létrehozásához a(z) XBRL webhelyen, és OFX kérés- vagy válaszfájlt a .NET könyvtáron keresztül.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Pénzügyi jelentési fájlok létrehozása a következőn keresztül: C#" h2="Pénzügyi jelentésformátumok létrehozása, beleértve a XBRL és OFX kérés- vagy válaszfájlt 1.03 vagy 2.2 formátumban a .NET alapú alkalmazásokban." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) egy funkciókban gazdag, bővíthető és könnyen használható pénzügyi jelentések létrehozása és feldolgozása API. A fejlesztők könnyedén létrehozhatnak XBRL példányt a semmiből, valamint hozzáadhatnak sémahivatkozást, kontextust, egységet, elemet, lábjegyzet hivatkozást, szerephivatkozást és 
ív szerephivatkozás. A API minden funkcióhoz megfelelő osztályt biztosít, például a kontextushoz, amelyet a fejlesztők használhatnak [ContextPeriod](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextperiod), [ContextEntity](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextentity) és [Kontextus](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/context). 
Ezenkívül a API támogatja a nyílt pénzügyi csere (OFX) formátumú kérés/válasz létrehozását 1.03 vagy 2.2 formátumban.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Hozzon létre XBRL fájlt elem hozzáadásával" %}}

A(z) XBRL fájl létrehozásához és az elem dokumentumhoz való hozzáadásához a folyamat a létrehozás [XbrlDocument osztály](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) példa. Készítse elő a megfelelő beállításokat az elemhez a megfelelő API osztályok használatával, mint pl [SchemaRef osztály](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemaref)releváns kontextus osztályok a fent említettek szerint és [Koncepció osztály](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/concept). Végül határozza meg és inicializálja [Tétel osztály](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/item) tulajdonságok, valamint hívja a [Mentés módja](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) nak nek [XBRL létrehozása](https://products.aspose.com/finance/net/create/xbrl/) fájlt a lemezre.

{{% blocks/products/pf/feature-page-code h3="C# Kód XBRL fájl létrehozásához elem hozzáadásával" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-item.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Hozzon létre OFX kérés- és válaszfájlokat" %}}


A(z) OFX fájl létrehozásához a(z) API lehetőséget biztosít [OfxRequestDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) és [OfxResponseDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) osztályok és fejlesztők könnyen [OFX kérés létrehozása](https://products.aspose.com/finance/net/create/ofx-request/) és válaszfájlok 1.03 és 2.2 formátumban. Az OfxRequestDocument tulajdonságok inicializálásához a API más osztályokat is biztosít, mint pl [SignonRequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonrequest), [Pénzintézet](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/financialinstitution) és [StatementTransactionRequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionrequest) osztályok. Hasonlóképpen, az OfxResponseDocument tulajdonságok inicializálásához a API támogató osztályokat biztosít, mint pl. [SignonResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse),  [StatementTransactionResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse) és [NyilatkozatTranzakció](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction). Az alábbiakban mindkét esetre vonatkozó kódrészletek találhatók a megfelelő osztályok használatával.

{{% blocks/products/pf/feature-page-code h3="C# Kód OFX kérési dokumentumok generálásához" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Kód OFX válaszdokumentumok generálásához" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
{{< /blocks/products/pf/feature-page-wrap >}}