---
title: Чтение файла XBRL через C#
description: Пример кода для чтения файла XBRL. Используйте пример кода API для чтения пакетных файлов XBRL в приложениях на основе .NET. 
url: /ru/net/read/xbrl/
family: finance
platformtag: net
feature: read
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Чтение XBRL файлов через C#" h2="Чтение финансовых отчетов в формате XBRL без установки Microsoft Office или любого другого программного обеспечения." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Как читать XBRL файлов" %}}

Следуйте инструкциям во фрагменте кода или улучшите его в соответствии с потребностями вашего приложения для чтения файлов расширяемого языка бизнес-отчетности XBRL. Убедитесь, что в вашем приложении есть требования к чтению.

1. Создавать [Класс XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Пример.1. Передайте имя допустимого файла XBRL в качестве параметра.1. Чтобы получить внутреннюю информацию о файле, используйте соответствующие классы, такие как [SchemaRefCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemarefcollection), [Контекст](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/context), [Единица измерения](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/unit) 
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требования к чтению" %}}
Чтобы приступить к чтению XBRL документов, .NET Finance API является основным требованием, которое должно быть включено в приложение. 
- Установите его через командную строку как ```nuget install Aspose.Finance``` или через консоль диспетчера пакетов Visual Studio с помощью ```Install-Package Aspose.Finance```.
- Кроме того, получите автономный установщик MSI или библиотеки DLL в ZIP-файле из [загрузки](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# код для чтения XBRL файлов" offSpacer="" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "read-xbrl-file.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Другие варианты чтения" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/read/ixbrl/" name="iXBRL" description="Встроенный расширяемый язык бизнес-отчетности" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}