---
title: Číst soubor iXBRL prostřednictvím C#
description: Ukázkový kód pro čtení souboru iXBRL. Použijte ukázkový kód API ke čtení dávkových souborů iXBRL v aplikacích založených na .NET. 
url: /cs/net/read/ixbrl/
family: finance
platformtag: net
feature: read
informat: iXBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Číst soubory iXBRL prostřednictvím C#" h2="Čtení finančních zpráv ve formátu iXBRL bez nutnosti instalace sady Microsoft Office nebo jiného softwaru." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Jak číst soubory iXBRL" %}}

Postupujte podle kroků ve úryvku kódu nebo jej vylepšete podle potřeb vaší aplikace pro čtení dokumentů v rozšiřitelném jazyce podnikových výkazů iXBRL. Ujistěte se, že máte ve své aplikaci požadavky na čtení.

1. Vytvořit [Třída InlineXbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) Instance.1. Předejte název platného souboru iXBRL jako parametr.1. Chcete-li získat vnitřní detaily souboru, použijte příslušné třídy jako např [InlineFact](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinefact), [Kontext](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/context), [Jednotka](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/unit) 
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavek na čtení" %}}
Chcete-li pokračovat ve čtení dokumentů iXBRL, hlavním požadavkem, který má být součástí aplikace, je .NET Finance API. 
- Nainstalujte jej pomocí příkazového řádku jako ```nuget install Aspose.Finance``` nebo pomocí konzoly Správce balíčků sady Visual Studio s ```Install-Package Aspose.Finance```.
- Případně získejte offline instalační program MSI nebo knihovny DLL v souboru ZIP [stahování](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# kód pro čtení iXBRL souborů" offSpacer="" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "read-ixbrl-file.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Další možnosti čtení" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/read/xbrl/" name="XBRL" description="Rozšiřitelný jazyk pro obchodní výkaznictví" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}