---
title: Skapa OFX Begäran fil via C#
description: Exempelkod för att skapa OFX-begäran. Använd API exempelkod för generering av batch-OFX begärandefiler inom .NET-baserade applikationer. 
url: /sv/net/create/ofx-request/
family: finance
platformtag: net
feature: create
informat: OFX Request
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Skapa OFX förfrågningsfiler via C#" h2="OFX begär att skapa filer utan att behöva installera Microsoft Office eller någon annan programvara." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Så här skapar du OFX förfrågningsfiler" %}}

Efter att ha uppfyllt kraven för att skapa OFX Begär filer i din applikation, följ stegen i kodavsnittet eller förbättra det enligt ditt krav.

1. Skapa [OfxRequestDocument klass](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) objekt.1. Tilldela relevanta egenskaper med hjälp av olika klasser som tillhandahålls av API som [SignonRequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonrequest), [Finansiell institution](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/financialinstitution), [StatementTransactionRequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionrequest)1. Använd ofxVersion V2x eller V1x för xml- respektive sgml-filer från [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) som parameter i Spara-metoden.1. Ring [Spara metod](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument/methods/save) genom att tillhandahålla målfilen och ofxVersion.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Skapande krav" %}}
För att fortsätta för OFX att skapa en begäran om fil, är .NET Finance API huvudkravet för att inkluderas i en rapportgenereringsapplikation. 
- Installera den via kommandoraden som ```nuget install Aspose.Finance``` eller via Package Manager Console of Visual Studio med ```Install-Package Aspose.Finance```.
- Alternativt kan du hämta offline MSI-installationsprogrammet eller DLL-filer i en ZIP-fil från [Nedladdningar](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# kod för att skapa OFX begärande filer" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-request-files.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Andra skapande alternativ" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-response/" name="OFX Svarsfil" description="1.03 eller 2.2 format" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/xbrl/" name="XBRL Fil" description="Extensible Business Reporting Language" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}