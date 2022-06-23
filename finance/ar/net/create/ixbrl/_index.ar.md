---
title: إنشاء ملف iXBRL (xbrl مضمّن) عبر C#
description: نموذج التعليمات البرمجية لإنشاء ملف iXBRL (xbrl). استخدم API رمز المثال لإنشاء ملفات الدُفعات iXBRL (inline xbrl) داخل التطبيقات المستندة إلى .NET. 
url: /ar/net/create/ixbrl/
family: finance
platformtag: net
feature: create
informat: iXBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="إنشاء ملفات iXBRL (xbrl مضمنة) عبر C#" h2="iXBRL إنشاء ملفات (xbrl مضمنة) دون الحاجة إلى تثبيت Microsoft Office أو أي برامج أخرى." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="كيفية إنشاء ملفات iXBRL (inline xbrl)" %}}

اتبع الخطوات الموجودة في مقتطف الشفرة أو قم بتحسينه وفقًا لاحتياجات تطبيقك لإنشاء ملفات لغة تقارير الأعمال الموسعة iXBRL (inline xbrl). تأكد من وجود متطلبات إنشاء داخل التطبيق الخاص بك.

1. خلق [فئة InlineXbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) مثال.2. بناء عنصر دوم شجرة
3. استدعاء [طريقة الحفظ](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline.inlinexbrldocument/save/methods/1) من خلال توفير مسار الملف الهدف.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات الخلق" %}}
لمتابعة إنشاء مستندات iXBRL (xbrl) ، فإن .NET Finance API هو المطلب الرئيسي الذي يجب تضمينه في التطبيق. 
- قم بتثبيته عبر سطر الأوامر كـ `` nuget install Aspose.Finance "" أو عبر Package Manager Console في Visual Studio مع `` Install-Package Aspose.Finance ''.
- بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [التحميلات](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# رمز لإنشاء ملفات XBRL" offSpacer="" %}}

{{< gist "aspose-finance-gists" "e4ec79e68a0658a63611ae321b110a48" "create-ixbrl.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="خيارات الإنشاء الأخرى" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="OFX طلب" description="تنسيق 1.03 أو 2.2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-response/" name="OFX الاستجابة" description="تنسيق 1.03 أو 2.2" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}