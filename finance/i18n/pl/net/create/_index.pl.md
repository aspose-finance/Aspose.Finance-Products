---
title: Tworzenie raportów finansowych za pomocą .NET
url: /pl/net/create/
description:  Kod C# do tworzenia raportów finansowych w XBRL i OFX plików żądań lub odpowiedzi za pośrednictwem biblioteki .NET.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Tworzenie plików sprawozdawczości finansowej poprzez C#" h2="Tworzenie formatów raportów finansowych, w tym XBRL i OFX plików z żądaniem lub odpowiedzią w formacie 1.03 lub 2.2 w aplikacjach opartych na .NET." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) To bogate w funkcje, rozszerzalne i łatwe w użyciu tworzenie i przetwarzanie raportów finansowych API. Programiści mogą łatwo tworzyć XBRL instancję od podstaw, a także dodawać odniesienie do schematu, kontekst, jednostkę, element, link do przypisu, odniesienie do roli i 
Odniesienie do roli łuku. API zapewnia odpowiednią klasę dla każdej funkcji, na przykład dla kontekstu, programiści mogą z nich korzystać [Okres kontekstowy](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextperiod), [ContextEntity](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextentity) I [Kontekst](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/context). 
Ponadto API obsługuje również tworzenie żądań/odpowiedzi w formacie otwartej wymiany finansowej (OFX) w formacie 1.03 lub 2.2.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Utwórz plik XBRL, dodając element" %}}

Aby utworzyć plik XBRL i dodać element do dokumentu, należy utworzyć proces [Klasa XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Instancja. Przygotuj odpowiednie ustawienia dla produktu, używając odpowiednich klas API, takich jak [Klasa SchemaRef](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemaref), Odpowiednie klasy kontekstu, jak wspomniano powyżej i [Klasa koncepcyjna](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/concept). Wreszcie zdefiniuj i intializuj [Klasa przedmiotu](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/item) Właściwości, a także zadzwoń do [Zapisz metodę](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) Do [Utwórz XBRL](https://products.aspose.com/finance/net/create/xbrl/) Plik na dysk.

{{% blocks/products/pf/feature-page-code h3="C# Kod do utworzenia pliku XBRL przez dodanie elementu" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-item.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Tworzenie plików OFX Request and Response" %}}


Do generowania OFX plików, API zapewnia [OfxRequestDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) I [OfxResponseDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) Klasy i programiści mogą łatwo [Stworzyć prośbę o OFX](https://products.aspose.com/finance/net/create/ofx-request/) I pliki odpowiedzi w formatach 1.03 i 2.2. W celu zainicjowania właściwości OfxRequestDocument API zapewnia również inne klasy, takie jak [SignonRequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonrequest), [Instytucja finansowa](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/financialinstitution) I [StatementTransactionRequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionrequest) Zajęcia. Podobnie, aby intializować właściwości OfxResponseDocument, API zapewnia klasy wspierające, takie jak [SignonResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse),  [StatementTransactionResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse) I [Zestawienie transakcji](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction). Poniżej znajdują się fragmenty kodu dla obu przypadków z użyciem odpowiednich odpowiednich klas.

{{% blocks/products/pf/feature-page-code h3="C# kod do wygenerowania OFX dokumentów z żądaniem" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# kod do wygenerowania OFX dokumentów odpowiedzi" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}