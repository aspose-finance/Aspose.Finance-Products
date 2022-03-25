---
title: Проверка финансовых отчетов через .NET
url: /ru/net/validate/
description:  Код C# для проверки финансовых отчетов в XBRL и iXBRL файлах через библиотеку .NET.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Проверка файлов финансовой отчетности через C#" h2="Форматы финансовых отчетов, включая XBRL и iXBRL, в приложениях на основе .NET." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) -Это многофункциональный, расширяемый и простой в использовании процесс обработки финансовых отчетов API. Разработчики могут легко загружать, проверять, просматривать или создавать форматы XBRL и iXBRL для финансовых и бизнес-решений. API обеспечивает [XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Класс и  [ИнлинеXbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) Класс для загрузки XBRL и iXBRL файлов.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Проверка документа XBRL" %}}

Проверка XBRL файла необходима для ряда случаев, например, чтобы проверить, что данные имеют правильную структуру и формат. Чтобы проверить документы XBLR, сначала используйте класс XbrlDocument для загрузки файла XBRL. Чтобы использовать [Validate ()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) Метод [XbrlInstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance) Класс, во-первых, интиализировать [XbrlInstanceCollection (Коллекция XbrlInstanceCollection)](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) С объектом XbrlDocument XbrlInstances. Iterate через каждый [XbrlInstance. Ошибки проверки](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/properties/validationerrors) Чтобы получить правильный код ошибки и действовать соответствующим образом, печатая настроенные сообщения об ошибках на консоли или записывая в файле.

{{% blocks/products/pf/feature-page-code h3="Код C# для проверки XBRL файла" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-xbrl-file.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Проверка документа iXBRL" %}}

Для проверки iXLRB загрузите его через [ИнлинеXbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) Класс и используйте его метод Validate(). В [ValidationErrorCode](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.validator/validationerrorcode) Перечисление, коды ошибок проверки определяются для каждого правила проверки. Немногие коды: ContextPeriodNoStartTime, ContextPeriodNoEndTime, ContextPeriodStafterEnd, ContextInstantNoTime, ContextScenioXbrNamespace, ContextScenarioXbrSubstitionGroup и т. Д. Разработчики могут отлаживать и отображать коды как конечных пользователей или могут отображать направление решения проблемы.

{{% blocks/products/pf/feature-page-code h3="Код C# для подтверждения документа iXBRL" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-ixbrl-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Validate" >}}