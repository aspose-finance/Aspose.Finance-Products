---
title: Создать OFX файл запроса через C#
description: Пример кода для создания файла запроса OFX. Используйте пример кода API для пакетного создания файлов запроса OFX в приложениях на основе .NET. 
url: /ru/net/create/ofx-request/
family: finance
platformtag: net
feature: create
informat: OFX Request
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Создать OFX файлов запроса через C#" h2="OFX запросить создание файлов без установки Microsoft Office или любого другого программного обеспечения." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Как создать файлы запроса OFX" %}}

Установив требования к созданию файлов запроса OFX в приложении, выполните действия, описанные во фрагменте кода, или улучшите его в соответствии с вашими требованиями.

1. Создавать [Класс OfxRequestDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) объект.1. Назначьте соответствующие свойства, используя различные классы, предоставляемые API, например [SignonRequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonrequest), [Финансовое учреждение](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/financialinstitution), [ЗаявлениеТранзакцииЗапрос](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionrequest)1. Используйте версию ofxVersion V2x или V1x для файлов xml и sgml соответственно из [Офксверсионенум](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) в качестве параметра в методе сохранения.1. Позвоните [Сохранить метод](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument/methods/save) путем предоставления целевого файла и ofxVersion.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требование к созданию" %}}
Чтобы продолжить создание файла запроса OFX, .NET Finance API является основным требованием, которое должно быть включено в приложение для создания отчетов. 
- Установите его через командную строку как ```nuget install Aspose.Finance``` или через консоль диспетчера пакетов Visual Studio с помощью ```Install-Package Aspose.Finance```.
- Кроме того, получите автономный установщик MSI или библиотеки DLL в ZIP-файле из [загрузки](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# код для OFX создания файлов запроса" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-request-files.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Другие варианты создания" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-response/" name="OFX Файл ответов" description="Формат 1.03 или 2.2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/xbrl/" name="XBRL файл" description="Расширяемый язык бизнес-отчетности" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}