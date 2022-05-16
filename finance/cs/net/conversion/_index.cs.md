---
title: Převést finanční přehledy prostřednictvím .NET
url: /cs/net/conversion/
description:  C# kód pro převod finančních zpráv ve formátech souborů XBRL, iXBRL(inline xbrl) a OFX prostřednictvím knihovny .NET.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Převést soubory finančních výkazů prostřednictvím C#" h2="Konverze formátů finančních zpráv včetně souborů XBRL, iXBRL a OFX z formátu 1.03 na 2.2 v aplikacích založených na .NET." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) je API bohatá, rozšiřitelná a snadno použitelná. Vývojáři mohou pomocí XBRL snadno ověřit instance, databáze odkazů a taxonomická schémata [metoda validate().](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) které musí splňovat syntaktické požadavky stanovené ve specifikaci. Navíc mohou číst formáty XBRL, iXBRL a také vytvářet instance XBRL od začátku. Navíc mohou **převést XBRL formát** na iXBRL a soubory Microsoft Excel XLSX. API také podporuje vytváření požadavku/odpovědi ve formátu otevřené finanční výměny (OFX) a převádí OFX soubor požadavku/odpovědi z formátu 1.03 na formát 2.2.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Převeďte soubory odpovědí a požadavků OFX" %}}

API podporuje vytváření souborů požadavků a odpovědí OFX tím, že poskytuje dvě třídy. [OfxRequestDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) pro vytváření a načítání OFX souborů požadavků ve formátu 1.03 a 2.2 a [OfxResponseDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) pro soubory odpovědí OFX ve formátu 1.03 a 2.2. dále [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) Výčet obsahující členy V1x, což je verze 1.x, formát souboru sgml a verze V2x 2.x, formát souboru xml. Po volání metody Save třídy OfxRequestDocument nebo třídy OfxResponseDocument mohou vývojáři snadno převést ze souboru 1,03 sgml do formátu 2,2 xml.


{{% blocks/products/pf/feature-page-code h3="C# Kód pro převod OFX souborů odpovědí" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-response-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Kód pro převod souborů požadavku OFX" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-request-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="XBRL Konverze finančních přehledů" %}}

API podporuje převod XBRL souborů do iXBRL a formátu Microsoft® Excel XLSX. Proces převodu je jednoduchý, nejprve načtěte soubor přes [Třída XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument). Použijte [Třída SaveOptions](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions) pro [UložitFormát](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions/properties/saveformat), který má být použit jako parametr v metodě Save třídy XbrlDocument. Pro uložení do souboru iXBLR, [SaveFormat.IXBRL](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveformat) a pro export do formátu XLSX se použije SaveFormat.XLSX.

{{% blocks/products/pf/feature-page-code h3="C# Kód k exportu XBRL do iXBRL" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-ixbrl.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Kód pro konverzi XBRL na XLSX" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-xlsx.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xbrl-to-ixbrl xbrl-to-xlsx" >}}