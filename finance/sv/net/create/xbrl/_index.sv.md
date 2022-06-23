---
title: Skapa XBRL-fil via C#
description: Exempelkod för att skapa XBRL-fil. Använd API exempelkod för generering av batch-XBRL-filer inom .NET-baserade applikationer. 
url: /sv/net/create/xbrl/
family: finance
platformtag: net
feature: create
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Skapa XBRL filer via C#" h2="Skapa XBRL filer utan att behöva installera Microsoft Office eller någon annan programvara." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Hur man skapar XBRL-filer" %}}

Följ stegen i kodavsnittet eller förbättra det utifrån dina programbehov för att skapa utökningsbara filer för affärsrapporteringsspråket XBRL. Var säker på att ha skapande krav i din ansökan.

1. Skapa [XbrlDocument-klass](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Exempel.1. För att skapa ett nytt XBRL-instansdokument [XbrlInstanceCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) och [XbrlInstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance).1. Lägg till schemareferens med [SchemaRefCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemarefcollection)1. Lägg till kontext, enhet, artikel, fotnotslänk och mer beroende på applikationens karaktär.1. Ring [Spara metod](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) genom att tillhandahålla målfilens sökväg.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Skapande krav" %}}
För att fortsätta för generering av XBRL dokument är .NET Finance API huvudkravet för att inkluderas i ansökan. 
- Installera den via kommandoraden som ```nuget install Aspose.Finance``` eller via Package Manager Console of Visual Studio med ```Install-Package Aspose.Finance```.
- Alternativt kan du hämta offline MSI-installationsprogrammet eller DLL-filer i en ZIP-fil från [Nedladdningar](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# kod för att skapa XBRL filer" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-schema-reference.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Andra skapande alternativ" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="OFX Begäran" description="1.03 eller 2.2 format" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-response/" name="OFX Svar" description="1.03 eller 2.2 format" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}