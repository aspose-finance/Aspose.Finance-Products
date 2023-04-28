---
title: Konwertuj raporty finansowe za pomocą Python
url: /pl/python-net/conversion/
description:  Python kod do konwersji raportów finansowych w formatach plików XBRL, iXBRL(inline xbrl) i OFX za pośrednictwem biblioteki Python.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konwertuj pliki raportów finansowych za pomocą Python" h2="Konwersja formatów raportów finansowych, w tym plików XBRL, iXBRL i OFX z formatu 1.03 do 2.2 w aplikacjach opartych na Python." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance dla Python przez .NET](https://products.aspose.com/finance/python-net/) to bogata w funkcje, rozszerzalna i łatwa w użyciu API. Deweloperzy mogą łatwo sprawdzać XBRL instancje, bazy łączy i schematy taksonomii za pomocą metody validate(), która musi być zgodna z wymaganiami składniowymi nałożonymi w specyfikacji. Ponadto potrafią czytać formaty XBRL, iXBRL, a także tworzyć XBRL instancje od podstaw. Ponadto mogą **konwertować format XBRL** do plików iXBRL i Microsoft Excel XLSX. API obsługuje również tworzenie żądań/odpowiedzi w formacie otwartej wymiany finansowej (OFX) i konwertuje OFX żądanie/odpowiedź pliku z formatu 1.03 do formatu 2.2.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Konwertuj OFX pliki odpowiedzi i żądań" %}}

API obsługuje tworzenie OFX plików żądań i odpowiedzi, udostępniając dwie klasy. OfxRequestDocument do tworzenia i ładowania OFX plików żądań w formacie 1.03 i 2.2 oraz OfxResponseDocument do OFX plików odpowiedzi w formacie 1.03 i 2.2. Ponadto Wyliczenie OfxVersionEnum mające elementy członkowskie V1x, czyli wersję 1.x, format pliku sgml i wersję V2x 2.x, format pliku xml. Po wywołaniu metody save klasy OfxRequestDocument lub klasy OfxResponseDocument programiści mogą w łatwy sposób dokonać konwersji z pliku sgml 1.03 na format 2.2 xml.


{{% blocks/products/pf/feature-page-code h3="C# Kod do konwersji OFX plików odpowiedzi" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-ofx-response-from-1.03-to-2.2.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Kod do konwersji OFX Żądania plików" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-ofx-request-from-1.03-to-2.2.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="XBRL Konwersja raportów finansowych" %}}

API obsługuje konwertowanie plików XBRL do formatu iXBRL i Microsoft® Excel XLSX. Proces konwersji jest prosty, najpierw załaduj plik za pomocą klasy XbrlDocument. Użyj klasy SaveOptions dla SaveFormat, która ma być użyta jako parametr w metodzie zapisu klasy XbrlDocument. Do zapisu w pliku iXBLR zostanie użyty SaveFormat.IXBRL, a do eksportu do formatu XLSX zostanie użyty SaveFormat.XLSX.

{{% blocks/products/pf/feature-page-code h3="Python Kod do eksportu XBRL do iXBRL" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-xbrl-to-ixbrl.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Python Kod konwersji XBRL na XLSX" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-xbrl-to-xlsx.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xbrl-to-ixbrl xbrl-to-xlsx" >}}
{{< /blocks/products/pf/feature-page-wrap >}}