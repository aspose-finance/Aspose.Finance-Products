---
title: Twórz raporty finansowe za pośrednictwem .NET
url: /pl/net/create/
description:  C# kod do tworzenia raportów finansowych w XBRL i OFX pliki żądań lub odpowiedzi za pośrednictwem biblioteki .NET.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Utwórz pliki raportów finansowych za pomocą C#" h2="Tworzenie formatów raportów finansowych, w tym plik żądań lub odpowiedzi XBRL i OFX w formacie 1.03 lub 2.2 w aplikacjach opartych na .NET." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) to bogate w funkcje, rozszerzalne i łatwe w użyciu narzędzie do tworzenia i przetwarzania raportów finansowych API. Deweloperzy mogą łatwo utworzyć XBRL instancję od podstaw, a także dodać odniesienie do schematu, kontekst, jednostkę, element, link do przypisu, odniesienie do roli i 
odniesienie do roli łuku. API zapewnia odpowiednią klasę dla każdej funkcji, na przykład kontekst, z którego mogą korzystać programiści [Okres kontekstu](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextperiod), [KontekstEntity](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextentity) oraz [Kontekst](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/context). 
Ponadto API obsługuje również tworzenie żądań/odpowiedzi w formacie otwartej wymiany finansowej (OFX) w formacie 1.03 lub 2.2.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Utwórz plik XBRL, dodając element" %}}

Proces tworzenia pliku XBRL i dodawania pozycji do dokumentu polega na stworzeniu [Klasa XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) instancja. Przygotuj odpowiednie ustawienia dla elementu, używając odpowiednich API klas, takich jak [Klasa schematu](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemaref)odpowiednie klasy kontekstowe, jak wspomniano powyżej i [Klasa koncepcyjna](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/concept). Wreszcie zdefiniuj i zainicjuj [Klasa przedmiotu](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/item) właściwości, a także wywołaj [Zapisz metodę](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) do [utwórz XBRL](https://products.aspose.com/finance/net/create/xbrl/) plik na dysk.

{{% blocks/products/pf/feature-page-code h3="C# Kod do utworzenia XBRL pliku przez dodanie elementu" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-item.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Utwórz OFXpliki żądań i odpowiedzi" %}}


Do generowania OFX plików, API zapewnia [OfxRequestDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) oraz [OfxOdpowiedźDokument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) zajęcia i programiści mogą łatwo [utwórz OFX wniosek](https://products.aspose.com/finance/net/create/ofx-request/) oraz Pliki odpowiedzi w formatach 1.03 i 2.2. Do inicjowania właściwości OfxRequestDocument API udostępnia również inne klasy, takie jak [Żądanie logowania](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonrequest), [Instytucja finansowa](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/financialinstitution) oraz [WyciągZlecenie Transakcji](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionrequest) zajęcia. Podobnie, do inicjowania właściwości OfxResponseDocument, API udostępnia klasy pomocnicze, takie jak [Zaloguj sięOdpowiedź](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse),  [WyciągTransakcjaOdpowiedź](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse) oraz [WyciągTransakcja](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction). Poniżej znajdują się fragmenty kodu dla obu przypadków z wykorzystaniem odpowiednich odpowiednich klas.

{{% blocks/products/pf/feature-page-code h3="C# Kod do wygenerowania OFX Poproś o dokumenty" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Kod do generowania OFX dokumentów odpowiedzi" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
{{< /blocks/products/pf/feature-page-wrap >}}