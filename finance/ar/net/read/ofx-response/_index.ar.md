---
title: قراءة ملف الاستجابة OFX عبر C#
description: نموذج رمز لقراءة ملف الاستجابة OFX. استخدم API مثال التعليمات البرمجية لقراءة ملفات استجابة الدُفعات OFX داخل التطبيقات المستندة إلى .NET. 
url: /ar/net/read/ofx-response/
family: finance
platformtag: net
feature: read
informat: OFX response
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="قراءة ملفات الردود OFX عبر C#" h2="قراءة التقارير المالية بتنسيق استجابة OFX دون الحاجة إلى تثبيت Microsoft Office أو أي برامج أخرى." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="كيف تقرأ ملفات استجابة OFX" %}}

اتبع الخطوات الموجودة في مقتطف الشفرة أو قم بتحسينه وفقًا لاحتياجات تطبيقك لقراءة ملفات استجابة OFX لغة إعداد التقارير التجارية الموسعة. تأكد من وجود متطلبات القراءة في التطبيق الخاص بك.

1. خلق [فئة OfxResponseDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) نموذج.1. قم بتمرير اسم ملف استجابة OFX صالح كمعامل.1. للحصول على التفاصيل الداخلية للملف ، استخدم الفئات ذات الصلة مثل [SignonResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات القراءة" %}}
لمتابعة قراءة مستندات الاستجابة OFX ، فإن .NET Finance API هو المطلب الرئيسي الذي يجب تضمينه في التطبيق. 
- قم بتثبيته عبر سطر الأوامر باسم "nuget install Aspose.Finance" أو عبر Package Manager Console في Visual Studio مع `` Install-Package Aspose.Finance ''.
- بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [التحميلات](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# رمز لقراءة ملفات الاستجابة OFX" offSpacer="" %}}

{{< gist "aspose-finance-gists" "01125f8901f4fde8dfd5c9764b59ef2f" "read-ofx-response.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="خيارات القراءة الأخرى" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/read/ixbrl/" name="iXBRL" description="لغة تقارير الأعمال القابلة للتوسيع المضمنة" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}