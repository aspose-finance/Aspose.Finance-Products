---
title: Проверка финансовых отчетов через Python
url: /ru/python-net/validate/
description:  Код Python для проверки финансовых отчетов в файлах XBRL и iXBRL через библиотеку Python.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Проверка файлов финансовой отчетности через Python" h2="Проверка форматов финансовых отчетов, включая XBRL и iXBRL, в приложениях на основе Python." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance для Python через .NET](https://products.aspose.com/finance/python-net/) представляет собой многофункциональную, расширяемую и простую в использовании программу обработки финансовых отчетов API. Разработчики могут легко загружать, проверять, просматривать или создавать форматы XBRL и iXBRL для финансовых и бизнес-решений. API предоставляет класс XbrlDocument и класс InlineXbrlDocument для загрузки файлов XBRL и iXBRL.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Подтвердить XBRL документ" %}}

Проверка файла XBRL требуется в ряде случаев, например для проверки правильности структуры и формата данных. Чтобы проверить документы XBLR, сначала используйте класс XbrlDocument для загрузки файла XBRL. Чтобы использовать метод проверки класса XbrlInstance, сначала инициализируйте XbrlInstanceCollection с помощью объекта XbrlDocument XbrlInstances. Повторите все XbrlInstance.ValidationErrors, чтобы получить правильный код ошибки, и действуйте соответствующим образом, печатая настроенные сообщения об ошибках на консоли или записывая их в файл.

{{% blocks/products/pf/feature-page-code h3="Python Код для проверки файла XBRL" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "validate-xbrl-instance-file.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Подтвердить iXBRL документ" %}}

Для проверки iXLRB загрузите его через класс InlineXbrlDocument и используйте его метод validate(). В перечислении ValidationErrorCode коды ошибок проверки определяются для каждого правила проверки. Несколько кодов: ContextPeriodNoStartTime, ContextPeriodNoEndTime, ContextPeriodStartAfterEnd, ContextInstantNoTime, ContextScenarioXbrlNamespace, ContextScenarioXbrlSubstitutionGroup и т. д. Разработчики могут отлаживать и отображать коды конечных пользователей или указывать направление решения проблемы.

{{% blocks/products/pf/feature-page-code h3="Python Код для проверки iXBRL документа" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "validate-ixbrl-file.py" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Validate" >}}