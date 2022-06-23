---
title: .NET के माध्यम से वित्तीय रिपोर्ट बनाएं
url: /hi/net/create/
description:  C# कोड XBRL में वित्तीय रिपोर्ट बनाने के लिए, और OFX .NET लाइब्रेरी के माध्यम से अनुरोध या प्रतिक्रिया फ़ाइलें।
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# के माध्यम से वित्तीय रिपोर्टिंग फ़ाइलें बनाएं" h2="वित्तीय रिपोर्ट .NET आधारित अनुप्रयोगों के भीतर 1.03 या 2.2 प्रारूप में XBRL और OFX अनुरोध या प्रतिक्रिया फ़ाइल सहित निर्माण प्रारूपित करती है।" >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) एक सुविधा संपन्न, एक्स्टेंसिबल और उपयोग में आसान वित्तीय रिपोर्ट निर्माण और संसाधन API है। डेवलपर्स आसानी से खरोंच से XBRL उदाहरण बना सकते हैं और साथ ही स्कीमा संदर्भ, संदर्भ, इकाई, आइटम, फुटनोट लिंक, भूमिका संदर्भ और जोड़ सकते हैं 
चाप भूमिका संदर्भ। API प्रत्येक सुविधा के लिए प्रासंगिक वर्ग प्रदान करता है जैसे संदर्भ के लिए, डेवलपर्स उपयोग कर सकते हैं [प्रसंगअवधि](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextperiod), [प्रसंग इकाई](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextentity) तथा [संदर्भ](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/context). 
इसके अलावा, API 1.03 या 2.2 प्रारूप में खुले वित्तीय विनिमय (OFX) प्रारूप अनुरोध / प्रतिक्रिया निर्माण का भी समर्थन करता है।

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="आइटम जोड़कर XBRL फ़ाइल बनाएं" %}}

दस्तावेज़ में XBRL फ़ाइल बनाने और आइटम जोड़ने के लिए, प्रक्रिया है, create [XbrlDocument वर्ग](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) उदाहरण। उपयुक्त API वर्गों जैसे . का उपयोग करके आइटम के लिए प्रासंगिक सेटिंग तैयार करें [स्कीमारेफ वर्ग](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemaref)प्रासंगिक संदर्भ वर्ग जैसा कि ऊपर उल्लेख किया गया है और [अवधारणा वर्ग](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/concept). अंत में परिभाषित और प्रारंभ करें [आइटम वर्ग](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/item) संपत्तियों के साथ-साथ कॉल करें [विधि सहेजें](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) प्रति [बनाएं XBRL](https://products.aspose.com/finance/net/create/xbrl/) डिस्क में फ़ाइल।

{{% blocks/products/pf/feature-page-code h3="C# कोड बनाने के लिए XBRL आइटम जोड़कर फ़ाइल करें" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-item.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="OFX अनुरोध और प्रतिक्रिया फ़ाइलें बनाएं" %}}


OFX फ़ाइलें उत्पन्न करने के लिए, API प्रदान करता है [OfxRequestदस्तावेज़](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) तथा [OfxResponseDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) कक्षाएं और डेवलपर्स आसानी से कर सकते हैं [OFX अनुरोध बनाएं](https://products.aspose.com/finance/net/create/ofx-request/) और प्रतिक्रिया फ़ाइलें 1.03 और 2.2 दोनों स्वरूपों में। OfxRequestDocument गुण आरंभ करने के लिए, API अन्य वर्ग भी प्रदान करता है जैसे [साइनऑनअनुरोध](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonrequest), [वित्तीय संस्था](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/financialinstitution) तथा [स्टेटमेंट ट्रांजैक्शन रिक्वेस्ट](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionrequest) कक्षाएं। इसी तरह, OfxResponseDocument गुणों को आरंभ करने के लिए, API सहायक वर्ग प्रदान करता है जैसे [साइनऑन रिस्पांस](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse),  [वक्तव्य लेन-देन प्रतिक्रिया](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse) तथा [स्टेटमेंट ट्रांजैक्शन](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction). प्रासंगिक उपयुक्त वर्गों के उपयोग के साथ दोनों मामलों के लिए कोड स्निपेट नीचे दिए गए हैं।

{{% blocks/products/pf/feature-page-code h3="C# कोड जेनरेट करने के लिए OFX दस्तावेज़ों का अनुरोध करें" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# कोड उत्पन्न करने के लिए OFX प्रतिक्रिया दस्तावेज़" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}