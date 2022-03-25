---
title: Проверка XBRL файла через C#
description: Пример кода для проверки файла XBRL. Используйте пример API кода для проверки пакетных XBRL файлов в приложениях на основе .NET. 
url: /ru/net/validate/xbrl/
family: finance
platformtag: net
feature: validate
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Проверка XBRL файлов через C#" h2="Отчетность финансовых отчетов в формате XBRL без необходимости установки Microsoft Office или какого-либо другого программного обеспечения." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Как подтвердить XBRL файлов" %}}

Выполните действия в фрагменте кода или улучшите его в соответствии с требованиями приложения для проверки документов XBRL на языке расширяемой бизнес-отчетности. Убедитесь, что в вашем приложении есть требования к проверке.

1. Загрузить файл XBRL с использованием [Класс XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Экземпляр.1. Чтобы проверить действительность загруженного файла, чтобы он соответствовал [XBRL спецификация](http://www.xbrl.org/specification/inlinexbrl-part1/rec-2013-11-18/inlinexbrl-part1-rec-2013-11-18.html)1. Чтобы проверить валидатичность, используйте [Проверить ()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) Метод [XbrlInstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance) Класс.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требование валидации" %}}
Чтобы продолжить проверку документов XBRL, .NET Finance API является основным требованием для включения в приложение. 
- Установите его через командную строку как «nuget install Aspose.Finance» или через консоль диспетчера пакетов Visual Studio с «Install-Package Aspose.Finance».
- В качестве альтернативы, получите автономный установщик MSI или DLL в ZIP-файле из [Загрузки](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Код C# для проверки XBRL файлов" offSpacer="" %}}

{{< gist "aspose-com-gists" "1272da1f804f8cef122600269db09fbb" "validate-xbrl-instance-file.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Другие варианты валливации" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/validate/ixbrl/" name="XBRL" description="Расширяемый язык деловой отчетности Inline" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}