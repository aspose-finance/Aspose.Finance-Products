---
title: Преобразование финансовых отчетов через .NET
url: /ru/net/conversion/
description:  Код C# для преобразования финансовых отчетов в форматы файлов XBRL, iXBRL и OFX с помощью библиотеки .NET.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Преобразование файлов финансовых отчетов с помощью C#" h2="Преобразование форматов финансовых отчетов, включая файлы XBRL, iXBRL и OFX из формата 1.03 в формат 2.2 в приложениях на основе .NET." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) представляет собой многофункциональный, расширяемый и простой в использовании API. Разработчики могут легко проверять экземпляры XBRL, базы ссылок и схемы таксономии, используя [метод проверки()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) который должен соответствовать требованиям синтаксиса, установленным в спецификации. Кроме того, они могут читать форматы XBRL, iXBRL, а также создавать экземпляр XBRL с нуля. Более того, они могут **конвертировать формат XBRL** в файлы iXBRL и Microsoft Excel XLSX. API также поддерживает создание запроса/ответа в формате открытого финансового обмена (OFX) и преобразует файл запроса/ответа OFX из формата 1.03 в формат 2.2.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Преобразование OFX файлов ответов и запросов" %}}

API поддерживает создание OFX файлов запросов и ответов, предоставляя два класса. [Офксрекуестдокумент](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) для создания и загрузки OFX файлов запросов в формате 1.03 и 2.2 и [Офксреспонсдокумент](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) для файлов ответов OFX в формате 1.03 и 2.2. Кроме того, [Офксверсионенум](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) Перечисление, имеющее элементы V1x версии 1.x, формат файла sgml и версию V2x 2.x, формат файла xml. После вызова метода Save класса OfxRequestDocument или класса OfxResponseDocument разработчики могут легко преобразовать файл формата 1.03 sgml в формат 2.2 xml.


{{% blocks/products/pf/feature-page-code h3="C# Код для преобразования OFX файлов ответов" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-response-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Код для преобразования OFX файлов запроса" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-request-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="XBRL Преобразование финансовых отчетов" %}}

API поддерживает преобразование файлов XBRL в формат iXBRL и Microsoft® Excel XLSX. Процесс преобразования прост, сначала загрузите файл через [Класс XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument). Использовать [Класс SaveOptions](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions) для [СохранитьФормат](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions/properties/saveformat), который будет использоваться в качестве параметра в методе Save класса XbrlDocument. Для сохранения в файл iXBLR, [СохранитьФормат.IXBRL](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveformat) будет использоваться, а для экспорта в формат XLSX будет использоваться SaveFormat.XLSX.

{{% blocks/products/pf/feature-page-code h3="C# Код для экспорта XBRL в iXBRL" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-ixbrl.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Код для преобразования XBRL в XLSX" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-xlsx.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xbrl-to-ixbrl xbrl-to-xlsx" >}}