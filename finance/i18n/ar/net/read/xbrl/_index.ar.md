---
title: قراءة XBRL ملف عبر C#
description: رمز عينة لقراءة الملفات XBRL. استخدم API كود سبيل المثال لقراءة ملفات دفعة XBRL داخل .NET تطبيقات قائمة. 
url: /ar/net/read/xbrl/
family: finance
platformtag: net
feature: read
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="قراءة XBRL من الملفات عبر C#" h2="قراءة التقارير المالية بتنسيق XBRL دون الحاجة إلى تثبيت Microsoft Office أو أي برامج أخرى." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="كيفية قراءة ملفات XBRL" %}}

اتبع الخطوات الواردة في مقتطف التعليمات البرمجية أو قم بتعزيزها وفقًا لاحتياجات التطبيق لقراءة ملفات لغة تقارير الأعمال القابلة للتوسيع XBRL. تأكد من وجود متطلبات القراءة داخل التطبيق الخاص بك.

1. إنشاء [فئة XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) المثبت.1. مرر اسم ملف XBRL صالح كمعلمة.1. للحصول على التفاصيل الداخلية للملف ، استخدم الفئات ذات الصلة مثل [SchemaRefCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemarefcollection)، [السياق](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/context)، [الوحدة](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/unit) 
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات القراءة" %}}
للمضي قدمًا في قراءة مستندات XBRL ، فإن .NET Finance API هو الشرط الرئيسي الذي يجب تضمينه في التطبيق. 
- قم بتثبيته عبر سطر الأوامر على أنه ''nuget install Aspose.Finance'' أو عبر Package Manager Console of Visual Studio مع '''' تثبيت-حزمة Aspose.Finance''.
- بدلاً من ذلك ، احصل على مثبت MSI أو DLLs غير المتصل بالإنترنت في ملف ZIP من [التنزيلات](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# كود لقراءة ملفات XBRL" offSpacer="" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "read-xbrl-file.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="خيارات القراءة الأخرى" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/read/ixbrl/" name="iXBRL" description="لغة الإبلاغ عن الأعمال القابلة للتمديد" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}