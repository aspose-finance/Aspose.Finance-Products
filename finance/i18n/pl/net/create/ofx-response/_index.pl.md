---
title: Utwórz plik odpowiedzi OFX za pomocą C#
description: Przykładowy kod do tworzenia pliku odpowiedzi OFX. Użyj kodu przykładowego API dla generowania plików odpowiedzi wsadowych OFX w aplikacjach opartych na .NET. 
url: /pl/net/create/ofx-response/
family: finance
platformtag: net
feature: create
informat: OFX Response
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Utwórz OFX plików odpowiedzi przez C#" h2="Tworzenie plików odpowiedzi OFX bez konieczności instalowania pakietu Microsoft Office lub innego oprogramowania." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Jak utworzyć pliki odpowiedzi OFX" %}}

Postępuj zgodnie z krokami w fragorze kodu lub popraw go zgodnie z potrzebami aplikacji po spełnieniu wymagań dotyczących tworzenia w aplikacji.

1. Stwórz [Klasa OfxResponseDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) Obiekt.1. Przypisywanie odpowiednich właściwości przy użyciu różnych klas podanych przez API jak [SignonResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse),  [StatementTransactionResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse), [Zestawienie transakcji](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction)1. Użyj plików xxVersion V2x lub V1x dla plików xml i sgml odpowiednio z [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) Jako parametr w metodzie Zapisz.1. Zadzwoń do [Zapisz metodę](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument/methods/save) Dostarczając plik docelowy i ofxVersion.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymóg stworzenia" %}}
Aby kontynuować tworzenie pliku odpowiedzi OFX, .NET Finance API to główne wymaganie, które należy uwzględnić w aplikacji do generowania raportów. 
- Zainstaluj go za pomocą wiersza poleceń jako ''nuget install Aspose.Finance'' lub za pomocą konsoli menedżera pakietów w Visual Studio z ''Zainstaluj pakiet Aspose.Finance''.
- Alternatywnie, pobierz instalator MSI offline lub biblioteki DLL w pliku ZIP z [Pliki do pobrania](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# kod dla OFX tworzenia plików odpowiedzi" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Inne opcje tworzenia" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="Plik wniosku OFX" description="Format 1.03 lub 2.2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/xbrl/" name="Plik XBRL" description="Rozszerzalny język raportowania biznesowego" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}