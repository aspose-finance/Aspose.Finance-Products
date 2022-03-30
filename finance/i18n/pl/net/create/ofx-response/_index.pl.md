---
title: Utwórz plik odpowiedzi OFX przez C#
description: Przykładowy kod do tworzenia pliku odpowiedzi OFX. Użyj API przykładowego kodu do wsadowego OFX generowania plików odpowiedzi w aplikacjach opartych na .NET. 
url: /pl/net/create/ofx-response/
family: finance
platformtag: net
feature: create
informat: OFX Response
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Utwórz OFX pliki odpowiedzi przez C#" h2="OFX tworzenie plików odpowiedzi bez konieczności instalowania pakietu Microsoft Office lub innego oprogramowania." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Jak utworzyć OFX pliki odpowiedzi" %}}

Wykonaj czynności opisane we fragmencie kodu lub ulepsz go zgodnie z potrzebami aplikacji po spełnieniu wymagań dotyczących tworzenia w aplikacji.

1. Tworzyć [Klasa OfxResponseDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) obiekt.1. Przypisz odpowiednie właściwości, używając różnych klas dostarczonych przez API like [Zaloguj sięOdpowiedź](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse),  [WyciągTransakcjaOdpowiedź](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse), [WyciągTransakcja](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction)1. Użyj ofxVersion V2x lub V1x odpowiednio dla plików xml i sgml z [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) jako parametr w metodzie Save.1. Zadzwoń do [Zapisz metodę](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument/methods/save) dostarczając plik docelowy i ofxVersion.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymóg tworzenia" %}}
Aby przejść do OFX tworzenia pliku odpowiedzi, .NET Finance API jest głównym wymaganiem dołączenia do aplikacji do generowania raportów. 
- Zainstaluj go za pomocą wiersza poleceń jako ```nuget install Aspose.Finance``` lub za pomocą konsoli Menedżera pakietów programu Visual Studio za pomocą ```Install-Package Aspose.Finance```.
- Alternatywnie, pobierz instalator MSI offline lub biblioteki DLL w pliku ZIP z [pliki do pobrania](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# kod do OFX tworzenia plików odpowiedzi" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Inne opcje tworzenia" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="OFX Poproś o plik" description="Format 1.03 lub 2.2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/xbrl/" name="XBRL Plik" description="Rozszerzalny język raportowania biznesowego" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}