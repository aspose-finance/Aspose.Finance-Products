---
title: Pénzügyi jelentések konvertálása .NET segítségével
url: /hu/net/conversion/
description:  C# kód a pénzügyi jelentések XBRL, iXBRL és OFX file fomatokban történő konvertálásához .NET könyvtárban.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Pénzügyi jelentés fájlok konvertálása C#-on keresztül" h2="Pénzügyi jelentés formátumok konverziója, beleértve a XBRL, iXBRL és OFX fájl 1.03 és 2.2 formátumban .NET alapú alkalmazások." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) A feature gazdag, bővíthető és könnyen használható API. A fejlesztők könnyen érvényesíthetik a XBRL példányokat, linkbázisokat és rendszertani sémákat [Validate () módszer](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) Ennek meg kell felelnie a specifikációban megszabott szintaxis követelményeknek. Ráadásul XBRL, iXBRL formátumokat is olvashatnak, valamint XBRL példányt készíthetnek a nulláról. Továbbá, hogy ** konvertálni XBRL formátum ** iXBRL és microsoft excel xlsx fájlokat. API támogatja a open financial exchange (OFX) formátumú kérés/válasz létrehozását, és konvertálja a OFX fájl kérést/választ az 1.03-ról a 2.2 formátumra.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="OFX válasz és kérés fájlok konvertálása" %}}

API két osztály megadásával támogatja a OFX kérelem-és válaszfájlok létrehozását. [Ofxrequestdocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) OFX kérés fájlok létrehozásához és betöltéséhez 1.03 és 2.2 formátumban és [Ofxresponsedocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) OFX válaszfájlok 1.03 és 2.2 formátumban. Futhermore, [Ofxversionenum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) Számolás, amelynek tagjai v1x, hogy 1.x verzió, sgml fájlformátum és v2x 2.x verzió, xml fájlformátum. Miután az ofxrequestdocument osztály vagy ofxresponsedocument osztály mentési módszerét meghívják, a fejlesztők könnyen átalakíthatják az 1.03 sgml fájlt 2.2 xml formátumba.


{{% blocks/products/pf/feature-page-code h3="C# kód a OFX válaszfájlok átalakításához" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-response-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# kód a OFX kérelem fájlok átalakításához" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-request-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="XBRL pénzügyi jelentések konverziója" %}}

API támogatja a XBRL fájlok iXBRL és a microsoft®Excel xlsx formátum. Konverziós folyamat egyszerű, először is betölteni a fájlt keresztül [Xbrldocument osztály](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument)A "", a "" ", a" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "". Használja a [Saveoptions osztály](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions) For [Saveformat](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions/properties/saveformat), Az xbrldocument osztály mentési módjának paramétereként használható. Ixblr fájlba való mentéshez, [Saveformat. ixbrl](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveformat) Lesz használható, és exportálni xlsx formátumban, saveformat. xlsx lesz használva.

{{% blocks/products/pf/feature-page-code h3="C# kód a XBRL iXBRL exportálásához" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-ixbrl.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# kód XBRL xlsx konverzióra" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-xlsx.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xbrl-to-ixbrl xbrl-to-xlsx" >}}