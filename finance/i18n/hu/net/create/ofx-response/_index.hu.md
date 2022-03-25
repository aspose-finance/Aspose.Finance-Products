---
title: OFX válaszfájl létrehozása C# segítségével
description: Minta kód OFX válasz fájl létrehozásához. API példa kódot használjon a .NET alapú alkalmazásokon belül a OFX válaszfájlok generálásához. 
url: /hu/net/create/ofx-response/
family: finance
platformtag: net
feature: create
informat: OFX Response
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="OFX válaszfájlok létrehozása C# segítségével" h2="OFX válasz fájlok létrehozása anélkül, hogy a microsoft office telepített vagy más szoftver." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Hogyan készítsünk OFX válaszfájlokat" %}}

Kövesse a kódrészlet lépéseit, vagy fokozza az alkalmazása igényeinek megfelelően, miután a létrehozási követelmények az alkalmazáson belül.

1. Create [Ofxresponsedocument osztály](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) Objektumot.1. Hozzárendelje a vonatkozó tulajdonságokat különböző osztályok által megadott API mint [Bejelentkezési válasz](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse),  [Statementtransactionresponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse), [Statementtranzakció](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction)1. Használja az ofxversion v2x vagy v1x xml és sgml fájlokat [Ofxversionenum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) A mentési módszer paramétereként.1. Call the [Mentési módszer](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument/methods/save) A célfájl és az ofxversion megadásával.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Létrehozási követelmény" %}}
A OFX válaszfájl létrehozásához a .NET Finance API a fő követelmény, amelyet a jelentés-generálás alkalmazásban kell bevenni. 
- Telepítse a parancssoron keresztül, mint "" nuget install Aspose.Finance "", vagy a visual studio csomagkezelő konzolján keresztül a "" install-package Aspose.Finance "".
- Alternatív módon, kap az offline msi telepítő vagy dll egy zip fájlt a [Letöltések](https://downloads.aspose.com/finance/net)A "", a "" ", a" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "".{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# kód OFX válaszfájlok létrehozásához" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Egyéb létrehozási lehetőségek" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="OFX kérelem fájl" description="1.03 vagy 2.2 formátum" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/xbrl/" name="XBRL fájl" description="Bővíthető üzleti jelentési nyelv" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}