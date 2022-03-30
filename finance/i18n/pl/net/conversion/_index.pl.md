---
title: Konwertuj raporty finansowe za pomocą .NET
url: /pl/net/conversion/
description:  C# kod do konwersji raportów finansowych w formatach plików XBRL, iXBRL i OFX za pośrednictwem biblioteki .NET.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konwertuj pliki raportów finansowych za pomocą C#" h2="Konwersja formatów raportów finansowych, w tym plików XBRL, iXBRL i OFX z formatu 1.03 do 2.2 w aplikacjach opartych na .NET." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) to bogata w funkcje, rozszerzalna i łatwa w użyciu API. Deweloperzy mogą łatwo weryfikować XBRL instancje, bazy linków i schematy taksonomii za pomocą [metoda validate()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) które muszą być zgodne z wymaganiami składniowymi nałożonymi w specyfikacji. Ponadto potrafią czytać formaty XBRL, iXBRL, a także tworzyć od podstaw XBRL instancje. Co więcej, mogą **konwertować format XBRL** na pliki iXBRL i Microsoft Excel XLSX. API obsługuje również tworzenie żądań/odpowiedzi w formacie otwartej wymiany finansowej (OFX) oraz konwertuje OFX żądanie/odpowiedź pliku z formatu 1.03 na 2.2.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Konwertuj OFX pliki odpowiedzi i żądań" %}}

API obsługuje tworzenie OFX plików żądań i odpowiedzi, udostępniając dwie klasy. [OfxRequestDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) do tworzenia i ładowania OFX plików żądań w formacie 1.03 i 2.2 oraz [OfxOdpowiedźDokument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) dla OFX plików odpowiedzi w formacie 1.03 i 2.2. Ponadto [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) Wyliczenie mające członków V1x, czyli wersję 1.x, format pliku sgml i wersję V2x 2.x, format pliku xml. Po wywołaniu metody Save klasy OfxRequestDocument lub klasy OfxResponseDocument programiści mogą łatwo przekonwertować plik sgml 1,03 na format 2,2 xml.


{{% blocks/products/pf/feature-page-code h3="C# Kod do konwersji OFX plików odpowiedzi" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-response-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Kod do konwersji OFX Żądania plików" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-request-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="XBRL Konwersja raportów finansowych" %}}

API obsługuje konwertowanie plików XBRL do formatu iXBRL i Microsoft® Excel XLSX. Proces konwersji jest prosty, najpierw załaduj plik przez [Klasa XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument). Użyj [Klasa SaveOptions](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions) dla [Zapisz format](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions/properties/saveformat), który ma być używany jako parametr w metodzie Save klasy XbrlDocument. Do zapisu w pliku iXBLR, [Zapisz format.IXBRL](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveformat) zostanie użyty, a do eksportu do formatu XLSX zostanie użyty SaveFormat.XLSX.

{{% blocks/products/pf/feature-page-code h3="C# Kod do eksportu XBRL do iXBRL" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-ixbrl.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Kod konwersji XBRL na XLSX" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-xlsx.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xbrl-to-ixbrl xbrl-to-xlsx" >}}