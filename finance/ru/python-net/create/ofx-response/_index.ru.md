---
title: Создать файл ответов OFX через Python
description: Пример кода для создания файла ответов OFX. Используйте пример кода API для пакетного создания файлов ответов OFX в приложениях на основе Python. 
url: /ru/python-net/create/ofx-response/
family: finance
platformtag: python
feature: create
informat: OFX Response
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Создайте файлы ответов OFX через Python" h2="OFX создание файлов ответов без установки Microsoft Office или любого другого программного обеспечения." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Как создать файлы ответов OFX" %}}

Следуйте инструкциям во фрагменте кода или улучшите его в соответствии с потребностями вашего приложения после того, как в вашем приложении будут созданы требования к созданию.

1. Создайте объект класса OfxResponseDocument.1. Назначьте соответствующие свойства, используя различные классы, предоставляемые API, такие как SignonResponse, StatementTransactionResponse, StatementTransaction.1. Используйте ofxVersion V2x или V1x для файлов xml и sgml соответственно из OfxVersionEnum в качестве параметра в методе сохранения.1. Вызовите метод сохранения, указав целевой файл и версию ofxVersion.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требование к созданию" %}}
Чтобы приступить к созданию файла ответов OFX, убедитесь, что выполнены следующие предварительные требования. 
- ОС на базе Microsoft Windows или Linux.- Python 3.5 или новее.- Aspose.Finance для Python, на которые есть ссылки в вашем проекте.{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python код для создания файлов ответов OFX" offSpacer="" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-response-files.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Другие варианты создания" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/ofx-request/" name="OFX Запросить файл" description="Формат 1.03 или 2.2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/xbrl/" name="XBRL файл" description="Расширяемый язык бизнес-отчетности" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}