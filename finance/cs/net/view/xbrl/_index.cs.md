---
title: Zobrazit soubor XBRL prostřednictvím C#
description: Ukázkový kód pro zobrazení souboru XBRL. Použijte ukázkový kód API k zobrazení dávkových souborů XBRL v aplikacích založených na .NET. 
url: /cs/net/view/xbrl/
family: finance
platformtag: net
feature: view
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Zobrazit soubory XBRL prostřednictvím C#" h2="Prohlížení finančních zpráv ve formátu XBRL bez nutnosti instalace sady Microsoft Office nebo jiného softwaru." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Jak zobrazit soubory XBRL" %}}

Postupujte podle kroků ve úryvku kódu nebo jej vylepšete podle potřeb vaší aplikace pro čtení souborů v rozšiřitelném jazyce pro obchodní výkaznictví XBRL. Ujistěte se, že máte ve své aplikaci požadavky na čtení.

1. Vytvořit [Třída XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Instance.2. Předejte název platného souboru XBRL jako parametr.
3. Pro získání vnitřních detailů souboru použijte příslušné třídy jako např [SchemaRefCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemarefcollection), [Kontext](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/context), [Jednotka](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/unit) 
4. Ukažte tyto informace

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavek na čtení" %}}
Chcete-li pokračovat v zobrazení dokumentů XBRL, hlavním požadavkem, který má být součástí aplikace, je .NET Finance API. 
- Nainstalujte jej pomocí příkazového řádku jako ```nuget install Aspose.Finance``` nebo pomocí konzoly Správce balíčků sady Visual Studio s ```Install-Package Aspose.Finance```.
- Případně získejte offline instalační program MSI nebo knihovny DLL v souboru ZIP [stahování](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# kód pro čtení XBRL souborů" offSpacer="" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "read-xbrl-file.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Další možnosti zobrazení" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/view/ixbrl/" name="iXBRL" description="Inline Extensible Business Reporting Language" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}