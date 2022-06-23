---
title: Создать файл XBRL через Python
description: Пример кода для создания файла XBRL. Используйте пример кода API для создания пакетных файлов XBRL в приложениях на основе Python. 
url: /ru/python-net/create/xbrl/
family: finance
platformtag: python
feature: create
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Создать XBRL файлов через Python" h2="Создание файлов XBRL без установки Microsoft Office или любого другого программного обеспечения." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Как создать файлы XBRL" %}}

Выполните действия, описанные во фрагменте кода, или улучшите его в соответствии с потребностями вашего приложения для создания файлов расширяемого языка бизнес-отчетности XBRL. Убедитесь, что в вашем приложении есть требования к созданию.

1. Создайте экземпляр класса XbrlDocument.1. Чтобы создать новый экземпляр XBRL, задокументируйте XbrlInstanceCollection и XbrlInstance.1. Добавьте ссылку на схему, используя SchemaRefCollection1. В зависимости от характера приложения добавьте контекст, единицу измерения, элемент, ссылку на сноску и многое другое.1. Вызовите метод сохранения, указав путь к целевому файлу.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требование к созданию" %}}
Чтобы приступить к созданию XBRL документов, убедитесь, что выполнены следующие предварительные требования. 
- ОС на базе Microsoft Windows или Linux.- Python 3.5 или новее.- Aspose.Finance для Python, на которые есть ссылки в вашем проекте.{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python код для создания XBRL файлов" offSpacer="" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-xbrl-file-and-add-schema-reference.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Другие варианты создания" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/ofx-request/" name="OFX Запрос" description="Формат 1.03 или 2.2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/ofx-response/" name="OFX Ответ" description="Формат 1.03 или 2.2" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}