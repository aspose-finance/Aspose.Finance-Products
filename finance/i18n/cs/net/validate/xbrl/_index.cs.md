---
title: Ověřit soubor XBRL pomocí C#
description: Vzorový kód pro validaci XBRL souboru. Použijte API příkladový kód pro ověření souborů batch XBRL v aplikacích založených na .NET. 
url: /cs/net/validate/xbrl/
family: finance
platformtag: net
feature: validate
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Ověřit soubory XBRL pomocí C#" h2="Ověření finančních zpráv ve formátu XBRL bez potřeby nainstalovaného microsoft office nebo jiného softwaru." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Jak ověřit XBRL soubory" %}}

Postupujte podle kroků v úrypu kódu nebo jej zdokonalte podle potřeby aplikace pro validaci rozšiřovatelných dokumentů v jazyce obchodního vykazování XBRL. Ujistěte se, že budete mít požadavky na ověření v rámci vaší aplikace.

1. Načíst soubor XBRL pomocí [Třída xbrldocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Instance.1. Chcete-li ověřit platnost načteného souboru tak, aby se měl shodovat s [XBRL specifikace](http://www.xbrl.org/specification/inlinexbrl-part1/rec-2013-11-18/inlinexbrl-part1-rec-2013-11-18.html)1. Chcete-li ověřit platnost, použijte [Validate()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) Metoda [Xbrlinstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance) Třída.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavek na ověření" %}}
.NET Finance API je hlavní požadavek, který je třeba zahrnout do aplikace. 
- Nainstalujte ji na příkazovém řádku jako "nuget install Aspose.Finance" nebo přes konzolu správce balíků visual studio s "" install-package Aspose.Finance "".
- Alternativně získejte offline instalační program msi nebo dll v souboru zip z [Stahování](https://downloads.aspose.com/finance/net)A.{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# kód pro ověření XBRL souborů" offSpacer="" %}}

{{< gist "aspose-com-gists" "1272da1f804f8cef122600269db09fbb" "validate-xbrl-instance-file.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Další možnosti validace" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/validate/ixbrl/" name="XBRL" description="Inline extensible business reporting language" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}