---
title: Konvertera finansiella rapporter via .NET
url: /sv/net/conversion/
description:  C# kod för att konvertera finansiella rapporter i XBRL, iXBRL och OFX filfomat via .NET biblioteket.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konvertera finansiella rapporter via C#" h2="Konvertering av finansiella rapportformat inklusive XBRL, iXBRL och OFX filen från 1.03 till 2.2 format inom .NET baserade program." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) Är en funktion rik, extensibel och lättanvänd API. Utvecklare kan enkelt validera XBRL instanser, länkbaser och taxonomy scheman [Validate() metoden](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) Som ska uppfylla de syntaxkrav som föreskrivs i specifikationen. Dessutom kan de läsa XBRL, iXBRL format samt skapa XBRL instans från grunden. Dessutom kan de ** konvertera XBRL format* till iXBRL och Microsoft Excel XLSX-filer. API stöder också öppet finansiellt utbyte (OFX) format begäran / svar skapande och konverterar OFX filfrågan / svar från 1.03 till 2.2 format.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Konvertera OFX Svar och begär filer" %}}

API stöder att skapa OFX förfrågan och svarsfiler genom att tillhandahålla två klasser. [OfxRequestDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) För att skapa och ladda OFX efterfråga filer i 1.03 och 2.2 format. [OfxResponseDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) För OFX svarsfiler i 1.03 och 2.2 format. För övrigt, [AvxVersionEnumName](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) Uppräkning med medlemmar V1x som är 1.x version, sgml filformat och V2x 2.x version, xml filformat. Efter att ha ringt Save metod OfxRequestDocument klass eller OfxResponseDocument klass, utvecklare kan enkelt konvertera från 1.03 sgml-fil till 2.2 xml-format.


{{% blocks/products/pf/feature-page-code h3="C# Kod för att konvertera OFX Svarsfiler" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-response-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Kod för att konvertera OFX Begär filer" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-request-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="XBRL Konvertering av finansiella rapporter" %}}

API stöder konvertering av XBRL filer till iXBRL och Microsofts®Excel XLSX-format. Konverteringsprocessen är enkel, först ladda filen via filen [XbrlDokumentklass](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument). Använd den [Spara optionsklass](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions) För [Spara format](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions/properties/saveformat), Ska användas som parameter i Spara metod för XbrlDocument Class. För att spara i iXBLR-fil, [SparaFormat.IXBRL](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveformat) Kommer att användas och för export till XLSX-format kommer SaveFormat.XLSX att användas.

{{% blocks/products/pf/feature-page-code h3="C# Kod för att exportera XBRL till iXBRL" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-ixbrl.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Kod för XBRL till XLSX- konvertering" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-xlsx.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xbrl-to-ixbrl xbrl-to-xlsx" >}}