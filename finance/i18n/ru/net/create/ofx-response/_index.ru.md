---
title: Создайте файл ответа OFX через C#
description: Пример кода для создания файла ответа OFX. Используйте пример API кода для пакетной генерации файлов ответов OFX в приложениях на основе .NET. 
url: /ru/net/create/ofx-response/
family: finance
platformtag: net
feature: create
informat: OFX Response
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Создайте файлы ответов OFX через C#" h2="Создание файлов ответов OFX без необходимости установки Microsoft Office или какого-либо другого программного обеспечения." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Как создать OFX файлы ответов" %}}

Следуйте шагам в фрагменте кода или улучшите его в соответствии с потребностями вашего приложения после получения требований к созданию в вашем приложении.

1. Создать [Класс OfxResponseDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) Объект.1. Назначьте соответствующие свойства с использованием различных классов, предоставленных API like [SignonResponse (Сигноответ)](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse),  [StatementTransactionResponse-ответ](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse), [СтатентТранзакция](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction)1. Используйте ofxVersion V2x или V1x для файлов xml и sgml соответственно из [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) Как параметр в методе Save.1. Позвоните [Метод Save](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument/methods/save) Предоставив целевой файл и ofxVersion.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требование создания" %}}
Чтобы приступить к созданию файла ответа OFX, .NET Finance API является основным требованием для включения в приложение генерации отчетов. 
- Установите его через командную строку как «nuget install Aspose.Finance» или через консоль диспетчера пакетов Visual Studio с «Install-Package Aspose.Finance».
- В качестве альтернативы, получите автономный установщик MSI или DLL в ZIP-файле из [Загрузки](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Код C# для создания файлов ответов OFX" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Другие варианты создания" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="Файл запроса OFX" description="Формат 1,03 или 2,2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/xbrl/" name="Файл XBRL" description="Расширяемый язык деловой отчетности" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}