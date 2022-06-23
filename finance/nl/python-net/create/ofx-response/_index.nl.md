---
title: Maak OFX Reactiebestand via Python
description: Voorbeeldcode voor het maken van OFX antwoordbestand. Gebruik API voorbeeldcode voor het genereren van batch-OFX responsbestanden binnen Python-gebaseerde applicaties. 
url: /nl/python-net/create/ofx-response/
family: finance
platformtag: python
feature: create
informat: OFX Response
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Maak OFX Reactiebestanden via Python" h2="OFX maken van responsbestanden zonder dat Microsoft Office of andere software hoeft te worden geïnstalleerd." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Hoe u OFX antwoordbestanden maakt" %}}

Volg de stappen in het codefragment of verbeter het naar gelang uw toepassingsbehoeften nadat u de aanmaakvereisten binnen uw toepassing hebt vervuld.

1. Maak een OfxResponseDocument-klasseobject.1. Wijs de relevante eigenschappen toe met behulp van verschillende klassen die door API worden geleverd, zoals SignonResponse, StatementTransactionResponse, StatementTransaction1. Gebruik de ofxVersion V2x of V1x voor respectievelijk xml- en sgml-bestanden van OfxVersionEnum als parameter in de opslagmethode.1. Roep de opslagmethode aan door het doelbestand en ofxVersion op te geven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Aanmaakvereiste:" %}}
Zorg ervoor dat u aan de volgende vereisten voldoet om door te gaan met het maken van OFX Reactiebestand. 
- Microsoft Windows of Linux gebaseerd besturingssysteem.- Python 3.5 of hoger.- Aspose.Finance voor Python waarnaar in uw project wordt verwezen.{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python code voor het maken van OFX responsbestanden" offSpacer="" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-response-files.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Andere aanmaakopties" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/ofx-request/" name="OFX Bestand aanvragen" description="1.03 of 2.2 Formaat" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/xbrl/" name="XBRL Bestand" description="Uitbreidbare taal voor bedrijfsrapportage" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}