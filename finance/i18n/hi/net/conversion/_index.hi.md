---
title: कन्वर्ट वित्तीय रिपोर्ट के माध्यम से .NET
url: /hi/net/conversion/
description:  C# कोड कन्वर्ट करने के लिए वित्तीय रिपोर्ट में XBRL, iXBRL और OFX फ़ाइल fomats के माध्यम से .NET पुस्तकालय है।
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="कन्वर्ट वित्तीय रिपोर्ट फ़ाइलें के माध्यम से C#" h2="वित्तीय रिपोर्ट प्रारूपों रूपांतरण सहित XBRL, iXBRL और OFX 1.03 करने के लिए 2.2 से फ़ाइल प्रारूप भीतर .NET आधारित अनुप्रयोगों." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) एक सुविधा अमीर है, एक्स्टेंसिबल और प्रयोग करने में आसान API. आसानी से कर सकते हैं डेवलपर्स validate XBRL उदाहरणों, linkbases और वर्गीकरण विज्ञान स्कीमा का उपयोग [Validate () विधि](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) सिंटेक्स के आवश्यकताओं के साथ पालन करना चाहिए कि विशिष्टता में लगाया. इसके अलावा, वे पढ़ सकते हैं XBRL, iXBRL प्रारूपों के रूप में के रूप में अच्छी तरह से बनाने XBRL खरोंच से उदाहरण है। इसके अलावा, वे कर सकते हैं ** कन्वर्ट XBRL प्रारूप करने के लिए ** iXBRL और माइक्रोसॉफ्ट एक्सेल XLSX files. API भी खुले वित्तीय विनिमय का समर्थन करता है (OFX) प्रारूप अनुरोध/प्रतिक्रिया निर्माण और धर्मान्तरित OFX फ़ाइल अनुरोध/1.03 करने के लिए 2.2 प्रारूप से प्रतिक्रिया.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="कन्वर्ट OFX प्रतिक्रिया और अनुरोध फ़ाइलें" %}}

API बनाने का समर्थन करता है OFX अनुरोध और प्रतिक्रिया फ़ाइलें उपलब्ध कराने के द्वारा दो वर्गों. [OfxRequestDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) बनाने के लिए और लोड हो रहा है OFX अनुरोध में 1.03 और 2.2 प्रारूप फ़ाइलें और [OfxResponseDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) के लिए OFX प्रतिक्रिया में 1.03 और 2.2 प्रारूप फ़ाइलें. इसके अलावा, [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) गणना होने सदस्यों V1x है कि 1.x संस्करण, sgml फ़ाइल प्रारूप और V2x 2.x संस्करण, xml फ़ाइल प्रारूप. के बाद बुला बचाने के OfxRequestDocument वर्ग या OfxResponseDocument वर्ग की विधि, डेवलपर्स से कन्वर्ट आसानी से कर सकते हैं 1.03 sgml फ़ाइल 2.2 एक्सएमएल प्रारूप करने के लिए.


{{% blocks/products/pf/feature-page-code h3="C# कन्वर्ट करने के लिए कोड OFX प्रतिक्रिया फ़ाइलें" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-response-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# कन्वर्ट करने के लिए कोड OFX अनुरोध फ़ाइलें" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-request-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="XBRL वित्तीय रिपोर्ट रूपांतरण" %}}

API का समर्थन करता है परिवर्तित XBRL फ़ाइलों को iXBRL और माइक्रोसॉफ्ट®एक्सेल XLSX प्रारूप. रूपांतरण प्रक्रिया सरल है, सबसे पहले लोड फ़ाइल के माध्यम से [XbrlDocument वर्ग](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument)है। का उपयोग [SaveOptions वर्ग](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions) के लिए [SaveFormat](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions/properties/saveformat), रूप में इस्तेमाल किया जा करने के लिए पैरामीटर बचाने में XbrlDocument वर्ग की विधि है। IXBLR में बचत के लिए फ़ाइल, [SaveFormat.IXBRL](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveformat) के लिए इस्तेमाल किया जाएगा और निर्यात में XLSX प्रारूप, SaveFormat.XLSX प्रयोग किया जायेगा.

{{% blocks/products/pf/feature-page-code h3="C# निर्यात करने के लिए कोड XBRL करने के लिए iXBRL" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-ixbrl.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# कोड के लिए XBRL XLSX रूपांतरण करने के लिए" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-xlsx.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xbrl-to-ixbrl xbrl-to-xlsx" >}}