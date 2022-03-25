---
title: تحويل التقارير المالية عبر .NET
url: /ar/net/conversion/
description:  C# رمز لتحويل التقارير المالية في XBRL و iXBRL و OFX fomats عبر .NET مكتبة.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="تحويل ملفات التقارير المالية عبر C#" h2="تحويل تنسيقات التقارير المالية بما في ذلك ملف XBRL و iXBRL و OFX من تنسيق 1.03 إلى 2.2 داخل .NET." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) هي ميزة غنية ، قابلة للتوسيع وسهلة الاستخدام API. يمكن للمطورين التحقق بسهولة من XBRL من المثيلات وقواعد الربط ومخططات التصنيف باستخدام [طريقة التحقق من صحة ()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) التي يجب أن تتوافق مع متطلبات بناء الجملة المفروضة في المواصفات. علاوة على ذلك ، يمكنهم قراءة تنسيقات XBRL ، iXBRL بالإضافة إلى إنشاء XBRL مثيل من الصفر. علاوة على ذلك ، يمكنهم تحويل XBRL تنسيق ** إلى iXBRL وملفات Microsoft Excel XLSX. يدعم API أيضًا طلب تنسيق التبادل المالي المفتوح (OFX) إنشاء الاستجابة وتحويل OFX طلب/استجابة الملف من تنسيق 1.03 إلى 2.2.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="تحويل OFX ملفات الاستجابة وطلب" %}}

يدعم API إنشاء OFX ملفات الطلب والاستجابة من خلال توفير فئتين. [OfxRequestDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) لإنشاء وتحميل OFX طلب ملفات بتنسيق 1.03 و 2.2 و [OfxResponseDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) لملفات الاستجابة OFX بتنسيق 1.03 و 2.2. فوساوث ، [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) عدد الأعضاء V1x الذي هو إصدار 1.x ، تنسيق ملف sgml وإصدار V2x 2.x ، تنسيق ملف xml. بعد استدعاء طريقة حفظ فئة OfxRequestDocument أو فئة OfxResponseDocument ، يمكن للمطورين التحويل بسهولة من ملف 1.03 sgml إلى تنسيق 2.2 xml.


{{% blocks/products/pf/feature-page-code h3="C# رمز لتحويل OFX ملفات الاستجابة" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-response-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# رمز لتحويل OFX طلب ملفات" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-request-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="XBRL تحويل التقارير المالية" %}}

API يدعم تحويل XBRL من الملفات إلى iXBRL و Microsoft®تنسيق Excel XLSX. عملية التحويل بسيطة ، أولا تحميل الملف عن طريق [فئة XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument). استخدام [فئة SaveOptions](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions) ل [SaveFormat](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions/properties/saveformat)، لاستخدامها كمعلمة في طريقة حفظ XbrlDocument Class. للحفظ في ملف iXBLR ، [SaveFormat.IXBRL](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveformat) سيتم استخدامها والتصدير إلى تنسيق XLSX ، سيتم استخدام SaveFormat.XLSX.

{{% blocks/products/pf/feature-page-code h3="C# رمز لتصدير XBRL إلى iXBRL" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-ixbrl.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# كود لـ XBRL إلى تحويل XLSX" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-xlsx.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xbrl-to-ixbrl xbrl-to-xlsx" >}}