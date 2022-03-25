---
title: التحقق من صحة XBRL ملف عبر C#
description: نموذج رمز للتحقق من صحة الملف XBRL. استخدم API كود سبيل المثال للتحقق من صحة ملفات الدفعات XBRL داخل .NET. 
url: /ar/net/validate/xbrl/
family: finance
platformtag: net
feature: validate
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="التحقق من صحة XBRL من الملفات عبر C#" h2="التحقق من صحة التقارير المالية بتنسيق XBRL دون الحاجة إلى تثبيت Microsoft Office أو أي برامج أخرى." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="كيفية التحقق من صحة ملفات XBRL" %}}

اتبع الخطوات الواردة في مقتطف التعليمات البرمجية أو قم بتعزيزها وفقًا لاحتياجات التطبيق الخاصة بك للتحقق من مستندات لغة الإبلاغ التجارية القابلة للتوسيع XBRL. تأكد من وجود متطلبات التحقق في التطبيق الخاص بك.

1. تحميل XBRL ملف باستخدام [فئة XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) المثبت.1. للتحقق من صحة الملف المحمّل ، بحيث يجب أن يتطابق مع [XBRL مواصفات](http://www.xbrl.org/specification/inlinexbrl-part1/rec-2013-11-18/inlinexbrl-part1-rec-2013-11-18.html)1. للتحقق من صحة ، استخدم [التحقق من صحة ()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) طريقة من [XbrlInstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance) الطبقة.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحقق" %}}
للمضي قدمًا في التحقق من صحة مستندات XBRL ، فإن .NET Finance API هو الشرط الرئيسي الذي يجب تضمينه في التطبيق. 
- قم بتثبيته عبر سطر الأوامر على أنه ''nuget install Aspose.Finance'' أو عبر Package Manager Console of Visual Studio مع '''' تثبيت-حزمة Aspose.Finance''.
- بدلاً من ذلك ، احصل على مثبت MSI أو DLLs غير المتصل بالإنترنت في ملف ZIP من [التنزيلات](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# كود للتحقق من صحة ملفات XBRL" offSpacer="" %}}

{{< gist "aspose-com-gists" "1272da1f804f8cef122600269db09fbb" "validate-xbrl-instance-file.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="خيارات التحقق الأخرى" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/validate/ixbrl/" name="XBRL" description="لغة الإبلاغ عن الأعمال القابلة للتمديد" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}