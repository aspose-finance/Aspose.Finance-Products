---
title: التحقق من صحة التقارير المالية عبر Python
url: /ar/python-net/validate/
description:  Python رمز للتحقق من صحة التقارير المالية في XBRL و iXBRL الملفات عبر مكتبة Python.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="التحقق من صحة ملفات التقارير المالية عبر Python" h2="التحقق من صحة تنسيقات التقارير المالية بما في ذلك XBRL و iXBRL داخل التطبيقات المستندة إلى Python." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance لـ Python عبر .NET](https://products.aspose.com/finance/python-net/) هي ميزة غنية وقابلة للتوسيع وسهلة الاستخدام لمعالجة التقارير المالية API. يمكن للمطورين بسهولة تحميل ، والتحقق من صحة ، وعرض أو إنشاء تنسيقات XBRL و iXBRL للحلول المالية والتجارية. يوفر API فئة XbrlDocument وفئة InlineXbrlDocument لتحميل ملفات XBRL و iXBRL.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="تحقق من صحة مستند XBRL" %}}

يلزم التحقق من صحة ملف XBRL لعدد من الحالات مثل التحقق من أن البيانات في الهيكل والتنسيق الصحيحين. للتحقق من صحة مستندات XBLR ، استخدم أولاً فئة XbrlDocument لتحميل ملف XBRL. لاستخدام طريقة التحقق من صحة فئة XbrlInstance ، قم أولاً بتهيئة XbrlInstanceCollection باستخدام كائن XbrlDocument XbrlInstances. كرر من خلال كل XbrlInstance.ValidationErors للحصول على رمز الخطأ الصحيح والتصرف وفقًا لذلك عن طريق طباعة رسائل الخطأ المخصصة على وحدة التحكم أو الكتابة داخل ملف.

{{% blocks/products/pf/feature-page-code h3="Python رمز للتحقق XBRL من الملف" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "validate-xbrl-instance-file.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="تحقق من صحة مستند iXBRL" %}}

للتحقق من صحة iXLRB ، قم بتحميله عبر فئة InlineXbrlDocument واستخدم طريقة التحقق () الخاصة به. في تعداد ValidationErrorCode ، يتم تحديد أكواد خطأ التحقق من الصحة لكل قاعدة تحقق من الصحة. قليل من الرموز هي ContextPeriodNoStartTime و ContextPeriodNoEndTime و ContextPeriodStartAfterEnd و ContextInstantNoTime و ContextScenarioXbrlNamespace و ContextScenarioXbrlSubstitutionGroup وما إلى ذلك.

{{% blocks/products/pf/feature-page-code h3="مستند Python رمز للتحقق iXBRL" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "validate-ixbrl-file.py" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Validate" >}}
{{< /blocks/products/pf/feature-page-wrap >}}