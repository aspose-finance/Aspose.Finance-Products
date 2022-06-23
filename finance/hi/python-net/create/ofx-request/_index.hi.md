---
title: Python के माध्यम से OFX अनुरोध फ़ाइल बनाएं
description: OFX अनुरोध फ़ाइल निर्माण के लिए नमूना कोड। बैच के लिए API उदाहरण कोड का उपयोग करें OFX Python आधारित अनुप्रयोगों के भीतर फाइल निर्माण का अनुरोध करें। 
url: /hi/python-net/create/ofx-request/
family: finance
platformtag: python
feature: create
informat: OFX Request
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Python के माध्यम से OFX अनुरोध फ़ाइलें बनाएं" h2="OFX Microsoft Office स्थापित या किसी अन्य सॉफ़्टवेयर की आवश्यकता के बिना फ़ाइल निर्माण का अनुरोध करें।" >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="कैसे बनाएं OFX अनुरोध फ़ाइलें" %}}

आपके आवेदन में OFX अनुरोध फ़ाइलें बनाने की आवश्यकताएं होने के बाद, कोड स्निपेट में दिए गए चरणों का पालन करें या अपनी आवश्यकता के अनुसार इसे बेहतर बनाएं।

1. OfxRequestDocument क्लास ऑब्जेक्ट बनाएं।2. API द्वारा प्रदान किए गए विभिन्न वर्गों जैसे साइनऑनरक्वेट, वित्तीय संस्थान], StatementTransactionRequest . का उपयोग करके प्रासंगिक गुण असाइन करें
3. सहेजें विधि में पैरामीटर के रूप में OfxVersionEnum से क्रमशः xml और sgml फ़ाइलों के लिए ofxVersion V2x या V1x का उपयोग करें।
4. लक्ष्य फ़ाइल और ofxVersion प्रदान करके सेव विधि को कॉल करें।

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="निर्माण आवश्यकता" %}}
OFX फ़ाइल निर्माण का अनुरोध करने के लिए आगे बढ़ने के लिए, सुनिश्चित करें कि आपके पास निम्नलिखित पूर्वापेक्षाएँ हैं। 
- माइक्रोसॉफ्ट विंडोज या लिनक्स आधारित ओएस।- Python 3.5 या बाद का।- आपके प्रोजेक्ट में संदर्भित Python के लिए Aspose.Finance।{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="OFX फ़ाइल निर्माण का अनुरोध करने के लिए Python कोड" offSpacer="" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-request-files.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="अन्य निर्माण विकल्प" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/ofx-response/" name="OFX प्रतिक्रिया फ़ाइल" description="1.03 या 2.2 प्रारूप" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/xbrl/" name="XBRL फ़ाइल" description="एक्स्टेंसिबल बिजनेस रिपोर्टिंग लैंग्वेज" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}