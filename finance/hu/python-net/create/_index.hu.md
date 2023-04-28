---
title: "Pénzügyi jelentések létrehozása a következőn keresztül: Python"
url: /hu/python-net/create/
description:  Python kódot pénzügyi jelentések létrehozásához a(z) XBRL webhelyen, és OFX kérés- vagy válaszfájlt a Python könyvtáron keresztül.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Pénzügyi jelentési fájlok létrehozása a következőn keresztül: Python" h2="Pénzügyi jelentésformátumok létrehozása, beleértve a XBRL és OFX kérés- vagy válaszfájlt 1.03 vagy 2.2 formátumban a Python alapú alkalmazásokban." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance, Python ezen keresztül: .NET](https://products.aspose.com/finance/python-net/) egy funkciókban gazdag, bővíthető és könnyen használható pénzügyi jelentések létrehozása és feldolgozása API. A fejlesztők könnyedén létrehozhatnak XBRL példányt a semmiből, valamint hozzáadhatnak sémahivatkozást, kontextust, egységet, elemet, lábjegyzet hivatkozást, szerephivatkozást és 
ív szerephivatkozás. A API minden funkcióhoz megfelelő osztályt biztosít, például a kontextushoz, a fejlesztők használhatják a ContextPeriod, a ContextEntity és a Context elemeket. 
Ezenkívül a API támogatja a nyílt pénzügyi csere (OFX) formátumú kérés/válasz létrehozását 1.03 vagy 2.2 formátumban.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Hozzon létre XBRL fájlt elem hozzáadásával" %}}

A(z) XBRL fájl létrehozásához és az elem dokumentumhoz való hozzáadásához a folyamat az XbrlDocument osztálypéldány létrehozása. Készítse elő az elem releváns beállításait a megfelelő API osztályok, például a SchemaRef osztály, a fent említett releváns kontextusosztályok és a Concept osztály használatával. Végül határozza meg és inicializálja az elemosztály tulajdonságait, valamint hívja meg a mentési metódust a XBRL fájl lemezre való létrehozásához.

{{% blocks/products/pf/feature-page-code h3="Python Kód XBRL fájl létrehozásához elem hozzáadásával" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-xbrl-file-and-add-item.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Hozzon létre OFX kérés- és válaszfájlokat" %}}


A(z) OFX fájlok generálásához a(z) API OfxRequestDocument és OfxResponseDocument osztályokat biztosít, és a fejlesztők könnyen [OFX kérés létrehozása](https://products.aspose.com/finance/python-net/create/ofx-request/) és válaszfájlok 1.03 és 2.2 formátumban. Az OfxRequestDocument tulajdonságok inicializálásához a API további osztályokat is biztosít, például a SignonRequest, a FinancialInstitution és a StatementTransactionRequest osztályokat. Hasonlóképpen, az OfxResponseDocument tulajdonságok inicializálásához a API olyan támogató osztályokat biztosít, mint a SignonResponse, StatementTransactionResponse és StatementTransaction. Az alábbiakban mindkét esetre vonatkozó kódrészletek találhatók a megfelelő osztályok használatával.

{{% blocks/products/pf/feature-page-code h3="Python Kód OFX kérési dokumentumok generálásához" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-response-files.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Python Kód OFX válaszdokumentumok generálásához" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-response-files.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
{{< /blocks/products/pf/feature-page-wrap >}}