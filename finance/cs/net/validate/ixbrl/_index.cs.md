---
title: Ověřit soubor iXBRL prostřednictvím C#
description: Ukázkový kód pro ověření souboru iXBRL. Použijte ukázkový kód API k ověření dávkových souborů iXBRL v aplikacích založených na .NET. 
url: /cs/net/validate/ixbrl/
family: finance
platformtag: net
feature: validate
informat: iXBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Ověřit soubory iXBRL prostřednictvím C#" h2="Ověřování finančních zpráv ve formátu iXBRL bez nutnosti instalace sady Microsoft Office nebo jiného softwaru." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Jak ověřit soubory iXBRL" %}}

Postupujte podle kroků ve úryvku kódu nebo jej vylepšete podle potřeb vaší aplikace pro ověřování dokumentů v rozšiřitelném jazyce podnikových výkazů iXBRL. Ujistěte se, že máte ve své aplikaci požadavky na ověření.

1. Načíst soubor iXBRL pomocí [Třída InlineXbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) Instance.1. Pro kontrolu platnosti načteného souboru, takže se musí shodovat s [iXBRL specifikace](http://www.xbrl.org/specification/inlinexbrl-part1/rec-2013-11-18/inlinexbrl-part1-rec-2013-11-18.html)1. Použití [Ověřit()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument/methods/validate) způsob platnosti souboru.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavek na ověření" %}}
Chcete-li pokračovat v ověřování dokumentů iXBRL, hlavním požadavkem, který má být součástí aplikace, je .NET Finance API. 
- Nainstalujte jej pomocí příkazového řádku jako ```nuget install Aspose.Finance``` nebo pomocí konzoly Správce balíčků sady Visual Studio s ```Install-Package Aspose.Finance```.
- Případně získejte offline instalační program MSI nebo knihovny DLL v souboru ZIP [stahování](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# kód pro ověření iXBRL souborů" offSpacer="" %}}

{{< gist "aspose-com-gists" "1272da1f804f8cef122600269db09fbb" "validate-ixbrl-file.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Další možnosti ověření" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/validate/xbrl/" name="XBRL" description="Rozšiřitelný jazyk pro obchodní výkaznictví" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}