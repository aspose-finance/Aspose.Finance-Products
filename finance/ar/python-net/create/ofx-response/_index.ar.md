---
title: أنشئ OFX ملف استجابة عبر Python
description: نموذج كود لإنشاء ملف استجابة OFX. استخدم API رمز المثال لإنشاء ملفات استجابة الدُفعة OFX داخل التطبيقات المستندة إلى Python. 
url: /ar/python-net/create/ofx-response/
family: finance
platformtag: python
feature: create
informat: OFX Response
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="أنشئ OFX ملفات استجابة عبر Python" h2="إنشاء ملفات استجابة OFX بدون الحاجة إلى تثبيت Microsoft Office أو أي برامج أخرى." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="كيفية إنشاء OFX ملفات الاستجابة" %}}

اتبع الخطوات الموجودة في مقتطف الشفرة أو قم بتحسينه حسب احتياجات التطبيق بعد الحصول على متطلبات الإنشاء داخل التطبيق الخاص بك.

1. قم بإنشاء كائن فئة OfxResponseDocument.1. عيّن الخصائص ذات الصلة باستخدام الفئات المختلفة التي يوفرها API مثل SignonResponse و StatementTransactionResponse و StatementTransaction1. استخدم ofxVersion V2x أو V1x لملفات xml و sgml على التوالي من OfxVersionEnum كمعامل في طريقة الحفظ.1. قم باستدعاء طريقة الحفظ بتوفير الملف الهدف و ofxVersion.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات الخلق" %}}
لمتابعة إنشاء ملف الاستجابة OFX ، تأكد من توفر المتطلبات الأساسية التالية. 
- نظام التشغيل Microsoft Windows أو Linux.- Python 3.5 أو أحدث.- Aspose.Finance لـ Python المشار إليها في مشروعك.{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python رمز لإنشاء ملفات الاستجابة OFX" offSpacer="" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-response-files.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="خيارات الإنشاء الأخرى" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/ofx-request/" name="OFX طلب ملف" description="تنسيق 1.03 أو 2.2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/xbrl/" name="XBRL ملف" description="لغة تقارير الأعمال الموسعة" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}