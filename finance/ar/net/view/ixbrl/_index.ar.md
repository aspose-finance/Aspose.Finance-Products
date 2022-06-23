---
title: عرض iXBRL ملف عبر C#
description: نموذج كود لعرض ملف iXBRL. استخدم API مثال التعليمات البرمجية لعرض ملفات الدُفعات iXBRL ضمن التطبيقات المستندة إلى .NET. 
url: /ar/net/view/ixbrl/
family: finance
platformtag: net
feature: view
informat: iXBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="عرض ملفات iXBRL عبر C#" h2="عرض التقارير المالية بتنسيق iXBRL دون الحاجة إلى تثبيت Microsoft Office أو أي برامج أخرى." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="كيفية عرض ملفات iXBRL" %}}

اتبع الخطوات الموجودة في مقتطف الشفرة أو قم بتحسينه وفقًا لاحتياجات تطبيقك لعرض مستندات iXBRL لغة تقارير الأعمال الموسعة. تأكد من وجود متطلبات القراءة في التطبيق الخاص بك.

1. خلق [فئة InlineXbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) مثال.2. قم بتمرير اسم ملف iXBRL صالح كمعامل.
3. للحصول على التفاصيل الداخلية للملف ، استخدم الفئات ذات الصلة مثل [InlineFact](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinefact)و [سياق](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/context)و [وحدة](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/unit) 
4. إظهار هذه المعلومات

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات القراءة" %}}
لمتابعة عرض مستندات iXBRL ، فإن .NET Finance API هو المطلب الرئيسي الذي يجب تضمينه في التطبيق. 
- قم بتثبيته عبر سطر الأوامر كـ `` nuget install Aspose.Finance "" أو عبر Package Manager Console في Visual Studio مع `` Install-Package Aspose.Finance ''.
- بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [التحميلات](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# رمز لقراءة iXBRL من الملفات" offSpacer="" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "read-ixbrl-file.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="خيارات العرض الأخرى" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/view/xbrl/" name="XBRL" description="لغة تقارير الأعمال الموسعة" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}