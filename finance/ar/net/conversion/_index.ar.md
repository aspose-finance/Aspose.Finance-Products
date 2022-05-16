---
title: تحويل التقارير المالية عبر .NET
url: /ar/net/conversion/
description:  C# رمز لتحويل التقارير المالية بتنسيق XBRL و iXBRL (inline xbrl) و OFX fomats عبر مكتبة .NET.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="تحويل ملفات التقارير المالية عبر C#" h2="تنسيقات التقارير المالية التحويل بما في ذلك تنسيق XBRL و iXBRL و OFX من 1.03 إلى 2.2 داخل التطبيقات المستندة إلى .NET." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) هي ميزة غنية وقابلة للتوسيع وسهلة الاستخدام API. يمكن للمطورين بسهولة التحقق من صحة XBRL المثيلات وقواعد الروابط ومخططات التصنيف باستخدام [تحقق من طريقة ()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) التي يجب أن تتوافق مع متطلبات النحو المفروضة في المواصفات. علاوة على ذلك ، يمكنهم قراءة تنسيقات XBRL و iXBRL وإنشاء مثيل XBRL من البداية. علاوة على ذلك ، يمكنهم ** تحويل XBRL تنسيق ** إلى iXBRL وملفات Microsoft Excel XLSX. يدعم API أيضًا إنشاء طلب / استجابة بتنسيق التبادل المالي المفتوح (OFX) ويحول طلب / استجابة ملف OFX من تنسيق 1.03 إلى 2.2.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="تحويل OFX ملفات الاستجابة والطلب" %}}

يدعم API إنشاء OFX ملفات الطلبات والاستجابة من خلال توفير فئتين. [OfxRequestDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) لإنشاء وتحميل OFX طلب ملفات بتنسيق 1.03 و 2.2 و [OfxResponseDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) لملفات الاستجابة OFX بتنسيق 1.03 و 2.2. المزيد ، [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) التعداد الذي يحتوي على أعضاء V1x وهو إصدار 1.x ، تنسيق ملف sgml وإصدار V2x 2.x ، تنسيق ملف xml. بعد استدعاء طريقة Save لفئة OfxRequestDocument أو فئة OfxResponseDocument ، يمكن للمطورين التحويل بسهولة من ملف 1.03 sgml إلى تنسيق 2.2 xml.


{{% blocks/products/pf/feature-page-code h3="C# رمز لتحويل OFX ملفات الاستجابة" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-response-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# رمز لتحويل OFX طلب الملفات" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-request-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="XBRL تحويل التقارير المالية" %}}

يدعم API تحويل الملفات XBRL إلى تنسيق Microsoft® Excel XLSX iXBRL. عملية التحويل بسيطة ، قم أولاً بتحميل الملف عبر [فئة XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument). استخدم ال [فئة SaveOptions](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions) بالنسبة [SaveFormat](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions/properties/saveformat)، لاستخدامها كمعلمة في طريقة الحفظ لفئة XbrlDocument. للحفظ في ملف iXBLR ، [SaveFormat.IXBRL](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveformat) سيتم استخدامها وللتصدير إلى تنسيق XLSX ، سيتم استخدام SaveFormat.XLSX.

{{% blocks/products/pf/feature-page-code h3="C# رمز للتصدير XBRL إلى iXBRL" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-ixbrl.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# رمز XBRL لتحويل XLSX" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-xlsx.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xbrl-to-ixbrl xbrl-to-xlsx" >}}