---
title: Převést XBRL na iXBRL prostřednictvím C#
description: Ukázkový kód pro konverzi XBRL na SEC xlsx report C#. Použijte API ukázkový kód pro dávkové soubory XBRL na převod sestav SEC xlsx v aplikacích založených na .NET. 
url: /cs/net/conversion/xbrl-to-sec-xlsx-report/
family: finance
platformtag: net
feature: convert
informat: XBRL
outformat: XLSX
otherformats: HTML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Převést sestavu XBRL na SEC xlsx prostřednictvím C#" h2="Převod zpráv XBRL na SEC xlsx bez potřeby dalšího softwaru v aplikacích založených na .NET." >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) je API pro zpracování XBRL, formátů iXBRL a vývojáři mohou snadno vytvářet softwarové aplikace pro správu obchodních procesů, finanční analýzu a výkaznictví, aby mohli převádět, vytvářet, číst, zobrazovat a ověřovat XBRL a iXBRL související s financemi soubory. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Jak převést XBRL na zprávu SEC xlsx" %}}
1. Načíst vstupní soubor XBRL pomocí [Třída XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument).2. Nastavte [UložitMožnosti](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions) pro výstupní soubor výběrem [SaveFormat.SEC_XLSX_REPORT](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveformat).
3. Zavolejte na [Uložit metodu](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/2) poskytnutím cílového souboru a příslušných SaveOptions jako parametrů.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Chcete-li pokračovat pro konverzi sestavy XBRL na SEC xlsx, je hlavním požadavkem .NET Finance API. Nainstalujte jej pomocí příkazového řádku jako ```nuget install Aspose.Finance``` nebo prostřednictvím konzoly Správce balíčků sady Visual Studio s ```Install-Package Aspose.Finance```.

Případně získejte offline instalační program MSI nebo knihovny DLL v souboru ZIP [stahování](https://downloads.aspose.com/finance/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Zdrojový kód C# pro převod XBRL do souboru sestavy SEC xlsx" offSpacer="" %}}

{{< gist "aspose-finance-gists" "283cfe3a6a0f0493c28290717b5b9379" "convert-xbrl-to-xlsx-sec-report.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Další možnosti převodu" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/conversion/xbrl-to-xlsx/" name="XBRL až XLSX" description="Microsoft Excel Open XML Spreadsheet" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/conversion/ofx-response/" name="OFX Odpověď" description="Od 1.03 do 2.2 Formát" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/conversion/ofx-request/" name="Žádost OFX" description="Od 1.03 do 2.2 Formát" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}