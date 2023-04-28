---
title: Создание финансовых отчетов с помощью Python
url: /ru/python-net/create/
description:  Код Python для создания финансовых отчетов в XBRL и OFX файлов запросов или ответов через библиотеку Python.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Создание файлов финансовой отчетности с помощью Python" h2="Создание форматов финансовых отчетов, включая запрос или файл ответа XBRL и OFX в формате 1.03 или 2.2 в приложениях на основе Python." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance для Python через .NET](https://products.aspose.com/finance/python-net/) — это многофункциональная, расширяемая и простая в использовании программа для создания и обработки финансовых отчетов API. Разработчики могут легко создать экземпляр XBRL с нуля, а также добавить ссылку на схему, контекст, единицу измерения, элемент, ссылку на сноску, ссылку на роль и 
ссылка на роль дуги. API предоставляет соответствующий класс для каждой функции, например для контекста. Разработчики могут использовать ContextPeriod, ContextEntity и Context. 
Кроме того, API также поддерживает создание запроса/ответа в формате открытого финансового обмена (OFX) в формате 1.03 или 2.2.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Создать файл XBRL, добавив элемент" %}}

Для создания файла XBRL и добавления элемента в документ необходимо создать экземпляр класса XbrlDocument. Подготовьте соответствующие настройки для элемента, используя соответствующие классы API, такие как класс SchemaRef, соответствующие классы контекста, как указано выше, и класс Concept. Наконец, определите и инициализируйте свойства класса Item, а также вызовите метод сохранения для создания файла XBRL на диске.

{{% blocks/products/pf/feature-page-code h3="Код Python для создания файла XBRL путем добавления элемента" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-xbrl-file-and-add-item.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Создать OFX файлов запросов и ответов" %}}


Для создания файлов OFX API предоставляет классы OfxRequestDocument и OfxResponseDocument, и разработчики могут легко [создать OFX запрос](https://products.aspose.com/finance/python-net/create/ofx-request/) и файлы ответов в форматах 1.03 и 2.2. Для инициализации свойств OfxRequestDocument API также предоставляет другие классы, такие как классы SignonRequest, FinancialInstitution и StatementTransactionRequest. Аналогично, для инициализации свойств OfxResponseDocument API предоставляет вспомогательные классы, такие как SignonResponse, StatementTransactionResponse и StatementTransaction. Ниже приведены фрагменты кода для обоих случаев с использованием соответствующих соответствующих классов.

{{% blocks/products/pf/feature-page-code h3="Python Код для создания OFX документов запроса" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-response-files.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Python Код для создания OFX ответных документов" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-response-files.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
{{< /blocks/products/pf/feature-page-wrap >}}