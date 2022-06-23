---
title: إنشاء XBRL ملف عبر C#
description: نموذج التعليمات البرمجية لإنشاء ملف XBRL. استخدم API مثال الكود لإنشاء ملفات الدُفعات XBRL داخل التطبيقات المستندة إلى .NET. 
url: /ar/net/create/xbrl/
family: finance
platformtag: net
feature: create
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="إنشاء XBRL ملفات عبر C#" h2="XBRL من الملفات دون الحاجة إلى تثبيت Microsoft Office أو أي برامج أخرى." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="كيفية إنشاء ملفات XBRL" %}}

اتبع الخطوات الموجودة في مقتطف الشفرة أو قم بتحسينه وفقًا لاحتياجات تطبيقك لإنشاء ملفات لغة تقارير الأعمال الموسعة XBRL. تأكد من وجود متطلبات إنشاء داخل التطبيق الخاص بك.

1. خلق [فئة XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) مثال.1. لإنشاء مستند مثيل XBRL جديد [XbrlInstanceCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) و [XbrlInstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance).1. أضف مرجع المخطط باستخدام [مجموعة المخططات](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemarefcollection)1. اعتمادًا على طبيعة التطبيق ، أضف السياق والوحدة والعنصر وارتباط الحاشية السفلية والمزيد.1. اتصل ب [طريقة الحفظ](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) من خلال توفير مسار الملف الهدف.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات الخلق" %}}
للمتابعة من أجل XBRL إنشاء المستندات ، فإن .NET Finance API هو المطلب الرئيسي الذي يجب تضمينه في التطبيق. 
- قم بتثبيته عبر سطر الأوامر كـ `` nuget install Aspose.Finance "" أو عبر Package Manager Console في Visual Studio مع `` Install-Package Aspose.Finance ''.
- بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [التحميلات](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# رمز لإنشاء ملفات XBRL" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-schema-reference.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="خيارات الإنشاء الأخرى" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="OFX طلب" description="تنسيق 1.03 أو 2.2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-response/" name="OFX الاستجابة" description="تنسيق 1.03 أو 2.2" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}