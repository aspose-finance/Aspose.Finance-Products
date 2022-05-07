---
title: Создать файл XBRL через C#
description: Пример кода для создания файла XBRL. Используйте пример кода API для создания пакетных файлов XBRL в приложениях на основе .NET. 
url: /ru/net/create/xbrl/
family: finance
platformtag: net
feature: create
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Создать XBRL файлов через C#" h2="Создание файлов XBRL без установки Microsoft Office или любого другого программного обеспечения." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Как создать файлы XBRL" %}}

Выполните действия, описанные во фрагменте кода, или улучшите его в соответствии с потребностями вашего приложения для создания файлов расширяемого языка бизнес-отчетности XBRL. Убедитесь, что в вашем приложении есть требования к созданию.

1. Создавать [Класс XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Пример.1. Чтобы создать новый экземпляр документа XBRL [XbrlInstanceCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) а также [XbrlInstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance).1. Добавьте ссылку на схему, используя [SchemaRefCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemarefcollection)1. В зависимости от характера приложения добавьте контекст, единицу измерения, элемент, ссылку на сноску и многое другое.1. Позвоните [Сохранить метод](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) указав путь к целевому файлу.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требование к созданию" %}}
Чтобы продолжить создание XBRL документов, .NET Finance API является основным требованием, которое должно быть включено в приложение. 
- Установите его через командную строку как ```nuget install Aspose.Finance``` или через консоль диспетчера пакетов Visual Studio с ```Install-Package Aspose.Finance```.
- Кроме того, получите автономный установщик MSI или библиотеки DLL в ZIP-файле из [загрузки](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# код для создания XBRL файлов" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-schema-reference.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Другие варианты создания" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="OFX Запрос" description="Формат 1.03 или 2.2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-response/" name="OFX Ответ" description="Формат 1.03 или 2.2" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}