---
title: التحقق من صحة XBRL الملف عبر Python
description: نموذج رمز للتحقق من صحة ملف XBRL. استخدم API مثال التعليمات البرمجية للتحقق من صحة الملفات المجمعة XBRL داخل التطبيقات المستندة إلى Python. 
url: /ar/python-net/validate/xbrl/
family: finance
platformtag: python
feature: validate
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="التحقق من صحة XBRL الملفات عبر Python" h2="التحقق من صحة التقارير المالية بتنسيق XBRL دون الحاجة إلى تثبيت Microsoft Office أو أي برامج أخرى." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="كيفية التحقق من ملفات XBRL" %}}

اتبع الخطوات الموجودة في مقتطف الشفرة أو قم بتحسينه وفقًا لاحتياجات تطبيقك للتحقق من مستندات لغة إعداد التقارير التجارية الموسعة XBRL. تأكد من وجود متطلبات التحقق من صحة في التطبيق الخاص بك.

1. تحميل ملف XBRL باستخدام مثيل فئة XbrlDocument.2. للتحقق من صلاحية الملف الذي تم تحميله ، بحيث يتطابق مع [مواصفات XBRL](http://www.xbrl.org/specification/inlinexbrl-part1/rec-2013-11-18/inlinexbrl-part1-rec-2013-11-18.html)
3. للتحقق من الصلاحية ، استخدم طريقة التحقق من صحة فئة XbrlInstance.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحقق من الصحة" %}}
لمتابعة التحقق من مستندات XBRL ، تأكد من أن لديك المتطلبات الأساسية التالية. 
- نظام التشغيل Microsoft Windows أو Linux.- Python 3.5 أو أحدث.- Aspose.Finance لـ Python المشار إليها في مشروعك.{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python للتحقق من صحة ملفات XBRL" offSpacer="" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "validate-xbrl-instance-file.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="خيارات التحقق الأخرى" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/validate/ixbrl/" name="XBRL" description="لغة تقارير الأعمال القابلة للتوسيع المضمنة" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}