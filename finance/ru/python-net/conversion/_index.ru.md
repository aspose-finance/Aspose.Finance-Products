---
title: Преобразование финансовых отчетов через Python
url: /ru/python-net/conversion/
description:  Код Python для преобразования финансовых отчетов в форматы файлов XBRL, iXBRL(встроенный xbrl) и OFX с помощью библиотеки Python.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Преобразование файлов финансовых отчетов с помощью Python" h2="Преобразование форматов финансовых отчетов, включая файлы XBRL, iXBRL и OFX из формата 1.03 в формат 2.2 в приложениях на основе Python." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance для Python через .NET](https://products.aspose.com/finance/python-net/) представляет собой многофункциональный, расширяемый и простой в использовании API. Разработчики могут легко проверять экземпляры XBRL, базы ссылок и схемы таксономии, используя метод validate(), который должен соответствовать требованиям синтаксиса, установленным в спецификации. Более того, они могут читать форматы XBRL, iXBRL, а также создавать экземпляр XBRL с нуля. Кроме того, они могут **конвертировать формат XBRL** в файлы iXBRL и Microsoft Excel XLSX. API также поддерживает создание запроса/ответа в формате открытого финансового обмена (OFX) и преобразует файл запроса/ответа OFX из формата 1.03 в формат 2.2.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Преобразование OFX файлов ответов и запросов" %}}

API поддерживает создание OFX файлов запросов и ответов, предоставляя два класса. OfxRequestDocument для создания и загрузки файлов запросов OFX в формате 1.03 и 2.2 и OfxResponseDocument для файлов ответов OFX в формате 1.03 и 2.2. Кроме того, в перечислении OfxVersionEnum есть члены V1x версии 1.x, формат файла sgml и версия V2x 2.x, формат файла xml. После вызова метода сохранения класса OfxRequestDocument или класса OfxResponseDocument разработчики могут легко преобразовать файл формата 1.03 sgml в формат 2.2 xml.


{{% blocks/products/pf/feature-page-code h3="C# Код для преобразования OFX файлов ответов" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-ofx-response-from-1.03-to-2.2.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Код для преобразования OFX файлов запроса" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-ofx-request-from-1.03-to-2.2.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="XBRL Преобразование финансовых отчетов" %}}

API поддерживает преобразование файлов XBRL в формат iXBRL и Microsoft® Excel XLSX. Процесс преобразования прост, сначала загрузите файл через класс XbrlDocument. Используйте класс SaveOptions для SaveFormat, который будет использоваться в качестве параметра в методе сохранения класса XbrlDocument. Для сохранения в файл iXBLR будет использоваться SaveFormat.IXBRL, а для экспорта в формат XLSX — SaveFormat.XLSX.

{{% blocks/products/pf/feature-page-code h3="Python Код для экспорта XBRL в iXBRL" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-xbrl-to-ixbrl.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Python Код для преобразования XBRL в XLSX" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-xbrl-to-xlsx.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xbrl-to-ixbrl xbrl-to-xlsx" >}}