---
title: Utwórz plik XBRL przez Python
description: Przykładowy kod do tworzenia pliku XBRL. Użyj API przykładowego kodu do wsadowego generowania XBRL plików w aplikacjach opartych na Python. 
url: /pl/python-net/create/xbrl/
family: finance
platformtag: python
feature: create
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Utwórz XBRL pliki przez Python" h2="Tworzenie XBRL plików bez konieczności instalowania pakietu Microsoft Office lub innego oprogramowania." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Jak tworzyć XBRL pliki" %}}

Wykonaj kroki opisane we fragmencie kodu lub ulepsz go zgodnie z potrzebami aplikacji, aby wygenerować rozszerzalne pliki języka raportowania biznesowego XBRL. Upewnij się, że aplikacja zawiera wymagania dotyczące tworzenia.

1. Utwórz Instancję klasy XbrlDocument.1. Aby utworzyć nowy XBRL dokument instancji XbrlInstanceCollection i XbrlInstance.1. Dodaj odwołanie do schematu za pomocą SchemaRefCollection1. W zależności od charakteru aplikacji dodaj kontekst, jednostkę, element, link do przypisu i nie tylko.1. Wywołaj metodę save, podając ścieżkę do pliku docelowego.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymóg tworzenia" %}}
Aby kontynuować generowanie XBRL dokumentów, upewnij się, że masz następujące wymagania wstępne. 
- System operacyjny oparty na systemie Microsoft Windows lub Linux.- Python 3.5 lub nowsza.- Aspose.Finance dla Python, do którego odwołuje się Twój projekt.{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python kod do tworzenia XBRL plików" offSpacer="" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-xbrl-file-and-add-schema-reference.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Inne opcje tworzenia" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/ofx-request/" name="OFX Prośba" description="Format 1.03 lub 2.2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/ofx-response/" name="OFX Odpowiedź" description="Format 1.03 lub 2.2" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}