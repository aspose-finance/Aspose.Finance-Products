---
title: Создать OFX файл запроса через Python
description: Пример кода для создания файла запроса OFX. Используйте пример кода API для пакетного создания файлов запроса OFX в приложениях на основе Python. 
url: /ru/python-net/create/ofx-request/
family: finance
platformtag: python
feature: create
informat: OFX Request
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Создать OFX файлов запроса через Python" h2="OFX запросить создание файлов без установки Microsoft Office или любого другого программного обеспечения." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Как создать файлы запроса OFX" %}}

Установив требования к созданию файлов запроса OFX в приложении, выполните действия, описанные во фрагменте кода, или улучшите его в соответствии с вашими требованиями.

1. Создайте объект класса OfxRequestDocument.2. Назначьте соответствующие свойства, используя различные классы, предоставляемые API, такие как SignonRequest, FinancialInstitution], StatementTransactionRequest.
3. Используйте ofxVersion V2x или V1x для файлов xml и sgml соответственно из OfxVersionEnum в качестве параметра в методе Save.
4. Вызовите метод сохранения, указав целевой файл и версию ofxVersion.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требование к созданию" %}}
Чтобы приступить к созданию файла запроса OFX, убедитесь, что выполнены следующие предварительные требования. 
- ОС на базе Microsoft Windows или Linux.- Python 3.5 или новее.- Aspose.Finance для Python, на которые есть ссылки в вашем проекте.{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python код для OFX создания файлов запроса" offSpacer="" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-request-files.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Другие варианты создания" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/ofx-response/" name="OFX Файл ответов" description="Формат 1.03 или 2.2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/xbrl/" name="XBRL файл" description="Расширяемый язык бизнес-отчетности" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}