---
title: إنشاء تقارير مالية عبر .NET
url: /ar/net/create/
description:  C# رمز لإنشاء تقارير مالية في XBRL ، و OFX طلب أو استجابة عبر .NET مكتبة.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="إنشاء ملفات التقارير المالية عبر C#" h2="إنشاء تنسيقات التقارير المالية بما في ذلك XBRL و OFX ملف الطلب أو الرد بتنسيق 1.03 أو 2.2 داخل .NET." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) هي ميزة غنية ، قابلة للتوسيع وسهلة الاستخدام إنشاء التقارير المالية ومعالجتها API. يمكن للمطورين إنشاء XBRL بسهولة من الصفر بالإضافة إلى إضافة مرجع المخطط والسياق والوحدة والعنصر ووصلة الحاشية ومرجعية الدور و 
مرجع دور القوس. يوفر API فئة ذات صلة لكل ميزة مثل السياق ، ويمكن للمطورين استخدامها [الفترة الزمنية](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextperiod)، [ContextEntity](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextentity) و [السياق](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/context). 
علاوة على ذلك ، يدعم API أيضًا إنشاء طلب/استجابة فتح (OFX) تنسيق طلب/استجابة بتنسيق 1.03 أو 2.2.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="إنشاء XBRL ملف عن طريق إضافة عنصر" %}}

لإنشاء ملف XBRL وإضافة عنصر إلى المستند ، فإن العملية هي إنشاء [فئة XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) سبيل المثال. قم بإعداد الإعدادات ذات الصلة للعنصر باستخدام فئات API المناسبة مثل [فئة SchemaRef](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemaref)، فئات السياق ذات الصلة كما ذكر أعلاه و [فئة المفهوم](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/concept). وأخيرا تحديد وتقنين [فئة البند](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/item) خصائص وكذلك استدعاء [حفظ طريقة](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) ل [إنشاء XBRL](https://products.aspose.com/finance/net/create/xbrl/) ملف في القرص.

{{% blocks/products/pf/feature-page-code h3="C# كود لإنشاء ملف XBRL عن طريق إضافة عنصر" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-item.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="إنشاء OFX ملفات الطلب والاستجابة" %}}


لإنشاء ملفات OFX ، يوفر API [OfxRequestDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) و [OfxResponseDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) يمكن للفصول والمطورين بسهولة [إنشاء OFX طلب](https://products.aspose.com/finance/net/create/ofx-request/) وملفات الاستجابة في كل من الأشكال 1.03 و 2.2. لتهيئة خصائص OfxRequestDocument ، يوفر API أيضًا فئات أخرى مثل [SignonRequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonrequest)، [المؤسسة المالية](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/financialinstitution) و [طلب معاملات البيانات](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionrequest) الطبقات. وبالمثل ، من أجل تقنين خصائص OfxResponseDocument ، يوفر API فئات داعمة مثل [SignonResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse)،  [الاستجابة لعملات البيانات](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse) و [3-المعاملات الثالثية](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction). فيما يلي قصاصات التعليمات البرمجية لكلتا الحالتين مع استخدام الفئات المناسبة ذات الصلة.

{{% blocks/products/pf/feature-page-code h3="C# رمز لتوليد OFX وثائق طلب" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# رمز لتوليد OFX وثائق استجابة" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}