---
title: Проверка финансовых отчетов через .NET
url: /ru/net/validate/
description:  Код C# для проверки финансовых отчетов в файлах XBRL и iXBRL через библиотеку .NET.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Проверка файлов финансовой отчетности через C#" h2="Проверка форматов финансовых отчетов, включая XBRL и iXBRL, в приложениях на основе .NET." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) представляет собой многофункциональную, расширяемую и простую в использовании программу обработки финансовых отчетов API. Разработчики могут легко загружать, проверять, просматривать или создавать форматы XBRL и iXBRL для финансовых и бизнес-решений. API обеспечивает [XbrlДокумент](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) класс и  [InlineXbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) класс для загрузки файлов XBRL и iXBRL.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Подтвердить XBRL документ" %}}

Проверка файла XBRL требуется в ряде случаев, например для проверки правильности структуры и формата данных. Чтобы проверить документы XBLR, сначала используйте класс XbrlDocument для загрузки файла XBRL. Чтобы использовать [подтвердить()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) метод [XbrlInstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance) класс, сначала инициализируйте [XbrlInstanceCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) с объектом XbrlDocument XbrlInstances. Итерация через каждый [XbrlInstance.ValidationErrors](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/properties/validationerrors) чтобы получить правильный код ошибки и действовать соответствующим образом, распечатав настроенные сообщения об ошибках на консоли или записав их в файл.

{{% blocks/products/pf/feature-page-code h3="C# Код для проверки файла XBRL" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-xbrl-file.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Подтвердить iXBRL документ" %}}

Для проверки iXLRB загрузите его через [InlineXbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) class и используйте его метод Validate(). В [Валидатионерркоде](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.validator/validationerrorcode) перечисление, коды ошибок проверки определяются для каждого правила проверки. Несколько кодов: ContextPeriodNoStartTime, ContextPeriodNoEndTime, ContextPeriodStartAfterEnd, ContextInstantNoTime, ContextScenarioXbrlNamespace, ContextScenarioXbrlSubstitutionGroup и т. д. Разработчики могут отлаживать и отображать коды конечных пользователей или указывать направление решения проблемы.

{{% blocks/products/pf/feature-page-code h3="C# Код для проверки iXBRL документа" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-ixbrl-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Validate" >}}
{{< /blocks/products/pf/feature-page-wrap >}}