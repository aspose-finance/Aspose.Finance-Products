---
title: Python के माध्यम से OFX प्रतिक्रिया फ़ाइल बनाएं
description: OFX प्रतिक्रिया फ़ाइल निर्माण के लिए नमूना कोड। बैच के लिए API उदाहरण कोड का उपयोग करें OFX प्रतिक्रिया फ़ाइलें Python आधारित अनुप्रयोगों के भीतर उत्पन्न होती हैं। 
url: /hi/python-net/create/ofx-response/
family: finance
platformtag: python
feature: create
informat: OFX Response
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Python के माध्यम से OFX प्रतिक्रिया फ़ाइलें बनाएं" h2="OFX Microsoft Office स्थापित या किसी अन्य सॉफ़्टवेयर की आवश्यकता के बिना फ़ाइलों का निर्माण प्रतिक्रिया।" >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="OFX प्रतिसाद फ़ाइलें कैसे बनाएं" %}}

कोड स्निपेट में दिए गए चरणों का पालन करें या अपने एप्लिकेशन के भीतर निर्माण आवश्यकताओं को पूरा करने के बाद इसे अपनी एप्लिकेशन की आवश्यकताओं के अनुसार बढ़ाएं।

1. OfxResponseDocument क्लास ऑब्जेक्ट बनाएं।1. API द्वारा प्रदान किए गए विभिन्न वर्गों जैसे साइनऑनरिस्पॉन्स, स्टेटमेंटट्रांसेक्शनरिस्पॉन्स, स्टेटमेंटट्रांसेक्शन का उपयोग करके प्रासंगिक गुण असाइन करें1. सेव विधि में पैरामीटर के रूप में OfxVersionEnum से क्रमशः xml और sgml फ़ाइलों के लिए ofxVersion V2x या V1x का उपयोग करें।1. लक्ष्य फ़ाइल और ofxVersion प्रदान करके सेव विधि को कॉल करें।
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="निर्माण आवश्यकता" %}}
OFX प्रतिसाद फ़ाइल निर्माण के लिए आगे बढ़ने के लिए, सुनिश्चित करें कि आपके पास निम्नलिखित पूर्वापेक्षाएँ हैं। 
- माइक्रोसॉफ्ट विंडोज या लिनक्स आधारित ओएस।- Python 3.5 या बाद का।- आपके प्रोजेक्ट में संदर्भित Python के लिए Aspose.Finance।{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="OFX प्रतिसाद फ़ाइलों के निर्माण के लिए Python कोड" offSpacer="" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-response-files.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="अन्य निर्माण विकल्प" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/ofx-request/" name="OFX अनुरोध फ़ाइल" description="1.03 या 2.2 प्रारूप" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/xbrl/" name="XBRL फ़ाइल" description="एक्स्टेंसिबल बिजनेस रिपोर्टिंग लैंग्वेज" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}