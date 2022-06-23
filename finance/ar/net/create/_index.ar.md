---
title: إنشاء تقارير مالية عبر .NET
url: /ar/net/create/
description:  C# لإنشاء تقارير مالية في XBRL ، و OFX طلب ملفات أو استجابة عبر مكتبة .NET.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="إنشاء ملفات التقارير المالية عبر C#" h2="إنشاء تنسيقات التقارير المالية بما في ذلك XBRL و OFX ملف الطلب أو الاستجابة بتنسيق 1.03 أو 2.2 داخل التطبيقات المستندة إلى .NET." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) هي ميزة غنية وقابلة للتوسيع وسهلة الاستخدام لإنشاء التقارير المالية ومعالجتها API. يمكن للمطورين إنشاء مثيل XBRL من البداية بسهولة بالإضافة إلى إضافة مرجع مخطط وسياق ووحدة وعنصر وارتباط حاشية سفلية ومرجع دور و 
مرجع دور القوس. يوفر API فئة ملائمة لكل ميزة مثل السياق ، يمكن للمطورين استخدامها [السياق](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextperiod)و [السياق الكيان](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextentity) و [سياق](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/context). 
علاوة على ذلك ، يدعم API أيضًا إنشاء طلب / استجابة بتنسيق التبادل المالي المفتوح (OFX) بتنسيق 1.03 أو 2.2.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="قم بإنشاء ملف XBRL عن طريق إضافة عنصر" %}}

لإنشاء ملف XBRL وإضافة عنصر إلى المستند ، تكون العملية هي إنشاء [فئة XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) نموذج. قم بإعداد الإعدادات ذات الصلة للعنصر باستخدام فئات API المناسبة مثل [فئة SchemaRef](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemaref)، فئات السياق ذات الصلة كما هو مذكور أعلاه و [فئة المفهوم](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/concept). أخيرًا حدد وخصص [فئة البند](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/item) خصائص وكذلك استدعاء [طريقة الحفظ](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) إلى [إنشاء XBRL](https://products.aspose.com/finance/net/create/xbrl/) ملف في القرص.

{{% blocks/products/pf/feature-page-code h3="C# رمز لإنشاء XBRL ملف عن طريق إضافة عنصر" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-item.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="قم بإنشاء OFX ملفات الطلبات والاستجابة" %}}


لإنشاء ملفات OFX ، يوفر API [OfxRequestDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) و [OfxResponseDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) يمكن الطبقات والمطورين بسهولة [إنشاء OFX طلب](https://products.aspose.com/finance/net/create/ofx-request/) وملفات الاستجابة بتنسيقات 1.03 و 2.2. لتهيئة خصائص OfxRequestDocument ، يوفر API أيضًا فئات أخرى مثل [طلب التوقيع](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonrequest)و [مؤسسة مالية](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/financialinstitution) و [طلب معاملة كشف الحساب](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionrequest) الطبقات. وبالمثل ، لإضفاء الطابع الشخصي على خصائص OfxResponseDocument ، يوفر API فئات داعمة مثل [SignonResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse)و  [كشف المعاملة الاستجابة](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse) و [بيان المعاملة](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction). فيما يلي مقتطفات التعليمات البرمجية لكلتا الحالتين باستخدام الفئات المناسبة ذات الصلة.

{{% blocks/products/pf/feature-page-code h3="C# رمز لإنشاء OFX طلب المستندات" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# رمز لإنشاء OFX مستندات الاستجابة" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}