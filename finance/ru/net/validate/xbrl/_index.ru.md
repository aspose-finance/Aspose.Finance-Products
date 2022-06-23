---
title: Проверить файл XBRL через C#
description: Пример кода для проверки файла XBRL. Используйте пример кода API для проверки пакетных файлов XBRL в приложениях на основе .NET. 
url: /ru/net/validate/xbrl/
family: finance
platformtag: net
feature: validate
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Проверить XBRL файлов через C#" h2="Проверка финансовых отчетов в формате XBRL без установки Microsoft Office или любого другого программного обеспечения." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Как проверить файлы XBRL" %}}

Следуйте инструкциям во фрагменте кода или улучшите его в соответствии с требованиями вашего приложения для проверки документов XBRL на расширяемом языке бизнес-отчетности. Убедитесь, что в вашем приложении есть проверочные требования.

1. Загрузите файл XBRL, используя [Класс XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Пример.1. Чтобы проверить правильность загруженного файла, чтобы он совпадал с [XBRL спецификация](http://www.xbrl.org/specification/inlinexbrl-part1/rec-2013-11-18/inlinexbrl-part1-rec-2013-11-18.html)1. Чтобы проверить достоверность, используйте [Подтвердить()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) метод [XbrlInstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance) учебный класс.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требование проверки" %}}
Чтобы приступить к проверке XBRL документов, .NET Finance API является основным требованием, которое должно быть включено в приложение. 
- Установите его через командную строку как ```nuget install Aspose.Finance``` или через консоль диспетчера пакетов Visual Studio с ```Install-Package Aspose.Finance```.
- Кроме того, получите автономный установщик MSI или библиотеки DLL в ZIP-файле из [загрузки](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# код для проверки XBRL файлов" offSpacer="" %}}

{{< gist "aspose-com-gists" "1272da1f804f8cef122600269db09fbb" "validate-xbrl-instance-file.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Другие варианты проверки" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/validate/ixbrl/" name="XBRL" description="Встроенный расширяемый язык бизнес-отчетности" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}