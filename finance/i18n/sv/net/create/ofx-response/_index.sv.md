---
title: Skapa OFX svarsfil via C#
description: Exempelkod för att skapa OFX svarsfil. Använd API exempelkod för batchgenerering av OFX svarsfiler inom .NET-baserade applikationer. 
url: /sv/net/create/ofx-response/
family: finance
platformtag: net
feature: create
informat: OFX Response
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Skapa OFX svarsfiler via C#" h2="Skapa OFX svarsfiler utan att behöva installera Microsoft Office eller någon annan programvara." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Så här skapar du OFX svarsfiler" %}}

Följ stegen i kodavsnittet eller förbättra det efter dina applikationsbehov efter att ha skapat kraven i din applikation.

1. Skapa [OfxResponseDocument-klass](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) objekt.1. Tilldela relevanta egenskaper med hjälp av olika klasser som tillhandahålls av API som [SignonResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse),  [StatementTransactionResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse), [Utdrag Transaktion](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction)1. Använd ofxVersion V2x eller V1x för xml- respektive sgml-filer från [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) som parameter i Spara-metoden.1. Ring [Spara metod](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument/methods/save) genom att tillhandahålla målfilen och ofxVersion.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Skapande krav" %}}
För att fortsätta för att skapa OFX svarsfil, är .NET Finance API huvudkravet för att inkluderas i en rapportgenereringsapplikation. 
- Installera den via kommandoraden som ```nuget install Aspose.Finance``` eller via Package Manager Console of Visual Studio med ```Install-Package Aspose.Finance```.
- Alternativt kan du hämta offline MSI-installationsprogrammet eller DLL-filer i en ZIP-fil från [Nedladdningar](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C#-kod för att skapa OFX svarsfiler" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Andra skapande alternativ" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="OFX Begär fil" description="1.03 eller 2.2 format" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/xbrl/" name="XBRL Fil" description="Extensible Business Reporting Language" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}