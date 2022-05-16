---
title: Konwertuj XBRL na iXBRL przez C#
description: Przykładowy kod konwersji raportu XBRL na SEC xlsx C#. Użyj API przykładowego kodu dla plików wsadowych XBRL do konwersji raportów SEC xlsx w aplikacjach opartych na .NET. 
url: /pl/net/conversion/xbrl-to-sec-xlsx-report/
family: finance
platformtag: net
feature: convert
informat: XBRL
outformat: XLSX
otherformats: HTML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konwertuj XBRL na raport SEC xlsx przez C#" h2="Konwersja raportów XBRL na SEC xlsx bez konieczności korzystania z żadnego innego oprogramowania w aplikacjach opartych na .NET." >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) to API do przetwarzania XBRL, iXBRL formatów, a programiści mogą łatwo tworzyć aplikacje do zarządzania procesami biznesowymi, analizy finansowej i raportowania do konwertowania, tworzenia, czytania, przeglądania i weryfikowania XBRL i iXBRL związanych z finansami akta. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Jak przekonwertować XBRL na raport SEC xlsx" %}}
1. Załaduj plik wejściowy XBRL za pomocą [Klasa XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument).2. Ustaw [ZapiszOpcje](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions) dla pliku wyjściowego, wybierając [ZapiszFormat.SEC_XLSX_REPORT](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveformat).
3. Zadzwoń do [Zapisz metodę](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/2) podając plik docelowy i odpowiednie SaveOptions jako parametry.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Aby przejść do konwersji raportu XBRL na SEC xlsx, głównym wymaganiem jest .NET Finance API. Zainstaluj go za pomocą wiersza poleceń jako ```nuget install Aspose.Finance``` lub za pomocą konsoli Menedżera pakietów programu Visual Studio za pomocą ```Install-Package Aspose.Finance```.

Alternatywnie, pobierz instalator MSI offline lub biblioteki DLL w pliku ZIP z [pliki do pobrania](https://downloads.aspose.com/finance/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# kod źródłowy do konwersji XBRL na plik raportu SEC xlsx" offSpacer="" %}}

{{< gist "aspose-finance-gists" "283cfe3a6a0f0493c28290717b5b9379" "convert-xbrl-to-xlsx-sec-report.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Inne opcje konwersji" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/conversion/xbrl-to-xlsx/" name="XBRL do XLSX" description="Arkusz kalkulacyjny Microsoft Excel Open XML" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/conversion/ofx-response/" name="OFX Odpowiedź" description="Od formatu 1.03 do 2.2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/conversion/ofx-request/" name="OFX Prośba" description="Od formatu 1.03 do 2.2" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}