---
title: वित्तीय रिपोर्ट को Python के माध्यम से सत्यापित करें
url: /hi/python-net/validate/
description:  वित्तीय रिपोर्ट को XBRL और iXBRL फ़ाइलों में Python लाइब्रेरी के माध्यम से सत्यापित करने के लिए Python कोड।
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="वित्तीय रिपोर्टिंग फ़ाइलों को Python के माध्यम से सत्यापित करें" h2="Python आधारित अनुप्रयोगों में XBRL और iXBRL सहित वित्तीय रिपोर्ट प्रारूपों का सत्यापन।" >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance Python के लिए .NET के माध्यम से](https://products.aspose.com/finance/python-net/) एक सुविधा संपन्न, एक्स्टेंसिबल और उपयोग में आसान वित्तीय रिपोर्ट संसाधन API है। डेवलपर वित्तीय और व्यावसायिक समाधानों के लिए XBRL और iXBRL प्रारूपों को आसानी से लोड, मान्य, देख या बना सकते हैं। API XBRL और iXBRL फ़ाइलें लोड करने के लिए XbrlDocument वर्ग और InlineXbrlDocument वर्ग प्रदान करता है।
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="XBRL दस्तावेज़ सत्यापित करें" %}}

कई मामलों के लिए XBRL फ़ाइल के सत्यापन की आवश्यकता होती है, जैसे कि डेटा की सही संरचना और प्रारूप में जाँच करना। XBLR दस्तावेज़ों को मान्य करने के लिए, सबसे पहले XBRL फ़ाइल लोड करने के लिए XbrlDocument वर्ग का उपयोग करें। XbrlInstance वर्ग की मान्य विधि का उपयोग करने के लिए, सबसे पहले XbrlInstanceCollection को XbrlDocument ऑब्जेक्ट XbrlInstances के साथ प्रारंभ करें। सही त्रुटि कोड प्राप्त करने के लिए प्रत्येक XbrlInstance.ValidationErrors के माध्यम से पुनरावृति करें और कंसोल पर अनुकूलित त्रुटि संदेशों को प्रिंट करके या फ़ाइल के भीतर लिखकर तदनुसार कार्य करें।

{{% blocks/products/pf/feature-page-code h3="Python सत्यापित करने के लिए कोड XBRL फ़ाइल" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "validate-xbrl-instance-file.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="iXBRL दस्तावेज़ सत्यापित करें" %}}

iXLRB सत्यापन के लिए, इसे InlineXbrlDocument वर्ग के माध्यम से लोड करें और इसकी मान्य() विधि का उपयोग करें। ValidationErrorCode एन्यूमरेशन में, प्रत्येक सत्यापन नियम के लिए सत्यापन त्रुटि कोड परिभाषित किए जाते हैं। कुछ कोड हैं ContextPeriodNoStartTime, ContextPeriodNoEndTime, ContextPeriodStartAfterEnd, ContextInstantNoTime, ContextScenarioXbrlNamespace, ContextScenarioXbrlSubstitutionGroup आदि। डेवलपर्स डिबग कर सकते हैं और अंतिम उपयोगकर्ताओं के रूप में कोड प्रदर्शित कर सकते हैं या समस्या को हल करने के लिए दिशा दिखा सकते हैं।

{{% blocks/products/pf/feature-page-code h3="Python सत्यापित करने के लिए कोड iXBRL दस्तावेज़" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "validate-ixbrl-file.py" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Validate" >}}
{{< /blocks/products/pf/feature-page-wrap >}}