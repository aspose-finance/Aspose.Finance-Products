---
title: قراءة XBRL ملف عبر C#
description: نموذج رمز لقراءة ملف XBRL. استخدم API مثال التعليمات البرمجية لقراءة ملفات الدُفعات XBRL داخل التطبيقات المستندة إلى .NET. 
url: /ar/net/read/xbrl/
family: finance
platformtag: net
feature: read
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="قراءة XBRL الملفات عبر C#" h2="قراءة التقارير المالية بتنسيق XBRL دون الحاجة إلى تثبيت Microsoft Office أو أي برامج أخرى." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="كيف تقرأ ملفات XBRL" %}}

اتبع الخطوات الواردة في مقتطف الشفرة أو قم بتحسينه وفقًا لاحتياجات التطبيق لقراءة ملفات لغة إعداد التقارير التجارية الموسعة XBRL. تأكد من وجود متطلبات القراءة في التطبيق الخاص بك.

1. خلق [فئة XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) مثال.1. قم بتمرير اسم ملف XBRL صالح كمعامل.1. للحصول على التفاصيل الداخلية للملف ، استخدم الفئات ذات الصلة مثل [مجموعة المخططات](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemarefcollection)و [سياق](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/context)و [وحدة](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/unit) 
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات القراءة" %}}
لمتابعة قراءة مستندات XBRL ، فإن .NET Finance API هو المطلب الرئيسي الذي يجب تضمينه في التطبيق. 
- قم بتثبيته عبر سطر الأوامر كـ `` nuget install Aspose.Finance "" أو عبر Package Manager Console في Visual Studio مع `` Install-Package Aspose.Finance ''.
- بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [التحميلات](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# رمز لقراءة XBRL من الملفات" offSpacer="" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "read-xbrl-file.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="خيارات القراءة الأخرى" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/read/ixbrl/" name="iXBRL" description="لغة تقارير الأعمال القابلة للتوسيع المضمنة" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}