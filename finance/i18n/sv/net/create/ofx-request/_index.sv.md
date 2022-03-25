---
title: Skapa OFX Begär fil via C#
description: Samplingskod för OFX begär fil skapande. Använd API exempelkod för batch OFX begär filer generering inom .NET baserade program. 
url: /sv/net/create/ofx-request/
family: finance
platformtag: net
feature: create
informat: OFX Request
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Skapa OFX Begär filer via C#" h2="OFX begär filer skapa utan att behöva Microsoft Office installeras eller någon annan programvara." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Hur man skapar OFX Be om filer" %}}

Efter att ha OFX Begära filer skapande krav i din ansökan, Följ stegen i kod snippet eller förbättra det som av ditt krav.

1. Skapa [OfxRequestDokumentklass](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) Objekt.1. Tilldela relevanta egenskaper med olika klasser som tillhandahålls av API [SignonRequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonrequest), [Finansiella institutioner](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/financialinstitution), [UttalandeTransactionRequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionrequest)1. Använd ofxVersion V2x eller V1x för xml respektive sgml-filer från xml respektive sgml [AvxVersionEnumName](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) Som parameter i Spara metoden.1. Ring. [Spara metoden](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument/methods/save) Genom att tillhandahålla målfilen och av xVersion.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Skapandekrav" %}}
Så här fortsätter du för OFX Begär skapande av filer, .NET Finance API är det huvudsakliga kravet att ingå i ansökan om rapport generering. 
- Installera den via kommandorad som ''nuget install Aspose.Finance''' eller via Package Manager Console i Visual Studio med'' 'Install-Package Aspose.Finance'''.
- Alternativt, få offline MSI installerare eller DLLs i en ZIP-fil från [Nerladdningar](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# kod för OFX begär skapande av filer" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-request-files.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Andra skapandealternativ" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-response/" name="OFX Svarsfil" description="1.03 eller 2.2 Format" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/xbrl/" name="XBRL Arkiv" description="Extenable Business Reporting Språk" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}