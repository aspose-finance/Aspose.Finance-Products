---
title: "XBRL fájl érvényesítése a következőn keresztül: C#"
description: Mintakód a(z) XBRL fájl érvényesítéséhez. Használjon API példakódot a kötegelt XBRL fájlok érvényesítéséhez a .NET alapú alkalmazásokban. 
url: /hu/net/validate/xbrl/
family: finance
platformtag: net
feature: validate
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="XBRL fájlok érvényesítése a következőn keresztül: C#" h2="Pénzügyi jelentések ellenőrzése XBRL formátumban Microsoft Office vagy bármilyen más szoftver telepítése nélkül." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="A XBRL fájlok érvényesítése" %}}

Kövesse a kódrészlet lépéseit, vagy javítsa azt az alkalmazás igényei szerint a bővíthető üzleti jelentési nyelvű XBRL dokumentumok érvényesítéséhez. Győződjön meg arról, hogy az alkalmazáson belül érvényesítési követelmények vannak.

1. XBRL fájl betöltése a következővel: [XbrlDocument osztály](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Példa.1. A betöltött fájl érvényességének ellenőrzéséhez, hogy egyeznie kell a [XBRL specifikáció](http://www.xbrl.org/specification/inlinexbrl-part1/rec-2013-11-18/inlinexbrl-part1-rec-2013-11-18.html)1. Az érvényesség ellenőrzéséhez használja a [Érvényesít()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) a metódusa [XbrlInstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance) osztály.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Érvényesítési követelmény" %}}
A(z) XBRL dokumentumok érvényesítésének folytatásához a(z) .NET Finance API fő követelmény, amelyet az alkalmazásba kell foglalni. 
- Telepítse parancssorból ```nuget install Aspose.Finance``` néven, vagy a Visual Studio Package Manager konzolján keresztül az ```Install-Package Aspose.Finance``` paraméterrel.
- Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban innen [letöltések](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# kód XBRL fájl érvényesítéséhez" offSpacer="" %}}

{{< gist "aspose-com-gists" "1272da1f804f8cef122600269db09fbb" "validate-xbrl-instance-file.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Egyéb érvényesítési lehetőségek" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/validate/ixbrl/" name="XBRL" description="Beépített bővíthető üzleti jelentési nyelv" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}