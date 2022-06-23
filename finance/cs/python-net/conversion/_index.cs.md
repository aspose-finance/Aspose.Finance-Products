---
title: Převést finanční přehledy prostřednictvím Python
url: /cs/python-net/conversion/
description:  Python kód pro převod finančních zpráv ve formátech souborů XBRL, iXBRL(inline xbrl) a OFX prostřednictvím knihovny Python.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Převést soubory finančních výkazů prostřednictvím Python" h2="Finanční zpráva převádí formáty včetně souborů XBRL, iXBRL a OFX z formátu 1.03 na 2.2 v aplikacích založených na Python." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance za Python prostřednictvím .NET](https://products.aspose.com/finance/python-net/) je API bohatá, rozšiřitelná a snadno použitelná. Vývojáři mohou snadno ověřit XBRL instance, báze odkazů a taxonomická schémata pomocí metody validate(), která musí splňovat požadavky na syntaxi stanovené ve specifikaci. Navíc mohou číst formáty XBRL, iXBRL a také vytvářet instance XBRL od začátku. Navíc mohou **převést XBRL formát** na iXBRL a soubory Microsoft Excel XLSX. API také podporuje vytváření požadavku/odpovědi ve formátu otevřené finanční výměny (OFX) a převádí soubor požadavku/odpovědi OFX z formátu 1.03 na formát 2.2.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Převeďte soubory odpovědí a požadavků OFX" %}}

API podporuje vytváření souborů požadavků a odpovědí OFX tím, že poskytuje dvě třídy. OfxRequestDocument pro vytváření a načítání souborů požadavků OFX ve formátu 1.03 a 2.2 a OfxResponseDocument pro soubory odpovědí OFX ve formátu 1.03 a 2.2. Kromě toho má OfxVersionEnum Enumeration členy V1x, což je verze 1.x, formát souboru sgml a verze V2x 2.x, formát souboru xml. Po volání metody uložení třídy OfxRequestDocument nebo třídy OfxResponseDocument mohou vývojáři snadno převést ze souboru 1,03 sgml do formátu 2,2 xml.


{{% blocks/products/pf/feature-page-code h3="C# Kód pro převod OFX souborů odpovědí" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-ofx-response-from-1.03-to-2.2.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Kód pro převod souborů požadavku OFX" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-ofx-request-from-1.03-to-2.2.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="XBRL Konverze finančních přehledů" %}}

API podporuje převod XBRL souborů do iXBRL a formátu Microsoft® Excel XLSX. Proces převodu je jednoduchý, nejprve načtěte soubor pomocí třídy XbrlDocument. Použijte třídu SaveOptions pro SaveFormat, která se má použít jako parametr v metodě ukládání třídy XbrlDocument. Pro uložení do souboru iXBLR bude použit SaveFormat.IXBRL a pro export do formátu XLSX SaveFormat.XLSX.

{{% blocks/products/pf/feature-page-code h3="Python Kód k exportu XBRL do iXBRL" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-xbrl-to-ixbrl.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Python Kód pro konverzi XBRL na XLSX" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-xbrl-to-xlsx.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xbrl-to-ixbrl xbrl-to-xlsx" >}}