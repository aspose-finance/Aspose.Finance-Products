---
title: Twórz raporty finansowe za pośrednictwem Python
url: /pl/python-net/create/
description:  Python kod do tworzenia raportów finansowych w XBRL i OFX pliki żądań lub odpowiedzi za pośrednictwem biblioteki Python.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Utwórz pliki raportów finansowych za pomocą Python" h2="Tworzenie formatów raportów finansowych, w tym plik żądań lub odpowiedzi XBRL i OFX w formacie 1.03 lub 2.2 w aplikacjach opartych na Python." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance dla Python przez .NET](https://products.aspose.com/finance/python-net/) to bogate w funkcje, rozszerzalne i łatwe w użyciu narzędzie do tworzenia i przetwarzania raportów finansowych API. Deweloperzy mogą łatwo utworzyć XBRL instancję od podstaw, a także dodać odniesienie do schematu, kontekst, jednostkę, element, link do przypisu, odniesienie do roli i 
odniesienie do roli łuku. API zapewnia odpowiednią klasę dla każdej funkcji, na przykład dla kontekstu, programiści mogą używać ContextPeriod, ContextEntity i Context. 
Ponadto API obsługuje również tworzenie żądań/odpowiedzi w formacie otwartej wymiany finansowej (OFX) w formacie 1.03 lub 2.2.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Utwórz plik XBRL, dodając element" %}}

Proces tworzenia pliku XBRL i dodawania elementu do dokumentu polega na utworzeniu instancji klasy XbrlDocument. Przygotuj odpowiednie ustawienia dla elementu, używając odpowiednich klas API, takich jak klasa SchemaRef, odpowiednie klasy kontekstowe, jak wspomniano powyżej i klasa Concept. Na koniec zdefiniuj i zainicjuj właściwości klasy Item, a także wywołaj metodę save, aby utworzyć plik XBRL na dysku.

{{% blocks/products/pf/feature-page-code h3="Python Kod do utworzenia XBRL pliku przez dodanie elementu" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-xbrl-file-and-add-item.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Utwórz OFXpliki żądań i odpowiedzi" %}}


Aby wygenerować OFX plików, API udostępnia klasy OfxRequestDocument i OfxResponseDocument, a programiści mogą łatwo [utwórz OFX wniosek](https://products.aspose.com/finance/python-net/create/ofx-request/) oraz Pliki odpowiedzi w formatach 1.03 i 2.2. Do inicjowania właściwości OfxRequestDocument API udostępnia również inne klasy, takie jak SignonRequest, FinancialInstitution i StatementTransactionRequest. Podobnie w przypadku inicjowania właściwości OfxResponseDocument API udostępnia klasy pomocnicze, takie jak SignonResponse, StatementTransactionResponse i StatementTransaction. Poniżej znajdują się fragmenty kodu dla obu przypadków z wykorzystaniem odpowiednich odpowiednich klas.

{{% blocks/products/pf/feature-page-code h3="Python Kod do wygenerowania OFX Poproś o dokumenty" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-response-files.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Python Kod do generowania OFX dokumentów odpowiedzi" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-response-files.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
{{< /blocks/products/pf/feature-page-wrap >}}