---
title: "Pénzügyi jelentések ellenőrzése a következőn keresztül: .NET"
url: /hu/net/validate/
description:  C# kód a pénzügyi jelentések érvényesítéséhez a(z) XBRL és iXBRL fájlokban a .NET könyvtáron keresztül.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Pénzügyi jelentési fájlok érvényesítése a következőn keresztül: C#" h2="Pénzügyi jelentésformátumok ellenőrzése, beleértve a XBRL és a iXBRL formátumot a .NET alapú alkalmazásokban." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) egy funkciókban gazdag, bővíthető és könnyen használható pénzügyi jelentések feldolgozása API. A fejlesztők egyszerűen betölthetik, ellenőrizhetik, megtekinthetik vagy létrehozhatják a pénzügyi és üzleti megoldások XBRL és iXBRL formátumait. API biztosítja [XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) osztály és  [InlineXbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) osztály XBRL és iXBRL fájlok betöltéséhez.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Érvényesítse a(z) XBRL dokumentumot" %}}

A(z) XBRL fájl érvényesítése számos esetben szükséges, például az adatok megfelelő szerkezetű és formátumú ellenőrzéséhez. Az XBLR dokumentumok érvényesítéséhez először használja az XbrlDocument osztályt a XBRL fájl betöltéséhez. Használatához a [érvényesít()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) a metódusa [XbrlInstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance) osztályba, először inicializálja a [XbrlInstanceCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) XbrlDocument objektummal, XbrlInstances. Ismételje meg mindegyiket [XbrlInstance.ValidationErrors](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/properties/validationerrors) hogy megkapja a megfelelő hibakódot, és ennek megfelelően járjon el úgy, hogy kinyomtatja a testreszabott hibaüzeneteket a konzolon vagy beírja egy fájlba.

{{% blocks/products/pf/feature-page-code h3="C# kód a XBRL fájl érvényesítéséhez" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-xbrl-file.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Érvényesítse a(z) iXBRL dokumentumot" %}}

Az iXLRB érvényesítéséhez töltse be a következőn keresztül [InlineXbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) osztályt, és használja a Validate() metódust. Ban ben [ValidationErrorCode](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.validator/validationerrorcode) felsorolás, érvényesítési hibakódok vannak meghatározva minden érvényesítési szabályhoz. A kódok közül néhány a ContextPeriodNoStartTime, ContextPeriodNoEndTime, ContextPeriodStartAfterEnd, ContextInstantNoTime, ContextScenarioXbrlNamespace, ContextScenarioXbrlSubstitutionGroup stb.

{{% blocks/products/pf/feature-page-code h3="C# Kód a iXBRL dokumentum érvényesítéséhez" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-ixbrl-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Validate" >}}
{{< /blocks/products/pf/feature-page-wrap >}}