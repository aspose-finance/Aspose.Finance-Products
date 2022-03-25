---
title: التحقق من صحة التقارير المالية عبر .NET
url: /ar/net/validate/
description:  C# رمز للتحقق من صحة التقارير المالية في ملفات XBRL و iXBRL عبر مكتبة .NET.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="التحقق من صحة ملفات التقارير المالية عبر C#" h2="التحقق من صحة تنسيقات التقارير المالية بما في ذلك XBRL و iXBRL ضمن التطبيقات المستندة إلى .NET." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) هي ميزة غنية ، قابلة للتوسيع وسهلة الاستخدام معالجة التقارير المالية API. يمكن للمطورين تحميل أو التحقق من صحة أو عرض أو إنشاء تنسيقات XBRL و iXBRL للحلول المالية والتجارية. API يوفر [XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) الطبقة و  [InlineXbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) فئة لتحميل XBRL و iXBRL ملفات.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="التحقق من صحة الوثيقة XBRL" %}}

هناك حاجة إلى التحقق من صحة ملف XBRL لعدد من الحالات مثل التحقق من البيانات في الهيكل الصحيح والتنسيق. للتحقق من صحة مستندات XBLR ، استخدم أولاً فئة XbrlDocument لتحميل ملف XBRL. لاستخدام [التحقق من صحة ()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) طريقة من [XbrlInstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance) الطبقة ، أولا إضفاء الطابع [XbrlInstanceCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) مع XbrlDocument كائن XbrlIncances. Iterate من خلال كل [XbrlInstance. صحة الأخطاء](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/properties/validationerrors) للحصول على رمز الخطأ الصحيح والتصرف وفقًا لذلك عن طريق طباعة رسائل الخطأ المخصصة على وحدة التحكم أو الكتابة داخل ملف.

{{% blocks/products/pf/feature-page-code h3="C# كود للتحقق من صحة ملف XBRL" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-xbrl-file.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="التحقق من صحة الوثيقة iXBRL" %}}

للتحقق من صحة iXLRB ، قم بتحميله عبر [InlineXbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) فئة واستخدام طريقة التحقق من صحة (). في [قانون صحة التصديق](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.validator/validationerrorcode) يتم تحديد رموز الخطأ ، التحقق من الصحة لكل قاعدة التحقق من الصحة. عدد قليل من الرموز هي ContextPeriodNoStartTime و ContextPeriodNoEndTime و ContextPeriodStartAfterEnd و ContextInstantNoTime و ContextScenarioXbrlSubstitutionGroup وما إلى ذلك. يمكن للمطورين تصحيح الرموز وعرضها كما في المستخدمين النهائيين أو يمكنهم إظهار الاتجاه لحل المشكلة.

{{% blocks/products/pf/feature-page-code h3="C# رمز للتحقق من صحة الوثيقة iXBRL" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-ixbrl-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Validate" >}}