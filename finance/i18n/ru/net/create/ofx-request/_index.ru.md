---
title: Создайте файл запроса OFX через C#
description: Пример кода для создания файла запроса OFX. Используйте пример API кода для создания пакетных OFX файлов запросов в приложениях на основе .NET. 
url: /ru/net/create/ofx-request/
family: finance
platformtag: net
feature: create
informat: OFX Request
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Создайте OFX файлы запросов через C#" h2="OFX запрашивают создание файлов без необходимости установки Microsoft Office или какого-либо другого программного обеспечения." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Как создать OFX файлы запросов" %}}

После получения OFX требований к созданию файлов запроса в вашем приложении, следуйте шагам в фрагменте кода или улучшите его в соответствии с вашими требованиями.

1. Создать [Класс OfxRequestDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) Объект.1. Назначьте соответствующие свойства с использованием различных классов, предоставленных API like [SignonRequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonrequest), [Финансово учреждение](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/financialinstitution), [Запрос StatementTransactionRequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionrequest)1. Используйте ofxVersion V2x или V1x для файлов xml и sgml соответственно из [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) Как параметр в методе Save.1. Позвоните [Метод Save](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument/methods/save) Предоставив целевой файл и ofxVersion.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требование создания" %}}
Чтобы приступить к созданию файла OFX Запросов, .NET Finance API является основным требованием для включения в приложение генерации отчетов. 
- Установите его через командную строку как «nuget install Aspose.Finance» или через консоль диспетчера пакетов Visual Studio с «Install-Package Aspose.Finance».
- В качестве альтернативы, получите автономный установщик MSI или DLL в ZIP-файле из [Загрузки](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Код C# для создания файлов запроса OFX" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-request-files.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Другие варианты создания" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-response/" name="Файл ответа OFX" description="Формат 1,03 или 2,2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/xbrl/" name="Файл XBRL" description="Расширяемый язык деловой отчетности" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}