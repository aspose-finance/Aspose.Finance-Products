---
title: قراءة iXBRL ملف عبر C#
description: نموذج رمز لقراءة ملف iXBRL. استخدم API مثال التعليمات البرمجية لقراءة ملفات الدُفعات iXBRL داخل التطبيقات المستندة إلى .NET. 
url: /ar/net/read/ixbrl/
family: finance
platformtag: net
feature: read
informat: iXBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="قراءة iXBRL الملفات عبر C#" h2="قراءة التقارير المالية بتنسيق iXBRL دون الحاجة إلى تثبيت Microsoft Office أو أي برامج أخرى." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="كيف تقرأ ملفات iXBRL" %}}

اتبع الخطوات الموجودة في مقتطف الشفرة أو قم بتحسينه وفقًا لاحتياجات التطبيق لقراءة مستندات لغة إعداد التقارير التجارية الموسعة iXBRL. تأكد من وجود متطلبات القراءة في التطبيق الخاص بك.

1. خلق [فئة InlineXbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) مثال.1. قم بتمرير اسم ملف iXBRL صالح كمعامل.1. للحصول على التفاصيل الداخلية للملف ، استخدم الفئات ذات الصلة مثل [InlineFact](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinefact)و [سياق](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/context)و [وحدة](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/unit) 
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات القراءة" %}}
لمتابعة قراءة مستندات iXBRL ، فإن .NET Finance API هو المطلب الرئيسي الذي يجب تضمينه في التطبيق. 
- قم بتثبيته عبر سطر الأوامر كـ `` nuget install Aspose.Finance "" أو عبر Package Manager Console في Visual Studio مع `` Install-Package Aspose.Finance ''.
- بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [التحميلات](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# رمز لقراءة iXBRL من الملفات" offSpacer="" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "read-ixbrl-file.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="خيارات القراءة الأخرى" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/read/xbrl/" name="XBRL" description="لغة تقارير الأعمال الموسعة" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}