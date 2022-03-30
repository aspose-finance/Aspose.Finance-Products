---
title: Utwórz plik XBRL przez C#
description: Przykładowy kod do tworzenia pliku XBRL. Użyj API przykładowego kodu do wsadowego generowania XBRL plików w aplikacjach opartych na .NET. 
url: /pl/net/create/xbrl/
family: finance
platformtag: net
feature: create
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Utwórz XBRL pliki przez C#" h2="Tworzenie XBRL plików bez konieczności instalowania pakietu Microsoft Office lub innego oprogramowania." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Jak tworzyć XBRL pliki" %}}

Wykonaj kroki opisane we fragmencie kodu lub ulepsz go zgodnie z potrzebami aplikacji, aby wygenerować rozszerzalne pliki języka raportowania biznesowego XBRL. Upewnij się, że aplikacja zawiera wymagania dotyczące tworzenia.

1. Tworzyć [Klasa XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Instancja.1. Aby utworzyć nowy XBRL dokument instancji [Kolekcja XbrlInstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) oraz [XbrlInstancja](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance).1. Dodaj odwołanie do schematu za pomocą [SchemaRefCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemarefcollection)1. W zależności od charakteru aplikacji dodaj kontekst, jednostkę, element, link do przypisu i nie tylko.1. Zadzwoń do [Zapisz metodę](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) podając ścieżkę do pliku docelowego.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymóg tworzenia" %}}
Aby kontynuować generowanie XBRL dokumentów, .NET Finance API jest głównym wymaganiem dołączenia do aplikacji. 
- Zainstaluj go za pomocą wiersza poleceń jako ```nuget install Aspose.Finance``` lub za pomocą konsoli Menedżera pakietów programu Visual Studio za pomocą ```Install-Package Aspose.Finance```.
- Alternatywnie, pobierz instalator MSI offline lub biblioteki DLL w pliku ZIP z [pliki do pobrania](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# kod do tworzenia XBRL plików" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-schema-reference.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Inne opcje tworzenia" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="OFX Prośba" description="Format 1.03 lub 2.2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-response/" name="OFX Odpowiedź" description="Format 1.03 lub 2.2" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}