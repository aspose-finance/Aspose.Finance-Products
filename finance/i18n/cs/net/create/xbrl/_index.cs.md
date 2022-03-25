---
title: Vytvořit soubor XBRL prostřednictvím C#
description: Vzorový kód pro vytvoření XBRL souboru. Použijte API příklad kódu pro generování souborů batch XBRL v aplikacích založených na .NET. 
url: /cs/net/create/xbrl/
family: finance
platformtag: net
feature: create
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Vytvořit XBRL soubory pomocí C#" h2="XBRL vytvoření souborů bez potřeby nainstalovaného microsoft office nebo jiného softwaru." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Jak vytvořit XBRL soubory" %}}

Postupujte podle kroků v úrypu kódu nebo jej zdokonalte podle potřeby aplikace pro generování rozšiřovatelných souborů s jazykem obchodního vykazování XBRL. Be sure of having creation requirements within your application.

1. Vytvořit [Třída xbrldocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Instance.1. Vytvořit nový dokument instance XBRL [Xbrlinstancecollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) A [Xbrlinstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance)A.1. Přidat odkaz na schéma pomocí [Schemarefcollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemarefcollection)1. Depending on application nature add context, unit, item, footnote link and more.1. Zavolejte [Uložit metodu](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) Poskytnutím cílové cesty souboru.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavek vytvoření" %}}
Chcete-li pokračovat v generování dokumentů XBRL, .NET Finance API je hlavní požadavek, který je třeba zahrnout do aplikace. 
- Nainstalujte ji na příkazovém řádku jako "nuget install Aspose.Finance" nebo přes konzolu správce balíků visual studio s "" install-package Aspose.Finance "".
- Alternativně získejte offline instalační program msi nebo dll v souboru zip z [Stahování](https://downloads.aspose.com/finance/net)A.{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# kód pro vytvoření souborů XBRL" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-schema-reference.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Další možnosti vytvoření" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="OFX požadavek" description="Formát 1.03 nebo 2.2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-response/" name="OFX odpověď" description="Formát 1.03 nebo 2.2" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}