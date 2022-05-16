---
title: قراءة OFX طلب ملف عبر C#
description: نموذج التعليمات البرمجية لـ OFX طلب قراءة ملف. استخدم API مثال التعليمات البرمجية لقراءة ملفات الطلبات المجمعة OFX داخل التطبيقات المستندة إلى .NET. 
url: /ar/net/read/ofx-request/
family: finance
platformtag: net
feature: read
informat: OFX request
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="قراءة OFX طلب الملفات عبر C#" h2="قراءة التقارير المالية بتنسيق طلب OFX دون الحاجة إلى تثبيت Microsoft Office أو أي برامج أخرى." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="كيفية قراءة OFX طلب الملفات" %}}

اتبع الخطوات الواردة في مقتطف الشفرة أو قم بتحسينه وفقًا لاحتياجات التطبيق لقراءة ملفات طلب لغة إعداد التقارير التجارية الموسعة OFX. تأكد من وجود متطلبات القراءة في التطبيق الخاص بك.

1. خلق [فئة OfxRequestDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) نموذج.1. قم بتمرير اسم ملف طلب OFX صالح كمعامل.1. للحصول على التفاصيل الداخلية للملف ، استخدم الفئات ذات الصلة مثل [طلب التوقيع](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonrequest)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات القراءة" %}}
لمتابعة قراءة OFX طلب المستندات ، فإن .NET Finance API هو المطلب الرئيسي الذي يجب تضمينه في التطبيق. 
- قم بتثبيته عبر سطر الأوامر باسم "nuget install Aspose.Finance" أو عبر Package Manager Console في Visual Studio مع `` Install-Package Aspose.Finance ''.
- بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [التحميلات](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# رمز لقراءة OFX طلب الملفات" offSpacer="" %}}

{{< gist "aspose-finance-gists" "e402ec71f2ad51f0fee413fa1a91945f" "read-ofx-request.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="خيارات القراءة الأخرى" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/read/ixbrl/" name="iXBRL" description="لغة تقارير الأعمال القابلة للتوسيع المضمنة" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}