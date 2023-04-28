---
title: Weryfikuj raporty finansowe za pośrednictwem Python
url: /pl/python-net/validate/
description:  Python kod do weryfikacji raportów finansowych w plikach XBRL i iXBRL za pośrednictwem biblioteki Python.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Sprawdź poprawność plików raportów finansowych za pośrednictwem Python" h2="Sprawdzanie formatów raportów finansowych, w tym XBRL i iXBRL w aplikacjach opartych na Python." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance dla Python przez .NET](https://products.aspose.com/finance/python-net/) to bogate w funkcje, rozszerzalne i łatwe w użyciu narzędzie do przetwarzania raportów finansowych API. Programiści mogą łatwo ładować, sprawdzać, wyświetlać lub tworzyć formaty XBRL i iXBRL dla rozwiązań finansowych i biznesowych. API udostępnia klasę XbrlDocument i klasę InlineXbrlDocument do ładowania plików XBRL i iXBRL.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Sprawdź poprawność XBRL dokumentu" %}}

Walidacja pliku XBRL jest wymagana w wielu przypadkach, takich jak sprawdzenie, czy dane mają odpowiednią strukturę i format. Aby sprawdzić poprawność dokumentów XBLR, najpierw użyj klasy XbrlDocument, aby załadować plik XBRL. Aby użyć metody walidacji klasy XbrlInstance, najpierw zainicjuj XbrlInstanceCollection za pomocą obiektu XbrlDocument XbrlInstances. Wykonaj iterację przez każdy błąd XbrlInstance.ValidationErrors, aby uzyskać właściwy kod błędu i postępuj zgodnie z nim, drukując dostosowane komunikaty o błędach na konsoli lub zapisując w pliku.

{{% blocks/products/pf/feature-page-code h3="Python Kod do weryfikacji XBRL pliku" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "validate-xbrl-instance-file.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Sprawdź poprawność iXBRL dokumentu" %}}

przypadku walidacji iXLRB załaduj ją za pomocą klasy InlineXbrlDocument i użyj jej metody validate(). W wyliczeniu ValidationErrorCode kody błędów walidacji są zdefiniowane dla każdej reguły walidacji. Niewiele kodów to ContextPeriodNoStartTime, ContextPeriodNoEndTime, ContextPeriodStartAfterEnd, ContextInstantNoTime, ContextScenarioXbrlNamespace, ContextScenarioXbrlSubstitutionGroup itp. Deweloperzy mogą debugować i wyświetlać kody jako użytkownicy końcowi lub mogą wskazać kierunek rozwiązania problemu.

{{% blocks/products/pf/feature-page-code h3="Python Kod do weryfikacji iXBRL dokumentu" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "validate-ixbrl-file.py" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Validate" >}}
{{< /blocks/products/pf/feature-page-wrap >}}