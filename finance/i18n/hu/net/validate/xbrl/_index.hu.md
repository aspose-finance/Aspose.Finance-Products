---
title: XBRL fájl validálása C# segítségével
description: A XBRL fájl érvényesítésének minta kódja. API példakóddal igazolja a .NET alapú alkalmazásokon belüli batch XBRL fájlokat. 
url: /hu/net/validate/xbrl/
family: finance
platformtag: net
feature: validate
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="XBRL fájlok validálása C#-en keresztül" h2="A pénzügyi jelentések XBRL formátumban történő validálása a microsoft office telepített vagy más szoftver nélkül." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="XBRL fájlok validálása" %}}

Kövesse a kódrészlet lépéseit, vagy fokozza az alkalmazása igényeinek megfelelően a bővíthető üzleti jelentési nyelv XBRL dokumentumok validálásához. Győződjön meg róla, hogy az ön alkalmazásán belül érvényesítő követelményeket.

1. XBRL fájl betöltése segítségével [Xbrldocument osztály](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Példány.1. A betöltött fájl érvényességének ellenőrzéséhez, így meg kell egyeznie vele [XBRL specifikáció](http://www.xbrl.org/specification/inlinexbrl-part1/rec-2013-11-18/inlinexbrl-part1-rec-2013-11-18.html)1. Az érvényesség ellenőrzéséhez használja [Validate()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) Módszer [Xbrlinstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance) Osztályt.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Érvényesítési követelmény" %}}
A XBRL dokumentumok validálásához a .NET Finance API a fő követelmény, amelyet be kell venni az alkalmazásba. 
- Telepítse a parancssoron keresztül, mint "" nuget install Aspose.Finance "", vagy a visual studio csomagkezelő konzolján keresztül a "" install-package Aspose.Finance "".
- Alternatív módon, kap az offline msi telepítő vagy dll egy zip fájlt a [Letöltések](https://downloads.aspose.com/finance/net)A "", a "" ", a" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "".{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# kód XBRL fájlok érvényesítésére" offSpacer="" %}}

{{< gist "aspose-com-gists" "1272da1f804f8cef122600269db09fbb" "validate-xbrl-instance-file.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Egyéb érvényesítési lehetőségek" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/validate/ixbrl/" name="XBRL" description="Inline kiterjeszthető üzleti jelentési nyelv" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}