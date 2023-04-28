---
title: Weryfikuj raporty finansowe za pośrednictwem .NET
url: /pl/net/validate/
description:  C# kod do weryfikacji raportów finansowych w plikach XBRL i iXBRL za pośrednictwem biblioteki .NET.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Sprawdź poprawność plików raportów finansowych za pośrednictwem C#" h2="Sprawdzanie formatów raportów finansowych, w tym XBRL i iXBRL w aplikacjach opartych na .NET." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) to bogate w funkcje, rozszerzalne i łatwe w użyciu narzędzie do przetwarzania raportów finansowych API. Programiści mogą łatwo ładować, sprawdzać, wyświetlać lub tworzyć formaty XBRL i iXBRL dla rozwiązań finansowych i biznesowych. API zapewnia [Dokument Xbrl](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) klasa i  [Wbudowany dokument Xbrl](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) klasa do ładowania plików XBRL i iXBRL.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Sprawdź poprawność XBRL dokumentu" %}}

Walidacja pliku XBRL jest wymagana w wielu przypadkach, takich jak sprawdzenie, czy dane mają odpowiednią strukturę i format. Aby sprawdzić poprawność dokumentów XBLR, najpierw użyj klasy XbrlDocument, aby załadować plik XBRL. Aby użyć [uprawomocnić()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) metoda [XbrlInstancja](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance) klasy, najpierw zainicjuj [Kolekcja XbrlInstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) z obiektem XbrlDocument XbrlInstances. Iteruj przez każdą z nich [XbrlInstance.ValidationErrors](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/properties/validationerrors) aby uzyskać właściwy kod błędu i podjąć odpowiednie działania, drukując dostosowane komunikaty o błędach na konsoli lub zapisując w pliku.

{{% blocks/products/pf/feature-page-code h3="C# Kod do weryfikacji XBRL pliku" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-xbrl-file.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Sprawdź poprawność iXBRL dokumentu" %}}

Aby uzyskać walidację iXLRB, załaduj go przez [Wbudowany dokument Xbrl](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) klasy i użyj jej metody Validate(). W [Kod błędu weryfikacji](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.validator/validationerrorcode) wyliczenia, kody błędów walidacji są zdefiniowane dla każdej reguły walidacji. Niewiele kodów to ContextPeriodNoStartTime, ContextPeriodNoEndTime, ContextPeriodStartAfterEnd, ContextInstantNoTime, ContextScenarioXbrlNamespace, ContextScenarioXbrlSubstitutionGroup itp. Deweloperzy mogą debugować i wyświetlać kody jako użytkownicy końcowi lub mogą wskazać kierunek rozwiązania problemu.

{{% blocks/products/pf/feature-page-code h3="C# Kod do weryfikacji iXBRL dokumentu" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-ixbrl-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Validate" >}}
{{< /blocks/products/pf/feature-page-wrap >}}