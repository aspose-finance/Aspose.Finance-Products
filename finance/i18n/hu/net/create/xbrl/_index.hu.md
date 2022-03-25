---
title: XBRL fájl létrehozása C# segítségével
description: Minta kód XBRL fájl létrehozásához. API példa kódot használjon a .NET alapú alkalmazásokon belül XBRL fájlok generálásához. 
url: /hu/net/create/xbrl/
family: finance
platformtag: net
feature: create
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="XBRL fájlok létrehozása C# segítségével" h2="XBRL fájlok létrehozása anélkül, hogy microsoft office telepített vagy más szoftver." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="XBRL fájlok létrehozása" %}}

Kövesse a kódrészlet lépéseit, vagy fokozza az alkalmazása igényeinek megfelelően a bővíthető üzleti jelentési nyelv XBRL fájlok generálásához. Győződjön meg róla, hogy létrehozási követelmények az alkalmazáson belül.

1. Create [Xbrldocument osztály](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Példány.1. Új XBRL példány dokumentum létrehozása [Xbrlinstancecollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) És [Xbrlinstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance)A "", a "" ", a" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "".1. Hozzáadása séma hivatkozás segítségével [Schemarefcollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemarefcollection)1. Az alkalmazás jellegétől függően adjunk hozzá kontextust, egységet, elemet, lábjegyzetet és még többet.1. Call the [Mentési módszer](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) A célfájl elérési útjának megadásával.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Létrehozási követelmény" %}}
A XBRL dokumentumok generálásához a .NET Finance API a fő követelmény, amelyet be kell venni az alkalmazásba. 
- Telepítse a parancssoron keresztül, mint "" nuget install Aspose.Finance "", vagy a visual studio csomagkezelő konzolján keresztül a "" install-package Aspose.Finance "".
- Alternatív módon, kap az offline msi telepítő vagy dll egy zip fájlt a [Letöltések](https://downloads.aspose.com/finance/net)A "", a "" ", a" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "".{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# kód XBRL fájlok létrehozásához" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-schema-reference.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Egyéb létrehozási lehetőségek" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="OFX kérelem" description="1.03 vagy 2.2 formátum" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-response/" name="OFX válasz" description="1.03 vagy 2.2 formátum" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}