---
title: Создание финансовых отчетов через .NET
url: /ru/net/create/
description:  Код C# для создания финансовых отчетов в XBRL и OFX файлов запросов или ответов через библиотеку .NET.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Создание файлов финансовой отчетности через C#" h2="Создание форматов финансовых отчетов, включая XBRL и OFX файлов запроса или ответа в формате 1,03 или 2,2 в приложениях на основе .NET." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) -Это многофункциональный, расширяемый и простой в использовании процесс создания и обработки финансовых отчетов API. Разработчики могут легко создавать экземпляр XBRL с нуля, а также добавлять ссылку на схему, контекст, единицу, элемент, ссылку на сноску, ссылку на роль и 
Ссылка на роль дуги. API предоставляет релевантный класс для каждой функции, например для контекста, разработчики могут использовать [Контекстный период](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextperiod), [Контекстность](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextentity) И [Контекст](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/context). 
Кроме того, API также поддерживает открытый финансовый обмен (OFX) формат создания запроса/ответа в формате 1,03 или 2,2.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Создайте файл XBRL, добавив элемент" %}}

Для создания XBRL файла и добавления элемента в документ, процесс заключается в создании [Класс XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Экземпляр. Подготовьте соответствующие настройки для элемента, используя соответствующие классы API, такие как [Класс SchemaRef](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemaref), Соответствующие контекстные классы, как упомянуто выше, и [Концептуальный класс](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/concept). Наконец определить и интиализировать [Класс товара](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/item) Свойства, а также позвонить [Метод Save](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) К [Создать XBRL](https://products.aspose.com/finance/net/create/xbrl/) Файл в диск.

{{% blocks/products/pf/feature-page-code h3="Код C# для создания XBRL файла, добавив товар" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-item.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Создание файлов запросов и ответов OFX" %}}


Для создания OFX файлов API [OfxRequestDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) И [OfxResponseDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) Классы и разработчики могут легко [Создать OFX Запрос](https://products.aspose.com/finance/net/create/ofx-request/) И файлы ответа в обоих форматах 1,03 и 2,2. Для инициализации свойств OfxRequestDocument API также предоставляет другие классы, такие как [SignonRequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonrequest), [Финансово учреждение](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/financialinstitution) И [Запрос StatementTransactionRequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionrequest) Классы. Точно так же для интиализации свойств OfxResponseDocument API предоставляет поддерживающие классы, такие как [SignonResponse (Сигноответ)](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse),  [StatementTransactionResponse-ответ](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse) И [СтатентТранзакция](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction). Ниже приведены фрагменты кода для обоих случаев с использованием соответствующих классов.

{{% blocks/products/pf/feature-page-code h3="Код C# для создания OFX документов запроса" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Код C# для создания ответных документов OFX" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}