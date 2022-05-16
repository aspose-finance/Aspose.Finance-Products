---
title: Konvertera finansiella rapporter via .NET
url: /sv/net/conversion/
description:  C#-kod för att konvertera finansiella rapporter i XBRL, iXBRL(inline xbrl) och OFX filformat via .NET-biblioteket.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konvertera finansiella rapportfiler via C#" h2="Finansiell rapport formaterar konvertering inklusive XBRL, iXBRL och OFX fil från 1.03 till 2.2 format inom .NET baserade applikationer." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) är en funktionsrik, utbyggbar och lättanvänd API. Utvecklare kan enkelt validera XBRL-instanser, länkbaser och taxonomischeman med hjälp av [validate() metod](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) som måste uppfylla syntaxkraven i specifikationen. Dessutom kan de läsa formaten XBRL, iXBRL och skapa XBRL-instanser från början. Dessutom kan de **konvertera XBRL-format** till iXBRL- och Microsoft Excel XLSX-filer. API stöder också skapande av begäran/svar i öppet finansiellt utbyte (OFX) och konverterar OFX filbegäran/svar från formatet 1.03 till 2.2.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Konvertera OFX svars- och begärandefiler" %}}

API stöder att skapa OFX förfrågnings- och svarsfiler genom att tillhandahålla två klasser. [OfxRequestDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) för att skapa och ladda OFX begärandefiler i 1.03 och 2.2 format och [OfxResponseDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) för OFX svarsfiler i formaten 1.03 och 2.2. Dessutom, [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) Uppräkning med medlemmar V1x som är 1.x version, sgml filformat och V2x 2.x version, xml filformat. Efter att ha anropat Save-metoden för OfxRequestDocument-klassen eller OfxResponseDocument-klassen, kan utvecklare enkelt konvertera från 1,03 sgml-fil till 2,2 xml-format.


{{% blocks/products/pf/feature-page-code h3="C# Kod för att konvertera OFX svarsfiler" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-response-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Kod för att konvertera OFX förfrågningsfiler" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-request-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="XBRL Konvertering av finansiella rapporter" %}}

API stöder konvertering av XBRL filer till iXBRL och Microsoft® Excel XLSX-format. Konverteringsprocessen är enkel, ladda först filen via [XbrlDocument Class](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument). Använd [Sparaalternativ klass](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions) för [SaveFormat](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions/properties/saveformat), som ska användas som parameter i Save-metoden för XbrlDocument Class. För att spara i iXBLR-fil, [SaveFormat.IXBRL](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveformat) kommer att användas och för export till XLSX-format kommer SaveFormat.XLSX att användas.

{{% blocks/products/pf/feature-page-code h3="C# Kod att exportera XBRL till iXBRL" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-ixbrl.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Kod för konvertering från XBRL till XLSX" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-xlsx.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xbrl-to-ixbrl xbrl-to-xlsx" >}}