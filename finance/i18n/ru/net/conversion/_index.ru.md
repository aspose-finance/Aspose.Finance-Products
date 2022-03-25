---
title: Конвертировать финансовые отчеты через .NET
url: /ru/net/conversion/
description:  Код C# для преобразования финансовых отчетов в файлах XBRL, iXBRL и OFX через библиотеку .NET.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Конвертируйте файлы финансового отчета через C#" h2="Формат преобразования финансовых отчетов, включая XBRL, iXBRL и OFX файлов с формата 1,03 на 2,2 в приложениях на основе .NET." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) Является многофункциональным, расширяемым и простым в использовании API. Разработчики могут легко проверять экземпляры XBRL, базы ссылок и схемы таксономии с помощью [Метод validate()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) Которые должны соответствовать требованиям синтаксиса, налагаемым в спецификации. Кроме того, они могут читать форматы XBRL, iXBRL, а также создавать экземпляр XBRL с нуля. Кроме того, они могут ** конвертировать XBRL формат ** в iXBRL и Microsoft Excel XLSX файлы. API также поддерживает открытый финансовый обмен (OFX) формат создания запроса/ответа и преобразует OFX запрос/ответ файла из формата 1,03 в 2,2.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Конвертируйте файлы ответов и запросов OFX" %}}

API поддерживает создание OFX файлов запросов и ответов, предоставляя два класса. [OfxRequestDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) Для создания и загрузки OFX файлов запросов в формате 1,03 и 2,2 и [OfxResponseDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) Для файлов ответа OFX в формате 1,03 и 2,2. Более того, [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) Перечисление с членами V1x, версия 1.x, формат файла sgml и версия V2x 2.x, формат файла xml. После вызова метода Save класса OfxRequestDocument или класса OfxResponseDocument разработчики могут легко конвертировать из файла 1,03 sgml в формат 2,2 xml.


{{% blocks/products/pf/feature-page-code h3="C# Код для преобразования OFX файлов ответов" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-response-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Код для преобразования OFX файлов запроса" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-request-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="XBRL Преобразование финансовых отчетов" %}}

API поддерживает преобразование XBRL файлов в iXBRL и Microsoft®Формат Excel XLSX. Процесс преобразования прост, сначала загрузите файл через [Класс XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument). Используйте [Класс SaveOptions](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions) Для [SaveFormat](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions/properties/saveformat), Который будет использоваться в качестве параметра в методе Save класса XbrlDocument. Для сохранения в файле iXBLR, [SaveFormat.IXBRL](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveformat) Будет использоваться и для экспорта в формат XLSX будет использоваться SaveFormat.XLSX.

{{% blocks/products/pf/feature-page-code h3="C# Код для экспорта XBRL в iXBRL" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-ixbrl.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Код C# для преобразования XBRL в XLSX" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-xlsx.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xbrl-to-ixbrl xbrl-to-xlsx" >}}