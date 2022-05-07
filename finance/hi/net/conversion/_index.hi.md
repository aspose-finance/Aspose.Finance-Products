---
title: वित्तीय रिपोर्ट को .NET के माध्यम से रूपांतरित करें
url: /hi/net/conversion/
description:  वित्तीय रिपोर्ट को XBRL, iXBRL और OFX फ़ाइल प्रारूपों में .NET पुस्तकालय के माध्यम से परिवर्तित करने के लिए C# कोड।
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="वित्तीय रिपोर्ट फ़ाइलों को C# के माध्यम से रूपांतरित करें" h2="वित्तीय रिपोर्ट XBRL, iXBRL और OFX फ़ाइल सहित रूपांतरण को 1.03 से 2.2 प्रारूप में .NET आधारित अनुप्रयोगों में प्रारूपित करती है।" >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) एक समृद्ध, एक्स्टेंसिबल और उपयोग में आसान API सुविधा है। डेवलपर्स आसानी से XBRL इंस्टेंस, लिंकबेस और टैक्सोनॉमी स्कीमा का उपयोग करके मान्य कर सकते हैं [मान्य () विधि](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) जो विनिर्देश में लगाए गए सिंटैक्स आवश्यकताओं का पालन करना चाहिए। इसके अलावा, वे XBRL, iXBRL प्रारूप पढ़ सकते हैं और साथ ही शुरू से XBRL उदाहरण बना सकते हैं। इसके अलावा, वे **XBRL प्रारूप** को iXBRL और माइक्रोसॉफ्ट एक्सेल एक्सएलएसएक्स फाइलों में बदल सकते हैं। API ओपन फाइनेंशियल एक्सचेंज (OFX) प्रारूप अनुरोध / प्रतिक्रिया निर्माण का भी समर्थन करता है और OFX फ़ाइल अनुरोध / प्रतिक्रिया को 1.03 से 2.2 प्रारूप में परिवर्तित करता है।

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="OFX प्रतिक्रिया और अनुरोध फ़ाइलें कनवर्ट करें" %}}

API दो वर्ग प्रदान करके OFX अनुरोध और प्रतिक्रिया फ़ाइलें बनाने का समर्थन करता है। [OfxRequestदस्तावेज़](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) बनाने और लोड करने के लिए OFX अनुरोध फ़ाइलें 1.03 और 2.2 प्रारूप में और [OfxResponseDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) 1.03 और 2.2 प्रारूप में OFX प्रतिक्रिया फ़ाइलों के लिए। इसके अलावा, [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) सदस्यों की संख्या V1x जो कि 1.x संस्करण, sgml फ़ाइल स्वरूप और V2x 2.x संस्करण, xml फ़ाइल स्वरूप है। OfxRequestDocument वर्ग या OfxResponseDocument वर्ग की सहेजें विधि को कॉल करने के बाद, डेवलपर्स आसानी से 1.03 sgml फ़ाइल से 2.2 xml प्रारूप में कनवर्ट कर सकते हैं।


{{% blocks/products/pf/feature-page-code h3="C# रूपांतरित करने के लिए कोड OFX प्रतिसाद फ़ाइलें" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-response-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# कन्वर्ट करने के लिए कोड OFX फाइलों का अनुरोध करें" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-request-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="XBRL वित्तीय रिपोर्ट रूपांतरण" %}}

API XBRL फ़ाइलों को iXBRL और Microsoft® Excel XLSX प्रारूप में कनवर्ट करने का समर्थन करता है। रूपांतरण प्रक्रिया सरल है, सबसे पहले फ़ाइल को लोड करें [Xbrl दस्तावेज़ वर्ग](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument). उपयोग [सेवऑप्शन क्लास](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions) के लिये [प्रारूप सहेजें](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions/properties/saveformat), XbrlDocument Class के सेव मेथड में पैरामीटर के रूप में उपयोग किया जाना है। iXBLR फाइल में सेव करने के लिए, [SaveFormat.IXBRL](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveformat) का उपयोग किया जाएगा और XLSX प्रारूप में निर्यात करने के लिए, SaveFormat.XLSX का उपयोग किया जाएगा।

{{% blocks/products/pf/feature-page-code h3="C# निर्यात करने के लिए कोड XBRL से iXBRL" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-ixbrl.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# XBRL से XLSX रूपांतरण के लिए कोड" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-xlsx.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xbrl-to-ixbrl xbrl-to-xlsx" >}}