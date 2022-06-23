---
title: أنشئ OFX ملف استجابة عبر C#
description: نموذج كود لإنشاء ملف استجابة OFX. استخدم API رمز المثال لإنشاء ملفات استجابة الدُفعة OFX داخل التطبيقات المستندة إلى .NET. 
url: /ar/net/create/ofx-response/
family: finance
platformtag: net
feature: create
informat: OFX Response
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="أنشئ OFX ملفات استجابة عبر C#" h2="إنشاء ملفات استجابة OFX بدون الحاجة إلى تثبيت Microsoft Office أو أي برامج أخرى." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="كيفية إنشاء OFX ملفات الاستجابة" %}}

اتبع الخطوات الموجودة في مقتطف الشفرة أو قم بتحسينه حسب احتياجات التطبيق بعد الحصول على متطلبات الإنشاء داخل التطبيق الخاص بك.

1. خلق [فئة OfxResponseDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) هدف.1. عيّن الخصائص ذات الصلة باستخدام الفئات المختلفة المتوفرة بواسطة API like [SignonResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse)و  [كشف المعاملة الاستجابة](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse)و [بيان المعاملة](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction)1. استخدم ofxVersion V2x أو V1x لملفات xml و sgml على التوالي من [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) كمعلمة في طريقة الحفظ.1. اتصل ب [طريقة الحفظ](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument/methods/save) من خلال توفير الملف الهدف و ofxVersion.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات الخلق" %}}
لمتابعة OFX إنشاء ملف الاستجابة ، فإن .NET Finance API هو المطلب الرئيسي الذي يجب تضمينه في تطبيق إنشاء التقرير. 
- قم بتثبيته عبر سطر الأوامر كـ `` nuget install Aspose.Finance "" أو عبر Package Manager Console في Visual Studio مع `` Install-Package Aspose.Finance ''.
- بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [التحميلات](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# رمز لإنشاء ملفات الاستجابة OFX" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="خيارات الإنشاء الأخرى" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="OFX طلب ملف" description="تنسيق 1.03 أو 2.2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/xbrl/" name="XBRL ملف" description="لغة تقارير الأعمال الموسعة" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}