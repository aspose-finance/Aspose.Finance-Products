---
title: Проверить файл XBRL через Python
description: Пример кода для проверки файла XBRL. Используйте пример кода API для проверки пакетных файлов XBRL в приложениях на основе Python. 
url: /ru/python-net/validate/xbrl/
family: finance
platformtag: python
feature: validate
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Проверить XBRL файлов через Python" h2="Проверка финансовых отчетов в формате XBRL без установки Microsoft Office или любого другого программного обеспечения." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Как проверить файлы XBRL" %}}

Следуйте инструкциям во фрагменте кода или улучшите его в соответствии с требованиями вашего приложения для проверки документов XBRL на расширяемом языке бизнес-отчетности. Убедитесь, что в вашем приложении есть проверочные требования.

1. Загрузите файл XBRL с помощью экземпляра класса XbrlDocument.2. Проверить правильность загружаемого файла, чтобы он совпадал с [XBRL спецификация](http://www.xbrl.org/specification/inlinexbrl-part1/rec-2013-11-18/inlinexbrl-part1-rec-2013-11-18.html)
3. Чтобы проверить валидность, используйте метод validate класса XbrlInstance.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требование проверки" %}}
Чтобы продолжить проверку документов XBRL, убедитесь, что у вас выполнены следующие предварительные условия. 
- ОС на базе Microsoft Windows или Linux.- Python 3.5 или новее.- Aspose.Finance для Python, на которые есть ссылки в вашем проекте.{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python код для проверки XBRL файлов" offSpacer="" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "validate-xbrl-instance-file.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Другие варианты проверки" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/validate/ixbrl/" name="XBRL" description="Встроенный расширяемый язык бизнес-отчетности" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}