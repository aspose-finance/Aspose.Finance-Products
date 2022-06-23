---
title: Utwórz plik odpowiedzi OFX przez Python
description: Przykładowy kod do tworzenia pliku odpowiedzi OFX. Użyj API przykładowego kodu do wsadowego OFX generowania plików odpowiedzi w aplikacjach opartych na Python. 
url: /pl/python-net/create/ofx-response/
family: finance
platformtag: python
feature: create
informat: OFX Response
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Utwórz OFX pliki odpowiedzi przez Python" h2="OFX tworzenie plików odpowiedzi bez konieczności instalowania pakietu Microsoft Office lub innego oprogramowania." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Jak utworzyć OFX pliki odpowiedzi" %}}

Wykonaj czynności opisane we fragmencie kodu lub ulepsz go zgodnie z potrzebami aplikacji po spełnieniu wymagań dotyczących tworzenia w aplikacji.

1. Utwórz obiekt klasy OfxResponseDocument.1. Przypisz odpowiednie właściwości za pomocą różnych klas dostarczanych przez API, takich jak SignonResponse, StatementTransactionResponse, StatementTransaction1. Użyj ofxVersion V2x lub V1x odpowiednio dla plików xml i sgml z OfxVersionEnum jako parametru w metodzie zapisu.1. Wywołaj metodę save, podając plik docelowy i ofxVersion.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymóg tworzenia" %}}
Aby kontynuować tworzenie pliku odpowiedzi OFX, upewnij się, że spełnione są następujące wymagania wstępne. 
- System operacyjny oparty na systemie Microsoft Windows lub Linux.- Python 3.5 lub nowsza.- Aspose.Finance dla Python, do którego odwołuje się Twój projekt.{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python kod do OFX tworzenia plików odpowiedzi" offSpacer="" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-response-files.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Inne opcje tworzenia" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/ofx-request/" name="OFX Poproś o plik" description="Format 1.03 lub 2.2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/xbrl/" name="XBRL Plik" description="Rozszerzalny język raportowania biznesowego" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}