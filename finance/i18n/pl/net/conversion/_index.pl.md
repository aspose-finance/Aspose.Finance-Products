---
title: Konwertuj raporty finansowe za pośrednictwem .NET
url: /pl/net/conversion/
description:  C# kodu do konwersji raportów finansowych w XBRL, iXBRL i OFX fomatów plików za pośrednictwem biblioteki .NET.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konwertuj pliki raportów finansowych za pośrednictwem C#" h2="Konwersja formatów raportów finansowych, w tym XBRL, iXBRL i OFX plików z formatu 1.03 do 2.2 w aplikacjach opartych na .NET." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) To bogata w funkcje, rozszerzalna i łatwa w użyciu API. Programiści mogą łatwo zweryfikować XBRL instancji, baz linków i schematów taksonomii za pomocą [Metoda walidacji ()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) Które muszą być zgodne z wymogami składni nałożonymi w specyfikacji. Ponadto potrafią odczytać XBRL, iXBRL formatów, a także utworzyć od podstaw XBRL instancję. Ponadto mogą one ** konwertować XBRL format ** na iXBRL i pliki Microsoft Excel XLSX. API obsługuje również tworzenie żądań/odpowiedzi w formacie otwartej wymiany finansowej (OFX) i konwertuje OFX żądanie/odpowiedź pliku z formatu 1.03 na 2.2.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Konwertuj pliki odpowiedzi i odpowiedzi OFX" %}}

API obsługuje tworzenie OFX plików żądań i odpowiedzi poprzez udostępnienie dwóch klas. [OfxRequestDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) Do tworzenia i ładowania plików OFX żądań w formacie 1.03 i 2.2 oraz [OfxResponseDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) Dla OFX plików odpowiedzi w formacie 1.03 i 2.2. Ponadto, [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) Wyliczenie posiadające członków V1x, czyli wersja 1.x, format pliku sgml i wersja V2x 2.x, format pliku xml. Po wywołaniu metody zapisywania klasy OfxRequestDocument lub klasy OfxResponseDocument programiści mogą łatwo konwertować z pliku 1.03 sgml do formatu 2.2 xml.


{{% blocks/products/pf/feature-page-code h3="C# kodu, aby przekonwertować OFX plików odpowiedzi" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-response-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# kod do konwersji OFX plików wniosków" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-request-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="XBRL Konwersja raportów finansowych" %}}

API obsługuje konwersję XBRL plików na iXBRL i Microsoft®XLSX w formacie Excel. Proces konwersji jest prosty, najpierw załaduj plik za pośrednictwem [Klasa XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument). Użyj [Klasa SaveOptions](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions) Dla [SaveFormat](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions/properties/saveformat), Do użycia jako parametr w Save method of XbrlDocument Class. Do zapisywania w pliku iXBLR, [SaveFormat.IXBRL](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveformat) Będzie używany, a do eksportowania do formatu XLSX zostanie użyty SaveFormat.XLSX.

{{% blocks/products/pf/feature-page-code h3="C# Kod do eksportu XBRL do iXBRL" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-ixbrl.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Kod dla XBRL do konwersji XLSX" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-xlsx.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xbrl-to-ixbrl xbrl-to-xlsx" >}}