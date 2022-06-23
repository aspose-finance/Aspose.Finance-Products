---
title: Zweryfikuj plik XBRL przez Python
description: Przykładowy kod do weryfikacji pliku XBRL. Użyj API przykładowego kodu, aby sprawdzić poprawność XBRL plików wsadowych w aplikacjach opartych na Python. 
url: /pl/python-net/validate/xbrl/
family: finance
platformtag: python
feature: validate
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Sprawdź poprawność XBRL plików przez Python" h2="Sprawdzanie poprawności raportów finansowych w formacie XBRL bez konieczności instalowania pakietu Microsoft Office lub innego oprogramowania." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Jak zweryfikować XBRL pliki" %}}

Wykonaj czynności opisane we fragmencie kodu lub ulepsz go zgodnie z potrzebami aplikacji, aby sprawdzić poprawność dokumentów w języku XBRL w języku raportowania biznesowego. Upewnij się, że aplikacja zawiera wymagania dotyczące walidacji.

1. Załaduj plik XBRL przy użyciu instancji klasy XbrlDocument.2. Aby sprawdzić poprawność wczytanego pliku, tak aby był zgodny z [XBRL specyfikacja](http://www.xbrl.org/specification/inlinexbrl-part1/rec-2013-11-18/inlinexbrl-part1-rec-2013-11-18.html)
3. Aby sprawdzić poprawność, użyj metody walidacji klasy XbrlInstance.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymóg walidacji" %}}
Aby przejść do sprawdzania poprawności XBRL dokumentów, upewnij się, że masz następujące wymagania wstępne. 
- System operacyjny oparty na systemie Microsoft Windows lub Linux.- Python 3.5 lub nowsza.- Aspose.Finance dla Python, do którego odwołuje się Twój projekt.{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python kod do weryfikacji XBRL plików" offSpacer="" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "validate-xbrl-instance-file.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Inne opcje walidacji" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/validate/ixbrl/" name="XBRL" description="Wbudowany rozszerzalny język raportowania biznesowego" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}