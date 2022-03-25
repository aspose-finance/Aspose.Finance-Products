---
title: Převést finanční zprávy pomocí .NET
url: /cs/net/conversion/
description:  C# kód pro konverzaci finančních zpráv v XBRL, iXBRL a OFX souborů fomat přes knihovnu .NET.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Převést soubory finančních zpráv pomocí C#" h2="Konverzace formátů finančních zpráv včetně souborů XBRL, iXBRL a OFX ze formátu 1.03 do 2.2 v aplikacích založených na .NET." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) Is a feature rich, extensible and easy to use API. Vývojáři mohou snadno ověřit XBRL instance, linkbase a schéma taxonomie pomocí [Validate () method](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) To musí splňovat požadavky syntaxe stanovené ve specifikaci. Navíc mohou číst formáty XBRL, iXBRL, stejně jako vytvářet instance XBRL od nuly. Navíc mohou ** převést XBRL formát ** na iXBRL a microsoft excel xlsx soubory. API podporuje také vytváření požadavků/odpovědí ve formátu open financial exchange (OFX) a konvertuje OFX soubor požadavek/odpověď z 1.03 do 2.2 formátu.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Convert OFX response and request files" %}}

API podporuje vytváření souborů požadavků a odpovědí OFX poskytnutím dvou tříd. [Dokument ofxrequestdocument (angl.: + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + + +](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) Pro vytváření a načítání souborů požadavků OFX ve formátu 1.03 a 2.2 a [Ofxresponsedocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) Pro soubory odezvy OFX ve formátu 1.03 a 2.2. Futhermore, [Ofxversionenum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) Enumeration having members v1x that is 1.x version, sgml file format and v2x 2.x version, xml file format. Po volání metody uložení třídy ofxrequestdocument nebo třídy ofxresponsedocument, vývojáři mohou snadno převést z 1.03 sgml soubor do 2.2 xml formátu.


{{% blocks/products/pf/feature-page-code h3="C# kód pro převod souborů odezvy OFX" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-response-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# kód pro převod souborů požadavků OFX" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-request-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Konverzace XBRL finančních zpráv" %}}

API podporuje převod souborů XBRL na iXBRL a microsoft®Formát excel xlsx. Konverzní proces je jednoduchý, nejprve načíst soubor prostřednictvím [Třída xbrldocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument)A. Použít [Class saveoptions](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions) Pro [Uložit formát](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions/properties/saveformat), Které mají být použity jako parametr v metodě uložení třídy xbrldocument. Pro ukládání souboru ixblr, [Saveformat. ixbrl](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveformat) Bude použit a pro export do xlsx formátu, bude použit saveformat. xlsx.

{{% blocks/products/pf/feature-page-code h3="C# kód pro export XBRL do iXBRL" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-ixbrl.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# kód pro převedení XBRL na xlsx" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-xlsx.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xbrl-to-ixbrl xbrl-to-xlsx" >}}