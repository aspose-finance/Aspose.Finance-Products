---
title: Pénzügyi jelentések validálása .NET segítségével
url: /hu/net/validate/
description:  C# kód a XBRL és iXBRL fájlok pénzügyi beszámolóinak hitelesítésére a .NET könyvtárban.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Pénzügyi jelentési fájlok validálása C#-on keresztül" h2="Pénzügyi jelentés formátumok, beleértve a XBRL és iXBRL .NET alapú alkalmazások érvényesítése." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) Egy funkció gazdag, bővíthető és könnyen használható pénzügyi jelentés feldolgozása API. A fejlesztők könnyen betölthetik, érvényesíthetik, megtekinthetik vagy létrehozhatják a XBRL és iXBRL formátumokat pénzügyi és üzleti megoldásokhoz. API biztosítja [Xbrldocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Osztály és  [Inlinexbrldokumentum](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) A XBRL és iXBRL fájlok betöltésére szolgáló osztály.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="XBRL dokumentum validálása" %}}

A XBRL fájl érvényesítése számos esetben szükséges, például az adatok megfelelő szerkezetű és formátumú ellenőrzéséhez. Az xblr dokumentumok validálásához először az xbrldocument osztályt használja a XBRL fájl betöltéséhez. A [Validate ()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) Módszer [Xbrlinstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance) Osztály, először is intialize a [Xbrlinstancecollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) Xbrldocument objektummal xbrlinstances. Iterate keresztül minden [Xbrlinstance. validationerrors](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/properties/validationerrors) Ahhoz, hogy a megfelelő hibakódot kapja meg, és ennek megfelelően cselekedjen azáltal, hogy a személyre szabott hibaüzeneteket a konzolra vagy a fájlon belüli írásra nyomtatja.

{{% blocks/products/pf/feature-page-code h3="C# kód a XBRL fájl érvényesítésére" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-xbrl-file.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="iXBRL dokumentum validálása" %}}

Az ixlrb érvényesítéséhez töltsük be a [Inlinexbrldokumentum](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) Osztályozza és használja annak validate () módszerét. In [Validationerrorcode](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.validator/validationerrorcode) Számolás, érvényesítési hibakódok vannak definiálva minden érvényesítési szabály. Kevés kód a contextperiodnostarttime, contextperiodnoendtime, contextperiodstartafterend, contextinstantnotime, contextscenarioxbrlnamespace, contextscenarioxbrlsubstitutiongroup stb. a fejlesztők hibakereshet és megjelenítheti a kódokat a végfelhasználók, vagy megmutathatja az irányt a probléma megoldására.

{{% blocks/products/pf/feature-page-code h3="C# kód a iXBRL dokumentum érvényesítésére" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-ixbrl-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Validate" >}}