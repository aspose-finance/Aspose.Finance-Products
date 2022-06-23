---
title: Konvertera finansiella rapporter via Python
url: /sv/python-net/conversion/
description:  Python-kod för att konvertera finansiella rapporter i XBRL, iXBRL(inline xbrl) och OFX filformat via Python-biblioteket.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konvertera finansiella rapportfiler via Python" h2="Finansiell rapport formaterar konvertering inklusive XBRL, iXBRL och OFX fil från 1.03 till 2.2 format inom Python baserade applikationer." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance för Python via .NET](https://products.aspose.com/finance/python-net/) är en funktionsrik, utbyggbar och lättanvänd API. Utvecklare kan enkelt validera XBRL-instanser, länkbaser och taxonomischeman med metoden validate() som måste uppfylla syntaxkraven i specifikationen. Dessutom kan de läsa formaten XBRL, iXBRL och skapa XBRL-instanser från början. Dessutom kan de **konvertera XBRL-format** till iXBRL- och Microsoft Excel XLSX-filer. API stöder även skapande av begäran/svar i öppet finansiellt utbyte (OFX) och konverterar OFX filbegäran/svar från formatet 1.03 till 2.2.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Konvertera OFX svars- och begärandefiler" %}}

API stöder att skapa OFX förfrågnings- och svarsfiler genom att tillhandahålla två klasser. OfxRequestDocument för att skapa och ladda OFX begärandefiler i formaten 1.03 och 2.2 och OfxResponseDocument för OFX svarsfiler i formaten 1.03 och 2.2. Dessutom har OfxVersionEnum Enumeration medlemmarna V1x som är 1.x-version, sgml-filformat och V2x 2.x-version, xml-filformat. Efter att ha anropat sparmetoden för OfxRequestDocument-klassen eller OfxResponseDocument-klassen, kan utvecklare enkelt konvertera från 1,03 sgml-fil till 2,2 xml-format.


{{% blocks/products/pf/feature-page-code h3="C# Kod för att konvertera OFX svarsfiler" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-ofx-response-from-1.03-to-2.2.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Kod för att konvertera OFX förfrågningsfiler" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-ofx-request-from-1.03-to-2.2.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="XBRL Konvertering av finansiella rapporter" %}}

API stöder konvertering av XBRL filer till iXBRL och Microsoft® Excel XLSX-format. Konverteringsprocessen är enkel, ladda först filen via XbrlDocument Class. Använd klassen SaveOptions för SaveFormat, som ska användas som parameter i sparametoden för XbrlDocument Class. För att spara i iXBLR-fil kommer SaveFormat.IXBRL att användas och för export till XLSX-format kommer SaveFormat.XLSX att användas.

{{% blocks/products/pf/feature-page-code h3="Python Kod att exportera XBRL till iXBRL" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-xbrl-to-ixbrl.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Python Kod för konvertering från XBRL till XLSX" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-xbrl-to-xlsx.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xbrl-to-ixbrl xbrl-to-xlsx" >}}