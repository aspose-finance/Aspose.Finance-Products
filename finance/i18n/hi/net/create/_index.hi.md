---
title: बनाने वित्तीय रिपोर्ट के माध्यम से .NET
url: /hi/net/create/
description:  C# कोड बनाने के लिए वित्तीय रिपोर्ट में XBRL, और OFX अनुरोध या प्रतिक्रिया के माध्यम से फ़ाइलें .NET पुस्तकालय है।
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="बनाने वित्तीय रिपोर्टिंग फ़ाइलें के माध्यम से C#" h2="वित्तीय रिपोर्ट प्रारूपों निर्माण सहित XBRL और OFX अनुरोध या प्रतिक्रिया फ़ाइल में 1.03 या 2.2 भीतर प्रारूप .NET आधारित अनुप्रयोगों." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) एक सुविधा अमीर है, एक्स्टेंसिबल और प्रयोग करने में आसान वित्तीय रिपोर्ट निर्माण और प्रसंस्करण API. डेवलपर्स आसानी से कर सकते हैं XBRL खरोंच से उदाहरण के रूप में अच्छी तरह से संदर्भ स्कीमा जोड़ सकते हैं के रूप में, संदर्भ, इकाई, आइटम, फुटनोट लिंक, भूमिका संदर्भ और 
आर्क भूमिका संदर्भ है। API प्रासंगिक प्रदान करता कक्षा प्रत्येक सुविधा के लिए संदर्भ के लिए के रूप में, डेवलपर्स का उपयोग कर सकते हैं [ContextPeriod](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextperiod), [ContextEntity](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextentity) और [संदर्भ](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/context)है। 
इसके अलावा, API भी खुले वित्तीय विनिमय का समर्थन करता है (OFX) प्रारूप अनुरोध/प्रतिक्रिया निर्माण में 1.03 या 2.2 प्रारूप.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="बनाने XBRL फ़ाइल जोड़कर आइटम" %}}

बनाने के लिए XBRL फ़ाइल और जोड़ने आइटम दस्तावेज़ में, प्रक्रिया है, बनाने [XbrlDocument वर्ग](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) उदाहरण है। तैयार प्रासंगिक सेटिंग्स के लिए आइटम का उपयोग करके उपयुक्त API वर्गों के रूप में [SchemaRef वर्ग](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemaref), प्रासंगिक संदर्भ वर्गों के रूप में ऊपर उल्लेख किया और [अवधारणा वर्ग](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/concept)है। अंत में परिभाषित और intialize [आइटम कक्षा](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/item) गुण के रूप में के रूप में अच्छी तरह से कॉल के [बचाने विधि](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) करने के लिए [बनाने XBRL](https://products.aspose.com/finance/net/create/xbrl/) फ़ाइल में डिस्क है।

{{% blocks/products/pf/feature-page-code h3="C# कोड बनाने के लिए XBRL फ़ाइल जोड़कर आइटम" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-item.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="बनाने OFX अनुरोध और प्रतिक्रिया फ़ाइलें" %}}


पैदा करने के लिए OFX फ़ाइलें, API प्रदान करता [OfxRequestDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) और [OfxResponseDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) वर्गों और डेवलपर्स आसानी से कर सकते हैं [बनाने OFX अनुरोध](https://products.aspose.com/finance/net/create/ofx-request/) और प्रतिक्रिया दोनों 1.03 और 2.2 में फ़ाइलें प्रारूपों। के लिए शुरू करने में OfxRequestDocument गुण, API भी अन्य वर्गों प्रदान करता है के रूप में [SignonRequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonrequest), [FinancialInstitution](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/financialinstitution) और [StatementTransactionRequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionrequest) वर्गों. इसी तरह, intializing के लिए OfxResponseDocument गुण, API प्रदान करता सहायक वर्गों के रूप में [SignonResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse),  [StatementTransactionResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse) और [StatementTransaction](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction)है। नीचे कोड हैं स्निपेट्स के उपयोग के साथ दोनों ही मामलों के लिए प्रासंगिक उपयुक्त वर्गों.

{{% blocks/products/pf/feature-page-code h3="C# उत्पन्न करने के लिए कोड OFX अनुरोध दस्तावेजों" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# उत्पन्न करने के लिए कोड OFX प्रतिक्रिया दस्तावेजों" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}