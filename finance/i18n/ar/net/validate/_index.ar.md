---
title: التحقق من صحة التقارير المالية عبر .NET
url: /ar/net/validate/
description:  C# رمز للتحقق من صحة التقارير المالية في XBRL و iXBRL الملفات عبر مكتبة .NET.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="التحقق من صحة ملفات التقارير المالية عبر C#" h2="التحقق من صحة تنسيقات التقارير المالية بما في ذلك XBRL و iXBRL داخل التطبيقات المستندة إلى .NET." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) هي ميزة غنية وقابلة للتوسيع وسهلة الاستخدام لمعالجة التقارير المالية API. يمكن للمطورين بسهولة تحميل ، والتحقق من صحة ، وعرض أو إنشاء تنسيقات XBRL و iXBRL للحلول المالية والتجارية. API يقدم [Xbrl وثيقة](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) فئة و  [InlineXbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) فئة لتحميل ملفات XBRL و iXBRL.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="تحقق من صحة مستند XBRL" %}}

يلزم التحقق من صحة ملف XBRL لعدد من الحالات مثل التحقق من أن البيانات في الهيكل والتنسيق الصحيحين. للتحقق من صحة مستندات XBLR ، استخدم أولاً فئة XbrlDocument لتحميل ملف XBRL. لاستخدام ال [التحقق من صحة ()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) طريقة [XbrlInstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance) الطبقة ، أولاً قم بتهيئة ملف [XbrlInstanceCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) باستخدام XbrlDocument object XbrlInstances. كرر من خلال كل [XbrlInstance.ValidationErrors](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/properties/validationerrors) للحصول على رمز الخطأ الصحيح والتصرف وفقًا لذلك عن طريق طباعة رسائل الخطأ المخصصة على وحدة التحكم أو الكتابة داخل ملف.

{{% blocks/products/pf/feature-page-code h3="C# رمز للتحقق XBRL من الملف" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-xbrl-file.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="تحقق من صحة مستند iXBRL" %}}

للتحقق من صحة iXLRB ، قم بتحميله عبر [InlineXbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) class واستخدام طريقة Validate () الخاصة بها. في [ValidationErrorCode](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.validator/validationerrorcode) التعداد ، يتم تحديد رموز خطأ التحقق من الصحة لكل قاعدة التحقق من الصحة. قليل من الرموز هي ContextPeriodNoStartTime و ContextPeriodNoEndTime و ContextPeriodStartAfterEnd و ContextInstantNoTime و ContextScenarioXbrlNamespace و ContextScenarioXbrlSubstitutionGroup وما إلى ذلك.

{{% blocks/products/pf/feature-page-code h3="مستند C# رمز للتحقق iXBRL" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-ixbrl-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Validate" >}}