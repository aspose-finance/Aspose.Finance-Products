---
title: "Hozzon létre OFX válaszfájlt a következőn keresztül: Python"
description: Mintakód a OFX válaszfájl létrehozásához. Használjon API példakódot a OFX válaszfájlok kötegelt generálásához a Python alapú alkalmazásokban. 
url: /hu/python-net/create/ofx-response/
family: finance
platformtag: python
feature: create
informat: OFX Response
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Hozzon létre OFX válaszfájlt a következőn keresztül: Python" h2="OFX válaszfájlok létrehozása a Microsoft Office vagy bármilyen más szoftver telepítése nélkül." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="OFX válaszfájlok létrehozása" %}}

Kövesse a kódrészlet lépéseit, vagy javítsa azt az alkalmazás igényei szerint, miután az alkalmazáson belül megvannak a létrehozási követelmények.

1. Hozzon létre OfxResponseDocument osztályobjektumot.1. Rendelje hozzá a releváns tulajdonságokat a API által biztosított különböző osztályok használatával, például SignonResponse, StatementTransactionResponse, StatementTransaction1. Használja az ofxVersion V2x vagy V1x fájlt az OfxVersionEnum xml és sgml fájljaihoz a mentési módszer paramétereként.1. Hívja meg a mentési módszert a célfájl és az ofxVersion megadásával.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Létrehozási követelmény" %}}
A OFX válaszfájl létrehozásának folytatásához győződjön meg arról, hogy rendelkezik a következő előfeltételekkel. 
- Microsoft Windows vagy Linux alapú operációs rendszer.- Python 3.5 vagy újabb.- Aspose.Finance a projektben hivatkozott Python számára.{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python kód OFX válaszfájl létrehozásához" offSpacer="" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-response-files.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Egyéb létrehozási lehetőségek" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/ofx-request/" name="OFX Fájl kérése" description="1.03 vagy 2.2 formátum" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/xbrl/" name="XBRL Fájl" description="Bővíthető üzleti jelentési nyelv" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}