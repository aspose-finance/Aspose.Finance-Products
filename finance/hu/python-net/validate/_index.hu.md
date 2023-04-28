---
title: "Pénzügyi jelentések ellenőrzése a következőn keresztül: Python"
url: /hu/python-net/validate/
description:  Python kód a pénzügyi jelentések érvényesítéséhez a(z) XBRL és iXBRL fájlokban a Python könyvtáron keresztül.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Pénzügyi jelentési fájlok érvényesítése a következőn keresztül: Python" h2="Pénzügyi jelentésformátumok ellenőrzése, beleértve a XBRL és a iXBRL formátumot a Python alapú alkalmazásokban." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance, Python ezen keresztül: .NET](https://products.aspose.com/finance/python-net/) egy funkciókban gazdag, bővíthető és könnyen használható pénzügyi jelentések feldolgozása API. A fejlesztők egyszerűen betölthetik, ellenőrizhetik, megtekinthetik vagy létrehozhatják a pénzügyi és üzleti megoldások XBRL és iXBRL formátumait. A API XbrlDocument osztályt és InlineXbrlDocument osztályt biztosít a XBRL és iXBRL fájlok betöltéséhez.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Érvényesítse a(z) XBRL dokumentumot" %}}

A(z) XBRL fájl érvényesítése számos esetben szükséges, például az adatok megfelelő szerkezetű és formátumú ellenőrzéséhez. Az XBLR dokumentumok érvényesítéséhez először használja az XbrlDocument osztályt a XBRL fájl betöltéséhez. Az XbrlInstance osztály érvényesítési módszerének használatához először inicializálja az XbrlInstanceCollection-t az XbrlDocument objektummal, az XbrlInstances. Iteráljon végig minden XbrlInstance.ValidationErrors-t, hogy megkapja a megfelelő hibakódot, és ennek megfelelően járjon el a testreszabott hibaüzenetek kinyomtatásával a konzolon vagy egy fájlba írásával.

{{% blocks/products/pf/feature-page-code h3="Python kód a XBRL fájl érvényesítéséhez" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "validate-xbrl-instance-file.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Érvényesítse a(z) iXBRL dokumentumot" %}}

Az iXLRB érvényesítéséhez töltse be az InlineXbrlDocument osztályon keresztül, és használja a valide() metódust. A ValidationErrorCode felsorolásban minden érvényesítési szabályhoz érvényesítési hibakódok vannak meghatározva. A kódok közül néhány a ContextPeriodNoStartTime, ContextPeriodNoEndTime, ContextPeriodStartAfterEnd, ContextInstantNoTime, ContextScenarioXbrlNamespace, ContextScenarioXbrlSubstitutionGroup stb.

{{% blocks/products/pf/feature-page-code h3="Python Kód a iXBRL dokumentum érvényesítéséhez" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "validate-ixbrl-file.py" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Validate" >}}
{{< /blocks/products/pf/feature-page-wrap >}}