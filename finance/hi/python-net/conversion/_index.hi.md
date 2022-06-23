---
title: वित्तीय रिपोर्ट को Python के माध्यम से रूपांतरित करें
url: /hi/python-net/conversion/
description:  वित्तीय रिपोर्ट को XBRL, iXBRL(इनलाइन xbrl) और OFX फ़ाइल फ़ोमैट में Python लाइब्रेरी के माध्यम से परिवर्तित करने के लिए Python कोड।
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="वित्तीय रिपोर्ट फ़ाइलों को Python के माध्यम से रूपांतरित करें" h2="वित्तीय रिपोर्ट XBRL, iXBRL और OFX फ़ाइल सहित रूपांतरण को 1.03 से 2.2 प्रारूप में Python आधारित अनुप्रयोगों में प्रारूपित करती है।" >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance Python के लिए .NET के माध्यम से](https://products.aspose.com/finance/python-net/) एक समृद्ध, एक्स्टेंसिबल और उपयोग में आसान API सुविधा है। डेवलपर्स आसानी से XBRL इंस्टेंस, लिंकबेस और टैक्सोनॉमी स्कीमा को मान्य () पद्धति का उपयोग करके मान्य कर सकते हैं, जो विनिर्देश में लगाए गए सिंटैक्स आवश्यकताओं का पालन करना चाहिए। इसके अलावा, वे XBRL, iXBRL स्वरूपों को पढ़ सकते हैं और साथ ही शुरुआत से XBRL उदाहरण बना सकते हैं। इसके अलावा, वे **XBRL प्रारूप** को iXBRL और माइक्रोसॉफ्ट एक्सेल एक्सएलएसएक्स फाइलों में बदल सकते हैं। API ओपन फाइनेंशियल एक्सचेंज (OFX) प्रारूप अनुरोध / प्रतिक्रिया निर्माण का भी समर्थन करता है और OFX फ़ाइल अनुरोध / प्रतिक्रिया को 1.03 से 2.2 प्रारूप में परिवर्तित करता है।

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="OFX प्रतिक्रिया और अनुरोध फ़ाइलें कनवर्ट करें" %}}

API दो वर्ग प्रदान करके OFX अनुरोध और प्रतिक्रिया फ़ाइलें बनाने का समर्थन करता है। 1.03 और 2.2 प्रारूप में OFX अनुरोध फ़ाइलें बनाने और लोड करने के लिए OfxRequestDocument और 1.03 और 2.2 प्रारूप में OFX प्रतिक्रिया फ़ाइलों के लिए OfxResponseDocument। इसके अलावा, OfxVersionEnum Enumeration के सदस्य V1x हैं जो 1.x संस्करण, sgml फ़ाइल स्वरूप और V2x 2.x संस्करण, xml फ़ाइल स्वरूप है। OfxRequestDocument वर्ग या OfxResponseDocument वर्ग की सेव विधि को कॉल करने के बाद, डेवलपर्स आसानी से 1.03 sgml फ़ाइल से 2.2 xml प्रारूप में कनवर्ट कर सकते हैं।


{{% blocks/products/pf/feature-page-code h3="C# रूपांतरित करने के लिए कोड OFX प्रतिसाद फ़ाइलें" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-ofx-response-from-1.03-to-2.2.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# कन्वर्ट करने के लिए कोड OFX फाइलों का अनुरोध करें" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-ofx-request-from-1.03-to-2.2.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="XBRL वित्तीय रिपोर्ट रूपांतरण" %}}

API XBRL फ़ाइलों को iXBRL और Microsoft® Excel XLSX प्रारूप में कनवर्ट करने का समर्थन करता है। रूपांतरण प्रक्रिया सरल है, सबसे पहले फ़ाइल को XbrlDocument Class के माध्यम से लोड करें। XbrlDocument क्लास की सेव विधि में पैरामीटर के रूप में उपयोग करने के लिए, SaveFormat के लिए SaveOptions क्लास का उपयोग करें। iXBLR फाइल में सेव करने के लिए SaveFormat.IXBRL का इस्तेमाल किया जाएगा और XLSX फॉर्मेट में एक्सपोर्ट करने के लिए SaveFormat.XLSX का इस्तेमाल किया जाएगा।

{{% blocks/products/pf/feature-page-code h3="Python निर्यात करने के लिए कोड XBRL से iXBRL" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-xbrl-to-ixbrl.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Python XBRL से XLSX रूपांतरण के लिए कोड" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-xbrl-to-xlsx.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xbrl-to-ixbrl xbrl-to-xlsx" >}}