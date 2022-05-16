---
title: Wyświetl plik iXBRL przez C#
description: Przykładowy kod do przeglądania plików iXBRL. Użyj API przykładowego kodu, aby wyświetlić iXBRL pliki wsadowe w aplikacjach opartych na .NET. 
url: /pl/net/view/ixbrl/
family: finance
platformtag: net
feature: view
informat: iXBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Wyświetl iXBRL pliki przez C#" h2="Wyświetlanie raportów finansowych w formacie iXBRL bez konieczności instalowania pakietu Microsoft Office lub innego oprogramowania." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Jak wyświetlić iXBRL pliki" %}}

Wykonaj czynności opisane we fragmencie kodu lub ulepsz go zgodnie z potrzebami aplikacji, aby wyświetlić dokumenty w języku iXBRL, które można rozszerzyć w języku raportowania biznesowego. Upewnij się, że aplikacja zawiera wymagania dotyczące czytania.

1. Tworzyć [Klasa InlineXbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) Instancja.2. Przekaż nazwę prawidłowego pliku iXBRL jako parametr.
3. Aby uzyskać wewnętrzne szczegóły pliku, użyj odpowiednich klas, takich jak [InlineFakt](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinefact), [Kontekst](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/context), [Jednostka](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/unit) 
4. Pokaż te informacje

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Czytanie wymagania" %}}
Aby przejść do przeglądania iXBRL dokumentów, .NET Finance API jest głównym wymaganiem dołączenia do aplikacji. 
- Zainstaluj go za pomocą wiersza poleceń jako ```nuget install Aspose.Finance``` lub za pomocą konsoli Menedżera pakietów programu Visual Studio za pomocą ```Install-Package Aspose.Finance```.
- Alternatywnie, pobierz instalator MSI offline lub biblioteki DLL w pliku ZIP z [pliki do pobrania](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# kod do odczytu iXBRL plików" offSpacer="" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "read-ixbrl-file.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Inne opcje przeglądania" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/view/xbrl/" name="XBRL" description="Rozszerzalny język raportowania biznesowego" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}