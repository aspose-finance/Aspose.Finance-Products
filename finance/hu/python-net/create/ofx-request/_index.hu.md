---
title: "Hozzon létre OFX kérési fájlt a következőn keresztül: Python"
description: Mintakód a OFX kérelemfájl létrehozásához. Használjon API példakódot a kötegelt OFX kérelemfájlok generálásához a Python alapú alkalmazásokban. 
url: /hu/python-net/create/ofx-request/
family: finance
platformtag: python
feature: create
informat: OFX Request
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Hozzon létre OFX kérési fájlt a következőn keresztül: Python" h2="OFX kérheti a fájlok létrehozását a Microsoft Office vagy bármilyen más szoftver telepítése nélkül." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="OFX Kérelemfájlok létrehozása" %}}

Miután megtörtént a OFX Fájlok létrehozására vonatkozó követelmények az alkalmazáson belül, kövesse a kódrészletben található lépéseket, vagy javítsa ki azt igénye szerint.

1. Hozzon létre OfxRequestDocument osztályobjektumot.2. Rendelje hozzá a releváns tulajdonságokat a API által biztosított különböző osztályok használatával, például SignonRequest, FinancialInstitution], StatementTransactionRequest
3. Használja az ofxVersion V2x vagy V1x paramétert az OfxVersionEnum xml és sgml fájljaihoz a Mentés metódus paramétereként.
4. Hívja meg a mentési módszert a célfájl és az ofxVersion megadásával.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Létrehozási követelmény" %}}
Ha folytatni szeretné a OFX Fájl létrehozásának kérelmezését, győződjön meg arról, hogy rendelkezik a következő előfeltételekkel. 
- Microsoft Windows vagy Linux alapú operációs rendszer.- Python 3.5 vagy újabb.- Aspose.Finance a projektben hivatkozott Python számára.{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python kód OFX kérelemfájl létrehozásához" offSpacer="" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-request-files.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Egyéb létrehozási lehetőségek" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/ofx-response/" name="OFX Válaszfájl" description="1.03 vagy 2.2 formátum" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/xbrl/" name="XBRL Fájl" description="Bővíthető üzleti jelentési nyelv" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}