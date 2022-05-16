---
title: "Hozzon létre OFX válaszfájlt a következőn keresztül: C#"
description: Mintakód a OFX válaszfájl létrehozásához. Használjon API példakódot a OFX válaszfájlok kötegelt generálásához a .NET alapú alkalmazásokban. 
url: /hu/net/create/ofx-response/
family: finance
platformtag: net
feature: create
informat: OFX Response
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Hozzon létre OFX válaszfájlt a következőn keresztül: C#" h2="OFX válaszfájlok létrehozása a Microsoft Office vagy bármilyen más szoftver telepítése nélkül." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="OFX válaszfájlok létrehozása" %}}

Kövesse a kódrészlet lépéseit, vagy javítsa azt az alkalmazás igényei szerint, miután az alkalmazáson belül megvannak a létrehozási követelmények.

1. Teremt [OfxResponseDocument osztály](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) tárgy.1. Rendelje hozzá a releváns tulajdonságokat a API like által biztosított különböző osztályok használatával [SignonResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse),  [StatementTransactionResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse), [NyilatkozatTranzakció](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction)1. Használja az ofxVersion V2x vagy V1x verziót az xml és sgml fájlokhoz [OffxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) paraméterként a Mentés metódusban.1. Hívja a [Mentés módja](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument/methods/save) a célfájl és az ofxVersion megadásával.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Létrehozási követelmény" %}}
A OFX válaszfájl létrehozásának folytatásához a .NET Finance API fő követelmény a jelentéskészítő alkalmazásban. 
- Telepítse a parancssorból ```nuget install Aspose.Finance``` néven, vagy a Visual Studio Package Manager konzolján keresztül az ```Install-Package Aspose.Finance``` paraméterrel.
- Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban innen [letöltések](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# kód OFX válaszfájl létrehozásához" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Egyéb létrehozási lehetőségek" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="OFX Fájl kérése" description="1.03 vagy 2.2 formátum" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/xbrl/" name="XBRL Fájl" description="Bővíthető üzleti jelentési nyelv" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}