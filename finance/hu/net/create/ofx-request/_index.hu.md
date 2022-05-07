---
title: "Hozzon létre OFX kérési fájlt a következőn keresztül: C#"
description: Mintakód a OFX kérelemfájl létrehozásához. Használjon API példakódot a kötegelt OFX kérelemfájlok generálásához a .NET alapú alkalmazásokban. 
url: /hu/net/create/ofx-request/
family: finance
platformtag: net
feature: create
informat: OFX Request
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Hozzon létre OFX kérési fájlt a következőn keresztül: C#" h2="OFX kérheti a fájlok létrehozását a Microsoft Office vagy bármilyen más szoftver telepítése nélkül." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="OFX Kérelemfájlok létrehozása" %}}

Miután megtörtént a OFX Fájlok létrehozására vonatkozó követelmények az alkalmazáson belül, kövesse a kódrészletben található lépéseket, vagy javítsa ki azt igénye szerint.

1. Teremt [OfxRequestDocument osztály](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) tárgy.1. Rendelje hozzá a releváns tulajdonságokat a API like által biztosított különböző osztályok használatával [SignonRequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonrequest), [Pénzintézet](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/financialinstitution), [StatementTransactionRequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionrequest)1. Használja az ofxVersion V2x vagy V1x verziót az xml és sgml fájlokhoz [OffxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) paraméterként a Mentés metódusban.1. Hívja a [Mentés módja](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument/methods/save) a célfájl és az ofxVersion megadásával.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Létrehozási követelmény" %}}
A OFX Kérelemfájl létrehozásának folytatásához a .NET Finance API fő követelmény, hogy szerepeljen a jelentéskészítő alkalmazásban. 
- Telepítse parancssorból ```nuget install Aspose.Finance``` néven, vagy a Visual Studio Package Manager konzolján keresztül az ```Install-Package Aspose.Finance``` paraméterrel.
- Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban innen [letöltések](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# kód OFX kérelemfájl létrehozásához" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-request-files.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Egyéb létrehozási lehetőségek" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-response/" name="OFX Válaszfájl" description="1.03 vagy 2.2 formátum" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/xbrl/" name="XBRL Fájl" description="Bővíthető üzleti jelentési nyelv" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}