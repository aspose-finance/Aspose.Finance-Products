---
title: "iXBRL fájl megtekintése a következőn keresztül: C#"
description: Mintakód a(z) iXBRL fájl megtekintéséhez. Használjon API példakódot a iXBRL fájlok kötegelt megtekintéséhez a .NET alapú alkalmazásokban. 
url: /hu/net/view/ixbrl/
family: finance
platformtag: net
feature: view
informat: iXBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="iXBRL fájl megtekintése a következőn keresztül: C#" h2="Pénzügyi jelentések megtekintése iXBRL formátumban a Microsoft Office vagy bármilyen más szoftver telepítése nélkül." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="A(z) iXBRL fájlok megtekintése" %}}

Kövesse a kódrészlet lépéseit, vagy javítsa azt az alkalmazás igényeinek megfelelően a bővíthető üzleti jelentési nyelvű iXBRL dokumentumok megtekintéséhez. Győződjön meg arról, hogy az alkalmazásban olvasási követelmények vannak.

1. Teremt [InlineXbrlDocument osztály](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) Példa.2. Adja meg egy érvényes iXBRL fájl nevét paraméterként.
3. A fájl belső részleteinek megtekintéséhez használja a megfelelő osztályokat, mint pl [InlineFact](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinefact), [Kontextus](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/context), [Mértékegység](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/unit) 
4. Mutassa meg ezeket az információkat

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Olvasási követelmény" %}}
A(z) iXBRL dokumentumok megtekintésének folytatásához a(z) .NET Finance API fő követelmény, hogy szerepeljen az alkalmazásban. 
- Telepítse parancssorból ```nuget install Aspose.Finance``` néven, vagy a Visual Studio Package Manager konzolján keresztül az ```Install-Package Aspose.Finance``` paraméterrel.
- Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban innen [letöltések](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# kód iXBRL fájl olvasásához" offSpacer="" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "read-ixbrl-file.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Egyéb megtekintési lehetőségek" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/view/xbrl/" name="XBRL" description="Bővíthető üzleti jelentési nyelv" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}