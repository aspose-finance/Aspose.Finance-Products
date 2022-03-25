---
title: إنشاء OFX ملف استجابة عبر C#
description: نموذج رمز لإنشاء ملف استجابة OFX. استخدم API كود سبيل المثال لتوليد ملفات استجابة دفعة OFX داخل .NET تطبيقات قائمة. 
url: /ar/net/create/ofx-response/
family: finance
platformtag: net
feature: create
informat: OFX Response
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="إنشاء OFX ملفات استجابة عبر C#" h2="OFX إنشاء ملفات استجابة دون الحاجة إلى تثبيت Microsoft Office أو أي برنامج آخر." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="كيفية إنشاء OFX ملفات استجابة" %}}

اتبع الخطوات الواردة في مقتطف التعليمات البرمجية أو تحسينه حسب احتياجات التطبيق الخاص بك بعد الحصول على متطلبات الإنشاء داخل التطبيق الخاص بك.

1. إنشاء [فئة OfxResponseDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) الكائن.1. تعيين الخصائص ذات الصلة باستخدام فئات مختلفة تقدمها API مثل [SignonResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse)،  [الاستجابة لعملات البيانات](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse)، [3-المعاملات الثالثية](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction)1. استخدم ofxVersion V2x أو V1x لملفات xml و sgml على التوالي من [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) كمعلمة في طريقة حفظ.1. استدعاء [حفظ طريقة](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument/methods/save) من خلال توفير الملف الهدف و ofxVersion.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات الخلق" %}}
للمضي قدمًا في إنشاء ملف استجابة OFX ، فإن .NET Finance API هو المطلب الرئيسي الذي يجب تضمينه في تطبيق توليد التقارير. 
- قم بتثبيته عبر سطر الأوامر على أنه ''nuget install Aspose.Finance'' أو عبر Package Manager Console of Visual Studio مع '''' تثبيت-حزمة Aspose.Finance''.
- بدلاً من ذلك ، احصل على مثبت MSI أو DLLs غير المتصل بالإنترنت في ملف ZIP من [التنزيلات](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# كود لإنشاء ملفات الاستجابة OFX" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="خيارات إنشاء أخرى" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="OFX طلب ملف" description="1.03 أو 2.2 شكل" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/xbrl/" name="XBRL ملف" description="لغة الإبلاغ عن الأعمال القابلة للتمديد" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}