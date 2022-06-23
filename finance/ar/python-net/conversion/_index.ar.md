---
title: تحويل التقارير المالية عبر Python
url: /ar/python-net/conversion/
description:  Python رمز لتحويل التقارير المالية بتنسيق XBRL و iXBRL (inline xbrl) و OFX fomats عبر مكتبة Python.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="تحويل ملفات التقارير المالية عبر Python" h2="تنسيقات التقارير المالية التحويل بما في ذلك تنسيق XBRL و iXBRL و OFX من 1.03 إلى 2.2 داخل التطبيقات المستندة إلى Python." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance لـ Python عبر .NET](https://products.aspose.com/finance/python-net/) هي ميزة غنية وقابلة للتوسيع وسهلة الاستخدام API. يمكن للمطورين بسهولة التحقق من صحة XBRL مثيلات وقواعد الروابط ومخططات التصنيف باستخدام طريقة التحقق من الصحة () التي يجب أن تتوافق مع متطلبات بناء الجملة المفروضة في المواصفات. علاوة على ذلك ، يمكنهم قراءة تنسيقات XBRL و iXBRL وإنشاء مثيل XBRL من البداية. علاوة على ذلك ، يمكنهم ** تحويل XBRL تنسيق ** إلى iXBRL وملفات Microsoft Excel XLSX. يدعم API أيضًا إنشاء طلب / استجابة بتنسيق التبادل المالي المفتوح (OFX) ويحول طلب / استجابة ملف OFX من تنسيق 1.03 إلى 2.2.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="تحويل OFX ملفات الاستجابة والطلب" %}}

يدعم API إنشاء OFX ملفات الطلبات والاستجابة من خلال توفير فئتين. OfxRequestDocument لإنشاء وتحميل OFX طلب الملفات بتنسيق 1.03 و 2.2 و OfxResponseDocument OFX لملفات الاستجابة بتنسيق 1.03 و 2.2. Futhermore ، تعداد OfxVersionEnum به أعضاء V1x إصدار 1.x ، تنسيق ملف sgml وإصدار V2x 2.x ، تنسيق ملف xml. بعد استدعاء طريقة الحفظ لفئة OfxRequestDocument أو فئة OfxResponseDocument ، يمكن للمطورين بسهولة التحويل من ملف 1.03 sgml إلى تنسيق 2.2 xml.


{{% blocks/products/pf/feature-page-code h3="C# رمز لتحويل OFX ملفات الاستجابة" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-ofx-response-from-1.03-to-2.2.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# رمز لتحويل OFX طلب الملفات" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-ofx-request-from-1.03-to-2.2.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="XBRL تحويل التقارير المالية" %}}

يدعم API تحويل الملفات XBRL إلى تنسيق Microsoft® Excel XLSX iXBRL. عملية التحويل بسيطة ، أولاً قم بتحميل الملف عبر XbrlDocument Class. استخدم فئة SaveOptions لـ SaveFormat ، لاستخدامها كمعلمة في أسلوب الحفظ لفئة XbrlDocument. للحفظ في ملف iXBLR ، سيتم استخدام SaveFormat.IXBRL وللتصدير إلى تنسيق XLSX ، سيتم استخدام SaveFormat.XLSX.

{{% blocks/products/pf/feature-page-code h3="Python رمز للتصدير XBRL إلى iXBRL" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-xbrl-to-ixbrl.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Python رمز XBRL لتحويل XLSX" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-xbrl-to-xlsx.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xbrl-to-ixbrl xbrl-to-xlsx" >}}