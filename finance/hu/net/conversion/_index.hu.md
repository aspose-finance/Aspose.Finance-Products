---
title: "Pénzügyi jelentések konvertálása a következőn keresztül: .NET"
url: /hu/net/conversion/
description:  C# kód a pénzügyi jelentések konvertálásához XBRL, iXBRL és OFX fájlformátumban a .NET könyvtáron keresztül.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Pénzügyi jelentésfájlok konvertálása a következőn keresztül: C#" h2="Pénzügyi jelentések formátumának átalakítása, beleértve a XBRL, iXBRL és OFX fájlt 1.03-ról 2.2-re a .NET alapú alkalmazásokon belül." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) egy funkciókban gazdag, bővíthető és könnyen használható API. A fejlesztők egyszerűen ellenőrizhetnek XBRL példányt, linkbázist és taxonómiai sémát a használatával [validate() metódus](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) amelyeknek meg kell felelniük a specifikációban előírt szintaktikai követelményeknek. Sőt, képesek olvasni XBRL, iXBRL formátumokat, valamint a semmiből létrehozni XBRL példányt. Ezenkívül képesek **konvertálni XBRL formátumot** iXBRL és Microsoft Excel XLSX fájlokká. A API támogatja a nyílt pénzügyi csere (OFX) formátumú kérés/válasz létrehozását is, és a OFX fájl kérés/válasz fájlt 1.03-ról 2.2 formátumra konvertálja.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Konvertálja a OFX válasz- és kérelemfájlokat" %}}

A API két osztály megadásával támogatja a OFX kérés- és válaszfájlok létrehozását. [OfxRequestDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) OFX kérésfájlok létrehozásához és betöltéséhez 1.03 és 2.2 formátumban és [OfxResponseDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) OFX válaszfájlhoz 1.03 és 2.2 formátumban. Továbbá [OffxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) A V1x tagokat tartalmazó felsorolás 1.x verzió, sgml fájlformátum és V2x 2.x verzió, xml fájlformátum. Az OfxRequestDocument osztály vagy az OfxResponseDocument osztály Save metódusának meghívása után a fejlesztők könnyen konvertálhatnak 1.03 sgml fájlt 2.2 xml formátumba.


{{% blocks/products/pf/feature-page-code h3="C# Kód a OFX válaszfájlok konvertálásához" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-response-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Kód a OFX kérelemfájlok konvertálásához" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-request-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="XBRL Pénzügyi jelentések konverziója" %}}

API támogatja XBRL fájlok konvertálását iXBRL és Microsoft® Excel XLSX formátumba. A konvertálási folyamat egyszerű, először töltse be a fájlt ezen keresztül [XbrlDocument Class](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument). Használja a [SaveOptions osztály](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions) számára [SaveFormat](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions/properties/saveformat), az XbrlDocument Class mentési metódusának paramétereként használható. Az iXBLR fájlba való mentéshez [SaveFormat.IXBRL](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveformat) lesz használva, az XLSX formátumba exportáláshoz pedig a SaveFormat.XLSX lesz használva.

{{% blocks/products/pf/feature-page-code h3="C# Kód a(z) XBRL exportálásához ide: iXBRL" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-ixbrl.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Kód a(z) XBRL XLSX-re való konvertálásához" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-xlsx.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xbrl-to-ixbrl xbrl-to-xlsx" >}}