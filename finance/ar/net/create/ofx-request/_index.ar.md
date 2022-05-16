---
title: أنشئ OFX طلب ملف عبر C#
description: نموذج التعليمات البرمجية لـ OFX طلب إنشاء ملف. استخدم API رمز المثال للدفعة OFX لإنشاء ملفات الطلب داخل التطبيقات المستندة إلى .NET. 
url: /ar/net/create/ofx-request/
family: finance
platformtag: net
feature: create
informat: OFX Request
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="أنشئ OFX طلب ملفات عبر C#" h2="OFX طلب إنشاء الملفات دون الحاجة إلى تثبيت Microsoft Office أو أي برامج أخرى." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="كيفية إنشاء OFX طلب الملفات" %}}

بعد الحصول على OFX طلب متطلبات إنشاء الملفات داخل تطبيقك ، اتبع الخطوات الواردة في مقتطف الشفرة أو قم بتحسينه وفقًا لمتطلباتك.

1. خلق [فئة OfxRequestDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) هدف.1. عيّن الخصائص ذات الصلة باستخدام الفئات المختلفة المتوفرة بواسطة API like [طلب التوقيع](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonrequest)و [مؤسسة مالية](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/financialinstitution)و [طلب معاملة كشف الحساب](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionrequest)1. استخدم ofxVersion V2x أو V1x لملفات xml و sgml على التوالي من [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) كمعلمة في طريقة الحفظ.1. اتصل ب [طريقة الحفظ](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument/methods/save) من خلال توفير الملف الهدف و ofxVersion.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات الخلق" %}}
لمتابعة OFX طلب إنشاء ملف ، فإن .NET Finance API هو المطلب الرئيسي الذي يجب تضمينه في تطبيق إنشاء التقرير. 
- قم بتثبيته عبر سطر الأوامر باسم "nuget install Aspose.Finance" أو عبر Package Manager Console في Visual Studio مع `` Install-Package Aspose.Finance ''.
- بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [التحميلات](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# رمز OFX طلب إنشاء الملفات" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-request-files.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="خيارات الإنشاء الأخرى" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-response/" name="OFX ملف الاستجابة" description="تنسيق 1.03 أو 2.2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/xbrl/" name="XBRL ملف" description="لغة تقارير الأعمال الموسعة" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}