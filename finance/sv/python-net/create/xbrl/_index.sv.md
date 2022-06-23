---
title: Skapa XBRL-fil via Python
description: Exempelkod för att skapa XBRL-fil. Använd API exempelkod för generering av batch-XBRL-filer inom Python-baserade applikationer. 
url: /sv/python-net/create/xbrl/
family: finance
platformtag: python
feature: create
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Skapa XBRL filer via Python" h2="Skapa XBRL filer utan att behöva installera Microsoft Office eller någon annan programvara." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Hur man skapar XBRL-filer" %}}

Följ stegen i kodavsnittet eller förbättra det utifrån dina programbehov för att skapa utökningsbara filer för affärsrapporteringsspråket XBRL. Var säker på att ha skapande krav i din ansökan.

1. Skapa XbrlDocument class Instance.1. För att skapa ett nytt XBRL-instansdokument XbrlInstanceCollection och XbrlInstance.1. Lägg till schemareferens med SchemaRefCollection1. Lägg till kontext, enhet, artikel, fotnotslänk och mer beroende på applikationens karaktär.1. Anropa sparmetoden genom att ange målfilens sökväg.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Skapande krav" %}}
För att fortsätta för generering av XBRL dokument, se till att du har följande förutsättningar. 
- Microsoft Windows eller Linux-baserat operativsystem.- Python 3.5 eller senare.- Aspose.Finance för Python som refereras till i ditt projekt.{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python kod för att skapa XBRL filer" offSpacer="" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-xbrl-file-and-add-schema-reference.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Andra skapande alternativ" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/ofx-request/" name="OFX Begäran" description="1.03 eller 2.2 format" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/ofx-response/" name="OFX Svar" description="1.03 eller 2.2 format" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}