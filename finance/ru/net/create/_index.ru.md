---
title: Создание финансовых отчетов с помощью .NET
url: /ru/net/create/
description:  Код C# для создания финансовых отчетов в XBRL и OFX файлов запросов или ответов через библиотеку .NET.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Создание файлов финансовой отчетности с помощью C#" h2="Создание форматов финансовых отчетов, включая запрос или файл ответа XBRL и OFX в формате 1.03 или 2.2 в приложениях на основе .NET." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) — это многофункциональная, расширяемая и простая в использовании программа для создания и обработки финансовых отчетов API. Разработчики могут легко создать экземпляр XBRL с нуля, а также добавить ссылку на схему, контекст, единицу измерения, элемент, ссылку на сноску, ссылку на роль и 
ссылка на роль дуги. API предоставляет соответствующий класс для каждой функции, например для контекста, которую разработчики могут использовать [КонтекстПериод](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextperiod), [КонтекстЭнтити](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextentity) а также [Контекст](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/context). 
Кроме того, API также поддерживает создание запроса/ответа в формате открытого финансового обмена (OFX) в формате 1.03 или 2.2.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Создать файл XBRL, добавив элемент" %}}

Для создания файла XBRL и добавления элемента в документ необходимо создать [Класс XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) пример. Подготовьте соответствующие настройки для элемента, используя соответствующие классы API, такие как [Класс SchemaRef](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemaref)соответствующие классы контекста, как указано выше, и [Концептуальный класс](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/concept). Наконец определите и инициализируйте [Класс предмета](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/item) свойства, а также вызывать [Сохранить метод](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) к [создать XBRL](https://products.aspose.com/finance/net/create/xbrl/) файл на диск.

{{% blocks/products/pf/feature-page-code h3="Код C# для создания файла XBRL путем добавления элемента" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-item.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Создать OFX файлов запросов и ответов" %}}


Для создания файлов OFX API предоставляет [Офксрекуестдокумент](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) а также [Офксреспонсдокумент](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) классы и разработчики могут легко [создать OFX запрос](https://products.aspose.com/finance/net/create/ofx-request/) и файлы ответов в форматах 1.03 и 2.2. Для инициализации свойств OfxRequestDocument API также предоставляет другие классы, такие как [SignonRequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonrequest), [Финансовое учреждение](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/financialinstitution) а также [ЗаявлениеТранзакцииЗапрос](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionrequest) классы. Точно так же для инициализации свойств OfxResponseDocument API предоставляет вспомогательные классы, такие как [SignonResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse),  [ЗаявлениеТранзакцияОтвет](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse) а также [ЗаявлениеТранзакция](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction). Ниже приведены фрагменты кода для обоих случаев с использованием соответствующих соответствующих классов.

{{% blocks/products/pf/feature-page-code h3="C# Код для создания OFX документов запроса" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Код для создания OFX ответных документов" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
{{< /blocks/products/pf/feature-page-wrap >}}