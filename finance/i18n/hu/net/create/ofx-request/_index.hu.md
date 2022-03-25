---
title: OFX kérés fájl létrehozása C# segítségével
description: Minta kód OFX kérelem fájl létrehozásához. API példa kódot használjon a .NET alapú alkalmazásokon belül OFX kérés fájlok generálásához. 
url: /hu/net/create/ofx-request/
family: finance
platformtag: net
feature: create
informat: OFX Request
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="OFX kérés fájlok létrehozása C# segítségével" h2="OFX a microsoft office telepített vagy más szoftver nélkül szükséges fájlok létrehozása." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Hogyan hozhatunk létre OFX kérési fájlokat" %}}

Miután a OFX kérelem fájlok létrehozási követelmények az alkalmazáson belül, kövesse a kódrészlet lépéseit, vagy fokozza a követelmény szerint.

1. Create [Ofxrequestdocument osztály](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) Objektumot.1. Hozzárendelje a vonatkozó tulajdonságokat különböző osztályok által megadott API mint [Signonrequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonrequest), [Financialinstitution](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/financialinstitution), [Statementtransactionrequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionrequest)1. Használja az ofxversion v2x vagy v1x xml és sgml fájlokat [Ofxversionenum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) A mentési módszer paramétereként.1. Call the [Mentési módszer](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument/methods/save) A célfájl és az ofxversion megadásával.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Létrehozási követelmény" %}}
A OFX kérés fájl létrehozásához a .NET Finance API a fő követelmény, amelyet a jelentés-generálás alkalmazásban kell bekeríteni. 
- Telepítse a parancssoron keresztül, mint "" nuget install Aspose.Finance "", vagy a visual studio csomagkezelő konzolján keresztül a "" install-package Aspose.Finance "".
- Alternatív módon, kap az offline msi telepítő vagy dll egy zip fájlt a [Letöltések](https://downloads.aspose.com/finance/net)A "", a "" ", a" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "".{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# kód OFX kérelem fájlok létrehozása" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-request-files.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Egyéb létrehozási lehetőségek" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-response/" name="OFX válaszfájl" description="1.03 vagy 2.2 formátum" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/xbrl/" name="XBRL fájl" description="Bővíthető üzleti jelentési nyelv" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}