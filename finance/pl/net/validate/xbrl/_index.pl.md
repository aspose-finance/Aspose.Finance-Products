---
title: Zweryfikuj plik XBRL przez C#
description: Przykładowy kod do weryfikacji pliku XBRL. Użyj API przykładowego kodu, aby sprawdzić poprawność XBRL plików wsadowych w aplikacjach opartych na .NET. 
url: /pl/net/validate/xbrl/
family: finance
platformtag: net
feature: validate
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Sprawdź poprawność XBRL plików przez C#" h2="Sprawdzanie poprawności raportów finansowych w formacie XBRL bez konieczności instalowania pakietu Microsoft Office lub innego oprogramowania." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Jak zweryfikować XBRL pliki" %}}

Wykonaj czynności opisane we fragmencie kodu lub ulepsz go zgodnie z potrzebami aplikacji, aby sprawdzić poprawność dokumentów w języku XBRL w języku raportowania biznesowego. Upewnij się, że aplikacja zawiera wymagania dotyczące walidacji.

1. Załaduj plik XBRL za pomocą [Klasa XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Instancja.1. Aby sprawdzić poprawność wczytanego pliku, tak aby był zgodny z [XBRL specyfikacja](http://www.xbrl.org/specification/inlinexbrl-part1/rec-2013-11-18/inlinexbrl-part1-rec-2013-11-18.html)1. Aby sprawdzić ważność, użyj [Uprawomocnić()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) metoda [XbrlInstancja](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance) klasa.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymóg walidacji" %}}
Aby przejść do weryfikacji XBRL dokumentów, .NET Finance API jest głównym wymaganiem dołączenia do aplikacji. 
- Zainstaluj go za pomocą wiersza poleceń jako ```nuget install Aspose.Finance``` lub za pomocą konsoli Menedżera pakietów programu Visual Studio za pomocą ```Install-Package Aspose.Finance```.
- Alternatywnie, pobierz instalator MSI offline lub biblioteki DLL w pliku ZIP z [pliki do pobrania](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# kod do weryfikacji XBRL plików" offSpacer="" %}}

{{< gist "aspose-com-gists" "1272da1f804f8cef122600269db09fbb" "validate-xbrl-instance-file.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Inne opcje walidacji" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/validate/ixbrl/" name="XBRL" description="Wbudowany rozszerzalny język raportowania biznesowego" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}