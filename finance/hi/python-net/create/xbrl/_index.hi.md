---
title: Python के माध्यम से XBRL फ़ाइल बनाएं
description: XBRL फ़ाइल निर्माण के लिए नमूना कोड। बैच के लिए API उदाहरण कोड का उपयोग करें XBRL Python आधारित अनुप्रयोगों के भीतर फाइल निर्माण। 
url: /hi/python-net/create/xbrl/
family: finance
platformtag: python
feature: create
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Python के माध्यम से XBRL फ़ाइलें बनाएं" h2="XBRL Microsoft Office स्थापित या किसी अन्य सॉफ़्टवेयर की आवश्यकता के बिना फ़ाइलें बनाना।" >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="कैसे बनाएं XBRL फ़ाइलें" %}}

कोड स्निपेट में दिए गए चरणों का पालन करें या एक्स्टेंसिबल व्यावसायिक रिपोर्टिंग भाषा XBRL फ़ाइलें जेनरेट करने के लिए आपके एप्लिकेशन की आवश्यकता के अनुसार इसे बेहतर बनाएं। सुनिश्चित करें कि आपके आवेदन में निर्माण संबंधी आवश्यकताएं हैं।

1. XbrlDocument क्लास इंस्टेंस बनाएं।1. एक नया XBRL उदाहरण दस्तावेज़ बनाने के लिए XbrlInstanceCollection और XbrlInstance.1. SchemaRefCollection का उपयोग करके स्कीमा संदर्भ जोड़ें1. एप्लिकेशन प्रकृति के आधार पर संदर्भ, इकाई, आइटम, फुटनोट लिंक और बहुत कुछ जोड़ें।1. लक्ष्य फ़ाइल पथ प्रदान करके सहेजें विधि को कॉल करें।
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="निर्माण आवश्यकता" %}}
XBRL दस्तावेज़ बनाने के लिए आगे बढ़ने के लिए, सुनिश्चित करें कि आपके पास निम्नलिखित पूर्वापेक्षाएँ हैं। 
- माइक्रोसॉफ्ट विंडोज या लिनक्स आधारित ओएस।- Python 3.5 या बाद का।- आपके प्रोजेक्ट में संदर्भित Python के लिए Aspose.Finance।{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XBRL फ़ाइल निर्माण के लिए Python कोड" offSpacer="" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-xbrl-file-and-add-schema-reference.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="अन्य निर्माण विकल्प" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/ofx-request/" name="OFX अनुरोध" description="1.03 या 2.2 प्रारूप" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/ofx-response/" name="OFX प्रतिक्रिया" description="1.03 या 2.2 प्रारूप" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}