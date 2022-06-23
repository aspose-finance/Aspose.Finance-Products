---
title: Utwórz OFX Zażądaj pliku przez Python
description: Przykładowy kod do tworzenia pliku żądania OFX. Użyj API przykładowego kodu do wsadowego OFX generowania plików żądań w aplikacjach opartych na Python. 
url: /pl/python-net/create/ofx-request/
family: finance
platformtag: python
feature: create
informat: OFX Request
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Utwórz OFX pliki żądań przez Python" h2="OFX żądaj tworzenia plików bez konieczności instalowania pakietu Microsoft Office lub innego oprogramowania." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Jak utworzyć OFX pliki żądań" %}}

Po spełnieniu OFXwymagań dotyczących tworzenia plików żądania w swojej aplikacji, postępuj zgodnie z instrukcjami we fragmencie kodu lub ulepsz go zgodnie z wymaganiami.

1. Utwórz obiekt klasy OfxRequestDocument.2. Przypisz odpowiednie właściwości, korzystając z różnych klas dostarczanych przez API, takich jak SignonRequest, FinancialInstitution], StatementTransactionRequest
3. Użyj ofxVersion V2x lub V1x odpowiednio dla plików xml i sgml z OfxVersionEnum jako parametru w metodzie Save.
4. Wywołaj metodę save, podając plik docelowy i ofxVersion.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymóg tworzenia" %}}
Aby przejść do OFX tworzenia pliku żądania, upewnij się, że spełnione są następujące wymagania wstępne. 
- System operacyjny oparty na systemie Microsoft Windows lub Linux.- Python 3.5 lub nowsza.- Aspose.Finance dla Python, do którego odwołuje się Twój projekt.{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python kod do OFX tworzenia plików żądań" offSpacer="" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-request-files.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Inne opcje tworzenia" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/ofx-response/" name="OFX Plik odpowiedzi" description="Format 1.03 lub 2.2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/xbrl/" name="XBRL Plik" description="Rozszerzalny język raportowania biznesowego" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}