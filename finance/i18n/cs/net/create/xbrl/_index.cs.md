---
title: Vytvořit soubor XBRL prostřednictvím C#
description: Ukázkový kód pro vytvoření souboru XBRL. Použijte API ukázkový kód pro dávkové generování XBRL souborů v aplikacích založených na .NET. 
url: /cs/net/create/xbrl/
family: finance
platformtag: net
feature: create
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Vytvořit XBRL souborů prostřednictvím C#" h2="Vytvoření XBRL souborů bez nutnosti instalace sady Microsoft Office nebo jiného softwaru." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Jak vytvořit soubory XBRL" %}}

Postupujte podle kroků ve fragmentu kódu nebo jej vylepšete podle potřeb vaší aplikace pro generování rozšiřitelných souborů v jazyce obchodního reportingu XBRL. Ujistěte se, že máte ve své aplikaci požadavky na vytvoření.

1. Vytvořit [Třída XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Instance.1. Chcete-li vytvořit nový dokument instance XBRL [XbrlInstanceCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) a [XbrlInstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance).1. Přidejte odkaz na schéma pomocí [SchemaRefCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemarefcollection)1. V závislosti na povaze aplikace přidejte kontext, jednotku, položku, odkaz na poznámku pod čarou a další.1. Zavolej [Uložit metodu](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) zadáním cesty k cílovému souboru.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavek na vytvoření" %}}
Chcete-li pokračovat ve generování dokumentů XBRL, hlavním požadavkem, který má být součástí aplikace, je .NET Finance API. 
- Nainstalujte jej pomocí příkazového řádku jako ```nuget install Aspose.Finance``` nebo pomocí konzoly Správce balíčků sady Visual Studio s ```Install-Package Aspose.Finance```.
- Případně získejte offline instalační program MSI nebo knihovny DLL v souboru ZIP [stahování](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# kód pro vytvoření XBRL souborů" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-schema-reference.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Další možnosti tvorby" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="Žádost OFX" description="Formát 1.03 nebo 2.2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-response/" name="OFX Odpověď" description="Formát 1.03 nebo 2.2" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}