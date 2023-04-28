---
title: إنشاء تقارير مالية عبر Python
url: /ar/python-net/create/
description:  Python لإنشاء تقارير مالية في XBRL ، و OFX طلب ملفات أو استجابة عبر مكتبة Python.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="إنشاء ملفات التقارير المالية عبر Python" h2="إنشاء تنسيقات التقارير المالية بما في ذلك XBRL و OFX ملف الطلب أو الاستجابة بتنسيق 1.03 أو 2.2 داخل التطبيقات المستندة إلى Python." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance لـ Python عبر .NET](https://products.aspose.com/finance/python-net/) هي ميزة غنية وقابلة للتوسيع وسهلة الاستخدام لإنشاء التقارير المالية ومعالجتها API. يمكن للمطورين إنشاء مثيل XBRL من البداية بسهولة بالإضافة إلى إضافة مرجع مخطط وسياق ووحدة وعنصر وارتباط حاشية سفلية ومرجع دور و 
مرجع دور القوس. يوفر API فئة ملائمة لكل ميزة مثل السياق ، يمكن للمطورين استخدام ContextPeriod و ContextEntity و Context. 
علاوة على ذلك ، يدعم API أيضًا إنشاء طلب / استجابة بتنسيق التبادل المالي المفتوح (OFX) بتنسيق 1.03 أو 2.2.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="قم بإنشاء ملف XBRL عن طريق إضافة عنصر" %}}

لإنشاء ملف XBRL وإضافة عنصر إلى المستند ، تكون العملية هي إنشاء مثيل فئة XbrlDocument. قم بإعداد الإعدادات ذات الصلة للعنصر باستخدام فئات API المناسبة مثل فئة SchemaRef وفئات السياق ذات الصلة كما هو مذكور أعلاه وفئة المفهوم. أخيرًا قم بتعريف خصائص فئة العنصر وتهيئتها وكذلك استدعاء طريقة الحفظ لإنشاء ملف XBRL في القرص.

{{% blocks/products/pf/feature-page-code h3="Python رمز لإنشاء XBRL ملف عن طريق إضافة عنصر" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-xbrl-file-and-add-item.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="قم بإنشاء OFX ملفات الطلبات والاستجابة" %}}


لإنشاء ملفات OFX ، يوفر API فئات OfxRequestDocument و OfxResponseDocument ويمكن للمطورين بسهولة [إنشاء OFX طلب](https://products.aspose.com/finance/python-net/create/ofx-request/) وملفات الاستجابة بتنسيقات 1.03 و 2.2. لتهيئة خصائص OfxRequestDocument ، يوفر API أيضًا فئات أخرى مثل فئات SignonRequest و FinancialInstitution و StatementTransactionRequest. وبالمثل ، لإضفاء الطابع الشخصي على خصائص OfxResponseDocument ، يوفر API فئات داعمة مثل SignonResponse و StatementTransactionResponse و StatementTransaction. فيما يلي مقتطفات التعليمات البرمجية لكلتا الحالتين باستخدام الفئات المناسبة ذات الصلة.

{{% blocks/products/pf/feature-page-code h3="Python رمز لإنشاء OFX طلب المستندات" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-response-files.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Python رمز لإنشاء OFX مستندات الاستجابة" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-response-files.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
{{< /blocks/products/pf/feature-page-wrap >}}