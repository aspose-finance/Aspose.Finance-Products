---
title: Potwierdź raporty finansowe za pośrednictwem .NET
url: /pl/net/validate/
description:  Kod C# do weryfikacji raportów finansowych w XBRL i iXBRL plikach za pośrednictwem biblioteki .NET.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Potwierdź pliki sprawozdawczości finansowej za pośrednictwem C#" h2="Sprawdzanie formatu raportów finansowych, w tym XBRL i iXBRL w aplikacjach opartych na .NET." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) To bogate w funkcje, rozszerzalne i łatwe w użyciu przetwarzanie raportów finansowych API. Programiści mogą łatwo ładować, sprawdzać, przeglądać lub tworzyć formaty XBRL i iXBRL dla rozwiązań finansowych i biznesowych. API zapewnia [XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Klasa i  [InlineXbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) Klasy do ładowania plików XBRL i iXBRL.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Zweryfikuj dokument XBRL" %}}

Walidacja pliku XBRL jest potrzebna w wielu przypadkach, na przykład w celu sprawdzenia, czy dane mają odpowiednią strukturę i format. Aby zweryfikować dokumenty XBLR, najpierw użyj klasy XbrlDocument, aby załadować plik XBRL. Aby skorzystać z [Walidacja ()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) Metoda [XbrlInstancja](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance) Klasa, najpierw intializuj [XbrlInstanceCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) Z obiektem XbrlDocument XbrlInstances. Iteruj przez każdy [XbrlInstance. Błędy walidacjowe](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/properties/validationerrors) Aby uzyskać właściwy kod błędu i działać odpowiednio, drukując niestandardowe komunikaty o błędach na konsoli lub pisząc w pliku.

{{% blocks/products/pf/feature-page-code h3="C# kod do weryfikacji pliku XBRL" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-xbrl-file.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Zweryfikuj dokument iXBRL" %}}

W przypadku walidacji iXLRB załaduj go przez [InlineXbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) Klasy i użyj jej metody Validate(). W [ValidationErrorCode](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.validator/validationerrorcode) Wyliczenie, kody błędów walidacji są zdefiniowane dla każdej reguły walidacji. Niewiele kodów to ContextPeriodNoStartTime, ContextPeriodNoEndTime, ContextPeriodStartAfterEnd, ContextInstantNoTime, ContextScenterNoTime, ContextInstantNoSubstitutionGroup itp. Programiści mogą debugować i wyświetlać kody jako użytkownicy końcowi lub mogą pokazywać kierunek rozwiązania problemu.

{{% blocks/products/pf/feature-page-code h3="C# kod do weryfikacji iXBRL dokumentu" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-ixbrl-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Validate" >}}