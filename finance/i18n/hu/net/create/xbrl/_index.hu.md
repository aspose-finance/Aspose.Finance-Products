---
title: "XBRL fájl létrehozása a következőn keresztül: C#"
description: Mintakód a(z) XBRL fájl létrehozásához. Használjon API példakódot a XBRL fájlok kötegelt generálásához a .NET alapú alkalmazásokban. 
url: /hu/net/create/xbrl/
family: finance
platformtag: net
feature: create
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Hozzon létre XBRL fájlt a következőn keresztül: C#" h2="XBRL fájlok létrehozása a Microsoft Office vagy bármilyen más szoftver telepítése nélkül." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="XBRL Fájlok létrehozása" %}}

Kövesse a kódrészlet lépéseit, vagy javítsa az alkalmazás igényei szerint bővíthető üzleti jelentési nyelvű XBRL fájlok létrehozásához. Ügyeljen arra, hogy az alkalmazáson belül legyenek létrehozási követelmények.

1. Teremt [XbrlDocument osztály](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Példa.1. Új XBRL példány dokumentum létrehozása [XbrlInstanceCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) és [XbrlInstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance).1. Adjon hozzá sémahivatkozást a használatával [SchemaRefCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemarefcollection)1. Az alkalmazás jellegétől függően adjon hozzá kontextust, egységet, elemet, lábjegyzet hivatkozását és egyebeket.1. Hívja a [Mentés módja](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) a célfájl elérési út megadásával.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Létrehozási követelmény" %}}
A(z) XBRL dokumentumok létrehozásának folytatásához a(z) .NET Finance API fő követelmény, hogy szerepeljen az alkalmazásban. 
- Telepítse parancssorból ```nuget install Aspose.Finance``` néven, vagy a Visual Studio Package Manager konzolján keresztül az ```Install-Package Aspose.Finance``` paraméterrel.
- Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban innen [letöltések](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# kód XBRL fájl létrehozásához" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-schema-reference.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Egyéb létrehozási lehetőségek" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="OFX Kérelem" description="1.03 vagy 2.2 formátum" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-response/" name="OFX Válasz" description="1.03 vagy 2.2 formátum" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}