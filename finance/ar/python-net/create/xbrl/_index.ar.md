---
title: إنشاء XBRL ملف عبر Python
description: نموذج التعليمات البرمجية لإنشاء ملف XBRL. استخدم API مثال الكود لإنشاء ملفات الدُفعات XBRL داخل التطبيقات المستندة إلى Python. 
url: /ar/python-net/create/xbrl/
family: finance
platformtag: python
feature: create
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="إنشاء XBRL ملفات عبر Python" h2="XBRL من الملفات دون الحاجة إلى تثبيت Microsoft Office أو أي برامج أخرى." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="كيفية إنشاء ملفات XBRL" %}}

اتبع الخطوات الموجودة في مقتطف الشفرة أو قم بتحسينه وفقًا لاحتياجات تطبيقك لإنشاء ملفات لغة تقارير الأعمال الموسعة XBRL. تأكد من وجود متطلبات إنشاء داخل التطبيق الخاص بك.

1. قم بإنشاء مثيل فئة XbrlDocument.1. لإنشاء XBRL مستند مثيل جديد XbrlInstanceCollection و XbrlInstance.1. أضف مرجع المخطط باستخدام SchemaRefCollection1. اعتمادًا على طبيعة التطبيق ، أضف السياق والوحدة والعنصر وارتباط الحاشية السفلية والمزيد.1. قم باستدعاء طريقة الحفظ بتوفير مسار الملف الهدف.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات الخلق" %}}
لمتابعة إنشاء مستندات XBRL ، تأكد من أن لديك المتطلبات الأساسية التالية. 
- نظام التشغيل Microsoft Windows أو Linux.- Python 3.5 أو أحدث.- Aspose.Finance لـ Python المشار إليها في مشروعك.{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python رمز لإنشاء ملفات XBRL" offSpacer="" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-xbrl-file-and-add-schema-reference.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="خيارات الإنشاء الأخرى" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/ofx-request/" name="OFX طلب" description="تنسيق 1.03 أو 2.2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/ofx-response/" name="OFX الاستجابة" description="تنسيق 1.03 أو 2.2" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}