---
title: أنشئ OFX طلب ملف عبر Python
description: نموذج التعليمات البرمجية لـ OFX طلب إنشاء ملف. استخدم API رمز المثال للدفعة OFX لإنشاء ملفات الطلب داخل التطبيقات المستندة إلى Python. 
url: /ar/python-net/create/ofx-request/
family: finance
platformtag: python
feature: create
informat: OFX Request
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="أنشئ OFX طلب ملفات عبر Python" h2="OFX طلب إنشاء الملفات دون الحاجة إلى تثبيت Microsoft Office أو أي برامج أخرى." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="كيفية إنشاء OFX طلب الملفات" %}}

بعد الحصول على OFX طلب متطلبات إنشاء الملفات داخل تطبيقك ، اتبع الخطوات الواردة في مقتطف الشفرة أو قم بتحسينه وفقًا لمتطلباتك.

1. قم بإنشاء كائن فئة OfxRequestDocument.2. عيّن الخصائص ذات الصلة باستخدام الفئات المختلفة التي يوفرها API مثل SignonRequest و FinancialInstitution] و StatementTransactionRequest
3. استخدم ofxVersion V2x أو V1x لملفات xml و sgml على التوالي من OfxVersionEnum كمعامل في أسلوب الحفظ.
4. قم باستدعاء طريقة الحفظ بتوفير الملف الهدف و ofxVersion.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات الخلق" %}}
لمتابعة OFX طلب إنشاء ملف ، تأكد من أن لديك المتطلبات الأساسية التالية. 
- نظام التشغيل Microsoft Windows أو Linux.- Python 3.5 أو أحدث.- Aspose.Finance لـ Python المشار إليها في مشروعك.{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python رمز OFX طلب إنشاء الملفات" offSpacer="" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-request-files.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="خيارات الإنشاء الأخرى" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/ofx-response/" name="OFX ملف الاستجابة" description="تنسيق 1.03 أو 2.2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/xbrl/" name="XBRL ملف" description="لغة تقارير الأعمال الموسعة" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}