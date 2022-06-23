---
title: "Pénzügyi jelentések konvertálása a következőn keresztül: Python"
url: /hu/python-net/conversion/
description:  Python kód a pénzügyi jelentések konvertálásához XBRL, iXBRL(inline xbrl) és OFX fájlformátumban a Python könyvtáron keresztül.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Pénzügyi jelentésfájlok konvertálása a következőn keresztül: Python" h2="Pénzügyi jelentések formátumának átalakítása, beleértve a XBRL, iXBRL és OFX fájlt 1.03-ról 2.2-re a Python alapú alkalmazásokon belül." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance, Python ezen keresztül: .NET](https://products.aspose.com/finance/python-net/) egy funkciókban gazdag, bővíthető és könnyen használható API. A fejlesztők egyszerűen ellenőrizhetnek XBRL példányt, linkbázist és taxonómiai sémát a validte() metódussal, amelynek meg kell felelnie a specifikációban előírt szintaktikai követelményeknek. Sőt, XBRL, iXBRL formátumokat is tudnak olvasni, valamint XBRL példányt hozhatnak létre a semmiből. Ezenkívül képesek **konvertálni XBRL formátumot** iXBRL és Microsoft Excel XLSX fájlokká. A API emellett támogatja a nyílt pénzügyi csere (OFX) formátumú kérés/válasz létrehozását, és konvertálja a OFX fájl kérés/válasz fájlt 1.03-ról 2.2 formátumra.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Konvertálja a OFX válasz- és kérelemfájlokat" %}}

API két osztály megadásával támogatja a OFX kérés- és válaszfájlok létrehozását. OfxRequestDocument OFX kérelemfájl létrehozásához és betöltéséhez 1.03 és 2.2 formátumban, OfxResponseDocument pedig OFX válaszfájlokhoz 1.03 és 2.2 formátumban. Ezenkívül az OfxVersionEnum Enumeration V1x tagokat tartalmaz, amely 1.x verzió, sgml fájlformátum és V2x 2.x verzió, xml fájlformátum. Az OfxRequestDocument osztály vagy az OfxResponseDocument osztály mentési metódusának meghívása után a fejlesztők könnyen konvertálhatnak 1.03 sgml fájlt 2.2 xml formátumba.


{{% blocks/products/pf/feature-page-code h3="C# Kód a OFX válaszfájlok konvertálásához" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-ofx-response-from-1.03-to-2.2.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Kód a OFX kérelemfájlok konvertálásához" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-ofx-request-from-1.03-to-2.2.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="XBRL Pénzügyi jelentések konverziója" %}}

A API támogatja XBRL fájlok konvertálását iXBRL és Microsoft® Excel XLSX formátumba. A konvertálási folyamat egyszerű, először töltse be a fájlt az XbrlDocument Class segítségével. Használja a SaveOptions osztályt a SaveFormathoz, amely paraméterként használható az XbrlDocument Class mentési módszerében. Az iXBLR fájlba történő mentéshez a SaveFormat.IXBRL, az XLSX formátumba történő exportáláshoz pedig a SaveFormat.XLSX lesz használva.

{{% blocks/products/pf/feature-page-code h3="Python Kód a(z) XBRL exportálásához ide: iXBRL" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-xbrl-to-ixbrl.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Python Kód a(z) XBRL XLSX-re való konvertálásához" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-xbrl-to-xlsx.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xbrl-to-ixbrl xbrl-to-xlsx" >}}