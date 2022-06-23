---
title: Skapa OFX Begäran fil via Python
description: Exempelkod för att skapa OFX-begäran. Använd API exempelkod för generering av batch-OFX begärandefiler inom Python-baserade applikationer. 
url: /sv/python-net/create/ofx-request/
family: finance
platformtag: python
feature: create
informat: OFX Request
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Skapa OFX Begäran filer via Python" h2="OFX begär att skapa filer utan att behöva installera Microsoft Office eller någon annan programvara." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Så här skapar du OFX förfrågningsfiler" %}}

Efter att ha uppfyllt kraven för att skapa OFX Begär filer i din applikation, följ stegen i kodavsnittet eller förbättra det enligt ditt krav.

1. Skapa OfxRequestDocument-klassobjekt.2. Tilldela relevanta egenskaper med hjälp av olika klasser som tillhandahålls av API som SignonRequest, FinancialInstitution], StatementTransactionRequest
3. Använd ofxVersion V2x eller V1x för xml- respektive sgml-filer från OfxVersionEnum som parameter i metoden Spara.
4. Anropa sparmetoden genom att tillhandahålla målfilen och ofxVersion.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Skapande krav" %}}
För att fortsätta för OFX Begär filskapande, se till att du har följande förutsättningar. 
- Microsoft Windows eller Linux-baserat operativsystem.- Python 3.5 eller senare.- Aspose.Finance för Python som refereras till i ditt projekt.{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python kod för att skapa OFX begärande filer" offSpacer="" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-request-files.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Andra skapande alternativ" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/ofx-response/" name="OFX Svarsfil" description="1.03 eller 2.2 format" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/xbrl/" name="XBRL Fil" description="Extensible Business Reporting Language" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}