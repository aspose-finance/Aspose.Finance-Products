---
title: Utwórz plik iXBRL(wbudowany xbrl) przez C#
description: Przykładowy kod do tworzenia pliku iXBRL(inline xbrl). Użyj przykładowego kodu API do generowania plików wsadowych iXBRL(inline xbrl) w aplikacjach opartych na .NET. 
url: /pl/net/create/ixbrl/
family: finance
platformtag: net
feature: create
informat: iXBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Twórz pliki iXBRL(inline xbrl) przez C#" h2="iXBRLTworzenie plików (wbudowanych w formacie xbrl) bez konieczności instalowania pakietu Microsoft Office lub innego oprogramowania." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Jak tworzyć iXBRLpliki (wbudowane xbrl)" %}}

Wykonaj czynności opisane we fragmencie kodu lub ulepsz go zgodnie z potrzebami aplikacji, aby wygenerować rozszerzalne pliki języka raportowania biznesowego iXBRL(wbudowane xbrl). Upewnij się, że aplikacja zawiera wymagania dotyczące tworzenia.

1. Tworzyć [Klasa InlineXbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) Instancja.2. Zbuduj drzewo dom
3. Zadzwoń do [Zapisz metodę](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline.inlinexbrldocument/save/methods/1) podając ścieżkę do pliku docelowego.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymóg tworzenia" %}}
Aby kontynuować iXBRLgenerowanie dokumentów (inline xbrl), .NET Finance API jest głównym wymaganiem dołączonym do aplikacji. 
- Zainstaluj go za pomocą wiersza poleceń jako ```nuget install Aspose.Finance``` lub za pomocą konsoli Menedżera pakietów programu Visual Studio za pomocą ```Install-Package Aspose.Finance```.
- Alternatywnie, pobierz instalator MSI offline lub biblioteki DLL w pliku ZIP z [pliki do pobrania](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# kod do tworzenia XBRL plików" offSpacer="" %}}

{{< gist "aspose-finance-gists" "e4ec79e68a0658a63611ae321b110a48" "create-ixbrl.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Inne opcje tworzenia" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="OFX Prośba" description="Format 1.03 lub 2.2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-response/" name="OFX Odpowiedź" description="Format 1.03 lub 2.2" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}