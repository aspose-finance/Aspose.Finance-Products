---
title: إنشاء XBRL ملف عبر C#
description: نموذج رمز لإنشاء ملف XBRL. استخدم API رمز سبيل المثال لتوليد ملفات batch XBRL داخل .NET تطبيقات قائمة. 
url: /ar/net/create/xbrl/
family: finance
platformtag: net
feature: create
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="إنشاء XBRL ملفات عبر C#" h2="XBRL إنشاء ملفات بدون الحاجة إلى تثبيت Microsoft Office أو أي برنامج آخر." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="كيفية إنشاء XBRL ملفات" %}}

اتبع الخطوات الواردة في مقتطف التعليمات البرمجية أو قم بتعزيزها وفقًا لاحتياجات التطبيق الخاصة بك لإنشاء ملفات XBRL. تأكد من وجود متطلبات إنشاء داخل التطبيق الخاص بك.

1. إنشاء [فئة XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) المثبت.1. لإنشاء مستند مثيل XBRL جديد [XbrlInstanceCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) و [XbrlInstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance).1. إضافة إشارة مخطط باستخدام [SchemaRefCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemarefcollection)1. اعتمادًا على طبيعة التطبيق ، أضف السياق والوحدة والبند ووصلة الحاشية والمزيد.1. استدعاء [حفظ طريقة](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) من خلال توفير مسار الملف المستهدف.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات الخلق" %}}
للمضي قدمًا في إنشاء XBRL من المستندات ، فإن .NET Finance API هو الشرط الرئيسي الذي يجب تضمينه في التطبيق. 
- قم بتثبيته عبر سطر الأوامر على أنه ''nuget install Aspose.Finance'' أو عبر Package Manager Console of Visual Studio مع '''' تثبيت-حزمة Aspose.Finance''.
- بدلاً من ذلك ، احصل على مثبت MSI أو DLLs غير المتصل بالإنترنت في ملف ZIP من [التنزيلات](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# كود لإنشاء ملفات XBRL" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-schema-reference.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="خيارات إنشاء أخرى" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="OFX طلب" description="1.03 أو 2.2 شكل" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-response/" name="OFX استجابة" description="1.03 أو 2.2 شكل" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}