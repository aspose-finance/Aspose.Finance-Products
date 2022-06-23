---
title: Skapa OFX svarsfil via Python
description: Exempelkod för att skapa OFX svarsfil. Använd API exempelkod för batchgenerering av OFX svarsfiler inom Python-baserade applikationer. 
url: /sv/python-net/create/ofx-response/
family: finance
platformtag: python
feature: create
informat: OFX Response
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Skapa OFX svarsfiler via Python" h2="Skapa OFX svarsfiler utan att behöva installera Microsoft Office eller någon annan programvara." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Så här skapar du OFX svarsfiler" %}}

Följ stegen i kodavsnittet eller förbättra det efter dina applikationsbehov efter att ha skapat kraven i din applikation.

1. Skapa OfxResponseDocument-klassobjekt.1. Tilldela relevanta egenskaper med olika klasser som tillhandahålls av API som SignonResponse, StatementTransactionResponse, StatementTransaction1. Använd ofxVersion V2x eller V1x för xml- respektive sgml-filer från OfxVersionEnum som parameter i sparmetoden.1. Anropa sparmetoden genom att tillhandahålla målfilen och ofxVersion.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Skapande krav" %}}
För att fortsätta för att skapa OFX svarsfil, se till att du har följande förutsättningar. 
- Microsoft Windows eller Linux-baserat operativsystem.- Python 3.5 eller senare.- Aspose.Finance för Python som refereras till i ditt projekt.{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python-kod för att skapa OFX svarsfiler" offSpacer="" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-response-files.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Andra skapande alternativ" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/ofx-request/" name="OFX Begär fil" description="1.03 eller 2.2 format" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/xbrl/" name="XBRL Fil" description="Extensible Business Reporting Language" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}