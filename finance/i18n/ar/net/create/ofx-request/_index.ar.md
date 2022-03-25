---
title: إنشاء OFX طلب ملف عبر C#
description: نموذج رمز لإنشاء ملف طلب OFX. استخدم API رمز سبيل المثال لدفعة OFX توليد ملفات الطلب داخل .NET. 
url: /ar/net/create/ofx-request/
family: finance
platformtag: net
feature: create
informat: OFX Request
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="إنشاء OFX طلب ملفات عبر C#" h2="OFX طلب إنشاء ملفات دون الحاجة إلى تثبيت Microsoft Office أو أي برنامج آخر." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="كيفية إنشاء OFX طلب الملفات" %}}

بعد الحصول على OFX متطلبات إنشاء الملفات داخل التطبيق الخاص بك ، اتبع الخطوات الواردة في مقتطف التعليمات البرمجية أو قم بتعزيزها وفقًا لمتطلباتك.

1. إنشاء [فئة OfxRequestDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) الكائن.1. تعيين الخصائص ذات الصلة باستخدام فئات مختلفة تقدمها API مثل [SignonRequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonrequest)، [المؤسسة المالية](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/financialinstitution)، [طلب معاملات البيانات](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionrequest)1. استخدم ofxVersion V2x أو V1x لملفات xml و sgml على التوالي من [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) كمعلمة في طريقة حفظ.1. استدعاء [حفظ طريقة](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument/methods/save) من خلال توفير الملف الهدف و ofxVersion.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات الخلق" %}}
للمتابعة لـ OFX إنشاء ملف الطلب ، فإن .NET Finance API هو المطلب الرئيسي الذي يجب تضمينه في تطبيق توليد التقارير. 
- قم بتثبيته عبر سطر الأوامر على أنه ''nuget install Aspose.Finance'' أو عبر Package Manager Console of Visual Studio مع '''' تثبيت-حزمة Aspose.Finance''.
- بدلاً من ذلك ، احصل على مثبت MSI أو DLLs غير المتصل بالإنترنت في ملف ZIP من [التنزيلات](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# كود لإنشاء ملفات طلب OFX" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-request-files.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="خيارات إنشاء أخرى" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-response/" name="OFX ملف الاستجابة" description="1.03 أو 2.2 شكل" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/xbrl/" name="XBRL ملف" description="لغة الإبلاغ عن الأعمال القابلة للتمديد" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}