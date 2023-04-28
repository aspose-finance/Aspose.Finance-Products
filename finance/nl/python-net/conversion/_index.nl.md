---
title: Financiële rapporten converteren via Python
url: /nl/python-net/conversion/
description:  Python code om financiële rapporten om te zetten in XBRL, iXBRL(inline xbrl) en OFX bestandsformaten via de Python bibliotheek.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Converteer financiële rapportbestanden via Python" h2="Conversie van financiële rapportformaten inclusief XBRL, iXBRL en OFX bestanden van 1.03 naar 2.2 formaat binnen Python gebaseerde applicaties." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance voor Python via .NET](https://products.aspose.com/finance/python-net/) is rijk aan functies, uitbreidbaar en gebruiksvriendelijk API. Ontwikkelaars kunnen eenvoudig XBRL instanties, linkbases en taxonomieschema's valideren met behulp van de methode Valid() die moet voldoen aan de syntaxisvereisten die in de specificatie zijn opgelegd. Bovendien kunnen ze XBRL-, iXBRL-indelingen lezen en een XBRL-instantie helemaal opnieuw maken. Bovendien kunnen ze **de XBRL-indeling** converteren naar iXBRL en Microsoft Excel XLSX-bestanden. API ondersteunt ook open financiële uitwisseling (OFX) formaat verzoek / reactie creatie en converteert OFX bestandsverzoek / antwoord van 1.03 naar 2.2 formaat.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Converteer OFX antwoord- en verzoekbestanden" %}}

API ondersteunt het maken van OFX verzoek- en antwoordbestanden door twee klassen aan te bieden. OfxRequestDocument voor het maken en laden van OFX aanvraagbestanden in 1.03 en 2.2 formaat en OfxResponseDocument voor OFX responsbestanden in 1.03 en 2.2 formaat. Bovendien heeft OfxVersionEnum Enumeration leden V1x dat is 1.x-versie, sgml-bestandsformaat en V2x 2.x-versie, xml-bestandsformaat. Na het aanroepen van de opslagmethode van de OfxRequestDocument-klasse of OfxResponseDocument-klasse, kunnen ontwikkelaars eenvoudig een 1.03 sgml-bestand converteren naar een 2.2 xml-formaat.


{{% blocks/products/pf/feature-page-code h3="C# Code om OFX antwoordbestanden te converteren" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-ofx-response-from-1.03-to-2.2.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Code om OFX aanvraagbestanden te converteren" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-ofx-request-from-1.03-to-2.2.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="XBRL Conversie van financiële rapporten" %}}

API ondersteunt het converteren van XBRL bestanden naar iXBRL en Microsoft® Excel XLSX-indeling. Het conversieproces is eenvoudig, laad eerst het bestand via XbrlDocument Class. Gebruik de klasse SaveOptions voor SaveFormat, te gebruiken als parameter in de opslagmethode van XbrlDocument Class. Voor het opslaan in een iXBLR-bestand wordt SaveFormat.IXBRL gebruikt en voor het exporteren naar XLSX-formaat wordt SaveFormat.XLSX gebruikt.

{{% blocks/products/pf/feature-page-code h3="Python Code om te exporteren XBRL naar iXBRL" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-xbrl-to-ixbrl.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Python Code voor XBRL naar XLSX-conversie" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-xbrl-to-xlsx.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xbrl-to-ixbrl xbrl-to-xlsx" >}}
{{< /blocks/products/pf/feature-page-wrap >}}