---
title: Utwórz OFX Zażądaj pliku przez C#
description: Przykładowy kod do tworzenia pliku żądania OFX. Użyj API przykładowego kodu do wsadowego OFX generowania plików żądań w aplikacjach opartych na .NET. 
url: /pl/net/create/ofx-request/
family: finance
platformtag: net
feature: create
informat: OFX Request
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Utwórz OFX pliki żądań przez C#" h2="OFX żądaj tworzenia plików bez konieczności instalowania pakietu Microsoft Office lub innego oprogramowania." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Jak utworzyć OFX pliki żądań" %}}

Po spełnieniu OFXwymagań dotyczących tworzenia plików żądania w swojej aplikacji, postępuj zgodnie z instrukcjami we fragmencie kodu lub ulepsz go zgodnie z wymaganiami.

1. Tworzyć [OfxRequestDocument class](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) obiekt.1. Przypisz odpowiednie właściwości, używając różnych klas dostarczonych przez API like [Żądanie logowania](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonrequest), [Instytucja finansowa](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/financialinstitution), [WyciągZlecenie Transakcji](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionrequest)1. Użyj ofxVersion V2x lub V1x odpowiednio dla plików xml i sgml z [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) jako parametr w metodzie Save.1. Zadzwoń do [Zapisz metodę](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument/methods/save) dostarczając plik docelowy i ofxVersion.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymóg tworzenia" %}}
Aby kontynuować OFX tworzenie pliku żądania, .NET Finance API jest głównym wymaganiem dołączenia do aplikacji do generowania raportów. 
- Zainstaluj go za pomocą wiersza poleceń jako ```nuget install Aspose.Finance``` lub za pomocą konsoli Menedżera pakietów programu Visual Studio za pomocą ```Install-Package Aspose.Finance```.
- Alternatywnie, pobierz instalator MSI offline lub biblioteki DLL w pliku ZIP z [pliki do pobrania](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# kod do OFX tworzenia plików żądań" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-request-files.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Inne opcje tworzenia" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-response/" name="OFX Plik odpowiedzi" description="Format 1.03 lub 2.2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/xbrl/" name="XBRL Plik" description="Rozszerzalny język raportowania biznesowego" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}