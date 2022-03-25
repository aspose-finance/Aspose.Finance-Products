---
title: Sprawdź XBRL pliku za pomocą C#
description: Przykładowy kod dla XBRL walidacji pliku. Użyj API przykładowego kodu, aby zweryfikować pliki wsadowe XBRL w aplikacjach opartych na .NET. 
url: /pl/net/validate/xbrl/
family: finance
platformtag: net
feature: validate
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Potwierdź XBRL plików przez C#" h2="Weryfikowanie raportów finansowych w formacie XBRL bez konieczności instalowania pakietu Microsoft Office lub innego oprogramowania." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Jak zweryfikować XBRL plików" %}}

Postępuj zgodnie z krokami w fragorze kodu lub popraw go zgodnie z potrzebami aplikacji, aby zweryfikować rozszerzalny język raportowania biznesowego XBRL dokumentów. Upewnij się, że masz wymagania dotyczące walidacji w swojej aplikacji.

1. Załaduj plik XBRL za pomocą [Klasa XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Instancja.1. Aby sprawdzić ważność załadowanego pliku, tak aby musiał być zgodny z [Specyfikacja XBRL](http://www.xbrl.org/specification/inlinexbrl-part1/rec-2013-11-18/inlinexbrl-part1-rec-2013-11-18.html)1. Aby sprawdzić walidatity, użyj [Weryfikacja ()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) Metoda [XbrlInstancja](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance) Klasy.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymóg walidacji" %}}
Aby przystąpić do walidacji XBRL dokumentów, .NET Finance API to główne wymaganie, które należy uwzględnić w aplikacji. 
- Zainstaluj go za pomocą wiersza poleceń jako ''nuget install Aspose.Finance'' lub za pomocą konsoli menedżera pakietów w Visual Studio z ''Zainstaluj pakiet Aspose.Finance''.
- Alternatywnie, pobierz instalator MSI offline lub biblioteki DLL w pliku ZIP z [Pliki do pobrania](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# kodu do weryfikacji XBRL plików" offSpacer="" %}}

{{< gist "aspose-com-gists" "1272da1f804f8cef122600269db09fbb" "validate-xbrl-instance-file.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Inne opcje walidacji" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/validate/ixbrl/" name="XBRL" description="Inline rozszerzalny język raportowania biznesowego" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}