---
title: Skapa OFX Svarsfil via C#
description: Samplingskod för skapande av OFX svarsfil. Använd API exempel kod för generering av batch OFX svarsfiler inom .NET baserade program. 
url: /sv/net/create/ofx-response/
family: finance
platformtag: net
feature: create
informat: OFX Response
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Skapa OFX svarsfiler via C#" h2="OFX svarsfiler skapande utan att behöva Microsoft Office installeras eller någon annan programvara." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Hur man skapar OFX svarsfiler" %}}

Följ stegen i kod snippet eller förbättra den som av din applikationsbehov efter att ha skapande krav inom din ansökan.

1. Skapa [OfxResponseDokumentklass](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) Objekt.1. Tilldela relevanta egenskaper med olika klasser som tillhandahålls av API [SignonResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse),  [Uttalande Transaction Respons](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse), [UttalandeTransaktioner](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction)1. Använd ofxVersion V2x eller V1x för xml respektive sgml-filer från xml respektive sgml [AvxVersionEnumName](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) Som parameter i Spara metoden.1. Ring. [Spara metoden](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument/methods/save) Genom att tillhandahålla målfilen och av xVersion.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Skapandekrav" %}}
Så här fortsätter du för skapande av OFX Svarsfil, .NET Finance API är det huvudsakliga kravet att ingå i ansökan om rapport generering. 
- Installera den via kommandorad som ''nuget install Aspose.Finance''' eller via Package Manager Console i Visual Studio med'' 'Install-Package Aspose.Finance'''.
- Alternativt, få offline MSI installerare eller DLLs i en ZIP-fil från [Nerladdningar](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# kod för skapande av OFX svarfiler" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Andra skapandealternativ" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="OFX Begär fil" description="1.03 eller 2.2 Format" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/xbrl/" name="XBRL Arkiv" description="Extenable Business Reporting Språk" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}