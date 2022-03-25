---
title: Utwórz plik XBRL za pomocą C#
description: Przykładowy kod do tworzenia pliku XBRL. Użyj kodu przykładowego API dla generowania plików wsadowych XBRL w aplikacjach opartych na .NET. 
url: /pl/net/create/xbrl/
family: finance
platformtag: net
feature: create
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Utwórz XBRL plików przez C#" h2="XBRL tworzenia plików bez konieczności instalowania pakietu Microsoft Office lub innego oprogramowania." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Jak utworzyć XBRL plików" %}}

Postępuj zgodnie z krokami podanymi we fragorze kodu lub popraw go zgodnie z potrzebami aplikacji do generowania rozszerzalnego języka raportowania biznesowego XBRL plików. Upewnij się, że masz wymagania dotyczące tworzenia w swojej aplikacji.

1. Stwórz [Klasa XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Instancja.1. Aby utworzyć nowy dokument instancji XBRL [XbrlInstanceCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) I [XbrlInstancja](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance).1. Dodaj odniesienie do schematu przy użyciu [SchemaRefCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemarefcollection)1. W zależności od charakteru aplikacji dodaj kontekst, jednostkę, przedmiot, link do przypisu i więcej.1. Zadzwoń do [Zapisz metodę](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) Podając docelową ścieżkę pliku.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymóg stworzenia" %}}
Aby kontynuować generowanie XBRL dokumentów, .NET Finance API jest głównym wymaganiem uwzględnienia w aplikacji. 
- Zainstaluj go za pomocą wiersza poleceń jako ''nuget install Aspose.Finance'' lub za pomocą konsoli menedżera pakietów w Visual Studio z ''Zainstaluj pakiet Aspose.Finance''.
- Alternatywnie, pobierz instalator MSI offline lub biblioteki DLL w pliku ZIP z [Pliki do pobrania](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# kod dla XBRL tworzenia plików" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-schema-reference.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Inne opcje tworzenia" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="OFX Prośba" description="Format 1.03 lub 2.2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-response/" name="OFX odpowiedzi" description="Format 1.03 lub 2.2" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}