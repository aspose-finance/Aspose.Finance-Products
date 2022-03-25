---
title: Создайте файл XBRL через C#
description: Пример кода для создания файла XBRL. Используйте пример API кода для пакетной генерации XBRL файлов в приложениях на основе .NET. 
url: /ru/net/create/xbrl/
family: finance
platformtag: net
feature: create
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Создавайте файлы XBRL через C#" h2="Создание файлов XBRL без необходимости установки Microsoft Office или какого-либо другого программного обеспечения." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Как создать XBRL файлов" %}}

Выполните действия в фрагменте кода или улучшите его в соответствии с потребностями приложения для создания расширяемых файлов XBRL языка бизнес-отчетности. Будьте уверены, что в вашем приложении есть требования к созданию.

1. Создать [Класс XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Экземпляр.1. Чтобы создать новый документ экземпляра XBRL [XbrlInstanceCollection (Коллекция XbrlInstanceCollection)](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) И [XbrlInstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance).1. Добавить ссылку на схему с использованием [Коллекция SchemaRefCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemarefcollection)1. В зависимости от характера приложения добавьте контекст, единицу, элемент, ссылку сноски и многое другое.1. Позвоните [Метод Save](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) Путем предоставления целевого пути к файлу.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требование создания" %}}
Чтобы приступить к созданию документов XBRL, .NET Finance API является основным требованием для включения в приложение. 
- Установите его через командную строку как «nuget install Aspose.Finance» или через консоль диспетчера пакетов Visual Studio с «Install-Package Aspose.Finance».
- В качестве альтернативы, получите автономный установщик MSI или DLL в ZIP-файле из [Загрузки](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Код C# для создания файлов XBRL" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-schema-reference.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Другие варианты создания" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="Запрос OFX" description="Формат 1,03 или 2,2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-response/" name="Ответ OFX" description="Формат 1,03 или 2,2" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}