---
title: Python के माध्यम से वित्तीय रिपोर्ट बनाएं
url: /hi/python-net/create/
description:  Python कोड XBRL में वित्तीय रिपोर्ट बनाने के लिए, और OFX Python लाइब्रेरी के माध्यम से अनुरोध या प्रतिक्रिया फ़ाइलें।
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Python के माध्यम से वित्तीय रिपोर्टिंग फ़ाइलें बनाएं" h2="वित्तीय रिपोर्ट Python आधारित अनुप्रयोगों के भीतर 1.03 या 2.2 प्रारूप में XBRL और OFX अनुरोध या प्रतिक्रिया फ़ाइल सहित निर्माण प्रारूपित करती है।" >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance Python के लिए .NET के माध्यम से](https://products.aspose.com/finance/python-net/) एक सुविधा संपन्न, एक्स्टेंसिबल और उपयोग में आसान वित्तीय रिपोर्ट निर्माण और संसाधन API है। डेवलपर्स आसानी से खरोंच से XBRL उदाहरण बना सकते हैं और साथ ही स्कीमा संदर्भ, संदर्भ, इकाई, आइटम, फुटनोट लिंक, भूमिका संदर्भ और जोड़ सकते हैं 
चाप भूमिका संदर्भ। API प्रत्येक सुविधा के लिए प्रासंगिक वर्ग प्रदान करता है जैसे संदर्भ के लिए, डेवलपर्स ContextPeriod, ContextEntity और Context का उपयोग कर सकते हैं। 
इसके अलावा, API 1.03 या 2.2 प्रारूप में खुले वित्तीय विनिमय (OFX) प्रारूप अनुरोध / प्रतिक्रिया निर्माण का भी समर्थन करता है।

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="आइटम जोड़कर XBRL फ़ाइल बनाएं" %}}

दस्तावेज़ में XBRL फ़ाइल बनाने और आइटम जोड़ने के लिए, प्रक्रिया है, XbrlDocument क्लास इंस्टेंस बनाएं। उपयुक्त API वर्गों जैसे कि SchemaRef वर्ग, प्रासंगिक संदर्भ वर्ग, जैसा कि ऊपर उल्लेख किया गया है और संकल्पना वर्ग का उपयोग करके आइटम के लिए प्रासंगिक सेटिंग्स तैयार करें। अंत में आइटम वर्ग के गुणों को परिभाषित और प्रारंभ करें और साथ ही डिस्क में XBRL फ़ाइल बनाने के लिए सेव विधि को कॉल करें।

{{% blocks/products/pf/feature-page-code h3="Python कोड बनाने के लिए XBRL आइटम जोड़कर फ़ाइल करें" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-xbrl-file-and-add-item.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="OFX अनुरोध और प्रतिक्रिया फ़ाइलें बनाएं" %}}


OFX फ़ाइलें बनाने के लिए, API OfxRequestDocument और OfxResponseDocument कक्षाएं प्रदान करता है और डेवलपर आसानी से कर सकते हैं [OFX अनुरोध बनाएं](https://products.aspose.com/finance/python-net/create/ofx-request/) और प्रतिक्रिया फ़ाइलें 1.03 और 2.2 दोनों स्वरूपों में। OfxRequestDocument गुणों को आरंभ करने के लिए, API अन्य वर्ग भी प्रदान करता है जैसे कि SignonRequest, FinancialInstitute और StatementTransactionRequest कक्षाएं। इसी तरह, OfxResponseDocument गुणों को आरंभ करने के लिए, API सहायक वर्ग प्रदान करता है जैसे कि SignonResponse, StatementTransactionResponse और StatementTransaction। प्रासंगिक उपयुक्त वर्गों के उपयोग के साथ दोनों मामलों के लिए कोड स्निपेट नीचे दिए गए हैं।

{{% blocks/products/pf/feature-page-code h3="Python कोड जेनरेट करने के लिए OFX दस्तावेज़ों का अनुरोध करें" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-response-files.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Python कोड उत्पन्न करने के लिए OFX प्रतिक्रिया दस्तावेज़" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-response-files.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
{{< /blocks/products/pf/feature-page-wrap >}}